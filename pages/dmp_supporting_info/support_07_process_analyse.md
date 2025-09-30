---
layout: page
<!--type: cheat_sheet-->
title: Processing, analysing and interpreting data
search_exclude: false
contributors: [Korbinian Bösl, Jenny Ostrop, Ingrid Heggland]
page_id: support_07_process_analyse
description: Supporting DMP Information, process data, data processing, analyse data, data analysis, analyze, analysis
sidebar: dmp_supporting_information
dsw:
- name: Processing, analysing and interpreting data
  uuid: knowledge-models/research.data.no:norway-generic:latest/preview?questionUuid=50f9d580-3e62-434b-81ff-86daed56aca8
cessda:
- name: Process
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process
rdmkit:
- name: Processing
  url: https://rdmkit.elixir-europe.org/processing
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

### Do you need a shared space with your collaborators to work on data analysis?
It might be worth to consider to have a shared work environment with collaborators to avoid the duplication of data, reduce data transfer issues and provide the same software to all project participants. If you are working with large datasets, bandwidth to compute infrastructure or data sources might become an issue. Also consider how critical the access to the workspace is for your project or whether you can tolerate data loss and downtime. It is often best to rely on professionals to operate the infrastructure, also to avoid straining project resources my infrastructure maintenance. Also consider how data is entering and leaving the environment. Sometimes the provisioning of the environment will require active application or will take time.

