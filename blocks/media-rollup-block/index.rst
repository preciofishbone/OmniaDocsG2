Media rollup
========================

This is a new block in Omnia 7.6. The purpose is to rollup different types of media resources for easy access, mainly for end users, but can also be configured to be of use for editors, for example if official images are located somewhere else than in any of the Central media locations.

**The documentation is just started with a preliminary description. More will be added soon.**

Settings
***********
The following settings are available:

.. image:: media-rollup-settings.png

General
---------
Add a title for the block, if necessary.

.. image:: media-rollup-settings-general.png

Query
-------
Here you select the data source for the rollup.

.. image:: media-rollup-settings-query.png

You can rollup media files from a SharePoint library or you can use SharePoint search.

In both cases, start by selecting to rollup images, video or audio.

.. image:: media-rollup-settings-query-library-new.png

Media files from a SharePoint library
---------------------------------------
The next step for a Sharepoint library is to add a path to the library, or just accept the default path (more info about this soon).

.. image:: media-rollup-settings-query-library-path.png

Media files through SharePoint search
-------------------------------------------
For SharePoint search you can add a query the same way as for many other blocks in Omnia:

.. image:: media-rollup-settings-query-search.png

Display
-----------
For display, you can choose a list view or a photowall view. For "List view" you must add at least one column for the rollup to work, and use these settings:

.. image:: media-rollup-settings-displat-list.png

If you select "Fixed header", the header is always shown when users scroll the list.

The rest of the options should be self explanatory.

**A tip!** If you would like to make it possible to download the media files in the list, there's a "Download" column you can add.

Here's a simple example of a list with a small preview and a download icon:

.. image:: media-rollup-settings-displat-list-example2.png

For photowall, these settings are avialable:

.. image:: media-rollup-settings-display-photowall.png

Here's an example of a photowall display with three columns:

.. image:: media-rollup-settings-display-photowall-example.png

For a larger view, click a file. The media list can then be browsed this way:

.. image:: media-rollup-settings-display-photowall-example-browse.png

Filter
----------
For filtering, common options are available. See this page for more information: :doc:`Filter options for blocks </blocks/general-block-settings/filter-options-block/index>`

Style
------------
Under "Style", you can set some padding.

.. image:: media-rollup-settings-style.png

Layout and Write
******************
The Write tab is not used here. The Layout tab contains general settings for blocks. For more information see: :doc:`General block settings </blocks/general-block-settings/index>`

