Release 7 - Preview
========================================

.. note:: The release notes are currently in preview and may be subject to change at any time.

User Management
----------------------------------------

Omnia now offers the ability to create and manage users within the platform, allowing for seamless user onboarding without requiring a Microsoft 365 license.

.. image:: usermgmt-users.png

In addition to user management, Omnia provides the capability to create and manage security groups that can be utilized to safeguard content and features throughout the platform.

.. image:: usermgmt-groups.png

All users in Omnia will be assigned a user type. Examples of a user type can be Office worker, Production worker, Partner, Customer etc.
Customized user profile cards can be created for each user type, featuring unique sets of properties.

.. image:: usermgmt-usertypes.png

Omnia supports dynamic security groups based on user types. The dynamic security groups will replace and expand on the built-in groups "Internal users" and "External users".

.. image:: usermgmt-dynamicgroups.png

It is possible to create user properties in Omnia. These properties can be shown on the customized user profile cards together with properties from Azure AD and SharePoint.
The user properties in Omnia will also be used to manage targeted mobile push notifications and statistics going forward.

.. image:: usermgmt-userproperties.png

Omnia supports any custom user directory provider to synchronize groups and users into the system. Built-in providers are Microsoft Graph (Azure AD) and Active Directory (On-prem).

.. image:: usermgmt-sync.png

Omnia supports any custom authentication provider to be plugged into the system. Built-in authentication providers are Azure AD, Active Directory (On-prem) and Omnia.
Omnia provides support for a range of authentication options, including passwords, one-time passwords (OTPs), magic links, and combinations of these methods.

.. image:: usermgmt-authentication.png

Media Gallery
----------------------------------------

The media block can be configured to allow multi-select of images and videos. 



Process Management improvements
----------------------------------------

Enhancements have been made to process templates, now encompassing a process layout along with default canvas size and available shapes settings.

.. image:: pm-processlayout.png

.. image:: pm-processlayout-shapes.png

The process editor has undergone a division into two distinct modes, namely Design and Content. In Design mode, you are able to work with the process drawing and the layout.
The layout for each process step can either be inherited from the overall process or customized specifically for that particular step.

.. image:: pm-process-design.png

.. image:: pm-process-design-layout.png

The process drawing tool has been improved:

* Move shapes with keyboard.
* Select multiple shapes.
* Snap to grid when rotating.
* Full support to clone all properties of a shape.
* Option to determine the priority of layers when overlaying shapes on top of one another.
* Input boxes to adjust width and height of a shape.
* Enable image cropping on background image.
* Default canvas size.

.. image:: pm-process-shapes.png


Document Management improvements
----------------------------------------

The Documents Bulk Update feature now includes the ability to find and replace inactive user accounts for employees who have left the company.

.. image:: dm-batchupdate.png

The create document wizard will now display a tooltip for document types that include a description.

.. image:: dm-doctypedescription.png

It is now possible to restore controlled document drafts from the SharePoint recycle bin.

.. image:: dm-restoredrafts.png

Teamwork governance as Microsoft Teams app
------------------------------------------

Teamwork governance can now be deployed as a Microsoft Teams app.

.. image:: msteamsapp-teamworkgovernance.png

Improved end user filters
----------------------------------------

The end user filters for all rollups have undergone significant enhancements.

The refiners section in the settings have been removed and merged into the filters section.
Rollups that support refiners (all rollups based on SharePoint Search) will have a new filter setting
to allow the possiblity to "Show result count".

Least privilege app permission model
----------------------------------------

Omnia now use a least privilege app permission model. Any app permissions required to run Omnia will be consent based on tenant features that are activated.
All application access to SharePoint sites will utilize the SharePoint Site Selected permission model.

Reusable content cross tenants
----------------------------------------

It is now possible to connect one or more tenants together (both on-premise and online) to allow cross tenant publishing.
The automatic page creation feature has been enhanced to allow a page created in one tenant to be automatic published in another tenant.

.. image:: crosstenant-automaticpagecreation.png

Security-trimmed apps
----------------------------------------

All rollups of apps (Publishing, Community, Teamwork) has been enhanced to support security trimming. The security trimming can be configured to be based on five different types of permission:

* Administrator: Administrator of the app, for example a publishing app administrator or an M365 group owner.
* Author: Author role in the app, for example a publishing app editor/author or a controlled documents author.
* Contributor: Contributor role in the app, for example a community member or an M365 group member.
* Reader: Reader role in the app, for example reader in a page collection or SharePoint site reader.
* Viewer: Viewer role in the app, possibility to read meta information about an app and public teamwork information.

.. image:: approllup-securitytrimming.png

Multi-lingual improvements
----------------------------------------

Enhanded multi-lingual support:

* Tenant and Business Profile names.
* Publishing App title and description.
* Navigation node titles.
* Page Types titles.

Versions
-----------------------------------------

.. toctree::
   :titlesonly:

   versions