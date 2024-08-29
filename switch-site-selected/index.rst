Switch to site selected
==================================

**(This page is just started, will be finfished very soon).**

This information is intended for existing implementations of Omnia. For new implementaitons, this is not needed.

The possibility to have App access to only selected site collections.
This is the new standard way to run Omnia.
It replaces both the old way (FullControl.All.SiteCollections) and System Account mode.
All new tenants will run in this mode by default.
No new tenants should be allowed to use system account mode, it will be completely removed in the future.
 
1.Reconsent the tenant with one of the Core features that requires Sites.Selected
1.Web content management core.
2.Activate the feature “Sites selected permissions” as a site collection admin, on all sites that have specific Omnia functionality.
1.Publishing apps.
2.Communities.
3.Sites with Controlled Document libraries.
4.Sites with Process Management authoring.
5.The Document management archive site.
6.The default context site.
 
3.Ensure everything is working
4.Deactivate the feature “Legacy app permissions”
5.Get the consent link from Azure AD permissions page in Omnia admin
6.Consent
7.Win!
 









