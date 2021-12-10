Page Type Settings
======================

On the "Settings" tab you can set the Properties for all pages created from this Page Type. In many cases it results in fields the page editor has to or can fill in for a page. You can select any of the properties defined in the tenant. See this page for more information about setting up properties: :doc:`Tenant Settings - Properties </admin-settings/tenant-settings/properties/index>`

Here's an example with a Page Type with left navigation:

.. image:: page-type-settings-left-new2.png

(For a description of "Override Sharepoint Sync Settings", see below.)

On Omnia 6.7 and later, it will be possible to automatically archive a page of a certain Page type. For more information, see below.

If properties was selected as in the image above it would result in these fields being available on the Properties tab for a page:

.. image:: page-type-settings-left-fields-new2.png

And here's an example with a Page Type for News:

.. image:: page-type-settings-news-new.png

Which results in these fields being available on the Properties tab for a News Article page:

.. image:: page-type-settings-news-fields-new.png

Set properties for the Page Type this way:

1. Select the properties to be used for this Page Type.
2. Click the cog wheel for more settings for a property.

.. image:: page-type-settings-cogwheel.png

Something like the following is shown:

.. image:: page-type-settings-dot-menu-settings-new.png

The following settings can be available for a property:

+ **Required**: The editor creating the page has to enter information in the field.
+ **Allow multiple values**: For some properties multiple values are possible. If you will allow the editor to enter more than one value, check this option. If multiple values is not possible for the property, this option is not shown.
+ **Show in new page**: If the property (field) should be available in the New Page Wizard when creating a page, select this option.
+ **Show in edit properties**: If the property should be available on the Properties tab for a page created from this Page Type, select this option.
+ **Date only**: If it's a date/time field, both date and time can be set, or only the date. If you would like juat the date to be set, not the time, select this option.
+ **Receive e-mail**: This is available for most people properties. If the colleague set for this property should receive e-mails, select this option.
+ **Category**: This a preparation for future functionality. No need to enter anything here now.
+ **Default value**: A default value can be entered here. A defalt value can be edited by the author. What is possible to select here differs with type of property. 
+ **Limit Edit Permission**: You can limit Edit Permission for this property if needed. In that case, add one or more users here.

Override Sharepoint Sync Settings
************************************
Sharepoint Sync Settings are set in Omnia Admin (available under Web Content Management), for the whole tenant. If you need some other synchronization for pages created from this Page Type, you can override the tenant settings and create a specific synchronization here.

When you activate this option, the following is shown:

.. image:: page-type-settings-override-message.png

And then something like the following is available:

.. image:: page-type-settings-override.png

The settings are used exactly the same way here as the settings for the tenant. See this page for more information: :doc:`Sharepoint Sync </admin-settings/tenant-settings/webcontent-managament/sharepoint-sync/index>`

When you have set up the sync here, you must execute a full sync to Sharepoint, as the message stated. Go to the Publishing App settings and click this button:

.. image:: page-type-settings-sync-button.png

Enable Automatic Archive
***************************
This is a new option that will be availble in Omnia 6.7 and later.

Here's a Tenant Page Type as an example:

.. image:: automatic-archive.png

When you click "Enable Automatic Archive" the following is shown:

.. image:: automatic-archive-settings-new.png

Select a property to base the automatic archiving on. **Note!** Best proactice is to create a specific property to use for this purpose. Any Custom property of type date or time can be used.

You can then edit the settings for the property you have chosen by clicking the cogwheel for the property.

.. image:: automatic-archive-settings-select.png

Available options can differ depending on how the property is set up. Here's an example:

.. image:: automatic-archive-settings-settings-red.png

+ **Required**: Select this option to make it mandatory to add settings to this property for all pages that use this Page Type.
+ **Date Only**: If date should be the only type of data possible for this property, select this option.
+ **Show in new page**: if this property should be available in the wizard when a new page is created, select this option.
+ **Show in edit properties**: if this property should be available in settings for a page when it's edited, select this option.
+ **Show label**: Select this to show the label for the property.
+ **Custom label**: If Show label is selected, the property name is displayed per default. If you want another label to be displayed, add it here.
+ **Category**: (A description will be added soon).
+ **Default value**: Use this setting to decide what should be shown for the property as a suggested value, when the page is created. Empty is just that, no value. Today displays todays date. You can also base the automatic archiving on another property. See below for more information.
+ **Read only**: A property used for automatic archiving should always be read only.
+ **Limit access permission**: If not all authors are permitted to edit this setting, add the colleagues or groups that should be able to edit these settings here.

Calculate based on another property on the page
------------------------------------------------
Automatic archiving can be a calculated value. Note that the property that is used as base for the calculation, must be one of the other properties for the page.

In this example, the page should be automatically archived one month after the article date:

.. image:: automatic-archive-settings-calculated.png

Note that if the value for the base property can be edited, which often is the case for Article Date, the automatic archiving date is automatically recalculated if the value of the base property is edited.

Automatic termination
-----------------------
Furthermore you can set automatic termination from the archive, based on archiving date. You can find that setting in the Publishing App Settings. See the heading "Archive" at the bottom of this page: :doc:`Publishing App Settings </pages/page-settings/index>`
