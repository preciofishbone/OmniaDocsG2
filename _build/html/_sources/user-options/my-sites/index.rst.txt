Teamwork Navigation
===========================================

Teamwork Navigation can display links to several types of sites and groups, including Yammer Groups, Facebook Workplace and Microsoft Teams Groups. Settings in Omnia Admin states if Teamwork Navigation should be shown or not in the top menu.

.. image:: my-sites-example-new3.png

Available tabs can be set up in a number of ways. 

The user can follow or unfollow a site by clicking the star. An unfilled star indicates that the site is not followed and a filled star indicates that the user follows the site. 

Two things will happen when a user follows a site:

+ The site may be available as a quick link in the "Following" tab in the My Teams block, if such a tab is set up.
+ Any conversations in the user feed on the site will be available in the user feed on the start page.

If there is a Yammer Group and/or, Facebook Workplave or Teams Group connected to a site, it is indicated by an icon. You can click the icon to go to the Yammer Group, Facebook Workplace or Teams Group.

In the image above you can see the Teams Group icon. Here's an example of a list with four facebook icons and one Yammer icon:

.. image:: teamwork-navigation-icons.png

Create Teamwork
*************************
End users can be allowed to create a new site or group using the option here. Depending on settings, approval can be needed. If it's not needed, the site or group will be created when the user clicks "Create". If approval is needed, a request is sent to an administrator for processing.

Another way users can be allowed to create teamworks, is through the Create App block. See this page for more information: :doc:`The Create App block </blocks/create-app/index>`

What the option is called and which fields and options will be available when creating a teamwork can differ depending on how the Provisioning Template is set up.

Here's an example with some common fields and options:

1. Click "Create Teamwork".

.. image:: click-new-site-new.png

2. Select the site or group to create.

.. image:: select-site-type-new2.png

(What is available in this list depends on templates set up in Omnia Admin.)

This example will create a "Team" site.

3. Select "Team".
4. Set the following:

.. image:: create-site-1-new2.png

+ **Title**: This is the name that will be shown for the site in lists and when searching.
+ **Description**: A Description is not mandatory but is very helpful when colleagues search for sites.
+ **Show in Public Listings**: If this option is available, deselect if the site should not be shown in lists all colleagues has access to.
+ **Sharepoint Alias**: The last part of the address to the site is created automatically but can be edited if necessary. If the name (address) already exists an alternative address is suggested.
+ **Languages**: The same language as the main Business Profile language is suggested. Another language can be selected if needed.  
+ **Time Zones**: Normally the correct Time Zone is already selected. Can be changed if needed.

5. Click "Next".
6. Set the following:

.. image:: create-site-2-new2.png

+ **Enterprise Properties**: Properties has many uses in Omnia. This step can look very different - which properties the user has to fill in is set up in the template for the teamwork. In this example this could be used to set which Office this site will be used for. See for example this page for more information about properties: :doc:`Properties </admin-settings/tenant-settings/properties/index>`

7. As the next, often the last step, site Owners and Members can be added:

.. image:: create-site-2-member.png

There should be at least two owners (administrators) of a Teamwork, but there should normally not be more than a few, as site owners has extensive permissions to the Teamwork's settings.

Members can be added now or later.

And now, this short example is finished. There can be additional parts of the process, depending on how the template is set up.

When all is done:

8. Click "Create".

.. image:: create-site-3new3.png

The "Create" option can also say "Send for approval", depending on what is set up in the template. If the button's label is "Create", the site/group is created when you click the button. If the button's label is "Send for approval", an administrator must approve your request before the site/group can be created. When the administrator has done his or her job, you will be notified.

Templates for teamwork creation
**********************************
How this wizard works and which options and fields will be available depends on the template used. Templates, selected in step 2 above, are set up as Teamwork Templates in Omnia Admin, see: :doc:`Teamwork Templates </admin-settings/business-group-settings/team-collaboration/teamwork-65/templates/index>`

