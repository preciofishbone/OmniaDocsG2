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
