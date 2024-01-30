Users
=============================================

This pages describes the options in Omnia 7.0 and 7.1. For information on the options for Omnia 7.5, see this page: :doc:`Users in Omnia 7.5 </admin-settings/tenant-settings/user-management/users-75/index>`

Two lists are available here; ALL USERS and DELETED USERS.

.. image:: user-management-users-list-new.png

All users
************
In the ALL USERS list, all users in the tenant are listed. Here you can add Omnia users - users that does not require a Microsoft 365 licence, and delete users you have added this way.

Note that you can use the search field to find a user and filter the list on "User type" and "Provider". If you would like to list Omnia users created here, select "Omnia" for "Provider".

.. image:: user-management-users-list-omnia-new.png

A few settings are available for Omnia users; use the pen to edit user type, the key for authentication settings (see below) and the dust bin to delete the user.

.. image:: user-management-users-list-omnia-options-new.png

Using the pen, all settings for user (see below), except authentication settings, can be edited.

To edit authentication settings, click the key, and the following is available:

.. image:: user-management-users-list-omnia-options-key.png

Save the changes when you're finished.

If you need to reinitiate the whole onboarding process for the user, click RESET ACCOUNT.

About limitations for Omnia users
-----------------------------------
As mentioned, Omnia users does not require a Microsoft 365 licence, and that means no options that are depending on SharePoint or Microsoft 365 can be used. That includes, for example; Teams functionality, Teamworks, Document management, Process management and search.  

When creating pages, or rather page templates, that will be used by Omnia users, it's important to consider which blocks to use. No block that depends on SharePoint works for these users, at least not as intended, including rollups.

All other aspects regarding pages works well for Omnia users, but keep in mind that permissions must be handled through Omnia groups or Dynamic groups for these users.

Add a new Omnia user
-----------------------------
To add a new user, click the ADD USER button.

.. image:: user-management-users-add-button-new.png

Available fields are the properties set up under the option in the User management menu. Here's an example:

.. image:: user-management-users-settings-1.png

and these:

.. image:: user-management-users-settings-2.png

The following options are always available:

+ **User type**: Select user type in the list. User types that should be available here must be set up using the option in the User management menu.
+ **ADD IMAGE**: To add an image of the user, click here and use the media picker to find the image.
+ **Account enabled**: When this user should be activated, select this option.
+ **Authentication information**: Add an authentication Email. This is mandatory. If needed, enter a  phone number for mobile authentication.
+ **Send on-boarding link by Email to user**: You can chosse to send an on-boarding Email to the user by selecting this option. The Email is sent when the user is saved.

Delete a user
--------------
To delete one or more Omnia users, do the following:

1. Select the user/users.
2. Click the DELETE USER button that has become available, or click the dust bin for a single user.

.. image:: user-management-users-delete-new.png

The DELETED USERS list
***********************
You can use this list to restore deleted Omnia users or delete users permanently. To restore or pemanently delete a single user, use the buttons at the right of the user's row.

.. image:: user-management-users-delete-buttons-new.png

To restore or permanently delete a number of users, select them first and use the buttons at the top:

.. image:: user-management-users-delete-buttons-top-new.png

