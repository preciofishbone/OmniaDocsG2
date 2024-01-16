Client security and recommendations
====================================

This option was previously called Big Picture.

About setting up Info screen
************************************

Since InfosScreen can be seen as an only-display extension, meaning that it does not require much or any user interaction once its setup, therefore we recommend a few ways to set it up:

Operating system level Kiosk mode (recommended)
---------------------------------------------------
Kiosk mode, that is also called Assigned access, is a mode that comes with windows, and that allows the user to configure an account that is only allowed to use a specific software without access to anything else, like the start menu or the task manager for example, and forces the app to be in full screen mode. This way when a person uses the computer that is logged in to the kiosk account, the person can only access the specified app. In this case the app will be Microsoft Edge that will run InfosScreen.

1. In order to setup kiosk mode, you need to be logged in as an administrator, and you need to setup a new user account. This can be simply done by creating a new user in Settings > Accounts > Other people > Add someone else to this PC. Note that the account does not have to be a Microsoft account, it can also be a local account with a password. Make sure to name the account Kiosk.

2. Once that is done, open up Windows Powershell. Make sure to right click and run it as administrator:

.. image:: power.png

3. Type in the exact sentence following sentence: 

.. code-block :: powershell

    Set-AssignedAccess -AppUserModelId Microsoft.MicrosoftEdge_8wekyb3d8bbwe!MicrosoftEdge -UserName Kiosk

In case of an error, make sure to check the spelling of the sentence above, as the spelling and even the amount of spaces between each word has to be exact.

Now that kiosk mode is up and running, it can be used by logging into the Kiosk user account which will automatically launch Microsoft Edge.

Things to keep in mind
-------------------------
- The browser should have the startpage set to the page of Info screen. Using the query string fullscreen=true (For example https://tenant.sharepoint.com?fullscreen=true#/start/big-picture) will cause Info screen to go into full screen mode automatically. This will enable the computer to be rebooted but still end up on the correct page and put the browser in the correct mode.

+ Some TV's might have settings to go into sleep mode or turn off when there is no activity. Make sure to check the TV for such configuration.
+ Make sure to change the computer's settings for when to go into sleep mode or shutdown after no activity to "never".
+ Windows auto-update can cause the devices that are running Info Screen to automatically restart. This should be disabled on the devices that will run Info Screen. The instructions on how to disable it can be found here https://www.windowscentral.com/how-stop-updates-installing-automatically-windows-10

**Note** In order to remove the kiosk account, go to Settings > Accounts > Other people > Click on the Kiosk Account then remove:

.. image:: kiosk-remove.png

Alternative: Browser-level kiosk mode (not recommended)
-----------------------------------------------------------
Browsers, such as Google Chrome, offer a browser level kiosk, in which the browser will be entered into full screen mode and give a similar look to that of Operating System kiosk mode. 

The main perk with this feature is that it is much easier to setup and get started with than operating system level kiosk mode. The reason this is not recommended is because the user can exit this mode in multiple ways and gain full access to the device. Therefore it makes it a non secure
method to use in public spaces where non-personal can access the device.

Physical security
**********************
Physical security is something to be considered when the companies requires the device to be physically protected.

In many cases, the device that is connected to the display, will also be connected to the non-public internet. Therefore an intrusion can cause sensitive data leaks or even damage

We recommend that the device itself should be locked in a safe or a locker that is only accessable by staff members, and is connected to the monitor that displays big screen wirelessly. this can be done through chromecast, or if its a smart tv, then the computer can connect to it using bluetooth.
Make sure to lock the screen after activating Info Screen for an extra secure usage. 

Network security
*********************
Network security is something to be considered, since the device that is a publicl display will be connected to the company network. Therefore we advice to a create a separate wifi-network for the the device or devices that will be running Info Screen. This network should have the properties of a guest network, but be password protected so that only the machines that are running Info Screen can access it.

Another alternative is to use a dedicated network, that is completly seperate from the company network for this device. Such options can be purchased at service-providers and often comes in the form of a USB stick or router that will be connected to the device running Info Screen.

Additional security
**********************
To run Info Screen, a normal user account that can login to O365 and Omnia is needed. This account should have a minimal amount of permissions. For Info Screen to work, the account needs the following permissions:

+ Access to the page where the Info Screen Glue control is placed.
+ Access to any data it will show (The news center for example).
+ Access to the Glue site system page (The welcome page of the Glue site called Omnia.aspx).
