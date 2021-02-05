6.0.0
========================================

.. note::  These release notes are a draft. Items might be added, edited or removed.

General
***********************
- Omnia Banners are no longer supported in SPFx.
- Ensured MS Teams to always open external links in a new tab.
- Better handling of enterprise properties (#123320).
- Tenant and Business Profile logo is now saved as real image resources instead of base64.
- Current user language can now be set by the user; this is especially useful if the Windows AD property for language is not set.
- Theming is now generally available for all blocks and the editor.
- The login form for Kaizala users now supports correct keyboard controls.
- A new control for selecting enterprise properties has been introduced. It will be used through the entire system. 
- New structure and organization in Omnia Admin.
- New option for properties “Queryable properties”. This pane replaces the old queryable checkbox on each property, and allow for editing the queryable option.


Web Content Management
***********************
- Page types are now available on tenant level, see general release notes.
- A new media picker is now available, see general release notes (#126458).
- Its now possible to reuse content between variations of a page.
- Open in dialog on People Rollup no longer affects the email link (#123092).
- The page rollup feature "Exclude current page" now works correctly with variation pages (#121376, #121378).
- Fixed an issue with deleting variations (#118456).
- New Media picker and compression logic (#114223, #114919)
- The new media picker now supports .svg files (#123514).
- Several performance improvements for all page queries (#123670)
- Updates to the card view of the page rollup.
- Read news no longer depend on the device but is stored on your user profile instead.
- Status if a important announcement has been closed or not is now remembered across devices.
- Image ratios are now supported in newsletters.
- Page rollup can now be sorted on numbers.
- Increased performance of the page rollup.
- Its now possible to query a page rollup towards a specific variation, as well as the current page or the current user.
- Stability improvements to the page sync. (#)
- Options for video embed has been expanded to correctly handle autoplay and mute. Note all options are not available in videos from stream.
- Several updates to the page picker.
- The dynamic roller view has gotten several stability updates (#124584).
- New design for the RTF quote style. 
- 

Teamwork
***********************
- Fixed an issue causing default visitors not to applied to certain site types when provisioned.
- Properties for a teamwork template now uses property sets, allowing you to set dependent properties and ordering of properties (#123320).
- Document management and Process management MS Teams tabs can now be easily configured in the Template.
- Its now possible to add members and owners when creating a new teamwork.
- Confirmation emails are no longer sent when editing Teamwork.
- Validation when creating new Teamwork has been improved (#120614).
- 

Document Management
***********************
- Features for retention and termination.
- Bulk update.
- Published ODM documents are now set as read only on a file level.
- Several changes to improve stability of the publish flow.
- Retention date can now be based on any enterprise property (#115742).

Process Management
***********************
- Its now possible to publish processes with limited permissions.

For Developers
***********************
- Omnia now uses the .NET Standard CSOM. 
- Several of the Omnia Core Extensions have been merged into one. 
- Better error handling when creating client context.

