---
layout: page
<!--type: cheat_sheet-->
title: Data documentation during the project
search_exclude: false
contributors: [Svein Høier, Ida Juhasz, Jenny Ostrop]
page_id: support_06_document
description: Supporting DMP Information, data collection, data creation, data generation, data production
sidebar: dmp_supporting_info
dsw:
- name: Responsibilities and resources
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=b1df3c74-0b1f-4574-81c4-4cc2d780c1af
cessda:
- name: Documentation and metadata
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata
rdmkit:
- name: Documentation and metadata
  url: https://rdmkit.elixir-europe.org/metadata_management
turing:
- name: Documentation and Metadata
  url: https://book.the-turing-way.org/reproducible-research/rdm/rdm-metadata
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> Understanding, analysing and reusing data depends on how said data has been documented, structured, named and in other ways described\\
>> The inclusion of metadata, providing data about the data used in a project, secures that data can be properly utilized, both within and beyond your own project\\
>> Interpretation of project results requires an understanding of the data provenance/data lineage, i.e. where the data originates from and how it has been processed\\
>> Data documentation should start as early as possible, and in the form of accompanied structured metadata, ensures that data is accessible\\
" %}

## About this chapter

This chapter includes information about how metadata and other accompanying information will be handled in the active phase of the project. 

## Question-specific guidance

### How will you link data and metadata?
Metadata is data about data, providing the necessary context that allows to understand or use data. Providing this information in a structured way facilitates data reuse. Metadata can be descriptive (e.g. title, data content, date of creation), structural (e.g. explaining file organisation), give information about data provenance (e.g. data origin, versions), administrative (e.g. access permissions), legal (e.g. data license), or technical (e.g. data format, tools and software). A metadata standard is a predefined way of describing data.

Often there will be multiple ways in which data and metadata can be linked within a project. Basic descriptive techniques will be relevant to many projects: these include structured and consistent naming of files and folders, using a  README-file to provide information, using embedded metadata in files, or using a separate metadata-file (a sidecar file for each file in the dataset). More advanced techniques that may be relevant include using a database system for linking metadata and data, or establishing a data/variable dictionary for the data in the project.

