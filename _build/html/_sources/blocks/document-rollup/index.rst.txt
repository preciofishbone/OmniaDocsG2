Document Rollup
===========================================

Using The Document Rollup block you can show suitable documents in a list. 

For implementation examples, see this page: :doc:`Document Rollup implementation examples </blocks/document-rollup/document-rollup-implementation/index>`

Settings
*************************
The following settings are available:

.. image:: document-rollup-settings-all-new3.png

General
-----------------
Here you can set the following:

.. image:: document-rollup-settings-general-new6.png

+ **Title**: If a title should be shown for the block, add it in this field. The title can be added in any, or all tenant languages. Click the flag to change language.
+ **Open in Client App**: Documents are by default opened in the online app. If document should be opened in the client app instead, select this option.

Query
---------
You can either choose to pick documents to be displayed in the block, or use the Query Builder.

.. image:: document-rollup-query-new2.png

Pick Documents
^^^^^^^^^^^^^^^^^
To pick documents, click "ADD DOCUMENT".

.. image:: document-rollup-pick-new2.png

The Document Picker opens and you use it to select documents.

.. image:: document-rollup-document-picker-new.png

See this page for more information on how to use the Document Picker: :doc:`The Document Picker </general-assets//document-picker/index>`

Query Builder
^^^^^^^^^^^^^^
Here you add queries, which is the detailed "settings" for what to display in the list:

1. Set scope for the document rollup: 

.. image:: document-rollup-settings-query-scope-new2.png

+ **All Documents** - always available, meaning ALL documents the logged in user has permissions to read. Use the query settings below to limit what will be shown in the rollup. The rollup can then be set to display just "normal" documents or both normal and controlled documents. To rollup documents from one or more Team Sites, use this option.
+ **Published Documents**  - available only if Controlled Documents is active. Meaning ALL published CONTROLLED DOCUMENTS the logged in user has permissions to read. Use the query settings below to limit what will be shown in the rollup.
+ **Archived Documents** - available only if Controlled Documents is active. Meaning all published Controlled Documents in the Archive. As permissions to read documents in the Archive normally is given to just a few, this is for specialized implementations.

**Note!** Regardless of what you select here, the documents that will be displayed for a user are only those documents that the user has premissions to read.

2. Use the three lists for base settings and the field to add a Query Parameter. 

.. image:: document-rollup-settings-query-scope-settings.png

3. Click "Add" to add the Query. 

Note that you can type the script directly in the field, if you know how. You can use all options in the Keyword Query Language (KQL). See this Microsoft page for reference: https://docs.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference

Additionally you can set:

.. image:: document-rollup-settings-query-scope-settings2.png

+ **Day Limit**: Use this option to limit the display of older documents. You first select property (for example Modified) and then select how old the documents can be to be displayed in the list.
+ **Last modified by current user**: Use this option to limit the rollup to documents the logged in user has edited, for example for a "My Latest Documents" implementation.

Display
---------------
You can select "List View", "Summary View", "Group by site" and "Card" here. Available settings differ depending on your choice.

For **List View** you can set the following:

.. image:: document-rollup-settings-display-new3.png

+ **Add Column**: Select the columns to show in the list. Note! If users should be able to send feedback on controlled documents, add the column "Feedback Icon". In the rollups shown in the implementation section below, the Feedback icon is the icon to the far right. An information icon can also be very useful as it displays more information about the document.
+ **Trim by Following Sites**: If this option is selected only documents from sites the logged in user follows are displayed in the list.
+ **Sort By**: Select the column the list should be sorted by.
+ **Paging**: Select paging for the list here. It can be "No paging", "Classic" or "Scroll".
+ **Item Limit**: Shown when No Paging is selected. Set the item limit to display in each "page" of the list.
+ **Page Size**: Shown when Classic or Scroll paging is selected. Set the item limit to display in each "page" of the list.
+ **Padding**: Use this setting for padding around the contents in the block.

If you select "Adjust Columns" - displayed when you have selected columns - you can set the width for the columns, if needed:

.. image:: document-rollup-settings-display-width.png

For **Summary View** these settings are available:

.. image:: document-rollup-settings-summary-view.png

+ **Title**: Select property to to get the title from.
+ **Modified At**: Select the property to get this information from.
+ **Modified By**: Select the property to get this information from.
+ **Trim by Following Site**: If this option is selected only documents from sites the logged in user follows are displayed in the list.
+ **Sort By**: Select the column the list should be sorted by.
+ **Paging**: Select type of paging here; No Paging, Classic or Scroll.
+ **Item Limit**: Shown when No Paging is selected. Set the item limit to display in each "page" of the list.
+ **Page Size**: Shown when Classic or Scroll paging is selected. Set the item limit to display in each "page" of the list.
+ **Padding**: Use this setting for padding around the contents in the block.

For **Group By Site** these settings are available:

.. image:: document-rollup-settings-display-group-new2.png

+ **Title**: Select property to to get the title from.
+ **Modified At**: Select the property to get this information from.
+ **Modified By**: Select the property to get this information from.
+ **Always Show Letter Avatar**: If letter avatars always should be shown, select this option.
+ **Trim by Following Site**: If this option is selected only documents from sites the logged in user follows are displayed in the list.
+ **Sort By**: Select the column the list should be sorted by.
+ **Item Limit**: Set the item limit to display in each "page" of the list.
+ **Padding**: Use this setting for padding around the contents in the block.

For **Card** view the following settings are available:

.. image:: document-rollup-settings-display-card-new3.png

+ **Title**: Select property to to get the title from.
+ **Modified At**: Select the property to get this information from.
+ **Modified By**: Select the property to get this information from.
+ **Show Modified By Info**: If it should be shown who the latest version of this document was created by, select this option.
+ **Show Action Buttons**: Makes the following options available in a menu: "Copy link" and "Source library".
+ **Trim by Following Site**: If this option is selected only documents from sites the logged in user follows are displayed in the list.
+ **Sort By**: Select the column the list should be sorted by.
+ **Paging**: Select paging for the list here. It can be "No paging", "Classic" or "Scroll".
+ **Item Limit**: Set the item limit to display in each "page" of the list.
+ **Padding**: Use this setting for padding around the contents in the block.

For Card View, you can also edit Card Spacing, available under STYLES:

.. image:: document-rollup-settings-display-card-style.png

Filter
--------
Here you can add filters to show for the list, or add a search box.

.. image:: document-rollup-filter-new.png

What you can do here is described on this page: :doc:`Filter UI </blocks/general-block-settings/filters/index>`

Refiner
-----------------
Here you select refiners users can use to refine the list:

.. image:: document-rollup-settings-refiners-new.png

+ **Position**: Set position for the refiners here; "Top", "Left" or "Right".
+ **Add refiner**: Click this option to add a a property to use as a refiner. You can add as many properties as is applicable. For each refiner added you can set sort order; "Alphabetical" or "Count". You can also set a limit.

Here's an example:

.. image:: document-rollup-settings-refiners-example.png

Click "Adjust Refiners" to edit the order.

Using STYLE you can set the following:

.. image:: document-rollup-settings-refiners-style.png

Test the options and see a preview in the block.

Layout and Write
*********************
The WRITE Tab is not used here. The LAYOUT tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

