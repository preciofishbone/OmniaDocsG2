6.1.0 - Draft
========================================
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
- User profile competition now works as expected when a description is not filled in.



6.0.2
========================================

Permissions updates
************************


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
- The flow for creating reusable content has been greatly improved, see general release notes (#122365, #124250, #126920).
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
