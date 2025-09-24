---
layout: page
<!--type: cheat_sheet-->
title: Storage and backup during the research process
search_exclude: false
contributors: [Lisbeth Jahren, Ingrid Heggland, Svein Høier]
page_id: 3_storage_backup
description: Data storage, backup
affiliations: 
sidebar: background_knowledge
toc: true
---

<!--Science Europe question ID & title-->
## 3a - How will data and metadata be stored and backed up during the research process?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated

> 3a.1\
Describe where the data will be stored and backed up during research activities and how often the backup will be performed. It is recommended to store data in least at two separate locations.

> 3a.2\
Give preference to the use of robust, managed storage with automatic backup, such as provided by IT support services of the home institution. Storing data on laptops, stand-alone hard drives, or external storage devices such as USB sticks is not recommended.

As a default, choose storage solutions delivered by the IT department at your institution. These services will in general will include backup, make sure you familiarise yourself with the backup routines at your institution (e.g. frequency and retention period). Important aspects when choosing a suitable storage solution for your projecrt includes confidentiality, collaboration with external partners and amount of data.

Be especially aware of cost and capacity issues if you have large amounts of data (in the order of terrabytes).  

In cases where institutionally managed storage cannot be used (e.g. field trips), the 3-2-1 rule should be followed (at least 3 copies of the data, 2 different media, 1 off-site copy). 
 
#### Science Europe DMP Evaluation Rubric: sufficiently addressed
Clearly (even if briefly) describes:
- The location where the data and backups will be stored during the research activities.
- How often backups will be performed.
- The use of robust, managed storage with automatic backup (for example storage provided by the home institution).
or
- Explains why institutional storage will not be used (and for what part of the data) and describes the (additional) locations, storage media, and procedures that will be used for storing and backing up data during the project.

