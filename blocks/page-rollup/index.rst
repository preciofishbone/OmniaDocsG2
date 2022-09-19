Page Rollup
===========================================

This block can be used for many purposes, for example:

+ List News in different ways; a news center, new news, latest news etc.
+ Most read pages.
+ Most commented pages.
+ Popular pages.
+ Underused pages.
+ Pages with a certain variation (for example a language).
+ Created but unpublished pages.
+ Various page statistics.
+ Various rollups that authors and editors can benefit from.
+ Part of a News Letter implementation.
+ Part of an Event Management implementation.

For implementation examples, see this page: :doc:`Page Rollup implementation examples </blocks/page-rollup/page-rollup-implementation/index>`

Settings
*********
These settings are available for the block:

.. image:: page-rollup-settings-new5.png

General
--------
Here you can add a title for block:

.. image:: page-rollup-settings-general-frame.png

If any variations exist, titles in other languages are handled through variations. If no variations exist you can add titles in any or all languages in the tenant.

Query
------
Here you can set the following:

.. image:: page-rollup-settings-query-new4.png

+ **Pick Pages**: If the editor should be able to pick pages from a list, select this option.
+ **Pick in Write Mode**: Available when Pick Pages is selected. Select this option if editors should be able to pick pages in Write mode. If not selected, Design mode has to be used.
+ **ADD PAGE**: When you have selected Pick Pages, you can pick some pages to always be shown. Click this option and use the Page Picker. See this page for more information: :doc:`Page Picker </general-assets/page-picker/index>`
+ **Use Query Builder**: If you want to use the query builder to set which pages should be available here, select this option.

For Query Builder, the following options are available:

+ **Scope**: When you have chosen to use the Query Builder, select scope for the block. This is where you choose where to get the pages from. You can select:

  + Tenant.
  + Business Profile(s).
  + Publishing App(s).
  + Page Collection(s).
  + Navigation Path.
  + Channel(s).

When you have selected Business Profiles, Publishing Apps, Page Collections or Channels, as the next step, you select one or more to get the pages from. 

The following settings can then be available, depending on scope chosen:

+ **Cache on client**: This setting can be used to speed up rendering on subsequent page loads. This is is done by storing data in the browser cache. Default: selected.
+ **Current User Subscription**: Available for scope Channels. Select this if only the pages that the logged in users subscribes to should be displayed.
+ **Current Node/Custom**: Available for scope Navigation path. Choose the start point for the navigation path to be displayed. If you select "Custom", you can use the Page Picker to select start node.
+ **Custom Query**: Available for scope Channels. Use this to select one or more channels to rollup pages from. Note that a channel can be targeted to just certain colleagues or groups. See example below.
+ **Filter by user subscription**: Availabel for Scope Channels. Select this if the list should display only thos channels the logged in user follows.
+ **Exclude current page**: Available when you have chosen scope for the Query Builder. The default setting is to exclude the current page, but if you, for some reason, would like to include the current page, uncheck this option.
+ **Exclude start node**: Available for scope Navigation path. If the start page selected should not be displayed in the block, select this option.
+ **Exclude variations**: Usings this option, you can exclude varations from the query. Not available for Navigation path.
+ **Status**: By using this option you can create rollups for pages with the status Never published, Published or Any status. 
+ **Trim duplicates**: If more than one Page Rollup block is added to a page, this option can be used to handle duplicates between the blocks. When the option is selected, you can enter a number indicating the priority for duplicates, for this block. If you set "1" for a block it means this block has priority showing a post that would have been a duplicate. 
+ **Navigation Depth Level**: Available for scope Navigation path. Choose the number of nodes that should be displayed, including the start node.
+ **Page Size**: Use the slider, or type the number (1-99) to set the number of items (pages) that should be displayed on each "page" of the list. Also see under *Display* below for additional settings for the list. 
+ **Query Item Limit**: Use the slider, or type the number (1-99) to set the number of pages that should be retrieved to make sure all duplicates are found. You should not set this number higher than you really need, as higher numbers may have an impact on performance. Note that when you change the number, "Max Display Limit" is also changed, see below.

More on Scope Navigation Path
---------------------------------
Navigation path is a special case, it's used for creating a navigation. When you have selected start node you can choose start node and navigation depth. There's also a view available, specifically for Navigation Path; Navigation View. Select it under Display. It's only available if you first select Navigation Path as Scope.

