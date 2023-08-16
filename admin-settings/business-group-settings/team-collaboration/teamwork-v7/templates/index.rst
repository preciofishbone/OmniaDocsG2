Teamwork templates for in Omnia v7
=======================================

**This page is under construction.**

Here you can work with templates for Teamwork; Microsoft 365 Group, Sharepoint Team Site, Microsoft Team, Private Yammer Community and Facbook Workplace Group. The first list displays all templates that has been created so far, for example:

.. image:: teamwork-templates-v7.png

The following actions are available in the dot menu for a template:

.. image:: teamwork-templates-dotmenu-v7.png

To edit a template, you can also just click the name. When you edit a template, all options that are described below are available.

You create templates for publishing apps, community sites and Teamwork the same way, see this page: :doc:`Creating app templates in Omnia v7 </general-assets/creating-app-templates/index>`

The settings for General, Properties, Custom steps and Policies are handled as decsibred on the page linked above, even if available property sets can differ. Available settings under Features and Setup differ depending on type of teamwork. The differences is descibed here.

Microsoft 365 Group
-----------------------
The following options are available for a Microsoft 365 Team Group:

.. image:: teamwork-settings-setup-365-612.png

Available only for Microsoft 365 Group are:

+ **Welcome Page**: Choose to link to a Sharepoint site or to Microsoft Teams.
+ **Privacy**: Decide if the Group should be Private or Public.

For descriptions of the rest of the options, see below.

Sharepoint Team Site and Sharepoint Communication site
------------------------------------------------------------
For Sharepoint Team Site and Sharepoint Communication Site, these settings are available for Setup:

.. image:: teamwork-settings-setup-new.png

+ **Site Design**: Here templates can be available, templates made according to Microsoft's standard for Site Design. Such templates can be used in Omnia.  Not mandatory. If no such templates are available, the list is empty. For more information about Site Design, see this Microsoft page: https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/site-design-overview
+ **Languages**: Select language to be used for system texts in the site.
+ **User can select language**: Select this option to enable language selection by the user creating the site.
+ **Time Zones**: Select the correct time zone here.
+ **Primary Site Collection Administrator**: If empty, the user creating or requesting the site will automatically become the default administrator (Owner) of the site. If a specific group or user should be administrator for all sites created from this template, add that group or user. Only on group or user can be added in this field.
+ **Default Site Collection Administrators**: You can add (several) additional administrators here, if needed.
+ **Default Visitors**: You can use this to set a default visitor group (read permissions) to all sites created from this template. 

Microsoft Team
---------------------
For Microsoft Team, the following settings are available for Setup:

.. image:: teamwork-settings-setup-team-612.png

**Note!** Microsoft Team is not available in Omnia on-prem.

+ **Welcome Page**: Choose to link to a Sharepoint site or to Microsoft Teams.
+ **Setup template**: Here you can select to create a Custom template, to use a Microsoft Teams template, or to give the user the option to Clone an excisting team. Note that a colleague must be member of a team to be able to clone it. See below for more information on a custom template. To use a Microsoft Teams template you must enter the id of the template (can be found in Teams admin center). 
+ **Settings**: Available for a custom template, see below.
+ **Apps**: Available for a custom template, see below.
+ **Channels**: Available for a custom template, see below.

Create a custom Microsoft Team template
----------------------------------------
When you have selected to create a custom template the following options are available:

.. image:: teamwork-settings-setup-team-all.png

Under **Settings** you can do the following:

.. image:: teamwork-settings-setup-team-settings-new.png

+ **Visibility**: Here you select how joining the team will work; if anyone can join the team or if only administrators can add memebers to the team.

For the rest of the options: point at the i icon and read the tooltip, to learn what the option are for.

For **Apps** the following is available:

.. image:: teamwork-settings-setup-team-apps.png

Add the apps that should be added when a teamwork is created from this template.

For **Channels** the following settings are available:

.. image:: teamwork-settings-setup-channels.png

Here a list of channels that are already added to the template is shown. Click the pen to edit a channel. 

To add a new channel, click the plus and use these settings:

.. image:: teamwork-settings-setup-channels-settings.png

+ **Channel name**: TYpe the name here.
+ **Description**: Add a description of the channel if necessary.
+ **Shown by default**: if the channel should be marked as "Favourite" for all members of the team, select this option.

You can also set which tabs should be added for all teams that are created from this template. When adding a tab, the following settings are available:

.. image:: teamwork-settings-setup-channels-settings-tab.png

+ **Tab name**: Type the name for the tab here.
+ **App Types**: Select type of app for the tab; Built-in meaning Microsoft Apps, or Organization for other Apps, which can, for example, be Omnia Apps.

Yammer Community
--------------------
The following setting is available for a Yammer Community template for Setup:

.. image:: teamwork-yammer-community-612.png

**Note!** Yammer Community is not available in Omnia on-prem.

+ **Welcome Page**: Select the default Url for Sharepoint or for a Yammer group.
+ **Client id**: Type the Client id for the Yammer Network here.

Facebook Workplace Group
-------------------------------
This setting is available for a Facebook Workplace Group template for Setup:

.. image:: teamwork-facebook-workplace-group-612.png

**Note!** Facebook Workplace Group is not available in Omnia on-prem.

+ **Workplace Domain**: Add the Facebook Workplace name here.

Custom steps
*****************
If any custom steps has been developed for the type of community you have selected, you can add them using this option.

.. image:: teamwork-edit-custom-steps-612.png


Policies
**********
Use this for further policies settings, that will be applied to teamworks created from specific templates. A prerequisite is that Sensitivity Labels are created in Microsoft 365.

The following can be set here:

.. image:: teamwork-templates-policies.png

+ **Naming Policy**: Select the naming policy to set settings for. The policies listed here are those setup for teamworks, see: :doc:`Naming policies </admin-settings/business-group-settings/team-collaboration/teamwork-65/naming-policies/index>`
+ **Minimum number of characters in description**: Here you can set a number of characters for the teamwork descripton, to force users to add a description of a certain length. 
+ **Minimim number of administrators**: There must always be at least one administrator for a teamwork, but you can decide that more administrators should be required, up to 5.
+ **Default Administrators**: Use this to add one or more administrators for teamworks created from this template. These administrators will always be added, can not be removed in the Create Teamwork wizard. Must be persons, can not be groups.
+ **Sensitivity Label**: Here you decide how Microsoft 365 Sensitivity Labels will be handled for this Teamwork Template; No senitivity label, Fixed or Let user decide. If you select "Fixed", a list of the existing sensitivity labels are shown and you select one from the list. It can't be changed when a teamwork is created. If you select "Let user decide", the user creating a teamwork from this template can select which sensitivity label to use for the teamwork. It's still mandatory to select one when creating the teamwork.