{% include callout.html type="note" content="
**Mappings**\\
\\
**Relevant PID**\\
* none?\\
\\
**Interested stakeholder**\\
* Level 2: ITA, Sigma2 if big data\\
\\
**Relevant project phase**\\
* pre-award: outline (if budget-relevant)\\
* planning post-award, active phase\\
" %}

#### Coverage in [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in distribution]
- [#host_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_table): nested, see below

[Properties in host] may also be used to describe unpublished datasets?
- [#host_geo_location_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_geo_location_tree) [country code, controlled vocabulary]
- [#host_storage_type_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_storage_type_tree) [string, free text]
- [#host_backup_frequency](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_backup_frequency) [string, free text]
- [#host_backup_type_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_backup_type_tree) [string, free text]
- [#host_certified_with_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_certified_with_tree) [controlled vocabulary]
- [#host_supports_versioning_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_supports_versioning_tree): yes/no/unknown

Missing:
- Most suited to published data

---
<!--additional guidance from funders-->
### Other DMP guidance

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Storage and data security during the project]
- Where will (meta)data be stored and backed up throughout the project, and how often will this be performed? Storing data on laptops, typical external hard drives, USB-sticks or similar is not recommended due to less protection and greater risk of data being lost.
- How should data be recovered in the event of an accident?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- not covered

---
<!--additional explanations-->
### Knowledge for support staff
- Where to find information about local & national computing infrastructure. When to use what.
- Technical knowledge of backup approaches

---
<!--additional explanations - only keywords-->
### Knowledge for users
- Where to find information at own institution
- Use of institutionally managed storage, pricing policy (see question 6b)
- Backup in case institutional storage cannot be used.

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
- Describe where your data will be stored during the project period. We recommend using NTNU’s standard storage solutions (see NTNU storage guide). For specific information about procedures for back-up for the solution you choose for your project, contact the IT support at NTNU.
- Storing data on laptops, external hard drives, or external storage devices such as USB sticks is not recommended. Be sure to consider information security as well as data integrity and accessibility.

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
- What are the procedures for storage and backup, and where will this be done?
- Who is responsible for backup and restoring the data?
(For projects run exclusively at UiT, this will be the UiT IT Department for, provided that UiT facilities are used for storage.)
- Do you have sufficient storage facilities, or do you need extra services?
If collecting data in the field (out of office), how will the data be safely transferred from the field to the main storage unit?
- What kind of folder structure and filename conventions will be used?
- If collecting data in the field (out of office), how will the data be safely transferred from the field to the main storage unit?

#### [SIKT DMP](https://sikt.no/en/data-management-plan) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Security classification is a classification of data collections into classes based on the need for protection. Based on the security classification of each data package, you will get suggestions for secure data collection, storage and file transfer. There are four classes of security and confidentiality. These classes also apply to the processing and storage of research data.

Open (Green) category means that data can be accessible to anyone without special access rights.

Internal (Yellow) means that data must have some protection and that access is controlled through access restrictions.

Confidential (Red) means that data must be highly protected with strict access control.

Strictly Confidential (Black) means that data must be have the strictest access control.

Based on the outcome of the security classification carried out earlier in the plan, you will be provided with a list of data collection tools and services as these are stated in the guidelines of your institution. If your institution has not published its policy in the Data Policy Manager, suggested guidelines are listed as default.

Based on the outcome of the security classification carried out earlier in the plan, you will be provided with a list of file transfer services as these are stated in the guidelines of your institution. If your institution has not published its policy in the Data Policy Manager, suggested guidelines are listed as default.

#### [EasyDMP](https://www.sigma2.no/service/data-management-plan) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
**Storage and backup during the research process – covers how you plan to store your data and the back-up procedures you plan to use to ensure your data remains accessible.**

Describe how you will store and back-up your data during your project - you should describe where your data will be stored and backed-up and the number of replicas. If you do not plan to use instututional or national storage you can refer to your project’s or group’s procedures for back-up and replication. You should consider robust, managed storage for your data (laptops and personal USB drives should be avoided).

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Where and how will the data material be stored, and how do you make sure that it is securely stored? Will you do regular backups of the files? How will the data be recovered in the event of an incident?

**Why is this important? **

Losing a data material is something you want to avoid. Secure storage with regular backups of the data is essential. You may want to consult with the university’s/organization’s IT security office about storage and backups before you begin the data collection/project.]

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Where will your data be stored, and how will the data be backed up? Describe where you will store and back up your data during your research project. Consider who will be responsible for backup and recovery. If there are several researchers involved, create a plan with your collaborators and ensure safe transfer between participants. Show that you are aware of the storing solutions provided by your organisation. Do not merely refer to IT services. In the end, you are responsible for your data, not the IT department or the organisation. Explain the methods for preserving and sharing your data after your research project has ended in more detail in Section 5. 

**Tips for best practices**
- The use of a safe and secure storage provided and maintained by your organisation’s IT support or other reliable IT provider such as CSC is preferable.
- Do NOT USE external hard drives as the main storing option.
- Follow your institution's data security requirements


-----
-----
<!--Science Europe question ID & title-->
## 3b - How will data security and protection of sensitive data be taken care of during the research?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 3b.1\
Explain how the data will be recovered in the event of an incident.

When using storage solutions and infrastructure at your institution or IT department, routines for backup and recovery should be in place. Check what is relevant for the specific solution used in your project.

> 3b.2\
Explain who will have access to the data during the research and how access to data is controlled, especially in collaborative partnerships.

When choosing storage solutions and infrastructure, consider whether partners or collaborators outside your institution need access, as this might limit your options.

> 3b.3\
Consider data protection, particularly if your data is sensitive for example containing personal data, politically sensitive information, or trade secrets. Describe the main risks and how these will be managed.

As in 3b.2, choosing a suitable storage and infrastructure is essential, in this case to be able to ensure data protection. In addition, a risk assessment should be performed to reduce and manage risks.

> 3b.4\
Explain which institutional data protection policies are in place.

Consult institutional information security policies and storage guides:
* [NTNU Data storage guide](https://i.ntnu.no/wiki/-/wiki/English/Data+storage+guide  "2024-03-05")
* [UiB Storage guide](https://www.uib.no/en/foremployees/153608/storage-guide "2024-03-05")
* [UiO Data storage guide](https://www.uio.no/english/services/it/security/lsis/storage-guide.html "2024-03-05")
* [UiT Processing and storage](https://en.uit.no/research/research-dataportal/art?p_document_id=729174 "2024-03-05")

#### Science Europe DMP Evaluation Rubric: sufficiently addressed
Clearly explains:
- How the data will be recovered in the event of an incident.
- Which institutional and/or national data protection policies are in place and provides a link to where they can be accessed.
- Who will have access to the data during the research.
- Clearly describes the additional security measures (in terms of physical security, network security, and security of computer systems and files) that will be taken to ensure that stored and transferred data are safe, when sensitive data are involved (for example personal data, politically sensitive information, or trade secrets).

{% include callout.html type="note" content="
**Mappings**\\
\\
**Relevant PID**\\
* none?\\
\\
**Interested stakeholder**\\
* Level 1: Institution (information security)\\
* Level 2: DPO, REK, Sikt personverntjenester\\
\\
**Relevant project phase**\\
* pre-award: outline\\
* planning post-award, active phase\\
" %}

#### Coverage in [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in security and privacy]
- [#properties-in-security_and_privacy](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#properties-in-security_and_privacy): description [string, free text], name [string, free text]

[Properties in distribution]
- [#distribution_data_access_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_data_access_tree): open/shared/closed

Missing:
- Data recovery
- Institutional/national data protection policies
- Differential access rights, particularly in the active phase

---
<!--additional guidance from funders-->
### Other DMP guidance

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Storage and data security during the project]
- Who will have access to the data during the project and how is access controlled? This is particularly important where the project is a collaboration with several research communities/institutions.
- If applicable, how should data security and risk management be handled in relation to sensitive data, such as personal data and data that underlies trade secrets?
- What institutional data protection policies apply?

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[5. Data Security]
- What provisions are or will be in place for data security (including data recovery as well as secure storage/archiving and transfer of sensitive data)?
- Will the data be safely stored in trusted repositories for long term preservation and curation? (see also 5_sharing_preservation)

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- not covered

---
<!--additional explanations-->
### Knowledge for support staff
- National policies
- Classification of information: Institutional policies and storage guides
	- [Klassifisering av infomasjon: Sektorstandard for universiteter, høgskoler og forskningsinstitutter](https://cms.sikt.no/sites/default/files/2024-10/Veileder%20i%20ledelsessystem%20for%20informasjonssikkerhet.pdf "2025-09-19")
	- Dual use research: Report [Et helhetlig forskningssystem for åpen, skjermet og gradert forskning (NFR, 2024)](https://www.forskningsradet.no/nyheter/2024/fire-anbefalinger-for-et-helhetlig-forskningssystem-for-apen-skjermet-og-gradert-forskning/ "2024-09-11")
	- Export control: Guidelines for [International research and innovation cooperation](https://hkdir.no/en/guidelines-and-tools-for-responsible-international-knowledge-cooperation/international-research-and-innovation-cooperation "2024-10-03")
- Routines for data recovery
- Understanding data security measures

---
<!--additional explanations - only keywords-->
### Knowledge for users
- Data recovery
- National and institutional policies
- Information security levels 

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP Guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Note that all data should be classified in order to choose the correct level of security and confidentiality. See Innsida for more information on how to classify research data. Also see [Sikresiden.no](https://www.sikresiden.no/en/preventive/securinginformation) for more information about information security.
**Relevant documents:**
[NTNU Policy for information security](https://i.ntnu.no/wiki/-/wiki/English/Policy+for+information+security) 
[NTNU Storage Guide](https://i.ntnu.no/wiki/-/wiki/English/Data+storage+guide)

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
Does your data include sensitive data? (If yes, also answer the questions below.) 
Are you going to collect informed consent to store and share the data? If so, how? 
How are you going to secure confidentiality and identity protection?

#### [SIKT DMP](https://sikt.no/en/data-management-plan) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
State whether your project contains research on human subjects. As a main rule, you are obligated to inform the person(s) whose personal data you are going to collect. Read more about information and consent at Data Protection Services.

#### [EasyDMP](https://www.sigma2.no/data-planning) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
If your project uses sensitive data, describe how you will take care of data protection and security - you should describe how access to your data will be controlled and who will be allowed access. You should describe how you plan to conform with your organisation’s data protection rules, how you will satisfy institutional data protection policies, the main risks and recovery procedures.

#### [SND - Checklist DMP](https://doi.org/10.5281/zenodo.6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Refer to the information security guidelines and policies in your university/organization and define what implications they have. What information classification level does the data material have and what security measures are needed to protect the material? Who should have access to the project data during the project and how do you plan to protect the data from unauthorised access?

**Why is this important?**
Access to the data material must be restricted so that authorised people can access it, but it is protected from unauthorised access. Secure work and storage environments can include access restriction (e.g. passwords), encryption, and virus and access protection. You may need to contact your organization’s IT security office to make sure that you have addressed all questions regarding information security before the data collection begins.]

#### [DMP Tuuli](https://zenodo.org/doi/10.5281/zenodo.3629371) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
What legal issues are related to your data management? (For example, GDPR and other legislation affecting data processing).
All types of research data involve questions of rights and legal and ethical issues. Demonstrate that you are aware of the relevant legislation related to your data processing. If you are handling personal or sensitive information, describe how you will ensure privacy protection and data anonymisation or pseudonymisation.

**Tips for best practices**
- Check your institutional ethical guidelines, data privacy guidelines and data security policy, and prepare to follow the instructions that are given in these guidelines.
- If your research is to be reviewed by an ethical committee, outline in your DMP how you will comply with the protocol (e.g., how you will remove personal or sensitive information from your data before sharing data to ensure privacy protection).
- Will you process personal data? If you intend to do so, please detail what type of personal data you will collect.
- All data related to an identified or identifiable person is personal data. Information such as names, telephone numbers, location data and information on the congenital diseases of the individual's grandparents is personal data.
