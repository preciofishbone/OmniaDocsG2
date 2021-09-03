Metrics block
================

In omnia 6.5, the Dashoboard is moved to Omnia Admin, see: :doc:`Dashboard in Omnia 6.5 </admin-settings/tenant-settings/dashboard/index>`

You can use this block to display status for either Teamwork, Pages or User Activity. (And you can use it when you set up the Dashboard).

The following settings are available:

.. image:: metrics-block-settings.png

General
********
Here you can add a title for the block and set some padding:

.. image:: metrics-block-settings-general.png

Scope
******
Here you decide what to display in the block:

.. image:: metrics-block-settings-scope.png

You can select Teamwork, Pages or User Activity. Then some settings becomes available, depending on what you have selected.

+ **Teamwork Template**: Select what kind of Teamwork, based on template, that will be shown. If you leave this field empty, all teamworks will be shown. Available for Teamwork only.
+ **Publishing Apps**: You can select one publishing app to show metrics for. If you don't, all Publishing Apps will be shown. Available for Pages only.
+ **Page Types**: You can select one page type to show metrics for. If you don't, all page types will be shown. Available for Pages only.

Metrics
*********
The following settings are available here:

.. image:: metrics-block-settings-metrics.png

+ **Metrics per row**: Set the number of metrics to be shown per row.
+ **Metric block height**: Use the slider to set the height of the block.

In the field at the bottom you can select just some of the metrics to be shown. The options are different depending on the Scope chosen. You can for example choose to show only active teamworks or only new teamworks, ot both, for Teamwork. For Pages you can, for example, decide to show just pages waiting for approval, or just pages that has underused content, among other settings. For User Activity you can select to show the number of active readers or the number of active contributors.

To show several metrics on a page (for example the Dashboard) just add the block several times, with different settings.

Filter UI
************
You can also add filters so users can decide what they will see, within the scope and metrics you have decided.

.. image:: metrics-block-settings-filter.png

+ **Max filters per row**: Set the number of filters per row here.

In the field at the bottom you can choose what filters to display. Available options differ depending on scope chosen.
