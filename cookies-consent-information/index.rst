Cookies consent information
===============================

Omnia only stores cookies needed for authentication, nothing else. Omnia can't be run without these cookies.

If you need to add cookies consent information, a tip is to use the tutorial for this purpose. 

You should set this tutorial to be available at the start page and to start automatically.

For more information on how to create a tutorial, see: :doc:`Tutorial </admin-settings/tenant-settings/tutorial/index>`

Detailed information on Omnia cookies
****************************************
Heres' a detailed (more technical) description of the cookies used:

+ OmniaTokenKey - Omnia access token to authenticate user.
+ Dynamic request context - This cookie is dynamically created in runtime. It stores all the context values of the current request. It's key is related to the accept header in the request. E.g. If the accept header value in the request is: “application/json, omniarequestctx/6809C0FBF8A434D7601AAA55F6FEBD00”, there will be a cookie with the key “6809C0FBF8A434D7601AAA55F6FEBD00”.
+ SessionCacheState{n} - This cookie is used to ensure that the latest server-side cache is used in all Omnia server instances. Depending on the size of the value, it may be split to multiple cookies (due to the limitation of cookie size). This cookie does not always exist as it is only needed for some specific caching, r.g. SessionCacheState1, essionCacheState2, …
+ OmniaDisableAuthRedirect - This cookie is only used in SPFx to make sure that Omnia does not cause the authentication redirect loop if there are some issues when authenticating the current user with Omnia.
+ TempUniqueName - This cookie stores the current username after onboarding. It is just a temporary cookie and it exists a very short time.
+ Remember-me related cookies: UniqueName: stores the username, LoginType: whether it is an Omnia user login or Entra ID login, OmniaAuthType: Omnia authentication method (password, OTp).

