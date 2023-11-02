Using Newsletters
===========================

There's a number of options and settings in Omnia you can use for a newsletter implementation, to send internally or externally through e-mail. These options and settings are described here, together with an implementation example.

For an implementation example, see this page (being updated at the moment): :doc:`Newsletter implementation example </using-newsletters/newsletter-implementation/index>`

A Page Type for Newsletters
*****************************
You will need a Page Type set up for Newsletters. See the implementation example for more information (see link above).

You use the options available in Omnia, see: :doc:`Page Types </pages/page-types/index>`

**Important Note!** When planning a Page Type that will be used as a base to send information in e-mails, be aware that only these three blocks are supported for e-mail send outs:

+ Text.
+ Page Rollup.
+ Media.

Other blocks can of course be used on the page itself, but will then not be present in the e-mails.

Important and useful settings
******************************
To be able to send (Newsletter) pages this setting must be activated for the Page Collection:

.. image:: newsletter-page-collection-setting.png

When this setting is active, the following tab is displayed in the page settings so Newsletter Editors can enter the groups/e-mail adresses to send to:

.. image:: page-setting-newsletter.png

In this field both groups and individual e-mail adresses can be entered. This tab is available for Page Editors, even using Write mode.

Page Rollup block for Newsletters
***********************************
You will need a Page Rollup block on the Newsletter Editor's page. When you set up the Page Rollup, Pick Pages and Pick in Write Mode are useful settings.

.. image:: page-rollup-pick-pages.png

There's also a View called Newsletter. This view is suitable for emailing.

.. image:: page-rollup-newsletter-view.png

More information about the Page Rollup block is found on this page: :doc:`The Page Rollup block </blocks/page-rollup/index>`

