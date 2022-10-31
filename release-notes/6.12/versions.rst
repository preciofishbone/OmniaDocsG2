6.12.0
========================================
(Omnia 6.12.0 / Workplace 6.12.0 / WCM 6.12.0 / MS 6.12.0)

Omnia
*****
-	All blocks now hide and show "no data" messages consistently (#127257, #128888, #129537, #131965, #133529, #138982)
-	Social reactions are now available including a revisit of all comment components for improved consistency (#138539).
-	Audit log improved to contain the start and end of a page archive action.
-	The setup wizard now supports "Basic Intranet" as well as Teamwork Content.
-	A sneak peak of what is to come as been added to the setup wizard.
-	Fixed a bug that would cause the link picker to highlight multiple categories. (#137969, )
- 	Corrected a styling issue in the media picker that would sometimes cause white text on white background (#141818).
- 	The Setup Wizard has gotten several improvements as well as the option to provision a basic intranet, a solution with only one publishing app. 
-	The default settings for the RTF editor are now correctly populated (#137218).
-	The metrics block has received an updated design.
-	Machine translations are now extendible making it possible to plug a third-party provider into Omnia for translations.
-	Central image locations are now central media locations and will also support video stored in SharePoint.
-	Omnia admin has gotten a small restructure, Microsoft 365 and Services integration points have been clustered into their own categories.
-	Emoticons can now be enabled in the RTF editor.


Web Content Management
******

-	Social reactions can now be used instead of just likes. 
-	Gifs via Giphy can now be inserted into comments and content (#126061).
-	Navigation nodes to specific layouts can now be exposed in the WCM editor. This together with the new Page Rollup capabilities solves all editorial listing issues (#127215, #116794, #117789, #127484)
-	The Editor now has adjustable panels to the left and right, resolving many spacing issues in that UI. (#124216)
-	Central Media Locations now supports picking videos stored in SharePoint (#134797).
-	Its now possible to create metrics using the count of a page rollup. (#123253).
-	RTF: Copy from word with multiple images greatly improved. (#137289)
-	RTF: Improved the rendering of option buttons when right aligning an image (#138182, #139470).
-	Image too large warning box have improved design and wording.
-	A page collection can now be changed between flat or hierarchy in the UI. 
-	Fixed an issue with the sign-off request block making it impossible to leave the title empty (#141758).
-	Improved UX for the publishing app setting UI. 
- 	Naming updates for a number of columns in the Page Rollup to better match what they are (example: "Reaction Count").
- 	Page Types can now be deleted even if there are old versions of pages using that page type.
-	Page collection nodes in the WCM editor are now ordered as: Default page collection on top, rest in alphabetical order (#135404).
- 	When opening a second WCM editor (e.g., the tenant page types in Omnia admin), the first editor will automatically close. 
-	Like/React and Share is now available in the page rollup dialog view.
-	Improved stability of the copy block feature.
- 	Better breadcrumb rendering for RTL languages.
-	Corrected an issue where the term options on a page would be in the wrong language (#139500).
-	The left navigation will no longer us break word in its styling (#138638).
-	Corrected logic for archiving, the comment will only be mandatory when multiple pages will be deleted (#124125).
-	The FAQ block now correctly gets its language from the Business Profile (#137196).
-	Corrected alignment of the people rollup card properties.
-	Copy banner now works as expected (#138302).
-	Corrected an issue where mentioning a user would cause the browser to hang. 
-	Event management copy event will now work even when no system account for event management is setup (#127051).
-	Improved export to excel in the page rollup.
-	Approvals can now be configured to only apply to Authors and not editors (#120455).
- 	Queries and filtering for the Process datatype now works as expected in the Page Rollup. 
- 	Corrected an issue where the browser title would be lost of filters are kept by query string.
-	An administrator can now correctly remove other people’s comments. 
-	Improved handling of time zones in page data.
- 	Corrected an issue with page property padding (#138463).
- 	Digital signage now supports display names for term properties and display names for people properties. 
-	Page rollup can now show targets in its statistics centered views.
-	Page rollup Channel filter now correctly has a scrollbar.
-	Improved stability for the Publishing App Admin sync to Site collection admin (#139157, #140381).
-	Community pages can now be correctly shown in the page rollup via "App" query scope.
-	A page collection can now be connected to a taxonomy, making each page create a taxonomy term.
-	A new action has been made available to the action button to add any page to your calendar via an .ics file.
-	Term "Pending Publishing" has been renamed "Unpublished Changes" in the page rollup for clarity.
-	Team news rollup now show thumbnail correctly.




Search and People Rollup
*****
-	Corrected an issue where the search dialog would not close correctly on navigate (#139364, #140210). 
-	Spelling suggestions are now available for searching (#116122, #116114, #126845).
-	Search statistics are now available in omnia admin, see main release notes.
-	Fixed a race condition that would sometimes cause the previous search result to be rendered (#137980).
-	Shared Links item template now includes description and has aligned its look and feel with other views.
-	Date refiners can now have a default value.
- 	Corrected an issue with paging in the search (#139335).
-	A permission role for Search has been added (Search Administrator).
-	Quick search now shows the total numbers of results in advanced search for each category.
-	Birthday queries can now be made in the people rollup. 


Teamwork and Workplace
***********

-	Security groups can now be correctly synced to SharePoint on Team Sites and Communication sites (#140845).
-	Updates to Active/Inactive Teamwork metrics.
-	The Omnia header no longer shows incorrectly in some MS teams Tab types (#139911, #139956).
- 	The all tab in "Manage Links" now behaves the same as the "All Links" option in search on my links (#131815, #139096)
- 	Teamwork navigation will now always open a SharePoint site in a new tab (to prevent issues from within the MS Teams client (#133140).
-	A Process can now be shown in the context of a project Team, see main release notes for more information.
-	Omnia App Instance properties can now be access from within MS Teams via a new button.
-	The User profile completeness block now works correctly in Dark Themes (#140327).
-	Added correct validation of length of title and alias when creating teamwork (#140627).
-	Security on App level has been removed from Omnia Admin; it is no longer needed.
-	Corrected an issue with Announcement emails, they now replace tokens correctly.


Management System
*****

-	Document management now integrates with Draftable.
-	Date format of tokens in documents can now be set by putting the formatting in the token. Example: [[InternalName|YYYY-MM-DD]].
-	Corrected an issue in the Swedish feedback email (#14026).
-	Documents can now be flagged as “Is Record” allowing the admin to disable certain actions such as create draft (#123956).
-	Metadata can now be inserted into the content of excel files.
-	Marco enabled files now have correct higher resolution icons (#139585).
- 	Process Management print functionality now better supports inline images. 
-	When publishing a page, the properties dialog will now clearly indicate which properties are missing (#117951, #138156).
- 	Corrected the query logic for Draft Controlled Documents (#138189).
-	Default document template can now be removed from a document type.
- 	Corrected an issue that would sometimes show "undefined" in the create document dialog. 
- 	Fixed an issue that would case the wrong document to open in the managed properties dialog on a controlled document (#139906).
-	Workflow history has been improved to more clearly show which action were taken for a specific document.

WCAG
********
-	Configurable arial role has been added to all buttons in the Workspace action menu.
-	User profile completion block is now WCAG compliant. 
-	Improved keyboards controls for comments, tabs block, Action menu and card view in page rollup.
-	Dynamic roller view next/prev arrows now has correct aria labels.
-	The RSS viewer will now show alt-text if supported by the RSS feed (#119782).
-	The tabs section now supports keyboard controls.
- 	Improved keyboard controls for the advanced search.
- 	Added alt text to the placeholder image in the page rollup.

