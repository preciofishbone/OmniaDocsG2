Tokens in Omnia e-mails
=========================

Here you will find a list of Omnia e-mails that contain tokens, and the tokens supported in each e-mail. Also note that tokens must not be translated.

(This documentation ongoing, more will be added soon).

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

In the (Document) **Review Task e-mails**, the following token is supported in Subject:

+ {{DocumentTitle}}

In the body, the following tokens are supported:

+ {{Reviewer}}
+ {{Author}}
+ {{DueDate}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{TaskUrl}}
+ {{TaskTitle}}
+ {{Message}}
+ {{*}}

In the (Document) **Review Reminder e-mail**, this token is supported in Subject:

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

In the (Document) **Send for Approval** e-mails, which is both the e-mails sent to the approver, and the e-mails sent to the author, this token is supported in Subject:

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

In the (Document) **Feedback e-mail**, these tokens are supported in the e-mail Titel:

+ {{DocumentName}}
+ {{DocumentId}}

In Body for that e-mail, the following tokens are supported:

+ {{Sender}}
+ {{Feedback}}
+ {{DocumentLink}}

In the **Related Document e-mails**, no token is supported in Subject. The following tokens are supported in Body:

+ {{Recipient}}
+ {{RelatedDocument}}
+ {{Publisher}}
+ {{ControlledDocuments}}

In the **Retention Policy e-mail**, no token are supported in E-mail Title. The following tokens are supported in Body:

+ {{RetentionManager}}
+ {{RetentionDocuments}}

In the **Review Workflow Tasks e-mail**, no token is supported in the e-mail Title. The following tokens are supported in Description:

+ {{Author}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}

E-mails for Processes
------------------------
In the (Process) **Feedback e-mail**, these two tokens are supported in Subject:

+ {{ProcessTitle}}
+ {{ProcessStepId}}

In the Body for this e-mail, these tokens are supported:

+ {{Sender}}
+ {{Feedback}}

In the (Process) **Send for Approval e-mail**, this token is supported in Subject:

+ {{ProcessTitle}}

And these tokens are supported in Body:

+ {{ApproverName}}
+ {{AuthorName}}
+ {{ProcessTitle}}
+ {{DueDate}}
+ {{ProcessLink}}
+ {{TaskLink}}
+ {{TaskTitle}}
+ {{StartDate}}
+ {{Message}}

In the **Cancel Approval e-mail**, this token is supported in Subject:

+ {{ProcessTitle}}

And these two tokens are supported in Body:

+ {{ApproverName}}
+ {{ProcessTitle}}

In the **Complete Approval e-mails** - used for both approval message and rejected message, this token is supported in Subject:

+ {{ProcessTitle}}

The following tokens are supported in Body:

+ {{AuthorName}}
+ {{ProcessTitle}}
+ {{ApproverName}} 
+ {{ApproverComment}}
+ {{AuthorName}}

In the (Process) **Review Reminder email**, this token is supported in Subject:

+ {{ProcessTitle}}

The following tokens are supported in Body:

+ {{Recipient}}
+ {{ProcessLink}}
+ {{ProcessTitle}}
+ {{SiteUrl}}
+ {{SiteTitle}}
+ {{PublishDate}}
+ {{ReviewDate}}

App aproval e-mails
----------------------
In the App approval e-mails (for Communities, Publishing and Teamwork), the following tokens are supported.

In the **App Request Approve e-mail** - sent to the approver, no token is supported in Subject. The following token is supported in Body:

+ {{pendingRequestUrl}}

In the **App Provisioning Complete e-mail** - sent to the requester, no token is supported in Subject. The following tokens are supported in Body:

+ {{userDisplayName}}
+ {{appUrl}}
+ {{title}}

In the **AppRequestRejectedToRequester e-mail** - sent when creation of the community, publishing app or teamwork is rejected, no tokens are supported in Subject. The following tokens are supported in Body:

+ {{UserDisplayName1}}
+ {{rejectedComment}}
+ {{UserDisplayName2}}
+ {{rejectedTime}}

E-mails for Events
-------------------
In the **AddParticipant e-mail**, this token is supported in Subject:

+ {{eventName}}",

and the following tokens supporte in Body:

+ {{eventName}}
+ {{startDate}}

Various e-mails connected to Action Buttons
---------------------------------------------
A number of short e-mails can be sent after Action Butotn Actions. The token {{title}} is supported in Subject in some of these e-mails:

AddComment, BestReplyComment, SubmitFeedback, PublishingApproval (six different e-mails - Approve, Reject, CancelApproval, ScheduleApprove, ScheduleReject, CancelScheduleApproval).


