---
layout: page
<!--type: cheat_sheet-->
title: Conceptual DMP reflections
search_exclude: false
contributors:
page_id: dmp_reflections
description: DMP reflections, conceptual view, stakeholders, stakeholder motivations
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

## Mapping of DMP stakeholders and needs
In addition to analysing and annotating existing guidelines and resources, the project group has reflected on DMP stakeholders in Norway that should be considered when designing DMP guidance and templates. This mapping is both inspired by taking a multi-stakeholder perspective on data management plans as proposed by [Kvale and Pharo 2021. Understanding the Data Management Plan as a Boundary Object through a Multi-stakeholder perspective.](https://doi.org/10.2218/ijdc.v16i1.746) and the group’s extensive experience in providing data management support in institutions and research infrastructures to both researchers and policy makers. Furthermore, we have illustrated DMP needs resulting from the wide spectrum of research projects and expectations a DMP may need to serve.

These considerations are also available on [zenodo (DOI: 10.5281/zenodo.10836867)](https://doi.org/10.5281/zenodo.10836867).

### DMP Stakeholders
A data management plan (DMP) is a structured document containing information and thoughts regarding the handling of research data throughout the entire lifecycle of a research project, with the intention of making data as FAIR (Findable, Accessible, Interoperable, Reusable) and as open as possible. A data management plan is a living document to be updated as the project develops. Researchers meet requirements from institutions and research funders to create DMPs for their projects, in order to maximise project impact and to ensure that legal and ethical aspects t are considered. For researchers, writing a DMP should be an awareness-creating process and the DMP can function as a hub that connects data-related aspects in a project. Relevant guidance is essential in order to make writing a DMP a useful exercise instead of being perceived as an administrative burden.

Importantly, the information in a data management plan can also be valuable for third-party actors at different stages of a research project. Integrating information in DMPs with other services through machine-actionable data management plans (maDMP) is increasingly gaining attention (see e.g. [Miksa et al. 2019. Ten Príncipes for Machine-Actionable Data Management Plans.](https://doi.org/10.1371/journal.pcbi.1006750)). Of note, not all of the suggested interactions are currently covered by the [RDA Common Standard for machine-actionable DMPs](http://doi.org/10.15497/rda00039). The current standard is best suited for documenting administrative information and produced datasets, and thus exchanging DMP information connected to the beginning or end of a research project. Aspects related to conducting research in the active phase, such as routines for data management and processing or legal and ethical considerations, are currently not sufficiently covered. These aspects are more difficult to standardise and closely linked to the research domain, yet potentially of interest for stakeholders and crucial for the awareness-creating function of a DMP.

In this project, we have categorised DMP stakeholders in 3 levels as illustrated below as stakeholder pyramid: stakeholders that have requirements on DMP format or content (level I), stakeholders that could interact with information in the DMP (level II), and stakeholders that are not directly involved but have an interest in DMPs facilitating FAIR research data or in the DMP itself (level III).

#### Level I: Stakeholders who set requirements
- Researchers (employed in various structures, at different career levels): Requirements for user-friendliness and academic relevance
- Institutions: Requirements for complying with information security, legislation and research ethics
- Research funders, Institutions that require DMP: Requirements for Open Science and DMP

#### Level II: Stakeholders who can provide/use information in DMP
The level II stakeholders might have interests in a DMP at different times during a research project, the relevant project phases are indicated in square brackets: planning (pre/post-award), implementation (active phase of the research: data creation/collection, data processing, preparing data for archiving), reporting (to institution/funder, e.g. using research information system).

##### Within the institution
- IT department: Data storage services, information security guidelines [planning, implementation]
- Data Protection Officer: Projects with personal data/special category personal data, research ethics guidelines [planning]
- Research Advisor/Research Administration: Project funding, project results, for evaluation and statistical purposes [planning, reporting]

##### Support personnel
- Data Steward (affiliated with research unit, core facility, or research infrastructure): Planning, data documentation, data storage, data analysis, data sharing [planning, implementation]
- Research support at the university library: Planning, data documentation, data sharing [planning, implementation]
- Data Curator (at data archive): Data sharing [implementation, reporting]

##### National/regional service providers
- Sigma2 (national service provider of computational infrastructure): Allocating data storage services, high-performance computing [planning]
- REK (regional ethical committees): Projects with health data [planning]
- SIKT (Norwegian Agency for Shared Services in Education and Research) privacy services: Projects with personal data [planning]
- CRIStin/NVA (research information system): Project results [reporting]

#### Level III: Stakeholders without immediate involvement
- Research community: Reuse of research data, transparency in the research process, overview of ongoing projects
- Open Science ecosystem: DMP as research object
- Industry: Re-use of research data
- Society: Transparent and cost-effective research

{% include image.html file="stakeholder_pyramid.png" caption="Stakeholder pyramid: DMP stakeholders in Norway." alt="DMP stakeholders depicted as pyramid with Level 1 (Stakeholders who set requirements) at the top, surrounded by the words Risk reduction, Compliance, User-friendliness & Relevance. Level 2 (Stakeholders who can offer/use information in DMP) in the middle. Level 3 (Stakeholders without immediate involvement) at the bottom" %}

---
### DMP needs
Depending on the field of research and the needs of the project, the DMP may take different forms. A DMP for a straightforward project with few participants and limited data volume will look different from a DMP for a complex international consortium project that will produce terabytes of data. A DMP for a project that analyses literature sources will look different from a project that creates many different types of data from patient samples. The project aims to address these - partially opposing - ‘DMP cornerstones’, as illustrated below.

{% include image.html file="dmp_cornerstones.png" caption="Cornerstones illustrating the different needs a DMP may need to meet." alt="Hexagon illustrating different DMP needs with characteristics written at each corner and arrows pointing to writing 'DMP needs' in the middle." %}

## Expectations of DMP stakeholders
When mapping stakeholders, it became evident that they have distinct expectations towards DMPs. The motivations for requesting DMP can be promotion of practices, getting an overview of project outputs, ensuring that guidelines are followed, or reusing information from the DMP in seamless integrations. There is still development potential for the latter two. The figure below illustrates which expecations appear to be dominant for selected stakeholders.

{% include image.html file="dmp_expectations.png" caption="Expecations towards DMPs and their relevance to selected stakeholders." alt="9-pointed star labelled 'DMP expecations' with expecation written at each point. Below, star-figures with colored points and without labels indicate which expecations are most relevant to selected stakeholders." %}

## Inspiring DMP project elsewhere
While working on the project, we came across inspiring DMP projects in other countries working on national or local DMP guidance and strengthening DMPs as useful tools in the research process.

- Open data flagship pilot (Sweden): [final report](https://doi.org/10.17196/snd.flagship-open-data.2022)
- Aalto University (Finland): Viitanen, E. (2023). Testing Open Science Tools: Machine-actionable DMPs. Septentrio Conference Series, (1). [https://doi.org/10.7557/5.7129](https://doi.org/10.7557/5.7129)
- DeiC DMP (Danmark): [https://dmp.deic.dk/](https://dmp.deic.dk/)
- Salzburg Manifesto on machine-actionable Data Management Plans (maDMPs): [https://doi.org/10.5281/zenodo.10658522](https://doi.org/10.5281/zenodo.10658522)
- OSTrails (EU project): [https://ostrails.eu](https://ostrails.eu)

### Relevant working groups
- [Research Data Allicance (RDA) DMP Common Standards WG](https://www.rd-alliance.org/groups/dmp-common-standards-wg/)
- [Research Data Allicance (RDA) Active Data Management Plans IG](https://www.rd-alliance.org/groups/active-data-management-plans/)
- [LIBER Research Data Management Working Group](https://libereurope.eu/working-group/research-data-management/)