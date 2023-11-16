Setup Intune for Omnia Feed
=============================================

**This page is just started. Please come back in i few days.**

This document is a guideline for setting up Intune for the Omnia Feed App.

Prerequisite: The "Omnia Feed 2" App (ab4ee7fd-4aa2-494b-82a2-fe16b8f2c3ff) must have the permission "Microsoft Mobile Application Management".


Setup Intune for Tenant (should do by customer) 
Set up Microsoft Intune | Microsoft Learn
Before continuing should ensure config Intune:
-	Config Apple enrollment, Android enrollment

1. Create App Protection Policies
*************************************
Setup app protection policy for Omnia Feed App, should create for both Android and iOS.
Follow Microsoft document : https://docs.microsoft.com/en-us/mem/intune/apps/app-protection-policies#app-protection-policies-for-iosipados-and-android-apps

Go to Microsoft Endpoint Manager : https://endpoint.microsoft.com/
Select in side menu “Apps” => “App protection policies”

Create policy for Android or iOS => put a title for the policy => go to second screen config “Apps” => “select custom apps”

New popup will show => in this popup put in the “Package Id” => Then click on Add button
 Android: se.precio.news
 iOS: se.preciofishbone.omniafeed
 
Select the custom added app 
 
After that you will see the custom app in list app

Then go through next the setup steps.
Notice in step 6 “Assignments” you will need config a deploy group for it to work.
Then create the policy.
Verify that policy is deployed
 
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
 








