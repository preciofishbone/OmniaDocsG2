Header settings for the Business Profile
==========================================

The following settings are available for the Header:

.. image:: business-profile-settings-header-new3.png

General
*********
Under General you can set the following:

.. image:: business-profile-settings-header-general.png

+ **Background Color**: Set background color for the header here.
+ **Icon Color**: Set icon color here.
+ **Search Box on Header**: If a search box should be available in the header, select this option.
+ **Default Search Box text to Query string (q) value**: Available when the option above is selected. For advanced search implementations. With this option active you can add parameters to the search query string, for various implementations.

Here's an example with black background color, white icon color and a search box:

.. image:: business-profile-settings-header-general-searchbox.png

Logo
*******
Use these settings for the logo in the Heading.

.. image:: logo-in-heading.png

The following settings are available:

.. image:: logo-settings-bp-new.png

+ **Url**: Add the Url to the Logo Image here (or use the Media Picker, see below).
+ **Logo Text**: Here you can add a text for the logo, if applicable. You can add it in any or all available tenant languages.
+ **ADD IMAGE**: To use the Media Picker to select Logo Image, click this link. See this page for information on how to use the Media Picker: :doc:`The Media Picker </general-assets/media-picker/index>`
+ **Padding**: Use these settings to add som padding around the Logo, if needed.

Mega Menu
***********
The Mega Menu makes it possible for the end user to navigate to any page in the navigation structure. It is displayed across all sites in Omnia. 

.. image:: mega-menu.png

The following settings are available:

.. image:: mega-menu-settings-new.png

+ **Publishing App**: If you use more than one Publishing App in this Business Profile, you can select Publishing App here.
+ **Page Collection**: Select Page Collection the Publishing Pages of the Business Profile.
+ **Static Display Level**: Defines the number of levels in the navigation term set that will always be displayed in the menu.
+ **Dynamic Display Level**: Defines the number of levels in the navigation term set that should be displayed in the mega menu when a user clicks an item in the static menu.
+ **Max Height**: As Default, the menu's Height is dynamic, meaning it adapts to the Height needed. You can set a fixed Height in pixels if you wish.
+ **Max Width**: As Default, the menu's Width is dynamic, meaning it adapts to the Width needed. You can set a fixed Wodth in pixels if you wish.
+ **Background Color**: As Default, the Background Color for the Mega Menu is the same as the Header, but you can set another Background Color if you wish.
+ **Text Color**: As Default, the Text Color for the Mega Menu is the same as the text in the Header, but you can set another Text Color if you wish.
+ **Selected Border Color**: Ypou can set Border Color separately if you wish. Default=no Color.

Action Menu
**************
The Action Menu is this part of the Heading:

.. image:: action-menu-startpage.png

You can use these settings:

.. image:: action-menu-settings-new2.png

+ **Components**: This column lists the Components that can be displayed in the Action Menu. "My Teams" and "Notification Panel" has additional settings, see below.
+ **Display**: You can decide which Components to display, and how: "Pinned" - is default, an Icon will be displayed; "Hidden" - if you don't want the Component to be available; "Menu" - if you want to display the Component in the menu (the three standing dots) instead as an Icon.
+ **Order**:  You can decide the order for the Components you're displaying, from left to right.

Teamwork Navigation - additional settings
----------------------------------------------
Click the cog wheel to set additional settings for Teamwork Navigation. Here's what you can set:

.. image:: teamwork-navigation-overview.png

You can edit which Categories (tabs) to display in Teamwork Navigation and you can work with a number of details for what is actually shown under each category. Using the option Create Teamwork you can edit the settings for what is to be displayed regarding Show Create New Site, and if that option should be available for users at all.

Note that a category is basically a Team Collaboration Rollup, so if you think along this line when you edit the settings for a category, you're on the right track.

Categories
''''''''''''
You can edit categories this way:

+ Click the dust bin to remove a category.
+ Click the cog wheel to handle the detailed settings for a category. 

When editing settings for a category, the same settings are available as when creating a new category, see below.

+ To add a new category, click ADD.

.. image:: teamwork-navigation-add.png

The following settings are available:

.. image:: teamwork-navigation-add-settings.png

+ **Category Name**: Add a name for the category (tab) here, in some or all the available languages.

Query
'''''''
For Query you can set:

.. image:: teamwork-navigation-addquery.png

+ **Scope**: Open the list and select the type of query the execute for this category.
+ **Run Query On Load**: For a shorter list of Teamworks, it most likely works fine to run a query when the list is opened, but for longer lists it may not. For a longer list, for example a list of all Teamworks, deselecting this option and instead displaying a search box, may be a better choice. 