**A tip**: When you're creating a Page Type, selecting Current Node for a Navigation Path can be very useful. Wherever that Page Type is used, the view (Navigation View) always starts at the current node for that page.

Display
----------
Select View here. Note that a preview is shown in the block.

.. image:: page-rollup-settings-display-new.png

The following lists all available display settings, shown in different order for different displays, here listed in alphabetical order.  

Options for all views
------------------------
These options are available for most views:

+ **Date**: Select the property that contains the date for the item(s) to display. Available for Roller, Listing with image, Dynamic Roller, Card and Newsletter.
+ **Dialog Image**: Select image to display, if any. Available when ypu have selected "Open Page as a dialog".
+ **Hide block when no data**: Select this option if the block should be hidden when there's nothing to display.
+ **Hide if read**: Select this option to hide all pages the logged in user has visited. This affects all pages, including news.
+ **Highlight non-read**: This option makes sure non-read pages are highlighted. Default=selected. Deselect if you don't want that.
+ **Image**: Select the property that contains the image for the item(s) to display. Available for Roller, Listing with image, Dynamic Roller, Card and Newsletter views.
+ **Image Ratio**: Select ratio for the image; Landscape, Square or Wide. Available for Roller, Listing with image, Dynamic Roller and Newsletter.
+ **Link label**: Add the text to be shown for the link here. Available only if "Show link" is selected.
+ **Link url**: Add the url to open when a user clicks the link. Available only if "Show link" is selected.
+ **Max Display Limit**: Available only for Scope Navigation Path, for all views. Set the number of pages that should be displayed. 
+ **No result text**: Enter the text that will be shown if no page can be displayed.
+ **Open in Editor**: Available for all views except Calendar. If this option is selected, a page link can be clicked to open the page in edit mode. This options was devolped with rollups for editors and authors in mind. Permissions apply, so if a user without any edit permissions for the page opens a page this way, nothing can be edited.
+ **Open in new tab**: If the link should be opened in a new tab (as opposed to in current window or dialog), select this option.
+ **Open page as a dialog**: If the page should be opened in a dialog instead for in a page (new or current), select this option. 
+ **Padding**: Add some padding between the list and the block border, if needed.
+ **Paging**: Select paging here; "No paging", "Classic" or "Scroll". Available for List View, Dynamic Roller, Card and Newsletter.
+ **Show Likes/Comments**: If the number of likes and comments should be displayed for the item, select this option. Available for Roller, Listing with image, Dynamic Roller and Card.
+ **Show link**: You can add a link button at the bottom of the list. The first page collection is default, but you can link to any target. 
+ **Sort by**: Choose what the list should be sorted by, and then select ascending or descending. Available for all, except Navigation View. Note that on Omnis 6.12 and later the sorting is extended. You can now sort on Comment, Like, Rating, Feedback, Last Activity and Last Commented. For the Navigation View you can also sort on Navigation. 
+ **Summary**: Select the property that contains the page summary for the item to display. Available for Listing with image, List View, Dynamic Roller, Card and Newsletter.

Roller
------
Contains general settings only, see above. 

Listing with image
-------------------
Contains mostly general settings, see above. The only special setting is:

+ **Show Rating**: If the rating for the page(s) displayed should be shown, select this option. 

List View
------------
Contains mostly general settings, see above. The only special setting is:

+ **Show Export to Excel**: If it should be possible for users to export a list to Excel, select this option. When this is done, an "Export to Excel" button is shown. 

You also have to add at least one column, for the display to work. See below for more information.

Dynamic Roller
-----------------
The special settings for this view are:

+ **Autoplay**: If the roller should roll automatically, select this option. 
+ **Delay between slides**: Set the time between slides in milli seconds.
+ **Loop**: Normally a roller stops when the last post is reached (and can restart after a short while). When this option is selected, there is no "end" and the roller just keeps rolling. Important note: When Loop is selected the arrows users can use to roll "manually" are not shown.
+ **Number of slides to display**: Select number of slides, 1-12.
+ **Show Paging**: Small icons shown that users can use to page back and fort. See image below for an example.
+ **Show Navigation**: If navigation icons for the users to use for rolling should be shown, select this option.
+ **Slider Size**: Select the size of the slider here: Small, Medium, Large or Extra large. 
+ **Slider Type**: Select Horisontal slider or Vertical slider. 

For the general settings, see above.

Card
------
The special settings for this view are:

