6.12.0
========================================
(Omnia 6.12.0 / Workplace 6.12.0 / WCM 6.12.0 / MS 6.12.0)

Omnia
*****
-	All blocks now hide and show no data consistently (#127257, #128888, #129537, #131965, #133529, #138982)
-	Social reactions are now available including a revisit of all comment components for improved consistency (#138539).
-	Audit log improved to contain the start and end of a page archive action.


Web Content Management
******
-	Gifs via Giphy can now be inserted into comments and content (#126061).
-	Navigation nodes to specific layouts can now be exposed in the WCM editor. This together with the new Page Rollup capabilities solves all editorial listing issues (#127215, #116794, #117789, #127484)
-	The Editor now has adjustable panels to the left and right, resolving many spacing issues in that UI. (#124216, )
-	Central Media Locations now supports picking videos stored in SharePoint (#134797).
-	Its now possible to create metrics using the count of a page rollup. (#123253).
-	RTF: Copy from word with multiple images greatly improved. (#137289)
-	Image too large warning box have improved design and wording.
-	A page collection can now be changed between flat or hierarchy in the UI. 
-	Fixed an issue with the sign-off request block making it impossible to leave the title empty (#141758).


Search
*****
-	Corrected an issue where the search dialog would not close correctly on navigate (#139364, #140210). 
-	Spelling suggestions are now available for searching (#116122, #116114, #126845).
-	Fixed a race condition that would sometimes cause the previous search result to be rendered (#137980).



Management System
*****
-	Date format of tokens in documents can now be set by putting the formatting in the token. Example: [[InternalName|YYYY-MM-DD]].
-	Corrected an issue in the Swedish feedback email (#14026).
-	Documents can now be flagged as “Is Record” allowing the admin to disable certain actions such as create draft (#123956).
-	Metadata can now be inserted into the content of excel files.
-	Marco enabled files now have correct higher resolution icons (#139585).

WCAG
********
-	Configurable arial role has been added to all buttons in the Workspace action menu.
-	User profile completion block is now WCAG compliant. 
-	Improved keyboards controls for comments, tabs block, Action menu.

