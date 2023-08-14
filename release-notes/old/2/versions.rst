2.1.1
========================================

New Features and Enhancements
****************************************
- Support for targeting using AzureAD properties
- Support for targeting on O365 Language
- Accordion block now hides completely if it has no content.
- WCM Editor: Performance enhancements in edit mode.
- Revised system labels in Swedish and English.
- Its now possible to edit provisioning templates deployed by the system
- Long titles in the current navigation now breaks into 2 rows.
- Tutorial has an updated design

Fixes
****************************************
- Omnia now works for users without a mailbox
- Several issues on mobile has been resolved.
- The back button in the browser now works as expected. 
- Fixes to default enterprise properties.
- Notification panel: Fixes to problems related to having 2 notification panels on the same page
- Notification panel: Fixed a problem where the document rollup sometimes could not be configured in the notification panel.
- Using the logo to navigate now works correctly between publishing apps. 
- WCM: Fixed a problem related to trim duplicates in the page rollup.
- WCM: Fixed a problem related to RTF page properties 
- WCM: Fixed a problem with the Advanced button in the create page dialog
- WCM: Fixed a design issue with the Modal window for news
- WCM: Read news articles now correctly displays as read.
- WCM: Default page collection now works together with page variations
- Workplace: Updated overrides for refinable in advanced search.
- Workplace: User Profile Completeness: Fixed an issue related to setting profile image as a field
- Workplace: Site properties now works as expected when using the MSTeams feature.
- Unread notification now works correctly in document rollup.
- Deleted publishing apps do no longer show up when setting up different parts of the system.
- Button links now align correctly when placed next to each other. 
- User profile Completion: Now validates required properties correctly.
- People Rollup: Now supports taxonomy/Boolean properties as filter. 
- People Rollup: Better design. 

2.2
========================================

New Features and Enhancements
****************************************
- It's now possible to configure the Quick links component / App selector to show non mandatory links.
- Keywords datatype are now supported in the page rollup (To display in list view, to use for Query and Filter).
- Updates to the Omnia Tenant header to align with new O365 design.
- Targeting information now updates instantly if User profile completness block is used.
- Updated labels for media block and Layout blocks.
- Added a free text search box to the people rollup
- New UI for buttons in the editor.

Fixes
****************************************
- Fixes to prevent a redirect loop when using page variations.
- Fixes to how page variation behaves in the page rollup.
- Preview mode now works as expected for non admin users.
- Fixed an issue related to z-index in team sites.
- Fixed a rendering issue in the current navigation.
- Fixed so deleting a search category also removes it from the selection in Quick Search or Advanced Search.
- Fixed a problem in the megamenu causing Dynamic levels not to work as intended.

2.3.1
========================================

New Features and Enhancements
****************************************
- New design for the open page as modal from Page Rollup.
- App launcher design has been aligned with O365 changes.
- Quick Links block now has a setting to include followed links.
- Its now possible to take over/remove pages that have no published version.
- People picker suggestions and much more performant search experience.
- Client side error messages now show at the top of the screen.
- Renamed sections in the layout parts of the WCM editor.
- Impolemented the standard block header in the Advanced Search Block.
- New setting for setting the background color of the selected tab in the notification panel.

Fixes
****************************************
- Fixed a bug causeing related documents to get the wrong url
- Site Design dropdown is no longer shown to end users when creating a site.
- Fixed a permission bug causing Page Colleciton admins to sometimes get wrong read permissions.
- Link from page rollup to page collection now works as expected if open page as dialog is tunred on.
- Team Collaborations now provision correctly when approval is turned on and features are used in the template.
- Left navigation now behaves correctly when navigating between publishing apps using the mega menu.
- Roller view sometimes got a corrupt image when open in modal dialog was used.
- Variations selector now works as expected.
- 401 pages that sometimes flashes by has been fixed.
- Fixed a bug where page properties could not be previewed.
- Removed a blur effect from the Content editor.
- Open in new window now works as expected for custom links in the structure.
- The default message for Quick search is now correct when no search has been made.
- Dialogs now always correctly render the close button in the top right corner.
- Multiple fixes and stability improvments to the RSS reader.
- Added correct validation to the urls when creating a new publishing app.
- When a min height is set on a section, the content now aligns at the top instead of the center.
- Quick Links with no background color set will now render as transparent instead of black.
- Link button now correctly opens in new tab if set as open in new tab.
- Document picker now correctly shows up in new environments and correctly resolves links if a custom fallback url is set.

2.4
========================================

New features and enhancements
****************************************
- RTF editor in the Accordion has been aligned with other RTF editors.
- Made it possible to set all colors of the notification panel. Background Color, Active background color, Icon color, Active Icon color, Notification count color and border color.
- Default Business Profile Config feature, will automatically setup, App Launcher, Action menu in the top right and the Mega menu.
- Allow for selection of external users in all roles.
- Updated publishing app settings to make it easier to configure the document library to use.
- Added a tenant wide setting to turn client side error messages on or off.
- Updated the create page button on the page rollup to create pages in any page collection its connected to. 
- Updated terminology on non O365 group Team Sites.
- Improved performance in the central image locations in some scenarios.

