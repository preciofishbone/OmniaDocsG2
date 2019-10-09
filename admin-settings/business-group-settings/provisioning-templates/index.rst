Provisioning Templates
===========================================

Use these options to create Provisioning Templates for Team Sites of different types, or Publishing Apps.

All existing templates are displayed in the list.

.. image:: provisioning-templates-new.png

Use the icons to edit or delete a template. 

.. image:: provisioning-templates-edit-delete-new.png

When editing a template, the same options as when creating a template is available, see below.

Create a Provisioning Template
*********************************
To create a Template, do the following:

1. Click the plus.

.. image:: provisioning-templates-create-1.png

Available settings differ depending on which type of template you're creating, see below.

The first step is the same for all template types. Do the following:

2. For "Base Definition", select "Publishing App" or "Team Collaboration" and use the following settings:

.. image:: provisioning-templates-create-publishing-2.png

+ **Title**: Add a Title for the Template.
+ **Description**: Add a Description if needed.
+ **Icon Type**: An icon is always shown for a Template. If you would like another icon for this Template, select the set of Icons here: "Font Awesome", "Fabric" or "Custom". When selecting "Custom" you can choose any image as the Icon.
+ **Icon**: When you have select Icon Type, use this list to select the icon. If you select "Custom", this list is not shown. Instead a "Url" field is shown, where you enter the Url for the image.
+ **Show in Create New Wizard**: Select this option if the Template should be available in the user Wizard for creating new sites.
+ **Site Creation Mode**: Here you select if users will be available to create sites from this Template or if Approval is required.

3. Click "Next".

Next step is for Team Collaboration sites only:

.. image:: provisioning-templates-create-team-3.png

+ **Type**: Select template to base the new template on; "Office 365 Group, Team", "Yammer Group" or "Facebook Workplace Group".

The following settings are available for Office 365 Group and Team:

+ **Site Design**: If creating a Template for an Onboarding project, select that design. 
+ **Language**: Select Language to be used for system texts in the site.
+ **User can select language**: Select this option to enable Language selection by the user creating the site.
+ **Time Zone**: Select the correct Time Zone here.
+ **Location**: Select location for the sites created from this template. For a site collection site, you can select to create sites from this template in any of the managed paths, normally either /sites or /teams. Not available for Office 365 Groups.
+ **Default Administrator**: If empty, the user creating or requesting the site will automatically become the Default Administrator (Owner) of the site, in Sharepoint terms; Primary Site Collection Administrator. If a specific group or user should be administrator for all sites created from this template, add that group or user. Not available for Office 365 Groups.
+ **Default Secondary Administrator**: You can add a second Administror, if needed.
+ **Default Visitors**: You can use this to set a default visitor group (read permissions) to all sites created from this template. Let's say it's a template for community pages - then probably all users of the intranet should have read permission to all pages in the site. Not available for Office 365 Groups.
+ **Privacy**: For 365 Groups (Not for Teams), you can select either "Private" or "Public". The text in the selections explains the difference.

The following setting is available for a Yammer Group Template:

+ **Client id**: Type Client id for the Yammer Network here.

This setting is available for a Facebook Workplace Group Template:

+ **Workplace Domain**: Add the Facebook Workplace name here.

4. Click "Next".

The next step is to edit properties, which you do for all types of templates. All available properties are shown, for example:

.. image:: template-properties.png

What you can do here is to select if a property should be required (meaning that it should be mandatory to add information for the property when creating a site). For some properties you can also set that multiple values are allowed.

Here's an example with Keywords, where you can set both:

5. Select the property and then click the dot menu.

.. image:: template-properties-dot-menu.png

6. Select if the property is required and/or if multiple values should be allowed:

.. image:: template-property-required.png

7. Click "Save"
8. When all property settings are done, click "Next", at the bottom of the properties list.

As the next step you can set this:

.. image:: template-features.png

+ **Apply Microsoft Teams to an Office 365 Group**: Here you can select that a Microsoft Teams Group should be created for the Office 365 Group.
+ **Archived Documents**: Select this option if the feature "Archived Documents" should be activated automatically when a site is created from this template.
+ **Project Site**: Select this option if the feature "Project Site" should be activated automatically when a site is created from this template.
+ **Default Page Collections and Page Types**: Select this option if the corresponding feature should be activated automatically when a site is created from this template.

9. Set the options here as needed and click "Next".

Finally, you can select to add Custom Steps. If you do, something like the following is shown:

.. image:: custom-steps.png

You can choose to add some standard "Custom steps" as shown in the image above. If additional Custom Steps are developed, they are shown here.

10. When all settings are done here, or if you selected not to add custom steps, click "ADD" to create the Template.

.. image:: provisioning-templates-4-new.png