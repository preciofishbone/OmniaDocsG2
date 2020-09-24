Azure AD Synchronization settings
===================================

Use these advanced settings to make sure person properties are synchronized from Azure AD to Sharepoint.   

This is what's available:

.. image:: azure-ad-overview.png

+ **SYNCHRONIZE NOW**: Click this button to execute the syncrhonizations set up (listed at the bottom). If you select "Enable Azure AD Synchronization" and set and interval, you don't have to click this button. The synchronization is then executed with the interval set.
+ **EVENTS**: Click this button to access logs from the synchronizations. 
+ **Log Detail**: Use this if you have problems with the synchronization. In the details you will hopefully find out what's wrong. 
+ **Enable Azure AD Synchronization**: Select this option to enable the synchronization.
+ **Batch Execute**: This is an advanced option if you have a very long list of users - several hundreds and above. Contact you provider/consultant for help when using this.
+ **Batch Number**: When you hav selcected "Batch Execute" you use this field to set the number of users that should be synchronized each time.
+ **Delete log after number of days**: Set the number of days the log file will be available. Default: 14 days.

At the bottom the synchronizations that has been set up are shown. By clicking the pen you can edit the same settings as when the synchronization was set up (see below).

To delete a synchronization from the list, click the dust bin.

Set up a new synchronization
*****************************
To set up a new synchronization, do the following:

1. Click the plus.

.. image:: synchro-click-plus.png

2. Use the following settings:

.. image:: azure-ad-settings.png

+ **Azure AD property**: Open the list and select the AD property to synchronize.
+ **Sharepoint property**: Type the name of the Sharepoint property to synchronize to.
+ **Sync when value is empty**: Normally empty fields are not synchronized from the AD. If you want to do that, select this option.

Here's an example:

.. image:: azure-ad-settings-example.png

3. Save when your finished here.
4. Save your changes in the settings window.

Events
********
In the list each synchronization is described with Type, Status and start- and end time. The top icon for each post will show more details. Here's where you will see detailed log if you selected "Log Details".

.. image:: azure-ad-settings-events.png

