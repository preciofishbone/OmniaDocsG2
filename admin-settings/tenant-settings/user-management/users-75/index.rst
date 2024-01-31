Users in Omnia 7.5
=============================================

**Work on this page is ongoing. More information will be added soon.**

This pages describes the tenant options for Users in Omnia 7.5. For information on the options for Omnia 7.0 and 7.1, see this page: :doc:`Users in Omnia 7.0 and 7.1 </admin-settings/tenant-settings/user-management/users/index>`

Also note that in Omnia 7.5 options for User management are available in each business profile, see: :doc:`Users management options for business profiles </admin-settings/business-group-settings/user-management-bp/index>`

Three lists are available here; ALL USERS, DELETED USERS and PENDING APPROVAL. Youcan list users from all business profiles here.

.. image:: user-management-users-list-75.png

All users
************
In the ALL USERS list, all users in the tenant are listed. Here you can add Omnia users - users that does not require a Microsoft 365 licence, and delete users you have added this way.

Note that you can use the search field to find a user and use the filters for a shorter list (see more info about this below). 

If you would like to list Omnia users created here, select "Omnia" for "Provider".

.. image:: user-management-users-list-omnia-75.png

A few settings are available for Omnia users; use the pen to edit user type, the key for authentication settings (see below) and the dust bin to delete the user.

.. image:: user-management-users-list-omnia-options-75.png

Using the pen, all settings for user (see below), except authentication settings, can be edited.

To edit authentication settings, click the key, and the following is available:

.. image:: user-management-users-list-omnia-options-key-75.png

Save the changes when you're finished.

If you need to reinitiate the whole onboarding process for the user, click RESET ACCOUNT. You can alos enable or disable an Omnia user account from here.

**A note for users of earlier Omnia versions**: The general settings for authentication has been move to business profile settings. See this page for more information: :doc:`User management settings - business profile </admin-settings/business-group-settings/user-management-bp/index>`

Filters for the All users list
---------------------------------
The following filters are available, to display only some users in the list:

+ **Time-limited**: For users accounts with a limited time, you can choose to list active or not active accounts.
+ **Status**: Here you can choose to list enabled or disabled accounts.
+ **User type**: Using this filter you can choose to list just one of registrered user types.
+ **Provider**: You can choose to list just one of the providers, usually Microsoft Graph or Omnia.
+ **Owner**: Here you can choose to list users from just one of the business profiles in the tenant.

About limitations for Omnia users
-----------------------------------
As mentioned, Omnia users does not require a Microsoft 365 licence, and that means no options that are depending on SharePoint or Microsoft 365 can be used. That includes, for example; Teams functionality, Teamworks, Document management, Process management and search.  

When creating pages, or rather page templates, that will be used by Omnia users, it's important to consider which blocks to use. No block that depends on SharePoint works for these users, at least not as intended, including rollups.

All other aspects regarding pages works well for Omnia users, but keep in mind that permissions must be handled through Omnia groups or Dynamic groups for these users.

Add a new Omnia user
-----------------------------
To add a new user, click the ADD USER button.

Available fields are the properties set up under the option in the User management menu. Here's an example:

.. image:: user-management-users-settings-1-75.png

The following options are always available:

+ **User type**: Select user type in the list. User types that should be available here must be set up using the option in the User management menu.
+ **Authentication information**: Add an authentication Email. This is mandatory. If needed, enter a  phone number for mobile authentication.
+ **Time-limited account**: if this user account should be active for a specific time period only, select this option and set the start and ned date.
+ **Send on-boarding link by Email to user**: You can chosse to send an on-boarding Email to the user by selecting this option. The Email is sent when the user is saved.

Note that you can enable, disable or reset an Omnia user account using the authentication settings (the key), see above.

Bulk create users
-------------------
By clicking BULK CREATE USERS you can onboard a number of users. Here's the settings you can use:

.. image:: user-management-users-settings-1-75.png

(A description will be added soon).

Delete an Omnia user
-------------------------
To delete one or more Omnia users, do the following:

1. Select the user/users.
2. Click the DELETE USER button that has become available, or click the dust bin for a single user.

.. image:: user-management-users-delete-75.png

The Deleted users list
***********************
You can use this list to restore deleted Omnia users or delete users permanently (Purge). To restore or pemanently delete a single user, use the buttons at the right of the user's row.

.. image:: user-management-users-delete-buttons-75.png

To restore or permanently delete a number of users, select them first and use the buttons at the top:

.. image:: user-management-users-delete-buttons-top-75.png

The Pending approval list
----------------------------
If any user is not onboarded yet, that can be dome using this list:

.. image:: user-management-users-pending.png

Click the pen for available actions:

.. image:: user-management-users-pending-actions.png

and these:

.. image:: user-management-users-pending-actions-more.png

More information about how to use this will be added soon.

