Event management - implementation example
==========================================
Here's an example from a test environment of how Event management can be implemented.

In this example a site for different training events has been set up, both internal, external and online. The landing page is set up with a page rollup.

.. image:: event-implementation-1-new.png

"Upcoming course dates" displays the upcoming training events in form of a calendar. Different colors are used for the different kinds of training events.

.. image:: event-implementation-2-new2.png

A description of a course (page) can look like this:

.. image:: event-implementation-4-new.png

There can be three buttons available for registration: SIGN UP, CANCEL and SIGN UP OTHER. The CANCEL button is only shown once the user has registered. The buttons can of course be named something else, as they have been in this example. 

Aavailable seats for this course are 15 in total where one has already been taken.

.. image:: event-implementation-booked-New.png

When signing up for this course, the following is shown:

.. image:: event-implementation-signup-New.png

The user can add a phone number, add a number of not named colleagues that will accompany him or her to the course, and add a comment. The rest is filled in automatically.

When the user has signed upp, the sign up button changes to a cancel button:

.. image:: event-implementation-signup-cancel.png

The information about available seats has also been updated, two seats are now taken.

If signing up a colleage, a list of all users in Omnia is made available. Also note that an external user can be added, by clicking that link.

.. image:: event-signup-colleague.png

The settings
***************
The following settings has been used for the pages:

When a manager/page editor creates a new event - meaning a new event page - the following settings are set up in this example:

.. image:: event-implementation-settings-1-new.png

It is here the manager/page editor adds all data about the event; for example when it starts and ends and the maximum number of participants. Some properties may have to be set up specifically in Omnia admin before they can be used here.

For more information about these options, see: :doc:`Creating a new event </working-with-events/creating-new-event/index>`.

The page type for the event pages consists of a number of blocks. Important to mention is the following:

The buttons in the Action button block must have the type "Event management" to work for this purpose.

.. image:: event-implementation-settings-2-new.png

(All settings are not shown in the image.)

The Event participant counter block is set up this wvay:

.. image:: event-implementation-settings-3-new.png

The block is using the setting for available seats done when creating the event page, see above.

More information about the event management blocks is found here: :doc:`Blocks for event management </blocks/blocks-event-management/index>`

The rest of the sections and blocks used on the page type are set up depending on the information being displayed, by using options available for any page type.


