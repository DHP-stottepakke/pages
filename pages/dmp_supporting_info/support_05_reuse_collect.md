---
layout: page
<!--type: cheat_sheet-->
title: Reusing or collecting data
search_exclude: false
contributors: [Svein Høier, Jenny Ostrop, Lisbeth Jahren]
page_id: support_05_reuse_collect
description: Supporting DMP Information, reusing data, data reuse, data re-use, pre-existing data
sidebar: dmp_supporting_info
dsw:
- name: Reusing and collecting data
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=43e2efe4-016c-4a20-8b94-526ae1799afa
cessda:
- name: Discover
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/7.-Discover
- name: Research data
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Research-data
- name: Data quality
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process/Wrap-up-Data-quality
rdmkit:
- name: Existing data
  url: https://rdmkit.elixir-europe.org/existing_data
- name: "Data life cycle: Collecting"
  url: https://rdmkit.elixir-europe.org/collecting
- name: Data quality
  url: https://rdmkit.elixir-europe.org/data_quality
turing:
- name: Finding data
  url: https://book.the-turing-way.org/reproducible-research/rdm/rdm-find
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> Defining what data will be included and analysed within your project is an important core element when designing your research project. And identifying reusable data will often be a very effective way of starting the planning of a project, and thus you should always check whether existing data can be of relevance to your project.\\
>> Defining how project data will be collected will also help when defining data management roles and delegate data management in the project\\
>> Defining how data will be created, possibly reused, and flow both in and out of your project, will contribute to Open Data and Open Science practices.\\
" %}

## About this chapter
This chapter collects information about the type and origin of the data that will be included in the project. This could be both datasets or records originating outside of the project, as well as novel data collected, captured, generated or created by yourself or other project members.   

Different disciplines may use different terms to describe the data or records underlying a research project. In this chapter, an inclusive approach is used with 'data' functioning as a broad and overarching term. This includes observational and experimental data, surveys, registry data, simulations, as well as data in digital museum archives and other data records.

Depending on the discipline and specifics of a project, a data unit may already resemble what will be archived or published as a dataset, or it may undergo significant processing on the way to becoming a dataset.

## Question-specific guidance

### The project will (re)use datasets or records available in a repository/registry/archive
Many research projects are using existing digital sources for producing knowledge. For example, existing data can be used as reference, be combined with other data, and datasets can be approached with novel questions. Often, pre-existing data will be combined with novel data collected or produced in a project.

As many of the same considerations apply, also access to materials that are commonly referred to as 'records' or 'sources' rather than 'data' should be included here, such as material in public archives, media archives, legal resources, or large amounts of digital literature.

Not all data from conducted research within your research field will be open and unrestricted. But very often, even restricted and closed data(sets) of relevance can be findable by reference in publications, or by searchable metadata within registers and the like.

There can of course be a number of reasons to discard the idea of reusing data in your project, like lack of relevance for existing data etc. Taking the time to identify such reasons (when designing your project) will most often motivate the necessity of collecting new data both for yourself, project members and collaborators. If the idea of reusing data is discarded, funder guidelines ask for a brief description why building on existing sources is not relevant or applicable for the project.

