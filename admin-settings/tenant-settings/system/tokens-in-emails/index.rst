Tokens in Omnia e-mails
=========================

Here you will find a list of Omnia e-mails that contain tokens, and the tokens supported in each e-mail. Also note that tokens must not be translated.

(This documentation ongoing, more will be added soon).

**Note!** In some files Subject is called "EmailTitle" and Body can be called "Decsription". In this document Subject and Body are always used.

Announcements e-mails
-------------------------
There are three different e-mails that can be sent, regarding comments to announcements. In all three e-mails, just one token is supported in Subject:

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

**Review Task e-mails**:
In these e-mails for Document Management, the following token is supported in Subject:

In **ReviewerEmailSubjectTemplate** and **CancelSubjectTemplate**:

+ {{DocumentTitle}}

(In ReviewEndNotifyEmailSubjectTemplate no token is supported).

In the body, the following tokens are supported:

In **ReviewerEmailBodyTemplate**:

+ {{Reviewer}}
+ {{Author}}
+ {{DueDate}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{TaskUrl}}
+ {{TaskTitle}}
+ {{Message}}

In **ReviewEndNotifyEmailBodyTemplate**:

+ {{Author}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}

In **CancelBodyTemplate**:

+ {{Reviewer}}
+ {{DocumentTitle}}

In **ReviewerCompleteInfo** and **ReviewerIncompleteInfo**:

+ {{*}}

**Review Reminder e-mail**:
In this e-mail for Document Management, this token is supported in Subject:

+ {{DocumentTitle}}

and these tokens are supported in Body:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{SiteUrl}}
+ {{SiteTitle}}
+ {{PublishDate}}
+ {{ReviewDate}}

**Publishing Notification e-mail**:
In this Document Management e-mail, this token is supported in Subject:

+ {{DocumentTitle}}

In the body of **EmailBodyTemplate**, the following tokens are supported:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}

If Read Receipt is selected **EmailBodyWithReadReceiptTemplate**, these tokens are supported:

+ {{Recipient}}
+ {{DocumentUrl}}
+ {{DocumentTitle}}
+ {{ReadReceiptUrl}}

 **Send for Approval e-mails**:
In these Document Managment e-mails, this token is supported in Subject (in **EmailSubjectTemplate**, **SubjectApproval**, **SubjectReject** and **CancelSubjectTemplate**):

+ {{Name}}

The folllowing tokens are supported in Body for these e-mails:

In **EmailBodyTemplate**:

+ {{Approver}}
+ {{Author}}
+ {{Name}}
+ {{DueDate}}
+ {{DocumentLink}}
+ {{TaskTitle}}

In **ApprovalEditionCommentTemplate**:

+ {{Author}}
+ {{StartDate}}
+ {{Message}}

In **BodyApproval** and in **BodyReject**:

+ {{Author}}
+ {{Name}}
+ {{Approver}}
+ {{ApproverComment}}

In **BodyApprovalNoComment**:

+ {{Author}}
+ {{Name}}
+ {{Approver}}

In **CancelBodyTemplate**: 

+ {{Approver}}
+ {{Name}}

**Feedback e-mail**:
In this Document Management e-mail, these tokens are supported in Subject:

+ {{DocumentName}}
+ {{DocumentId}}

In Body for that e-mail, the following tokens are supported:

+ {{Sender}}
+ {{Feedback}}
+ {{DocumentLink}}

**Related Document e-mails**:
Here, no tokens are supported in Subject. The following tokens are supported in Body:

+ {{Recipient}}
+ {{RelatedDocument}}
+ {{Publisher}}
+ {{ControlledDocuments}}

**Retention Policy e-mail**:
In this e-mail, no tokens are supported in Subject. The following tokens are supported in Body:

+ {{RetentionManager}}
+ {{RetentionDocuments}}

**Review Workflow Tasks e-mail**:
In these Document Management e-mails, no tokens are supported in Subject. The following tokens are supported in Body:

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


