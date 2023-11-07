Setup Document Management
===========================================

.. note:: In order for Document Management features to appear in the UI, the OmniaManagementSystem extension needs to be installed and the Controlled Documents feature needs to be activated. Please consult with your local partner to set up these prerequisites.

Below you will find the steps needed in order to create a basic setup of Document Management.

Document Types
-------------------------------------------

1. Go to the SharePoint admin center.
2. Click on Content Services > Term store in the left-hand navigation.
3. Make sure to add the Working Languages that you would like to support in the Document Management System. Note! This is a global setting. It will affect all services dependent on the term store.

.. image:: termstore-workinglanguages.png

4. Create a new term set for Document Types.

.. image:: documenttypes.png

5. Go to Omnia Admin > Properties > Enterprise Properties.
6. Find the property Document Type and click on the edit icon.
7. Connect the property to the terms set Document Types and save.

.. image:: documenttypes2.png

.. note:: This activity can't be undone in the UI. If the property needs to be reconnected, a support ticket needs to be submitted.

Document Title
-------------------------------------------

8. Go to SharePoint Admin Center.
9. Click on More features > Search.
10. Click on Manage Search Schema.
11. Filter on “refinablestring50”.

.. image:: refinablestring50.png

12. Edit the managed property and map the following crawled properties.

.. image:: refinablestring50mapping.png

13. Go to Omnia Admin > Properties > Enterprise Properties.
14. Find the property Title and click on the edit icon.
15. Check the SharePoint Searchable checkbox and use RefinableString50 as the default Managed Property and check all search boxes.

.. image:: edittitle-refinablestring50.png

Document Archive
-------------------------------------------

.. note:: If you have Process Management setup, you can ignore step 16 - 17.

16. Go to the Business Profile in which you want to host the central controlled documents archive.
17. Go to Teamwork > Templates and create a new template that can be used for system sites.

.. image:: teamwork-template-add.png

18. Click on Teamwork > Apps and create a new site for the controlled documents archive based on the System Site template.

.. image:: controlleddocuments-archive.png

19. Activate the features Archived Documents and SPFx Infrastructure on the newly created site.
20. Click on Document Management in Omnia Admin and click on Settings.
21. Put in the full URL to the newly created site in the Archive Site Url and save.


Document Authors
-------------------------------------------

22. Go to Omnia Admin > Document Management > Settings.
23. Take a decision on how you want to define controlled documents authors within your solution:

* Document Authors Group: This will create an explicit SharePoint Group on the site that is used as the document authors group.
* Site Owners: You need to have the role of the site owner (or M365 Group owner) to be able to edit controlled documents.
* Site Owners and Members: You need to be at least a site member (or M365 Group member) to be able to edit controlled documents.

24. Check the Approvers Group checkbox if you want to allow sites to have a specific list that can be used to define a group of site specific approvers.

.. image:: settings-provisioning-controlleddocs.png

Basic Document Template
-------------------------------------------

25. Go to Omnia Admin > Document Management > Document Templates.
26. Create a new Document Template for a blank Word document.

.. image:: blank-word-document-template.png

Basic Property Set
--------------------------------------------

27. Go to Omnia Admin > Properties > Enterprise Properties.
28. Create a new person property for Document Owner.

.. image:: add-property-documentowner.png

29. Go to Omnia Admin > Properties > Property Sets.
30. Create a new property set for a basic controlled document.
31. Add the Document Owner property and make it required.

.. image:: controlleddocument-propertyset.png

Basic Document Type
--------------------------------------------

32. Go to Omnia Admin > Document Management > Document Types.
33. Create a first document type that can be used for templates in the system.

.. image:: create-documenttype-general.png

.. image:: create-documenttype-publish.png

.. image:: create-documenttype-review.png

.. image:: create-documenttype-archive.png

First Team Site
--------------------------------------------

.. note:: Make sure you have installed Omnia SPFx Integration using the instruction in Omnia Admin > System > SPFx Instruction.

In order to create a first controlled document that can be indexed by SharePoint Search, we need to create a first site. If you already have existing team sites in your solution that are attached to Omnia, you can use one of those and activate the feature Controlled Documents Library on that site. In this example we will create a new provisioning template for Departments that will activate this feature by default.

34. Go to Omnia Admin and select your default business profile.
35. Click on Teamwork > Templates.
36. Create a new provisioning template for departments.

.. image:: add-provisioningtemplate-department-step1.png

.. image:: add-provisioningtemplate-department-step2.png

.. image:: add-provisioningtemplate-department-step3.png

.. image:: add-provisioningtemplate-department-step4.png

37. Create a new site based on the provisioning template.

.. image:: create-department-step1.png

.. image:: create-department-step2.png

38. Go to the newly created site and click on Controlled Documents in the left-hand navigation
39. Click on Permissions in the right-hand corner of the controlled documents library.

.. image:: controlled-documents-permissions.png

40. Add a default readers group (in this example Everyone except External Users).

.. image:: controlled-documents-permissions2.png


Publish a Controlled Document
--------------------------------------------

41. Create and publish a new controlled document.

.. image:: published-controlleddocument.png

42. Create a draft and publish a new edition. (Note! We do this to be able to crawl a document in the archive as well).

Default Search Properties
--------------------------------------------

Now you will have to wait a few minutes before the controlled document has been indexed by SharePoint Search.

42. Go to SharePoint admin center > More features > Search.
43. Click on Managed Search Schema.
44. Map the following Managed and Crawled Properties. (Note! This is just a recommendation and any refinable managed properties can be used.)

- RefinableString51 > ows_ODMDocId
- RefinableString52 > ows_ODMDocumentType
- RefinableString54 > ows_ODMApprovedBy
- RefinableString55 > ows_ODMContentLanguage
- RefinableString56 > ows_SiteName
- RefinableString57 > ows_SPSiteUrl
- RefinableString59 > ows_q_USER_ODMApprovedBy
- RefinableString60 > ows_taxid_ODMDocumentType

.. image:: search-refinablestrings.png

- RefinableInt30 > ows_ODMDocIdNumber
- RefinableInt31 > ows_ODMEdition

.. image:: search-refinableints.png

- RefinableDate10 > ows_q_DATE_ODMPublished
- RefinableDate11 > ows_q_DATE_ODMApproved
- RefinableDate12 > ows_q_DATE_ODMReviewDate
- RefinableDate13 > ows_q_DATE_ODMPublishedFrom
- RefinableDate14 > ows_q_DATE_ODMPublishedTo

.. image:: search-refinabledates.png

45. Go to Omnia Admin > Properties > Enterprise Properties.
46. Edit and update the search configuration for the following enterprise properties.

.. image:: property-approvedby.png
.. image:: property-documentid.png
.. image:: property-documenttype.png
.. image:: property-edition.png
.. image:: property-published.png
.. image:: property-reviewdate.png

47. Create another draft of a controlled document and publish it. (Note! This is necessary in order for SharePoint Search to map the crawled properties to the managed properties.)

You are now ready to start creating Document Types, Document Templates and add Controlled Documents in Teamwork and Publishing Apps.



 
