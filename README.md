# Workshop on Making Color Lithophane Lightbox
## Objective:
The purpose of this workshop is to introduce participants to the fascinating world of custom colored lithophanes, merging traditional craftsmanship with modern 3D printing technology. Participants will have the opportunity to create their own unique colored lithophane light box, combining artistry, design, and illumination.  
  
![alt text](https://github.com/zaayush/Prototyping-Lab-Workshop/blob/main/LithoLightBox.jpg)
## Workshop Overview:
### Duration: 2-day, Day 1: 2 Hour + 3D Print Time and Day 2: 30 min (Just for assembly).  
### [YouTube link](https://www.youtube.com/watch?v=4FvtQOHzus4&t=181s)  
### Materials Provided:  
•	Digital Instruction Manual   
•	COB LED Strip – 5v  
•	Type C power module  
•	3D Printing supplies/equipment.  
•	Laser Cutting supplies/equipment.  
### What Participants Will Take Home:  
•	Personalized colored lithophane light box (a complete custom product)  
•	Knowledge and skills in 3D printing lithophanes, fabrication, and coloring techniques  
•	Skills to optimize slicer settings to print fast and efficiently.  
•	Workshop Instructions (digital file) with resources.  
## Workshop Instructions:  
### Day 1: Image to STL and Design   
1.	Generating STL for Lithophane using Image file:  
-	Go to the website https://itslitho.com/  
-	Click on “Get Started” button.  
-	On the top left side of the web page click on “UPLOAD” button.  
-	Click on the “UPLOAD” button under the Upload Image section and then select your desired image. (Note: We will make a square lithophane so make sure the image you select fits in a square the way you want)  
-	You’ll see the image you uploaded, then click on “MODEL” button.  
-	Update the following settings:  
o	Shape: Plane  
o	Width: 100mm (Size in based on the box)  
o	Height: 100mm  
o	Min Thick: 0.8mm  
o	Max Thick: 3.2mm  
o	Frame Options: Frame  
o	Thickness: 2mm  
o	Depth: 3mm  
o	Quality Options – mm per pixel: 0.1mm  
o	Image Options – Positive: Enabled  
-	Click on the “DOWNLOAD” button at the bottom right corner.  
-	Then, you’ll see a download page popping up, click on “Lithophane” button to download the STL file.  
-	Here, you can also click on “Color Lithophane” button to download the color filter image file.  

2.	Setting up the slicing parameters on Cura:  
-	Open the STL file which you just downloaded from the website.  
-	Select the “Fine” Profile and then choose the option “discard any changes”.  
-	In the Walls section, enter the wall count as 50.  
-	In the Top/Bottom section, change the # of top layer to 2 and the # of bottom layer to 2.  
-	Make sure that the generate support option is NOT checked.  
-	Select the Build Plate Adhesion Type as “Brim”.  
-	Using the search bar in the Printer settings, search for the setting “Retraction”, and in the section “Travel” uncheck the retraction setting.  
-	Now, click on “Slice”, and then verify from the “Preview” tab that model is having only walls for both outside and inside. (Use the scroll bar at the right edge of the window).  
-	Once all the steps above are completed, save your sliced file to a PD and 3D print it.  
 
3.	Making the Light Box  
-	Download the SVG files for Laser cutting the box from here. (Size 100x100mm)  
-	Use “Birchwood – 3.175mm” as the material. (Medium Cherry Hardwood in Glowforge)  
-	Now connect the Type-C Power module to the LED strip and/or a switch (if you want).  
-	Before assembling the entire box, please stick the LED strip at the back panel and fix the Type-C power module using glue gun. Make sure the port of the power module aligns to the hole in the box frame.   
-	Now assemble the sides of the box and keep one of the side panels open to slide in the lithophane.   
-	Now, you should have a partially assembled light box, so test out the light box with a demo lithophane and make sure the image is visible when you light it up.  
### Day 2: Final Assembly   
•	Collect your 3D print from your respective 3D printer and slide it into the light box you made earlier.  
•	Stick the last side panel which you kept open for sliding in the final lithophane.  
•	There you have it! Enjoy!!  

