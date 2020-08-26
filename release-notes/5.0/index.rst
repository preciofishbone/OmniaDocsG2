Release 5 (DRAFT)
========================================
*NOTE: Items might be added, altered or removed.*

Newsletter
----------------------------------------
You can setup a Page Collection to allow for pages to be sent out as e-mail.

.. image:: newsletter-settings.png


This makes it possible to create an archive for Newsletters.




MS Teams apps single sign on
----------------------------------------
A new app consent is needed to allow Microsoft Teams Single sign on. It contains the following added permissions:

- offline_access	Delegated	Maintain access to data you have given it access to

- openid			Delegated	Sign users in

- profile			Delegated	View users' basic profile


New SharePoint file structure
-----------------------------------------
- The file structure of SharePoint data has been remade to be more logical and human readable.
- The SharePoint site pages can now be configured to contain Title, Summary, Content, Image.
*NOTE: If search rules have been setup based on path, these must be updated to match the new content structure*


New Page lifecycle
----------------------------------------
The old recycle bin has been replaced with a proper page lifecycle.

- The "Advanced" page creation mode no longer exists (#117182). 

Also fixes (#114801, #120924, #115549).




MS Teams Apps and Deep links
----------------------------------------
- New Query strings for showing/hiding the Tenant and Business Profile header. (#119541)

Design updates
----------------------------------------
Many new style options have been added to the page editor.


Rich text editor improvements
----------------------------------------
The rich text editors have received many updates

Tables
****************************************
- Tables can now be created and designed directly in the RTF editor. (#115412)

Other enhancements
****************************************
- Floating toolbar; The most common settings of the RTF editor are now available as a floating toolbar close to the cursor. This greatly improves the experience when working with long texts.
- Improved link handling; Links can now be added to existing text, existing links can now be edited when selected.
- Update media; Media (Images and video) can now be edited in the RTF content. (#113395, #120160).
- Paste without formatting; The RTF editor can now clean formatting when pasting content. (#114917)
- Styling of bullet lists (#115411, #117579, #118512).
- Multiple line breaks now render correctly (#119841).

Also fixes: (#116523, #117674, #117680, #120177, #120284, #115453, #115539)

Settings
****************************************
- Styles can now be globally defined to be used for all text fields in Omnia. This allows the administrator to create headings directly in omnia without need for any custom development. (#114817).

Dashboards and KPIs
----------------------------------------
- A new block has been introduced, allowing you to setup statistics dashboards to view the usage of your Omnia digital workplace.

Admin Release Information
----------------------------------------
- Customer contact information has now been surfaced to the UI.


Release 5.0.0
========================================

Enhancements and Fixes
------------------------------------

Omnia
***********************
**Enhancements**

- Added "normal" Spanish (Espa�ol) as a selectable language. 
- Better handling when saving a list of permissions with some invalid selections (#117350).
- Icon set "Fabric" has been renamed to "Microsoft" for easier understanding (#114041).

**Fixes**
- Correct issues with showing profile images in some components (#116587).

Web Content Management
***********************

**Enhancements**

- Version history UI updated when there are many versions (#121377).
- Redirect links now work for users who have not yet logged in.
- Export to excel of the usage report now work better with more than 5000 pages (#120247).
- Fixed an issue with resolving the "Everyone except external users" group in some tenants when creating new publishing apps (#121380).
- Corrected a link formatting issue in notification emails from new comments (#121438).
- When adding a new block, the cursor is now automatically focused in the search box for the blocks (#116574).
- Updates to the link picker to select "Automatic" as the default link selection (#117244).
- Move block action now has a new icon (#115387).
- Its now possible to reorder the exiting content in the accordion (#116623).

**Fixes**

 - Corrected the date formatting in the schedule page dialog (#116811).
 - Fixed an issue causing the RSS notification count to not show until selected (#114774).
 - Empty banners no longer takes any space (#114714, #115854).


Document Management
***********************

**Fixes**
- Fixed an issue where the "Create draft" and "Unpublish" buttons would not show up in the document rollup (#118540).
- Corrected the date format in the publish dialog (#1150589).

Tenant Administration
***********************

Team Collaboration
***********************

Workplace
***********************
- People rollup have been reworked, with new design options and features (#120973, #114014).

**Fixes**
- The announcement comments feed now take all available screen space (#117248).
- Corrected an issue where the header toolbar would show the wrong icons  (#117530).
- Corrected the style of the User Profile Completion Wizard in SPFx (#114438).

Communities
***********************
**Enhancements**

- The "My Subscriptions" button now have links to the individual pages the user subscribes to (#121151).

Process Management
***********************
- Processes can now be shown in a TeamSite.






