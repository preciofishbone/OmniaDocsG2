Publishing App Rollup block
==============================

The purpose of this block is to list all, or some of the Publishing Apps available in the Business Profile.

Settings
***********
The following settings are available for the block:

.. image:: publishing-app-rollup-settings-all.png

General
---------
Here you can add a title for the block.

.. image:: publishing-app-rollup-settings-general.png

Query
-----------
Here you decide what to rollup in the block.

.. image:: publishing-app-rollup-settings-query.png

+ **Scope**: You can choose to rollup all public publishing apps, all the logged in user follows, or to display the last publishing app the user visited.
+ **Only Current Business Profile**: If only publishing apps from the current Business Profile should be listed, select this option (default).
+ **Site Template**: Select Publishing App Template from the list. You must select template, even if just one is available.
+ **Run Query On Load**: Decide if the query should be run on load, so the list is filled with publishing apps, or not. If a list is very long it can be a good idea to add a search box, and to deselect this option. You add a search box under Filter, see below.

Display
--------
Here you can select List View or Card View.

.. image:: publishing-app-rollup-settings-display.png

Available settings depends on what you select. All options are listed below.

+ **Add Column**: If you select List View, you must add at least one Column for the display to work.
+ **Cards per Row**: Available for Card view. As it says, set the number of cards to show per row.
+ **Paging**: Select how paging should work; "No Paging", "Classic" or "Scroll".
+ **Image**: Available for Card view. Choose to display an image or not.
+ **Item Limit**: Set the number of sites to be shown on each "page" of the list.
+ **Sort By**: Select what to sort the list on, and then select Ascending or Descending sorting.
+ **Padding**: You can add some padding between the block's borders and the list.
+ **Show Follow status**: Follow status is indicated by a star, filled if the teamwork is followed, hollow if not, see below for an example.
+ **Open in new window**: For some (maybe all) of of the teamworks, it can be a good idea to open the link in a new window.

If you select STYLES for Card View, the following, additional settings becomes available:

.. image:: publishing-app-rollup-settings-styles.png

Filter
------------------
Here you can add filters so users can filter (= choose to just see some) of a long list.

.. image:: publishing-app-rollup-settings-filter.png

+ **Add filter**: To add filters, click this link. See below for more information.
+ **Show Search Box**: To add a search box, select this option. You can do that without adding filters.
+ **Enable partial word search**: Per default the search will onfly find whole words, so a search for Chris will find just that, not for example Christina. But if you select this option, the search will find parts of words as well, so both Chris, Christina and Christian, for example.
+ **Hide filter by default**: If you chose a search box you can select this option. Then no filters are shown until users has executed a search and got a search result.

In Omnia 7.0 and later, new options for filtering can be available, see: :doc:`Filter options for blocks in Omnia 7.0 </blocks/general-block-settings/filter-options-block/index>`

Layout and Write
*********************
The WRITE TAB is not used here. The LAYOUT tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

