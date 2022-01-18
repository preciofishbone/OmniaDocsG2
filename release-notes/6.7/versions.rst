6.7.0
========================================
(Omnia 6.7.0 / Workplace 6.7.0 / WCM 6.7.0 / MS 6.7.0)

New Major Features
**************************

_`Copy blocks and sections across pages <https://omnia-docs-g2.readthedocs.io/en/latest/release-notes/6.7/index.html#copy-block-section-clipboard>`_ 
------------------------------------------
- (#129970)

Favicon is now configurable per business profile. 
------------------------------------------
- (#126515)

Calculated Date Properties
-----------------------------------------
- (#123172, #114551)

Automatic Archive
-----------------------------------------
- (#128186, #128942)


Sign off requests
-----------------------------------------


Block for displaying PowerApps
-----------------------------------------


Search Feedback and promoted search results.
-----------------------------------------


Modals and panels will now close on click out 
-----------------------------------------
- (#123157, #122336, #125956)

Yammer for likes and comments
-----------------------------------------

Anchor links
-----------------------------------------


Teams Precense
----------------------------------------


More actions for the people rollup
----------------------------------------
- (#127035, #122406, #126851).

Full Text Search Solution 
---------------------------------------
- (#132701, #124961, #128796, #129938, #129938).


Channels
---------------------------------------

Conditional Consent
---------------------------------------





New Minor Features
**************************
- Its now possible to add a link on an image in an RTF field (#123318, #125364).
- Image descriptions are now rendered as both alt text and title text on the img element (#131343).
- Image default ratios and enforce scaling is now available for images in a section.
- When using a custom icon for a link, it’s now possible to upload an image from your computer. (#116728, #116782)
- When using the Keep text only feature in RTF, all style tags are now removed (Only default HTML styles is kept)
- Its now possible to move document types in the document type tree in Omnia Admin.
- When the accordion/FAQ block has no content, it will be completely hidden in read mode (#128010).
- Its now possible to configure my site to only show a link to Teams (And not also to the SharePoint site) (#121953, #113020).
- Action buttons can now be rearranged within the same action button block (#129574).
- Card view for the document rollup.
- Its now possible to sort pages in the page rollup by title (#127889).
- Important announcements now supports RTF, making it possible to have for example links in the important announcement (#116651).
- Its now possible to start a phone call or MS Teams call directly from the people rollup. (#122406, #127035, #126851).
- SPFx: The Omnia Webpart now supports full width sections. 
- Communities: When following a community you will also subscribe to it.
- Info screen now supports custom colors for important announcements. 
- WCM navigation node page size is now configurable in Omnia Admin.
- Grouping for action buttons.
- AzureAD Sync now supports the Delta API. This means greatly improved sync performance for large customers.
- Its now possible to add the same page collection several times in one page rollup.
- Strengthen profile has a new and improved horizontal design.
- Configurability for the search block has been improved.
- The new mobile navigation now includes siblings and parents.
- An email Icon can now be added to the People search template (#113710).
- Term properties now expand by default if there is only one parent term selected (#127849).
- The WCM archive now allows for any editor to restore thier own archved pages.
- It's now possible to include User Properties as filters for metrics. 


Fixes
**************************
- Page feedback now correctly supports, rich text, limited rich text and plain text (#131183, #131286, #131302, #131487)
- Its now possible to mention people both on name and email, a scroll has been added to the mention list, and the login name is displayed as a tooltip (#125014, #126325)
- Page types now correctly use the default settings for date styles configured on tenant level (#128621).
- Per page property permissions now works correctly in the create page dialog (#126754).
- Calendar rollup now opens details in a custom form in Omnia, solving issues with opening the details of the event in Outlook (#129532, #114133, #119406, #130515).
- Fixes to the layout settings of the notification panel (#128805).
- The cache for the RSS reader has been reduced to 1 minute, this will ensure quicker updates of new entries in the RSS block (#126762).
- Fixed a small styling issue with refiners in search (#128377).
- Improved performance when creating pages in page collections with many entries (#130658).
- The RSS block no longer crashes the page when a faulty URL is supplied in settings (#124703).
- Info screen now keeps settings when switching views. (#132723).
- Fixed a layout issue that could hang the layout editor (#132703).
- Updated execution logic for the script block, its now possible to create redirect script blocks again (#134001, #134333, #134692).
- Corrected a page rollup rendering glitch in mobile (#134007).
- Teamwork rollup now correctly shows all templates when filtering for "Only current business profile" (#134033).
- .ico files are now supported in the Media picker. 
- Fixed an issue that caused videos to not be configurable in info screen. 
- Corrected a data load dependecy between Omnia Admin and blocks for links. 
- Corrected an issue with the search query strings. 
- Terms in the notification panel now keep thier colors even when the item is highlighted (#135024).
- Ensured the notification panel will load the configured icon and not the default one. (#134349).
- Date format is now configurable for the people rollup. 
- Corrected an issue occuring when editing comments (#132670).
- The Create Document Wizard can now create documents in libraries with more than 5000 documents. (#132539).
- Updates to the new indicator logic for notification panel items.
- Improvments to the RTF editor (#132945, #133104).
- Fixed som invalid config for the default page layouts (#133031).
- Design correction for new items in the page rollup Roller view (#134766).
- Several events in the Activity view have been fixed. 
- Improved the way records declaration for ODM published documents are applied (#133646).
- Fixed an issue with deleting selected languages on Tenant level (#113528).
- Removed an invalid option from the Controlled Documents view.
- Its no longer possible to select "Current User" in info screen. (#129720).
- Fixed an issue in the search for published documents in the Controlled documents Authoring site. (#129615).
- Followed sites provider for the teamwork rollup now correctly also filters bnased on configuration (#130011).
- Fixed an issue where Separator Color and Border Radius could not be saved in layout settings (#129423).
- Fixed an issue in process managhemed where non clickable shapes would render as clickable.
- Events created via the copy feature can now be opened directly (#127051).
- Fixed a design issue on the people rolluo (#133847). 
- The central image locations now pages content correctly (#131219, #131639, #134287).
- Stability improvements to the Action Button (#133878).

- Also above also fixes tickets (#127462, ) 

For developers
****************************
- Several agressive CSS selectors have been made less specific, allowing them to be overridden by custom stylesheets.
