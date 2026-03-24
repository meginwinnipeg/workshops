---
layout: default
title: Analyze
parent: GEOG2200
grand_parent: Classes
nav_order: 3
---

# Conducting analysis using ArcGIS Online tools

---
<iframe width="720" height="480" frameborder="0" marginheight="0" marginwidth="0" style="border:12px solid  #fcfcfc" src="https://meginwinnipeg.github.io/slides/RVanalyzing.html"></iframe>


---

## 0. **Summary**:  
In this step we will be creating three (3) different type of maps, and an additional feature layer to support our story.  

- Genus Map  
- Heat map  
- Proportional symbology  
- Summary Statistics 

---

## 1. Select the **map** you made in the previous step, we're going to use it as a template to create our other maps. 
 
1. Navigate to UM's ArcGIS Online Portal (https://univmb.maps.arcgis.com) and ensure you are signed in.  
2. Access the **Content** area by clicking on that option in the top navigation.  
![AGOL workspace](img/analyze/step1a.PNG)<br>  

3. Click the **map** title in your Contents area.  
4. On the details page that opens, select the **Open in Map Viewer** option to open our map.  
![AGOL workspace](img/analyze/step2b.PNG)<br>  
 
5.  Save multiple copies of the map to your personal content area by selecting the **Save As** option.   
![AGOL workspace](img/analyze/step3e.PNG)<br>
We will be creating the following maps, so save one copy for each (name it something meaningful and be sure to add your initials to the end of the filename).  
    1. Tree Species Map     
	2. Heat Map of Trees  
	3. Proportional Symbology Map  
6. When you return to your **content** area, you should now see **four (4)** maps listed.   
![AGOL workspace](img/analyze/step2g.PNG)<br>  


## 2a. Create a **Species map** to show distribution around campus.  

1. Click the **Species map** title in your Contents area.  
2. On the details page that opens, select the **Open in Map Viewer** option to open our map.  
![AGOL workspace](img/analyze/step2b.PNG)<br>
3. In the Table of Contents ensure that:
   1. The Space Inventory is hidden  
   2. The Tree Inventory is selected
![AGOL workspace](img/analyze/step2c.PNG)<br>  
4. Select the **Styles** toolbar at the right side of the screen. 
5. Then click the ** Field** button.  
![AGOL workspace](img/analyze/step2d.PNG)<br> 
6. Check off **Species** in the list that opens, and then **Add** to the map.  
7. Your map should now look something like:  
![AGOL workspace](img/analyze/step2e.PNG)<br>

## 2b. **Configure pop-up** in your map for visual clarity.  
Right now, our pop-up contains a lot of extra information that our audience may not be interested in:  
![AGOL workspace](img/analyze/step2f.PNG)<br>
 
1. To edit, ensure the **Tree Inventory** layer is selected in your Table of Contents and select the **Pop-up** toolbar on the right side of the screen.  
2. We can see there is a title block coming from the _latin names_ field, a list of 30 fields, and an attachment image.  
![AGOL workspace](img/analyze/step2h.PNG)<br>
3. Delete the list of fields by clicking the 3 dots to the right of the item and selecting **delete**.  
4. Select the **add content** option at the bottom of the menu, and select **Text**.  
![AGOL workspace](img/analyze/step2i.PNG)<br> 
5. Paste the following code into the text box and click OK:  

`This {Species} is listed as {Tree_Maturity} and stands at {Height}m tall, with a crown that is {Spread}m wide.
We are currently updating our dataset to include names of our campus trees in Indigenous languages.
The {Species} ({Latin_Names}) is known as:
Michif: {Michif}
Dene: {Dene} 
Anisininew: {Anisininew}
Anishinaabeg: {Anishinaabeg}`
 
6. Your pop-up should now look something like:  
![AGOL workspace](img/analyze/step2j.PNG)<br> 

3. Edit the title for the pop-up so that the label is _Common Name_:  instead of the feature service name.  
4. Select the blue **Configure Attributes** text to select which attributes you want to show up.  
![AGOL workspace](img/integrate/step6c.PNG)<br>

5. Click _OK_ to save your changes, now your pop-up should look something like:  
![AGOL workspace](img/integrate/step6d.PNG)<br>


## 7. **Center/ zoom** your map for reuse.  
We will be reusing this map later in a StoryMap. How your map looks here is how it will look when it is reused so we want to center it/ set base maps accordingly.  

1. To **center**, ensure the _Content_ option is open in your Table of Contents and hover over the _TreeInventory_ layer to reveal its options.  
2. Select the three small dots on the right to open the **properties**, then the **Zoom to** option,  
![AGOL workspace](img/integrate/step7a.PNG)<br>

3. Your map should now look something like:  
![AGOL workspace](img/integrate/step7b.PNG)<br>

