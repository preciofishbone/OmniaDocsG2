The Drawing tab - authoring processes
========================================

You use this tab to visualize the process or process step.

Canvas Settings
****************
To open the canvas settings, click the cog wheel.

.. image:: pm-drawing-canvas-1.png

Here you can set the following and you can edit these settings anytime.

.. image:: pm-drawing-canvas-2.png

+ **Width/Height**: Set the size of the work area in pixels here.
+ **GridX/GridY**: The work area has a grid that shapes and clickable areas snap to. You set the size of a square in the grid here.
+ **Show gridlines**: Select this option if you want the grid lines to be visible. 
+ **Highlight shapes**: Select this option to display an outline around the shapes. This can be useful if, for example, the shapes color is similar to the background image.

Here's an example with grid lines visible:

.. image:: pm-drawing-canvas-3.png

Here's an example with shapes outlined:

.. image:: pm-drawing-canvas-4.png

**Very important!** The canvas setting is the same for all devices so you have to consider what canvas size is the most user friendly for the devices most commonly used in your organization for accessing the process.

Working with shapes
*********************
To add a shape, click "ADD SHAPE".

.. image:: pm-addshape.png

Something like the following is shown:

.. image:: pm-drawing-shape-settings.png

Exactly what is available here depends on settings for the Process Type, so this is just an example. For more information see: :doc:`Process Types </admin-settings/tenant-settings/process-management/process-types/index>`

+ **All Shapes**: If the list of shapes is very long, you can use this field to search for a shape.

Custom shapes may not be allowed at all. If custom shapes are allowed "Freeform" means you, the process author, can draw a new shape when needed. "Media" means you can upload an image to use as a shape for this process or process step.  

Settings for a shape
----------------------
To select a shape, just click it and the following settings is shown:

.. image:: pm-drawing-shape-settings-settings.png

+ **Shape Type**: Here you decide what to use the shape for. Process Step is the default. You can also choose "None", which means it's just an image; "Linked process" and "Link". All selections except "None" creates a clickable shape. See below for more information. Note that to be able to create a linked process, other processes must already exist, to link to. 
+ **Select Process**: When you have selected "Linked Process" in the top list, use this list to choose the process to link to.
+ **Add Link**: When you have selected "Link" in the top list, this option is shown. See below for more information.
+ **Title**: Add the text that should be displayed for the shape here, if a text should be displayed. You can see a preview to the right. You can add the title in any or all available languages.
+ **Text Position**: Set the position for the text: "On Shape", "Above Shape" or "Below Shape".
+ **Text Alignment**: Set text alignment here: "Center", "Left" or "Right".
+ **Text Adjustment**: Use the arrows to fine tune the placement of the text. Use the center icon to center the text.
+ **Show more settings**: Click to show the following settings:

.. image:: pm-drawing-shape-settings-settings-more.png

+ **Font Size**: Set the font size in pixels for the text here.
+ **Colors**: Use the options in this section to set details for colors, for the shape and text.

When you select the option "Add Link", you can use the following settings:

.. image:: pm-drawing-shape-settings-add-link.png

Add a title for the link (default language mandatory), add or paste the URL and decide if the link should be opened in a new window or not.

Click "OK" to save the shape.

Click "CHANGE SHAPE" to go back a step to create an additonal shape.

Click "CANCEL" to exit.

.. image:: pm-drawing-shape-settings-save.png

If you created process steps when adding shapes, you can now see that they are listed in the navigation.

.. image:: pm-drawing-process-step.png

You can use the tabs to edit the process steps.

Adjust the shapes
-------------------
Note that when you add a new shape it's placed in the upper left corner of the canvas, and text above may not be seen. It that is not the intended position, use drag and drop to place the new shape. You can place a shape anywhere within the canvas.

To adjust the size of the shape, click it and use the handles to drag to the desired size.

.. image:: pm-drawing-shape-size.png

To edit the settings for a shape, click the shape and then click the pen.

.. image:: pm-drawing-shape-edit.png

Clone a shape
---------------
If you need a number of shapes that are similar, this is a handy option.

1. Select the shape you want to clone.
2. Click "CLONE SHAPE".

.. image:: pm-drawing-shape-clone.png

3. Select the new shape to change settings as needed.

(Note that the cloned shape may be placed on top of the "mother" shape. You may have to move the new shape to see it.)

Delete a shape
----------------
To delete a shape you no longer need, do the following.

1. Select the shape.
2. Click "DELETE SHAPE".

.. image:: pm-drawing-shape-delete-1.png

The following is shown:

.. image:: pm-drawing-shape-delete-2.png

3. Click "OK" to delete or "CANCEL" to change your mind.

Create a drawing for a process step
**************************************
Regarding a drawing for a process step, the default setting is that the main process drawing (the "parent drawing") is used. If you want to create a drawing for a proces step, do the following:

1. Select the process step.

.. image:: select-process-step.png

2.Click "CREATE DRAWING".

.. image:: create-drawing.png

Now you can work with the process step's drawing as described above.

Add a background image
***************************
The option for adding a background image is also available in the canvas settings. You can use this option either for just a nice background image, to place shapes on, or to upload a process image you have created in for example PowerPoint or Visio, to add clickable areas on. For more information about clickable areas, see below.

To add a background image:

1. Open the Canvas Settings.
2. Click "Add Image".

.. image:: pm-background-image-2.png

The Media Picker opens and you use it to upload an image from your computer or from any of the available resources, for example:

.. image:: pm-background-image-3.png

For more information on how to use the Media Picker, see: :doc:`Media Picker </general-assets/media-picker/index>`

Adding clickable areas to a drawing
-------------------------------------
If you have uploaded a drawing you can place clickable areas on that drawing, to go to process steps and more.

**Important Note!** To be able to add clickable areas, the Process Type must contain Freeform.

**Tip!** Activating "Highlight shapes" in the grid settings can be useful when working with clickable areas.

1. Click "Add shape".

.. image:: clickable-1.png

2. Click "Freeform".

.. image:: clickable-2.png

3. Edit the settings for the shape, see the heading "Settings for a shape", above. Note, here you set what will happen when the area is clicked.

**Tip!** You probably don't want any colors for the clickable area, or maybe just a border color when the mouse hovers over the area. Click "Show more settings" to edit the colors.

4. Click "Draw shape".

.. image:: clickable-3.png

The drawing is now shown with the grid on top, for example:

.. image:: clickable-4.png

5. Click to set the start corner, move the mouse to the next corner and click to set it ... continue this way until you have "painted" the shape.
6. Set the shape by clicking at the start corner once more.

You now have the first clickable area in place and what is opened when a user clicks it depends on the setting in step 3. (In the image below "Highlight shapes" is on.)

.. image:: clickable-5.png

7. Click "OK" in the grid window.
8. Click "OK" for the shape settings.

To add additional clickable areas you have to go back to step 1, but there's a neat trick if you are adding several clickable areas with the same shape. A quick way of adding additional steps is this:

9. Select the shape.
10. Select "CLONE SHAPE".

.. image:: clickable-6.png

10. Edit the settings for the copy (clone) and save.
11. Move the new clickable area to the correct position.

Change the size of a clickable area or move it
--------------------------------------------------
To change the size of a clickable area, do the following:

1. Click the area.
2. Use the handles the resize the area.

.. image:: clickable-7.png

To move a clickable area, just use drag and drop.

Edit settings for a clickable area
-----------------------------------
To edit settings for a clickable area, do the following:

1. Click the area.
2. Click the pen icon.

.. image:: clickable-8.png

3. Change the settings and save.
