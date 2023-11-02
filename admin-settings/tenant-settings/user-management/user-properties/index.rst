User Properties
=============================================

This option is available in Omnia 7.0 and later.

The properties you want to use when creating Omnia users must be present in this list. These properties can also be shown on the customized user profile cards together with properties from Azure AD and SharePoint. Besides that, they will also be used to manage targeted mobile push notifications and statistics. Also note the comment about GDPR.

A number of default properties are always available. They can not be edited or deleted. If you need additional properties you add them here as described below.

Here's an example of user properties. The ones with a pen and a dust bin are added by an administrator.

.. image:: user-management-properties-new.png

When adding a new property, the following settings are available:

.. image:: user-management-properties-settings-new.png

The list of options at the bottom will differ depending on type of property. For more information, see below.

You can "lock" the settings for a property and then it can't be edited anywhere else but here. If a property is unlocked the settings can be edited in the Property block. Click the icon to lock or unlock.

Setup and Edit can be also be available, as here for SharePoint Term set.

.. image:: user-management-properties-new-variant.png

Display
---------
Display options are present for most property types, except for Process. For most properties you can choose to display label text and label icon.

.. image:: user-management-properties-display.png

Additionally, for type Identity you can choose to display image and name as well.

.. image:: user-management-properties-display-alt.png

Edit
------
These types have Edit options: 

+ HTML - you can choose to display the edit options; Rich Text, Limited Rich Tect or Custom Rich Text.
+ Image - you can set default scaling, decide which crop ratios that should be available and decide to force default scaling.
+ Sharepoint Term Set - you can choose to allow multi value.

Setup
-------
Available for type SharePoint Term Set only. For a property from a Sharepoint term set to work, it must be mapped using the list available under Setup.

Deleting a user property
************************
When you delete a user property from this list, it's moved the property recycle bin, available under the tenant settings Properties, see: :doc:`Property Recycle Bin </admin-settings/tenant-settings/properties/recycle-bin/index>`
