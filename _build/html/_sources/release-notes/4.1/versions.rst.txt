4.1.1
========================================

Fixes
****************************************
- Fixed any encoding issue in token replacements of ODM (#120627).
- Fixed an issue preventing a draft being created from a published controlled document. 
- Ensured the paging control of the Controlled Document library.
- ODM specific read rights now works as expected (#120435, #120659, #120471).

Enhancements
****************************************
- Its now possible to choose whether to enable query rules on search categories.
- The Process enterprise property type can now be used for filtering.

4.1.3
========================================

Fixes
****************************************
- Fixed an error that would cause a very deeply nested layout to not publish correctly (#120315).
- Ensured search properties of the teamwork navigation (#120418).
- Tabs now correctly hidden for users without permissions in the controlled document library (#120529).
- Fixed an issue that would cause the review task not to be created correctly in Controlled Documents (#120447).

Enhancements
****************************************
- Azure AD sync now correctly syncs birthday date to the SharePoint profile.

4.1.5
========================================

Fixes
****************************************
- It's now possible to upload larger files in the controlled documents library. (#114250, #119483, #117145).
- Fixed an issue that would sometimes show the wrong columns in the document rollup (#120458).
- Fixed on UI feedback issue on the controlled documents library (#120528).
- Fixed an issue with the bottom padding for the teamwork navigation in mobile mode.
- Stability improvements to site attachment (#120727).
- Fixed an issue that caused incorrect merging of document templates (#120907, #120291).
- Added missing translation in Swedish for terms "Like" and "Share" (#120792).
- Fixed rendering of empty banners. (#118832).
- Team news images now show correctly when not signed into SharePoint. 
- Fixed an issue with the hide comments and likes features (#120804, #120838).
- Renaming sites now works as expected. (#120060, #120439, #120954).
- Fixed an error with display breakpoints on the page rollup (#120608).
- Its now possible to use Tags as a filter for the page rollup.

4.1.6
========================================

Fixes
****************************************
- Fixed a validation issue with when entering a document library URL in publishing app settings (#120722).
- Stability improvements to the document publish flow (#120972).
- Fixed an issue that would prevent moving a controlled document between sites (#120522).
- Updated labels and translations (#120959, #120975).
- Performance improvements to page rollup.
- Fixed an issue affecting certain Process Management Authoring sites (#120817, #120756)
- Corrected an issue that caused OneDrive folder to show up in a file listing  due to an unannounced MS API change. (#120740).
- Sites renamed in the Teamwork approval flow now get the correct name (#120615)
- Fixed an issue that caused Document types not to sync correctly in some scenarios (#121009).

4.1.9
========================================

Fixes
****************************************
- Performance improvements related to diagnostics.
- Deprecated values in term sets now works as expected. 
- All Document Management emails are now correctly sent by the system instead of the user. (#120589)

4.1.13
========================================

Fixes
****************************************
- Corrected an issue preventing a document to be published with PDF conversion (#121625).
- Corrected a targeting issue that would occur when primary email and login name differ (#119416).
- Improved stability to controlled documents when changing Document Template (#114831, #117947).
- Corrected an issue preventing access to the settings in authoring sites (#121700, #121726).
- Ensured Document management and Process Management works well with recent Microsoft updates to Fluent UI.
- Fixed an issue where Process Types would not sync correctly to SPO (#121288).
- Stability improvements to the document move function when moving documents with appendices. 
