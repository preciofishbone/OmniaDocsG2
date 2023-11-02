Controlled Documents Library Settings
=======================================

You must be Administrator (The permission group is often called "Owners") of the Team Site - there can be one or more - to be able to edit the settings for the three lists in the Controlled Documents library, and to edit permissions.

Settings for the tabs
***********************
To access the seetings, go to the Controlled Documents library and click "Edit".

.. image:: edit-controlled-library-new2.png

Here, the following settings are available:

.. image:: edit-controlled-library-settings-all.png

General
-----------
Here you can use the following settings:

.. image:: edit-controlled-library-general.png

+ **Title**: You can edit or add a Title for the list in all languages available for the tenant. The default language is mandatory. 
+ **Open In Client App**: Per default, documents are opened in the online Microsoft 365 application. If documents should be opened in the locally installed application instead, select this option. 

Display
----------
Here you can set the following:

.. image:: edit-controlled-library-display.png

+ **Default tab**: Decide which tab will be shown when an author enters the Controlled Documents library.
+ **Paging**: Select paging for the lists here; “No paging”, “Classic” or “Scroll”.
+ **Page Size**: Set the number of rows to display. **Important Note**: If more documents or tasks are available than the Page Size set, a navigation to the next page is shown when Paging is set to "Classic". If Paging is set to either "No paging" or "Scroll", Page Size is the maximum number of documents or tasks that can be shown in the lists, regardless of how many are available.
+ **Padding**: Set some padding around the lists, if needed.
+ **Hide Tasks Tab**: If the Tasks tab should not be displayed for authors, select this option.

Drafts
--------
The following settings are available for the Drafts tab:

.. image:: edit-controlled-library-drafts-new.png

+ **Default Ordering Field**: Select the column for default sort order for the list.
+ **Sort Direction**: Select Descending or Ascending here.
+ **Show Search Box**: If authors should be able to search for documents in the list, select this option.
+ **Column**: Use this option to add a column to be shown. Open the list, select the column and click "ADD".
+ **Display columns in draft view**: Here the selected columns are listed. To remove a column, click the dust bin. If no dust bin is shown for a column it's mandatory, and therefore can't be removed. You can set the order of the columns by grabbing the Equal To icon for the column and drag it to another place in the list.

Published
------------
The same type of settings as for Drafts are available here. See above for a description.

.. image:: edit-controlled-library-published-new.png

Default Document Types
------------------------
Use this setting to select one or more Document Types to be suggested when an author creates a new draft document in this Controlled Documents library.

As an example, these settings:

.. image:: default-types-example-2.png

Will result in the following:

.. image:: default-types-example-2-wizard.png

A user can always click "Show All" to see all available document types. More information about how the Document Wizard works is found here: :doc:`Using the Create New Document Wizard </working-with-documents/using-the-document-wizard/index>`

To add a Document Type, do the following:

1. Click in the field.

.. image:: document-type-add-1-new.png

2. Use the list to select one or more Document Types. 

.. image:: document-type-add-2-new.png

If the Document Types are grouped (as in the image above) you may need to expand a group to select a Document Type there. 

Also note that you can deselect Document Types as well using this list.

For more information about Document Types, see this page: :doc:`Document Types </admin-settings/tenant-settings/document-management/document-types/index>`

Permissions
************
If Document Management is set up for using permission groups, you can, as an Administrator (Owner) of the Team Site, edit these permissions.

**Important Note for Omnia 7.0 and later!** Only SharePoint users can be added here (not Omnia only users). Also note that a user or a group must be permissions enabled to show up in the list.

Do the following:

1. Click "Permissions" in the Controlled Documents library.

.. image:: click-permissions-new2.png

Something like the following is shown:

.. image:: controlled-permissions-new2.png

You can add/remove groups and/or users in these lists.

If permission groups are used, as in the example above, you can add and remove users in these groups by using the Sharepoint standard functionality "Advanced permissions settings" - found under "Site Permissions" in the settings for the site. 

.. image:: advanced-permissions-settings-new2.png

Note that external users that has been invited in the Azure AD can be added here as well. Users invited this way can log in with their own Microsoft 365 account.

Settings for Document Management is found under that heading in Omnia Admin, see this part of the documentation for more information: :doc:`Document Management </admin-settings/tenant-settings/document-management/index>`








