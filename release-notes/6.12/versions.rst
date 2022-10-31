6.12.0
========================================
(Omnia 6.12.0 / Workplace 6.12.0 / WCM 6.12.0 / MS 6.12.0)

Omnia
*****
-	All blocks now hide and show "no data" messages consistently (#127257, #128888, #129537, #131965, #133529, #138982)
-	Social reactions are now available including a revisit of all comment components for improved consistency (#138539).
-	Audit log improved to contain the start and end of a page archive action.
-	The setup wizard now supports "Basic Intranet" as well as Teamwork Content.
-	Fixed a bug that would cause the link picker to highlight multiple categories. (#137969, )
- 	Corrected a styling issue in the media picker that would sometimes cause white text on white background (#141818).


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
- 	When opening a second WCM editor (e.g., the tenant pages types in Omnia admin), the first editor will automatically close. 
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




Search
*****
-	Corrected an issue where the search dialog would not close correctly on navigate (#139364, #140210). 
-	Spelling suggestions are now available for searching (#116122, #116114, #126845).
-	Fixed a race condition that would sometimes cause the previous search result to be rendered (#137980).
-	Shared Links item template now includes description and has aligned its look and feel with other views.
-	Date refiners can now have a default value.
- 	Corrected an issue with paging in the search (#139335).
-	A permission role for Search has been added (Search Administrator).


Teamwork
***********

-	Security groups can now be correctly synced to SharePoint on Team Sites and Communication sites (#140845).
-	Updates to Active/Inactive Teamwork metrics.
-	The Omnia header no longer shows incorrectly in some MS teams Tab types (#139911, #139956).


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


WCAG
********
-	Configurable arial role has been added to all buttons in the Workspace action menu.
-	User profile completion block is now WCAG compliant. 
-	Improved keyboards controls for comments, tabs block, Action menu.
-	Dynamic roller view next/prev arrows now has correct aria labels.
-	The RSS viewer will now show alt-text if supported by the RSS feed (#119782).

