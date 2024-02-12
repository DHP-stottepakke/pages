---
layout: page
<!--type: cheat_sheet-->
title: Documentation and data quality
search_exclude: false
contributors: [Svein Høier, Lisbeth Jahren]
page_id: 2_documentation_quality
description: Data documentation, metadata, data quality
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

<!--Science Europe question ID & title-->
## 2a - What metadata and documentation (for example the methodology of data collection and way of organising data) will accompany data?

<!--key information-->
### [Science Europe Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862")[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 2a.1\
Indicate which metadata will be provided to help others identify and discover the data.

both in the active phase and when preparing the data for archiving/publishing.

> 2a.2\
Indicate which metadata standards (for example DDI, TEI, EML, MARC, CMDI) will be used.

> 2a.3\
Use community metadata standards where these are in place.

when archiving/publishing the data.

> 2a.4\
Indicate how the data will be organised during the project, mentioning for example conventions, version control, and folder structures. Consistent, well-ordered research data will be easier to find, understand, and re-use.

in the active phase of research

> 2a.5\
Consider what other documentation is needed to enable re-use. This may include information on the methodology used to collect the data, analytical and procedural information, definitions of variables, units of measurement, and so on.

both in the active phase of research and when preparing the data for archiving/publishing.

> 2a.6\
Consider how this information will be captured and where it will be recorded (for example in a database with links to each item, a ‘readme’ text file, file headers, code books, or lab notebooks).

in the active phase of research.

