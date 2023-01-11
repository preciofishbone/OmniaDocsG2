Templates for Publishing Apps
================================

Here you can work with templates for Publishing Apps.

.. image:: publishing-templates-612.png

To edit a template, click the name - to delete, click the dust bin. When you edit a template, all options that are described below are available.

Creating a new Publishing App template
****************************************
To create a new template, do the following:

1. Click the plus.

.. image:: publishing-template-click-plus-612.png

Use the following settings:

.. image:: publishing-template-settings-612.png

General
----------
The following settings are available here:

.. image:: publishing-edit-general-612-frame.png

+ **Title**: Add a Title for the Template. You can add titles in a number of the languages available in the tenant. Default language is mandatory. (Click the fal to change language).
+ **Description**: Add a Description if needed. You can add a description in a number of the languages available in the tenant.(Click the fal to change language).
+ **Icon Type**: An icon is always shown for a template. If you would like another icon for this template, select the set of icons here: Font Awesome, Microsoft, Flags or Custom. When selecting Custom you can choose any image as the icon.
+ **Icon**: When you have select Icon Type, use this list to select the icon. If you select Custom, a Url field is shown, where you enter the Url for the image.
+ **Available To**: Here you select who the template should be available for. What "All Users" and "Admins only" means is obvious. When you select "Specific Users" you click "Add Targeting Filter", choose a property (for example Administration Roles or Language) and set the necessary settings to create the targeting filter for the group of users you have in mind.
+ **Site Creation Mode**: Here you select if approval is required when users create sites from this template. When you select "Approval" you must also select one or more approvers.

Properties
------------
You can add a property set to the template. 

.. image:: publishing-edit-properties-612.png

+ **Property Set**: Select property set here. The properties in the set can or will have to be filled in when an app is created from this template, depending on settings for the property. The property sets are set up using the Tenant settings. See this page for more information: :doc:`Property sets </admin-settings/tenant-settings/properties/property-sets/index>`
+ **Default values**: You can set default values for suitable properties in a set, valid for this template. Default values can be edited when an app is created from this template.
+ **Visibility**: Here you select where the properties should be available: "Show in new form" means when an app is created from this template, "Show in edit form" means when the settings for the app is edited.

Features
----------
Select the features that should be available for the publishing app (all are not shown in the image):

.. image:: publishing-edit-features-612.png

The features can be updated in Omnia Admin using App Features for the app.

Setup
-------
Using the options here you set Publishing App settings and can create one or more Page Collections to be set up automatically when this template is used.

.. image:: publishing-edit-setup-new.png

To edit settings, click "Publishing App Settings" and use the following settings (can be edited later by a Publishing App Administrator):

.. image:: publishing-edit-setup-settings.png

+ **Enable Reuse Content**: If publishing apps created from this template should allow reuse of content, select this option. 
+ **Contact Property**: Select the default property for page contact.
+ **Review Date Property**: Select the default property for review date.

To create one or more Page Collections, do the following:

1. Click the plus for "Page Collection".

.. image:: publishing-page-collection.png

2. Create a page collection using the following settings:

.. image:: publishing-page-collection-settings.png

3. Choose to use a Navigation Structure or just Flat, meaning no navigation structure.

One example where “Flat” is a relevant choice, is when creating a Page Collection for News.

4. Type a name (Title) for the new Page Collection.

An Url is added, based on the name. It can be edited if needed.

5. Click “Create”.
6. Edit the settings.

.. image:: publishing-page-collection-settings-edit-612.png

(There's a lot more settings than is shown in the image).

Page Collection Permissions are described on this page: :doc:`Page Collection Permissions </pages/page-collections/page-collection-permissions/index>`

You use the rest of the settings the same way as is described on this page: :doc:`Page Collections </pages/page-collections/index>`

Don't forget to save when you're ready (the "Save" option is located at the bottom, in the low right corner).

To add another Page Collection, just do it the same way.

When you have added one or more Page Collections, you can use the the icons to:

.. image:: publishing-page-collection-settings-icons.png

+ Sort the order in which they are shown (left-most icon).
+ Edit the settings (the cogwheel).
+ Delete a Page Collection.

Custom steps
---------------
If any custom steps has been developed for the creation of publishing apps, you can select them using this option.

.. image:: publishing-edit-custom-steps-612.png

Policies
***********
Use this for further policies settings, that will be applied to publishing apps created from this template. 

The following can be set here:

.. image:: publishing-templates-policies-612.png

+ **Minimum number of characters in description**: Here you can set a number of characters for the description of the publishing app, to force users to add a description of a certain length. 
+ **Minimim number of administrators**: There must always be at least one administrator for a publishing app, but you can decide that more administrators should be required, up to 5.
+ **Default Administrators**: Use this to add one or more default administrators for publisning apps created from this template. These administrators will always be added, and can not be removed in the Create Publishing App wizard. Must be persons, can not be groups.

