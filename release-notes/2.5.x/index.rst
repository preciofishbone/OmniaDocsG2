Release Notes 2.5.0
========================================

New features and enhancements
***********************

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
***********************

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

Release Notes 2.5.4
========================================

Fixes
***********************

- Fallback to Tenant default language correctly when the users language is not set
- Fixed an issue where the statistics provider would sometimes not execute correctly
- Translation fixes for Swedish and Danish