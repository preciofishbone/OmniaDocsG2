4.0.3
========================================

Fixes 
***********************
- The new datatype "Tags" can now be made searchable in SharePoint.
- Adjustments to page content font sizes.
- Fixed a problem that would sometimes cause the page rollup not to render (#119619).
- Fixed a problem causing display breakpoint settings to become unavailable (#119761).
- Fixes to the new Teamwork navigation migration.
- Fixed a problem where it would not be possible to create a publishing app on the root (#119678).
- Fixed a problem causing the page rollup to not render its selections of page collections (#119547, #119919).
- The SPFx package version number is now updated to reflect the current omnia version. (However, the contents are the same.)
- Advanced search refiners now have the correct alignment.
- Fixed a problem where documents could not be approved when migrated from G1 (#118587, #119733).
- Fixed a problem where the document history would become unavailable on migrated documents (#119631).
- Fixed a problem where default sort order on taxonomy properties would not work correctly in the document rollup.

4.0.8
========================================

Fixes 
***********************
- Fixed an issue that would cause comments to be from the system instead of the user when comment was posted from Omnia Feed.
- ODMDocumentHistory can now better handle invalid data.
- Stability updates for site creation when running tenant in User Account Mode.
- AzureAD Sync now has a setting to write over values in SharePoint profile will null or not (#120090).
- Fixed a permissing issue with review reminder tasks.
- Fixed an issue that cause base definitions to be missing for new tenants (#119864).
- Platform stability updates.
- SVG files can now be correctly used in the media block.

4.0.9
========================================

Fixes 
***********************
- Teamwork sites with error now display in public display listings (#120096, #120127, #120285).
- Fixed an issue that would cause new manifests not to update when installing new extensions. 
- Danish translation updates (#120289).
- Corrected the behavior of the current navigation in a multi publishing app scenario. (#118484).
- People rollup now works correctly in SPFx (#120283).
- Fixed an issue that would cause external links in quick links to open multiple tabs (#120142).
- The MS Teams Icon on the Teamwork listing now works as expected in IE11.