---
layout: page
<!--type: cheat_sheet-->
title: Get started with DMP writing
search_exclude: false
contributors: [Svein Høier, Jenny Ostrop]
page_id: support_00_start_writing
description: Supporting DMP Information, DMP writing, Data Stewardship Wizard, DSW, User guide
sidebar: dmp_supporting_info
---

{% include callout.html type="note" content="
**On this page**\\
>> Short user guidance to DMP questionnaire\\
>> Supporting information for filling out the DMP (by DMP chapter)\\
" %}

## Get started with writing your Data Management Plan in Data Stewardship Wizard
After logging in for the first time, you will have to start by creating a project. Simply said, the different plans you have worked on for your research projects over time are listed as “projects” in DSW. So, projects are in some sense equivalents to plans that you are working on. Please start, as a first step, by creating a new project (plan), and use a good title for later revisions.

Projects/ planning drafts are auto-saved, details can be seen under “Projects” – last edited. Management of your plans, editing, revisions, exports – it all starts here. You can also think of listed projects as a set of listed documents you are working on, in a simplified sense. 

The second step is to choose a proper title for your planning project, and then the defining step: choosing a project template to use for your project. A project template present you with a questionnaire in the project workspace, as well as a set of default values, so you don't have to start from scratch. Select the questionnaire variant that fits your project best.   

### Choose the right project template for your project
<code> The described setup refers to the pre-defined templates in the [ELXIR Norway DSW testing instance](https://dsw-test.elixir.no/). If using another instance, see section Advanced setup. </code>
To accommodate different project needs, you will have access to four different project templates in this setup. Select the questionnaire variant that fits your project best.

For externally funded projects:
* **Science Europe/RCN and ELSI** questionnaire is a comprehensive questionnaire for projects with external funding and/or external partners. Handling of sensitive data or personal data or requiring ethical pre-application can be addressed or marked as not relevant to the project. This questionnaire is in line with the Science Europe DMP guidance and thus meeting the requirements of research funders such as the Research Council of Norway or Horizon Europe.
* **Science Europe/RCN and ELSI and HPC** is a variant with additional questions for computationally demanding projects.

For less complex projects:
* **Minimum** questionnaire covers a core set of questions adapted to less complex projects (e.g. student projects). This questionnaire is suited for projects without external funding or external project partners. For less complex projects that are handling sensitive data or personal data or requiring ethical pre-application, see below.
* **Minimum and ELSI** combines the **Minimum** questionnaire with questions on handling sensitive data or personal data or requiring ethical pre-application.

{% include image.html file="dsw_project.png" caption="Select project template" alt="Screenshot project template selection menu" %}

#### Advanced setup of questionnaire
For other combinations or specific needs (e.g. writing an 'umbrella DMP') or transferring answers from one questionnaire to another questionnaire variant, contact [support staff at your institution](/pages/support_00_local_disc). Advanced users can customize the questionnaire within the framework of the knowledge model, select questions by tags, and configure the document template and other settings.


### Fill out the questionnaire
You will find a description of the core steps below. For more detailed descriptions, see the [instructional video](https://www.youtube.com/watch?v=XrI8qYtWSBw ) and the [user guidance](https://guide.ds-wizard.org/en/latest/application/projects/list/detail/questionnaire.html) by DSW.

Answering the questionnaire is done in three steps:
1. Choose the project phase (in the drop-down menu on top of the left navigation pane): Initial DMP (the first version), Midway DMP (revising the DMP and adding more information), or Complete DMP (concluding the project and reporting results).
2. Select the chapter. There are nine DMP chapters focussing on different aspects. It is recommended to fill in chapters in a chronological order.
3. Answer the questions. The navigation bar to the left can be used actively to jump between questions without scrolling. For additional information, the links in the questionnaire lead to the question-specific [Supporting Information for Users](/pages/dmp_supporting_info/).

{% include image.html file="dsw_phases.png" caption="1. Select project phase: Initial, midway or complete DMP, 2. Select the chapter, 3. Answer questions" alt="Screenshot with 1. Phase selection menu: Initial, midway or complete DMP, 2. Chapter selection, 3. Questionnaire" %}

There is different types of questions:
* Free-text or values (e.g. numerical, url, date)
* Multi-choice: select one or several choices
* Options: select one option and answer follow-up questions, if they exist. Use "Clear answer" to remove choice. Follow-up questions can be collapsed.
* List of items: click "+Add" for any new item. Items with their follow-up questions can be collapsed by clicking on the v arrow symbol, if several items are present they can be simultaneously collapsed or expanded. Item order can be changed and the bin symbol deletes an item.
* Item-select: refer to an item in another question by selecting it from the drop-down menu. This requires that the original question is filled in.

#### Controlling what is presented in the questionnaire tab
**View** – note that you can control what is presented in the user interface. By default, only questions desirable the chosen project phase are visible and question tags are hidden.

{% include image.html file="dsw_view.png" caption="View: Change visible features" alt="View menu allows to view or hide question tags and other features." %}


### Other tabs and export options
Use the square button on the right hand side to hide or view the navigation pane.

{% include image.html file="dsw_navigation.png" caption="The navigation pane" alt="Screenshot navigation pane" %}

#### Project sharing and commenting
The 'Share'-button opens a dialogue to share the project (plan) with collaborators by inviting them individually with defined reading and writing rights, or sharing by providing a link. The TODO- and the comment function (to the right of each question) can be used to communicate about the project.

#### The Metrics tab
This tab show your metrics, connected to how much of the plan that is finished.\
Other types of FAIR/openness metrics are not supported in the current knowledge model, yet technically possible.

#### The Preview tab
Use the preview tab for previewing your finalised plan as you go along. 

#### The Documents tab 
Use the Documents tab to export finalised plans in different formats. Currently, html and pdf are supported.

#### The Settings tab
Here you can change the document template and document format, as well as settings that again defines your preview and function as default values for exporting finalised plans. 
