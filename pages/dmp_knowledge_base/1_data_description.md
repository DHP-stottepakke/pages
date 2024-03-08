---
layout: page
<!--type: cheat_sheet-->
title: Data description and collection or re-use of existing data
search_exclude: false
contributors: [Jenny Ostrop, Leif Longva]
page_id: 1_data_description
description: Data description, Data types, Data reuse
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

<!--Science Europe question ID & title-->
## 1a - How will new data be collected or produced and/or how will existing data be re-used?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated

> 1a.1\
Explain which methodologies or software will be used if new data are collected or produced.

If data is or will be produced, the methodology should briefly be explained.

> 1a.2\
State any constraints on re-use of existing data if there are any.

If data is re-used, outline how data was chosen.\
Are there limitations to the re-use of existing data? (Examples: limiting license conditions, insufficient metadata)

> 1a.3\
Explain how data provenance will be documented.

Documenting data provencance (data lineage) is important both for produced and re-used data. Often, both information about origin of the data (methodology, instrument, date) and data processing steps are required to understand and interpret the data.

> 1a.4\
Briefly state the reasons if the re-use of any existing data sources has been considered but discarded.

Some existing data may be thought of as natural to re-use. If such data are decided not to be re-used, explaining why it is not re-used will be important information.

#### Science Europe DMP Evaluation Rubric: sufficiently addressed
- Gives clear details of where the existing data come from and how new data will be collected or produced. It clearly explains methods and software used.
- Explains, if existing data are re-used, how these data will be accessed and any constraints on their re-use.
- Explains clearly, if applicable, why new data must be collected, instead of re-using existing data.

```
**Relevant PID**
- PID of reused datasets

**Interested stakeholder**
- Level 3: Stakeholders interested in reuse of their research data
- Stakeholders interested in receiving data and later governance of data within their contexts (statistics database etc.)

**Relevant project phase**
- pre-award: outline
- planning post-award, active phase
```

