---
layout: page
<!--type: cheat_sheet-->
title: Archiving and publishing data
search_exclude: false
contributors: [Leif Longva, Jenny Ostrop]
page_id: support_08_preserve_publish
description: Supporting DMP Information, preservation strategy, preserve data, data preservation, publish data, data publication, repository, open access, closed access, data sharing
sidebar: dmp_supporting_info
dsw:
- name: Archiving and publishing data
  uuid: knowledge-models/research.data.no:norway-generic:latest/preview?questionUuid=a549d10b-aa46-4c0c-863f-30219ac5ecce
cessda:
- name: Archive & Publish
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/6.-Archive-Publish
rdmkit:
- name: Data publication
  url: https://rdmkit.elixir-europe.org/data_publication
- name: Identifiers
  url: https://rdmkit.elixir-europe.org/identifiers
turing:
- name: Sharing and Archiving Data
  url: https://book.the-turing-way.org/reproducible-research/rdm/rdm-sharing
other:
- name: "GOFair: FAIR principles"
  url: https://www.go-fair.org/fair-principles/
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> Research data is valuable – they should be available for reuse.\\
>> Archiving ensures availability of data for yourself at a later time point, e.g. after switching affiliations.\\
>> Rich metadata and usage of trustworthy data archives will make the data findable through search engines. 
>> Good documentation, structured metadata and a license will enable others to understand the information held in the data and enable data reuse.\\
>> Research funders and academic publishers commonly require data underlying a study to be available ('as open as possible').\\
>> Increasingly, archiving FAIR data is viewed as equally important as publishing other research output, in the assessment of research.\\
" %}

## About this chapter
Research data is valuable. Collecting or generating data may require significant effort. Making data available for reuse in an ongoing process to build new knowledge, is thus the right thing to do, economically as well as research ethically, to ensure the value of the data is maximised. It is therefore important to follow good practice in how to preserve data and make data accessible for future use. This is done by use of archives (also called repositories) where data is organised in files with formats that we trust to be accessible also long into the future. And moreover, the data need to be described well, so that there is no ambiguity to what information the data holds, including all relevant circumstances and conditions that may have had impact when the data was collected or generated. Description of the data is often done in a so called ‘readme’ file entered along with the data files, in addition to attaching rich metadata that holds information on the data.

This chapter will assist you in walking through the planning steps of making the data available in line with the FAIR principles, including selecting an archive to publish the data (or, if needed, archiving with access restrictions) and providing appropriate metadata. The chapter includes both questions that should be considered at the initial stage of the DMP, and questions to be answered towards the end of the research project to plan the fate of data in the project, whether they will be deposited in a research data archive, preserved in other ways, or in certain cases will be discarded.

### Trustworthy research data archives
The process of selecting archive to use is therefore important, to ensure best archival practice and the quality of the data. The most important issue to look for is whether the archive is a trustworthy one, that is either certified with e.g. the CoreTrustSeal or the ISO 16363 standard or are disciplinary or domain repositories that are widely endorsed and supported by research communities and are recognized on an international scale.  Prerequisites for trusted archives include a curation procedure. Curation should be done in cooperation between archive curators and the depositing researcher to ensure the data is preserved in preferred file formats and accompanied by good description and rich metadata.

