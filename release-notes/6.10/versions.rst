6.10.0 – In Progress
========================================

Teamwork
*********
- Using a new way to provision teams - approver who approves a team no longer becomes owner (#127793, #127652, #127793)
- Default values for properties on Teamwork is now available (#115969).
- Naming policies can now be configured on Teamwork.
- Teamwork can now be created in app context. Allowing the possibilities of only having self-service of MS Teams through Omnia.
- The create Teamwork wizard has been completely remade and fixes (#136225, #126909).
- Teamwork provisioning now supports sensitivity labels.
- Corrected validation of group names already existing. 
- Corrected URL validation in all scenarios (#124846, #120614).
- Teamwork rollup now uses the correct date format configured (#120436, #120434).
- Better usage of space in the teamwork rollup in narrow columns (#122146).
- Teamwork image can now be set in Omnia and will be synced to the O365 Group or Site.
- Updated people picker to only allow picking valid options (#132420, #133052).



Process Management
*****
- Using “Add as favorite” action button on processes now adds the process with the correct title (#135579).
- Processes can now be printed, or exported to PDF.

Workplace
************
- The User Profile Competition block now has configurable button labels (#116581).
-  Mega menu rendering in mobile and tablet improved (#125709).
- Corrected an issue with the action bar rendering when navigating via direct links (#119504).
- Corrected however effect on links in the top navigation (#114578).
- App Instance Posts Block available. See main release notes.

Web Content Management
*************
- Label padding now aligns better (#138463).
- Possibility to move pages between page collections (#113462, #132221).
- Possibility to move page collections between publishing apps (#113462, #132221).
- Related links can now use more options on how to open links (#133631, #119645, #120098).
- Related links now handles long links better including line breaks (#113899).
- RSS Feed block can now handle more kinds of images (#115862, #116968).
- Media properties can now have default values (#116730).
- SVG files now provide correct thumbnails when picked from a SharePoint library (#136801)
- Show more button in the Quick Links block now have the correct colour settings (#117529, #117911)
- Corrected an issue with colour settings in the enterprise glossary (#136443).
- Sorting by columns now has a larger clickable area (#119772).
- Fixed a cache issue on the page collection settings page (#137099).
- The variation picker no longer shows drafts as selectable (#128061).
- Improved UI in the edit banner form for small screens (#136671).
- Corrected the design of bullet lists in the FAQ block (#114117). 
- Automatic translation options are now correct when inheriting from tenant (#115062).
- Added possibility to resync Omnia Search Index, stability improvements to sync of SharePoint data. (#137857). 
- Improved page view statistics gathering. 
- Fixed an intermittent error where the preview of pages would sometimes give access denied (#136471, #138372, #134866, #136157).
- Authors can no longer delete page collections.
- Reworked action menus, icons, and option placement.
- Performance improvements for automatic translations.
- Performance improvements for editing Channels.
- Improved support for right to left languages when using auto translate.
- Emails sent from Web Content Management now fallback to the Business profile language.
- “Controlled Documents” and “Process Library” can now be activated on the backend site of a publishing app. 
- Channels can now be categories in to one Default Channel and Additional Channels.
- Blocks from a Layout/Page Type can now be configured to be unlockable. Allowing the editor on the page to change its configuration.
- Updated link picker UX with more options.




Search
*******
- Corrected rendering of links in search (#138299).
- Layout updates to search to better use the space when using promoted links and feedback (#136188, #136341, #136593).
- Improvements to the Omnia Free Text search generation (#136940, #136892).
- Corrected rendering of Teams Presence in Quick Search.

Controlled documents
****
- Added support for icons on .msg files (#120880).
- Updating multiple draft documents properties will now work correctly (#138671).
- Added a missing space to the default text in the Feedback dialog (#120819, #122188).


System
**********
- The Azure AD Sync has received several updates to improve stability (#138948).
- Default content features can now be upgraded without error (#120974).
- User profile completeness now reaches 100% even when the user profile picture is included (#119425, #134770).
- Improved rendering of Icons in all system (#120369).
- Corrected the z-index of the “Your session has expired” message (#120381).
- General performance improvements for page loads and page rollups.
- The login flow has been simplified, leading to better performance on login.
- The setup Wizard is now available for all tenants.
- The Script block MSGraph client now refreshes its tokens automatically in case they expire.
- New definitions of built in groups, see main release notes.

Page Rollup
*********
- Possibility to view and sort by Most visited (#118520).
- Better overflow for the page rollup in narrow columns (#133906).
- Its now possible to sort on text in the page rollup (#119522, #127382, #128932, #124725).
- Possibility to show pages in a calendar view.
- Possibility to query on All pages (Tenant) or all pages in a Business Profile.
- Possibility to query on Language.
- Possibility to query on and show pages that has never been published.
- Possibility to query on Workflow status (Scheduled).
- Possibility to sort by most viewed. (#115241, #121723).
- The page rollup results can now be exported to Excel.
- Possibility to filter on Channels for all scopes. 



WCAG and UI/UX
***************
- alt text when hovering term picker icon corrected. (#115442)
- When selecting multiple terms, the picker will not close between selections (#116627, #121832).
- Corrected color for the close button of the notification panel admin blade (#126112).
- aria-describedby is now used to connect error messages in user profile completeness to the correct form input.
- Configurable alt-text now available on the tenant and BP logos.
- Browser title updated to better comply with WCAG recommendations. 
- Updated aria-labels for navigation components.
- no-script message added if Omnia is started without JavaScript enabled. 
- Corrected heading structure to better comply with WCAG standard. 
- Better element IDs for the search panel.
- Improved keyboard control feedback.
- Several corrections to rendering in Safari.
- Teams presence is now available on all components where applicable. 
- Corrected background color on the skeleton loader.
- Close button and click out added to the tutorial.

Also fixes preview bugs (#138042, #138335, #138527, #138224, #138538, #138239, #138050, #137947, #138216)
