Process Types
==================

**(This documentation is just started. More will be added soon.)**

When an author creates a process he or she selects a Process Type. A Process type consists of a Property Set, one or more Process Templates and settings for how publis, review and archive should be handled for the process.

Before you continue here, make sure all Process Templates you will need has been created, see (link to be added).

Also see to that the Property set you need has been created, see (link to be added).

Creating a new Process Type
*****************************
1. Select the top "folder".
2. Click the plus.

(Image to be added)

General
--------
3. Use the following settings:

(Image to add)

+ **Title**: Add a title for the process type, in one or more languages. Default language for the tenant is mandatory.
+ **Property Set**: Select property set from the list. For more information about property sets, see the ink above.
+ **Process Templates**: Select one or more process templates for the process author to choose from.
+ **Default Process Template**: If you selected more than one you can also set which of the process templates that should be pre selected.

4. Save when you're done.

Publish
---------
5. Set how publishing of the process should work.

(Image to add)

+ **Allow Revisions**: Selecting this option you can allow authors to publish a revision of a process, instead of a full edition, for example for correcting typing errors. 
+ **Allow to bypass approval for Revisions**: If this option is active, it's up to the author to decide if approval is needed or not, when publishing a revision. Approval is still needed for publishing a new (full) edition of a process.
+ **Publishing approval**: Select if approval is to be used for this Process Type. If this option is NOT active, a process will be published immediately when an author clicks "Publish". If Publishing Approval is selected, you must also choose how approval will take place:
    - Anyone: The author can select any user of the portal as approver, when the process is published.
    - Limited list of users: Authors can select approvers from a defined list only. You create the list here.

6. Save when you're done.

Review
-------
7. Here you handle settings for feedback and review reminder.

(Image to be added)

+ **Feeback Recipients**: User can normally send feedback for a process. Here you select which role will receive feedback e-mails. Feedback is also available in the Process Library, for all process authors to see.
+ **Review Reminder**: Select this option if a review reminder should be sent for the process. If this option is selected, you must also set the following:
    - Time after publishing: You can set how often a review reminder should be sent, in one of two ways. Here you can set a time span, a number of days, months or years.
    - Property: You can set how often a review reminder should be sent, in one of two ways. Here you can set a property for that purpose, a property a process author will fill in - a specific date or a specific retention date.
    - Term-driven: Authors can select approvers from a defined list only. Which approvers will be available depends on the Properties selected for the process. You select the term(s) here. When you have selected one or more terms you can use the cogwheel to set approvers for individual terms in the set.
    - Based on person property: You select one of the person properties defined, for example Process owner or Approver.
+ **Send reminder in advance**: The reminder can be sent a number of days, months or years before the decided revision date. Set how far in advance it will be sent here.
+ **Review Reminder Recipients**: Select which role will recieve the reminders.
+ **Create Task**: A review reminder is always sent by e-mail. If a task should be created as well, select this option, and the then set the following:
    - (Top list): Use the top list to set which role the task will be created for.
    - Task expire in: Set a number od days, months or years for when the task will expire (the task will still be available, but marked as expired).

8. Save when you're done with the settings here.

Archive
----------
Here you set if archiving should be available for the process. If you select this option, you can enter the url to the archive site to be used, or leave the field empty to use the default archive.

(Image to be added)

If archiving is permitted, a process author can remove a process from the Process Library by archiving it. An archived process can be restired later if needed. 

9. Save when you're done with all settings.

Editing a Process Type
************************
To edit a process type, just click it in the main list. All settings described above can be edited.

(Image to be added)

Syncronising of Process Types
******************************
Process Types are syncronized to term sets. Information about the last syncronization is found by clicking the i icon.

(Image to be added)

The information can look like this:

(Image to be added)
