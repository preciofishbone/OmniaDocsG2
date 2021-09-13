Dashboard
===========

This is an ongoing, preliminary documentation for functionality to come in Omnia 6.5.

In omnia 6.5, the dashboard has been moved to Omnia Admin and you can build it to your needs. You set up the Dashboard much like you would do a page type. Most sections and blocks can be used.

.. image:: dashboard-new.png

As you would a page type, the first step is to add the layout, using sections. See this page for more information: :doc:`Working with section and blocks </pages/page-types/working-with-sections-and-blocks/index>`

You then add the blocks you need. All available blocks are listed on this page: :doc:`Blocks </blocks/index>`

The Metrics block (new in Omnia 6.5) can be especially useful: :doc:`The Metrics block </blocks/metrics/index>`

You can also edit some of the metrics settings, in Omnia Admin, see: :doc:`Metric settings </admin-settings/tenant-settings/settings/metrics/index>`

Implementation example
************************

Here's an example of a Dashoboard set up:

.. image:: admin-dashboard-usage.png

Under Usage, information about active readers and active contributors are shown. What should be considered an active reader or an active contributor is defined in the Metrics settings, see link above.

Under Page Status, something like the following is shown:

.. image:: admin-dashboard-page-status.png

What you see in the example is the total status for the tenant. You can choose to see status for just one of the publishing apps and/or just one of the page types.

For Underused Content, something like the following can be shown:

.. image:: admin-dashboard-underused-content.png

What should be considered underused content is defined in the Metrics settings, see link above.

Regarding Reach - a description will be added soon.

.. image:: admin-dashboard-reach.png

For Teamwork, you can see the number of active teamworks and if any has been created this week or this month:

.. image:: admin-dashboard-teamwork.png

Finally, for Communities, the following information is shown:

.. image:: admin-dashboard-communities.png






