Release 7.0 - Preview
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

Process Management improvements
----------------------------------------


Document Management improvements
----------------------------------------

The Documents Bulk Update feature now includes the ability to find and replace inactive user accounts for employees who have left the company.

.. image:: dm-batchupdate.png

The create document wizard will now display a tooltip for document types that include a description.

.. image:: dm-doctypedescription.png

It is now possible to restore controlled document drafts from the SharePoint recycle bin.

.. image:: dm-restoredrafts.png



Teamwork governance as MS Teams app
----------------------------------------

Improved end user filters
----------------------------------------

Least privilege app permission model
----------------------------------------

Reusable content cross tenants
----------------------------------------

Security-trimmed apps
----------------------------------------

Multi-lingual improvements
----------------------------------------

Versions
-----------------------------------------

.. toctree::
   :titlesonly:

   versions