```
**Relevant PID**
- Metadata standard 

**Interested stakeholder**
- Level 2: Possibly core facility, library staff

**Relevant project phase**
- planning post-award, active phase
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dataset]
- [#metadata_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#metadata_tree): nested, see below

[Properties in metadata]
- [#properties-in-metadata](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#properties-in-metadata): description, language, metadata_standard_id (identifier, type)
- [#metadata_standard_id_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#metadata_standard_id_tree): nested, see below

[Properties in metadata_standard_id]
- [#properties-in-metadata_standard_id](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#properties-in-metadata_standard_id): identifer, type

---
<!--additional explanations-->
### Explanations for support staff
- Identifying domain-specific archives. Generic archive properties.
- Metadata standards. Data findability.
- Data organization, version control.
- Data documentation, domain conventions. 
- Specific software: domain-specific, ELN
- Useful resources, generic and domain-specific.

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Documentation, metadata, and data quality]
- What metadata will be used to help others identify and discover the data?
- What metadata standards will be used? Examples could be DDI, TEI, MARC, CMDI.
- How will data be organized throughout the project? This can be version control, file structure, conventions for file naming, etc.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[2.1 Making data findable, including provisions for metadata]
- Will data be identified by a persistent identifier?
- Will rich metadata be provided to allow discovery? What metadata will be created? What disciplinary or general standards will be followed? In case metadata standards do not exist in your discipline, please outline what type of metadata will be created and how

[2.2 Making data accessible - Metadata]
- Will documentation or reference about any software be needed to access or read the data be included? Will it be possible to include the relevant software (e.g. in open source code)?

[2.3 Making data interoperable]
- What data and metadata vocabularies, standards, formats or methodologies will you follow to make your data interoperable to allow data exchange and re-use within and across disciplines? Will you follow community-endorsed interoperability best practices? Which ones? 
- In case it is unavoidable that you use uncommon or generate project specific ontologies or vocabularies, will you provide mappings to more commonly used ontologies? Will you openly publish the generated ontologies or vocabularies to allow reusing, refining or extending them?

[2.4 Increase data re-use]
- How will you provide documentation needed to validate data analysis and facilitate data re-use (e.g. readme files with information on methodology, codebooks, data cleaning, analyses, variable definitions, units of measurement, etc.)?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

##### Guidance for Researchers
- With respect to the metadata standards: Find a suitable community- endorsed metadata standard in metadata registries (e.g., RDA, DCC). Preferably use domain and discipline- specific repositories to deposit your data in when using community- endorsed metadata standards (use Re3data to find a suitable repository). 
- Confer with your local research data management specialist to determine the best metadata standard to use when no community-endorsed metadata standards are developed in your domain. 
- Use controlled vocabularies for your metadata (and other documentation) to create unambiguous, reusable, and machine-interpretable information. Choose your vocabulary based on community standards and information you have on the use and openness. When available in your domain, choose a repository to deposit your data in based on whether they support your preferred vocabulary (find a suitable repository on FAIRsharing).

##### Sufficiently adressed
- Clearly outlines the metadata that will accompany the data, with reference to good practice in the scientific community (for example uses metadata standards where they exist). 
- Clearly outlines the documentation needed to enable data re-use, stating where the information will be recorded (for example a database with links to each item, a ‘readme’ text file, file headers, code books, or lab notebooks). 
- Indicates how the data will be organised during the project (for example naming conventions, version control strategy and folder structures).

---
<!--additional explanations - only keywords-->
### Explanations for users
- Metadata standard mostly defined by archive, how to identify archive
- Data organization in active phase
- Data documentation

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
How will you document your data in order to make the data findable, accessible, interoperable and re-usable for you and others? What kind of metadata standards, README files or other documentation will you use to help others to understand and use your data?
Data documentation enables data sets and files to be discovered, used and properly cited by other users (human or computer). Without sufficient documentation the data cannot be reused.
Documentation includes essential information regarding the data, for example a) core metadata (for discovery and identification) where, when, why and how the data were collected as well as b) descriptive information how the data is interpreted correctly using metadata standards, vocabularies and e.g. readme-files. 

Tips for best practices
- Describe all the types of documentation (README files, metadata standards, vocabularies etc.) you will provide to help secondary users to understand and reuse your data. Repositories often require the use of a specific metadata standard. Check whether a discipline-specific metadata schema or standard exists that can be adopted.
- Consider how the data will be organised during the project. Describe, for example, your file-naming conventions, version control and folder structure.
- Use research instruments, which create standardised metadata formats automatically.
- Identify the types of information that should be captured to enable other researchers to discover, access, interpret, use and cite your data. See for example Qvain requirements (https://www.fairdata.fi/en/user-guides/qvain-user-guide/#QvainDataset)

#### [NTNU - DMP guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
What information is necessary for future users (including your future self) to find and understand the data? 
Tip: Read Making a Research Project Understandable: Guide for data documentation (Fuchs & Kuusniemi 2018).

Documentation might for instance include details on the methodology used, lab protocols, codebook, analytical and procedural information, definitions of variables, vocabularies, units of measurement, any assumptions made, and the format and file type of the data. Consider how you will capture this information and where it will be recorded (for instance in a ReadMe-file when you archive your data). Wherever possible you should identify and use existing community standards.
 
Metadata is often defined as “data about data”, and metadata standards are standardized ways of describing data. For more information about metadata and metadata standards, visit the website How to FAIR > Metadata. You could also see the RDA Metadata standards catalog to look for metadata standards for your field or data type.
 
A common metadata standard is Dublin Core, which is a list of 15 standardized elements describing a digital resource. Often, research data repositories (archives) will use some version of Dublin Core when describing datasets. An example is the NTNU institutional archive, NTNU Open Research Data.
 
Also indicate how the data will be organised during the project, mentioning for example conventions, version control, and folder structures. Consistent, well-ordered research data will be easier to find, understand, and re-use.

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
How will the data be documented so that they are comprehensible and reusable for yourself and others also in the long term?
(According to best practice, research data should be documented in a ReadMe file which explains column headings, abbreviations etc.)

What kind of metadata standard(s) will be used?
(Both open and restricted data have to be provided with metadata according to section 4.6 in the UiT guidelines. Some academic fields have established metadata standards, whereas other fields do not. Examine best practice in your field. See this page for an overview of established metadata standards.)

What standards and methods will be used for data collection/generating?

What is the expected file size for the data?

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Will the project use any established terminologies, ontologies, standards, or similar, to describe and document the material? Which ones? If you create your own terminology, will it be mapped against established terminologies?
Why is this important? Many scientific disciplines have established terminologies, ontologies, and vocabularies (e.g. MeSH, ISCED, AAT, and ELSST) that can be used to categorize and document data materials. There are various standards that are recommended to follow (e.g. ISO 8601 for date, time, and time intervals). The use of standards and established terminologies simplifies the communication between people who belong to the same scientific field but can also make it easier to find material in, for example, journals. Sometimes, it may be necessary to create project-specific terminology lists if the existing ones aren’t sufficient or suited for the project. If you create a project-specific list, you should do a mapping, where you show which terms that mean exactly or almost the same thing as in other lists, but also which terms that are unique for your list. Mapping terms against other terminologies will improve the findability of the data material.

#### [SIKT](https://sikt.no/en/data-management-plan)
Examples of measures to control and ensure data quality may be the use of standardized methods and protocols to capture observations; checking precision and calibration of instruments; quality-check equipment to be used for audio or video recording; make multiple measurements, observations or samples; use standardized interview protocols and/or computer-assisted software when conducting interviews; and using standardized and consistent procedures when digitizing or transcribing data.


-----
-----
<!--Science Europe question ID & title-->
## 2b - What data quality control measures will be used?

<!--key information-->
### [Science Europe Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862")[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 2b.1\
Explain how the consistency and quality of data collection will be controlled and documented. This may include processes such as calibration, repeated samples or measurements, standardised data capture, data entry validation, peer review of data, or representation with controlled vocabularies.

```
**Relevant PID**
not pid, but defined persitant standards for quality control relevant?
(established practices like calibration, signing by colleague, peer review etc.) 

