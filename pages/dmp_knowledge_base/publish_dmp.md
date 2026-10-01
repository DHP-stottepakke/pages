---
layout: page
<!--type: cheat_sheet-->
title: Publishing the DMP
search_exclude: false
contributors: [Jenny Ostrop]
page_id: publish_dmp
description: Publishing a DMP
supported_by: 
sidebar: background_knowledge
toc: true
---

## Where to publish the DMP?

<!--key information-->
### Science Europe Guidance - annotated

{% tool "science-europe-dmp-guidance" %} [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

>
> not covered

Best practice is to publish the DMP with a PID. This can be referred to (and from) when publishing papers, data sets and other outputs from the research project. Ideally, all versions of the DMP could be published, but at minimum the final version should be made available (i.e. when reporting the project). The research repository {% tool "zenodo" %} is often used to publish DMPs, together with other research results. In Norway, the National Research Archive, {% tool "nva" %}, is [under development](https://sikt.no/tjenester/nasjonalt-vitenarkiv-nva), and this might also be a possible repository for DMP archiving and/or publication.

{% include callout.html type="note" content="
**Mappings**

**Relevant PID**

* PID of DMP

**Interested stakeholder**

* Level 1: Funder
* Level 2: Research Administration, CRIStin/NVA
* Level 3: Research community

**Relevant project phase**

* planning post-award, active phase
" %}

#### Coverage in RDA Common Standard for maDMP

{% tool "rda-dmp-common-standard" %} [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

[Properties in dmp]

* [#dmp_id_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_id_tree): nested, see below
* [#dmp_title_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_title_tree): dmp title
* [#dmp_created_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_created_tree): first version (date + time)
* [#dmp_modified_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_modified_tree): each modified version (date + time)
* [#dmp_language_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dmp_language_tree): dmp language

[Properties in dmp id]

* [#properties-in-dmp_id](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#properties-in-dmp_id): identifier, type

Missing:

* version id (human readable)

---
<!--additional guidance from funders-->
### Other DMP guidance

#### Guidance from NFR

{% tool "nfr-dmp-guidance" %}

[What a data management plan should include]\
We also recommend assigning your data management plan a persistent identifier, such as a DOI. Several services for data management plans offer this.

#### Horizon Europe Program Guide V5.1 – 15.09.2025

{% tool "horizon-europe-programme-guide" %}

>
> A good practice regarding DMPs is to register them as a non-restricted public deliverables to make them openly accessible, unless legitimate reasons exist to keep them confidential. An additional good practice is to publish the DMP in specialised journals or publishing platforms such as {% tool "rio-journal" %} etc., or to deposit them in DMP-specific public repositories [...]. (p.48)

#### FAIRsFAIR FAIR-Aware Additional Guidance

{% tool "fair-aware-additional-guidance" %} [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

* not covered

---
<!--additional explanations-->
### Knowledge for support staff

* How to publish a DMP (with different tools, recommended platforms, versions)

---
<!--additional explanations - only keywords-->
### Knowledge for users

* Why should you publish your DMP
* How to publish your DMP

---
<!--recycling possible?-->
### Existing sources that can be reused

#### Open Science Toolbox

{% tool "ntnu-open-science-toolbox" %} [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

Forskningsrådet og andre finansiører oppfordrer til åpen publisering av datahåndteringsplaner. Da planene endres underveis, kan det gjerne publiseres flere versjoner etter hvert som de oppdateres. Mange prosjekt publiserer ulike versjoner av sin datahåndteringsplan i arkiv som Zenodo.
