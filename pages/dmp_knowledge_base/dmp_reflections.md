---
layout: page
<!--type: cheat_sheet-->
title: Conceptual DMP reflections
search_exclude: false
contributors: [Jenny Ostrop, Korbinian Bösl, Illimar Rekand, Ida Juhasz, Live Kvale, Leif Longva, Svein Høier, Lisbeth Jahren, Ingrid Heggland]
page_id: dmp_reflections
description: DMP reflections, conceptual view, stakeholders, stakeholder motivations
affiliations: 
sidebar: background_knowledge
toc: true
---

On this page, we share conceptual considerations on DMPs as part of our working process.\
We appreciate feedback from the community and are always happy to discuss research data management - please [get in touch](/pages/about/#contact). 


## Mapping of DMP stakeholders and user needs
In addition to analysing and annotating [existing guidelines and resources](/pages/science_europe), the project group has reflected on DMP stakeholders in Norway that should be considered when designing DMP guidance and templates. This mapping is both inspired by taking a multi-stakeholder perspective on data management plans as proposed by [Kvale and Pharo 2021. Understanding the Data Management Plan as a Boundary Object through a Multi-stakeholder perspective.](https://doi.org/10.2218/ijdc.v16i1.746) and the group’s extensive experience in providing data management support in institutions and research infrastructures to both researchers and policy makers. Furthermore, we have illustrated DMP needs resulting from the wide spectrum of research projects and expectations a DMP may need to serve.

An initial version of these reflections has been published as working paper on zenodo with the title *Mapping of DMP stakeholders and user needs in the project ‘Data Management Plans: Support package for Norwegian higher education libraries’* (March 2024). [DOI: 10.5281/zenodo.10836867](https://doi.org/10.5281/zenodo.10836867)

### DMP Stakeholders
A data management plan (DMP) is a structured document containing information and thoughts regarding the handling of research data throughout the entire lifecycle of a research project, with the intention of making data as FAIR (Findable, Accessible, Interoperable, Reusable) and as open as possible. A DMP is a living document to be updated as the project develops, ensuring that legal and ethical aspects as well as information security requirements are met, and helping to maximise project impact. For researchers, writing a DMP should be an awareness-creating process while the DMP itself can function as a hub that connects data-related aspects in a project.

Importantly, the information in a data management plan can also be valuable for third-party actors at different stages of a research project. Integrating information in DMPs with other services through **machine-actionable data management plans (maDMP)** is increasingly gaining interest (see e.g. [Miksa et al. (2019). Ten Principles for Machine-Actionable Data Management Plans.](https://doi.org/10.1371/journal.pcbi.1006750)).\
[Version 1.2 of the maDMP Common Standard](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard/releases/tag/v1.2) has been released end of 2025, yet there are interactions remaining that are not currently covered by the standard. Currently, the standard is best suited to exchange administrative information and information about produced datasets, relating to information that is relevant in the starting or concluding phase of a research project. Aspects related to conducting research in the active phase, including legal and ethical considerations and dynamic changes to data and metadata remain difficult to reflect.

In our experience, one critical obstacle remains the technological readiness on the stakeholder side to receive DMP-information through API endpoints. Overcoming this requires both international standardization efforts (such as the [OSTrails project](/pages/dmp_reflections#inspiring-dmp-project-elsewhere)) and working together on implementing local or national use case examples.

Conceptually, we have categorised DMP stakeholders in 3 levels as illustrated below as stakeholder pyramid: 

* stakeholders that have requirements on DMP format or content (level I)
* stakeholders that could interact with information in the DMP (level II)
* stakeholders that are not directly involved but have an interest in DMPs facilitating FAIR research data or in the DMP itself (level III).

{% include image.html file="stakeholder_pyramid.png" caption="DMP stakeholders and their motivations." alt="DMP stakeholders depicted as pyramid with Level 1 (Stakeholders who set requirements) at the top, surrounded by the words Risk reduction, Compliance, User-friendliness & Relevance. Level 2 (Stakeholders who can offer/use information in DMP) in the middle. Level 3 (Stakeholders without immediate involvement) at the bottom" %}

#### Level I: Stakeholders who set requirements
* Researchers (employed in various structures, at different career levels): Expect research relevance
* Institutions: DMP requirements as means to promote compliance with legislation, research ethics, and information security
* Research funders, Institutions as funders: Open Science and DMP policy requirements

#### Level II: Stakeholders who can provide/use information in DMP
Level II stakeholders are a broad category with diverse motivations, ranging from provision of expert knowledge over resource planning to output monitoring. While reuse of information and seamless integrations between systems stands central, information needs are distinct to each stakeholder and purpose and only a distinct part of the DMP or certain timepoint in a project can be relevant. The category roams both services such as computational resources and individuals such as research support staff. Level II stakeholders can be localized within the institution or at national infrastructures.

Examples:
* Administrative information in DMP is populated by CRIS system
* Embedded data steward uses information in the DMP to provide advice on data management
* Data Protection Officer gets automatically alerted if a project states handling of special category personal data
* National e-infrastructure allocates and terminates resources based in information in the DMP
* DMP exchanges information with Electronic Lab Notes (ELN) system or research data archive
* Research data archive uses information about planned data publications for future resource planning
* Research administration monitors research outputs based on dataset information in the DMP

#### Level III: Stakeholders without immediate involvement
* Research community: Reuse of research data, transparency in the research process, overview of ongoing projects
* Open Science ecosystem: DMP as research object, linking between articles and research outputs
* Industry: Re-use of research data
* Society: Transparent and cost-effective research

### DMP needs
Depending on the field of research and the needs of the project, the DMP may take different forms. Complexity of the research question, number of data types, data volume, legal and ethical aspects to consider and number of project partners will reflect in the DMP. A DMP for a straightforward project with few participants and limited data volume will look very different from a DMP for a complex international consortium project that will produce terabytes of data, and a DMP for a project in theoretical mathematics will look different from a project that creates many different types of data from patient samples. As illustrated below, these ‘DMP cornerstones’ are partially opposing.

{% include image.html file="dmp_cornerstones.png" caption="Cornerstones illustrating the different and partially opposing project needs a DMP may need to cater." alt="Polygon illustrating different DMP needs with characteristics written at each corner and arrows pointing to writing 'DMP needs' in the middle." max-width="40em" %}

 To create DMP templates that work across project complexity and disciplinary preferences is a challenge. Straightforward projects should not be bothered with too many questions, while providing in-depth follow-up questions can be necessary to address data management needs in more complex projects. Maintaining several parallel DMP templates to address different project needs is not a feasible approach, as it this will create a significant maintenance debt over time. Therefore, the projects has chosen to create one Knowledge Model in which a combination of tags can be used to generate targeted questionnaires. Following this modular 'Lego-brick' approach, questions only relevant to a certain user group can be included or left out (see below). In addition, explicit opt-out options have proven to be a suitable approach to accommodate projects which e.g. handle very little data.

{% include image.html file="km_lego.png" caption="Modular 'Lego-brick' approach is used to generate DMP questionnaires adapted to different user needs based on one knowledge model. Dimensions adding to DMP complexity: Cross-institutional projects, Ethical legal and societal implications (ELSI), Computationally demanding projects (HPC)." alt="Illustration of four Lego brick stacks next to each other, from left to right: Minimum (one large orange brick), ELSI (small green brick) stacked on Minimum (large orange brick), ELSI (small green brick) stacked on RCN/ Science Europe (large blue brick), HPC (small violet brick) and ELSI (small green brick) stacked on RCN/ Science Europe (large blue brick)." max-width="30em" %}


---
## Expectations of DMP stakeholders
When mapping stakeholders, it became evident that different stakeholders can have distinct expectations towards DMPs. The motivations for requesting DMP can be promotion of practices, getting an overview of project outputs, ensuring that guidelines are followed, or reusing information from the DMP in seamless integrations. There is still development potential for the latter two. The figure below illustrates which expectations and motivations appear to be prominent for selected stakeholders. This does not imply that other perspectives cannot be important for the different stakeholders, yet highlighting that they have divergent perspectives on the application of DMPs.

{% include image.html file="dmp_expectations.png" caption="Expectations towards DMPs and their relevance to selected stakeholders." alt="9-pointed star labelled 'DMP expecations' with expecation written at each point. Below, star-figures with colored points and without labels indicate which expectations are most relevant to selected stakeholders." %}


---
## On DMP tools
Although it is possible to write a DMP as a text document, using a digital DMP tool has many advantages. At the same time, it can be challenging for researchers to navigate between different DMP tools and templates. While choosing a DMP tool is partly a matter of taste, there are also substantial differences between tools.

Researchers impression of a DMP tool will always reflect a composite of the user-friendliness of the tool itself, the quality and appropriateness of the used DMP template, the quality of the user guidance and the available export options. When providing advice on DMP tools and templates in a support role, it is however necessary to take a more conceptual approach. The different elements should be evaluated independently and can give room for improvements: The technical functionality within the DMP tool, structure and content of the questionnaire, and configuration of export functions for use by humans and machines. At the same time, collecting realistic user feedback on a DMP questionnaire is only possible if a real DMP tool is used.

{% include image.html file="dmp_tool_reflections.png" caption="Researcher experience and conceptual approach to assessing DMP tools." alt="Researcher experience visualized as black square leading to document to be delivered to funder. Conceptual approach visualized as adjacent, independent rectangles in different blue shades leading to several possible outputs fulfilling stakeholder needs." %}

### Evaluation of DMP Tools
Aiming to give guidance to researchers on which DMP tool to use, a working group between the Universities of Bergen, Oslo, Trondheim og Tromsø (BOTT) evaluated different DMP tools based on a list of defined criteria. In addition the recommending DMP tools, their [report published in December 2022 (DOI: 10.5281/zenodo.7428542)](https://doi.org/10.5281/zenodo.7428542) also points out the potential on collaborating on DMP guidance, which was followed up in this project. As the DMP field is moving fast, an [update of the work was published in April 2024 (DOI: 10.5281/zenodo.10977711)](https://doi.org/10.5281/zenodo.10977711).\
Subsequently, the Norwegian Agency for Shared Services in Education and Research (Sikt) invited a working group on a common national solution for DMP tools with representation of the higher education and research institute sector as well as e-infrastructure provider Sigma2 and the Norwegian Research Council, which started in February 2024 and delivered its [report in September 2024 (DOI: 10.18711/dcde-9537)](https://doi.org/10.18711/dcde-9537). The choice in the project of using the DMP tool Data Stewardship Wizard to implement the DMP questionnaire is in line with the reports' recommendations.

Coordinated by Sikt, a [national pilot of the DMP tool FAIR Wizard started in September 2025](https://sikt.no/tiltak/nasjonal-pilot-utproving-av-nytt-verktoy-datahandteringsplanlegging-fairwizard).


---
## Inspiring DMP project elsewhere
While working on the project, we came across inspiring DMP projects in other countries working on national or local DMP guidance and strengthening DMPs as useful tools in the research process.

* Open data flagship pilot (Sweden): [final report](https://doi.org/10.17196/snd.flagship-open-data.2022)
* Aalto University (Finland): Viitanen, E. (2023). Testing Open Science Tools: Machine-actionable DMPs. Septentrio Conference Series, (1). [https://doi.org/10.7557/5.7129](https://doi.org/10.7557/5.7129)
* DeiC DMP (Denmark): [https://dmp.deic.dk/](https://dmp.deic.dk/)
* Salzburg Manifesto on machine-actionable Data Management Plans (maDMPs): [https://doi.org/10.5281/zenodo.10658522](https://doi.org/10.5281/zenodo.10658522)
* OSTrails (EU project): [https://ostrails.eu](https://ostrails.eu)

### maDMP extensions (non-exhaustive)
* OSTrails Application Profile for maDMPs: [https://docs.ostrails.eu/en/latest/commons/dmp/application-profile.html](https://docs.ostrails.eu/en/latest/commons/dmp/application-profile.html "2026-02-23")
* Extension of the RDA maDMP standard for governments and other large organizations: [https://fairerdata.github.io/maDMP-Standard/](https://fairerdata.github.io/maDMP-Standard/ "2026-02-23")
* maSMP for Software Management Plans by ZB MED: [https://zbmed-semtec.github.io/maSMPs/](https://zbmed-semtec.github.io/maSMPs/ "2026-02-23")

### Relevant working groups
* [Research Data Alliance (RDA) DMP Common Standards WG](https://www.rd-alliance.org/groups/dmp-common-standards-wg/)
* [Research Data Alliance (RDA) Active Data Management Plans IG](https://www.rd-alliance.org/groups/active-data-management-plans/)
* [Research Data Alliance (RDA)Common Application Programming Interface (API) for machine-actionable Data Management Plans (maDMPs)](https://www.rd-alliance.org/groups/common-application-programming-interface-api-for-machine-actionable-data-management-plans-madmps/)
* [LIBER Research Data Management Working Group](https://libereurope.eu/working-group/research-data-management/)
* Nordic DMP Forum within the [Nordic Data Stewardship Network](https://datice.is/en/nordic-data-stewardship-network)