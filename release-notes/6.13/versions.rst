6.13.1
========================================
(Omnia 6.13.1 / Workplace 6.13.1 / WCM 6.13.2 / MS 6.13.1)

- Reindex to SharePoint now correctly keeps original modified date (#145591).
- Fixed a width rendering issue in the current navigation (#145610).
- Fixed an issue with send email in send for comments flow when sites have been deleted.
- Fixed an issue with filters for channel in the page rollup.


6.13.0
========================================
 (Omnia 6.13.0 / Workplace 6.13.0 / WCM 6.13.0 / MS 6.13.0)


Setup Wizard
***********

- Now supports the setup of Knowledge sharing.
- Now supports the setup of a Learning Center.
- Now support additional News Centers. 
- Setup wizard can now be accessed from Omnia Admin in Business Profile and Tenant scopes, respectively. Old query strings are removed.
- Added default SharePoint search mapping for built in user fields.



Web Content Management
***********

- Fixed an issue that prevented the Channels admin UI to load correctly (#143892).
- Added support for scenarios when channels and variations are combined in the page rollup (#141379).
- Improved UX for commenting on mobile, the keyboard now opens automatically.
- Posts block now manages permissions in a better way (#143491).
- Digital Signage now supports video and Static Content.
- Modified by now works as expected when used as a property in the JSON based endpoint of Digital Signage.
- Performance improvements for the Page Rollup.
- Improved stability for move page and move page collection. 
- Corrected the page collection and publishing app sorting in the page picker (#143406).
- Now possible to more easily rollup pages checked out by me that have already been published.
- Fixed several z-index issues with dialogs and the workplace megamenu.
- Ensured Tab rendering (#145162).

Teamwork
*********
- Corrected an issue where saved sensitivity label setting "Let the user decide" would not repopulate correctly in the form.
- Modified by now works as expected when used as a property in the JSON based endpoint of digital signage.

Workplace
********
- The User Profile Completion Wizard taxonomy picker no longer closes upon selection (#142754).
- Fixed an issue where the posts block would not always show its context menu.

Sign Off Requests
***********

- Sign Off Requests now supports any enterprise property as metadata.
- A new section for queryable properties for Sign Off requests have been added. 
- A new Sign Off Request rollup has been added which includes configurable columns.
- A new type of Sign Off Request is now available, Group Request. This allows for multiple people to Share the same sign off. 
- A new detail view of sign of requests. 
 

Document Management
***********
- Controlled documents now have an improved recycle bin.
- Direct links to New Stream videos can now be used in the Media picker.
- Added a clearer end user message when changing document template in Controlled Documents (#143514).


System
***********
- MS Teams Manifest updated to the latest version (Used when generating MS Teams apps through the Omnia admin interface.)
- Performance improvements on publishing pages.
- Its now possible to Remove features completely via an API call (For Extensions development).
- Stability improvements in the Page Archive flow.
- In preparation for future rollouts, Omnia can now run in a Read Only mode.
