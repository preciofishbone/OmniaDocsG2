6.3.19
=========================================
(Omnia 6.3.11 / Workplace 6.3.10 / WCM 6.3.19 / MS 6.3.17)

- Terms now render correctly when a custom sort order has been used in the term store.
- Fixed an issue that would prevent the page dialog to open when the roller view template was used (#132416).
- The 5000 items warning in ODM has been moved to the settings dialog.
- Fixed a page cache issue (#132422, #130577).

6.3.18
=========================================
(Omnia 6.3.10 / Workplace 6.3.9 / WCM 6.3.18 / MS 6.3.16)

.. note:: Reconsent needed. To fix a provisioning error, a reconsent is needed. Permission TeamMember.ReadWrite.All has been added to the omnia app.

- SSL certificates are updated to a stronger standard. (Making IE11 fully incompatible).
- Updated error messages for the Full Sync to SharePoint (#132127).
- Fixed an intermittent issue with teamwork creation (#131403).
- Fixed a number of issues due to undocumented changes mad by Microsoft to SharePoint search in some tenants (#131142, #132045, #132101, #131931).
- Fixed an issue that would prevent related documents in ODM to show up correctly (#131532).
- Fixed an issue with Teamwork creating and the adding of default members, reconsent needed, see above. (#131661)
- Stability improvments to the ODM publishing flow (#132267).
- The document rollup now correctly opens document in a new tab from inside of MSTeams. (#131651, #131979, #129747, #132147)



6.3.16
=========================================
(Omnia 6.3.8 / Workplace 6.3.7 / WCM 6.3.16 / MS 6.3.13)

- Fixed an issue with the full sync to SharePoint that would occur in Page Collections with more than 5000 items (#131419).
- Fixed an issue with the Action button text (From 6.3.13) (#131737, #131770, #131780, #131782, #131910)
- Document management can now support more than 2000 items in one authoring site. It’s not recommended to exceed the limit of 2000 documents in one site since some functionality will be unavailable (#131562).
- Teamwork created from omnia now always shows in the listing, even when the confirmation email could not be sent (#131742).
- Fixed an issue that would sometimes prevent the Controlled Document Library feature from activating (#131025, #131308, #131403).



6.3.13
========================================
(Omnia 6.3.7 / Workplace 6.3.6 / WCM 6.3.13 / MS 6.3.8) 

- "Limit edit permission" on a page property, now correctly hides the property in the create new page form.
- Fixed an issue with the Dynamic Roller view that would cause pages to open when using the arrow buttons to browse. 
- Corrected a cache issue that would cause the variation selector to show the wrong variation in edit mode.
- Fixed an issue with Quick links targeting where there would sometimes be too many links shown.
- Corrected how the MS Teams Icon is fetched to fix an unannounced API Change from Microsoft.
- Fixed an issue that would sometimes prevent the page rollup show in dialog to open correctly.
- The page rollup now supports 200 pages without paging.
- Stability fixes for ODM (#131097, #130007, #131089)
- Major Performance improvements to scenarios when we have many navigation nodes in the mega menu. (#130741, #130007, #131089).
- Corrected an issue that would prevent the Controlled Document Feature to activate for some users (#131025, #131308, #131403).
- Added paging to the Azure AD Sync, it’s now possible to see more than 10 entries to sync.
- Corrected an issue in ODM when loading templates in a multilingual scenario. (#131267).
- Fixed an issue that would sometimes prevent the notification panel to load correctly (#131268).
- Corrected a sign-up issue for event management (#131262).


6.3.9
========================================
(Omnia 6.3.6 / Workplace 6.3.4 / WCM 6.3.9 / MS 6.3.5)

- Fixed a caching issue that would sometimes lead the scheduling not being editable (#130473).
- OPM Task assignment emails now have the full intended content (#129229).
- Fixed an issue that prevented ODM approval emails to be sent in some cases (#130953).

6.3.8
========================================
(Omnia 6.3.5 / Workplace 6.3.3 / WCM 6.3.8 / MS 6.3.4)

- Fixed an issue in our auth service together with file downloads causing reports to not be downloadable (#130848, #130878).
- Fixed a permission related issue in ODM (#129497).

6.3.6
========================================
(Omnia 6.3.4 / Workplace 6.3.3 / WCM 6.3.6 / MS 6.3.4)

- Fixed a graphical glitch in the dialog for My Teamwork (#129686, #129028).
- Fixed an issue related to outlook integration in Event Management (#130596).
- Fixed an issue related to multiple variations in combination with automatic page creation (#130692).
- Fixed a cache issue that would cause old versions of a page to be shown to some users (#130653, #130562, #130680).
- Fixed an issue on the process rollup. Searched process now open the correct page. (#130181).
- Ensured stability of the variation picker block (#130496).


6.3.4
========================================
(Omnia 6.3.3 / Workplace 6.3.2 / WCM 6.3.4 / MS 6.3.3)

- Several improvements to the Create Document Wizard.
- Fixed a migration issue for 5.1 -> 6.x upgrades (#130566).
- Fixed an issue that would cause the wrong variation to be displayed (#130240).
- Fixed a navigation issue with the Dynamic Roller (#130306).

6.3.3
========================================
(Omnia 6.3.3 / Workplace 6.3.2 / WCM 6.3.3 / MS 6.3.1)

New Features
**************************

- When moving a Controlled Document, it is now possible to replace any users that doesn't exist anymore. (#129277).

Fixes
**************************

- The accordion now uses the Rich Text editor instead of the Limited Rich Text Editor (#130488).
- The process rollup now correctly shows the process publish date (#130398)

6.3.2
========================================
(Omnia 6.3.2 / Workplace 6.3.2 / WCM 6.3.2 / MS 6.3.1)

- Stability fixes in Controlled Documents for migrated sites (#129852).
- Fixed a layout issue in the Document Rollup (#130290).
- Fixed an issue with date filtering on Events (#130153).
- Fixed an issue with enabling and disabling mentions in comments. 
- Corrected an issue with opening Omnia links in a new window from OPM (#130019).
- Fixed an issue with info screen that would cause images to not render correctly (#129854, #130522).

6.3.0
========================================
(Omnia 6.3.0 / Workplace 6.3.1 / WCM 6.3.1 / MS 6.3.1)

New Features
**************************

- Search image/icon display sizes are now configurable. Allowing for same size images in all scenarios. (#114546).
- The RSS Feed will now clearly specify that it only supports RSS 2.0, Atom 1.0 or newer. 
- The new Media Picker now supports .svg files as an image source (#123514).
- A Search box for all enterprise properties is now available. 
- The page rollup can now apply client-side optimizations for much better perceived performance.
- Several performance improvements to page loading.
- The URLs to pages are now available in all excel exports of page reports.
- The Azure AD Sync feature is updated to use a SharePoint Addin App identity instead of a user account, this will allow the tenant to turn of legacy sign in and still use the Azure AD Sync. 
- Office 365 groups can now be used for permissions in WCM (#128519).
- Automatic page creation now works without using reusable content and can work together with quick publish (#128047). 
- Automatic page creation can now create pages as drafts and has better support in a multi variation scenario.
- Localization has been added to the date refiner control. (#122160).
- Improvements to the "Keep Text Only" feature. It now removes external style tags (#128638, #128344, #128832).
- Create new document wizard has gotten several UX improvements.  (#128162).


Fixes
***************************

- The document picker on a publishing app can now be used without a document library being configured on the publishing app (#128044).
- Fixed an issue that made certain Bing images fail.
- Document rollup partial word search now works as expected when using Full Text search option on filters.
- Fixed an issue with picking page collections in the notification panel (#125877).
- Made it easier to add content to an accordion block.
- Exif orientation metadata are now stripped from images when using scaling in Omnia. This will prevent upside down images.
- Take Control now works as expected for pages that have never been published. 
- Fixed an issue that prevented confirmation emails to be sent out when approving a site (#128549).
- Updated compatibility with certain RSS Feeds.
- Copy event now includes Created By (#126505).
- Fixed an issue where removed features would still be in provisioning templates (#129117, #129705, #129697).
- Height of the Taxonomy and Enterprise property picker has been increased (#129264).
- Different Info Screen configurations now correctly get different URLs (#128803).
- Fixed a rendering issue with the tab control (#129209, #129674, #126082, #127587).
- Updated localizations. (#117437, #113842, )
- Flag Icons no longer have rounded corners in the icon picker. 
- Fixed an issue for creating repeated events in Event Management. 
- Corrected several theme bugs including but not limited to the app icons view for shared links, the scheduling dialog, and the likes details dialog. (#128222).
- Fixed an issue preventing the saving of new text styles (#129333).
- Its now possible to add background images to processes when using OPM from inside MS Teams (#129307)
- Fixed an issue where more settings in the OPM authoring site would open a new tab (#128195).
- Space is no longer unintentionally added when using the HTML mode in the RTF editor. (#124930).
- The Document History placeholder in ODM now supports translations (#125776).
- Fixed an issue preventing the App Icons view from removing shared links. (#128739).
- Corrected an issue with the User Language replacement in the Document and People Rollups. (#128175).
- Improved validation feedback for page properties (#128686).
- Fixed an issue with the accordion block header style. (#128317).
- Fixed a caching issue that would happen when navigating between OPM authoring sites (#126427).  
- Page history now shows the correct time format (#128800, #125616).
- Improvements to the page rollup settings UI.
- Fixed an issue that would sometimes not create a review reminder email on a document type. 
- Review reminder emails no longer contain broken links to the process.
- Fixed a caching problem in the WCM editor that would give the impression you were on the wrong page.
- Search no longer closes after opening a result in a new tab (#129124).
- Events in event management without a reserve list now act like they do not have a reserve list (#127000).
- Fixed an issue where you could not activate OPM Authoring on a site with illegal characters in the site title (#128504, #128056).
- Fixed an issue with central image locations, all images are now shown (#128810).
- Fixed an issue with variations where their navigation node would not update correctly without reloading the page (#128842).
- UI fixes for IOS.
- Fixed an issue with "Open in client app" in ODM (#128392).
- External links now open correctly in a new tab when set to do so.
- Script/HTML now works as intended inside of a tab section. (#128248).
- SVG images can now be dragged into the media picker (#118432).
- Design updates to the select template UI of teamwork creation. 
- Team news rollup icon and title now align correctly in SPFx.
- Permissions no longer conflict when using ODM on the Publishing app backing communication site (#127795).
- Design fixes to the Manage Link dialog (#129800).
- Queries based on page properties now work well when the property is not set (#129029, #129016).
- Data properties are now possible to set as SharePoint searchable. (#125055).
- Design updates to the ODM Read Receipt (#129305).
- Document rollup refiner width now works as expected (#129459).
- Fixed a caching issue for the page content(#129746).
- Corrected an issue that would push the wrong page title into browser history, giving the impression the back button led to the wrong page (#128302).
- Reverted permission changes done in 6.x back to 5.1 logic. O365 groups can now be used for permissions in most places.
- Setting the order of RTF actions in Omnia admin is now much more stable.
- Corrected an issue with caching page data (#130086).
- ODM Stability improvments (#129852).

For developers
***************************
- Getting visited pages are now part of OmniaFX.


6.2.8
========================================
(Omnia 6.2.4 / Workplace 6.2.4 / WCM 6.2.9 / MS 6.2.8)

- Performance improvements for the page rollup.
- Stability improvements to the ODM publish and unpublish flows (#128841, #129280, #129862, #129861, #129777).
- Fixed a styling issue for banners.


6.2.7
========================================
(Omnia 6.2.4 / Workplace 6.2.4 / WCM 6.2.7 / MS 6.2.7)

- Improved rendering performance for large structures.
- Links in RTF now works as expected when not having the color picker as an action in the RTF editor (#129495).
- Fixed an issue with duplicated rendering in the ODM authoring sites when using the move feature (#129678, #129330, #129678).
- Fixed an upgrade issue for banners and accordion that would occur when content has been added to a component owned by the page type (#129597, #129552).


6.2.5
========================================
(Omnia 6.2.3 / Workplace 6.2.4 / WCM 6.2.4 / MS 6.2.5)

- Performance updates for the Page Rollup.
- Send for comments in ODM will now work even if email send outs fail (#128539).
- Delete and Unpublish now works correctly for ODM sites where an On-Hold policy has been applied.
- Fixed an issue with documents incorrectly displaying as published in the draft library (#129289, #129313).
- Fixed an issue with moving documents (#125839, #129256).

6.2.3
========================================
(Omnia 6.2.1 / Workplace 6.2.3 / WCM 6.2.2 / MS 6.2.4)

- Fixed an issue causing deleted draft documents incorrectly showing up. (#128575).
- Fixed an issue where the draft library would not show up correctly (#129003).
- The content header now loads correctly on the first page load (#129004, #129014, #128991, #128525, #129072, #128635).
- Fixed an issue where OPM processes would fail saving its data to SharePoint. (#129189, #128390)
- Several stability fixes to the page rollup when invalid config is used. The rollups will now load anyway. (#129119, #129160, #129177, #129232, #129250, #129259).
- Fixed an issue with ODM that would occur due to a language mismatch between Omnia and the Term store.

6.2.2
========================================
(Omnia 6.2.0 / Workplace 6.2.2 / WCM 6.2.2 / MS 6.2.1 )

- Additional performance improvements for the page rollup.
- Page now reloads correctly when switching language in the omnia user menu.

6.2
========================================
(Omnia 6.2.0 / Workplace 6.2.1 / WCM 6.2.1 / MS 6.2.1 )

- Improved performance in loading of static resources.
- Table styles in OPM now works as expected (#126863).
- Current page is now supported when making queries in the People Rollup. (#114971).
- Corrected an issue with reordering related links (#128578).
- Search as you type experience is improved (#123522).
- It is now possible to define link styles for RTF, allowing you to configure them to be underlined by default (#125728).
- Corrected theme for the "show more" dialog for likes(#128262).
- Fixed an issue preventing information text to be removed in the new media picker(#128008).
- Event management enterprise properties have been converted into system properties.
- Community tags now accept Swedish letters again (åäö) (#127968).
- Layout templates have gotten several tweaks.
- Corrected a setup issue in ODM, where incorrect Managed properties would cause creating drafts from published documents to not work correctly (#125287).
- Stability fixes to Tenant page types.
- Pasting images in RTF will not correctly upload the image using the Omnia image picker.
- Process Type metadata can now be correctly shown on the process rollup.
- Using the speed dial to enter design mode now correctly enters design mode and not edit mode.
- The people rollup feature "User fields on page" now works as expected.
- Using a custom navigation node title for a page now works as expected.
- ODM Tasks completion messages have been improved, it now correctly indicates if the task was completed or cancelled. (#115443).
- Fixed a migration issue causing action buttons added in 5.1 to sometimes not be editable in 6.x.
- Fixed an issue where moved controlled documents would display in both the source and target sites for a while.
- Feedback form for ODM has gotten a new design (#115119).
- Fixed an issue in event management preventing un-registration for copied events (#126503).
- Better UI feedback when publishing pages with missing mandatory metadata (#127265).
- Fixed error message in WCM editor that previously stated "this.editorstore..." it now displays the correct message.
- Terms now behave consistently in a multilingual setting when picking terms. (#127034).
- Fixed an issue in OPM setting focus to the wrong tab when adding shapes.
- Corrected an issue with 10px extra padding automatically being added to the Listing with image page rollup view.
- Updated several labels and spellings.
- RTF Heading dropdown now renders like the settings. 
- Added placeholder for all blocks. (The placeholder is used when the block has no data to show in edit mode).
- Shared links now correctly open on IOS. 
- If no image is mapped in the page rollup views, the placeholder image no longer shows.
- Svgs can no longer be uploaded as a template in ODM. 
- The media picker can now correctly bypass its functionality to support all file formats in its native format. 
- Document rollup grouped by site now uses the image proxy to get the SharePoint image. 
- Fixed an issue where header theming would get incorrect settings.
- Document type changes now correctly propagate to all ODM Authoring sites. (#128387).


6.1.15
========================================
(Omnia 6.1.10 / Workplace 6.1.3 / WCM 6.1.15 / MS 6.1.8 )

- Fixed an issue where Omnia Admin would not show enough options to Business Profile Admins (#128501).
- Corrected an upgrade issue that would sometimes occur for images in OPM. 
- Fixed an issue in the page rollup with the scroll paging.
- Corrected an issue with targeting when the user has no value in the targeting property. (#128677)-


6.1.13
========================================
(Omnia 6.1.9 / Workplace 6.1.2 / WCM 6.1.13 / MS 6.1.5 )

- Permissions for the AzureAD Sync features are now automatically ensured on upgrades. 
- Added Swedish translations to new labels related to Query Limit.
- When adding a queryable property, it will now correctly make existing content queryable without republish.
- Updated API to fetch MSTeams links, resolving issues displaying the MSTeams Icon in Teamwork rollup (#128558).

6.1.12
========================================
(Omnia 6.1.9 / Workplace 6.1.2 / WCM 6.1.12 / MS 6.1.5 )

- Big performance improvement for the Page Rollup in trim duplicate scenarios with many pages.
- Added new setting to page rollups, page query limit. Use this to optimize start page performance.
- Corrected translations for nl-be.
- Stability improvements for Controlled Documents. 
- Corrected an issue where the page rollup would not render correctly if it had an empty filter.
- Corrected an issue where taxonomy properties filtering would not work after an upgrade from 5.1 (#128637)
- Color theme is now correctly kept in the Accordion when updating from 5.1.
- Fixed an issue with terminating Enterprise properties. 
- Corrected an issue with activating ODM on migrated sites (#128385).


6.1.7
========================================
(Omnia 6.1.2 / Workplace 6.1.1 / WCM 6.1.7 / MS 6.1.3 )

- Big performance improvement for the Page Rollup.
- Its now easier to have text on multiple lines on OPM shapes (#125370).
- Taxonomy refiners based on term ids correctly resolve in quick search and advanced search.
- Corrected an issue that would occur in the upgrade from 5.1 for page types with background images.
- Implemented better handling of language fallback when en-us is not an available language. 
- Corrected an issue that would occur in the upgrade from 5.1 in the icons of a block header.

6.1.0
========================================
(Omnia 6.1.0 / Workplace 6.1.1 / WCM 6.1.1 / MS 6.1.1 )


- The sort by field in Search Category settings can now be cleared.
- Mandatory Boolean page properties are now handled correctly (#127641).
- Displaying notifications on updated pages now works as expected outside of communities (#127643).
- The search dropdown on a block now has the same width as the block.
- Info Screen has gotten several stability updates.
- Page Rollup has gotten several stability updates.
- Process Management has gotten several stability updates.
- The new Media picker has gotten several stability updates.
- Data migrations for the Notification panel have been improved.
- Several color theme related issues have been fixed.
- The page picker now correctly shows the value you search for.
- It is now possible to have a search box in the Document Picker.
- People rollup now correctly handle zone width.
- Default content community layout buttons can now be edited.
- Fixed an issue preventing display breakpoints from working in the page rollup.
- User profile completion now works as expected when a description is not filled in.
- Fixed an issue that caused rounded corners in the top navigation. (#127893).
- The document rollup now correctly restores settings of the search box when edited (#127131).
- The click guard now works correctly in design mode.
- Fixed an issue where the data of the document rollup would not render in edit mode.
- Corrected the ratio of the tutorial to be more like 5.1.
- Hidden pages now works correctly in the Dashboard block.
- Margins corrected in the action menu.
- The opacity effect has been removed from the page listing with image.
- Fixed a bug that caused redirect links not to work if not already logged in (#127592).
- Updated width settings of the document rollup for a better responsive behavior (#127685).
- Corrected the feedback block detail view, now has correct background color (#127621).
- Fixed a bug that caused a bullet point to be rendered next to summary elements (#127486, #127655).
- Fixed an issue with multiple notification panels on the same page (#127762).
- Corrected display of people properties in DM documents (#117207).


6.0.2
========================================


Notes
************************
- In this release, the Omnia extension structure has changed. This means you will only see 4-5 extensions installed by default.
- Previously hidden important announcements and read news might display again.
- CSS Isolation strategy has been updated, this should prevent any style leak between Omnia and SPFx.
- MS Teams is now a first-class target for omnia, with many style fixes and improvements as a result.

General
***********************
- Omnia Banners are no longer supported in SPFx.
- Ensured MS Teams to always open external links in a new tab.
- Better handling of enterprise properties, including categories and sort on header (#123320, #120366).
- When removing enterprise properties, they now end up in a recycle bin (#114120).
- Tenant and Business Profile logo is now saved as real image resources instead of base64.
- Current user language can now be set by the user; this is especially useful if the Windows AD property for language is not set.
- Theming is now generally available for all blocks and the editor.
- The login form for Kaizala users now supports correct keyboard controls.
- A new control for selecting enterprise properties has been introduced. It will be used through the entire system. 
- New structure and organization in Omnia Admin as well as in block settings.
- New option for properties “Queryable properties”. This pane replaces the old queryable checkbox on each property and allow for editing the queryable option.
- The default context URL can now point to a Modern site.
- RTF custom settings now correctly fallback to default settings if custom settings removed.
- Embedded images are now supported in comments. 
- Scaling and ratios are now configurable in Omnia Admin (#115473, #114224, #118327, #120242, #116642, #126567).
- Filtered images now result in server side stored edited images. Fixing issues in the rollups (#115388, #118815).
- An Omnia App Instance can now connect to a site without injecting any code, useful for connecting sites that have other custom code running via SPFx. The SPFx injection has been moved to an Omnia Feature.
- Rich text standard typography has been updated.
- The M365 App launcher has gotten style updates to match the changes of M365.
- Console log has been cleaned up.
- All labels for official Omnia languages have been updated in this release. (#123528, #125414, #116552, #113838, #126160, ).
- Better compression (Brotli) have been enabled for all resources resulting in better performance.
Workplace
**********************
- Info screen does not show session expired as often anymore (#122036).
- Sort order in the quick links block is no longer case sensitive (#125035).


Web Content Management
***********************
- Page types are now available on tenant level, see general release notes.
- Default content can now be specified, see general release notes. (#124775).
- Layout Templates are now available, this allows you to start a page type or root page collection from a predefined layout instead of empty.
- Edit mode on mobile has gotten several upgrades.
- The media picker has been improved, see general release notes (#114223, #114919, #126458).
- Open in dialog on People Rollup no longer affects the email link (#123092).
- People rollup now correctly displays people fields (#123705).
- Fixed an issue with deleting variations (#118456).
- The translation workflow has been improved (#123250).
- The new media picker now supports .svg files (#123514).
- Read news no longer depend on the device but is stored on your user profile instead.
- Status if an important announcement has been closed or not is now remembered across devices.
- Image ratios are now supported in newsletters.
- Several updates to the page picker.
- Stability improvements to the page sync. 
- Options for video embed has been expanded to correctly handle auto play and mute. Note: all options are not available in videos from MS Stream.
- The accordion block now has correct padding settings.
- Page properties can now be rendered in many new ways (See general release notes).
- Shape dividers are now available for the people rollup.
- People rollup now supports refiners based on term ids, useful in a multilingual environment with many translated terms.
-  Multi-value filters now have the correct AND/OR logic in people rollup.
- Section background images now work as expected (#124398).
- The reports now support much more data; the report is generated async and can later be downloaded. (#120247).
- Single people pickers now validate correctly on publish of a page (#125595).
- YouTube videos now show the correct preview in all rollups (#125258).
- Banners no longer have a faulty scrollbar (#124321, #124677).
- Improved compatibility of RSS feeds using enclosure tags (#121777, #123927).
- Tooltips now show correctly on Tab sections (#125115, #126105).
- Fixed an issue where the action buttons would not correctly render as multilingual (#125063).
- System properties (Non removable properties) can now be added to page types. 
- An action button can now be configured to add the current page to my personal links.
- Fixed an issue with the people rollup, it no longer causes incorrect results when clearing a refiner (#117366).
- People rollup now has an action for clearing a search (#119982).
- People rollup now has better handling of width (#124474).
- People rollup can now base its queries on current page metadata. 
- Fixed a navigation issue where settings would not reload correctly when navigating between business profiles without reloading the page (#126923).
- Fixed an issue with the URL segment storage in SharePoint (#124243).
- Corrected localization for dates in the Calendar Rollup and the Task Rollup. (#113575, #113582).
- Corrected an issue in the Notification panel settings that would occur when switching business profiles without reloading the page (#115247).
- Device breakpoints no longer show tabs with empty settings. The tabs are hidden instead. (#113972).
Reusable content
-------------------
- The flow for creating reusable content has been greatly improved, see general release notes (#122365, #124250, #126920, #128074).
- The page picker is now supported when selecting a page to reuse.
- Its now possible to reuse content between variations of a page. (#120352).

Page Rollup
-------------------

- Several performance improvements for all page queries (#123670)
- Its now possible to query a page rollup towards a specific variation, as well as the current page or the current user. The feature implementation has moved to the Query tab. (#124743).
- The dynamic roller view has gotten several stability updates and more consistent handling regarding number of slides (#124584).
- The page rollup feature "Exclude current page" now works correctly with variation pages (#121376, #121378).
- Opacity is now configurable for the Roller, Dynamic Roller and Card View. (#123681).
- Updates to the card view of the page rollup.
- The image ratio for page rollups is now configurable (#125021).
- DateTime and Integer fields will now correctly sort instead of sorting as strings.
- The loop setting, and number of items displayed for the Dynamic roller now works as expected. (#123925, #122082).
- Page Rollups now works correctly in SPFx (#125238).
- Open in dialogue no longer shows placeholder image (#115500).
- List view padding now works correctly when showing the no result message (#120774).
- Variations are now selected in the query section. It is now possible to select specific variations. (#114179).


RTF Updates
-------------------

- New design for the RTF quote style. 
- Text and image flow have received several fixes.
- Link color is now part of the settings (#124162, #124053, #123917).

Teamwork
***********************
- Fixed an issue causing default visitors not to applied to certain site types when provisioned.
- Properties for a teamwork template now uses property sets, allowing you to set dependent properties and ordering of properties (#123320).
- Document management and Process management MS Teams tabs can now be easily configured in the Template.
- Its now possible to add members and owners when creating a new teamwork.
- Confirmation emails are no longer sent when editing Teamwork.
- Validation when creating new Teamwork has been improved (#120614, #122066).
- Multiple App Administrators can now be assigned. If resource is an O365 group, the owners will be automatically synced. This will allow for the owner group to edit site properties (#124469).
- Fixed an issue that would sometimes cause the edit properties panel to not render correctly (#126141).


Document Management
***********************
- Features for retention and termination.
- Bulk update.
- Published ODM documents are now set as read only on a file level.
- Several changes to improve stability of the publish flow.
- Retention date can now be based on any enterprise property (#115742).
- Create new document action can now be added to any action button.
- Custom sort order for Terms now propagate correctly into the Document Management UI (#123926).
- Fixed an issue where sites would not be found when searching in the Create New Document Wizard (#126154)


Process Management
***********************
- Its now possible to publish processes with limited permissions.
- The process rollup now supports filters based on datetime.
- Archiving a process now works as expected (#124024).
- Fixed an issue with process navigation using the back button (#125663, #125264).
- Fixed an issue that impacted direct linking to processes (#126398).
- Process steps can now have pages as well as documents as related information.

Event Management
*****************
- Fixed an issue where having no participant limits would result in rendering Int.Max in the UI (#125038).
- Corrected an issue in the Admin UI where a table would have the wrong headings (#126597, #127623).


For Developers
***********************
- Omnia now uses the .NET Standard CSOM. 
- Several of the Omnia Core Extensions have been merged into one. 
- Better error handling when creating client context.
- When creating a SharePoint ClientContext, its now possible to use a username and password.

Preview
*************************
Also fixes preview issues (#126520, #126517, #126259)
