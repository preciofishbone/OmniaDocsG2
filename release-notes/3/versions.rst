Release 3.4.1 
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