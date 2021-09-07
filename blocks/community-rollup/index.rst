Community Rollup block
=========================

This is an ongoing, preliminary documentation of a new block to come in Omnia 6.5. 

Settings
*************
The following settings is available:

.. image:: community-rollup-settings-all.png

General
---------
Here you can add a title for the block.

.. image:: community-rollup-settings-general.png

Query
-----------
Here you decide what to rollup in the block.

.. image:: community-rollup-settings-query.png

+ **Scope**: You can choose to rollup all public communities, all communities the logged in user follows, or to display the last community the user visited.
+ **Only Current Business Profile**: If only communities from this Business Profile should be listed, select this option (default).
+ **Site Template**: 
+ **Run Query On Load**: Decide if the query should be run on load, so the list is filled with communities, or not. If a list is very long it can be a good idea to add a search box, and to deselect this option. You add a search box under Filter UI, see below.

Display
--------
Here yopu can select List View or Card View.

.. image:: community-rollup-settings-display.png

Available settings depends on what you select. All options are listed below.

+ **Add Column**: If you select List View, you must add at least one Column for the display to work. (Navigation View is fixed regarding the columns to display).
+ **Paging**: Select how paging should work; "No Paging", "Classic" or "Scroll".
+ **Item Limit**: Set the number of sites to be shown on each "page" of the list.
+ **Sort By**: Select what to sort the list on, and then select Ascending or Descending sorting.
+ **Padding**: You can add some padding between the block's borders and the list.
+ **Show Follow status**: Follow status is indicated by a star, filled if the teamwork is followed, hollow if not, see below for an example.
+ **Open in new window**: For some (maybe all) of of the teamworks, it can be a good idea to open the link in a new window.

Filter UI
------------------
Here you can add filters so users can filter (= choose to just see some) of a long list.

.. image:: add-filter-new2.png

For more information on how to add filters, or a search box, see this page: :doc:`Filter UI </blocks/general-block-settings/filters/index>`

Layout and Write
*********************
The WRITE TAB is not used here. The LAYOUT tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

