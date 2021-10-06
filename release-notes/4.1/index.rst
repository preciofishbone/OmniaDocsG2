Release 4.1
========================================

Enhancements
------------------------------------

General
***********************
- Targeting is now possible on custom Azure AD properties.
- Several WCAG improvements.
- Open term sets are now supported. (#117764, #118724, #119930, #117753)
- Several improvements to the mobile experience.
- MS Teams apps now work with SSO. This enables the omnia based MS Teams apps to work in mobile and desktop clients.
- The term store no longer requires English to be an available language (#119375, #120348).

Web Content Management
***********************
- Increased contrast in page properties. 
- The translation feature can now support longer texts.

Team Collaboration
***********************
- Last visited will now be recorded when using the SharePoint provider to list sites.
- Mobile UI improvements.

Document Management
***********************
- The document picker now supports using a folder as well as a library (#120351, #120122).

People and networking
***********************
- Padding is now properly supported in the People Rollup.

Tenant Administration
***********************
- Possible to view system logs in Omnia Admin to troubleshoot issues on site provisioning and other long running operations.

Workplace
***********************
- The high priority Announcement view now works in a block. 
- Its now possible to configure default sort order for search categories (#118857).
- Sort direction is now configurable. A search category can be sorted on Relevance, Popularity or a sortable enterprise property.
- Improved error messages when trying to follow a Group you don�t have access to. (#120336).
- Its now possible to configure whether query rules should be applied on not in search queries. This configuration helps solve apparently inconsistent search results (#120316)
- Advanced search as a block has been improved.
- MS Teams icon is now shown for sites in the Member Of provider (#116695).
- Search now correctly resolves people when used as a property from search.

Communities
***********************
- Several stability updates and fixes to default data.

Process Management
***********************
- Updated the way published processes can be fetched via search.
- Responsiveness of the default process preview page has been improved (#120204)

Fixes 
------------------------------------
- Fixed an issue where the dynamic news roller sometimes would not display.
- Updated the dynamic roller to render better in the notification panel (#120109)
- The notification panel now correctly renders notification when placed in the Action menu.
- Corrected font size in the site creation wizard (#119960).
- Corrected font sizes in edit and view mode. They no longer differ. 
- Corrected the Mobile UI for subscriptions 
- Design updates on all table listing views. They are now consistent.
- The author field now renders correctly on updates in the edit variations UI.
- Updated banner behavior when not having any image. 
- Fixed banner rendering when zooming in the browser (#120125)
- Stability updates to the Activity feed. 
- Corrected a bug that caused page property setting "Date Only" to be editable when it should not (#118753).
- Several improvements to search and page dialog view experience on IOS.
- Fixed an issue that would case an OPM shape to reset when a child process step was added.
- Added correct translations for default shapes in OPM. 
- Added correct behaviors when languages are deleted regarding document templates.
- Enhancement to translation UI on low resolution screens.
- Fixed an issue that would sometimes cause incorrect validation when publishing a document. 
- Old Teamwork navigations now correctly run on page load. (#120088)
- Teamwork navigation admin list now correctly updates when a Teamwork is removed.
- Updates to the default Communities template.
- Fixed an issue where deleted app instances would still show up in the admin UI.
- Stability improvements in the Teamwork navigation (#118680).
- Number properties now provision correct columns in SharePoint.
- Removed duplicate in the settings UI for the Script/HTML block.
- Search now closes correctly when a page is selected (#120078).
- The Search block no longer puts focus in the textbox, making it possible to place the search low on the page (#119768).
- The mobile menu now correctly hides indication of child nodes if all child nodes are hidden (#118556).
- Colors now apply correctly to important announcements in a multi business profile scenario (#119616).
- Fixed a bug that cause the preview in search to not work on some tenants (#117849, #120303).
- Tag display is now WCAG compliant.
- Fixed an issue with the tooltip on the Teamwork rollup (#120336).
- Preview of process on search now works as expected.
- Fixed an issue with the Action button that would cause the wrong icon to display.
- Fixed an issue that caused the filters on the page rollup to not render correctly (#120067)
- Fixed an error where different in casing would identify the same user as two different.
- Fixed an issue in the preview of shapes in the shape gallery.
- Client-side validation on colors now work correctly when removing a color from a shape.
- Corrected translation issues (#120333).
- Fixed a styling issue on page links in related links.
- Show more on refiners now works as expected in advanced search (#120347).
- Corrected an issue related to syncing enterprise properties to the term store in Document Management and Process Management (#120338).

Versions
-----------------------------------------

.. toctree::
   :titlesonly:

   versions
