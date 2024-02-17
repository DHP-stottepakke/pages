---
layout: page
<!--type: cheat_sheet-->
title: Administrative Information
search_exclude: false
contributors: [Jenny Ostrop]
page_id: 0_admin_information
description: Administrative information about the DMP
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

<!--Science Europe question ID & title-->
## 0 - Administrative Information

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated

> 0.1\
>Provide information such as name of applicant, project number, funding programme, version of DMP.

This section should identify the project with title, acronym and funding (if relevant) and contain information about the host institution, participants, and collaborators. Persistent identifiers should be used wherever possible.
It is beneficial to include references to relevant documents/agreements/contracts (e.g. collaborative agreements), particularly in multi-stakeholder projects.
Adding brief information about the purpose/aim of the project (abstract) is helpful for evaluators.
The DMP should be versionized (see also [Publishing the DMP](publish_dmp)).

#### Sufficiently adressed (DMP Evaluation Rubric)
- Contains the minimal information required to identify the applicant and the references of the project.

```
**Relevant PID**
- Persons: ORCID, CRIStin ID/NVA ID, role description DataCite/CredIT
- Institutions: ROR
- Funder: ID Open Funder Registry, ID CrossRef Funder Registry
- Funding: Grant ID

**Interested stakeholder**
- Level 1: Funder
- Level 2: Research Administration, CRIStin/NVA

**Relevant project phase**
- planning post-award, final reporting
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#dmp_contact_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_contact_table): contact_id (identifier, type), mbox, name
- [#dmp_contributor_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_contributor_table): contributor_id (identifier, type), mbox, name, role [string, not controlled])
- [#project_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#project_table): start, end, title, description [string, free text], funding (funder_id [CrossRef funder registry recommended], funding_status, grant_id)

Missing:
- institution(s) with ROR
- ID in institutional project management tool (if relevant)
- coupling of contact and contributors with CRIS
- controlled values for roles

---
<!--additional explanations-->
### Explanations for support staff

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Administrative information]
- The data management plan should include information about the Project Owner's institution, project manager, project number, project title, funder and version.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[1. Data Summary]
- Do you, or will you, make use of other national/funder/sectorial/departmental procedures for data management? If yes, which ones (please list and briefly describe them)?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

- not covered

---
<!--additional explanations - only keywords-->
### Explanations for users
- How to find the right PIDs (wishful thinking: pre-filled information based on Feide login)

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [SND - Checklist DMP](https://zenodo.org/records/6424769)[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

1.1 Project description
 
 [A brief description of the project. For example, the purpose of the project and what research questions will be addressed.]
 
Why is 1.1 important?
 If you collect all information about a project in a single document, old and new project members can more easily find the information they need, instead of having to search for the information or try to find out who may have it.
 
 1.2 Primary investigator/researcher (person, institution, or organization)
 [The person, institution, or organization responsible for the
 material and the intellectual content of the project. Enter a researcher ID if possible, e.g. ORCID (http://orcid.org).]
 
Why is 1.2 important?
 It’s important to know who is behind a project, and responsible for its material and intellectual content. This also means that data that are made accessible can be cited correctly.
 
 1.3 Contributing researcher(s) and/or organization(s) and their roles
 
 [Other organizations and/or person(s) who are or will be
 involved in the project. Describe how responsibilities are assigned in the research group (e.g. between the project leader, research staff, and technical staff), and who is responsible for what (who creates and updates the DMP, who is the project’s representative, etc.).]

Why is 1.3 important? If you collect all information about a project in a single document, old and new project members can more easily find the information they need, instead of having to search for the information or try to find out who may have it.
 
 1.4 Research principal
 [Who or what organization that is responsible for the research, and for making sure that an application for ethical approval is/has been made.]

 Why is 1.4 important?
 A research principal is the physical or legal person in whose organization the research is carried out, e.g. a university, city council, regional council, government agency, or private corporation. The research principal has the ultimate responsibility for the research and applies for ethical approval from the Swedish Ethical Review Agency. If a research project has several research principals, one of them is responsible for applying for ethical approval.
 Definition of Research principal according to the Swedish Ethical Review Agency, in Swedish only.
 
 
 1.5 Responsible department/unit
 [The organization with administrative responsibility for the project, e.g. a department at a university.]
 
Why is 1.5 important?
 This is administrative information that may be of interest for a funder or data repository. This information makes it possible to trace a project to someone responsible within an organization.
 
 1.6 Funding
 [Information about the research funding, e.g. funder(s), project title on the funding application, and the funder’s reference number for the application.]
 
Why is 1.6 important?
 If the DMP contains information about project funding, it’s easier to find the information when needed. Enter information about submitted applications and funding that’s been received in the DMP or add references to the documents and where to find them.
 
 1.7 Guidelines
 [Information about relevant guidelines from funders or the principal HEI, preferably with references to where those documents can be found, as well as the document version used. Make sure that the documents can be accessed even after the project ends. If information later in the DMP relates to these guidelines, make a reference to this paragraph.]
 
Why is 1.7 important?
 Many HEIs/research organizations have local rules and guidelines that are important to be aware of. Some examples are IT security policies, guidelines for information classification, or a handbook for research documentation. By complying with these guidelines, you get some assistance in e.g. how to adapt the technical, physical, and administrative environments so that the research material is securely handled. One way to make sure that these documents can be accessed even after the project has ended is to save them in the project’s document folder.
