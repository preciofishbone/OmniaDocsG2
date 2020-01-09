Page Types
==================

An administrator or an editor with the correct permissions can work with Page Types. A page type contains sections where blocks can be placed for content. Sections can be targeted.

Some blocks can be added to a page type so they are a part of the layout presented to editors of a page based on the Page Type. See the bottom of this page for more information on blocks that belong to the Page Type.

When a new page is created, the editor can choose page type from any available in the page type list.

Edit a Page Type
*****************
To edit a page type, do the following:

1. Go to any page.
2. Edit the page.

.. image:: page-types-edit-page-new.png

3. Open this menu (if it doesn't open automatically):

.. image:: page-types-open-menu-new.png

4. Open the list of page types at the bottom:

.. image:: page-types-open-list-new.png

5. Select the page type you want to edit.

.. image:: page-types-edit-select-new.png

6. Click "Edit".

.. image:: page-types-click-edit-new.png

7. To edit a section, click the section, and then the cog wheel.

.. image:: page-types-edit-section-new.png

For information about various settings and how to place Blocks, see below.

Create a new Page Type
**************************
To create a new page type when you're editing a page, do the following:

1. Click the plus for Page Types.

.. image:: page-types-click-plus.png

2. Add a name for the new page type and click "CREATE".

.. image:: page-types-click-create.png

3. Click the plus to add a section.

.. image:: page-types-add-section.png

4. Select a base layout.

.. image:: page-types-base-layout.png

See the images on the icons for the layouts, for a simple preview of the layout.

5. Use the section settings:

.. image:: page-types-section-settings-new.png

General
----------
Under General, the following can be set:

.. image:: page-types-general-new.png

+ **Width Type**: Set dynamic width ("Full Page") or a fixed width in pixels. When you have selected Fixed, a slider is shown where you can set the width.
+ **Column**: Using the sliders, set a width for each of the column. Default = same width for every column.
+ **Add Column**: You can add a column if needed. The same settings as above can then be used for the new column. 

To remove a column, click the dust bin. By clicking the pen, the following can be set for a column:

.. image:: page-types-columns-pen.png

+ **Chrome**: Set boxed or not for the column.
+ **Color**: The background color for the column can be set here.
+ **Elevation**: If the column should stand out from the page, use the slider to set how much.
+ **Custom CSS**: You can use custom CSS for formatting the column.

Spacing
--------
Here you can set the following:

.. image:: page-types-spacing.png

+ **Section Padding**: Here you can set some padding within the active section.
+ **Column Spacing**: Here you can set the spacing between the columns in this section.
+ **Block Spacing**: You can set spacing between blocks in this section. 

Style
------
This can be set for Style, for the active section:

.. image:: page-types-style.png

+ **Minimum Height**: You can make sure that this section always has a minimun height, regardless of what is shown in the section. Set the height in pixels here.
+ **Background color**: A default background color for sections are set in Omnia Admin. You can set another background color for this section here, if needed.
+ **Background image**: Another option is to use an image as background in this section. When you click "Add Image", the Media Picker starts, see this page for more information: :doc:`Media Picker </general-assets/media-picker/index>`
+ **Elevation**: With this setting you can make the content of the section “stand out” from the page. 

Header
--------
Here you can set the following:

.. image:: page-types-settings-header.png

+ **Title**: If you want a Title to be displayed for the section, add it here. Not mandatory.

You can then decide to use the global settings for the business profile, or custom settings. 

The global settings are set in Omnia Admin, see the bottom at this page: :doc:`Header Settings </admin-settings/business-group-settings/settings/index>`

When selecting custom settings, the following is available:

.. image:: page-types-settings-header-custom-new.png

This is the same settings as for the global settings, see the link above.

Targeting
----------
A section can be targeted by using this setting:

.. image:: page-types-settings-targeting-new.png

Targeting must have been setup in Omnia Admin for this to work, see that section on this page: :doc:`Properties </admin-settings/tenant-settings/properties/index>`

To set up targeting for the section, do the following:

1. Click "Add Targeting Filter".
2. Select Property for Targeting.

.. image:: page-types-settings-targeting-property-new.png

3. Select one or more children for the property.

.. image:: page-types-settings-targeting-properties-metadata-new.png

Or:

3. Select "Include Children", to include all children pf the property.

.. image:: page-types-settings-targeting-properties-children-new.png

4. Click "Add Targeting Filter" to add additional filters.

.. image:: page-types-settings-targeting-additional-new.png

To remove a targeting filter, just click the X.

Advanced Settings
----------------------
In the advanced settings you can use custom CSS styling for the section.

.. image:: page-types-settings-advanced-new.png

Create a Section in a Column
******************************
If needed, you can create a section in a column and then select a layout for the column and set all other section's settings. Here's how:

1. Click the plus for the column.

.. image:: column-layout-click-plus.png

2. Open the Layout list.

.. image:: column-layout-list.png

3. Select layout for the column.

.. image:: column-layout-list-open.png

4. Set the section's settings (see above).

If needed, you can even go a step further and create a new section in one of the new columns.

Delete a section
*****************
If you need to delete a section, here's how to do it:

1. Click in the section (not on any plus).

.. image:: delete-section-1.png

2. Click the dust bin for the section.

.. image:: delete-section-2-new.png

Adding blocks to a Section
***************************
Here's how to add a block to a section:

1. Click the plus for the section.
2. Select block to add.

.. image:: section-add-block.png

Here's an example with a block added:

.. image:: section-block-added-new.png

You add additional blocks, work with the settings, move or delete blocks the same way as editors do when editing a page, see: :doc:`Working with Blocks </blocks/working-with-blocks/index>`

**Note!** When editing a page, blocks that belong to the Page Type is locked, meaning they can not be moved or deleted, and settings for those blocks can't be edited. But content can be edited, if applicable, using Write mode. 

.. image:: using-write-mode.png

More information on editing blocks when editing a page, is found here: :doc:`Edit a Page </pages/edit-page/index>`

Decide to show a section on a device or not
**********************************************
When you're working on a section you can select to show it on different devices or not.

Click this icon:

.. image:: device-support-section-new.png

Then you can decide on which devices to show this section:

.. image:: select-device-section-new.png

Settings
*********
On the "Settings" tab you can set the Properties for all pages created from this Page Type. In many cases it results in fields the page editor has to or can fill in for a page. You can select any of the properties defined in the tenant. See this page for more information about setting up properties: :doc:`Tenant Settings - Properties </admin-settings/tenant-settings/properties/index>`

Here's an example with a Page Type with left navigation:

.. image:: page-type-settings-left.png

It results in these fields being available on the Properties tab for a page:

.. image:: page-type-settings-left-fields.png

And here's an example with a Page Type for News:

.. image:: page-type-settings-news.png

Which results in these fields being available on the Properties tab for a News Article page:

.. image:: page-type-settings-news-fields.png

Set properties for the Page Type this way:

1. Select the properties to be used for this Page Type.
2. Click the dot menu for more settings for a property.

.. image:: page-type-settings-dot-menu.png

Something like the following is shown:

.. image:: page-type-settings-dot-menu-settings.png

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




 
