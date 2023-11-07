Features - Tenant
=====================

All available Features for the Tenant is listed here and can be activated, deactivated and updated when needed. 

Exactly what is available can differ depending on how the Tenant is set up and the version of Omnia. 

This page describes features available in Omnia 6.13 and earlier. For features in Omnia 7.0 and later, see: :doc:`Features (Tenant) in Omnia v7 </admin-settings/tenant-settings/features-tenant-7/index>`

Add-ons
*********
Here you can activate, remove or upgrade the Omnia Add-ons. 

.. image:: tenant-features-add-ons.png

+ **Processes and Documents integration**: When this feature is activated, authors of controlled documents can suggest documents to be related to a process. Process authors can then decide to add a suggested document to the process, or not. Also note that this feature changes the way a process author works with the Documents list for a process. 
+ **Document Comparison powered by Draftable**: This feature needs a paid subscription with Draftable. When this feature is activated, comparison of documents is extended and improved. Works for documents without having to open them. Works for PDF:s as well. Note that you have to add the Draftable Account information as well, for this to work. That is done under Permissions-Secrets.
+ **Controlled Documents**: Activates the extensive funcionality for working with cxontrolled documents in the tenant.
+ **Info Screen**: Activates functionality for sending selected Omnia pages to general or public screens.
+ **Event Management**: Activates the extensive functionality for Omnia Event Management in the tenant. 
+ **Documents Link Handler**: Activates the link handler functionality for documents. Settings are then available through "Link Handler" under "Settings" for the tenant.
+ **Process Management**: Activates the extensive Omnia Process Management functionality in the tenant.
+ **Rules Link Handler**: Activates the link rules handler functionality. Settings are then available through "Link Handler" under "Settings" for the tenant.
+ **Digital Signage**: Activates the options for digital signage in the the tenant.
+ **Communities**: Activates the extensive functionality for Omnia Communities in the tenant.

For more information, see the links below:

+ :doc:`Working with Documents </working-with-documents/index>` 
+ :doc:`Info Screen </admin-settings/business-group-settings/settings/info-screen/index>`
+ :doc:`Working with Events </working-with-events/index>`
+ :doc:`Working with Processes </working-with-processes/index>`
+ :doc:`Using Communities </using-communities/index>`
+ :doc:`Digital Signage </admin-settings/tenant-settings/settings/digital-signage-613/index>`

Integration
*************
Here's an example of what can be available here:

.. image:: tenant-features-integration.png

+ **Process tasks provider: Microsoft Planner**: Activate this feature to use Microsoft Planner to assign and work with process tasks. Can be used when processes are accessed through Microsoft Teams. If this feature is not activated, tasks for processes is just a simple list. 
+ **Support Kaizala login**: As it states. Was called "Allow mobile login" in earlier Omnia version.
+ **Microsoft Teams presence**: If activated, Teams presence is indicated by all people icons in Omnia (see below).
+ **Yammer posts and comments integration**: There's a lot of integration between Yammer and Omnia that is possible without having to activate this feature, but in order to use the new, improved Yammer integration where a post will be created in the selected Yammer community whenever a new page, matching the selected criteria, is created - this feature must be activated.

When Microsoft Teams presence is active, this type of icon indicates Teams presence:

.. image:: teams-presence.png

In this example the icon indicates that the colleagues are offline at the moment.

For more information on how to set up Yammer in Omnia, see:

:doc:`Setup Yammer in Omnia </setup/setup-yammer-in-omnia/index>` 

System
**********
That following features may be found here:

.. image:: tenant-features-system.png

+ **Email provider - Exchange Online mailbox**: This feature must be activated if custom system email functionality is needed in the tenant. The option was called "Enable Custom System Email" in earlier Omnia version. It's just a relabel, same funcitonality as before.
+ **Web Content Managament file storage**: When activated, the option "Copy documents locally" becomes available in the settings for the Realated Links block. Documents that are locally accessible are versioned together with the page and can be accessed by users without a SharePoint license.
+ **Teamwork provisioning using application context**: If you want users to only be able to create Microsoft 365 Groups through Omnia templates, activate this feature. Note that additional settings needs to be made, to make sure Microsoft 365 Group can not be created any other way. More information can be found on this Microsoft page: https://docs.microsoft.com/en-us/microsoft-365/solutions/manage-creation-of-groups?view=o365-worldwide
+ **Social reactions**: Activate this feature to use the same social reactions functionality in Omnia as in Teams. Note that when activating this feature, the Likes functionality is no longer available in any block, regardless of the "Allow social reactions" is selected or not. Existing likes will be showns as thumbs up when this feature is activated.

Default configuration
******************************
The purpose of these features is to provide a number of Enterprise Properties for an easy starting point, and ready to go app launcher links. You can then edit the properties lists and the app launcher links to your organization's needs. Add the common properties you would like to have in your tenant.

.. image:: tenant-features-default-configuration.png

Note that default properties can not be deleted, but all can be edited. 

For more information on working with properties, see these pages: :doc:`Properties </admin-settings/tenant-settings/properties/index>`

Regarding M365 App Launcher links: Activate this Feature for a number of default links for the App launcher - many of the links that will normally appear in the Microsoft 365 menu. You can then use "Shared links" to edit the links and decide which ones to use. **Note!** Most links here will not be applicable in Omnia on-prem.


