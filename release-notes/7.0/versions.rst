7.1.0 - Draft
========================================
(Omnia 7.1.0 / Workplace 7.1.0 / WCM 7.1.0 / MS 7.1.0) 

- Added additional default fields to the setup feature "Enterprise properties - Documents".
- Refiner collapse setting now works as expeted for date refiners (#147647).
- Document Management and Process Management now have different comments for "Change comment" and "Message to approver".
- Fixed an issue with available seats in Event Management (#148057).
- It is now possible to force a page to have a Publishing Channel when it gets created. 
- It is now possible to attach a publishing app to an existing communication site.
- Custom 404/401 pages can now be designed in Omnia Admin.
- Broken links statistics are now available in the metrics block. 
- The page rollup list view can now should people with only name or only user image.
- Limit read access are now persistent between versions in Process Management (#122305)
- Sort by using the column header now uses the correct configured managed property (#133600).
- Mediaflow is now available as a possible media picker, NOTE: License with mediaflow is required to use this feature.
- App instance connected sites URLs can now be edited in Omnia Admin.
- Suggested templates in the new document wizard now show correct when switching between normal and controlled document (#140277).

- Also fixes preview bugs (#149420, #148905, ). 

7.0.16
========================================
(Omnia 7.0.16 / Workplace 7.0.12 / WCM 7.0.13 / MS 7.0.11)

- Fixes to new filter migration (#148620).


7.0.15
========================================
(Omnia 7.0.15 / Workplace 7.0.12 / WCM 7.0.12 / MS 7.0.10)

- Fixed issue in people rollup relating to Yes/No fields in the new filters.
- Archived pages now show as expected.
- Fixed an intermitted issue where granted permissions would not take effect.
- 6.13 -> 7.0 Data migration fixes.


7.0.12
========================================
(Omnia 7.0.12 / Workplace 7.0.9 / WCM 7.0.10 / MS 7.0.9) 

- Fixed an issue that would cause documents to fail in the controlled documents publish flow (#149283).
- Fixed an issue related to date formatting in event management (#149203).
- The new profile card should now work as expected for newly created Azure Ad users (#149111). 


7.0.5
========================================
(Omnia 7.0.5 / Workplace 7.0.4 / WCM 7.0.4 / MS 7.0.4) 

System wide
******
- New Filter UX and settings for all rollups. Resolves (#146912, #136058, #138038, #144147, #142858, #144762, #143976).
- The date picker now shows in the correct language.
- Terms picked now searched the full content of the term (#137357).
- All filters can be configured to have a fixed position.
- In a term set filter, it’s now possible to select if deprecated terms should be displayed or not (#115011).
- Long term names can now be viewed via tool tip, including the path to the term (#143157, #143460).
- Omnia users are now available and Kaizala logins are now no longer supported (#123798).
- Fixes to theming issues in Omnia Admin (#144292)
- Azure AD Group targeting is now case insensitive (#145285).
- Anchors to tabs can now both scroll the page and select the correct tab/accordion (#140710, #141196, #137953).
- New feature system, Omnia App permission is now handled on a per feature basis.
- All features’ names and descriptions have been updated.
- All features now have a permission description if they require Azure AD app permissions.
- Several new Omnia Features have been introduced to be able to limit the permissions of the Omnia Azure AD app.
- Only valid app instance features can now be selected on an app instance template (#117577, #120285).
- The org chart block now respects the msExchHideFromAddressLists property (#133417, #136830, #147094).
- For all rollups, partial word search is now always turned on. The setting has been removed.
- When using the image picker, correct message is now shown while searching.
- Several label updates and corrections.
- The filter state of all rollups can now be stored to the URL.
- Tenant and Business Profile titles are now multi-lingual.


Workplace
*****
- Sign-off Request rollup now shows the correct requests in regard to admin and normal users (#146317). 
- User profile completion feedback emails now work for users with different email and login name (#140368).
- A value can now be written to the user profile from an action button. This can be used in LMS.
- Sign-off request export now includes the time of sign off in the excel report. 
- Multiple status filters can now be used in the sign-off request rollup.
- Click out now works as expected for the User Profile completeness form.
- The old profile card can be activated using a tenant feature.


Communities
*****

- Auto translated pages no longer creates empty rows in the Activity feed (#137822).
- Fixed an issue that would create non clickable notifications on comment (#147554, #136648).  

Web Content Management
******

- Resource readers are no longer synced to a SharePoint permission (#141928).
- The create page action button now works as expected when placed on a Workspace page (#141516, #142027).
- Links created in the RTF content no longer contains and extra blank space (#129934, #143227, #143642, #130377, #147698).
- People rollup card view alignments have been corrected (#137509).
- Corrected quick poll submit button spacing (#145113).
- Page properties block text colour now works as expected (#142137, #140879).
- Fixed an intermittent issue with page type default values (#142421).
- Page Type names are now multilingual (#127732).
- Adding a link to RTF now supports links other than https links (#128013).
- Link to delve is no longer exposed in emails from the system (#144270).
- Distribution groups are now hidden from the identity picker where you can set permissions (#133992).
- Custom link nodes in the navigation structure are now multi-lingual (#132960).
- Thumbnails from a new stream video now have the correct ratio (#133809).
- The mega menu loading has been stabilized (#147842).
- Pages that are both under approval and scheduling now works as expected (#147464, #140255).
- Stability fixes to automatic page creation using auto publish (#147616). 
- Fixed an issue that prevented some users from seeing total page likes (#146569).
- Page Types can now be soft-deleted in the UI.
- Connected tenants can now be setup, to allow automatic page creation between tenants.
- Page rollup list view can now be configured with a fixed position.
- In the case of trying to create a duplicated URL to a page, better feedback is now provided, and the result is prettier. 
- Comments and likes can now be shared between variations of a page. (#142216).
- It is now possible to stop using variations if it was turned on by mistake.
- Publishing app settings have a new UI with only one save button.
- Page collections can now be moved across business profiles. 
- Page rollup filters will only show tenant page types and current publishing app page types.

Teamwork
****

- New Admin UI for teamwork (#142065, #148411).
- Several changes have been made to the handling of permissions in omnia, solves several sync to SharePoint issues (#141378, #144775, #125161). 
- Security trimming is now available for teamwork rollup (#128494, #138068).
- Better handling and user information when deleting a teamwork template (#142404).
- A site template can now define default values for different properties (#107193, #117587).
- Visibility of properties can now be configured. Properties can be shown in new and edit form respectively (#123637). 
- When deleting a teamwork, the list now updates immediately (#142098).
- "Open in client app" in the controlled documents library will now work for PDF documents (the document is opened in MS Teams) (#142086).
- Teamwork synchronization now uses the new Sites selected model. To manually sync last activity has been removed.
- Only supported languages can now be selected for a teamwork template.
- Communication site templates have moved and can now be found under publishing.
- When switching teamwork template, only valid choices are now shown. 



Process Management
*****

- Several improvements to the drawing capabilities of the editor (#122306).
- Edit button of shapes is now placed above the shape instead of on the shape (#120201).
- Possibly to edit z-index. Send to back, send backward, send to front, send forward (#128355, #122279).
- Shapes can now be moved using the keyboard (#120199, #129303).
- Multiple shapes can now be moved at once (#118677, #129301).
- A copied shape now retains its orientation (#135509).
- Rotating shapes will snap to a rotation grid if shift is pressed.
- Shape width and height can now be set using exact pixel sizes if desired (#120228). 
- Default canvas size can now be set for a process (#129245).
- Its now possible to link to a draft process (#123246).
- Better handling when a process authoring site is deleted (#141038).
- Multiple document rollups can now be added to a process, resolving the need for categorizing documents (#124937).
- Image cropping is now available for Background images and shapes (#127246, #128403).
- When using Process templates, search results will now render according to the template (#144094).
- The process rollup can now sort on process title (#135580).
- The browser back button now works as expecting when navigating away from a process (#136680, #136838, #125505).
- Fixed an issue where media-based shapes would not show up automatically (#140047).
- Individual process steps can now be found using search (#143938).
- Empty process drawings (using only a background image) can now be rendered (#132564).
- Fixed an issue that caused drawing background image to not update correctly (#133588).
- The process rollup is now supported in SPFx.
- Process approval tasks titles now have the correct translation (#128402).
- Archived processes can now be restored.
- The process picker will now show processes without searching.

Document Management
*****

- Click out now works as expected for document properties dialog (#138950).
- Recipient is now required in the send for comments form (#144813).
- Reviewers are now required in the send for review form.
- Compatible video files will now open in the browser (#146362).
- Bulk update now gives consistent results for users with different email and login name (#144982).
- Document types can now be configured to be compliant with Microsoft AIP. This by disabling features that replace properties and put the document into review mode.
- More tokens are now available to be used in the Document Management related emails. These include all enterprise properties and change comment.
- Document history now contains Published by (#138412).
- Bulk update can now search for user properties where the user has been deleted (#138222).
- Draft documents can now be restored from the SharePoint recycle bin (#136051).
- Document management file history now shows correct file names.
- Descriptions of the Document Type are now shown in the create document wizard (#136056).

Notes for developers
*****

- Omnia now uses Vue 2.7.
- Backend is upgraded to .NET Core 7.

Also solves preview issues: (#148163, #148232, #148911)
