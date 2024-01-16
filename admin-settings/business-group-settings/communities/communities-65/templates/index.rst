Templates for communities
============================

Here  you can work with templates for communities.

.. image:: communties-templates-new.png

To edit a template, click the name - to delete, click the dust bin.

Creating a new community template
*************************************
To create a new template, do the following:

1. Click the plus.

.. image:: community-template-click-plus.png

Use the following settings:

.. image:: community-template-settings-612-new.png

General
----------
The following settings are available here:

.. image:: community-template-settings-general-612.png

+ **Title**: Add a title for the template. You can add titles in all or some of the languages available in the tenant. Default language is mandatory. Click the flag to change language.
+ **Description**: Add a description if needed, in one or more languages. Click the flag to change language. 
+ **Icon type**: An icon is always shown for a template. If you would like another icon for this template, select the set of icons here: Font Awesome, Microsoft, Flags or Custom. When selecting Custom you can choose any image as the icon.
+ **Icon**: When you have selected icon type, use this list to select the icon. If you select Custom, a URL field is shown, where you enter the URL for the image.
+ **Available to**: Select who this template should be available to. What **All users** and **Admins only** means is obvious. If you select **Specific users** you can select a property (for example Job role or Location) and set the necessary settings. 
+ **Site creation mode**: Here you select if approval is required when users create community apps from this template. 

Community templates for specific users
--------------------------------------
When you select "Specific users" the following option is shown:

.. image:: specific-users.png

Click "Add targeting filter" and the following is shown:

.. image:: specific-users-filter.png

You use targeting here the same way as in other parts of Omnia. For more information, see this page: :doc:`Using targeting </general-assets/targeting-in-omnia/index>`

Also note that all properties that should be available for targeting must be set up in the Targeting properties list, see: :doc:`Targeting properties </admin-settings/tenant-settings/properties/targeting-properties/index>`

Properties
------------
You can add a property set to the template. 

.. image:: community-edit-properties-612.png

+ **Property set**: Select property set here. The properties in the set can or will have to be filled, depending on settings for the property, when a community is created from this template. The property sets are set up using the tenant settings. See this page for more information: :doc:`Property sets </admin-settings/tenant-settings/properties/property-sets/index>`
+ **Default values**: You can set default values for some properties in a set, valid for this template. Default values can be edited when a community is created from this template.
+ **Visibility**: Here you select where the properties should be available: "Show in new form" means when an app is created from this template, "Show in edit form" means when the settings for the app is edited.

Features
----------
Select the features that should be available for the community (all are not shown in the image):

.. image:: community-edit-features-612.png

Setup
-------
Using the options here you can create one or more page collections to be set up automatically when this template is used, such as Knowledge articles and Discussion. There's also some settings available.

.. image:: community-edit-setup-new2.png

To edit settings, click "Publishing app settings" and use the following settings (can be edited later by a publishing app administrator for the community):

.. image:: community-edit-setup-settings-612.png

+ **Enable reuse content**: If community apps created from this template should allow reuse of content, select this option. 
+ **Contact property**: Select the default property for page contact.
+ **Review date property**: Select the default property for review date.
+ **Promoted tags**: A community app can be configured to have promoted tags/terms for certain properties. Promoted tags/terms will be displayed at the top of the tag/term picker both for the author, when working with pages, and for the end user when filtering in a page rollup.

To create one or more page collections, do the following:

1. Click the plus for "Page collection".

.. image:: community-page-collection-new.png

2. Create a page collection using the following settings:

.. image:: community-page-collection-settings-new.png

3. Choose to use a navigation structure or just flat, meaning no navigation structure.

One example where “Flat” is a relevant choice, is when creating a page collection for news. Probably not that relevant for a community.

4. Type a name for the new page collection.

An Url is added, based on the name. It can be edited if needed.

5. Click “Create”.
6. Edit the settings.

.. image:: community-page-collection-settings-edit-612.png

(There's a lot more settings than is shown in the image).

Page collection permissions are described on this page: :doc:`Page collection permissions </pages/page-collections/page-collection-permissions/index>`

You use the rest of the settings the same way as is described on this page: :doc:`Page collections </pages/page-collections/index>`

Don't forget to save when you're ready (the "Save" option is located at the bottom, in the low right corner).

To add another page collection, just do it the same way.

When you have added one or more page collections, you can use the icons to:

.. image:: community-collection-settings-icons-blue.png

+ Sort the order in which they are shown (left-most icon).
+ Edit the settings (the cogwheel).
+ Delete a page collection.

Custom steps
---------------
If any custom steps has been developed for the creation of communities, you can select them using this option.

.. image:: community-edit-custom-steps.png

Policies
----------
Use this for further policies settings, that will be applied to community apps created from this template. 

The following can be set here:

.. image:: community-templates-policies-612.png

+ **Minimum number of characters in description**: Here you can set a number of characters for the description of the commmunity app, to force users to add a description of a certain length. 
+ **Minimim number of administrators**: There must always be at least one administrator for a community app, but you can decide that more administrators should be required, up to 5.
+ **Default administrators**: Use this to add one or more default administrators for community apps created from this template. These administrators will always be added, and can not be removed in the Create publishing app wizard. Must be persons, can not be groups.