Fixes
****************************************
- Fixed some layout issues in the WCM editor.
- The preview of the Media Picker now works correctly in all supported browsers.
- Fixed an error where page variations would not create correctly.
- Updated the text in the Team Collaboration App provisioning email flow.
- Fixed a javascript console error that sometimes would occur on navigate.
- Updated names for default image ratios.
- Fixed an issue where the page was not correctly published in SharePoint.
- Fixes to related documents getting the wrong url when updated and a custom fallback url being used.
- Made sure deleting a publishing app clear up any allocated urls.
- Fixed an issue where a termset could cause client side error.
- Fixed an error making it difficult to remove a column on a section in the WCM.
- Fixed a number of navigation errors, sometimes causing current navigation and page rollup to get the wrong data. 
- Fixed the default data features to create the page collections intended to be flat as a flat page collection.
- Fixed the current navigation sometimes indicating it has children when they were not there.
- Fixed Swedish translation on Share and Like button in comment control. 
- Updated handling of enterprise properties on sites created via site designs. 
- Removed frame from embedded youtube videos.
- Fixed an error sometimes causing a site request not being approved.
- Fixed a problem where the approval buttons would not display if the users had a different navigation node loaded in the editor. 
- Fixed a design glitch in the quick search when content has very long titles. 
- Fixed so help texts now works with RTF.
- Term picker now displays correctly at the bottom of the page. 
- Fixed an issue related to editing custom links in the navigation structure. 
- Fixed an issue with publishing app settings when on the root page. 
- Fixes to the background image upload. 
- Fixes to the mysites titles.

2.5
========================================

New features and enhancements
****************************************

Omnia
----------------------------------------

- UI for selecting available RTE actions on both Tenant and block level. 
- Possibility to turn end user error messages on or off.
- Display of taxonomy properties has been redone.
- Fixes to the login process to support a broader range of MFA scenarios

Team Collaboraion
----------------------------------------

- Provisioning of Communication sites. Its now possible to provision communication sites. They can be found as a template under the Team collaboration area.
- Support for Office 365 Naming policies. Omnia vill now validate Site names and urls against policies set in the tenant.
- When provisioning an O365 group with a MS Teams, the Conversations link in the group will now point to the MS Team. 

Web Content Management
----------------------------------------

- Setting on the Related links block to open office documents in the Web Client.
- Enhanced default values for dates. Its now possible to set the default value to a relative time in the future i.e. Today + 6 weeks.

Document Management
----------------------------------------

- Document rollup now evaluates terms at query time instead of ad configuration time.

Fixes
****************************************
- Updates to term picker to more clearly indicate if a term is not available for tagging
- Wrong language in Omnia Admin and the WCM Editor for some users.
- Fixes to the notification panel to support documents with " ' " - charaters in the filename. 
- Several UI Fixes for IE11.
- Several UI Fixes for Safari. 
- Fixes to the term picker not rendering correctly in the user profile completeness.
- Fixed an issue that caused new Tenant Features to not show up correctly. 
- Updates to the third party statistics provider for a more consistent experience. 
- Updates to social dates to correctly display in Swedish on likes and comments and advanced search.
- Fixed an issue where the system field [Current User] would not display.
- Fixed an issue where the Calendar rollup would not correctly fetch Personal calendars when in the notification panel.  
- Fixes to the RTF Editor making it easier to remove images in IE11 and Edge.
- Fixed an issue where pages would not correctly render inside the notification panel in the header.
- Added missing translations for Provisioning Templates and confirmation emails. 
- Added missing label in site creation form.
- Fixes to Section header being incorrectly placed when using a large column spacing.

2.5.4
========================================

Fixes
****************************************

- Fallback to Tenant default language correctly when the users language is not set.
- Fixed an issue where the statistics provider would sometimes not execute correctly.
- Translation fixes for Swedish and Danish.

2.6
========================================

New features and enhancements
****************************************
- Widening of the user profile completeness dialog.
- The attach site API can now be called from an extension.
- When creating a site through omnia using approval, the requester of the site becomes the owner, not the approver.
- The calendar rollup query limit increased to 90 days.

Fixes
****************************************
- Yammer group provisioning together with approval now works as expected.
- Fixed several issues related to page variations.
- Updates to Danish, German and French Translations.
- Fixed an issue that sometimes prevented Taxonomy metadata on pages to be saved.
- Fixed an error in the default content feature causing an enterprise property mapping to be wrong.
- Fixed an issue where images would sometimes not render in Safari.
- Fixes to the mobile global navigation to correctly handle page variations.
- Fixed an issue where default values for the document rollup sometimes would not show up.
- Fixed an issue with controlled documents stuck in publishing.
- Fixed an issue that caused the page statistics not to work correctly.
- Fixed an issue that made comments always run in Rich Text Mode.
- Fixed an issue that caused page property validation to be wrong when reusing content.
- Fixed the quickserach to have correct responsive behaviour on IOS.

2.6.10
========================================

Enhancements
***********************

- Performance improvements when having deep structures in the left navigation.
- Ensured compatability with Chrome version 80 (new cookie policy: https://blog.chromium.org/2019/05/improving-privacy-and-security-on-web.html?m=1).

Fixes 
***********************

- Fixed an issue where custom links would not work properly in IE.
- Fixed an Ui issue in Quick Search on mobile.
- Fixed an issue where Document Management authoring sites would not provision correctly.
- Improved stability when provisioning MS Teams teams.
- Fixes to page variations in rollups in certain configurations.
- Team collaboration sites now displays the correct owner when the site is created with approval.
- The indicator in the left navigation for child-nodes now displays correctly in all scenarios.
- Fixed an issue of the languge inheretence between the Tenant and it's business profiles.
- Fixed an issue where users from active directory groups did not get the correct permission level when added as an announcement administrator.
- Fixed an issue where some documents could not be removed from sharepoint-sites linked to ODM.
- Fixed an issue where yammer group could sometimes not be created.


