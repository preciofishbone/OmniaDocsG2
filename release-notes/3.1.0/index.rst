Release Notes 3.1.0
========================================

New features
----------------------------------------
- Omnia Feed is now supported.

Developer changes
---------------------------------------
In an effort to reduce the Omnia AzureADs app permissions impact, the feature activations and app instance provisioning will now by default run in the current user context, not the application context. 

To run in the app context this needs to be explicitly set when triggering the feature activation or app instance provisioning.

Enhancements and Fixes
------------------------------------

Omnia
***********************
- Ensured targeting cache for user profiles is never longer than 30 minutes.
- Fixed a problem that would invalidate all users security sesseion when read permissions change
- 

Web Content Management
***********************
- Fixed table layout so edit mode matches read mode in all scenarios
- 


Document Management
***********************

People and Networking
***********************


