Setup Yammer in Omnia
=======================

Follow these steps to setup Yammer in Omnia Online.

(We are still working this guide - as is quite obvious - it will be edited soon).

**1**. The account used to create the Yammer App needs to be at least Verified Admin in Yammer (Network Admin level is not enough), or alternatively Global Administrator in Microsoft 365. We recommend using a non-personal service account for creating the Yammer App, as the app stops working if the account used to create the app is deleted.

**2**. Navigate to the following URL (replace m365x249588 with your tenant), as the new Yammer does not have a direct link to client applications.

https://www.yammer.com/m365x249588.onmicrosoft.com/client_applications

**3**. Create the Yammer App.

.. image:: yammer-1.png

**4**. After creating the new app, click the link to generate the app token.

.. image:: yammer-2.png

**5**. Go to Network admin -> security settings to enable Office 365 Identity Enforcement. We need it to yammer group auto create sharepoint site shen yammer group created

(Image to be added)
	 
**6**. Setup Yammer group template in omnia. Add above yammer app -> client id  to yammer group template as below

(Image to be added)

**7**. Setup omnia secret key at business profile scope the same with that provisioning template. Add above yammer app token to secret key as below.

(Image to be added)
 
**8**. Finally create app provisioning from yammer group template.

Example my result when done create yammer group name like nhanyamer8
 
(Image to be added)

And sp site:

(Image to be added)






