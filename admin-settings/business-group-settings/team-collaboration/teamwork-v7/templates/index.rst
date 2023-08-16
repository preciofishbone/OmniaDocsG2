Teamwork templates for in Omnia v7
=======================================

**This page is under construction.**

Here you can work with templates for Teamwork. The first list displays all templates that has been created so far, for example:

Here you can work with templates for Publishing Apps.

.. image:: publishing-templates-v7.png

To edit a template, click the name - to delete, click the dust bin. When you edit a template, all options that are described below are available.

You create templates for publishing apps, community sites and Teamwork the same way, see this page: :doc:`Creating app templates in Omnia v7 </general-assets/creating-app-templates/index>`

Here you can create teamplates for Omnia Publishing Apps and Sharepoint Communication Sites.

Most settings are the same but Setup is different for a Sharepoint Communication Site:

.. image:: publishing-templates-communication-site.png

+ **Site Design**: Here templates can be available, templates made according to Microsoft's standard for Site Design. Such templates can be used in Omnia. Not mandatory. If no such templates are available, the list is empty. For more information about Site Design, see this Microsoft page: https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/site-design-overview
+ **Languages**: Select language to be used for system texts in the site.
+ **User can select language**: Select this option to enable language selection by the user creating a site from this template.
+ **Time Zones**: Select the correct time zone here.
+ **Primary Site Collection Administrator**: If empty, the user creating or requesting the site will automatically become the default administrator (Owner) of the site. If a specific group or user should be administrator for all sites created from this template, add that group or user. Only one group or user can be added in this field.
+ **Default Site Collection Administrators**: You can add (several) additional administrators here (users or groups), if needed.
+ **Default Visitors**: You can use this to set a default visitor group(s) or users(s) (read permissions), to all sites created from this template. 

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
