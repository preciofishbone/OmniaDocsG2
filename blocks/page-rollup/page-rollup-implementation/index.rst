Page Rollup implementation examples
==============================================

Here you will find some examples of how the Page Rollup block can be used.

**These page is being updated. Will be finished soon.**

News Archive/News Center
--------------------------
The purpose of a News Center is to display ALL published news for the users to read. Normally a News Editor can create and edit news artcicles from there.

Here's an example of how the user interface can look:

.. image:: page-rollup-example-news-center-new.png

(The "Create News Article" button is shown only for those that has the permission to create News.)

The Page Rollup can be set up the following way:

+ Query: Scope - Page Collections, News (the Page Collection with the name "News").
+ The option "Exclude current page" can be a good idea to have selected. 
+ The option "Enable partial word search" is also useful in this case.
+ Social Period: All default.

.. image:: news-archive-example-1new.png

+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: news-archive-example-1new-display.png

and these:

.. image:: news-archive-example-2new.png

and finally, these:

.. image:: news-archive-example-3new.png

Note the "Show create button" option, the label for that button and the option to set in which Page Collection these pages are created (in this case "News", the Page Collection selected under "Query").

+ Filters: A search box is always a good idea in a News Center. The users should most likely also be able to filter the list on one or more properties, for example:

.. image:: news-archive-filters-new.png

+ Page Variations: None. (If Page variations will be used, for example for different languages, it will be used on the pages. Or a separate News Center could be set up for News in other languages, or for any other purpose, for that matter.)

Latest News
-------------
The purpose of this Page Rollup is as it says - to display a number of the latest News.

It can look like this for users:

.. image:: page-rollup-latest-news-example-new.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ The option "Exclude current page" can be a good idea to have selected. 
+ The option "Enable partial word search" is also useful in this case.
+ Social Period: All default.
+ Display: Depends on how you want it to look, of course. In the above example, these settings are used:

.. image:: latest-news-example-1new.png

and these:

.. image:: latest-news-example-2new.png

+ Filters: none.
+ Page Variations: Default Variations.

Most Commented News
----------------------
The purpose of this Page Rollup is as it says - to display a number of the most commented News.

It can look like this for users:

.. image:: page-rollup-example-most-commented-news.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Comment: If you don't want old comments to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: most-commented-example-1new.png

and these:

.. image:: most-commented-example-2-new.png

+ Filters: none.
+ Page Variations: User variation.

Most Liked News
-----------------
The purpose of this Page Rollup is as it says - to display a number of the most liked News.

It can look like this for users:

.. image:: page-rollup-most-liked-news-example.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Like: If you don't want old likes to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: most-liked-example-1new.png

and these:

.. image:: most-liked-example-2new.png

+ Filters: none.
+ Page Variations: User variation.

News - Dynamic Roller
------------------------
When a Dynamic Roller display is used for news, it can look like this:

.. image:: dynamic-roller-example-new.png

In this example the Page Rollup block is set up this way:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Like: If you don't want old likes to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: dynamic-roller-example-1new.png

and these:

.. image:: dynamic-roller-example-2new.png

and, finally, these:

.. image:: dynamic-roller-example-3new.png

(Padding is set to 0, not shown in the image above.)

+ Filters: none.
+ Page Variations: User variation.
