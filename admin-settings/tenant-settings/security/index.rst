Security
===========
The following settings are found here:

.. image:: security-tenant-new.png

Permissions
************
Use this setting to add and remove Tenant Administrators. Only Tenant Administrators can use this setting and other settings under "Tenant" in Omnia Admin. 

A Tenant Administrator can also edit all the settings for all Business Profiles within the Tenant. 

.. image:: tenant-permissions-new.png

To delete an administrator here, just click the x. To add an administrator, add the name the same way as in other name fields.

External users that has been invited in the Asher AD can be added here as well. Users invited this way can log in with their own Microsoft 365 account.

**Note!** There must always be at least one Tenant Administrator. If there is only one, that administrator can not be removed until an additional one has been added.

Secrets
********
The following settings can be available here:

.. image:: tenant-secrets.png

System Account
------------------
System account is a standard extension for specialized implementations only.

.. image:: tenant-secrets-system.png

Azure AD Sync Account
-----------------------
(A description will be added soon.)

.. image:: tenant-secrets-sync.png

Event Management Service Account
----------------------------------

If you will be using Event Management with a connection to calendars in Outlook, here you must add the service account that will be used to read and write from the calendars.

.. image:: tenant-secrets-event.png
