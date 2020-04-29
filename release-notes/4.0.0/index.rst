Upcoming Release 4.0.0 (Draft) 
========================================
*NOTE: These release notes are a draft. Items might be added, altered or removed.*


New features
----------------------------------------

Dynamic News Roller
************************************************

A new page rollup view is available that will make it possible, among other things, to show news on a start page in a horizontal scroll.

.. image:: dynamicroller.png

Pexels Connector
************************************************

It is now possible to enable Pexels images in the media picker. https://www.pexels.com provides high quality picture that are free to use.

.. image:: pexels.png

Note! This connector is not available for authors using Internet Explorer 11.

Translation Workflow
************************************************

Variation authors can now be registered to variations in a publishing app. A variation author is responsible for a specific variation and will be notified via e-mail when the default variation page is updated with a new major version.

.. image:: variation-author.png


Version Compare UI
************************************************

To help variation authors to translate a page, a new UI is available for comparing versions.

.. image:: compare-version-ui-icon.png

The UI will show the default variation page text on the left-hand side and the variation text on the right-hand side. It is possible to visualize changes that was made from the previous published major version of the default variation text. If you need to scroll the two texts separately, you can turn on the Scroll switch.

.. image:: compare-version-ui.png

Document Picker
************************************************

There is a new possibility to configure the Document Picker centrally in Omnia Admin to make different tabs available for the author. Two typers of categories can be created, either you select a specific SharePoint document library or you create a Search Category that should be available.


.. image:: document-picker-administration.png

The new document picker will replace the old one when adding related links on web pages. It will also show any document library that has been configured for the current publishing app.

.. image:: document-picker-ui.png

The new document picker will also be available in the document rollup. This will make it possible to pick individual documents instead of using a query to display documents.

.. image:: documentrollup-pickdocuments.png


Improved Search
************************************************

It is now possible to configure a search box to be shown in the header of a business profile.

.. image:: search-in-header.png

The Advanced Search block has been replaced by a Search block that can be configured to show either a quick or advanced search view with some additional display settings.

.. image:: search-block.png

A search category can be targeted to a specific group of people based on the targeting system in Omnia. The targeting settings will be used both in quick and advanced search.

.. image:: search-categories-targeted.png

Improved Teamwork Navigation and Administration
************************************************


(To be added to releasenotes soon!)
(#116996, #114661, #114870, #117577, #114837, #116854, #117576)

Process Management
************************************************

(To be added to releasenotes soon!)

Communities
************************************************

(To be added to releasenotes soon!)

Improved Audit Log
************************************************

(To be added to releasenotes soon!)

User Profile Sync
************************************************

(To be added to releasenotes soon!)

Enable/Disable Business Profile Header (and Preallocated Height)
*****************************************************************

(To be added to releasenotes soon!)



Enhancements
------------------------------------

Omnia
***********************
- Fixes to remove certificate error in Firefox.
- Several fixes to align with WCAG 2.1 AA.
- Improved keyboard controls.
- Several performance improvements for both Omnia and SPFx.
- Stability improvements to the color picker.

Web Content Management
***********************
- Now possible to use @mentions in page comments. An email will be sent to the mentioned user. (#113114)
- New Tab Section component, use it to create tabbed views on your pages.
- Deleting a page now gives correct UI feedback.
- Ensured correct label on the edit link and edit header in related links.
- Picking a document in related links can now support libraries with more than 5000 documents. 
- Auto rolling of the news roller will be disabled if accessibility mode is turned on.
- Custom block header size now starts at 1px instead of 30px.
- The page rollup now works correctly in SPFx (#118051).

Document Management
***********************
- Support for vsdx icons.
- The Tabs Drafts, Tasks, and Published now has a larger click area (#117861).

Tenant Administration
***********************
- Better handling for long display names on enterprise properties. (#114375, #114783, #117172).

Workplace
***********************
- It is now possible to base search queries on page variation url segment. 
- Targeting for search categories. It is now possible to use the targeting engine on search categories. (#115142, #115263).
- Date refiners now work as expected in advanced search (#114577, #115570).
- Updated design in advanced search (#117305, #116824).
- Updated design for action bar item tabs.
- Updated design for shared links.
- Action button has recieved many updates and multilingual support has been improved and it can now be used to create pages (#117303, #114101).

Fixes 
***********************
- Fixed a design glitch in document libraries when the omnia header is used. 
- People rollup roller view not auto rotates correctly (#117277).
- Page rollup column adjustment now works when having only one column (#117154, #117304).
- Correct default setting on date format when setting up a new environment (#114587).
- Several fixes to the document rollup, including taxonomy properties now work correctly in the query builder (#117598).
- Fixed an issue when related links settings would be unavailable after adding a link (#117580).
- Corrected email content from comment on important announcement (#117825).
- Background color on Shared Links is now set correctly when using the color picker to remove the color (#117646).
- Site Design is now hidden from the end user when creating a site (#113598).
- Improvements to term picker in dialogs.
- Fixed a problem that would cause the browser to hang if resized.
- Fixed alignment of top header for nodes without children.
- Fixed a z-index problem that would sometimes occur in SPFx.
- Padding now works as expected on the button link (#116905).
- Fixed a problem in the term picker for controlled documents (#117247).
- Fixes to the document rollup query builder to have better default values.
- Several fixes to margins and padding on the action button.
- Fixes to block margins, border radius and breadcrumb margins (#117653).
- Placeholder behavior is now correct on the accordion.
- Corrected UI in Document Management authoring sites to make tick boxes align (#117430).
- Corrected mobile navigation when using multiple page collections in one navigation structure (#115759).
- Document rollup now shows sorting arrows correctly when sorting (#117793, #118277).
- Document rollup now correctly hides when there is no content in the rollup (#117827).
- Advanced search now always shows the correct item count. Also impacts results and paging in some scenarios (#114072, #115352, #116723, #114039, #115789, #117802, #115121, #115250).
- External links in Shared Links now work correctly on IOS (#117048).
- Adding documents through related links now correctly lists deleted users (#117801).
- Now possible to create two enterprise properties with the same displayname (#115627).
- Fixed the page properties block to correctly rowbreak properties that does not fit (#118275).






