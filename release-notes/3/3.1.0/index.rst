Release 3.1.5
========================================

Enhancements and Fixes
------------------------------------
- Fixed an issue where the tutorial would sometimes not open correctly.
- Fixed an issue related to creating a new page from the page colleciton header.
- Fixed an issue where the strengthen profile dialog would show on days it should be hidden.
- Corrected the height of the media block when in a narrow column.
- Fixed an issue where the people rollup width settings would not work correctly
- Related links now has the correct font size in all scenarios.
- Related links edit dialog now has correct input headers.
- Fixed an error sometimes preventing configuration of the create page button in the page rollup.
- Added better stability checks on site and teams provisioning.
- Improved contrast in on the new icon in the document rollup.
- Updated accordion so it now correctly works in page types.

Release Notes 3.1.4
========================================

New features
----------------------------------------
- Added display breakpoint for large screens. This makes it possible to easily hide blocks in desktop mode.


Enhancements and Fixes
------------------------------------
- Several stability updates to the site provisioning flow
- When creating a MS Teams team no extra workbook will be created anymore.
- The developer feature to import pagetype now works correctly.
- Corrected the read reciept link, it now points to the correct page
- Fixed a display issue in the top navigation in SPFx
- Related documents are now correctly opened in a new window if set to open in new window.
- Updated hte UX experience on the people picker.
- Corrected margins in the page rollup header when having the create button enabeled.


Release Notes 3.1.0
========================================

New features
----------------------------------------
- Omnia Feed is now supported in Omnia for Modern SharePoint Tenants.
- Added the possibility to make the User Profile Completeness dialog never show up automaticially.
- The Page rollup roller view will now correctly show one item. This enables implementers to use pages as banners.

Developer changes
---------------------------------------
In an effort to reduce the Omnia AzureADs app permissions impact, the feature activations and app instance provisioning will now by default run in the current user context, not the application context. 

To run in the app context this needs to be explicitly set when triggering the feature activation or app instance provisioning.

Enhancements and Fixes
------------------------------------

Omnia
***********************
- Ensured targeting cache for user profiles is never longer than 30 minutes.
- Fixed a problem that would invalidate all users security sesseion when read permissions change
- Fixed a problem that prevented the user from entering Omnia Admin on new tenants. 
- Corrected the display of English laguganges in tenant settings.
- Fixed an issue where the Omnia header would show above document previews in SPFx.

Web Content Management
***********************
- Fixed HTML-tables so edit mode matches read mode in all scenarios.
- Fixed a design issue in the notification panel on mobile.
- Fixed the alignment of the editor speed dial button.
- Fixed the text block custom RTF setting.
- Enterprise keywords can now be multivalue.
- Fixed a bug related to the rendering of page statistics.
- Default values now work correctly for person and date fields.
- Fixed a problem where page rollups would not render correctly in SPFx.
- Improved the performance of the Page Rollup roller view.
- Improved the performance of the Central Image Bank.
- Several alignment fixes to buttons and labels.
- Limited permissions on page properties now works as expected.

Workplace
***********************
- Fixed a color theme issue in the advanced search on mobile.
- Several fixes related to Team Collaboration provisioning.
- Fixed My Links to properly support http links.


Document Management
***********************
- ODM Preview now works as expected.
- Fixed a problem where the document info dialog would not render on the first click in the document rollup.
- Corrected a bug where emails would sometimes be sent with the wrong localization.
- Fixed a problem where the Ok button would not always show up on the read receipt page.


People and Networking
***********************
- Fixed a problem where the search box would not display in the people rollup.

