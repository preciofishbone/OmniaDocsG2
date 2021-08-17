Custom Email Service
=======================

Use these settings to decide if e-mails should be sent from Omnia or not.

.. image:: custom-email-settings.png

+ **Enable Email Service**: If this option is enabled AND an account is added to the field, Microsoft Graph is used as e-mail service. The sender address will be the one shown under the field (admin@adventrixgroup.onmicrosoft.com in this example). SharePoint is used if no account is registered. If this option is disabled, no e-mails are sent from Omnia at all.

When enabling this, best practice is to setup a dedicated account. Omnia will then send e-mails using this dedicated user account via Microsoft Graph.

**Note:** The selected user account need to have a cloud Exchange mailbox.