Directory (Teamwork) in Omnia v7
==================================

**This page is under construction.**

Here Teamworks are listed, the "All" tab as an example:

.. image:: teamwork-apps-new-v7.png

On this tab active teamworks, orphaned and inactive are listed, but not teamworks with pending approval. 

Use this icon to close the menu to the left and work in full window mode:

.. image:: teamwork-icon-v7.png

You can click the link to go to a teamwork. You can search for a teamwork and use the headings "Title", "Template", "Created Date" and "Last Activity" to sort the list.

The following actions, using the dot menu to the right, are available for a teamwork (in the All, Orphaned and Inactive lists):

.. image:: teamwork-actions-v7.png

**Note!** To be able to delete a teamwork, you must be App Administrator for the teamwork. Also note that deleting a teamwork from this list does not delete 
the connected Sharepoint site.

For more information, see below.

Create a Teamwork
***********************
To create a Teamwork from here, do the following:

1. Click CREATE NEW.
2. Select "Create New".
3. Select Template. 

Here's an example with a lot of different alternatives. You may not have as many.

.. image:: team-collaboration-template-v7.png

4. Edit the settings.

.. image:: team-collaboration-settings-v7.png

Available settings depends on how the template is set up. All steps in the setup may not be needed for a certain template. Here's a common example:

+ **Title**: Add a Title for the Publishing App.
+ **Description**: Add a Description if needed.
+ **Show in Public Listings**: If a link to the app should be available in public listings (meaning listings in Omnia) select this option. If this option is deselected, the app can only be reached by specific links, for example in a Workspace navigation.
+ **Default View Access/Limit View Acess**: If you select “Limit View Access” you can change view permissions for the app to specific users.
+ **Alias**: The last part of the address to the site is created automatically but can be edited if necessary. If the name (address) already exists an alternative address is suggested.
+ **Languages**: The same language as the main Business Profile language is suggested. Another language can be selected if needed.  
+ **ADD IMAGE**: The editor setting up a Publishing Rollup can choose to show images for the apps, both for List and for Card display. Here you can select an image to be shown there, using the Media Picker. When an image has been selected it can be deleted or edited using the X and the pen that is shown then.

4. Click "Next" and use the following settings:

.. image:: teamwork-settings-v7.png

+ **App Administrators**: The active Administrator (you) is automatically added as App Administrator. Add or delete administrators as needed. There must always be at least one.

5. The Properties step may be very different in different templates, or maybe not neded at all (and is in that case empty). Here's a simple example. Note that a star indicates if the property must be set (Organization in this example).

.. image:: teamwork-settings-property-v7.png

6. Set Owner and also Members, if needed. 

.. image:: team-collaboration-owner-v7.png

There may be teamwork types that don't need these settings. In that case this step is simply empty.

When you click NEXT, a summary is shown, where you can click the pen the edit any of the steps.

7. Click CREATE to create the Teamwork or SEND FOR APPROVAL, depending on how the template has been set up.

.. image:: team-collaboration-create-v7.png

Attach a Teamwork Site
************************
Using this option you can attach any Teamwork Site to Omnia. When a Teamwork Site is attached you can handle the site through Omnia the same way as a site created through Omnia.

The following permissions are required to be able to attach a site:

+ For an Omnia Teamwork app: App Administrator permissions.
+ For a Sharepoint site: Site Collection Administrator permissions.

Do the following to attach a site:

1. Copy the Url for the Sharepoint site for the Teamwork you want to attach.
2. Go to Team Collaboration settings and click the plus.
3. Select "Attach Site".

.. image:: attach-site-612.png

The following is shown:

.. image:: team-collaboration-attach-612.png

3. Paste the Url and click "Resolve".

You can "detach" (delete) a site if needed. Then the following permissions are needed:

+ For an Omnia Teamwork app: App Administrator permissions.
+ For a Sharepoint site: Site Owner or Site Collection Administrator permissions.

**Note!** What actually happens when you click the dust bin to delete a site, is that the site is detached. That is true for all Teamwork sites, regardless of if they have been created in or attached to Omnia.

**Note!** When a site is detached, an e-mail is sent to the site owner(s).

Edit App Route
----------------
If it should be needed to edit the App Route, click the icon and the following is shown:

.. image:: teamwork-apps-app-route-community-612.png

Edit the app route and save.

Edit Permissions
-----------------
If you need to add or remove owners (administrator) or members for a Teamwork, you do it here:

.. image:: teamwork-app-premissions-612-new-frame.png

Don't forget to save when you're done.

Edit Features
---------------
If it's needed to upgrade a feature for the Teamwork, you need to go here. You also go here to activate or remove a feature. Available features can differ a lot depending on typoer of app. Here's an example:

.. image:: teamwork-app-features-612.png

Edit App Instance
---------------------
If it should be needed to edit the App Instance, click the icon and the following is shown:

.. image:: teamwork-apps-app-instance-612-url.png

Use the ADD IMAGE button to add an image for use in rollups. You can also edit Title, Description, Public Listing setting and edit the Sharepoint Url, if needed. SharePoint Url is not aplicable for all types of teamwork.  

Pending Approval
*****************
When a user creates a Teamwork where Approval is needed, an administrator uses this list to approve or reject. Here's an example:

.. image:: pending-approval-612.png

Approval (or Rejection) is done this way:

1. Click the link for the Teamwork.
2. Check the name, settings and so on.
3. If everything is OK, click "Approve", or if changes are needed, click "Reject".

.. image:: pending-approval-approve-612.png

If you approve the creation of the Teamwork a message is sent to the person requesting it, and the Teamwork is created.

If you reject, the following is shown:
 
.. image:: pending-approval-reject-612.png

4. Type a message stating what needs to be done for approval, and click "Save" to send the message.

The person requesting the Teamwork receives the message and can then start a new Teamwork creation with your comments in mind. 

**Note!** Requesting a Teamwork must always be done from start each time. If rejected, nothing from the request is saved.

Orphaned
**********
When a site of the type Microsoft 365 Team Site, Sharepoint Team Site or Sharepoint Communication Site is created, a Sharepoint site is created and is connected to the site. A Yammer Group can also need a Sharepoint site, depending on how the Yammer Group is set up.

The connected Sharepoint site may be deleted for some reason, but when that happens the Omnia site may not. When this happens a link to the site is placed in this list, so an administrator can take actions.

Inactive
***********
A teamwork is considered inactive if Last Activity, as registered in the Sharepoint site, is more than three months old.

Here's an exampl from a test environment:

.. image:: teamwork-apps-inactive-612.png

Here administrators can check/edit the settings for the teamworks and delete a teamwork that is not needed. The list can be sorted by "Created Date" or "Last Activity", to for example see if any activity has taken place at all.

Click SYNCHRONIZE LAST ACTIVITY to update the list with the latest activities. The list is not updated automatically. Note that if there are a huge number of teamworks in your solution, the update can take some time.

Click the pen to check the settings for a teamwork. All settings can then be checked an edited:

.. image:: teamwork-apps-inactive-edit-612.png

To delete a teamwork, click the dust bin. Then this is shown:

.. image:: teamwork-apps-inactive-edit-ok.png

**Important Note!** When you click OK here the delete is final. There's no way to retrieve a deleted teamwork.


