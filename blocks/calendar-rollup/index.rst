Calendar Rollup
================

Use this block to display events from one or more Calendars. Note that the Calendars are based on Outlook or Exchange, not SharePoint Calendars.

**Note!** In Omnia on-prem, only personal calendars are supported.

Note that a Calendar Rollup block can be targeted, see the common Layout options: :doc:`General block settings </blocks/general-block-settings/index>`

The user experience
********************
A list of events can look like this for a user:

.. image:: calendar-rollup-example.png

The user can click the icon to the right of the event to read more.

Settings
*********
Use these settings for the block:

.. image:: calendar-rollup-settings-new2.png

+ **Title**: If a title should be shown for the block, add it in this field. If variation exists, it looks like in the image above, and only one title can be set. In that case, titles in other languages are set in the variations. If no variation exists for the page, you can set the title in the languages active in the tenant. 

General
---------
Under General you can add a title for the block.

.. image:: calendar-rollup-settings-general.png

Query
-------
Here you select calendars.

.. image:: calendar-rollup-query-new.png

+ **Select Calendar Type**: You can select to add Microsoft 365 group calendars or the current user's calendar.
+ **Select Microsoft 365 Group**: If you have selected "Microsoft 365 group" above you use this field to search for a calendar. 

To add a Micorosoft 365 Group Calendar
--------------------------------------------
Do the following:

1. Select "Microsoft 365 Group".
2. Click in the "Select Microsoft 365 Group" field and search for calendars.
3. Select one or more calenders.
4. Click "Add".

.. image:: calendar-office-add-new.png

5. Continue until all calendars are added to the list.

Ta add the current user's calendar
------------------------------------
Do the following:

1. Select "Current User".
2. Click "Add".

Here's an example with two HR calendars and the current user's calendar selected;

.. image:: calendar-rollup-example-new.png

Targeting and Color for each calendar
--------------------------------------
Each calendar displayed in the block can be targeted and can be shown with a different color. These settings are available when you expand a calendar.

.. image:: expand-calendar-new.png

.. image:: expand-calendar-expanded-new.png

To select another color, open the list. You can select any of the pre defined colors, or add a custom one.

.. image:: expand-calendar-color-new.png

Targeting a calendar works the same way as in many other parts of Omnia. See this page for more information: :doc:`Using Targeting </general-assets/targeting-in-omnia/index>`

You can always target the whole Calendar Rollup block as an alternative, if calendars should be shown for some and no calendars for others. See the link above.

Display
---------
Here you can set the following:

.. image:: calendar-rollup-display-new4.png

+ **View**: Select the view for the list here. (Only Listing is available for now.)
+ **Item Limit**: Set the number of items to display on each "page" of the list.
+ **Padding**: Set some padding around the list if needed.

Layout and Write
*********************
The WRITE TAB is not used here. The LAYOUT tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`




