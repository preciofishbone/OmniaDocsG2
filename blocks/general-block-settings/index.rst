General Block Settings
===========================================

The Layout tab and the Advanced tab contains settings that are general for most blocks, but scoped for each block. 

.. image:: general-block.png

Adding filters to a block, if it's possible, works the same for most blocks. Find a general description of how to do that at the bottom of this page.

Layout
*********
The Layout tab contain the following settings:

.. image:: layout-tab-new.png

Spacing
--------
Use this setting to add some space from the block's border in to the content.

.. image:: general-spacing.png

Style
------
Use these settings for block style:

.. image:: general-style.png

+ **Chrome**: Select to have no Chrome setting or Boxed.
+ **Background color**: A default background color for blocks are set in Omnia Admin. You can set another background color for this block here, if needed.
+ **Elevation**: With this setting you can make the content of the block "stand out" from the page. See below for examples.

In this example there's no elevation set for the block:

.. image:: no-elevation.png

And here the elevation is set to 2:

.. image:: elevation-2.png

The difference is noticeable at the left side and at the bottom.

Header
--------
For Header you can choose to use the global settings (set up in Omnia Admin) or use Custom Settings for this block.

.. image:: layout-header-new.png

For Custom Header Settings you can set the following:

.. image:: layout-header-custom-new.png

"Separator Size" sets the distance from the heading to the content in the block. The rest of the settings - it's obvious what they do.

Targeting
-------------
A lot of blocks can be targeted to one or more groups using Targeting Properties. The Targeting Properties must be set up in Omnia Admin, see the section on this page: :doc:`Properties </admin-settings/tenant-settings/properties/index>`

To target a block, open the settings for the block and select "Add Targeting Filter".

.. image:: layout-targeting-new2.png

Then select Targeting Property from the list. As the next step you can select to include all Children, or you can target one or more of the Children specifically. Here's an example with the Sweden office selected for the Office property.

.. image:: targeting-sweden-new2.png

You can add as many Targeting Properties for a block as is needed, this way. To remove a target, just click the X.

Advanced
***********
For some blocks you can use Custom CSS settings. You then use this tab.

.. image:: layout-css-new.png

Filter UI
**********
Here's a general description on how to add filters for a block, when the option is available:

The first step is:

.. image:: filter-new-1.png

+ **Position**: Choose where to place the filters; Top, Left or Right.
+ **Add filter**: To add filters, click this link. See below for more information.
+ **Show Search Box**: To add a search box, select this option. You can do that without adding filters.
+ **Hide filter by default**: If you chose a search box you can select this option. Then no filters are shown until users has executed a search and got a search result.

Settings for search box
------------------------
If you added a Search Box you can set the following:

.. image:: filter-search-settings.png

+ **Search Box (Properties)**: Here you can choose that the search should be conducted on Properties or be a Full text search.
+ ** Search Text**: If you selected Properties above you can add a search text here.
+ **Search on XXXXX Title and**: This is available when you selected Properties above. Available for example for documents and pages. Titles are always part of the search. Here you can select additionl properties to be searched. Regarding pages, if you select one or more properties here, the text in blocks on pages, using these properties, are also searched.

Add filter
---------------
To add filters, do the following:

1. Click "Add filter".

.. image:: filters-new-add.png

2. Open the list and add a property to filter on.

.. image:: filters-new-add-list.png

It can be a quite long list. You can press any key to go that part of the list, for example P to go to properties starting with Page.

Some properties may have additional options, which you normally can choose (not mandatory) for more detailed filter options. Here's an example:

.. image:: filters-new-add-list-2.png

In this example users can select either Anna or Robert as Approved By.

3. Continue adding filters until you're done.

4. If you added several filters, select "Adjust Filters" the decide the order.