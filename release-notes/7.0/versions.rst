7.1.9
========================================
(Omnia 7.1.9 / Workplace 7.1.3 / WCM 7.1.5 / MS 7.1.3)

- Fixed an issue that caused page rollup paging to not update images correctly (#151215).
- The M365 app launcher have an updated name to go to the M365 home (#151134).
- Fixed an issue that would prevent the configuration of styles in the RTF editor.
- Fixed an issue that prevented App Instances to be provisioned via an extension identity.
- Several stability improvements to the 6.13 to 7.1 upgrade.
- Improved stability of the multi step page approval flow.
- Corrected the breadcrumb navigation behaviour when viewing a process from the process rollup (#150794).
- Navigation between link nodes in the WCM editor now works as expected.


7.1.0
========================================
(Omnia 7.1.0 / Workplace 7.1.1 / WCM 7.1.0 / MS 7.1.0) 


Improvements
******
- Media flow is now available as a possible media picker, NOTE: License with Media flow is required to use this feature.
- The media block now supports multiple images.
- Added additional default properties to the setup feature "Enterprise properties - Documents".
- Added additional default properties to the setup feature "Enterprise properties - People".
- Document Management and Process Management now have different comments for "Change comment" and "Message to approver".
- It is now possible to force a page to have a Publishing Channel when it gets created. 
- It is now possible to attach a publishing app to an existing communication site.
- Custom 404/401 pages can now be designed in Omnia Admin (#119744, #133793).
- Broken links statistics are now available in the metrics block. 
- The page rollup list view can now show people with only name or only user image.
- Limit read access are now persistent between versions in Process Management (#122305)
- App instance connected sites URLs can now be edited in Omnia Admin.
- The page rollup calendar view now has an improved date range selector. 
- Only valid languages can now be selected for a Teamwork template (#145938).
- It is now possible to copy link to document from the document rollup information panel (#147490, #147010). 
- Identity picker can now differentiate between email enabled and Permission enabled groups.
- The process property type now supports multiple values.
- Additional data is now included in the Sign-off request export.
- It is now possible to exclude mandatory links from the quick links block.
- For controlled documents with no document type set, multiple documents can now be set at once (#143517).
- Lazy load can now be disabled for tabs, to allow for trim duplicates to work as expected (#147084).
- Added clearer error handling to the enterprise glossary to inform the user term store permissions are missing (#143078).
- Improved rendering of the recipient list of sign-off requests (#146972).
- Teamwork provisioning emails are no longer sent on edits of an app instance (#148412).
- Work email is now used to send emails in event management instead of login name, this to improve compatibility with external and omnia users (#141587).
- Send page as email now works from preview (#149812).
- SharePoint user profile sync property mappings are now case insensitive.
- The SharePoint user profile sync feature is now tied to a new feature that will provision correct AAD permissions (#149390).
- It is now possible to limit who can be set in a person property of controlled documents (#138296).
- Digital signage now support reusable Json mapping templates.
- If using Draftable, the show changes button is now configurable per document type.
- Selection list in rollups for business profile are now sorted alphabetically. 
- Additional reviewers can now be added to the send for comments flow in ODM.
- Multi level approval is now possible for pages. (See main release notes)
- Open AI Integrations (See main release notes).
- When saving filter state, if using classic paging, the page number is now remembered (#146197).
- Its now possible to write to your user profile using an action button, this can be used to track for example completed courses.
- All page rollups (except the calendar view) can now sort on Navigation.
- Security trimmed teamwork rollups (See main release notes).
- Media in pages now supports image caption.
- The process rollup now supports metadata queries based on currently rendered process.
- A process can now use properties of type media.
- It is now possible to configure the Omnia MS Teams app using a custom domain.
- Additional colour codes (Page Type and Page Workflow Status) are now possible for the page rollup calendar view.
- Document rollup copy link feature now uses a web link.
- A new add shapes UI with descriptions have been added to Process Management.
- Fixed label "All Languages" it no longer has an incorrect comma.
- It is now possible to move page collections across business profiles.
- Enhancements to the audit log.
- Review interval in ODM can now be configured to use either approval or publish date (#144801).


Fixes
******

- Sort by using the column header now uses the correct configured managed property (#133600).
- Fixed an issue with available seats in Event Management (#148057).
- Advanced search now handles dates in the same way as the document rollup (#148143).
- Refiner collapse setting now works as expected for date refiners (#147647).
- Suggested templates in the new document wizard now show correct when switching between normal and controlled document (#140277).
- WCAG: The left navigation now has the correct aria labels for use together with screen readers.
- WCAG: All views of the page rollup now use actual anchor elements, allowing for browser functions to work as expected (#142189).
- WCAG: Related processes now uses actual anchor elements, allowing for browser functions to work as expected (#146686).
- WCAG: Video description is now available to be set.
- WCAG: Correct aria labels set for input fields for Comments, My links search and app posts.
- WCAG: The document rollup now has correct tooltips if the value is cut (#140431).
- WCAG: Block headers now render correct non interactive HTML (#149303).
- WCAG: Search input field in the search block now has correct aria-label (#149303).
- WCAG: The calendar page rollup view now has interactive days and its date picker is now compliant (#149437).
- The org chart now displays all users if there are more than 100 on one level (#147538).
- Mailto links can now be added as a related link (#143722).
- Text styles now properly apply to bullet lists (#148259).
- Fixed a layout issue in the people rollup for small screens (#144373).
- AAD Permission read all applications as application permission removed.
- Stability improvements to tab navigations (#144707).
- Horizontal rendering for multiple people has been improved (#145312).
- Stability improvements to the setup wizard (#147091).
- Stream videos can now set Autoplay correctly (#148122).
- The WCM page archive now displays correct date format (#144979).
- Vertical text alignment of tabs updated (#143472).
- When combining scheduling and approval for pages, cancelling the approval now works as expected (#145639).
- Links in email now uses the custom email if available (#145697).
- The keep text button now shows when text are dragged into the RTF editor (#145351).
- Borders for banners now apply directly (#144626).
- Poll dialog is now hidden if no final text has been set (#145426).
- Fixed an issue that would prevent a form from opening when withing a stepper section (#44158).
- Improved active tab rendering for small screens (#146318).
- The dynamic roller page rollup view now allows for more text to be shown (#144992, #147721).
- Page rollup settings no longer try to adjust View and query settings dependent of each other (#136304, #145096).
- When pasting content into the RTF editor, the cursor is now placed correctly after the paste (#147276).
- The properties block can now be configured to have the correct date format settings (#149615).
- All blocks now hide correctly if they have no data to render (#145860).
- Fixed a rendering issue in Process Management (#149872).
- Fixed an issue with auto translation when using many images in the RTF content (#149437).
- Fixed an issue with the padding setting of the task rollup.
- A teamwork under approval can now have its fields edited as long as a naming policy based on users are not used (#147689, #146927).
- Manual translation tools now work as expected for drafts.
- OmniaVariationSegment is now updated as expected on resync to SharePoint.
- Updates to the SharePoint User Profile sync instructions. 
- Using the back button from advanced search now works as expected. 
- Digital signage preview URL now uses the custom domain if configured.
- Fixed an issue that would incorrectly hide blocks in edit mode when certain display breakpoints were set.
- Publishing app default settings now use the correct enterprise property picker.
- When trying to remove an enterprise property that is part of a property set, correct error feedback is now given.



- Also fixes preview bugs (#149420, #148905, #148253, #150468, #149862).

7.0.20
========================================
(Omnia 7.0.20 / Workplace 7.0.16 / WCM 7.0.20 / MS 7.0.16)

- Fixed an issue that prevented xslx files to be uploaded when documents are stored in Omnia (#150117).
- Fixed an issue that would sometimes cause the scroll arrows of OPM to not render correctly (#150075).
- The create page button now correctly opens edit mode (#150201).
- Fixed a targeting issue that would occur when a term set is deleted (#149570).
- Localization of social dates are now correct for Swedish locale.
- Fixed an issue with the page rollup calendar view when an event stretches over two months (#149970).
- Several migration improvements (#149933, #149826).
- Fixed an issue where pick pages would not work if the page rollup was added in the page type (#150142).
- Corrected an issue with mail enabled groups for odm notifications (#149316).
- Fixes to the page rollup padding settings (#149771).
- Stability updates to token replace for controlled documents (#142753).


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
