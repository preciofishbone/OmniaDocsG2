Advanced search settings
==============================================

You can use these settings here:

.. image:: advanced-search-612-new.png

+ **Collect statistic**: If search statistics should be collected from advanced Search, select this option. Search results can then be displayed in Omnia admin. For more information, see: :doc:`Search statistics </admin-settings/business-group-settings/search/search-statistics/index>`
+ **Search as you type**: The search can be executed either when the user hits enter or ongoing while the user types in the search field. Decide how it should work here.
+ **Hide categories**: If categories should not be shown for users, select this option.
+ **Enable promoted search results**: If it should be possible to see a promoted search result, select this option. Default=selected. For more information, see below.
+ **Enable search feedback**: If it should be possible for users to send feedback on an advanced search result, select this option. For more information, see below.
+ **Enable spelling suggestions**: Select this option to display spelling suggestions in advanced search, when users type in the search field. It's the same functionality that Microsoft 365 has. Note that spelling suggestions only works in English. Must be activated in Omnia admin for the option to show up. Not available in Omnia on-prem.
+ **Number of result columns**: Set the number of columns for the search result here.
+ **Refiner position**: Select where the Refiners will be placed - Left or Right.
+ **Refiners collapsed by default**: Per default, just the headings for the refiners are displayed. If all options for the refiners always should be shown, select this option. 
+ **Search categories**: Open the list to add or remove search categories to use in advanced search.
+ **Item per page**: Here you can see the Item per page setting for each category.
+ **Refiners**: In this column you can see the number of refiners added for the category. 

The search categories are set up under "Search config". Here you can decide which of them to use for advanced search. For more infomation about setting up search categories, see: :doc:`Search config </admin-settings/business-group-settings/search/search-config/index>`

To edit aettings for a category, click the pen. All settings available when creating a new category can be edited, see below.

You can decide the order for a category and it's refiners by grabbing the left most icon and use drag and drop. 

Removing a search category
****************************
To remove a category (or reather deicde not to use it), do the following:

1. Open the list of categories.

.. image:: categories-list.png

2. Deselect the category.

.. image:: categories-deselect.png

Adding a search category
*************************
To Add a new category here, and set refiners for it, do the following:

1. Open the list and select a category.

.. image:: new-refiner-1-612.png

2. Click the pen to enter the settings.

.. image:: new-refiner-3-612.png

3. Set the following:

.. image:: new-refiner-4-612.png

+ **Row limit**: Select number of search result rows to be displayed before a Show more link is displayed. 
+ **Image/Icon size**: Image or Icon size for the search result can set to Small, Medium or Large. Note that category can have a specific size, if needed. 
+ **Image ratio**: Image ratio for the image used in the search result can be set to Landscape, Square or Wide. Note that category can have a specific image ratio setting, if needed. 
+ **Refiners**: Use this option to add refiners for the search category.

To add a new refiner for the category, do the following:

4. Open the list and select a property.

.. image:: new-refiner-5-612.png

When you have added one or more refiners for the category, use the cogwheel to edit settings:

.. image:: new-refiner-6-612-border.png

5. Set the sort order (Alphabetical or Count) and set the item per page.

.. image:: new-refiner-7-612.png

To delete a refiner, just click the cogwheel.

Save when you are done here, and save on the advanced search settings main page as well.

Default value for date refiners
----------------------------------
You can set a default value for date refiners, if needed, to filter out old documents by default. Here's how:

1. Add or edit the refiner.
2. Click the cog wheel.

.. image:: refiner-default-cog.png

3. Use the slider to set the time frame.

.. image:: refiner-default-slider.png

4. Save the changes.

Promoted search results
*************************
If promoted search results are enabled, such search results, if any are applicable, will be shown here:

.. image:: promoted-search-results-place.png

For information on how to create them, see: :doc:`Promoted search results </admin-settings/business-group-settings/search/promoted-search-results/index>`

Search feedback
*******************
If Search feedback is enabled, a button will be shown for end users, for example:

.. image:: search-feedback-button.png

When the user clicks the button, something like the following is shown:

.. image:: search-feedback-form.png

If the user do'nt want to send a snapshot of the search results, that option can be deselected.

Administrators can evaluate the feedback here: :doc:`Search feedback </admin-settings/business-group-settings/search/search-feedback/index>`

