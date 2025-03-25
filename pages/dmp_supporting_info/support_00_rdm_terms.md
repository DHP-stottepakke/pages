---
layout: page
<!--type: cheat_sheet-->
title: Research data terms
search_exclude: false
contributors: [Jenny Ostrop, Korbinian Bösl, Ida Juhasz, Live Kvale, Leif Longva, Svein Høier, Lisbeth Jahren, Ingrid Heggland]
page_id: support_00_rdm_terms
description:
affiliations:
sidebar: dmp_supporting_info
---

{% include callout.html type="note" content="
**On this page**\\
>> Navigate research data management terms with ease\\
>> Overview about term definitions we try to follow\\
" %}

Some of the terms used in the context of data management plans and research data management might need explanation. We try to adhere to the following definitions.

For Norwegian translations, consult the [NO-RDA Termliste for forskningsdatahåndtering](https://www.openscience.no/en/node/3544).

## Key research data management terms explained (alphabetical order, non-exhaustive)

### Archiving
> Definition according to CODATA: "Engage in curation activity that ensures that records, objects, metadata and data are properly selected, stored, and can be accessed, and for which logical and physical integrity are maintained over time, including security and authenticity."
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Archiving includes several steps. Data first need to be deposited, see [Data deposition](/pages/support_00_rdm_terms#Data-deposition). Often, there is a curation process where a curator engages with the depositor to improve the quality and ensure the FAIRness of the dataset. Furthermore, selecting a 'trustworthy' or 'trusted' research data archive ensures the long term preservation of the data, including a backup service.

### Data archive
Synonym: Long-term data repository. On these pages and in the affiliated data management plan template, we use the term data archive for long-term repositories. 

> Archive (noun): Curated collection or repository containing physical or digital static records, objects, metadata and
data deemed suitable for permanent retention, set up and managed to established standards and
models, such as ISAD(G), CoreTrustSeal, and the OAIS reference model, that ensure long term
integrity, security, authenticity and accessibility of the records, objects, metadata and data.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

#### Trustworthy repository, trustworthy archive
The [Science Europe Practical Guide to the International Alignment of Research Data Management](https://doi.org/10.5281/zenodo.4915862) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) provides criteria for the selection of trustworthy repositories (pages 11-14 and 26-30).
> Trustworthy repositories should meet the following minimum criteria:
> * Provision of persistent and unique identifiers (PIDs)
> 	* Allow data discovery and identification
> 	* Enable searching, citing, and retrieval of data
> 	* Provide support for data versioning
> * Metadata
> 	* Enable finding of data
> 	* Enable referencing to related relevant information, such as other data and publications
> 	* Provide information that is publicly available and maintained, even for non-published, protected, retracted, or deleted data
> 	* Use metadata standards that are broadly accepted (by the scientific community)
> 	* Ensure that metadata are machine-retrievable
> * Data access and usage licences
> 	* Enable access to data under well-specified conditions
> 	* Ensure data authenticity and integrity
> 	* Enable retrieval of data
> 	* Provide information about licensing and permissions (in ideally machine-readable form)
> 	* Ensure confidentiality and respect rights of data subjects and creators
> * Preservation
> 	* Ensure persistence of metadata and data
> 	* Be transparent about mission, scope, preservation policies, and plans (including governance, financial sustainability, retention period, and continuity plan)

#### Trusted repository
The terms trusted and trustworthy repositories can be seen as interchangeable but have been defined independent of each other.

The definition given in the [Horizon Europe Annotated Grant Agreement (v1.0, p. 373ff)](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/common/guidance/aga_en.pdf):
> Trusted repositories can be grouped into three categories which may overlap
> * Certified repositories, such as those certified by international organisations or government-authorised certification bodies (e.g. CoreTrustSeal, nestor Seal, DIN31644, ISO16363)
> * disciplinary or domain repositories commonly used and endorsed by the research communities, and which are recognised internationally
> * general-purpose repositories, institutional repositories or any other repositories that present the essential characteristics of trusted repositories, i.e.:
> 	* display specific characteristics of organisational, technical and procedural quality, such as services, mechanisms and/or provisions that are intended to secure the integrity and authenticity of their contents, thus facilitating their use and re-use in the short- and long-term. Trusted repositories have specific provisions in place and offer explicit information online about their policies, which define their services (e.g. acquisition, access, security of content, long-term sustainability of service including funding, etc)
> 	* provide broad, equitable and ideally open access to content free at the point of use, as appropriate, and respect applicable legal and ethical limitations. They assign persistent unique identifiers to contents (e.g. DOIs, handles, etc), such that the contents (publications, data and other research outputs) are unequivocally referenced and thus citeable. They ensure that contents are accompanied by metadata sufficiently detailed and of sufficiently high quality to enable discovery, reuse and citation and contain information about provenance and licensing. Their metadata is machine-actionable and standardized (e.g. Dublin Core, Data Cite, etc) preferably using common non-proprietary formats and following the standards of the respective community the repository serves, where applicable.
> 	* facilitate mid- and long-term preservation of the deposited material. They have mechanisms or provisions for expert curation and quality assurance for the accuracy and integrity of datasets and metadata, as well as procedures to liaise with depositors where issues are detected. They meet generally accepted international and national criteria for security to prevent unauthorized access and release of content and have different levels of security, depending on the sensitivity of the data being deposited, to maintain privacy and confidentiality.


### Data deposition
To deposit data means to upload the data files to a data archive. Depositing is the first step in the archiving process. Normally, depositing data includes the act of accepting a depositing agreement with the archive. So, the person doing the depositing need to have the rights (or the assigned permission) to accept the depositing agreement.


### Data preservation
 > Definition according to CODATA: "An activity within archiving in which specific items of data are maintained over time so that they can still be accessed and understood through changes in technology."
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The CODATA definition implies that data preservation is part of the objectives with data archiving. When archiving data, data files should be in persistent file formats that ensure that users are able to open them long into the future. Furthermore, data should be well described with rich metadata, following standards and possibly including a readme-file. This ensures that future users understand what information the data holds. A good description is thus also part of data preservation.

Finally, backup routines is crucial in order to avoid data loss if something unforeseen happens to the dataset.


### Data publishing
To publish data is to make data publicly available. Data publishing is commonly the same process as data archiving, including all its steps, see [Archiving](/pages/support_00_rdm_terms#Archiving). But publishing also includes the element of making data available for access with or without some restrictions. Archiving, in contrast, may be done with access for some authorised few only.

Restrictions may be defined in a license that regulates how data may be reused, like ‘non derivative’ (ND) or ‘non commercial’ (NC). Or it may be that reuse is restricted to other selected purpose(s) or user group(s), like e.g. ‘for research purpose only’. Or it may be in the form of an embargo meaning that the data is barred from access until some given future date.

Data publishing may also be done in the form of a data paper in a peer reviewed journal. Data papers are not meant to replace the role of datasets in archives nor to replace the publication of the data analyses and conclusions. A data paper may rather add value to an archived dataset and a related research article by closely describing the data and how they were collected or generated. A data paper will allow elaboration on the description of the data, beyond what a readme file may do. A data paper can therefore be seen as a bridge between the dataset and the publication of the analyses and conclusions.


### Data repository
See [data archive](/pages/support_00_rdm_terms#data-archive)


### Embargo 
> A given period of time which defines when the data will be made available in an open archive after it has been deposited already.


### FAIR principles
 > FAIR data principles: Set of guiding principles to make data Findable, Accessible, Interoperable, and Reusable.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[The FAIR principles in detail](https://www.go-fair.org/fair-principles/)


### Metadata
 > Metadata: Data about data. It is data (or information) that defines and describes the characteristics of other data. It is used to improve the understanding and use of the data.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Metadata standard
 > Metadata standard: High level, shared representation of the metadata elements related to a dataset, collection, or other digital object. May also provide an XML schema describing the format in which the elements should be stored. Typically, a standard XML format is defined using XML Schema or document type definition (DTD). Standards are typically ratified by national or international standards bodies.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Persistent identifier (PID)
> Persistent identifier: Long-lasting digital reference to an object that gives information about that object regardless of what happens to that object. Developed to address link rot, a persistent identifier can be resolved to provide an appropriate representation of an object whether that object changes its online location or goes offline. [CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Examples:
* [Digital Object identifier (DOI)](https://en.wikipedia.org/wiki/Digital_object_identifier "2024-09-09")
* [Handle](https://en.wikipedia.org/wiki/Handle_System "2024-09-09")
* Persistent URL (PURL)
* Compact identifiers for life science data resolving via [identifers.org](https://identifiers.org/)


### Personal data
> Personal data is any information that relates to an **identified** or **identifiable living individual**. Different pieces of information, which collected together can lead to the identification of a particular person, also constitute personal data.
> Personal data that has been de-identified, encrypted or **pseudonymised** but can be used to re-identify a person remains personal data and falls within the scope of the GDPR.
> Personal data that has been rendered **anonymous** in such a way that the individual is not or no longer identifiable is no longer considered personal data. For data to be truly anonymised, the anonymisation must be irreversible.
> The GDPR protects personal data **regardless of the technology used for processing that data** – it’s technology neutral and applies to both automated and manual processing, provided the data is organised in accordance with pre-defined criteria (for example alphabetical order). It also doesn’t matter how the data is stored – in an IT system, through video surveillance, or on paper; in all cases, personal data is subject to the protection requirements set out in the GDPR.
[European Commission: What is personal data?](https://commission.europa.eu/law/law-topic/data-protection/data-protection-explained_en#what-is-personal-data)

### Provenance, data lineage
 > Provenance: A type of historical information or metadata about the origin, location or the source of something, or the history of the ownership or location of an object or resource including digital objects. For example, information about the Principal Investigator who recorded the data, and the information concerning its storage, handling, and migration.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Repository
On these pages and in the affiliated data management plan template, the term 'archive' is used for long-term repositories.

> Repository: Physical or digital storage location that can house, preserve, manage, and provide access to many types of digital and physical materials in a variety of formats. Materials in online repositories are curated to enable search, discovery, and reuse. There must be sufficient control for the physical and digital material to be authentic, reliable, accessible and usable on a continuing basis.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Research data
> The term **research data** is defined in this policy to mean the registration/recording/reporting of numerical scores, textual records, images and sounds that are generated by or arise during research projects. These may, for example, be data that are generated through new analysis by combining existing secondary data, or entirely new data that are generated through new data collection.
> Research data are always a direct result of research activity, regardless of whether the data are based on secondary data or whether they are collected from scratch.
> The term **secondary data** is used in this policy to refer to data that already exist, regardless of the research to be conducted. These may comprise information collected for a different purpose (e.g. public administrative data, clinical data or weather data) or they may be physical or digital collections of objects and texts (e.g. libraries or data reused from previous projects such text corpuses or other scientific collections). Information on the Internet may also be defined as secondary data in this context, and such information is highly heterogeneous. Data which are used as secondary data in research, but which have been collected, generated or processed by other researchers or research institutions than those conducting the research, will normally not be encompassed by the guidelines in this policy.
[The Research Council of Norway’s Policy for Open Access to Research Data](https://www.forskningsradet.no/contentassets/e4cd6d2c23cf49d4989bb10c5eea087a/the-research-council-of-norways-policy-for-open-access-to-research-data.pdf)

> Research data: Data that are used as primary sources to support technical or scientific enquiry, research, scholarship, or artistic activity, and that are used as evidence in the research process and/or are commonly accepted in the research community as necessary to validate research findings and results. All other digital and non-digital content have the potential of becoming research data. Research data may be experimental data, observational data, operational data, third party data, public sector data, monitoring data, processed data, or repurposed data.
[CODATA RDM Terminology (version 2023)](https://doi.org/10.5281/zenodo.10626170) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Restricted access
> Restricted access refers to a resource that is available in a system but with some type of restriction for full open access. This type of access can occur in a number of different situations. Some examples are described below: The user must log-in to the system in order to access the resource The user must send an email to the author or system administrator to access the resource Access to the resource is restricted to a specific community.
[COAR  Controlled Vocabularies for Repositories](https://vocabularies.coar-repositories.org/access_rights/c_16ec/) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)


### Sensitive data
>  The term sensitive data is used when making data publicly available could put people, organisations, countries, and/or ecosystems at risk - this could be for example, personal or commercial information, [...]. Such data sensitivity must be protected against unauthorized access, and therefore one should be cautious when dealing with potentially sensitive or sensitive information.
[RDMkit: Data sensitivity](https://rdmkit.elixir-europe.org/data_sensitivity) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


### Special category data
> The GDPR defines special categories of personal data (‘[personal] sensitive data’) as:
> * personal data revealing racial or ethnic origin, political opinions, religious or philosophical beliefs;
> * trade-union membership;
> * genetic data, biometric data processed solely to identify a human being;
> * health-related data;
> * data concerning a person’s sex life or sexual orientation.
[European Commission: What personal data is considered sensitive?](https://commission.europa.eu/law/law-topic/data-protection/reform/rules-business-and-organisations/legal-grounds-processing-data/sensitive-data/what-personal-data-considered-sensitive_en)


### Trusted repository
See [data archive](/pages/support_00_rdm_terms#data-archive)


### Trustworthy repository
See [data archive](/pages/support_00_rdm_terms#data-archive)