There are different types of archives you may use for research data. Disciplinary archives are designed to suit data from specific subject areas. These may use metadata standards and metadata schema that are best suited to capture important information on data from such a specific subject area. Then there are institutional data archives. These archives are designed to capture data from any subject area the institution handles. Have a look whether your institution offers such an archiving service. A benefit for you in choosing an institutional archive would be that your institution has good user support to ensure the quality of the archived data. Furthermore, there are 'catch all' archives, meaning archives where both scholarly publications as well as data may be archived. If you do not have access to use a data archive, you may consider using a catch all archive like [Zenodo](https://zenodo.org/).

You may browse or search for suitable archives in the [re3data registry](https://www.re3data.org/), which is a registry of data archives. The [FAIRsharing service](https://fairsharing.org/) is also a useful a searchable resource that holds information on data archives, as well as standards and data policies. Both resources have filtering functions.

You are advised to choose a so-called [trustworthy archive](/pages/support_00_rdm_terms#trustworthy-repository-trustworthy-archive) for the data that meets minimum criteria on provision of persistent and unique identifiers (PIDs), metadata, data access and usage licenses, and data preservation. A common certification is the [Core Trust Seal](https://www.coretrustseal.org/) which certifies that the archive in question operates in accordance with the Core Trust Seal quality criteria, both in terms of its financial foundation and its quality assuring data curation routines.

Data should be archived as open as possible and as closed as necessary, as is the guiding principle commonly referred to by research funders and others. This means that data archiving does not necessarily mean to make data openly available. When archiving data in a certified archive, the data is preserved for the future according to best practice. The issue of publishing data is a separate question. Remember: Make your data as open as possible, and as closed as necessary. See [Chapter 3](/pages/support_03_legal_ethics) of these guidelines for more on the issue of data that needs protection from public access. And this too is an important issue when selecting where to archive the data: If data need access control, which archive is well suited for this?

### Restricted access to research data
Some data should not be made openly available, according to law regulations (including the General Data Protection Regulation (GDPR) and/or ethical considerations. These may be data with person identifying information, or data that are [sensitive for other reasons](/pages/support_03_legal_ethics#sensitive-data) including national security or intellectual property rights. It may still be important to ensure their long term preservation and regulate data access beyond the project period. In many cases data can be archived with restricted access, enabling access only to eligible actors.

Archives with restricted access in Norway:
* [Sikt archive](https://sikt.no/en/archiving-research-data) for data about people and society
* [FEGA (Federated European Genome-phenome Archive)](https://ega.elixir.no/) is designed to help researchers securely store, access, and share sensitive human data across multiple countries, while adhering to local privacy regulations
* [CLARINO](https://repo.clarino.uib.no/xmlui/) is Norway's part of the European CLARIN infrastructure network, which stands for Common Language Resources and Technology Infrastructure. CLARINO includes a platform where researchers can store, share, and access language data in standardized formats. This also includes access with restricted access, since language research easily includes person identifying data.

[Data Use Ontology](https://www.ga4gh.org/product/data-use-ontology-duo/) is a service that may be useful for data that cannot be openly available. This service is especially developed for sensitive human data.

### Persistent identifiers
When deciding where to archive the data, make sure you chose an archive where the dataset is assigned a persistent identifier (PID). Two commonly used PIDs are Digital Object Identifier (DOI) and handle. With a PID assigned, you are guaranteed that the dataset may be referred to with correct identifier for findability. The (not uncommon) problem of URLs that stop working for some reason is then avoided. Archives assigning DOIs is also a sign of quality, since there is minimum requirements to the metadata schema used in order to acquire a DOI.


## Question-specific guidance

### Can all of the data become completely open over time?
As discussed above, research data should be made available, and preferably at an early stage, unless there are legal or ethical reasons for limiting the access. So, one of the first issues to clarify, is whether the data, all of it or part of it, can be made openly available, or if there need to be set an embargo period before opening access to the data. If no such legal or ethical considerations are valid, data should be archived as open as possible and as closed as necessary, and also as early as possible.\
If the data is background data for a scientific publication, normally it should be made available no later than at the time of publishing the article.

The chapter 'Legal and ethical aspects' may help to identify criteria for deciding whether (part of) the data needs to be restricted from public access. You should consider whether such parts may be anonymized or aggregated so that such a version of the data can be openly available. Data that cannot be openly available, may still be made available with restricted access. In this case it is particularly important to be aware of required steps from project start.

If certain datasets cannot be made available or only be made available under restricted access conditions, please explain why, clearly separating legal and contractual reasons from intentional restrictions.


### Identify archive(s) for depositing datasets
This question, and its sub-questions, will assist you in finding archive(s) suitable to deposit (publish) the data.

Where do you plan to archive the research data? Remember that this can also include project results, or background material that you not immediately are thinking of as 'data'. As archive choice often decides what metadata standards to be followed, it is advisable to investigate this question early in the project. When identifying alternative archives to use, have a look at the metadata schema they use, to see if it is suitable to describe the data.

Timely archiving of datasets in [trustworthy repositories](/pages/support_08_preserve_publish#trustworthy-research-data-archives) is recommended. Depending on the study and the type of data, it may be appropriate to archive everything in one repository or archiving different parts in different repositories that will link to the related datasets. 

Evaluate which archive(s) will be most relevant for the datasets, using the following the decision tree:

    1) Does the dataset contain personal data or sensitive information?
    [If yes, investigate discipline-specific or generic archives with restricted access.]

    2) Do journals or funders require that specific archives will be used or is there disciplinary conventions regarding the choice of archive?
    [If yes, make yourself familiar with the recommendations and use discipline-specific archives.]

    3) Can you use an institutional archive?
    [If yes, use your institutional archive.]

    If none of the above applies, use a generic research data archive, or possibly a multipurpose archive accepting both data and other type of outputs.\
	
[Re3data](https://www.re3data.org/) and [FAIRsharing](https://fairsharing.org/) are registries that may help you identify suitable repositories. For multipurpose repositories, see the [Generalist Repository Comparison Chart](https://doi.org/10.5281/zenodo.7946938).

In some cases, it is important to contact the research data archive beforehand. If dataset submission needs to be clarified with the repository, this should be done well ahead of data deposition.


### List data that you have deleted or will delete
Determining which data are of value and should be preserved or whether data need to or can be deleted, is a decision that should be taken actively. If data(sets) are or will be deleted, they can be listed in this question, including a brief description of the reasons for deletion. There may be legal (e.g. defined by the Health Research Act) or contractual obligations to delete data.

Generally, institutions and research funders set requirements to retain data for a given period. For example, the Research Council of Norway "has stipulated as a requirement that research data must be stored in a safe and secure manner for a minimum of 10 years" [(Policy for Open Science, 2020)](https://www.forskningsradet.no/siteassets/forskningspolitisk-radgivning/apen-forskning/nfr-policy-open-science-eng.pdf). On the other hand, the Research Council of Norway states that research projects "should explicitly address how research data that are not considered to have long-term value should be managed, or if relevant destroyed, after a certain period of time." [(Policy for for Open Access to Research
Data, 2017)](https://www.forskningsradet.no/contentassets/6ccb7b14c18a48ee974acd78fc64efba/the-research-council-of-norways-policy-for-open-access-to-research-data.pdf)

So, it can be worthwhile to consider which data in a project are not of value (e.g. data from failed experiments), only have intermediate value (e.g. during data analysis) and which data should be preserved long-term. This is particularly important if storage of large amounts of data is associated with significant costs. However, take into consideration that data not considered to be of any value for your present need, may turn out to be of value to others, or even to yourself, sometime into the future.


### List datasets that you have archived or will archive
Archiving of datasets includes the deposition of datasets in a research data archive, openly or with restricted access. Open data as well as data that should be archived with access restrictions should be equipped with a persistent identifier (PID). As mentioned above, research data should be made available at an early stage, following the principles "as open as possible, as closed as necessary". Funders and research institutions may specify more exact guidelines for this. E.g. the guidelines from the Research Council of Norway states that data underlying scientific articles should be made accessible latest at publication. Other research data should be made accessible within a reasonable amount of time, and never later than three years after the project has ended [(Policy for open access to research data, 2017)](https://www.forskningsradet.no/contentassets/e4cd6d2c23cf49d4989bb10c5eea087a/the-research-council-of-norways-policy-for-open-access-to-research-data.pdf).

Several of the sub-questions here let you refer to information in other chapters of your DMP or in external databases. When relevant, you can enter a free-text answer.

#### Which metadata and documentation accompanies the dataset?
Explain to the best of your knowledge what metadata (what metadata standard) is used for the dataset. Here you may reuse information from the metadata standard question in the 'Data documentation' chapter.

Metadata are an essential part of a dataset and provide the contextual information that is needed to understand the dataset. In many cases, deciding for a research data archive will also decide over the metadata standard used. 

Metadata is structured information about a dataset (or a document). _How to_ structure the information is done in various ways. Different metadata schemas are designed to capture the information, and such a schema is called a metadata standard. A metadata standard may be designed to suit a subject domain or a specific research area. There are, naturally, different information needs to describe a dataset with biological data, compared to a dataset which revolves on social sciences.
A metadata schema may capture information using controlled vocabularies or ontologies to avoid ambiguity. That way, information will be standardised and not be disrupted by different persons using different words or typology for same issues. Such a standardisation will preferably refer to ontologies from a given subject domain, which also helps to avoid misunderstandings if a term is used differently in different disciplines. The use of controlled vocabularies and ontologies will increase the quality and findability of the archived data.
Note that you here may reuse the answer from chapter VI: 'Data documentation during the project'.

#### Where has the data been, or where will the data be archived?
You should already have identified suitable archives in the 'Identify archive(s)' question above. Thus, you may reuse the information you entered there.

As mentioned above, archives to use should be 'trustworthy'. If you for some reason decide to use an archive not qualified as trustworthy, please consider closely what preservation policy the archive follows. Look for information on this in the 'About' section of the archive, and contact the archive if still in doubt.

In case data is not deposited to an archive but should be preserved locally beyond the project period, it is very important to define a preservation plan and who will be responsible.

In case data is not deposited to an archive but should be preserved locally beyond the project period, it is very important to define a preservation plan and who will be responsible.

#### Under which license will the dataset be made available?
As mentioned above, the preferred choice is to archive data 'as open as possible', where open refers to both accessibility and reusability. So, you should archive the data with an open license and thus as few restrictions as possible added. Even if in doubt if a dataset will be considered 'original' work, assigning a license is best practice to clarify reuse terms.\
See also the information on licensing in the chapter [Data documentation during the project](/pages/support_06_document#will-a-license-be-assigned-to-the-data-as-early-as-possible).

* [CC0 (No rights reserved)](https://creativecommons.org/public-domain/cc0/) is a permissive license often used for data. 
* [CC BY (Attribution)](https://creativecommons.org/share-your-work/cclicenses/) is a license also much used. CC BY requires referring to the author(s) of a dataset for its reuse. 
* [Public Domain Mark (PDM)](https://creativecommons.org/public-domain/pdm/) should be uses if the data are public domain material, typically very old material. This expresses that there are no known copyright to the material.
* [NLOD Norwegian Licence for Open Government Data](https://data.norge.no/nlod/en/2.0) is not an international license, and therefore less suitable for research data. If you use data licenses with NLOD these can be re-published under CC BY, attributing the original licensor.

Note that the CC BY clause may unintentionally restrict reuse of data if someone wants to include large amounts of data from numerous datasets. In such a case referring correctly to all the authors may be an insurmountable challenge. 
For research referring correctly to the dataset, also if data is licensed CC0 or Public Domain Mark, corresponds to good scientific norms. 

For information on Creative Commons licenses, see [https://creativecommons.org/](https://creativecommons.org/).


### FAIR data checklist
No matter whether the data may be published openly or not, it is always a question of making the research data FAIR - or rather as FAIR as possible. FAIR is an acronym for Findable, Accessible, Interoperable, Reusable and the [FAIR principles (2016)](/pages/support_08_preserve_publish#further-resources] describe a set of criteria to be met.\
The checklist can assist you in remembering the relevant elements:
* Archived datasets have persistent identifiers
* Archived datasets are indexed and findable in search engines
* Rich metadata is available for the archived datasets
* Metadata remains available even if data should be deleted
* Conditions for accessing the archived datasets are specified
* The file formats used in archived datasets support interoperability
* Controlled vocabularies/ontologies are used to describe data and datasets
* Datasets link to related information where relevant
* Datasets are assigned a license that define conditions for reuse
* The archive will guarantee future availability and reuse of the datasets

There are also online tools available for this purpose:
* [FAIRAware by DANS](https://fairaware.dans.knaw.nl/)


### If applicable: List research software/computational models/simulations you will be publishing
Research software as project result is related to research data, yet more dynamic. Research software can be anything from a few lines of code to a professionally developed software package.
The FAIR for Research Software (FAIR4RS) principles have been adapted from the FAIR principles to fit the characteristics of software/code ([Barker et al. 2022, doi: 10.1038/s41597-022-01710-x](https://doi.org/10.1038/s41597-022-01710-x), [Lamprecht et al. 2020, doi: 10.3233/DS-190026](https://doi.org/10.3233/DS-190026)).

Parts of these considerations are taken from the [Elixir Software Management Plan](https://smw.dsw.elixir-europe.org/wizard/knowledge-models/smw:smp:0.0.18) [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Further reading:
* [fair-software.nl: Five recommendations for FAIR software](https://fair-software.nl/home/)
* [Code Refinery: Social coding and open software - What can you do to get credit for your code and to allow reuse](https://coderefinery.github.io/social-coding/)
* [Software Carpentry: Version control with git - Open Science](https://swcarpentry.github.io/git-novice/10-open.html)
* [Turing way: Open source software](https://book.the-turing-way.org/reproducible-research/open/open-source)
* [Turing way: Licensing](https://book.the-turing-way.org/reproducible-research/licensing.html)
* [FAIRCookbook: Software Licensing](https://w3id.org/faircookbook/FCB033)
