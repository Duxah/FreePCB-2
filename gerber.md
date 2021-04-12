### How to export FreePCB-2 to gerber files

`Generate Drill and Gerber Files`

Select File -> Generate CAM files from the menu to open the gerber generation tool.
 
![](pictures/exp_gerb1.png)

In general, there are 8x layers you need to have a PCB fabricated:

* Top Copper + Top Solder mask  + Top Silkscreen 
*	Bottom Copper + Bottom Solder mask + Bottom Silkscreen 
*	Board outline 
*	Drill file

In the window that opens, select the layers:
 
 ![](pictures/exp_gerb2.png)
 
If there are inner layers, select them. If you don't know which layers, please check all layers, JLCPCB will help you to use the right layers. Then click the DEFAULT button(press the button several times to select one of the five standard folder names, or enter your name), and then click the CREATE FILES button.
 
 ![](pictures/exp_gerb3.png)
 
FreePcb-2 is configured to work with ViewMate, Geda's or GreberLogix. Check out the Gerber files by clicking on the Pentalogix's Gerber file Viewer button. How to configure this is described [here](Print.md).
 
 ![](pictures/exp_gerb4.png)
 
Or if you have another Gerber file viewer installed, then open the files manually in it. 

