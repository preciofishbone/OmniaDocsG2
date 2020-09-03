System
=============
Here, the following can be set:

.. image:: system-settings-new4.png

Extensions
************
All extensions used in the tenant are listed here, with ID and version installed, for example:

.. image:: system-extensions-new.png

Default SharePoint Context Url
*******************************
Here the Default SharePoint address can be set/edited.

.. image:: system-default-sharepoint.png

Error Information
******************
Use this setting to turn client side error messages on or off (Default=off).

.. image:: system-settings-error.png

SPFx Instruction
*****************
This is an instruction that may be needed for integration between Omnia and Sharepoint Team Sites.

Custom Email Service
*********************
This may be needed for some specialized implementations.

Adit logs
***********
This option logs some important events in Omnia. In this version the following is logged:

+ Any changes of permissions anywhere in Omnia.
+ When this functionality is turned on or off.

The listing can look like this:

.. image:: audit-logs-list.png

+ **Title**: Here you can see a description of what has been changed.
+ **Logged By**: The name of the person that did the change is shown here.
+ **Logged At**: Date and time for when the change was made is shown in this column.

You can filter the list on dates, category and person, by using the fields at the top.

.. image:: audit-logs-list-filter.png

Further information can be accessed through the i-icon:

.. image:: audit-logs-icon.png

Here's an example:

.. image:: audit-logs-icon-example.png

The settings
-------------
You access the setting by clicking the cogwheel.

.. image:: audit-logs-list-settings.png

What you can do in the settings is simply turning Audit logging on or off (which is also logged).

.. image:: audit-logs-list-settings-settings.png

Tenant Contact
***************
It's very important that you add contact information here. This will be the main channel for information from Omnia. You can edit the contact information any time.

.. image:: tenant-contact.png

+ **Main Contacts**: Here you add the main contact person(s) in your organization, for Omnia.
+ **Security**: This will (hopefully) be rarely used. If issues with security should arise, this is the person that will receive that information, to act on it.
+ **Update Notification**: Whenever updates will be executed, or will be available to act on, this contact person(s) will receive a notification when it is executed. Information will of course be available before this so you will be aware of updates som time before they are executed.
+ **Add External Main Contact, Security, Notification Email**: In these fields you can add email adresses to external partners that should recieve the same information.

Don't forget to save when you're done.

Queue logs
***********
Administrators can use this option to troubleshoot issues on site provisioning and other long running operations.

.. image:: queue-logs-1.png

Use the fields at the top to filter the list.

If something went wrong, information about what happened is made available through an i icon.

.. image:: queue-logs-2.png

Click the icon to view the information. Here's an example:

.. image:: queue-logs-3.png