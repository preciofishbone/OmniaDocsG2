7.0
========================================
 (Omnia 7.0 / Workplace 7.0 / WCM 7.0 / MS 7.0)

System wide
******
- New Filter UX and settings for all rollups. Resolves (#146912, #136058, #138038, #144147, #142858, #144762).
- In a term set filter, it’s now possible to select if deprecated terms should be displayed or not (#115011).
- Long term names can now be viewed via tool tip, including the path to the term (#143157, #143460).
- Omnia users are now available and Kaizala logins are now no longer supported (#123798).
- Fixes to theming issues in Omnia Admin (#144292, )
- Azure AD Group targeting is now case insensitive (#145285).
- Anchors to tabs can now both scroll the page and select the correct tab/accordion (#140710, #141196, #137953).
- New feature system, Omnia App permission is now handled on a per feature basis.
- Only valid app instance features can now be selected on an app instance template (#117577, #120285).

Workplace
*****
- Sign-off Request rollup now shows the correct requests in regards to admin and normal users (#146317). 
- User profile completion feedback emails now work for users with different email and login name (#140368).
- 


Communities
*****

- Auto translated pages no longer creates empty rows in the Activity feed (#137822).
- 

Web Content Management
******

- Resource readers are no longer synced to a SharePoint permission (#141928).
- The create page action button now works as expected when placed on a Workspace page (#141516, #142027).
- Links created in the RTF content no longer contains and extra blank space (#129934, #143227, #143642, #130377, #147698).
- People rollup card view alignments have been corrected (#137509).
- Corrected quick poll submit button spacing (#145113).
- Page properties block text color now works as expected (#142137, #140879).
- Fixed an intermittent issue with page type default values (#142421).
- Page Type names are now multilingual (#127732).
- Adding a link to RTF now supports links other than https links (#128013).
- Link to delve is no longer exposed in emails from the system (#144270).
- Distribution groups are now hidden from the identity picker where you can set permissions (#133992).
- Custom link nodes in the navigation structcure are now multi-lingual (#132960).
- 
- 

Teamwork
****

- New Admin UI for teamwork (#142065).
- Several changes have been made to the handling of permissions in omnia, solves several sync to SharePoint issues (#141378, #144775, #125161). 
- Security trimming is now available for teamwork rollup (#128494, #138068).
- Better handling and user information when deleting a teamwork template (#142404).
- A site template can now define default values for different properties (#107193, #117587).
- Visibility of properties can now be configured. Properties can be shown in new and edit form respectively (#123637). 
- When deleting a teamwork, the list now updates immediately (#142098).
- "Open in client app" in the controlled documents library will now work for PDF documents (the document is opened in MS Teams) (#142086).
- 




Process Management
*****

- Several improvements to the drawing capabilities of the editor.
- Edit button of shapes is now placed above the shape instead of on the shape (#120201).
- Possibly to edit z-index. Send to back, send backward, send to front, send forward (#128355, #122279).
- Shapes can now be moved using the keyboard (#120199, #129303).
- Multiple shapes can now be moved at once (#118677).
- A copied shape now retains its orientation (#135509).
- Shape width and height can now be set using exact pixel sizes if desired (#120228). 
- Default canvas size can now be set for a process (#129245).
- Better handling when a process authoring site is deleted (#141038).
- Multiple document rollups can now be added to a process, resolving the need for categorizing documents (#124937).
- Image cropping is now available for Background images and shapes (#127246, #128403).
- When using Process templates, search results will now render according to the template (#144094).
- The process rollup can now sort on process title (#135580).
- The browser back button now works as expecting when navigating away from a process (#136680, #136838, #125505).



Document Management
*****

- Click out now works as expected for document properties dialog (#138950).
- 

Also solves preview issues: (#148163, #148232, )
