---
layout: page
<!--type: cheat_sheet-->
title: Get started with DMP writing
search_exclude: false
contributors: [Svein Høier, Jenny Ostrop]
page_id: support_00_start_writing
description: Supporting DMP Information, DMP writing, Data Stewardship Wizard, DSW, User guide
sidebar: dmp_supporting_information
dsw:
- name: About the Data Management Plan
  uuid: knowledge-models/research.data.no:norway-generic:latest/preview?questionUuid=7ed9939b-b85c-48bf-87f5-2aa081bb5267
other:
- name: DSW User Guidance
  url: https://guide.ds-wizard.org/en/latest/application/projects/list/detail/questionnaire.html
---

{% include callout.html type="note" content="
**On this page**\\
>> Short user guidance to DMP questionnaire\\
>> Supporting information for filling out the DMP (by DMP chapter)\\
" %}

## Write your Data Management Plan in Data Stewardship Wizard/ FAIR Wizard
The DMP questionnaire is implemented in the DMP tool **Data Stewardship Wizard (DSW)**/ **FAIR Wizard** (DSW as software-as-a-service). It is available on the following instances:
* Researchers at NTNU, UiB, UiO og UiT can use the pilot instance [FAIR Wizard Norway](https://norway.fair-wizard.com/). The direct links on this web resource are linking to this instance. For support, contact your [local research data support](/pages/support_00_local_disc).
* Life Science Researchers at all Norwegian institutions can use the [DSW instance provided by ELIXIR Norway](https://elixir.no/services-2/data-stewardship-wizard). To use the template, follow the advanced setup instructions. For support, contact the [ELIXIR Norway helpdesk](https://elixir.no/helpdesk).
* [Other FAIR Wizard and Data Stewardship Wizard instances in Norway](/dmp_wizard/)

## Start with a new DMP
Simply said, the different plans you have worked on for your research projects over time are listed as **Projects** in Data Stewardship Wizard/ FAIR Wizard. So, projects are in some sense equivalents to DMPs that you are working on.

After logging in for the first time, you will have to start by creating a project: Use the 'Start your DMP' shortcut or start from the Projects menu.
It is recommended to choose a descriptive title for the project that makes it easy to identify it for later revisions. 

{% include image.html file="dsw_start.png" caption="Create a project: Use the 'Start your DMP' shortcut or start from the Projects menu. " alt="Screenshot side navigation" %}

Projects/ planning drafts are auto-saved, details can be seen under **Projects** – last edited. Management of your plans, editing, revisions, exports – it all starts here.

### Choose the right project template
<code> The described setup refers to the pre-defined templates on FAIR Wizard Norway. For the ELIXIR Norway DSW instance, see instructions for advanced questionnaire setup.</code>

To accommodate different project needs, you have by default access to four different project templates, in addition to a [pre-project/ pre-award questionnaire](/pages/support_00_planning_considerations). A project template present you with a questionnaire in the project workspace, as well as a set of default values, so you don't have to start from scratch. Select the questionnaire variant that fits your project best.

{% include image.html file="dsw_project.png" caption="Select project template" alt="Screenshot project template selection menu" %}

For externally funded projects:
* **Science Europe/RCN and ELSI** ![Static Badge](https://img.shields.io/badge/Wizard-ELSI-%231abc9cff) is a comprehensive questionnaire for projects with external funding and/or external partners. Handling of sensitive data or personal data or requiring ethical pre-application can be addressed or marked as not relevant to the project. This questionnaire is in line with the Science Europe DMP guidance and thus meeting the requirements of research funders such as the Research Council of Norway. 
* **Science Europe/RCN and ELSI and HPC** ![Static Badge](https://img.shields.io/badge/Wizard-ELSI-%231abc9cff) ![Static Badge](https://img.shields.io/badge/Wizard-HPC-%238e44adff) is a variant with additional questions for computationally demanding projects.

For less complex projects:
* **Minimum** questionnaire covers a core set of questions adapted to less complex projects (e.g. student projects). This questionnaire is suited for projects without external funding or external project partners. For less complex projects that are handling sensitive data or personal data or requiring ethical pre-application, see below.
* **Minimum and ELSI** ![Static Badge](https://img.shields.io/badge/Wizard-ELSI-%231abc9cff) combines the **Minimum** questionnaire with questions on handling sensitive data or personal data or requiring ethical pre-application. 

#### Advanced questionnaire setup 
Instead of starting with one of the pre-defined project templates, it is also possible to configure them and additional options based on the underlying knowledge model. Follow the instructions below if you are using the [ELIXIR Norway DSW instance](https://elixir.no/services-2/data-stewardship-wizard).

To use one of the above described templates:
1. Start with *From knowledge model* and select **Norwegian DSW Knowledge Model**
2. In the next step, select *Filter by question tags* and then combine the tags **RCN/ Science Europe** or **minimum** with **ELSI** ![Static Badge](https://img.shields.io/badge/Wizard-ELSI-%231abc9cff) (Ethical and legal aspects, ELSI = **E**thical, **L**egal and **S**ocial **I**mplications") and/ or **HPC** ![Static Badge](https://img.shields.io/badge/Wizard-HPC-%238e44adff) (for computationally demanding projects).

{% include image.html file="dsw_advanced.png" caption="View: Advanced setup" alt="Advanced setup allows to customize questionnaire based on question tags. Selected tags on the screenshot: Science Europe/RCN and ELSI." %}

Advanced users can customize the questionnaire within the framework of the knowledge model, select questions by tags, and configure the document template and other settings. It is also possible to transfer ("migrate") answers between the questionnaire variants. Contact [support staff at your institution](/pages/support_00_local_disc) for help.

Further tags are present in the knowledge model for additional customization or specific needs:
* umbrella DMP: Selection of questions for [umbrella DMPs](/pages/difficult_faq#a-research-centreresearch-consortium-needs-a-dmp), overarching DMPs for large consortia/research centres [not thoroughly tested, yet]
* for internal use within this project/ the research institution: maDMP, IT security, cross institutional project, Horizon Europe


## Fill out the questionnaire
You will find a description of the core steps below. For more detailed descriptions, see the [instructional video](https://www.youtube.com/watch?v=XrI8qYtWSBw ) and the [user guidance](https://guide.ds-wizard.org/en/latest/application/projects/list/detail/questionnaire.html) by DSW.

Answering the questionnaire is done in three steps:
1. Choose the project phase (in the drop-down menu on top of the left navigation pane): Initial DMP (the first version), Midway DMP (revising the DMP and adding more information), or Complete DMP (concluding the project and reporting results). NB! There are additional questions added in each phase. To see all questions, check the 'Non-desirable questions' under **View** (see below). 
2. Select the chapter. There are nine DMP chapters focussing on different aspects. It is recommended to fill in chapters in a chronological order.
3. Answer the questions.

There is different **types of questions**:
* Free-text or values (e.g. numerical, url, date). Free-text fields can be enlarged by dragging in the lower right corner.
* Multi-choice: select one or several choices
* Options: select one option and answer follow-up questions, if they exist. Use "Clear answer" to remove choice. Follow-up questions can be collapsed.
* List of items: use "+Add" button for any new item. Items with their follow-up questions can be collapsed by clicking on the v arrow symbol, if several items are present they can be simultaneously collapsed or expanded. Item order can be changed and the bin symbol deletes an item.
* Item-select: refers to an item in a previous question by selecting it from the drop-down menu. NB! This requires that the original question is filled in.

{% include image.html file="dsw_phases.png" caption="1. Select project phase: Initial, midway or complete DMP, 2. Select the chapter, 3. Answer questions" alt="Screenshot with 1. Phase selection menu: Initial, midway or complete DMP, 2. Chapter selection, 3. Questionnaire" %}

### Smart navigation
The chapter navigation pane to the left can be used actively to jump between questions without scrolling. Follow-up questions and item lists can be collapsed/ expanded using the black arrow symbols in the navigation pane.

{% include image.html file="dsw_smart.png" caption="Use arrows in the navigation pane on the left hand side for smart navigation" alt="Screenshot of the question Contibutor(s) in the chapter 'About the DMP', with two contributors added. Contributor are named 'Contributor A' and 'Contributor B' added. The follow-up questions (Name, E-mail address, ORCID Identifier etc.) for 'Contributor A' are expanded and for 'Contributor B' minimized." %}

#### Consulting additional information
For additional information, the links in the questionnaire lead to the question-specific [Supporting Information for Users](/pages/dmp_supporting_info/).

{% include image.html file="dsw_supporting.png" caption="Links to question-specific supporting information" alt="Screenshot of external link to question-specific supporting information." %}

#### Controlling what is presented in the questionnaire tab
**View** – note that you can control what is presented in the user interface. By default, only questions desirable the chosen project phase are visible and question tags are hidden.

{% include image.html file="dsw_view.png" caption="View: Change visible features" alt="View menu allows to view or hide question tags and other features." %}


## Export documents and collaborate on the DMP
Functions for exporting the DMP and collaboration are found in the top navigation bar. Use the square button on the right hand side to hide or view the navigation pane.

{% include image.html file="dsw_navigation.png" caption="The navigation pane" alt="Screenshot navigation pane" %}

### Collaborating on the DMP
The 'Share'-button opens a dialogue to share the project (plan) with collaborators. Collaborators with an account on [FAIR Wizard Norway](https://norway.fair-wizard.com/), can be searched for by name and assigned rights (Viewer/ Commenter/ Editor/ Owner). In addition, link sharing (with reading/ commenting/ editing rights) can be enabled for example to share with external collaborators.\

{% include image.html file="dsw_sharing.png" caption="Contributors can be invited individually or through link sharing and assigned reading, commenting or editing rights" alt="Screenshot of the 'Share'-dialogue." %}

The TODO- and the comment function (to the right of each question) can be used to communicate about the project. The **TODO** and **Comments tabs** (under the 'Share'-button) can be used to navigate them and get an overview.

{% include image.html file="dsw_communicate.png" caption="TODOs and Comments can be added by using the buttons on the right hand side. They can also be navigated in the top pane. UUID links can be used to refer to a specific question." alt="Screenshot of the TODO, Comments, and UUID buttons"%}

### Exporting documents
Use the **Preview tab** for previewing your finalised plan as you go along. The default format can be changed in the **Settings tab** (see below).

Use the **Documents tab** to download finalised plans in different formats. Use the 'New document'-button for any new document. Click on the three dots on the right hand side to download or delete a document from the list.

Useful: DMP versions can be named in the **Version history** tab (under the 'Share'-button).

{% include image.html file="dsw_export.png" caption="Different export formats can be generated from the 'Documents' tab" alt="Screenshot of document export." %}

### The Settings tab
Here you can change:
* The internal DMP name and description
* The default export and preview format (document template)
* Migrate to another version of the questionnaire (knowledge model)

#### The Metrics tab (disabled in FAIR Wizard Norway)
Metrics on completeness of the DMP and FAIR/ openness metrics are not supported in the current knowledge model, yet technically possible.
