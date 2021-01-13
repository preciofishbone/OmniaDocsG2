Custom Email Service
=======================

If this setting is disabled, Omnia will use the SharePoint API:s for sending e-mails.

.. image:: custom-email-settings.png

In some scenarios, for example when working with external users or when you want e-mails from Omnia to be sent from a specific e-mail address, you can enable this setting.

Enabling this allows you to select a user account. Best practice is to setup a dedicated account. Omnia will then send e-mails using this dedicated user account via the Exchange API:s.

**Note:** The selected user account need to have a cloud Exchange mailbox.