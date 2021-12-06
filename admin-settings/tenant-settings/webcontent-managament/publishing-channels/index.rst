Publishing Channels
===========================

**This is a preliminary documentation of new functionality to come in Omnia 6.7.**

Publishing Channels provide an alternative way of targeting information and place pages in context.

If you enable Publishing Channels on a Page Collection, it will be possible for an author to set which channels the page should be published to. Normally approval by the Administrator of the channel is needed for publication, but publishers can be defined for a channel and they don't need approval when publishing.

Publishing Channels can be used in page rollups to show news articles and pages in different parts of the intranet. The end user can also subscribe to channels of interest. 

Here, you administer the channels.

.. image:: channels-list.png

Click the pen to edit a channel, the dust bin to delete it. When you edit a channel, all settings used when creating a new channel can be edited, see below.

Create a new channel
**********************
Here's how to create a new channel:

1. Click the plus.

.. image:: channels-clickplus.png

2. Use the following settings:

.. image:: channels-settings-new.png

+ **Title**: Add a title in any or several of the tenant langauges. Click the flag to change language.
+ **Description**: Add a description of the purpose of the channel in any or several of the tenant langauges. Click the flag to change language.
+ **Url**: 
+ **ADD IMAGE**: To add an image to be shown for the channel, click here and use the Media Picker to upload the image. When an image is selected you delete it or edit it by clicking the pen. For more information about the Media Picker, see: :doc:`The Media Picker </general-assets/media-picker/index>`
+ **Owner**: One or more owners of the channel must be added. This is just information about who is responsible. The name/names will be shown when channels are listed.
+ **Administrator**: One or more administrators of the channel must be added. Administrators approve or reject publication to the channel. An administrator also has Publisher permissions to the channel.
+ **Publisher**: One or more publishers can be added. This is not mandatory. The colleagues you add here can publish to the channel without approval.
+ **Targeting filter**: This is a bit different compared to targeting elsewhere in Omnia. Targeting for the channel can be used to add a mandatory subscription to the channel for colleagues or groups.

3. Save when you're done.

Approve or reject publication
*******************************
If you're Administrator of a channel, you can approve or reject publication of pages to that channel, but note that any colleague added as "publisher" for the channel, can publish directly, without approval.

If one or more requests for publication are created, the number of request are shown in this column:

.. image:: channels-request.png

To approve or reject:

1. Click on the number of pages for a channel, to start the process.

The requests for that channel are then listed, for example:

.. image:: channels-requests-listed.png

2. Click the link for a page you want to check. The page is opened in a new tab.
3. Go back to the list and select APPROVE or REJECT.

An e-mail is sent to the requester with information about the result.