#### Coverage in [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dataset]
- [#dataset_description_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_description_tree): "Description is a property in both Dataset and Distribution, in compliance with W3C DCAT. In some cases these might be identical, but in most cases the Dataset represents a more abstract concept, while the distribution can point to a specific file."
- [#metadata_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#metadata_tree): if covered in metadata, see [2_documentation_quality](2_documentation_quality#2a---what-metadata-and-documentation-for-example-the-methodology-of-data-collection-and-way-of-organising-data-will-accompany-data)
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): nested, see below. 

[Properties in distribution] could be used to describe re-used datasets?
- [#distribution_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_table): e.g. title, access_url, download_url, description, format, license

Missing:
- Dataset/distribution are most suited to published datasets
- Methodology of data creation/collection
- Data re-use constraints

---
<!--additional guidance from funders-->
### Other DMP guidance

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Collection and/or use of existing data]
- What methods or software are used if new data is collected or produced?
- How should data provenance be documented? 
- Are there any limitations related to file format, licensed software or similar for (re)use of existing data?
- Are there any reasons why existing data sources are not reused?

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[1. Data Summary]
- Will you re-use any existing data and what will you re-use it for? State the reasons if re-use of any existing data has been considered but discarded.
- What is the purpose of the data generation or re-use and its relation to the objectives of the project?
- To whom might your data be useful ('data utility'), outside your project?
- What is the origin/provenance of the data, either generated or re-used?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- With respect to data provenance: Document the provenance for example by including it in the metadata record (e.g., using persistent identifiers), or via a linked provenance record (e.g., when you are familiar with using PROV-O, PAV, or VoID).
- Supply at least the following information:
- Sources of data generation or collection (e.g., model, instrument, methodology)
- The date of data creation or collection
- The contributor(s) involved
- Data versioning information (indicate relations to other versions and describe changes)

---
<!--additional explanations-->
### Explanations for support staff
- Licensing conditions
- Referencing to datasets at dataset/file level (different frameworks)

---
<!--additional explanations - only keywords-->
### Explanations for users
- Where to find datasets
- Licensing conditions
- How to cite datasets

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Are there any existing datasets you could reuse? 
Visit the research data topic page at NTNU Innsida to see a list of places to search for data. (link)

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
What standards and methods will be used for data collection/generating?
Are there any existing data (internal or external) on the topic? If yes, how can they be integrated and reused in the project?

#### [EasyDMP](https://www.sigma2.no/data-planning) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
**Data description and collection or reuse of existing data – this section covers how you plan to use or produce your project’s data including the amount of data you expect the project will produce or need access to.**

Describe how you plan to collect new or use existing data – this should cover the methodologies and soYware that you plan to use and any constraints thedata are subject to. Also, include how you plan to document the provenance of the data. If data exists, please include a reason why the existing data is not sufficient.

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[If you are going to collect new data, how will they be collected (questionnaires, interviews, observations, measurements, recordings, etc.), where, and during what period? Who will be responsible for the data collection? What resources will be needed during the collection process, in terms of staff, instruments, and software?]
 Why is this important? Data collection is a central, and often resource-heavy, part of the research process. By planning for how to collect the data, when they will be collected, and the scope of the data collection, you can assess and budget for various resources. If you pay consideration to this in good time, a reviewer can more easily understand what type of data that will be collected.

[Give a brief description of existing data in the field, i.e. data collected in previous research (including data from other researchers and research groups). If there are existing data, can they be reused in the project? How will you document the origin of existing data? If you cannot use existing data, enter the reason why.]
 Why is this important? You should include an overview of existing data in the DMP, as there could already be material that can be used to answer the research questions, or some of them, but also to make sure that you don’t duplicate a data collection. For a research funder, it may be relevant to know whether it’s possible to use existing data material. If there aren’t any existing data, it’s vital to explain the value of collecting a new data material. If you will be using both existing and new data, describe how you will combine them.
 
#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
What kinds of data is your research based on? What data will be collected, produced or reused? What file formats will the data be in? Additionally, give a rough estimate of the size of the data produced/collected. (1.1)
Briefly describe what types of data you are collecting or producing. In addition, explain what kinds of already existing data you will (re)use. List, for example, the types of texts, images, photographs, measurements, statistics, physical samples or codes.

-----
-----
<!--Science Europe question ID & title-->
## 1b - What data (for example the kind, formats, and volumes) will be collected or produced?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated

> 1b.1\
Give details on the kind of data: for example numeric (databases, spreadsheets), textual (documents), image, audio, video, and/or mixed media.

Encourage use of broad categories, researchers are often over-specific.\
Use controlled vocabulary if available.

> 1b.2\
Give details on the data format: the way in which the data is encoded for storage, often reflected by the filename extension (for example pdf, xls, doc, txt, or rdf).

> 1b.3\
Justify the use of certain formats. For example, decisions may be based on staff expertise within the host organisation, a preference for open formats, standards accepted by data repositories, widespread usage within the research community, or on the software or equipment that will be used.

> 1b.4\
Give preference to open and standard formats as they facilitate sharing and long-term re-use of data (several repositories provide lists of such ‘preferred formats’).

A list of preferred file formats for common data types are given by Data Archiving and Networked Services (DANS) at [https://dans.knaw.nl/en/file-formats/](https://dans.knaw.nl/en/file-formats/)

Be aware that what is appropriate file formats may depend on the phase of the project. In the active phase both open and proprietary formats can be appropriate. In the medium-term storage open formats are to be preferred - beware e.g. the danger of license loss for proprietary software. And for long-term preservation choose strictly open formats. Conversion strategies should be described.

> 1b.5\
Give details on the volumes (they can be expressed in storage space required (bytes), and/or in numbers of objects, files, rows, and columns).

Rough estimations are sufficient for planning purposes.
More precise numbers can be needed if shared with stakeholder, e.g. to apply for/purchase storage quotas.

#### Science Europe DMP Evaluation Rubric: sufficiently addressed
- Clearly describes or lists what data types will be generated (for example numeric, textual, audio, or video) and their associated data formats, including, if needed, data conversion strategies.
- Explains why certain formats have been chosen and indicates if they are in open and standard format. If a proprietary format is used, it explains why.
- Provides information about the estimated data volume.
- Clearly states, if applicable, that no new data will be produced or generated by the project.
- NB. Information derived from previously existing data sources (namely output, processed, and analysed data) are to be considered new data under this question.

```
**Relevant PID**
none?

**Interested stakeholder**
- Possibly core facility?
- Research community: The reusability of the data may depend on e.g. a good description of collection method and on the use of preferred file formats.

**Relevant project phase**
- pre-award: outline
- planning post-award, active phase
```

#### Coverage in [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dataset]
- [#dataset_description_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_description_tree): "Description is a property in both Dataset and Distribution, in compliance with W3C DCAT. In some cases these might be identical, but in most cases the Dataset represents a more abstract concept, while the distribution can point to a specific file." [string]
- [#dataset_type_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_type_tree): "If appropriate, type according to: DataCite and/or COAR dictionary. Otherwise use the common name for the type, e.g. raw data, software, survey, etc." [string]
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): nested, see below

[Properties in distribution]
- [#distribution_byte_size_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_byte_size_tree): byte size [number]
- [#distribution_format_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_format_tree): IANA media types recommended [string, free text]

Missing:
- Dataset/distribution are most suited to published datasets
- Justification of formats
- Is a given format considered open?

---
<!--additional guidance from funders-->
### Other DMP guidance

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[File types and format]
- What types of data will the project collect, produce and/or reuse? Examples of type of data can be numerical, text, image, audio, video, etc.
- What format data is data stored in when collecting and analyzing, such as .pdf, .xls(x), .doc(x), .txt, .rdf.
- On what basis are certain data formats chosen? For example, this may depend on expertise in specific formats, preference for open file formats is, standard formats accepted at data repositories, extensive use of specific formats in research communities or format given by equipment or software used.
- What is the (estimated) volume of data to be stored during collection and analysis, archived and possibly long-term preserved? This can be stated as storage space (bytes), number of objects, files, rows and columns.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[1. Data Summary]
- What types and formats of data will the project generate or re-use?
- What is the expected size of the data that you intend to generate or re-use?

[2.3 Making data interoperable]
- Will your data include qualified references  to other data (e.g. other data from your project, or datasets from previous research)?

[3. Other research outputs]
- In addition to the management of data, beneficiaries should also consider and plan for the management of other research outputs that may be generated or re-used throughout their projects. Such outputs can be either digital (e.g. software, workflows, protocols, models, etc.) or physical (e.g. new materials, antibodies, reagents, samples, etc.).
- Beneficiaries should consider which of the questions pertaining to FAIR data above, can apply to the management of other research outputs, and should strive to provide sufficient detail on how their research outputs will be managed and shared, or made available for re-use, in line with the FAIR principles.

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- With respect to data formats or file formats: Make data available in a file format that is accepted by your research community to enable data sharing, interoperability, and reuse, and by the repository to enable long- term preservation. When in doubt, check a couple of potentially relevant data repositories to find out what they expect, and include your findings in the DMP.
- For guidance about how to search for repositories, see [6a - Who (for example role, position, and institution) will be responsible for data management (i.e. the data steward)?](6_responsibilities_resources)

---
<!--additional explanations-->
### Explanations for support staff
- Domain conventions
- Data formats in active phase vs. long-term preservation
- Persistent file formats, lossy file formats, conversion techniques
- Calculating data volumes

---
<!--additional explanations - only keywords-->
### Explanations for users
- What is considered data ("I don't have data")
- Kind of data
- File formats
- How to estimate data volume

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Keep in mind whether the scale of the data will pose challenges when sharing or transferring data between sites; do you need to include additional costs? How will you address these challenges? If you have large volumes of data that need storage, please contact the IT department at NTNU. (link)
 
#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
What kind of data will be collected/generated (e.g. observations, simulations, interviews)? What are the sources (e.g. corpora or other raw data)?

What type of data will be collected/generated (e.g. text, image, numerical data, sound)? 

What file format(s) will be used?

#### [SIKT DMP](https://sikt.no/en/data-management-plan) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Provide an estimate of the presumed size/scale of data.

Specify the file format(s) of the data collection. Please note that it is recommended to make data available in open (non-proprietary) formats after the end of the project.

Provide the name of the software/tool that will be used to process and analyze data.

#### [EasyDMP](https://www.sigma2.no/data-planning) [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
**Data description and collection or reuse of existing data – this section covers how you plan to use or produce your project’s data including the amount of data you expect the project will produce or need access to.**

Describe how much data and the type of data you plan to collect or produce – this should include the type (e.g. databases, spreadsheets), the volume and formats you intend to use. You should justify your choice if the formats you intend to use are proprietary. The quantity of data should be in the amount of space required (e.g. in GigaBytes) or the number of files.

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Describe which type(s) of data that will be used in the project, and whether they will be generated, collected, or reused data. Also describe the scope, quantity and, if possible, the file format of the material.]

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Categorise your data in a table or with a clear list, for example:
 A) previously collected existing data which is being reused in this project,
 B) data collected for this project,
 C) data produced as an outcome of the research process.
 
The categorisation can form a general structure for the rest of the DMP.
List the file formats for each data set. In some cases, the file formats used during the research project may differ from those used in archiving the data after the project. List both. The file format is a primary factor in the accessibility and reusability of your data in the future.
In the DMP, what is important is to describe the required disk space, not how many informants participated in the project. A rough estimation of the size of the data is sufficient, for example, less than 100 GB, approx. 1 TB or several petabytes.

**Tips for best practices**
 • Use a table or bullet points for a concise way to present data types, file formats, the software used and the size of the data.
 • Examples of file formats are .csv, .txt, .docx, .xslx and .tif.
 • Make sure to describe any special or uncommon software necessary to view or use the data, especially if the software is coded in your project.
 • You can also estimate the increase in data production or collection during the project for a specific time period: "The project is producing/collecting approximately 100 GB of data per week."