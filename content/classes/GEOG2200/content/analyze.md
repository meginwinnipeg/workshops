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
In this step we will be creating two (2) different type of maps, and an additional feature layer to support our story.  

- Heat map  
- Proportional symbology  
- Summary Statistics 

---

## 1. Access your **Content** workspace to create your own feature service:  
 
1. Navigate to UM's ArcGIS Online Portal (https://univmb.maps.arcgis.com) and ensure you are signed in.  
2. Access the **Content** area by clicking on that option in the top navigation.  
![AGOL workspace](img/analyze/step1a.PNG)<br>  

 
## 2. **New Item** to create a feature service from a .csv file:  
We want to add our tree data to our Content area in the form of a feature service so that we can publish content with it.    

1. Select the **New Item** option from the top left of your content area.  
![AGOL workspace](img/analyze/step2a.PNG)<br>
2. From the options that appear we want to select the **From your device** option to select to .csv file from your downloaded data.  
![AGOL workspace](img/analyze/step2b.PNG)<br>  
 
3. **Navigate** to your TreeInventory_KingsPark.csv file and add it.  
In the series of dialogue boxes that follow:  
    1. Select the optiom to create a **hosted feature layer** from the .csv.  
	![AGOL workspace](img/analyze/step2c.PNG)<br>   
	2. Double-check your field types and location fields: _Diameter at Breast Height_ should be a **double**, _Latitude_ and _Longitude_ set as the **double** fields.
	![AGOL workspace](img/analyze/step2d.PNG)<br>  
	3. Ensure the **location type** matches the selected location fields.  
	![AGOL workspace](img/analyze/step2e.PNG)<br>  
	4. _Title_: **TreeInventory_yourinitials**, _Tags_: **2200_yourinitials**   
     ![AGOL workspace](img/analyze/step2f.PNG)<br>  

4. Click the _Save_ button, and wait while your service publishes.  
5. You should now have your own **feature service** to use that looks something like:  
![AGOL workspace](img/analyze/step2g.PNG)<br>  

 
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

