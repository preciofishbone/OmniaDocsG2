Switch to site selected
==================================

**(This page is just started, will be finfished very soon).**

This information is intended for existing implementations of Omnia. For new implementations, this is not needed.

The new standard way to run Omnia is to have app access to only selected site collections. All new tenants will run in this mode by default. It replaces both the old way (FullControl.All.SiteCollections) and System account mode.

If you're on an existing implementation of Omnia, you can switch to site selected this way:

1. Reconsent the tenant with one of the Core features that requires Sites.Selected Web content management core.

2. Activate the feature **Sites selected permissions** as a site collection admin, on all sites that have specific Omnia functionality:
+ Publishing apps.
+ Communities.
+ Sites with controlled document libraries.
+ Sites with process management authoring.
+ The document management archive site.
+ The default context site.

3. Ensure everything is working.
4. Deactivate the feature **Legacy app permissions**.
5. Get the consent link from Azure AD permissions page in Omnia admin.
6. Consent.

