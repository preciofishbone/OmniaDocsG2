Analytics report
========================

**This page is being updated.**

This is a new block in Omnia 7.6. Using this block you can display a list of pages in a business profile and see the usage.

Here's an example where the block is used in a governance hub with a lot of filter options:

.. image:: analytics-report-example-hub.png

Note that the block requires a fairly broad space to display all default columns in the list.

Settings
*****************
The following settings are available for this block:

.. image:: analytics-report-settings.png

General
------------
The following can be set under General:

.. image:: analytics-report-settings-general.png

+ **Title**: You can add a title for the block if needed.
+ **Connection key**: An anlytics report block kan be connected to one or more widget blocks to use the filters set up in the Analytics filter block. If you want to use the filters from an Analytics filter block here, add the connection key from that block. (And then you don't need to set any filter settings in this block).

Query
---------
Here you select web site and category, and when you have selected a category, you can also select a report. Here's an example:

.. image:: analytics-report-query.png

+ **Websites**: Select the website to show analytics data for. In most cases, a "website" is the analytics data for a business profile.
+ **Category**: Select the category to display in the block.
+ **Report**: Select report here. Available reports depend on category chosen.

Display
-------------
Here you choose Table view or Card view. The following settings are available for Table view:

.. image:: analytics-report-settings-display-table.png

And the folllowing for Card view:

.. image:: analytics-report-settings-display-card.png

(Details will be added soon).

Filter
--------
You can decide to display a number of filters. Select "Show" to activate a filter.

.. image:: analytics-report-settings-filter.png

+ **Period**: Period can be day, week, month or year.
+ **Period date**: Here you set details for the period. Note that you can add custom settings, see this page for more information: :doc:`Custom date filtering </general-assets/custom-date-filtering/index>`
+ **Properties**: This list can be used to add dimension filters the users can filter on. Select one or more properties and then edit the settings. See below for an example.

(The message "No dimension filters" are always shown when no properties/dimension filters has been added).

Here's an example of a dimension filter property setting:

.. image:: analytics-report-settings-filter-dimension.png

Style
------
Not much to it here. You can set some padding if needed.

.. image:: analytics-table-settings-style.png

Layout and Write
******************
The Write tab is not used here. The Layout tab contains general settings for blocks. For more information see: :doc:`General block settings </blocks/general-block-settings/index>`

