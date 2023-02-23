Text
=============
Use this block to add text anywhere on a page. You can use it just to add a container an editor can to add text to, or you can add some default text an editor can edit using Write mode, or text that editors can't edit.

When adding text to the block some basic formatting can be available, depending on the type of text set for the block. Here's an example with the formatting options for Rich Text:

.. image:: text-formatting-rich-new.png

Point at an icon and a Tool Tip will show what the option is for.

See this page for more information on how to use the RTF Editor: :doc:`RTF Editor </general-assets/rtf-editor/index>`

Available options for Rich Text is set up in Omnia Admin, see: :doc:`RTF Editor Settings </admin-settings/tenant-settings/settings/rtf-editor/index>`

Settings
*********
The following settings are available for the block:

.. image:: text-settings-612.png

+ **Title**: If a title should be shown for the block, add it in this field. If no variation exists for the page, it looks like in the image above and you can set the title in the languages active in the tenant. If variations exists, only one title can be set. In that case, titles in other languages are set in the variations.
+ **Mode**: Select mode for the text. For Plain Text and Multi-line Plain Text there are no formatting available. For more information on Custom Rich Text, see below.
+ **Formatting**: Select the default style here. Available for Plain Text and Multi-line Plain Text.
+ **Enable Machine Translation**: If machine translation should be available for this text block, select this option. **Note!** Machine Translation is not available in Omnia on-prem.
+ **Help text**: Here you can add a help text for the editor, for example to make it clear what kind of content should be added to the block. The help text is shown when no content is added, and when the block is edited. The help text is never shown to users as it's not shown for a published version of the page. Not available for Plain text. 
+ **Enable creation of tags**: When this option is selected, any #tag that is added in the text block will be set in the configured corresponding property.
+ **ADD CONTENT**: Click here if you want to add some default content to the block. (also see below).
+ **Padding**: You can set some padding around the text if needed.

For more information on how machine translation works, see the RTF Editor description (see link above).

Custom Rich Text
-----------------
If you select Rich Text or Limited Rich Text, the text tools include only those set up in omnia Admin. 

When you select Custom Rich Text you can set the text tools that should be available in this block, from the tools available in Rich Text. Open "Custom Rich Text" that now becomes available at the bottom of the settings window:

.. image:: custom-rich-text-new.png

**Note!** Not all options are shown in the image.

You work with these settings exactly the same way as when they are set up in Omnia Admin, see :doc:`RTF Editor Settings </admin-settings/tenant-settings/settings/rtf-editor/index>` 

Add default content
--------------------
When you click "ADD TEXT" the following is shown:

.. image:: text-block-add.png

Add the default content and save.

Using the WRITE tab you can set if it should be possible for editors to overwrite the default content or not, see below.

Layout
********
The LAYOUT tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

Write
******
Using the WRITE tab you can set the following:

.. image:: text-block-write.png

+ **Enable overwrite in write mode**: If it should be possible for editors to overrite the default content in the block, this option should be on. If not, click to set the option to off.
+ **Property to store data**: Select type of text to be used in this block; Title, Page Content or Page Summary. When one block on the page has data connected to a Property, that data can be reused in all blocks that uses the same Property. Page scoped. Not mandatory.

