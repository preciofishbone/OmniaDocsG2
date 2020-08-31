Release 5 (DRAFT)
========================================
.. note:: **This is a draft of the release notes. Text might be added, altered or removed.**

.. note:: A new app consent is needed to allow Microsoft Teams Single sign on. It contains the following added permissions:

          - **offline_access (Delegated)** Maintain access to data you have given it access to
          - **openid (Delegated)** Sign users in
          - **profile (Delegated)**	View users' basic profile


Newsletter
-----------------------------------------
You can now setup a Page Collection to allow for pages to be sent out as e-mail.

.. image:: newsletter-settings.png

This makes it possible to implement a Newsletter solution.

.. image:: newsletter-archive.png

An important part of a newsletter would be to be able to manually pick which pages that should be shown in a page rollup. A new feature makes it possible to configure a page type to pick pages in write mode.

.. image:: newsletter-pick-pages-settings.png

The author can create a new newsletter, write an introduction and pick the news articles that should be sent out.

.. image:: newsletter-pick-pages.png

A new tab is available where it is possible for an author to decide the target group for the newsletter by putting in one or more e-mail addresses.

.. image:: newsletter-recipients.png

Before a newsletter is sent out, the author can send a preview to any e-mail address.

.. image:: newsletter-send-preview.png

.. image:: newsletter-outlook.png

Page Lifecycle Improvements
-----------------------------------------

It is now possible for an editor to hide pages. This can be used to temporary unpublish a page or to prepare a new part of the content structure before it goes live.

.. image:: page-lifecycle-hide.png

When a page is hidden, all sub pages will also be hidden.

.. image:: page-lifecycle-hide-2.png

When a page is hidden, it is not only hidden in navigation, but also when trying to access the page using the full url and/or search.

.. image:: page-lifecycle-hidden-404.png

At any point it is possible for the editor to show a page and all its sub pages again.

.. image:: page-lifecycle-show.png

The Delete page action has been replaced with an Archive page action.

.. image:: page-lifecycle-archive.png

When a page is archived, it is possible to provide a comment on why the page or page should be archived.

.. image:: page-lifecycle-archive-confirmation.png

It is possible to archive a single page, a number of pages, a whole page collection or a page type. All archived objects will end up in the section Archive that can be accessed in the left-hand side menu.

.. image:: page-lifecycle-archive-pages.png

It is possible to restore pages, page collections and pages types from the archive. When an

.. image:: page-lifecycle-archive-restore.png

Text Block Improvements
-----------------------------------------

Tables
*****************************************

A new drop down for table styles is now available in the table toolbar. This makes it possible to select a predefined style for the table based on grayscale or the primary color.

.. image:: rtf-table-styles.png

It is also possible to style a specific cell with a specific background color and border style.

.. image:: rtf-cell-style.png

Media
*****************************************

When adding an image or video in rich text using the media picker, it is now  easier to edit it by selecting the media and use the action buttons on the media.

.. image:: rtf-media-tools.png

By default, the media will use 100% of the text block width, but it is possible to set a fixed width on the media if needed.

.. image:: rtf-media-fixed-width.png

When a fixed width is set, it is possible to align the media in the block and decide how the text should flow together with the media.

.. image:: rtf-media-text-flow.png

Links
*****************************************

This release makes it easier to manage links in rich text. It is possible to select a piece of text and quickly create a new link.

.. image:: rtf-links-add.png

.. image:: rtf-links-add-2.png

Once a link has been added, it is easy to remove or update the link using the action buttons next the link.

.. image:: rtf-links-update.png

Paste
*****************************************

When you copy html from web site or Word or likewise and paste it into a rich text block...

.. image:: rtf-copy-from-web-site.png

.. image:: rtf-keep-text-only.png

...it is now possible to keep the text only.

.. image:: rtf-keep-text-only-2.png

You can also select a portion of the rich text and clear the formatting by clicking on the keep text only action button.

Alignment
*****************************************



.. image:: rtf-text-alignment

Floating Toolbar
*****************************************

.. image:: rtf-floating-toolbar.png

Central Text Styles
*****************************************

.. image:: rtf-text-styles.png

.. image:: rtf-text-styles-2.png


Design Improvements
-----------------------------------------

Page Style
*****************************************

.. image:: designupdates-page-style.png

Card View
*****************************************

.. image:: designupdates-page-cards.png

.. image:: designupdates-people-cards.png

Microsoft Teams Integration
-----------------------------------------

.. image:: teams-start-page.png

.. image:: teams-mobile.png

.. image:: teams-deep-links.png

.. image:: teams-deep-links-2.png

.. image:: teams-provisioning.png

.. image:: teams-teamwork-directory.png

.. image:: teams-create-teamwork.png

.. image:: teams-create-teamwork-2.png

Microsoft Search Integration
-----------------------------------------

.. image:: mssearch-sharepoint-sync.png

.. image:: mssearch-pages-in-result.png


Governance Dashboards
-----------------------------------------

.. image:: governancedashboard-pages.png

.. image:: governancedashboard-waiting-for-approval.png

.. image:: governancedashboard-communities.png

.. image:: governancedashboard-teamwork.png


Omnia Tenant Contacts
-----------------------------------------

,, image:: tenantcontacts.png

Stacked Processes
-----------------------------------------

.. image:: stackedprocesses-step-1.png
.. image:: stackedprocesses-step-2.png


Versions
-----------------------------------------

.. toctree::
   :titlesonly:

   versions