As work spaces usually will include some form of data storage, please add the work space to the [list of used storage solutions](/pages/support_04_store_protect#where-will-you-store-data-and-documents), including considerations on the aspects of information security. Then, you can add specific information on work spaces in this question.

Shared workspace examples (non-exhaustive):
* [High-Performance Computing (HPC) resources](https://www.sigma2.no/service/high-performance-computing) provided by Sigma2
* [NIRD Service Platform](https://www.sigma2.no/service/nird-service-platform) provided by Sigma2
* [NeLS - Norwegian e-infrastructure for Life Science](https://nels.bioinfo.no/) provided by ELIXIR-NO
* [educloud](https://research.educloud.no/) provided by UiO
* [NREC](https://docs.nrec.no/intro.html) operated by UiB and UiO
* [Openstack at NTNU](https://www.ntnu.no/wiki/spaces/skyhigh/pages/93261214/Openstack+at+NTNU)
* [TSD (sensitive data)](https://www.uio.no/tjenester/it/forskning/sensitiv/) provided by UiO
* [HUNT Cloud (sensitive data)](https://about.hdc.ntnu.no/) provided by NTNU
* [SAFE (sensitive data)](https://www.uib.no/en/foremployees/131011/safe) provided by UiB

#### Requirements for using the work space
Some resources may require you to apply for using the work space. Make sure to investigate requirements, and if applicable application deadlines, and the expected time frame to receive an answer.

Sigma2 issues calls for proposal twice a year. There is also a procedure to apply outside the regular call periods.
* [Applying for Sigma2 e-infrastructure resources, e.g. NIRD](https://www.sigma2.no/apply-e-infrastructure-resources)

### Do you need to plan compute solutions and capacity?
![Static Badge](https://img.shields.io/badge/Wizard-HPC-%238e44adff) *Specific to data/compute heavy projects*\
If you require a large amount of CPU hours, I/O bandwidth or memory it is best to try estimating this in advance and to choose a computing infrastructure upfront. The infrastructure might have restrictions, require application and/or payment, and might only be able to run certain software or workflow systems.

If you will use federated computing in you project this should be considered early on.

Further resources on federated data analysis:
* [DataShield](https://www.datashield.org/)


### Will the data be converted to other file format(s) before archiving?
In some cases data has to be converted to different formats late in the project for archiving. It is important to ensure that there is sufficient computing time and software for this task.

Archiving and working with data have different requirements. You want archived data to be in a **persistent file format** that others can open and read without being dependent on proprietary software, also in a number of years from now. When working actively with the data, you need to be able to process and analyse efficiently and e.g. using software-specific formats can be appropriate. If the two differ, you need to plan for conversions. Complicated (binary) file formats tend to change over time, and software may not stay compatible with older versions. Also, some formats (e.g. DOC, XLS) hamper long term usability by making use of patents or being hampered by restrictive licensing. Be aware that storing data in a persistent format is not only facilitating reuse by others, but also ensures their future internal use (e.g. when loosing access to commercial software).

Ideally a format should be simple, text only, completely described, not restricted by copyrights, and implemented in different software packages.

Resources on file formats and conversions:
* [CESSDA DMEG: File formats and data conversions](https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process/File-formats-and-data-conversion)
* [DataverseNO: Prepare your data - Preferred file formats](https://site.uit.no/dataverseno/deposit/prepare/#preferred-file-formats)


### Will data processing or analysis alter metadata or produce additional metadata?
If your processing and analysis software and workflow engines produce metadata about these steps, it is good practise to consider upfront how this metadata can be captured and archived.

Generally speaking, script-based data cleaning & analysis is easier to reproduce than manual steps for analysis of quantitative data. For analysis of qualitative data, code categories should be exclusive, consistent & documented.

Examples of information to be added to metadata (non-exhaustive):
* Parameters or data coding used during data analysis
* Using a given version of a reference dataset in data analysis


### Will data processing affect information security?
In some cases data processing will affect e.g. privacy and such data security. For example, it might not longer be possible to identify individuals from aggregated data. However, in some cases only the processed data, but not the raw data might allow easy access to [sensitive information](/pages/support_03_legal_ethics#will-sensitive-information-apart-from-special-category-personal-data-be-collectedprocessed).

Resources on data anonymisation:
* [CESSDA DMEG: Anonymisation](https://dmeg.cessda.eu/Data-Management-Expert-Guide/5.-Protect/Anonymisation)
* [Norwegian data protections agency: A guide to the anonymisation of personal data (2015)](https://www.datatilsynet.no/en/regulations-and-tools/reports-on-specific-subjects/anonymisation/)
* [Amnesia anonymisation tool by OpenAire](https://amnesia.openaire.eu/)


### Will you handle different versions of files or documents?
Being able to track versions of files or documents helps to understand the history of changes and why something was done in a specific way. This contributes to making data processing and analysis reproducible. Being able to review and possibly restore previous versions is another aspect, particularly in collaborative projects with simultaneous changes. Approaches to version control range from establishing routines e.g. for file naming to using version control systems such as git.

Version history and different sets of data might be especially important, if you are training AI-models with different datasets. You might want to consider to use [git-annex](https://git-annex.branchable.com/), [git-lfs](https://git-lfs.com/) or more specialized systems for this purpose for larger datasets.

Resources on version control:
* [RDMkit: Data organisation - How do you manage file versioning?](https://rdmkit.elixir-europe.org/data_organisation#how-do-you-manage-file-versioning)
* [The Turing Way: Version Control](https://the-turing-way.netlify.app/reproducible-research/vcs.html)
* [The Turing Way: Version Control for Data](https://the-turing-way.netlify.app/reproducible-research/vcs/vcs-data.html)
* [Software Carpentry: Version Control with Git](https://swcarpentry.github.io/git-novice/)


### Will you monitor data integrity once it has been collected?
It is important to ensure that the data in your project is not corrupted through [transfer problems](https://en.wikipedia.org/wiki/Data_corruption), [data degradation (bitrot)](https://en.wikipedia.org/wiki/Data_degradation), vandalism, or human error. This is particularly important if data is transferred between sites/machines, and in complex projects with several people involved. Is it clear what should be done if an error is detected?

Examples of procedures to monitor data quality:
* One common procedure to detect data changes is to calculate checksums (e.g. [SHA256](https://confluence.wipo.int/confluence/display/dascg/e.5.-+Generate+File+Checksum+for+uploading+to+DAS)) that can be stored and compare after transfers and time
* Repeating measurements on the same samples/objects
* In complex projects, it can be a good idea to define routines for if a

Further reading:
* [RDMkit: Data quality](https://rdmkit.elixir-europe.org/data_quality.html)
* [FAIRCookbook: How to create checksum files](https://faircookbook.elixir-europe.org/content/recipes/findability/checksum-create.html)


### Will you be integrating or linking data from different origins or different types of data?
If you are integrating data from different origins it might be necessary to unify the structure of the data. The most common structures for knowledge representation are: [flat files](https://en.wikipedia.org/wiki/Flat-file_database) (e.g. table formats including tsv, csv, ...), [tabular databases](https://en.wikipedia.org/wiki/Database) (including SQL) and [linked data](https://en.wikipedia.org/wiki/Linked_data). While the complexity of relations and knowledge that can be saved in these structures increases in this order, this might also require additional skills and effort.

If possible, it is recommended to use of a common ontology to integrate data from different sources.

Further reading:
* [FAIRCookbook: Interlinking data using mappings](https://w3id.org/faircookbook/FCB016)
* [Wikipedia: Linked data](https://en.wikipedia.org/wiki/Linked_data)


### Does your computational approach require validation of results?
![Static Badge](https://img.shields.io/badge/Wizard-HPC-%238e44adff) *Specific to data/compute heavy projects*\
In some cases the results of computational steps cannot be considered to be deterministic, for instance due to randomness in the calculation, human inputs and possible errors or differences in the execution across infrastructures. To reduce false findings, the computational steps should be validated in these cases.

There are surprisingly many complications that can cause (slight) inconsistencies between results when workflows are run on different compute infrastructures. A good way to make sure this does not occur is to run a subset of all jobs on all different infrastructure to check the consistency.

Validation of results without a golden standard is very hard. One way of doing it is to develop two solutions for a problem (two independent workflows or two independently developed tools) to check whether the results are identical or comparable.

Surrounding all tools in your data processing and analysis workflows with the 'boilerplate' code necessary on the computer system you are using is tedious and error prone. Especially if you are using the same tools in multiple different work flows and/or on multiple different computer architectures. Automated instrumentation, e.g. by using a workflow management system, can prevent many mistakes.

Running a small subset of the data repeatedly can be useful to catch unexpected problems that would otherwise be very hard to detect.
