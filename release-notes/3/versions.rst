3.1
========================================

New features
----------------------------------------
- Omnia Feed is now supported in Omnia for Microsoft 365 Tenants.
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

3.1.4
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

3.1.5
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

3.4.1 
========================================

Enhancements
------------------------------------

Omnia
***********************
- Performance and stability improvements.
- Permission requirement on OneNote removed from the Omnia Azure AD app.
- Fixed a certificate issue that would lead to certificate errors in Firefox.
- Several updates to the Azure AD sync to be able to handle large amounts of users.

Web Content Management
***********************
- Fixed an issue with selecting documents in related links (#117454).
- Fixed an error with incorrect export of the usage reports (#116316).

Document Management
***********************
- Fixed placeholders in document for taxonomy values. (#117234).
- Fixed multi-value people properties, they now work as expected.
- Fixed an issue when creating a document with empty people properties.


Tenant Administration
***********************
- App instances list in Omnia admin now correctly handles very large amounts of data.

Workplace
***********************
- Fixed a problem that would sometimes cause business profile settings to be unexpectedly reset. (#115699)

3.4.4 
========================================

Fixes 
***********************
- Fixed an issue sometimes causing the calendar rollup to stop working.
- The App-Administrator field now correctly populates when using approval for Team Collaboration apps.
- Several capacity and stability fixes for Azure AD Sync.
- Several performance improvments.

3.4.6 
========================================

Fixes 
***********************
- Fixed a language issue sometimes causing users to get the wrong localization.
- Fixed ODM placeholders sometime not working in headers (#116273).
- Team Collaboration current user filter now works correctly (#114657).
- Fixed an issue preventing navigation between a page rollup in SPFx and Omnia publishing app. (#118103)

3.4.10 
========================================

Fixes 
***********************
- Reports are now correctly available to all users with read permissions (#118404).
- Several performance updates to the Azure AD sync feature.
- Banner in page types now works correctly when using very pre version 2.3 layouts.
- Fix for change to MSGraph api that caused folders to appear in controlled document libraries.(#118748, #118792)
- Performance improvements to page rendering.
- Performance improvements to the Azure AD sync feature.
- Stability improvements to document publishing flow (#118587,#118621).
- Page rollup now shows correct data on page 2 for people columns (#118591).
