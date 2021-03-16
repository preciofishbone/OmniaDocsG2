5.0.0
========================================

General
***********************

- Added "normal" Spanish (Espanol) as a selectable language. 
- Better handling when saving a list of permissions with some invalid selections (#117350).
- Icon set "Fabric" has been renamed to "Microsoft" for easier understanding (#114041).
- Correct issues with showing profile images in some components (#116587).
- Fixed an issue that would cause instability when switching between categories (#Missing).
- The "my computer" image provider can now be turned off using a feature (#118011).
- When an external user signs on for the first time, the welcome message no longer shows an error (#118695).
- Updated labels and wordings in many places of the application (#116801, #120576, #121034, #121734, #119773, #120373, #120979).
- Saving permissions now works even if one of the users/groups fails (usually due to the user being deleted) (#120781).
- Translated terms now work as expected (#121005).
- Improved performance and stability of Omnia in SPFx (#117481, #119580, #120670, #121712, #122258).
- Added danish localization for social dates (#120083).
- Corrected display of profile images (#121415).
- Better handling of deprecated terms (#121942).
- Icons with multiple shades have been removed from pickers in this release since they are not compatible (#121479).
- Term pickers now correctly handle multilingual terms (#121730, #121005).


Web Content Management
***********************

- New Page Lifecycle #link (#114801, #120924, #115549)
 - The "Advanced" page creation mode no longer exists (#117182, #113821). 
 - Pages can now be hidden without being removed (#117556).
 - Better handling of removing and restoring variation pages (#113818. #114725).
 - Corrected time zone sync into SharePoint (#114888, #115750).
- :doc:`New SharePoint File structure </release-notes/5/index>` 

- Reworked rich text editor #link.
 - Tables can now be created and designed directly in the RTF editor. (#115412, #114745)
 - Floating toolbar; The most common settings of the RTF editor are now available as a floating toolbar close to the cursor. This greatly improves the experience when working with long texts. (#114338, #115244, #115410, #116524, #117673, #118324)
 - Improved link handling; Links can now be added to existing text, existing links can now be edited when selected.
 - Update media; Media (Images and video) can now be edited in the RTF content. (#113395, #120160, #114249, #116633).
 - Paste without formatting; The RTF editor can now clean formatting when pasting content. (#114917, #114058, #119990).
 - Styling of bullet lists (#115411, #117579, #118512).
 - Multiple line breaks now render correctly (#119841).
 - Styles can now be globally defined to be used for all text fields in Omnia. This allows the administrator to create headings directly in omnia without need for any custom development. (#114817, #115918, #116976, #116503).
 - Stream movies now correctly render inside text content (#114742).
 - Width and text flow can now be explicitly set for images in the text (#117540, #112789, #114339).
 - Summary is now available as a predefined element (#113982).
 - Blockquote now has correct styling (#114751, #114918).
 - Improved link handling (#120401).
 - Corrected several issues where the editor styling would differ from display mode (#113594)
 - Also fixes (#118096, #118536, #116523, #117674, #117680, #120177, #120284, #115453, #115539, #114904, #117171, #121025).
- :doc:`Governance block </release-notes/5/index>` 

- Version history UI updated when there are many versions (#121377).
- Redirect links now work for users who have not yet logged in.
- Export to excel of the usage report now work better with more than 5000 pages (#120247).
- Fixed an issue with resolving the "Everyone except external users" group in some tenants when creating new publishing apps (#121380).
- Corrected a link formatting issue in notification emails from new comments (#121438).
- When adding a new block, the cursor is now automatically focused on the search box for the blocks (#116574).
- Updates to the link picker to select "Automatic" as the default link selection (#117244).
- Move block action now has a new icon (#115387).
- Its now possible to reorder the exiting content in the accordion (#116623).
- Corrected the date formatting in the schedule page dialog (#116811).
- Fixed an issue causing the RSS notification count to not show until selected (#114774).
- Empty banners no longer takes any space (#114714, #115854, #118350).
- Corrected thumbnail in page rollup for videos (#117123).
- The page rollup now supports multilingual for the no result message (#117168).
- The button "Go to news center" now supports multilingual (#118829).
 
- :doc:`Page Styling options </release-notes/5/index>` 
 - Prevented default colors to put white text on white backgrounds (#116995).

- Corrected an issue that would prevent the user from deleting a page when previewing it (#116506).
- Default values for page properties now work correctly together with the "years" setting (#115547, #120579)
- Default values for date properties now works as expected when editing (#117587).
- Its now possible to have default values for Yes/No properties on the page type (#114622).
- Fullscreen is now correctly supported for media in the media block (#115341).
- Display breakpoints are now applicable to all screen sizes (#116360, #117061).
- Added correct default left padding for the breadcrumb (#117062).
- Corrected an issue that would cause the wrong translation to appear on the navigation nodes (#120240).
- Updated UX feedback for page properties validation (#113533).
- Corrected a design flaw in the likes and commented columns of the page rollup (#116939).
- Corrected an issue that would prevent correct export of the Usage report (#116169).
- :doc:`Notification panel overhaul </release-notes/5/index>` (#120834, #120150).
- Corrected an issue that would sometimes prevent navigation to a page from the page rollup (#120420).
- Its now possible to have scheduling and approval on the same page (#120769).
- Corrected an issue that would prevent the create news button to not show up (#121678).
- Page types can now be deleted if not used (#114141, #121724, #121873).
- Action Button triggered dialog can now properly be closed (#115248, #115156).
- Video in the media block can now be edited (#116080).
- The notification count badge text and background color can now be explicitly set (#114605, #117706, #118278).
- Editing a URL to a node now behaves correctly (#114961).
- Corrected an issue where reused content would not show as reused (#121614).
- The indicator that a navigation node has children now shows correctly (#120305, #122251).
- Action button text is now correctly centered (#122128).
- Current navigation now renders indicators that have children correctly (#120305, #122251).
-



Document Management
***********************

- Fixed an issue where the "Create draft" and "Unpublish" buttons would not show up in the document rollup (#118540).
- Corrected the date format in the publish dialog (#1150589).
- Corrected an issue that would not render titles correctly when grouping by site (#117532).
- Fixed the positioning of the create button in the create document wizard (#115681).
- Time has been removed from the Date Time stamp in the Document management emails (#117442, #117574, #119927).
- Fixed an issue preventing the document history from being shown (#122171). 
- Improved stability of the publish flow (#120526, #121733).
- Removing a document type no longer cause issues to related documents (#122177).

Tenant Administration
***********************
- :doc:`Customer contact information </release-notes/5/index>` 

Team Collaboration
***********************
- Can now use template icon in listings instead of letter avatar.
- Site owners can now correctly edit site metadata (#122285).

Workplace
***********************

- :doc:`MS Teams Integration </release-notes/5/index>` 
- New Query strings for showing/hiding the Tenant and Business Profile header. (#119541)
- The Document rollup can now display Email icons (#116055, #117596).
- The People rollup have been reworked, with new design options and features (#120973, #114014, #114403, #121172, #116920, #120521).
- The document rollup can now display Email icons (#116055, #117596).
- The announcement comments feed now take all available screen space (#117248).
- Corrected an issue where the header toolbar would show the wrong icons (#117530).
- Corrected the style of the User Profile Completion Wizard in SPFx (#114438).
- Ensured the image ratio of the tutorial (#118601).
- The quick links block can now filter on links without any category (#116693).
- My tasks block now has a setting to open in a new tab (#114632, #116711).
- Search categories now have support for multilingual texts (#118271).
- Default property "Preferred Name" has been renamed "Display Name" (#114696).
- The Site properties dialog now renders correctly with many properties (#118585).
- My links block now has a "Show less" button (#117214).
- Corrected an issue that would make the important announcement get the wrong color (#114881).
- Search in my links now works as expected when filtering (#114496, #117273, #117648).
- Default O365 launcher link items have been updated and renamed where applicable (#117810, #117139).
- Fixed an issue that would prevent App Instance requests to be rejected if the template had been removed (#120901).
- Fixed an issue in the My Site header component that prevented settings from being saved (#120818).
- Corrected an issue where the people rollup would not render correctly when using SharePoint group query option together with being used in SPFx (#120283).
- Collaboration templates now sort alphabetically (#117977).
- Search now handles query rules properly, this solves issues with mismatch between standard SP search and search in Omnia (#114847, #121794).
- Drop-down search now correctly closes when navigating to a result (#121937).
- Profile Completeness now has a correctly implemented block title and new design options (#114212).
- SharePoint alias validation now correctly prevents the user from progressing in the site provisioning (#114641).
- Strengthen Profile block has a new design (#122074). 
- Corrected and issue that would prevent the MS Teams Icon to show correctly (#121446).
- Azure AD sync now correctly syncs Cloud only extension properties (#122229).
- Its now possible to configure if wildcard search will be used or not for search-based components (#114451).

Communities
***********************

- The "My Subscriptions" button now have links to the individual pages the user subscribes to (#121151).

Process Management
***********************
- Processes can now be shown in a TeamSite.


Also fixes preview issues (#121345, #122132, #122150, #122209, #122073, #121995, #121892, #121931, #121944, #121760, #122242, #121995)


5.0.3
========================================
- Corrected load of certain taxonomy properties in ODM (#123244).
- Full sync stability updates (#122371).


5.1.0
========================================

Fixes
****************************************
- UI for saving external contacts have been improved (#122295).
- The error log of the SharePoint Full sync can now be viewed in the UI.
- Logic on following sites have been improved. A followed site in omnia always follows the site in SharePoint. A site followed in SharePoint will automatically become followed in omnia (with some delay) (#123336).
- It is now possible to force letter avatars in the Team news rollup.
- Its now possible to turn off all system emails which is useful when running migrations (#122027, #122010)
- Name change of sites is now synced between Omnia and all connected resources (SPO, MS Teams, Outlook).
- Omnia welcome screen as been disabled, leading to quicker page loads.
- Structure for omnia pages have been changed.
- Several issues have been fixed there Omnia would affect look and feel of standard SPO components.
- An Issue where a search category title would sometimes render as "undefined" in omnia admin has been fixed.
- The Page rollup view "Card view" has gotten several updates for an improved experience in both mobile and desktop (#122104). 
- Term picker UI and UX improved for small spaces (#122221).
- Several UI issues have been fixed in the Document rollup display breakpoints settings UI.
- Default value on datetime properties, now correctly selects the time. 
- People rollup width settings have been adjusted. 
- Labels for "Enable partial search" have been consolidated.
- Quick links can now be correctly opened on IOS. 
- Language picker now shows correct available languages in all scenarios in Process Management and Document Management.
- Personal sites are now correctly excluded from the Teamwork rollup when a custom SharePoint Domain is used (#123163).
- The UX feedback when approving a Teamwork has been improved.
- Site properties can now only be edited by the Owner. Not members. 
- Improved the stability of the Process Management edit UI (#122252).
- Fixed an error when client validation would prevent sending a controlled document for comments.
- Fixed an error where Boolean default values would not work correctly in the Teamwork rollup filters.
- Corrected the padding of the Teamwork search when there is no result (#121893).
- Fixed text alignment in the RTF editor when combining tables with different text alignments.
- The process datatype now works correctly as a filter for all rollups where it is available.
- Fixed an issue where teamwork rollup filters would sometimes not work for term properties (#123350).
- Fixed an issue where newlines would be inserted in the wrong place in the RTF editor when bullet lists were used (#123315).
- Yes/No filters now work correctly in People Rollup.
- Filters can now be correctly placed to the right or left of the content in people rollup.
- The site logo is now correctly displayed when grouping by site in the Team news rollup.
- My subscription block now correctly refreshes without a page reload.
- Its now possible to list all teamwork cross business profiles.
- Min width for block has been adjusted (#123093).
- Block titles can now be displayed in the notification panel (#123430, #123438).
- Added support for ms-excel and ms-word links in RTF.
- Improved capabilities in searching for phone numbers (#121624).

5.1.5
========================================
- Enterprise keywords now correctly support multiple choice.
- Corrected style of the Teamwork rollup when used in SPFx. (#123469)
- Taxonomy refiners in the document rollup now correctly shows translated terms.
- Links in RTF now support ms-excel correctly (#123508).
- Corrected translation labels in document management (#122405).
- Corrected language fallback to use Business profile language if preferred language is null.
- Read access is now correctly granted to variations of a Page Collection root page. 
- Performance improvement when loading a page to set up as a reusable page.
- OPM emails now show the correct approver in its content (#123615).
- Variations URL-segments are now correctly validated to be lower case.  
- Corrected an issue that would sometimes prevent finding a published process (#123516).
- Corrected settings migration for the page rollup and document rollup (#123638).

5.1.14
==========================================
- It is now possible to have a customizable "Fallback" page, in case omnia is down. Contact your Omnia consultant to get it set up.
- Action button is now available for the notification panel (#122037).
- Corrected an issue where filter settings would be incorrectly set when upgrading from 4.1 (#123638)
- Correct an issue where certain metadata fields would create duplicate inserts in an ODM document (#121793)
- Increased stability of the Azure AD sync. (#123393, #121707)
- Fixed an issue where some navigation nodes could not be moved (#123775).
- Fixed an issue when newly created Business Profiles would get the wrong context (#123997).
- Several improvements to the "Full sync to SharePoint" feature (#123770, #123622).
- Fixed an issue where Info Screen would disable the Business Profile footer.
- Fixed an issue that prevented the action button from correctly linking to an internal omnia page (#123894, #123868)
- Fixed an issue where the browser back button would sometimes not work (#123824).

5.1.16
==========================================
- Strengthen profile can now display taxonomy properties if the user’s language is not available in the term store (#123571).
- Tags can now be used to setup related pages.
- .xls files now correctly open in webapp or desktop app depending on the settings on the Document Rollup (#124047).
- Performance of fetching followed sites has been improved. 
- Documents larger than 4 Mb can now be saved to OneDrive from the create document wizard. (#123907).
- Top contributors in people rollup now render correctly even when their contributions are older (#123853).
- Creating a page from an action button now render the correct form in the case you have never accessed the editor.
- Current navigation arrows now render correctly depending on if the node has children or not. (#120305, #122251).
- Fixes to the archive functionality that could affect older tenants. (#124214, #123931, #123922, #124206).
- Updated Danish labels.
- The People rollup dialog view no longer triggers a re-render of the content when opened (#121944).


5.1.20
==========================================
- The notification panel now closes on navigate on mobile devices (#123301).
- Ensured Document Management file size upload limit (#119483).
- The default page collection setting now pre-populates correctly in the settings form (#124191,#124247)
- Open in client app on related links now behaves as expected for all supported file types (#124220).
- Updated translations for Event Management in Danish and Swedish.
- A section in accordion mode can now be edited even when empty (#124285).
- Corrected an issue that prevented the controlled document feature to be activated on some sites (#124331).
- Improved stability in the controlled documents publish flow (#124145).
- The RTF feature "Keep text only" has been improved. It is also now always included by default
- Improved the search as you type experience for filters in rollups.
- Corrected an issue where Editors would not get enough permissions via AD-groups (#124279).


5.1.22
==========================================
- (Preview) It's now possible for a user to set their system language to be used in Omnia. This will take priority over any language set in O365. 
- It's now possible to enable a login flow that will allow Safari devices with ITP turned on correctly authenticate against Omnia Attached sites.
- Corrected an issue where default visitors would not always be correctly applied to new sites. 
- Corrected an issue that made term driven approval does not work properly for Controlled Documents (#124076).
- Corrected a migration issue that would occur when one authoring site had more than 5000 documents(#124333, #124334, #124090).
- Fixed an issue where new processes would not show up in the process rollup (#124329).

5.1.23
==========================================
- Advanced search refiner can now use Tax Id mapped properties like the document rollup (#124283)
- Fixed an issue that would prevent variation pages from being created (#124517).
- Stability improvements to page publish flow (#124569, #124292, #124487, #124700, ).
- Fixed an issue in related links that would cause 2 tabs to be opened in Edge and Chrome (#124649, #124259, #124587, #124708)
- Corrected an issue that would cause filters with spaces in them to not work correctly in people rollup (#122028).
- New teams are now correctly provisioned as private if set to provision as such.
- Corrected an issue that would sometimes show a term outside of its parent in the term picker (#1245880).
- Fixed an issue related to having a controlled document as a template for controlled documents (#124334).
- Corrected an issue with date only fields related to Daylight savings (#124531).
- An App Instance Admin can now change template (And business profile) of its site.


5.1.27
==========================================
- An infrastructure change that prevented new App Instances from being created has been resolved.
- An issue where Mobile first users would not get access has been resolved (#125242).
- The SPFx package downloaded from Omnia Admin now has the correct filename.
- Page types now correctly updates in the left navigation when the name is changed (#125096).
- Performance of navigation via quick links has been improved.
- The display name of external users will now be available to developers (#124922).
- People rollup can now correctly use people in a SharePoint group as a data source.
- Old settings on the Action button would now be correctly understood by the new component (#124554).

5.1.30
============================================
(Omnia 5.1.21 / WCM 5.1.30)

- Fixed an issue that caused sorting on most liked and most commented would not work correctly. 
- Enabled extended support for configurations with IE11 and Windows 7.
- Fixed a language targeting issue related to login names in uppercase. 
- Fixed an issue that would assign read access in SharePoint incorrectly, leading to incomplete search results for some users. (#125118, #125449, #125632, #125712, #125767).
- Updated the link picker to correctly handle edits of the “Open in new tab” setting (#125087).
- Improved error handling when Emails cannot be sent on Teamwork creation. (#123155).
- Fixed an issue where text pasted from notepad did not include newlines. 
- Fixed a translation issue in the Event Management default properties (#125713).
- Updated Danish translations across the solution.  
- Fixed an issue with reports when using multiple variations of a page collection root page (#125454).
- Corrected an issue where site titles would not get their data in all different localizations of SharePoint (#125009).
- Improved stability of the PDF conversion feature (#124331).
- Improved stability in controlled document creation especially when using multiple languages (#125287, #125482, #125540).
- Better compatibility for the Azure AD sync connection.
- Fixed a routing issue in OPM that would sometimes show the wrong version in preview (#124155, #124453).
- When not select to “Allow to bypass approval for Revisions” the user can now correctly see the approval option (#125473).
- Fixed an issue that prevented the global image back to load if illegal characters where used in the filename. (#125447, #125643).

5.1.33
============================================
(Omnia 5.1.24 / WCM 5.1.33 / Workplace 5.1.12)

- Event management does not longer send unnecessary messages about edited events (#126042).
- Everyone except external users again works correctly for ODM authoring sites.
- Fixed an error causing OPM images not to be updated correctly (#126422).

5.1.33b
=============================================
(Omnia 5.1.26 / Workplace 5.1.12 / WCM 5.1.33 / DM 5.1.17)

- Moving ODM documents now works as expected (#125839).
- Social dates are now translated into additional languages (Latvian, Estonian and Lithuanian) (#126318).
- Fixed an error that caused the entered password of Azure AD sync to be incorrect.

5.1.33c
============================================
(Omnia 5.1.26 / Workplace 5.1.13 / WCM 5.1.33 / DM 5.1.19 )

- Fixed an issue where notifications where not correctly updated (#126404).
- Fixed an issue in the Create Document Wizard where all sites would not be searchable (#126154).

