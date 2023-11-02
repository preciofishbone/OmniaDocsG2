Publishing App settings
=======================================

A number of Publishing App settings are available. You have to be Publishing App administrator to use them.

Open the Publishing App settings by clicking here:

.. image:: page-settings-612.png

General 
*********
The following settings are available here:

.. image:: page-settings-general-612.png

+ **Title**: Add the title to be displayed for the publishing app here. 
+ **Description**: Add a description if you wish (recommended).
+ **Authors**: Add general authors for pages in the publishing app. Can be edited for specific pages if needed.
+ (Image): You use the Media Picker to add or change the image. For more information on how to use this asset, see: :doc:`Media Picker </general-assets/media-picker/index>`

Permissions
************
Use these settings to Edit permissions in the Publishing App. 

.. image:: page-settings-permissions-612-new.png

+ **Allow Mobile Login**: This setting is intended to offer login to certain parts of Omnia for first line workers, partners and similar. The user needs the Kaizala app and a viable account. If you see the label "Kaizala login" somewhere, it's the same thing. **Note!** Mobile Login/Kaizala login is not available in Omnia on-prem.
+ **Administrators**: Add and remove Publishing App administrators here as needed.
+ **Contributors**: This permissions settings is needed if colleagues should be able to add comments to pages.
+ **Resource Readers**: Here you set the general Read permission for the Publishing App, needed for users to be able to read pages.

