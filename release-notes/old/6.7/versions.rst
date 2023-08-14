6.8.15
========================================
(Omnia 6.8.15 / Workplace 6.8.12 / WCM 6.8.15 / MS 6.8.9)

-	Corrected an issue in the default community template
-	Removed an incorrect permission check on the Process Management Tenant feature (#138395)
-	Improved performance in the create page dialog (#136922)
-	Fixed an issue with the Teamwork rollup search (#138358)
-	Made page visit registration more accurate
-	Non functional updates to prepare for 6.10 release.
-	Corrected an issue with assigning Co-authors in communities (#137109)
-	Combining a navigation path query with a date sort now works as expected.


6.8.14
========================================
(Omnia 6.8.14 / Workplace 6.8.11 / WCM 6.8.13 / MS 6.8.7)

- Improved support for languages in Controlled Documents (#137163).
- In the create document wizard, sites can now be searched as expected (#138091, #126154).
- The search result dropdown now renders correctly (#138020).
- Sign off requests can now correctly pick pages from flat page collections (#138134).
- Added a load more button to the Central Image Location media provider (#131639, #134287)
- Improved rendering of search results (#137987).


6.8.13
========================================
(Omnia 6.8.13 / Workplace 6.8.10 / WCM 6.8.11 / MS 6.8.6)

- Added some missing localizations
- Corrected an issue with text styling (#137896, #138106)
- All day events now show correctly in the Calendar Rollup (#137549, #138209)
- Increased the upload size limit for related links when uploading documents (#137736).
- Corrected an issue with text flow on pictures in RTF (#137552, #138029, #138047, #137553)
- Fixed an issue with related documents on controlled documents.
- Subscribing to Tags now works as expected in Communities (#137622, #137830).
- Stability improvements in the Archive (#138143, #138070).




6.8.11
========================================
(Omnia 6.8.11 / Workplace 6.8.9 / WCM 6.8.9 / MS 6.8.5)

- Corrected an issue with filtering in the people rollup (#137678).
- Teams channel feed images now loads in all scenarios.
- OnPrem: Profile card now works as expected. 
- Corrected an issue in the excel export on page reports (#137923).

6.8.10
========================================
(Omnia 6.8.8 / Workplace 6.8.6 / WCM 6.8.7 / MS 6.8.4)

- Updated SPFx install instructions to align with an Url change from Microsoft.
- Corrected an issue with Teams Presence  (#137590).
- Creating new documents from the Document rollup now works as expected (#127591).
- Custom icons now works as expected for related links (#137635).

6.8.8
========================================
(Omnia 6.8.8 / Workplace 6.8.6 / WCM 6.8.7 / MS 6.8.4)

- Fixed an issue with the enterprise glossary that would sometimes prevent details to show (#136729).
- Fixed an upgrade issue with texts on Action Buttons (#137434).
- Fixed sort order in the Advanced Search (#136405).
- Measure to better handling Throttling for Microsoft. (#137123).
- OnPrem: Fixed the profile picture ratio.


6.8.6
========================================
(Omnia 6.8.6 / Workplace 6.8.5 / WCM 6.8.6 / MS 6.8.3)

- Fixed an issue with token refresh for the new Teams Prescence feature.
- Click out on the mega menu now works as expected.
- Fixed the document management template creation feature from the document rollup (#124080, #128727).
- Process Management now follows the business profile settings (#137195).
- OnPrem: Sent for comments now shows the user correctly.


6.8.5
========================================
(Omnia 6.8.5 / Workplace 6.8.4 / WCM 6.8.5 / MS 6.8.2)

- Fixed a filtering issue on the page rollup (#136700).
- Better handling when rejecting an Event Management invite from Outlook.
- OnPrem: Waiting for approval dialog now works correctly. 
- OnPrem: Fixed targeting by language. 


6.8.3
========================================
(Omnia 6.8.3 / Workplace 6.8.3 / WCM 6.8.3 / MS 6.8.1)

- Fixed an issue that prevented forms result to be exported to Excel (#136397).
- Fixed an issue with counting Event attendees (#136458).
- Stability improvements to the Azure AD Sync (#136568).

6.8.2
========================================
(Omnia 6.8.2 / Workplace 6.8.1 / WCM 6.8.2 / MS 6.8.1)

- Corrected subscribe label on an enterprise glossary term.
- Updates to the default content community template.
- Fixed a rendering glitch in the Process Rollup
- Fixes to Community Rollup scroll paging.


6.8.0
========================================
(Omnia 6.8.1 / Workplace 6.8.1 / WCM 6.8.1 / MS 6.8.1)

Features
**************************
- Quick setup wizard is now available when creating new tenants.
- Each page collection can now configure default values for its page types (#113403).
- Its now possible to configure "Current Node" as the start node in page roll up navigation path query.

Improvements
**************************
- Omnia App Permissions has been lowered.
- Multiline text properties are now supported on Process properties. (#134554).
- Performance improvements client side due to lazy loading of the RTF Editor. 
- The strengthen profile button is now configurable to show or hide on the User Profile Card. 
- Reworked settings UI for custom email providers.
- When machine translating on a block, any language can now be selected.
- Better support for retention policies on publishing apps. Removing pages should now work with retention in folders turned on.
- The media picker now has a more suitable design for transparent images (#135188).
- Several enhancements to accessibility (WCAG)
 - Improved Opacity in the breadcrumb.
 - Better aria labels and keyboard navigation for the mobile menu.
 - Better aria labels and keyboard navigation for the current navigation.
 - Better aria labels and keyboard navigation for the mega menu.
 - Logo text is now used as tooltip and alt text for the logo image.
 - Added tooltips to the notification panel icons (#124162).
 - Its now possible to specify "Main Heading" in a page layout.
 - Most action bar actions can now specify a role attribute.
 - Closing behavior of the mega menu has been corrected.
 
 


Fixes
**************************
- Corrected the rendering of multi day events in calendar rollup. (#134811, #129576)
- Refiners are now reset correctly when query text is changed (#125278).
- Improved rendering of long names in the advanced search (#133468).
- Stability improvements to the Search settings. 
- Display as text on the people rollup now works correctly (#135167).
- Backspace no longer closes the FAQ block title (#135039).
- Fixes to the click-out logic. 
- Search now displays correct message when no search has been made (#113490).
- People and date can now be shown individually of each other on the card view (#133331).
- Fixed an issue with default values for Yes/No fields (#135454).
- When searching for specific metadata in the document picker, the title will stay searchable (#133520).
- Stability improvements to the yammer integration.
- Stability improvements to the anchor feature. 
- Fixed an issue with creating new documents when having many document templates in the system (#135764).
- Fixed an issue with searching a paging in the Teamwork rollup (#136024).
- Better support in scenarios when more than 14 different languages are used for content. 
- Fixed an issue with deleting app instance Queryable properties.
- Double quotes now works as expected when searching. 
- Fixed a context issue when setting up teamwork templates in Omnia Admin. 
- Fixed an issue with image scaling in the newsletter (#135437).
- Item limit now works as intended for the MS Teams Channel block (#134990).
- Better handling for approving processes without a comment (#131023).
- Corrected an issue with birthday rendering in the people card (#135606).
- Color settings for icons in the new mega menu now works correctly (#136006).
- Bulk update can now correctly filter on people properties in all scenarios.




Also resolves (#115655, #117305, #114222, #124003, #120422)

6.7.17
========================================
(Omnia 6.7.14 / Workplace 6.7.17 / WCM 6.7.9 / MS 6.7.7)

- Fixed an issue where templates based on another controlled document would not work correctly in some tenants.
- Controlled documents can now be created from an empty template.
- Increased performance for editing the people rollup.
- Stacked processes now works as expected (#136302).
- Increased page size for the image picker, solves problem when many folders are present on the root level (#136358).
- Excel export for forms now works as expected in all scenarios (#136397).



6.7.16
========================================
(Omnia 6.7.13 / Workplace 6.7.16 / WCM 6.7.8 / MS 6.7.5)

- Fixed an issue with editing links (#136303).
- Updated validation logic for Urls in the Action button, it's now possible to create javascript: constructs again.
- Fixed an issue where pages could not be approved in some scenarios (#134934).
- The termpicker now exapnds correctly when only one root node is present (#136050, #136058).
- Corrected the email flow for variation authors. 
- Old images (pre 6.0) Now render the correct icons to convert for svg images.


6.7.12
========================================
(Omnia 6.7.11 / Workplace 6.7.12 / WCM 6.7.5 / MS 6.7.3)

- Fixed an issue where section headers would not correctly update on navigation.
- Mentions in comments now works as expected. (#135776).
- Fixed an issue with symbols in documents when converting to pdf (#135884).
- My subscriptions in User Menu now correctly shows for all users.
- Custom shapes in OPM now retain their size when copied (#135509).
- Updated page rendering to better handle invalid data.
- Performance updates to the Azure AD sync.


6.7.9
========================================
(Omnia 6.7.7 / Workplace 6.7.9 / WCM 6.7.3 / MS 6.7.1)

- Fixed an issue with property templating for layouts. 
- The announcement block now works on the workspace startpage. 
- Ensured stability in the page rollup navigation view when used in the mega menu.
- Fixed a page rollup rendering issue that would sometimes occur in the notification panel (#135008).
- Fixed an issue that the tutorial tab would not load in some scenarios.
- Added a new feature to ensure Teamwork enterprise properties (#135180).
- Fixed an issue with MS Teams presence if it had never been used. 
- Ensured design of the MS Teams presence in the people rollup.
- Updated the way to fetch the preview image from SharePoint image libraries (#132127).
- Improved error handling when loading the profile card (#135494, #135607).
- Added configuration settings for max width and max heigh for the search block in dropdown mode (#135413).
- Added missing localization.
- Corrected an issue that would close the Announcement comments tab unexpectedly. 
- It's now possible to schedule variations together with the default page (#134920).
- Fixed an issue with spacing being incorrectly added to RTF (#135714, #135402).

6.7.3
========================================
(Omnia 6.7.0 / Workplace 6.7.3 / WCM 6.7.1 / MS 6.7.0)

New Major Features
**************************

- Copy blocks and sections across pages (#129970).
- Favicon is now configurable per business profile (#126515).
- Calculated Date Properties (#123172, #114551)
- Automatic Archive (#128186, #128942)
- Sign off requests
- Block for displaying PowerApps
- Search Feedback and promoted search results.
- Modals and panels will now close on click out. (Does not apply when accessibility is on) (#123157, #122336, #125956).
- Yammer for likes and comments
- Anchor links, to enable this, ensure to add the action to the RTF editor in Omnia Admin.
- Teams Presence 
- More actions for the people rollup (#127035, #122406, #126851).
- Full Text Search Solution (#132701, #124961, #128796, #129938, #129938).
- Channels
- Conditional Consent

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
- Communities: When following a community, you will also subscribe to it.
- Info screen now supports custom colors for important announcements. 
- Grouping for action buttons.
- Azure AD Sync now supports the Delta API. This means greatly improved sync performance for large customers.
- Its now possible to add the same page collection several times in one page rollup.
- Strengthen profile has a new and improved horizontal design.
- Configurability for the search block has been improved.
- The new mobile navigation now includes siblings and parents.
- Term properties now expand by default if there is only one parent term selected (#127849).
- The WCM archive now allows for any editor to restore their own archived pages.
- It's now possible to include User Properties as filters for metrics. 
- The RTF editor can now be configured to suggest terms when writing.


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
- Updated execution logic for the script block, it’s now possible to create redirect script blocks again (#134001, #134333, #134692).
- Corrected a page rollup rendering glitch in mobile (#134007).
- Teamwork rollup now correctly shows all templates when filtering for "Only current business profile" (#134033).
- .ico files are now supported in the Media picker. 
- Fixed an issue that caused videos to not be configurable in info screen. 
- Corrected a data load dependency between Omnia Admin and blocks for links. 
- Corrected an issue with the search query strings. 
- Terms in the notification panel now keep their colors even when the item is highlighted (#135024).
- Ensured the notification panel will load the configured icon and not the default one. (#134349).
- Date format is now configurable for the people rollup. 
- Corrected an issue occurring when editing comments (#132670).
- The Create Document Wizard can now create documents in libraries with more than 5000 documents. (#132539).
- Updates to the new indicator logic for notification panel items.
- Improvements to the RTF editor (#132945, #133104).
- Fixed some invalid config for the default page layouts (#133031).
- Design correction for new items in the page rollup Roller view (#134766).
- Several events in the Activity view have been fixed. 
- Improved the way records declaration for ODM published documents are applied (#133646).
- Fixed an issue with deleting selected languages on Tenant level (#113528).
- Removed an invalid option from the Controlled Documents view.
- It’s no longer possible to select "Current User" in info screen. (#129720).
- Fixed an issue in the search for published documents in the Controlled documents Authoring site. (#129615).
- Followed sites provider for the teamwork rollup now correctly also filters based on configuration (#130011).
- Fixed an issue where Separator Color and Border Radius could not be saved in layout settings (#129423).
- Fixed an issue in process management where non clickable shapes would render as clickable.
- Events created via the copy feature can now be opened directly (#127051).
- Fixed a design issue on the people rollup (#133847). 
- The central image locations now pages content correctly (#131219, #131639, #134287).
- Stability improvements to the Action Button (#133878).
- When using MS Search as a search provider, correct icons are now shown.
- Rich Text properties can now be used as description for Event Management (#134827).
- Corrected padding on the top menu (#132901).
- Corrected an issue with data migration to new Workspace (#134592).
- The default SharePoint Context Url now validates correctly.
- Improved how content is automatically saved in Process Management (#130412).
- And many more small design and theme fixes.

- Also above also fixes tickets (#127462, #134925, #134754, #133706) 

For developers
****************************
- Several aggressive CSS selectors have been made less specific, allowing them to be overridden by custom stylesheets.