**Interested stakeholder**
(not so much info here at this point in time)

**Relevant project phase**
- planning post-award, active phase
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dataset]
- [#dataset_quality_assurance_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_quality_assurance_tree): "Data Quality Assurance" [string, free text]

---
<!--additional explanations-->
### Explanations for support staff
Researchers might need help to present this explicit (might be self-explanatory to a researcher that one always calibrate an instrument for instance)?

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Documentation, metadata, and data quality]
- Is there other documentation necessary to facilitate reuse? It can be description of methodology, information about analysis and protocols, definitions of variables, electronic lab books, code books, readme.txt files, etc.
- How is reliability and quality of the data controlled and documented? This can include processes such as calibration of measuring instruments, repeated measurements and samples, standardized data capture, validation of data entry, peer review of data or use of controlled vocabulary.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[2.1 Making data findable, including provisions for metadata]
- Will search keywords be provided in the metadata to optimize the possibility for discovery and then potential re-use?
- Will metadata be offered in such a way that it can be harvested and indexed?

[2.2. Making data accessible - Metadata]
- Will metadata be made openly available and licenced under a public domain dedication CC0, as per the Grant Agreement? If not, please clarify why. Will metadata contain information to enable the user to access the data?

[2.4 Increase data-reuse]
- Describe all relevant data quality assurance processes

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

##### Guidance for Researchers
not covered

##### Sufficiently adressed
- Clearly describes the approach taken to ensure and document quality control in the collection of data during the lifetime of the project.

---
<!--additional explanations - only keywords-->
### Explanations for users
- Data quality measure examples

---
<!--recycling possible?-->
### Existing sources that can be reused
#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
How will you document your data in order to make the data findable, accessible, interoperable and re-usable for you and others? What kind of metadata standards, README files or other documentation will you use to help others to understand and use your data? 
 Data documentation enables data sets and files to be discovered, used and properly cited by other users (human or computer). Without sufficient documentation the data cannot be reused.
 Documentation includes essential information regarding the data, for example a) core metadata (for discovery and identification) where, when, why and how the data were collected as well as b) descriptive information how the data is interpreted correctly using metadata standards, vocabularies and e.g. readme-files. 
 
Tips for best practices
- Describe all the types of documentation (README files, metadata standards, vocabularies etc.) you will provide to help secondary users to understand and reuse your data. Repositories often require the use of a specific metadata standard. Check whether a discipline-specific metadata schema or standard exists that can be adopted.
- Consider how the data will be organised during the project. Describe, for example, your file-naming conventions, version control and folder structure.
- Use research instruments, which create standardised metadata formats automatically.
- Identify the types of information that should be captured to enable other researchers to discover, access, interpret, use and cite your data. See for example: [Qvain requirements](https://www.fairdata.fi/en/user-guides/qvain-user-guide/#QvainDataset)

#### [NTNU - DMP Guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
How will the consistency and quality of data collection be controlled and documented? 
 This may include processes such as calibration, repeated samples or measurements, 
 standardised data capture, data entry validation, peer review of data, or representation with controlled vocabularies.

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
When will the data be collected/generated?
Is there need for extra hardware or software?
Is there need for special expertise for collecting/generating data?

#### [SND - Checklist DMP](https://zenodo.org/records/6424769)[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) :
[Will the project use any established terminologies, ontologies, standards, or similar, to describe and document the material? Which ones? If you create your own terminology, will it be mapped against established terminologies?]\
Why is this important? Many scientific disciplines have established terminologies, ontologies, and vocabularies (e.g. MeSH, ISCED, AAT, and ELSST) that can be used to categorize and document data materials. There are various standards that are recommended to follow (e.g. ISO 8601 for date, time, and time intervals). The use of standards and established terminologies simplifies the communication between people who belong to the same scientific field but can also make it easier to find material in, for example, journals. Sometimes, it may be necessary to create project-specific terminology lists if the existing ones aren’t sufficient or suited for the project. If you create a project-specific list, you should do a mapping, where you show which terms that mean exactly or almost the same thing as in other lists, but also which terms that are unique for your list. Mapping terms against other terminologies will improve the findability of the data material.

#### [SIKT](https://sikt.no/en/data-management-plan)
Examples of measures to control and ensure data quality may be the use of standardized methods and protocols to capture observations; checking precision and calibration of instruments; quality-check equipment to be used for audio or video recording; make multiple measurements, observations or samples; use standardized interview protocols and/or computer-assisted software when conducting interviews; and using standardized and consistent procedures when digitizing or transcribing data.