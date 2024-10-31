---
layout: page
<!--type: cheat_sheet-->
title: Preserving and publishing data
search_exclude: false
contributors: [Leif Longva, Jenny Ostrop]
page_id: support_08_preserve_publish
description: Supporting DMP Information, preservation strategy, preserve data, data preservation, publish data, data publication, repository, open access, closed access, data sharing
sidebar: dmp_supporting_info
dsw:
- name: Preserving and publishing data
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=a549d10b-aa46-4c0c-863f-30219ac5ecce
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
>> Your data is valuable – they should be available for reuse.\\
>> Archiving data is also a way to ensure availability of data for yourself at a later time point, e.g. after switching affiliations.\\
>> Rich metadata will make your data findable through search engines. Good documentation and structured metadata will enable others to understand the information held in your data and enable data reuse.\\
>> Comply with requirements by research funders and academic publishers to making data underlying a study available.\\
>> Increasingly, archiving FAIR data is viewed as equally important as publishing other research output, in the assessment of research.\\
" %}

## About this chapter
Research data should be archived and preserved, for the benefit of future research and to ensure research transparency. Data should be archived as open as possible and as closed as necessary, as the guiding principle of research funders and others states. This chapter will assist you in walking through the steps of making your data available in line with the FAIR principles, including selecting an archive to publish your data and providing appropriate metadata.

The chapter includes both questions that should be considered at the initial stage of the DMP, and questions to be answered towards the end of the research project to document the fate of data in the project, whether they are deposited in a research data archived, will be preserved in other ways, or in certain cases be discarded.

### Trustworthy research data archives
*brief introduction to discipline-specific, institutional and generic research data archives. Explain re3data and FAIRSharing.*

### Restricted access to research data
*brief explanation of restricted access, examples in Norway: Sikt, FEGA, CLARINO*

*mention Data Use Ontology, Data Use Conditions*

### Persistent identifiers
*what does the term mean and why are they important*

## Question-specific guidance

### Can all of your data become completely open over time?
Research data should be made available at an early stage and latest at publication. However, there can be reasons to delay data publication with an embargo period or (some of) your data is of a nature that should not be made openly available. The chapter 'Legal and ethical aspects' may help to identify criteria for deciding whether part of your data need to be restricted from public access. Consider whether such parts may be anonymized or aggregated so that such a version of your data can be openly available. Data that cannot be openly available, may still be made available with restricted access. In this case it is particularly important to be aware of required steps from project start.

If certain datasets can not be made available or only be made available under restricted access conditions, please explain why, clearly separating legal and contractual reasons from intentional restrictions.


### Identify archive(s) for publishing datasets
*add figure for flow chart*

This question, and its sub-questions, will assist you in finding archive(s)/repository(-ies) suitable to deposit your data.

Where do you plan to archive you research data? Remember that this can also include project results that you are not immediately thinking of as 'data'.
As archive choice often decides over metadata standards to be followed, it is advisable to investigate this question early in the project.

Timely archiving of datasets in trustworthy repositories is recommended. Depending on the study and the type of data, it may be appropriate to archive everything in one repository or archiving different parts in different repositories that will link to the related datasets. Re3data and FAIRsharing are registries that may help identifying suitable repositories.

Evaluate which archive(s) will be most relevant for your datasets, using the following the decision tree:

    1) Does your dataset contain personal data or sensitive information?
    [If yes, investigate discipline-specific or generic archives with restricted access]

    2) Do journals or funders require that specific archives will be used or is there disciplinary conventions?
    [If yes, make yourself familiar with the recommendations and use discipline-specific archives]

    3) Can you use an institutional archive?
    [If yes, use your institutional archive]

    If none of the above applies, use a generic research data archive.

In some cases it is important to contact the research data archive beforehand. 

*elaborate*
*make sure trustworthy repository is explained in terms and linked to*

### List data that you have deleted or will delete
Determining which data are of value and should be preserved or whether data need to or can be deleted, is a decision that should be taken actively. If data(sets) are deleted, they can be listed in this question, including a brief description of the reasons for deletion.

There may be legal (e.g. defined by the Health Research Act) or contractual obligations to delete data.

Generally, institutions and research funders set requirements to retain data for a given period. For example, the Research Council of Norway "has stipulated as a requirement that research data must be stored in a safe and secure manner for a minimum of 10 years" [(Policy for Open Science, 2020)](https://www.forskningsradet.no/siteassets/forskningspolitisk-radgivning/apen-forskning/nfr-policy-open-science-eng.pdf). On the other hand, the Research Council of Norway states that research projects "should explicitly address how research data that are not considered to have long-term value should be managed, or if relevant destroyed, after a certain period of time."[(Policy for for Open Access to Research
Data, 2017)](https://www.forskningsradet.no/siteassets/forskningspolitisk-radgivning/apen-forskning/nfr-policy-open-science-eng.pdf)

Yet, it can be worthwhile to consider which data in a project are not of value (e.g. data from failed experiments), only have intermediate value (e.g. during data analysis) and which data should be preserved long-term, particularly if storage of large amounts of data is associated with significant costs.


### List datasets that you have archived or will archive
Archiving of datasets includes the deposition of datasets in a research data archive, openly or with restricted access, and equipped with a persistent identifier (PID) as well as data that should be preserved but not published. Research data should be made available at an early stage, following the principles as "as open as possible, as closed as necessary". According to the guidelines by Research Council of Norway should data underlying scientific articles be made accessible latest at publication. Other research data should be made accessible within a reasonable amount of time, and never later than three years after the project has ended [(Policy for open access to research data, 2017)](https://www.forskningsradet.no/contentassets/e4cd6d2c23cf49d4989bb10c5eea087a/the-research-council-of-norways-policy-for-open-access-to-research-data.pdf).

Several sub-questions allow to refer to information in other DMP chapters or external databases. Alternatively, it is always possible to enter a free-text answer.

#### Which metadata and documentation accompanies the dataset?
*write something about standards and use of ontologies*

#### Where has the data been archived?
*write something about preservation strategy if you are NOT using a trustworthy repository*

#### Under what license will the dataset be made available?
*write something about license selection*

### FAIR data checklist
No matter whether your data may be published openly or not, it is always a question of making your data FAIR - or rather as FAIR as possible. FAIR is an acronym for Findable, Accessible, Interoperable, Reusable and the [FAIR principles (2016)](/pages/support_08_preserve_publish#further-resources] describe a set of criteria to be met.\
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