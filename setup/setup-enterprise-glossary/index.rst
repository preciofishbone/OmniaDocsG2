Setup Enterprise Glossary
=====================================

**(This documentation is just started. Will be finished soon).**

**Step 1**: Go to the term store and create a new term set with the terms you wish to use as tags.

image

**Step 2**: Go back to Omnia Admin tenant settings, go to Properties, then Enterprise properties, and create a new property of the type Taxonomy that is then mapped to the same term set that you’ve created in the term store:
 
 image

**Step 3**: Now we start creating the pages that will be matched to each of the terms. To do that, start off by creating a page type that has our new created property “Organization unit” as a page property with the following settings:

 image

**Step 4**: Start creating pages that will be used as the home for each tag, and make sure to match the term from our new property with the page you wish to display when you click on the matching tag:
 
 image

**Step 5**: Once you’ve finished creating the pages, go to Omnia admin to tie it all together and create the tags:
 
image 

Then make sure to select the correct term set, add page as details provider, and fill in the rest of the properties correctly:
 
 

Keep in mind that properties like “image ratio” are subjective, you experiment with different image ratios and see what you like best. You can always come back to the enterprise glossary section and modify the properties you have selected in each box, or even taxonomy.

Step 6: Map each page that you’ve created with the correct taxonomy, by clicking on the tree structure icon of your enterprise glossary, and then clicking on each tree structure icon next to each term and selecting the matching page
 
 

Make sure to select the correct publishing app and page collection to be able to find your page:

And with that you will have successfully created your tags.
 
Optional: Once you're finished with mapping your pages, you will have successfully created your tags. You can now either give the tags some colors and icons if you wish to do so:

What does it look like when tags are implemented successfully? Here we have an example of a news page rollup that utilizes tags:

When you click on each tag, you will see a highlighted small pop-up window with information from the associated page with the tag:


These are the properties we have selected in step 5 that are displayed here. When you click on the Read More button, you will be teleported to the page associated with the tag:
 
 

If you wish to implement tags in your pages, you can simply do so by adding the property “organization unit” that we have created to the page type of the page you wish to tag. Here we have a news article for example:
 
 



And then in the page rollup where these pages will be displayed, make sure to select “Organization unit” as the term property:
 

 

And you are all set!

Bonus 1: How to create an org chart in your mega menu (Workspace Mega Menu Required)

 
 


Step 1: Once you’ve completely finished setting up your tags, go to Omnia admin, then workspace and navigation bar:
 

 

Then click the plus icon and create a new layout:
 
 

Step 2: in your new layout, add the component “Taxonomy Navigation”, with our Taxonomy selected and term selected but with no value:


Then in the view section, make sure to select the following view settings in Default settings:
 
axonomy Navigation	>

SETTINGS	LAYOUT

T T Gei11ernl	v

(1] Query	V


View

Line Colcf

•	#293237



No o' pare'll level s a shcw.·
1



No o' children a how
50


lnclude Taxonomy Roo


Navigate to connected page
E	CURRENT
Mapping

Show Mor2 L'lk
None


 

--:1le
litle
 

X ...
 

 


Summary

 

 


Then the following in Current settings:
 
Il Taxonomy	avigation	>

SETTIINGS	LAYOUT

, .,.._. .._.    ._.., 11HJ1t, I   ,_,  :-1IU-111'
50


lnclude Taxonomy Roo


Naviga1e to connected page
DEFAULT 13
Mapping

w Mo 2     nk
Navigate to page



-1e
Title



Summary


 

lrrage
Page llmage
 

X ....
 

 

 

lrr age Ratio
Wide
 

X ....
 

 


Moditied By	X ....
X

Add Column


,.,	style
 

 



And you are all set!










