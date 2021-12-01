Targeting Properties
===========================

Here you define which Properties to use for Targeting. 

.. image:: targeting-properties-v6.png

The Properties must be added to Enterprise Properties to be able to be selected here, as well as be of the type "Taxonomy".

**Note!** Term sets to be used as properties for targeting in Omnia, must be set to "Available for tagging" in Sharepoint.

**Note!** In Omnia on-prem, it's possible to target using SharePoint User Profile and Windows Active Directory group membership only. 

Add a Target Property
***************************
To add a Target Property definition, click the plus:

.. image:: targeting-properties-click-plus-v6.png

Use the following settings:

.. image:: targeting-properties-settings-v6.png

+ **Title**: Add the Title to be shown for editors, for the Property, when targeting.
+ **Property**: Select Tenant Property from the list.
+ **Type**: Select Type of targeting for this Property; Group Membership, User Profile Property or Azure AD Property. When "User Profile Property" or Azure AD Property is selected, choose Property from the list shown.

Map Group Membership
************************
When "Group Membership" is selected, this link is shown:

.. image:: targeting-properties-settings-map-v6.png

When you click the link, settings according to the property you have selected is shown. Here's an example of possible mappings for "Job Role":

.. image:: targeting-properties-settings-map-v6-group.png

What you do here is to map the properties shown to the left, to groups that exits in your tenant.

1. Click the property you want to link.
2. Select a group ine the list by searching (type beginning of a group and see what pops up).

.. image:: targeting-properties-settings-map-v6-group-list.png

3. Save when you're done.

Delete or edit Target Property
**********************************
To delete a Target Property, click the dust bin, to edit it, click the pen:

.. image:: targeting-properties-delete-edit-v6.png

All settings used when creating a Targeting Property can be edited, see above.
