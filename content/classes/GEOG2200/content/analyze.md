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

- Species Map  
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
5. Then click the **Field** button.  
![AGOL workspace](img/analyze/step2d.PNG)<br> 

6. Check off **Species** in the list that opens, and then **Add** to the map.  
7. Your map should now look something like:  
![AGOL workspace](img/analyze/step2e.PNG)<br>

## 2b. **Configure pop-up** in your map for visual clarity.  
Right now, our pop-up contains a lot of extra information that our audience may not be interested in:  
![AGOL workspace](img/analyze/step2f.PNG)<br>
 
1. To edit, ensure the **Tree Inventory** layer is selected in your Table of Contents and select the **Pop-up** toolbar on the right side of the screen.  
2. We can see there is a title block coming from the Latin Names_ field, a list of 30 fields, and an attachment image.  
![AGOL workspace](img/analyze/step2h.png)<br>  

3. Delete the list of fields by clicking the 3 dots to the right of the item and selecting **delete**.  
4. Select the **add content** option at the bottom of the menu, and select **Text**.  
![AGOL workspace](img/analyze/step2i.png)<br>   

5. Paste the following code into the text box and click OK:  

`This {Species} is listed as {Tree_Maturity} and stands at {Height}m tall, with a crown that is {Spread}m wide.
We are currently updating our dataset to include names of our campus trees in Indigenous languages.
The {Species} ({Latin_Names}) is known as:
Michif: {Michif}
Dene: {Dene} 
Anisininew: {Anisininew}
Anishinaabeg: {Anishinaabeg}`
 
6. Your pop-up should now look something like:  
![AGOL workspace](img/analyze/step2j.png)<br> 

7. Don't forget to **Save** your edits. 
8. Return to your **personal content** page.
 
 
## 3. Create a **Heat map** to show distribution around campus.  

1. Select the **Heat Map** you have created from the template.  
2. On the details page that opens, select the **Open in Map Viewer** option to open our map.  
3. In the Table of Contents ensure that the __Space Inventory__ layer is hidden and the __Tree Inventory__ is selected.  
![AGOL workspace](img/analyze/step2c.PNG)<br>  

4. Select the **Styles** toolbar at the right side of the screen. 
5. The style options for trees should open automatically on the right side of your screen.  
    1. _Drawing style_: **Heat Map**  
    2. Explore **options** for _Heat Map_  
![AGOL workspace](img/analyze/step3b.PNG)<br>  
     
    3. In the Heat Map options that open select a colour ramp that works for you.  
![AGOL workspace](img/analyze/step3c.PNG)<br>  
 
6.  Your map should look something like:  
![AGOL workspace](img/analyze/step3d.PNG)<br>  

7. Don't forget to **Save** your edits. 
8. Return to your **personal content** page.  


 
## 4. Use **Proportional Symbology** to show relative tree sizes around campus.  

1. Select the **Proportional Symbol Map** you have created from the template.  
2. On the details page that opens, select the **Open in Map Viewer** option to open our map.  
3. In the Table of Contents ensure that the __Space Inventory__ layer is hidden and the __Tree Inventory__ is selected.  
4. Select the **Styles** toolbar at the right side of the screen. 
5. The style options for trees should open automatically on the right side of your screen.  
    1. _Choose Attribute_: **Field**  
	![AGOL workspace](img/analyze/step4a.PNG)<br>  
	2. Use the checkbox to select __Crown Spread__.  
    3. _Drawing Style_: **Counts and Amounts (size)**, then select **options**.  
	  ![AGOL workspace](img/analyze/step4b.PNG)<br>  

4. In the _Counts and Amounts_ dialogue that opens:  
    1. _Symbol style_: change the colour to **green**, adjust transparency if you wish.   
    2. _Classify_: No need to check off, we just want to see the data points relative to one another.    
  	![AGOL workspace](img/analyze/step4c.png)<br>  

5. Your workspace should look something like:  
  ![AGOL workspace](img/analyze/step4d.png)<br>  
  
6. Don't forget to **Save** your edits. 
7. Return to your **personal content** page.  
  

## 6. **Re-open** your newly saved __Tree Species__ map to calculate some tree statistics for campus. We are interested in finding out species composition in the areas classified as __Interactive Landscapes__:  
  
1. Select the **Tree Species Map** you have created from the template.  
2. On the details page that opens, select the **Open in Map Viewer** option to open our map.  
3. In the Table of Contents ensure that the __Space Inventory__ layer is **visible** and the __Tree Inventory__ is selected.  
4. If you haven't already, take a moment to explore the contents of the __Space Inventory__ layer.  
5. From the **Analysis** options on the right of your screen, open the heading to **Summarize Data** and select the **Summarize Within** option (or search 'Summarize within' in the search bar).  
![AGOL workspace](img/analyze/step6a.PNG)<br>  

4. In the _Summarize Within Dialogue_ select the following options. Note that most options and tools have a blue circle you can hover over for more information.  
    1. _Features to Summarize_: **Tree Inventory**  
	2. _Summary Area_: **Space Inventory- Interactive Landscapes**      
    3. _Field Statistics_: **Total Height**, **Min, Max, Avg**  
    4. _Group By_: **Species**, add **minority, majority** and **percentages**    
    5. Name the file something meaningful including your initials.    

5. Click the _Run Analysis_ option, wait for the data to be added to the map  
6. Explore the Attribute table and pop-ups for the new layer you have created.   
7. Your workspace should look something like:  
  ![AGOL workspace](img/analyze/step6b.PNG)<br>  
  
8. Don't forget to **Save** your edits. 
9. Consider how you could use this information in a Story Map.  


That’s it! We now have the building blocks to create a **StoryMap** in the next section!  

