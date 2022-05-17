Tenant Page types
====================

Tenant Page Types can be created to be used in any Publishing App in the tenant.

The Tenant Page Types are handled from here:

.. image:: WCM-page-types-v6-new.png

You work with the Tenant Page Types exactly the same way as the Local Page Types, as described here: :doc:`Page Types </pages/page-types/index>`

The "only" difference is that the Tenant Page Types are created and edited here, they are not visible in the list "Page Types" in the Publishing App, but are available when an editor creates a new page.

**A tip!** If you go to a suitable page before going to Omnia Admin, the Preview can show some content when you edit Tenant Page Types.

Activating Tenant Page Types
******************************
You activate Tenant Page Types the same way as the Publishing App Page Types, in the settings for the Page Collection. Note the notification (Tenant):

.. image:: WCM-page-types-activate-v6-new.png

The Page Types can then be used by Page Editors to create pages, the same way as before.

**Important note!** If a Tenant Page Type is edited and published, it is updated for all pages using the Page Type all over the tenant!

Moving a Page Type to Tenant
*******************************
If you already have one or more Page Types you want to use as a Tenant Page Type, you can easily "make a Tenant Page Type" of them. 

Select the Page Type and choose "Promote To Tenant" in the menu:

.. image:: WCM-page-types-move-to-tenant-new.png

All pages using the promoted Page Type will continue using it, but the Page Type will now fully function as a Tenant Page Type. (See for example the comment about updating a Page Type above).

**Note!** The promoted Page Type is removed from the list of Page Types in the Publishing App - it can no longer be edited there. As it is a Tenant Page Type from now on, it must be edited in Omnia Admin. 

Deleting a Tenant Page Type
******************************
You can delete a Tenant Page Type:

.. image:: WCM-page-types-archive-menu-new.png

(Note that you must save or discard any changes that has not been saved, for the DELETE option to be available).

Deleted Tenant Page Types are placed in the Tenant Archive:

.. image:: WCM-page-types-archive-new.png

This archive works the same way as the archive for the Local Page Types, see: :doc:`Delete or restore a Page Type </pages/page-types/archive-restore-page-type/index>`