4. **Save** your edits. 


s








 
 
 
 
 
## 3. Create a **heat map** to show distribution.  

1. Click the  dropdown arrow beside the **Open in Map Viewer Classic** option at the top of the list of options on the right side of your feature service window.  
2. Select the **add to new map** option. The data may take a couple of seconds to load.  
![AGOL workspace](img/analyze/step3a.PNG)<br>  

3. The style options should open automatically in your Table of Contents.  
    1. _Choose an attribute to show_: **Show location only**  
    2. _Drawing style_: **Heat Map**  
    3. Select **options** for _Heat Map_  
![AGOL workspace](img/analyze/step3b.PNG)<br>  
     
3. In the Symbology options that open select the small icon on the right and select a colour ramp that works for you.  
![AGOL workspace](img/analyze/step3c.PNG)<br>  
 
4. Click _OK_ and then _Done_ at the bottom of the Table of Contents. Your map should look something like:  
![AGOL workspace](img/analyze/step3d.PNG)<br>  

5. **Save** a copy of the map to your personal content area by selecting the **Save As** option. Call it something meaningful and be sure to add your initials to the end of the filename.  
![AGOL workspace](img/analyze/step3e.PNG)<br>  

6. Return to your **personal content** page.  


## 4. Save copies of other workshop maps shared in **My Groups** to your personal content:  

1. Click on **My Groups** in the blue Content navigation bar.  
2. This brings up items that have been shared at the Group level, I have shared three (3) maps and two feature layers with you.  
3. Save a copy of  _TreeDiameterMapKP_demo_ and _TreeStatsMapKP_demo_ to your personal account  
    1. Open each map and select the **Open in Map Viewer Classic** option on the right side of your screen.  
    ![AGOL workspace](img/analyze/step4a.PNG)<br>
   
    2. **Save** a copy of the map to your personal content area by selecting the **Save As** option. Add your initials to the end of the filename.  

  ![AGOL workspace](img/analyze/step4b.PNG)<br>

 
## 5. **Open** your newly saved _TreeDiameter_ map to edit symbology:  
  
1. From your personal content list click the map title and select the **Open in Map Viewer Classic** option on the right side of your screen.  
![AGOL workspace](img/analyze/step4a.PNG)<br>

2. Ensure you are in the **Content** area of your Table of Contents to change symbology. The third tile from the left (3 stacked shapes) is the option to **change styles**.  
  ![AGOL workspace](img/analyze/step5a.PNG)<br>  

3. In the _Styles_ dialogue that opens:  
    1. _Attribute_: **Diameter at Breast Height**  
    2. _Drawing Style_: **Counts and Amounts (size)**, then select **options**.  
	  ![AGOL workspace](img/analyze/step5b.PNG)<br>  

4. In the _Counts and Amounts_ dialogue that opens:  
    1. _Symbols_: change the colour to **green**.   
    3. _Classify_: No need to check off, we just want to see the data points relative to one another.    
    5. _Transparency_: Adjust as you want.  
	  ![AGOL workspace](img/analyze/step5c.PNG)<br>  

5. Select _OK_ and then _Done_. Don’t forget to save. Your workspace should look something like:  
  ![AGOL workspace](img/analyze/step5d.PNG)<br>  
  

## 6. **Open** your newly saved _TreeStatsMap_ map to calculate some tree statistics for the park:  
  
1. From your personal content list click the map title and select the **Open in Map Viewer Classic** option on the right side of your screen.  
![AGOL workspace](img/analyze/step4a.PNG)<br>
 
2. You will see a new layer for park boundary appearing in your Table of Contents.  
3. From the **Analysis** options above your Table of Contents, open the heading to **Summarize Data** and select the **Summarize Within** option.  
![AGOL workspace](img/analyze/step6a.PNG)<br>  

4. In the _Summarize Within Dialogue_ select the following options. Note that most options and tools have a blue circle you can hover over for more information.  
    1. _Boundary_: **Polygon**  
	2. _Layer_: **Park and Open space**  
    3. _Summarize_: **TreeInventory** layer    
    4. _Add Statistics_: **Diameter at Breast Height**, **Min, Max, Avg**  
    5. _Group By_: **Genus**, add **minority, majority** and **percentages**    
    6. Name the file something meaningful including your initials.  
![AGOL workspace](img/analyze/step6b.PNG)<br>  

5. Click the _Run Analysis_ option, wait for the data to be added to the map  
6. Don't forget to save your work.  
7. There have been two new items added to your Table of Contents- a layer and a table   
![AGOL workspace](img/analyze/step6c.PNG)<br>  
 
9. Consider how you could use this information in a Story Map.  


That’s it! We now have the building blocks to create a **StoryMap** in the next section!  

