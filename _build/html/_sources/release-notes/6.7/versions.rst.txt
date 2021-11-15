6.7.0 - DRAFT
========================================
(Omnia 6.7.0 / Workplace 6.7.0 / WCM 6.7.0 / MS 6.7.0)

.. note:: These release notes are in Draft, it means they can change at any time. Items might be added, removed, or updated.

New Major Features
**************************

Copy blocks and sections across pages
------------------------------------------
- Its now possible to copy blocks and sections between pages using the new clipboard feature. (#129970)

Favicon is now configurable per business profile. (#126515)
------------------------------------------
- Full support for all apple and iOS icons.

Calculated Date Properties (#123172, #114551)
-----------------------------------------
- A date property can now be based of another date property.
- This enables automatic updates of review dates, and automatic unpublishing.

Automatic Archive
-----------------------------------------
- A Page can now be set to automatically archive based on a property. (#128186, #128942)
- The archive can be configured to automatically delete content after a set period.

Sign off requests
-----------------------------------------


Block for displaying PowerApps
-----------------------------------------


Search Feedback and promoted search results.
-----------------------------------------


Modals and panels will now close on click out (#123157, #122336, #125956)
-----------------------------------------
- Click out is prevented when edits have been made, or when accessibility is turned on.

Yammer for likes and comments
-----------------------------------------

Anchor links
-----------------------------------------
Its now possible to configure links to link to any position on the page, or into any tab or accordion.




New Minor Features
**************************
- Its now possible to add a link to an image in an RTF field (#123318, #125364).
- Image descriptions are now rendered as both alt text and title text on the img element (#131343).
- Image default ratios and enforce scaling is now available for images in a section.
- When using a custom icon for a link, it’s now possible to upload an image from your computer. (#116728, #116782)
- When using the Keep text only feature in RTF, all style tags are now removed (Only default HTML styles is kept)
- Its now possible to move document types in the document type tree in Omnia Admin.
- When the accordion/FAQ block has no content, it will be completely hidden in read mode (#128010).
- Its now possible to configure my site to only show a link to Teams (And not also to the SharePoint site) (#121953).
- Action buttons can now be rearranged within the same action button block (#129574).
- Card view for the document rollup.
- Its now possible to sort pages in the page rollup by title (#127889).
- Important announcements now supports RTF, making it possible to have for example links in the important announcement (#116651).
- Its now possible to start a phone call or MS Teams call directly from the people rollup. (#122406, #127035, #126851).


Fixes
**************************
- Page feedback now correctly supports, rich text, limited rich text and plain text (#131183, #131286, #131302, #131487)
- Its now possible to mention people both on name and email, a scroll has been added to the mention list, and the login name is displayed as a tooltip (#125014, #126325)
- Page types now correctly use the default settings for date styles configured on tenant level (#128621).
- Per page property permissions now works correctly in the create page dialog (#126754).
- Calendar rollup now opens details in a custom form in Omnia, solving issues with opening the details of the event in Outlook (#129532, #114133, #119406, #130515).
- Fixes to the layout settings of the notification panel (#128805).
- The cache for the RSS reader has been reduced to 1 minute, this will ensure quicker updates of new entries in the RSS block (#126762).
- Fixed a small styling issue with refiners in search (#128377).
- Improved performance when creating pages in page collections with many entries (#130658).
- The RSS block no longer crashes the page when a faulty URL is supplied in settings (#124703).
- Info screen now keeps settings when switching views. (#132723).
