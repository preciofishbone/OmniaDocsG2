Working with Events
===========================

**This documentation is just started. More will be added here soon.**

Using a number of options in Omnia, together with a few dedicated options, you can publish information about different kinds of events (training sessions is one example) and can handle registration of participants for the event.

By connecting the Omnia Event functionality to Outlook, options in Outlook can be used to display the event in the participants calendars and for communication between the participants and the event.

On an Event Page it is possible for colleagues, and even external users that has been invited in the Asher AD, to register or to be registered for participating in the event, and to edit or cancel registrations, if needed.

Before you can set up anything else, there's a few things you need to do. See this page for more information: :doc:`Setup Event Management </setup/eventmagaments/index>`

You create a Page Collection to use specifically for events. In that Page Collection you add an Event Center (quite like what you do when adding a News Center for news), among other pages that may be needed for describing the events. For the purpose of listing events, an "Event List" view is available for Display in the Page Rollup block.

You need at least one Page Type for Events, so Event Administrators can create pages for different events. On that Page Type you use the :doc:`Action Button block </blocks/button-link/index>` to add three Actions Buttons so colleagues can register for themseleves, register for others, and cancel their registration. You must use the type "Event Management" for the Action Buttons for this to work (on the Page Type for Event Pages, but not on the "Event Centre" page).

**Note!** In Features for an App in Omnia Admin, you can activate the feature called "Default Page types for Event Management", to get a Page Type for that purpose, if you don't want to create one yourself.

There's two specific blocks available for Event Management; :doc:`Event Participant List </blocks/blocks-event-management/event-participant-list/index>` and :doc:`Event Participant Counter </blocks/blocks-event-management/event-participant-counter/index>`. In all other aspects, you use available options for Page Types in Omnia to create pages with the information you want to display for the Event.

Event Administrators only needs to have Author permissions. Besides being able to create new events (pages), they can edit the information added by participants and even remove participants, if needed. The list of participants can be exported to Excel.


.. toctree::
   :titlesonly:

   creating-new-event/index
   administer-event/index
   register-for-event/index
   implementation-example/index



