Document Types
================

(This documentation is just started, more will be added soon).

When creating a new controlled document an author selects a Document Type. Document Types can be grouped. In that case the author first selects group and then Document Type within that group.

The settings displays all existing Document Types, and Groups, if they are grouped, for example:

.. image:: document-types-start.png

The i icon can show information on syncronization of new or edited Document Types. Here's an example:

.. image:: document-types-info.png

Creating a new Group
**********************
To create a new a group, do the following:

1. Point at any existing group.
2. Click the plus and select "Create Group".

.. image:: doctype-select-group.png
 
3. Add a Title in one or more languages (default language in the tenant is mandatory).

.. image:: doctype-group-title.png

4. Save.

Creating a Document Type
*****************************
To create a new Document Type, do the following:

1. Point at the group to create a Document Type in.
2. Click the plus and select "Create Document Type".

.. image:: doctype-new-type.png
 
2. Use the following settings:

.. image:: document-type-general.png

The same settings are available when creating a Document Type and when editing one. See below for detailed information.

Sort Document Types
***********************
You can sort if you want to present the list in a specific order to the editors.

1. Select the group or Document Type to move and use the arrows.

.. image:: doctype-sort.png

Edit or delete a Document Type or group
******************************************
To edit or a Group or Document Type, do the following:

1. Select the type or group.
2. Edit available settings (see below for detailed information about Document Type settings).
3. Save.

To delete a Group or Document type, do the following:

1. Select the type or group.
2. Available settings are now shown.
3. Click the dust bin.

.. image:: doctype-delete.png

Settings for Document Types
****************************
The settings are organized into five tabs, see the sections below.

General
--------
The General tab contains the following settings:

.. image:: document-types-general.png

+ **Title**: Add a Title for the Document Type in one or more of the tenant languages. Note that default language is mandatory.
+ **Property Set**: Select a property set for the Document Type. When you have selected a Propety Set you can click the cogwheel to see which properties belong to the set. You will also see information about Placeholder Shortname and default value for the properties in the set.
+ **Document Templates**: Select one of the templates defined for the profile you have chosen. You must always do that even if there’s just one template available.
+ **Default Document Template**: Use this option to select one of the templates for this Document Type as the default template. When selecting the Document Type, the author then has this template preselected.
+ **Allow appendices**: Check this option to allow for appendices. Authors can then tie other documents as appendices to the main documents. This option must be checked to make it possible for this document type.
+ **Allow document to be connected to an existing template**: This option is mainly used in migration scenarios. If this option is selected it works like this: When a Controlled Documents author creates a new draft or uploads a document that is not connected to a Controlled Documents template, a message is shown allowing the author to connect that document to a template.
+ **Unique id**: Created by the system. Shown here for information.

Don't forget to save when you're done.

Publish
---------
On the Publish tab you can set the following:

.. image:: document-types-publish.png

+ **Replace tokens inside document on poublishing**: When a document is published, the placeholders (tokens) will be replaced with metadata, but for a document that will be used as a template, you will probably not want that to happen. If you are creating a Document Type to bes used for templates, deselect this option.
+ **Allow Revisions**: Selecting this option you can allow authors to publish a revision of a document that does not require approval, for example for correcting typing errors. If this option is active, it's up to the author to decide if approval is needed or not. Approval is still nedded for publication of a new edition of a document.
+ **Publishing approval**: Select if approval is to be used for this Document Type. If this option is active, a document will be published immediately when an author clicks "Publish".

Not edited from her on:

+ **Anyone**: The author can select any user of the portal as approver.
+ **Limited list of users**: Authors can select approvers from a defined list only (see below for more information).
+ **Term-driven**: Authors can select approvers from a defined list only (which approvers will be available depends on the Properties selected for the documents, see below for more information).
+ **Based on person column**: You then select one of the person columns defined, most often Document owner or Approver.
