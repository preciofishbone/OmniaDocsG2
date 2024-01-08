Search
============

The Search block can be used for quick search or advanced search. 

**Note!** When used for advanced search, this block needs a really wide area, more or less the whole page.

Settings for search are set up in Omnia admin, see: :doc:`Business profile Settings - Search </admin-settings/business-group-settings/search/index>`

Settings
**********
The following settings are avilable:

.. image:: search-block-settings-3new67.png

General
---------
The General settings are:

.. image:: search-block-settings-general-new.png

+ **Title**: You can add a title for the block here. If variations exists, only one title can be set. In that case, titles in other languages are set in the variations. If no variation exists for the page, you can set the title in any or all languages active in the tenant. 
+ **Auto focus search box**: If this option is active, the search box is automatically in focus when a user opens the page, meaning the user can start searching directly without having to click in the search box first.
+ **Show results in dropdown**: If search results should be available in a dropdown list, select this option.
+ **Dropdown max height**: When the above option is selected you set the maximum height in pixels for the dropdown. Default=0.
+ **Dropdown max width**: When the above option is selected you set the maximum height in pixels for the dropdown. fault=0.
+ **Add @search parameter to the query string**: For advanced search implementations. With this option active you can add parameters to the search query string, for various implementations. 
+ **Run query when no filter**: If the above option is selected, select this option if a search should be executed when the page is loaded.
+ **Search mode**: Select search mode, Quick or Advanced.
+ **Padding**: You can add some padding if needed.

Search Categories
-------------------
The following is available here:

.. image:: search-block-settings-categories.png 

You can inherit the search settings from the business profile and if that is what you want to do, you don't need to change anything, it's default.

But if you would like to set specific category settings for this block, deselect and the following will be available:

.. image:: search-block-settings-categories-settings-new2.png 

Quick search
------------------
The folllwing settings are available for Quick search (se image above):

+ **Enable promoted search results**: 
+ **Search categories**: Use it to add search categories for quick search. Open the list and select. 
+ **Image/Icon sixes**: You can set image/icon size to Small, Medium or Large.
+ **Image ratio**: Use this to set the image for the rollup to Landscape, Square or Wide.

.. image:: search-block-settings-categories-quick-select.png

When you have selected a number of categories, you can edit the order, and set a row limit for each category:

.. image:: search-block-settings-categories-quick-select-example-new.png 

Under "View more results" you can set where the "View more" link is placed; "At bottom", "Per category" or "Custom Target". 

.. image:: search-block-settings-categories-quick-view-more-new.png 

Advanced search
-------------------
Here you can set the following:

.. image:: search-block-advanced-settings.png

+ **Hide categories**: By defaul, catogeories (tabs) are shown. If you don't want tha, select this option.
+ **Enable promoted search results**: If this option is selected, promoted search Results can be shown, if any are setup and are applicable.
+ **Enable search feedback**: If it should be possible to use to send feedback about the search result, select this option.
+ **Number of result columns**: Set the number of columns for the search result here.
+ **Refiner position**: Here you can set refiner position to Left or Right.
+ **Refiners collapsed by default**: If just the refiner groups should be shown to begin with, select this option.
+ **Search categories**: Select search categories (tabs) that should be shown.

When you have selected a number of categories, you can click the pen for more settings, for that category.

.. image:: search-block-settings-categories-advanced-new.png 

These settings are available for each category:

.. image:: search-block-settings-categories-advanced-settings-new.png 

Also note that search categories (tabs) that do not generate any result are hidden in Advanced Search.

Style
--------
For Style for the search box, the following settings are available:

.. image:: search-block-settings-style.png

You can try out different style settings and see the result in the block on the fly.

Layout and Write
*********************
The WRITE Tab is not used here. The LAYOUT tab contains general settings, see: :doc:`General block settings </blocks/general-block-settings/index>`

