Tokens in Omnia e-mails
=========================

Here you will find a list of all Omnia e-mails and the tokens supported in each e-mail.

(This documentation is just started, more will be added soon).

Announcements e-mails
-------------------------
There are three different e-mails that can be sent, regarding comments to announcements. In all three e-mails, just one token is supported:

+ {{title}}

Sign-off requests
---------------------
In e-mails for sign-off requests the following token is supported in Subject:

+ {{title}}

In the body of the e-mails, the following tokens are supported:

+ {{requestreceiver}}
+ {{requestfrom}}
+ {{requestdescription}}

User Profile Completion
-------------------------
In the User Profile Completion feedback e-mails, the following token is supported in Subject:

+ {{userprofileproperty}}

In the body of the e-mails, this token is supported:

+ {{feedback-email}}

Document Management - Controlled Documents
--------------------------------------------
The following tokens are supported in e-mails regarding Controlled Documents:

In the Review Task e-mails, the following token is supported in Subject:

+ {{DocumentTitle}}

In the body for **Review Task e-mails**, the following tokens are supported in Body:

+ {{Reviewer}}
+ {{Author}}
+ {{DueDate}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{TaskUrl}}
+ {{TaskTitle}}
+ {{Message}}
+ {{*}}

In the **Review Reminder e-mail**, this token is supported in Subject:

+ {{DocumentTitle}}

and these tokens are supported in Body:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{SiteUrl}}
+ {{SiteTitle}}
+ {{PublishDate}}
+ {{ReviewDate}}

In the **Publishing Notification e-mail**, this token is supported in e-mail Title:

+ {{DocumentTitle}}

In the body of that e-mail, the following tokens are supported:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}

If Read Receipt is selected, the body of this e-mail supports these tokens:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{ReadReceiptUrl}}

In the **Send for Approval** e-mails, which is both the e-mails sent to the approver, and the e-mails sent to the author, this token is supported in Subject:

+ {{Name}}

(Name is Document Name).

The folllowing tokens are supported in Body for these e-mails:

+ {{Approver}}
+ {{Author}}
+ {{Name}}
+ {{DueDate}}
+ {{DocumentLink}}
+ {{TaskTitle}}
+ {{StartDate}}
+ {{Message}}
+ {{ApproverComment}}







