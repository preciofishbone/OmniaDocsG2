Activity Feed
=================

Use this block to show activities for the subscriptions the logged in user has.

Here's an example of an activity feed with the scope set to My Subscriptions:

.. image:: activity-feed-example.png

The icon indicates the type of activity:

.. image:: activity-feed-example-icons.png

There's an additional icon not shown in the image above:

.. image:: activity-feed-example-icons-additional.png

The icon at the bottom, with the arrow pointing down, is the "see more" icon displayed when there are more items to show.

Settings
**********
The following settings are available for the block:

.. image:: activity-feed-settings.png

+ **Title**: You can add a title to be shown in the block. 
+ **Scope**: Select where the activities listed should come from: My Subscritions, the Publishing App or the Page Collection. See more information about the scope below.
+ **Item Limit**: Set the number of items to be shown in the list before a See more icon is shown (see above for an example). Default=10.
+ **Padding**: Set some padding between the block border and the list, if needded.

The tabs Layout and Advanced contains general settings for blocks. For more information see: :doc:`General Block settings </blocks/general-block-settings/index>`

More on Scope
---------------
The Scope setting results in the following:

**My Subscriptions**: All activities for everything the logged in user subscribes to is listed.
**Publishing App**: Lists all pages in the CURRENT publishing app that are either new or have been updated.
**Page Collection**: Lists all pages in the CURRENT page collection that are either new or have been updated.

Regarding what is consider an update on a page - more information about this will added soon.

Generally, a user will never be able to read a page that person does not have access to, even if an activity may be present in the feed, meaning not all activities are security trimmed, but the pages always are. 