+ **Cards per Row**: As it says, set the number of cards to show per row.
+ **Person**: This option can be used to show properties in Card view.
+ **Show Page Type**: If this option is selected, the Page Type used for the page is shown as metadata, the same way as other properties.
+ **Term properties**: Can be used to show properties in Card view. Click "Add" and select a property. Continue the same way for additional properties.

For general settings, see above.+

In Omnia 6.12 and later you can choose where meta data for Date and Person will be placed. Click here to display options:

.. image:: place-meta.png

Then use the settings to select Top Left, Top Right, Bottom Left or Bottom Right:

.. image:: place-meta-settings.png

Newsletter
-----------
As it suggests, this view is suitable for use in a Newsletter set up. The special settings are:

+ **Contact**: Select the property to be displayed as Contact. 
+ **Content**: Select the property that contains the page content for the item to display. 
+ **Page Content Character Limit**: If the number of characters displayed for Page Content should be limited, add the number here. The Content is simply jus cut after that. 
+ **Page Summary Character Limit**: If the number of characters displayed for Page Summary should be limited, add the number here. The Summary is simply jus cut after that. 

For general settings, see above.

Event List
------------
As it suggests, this view is suitable for use in a Event Management set up. Contains general settings only, see above. You also have to add at least one column, for the display to work. See below for more information.

Navigation View
-----------------
As said above, this is a special case, used for navigation. The Navigation View is only available for Scope Navigation Path. Mostly general settings, see above. the ony special settings is:

+ **Max Display Limit**: To limit the number of items being displayed, add a fixed number here. 

Calendar
---------
The special settings for this view are:

+ **Default Calendar Type**: Can be Month, Week or Day.
+ **Default time**: Select a defaul time from the list.
+ **Enable Calendar Type Dropdown**: Makes it possible for users to select Month, Week or Day.
+ **End date**: Select property to be used for end date.
+ **Event color**: Use it to set specific color for events in the calendar.
+ **Event Height**: Use the slider to set height for the events in the calendar. See a preview in the block.
+ **Height**: Use the slider the set the height for the whole calendar. See a preview in the block.
+ **Include time**: Select this to display time for events in the calendar.
+ **Weekdays**: Select what should be shown as weekdays in the calendar.

For general settings, see above.

Adding columns
----------------
For "List View" and "Event List", you have to add at least one column, for the display to work. Here's an example with three columns added for List View:

.. image:: list-view-columns-new3.png

This could show the following:

.. image:: list-view-example-new.png

Some examples and tips
-------------------------
"a month ago" etc is the "Social" setting for date. If you would like to show exact dates instead, select "Normal".

"Show paging" in settings for "Dynamic Roller" makes these icons available for navigation:

.. image:: show-paging-dynamic-new.png

Here's a simple example of a Card view used for navigation purposes:

.. image:: card-view-example-pages.png

Card view can now display sub pages if the scope "Navigation path" is used. Here's an example:

.. image:: card-view-example-sub-pages.png

The card view also supports a dynamic number of properties that can be displayed in the card. Here's an example:

.. image:: pagerollup-cardview-terms.png

The Navigation View can be used to display a mega menu style navigation. Here's an example of Page Rollup used for this purpose:

.. image:: navigation-view-mega-example.png

Style settings
----------------
For Roller, Dynamic Roller and Card, extra Style settings are available, for example (Card):

.. image:: page-roller-style.png

Just try out these settings. A preview is shown in the block.

Filter
-------
If users should be able to filter the list and/or search here, use these options. 

The following options are specific for the Page Rollup block:

.. image:: page-rollup-filter-65.png

+ **Save filter state**: If you select this option the filter keeps it's state in the page url as long as the page is active, and will be activated when the user goes back to the page, by using the browser's Back button. The url can also be copied and for example be used to prepopulate the page rollup.

The rest of the options are the same as for other blocks. See this page for information on how to use these filter options: :doc:`Filter UI </blocks/general-block-settings/filters/index>`

Time Period
--------------
These settings where called Social Period in earlier Omnia versions. The following settings are available here:

.. image:: page-rollup-settings-social-new3.png

Use these settings to decide the time period calculated for any of these options. If you don't select anything, it means "No Limit". You can select one week, two weeks or one month instead.

Filter on a specific variation
--------------------------------
If just pages with a certain variation (language or other variation) should be listed in the rollup, it can be done this way:

.. image:: page-rollup-variation-example-new.png

Only News in Swedish will be listed in this example.

Layout and Write
**********************
The WRITE tab is not used here. The Layout tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

