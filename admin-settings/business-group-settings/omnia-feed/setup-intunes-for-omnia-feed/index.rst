Setup Intune for Omnia Feed
=============================================

**This page is just started. Please come back in i few days.**

This document is a guideline for setting up Intune for the Omnia Feed App.

.. image:: intune-omnia-1.png

The "Omnia Feed 2" App (ab4ee7fd-4aa2-494b-82a2-fe16b8f2c3ff) must have the permission "Microsoft Mobile Application Management".

.. image:: intune-omnia-2.png 

+ Setup Intune for the Tenant.
+ Set up Microsoft Intune | Microsoft Learn.
+ Before continuing, ensure the folllowing configuration is done in Intune: Config Apple enrollment, Android enrollment.

Create App Protection Policies
*************************************
In this step, setup an app protection policy for the Omnia Feed App. It should be done for both Android and iOS.

1. Follow the instructions in this Microsoft document: https://docs.microsoft.com/en-us/mem/intune/apps/app-protection-policies#app-protection-policies-for-iosipados-and-android-apps
2. Go to Microsoft Endpoint Manager : https://endpoint.microsoft.com/
3. In the menu, select “Apps” => “App protection policies”.

.. image:: intune-omnia-3.png 

4. Create policy for Android or iOS => Add a title for the policy => Go to the second screen, config “Apps” => “Select custom apps”.

.. image:: intune-omnia-4.png

5. In the popup shown => Add the “Package Id” => Then click on the "Add" button.
6. Add: Android: se.precio.news and iOS: se.preciofishbone.omniafeed

.. image:: intune-omnia-5.png
 
7. Select the custom added app.

.. image:: intune-omnia-5.png
 
Then you will see the custom app in the list of apps.

8. Then go through the next setup steps.

Notice in step 6 “Assignments” you will need to configure a deploy group for it to work.

9. Then create the policy.

.. image:: intune-omnia-6.png

10. Verify that policy is deployed
 
After config policy it can take some time to affect.
If app have Intune SDK and setup app protection correctly first time open app will show this screen like below

2. Setup Conditional Access
*****************************
Follow Microsoft document: https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/concept-conditional-access-policies

Go to https://portal.azure.com => search for “Conditional Access” => 
 
Go to Conditional Access service, now you can see list of already setup policies. You can verify it or create new policy for Omnia Feed. 
 
Create new Conditional Access policy
 
Set Assignments to users or group to apply
 

Set Cloud Apps => Omnia Feed 2
 
You also want to select App “Office 365” it may block user of some Microsoft Apps (optional)
 
Config Conditional to focus on platforms Android, iOS since Omnia Feed App only support that 2 platforms.
In Client App section select “Browser” “Mobile apps and desktops clients” 

Access controls
Select “Grant”
In here there are 3 main options that Omnia Feed can support
-	Require multifactor authentication => will prompt MFA or some other of second layer protection when user login
-	Require device to be marked as compliant => only allow devices already enroll Intune using Omnia Feed
-	Require app protection policy => need to config App protection policy for Omnia Feed before enable this option 
There is 2 ways to config Mutil controls :
-	Require all the selected controls (AND condition)
-	Require one of the selected controls (OR condition)

After config the Grant section with option you want make sure in Enable policy select “On”
Then create policy. It should take about 1 hour to take effect.
Tips: let try test on some small group users first to make sure the setup is correct and not block users out.

For now there are some limit in Access control for Omnia Feed app:
Both “Require app protection policy” and “Require multi-factor authentication” can not turn on at the same time.
We can config these 2 conditions with multiple controls: ”Require one of the selected controls”
 








