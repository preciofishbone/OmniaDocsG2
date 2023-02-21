Requests
=============================================

All created requests are listed here. You can filter on "Requested By" and "Progress Status" (In Progress or Completed).

Here's an example of a list from a test environment:

.. image:: sign-off-requests-requests-613-new.png

The "Status" column indicates if the request is open or closed. the "Progress Status" column to the right indicates the number of answers; white for none, yellow for some/ongoing and green for all that the request was sent to.

For more details and the possibiblty to delete a request, click the link (Name).

Create a new request
***********************
To create a new request, do the following:

1. Click the plus.

.. image:: sign-off-requests-click-plus-613-new.png

2. Use the following settings:

.. image:: sign-off-requests-settings-1-613-new.png

+ **Types**: Only available if more than one type has been set up, and is then mandatory. If just one type exists, it's still used (the properties are available) but the "Types" option is not shown here. 

When you have selected Type, some or all of these settings can be available: 

+ **Name**: Add a name for the request here, in any of the tenant languages (click the flag to chance language).
+ **Description**: You can add a description of the request, in any of the tenant languages (click the flag to chance language).
+ **Properties**: The properties available depends on the Type used. The properties are useful for tagging the request. This can then be used as filters for what is to be displayed in a certain Sign-off Requests Rollup block. 
+ **To be signed off**: Here you add the pages that should be signed off, using the Page Picker. If the type was based on a template, the list of pages will most likely be pre populated with a number of pages. You can add or remove pages as needed. See below for more details.
+ **Sign-off Type**: Select how the sign-off request will be handled. If the type is based on a template, Sign-off type, and the following two fields can be pre populated sith siggestions. If you select "Individual", all users added to "Request sent to" will receive a personal request. Everyone has to sign-off individually. If you select "Group", it works as one group request, meaning it's enough that any of the recipients signs-off the request. All other recipients can see that the request was sent to them and can see if someone in the group has signed off, they can see if the task is done or not.
+ **Requested by**: Add one or more users, or groups, that will be shown as the "sender" of this request. Will be shown to the receivers. Your name will most lilkely be pre populated, but it can be removed. This field must always contain at least one person or group. To add several users or a group here can be useful, then all users, or the whole group, will be able to follow up on the request. This field is mandatory.
+ **Request sent to**: Select one or more users or groups to send to. Single users, Security groups and Microsoft 365 groups can be added here (In Omnia on-prem, Microsoft 365 groups can’t be used). This field is mandatory. 

3. Add or remove pages as needed.
4. Add a message for each page, if needed (for more information, see below).
5. Click REQUEST to save the Sign-off request and send it. If you don't, nothing is saved.

To add or remove pages
----------------------------
Here's how to add or remove pages for a Sign-off Request. 

If you use a template, this list can be pre populated, for example:

.. image:: sign-off-requests-settings-2-613-new.png

By clicking the pen, you can add a message for each page, if needed (not mandatory), in any or all tenant languages. As always, click the flag to change language. Here's an example:

.. image:: sign-off-requests-settings-2-613-message.png

To remove a page from the list, click the dust bin (this does not affect the template). To add additional pages, click the plus.

.. image:: sign-off-requests-settings-2-613-clickplus-new.png

The following is shown:

.. image:: sign-off-requests-settings-3-613-new.png

If you select "Current Page" the actual page where the sign-off request is placed can be signed off, wherever that is.

When you select "Specific Page", continue like this:

1. Navigate and Pick (Browse) or Search for pages, the same way as in the Page Picker (it's a part of the Page Picker that is used here). See this page for more information: :doc:`The Page Picker </general-assets/page-picker/index>`

2. Click ADD when you have selected one or more pages to add to the Sign-off Request.

.. image:: sign-off-requests-settings-3-613-pages-add.png

The selected pages are now added to the list of pages, see above.

3. Continue this way until you have added all pages that should be signed off.

Checking up on a request
*************************
You can check up on a Sign-off request to see what has happened.

1. Click the link (Name) for the request.

Something like the following is shown, example from a test environment:

.. image:: sign-off-requests-checking-1-613-new.png

Here you can see, for example, the status and the number of recipients that has completed the request. If a message has been added to any of the pages, you can also see the messages here (not present in this example).

For more information, you can click "Download Details" to download an Excel file.

Additionally, you can send a reminder to all participants.

Close or delete a request
****************************
You can close a request that should no longer be active. You can delete a request no longer needed.

.. image:: sign-off-requests-checking-1a-613-new.png

When you close a request, you can choose to send an email notification to the users that has not completed the request:

.. image:: sign-off-requests-checking-2-613.png

Just deselect if you don't need to send a message, and then click CLOSE REQUEST. If you choose to send a message, it's sent immediately.

Note that it's just a notification e-mail that is sent from the system. You can't add any text to that message (no dialog for that purpose is available).

A closed request can be reopened, a deleted request can (of course) not.

Sign-off Requests Rollup block
*********************************
There's a block available to be used for listing the Sign-off Requests that is sent to the logged in user or a group that the user belongs to.

More information about the block is found here: :doc:`Sign-off Requests Rollup </blocks/sign-off-request/index>`

