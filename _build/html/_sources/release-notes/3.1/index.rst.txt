Release 3.1
========================================

.. toctree::
   :titlesonly:

   3.1.5/index
   3.1.4/index

New features
----------------------------------------
- Omnia Feed is now supported in Omnia for Modern SharePoint Tenants.
- Added the possibility to make the User Profile Completeness dialog never show up automaticially.
- The Page rollup roller view will now correctly show one item. This enables implementers to use pages as banners.

Developer changes
---------------------------------------
In an effort to reduce the Omnia AzureADs app permissions impact, the feature activations and app instance provisioning will now by default run in the current user context, not the application context. 

To run in the app context this needs to be explicitly set when triggering the feature activation or app instance provisioning.

Enhancements and Fixes
------------------------------------

Omnia
***********************
- Ensured targeting cache for user profiles is never longer than 30 minutes.
- Fixed a problem that would invalidate all users security sesseion when read permissions change
- Fixed a problem that prevented the user from entering Omnia Admin on new tenants. 
- Corrected the display of English laguganges in tenant settings.
- Fixed an issue where the Omnia header would show above document previews in SPFx.

Web Content Management
***********************
- Fixed HTML-tables so edit mode matches read mode in all scenarios.
- Fixed a design issue in the notification panel on mobile.
- Fixed the alignment of the editor speed dial button.
- Fixed the text block custom RTF setting.
- Enterprise keywords can now be multivalue.
- Fixed a bug related to the rendering of page statistics.
- Default values now work correctly for person and date fields.
- Fixed a problem where page rollups would not render correctly in SPFx.
- Improved the performance of the Page Rollup roller view.
- Improved the performance of the Central Image Bank.
- Several alignment fixes to buttons and labels.
- Limited permissions on page properties now works as expected.

Workplace
***********************
- Fixed a color theme issue in the advanced search on mobile.
- Several fixes related to Team Collaboration provisioning.
- Fixed My Links to properly support http links.


Document Management
***********************
- ODM Preview now works as expected.
- Fixed a problem where the document info dialog would not render on the first click in the document rollup.
- Corrected a bug where emails would sometimes be sent with the wrong localization.
- Fixed a problem where the Ok button would not always show up on the read receipt page.


People and Networking
***********************
- Fixed a problem where the search box would not display in the people rollup.

