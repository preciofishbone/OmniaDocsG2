Working with Published documents
=================================

The Published tab lists the latest edition of all published documents from this Controlled Documents library. There are some useful options for a published document here. You can for example check the Properties, see the Document History, see Feedback that users has sent and Move a document.

A site Administrator (Owner) can set up which columns to show on this tab. Here's an example:

.. image:: published-example-new3.png

All options are found in the dot menu for a document (image from Omnia 6.12):

.. image:: published-dot-menu-new2.png

Create Draft
**************
You can create a new Draft from a published document and start working on the new edition when you need it. The existing edition is still available for users until it's replaced, when the new edition is published.

For more information on how to create a new draft, see the heading "Creating a new draft from a published document" on this page: :doc:`Working with Drafts </working-with-documents/authoring-controlled-documents/working-with-drafts/index>`

Signed copy
***************
In Omnia 6.12, you can use this option to create a signed copy of a document, that will be available together with the document. The option must be activated for the document type to be available here, see link below.

Use the following steps:

1. Open the dot menu for the document and select "Signed Copy".

.. image:: signed-copy-menu.png

2. Download the copy from here:

.. image:: signed-copy-download.png

3. Sign the document the way your organization do; either sign it digitally or print the document and sign it manually, and then scan it.
4. Upload the signed copy.

.. image:: signed-copy-upload.png

5. Save when you're done.

.. image:: signed-copy-save.png

If a signed copy is available for a document, it's indicated by this icon:

.. image:: signed-copy-icon.png

Users can click the icon to download the signed copy.

For more information on how to activate Signed copy, see the heading "Settings for Document Types" on this page: :doc:`Document Types </admin-settings/tenant-settings/document-management/document-types/index>`

Related Documents
*******************
You can relate a published document to other published documents. How to do that is described on this page: :doc:`Related Documents </working-with-documents/authoring-controlled-documents/related-documents/index>`

Related Processes
*******************
Using this option you can see if a document is related to any process(es) - meaning added as a document to the process(es). You can also suggest that the document should be added (related) to a process. The suggestion is sent to the feedback receiver for the process.

To check if a dcument is related to any process(es), do the following:

1. Open the dot menu for the document and select "Related Processes" (image from Omnia 6.12). 

.. image:: related-processes-menu-new.png

Any related processes are now listed.

2. To suggest that this document should be relate to a process, click ADD SUGEESTIONS.

.. image:: related-processes-related-new.png

3. Click in the field and type part of, or the whole, name of the process you have in mind, to search for it.

4. Select the process.

.. image:: related-processes-click-search-new.png

5. Select the process again in the next step, and the click SAVE.

.. image:: related-processes-sent-new.png

And now your suggestion is sent to the feedback receiver for the process, for evaluation, and it's shown this way:

.. image:: related-processes-sent-message.png

For information on what the author of the process can do with the sugestion, see this page: :doc:`The Documents tab - authoring processes </working-with-processes/authoring-processes/working-with-drafts/documents-tab/index>`

Checking a documents properties
*********************************
The properties for a published document can be checked this way:

1.	Click the dot menu for the document.
2.	Select "Properties".
 
The Properties window for the document is shown, for example:

.. image:: published-properties-new2.png
 
The properties can not be edited here. The properties can only be edited when working on a draft for a new edition of the document.

**Note!** A term that has been translated in the term store will be shown in the document's language here, but if the term is shown in the Published list, it is shown in the user's language. Also note that placeholders in DOCX and XLSX are replaced with terms based on the document's language.

Copy Link
**********
If you need to send a link to a published document, use this option.

Just click the option (no window or message is shown) and you can then paste the link in an e-mail, in a document, as a link on a page, or wherever you need the link.

.. image:: published-copylink.png

Document History
******************
There’s information about each published edition available. To see it, do the following:

1.	Click the dot menu for the document.
2.	Select "Document History".
 
Here’s an example:

.. image:: published-history-new2-frame.png
 
You can see the publication date for each edition, the author’s comment, if any, and who the document was approved by. The option "Workflow History" for an edition will show information about when workflows was used and the comments entered during the workflows, so here you can even see information from Send for Comments workflows used for the document.

Here's an example:

.. image:: published-history-workflow-new2.png

Check Feedback
****************
Any user can send feedback on a published document and that feedback is available for authors here. To read feedback for a document:

1.	Click the dot menu for the document.
2.	Select "Feedback".
 
The feedback posts for the document is shown. Click a post to read the feedback. Here's an example:

.. image:: feedback-example-new3.png

You can click the dust bin to delete the feedback when you have read it, or keep it for later reference, it’s up to you.

Read Receipt Status
********************
This option has to do with the option "Notify people" an author can select when publishing a document. See this page for more information: :doc:`Read and Understood - Notify and Read Receipt </working-with-documents/authoring-controlled-documents/read-and-understood/index>`

Move a published document
*****************************
A published document can be moved to any other site with a Controlled Documents library. If a draft for a new edition of the document is present, the draft must first be deleted.

**Note!** You must first check and note (or copy) the URL to the site you want to move the document to.

1.	Click the dot menu for the document.
2.	Select "Move Document".
 
The following is shown:

.. image:: published-move-document-new3.png

Note the message about what will happen with document properties.
 
3.	Type the URL (or paste, if you have copied it) to the site in the top field and click "Resolve". 

**Note!** You should type or paste the Url to the site, note the Controlled Documents library. If the Url is not correct (meaning pointing to the site only) you will get the message that site does not contain a Controlled Documents library.

If the URL is correct the site title is shown in the second field - Site Title.

4.	Click MOVE.

Unpublish
**********
As described in this section, this is how it works in Omnia 6.12 and earlier. For Omnia 6.13 and later, see below.

If needed, a published document can be unpublished. The document is then removed from the Controlled Documents library. If an archive for documents is set up, the document is placed in the archive. If a document archive is not set up, the document is simply deleted.

**Note!**
A document can't be unpublished if a draft has been created for that document. The draft must first be deleted.

When "Unpublish" is selected, you get a second chance to change your mind:

.. image:: unpublish-2-new2.png

Delete and restore a document
********************************
In Omnia 6.13 and later, this option is now called Delete:

.. image:: delete-document-613.png

It works like this:

A published document that has a new draft can't be deleted, just as before, the draft must be deleted first.

When you delete a document, you get a chance to change your mind:

.. image:: delete-document-613-ok.png

If an archive for documents is set up, the document is placed in the archive. The archive works as before, but in Omnia 6.13 the deleted document is also placed in a local (= for the site) recycle bin. 

If needed, an administrator can restore a document from there. A restored document, is restored as a draft and can then be edited and published the normal way. Also, if the document was published as a PDF, it's the original document that is restored, so the document can be edited.

The restored document keeps it's ID and the document history is retrieved as well. it's noted in the history that the document has been deleted and restored (if that happened).  

The recycle bin for controlled documents can look this (image from a test environment):

.. image:: delete-document-613-recycle-bin.png

Here, documents can be restored or permanently deleted.

Select the document and select option.

.. image:: delete-document-613-recycle-bin-options.png

If you choose to permanently delete a document here, you can change your mind:

.. image:: delete-document-613-recycle-bin-options-delete.png

If you choose to restore a document, the following is shown:

.. image:: delete-document-613-recycle-bin-options-restore.png

These are the same options as when you create a draft from a published document. See above for a secription-