Single users, Security groups and Microsoft 365 groups can be added here (In Omnia on-prem, Microsoft 365 groups can't be used).

Note that this permissions setting is valid for these settings only. To be able to edit Publishing App settings in Omnia Admin you need to be either a tenant administrator or administrator for the Business Profile.

Regarding these settings a tenant administrator and business profile administrator can go here and add him or herself to the permissions list and that way gain access to the settings.

Variations
************
Here you set up the Page Variations that should be possible to use in the Publishing App. It's then up to Page Editors to use a variation, or not, for a page. A page variation is created for a page when it's needed.

A variation can also be set up for Automatic Machine Translation, see below. (Not available in Omnia on-prem).

It's also possible to add one variation author for each variation. Here's an example with a number of variations set up:

.. image:: page-settings-variations-612.png

You see the variations that has been set up so far, with information about for example targeting. A "Variaton" in the tenant's default language is also listed here - note the label "Default" in the image above. For all pages, a variation with the default language must always exist. That is what is added when a page is created the first time.

To edit the settings for a variation, click the pen. To delete a variation, click the dust bin.

.. image:: page-settings-variations-edit-delete-612.png

When you edit a variation, the same settings as when you create a new variation are available, see below.

Create a new variation
-----------------------
Note that you can use Variations for a lot of implementations, not just languages, even if language versions of a page probably is the most common.

Do the following to create a new variation (you have to scroll down to the end of the list):

1. Click ADD VARIATION.

.. image:: click-add-variation-612.png

2. Use the following settings:

.. image:: variations-612.png

+ **Title**: Add a title for the variation to be shown in the lists, for example the list where users can select variation. If needed, the title can be added in any or all of the languages set up in the tenant. Click the flag to change language.
+ **Icon Type**: If you want show an icon for the variation, select Icon Type here, for excample "Flags".
+ **Icon**: Shown when you have selected Icon Type. Select the icon here.
+ **Url Segment**: Add a suitable Url Segment in this field.
+ **Variation author**: You can add a variation author for this variation. See this page for more information: :doc:`Edit Page Variations </pages/edit-page-variations/index>`
+ **Automatic Machine Translation**: You can select machine translation for this variation, to any language that is set up in the tenant. If you do, you can't select a Variation author, and the machine translated variation can not be edited manually. When you have selected this option, choose language in the list shown. Automatic Machine Translation is executed when the page is published. It will be noted on the variation page that it has been machine translated, see below. **Note!** Machine translation is not available in Omnia on-prem.
+ **Right to left**: If you're creating a variation for a language that is read right to left, select this option.
+ **Add Targeting Filter**: To set up targeting for this variation, click here. It is not mandatory. See below for more information.

Languages used for Titles, or for targering, must be set up in the Tenant Settings, see this page: :doc:`Regional Settings </admin-settings/tenant-settings/settings/regional-settings/index>`

Targeting a Page Variation
----------------------------
Use targeting for a variation to set which variation of a page that will be displayed to the logged in user. Note that if a Variation Selector block is added to a page, users can always select any of the available variations. This is true even if no targeting is set up. See this page for information about the Variation Selector block: :doc:`Variation Selector </blocks/variation-selector/index>`

**Note!** The Targeting Properties to use must be set up in Omnia Admin. See this page for more information: :doc:`Targeting Properties </admin-settings/tenant-settings/properties/targeting-properties>`

To target a Page Variation, do the following: 

1. Click "Add Targeting Filter" when editing a Page Variation's settings.

.. image:: page-variation-add-targeting-612.png

2. Select Targeting Property from the list. 
3. If there are children in the property -as the next step you can select to include all Children, or you can target one or more of the Children specifically. 

Here's an example which will see to that all users that has Danish set as preferred language will see the Danish variation of the page.

.. image:: page-targeting-danish.png

4. Click "OK" to save your changes.

You can add as many Targeting Properties for a Variation as is needed this way (and remember that variations can be a lot more than just languages). To remove a target, just click the X.

Note that the targeting settings also are shown in the Variations list, for example:

.. image:: page-variation-example-612.png

Edit contents of a Page Variation
--------------------------------------
When more than one variation of the page exists, an editor can select variation to work with in the list, in the lower left corner:

.. image:: select-variation-new4.png

If no variation exists yet for the page, the editor can select to create one.

.. image:: variation-create-page-new2.png

Editing a Page Variation works exactly the same way as editing the default page.

Statistics
*************
For more advanced statistics in Omnia, this is the place to add the scripts you get from your statistics provider, for example: 

.. image:: page-settings-statistics-612.png

Don't forget to save. The "Save" button is located in the lower right corner.

Retention
***********
Here you can edit the settings for automatic termination, for the pages in this app that has been archived. 

.. image:: page-settings-retention-612.png

Advanced
**********
Here you can edit these settings:

.. image:: page-settings-advanced-612-1.png

and these:

.. image:: page-settings-advanced-612-2.png

+ **Default Page Collection**: The default Page Collection for the page can be set here.
+ **Allow reuse content**: If it should be allowed to resuse content within the Publisging App, activate "Enable Reuse Content". For more information about how to reuse content, see: :doc:`Reusable Content </pages/reusable-content/index>`
+ **Connected SharePoint Site**: The address to the SharePoint Site is shown here.
+ **Editor navigation**: Here you can add options that should be available in the page menu, in additional to the default options. For more information, see below.
+ **Contact Property**: Select the property used to store information about the user being page contact.
+ **Review Date Property**: Select the property used to store information about review date for pages.
+ **Promoted tags**: A publishing app can be configured to have promoted tags/terms for certain properties. Promoted tags/terms will be displayed at the top of the tag/term picker both for the author, when working with pages, and for the end user when filtering in a page rollup.
+ **Document Management**: You use this part for Dcouments settings, both for "normal documents" and for controlled documents. For more information, see below.

For more information about layouts for publishing, see this page: :doc:`Publishing Layouts </admin-settings/business-group-settings/publishing-apps/publishing-65/layout/index>`

Editor Navigation
--------------------
Use this setting to add options to the page menu, if nedded. On example is to add an option to make it poosible to work with controlled documents in a publishing app.

Prerequisit: A publishing layout for the option to be used must have been created in Omnia Admin. For more information about how to work with publishing layouts, see: :doc:`Publishing Layouts </admin-settings/business-group-settings/publishing-apps/publishing-65/layoutindex>`

Here's how to add a menu option:

1. Click the plus to the right of "Editor Navigation".
2. Use the following settings:

.. image:: editor-navigation-settings.png

+ **Layout**: Select layout here.
+ **Title**: Add a title in any or several of the tenant languages. Click the flag to change language.
+ **Icon Type/Icon**: Add an icon if you wish by first selecting icon type.

3. Click OK when you're done.

.. image:: editor-navigation-settings-ok.png

4. Save the changes to the publishing app settings.

.. image:: editor-navigation-settings-save.png

The new option is now added to the menu, for example:

.. image:: editor-navigation-settings-added.png

To edit a menu option, click the pen, to delete it, click the dust bin.

.. image:: editor-navigation-settings-editdelete.png

Document Management settings
-----------------------------------
The following settings are available here (example from an existing site):

.. image:: document-management-settings.png

+ **Document picker categories**: If the document picker categories that are set up in Omnia Admin should be available here, select this option.
+ **Sharepoint document library**: If the documents created here should be saved in a specific SharePoint document library, enter the address to the library here.
+ **Allow User Upload Document**: Available when a document library has been defined here. Editors and authors can normally upload documents here. If this should be possible for all users, select this option.
+ **File storage**: Select the option if a copy of a docment an editor or author uploads, should be saved locally. The document is then saved in Omnia, not in SharePoint. This is useful if a specific version of a document should be saved with the page, for example a news page. 