Please consult the chapters in e.g. the [RDMkit for life sciences, the CESSDA Data Management Guide, or The Turing Way handbook for more information, e.g. on what to write in a README-file](/pages/support_06_document#further-resources).

_Supplementary info: Almost all computer systems will provide some system metadata embedded in files, and provide info on creation date and who has editor or read-only access to the file, for example. Most systems will also provide users with possibilities of adding user metadata that can be embedded in files, such as descriptive tags._


### Do suitable metadata standards exist for your data?
When planning and embarking on your project, you should familiarize yourself with, and choose, a suitable metadata standard, if one exists. Many research fields have established a metadata standard that are adapted to discipline-specific needs and are widely adopted the field. If available, applying a domain-specific standard ensures that all necessary information to facilitate data use and reuse are included. In addition to domain-specific standards, domain-agnostic standard exist. "Minimal Information Standard" describes a defined minimal set of metadata, while a metadata standard also can include optional values.

Most repositories for research data will implement specific standards and therefore planned use of an archive will often lead to planned use of a metadata standards.\
"Minimal Information Standards" can be important from the [FAIRsharing registry of standards](http://fairsharing.org/).

Further resources:
* [RDA metadata standards catalog](https://rdamsc.bath.ac.uk/)
* [Digital Curation Centre: Metadata standards by discipline](https://www.dcc.ac.uk/guidance/standards/metadata)

_Supplementary info: When unsure about relevant metadata standards within your field, the Dublin Core standard defines a minimum set of values and is embedded in many more comprehensive standards._


### Will you use existing vocabularies/ontologies/terminologies to describe your data?
Please consider what controlled vocabularies, ontologies or terminologies have relevance within your field of research, and apply these to heighten precision when describing research data. Specifying the applied vocabularies/ontologies/terminologies in the metadata or data documentation is important to avoid ambiguity.

Vocabularies/ontologies/terminologies can be important from the [FAIRsharing registry of standards](http://fairsharing.org/).

For some disciplines, lookup services to identify relevant vocabularies/ontologies/terminologies exist. When in doubt of relevance, please look for usage by others within your field, like in published published journal articles or connected to published datasets.
* [Linked Open Vocabularies (LOV)](https://lov.linkeddata.es/dataset/lov/)
* [EMBL-EBI Ontology Lookup Service (OLS)](https://www.ebi.ac.uk/ols4/index)
* [CESSDA and service providers: European Language Social Science Thesaurus (ELSST)](https://elsst.cessda.eu)

Further reading:
* [RDMkit: How do you find appropriate vocabularies or ontologies?](https://rdmkit.elixir-europe.org/metadata_management#how-do-you-find-appropriate-vocabularies-or-ontologies)
* [FAIRCookbook: Introduction to terminologies and ontologies](https://w3id.org/faircookbook/FCB019)
* [FAIRCookbook: Introduction to terminologies and ontologies](https://w3id.org/faircookbook/FCB004)
* [FAIRCookbook: Selecting an ontology lookup service](https://w3id.org/faircookbook/FCB004)


### How are the rights of the collected data distributed?
Discuss making agreements regarding usage rights and potential intellectual property rights prior to data collection. Defining rights and providing licenses to collected data will often reduce the potential for later conflicts around internal and external use (and reuse) of research data within and after the project period.

Not all data are covered by The Copyright Act, and some data may be in the form of databases, and may qualify for protection. If the data counts as databases, the institutions will often hold rights to the database, this does not however exclude usage rights by the researchers. 

If intellectual property rights are defined through a contract/agreement, make sure to refer to it in relation to the involved organisations in the chapter 'Legal and ethical aspects'.

If the data is owned by or copyrighted by external bodies select this one and elaborate in the follow up question, and the next question on "use restrictions".\
Please note that there is no Fair-use clause in the Norwegian copyright act, subsequently usage of data from secondary sources would place restriction on future sharing. This can be described in the section "Preserving and publishing data"

If there is a consortium agreement or rights are arranged in another way, please make sure to list any relevant contracts or agreements.


### Are there any use restrictions for these data?
Are there any limitations on the data use such as restricting use to research on certain types of diseases, sharing only within certain geographical boundaries, etc.?\
If applicable, describing data use in a formalised way greatly improves the data reusability. Explicitly stating usage permissions or restrictions is recommended over applying a restrictive data license. Data licenses are addressed in the next question.

Examples of use definition:
* [Data Use Ontology (DUO)](https://github.com/EBISPOT/DUO#readme) is an international standard, which provides codes to represent data use restrictions for controlled access datasets
* [Open Digital Rights Language (ODRL)](https://www.w3.org/TR/odrl-vocab/) is a policy expression language

Further reading:
* [FAIRCookbook: Permitted uses of data](https://w3id.org/faircookbook/FCB035)
* Article: Alter, G., Gonzalez-Beltran, A., Ohno-Machado, L., & Rocca-Serra, P. (2020). The Data Tags Suite (DATS) model for discovering data access and use requirements. GigaScience, 9(2), giz165. [doi: 10.1093/gigascience/giz165](https://doi.org/10.1093/gigascience/giz165)


### Will a license be assigned to your data as early as possible? 
It is not always clear to everyone in the project (and outside) what can and can not be done with a data set. Being clear about reuse conditions and assigning data a license is one requirement of the FAIR principles.

It is helpful to associate each data set with a license as early as possible in the project and the license should be stored together with the data all the time. A data license should ideally be as free as possible: any restriction like 'only for non-commercial use' or 'attribution required' may have undesired implications, reduce the reusability and thereby the number of citations. If possible, use a computer-readable and computer actionable license.

_Supplementary info: attribution requirements can lead to inconvenient [license stacking](https://mozillascience.github.io/open-data-primers/5.3-license-stacking.html "2024-10-12") and thus limiting reuse. Similarly, restricting commercial use can have unintended consequences._

Further reading:
* [RDMkit: Licensing](https://rdmkit.elixir-europe.org/licensing)
* [CESSDA DMEG: Licensing your data](https://dmeg.cessda.eu/Data-Management-Expert-Guide/6.-Archive-Publish/Publishing-with-CESSDA-archives/Licensing-your-data)
* [OpenAIRE: How do I license my research?](https://www.openaire.eu/how-do-i-license-my-research-data)
* [Figshare: On choosing licenses](https://help.figshare.com/article/what-is-the-most-appropriate-licence-for-my-research)
* [ELIXIR-BE RDM: Data licences](https://rdm.elixir-belgium.org/data_licences)