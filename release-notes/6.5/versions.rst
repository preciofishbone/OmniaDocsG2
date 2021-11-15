6.6.0
========================================
(Omnia 6.6.0 / Workplace 6.6.0 / WCM 6.6.0 / MS 6.6.0)

New Features 
**************************

- A reworked mega menu block, now with flexible querying and styling.
- New structure of settings in Workplace menus. 
- Default document properties are now applied when uploading and moving documents into ODM (#129968).
- Better error handling in ODM when a user has been deleted.
- Added settings for permissions to Publishing App Templates. (#133244).
- Its now possible to target variations to any language (regardless of the display languages).
- The ODM Review Reminder email now contains a link to the review task (#120327, #128346, #131886).
- Statistics is now shown for Workspace home.
- Default permissions can now be specified in the Publishing and Community App templates.
- Document rollup now works with files that contain the hash (#) character.
- The document rollup now supports new tokens, CurrentUser.Id as well as CurrentUser.Email (#132651, #131931).
- Improved performance in the page picker when having many pages (#132910).
- There is now an explicit color setting for not viewed items in the notification panel. 


Fixes
**************************

- Style updates for the Publishing- and Community rollup.
- Fixed an issue that prevented documents to be added to OPM processes on small screens.
- The Accessibility Theme is now correctly enabled when the user enables it. (#132931, #132894)
- Fixed an issue with the icon color in the new mega menu (#133266).
- Corrected the RTF theme on the new FAQ block.
- Corrected an issue in the settings form of the Activity Feed.
- Default Site Properties in Document Management can now be used on a publishing app.
- Improved error handling when draft exists (#132047, #132019, #131942).
- The Community default content feature can now be activated multiple times without additional artifacts being created.
- Fixed an issue with the background color of the tab control.
- The mobile navigation menu icon will now follow the icon color (#133309).
- Team news rollup now follows the Theme correctly.
- Corrected the padding of the tenant logo (#132901).
- General corrections for theming in the new mega menu (#132554).
- The editor for the Navigation Bar now follows the Editor theme.
- When link to delve is turned off, it’s no longer possible to open delve by right clicking the link and open in new tab.
- Fixed an issue that caused driveItem not to render from MS Search.
- Fixed a design glitch in the Publishing and Community rollup.
- Corrected icon color for tabbed sections (#132553).
- Stability fixes to the Teamwork provisioning flow.
- Fixed an issue with the Event Management participant list.
- Several Mobile design fixes.
- Fixed an issue that caused the Excel file for reports to not generate correctly (#131376, #132975, #133433).
- The page rollup now renders better in a very narrow column (#132738).
- ODM now supports files with a # character in the filename.
- Fixed an issue that caused the node order of the mega menu to be incorrect (#132214, #133119).
- Fixed an issue that caused limited read access to be lost on publish in ODM. (#132415).
- Community activities now show correctly (#133558).
- Fixed an issue that would prevent a user from searching on the same term twice in a row.
- Azure AD mappings are now shown instantly in the list without reloading the page (#133046).
- Publishing apps with status "Completed with warning" are now mappable in Event Management settings.
- Fixed an issue with displaying images in OPM. (#126985).
- Stability fixes to the Process Management publishing flow.
- Stability fixes to the page rollup.
- The icon position 'top' on a tab now works as expected (#132761).
- Fixed an issue that would cause page content to not sync correctly to SharePoint when an inline image was used.
- Follow actions are now longer shown when using incompatible providers (#129083).
- Corrected an issue with SharePoint sync related to inline images (#133456).
- When sharing a document to an external user in a document library, the user is not logged in to Omnia anymore. (#129997).
- The document picker has been updated to use the default document query (#133483).


6.5.8
========================================
(Omnia 6.5.5 / Workplace 6.5.6 / WCM 6.5.6 / MS 6.5.6)

- Fixed an issue that caused likes and comments to show an incorrect count on the dialog view in page rollup (#133275).
- Fixed an issue that caused the RTF editor to behave incorrectly in Firefox (#133202).
- Corrected email notification logic for translation authors (#132830).

6.5.6
========================================
(Omnia 6.5.5 / Workplace 6.5.6 / WCM 6.5.6 / MS 6.5.6)

- Fixed an issue that caused time to be wrong when events were put for approval.
- Fixed an issue in event management that would sometimes prevent outlook events from being created correctly.
- Fixed an issue that would cause the new navigation bar editor to hang (#132703, #132779, #133082)
- Default document types now work correctly in the create document wizard (#133016, #133019).
- Fixed an issue that would sometimes prevent relating documents (#132116).
- Fixed an issue that would cause the User Profile Completion dialog to show up when it should not.
- Corrected an issue with targeting of navigation nodes in SPFx.
- Corrected an issue that would sometimes cause permissions not to be saved correctly on Shared Links and Important Announcements. (#133469)
- Updated the logic on how links are provisioned for the default content app links. (#133165)


6.5.5
========================================
(Omnia 6.5.4 / Workplace 6.5.4 / WCM 6.5.5 / MS 6.5.5)


- Fixed an issue that caused the wrong node to be selected in the new megamenu (#132987,#132730).
- Fixed an upgrade issue related to the footer (#133034).
- Fixed an issue related to route change when switching variations (#128842, #132943).
- Several stability improvements to Event Management (#133010).
- Fixed an issue that caused the User Profile Wizard to not open automatically when configured to do so (#132751).
- Updated language logic for Document Management Authoring Sites (#132626).


6.5.0
========================================
(Omnia 6.5.0 / Workplace 6.5.0 / WCM 6.5.0 / MS 6.5.0)


Major New Features 
**************************

(:doc:`More Details </release-notes/6.5/index>`)

- Workplace apps 
 - Dynamic Mega Menu (#115472, #125718, #114686).
 - Query by navigation path in page rollup.
 - Display logo for extra small screens (#126714).

- Enterprise glossary and the Taxonomy Navigation.
- New Provisioning Templates.
- Communities 2.0.
 - Its now possible to subscribe to Taxonomies.
 - Auto subscribe to newly created page. (#127971).
 - Permissions can now be setup so a page can only be edited by the Author.
 - New Comments and Activity Feed UI. (#115431, #120984)
 - Community Rollup.

- Section stepper.
- Governance dashboard including new metrics. 
- Graph client in Script/HTML.
- Search
 - Microsoft Search is now available as a search provider.
 - My Links can now be configured as a search category source (#130359).
 - The advanced search block can now be configured to use any search categories.
- Omnia Forms.
- Teams Channel block.
- People Card (Replaces opening and iframe to delve) (#125406, #126500, #129389)
- Yammer feed block.
- Teams Share Action on the Action button.
- Yammer Share Action on the Action button.
- Like Action for the Action button. (#)
- Automatic page translation, pages can now automatically create all variations without any editor intervention (#114074)
- Iframe block.
- Pages can now have documents stored as a property. 
- Its now possible to change the url of publishing apps after thier creation. 


Minor New Features
**************************
- Calendar rollup can now query data in a configurable timespan (#115468, #117523, #125845, #127240).
- Event management can now create event which includes a MS Teams meeting. A link to the meeting can be shown on the event.
- The filter state of a page rollup can now be stored as a query string.
- You can now show taxonomy properties on the page rollup card view.
- Show child nodes on cards in card view.
- New Scheduling workflow. A schedule rule can now be tied to any date enterprise property. (#116302).
- By using the new community’s layout feature, communities can now be provisioned in any language (#127432).
- The see more link of search can now be configured to show after each category (#121840).
- The profile image edit link for User Profile Completeness is now configurable. 
- The Action button now supports most of the actions in Omnia.
- Current publishing app is now a Query Scope on the Page Rollup.
- Sections now support many new modes. 
- Property replacement tokens are now available to create complex publishing app templates.
- Image sizes in the search results can move be set to a fixed size (#121952).
- Updated UX for the multilingual text input control.
- The scheduling flow has been updated to use a enterprise property instead of unique business rules.
- When archiving a page, you can now get a new draft from the old, published page.
- Newlines are now possible on shapes in OPM. (#120216, #120197)
- Description can now be shown in all rollups of App Instances.
- Updated UX for the people picker, the picker is always closed upon picking a value.
- 

Fixes
**************************
- Fixed an issue with clearing search refiner in Advanced search (#131147).
- Fixed an issue with the active tab color in OPM (#130939).
- Document picker sources now work as expected weather or not a document library has been configured on the publishing app (#119811).
- Animated GIFs can now be uploaded correctly (As long as they are not cropped or scaled) (#130619).
- Fixed an issue with the mail icon in the people rollup, it now works correctly in mobile (#130616).
- Several Document Management stability fixes and a move back to using CSOM APIs.
- Several Page Variation stability fixes.
- Updates to a theme mapping is now directly applied.
- Rendering terms in page properties now always renders new properties on a new row. (#129761).
- When sorting by likes, the most recent will show in top if several articles have the same number of likes (#121978).
- Fixed an issue with the Teamwork rollup that could occur when adding a new enterprise property (#130831).
- Several issue with saving images has been fixed (#126594).
- The add link action for the action button now correctly handles query strings (#128671)
- Fixes to preview issues (#132822, #132752, #131891, #132553, #131845, #132261, #131901, #128525)


For developers
************************
- All Vue chart types have been added.
