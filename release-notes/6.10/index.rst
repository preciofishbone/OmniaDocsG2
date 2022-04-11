Release 6.10 (Preview)
========================================

.. note:: Release 6.10 is in preview. Items may be added or removed from this list at any time.

Page Rollup
------------------------------------------
It is now possible to create page rollup queries that spans the whole tenant or specific business profiles.

.. image:: pagerollup-tenantbp-scope.png

Page statistics is now built into the page rollup. It is possible to display and sort on [Page Hits: All Users],
[Page Hits: Current User] and [Unique Users]. The statistics time period can be limited to one week from today,
two weeks from today or one month from today.

.. image:: pagerollup-statistics.png

The page rollup can now be used to create editorial dashboards that includes pages that have not been published.
The rollup is security trimmed so that only authors can see pages that have not been published yet.

.. image:: pagerollup-publishingstatus.png

To further improve the experience for an editor, you can query and display the workflow status of a page.
The workflow status can be "Checked Out", "Pending Publishing", "Scheduled for Publishing" and "Waiting for Approval".

.. image:: pagerollup-workflow-status.png

A new switch has been addded to the query part that makes it possible to exclude variations from the rollup.

A new Calendar view is now available for the page rollup block.

.. image:: pagerollup-calendarview.png

A new switch has been added to the page rollup display that makes it possible to export the result to Excel for further analysis.

.. image:: pagerollup-exporttoexcel.png

.. image:: pagerollup-exporttoexcel2.png

Teamwork
------------------------------------------

Naming policies are now supported for teamwork templates. A naming policy consists of prefix, suffix and blocked words.

The prefix and suffix can be fixed text and/or dynamic values from the teamwork app properties or the current logged in user.

.. image:: teamwork-naming-policy.png

Besides a naming policy, a teamwork template can be configured with a number of additional policies:

* Minimum no of characters in description: Will not let the user proceed with the teamwork creation without a clear description.
* Minimum no of admins: Forces long-term membership of the teamwork.
* Default administrators: Makes it possible for central support functions to get ownership of all teamwork by default.
* Sensitivity labels: Makes it possible to apply additional policies using Microsoft compliance features.

.. image:: teamwork-template-policies.png

.. image:: teamwork-policies-wizard.png

Teamwork templates can now be targeted to a specific group of people.

.. image:: teamwork-targetingoftemplate.png

Teamwork properties now support both default values and help texts.

.. image:: teamwork-propertydefaultvalues.png

.. image:: teamwork-propertyhelptext.png

A new tab has been added to the teamwork app list in Omnia Admin to show inactive teamwork.

.. image:: teamwork-inactive.png

It is now possible for a global IT administrator to securely turn off the possibility for end users to create Microsoft 365 groups from within
the standard services in Microsoft 365 (Teams, Planner, SharePoint etc) and force a structured workflow using Omnia teamwork templates.

Microsoft Teams Integration
------------------------------------------

A new feature in Teamwork makes it possible to create layouts that can be used in MS Teams tabs.

.. image:: teamwork-layouts.png

.. image:: teamwork-layout-tab.png

Built-in MS Teams templates can now be used as a basis for Teamwork.

.. image:: msteams-builtin-templates.png

.. image:: msteams-templateinteamwork.png


A teamwork template can also be set up to allow for the end user to clone an existing MS Teams team.

.. image:: msteams-cloneexistingteam1.png

.. image:: msteams-cloneexistingteam2.png


[TODO: Planner board creation]

Web Content Management Editor
------------------------------------------

The related links block can be configured to allow documents that you pick to be locally accessible together with the page.
Documents that are locally accessible are versioned together with the page and can be accessed by users without a SharePoint license.

.. image:: wcm-localdocs-select.png

.. image:: wcm-localdocs-settings.png

A variation can be configured to support languages that flow from right to left.

.. image:: wcm-righttoleft-setting.png

.. image:: wcm-righttoleft-page.png

Pages can now be moved and copied across page collections within a publishing app.

.. image:: wcm-righttoleft-page.png

[TODO: Move page collections across publishing apps.]

.. image:: layouts-lockblock.png
    
.. image:: layouts-lockblockdialog.png

Digital Signage
------------------------------------------

Omnia is now prepared for integration with any modern supplier of digital signage solutions.

.. image:: digitalsignage.png

App Posts
------------------------------------------

A new feature makes it possible to post coversation messages in an app. It can be used to implement a common discussion within a community or a conversation within a teamwork.

.. image:: posts-community.png

.. image:: posts-teamwork.png


Print Processes
------------------------------------------

It is now possible to print a process including all process steps and drawings to either PDF or printer.

.. image:: process-print.png

.. image:: process-print2.png

