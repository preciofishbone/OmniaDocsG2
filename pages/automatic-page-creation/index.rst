Automatic Page Creation
=========================

**This page is being updated. Will be finsihes soon**.

An administrator can setup rules in a Page Collection for automatic page creation.

It works this way: Whenever a page is published in the Page Collection and match a specific rule, a copy of the page will be published to another Page Collection in the tenant. To be more specific; it is the information contained in the properties that are copied, not the whole page as it is. Therefore the page in the target Page Collection can look different depending on available Page Types. 

This can for example be used to make sure a specific type of news will be published in more than one News Center, for example both in the internal News Center and in a partner portal or a customer portal. But this is just one example, it can be used with any type of page.

**A tip!** If you want to make sure the copied page looks the same in the target Page Collection - use the same Tenant Page Type in both source and target Page Collections. You can find more information about Tenant Page Types on this page: :doc:`Tenant Page Types </admin-settings/tenant-settings/webcontent-managament/page-types/index>`

**Note!** You should not use this option for Events.

Settings
*********
The settings are available here, in the Page Collection Settings:

.. image:: automatic-page-1.png

Click the plus and the following settings becomes available:

.. image:: automatic-page-2.png

(Not all options are shown in the image, but are listed below.)

+ **Name**: Add name for the rule.
+ **Page Creation Rule**: If pages in this Page Collection always should be copied, select "Always Create". If pages should be copied only when certain prerequisites are met, select "Only Create If". See below for more information about this.
+ **Page Creation Info**: Select the Publishing, App, Page Collection to copy to, and choose the Page Type to be used.
+ **Enable Auto Publish**: If this option is selected a new page is always published automatically. It’s only applicable when a new page is created, not when it’s updated.
+ **Initial Properties**: Choose the source of the initial properties; "Enable Resuse Conten" or "Copy property to page on creation". Then select the propertie(s) to get this from. For more information, see below.
+ **Mapped Variations**: If the source page and/or the target page uses variations, you have to map variations, see below.

Don't forget to save when you're done.

When editing a Automatic Page Creation rule, all settings described above are available.

Setuo for Reusable content
------------------------------
When you activate Reusable Content, select a property that should have a Reusable content connection in the target page, and click ADD.

Add all Reusable content properties this way.

Here's an example:

.. image:: automatic-page-reusable-example.png

To remove a property from the list, click the dust bin.

Mapped variations
-------------------
Here's an example of mapping you have to do:

.. image:: automatic-page-mapped.png

In this example, the target Page Collection has two variations set up. You have to map variations from the source page to the two variations in the target page. If there are more (possible) variations for the source page, it does not matter. In this example there are four (possible) variations for the source page, and some of them are the same as for the target page. The mapping can then look like this:

.. image:: automatic-page-mapped-example-1.png

Here's another example where a variation for the target page does not exist for the source page. You could then map this way:

.. image:: automatic-page-mapped-example-2.png

Only Create If
---------------
When you select this option, the following is shown:

.. image:: automatic-page-3.png

Click ADD to set the first rule. The first step, when creating a rule, is to select a property.

.. image:: automatic-page-4.png

Here's a very simple example. Pages should only be copied if they are created by Anna Karlsson:

.. image:: automatic-page-example.png

If needed, click ADD again and set the next rule. 

Note that, in case you set up several rules here, all rules must be met for a copy to be created. It's an AND relation between rules. If it is possible to select multiple values for a property within a rule, it's an OR relation between values. 