To add a search box, use the Filter settings, see below.

Display
'''''''''''
Display has the follwing settings:

.. image:: teamwork-navigation-add-display.png

+ **View**: Select type for view for the list; List View or Navigation View. If you select List View you must also add at least one column.
+ **Title**: You can choose to add a title to be shown at the top of the list, to for example use for and explanation of what links is shown.
+ **Paging**: Use this option to decide how paging should be handled for this list; No paging, Classic or Scroll.
+ **Item Limit/Page Size**: Set the number of links that should be displayed before a Show more message is shown.
+ **Show Follow Status**: Set to show the stars for follow status, or not (se below for en example.)
+ **Open in New Window**: Decide if the teamwork should open in a new window or not, when the link is clicked.
+ **Padding**: Set some padding between the border of the list and the lit's content, if needed.

Here's an example with Show Follow Status selected. A filled star indicates that the user follows the teamwork.

.. image:: teamwork-navigation-add-display-follow.png

Use the filter settings to make filters available for users, in the list.

Filter UI
''''''''''''''
You can set this for Filter UI:

.. image:: teamwork-navigation-add-display-filterui.png

+ **ADD FILTER**: Click to add filters. It's done the same as for the Teamwork Rollup block, see: :doc:`Team Collaboration Rollup </blocks/team-collaboration-rollup/index>`
+ **Show search box**: Select this option to display a search box at the top of the list. Also see the comments under Query above.
+ **Hide filter by default**: This could be a handy option to use together with Show search box. Select this option if you want to show filters after a search has been executed (not before).

Don't forget to save your changes, you have to click SAVE both for the detailed settings and under Action Menu for the changes to take effect.

Notification Panel - additional settings
----------------------------------------------
Click the cog wheel to set additional settings for Notification Panel. The following settings can be used:

.. image:: notification-panel-settings-notification-panel.png

What you actually do is using a Notification Panel block to display in the heading. Therefore, these settings are exactly the same as are described here: :doc:`The Notification Panel block </blocks/notification-panel/index>`

App Launcher
***************
Omnia can replace the Microsoft 365 App Launcher with the Onnia App Launcher, to make it fully configurable. Here you can edit settings for the Omnia App Launcher, for the Business Profile. 

.. image:: omnia-app-launcher.png

The following settings are available:

.. image:: app-launcher-settings-overview.png

+ **Enable**: The first step is to decide to use the Omnia App Launcher or not (which means using the default Microsoft 365 App launcher). 

Note that there's a feature available for the tenant to install default App Launcher links to make it really easy to get going with the Omnia App Launcher. For more information, see: :doc:`Features - Tenant </admin-settings/tenant-settings/features/index>`

App Launcher Button
--------------------
Here you can set background color, icon color and hover color, if you're not happy with the default color settings.

General
---------
The following settings are available here:

.. image:: app-launcher-settings-general.png

+ **Title**: Set the title for the App Launcher in any or all availbale languages. This is shown as the Tool Tip for the button.
+ **Sorted By**: Open the list and decide how to sort the icons; Custom, Alphabetic or Last Visited. If you choose Custom, use the option "Custom" below for sorting.
+ **View Template**: The icons can be viewed in a number of ways; Simple List, App Icons, Navigation View or App launcher. See below for examples.
+ **Include Non-mandatory links**: (A description will be added soon.) 
+ **Use Targeting**: (A description will be added soon.)  
+ **Include Personal Links**: (A description will be added soon.)  
+ **Include Following Links**: (A description will be added soon.) 
+ **Categories**: (A description will be added soon.) 
+ **Item Limit**: (A description will be added soon.) 
+ **Padding**: Add some padding between the mwnu's border and the icon list, if needed.

In the following View Template examples, the sorting is Custom.

Example of View Template Simple List:

.. image:: app-launcher-settings-general-simple-list.png

When the View Template App Icons is selected, the list can look something lika this:

.. image:: app-launcher-settings-general-app-icons.png

With the Template Navigation View it can look like this:

.. image:: app-launcher-settings-general-navigation-view.png

The View Template App Launcher makes the list look like the Microsoft 365 App launcher, for example:

.. image:: app-launcher-settings-general-app-launcher.png

Custom colors
---------------
Here you can set custom colors for the icons, if needed:

.. image:: app-launcher-settings-custom-colors.png

Custom Sort
-------------
If you selected Custom Sort under Sorted By, use these options to customize the sorting. Click the up arrow or the down arrow to move an icon in the list.

.. image:: app-launcher-settings-custom-sort.png









