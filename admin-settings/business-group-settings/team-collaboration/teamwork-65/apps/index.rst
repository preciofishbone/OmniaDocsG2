Apps for Teamwork
===========================================

This is an ongoing, preliminary documentatin for this functionality in Omnia 6.5.

Apps
*******
Here Teamworks are listed, the "Active" tab as an example:

.. image:: teamwork-65-apps-new.png

Using the list "Inactive" you can handle sites with pending delete.

For Team Sites with "Approval" as Site Creation Mode, you use the "Pending Approval" list to approve or reject creation of a Team Site.

Use the icons this way:

+ The key to edit permissions.
+ The boxes to activate, deactivate and upgrade features.
+ The pen to edit some settings.
+ The dust bin to delete the collaboration site. 

You can use the headings for App Administrator, Provisioning Template and Created Date to sort the list.

You can also search the list.

Pending Approval
*****************
When a user creates a Teamwork site where Approval is needed, an administrator uses this list to approve or reject creation of the site. Here's an example:

.. image:: pending-approval-65.png (image to be added)

Approval (or Rejection) is done this way:

1. Click the link for the site.
2. Check the name, settings and so on for the site.
3. If everything is OK, click "Approve", or if changes are needed, click "Reject".

.. image:: pending-approval-approve-65.png (image to be added)

If you approve the creation of the Teamwork site a message is sent to the person requesting the site, and the site is created.

If you reject, the following is shown:
 
.. image:: pending-approval-reject-65.png (image to be added)

4. Type a message stating what needs to be done for approval, and click "Save" to send the message.

The person requesting the site receives the message and can then start a new Teamwork site creation with your comments in mind. 

**Note!** Requesting a Teamwork Site must always be done from start each time. If rejected, nothing from the request is saved.

Important note about Site Ownership when approving
-----------------------------------------------------
Because of caching issues in Sharepoint, it can take some time, even up to 2 hours after approval, before site ownership will work as intended - as set in the Teamwork Creation Wizard in Omnia. During this time, the Approver will have Owner permissions. 

Orphaned
**********
(This tab works the same way as the tab that was called "Inactive" in Omnia 6.0).

When a site of the type Microsoft 365 Team Site, Sharepoint Team Site or Sharepoint Communication Site is created, a Sharepoint site is created and is connected to the site. A Yammer Group can also need a Sharepoint site, depending on how the Yammer Group is set up.

The connected Sharepoint site may be deleted for some reason, but when that happens the Omnia site may not. When this happens a link to the site is placed in this list, so an administrator can take actions.


