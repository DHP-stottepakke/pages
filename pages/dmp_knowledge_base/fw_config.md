---
layout: page
<!--type: cheat_sheet-->
title: Configuration of norway.fair-wizard instance
search_exclude: false
contributors: [Jenny Ostrop, Elin Stangeland]
page_id: fw_config
description: FAIR Wizard, instance, configuration
affiliations: 
sidebar: background_knowledge
toc: true
---

This quick-start-guide lists steps in configuring a FAIR Wizard or DSW instance to achieve a similar configuration as the instance [norway.fair-wizard.com](/pages/dmp_wizard/#users-from-ntnu-uib-uio-uit). The page aims to support colleagues who are starting to use the tool and wish to set similar configuration settings to our instance.

[FAIR Wizard](https://fair-wizard.com/) is the software-as-a-service version of the Open Source DMP tool [Data Stewardship Wizard (DSW).](https://ds-wizard.org/). In addition to the Data Management Planner (which equals DSW), FAIR Wizard contains the module Admin Center, Integration Hub, and Analytics.\
The detailed user guide is available under [https://guide.fair-wizard.com/en/production/](guide.fair-wizard.com/).

## Appearance of the instance
[User guide](https://guide.fair-wizard.com/en/production/applications/admin-center/settings/user-interface/index.html)
* Instance settings
	* **Admin Center** > System Settings > Organization: Fill out description field
	* **Admin Center** > System Settings > Features: We have disabled AI Assistant and Tours
* Authentication settings: We use SAML with Feide
	* **Admin Center** > Settings > User Interface > Authentication > SAML/ Shibboleth
	* Tip: Consider if users should be able to login while you are still setting up things
* Provide information about your instance, login options, and available support on the login screen
	* **Admin Center** > Settings > User Interface > Dashboard & Login Screen: Add Login Info and Sidebar Login Info
		* Tip: Add info to re-route users who wish to use [other Norwegian instances](/pages/dmp_wizard/)
	* **Admin Center** > Settings > User Interface > Dashboard & Login Screen: Option to add announcements on dashboard and/or announcements, e.g. to inform about the pilot or updates
*  Customize the appearance
	* **Admin Center** > Settings > User Interface > Lock & Feel: Instance name, logo and color profile contribute to making the instance recognizable
		* Tip: Use different colors for production and preview instance
	* **Admin Center** > Settings > User Interface > Lock & Feel: Set custom menu links. See our setup below. *NB! This setting has to be done both in Admin Center and Data Management Planner*

{% include image.html file="config_menu.png" caption="Custom menu link setup." alt="Screenshot of user interface settings (left) and appearance for user (right): Start your DMP, DMP Supporting Information, Get help, Provide feedback." %}

---
## Data Management Planner
[User guide](https://guide.fair-wizard.com/en/production/applications/data-management-planner/index.html)
* Set custom menu links
	* **Data Management Planner** > Settings > User Interface > Menu: See above
* Settings for project visibility and sharing
	* **Data Management Planner** > Settings > Content Settings > Projects: Our settings below
		* Project visibility: enabled
		* Default project visibility: Private
		* Project sharing: enabled
		* Default project sharing: Restricted
		* Anonymous projects: enabled (only for the purpose of direct links on this page, can be disabled elsewise)
		* Project creation: Templates only <code> NB! See below for creating templates
		* Summary report: disabled
		* Feedback: disabled
		* Project tagging: disabled

### Import from Registry
* Import Knowledge Model from Registry: [Norwegian DSW Knowledge Model v1.1.0](https://registry.fair-wizard.com/knowledge-models/research.data.no:norway-generic:1.1.0)
	* [User guide](https://guide.fair-wizard.com/en/production/applications/data-management-planner/knowledge-models/list/import.html)
	* NB! Default templates should be created by selecting tags (see below)
	* NB! Export works currently only with default or lean Questionnaire Report and maDMP export (see below)
	* NB! FAIR sharing integration requires an API key under Knowledge Model Secrets (see below)
* Import Document Template from Registry: [Questionnaire report - lean](https://registry.fair-wizard.com/document-templates/research.data.no:questionnaire-report-lean:2.16.0)
	* [User guide](https://guide.fair-wizard.com/en/production/applications/data-management-planner/document-templates/list/import.html#from-fair-wizard-registry)

### Template setup
[User guide](https://guide.fair-wizard.com/en/production/applications/data-management-planner/projects/list/templates.html)
* The following steps are necessary to create a Project Template
	* Create project by selecting Knowledge Model and tags
	* **View**: Settings to your choice (e.g. everything hidden but non-desirable questions)
	* **Settings**: Set name and add description
	* **Settings**: Set default document template (e.g. Questionnaire Report - lean and HTML)
	* **Settings**: Enable *Project template*
	* **Share**: Enable *Visible by all other logged-in users*
* We are using four pre-set questionnaires to accommodate [different user needs](/pages/dmp_reflections#dmp-needs). See also the [guidance for researchers](/pages/support_00_start_writing#choose-the-right-project-template).
	* Minimum: tag minimum
	* Minimum and ELSI: tag minimum, ELSI
	* RCN/ Science Europe and ELSI: tag RCN/ Science Europe, ELSI
	* RCN/ Science Europe and ELSI and HPC: tag RCN/ Science Europe, ELSI, HPC
	* Other tags can be ignored for the setup
	* In addition, we have a freestanding [pre-award Knowledge Model](/pages/support_00_planning_considerations). We are uncertain whether this Knowledge Model will be continued.

### Integrations
A few preparations are necessary to use some of the integrations in the *Norwegian DSW Knowledge Model*.

#### Institutional resources
To keep the resources compatible with Data Stewardship Wizard (DSW), we have chosen to maintain the list of institutional policies and resources as an [API](https://api.research-data.no/policies/search). To propose changes to the content, make a [pull request](https://github.com/DHP-stottepakke/integrations) or [get in touch](/pages/about/#contact).

#### FAIR sharing
The FAIR sharing integration requires an API key
* [User guide](https://guide.fair-wizard.com/en/production/applications/data-management-planner/knowledge-models/secrets.html#knowledge-model-secrets)
* Create API key: 1) Register FAIRsharing account. 2) Generate ApiKey with base64 in command line: <code> echo -n 'username:password' | base64
* **Data Management Planner** > Knowledge Models > Secrets: Set values for 'fairsharingApiKey' and 'fairsharingApiUrl'

## User management and test users
[User guide](https://guide.fair-wizard.com/en/production/applications/admin-center/users/index.html#)
* Default user role should be 'Researcher'
	* **Admin Center** > System 
* It can be useful to create dummy users to be able to test out different roles
	* **Admin Center** > Users: Invite button, create dummy user. If using a dummy email address, one can set a passphrase for the test user after creating the user.