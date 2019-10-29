People Rollup
===========================================

Use this block to display lists of people, for many various reasons.

Here are two examples. New Recruitments and People on the Move are different People Rollup blocks.

.. image:: people-rollup-example.png

Settings
*************************
The following settings are available:

.. image:: peoplerollup-settings-new.png

General
----------------
Here you can add a Title to be displayed for the block:

.. image:: peoplerollup-settings-general.png

Display
-----------
You will be able set the type fo view to be used for the list here:

.. image:: peoplerollup-settings-display.png

You can choose to display the list as a Card view or Roller view.

In the image at the top of the page, Card view is used. See below for a Roller example.

The following settings are available for the views:

+ **Add Column**: Use this setting to add columns to the list. Note that this is important even for Card view. IKt's the "Columns" that actually shows information about the people. You must always add at least one column!
+ **Person Name**: Select property to get the Person Name from.
+ **Show Profile Image**: Select this option to show the person's image.
+ **Slide Height**: Set the height of the area to show the content in. Available for Roller view only.
+ **Alignment Option**: Set vertical alignment for the content. Available for Roller view only.
+ **Justify Options**: Set horizontal alignment for the content. Available for Roller view only.
+ **Show Achivements**: This option is a preparation for functionality to come. Available for Card view only.
+ **Max no of Columns**: Set the maximum number of columns to be displayed.
+ **Sort By**: Select the property to sort the list by.
+ **Paging**: Select how paging should work; “No Paging”, “Classic” or “Scroll”. See below for examples. Scroll is note applicabale for Roller view.
+ **Item Limit**: To limit the number of items being displayed, add a fixed number here. If you set a high number (for example the default, 50) as many people as meets the query criteria is shown, up to that number. If you set a low number, that is the number of people tha list wil show, regardless of how many meets the query criteria.
+ **Left Zone Width, Right Zone Width**: For the Roller view, the width of the left and right zones are per default handled dynamically. Here you can set a specific width in pixels, if needed.

Here's an example of a  Roller view, with Slide Height 150, Alignment Center, Justify Center, No Paging and Item Limit 5.

.. image:: roller-view.png

Query
-----------
Here you can work with the Query for what to display in the block.

.. image:: peoplerollup-settings-query.png

Follow these steps:

1. Select Query Type, Profile Query or Activity Query.
2. If you selected Activity Query, choose Activity period (also called Social Period in some other blocks). This sets how old the item can be to be displayed in the list. The default is "No limit", but you c an also select One Week, Two Weeks or One Month.
3. Select property for the query.

.. image:: query-property-1.png
.. image:: query-property-2.png

4. Set additional query parameters. Exactly what needs to be done depends on the property chosen.

Here's an example with parameters set for Department:

.. image:: query-parameters.png

5. Type a parameter if neded (needed for Manual or Query Parameter).

.. image:: query-type-parameter.png

6. Click "ADD" to add the query from your settings.

.. image:: query-add.png

It can result in something like this:

.. image:: query-added.png

Note that you can type the script directly in the field, if you know how.

You can also add additional parameters. by using the method explained above or typing directly in the field. Here's an example when the script collects users from two departments:

.. image:: query-more.png

Filter
-------
Use these settings to add filters for the users to use.

.. image:: peoplerollup-settings-filter.png

+ **Position**: Decide where to place the filters; top, left or right.
+ **Add filter**: Click this button to add a filter.

Refiner
---------
Use these settings to add refiners.

.. image:: peoplerollup-settings-refiner.png

+ **Position**: Decide where to out the refiners; top, left or right.
+ **Add refiner**: Click this button to add a refiner.

Layout and Advanced
**********************
The tabs Layout and Advanced contain general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

