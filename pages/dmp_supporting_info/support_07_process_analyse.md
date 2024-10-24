---
layout: page
<!--type: cheat_sheet-->
title: Processing, analysing and interpreting data
search_exclude: false
contributors: [Korbinian Bösl, Jenny Ostrop]
page_id: support_07_process_analyse
description: Supporting DMP Information, process data, data processing, analyse data, data analysis, analyze, analyzis
sidebar: dmp_supporting_info
dsw:
- name: Processing, analysing and interpreting data
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=50f9d580-3e62-434b-81ff-86daed56aca8
cessda:
- name: Process
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process
rdmkit:
- name: Data analysis
  url: https://rdmkit.elixir-europe.org/data_analysis
turing:
- name: Guide for Reproducible Research
  url: https://book.the-turing-way.org/reproducible-research/reproducible-research
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> What tools or infrastructure are needed for data processing and analysis?\\
>> Will data processing create additional metadata?\\
>> Do data formats need to be converted?\\
>> How will versions of files be managed?\\
" %}

## About this chapter
Data processing and analysis is a central element in the research process and part of the data lineage/provenance. This chapter collects information about tools and infrastructure used as well as asking to clarify steps that will be important for preparation of high-quality FAIR data.


## Question-specific guidance



#### Do you need a shared space with your collaborators to work on data analysis?
It might be worth to consider to have a short work environment with collaborators to avoid the duplication of data, reduce data transfer issues and provide the same software to all project participants. If you are working with large datasets, it bandwidth to compute infrastructure or data sources might become an issue. Also consider how critical the access to the workspace is for your project or whether you can tolerate data loss and downtime. It is often best to rely on professionals to operate the infrastructure, also to avoid straining project resources my infrastructure maintenance. Also consider how data is entering and leaving the environment. Sometimes the provisioning of the environment will require active application or will take time.
For the workspace you should follow similar [considerations as for storage is aspects of security](pages/support_04_store_protect).

#### Do you need to plan compute solutions and capacity?
This is mainly relevant for data and/or compute heavy projects. If you require a large amount of CPU hours, I/O bandwidth or memory it is best to try estimating this in advance and to choose a computing infrastructure upfront. The infrastructure might have restrictions, require application and/or payment, and might only be able to run certain software or workflow systems.

If you will use federated computing in you project this should be considered early on.


#### Will the data be converted to other file format(s) before archiving?
In some cases data has to be converted to different formats late in the project for archiving. It is important to ensure that there is sufficient computing time and software for this.  

#### Will data processing or analysis alter metadata or produce additional metadata?
If your processing and analysis software and workflow engines produce metadata about these steps, it is good practise to consider upfront how this metadata can be captured and archived.



#### Will you handle different versions of files and documents?
Version history and different set of data might be important in your project. This might be especially the case, if you are training AI-models with different datasets. You might want to consider to use [git-annex](https://git-annex.branchable.com/), [git-lfs](https://git-lfs.com/) or more specialized systems for this purpose for larger datasets.

#### Will you monitor data integrity once it has been collected?
It is important to ensure that the data in your project is not corrupted through [transfer problems](https://en.wikipedia.org/wiki/Data_corruption), [data degradation (bitrot)](https://en.wikipedia.org/wiki/Data_degradation), vandalism and manipulation. One common procedure to detect data changes is to calculate checksums (e.g. [SHA256](https://confluence.wipo.int/confluence/display/dascg/e.5.-+Generate+File+Checksum+for+uploading+to+DAS)) that can be stored and compare after transfers and time.
Another procedure might be to repeat measurements on the same samples/objects.

#### Will data processing affect information security?
In some cases data processing will affect e.g. privacy and such data security. For example, it might not longer be possible to identify individuals from aggregated data. However, in some cases only the processed data, but not the raw data might allow easy access to [sensitive information](pages/support_03_legal_ethics#will-sensitive-information-apart-from-special-category-personal-data-be-collectedprocessed).

#### Will you be integrating or linking data from different origins or different types of data?
When you are integration data from different origins it might be necessary to unify the structure of the data. The most common structures for knowledge representation are: [flat files](https://en.wikipedia.org/wiki/Flat-file_database) (e.g. table formats including tsv, csv, ...), [tabular databases](https://en.wikipedia.org/wiki/Database) (including SQL) and [linked data…](https://en.wikipedia.org/wiki/Linked_data)
While the complexity of relations and knowledge that can be saved in these structures increases in this order, this might also require additional skills and effort.

#### Does your computational approach require validation of results?
In some cases the results of computational steps cannot be considered to be deterministic, for instance due to randomness in the calculation, human inputs and possible errors or differences in the execution across infrastructures. To reduce false findings, the computational steps should be validated in these cases.
This might include:
* Improved workflow and software versioning systems to reduce human error
* Replicating results with different tools
* Repeating (parts of) the calculation on different computing infrastructure and architectures
* Repeating calculation steps (for parts of) the data
