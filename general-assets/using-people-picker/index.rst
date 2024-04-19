Using the people picker
=============================================

The people picker, sometimes called the identity picker, is used in many places in Omnia. 

To use it, just click in the search field and start typing. Here' an example:

.. image:: people-picker.png

Normally, single users, security groups and Microsoft 365 groups can be added here (In Omnia on-prem, Microsoft 365 groups can’t be used). There are a few excepetions where only single users can be added.

External users that has been invited in the Azure AD can be added here as well. Users invited this way can log in with their own Microsoft 365 account. 

Note that to be available in the people picker, users and groups may have to be imported the correct way from Entra ID (formely called Azure Active Directory).

Also note that if the picker is used in a permission context, people and groups must by permissions enabled to show up in the list. Likewise, if the picker is used in a context where Email is used, people and groups must be Email enabled to show up in the list.

If you just want to search for a specific user type or a specific group type, click here to filter:

.. image:: people-picker-example-filter1.png

What you can filter on depends on settings in Omnia Admin. Here's an example:

.. image:: people-picker-example-filter2.png

If you happen to select a user or a group by mistake, just click the x to remove.

.. image:: people-picker-remove.png

More information for administrators: :doc:`Synchronization (User management) </admin-settings/tenant-settings/user-management/synchronization/index>`

