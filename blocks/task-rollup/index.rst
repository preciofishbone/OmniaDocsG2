Task rollup
===========================================

This block can be used to show tasks assigned to the logged in user. Tasks from teamsites will always be shown. Tasks from Planner can also be added, if setup in Omnia.

**Note!** In Omnia on-prem, only SharePoint tasks are supported (Planner tasks are not).

All sites with tasks assigned to the user is displayed in a list. Here's an example with the list opened for one of the sites:

.. image:: tasks-rollup-example-new2.png

Settings
*********
The following settings are available:

.. image:: tasks-rollup-settings-v75.png

General
---------
Here you can add a Title for the block in any tenant language, if needed:

.. image:: tasks-rollup-settings-general-v75.png

Query
--------
For Query, you can set the following:

.. image:: tasks-rollup-settings-query-v75.png

+ **Day limit**: How many days forward in time to show assigned tasks. 0 = no limit.
+ **Enable Planner tasks**: Check the box to include tasks from planner in the Tasks rollup.
+ **Client cache in minute(s)**: (A description will be added soon).

Display
----------
These settings are available for Display:

.. image:: tasks-rollup-settings-display-v75.png

+ **Row limit**: The maximum number of tasks to show in the list.
+ **Sort by**: Select which column the list should be sorted on, and then select ascending or descending.
+ **No result text**: If you would a specific text to be shown when there are no tasks to show, add it here in an tenant language.
+ **Always show letter avatar**: Select if a letter avatar should always be shown instead of site image.
+ **Open in new window**: Select this option if tasks should be opened in a new window (default=selected).
+ **View template**: Select view template here; "Simple list" or "Grouped list".
+ **Padding**: You can add padding between the list and the block border if needed.

Custom colors
----------------
Here you can set custom colors for the block.

.. image:: tasks-rollup-settings-colors-v75.png

Layout and Write
*********************
The WRITE TAB is not used here. The LAYOUT tab contains general settings, see: :doc:`General block settings </blocks/general-block-settings/index>`

