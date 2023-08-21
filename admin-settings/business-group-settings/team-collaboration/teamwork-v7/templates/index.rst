Teamwork templates in Omnia v7
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
What is different for a Microsoft 365 Team Group is the Setup step:

.. image:: teamwork-settings-setup-365-v7.png

+ **Site Design**: Here templates can be available, templates made according to Microsoft's standard for Site Design. Such templates can be used in Omnia.  Not mandatory. If no such templates are available, the list is empty. For more information about Site Design, see this Microsoft page: https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/site-design-overview
+ **Languages**: Select language to be used for system texts in the site.
+ **User can select language**: Select this option to enable language selection by the user creating the site.
+ **Time Zones**: Select the correct time zone here.
+ **User can select time zone**: Select this option to enable time zone selection by the user creating the site.
+ **Welcome Page**: Choose to link to a Sharepoint site or to Microsoft Teams.
+ **Privacy**: Decide if the Group should be Private or Public.

Sharepoint Team Site
------------------------------------------------------------
For a Sharepoint Team Site, these settings are available for Setup:

.. image:: teamwork-settings-setup-teamsite-v7.png

+ **Site Design**: Here templates can be available, templates made according to Microsoft's standard for Site Design. Such templates can be used in Omnia.  Not mandatory. If no such templates are available, the list is empty. For more information about Site Design, see this Microsoft page: https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/site-design-overview
+ **Languages**: Select language to be used for system texts in the site.
+ **User can select language**: Select this option to enable language selection by the user creating the site.
+ **Time Zones**: Select the correct time zone here.
+ **User can select time zone**: Select this option to enable time zone selection by the user creating the site.
+ **Primary Site Collection Administrator**: If empty, the user creating or requesting the site will automatically become the default administrator (Owner) of the site. If a specific group or user should be administrator for all sites created from this template, add that group or user. Only on group or user can be added in this field.
+ **Default Site Collection Administrators**: You can add (several) additional administrators here, if needed.
+ **Default Visitors**: You can use this to set a default visitor group (read permissions) to all sites created from this template. 

Microsoft Team
---------------------
For Microsoft Team, the following settings are available for Setup:

.. image:: teamwork-settings-setup-team-v7.png

and these:

.. image:: teamwork-settings-setup-team-v7-2.png

**Note!** Microsoft Team is not available in Omnia on-prem.

Create a custom Microsoft Team template
----------------------------------------
Here's how to create a custom Teams template:

1. Select "Microsoft Teams" or "Sharepoint" as default welcome page.
2. Decide of Discovery should be private or public, and decide to show it in Teams search and suggestions, or not.
3. Decide which settings should be active.

All settings work the same way, and all are active per default.

4. Open settings (Messaging as an example).

.. image:: teamwork-settings-settings.png

5. Point at the i-icon of a setting for more information.
6. Click to deactive if it should be used.

If any channels should be added to the template, do the following:

7. Click ADD CHANNEL and use the settings:

.. image:: teamwork-settings-setup-channels-v7.png

+ **Channel name**: Type the name here.
+ **Description**: Add a description of the channel if necessary.
+ **Visible by default**: if the channel should be marked as "Favourite" for all members of the team, select this option.

8. Add additionall tabs for the channel, if needed.

For **Apps** the following settings are available:

  .. image:: teamwork-settings-setup-team-apps-v7.png

9. Save the template.

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
