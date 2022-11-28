Learning Center
===========================================

With Omnia, you can establish a learning center within your intranet.

Start off by watching this `introductory video <https://www.omniaintranet.com/omnia/knowledge/videos/video-omnia-best-practice---learning-center>`_.

Here is a summary of the best practice recommendations:

* Form a strategy for how to develop, provide, and maintain learning resources within the organization.

* Organize your course catalogue in course subjects and course types.

 * Course subjects are familiar topics related to your business, like IT, leadership, products, and sales.
 * Course types can describe whether the course is internal, external or self-service.

Course Subjects and Course Types
---------------------------------------------

1. Go to SharePoint admin center > Content services > Term store.
2. Create a new Term Set called Course Types. Add the following terms and change the sort order accordingly:

  * Internal course
  * Self-service
  * External course

3. Create a new Term Set called Course Subjects. Add the following terms:

  * IT
  * Leadership
  * Products
  * Sales

4. Create a new empty Term Set called Courses.

5. Go to Omnia Admin > Properties > Categories.
6. Create a new category called "Learning". 
7. Go to Omnia Admin > Properties > Enterprise Properties.
8. Create a new property for Course Subject. (Don't forget to make it SharePoint Searchable).

.. image:: best-practice-learning-center-property-coursesubject.png

9. Create a new property for Course Type.

.. image:: best-practice-learning-center-property-coursetype.png

10. Create a new property for Course.

.. image:: best-practice-learning-center-property-course.png

11. Go to Omnia Admin > Properties > Queryable Properties.
12. Add Course Subject, Course Type and Course to Pages.

.. image:: best-practice-learning-center-queryableproperties.png


Page layouts
----------------------------------------------
1. Go to Omnia Admin > Web Content Management > Page Layouts.
2. Create a new page layout for "Internal Course". (It can be based on the news article layout and then customized according to needs.)
    
.. image:: best-practice-pagelayout-course.png

Page Rollup Query (Left-hand side):

.. image:: best-practice-pagelayout-course-pagerollup-left.png

Page Rollup Query (Right-hand side):

Token: {{PublishingApp.PageCollections["course-dates"]}}

.. image:: best-practice-pagelayout-course-pagerollup-right.png

3. Add the properties following properties to the page type "Internal Course".

.. image:: internalcourse-properties.png

.. image:: internalcourse-coursesubject.png

.. image:: internalcourse-pagecontact.png

.. image:: internalcourse-coursetype.png

.. image:: internalcourse-course.png

3. Create a new page layout for a "Micro-course".

.. image:: pagelayout-micro-course.png

Learning Center Publishing App
----------------------------------------------

1. Go to Omnia Admin > [Default Business Profile] > Publishing.
2.  Create a new publishing app for the Learning Center.

.. image:: best-practice-learning-center-create-app.png

3. Go to the newly created publishing app and create a page collection for the start page of the Learning Center.

.. image:: best-practice-learning-center-pagecoll-start.png

4. Set this as the default page collection in the publishin app settings. 

5. Create a flat page collection for courses.

.. image:: best-practice-learning-center-pagecoll-courses.png

6. Create a flat page collection for course dates.
    
.. image:: best-practice-learning-center-pagecoll-coursedates.png

7. Add the tenant page type "Internal Course" to the Courses page collection.
8. Add "Create course" as dialog title and uncheck "Show Url".
9. Enable taxonomy connection and connect the page collection to the term set "Course".
10. Create and publish a first test course in the page collection "Courses".
11. Wait until the search engine has indexed the newly created page (it can take up to 15 minutes.)
12. Go to SharePoint admin center > Search > Manage search schema.
13. Map the following crawled properties and managed properties:

  * OWS_TAXID_LCCOURSESUBJECT > RefinableString90
  * OWS_TAXID_LCCOURSETYPE > RefinableString91
  * OWS_TAXID_LCCOURSE > RefinableString92

14. Go to Omnia Admin > Properties and add the managed properties to the the enterprise properties respectively.