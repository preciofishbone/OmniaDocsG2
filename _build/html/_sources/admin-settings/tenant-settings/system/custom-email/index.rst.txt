Custom Email Service
=======================

Use these settings to turn off or turn on e-mails from Omnia and to set the account e-mails will be sent from.

.. image:: custom-email-settings.png

+ **Enable Email Service**: If this option is enabled AND an account is added to the field, MS Graph is used to send e-mails from Omnia. The sender address will be the one shown under the field (admin@adventrixgroup.onmicrosoft.com in this example). If this option is enabled and no account is added, e-mails will be sent from team sites, using the site's e-mail adress (Sharepoint's API). If this option is disabled, no emails are sent from Omnia at all.

When enabling this, best practice is to setup a dedicated account. Omnia will then send e-mails using this dedicated user account via MS Graph.

**Note:** The selected user account need to have a cloud Exchange mailbox.