Announcements
===========================================

Here a user with the approrpiate permissions can create Announcements that can be displayed over the whole tenant, normally at the top. Tenant Administrators can always create announcements. Also, any user can be granted this permission. This is set under "Permissions" for the Tenant, see: :doc:`Permissions for the Tenant </admin-settings/tenant-settings/permissions/index>`

Tenant Announcements can also be shown through the Announcements block. For more information about the block, see: :doc:`The Announcements block </blocks/announcements/index>`

Note that an option to create Announcements for a specific Business Group also is available. The options are identical, the only difference is where Announcements are shown.

All existing Announcements, active or not, are shown in the list. From there you can edit or delete an Announcement.

.. image:: announcements-list-new.png

For explanation of Priority and Order, see below.

To edit an Announcement, click the pen. Everything added when a new Announcement is created can be edited, see below.

To delete an Announcement that is no longer needed, clik the dust bin.

Create an Announcement
------------------------
To create a new Announcement, do the following:

1. Click the plus.

.. image:: tenant-announcements-clickplus-new.png

Use the following settings:

.. image:: tenant-announcements-settings2-new2.png

+ **Title**: Add a title for the message. If you use more than one language in the tenant you can add a title in each language. Note that you must always add a title in the default language, other languages are optional. Click the flag to change language.
+ **Description**: Add the message here. If you use more than one language in the tenant you can add the description in each language. Note that you must always add the description in the default language, other languages are optional. Click the flag to change language. The Limited RTF Editor is used for the description. For more information, see: :doc:`Editing text with the RTF Editor </general-assets/rtf-editor/index>`
+ **Priority**: Set the Priority. Announcements with High priority will be displayed below the cross site mega menu on all pages (see example below). Announcements (with Normal or High priority) can be displayed to users in the Notification Panel or through the Announcements block.
+ **Order**: Set the order for this Announcement when there are several displayed.
+ **Start Date** and **End Date**: Set the start and end date of the Announcement. You can set exact times within the dates if needed. Start and end dates are optional, but we recommend that you always at least set an end date.
+ **Type**: Type is an indication of what type the Announcement is, noted with text and an icon. Available Types are created and edited in the settings (see below).
+ **Status**: Status is a color and text indication of the status (severity) of Announcement. Available Status options are created and edited in the settings (see below)
+ **Allow comments**: Decide to allow comments or not. The default is to not allow comments. If allowed, users can add comments, and even comment other comments (and so can you of course) the same way as for example for news. **Note!** Comments are sent to you, meaning the colleague who created the announcement.
+ **Targeting filter**: An Announcement can be targeted, which means just displayed to a defined group of users. See below for information on how to do that.

**Important Note!** If there are no Annoncements block placed on a suitable page and Announcements is not added as a category to the Notification Panel, Announcements with Normal priority are simply not shown!

Here's an example of an Announcement with high priority:

.. image:: high-priority-new3.png

Here's an example of Announcements displayed in the Announcements block:

.. image:: announcements-block-new.png

For more information, see: The Announcements block: :doc:`The Announcements block </blocks/announcements/index>`

All languages to be used here must be setup in the Tenant, see: :doc:`Regional Settings </admin-settings/tenant-settings/settings/regional-settings/index>`

Targeting Announcements
-------------------------
An Announcement can be targeted to any receivers that has been defined in Targeting Properties, see the section on this page: :doc:`Properties </admin-settings/tenant-settings/properties/index>`

You set up targeting for an announcement the same way as for many other parts of Omnia. See this page for more information: :doc:`Using Targeting </general-assets/targeting-in-omnia/index>`

Settings for Announcements
***************************
Click the cog wheel to enter the settings:

.. image:: cog-wheel-settings-new3.png

You can set the following:

.. image:: announcement-settings-new2.png

Types
------
Here you can add and edit Types that can be used in an Announcements to indicate what type of content the Announcement has.

The existing Types are listed, with selected icons shown. Edit and delete the Types using the pen or dust bin.

To create a new Type, click the plus:

.. image:: types-create-new3.png

Set the following:

.. image:: add-type-settings-new2.png

1. Add a Title in any or all tenant languages (click the fal to change language).
2. Select Icon Type.
3. Select Icon. 
4. Click the plus to save the Type.

**Tip!** You can select "Custom" under "Icon Type" to use any image as an icon, but you have to know (or have copied) the Url to the image.

Status
--------
Here you can add and edit Status options that can be used in an Announcements to indicate the status for the Announcement, for example the level or problem or Spotted/Solving/Solved.

The existing Types are Status options, with selected color shown. Edit and delete the Status options using the pen or dust bin.

To create a new Status option, click the plus:

.. image:: status-create-new4.png

Set the following:

.. image:: add-status-settings-new2.png

1. Add a Title in any tenant language (click the flag to change language).
2. Select Background Color.
3. Select Text Color. 
4. Click the plus to save the Status option.

