---
layout: page
<!--type: cheat_sheet-->
title: Legal and ethical requirements, codes of conduct
search_exclude: false
contributors: [Live Kvale, Jenny Ostrop]
page_id: 4_legal_ethics
description: Legal requirements, ethical requirements, codes of conduct
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

<!--Science Europe question ID & title-->
## 4a - If personal data are processed, how will compliance with legislation on personal data and on data security be ensured?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
Personal privacy is here addressed purely from a legal perspective, if working with personal data this should also be addressed under 4c ethical issues. 
Processing of personal data and or health data affects the need for data security in the project, make sure this is appropriately addressed under [3. storage and backup 3b.3](3_storage_backup#3b---how-will-data-security-and-protection-of-sensitive-data-be-taken-care-of-during-the-research).

[Test the Ethics and data protection decision tree from European Commission](https://ec.europa.eu/assets/rtd/ethics-data-protection-decision-tree/index.html "2024-01-22")

For the legal details in Norway, please consult:
* [Personal Data Act](https://lovdata.no/dokument/RFA/lov/2000-04-14-31)
* Regulations on the processing of personal data [Forskrift om behandling av personopplysninger](https://lovdata.no/dokument/SF/forskrift/2018-06-15-876)
* Transitional rules on the processing of personal data [Overgangsregler om behandling av personopplysninger](https://lovdata.no/dokument/SF/forskrift/2018-06-15-877)
* [The Norwegian Data Protection Agency: Journalistic, academic, artistic and literary purposes](https://www.datatilsynet.no/regelverk-og-verktoy/lover-og-regler/personvern-vs.-ytringsfrihet/)
* [The Norwegian Data Protection Agency: Code of Conduct on Information Security and Internal Control](https://www.datatilsynet.no/regelverk-og-verktoy/atferdsnorm/)

If conducting health research, consult the [Health Research Act](https://lovdata.no/dokument/LTI/lov/2008-06-20-44) and the [Health Registry Act](https://lovdata.no/dokument/NL/lov/2014-06-20-43).

In this context also the following laws and regulations might be relevant:
* [Regulations on the organization of medical and health research](http://www.lovdata.no/for/sf/ho/ho-20090701-0955.html)
* [Comments to health research legislative work by the Norwegian government](http://www.regjeringen.no/nb/dep/hod/dok/lover_regler/forskrifter/2009/helseforskningsloven.html?id=570542)
* [Regulations on population-based health surveys](https://lovdata.no/dokument/SF/forskrift/2018-04-27-645)
* [Health Personnel Act](http://www.lovdata.no/all/nl-19990702-064.html)
* [Patient and User Rights Act](http://www.lovdata.no/all/nl-19990702-063.html)
* [Medicines Act](http://www.lovdata.no/all/nl-19921204-132.html)
* [Regulations on clinical trials of medical products for human use](http://www.lovdata.no/for/sf/ho/ho-20091030-1321.html)
* [Biotechnology Act (on the medical use of biotechnology)](https://lovdata.no/dokument/NL/lov/2003-12-05-100)
* [e-helse Direktoratet: “Normen”: Norms for health research data](https://www.ehelse.no/normen/normen-dokumenter/Veileder-i-personvern-og-informasjonssikkerhet-i-forskningsprosjekter)


> 4a.1\
> Ensure that when dealing with personal data data protection laws (for example GDPR) are complied with:

According to GDPR there are two options for legal bases for processing of personal data in research, consent and general interest in research purposes, if the later is used consent is collected for compliance with ethical guidelines.
[Consult SIKTs guidance for Legal bases for personal data processing in research](https://sikt.no/en/tjenester/personverntjenester-forskning/personvernhandbok-forskning/legal-bases-personal-data-processing-research) 
[Consult SIKTs guidance for information and consent](https://sikt.no/en/fylle-ut-meldeskjema-personopplysninger/information-participants-research-projects "2024-01-23")
Also Consult your institutions requirements for notification forms for personal data, DData Protection Impact Assessments (DPIAs) risk and compliance system or similar




> 4a.2\
> Gain informed consent for preservation and/or sharing of personal data.

Please note that the specific 'consent' under GDPR as a legal basis is not equivalent with 'informed consent' in the context of health research. For more information please consult the [Opinion 3/2019 concerning the Questions and Answers on the interplay between the Clinical Trials Regulation (CTR) and the General Data Protection regulation (GDPR)](https://edpb.europa.eu/our-work-tools/our-documents/opinion-art-70/opinion-32019-concerning-questions-and-answers_en) of the European data protection board.

If consent is used as legal basis for processing of personal data consider asking for permission to archive the data for the purpose of future research, and possibly also educational purposes as part of both the informed and specific consent. It is advisable to use standard consent clauses, which can be reflected with maschine readable metadata (See e.g. the [GA4GH ethical toolkit](https://www.ga4gh.org/our-products/#{%22product%22:{%22related_work_streams%22:%22Regulatory%20&%20Ethics%20Work%20Stream%20(REWS)%22}}) as an example for human genetic data)


> 4a.3\
> Consider anonymisation of personal data for preservation and/or sharing (truly anonymous data are no longer considered personal data).

The relevance of anonymisation will depend on the data type and other available information

[Consult the Norwegian data protections agency guidance for data anonymisation "2024-01-23"](https://www.datatilsynet.no/en/regulations-and-tools/reports-on-specific-subjects/anonymisation/)

> 4a.4\
> Consider pseudonymisation of personal data (the main difference with anonymisation is that pseudonymisation is reversible).

Pseudonymisation is removal of names and other directly identifiable information, and follows the principle of data minimisation, removing or not collection more personal information than strictly necessary for the purpose. This includes the storage of information for re-identifaction in a separate system, which is not accessible for the researchers.

> 4a.5\
> Consider encryption which is seen as a special case of pseudonymisation (the encryption key must be stored separately from the data, for instance by a trusted third party).

Ignore this, encryption should be addressed under 3 storage and backup

> 4a.6\
> Explain whether there is a managed access procedure in place for authorised users of personal data.

Make sure this is addressed under storage and backup, in addition consider who should have and manage access at and archiving stage.

If the data should be available for future research contact the archive you wish to deposit the data in and make sure that you collect the correct consents at data collection, so that the data can be archived and used for future research when the project period is over. If data should be archived later under controlled access, the data access committee should be defined as early as possible and should be independent from the researcher. 

#### Sufficiently adressed (DMP Evaluation Rubric)
- Clearly indicates if personal data will be collected/used as part of the project, and, if applicable, how compliance with applicable legislation will be ensured (for example by gaining informed consent, considering encryption, anonymisation, or pseudonymisation). 
- Describes the procedure to manage access to only authorised users.

```
**Relevant PID**
- REK ID, ID SIKT personverntjenester
- Ontology terms reflecting data protection (e.g. [Informed Consent Ontology (ICO)](https://www.ebi.ac.uk/ols4/ontologies/ico), [Data Use Ontology](Data Use Ontology), [W3 Data Privacy Vocabulary (DPV)](https://w3c.github.io/dpv/dpv/)

**Interested stakeholder**
- Level 1: Host institution/data owner (information security, risk reduction)
- Level 2: REK, SIKT personverntjenester, DPO or legal experts

**Relevant project phase**
- pre-award: outline
- planning post-award, active phase

```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#ethical_issues_description_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_description_tree): "To describe ethical issues directly in a DMP" [string, free text]
- [#ethical_issues_exist_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_exist_tree): yes/no/unknown
- [#ethical_issues_report_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_report_tree): "To indicate where a protocol from a meeting with an ethical commitee can be found"

[Properties in dataset]
- [#dataset_personal_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#dataset_personal_data_tree): yes/no/unknown
- [#dataset_sensitive_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_sensitive_data_tree): yes/no/unknown
- [#security_privacy_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#security_privacy_table): nested, see below

[Properties in security and privacy]
- [#properties-in-security_and_privacy](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#properties-in-security_and_privacy): description [string, free text], name [string, free text]
- [#dataset_sensitive_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_sensitive_data_tree): yes/no/unknown

Missing:
- Description of legal issues
- Identification of ethical/legal issues at dmp level

---
<!--additional explanations-->
### Explanations for support staff
- local storage guidelines (consider list with links?)
- NB! encryption is problematic for long-term preservation (e.g. NFR guidance)

- National regulations of potential relevance:
### Data privacy
* [Personal Data Act](https://lovdata.no/dokument/RFA/lov/2000-04-14-31)
* Regulations on the processing of personal data [Forskrift om behandling av personopplysninger](https://lovdata.no/dokument/SF/forskrift/2018-06-15-876)
* Transitional rules on the processing of personal data [Overgangsregler om behandling av personopplysninger](https://lovdata.no/dokument/SF/forskrift/2018-06-15-877)
* [The Norwegian Data Protection Agency: Journalistic, academic, artistic and literary purposes](https://www.datatilsynet.no/regelverk-og-verktoy/lover-og-regler/personvern-vs.-ytringsfrihet/)
* [The Norwegian Data Protection Agency: Code of Conduct on Information Security and Internal Control](https://www.datatilsynet.no/regelverk-og-verktoy/atferdsnorm/)

### Health research data

* [Health Research Act](https://lovdata.no/dokument/LTI/lov/2008-06-20-44)
* [Regulations on the organization of medical and health research](http://www.lovdata.no/for/sf/ho/ho-20090701-0955.html)
* [Comments to health research legislative work by the Norwegian government](http://www.regjeringen.no/nb/dep/hod/dok/lover_regler/forskrifter/2009/helseforskningsloven.html?id=570542)
* [Health Register Act](https://lovdata.no/dokument/NL/lov/2014-06-20-43)
* [Regulations on population-based health surveys](https://lovdata.no/dokument/SF/forskrift/2018-04-27-645)
* [Health Personnel Act](http://www.lovdata.no/all/nl-19990702-064.html)
* [Patient and User Rights Act](http://www.lovdata.no/all/nl-19990702-063.html)
* [Medicines Act](http://www.lovdata.no/all/nl-19921204-132.html)
* [Regulations on clinical trials of medical products for human use](http://www.lovdata.no/for/sf/ho/ho-20091030-1321.html)
* [Biotechnology Act (on the medical use of biotechnology)](https://lovdata.no/dokument/NL/lov/2003-12-05-100)
* [e-helse Direktoratet: “Normen”: Norms for health research data](https://www.ehelse.no/normen/normen-dokumenter/Veileder-i-personvern-og-informasjonssikkerhet-i-forskningsprosjekter)

### Other laws of potential relevance to life sciences research data

* [Archive Act](https://lovdata.no/dokument/NL/lov/1992-12-04-126)
* [Research Ethics Act](https://lovdata.no/dokument/NL/lov/2017-04-28-23)
* [Patent Act](https://lovdata.no/dokument/NL/lov/1967-12-15-9)
* [Copyright Act](https://lovdata.no/dokument/NL/lov/2018-06-15-40)
* [Act on Universities and Colleges Act](https://lovdata.no/dokument/NL/lov/2005-04-01-15)
* [National Security Act](https://lovdata.no/dokument/NL/lov/2018-06-01-24)

- What is personal data & special category personal data, which laws & guidelines apply, responsibilities (e.g. DPO)
- If personal data is processed, which legal bases for data processing is used (usually relevant: public intrest or consent)?
- If research is legal basis for data processing, then consent is is part of 4c below.
- Use data minimisation as a strategy to avoid unwanted privacy breaches. 
- Explain whether there is a managed access procedure in place for authorised users of personal data. - ensure that this aspect is covered under storage [3B: How will data security and protection of sensitive data be taken care of during the research?](3_storage_backup)

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
- How are GDPR and the Personal Data Act complied with when handling/ processing personal data?
- Is informed consent for long-term preservation and possibly sharing of personal data used?
- Is anonymization, pseudonymization or encryption of personal data being considered for long-term preservation and/or sharing?
- Should a managed procedure be used for authorized access to personal data?
(Rights and legal requirements and codes of conduct)

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[6. Ethics]
- Are there, or could there be, any ethics or legal issues that can have an impact on data sharing? These can also be discussed in the context of the ethics review. If relevant, include references to ethics deliverables and ethics chapter in the Description of the Action (DoA).
- Will informed consent for data sharing and long term preservation be included in questionnaires dealing with personal data?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

- For guidance on access, see 5a.

---
<!--additional explanations - only keywords-->
### Explanations for users
- National regulations
- Personal data, special categories of personal data
- GDPR legal basis (behandlingsgrunnlag)
- Data minimization principle
- informed consent, granular consent
- health data
- de-identification - pseudonymisation
- anonymization


--
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP Guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
If your project includes personal data (any information relating to an identified or identifiable person), consider using the NSD DMP tool.
 To ensure compliance with GDPR, all projects with personal data are required to send a notification form describing all relevant elements of the planned data processing to Norwegian Centre for Research Data (NSD)/SIKT for an assessment. (The only exception: health research projects at the Faculty of Medicine and Health Sciences.)

 All projects with personal data must perform a risk assessment before data collection begins. 
 Relevant documents:
 Collection of personal data for research projects (NTNU)

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
Which data will be preserved, and which will be destroyed at the end of the project?

Will (a selection of) the data be long-term preserved, and how is this decided? (According to section 4.2 in the UiT guidelines, researchers have to assess the long-term value of their data, and describe how they will be managed.)

Will the data be made openly available? If only a selection of the data will be openly available, specify which data. (According to section 1 in the UiT guidelines, research data shall be made openly available, unless considerations regarding security, personal privacy, commercial or legal issues demand limitation of access.)

Does the material contain confidential information (e.g. personal data and data with security classification) that requires special treatment and/or limits the access to the material during/after the project?]
 Why is this important? If the material contains confidential information, you must guarantee that it’s protected from unauthorised access. Contact your organization’s IT security office to make sure that data are handled correctly for their information classification level (see the paragraph above).

### [University of Bergen (UiB)](https://www.uib.no/en/personaldata/130126/privacy-policy-university-bergen), also available [in Norwegian](https://www.uib.no/personvern)

### [University of Oslo (UiO)](https://www.uio.no/english/for-employees/support/privacy-dataprotection/personal-data-in-research.html)

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

**Does the material contain confidential information (e.g. personal data and data with security classification) that requires special treatment and/or limits the access to the material during/after the project?**
*Why is this important?* 
If the material contains confidential information, you must guarantee that it’s protected from unauthorised access. Contact your organization’s IT security office to make sure that data are handled correctly for their information classification level (see the paragraph above).
 
**If the research project will include processing of personal data, the research subjects need to receive thorough and transparent information about the data processing. The legal basis for processing personal data for research purposes is, for the most part, public interest. This means that the researcher can process personal data, but that a data controller is required to supply thorough information about how the data are processed.**
*Why is this important?* 
The General Data Protection Regulation (GDPR) regulates on which legal grounds personal data can be lawfully processed. One requirement is that the research subjects receive thorough information about which personal data will be processed and how they will be processed in the project. This means that the research subjects are informed about for what purpose and on what legal grounds the processing will be made. By giving the research subjects information about the personal data processing, they gain insight into and control over what information about them is processed.
 
**How will the research subjects’ identities be protected?**
*Why is this important?*
Protecting the personal integrity of research subjects (see the General Data Protection Regulation, GDPR) is a fundamental principle in research and an important ethical responsibility to the participants in a research project. During the project, data that contain personal information need to be securely stored, in compliance with the guidelines at your university/organization.
 Research material may also contain special category personal data that need to be classified to protect the integrity of research subjects. Therefore, it’s important to have routines for how to handle requests to access personal data in accordance with the principle of public access to information. When the project is finished and the data material shall be made accessible, it’s also important to guarantee that the individuals in the study cannot be re-identified (i.e. identified through indirect identifiers in the data material). This can be done by de-identification measures or pseudonymisation of the data, such as coding or encryption.
 
**Has the personal data processing been reported to the data protection officer, in compliance with the research principal’s policies?**
*Why is this important?*
Research material that will contain personal data has to be reported to the data protection officer. The research principal is legally obligated (GDPR, Article 30) to keep a record of all projects where personal data are processed.

#### [10 steps towards privacy compliance in research](https://zenodo.org/records/10417514) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
1. Keep the GDPR in mind when designing your research: Do you need to collect personal data, why, and how much?
2. Make sure you have a legal basis to use personal data, e.g., public interest or consent
3. Document privacy risks and privacy-related decisions, e.g., in a Data Management Plan, privacy scan, or Data Protection Impact Assessment
4. Arrange ethics review. Ethics review makes sure that you have also taken ethical implications into account
5. Inform participants properly, e.g., in an information letter, oral script, privacy statement
6. Protect your data with organisational measures, e.g., access control, agreements with external parties, data protection policies, researcher training
7. Protect your data with technical measures, e.g., anonymise, pseudonymise, encrypt your data, use safe storage
8. Enable participants to exercise their rights, e.g., right to data access, correction, objection, erasure
9. FAIR data: balance risks and Open Science principles, e.g., share under restricted access, or only share metadata and materials
10. Ask for help when you need it! Contact your privacy officer or data steward for support


-----
-----
<!--Science Europe question ID & title-->
## 4b - How will other legal issues, such as intellectual property rights and ownership, be managed? What legislation is applicable?

<!--key information-->
### [Science Europe Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
If relevant also export control, protection of cultural heritage (Kulturminneloven), commercial interests. etc. should be discussed here.

> 4b.1\
> Explain who will be the owner of the data, meaning who will have the rights to control access:

If personal data involved: owner of the data is "data controller" as defined in GDPR.
In regards to intellectual property rights: who owns it?

Please also note that 

> 4b.2\
> Explain what access conditions will apply to the data? Will the data be openly accessible, or will there be access restrictions? In the latter case, which? Consider the use of data access and re-use licenses.

Applies to both access control in the active phase and restricted access after data publication.
Re-use can be limited by licenses or other reuse terms (e.g. data use ontology, informed consent ontology, data privacy vocabulary, Data Tags Suite)

> 4.b.3\
> Make sure to cover these matters of rights to control access to data for multi-partner projects and multiple data owners, in the consortium agreement.

Important to cover this in collaborative agreements.
Legal requirements for data processor and joint data controller agreements.

> 4.b.4\
> Indicate whether intellectual property rights (for example Database Directive, sui generis rights) are affected. If so, explain which and how will they be dealt with.

Also relevant for artistic research.

> 4.b.5\
> Indicate whether there are any restrictions on the re-use of third-party data?

Is there restrictionst to re-use in the active phase of the project? Is there restrictions to sharing project results?

#### Sufficiently adressed (DMP Evaluation Rubric)
Clearly explains, if applicable:
- Who will have the rights to control access to which part of the data.
- What access conditions and re-use licenses will apply to the data.
- Clearly explains, if applicable, how intellectual property rights will be managed.
- Explains for multi-partner projects and multiple data owners how these matters are addressed in the consortium agreement.
- Alternatively, there is a clear statement that there are no such restrictions on the data.
- Indicates, if applicable, whether there are any restrictions on the re-use of thirdparty data.

```
**Relevant PID**
- country codes, laws, document ids of contracts/collaborative agreements, licenses of re-used data

**Interested stakeholder**
- Level 1: Host institution/data owner (risk reduction)
- Level 2: Possibly ITA, DPO or legal experts, REK

**Relevant project phase**
- pre-award: outline
- planning post-award, active phase
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039)
[Properties in dataset]
- [#dataset_sensitive_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_sensitive_data_tree): yes/no/unknown

Missing:
- legal issues such as IPR are hardly covered?


---
<!--additional explanations-->
### Explanations for support staff
- legislation, legal challenges (e.g. different legislations and GDPR)
- Export control, eksportkontrollloven
- IPR
- Cultural heritage, kulturminneloven
- commercial interests, patents, contact to local TTO
- collaborative agreement best practice, how are they referred to
- Åndsverkloven, arkivloven
- Report How should we share research data

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
- Which legal entities have rights to and/or rights to determine the use of the research data? 
- Will the data be openly accessible or with access restrictions, if so, what access restrictions? One example is that access to data is only granted via an authentication service. 
- Will there be any purpose restrictions, such as that the data can only be used for non-commercial purposes, and if so, why? 
- Which dedications to public domain or licenses should be applied to the research data? 
- Where the project involves several partners and/or several legal or natural persons with rights to research data; How should rights to control data access be managed in the project? 
- Where the research data falls under copyright or database protection under the Copyright Act; What rights apply and how will this be managed in the project? When using data from a third party; What access and purpose restrictions, if any, apply to this data? (Rights and legal requirements and codes of conduct)

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
- not covered

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- For guidance on access, see 5a.


---
<!--additional explanations - only keywords-->
### Explanations for users
- legislation, legal challenges (e.g. different legislations)
- possible restrictions, where to find information
- ethics resources at their institutions (list with links?)
- IPR at their institutions (list with links)
- commercial interests, patent applications and implications
- licensing

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Consider who will have ownership and/or rights to the data (including copyright), meaning who will have the rights or responsibility to control access, and later decide publishing. In general, if the research project is conducted by NTNU employees, NTNU will have ownership to results and IPR (see the IPR policy, part 4.3), The Policy for Open Science at NTNU states that results from research at NTNU should made publicly available if possible (for Licensing principles see part 3.1 in Guidelines for Open Science). Therefore, consider what data (and other results, like code, models, simulations etc) be openly accessible after the project is finalized, or will there be access restrictions? In the latter case, what restrictions and why?
 
If there are external partners, how will this affect ownership and sharing of data and other intellectual property rights (IPR)? Make sure to cover these matters of rights to control access to data for multi-partner projects and multiple data owners, in the consortium agreement. See wiki for more information on templates and agreements.
 
Note that in some cases, export control regulations will apply to the project results. See Control of knowledge transfer at Innsida for more information.

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
Who has ownership of the data? (Normally UiT, unless ownership has been agreed on differently e.g. with external collaborators.)

How will the data be licensed for reuse? (According to section 4.5 in the UiT guidelines, research data shall be equipped with licenses for access, reuse, and dissemination. These licenses should be internationally recognised and set as few limitations on the data as possible. The researcher must ensure that licenses and applicable conditions for the use or sharing of third party data are complied with.)

#### [SIKT](https://sikt.no/en/data-management-plan)
Generally, the rights to project results should be transferred from the researchers (and possibly others who have helped create such results) to the institution(s) where the researchers are employed. This is in accordance with the Employees’ Inventions Act, and in accordance with the objectives of the Act relating to universities and university colleges (see in particular §1-5, Academic freedom and responsibility). See also the Norwegian Research Council’s Policy on Intellectual Property Rights.

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Refer to the information security guidelines and policies in your university/organization and define what implications they have. What information classification level does the data material have and what security measures are needed to protect the material? Who should have access to the project data during the project and how do you plan to protect the data from unauthorised access?]
Why is this important? Access to the data material must be restricted so that authorised people can access it, but it is protected from unauthorised access. Secure work and storage environments can include access restriction (e.g. passwords), encryption, and virus and access protection. You may need to contact your organization’s IT security office to make sure that you have addressed all questions regarding information security before the data collection begins.
 
[Are there any copyright and/or intellectual property rights to consider? Do you need permission to collect the material that is going to be used?]
Why is this important? Copyright is protected in the Swedish constitution (Chapter 2, Article 19) and regulated in the Act (SFS 1960:729) on Copyright in Literary and Artistic Works. Copyright sets out a number of rights for the creator (author) of a work, and a number of limitations for the user. The Swedish Copyright Act regulates when and how the author’s work can be used. Permission to use copyright-protected material includes consent, agreements, licenses, and the permission to use material after the duration of copyright has passed (>70 years).


-----
-----
<!--Science Europe question ID & title-->
## 4c - How will possible ethical issues be taken into account, and codes of conduct followed?

<!--key information-->
### [Science Europe Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 4c.1\
> Consider whether ethical issues can affect how data are stored and transferred, who can see or use them, and how long they are kept.

Make sure this is appropriately addressed under [3. storage and backup 3b.3](3_storage_backup)

> 4c.2\
> Demonstrate awareness of these aspects and respective planning. Follow the national and international codes of conducts and institutional ethical guidelines, and check if ethical review (for example by an ethics committee) is required for data collection in the research project.

Does your institution have ethics committees?

[Veileder institusjonenens ansvar forskingsetikk](https://www.forskningsetikk.no/ressurser/veileder-om-institusjonenes-ansvar-for-forskningsetikk/)

Be aware of e.g. CARE principles - reflect on and consult communites, Nagoya protocol, RRI
Consider to list relevant agreements that will be followed e.g. Helsinki declaration on health data, 

[EU/H2020's guidelines on How to complete your ethics self-assessment.](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/common/guidance/how-to-complete-your-ethics-self-assessment_en.pdf)

#### Sufficiently adressed (DMP Evaluation rubric)
- Provides details of what ethical issues have been considered that may affect data storage, transfer, use, sharing and/ or preservation, and demonstrates that adequate measures are in place to manage ethical requirements.
- Mentions, if applicable, whether ethical review is being pursued. If ethical approval has been obtained, refers to the relevant committee and documents.
- Refers to relevant ethical guidelines and/or codes of conduct or alternatively provides a clear statement that explains why ethical issues have not been considered.

```
**Relevant PID**
- country codes, laws, document ids of contracts/collaborative agreements, licenses of re-used data

**Interested stakeholder**
- Level 1: Host institution (compliance with research ethics)
- Level 2: Possibly core facility (animal facility, sequencing facility)
- Level 3: Affected communities

**Relevant project phase**
- pre-award: outline
- planning post-award, active phase
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039)
[Properties in dmp]
- [#ethical_issues_description_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_description_tree): "To describe ethical issues directly in a DMP" [string, free text]
- [#ethical_issues_exist_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_exist_tree): yes/no/unknown
- [#ethical_issues_report_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#ethical_issues_report_tree): "To indicate where a protocol from a meeting with an ethical commitee can be found"

[Properties in dataset]
- [#dataset_personal_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard#dataset_personal_data_tree): yes/no/unknown

Missing:
- ethical approvals
- references to ethical guidelines

---
<!--additional explanations-->
### Explanations for support staff
- RRI
- [Forskningsetikkloven](https://lovdata.no/dokument/NL/lov/2017-04-28-23)
- [Veileder institusjonenens ansvar forskingsetikk](https://www.forskningsetikk.no/ressurser/veileder-om-institusjonenes-ansvar-for-forskningsetikk/)
- Nesh m venner
- Animal experiments: FOTS, 3R principles
- [Ethics and governance of artificial intelligence for health])https://iris.who.int/bitstream/handle/10665/375579/9789240084759-eng.pdf?sequence=1)
- [National Research Ethics Committees Q&A: Lew privacy legislation - what does this imply for research *Norwegian only*](https://www.forskningsetikk.no/ressurser/gdpr/)
- CARE - reflect on and consult communites 
- Nagoya protocol
- [Animals use for scientific purposes *Norwegian only*](https://www.forsoksdyrkomiteen.no/ressurser/)
- [Indigenous data, consent](https://www.ohchr.org/sites/default/files/Documents/Issues/IPeoples/FreePriorandInformedConsent.pdf)

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Rights and legal requirements and codes of conduct]
- What ethical issues can affect how data is stored and transferred, who has data access to view or use the data, and how long it should be kept?
- Which institutional, national and/or international guidelines for research ethics apply to the project? Examples may be approval from regional committees for medical and health research ethics (REK) or the Norwegian Food Safety Authority.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
- not covered

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- Explicitly state in your metadata when access to the data needs to be limited due to ethical reasons. Include information on how to request access when this is possible an mention the contact details of the rights holder.
- In case data cannot be publicly shared due to ethical reasons, make sure you do still publish the accompanying metadata.
- For more guidance on licensing and access, see 5a.


---
<!--additional explanations - only keywords-->
### Explanations for users
Awareness of ethical issues and implications, relevant documents
Local ethical resources and boards

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [NTNU - DMP Guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Is an ethical review (for example by an ethics committee/REK or approval of use of experimental animals) required for data collection in the research project?

#### [UiT - DMP guidance](https://en.uit.no/research/research-dataportal/art?p_document_id=726373)
Are you going to collect informed consent to store and share the data? If so, how? How are you going to secure confidentiality and identity protection?

#### [SIKT](https://sikt.no/en/data-management-plan)
Add any comments on issues related to for example: research on human embryos and fetuses, and/or human cells and tissues; collection of personal data and obtaining consent; animal research; research in non-EU countries; unintended effects on the environment, health and safety; and the potential misuse of research results. See also [EU/H2020's guidelines on How to complete your ethics self-assessment.](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/common/guidance/how-to-complete-your-ethics-self-assessment_en.pdf)

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
How will you manage the rights of the data you use, produce and share? (2.2) Describe how you will agree upon the rights of use related to your research data – including the collected, produced and (re)used data of your project. Here, you can employ your categorisation in the first question. Each of these categories involves different rights and licenses. Describe the transfer of rights procedures relevant to your project. Describe confidentiality issues if applicable in your project. License your data! Tips for best practices:

* Agreements on rights of use should be made as early as possible in the project life cycle.
* Have you gained consent for data preservation and sharing? • Follow the funder's or publisher's policies.
* It is recommended to make all of the research data, code and software created within a research project available for reuse, e.g., under a [Creative Commons](https://creativecommons.org/choose/), [GNU](https://www.gnu.org/licenses/gpl-3.0.en.html) or [MIT license](https://opensource.org/licenses/MIT), or under another relevant license.

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Does the project need ethical approval or has it been approved? Enter the reference number here.]
 Why is this important?
 Research that falls under the scope of the Act (2003:460) concerning the Ethical Review of Research Involving Humans (the Ethical Review Act, updated 2020-01-01) can only be carried out after ethical approval, which is applied for by the research principal. Without ethical approval, the research is illegal and subject to legal consequences. Ethical approval is also needed for research that involves animal testing.
