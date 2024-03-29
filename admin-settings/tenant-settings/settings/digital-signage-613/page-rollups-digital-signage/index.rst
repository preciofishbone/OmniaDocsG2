Page rollups (Digital signage)
=============================================

Here you set up rollups to be used for digital signage. You can use these rollups when you create screens for a web browser.

The list displays rollups that has been set up so far, for example:

.. image:: rollups-signage-list.png

When you click the plus to create a new rollup, the following settings are available:

.. image:: rollups-signage-settings.png

(All options are not shown in the image).

Add a title for the rollup at the top and use the tabs for settings:

QUERY
*******
You work with these settings in a similar way to those in the Page Rollup block.

+ **Pick Pages**: To pick specific pages, select this option.
+ **ADD PAGE**: When you have selected Pick Pages, you can pick pages using the Page Picker. See this page for more information: :doc:`Page Picker </general-assets/page-picker/index>`
+ **Use Query Builder**: If you want to use the query builder to choose pages, select this option.

For Query Builder, the following options are available:

+ **Scope**: When you have chosen to use the Query Builder, select scope for the block. This is where you choose where to get the pages from. You can select:

  + Tenant.
  + Business Profile(s).
  + Publishing App(s).
  + Page Collection(s).
  + Navigation Path.
  + Channel(s).

When you have selected Business Profiles, Publishing Apps, Page Collections or Channels, you select one or more to get the pages from as the next step, just as you would in the Page Rollup block. 

If you select Tenant, Business Profile or Publishing Apps as the scope you can add filters for what you want to display in the list, see below.

The following settings can then be available, depending on scope chosen:

+ **SELECT START NODE**: Available for scope Navigation path. Choose the start point for the navigation path to be displayed. If you select "Custom", you can use the Page Picker to select start node.
+ **Exclude start node**: Available for scope Navigation path. If the start page selected should not be displayed, select this option.
+ **Exclude variations**: Usings this option, you can exclude variations from the query. Not available for Navigation path.
+ **Trim duplicates**: If more than one Rollup is added to a layout, this option can be used to handle duplicates between the rollups. When the option is selected, you can enter a number indicating the priority for duplicates, for this rollup. If you set "1" for a rollup it means it has priority showing a post that would have been a duplicate. 
+ **Like, Comment, Rating**: Use these settings to decide the time period calculated for any of these options. If you don't select anything, it means "No Limit". You can select one week, two weeks or one month instead.
+ **Navigation Depth Level**: Available for scope Navigation path. Choose the number of nodes that should be displayed, including the start node (if shown).
+ **Item Limit**: Type the number to set the number of pages that should be retrieved to make sure all duplicates are found. You should not set this number higher than you really need, as higher numbers may have an impact on performance. Note that when you change the number, "Max Display Limit" is also changed, see below.
+ **Sort by**: Select a property to sort the list by, and then choose Ascending or Descending.

Filter on Tenant
----------------
When you have selected Tenant as the scope, you can add filters for what you want to display, by clicking here:

.. image:: rollups-signage-settings-tenant.png

Filter on Business Profile or Publishing App
----------------------------------------------
When you have selected Business Profile or Publishing Apps as the scope, and added one or more, you can add filters for what you want to display for each selected, by clicking here:

.. image:: rollups-signage-settings-business.png

VIEW
******
Use this tab for view settings, similar to those in the Page Rollup block:

.. image:: rollups-signage-view.png

(Not all options are shown in the image, but described below.)

+ **Title, Summary, Content, Image**: Select property to get the information from, for each of these.
+ **Image Ratio**: For the selected image property, choose Square or Wide here.
+ **Created By, Created At**: Select property to get this information from.
+ **Text Column Width**: Set the text column width in pixels. 
+ **Delay Time Before Scroll (seconds)**: Set the delay time before next scroll.
+ **Scrolling Speed**: Use the slider to set speed of the scroll.
+ **Delay Time after Scroll (seconds)**: Set the delay time after a scroll.
+ **Scrolls Whole Page**: Select this if you want the whole page to scroll.
+ **Show Likes/Comments**: Select if Page Likes and Comments should be shown on the screen.
+ **Show Logo**: To display a logo, select the option and use the settings.
+ **Logo Url**:  Available when "Show Logo" is selected. Add the url to the logo here.
+ **Logo Position**: Available when "Show Logo" is selected. You can choose to display the logo Top Right, Bottom Right, Top Left or Bottom Left.
+ **Logo Size**: Available when "Show Logo" is selected. Use the slider to set logo display size.
+ **Show Indicator**: Select this option to display an indicator.
+ **Indicator Position**: Available when "Show Indicator" is selected. You can chose to display the Indicator Top Right, Bottom Right, Top Left or Bottom Left.
+ **Slides Indicator Color**: Available when "Show Indicator" is selected. Use this option if you need to change Slides Indicator Color.
+ **Count Down Text Color**: Available when "Show Indicator" is selected. Use this option if you need to change the Count Down Text Color.
+ **Show QR Code**: To display a QR code so the page can be easily read on a mobile, select this option.
+ **QR Code Text**: Available when "Show QR Code" is selected. You can add a text here, to be shown by the QR Code.
+ **QR Code Poistion**: Available when "Show QR Code" is selected. You can choose to display the QR Code Top Right, Bottom Right, Top Left or Bottom Left.
+ **QR Code Size**: Available when "Show QR Code" is selected. Use the slider to set the display size of the QR Code.

