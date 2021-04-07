Mapping a user profile property
=====================================

**(This will be checked against Omnia v6 soon.)**

This is how it works in Omnia versions prior to v6:

In order to map an Omnia property to a user profile property, we need to first find the user profile property in sharepoint. In order to do that, lets look at this example:

Here we will try mapping the property Department:

.. image:: userprofile.png

In order to access this view, follow these steps:

1. Visit the sharepoint admin center by typing in https://((insert the name of your tenant)-admin.sharepoint.com 
2. Click on user profiles in the left menu.
3. Click on Manager user profiles.
4. Type in the name of the user you wish to inspect.

In order for a user profile property to be used in omnia, it has to be mapped first, and in order for it to be mapped, we need to know the name of the property, which can be found in search:

.. image:: search.png

We then go in to Manage search Schema:

.. image:: sharepoint-managesearch.png

We then type in the name of the property we are looking for, which in this case is Department: 

.. image:: sharepoint-properties-department.png

Here we can see on the left the name of the Managed property is indeed Department, and the crawled properties are People:Department and ows_department.

We also notice that department is of type Text, it is also queryable, retrievable and refinable but not searchable or sortable, which means that when we map it on omnia, it needs to have the same attrbutes if we want it have the same functionality
as it does now. Mapping it looks like the following: 

.. image:: tenant-properties-mapping.png

Department is now a usable property that functions as both a value displayer and a refiner in blocks like People roll up and features like the search.



