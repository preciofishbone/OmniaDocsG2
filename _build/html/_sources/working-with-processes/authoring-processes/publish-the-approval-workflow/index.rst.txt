Publish - the approval workflow for processes
================================================

**(This documentation is just started, more will be added soon.)

When a process has reached a final version, it must be published, and if approval is activated, be approved for publication, to be available for end users. To do that, you start an Approval Workflow.

All metadata must be properly set before the Approval Workflow is started. Some metadata can be mandatory. If all mandatory metadata has not been added, the Approval Workflow can not be started.

**Note!** Metadata can also have impact on who is available as approver.

Also note that, if it's the first time the process is published, a page needs to be set up, with use of the process blocks, to make it possible for end users to access the process.

To publish a process, do the following:

1. Check that all metadata (Properties) are correct.
2. Select the process.
3. Open the dot menu and select "Publish".

(Image to be added)

Something like the following is shown:

(Image to be added)

Exactly which options are available here depends on a a number of settings. These are the common ones:

+ **Approver**: You select one approver from the list, or accept the suggested. Available approvers depends on various settings and how the system is set up.
+ **Approval Due Date**: Here the author adds a date when the approval should be made, at the latest. This is just information for the approvers. The Approval workflow is not stopped if this date is pased.
+ **Comments**: Use this field for comments about what was edited/added in a new edition. The field is not shown when the first edition is published.
+ **Read rights**: The default selection is to use the Default Readers Group from the site’s permissions. If, for some reason, the Read Rights for this particular document should be different, you can select "Limit Read Access", and enter the names of the readers, or any group memberships, for example AD groups.
+ **Notify people**: You can use this option to notify certain people or groups about the new edition of the document. The notification is sent when the document is approved. You can find more information about notifying people on this page: :doc:`Read and understood - Notify and Read Receipt</working-with-documents-authoring-controlled-documents/read-and-understood/index>`
+ **Require Read Receipt**: When notifying people, you can also select this option for read receipts to be sent to this Controlled Documents library.
+ **Preview process**: Click here to see a preview of how the approver will see the document, converted to PDF or not.

5. Select approver and add a due date.
6. Click "Send".

(Image to be added)

When you click "Send", a task is created for the approver, and an e-mail is sent, with a link to the draft process. The task can look like this:

(Image to be added)
 
The approver automatically has read access to the process (Note! Read access only!), until the task is completed. If a Notification Panel is set up for Tasks, the approver is also notified in the notification panel, about the new task, and can choose to open the task from there. 

The workflow will be active until the task is completed and the process will be locked for editing during that time.

Approved or Rejected
*********************
If the process is approved for publication, it’s now available for readers. You, the author, will receive an e-mail stating that.

If it’s rejected, there’s some changes the approver would like you to do. You will receive an e-mail stating that the process was rejected and a message from the approver. After changes has been made, you start a new Approval Workflow the same way as before.