You can consult the chapters on data discovery and existing data in e.g. the [RDMkit for life sciences, the CESSDA Data Management Guide, or The Turing Way handbook](support_05_reuse_collect#further-resources) for inspiration.

There is a number of different strategies that can be applied to identify existing datasets or records:
#### Scientific datasets
Useful approaches to identify scientific datasets:
* Data underlaying a research article or described in a data publication
	* Use literature search engines to track relevant datasets via research articles. Data access should be described in a data availability statement.
	* Data journals are an emerging journal genre
	* Some search engines have filter functions to search in data availability statements, e.g. [EuropePMC](https://europepmc.org/advancesearch).
* Datasets in relevant discipline-specific data archives
	* Where do researchers in the same field publish their data? Check data availability statements in publications or publication guidelines of relevant journals.
	* Curated research data registries that allow filtering of discipline: [re3data.org](https://www.re3data.org/), [fairsharing.org](https://fairsharing.org/)
* Metasearch-services for datasets. Different search engines have different advantages and disadvantages, it can be useful to compare results. Often the best choice to identify data in institutional and generic archives.
	* Non-commercial: [DataCite Commons](https://commons.datacite.org/ "2024-10-02"), [BASE (Bielefeld Academic Search Engine)](https://www.base-search.net/), [OpenAIRE research graph, filter by type](https://explore.openaire.eu/search/advanced/research-outcomes "2024-10-02")
	* Commercial: [Google Dataset Search](https://datasetsearch.research.google.com/), [Mendeley Data](https://data.mendeley.com/), [WOS Data Citation Index](https://clarivate.com/webofsciencegroup/solutions/webofscience-data-citation-index/), [Dimensions](https://app.dimensions.ai/)

#### Data from the public sector including registry data
Useful resources (non-exhaustive):
* Norwegian public data are available from [data.norge.no](https://data.norge.no)
* [data.europa.eu](https://data.europa.eu/en) is the official portal for European data
* [Google Public Data search](https://www.google.com/publicdata/directory)
* Data by international organisations, e.g. [WHO Data collections](https://www.who.int/data/collections)
* [microdata.no](https://www.microdata.no/) and [sikt.no/surveybanken](https://sikt.no/surveybanken) are Sikt services to access register data and survey data, respectively
* [helsedata.no](https://www.helsedata.no) gives access to both open health data and datasets with restricted access
* Portals for national studies such as [HUNT Cloud Data](https://hunt-db.medisin.ntnu.no/hunt-db/variablelist)
* National knowledge bases such as [artsdatabanken.no](https://www.artsdatabanken.no/search) for biodiversity or [NVE map services *Norwegian only*](https://www.nve.no/karttjenester/) for geographical data

#### Data in digital archives and collections
Useful resources (non-exhaustive):
* Library collections
* [arkivverket.no](https://www.arkivverket.no/utforsk-arkivene)
* [digitaltmuseum.no](https://digitaltmuseum.no/)
* [europeana.eu](https://www.europeana.eu/en)


### The project will collect data through observations, questionnaires or interviews
Describe the types of data to be collected through observations, questionnaires or interviews, and how data quality will be ensured.
If you are collecting data about persons, make sure to provide all necessary information in the chapter 'Legal and ethical aspects'.

Further reading:
* [CESSDA DMEG: Data in the social sciences](https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Data-in-the-social-sciences)
* [CESSDA DMEG: File formats and data conversion](https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process/File-formats-and-data-conversion)
* [CESSDA DMEG: Data entry and integrity](https://dmeg.cessda.eu/Data-Management-Expert-Guide/3.-Process/Data-entry-and-integrity)


### The project will capture data using measurement equipment
Describe how data will be collected by using measurement equipment or laboratory instruments, how experimental parameters or other relevant information are documented, and how data quality will be ensured.

Further reading:
* [RDMkit: Data provenance](https://rdmkit.elixir-europe.org/data_provenance)
* [Turing way: Electronic Lab Notebooks](https://book.the-turing-way.org/reproducible-research/rdm/rdm-elns)
* [Turing way: Data Organisation in Spreadsheets](https://book.the-turing-way.org/reproducible-research/rdm/rdm-spreadsheets)

#### How will you be keeping track of the "provenance" of the data?
To make data understandable and accurate, and the results reliable by transparency or reproducibility, it is crucial that the data origin and relevant parameters as well as all processing and filtering steps are documented. Re-users of the data also need this information to assess the data quality and decide whether the data can be used for their purpose.

If traditional lab notebooks are used, the notes should be made available in electronic form along with your data.\
For qualitative data, consider how to enhance transparency regarding data coding and analysis through documentation.\
For historical research, consider how notes and annotations can be made available along with the (data)sources.

Further reading:
* [Turing way: Electronic Lab Notebooks](https://book.the-turing-way.org/reproducible-research/rdm/rdm-elns)


#### List data that you will acquire using measurement equipment
The description of the acquired data also includes information about the instrumentation used, as this is a critical part of the data lineage and thus needs to be included in metadata and data documentation.

If using non-standard equipment or if the technology is very much under development, you may want to come back later to understand exactly how the measurements have been made. Make sure to keep copies of any documentation and for example take pictures of the instruments for documentation.

Ownership: In case measurements are not carried out by project members but at a institutional or national core facility or by an external party, make sure that formal ownership of the data has been established. Agreements should include who will take responsibility for keeping raw data safe, and who will deal with data publication. 
Remember to include information about relevant contracts in the chapter 'Legal and ethical aspects' and if applicable, specify distribution of rights in the chapter 'Data documentation during the project'.

#### Is special care needed to get the raw data ready for processing?
Be aware that information security considerations also apply for file transfer. 
Often, data is not processed at the measurement location but needs to be transferred or ingested to allow further processing. Aspects to consider include the data format to be used, whether data will be transferred via network connection or on a physical medium, and how data integrity and security will be ensured. 

For larger data volumes, it is essential to investigate network bandwidth and the transfer protocol to be used. If a physical medium is used to transfer data, writing and reading capacity and speed are important. Consider to calculate checksums to ensure that data integrity is maintained.

Further reading:
* [RDMkit: Data transfer](https://rdmkit.elixir-europe.org/data_transfer.html)
* [FAIRCookbook: How to create checksum files](https://faircookbook.elixir-europe.org/content/recipes/findability/checksum-create.html)

#### Which quality processes will be applied?
Which measures will be taken to ensure data quality? This may include calibrating instruments or measurements, including control samples, repeating measurements, standardizing data capture and documentation, data entry validation, or data peer review. In most research project, several choices will apply.

Further reading:
* [RDMkit: Data quality](https://rdmkit.elixir-europe.org/data_quality.html)


### The project will collect physical samples
Describe how cross-referencing between physical samples and digital data will be achieved. If physical samples will be preserved in a public repository (e.g. museum archive, biobank), describe where the samples will be deposited, which identifier system will be used and any access conditions.

Further reading:
* [RDMkit: Identifiers](https://rdmkit.elixir-europe.org/identifiers.html)
* [Biobank Norway](https://bbmri.no/)


### The project will generate research software, code, computational models or simulations
Research software, computational models and simulations are related to research data as a research output, yet more dynamic. Describe what will be generated during the research project. This may be everything from a few lines of code for data analysis to a more complex project or software package. 

When writing code, use systems for version control and remember to document and refer to the version of the code used for the research results. By depositing the version of the code you use in a repository, you make it easy to refer to the correct version of the code in your publication(s) using a DOI. 
For code, different licenses are used than for data and publication. If you are working on and modifying code which has already been shared by others, then best practice is to assign the same license when you share.


If writing software/models is a significant part of the research project, you can consider writing a Software Management Plan (SMP) to supplement this DMP.
* [Elixir Software Management Plan](https://smw.dsw.elixir-europe.org/wizard/knowledge-models/smw:smp:0.0.18)

The FAIR for Research Software (FAIR4RS) RDA working group defines research software as "source code files, algorithms, scripts, computational workflows and executables that were created during the research process or for a research purpose" ([Gruenpeter et al. 2021, doi: 10.5281/zenodo.5504016](https://doi.org/10.5281/zenodo.5504016)). The FAIR for Research Software (FAIR4RS) principles have been adapted from the FAIR principles to fit the characteristics of software/code ([Barker et al. 2022, doi: 10.1038/s41597-022-01710-x](https://doi.org/10.1038/s41597-022-01710-x), [Lamprecht et al. 2020, doi: 10.3233/DS-190026](https://doi.org/10.3233/DS-190026)).

Further reading:
* [Turing way: Version control](https://the-turing-way.netlify.app/reproducible-research/vcs.html)
* [Software Carpentry: Version control with git](https://swcarpentry.github.io/git-novice/)
* [Turing way: Reproducible environments](https://book.the-turing-way.org/reproducible-research/renv)
* [Turing way: Code quality](https://book.the-turing-way.org/reproducible-research/code-quality)
* [GitHub integration to Zenodo](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)


### Other types of data the project will gather
What other types of documents will the project utilize or produce, which have not been captured by the previous categories?

For some projects that handle little data, this may be the only applicable category.


### Who else could be interested in us in using data from this project?
Thinking through who could be interested in the data that is used or produced in a research project, contributes to the project's impact and can motivate good data management practices.
