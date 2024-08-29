Switch to site selected
==================================

**(This page is just started, will be finfished very soon).**

This information is intended for existing implementations of Omnia. For new implementaitons, this is not needed.

The possibility to have App access to only selected site collections, it's the new standard way to run Omnia. It replaces both the old way (FullControl.All.SiteCollections) and System Account mode.

All new tenants will run in this mode by default. It will be completely removed in the future.

If you're on an existing implementation of Omnia, you can switch to site selected this way:

1. Reconsent the tenant with one of the Core features that requires Sites.Selected Web content management core.
2. Activate the feature **Sites selected permissions** as a site collection admin, on all sites that have specific Omnia functionality:
+ Publishing apps.
+ Communities.
+ Sites with Controlled Document libraries.
+ Sites with Process Management authoring.
+ The Document management archive site.
+ The default context site.

3. Ensure everything is working.
4. Deactivate the feature “**egacy app permissions**.
5. Get the consent link from Azure AD permissions page in Omnia admin.
6. Consent.








