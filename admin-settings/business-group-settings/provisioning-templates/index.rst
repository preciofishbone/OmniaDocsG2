Provisioning Templates
===========================================

Use these options to create Provisioning Templates for Team Sites of different types, or Publishing Apps.

All existing Templates are displayed in the list.

.. image:: provisioning-templates-new.png

Use the icons to edit or delete a Template. 

.. image:: provisioning-templates-edit-delete-new.png

When editing a Template, the same options as when creating a Template is available, see below.

Create a Provisioning Template
*********************************
To create a Template, do the following:

1. Click the plus.

.. image:: provisioning-templates-create-1.png

Available settings differ depending on if you create a Template for a Publishing App or for a Team Site, see below.

Create a Template for a Publishing App
-----------------------------------------
Do the following:

2. For "Base Definition", select "Publishing App" and use the following settings:

.. image:: provisioning-templates-create-publishing-2.png

+ **Title**: Add a Title for the Template.
+ **Description**: Add a Description if needed.
+ **Icon Type**: An icon is always shown for a Template. If you would like another icon for this Template, select the set of Icons here: "Font Awesome", "Fabric" or "Custom". When selecting "Custom" you can choose any image as the Icon.
+ **Icon**: When you have select Icon Type, use this list to select the icon. If you select "Custom", this list is not shown. Instead a "Url" field is shown, where you enter the Url for the image.
+ **Show in Create New Wizard**: Select this option if the Template should be available in the user Wizard for creating new sites.
+ **Site Creation Mode**: Here you select if users will be available to create sites from this Template or if Approval is required.

3. Click "Next".
4. Click "ADD" to create the Template.

.. image:: provisioning-templates-publishing-3.png

Create a Template for a Team Site
-----------------------------------------
Do the following:

2. For "Base Definition", select "Team Collaboration" and use the following settings:

.. image:: provisioning-templates-create-team-2.png

The first set of options is the same as for Publishing Templates, see above.

3. Click "Next".

Use the following options here:

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

+ **Client id**: Type id here.

This setting is available for a Facebook Workplace Greup Template:

+ **Workplace Domain**: (A description will be added soon.)

5. Click "Next".

The next step is to edit properties. All available properties are shown, for example:

.. image:: template-properties.png

What you can do here is to select if a property should be required (meaning that it should be mandatory to add information for the property when creating a site). For some properties you can also set that multiple values are allowed.

Here's an example with Keywords, where you can set both:

6. Select the property and then click the dot menu.

.. image:: template-properties-dot-menu.png

7. Select if the property is mandatory (Required) and/or if multiple values should be allowed:

.. image:: template-property-required.png

8. Click "Save"
9. When all property settings are done, click "Next", at the bottom of the properties list.

As the next step you can set this:

.. image:: template-features.png

+ **Apply Microsoft Teams to an Office 365 Group**: Here you can select that a Microsoft Teams Group should be created for the Office 365 Group.
+ **Archived Documents**: (A description will be added soon.)
+ **Project Site**: (A description will be added soon.)
+ **Default Page Collections and Page Types**: (A description will be added soon.)

10. Set this as needed and click "Next".

Finally, you can select to add Custom Steps. If you do, the following is shown:

.. image:: custom-steps.png

+ **Information**: (A description will be added soon.)
+ **Users**: (A description will be added soon.)
+ **Enterprise Properties**: (A description will be added soon.)

6. When all settings are done here, or if you selected not to add custom steps, click "ADD" to create the Template.

.. image:: provisioning-templates-4-new.png