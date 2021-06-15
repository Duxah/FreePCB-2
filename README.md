# FreePcb-2-2

***

_Warning! This document has been translated into English from another language. The author is not responsible for the inaccuracy of the translation, if any._

***
### `Latest improvements`

`FreePcb-2.2:`

* If you want to add a via as a part, then create a part with one pin (as in previous versions of FREEPCB), and name it for example VIA1. Parts with the VIA prefix are processed by the program in a special way. They are not removed when importing an external netlist and are not present in BOM lists

* When you swap the pins in the PCB editor, the same pins are automatically swapped in the schematic file. (How to swap pins is described in [PDF-1.359](https://github.com/Duxah/FreePCB-2/raw/master/FreePcb-2/bin/doc/freepcb_user_guide.pdf)). If both pins have the text attribute "description", then they are also swapped. If one of the pins does not have this attribute, then you can change it in the pop-up dialog box.

* As you move a group of objects using the arrows on the keyboard, FreePcb2 automatically aligns the copper trace segments that start from the pins outside the group.

* You can add a grid of vias to the area of ​​any copper area. This function is in the top menu **Addition**

![](pictures/presentation_1.png)

* You can highlight any net by selecting it in the NETS dialog and then clicking OK.

* Improved switching of layer view. If you repeatedly press the 1 button on the keyboard, then the bottom copper layer will be enabled / disabled.

* When routing copper traces, you can place vias on vertex on the fly by pressing the F button

* You can switch the window from the PCB editor to the schematic editor by selecting the pin of the part on the PCB and pressing F9

* Completed the Alignment menu item located at the top of the window in the main menu. Select the first pin, then select the second pin, then select from the Alignment menu what you want to do with the position of the second pin (**By previous ...** or **Per 45 deg ...** items). Or like this: Select the first pin, then select the second pin, then select the third pin, then select from the Alignment menu to make with the position of the third pin (**To place between ...** or **Midpoint into ...** items)

* Automatic duplication of similar blocks on a printed circuit board when the designations of parts in the blocks correspond to the naming style of hierarchical symbols in **Schematic Constructor-1.1**. For example, block 1 contains parts R1A R2A, block 2 contains parts R1B R2B, block 3 contains parts R1C R2C, etc. By routing only the first block, you can apply the same design to other blocks. The function is located in the main menu **PROJECT**.

* You can copy the copper area cutout. Select the side of cutout and press F4. A copy of the cutout appears on the right. Press F4 again to move it. 

* Added the function of printing to PDF, the program generates 2 pages with the top and bottom views of the board. The layer order corresponds to the layer order on the display at the time of printing. To print a section, select this section along with copper tracks and other objects. Or select only parts to print highlighted parts. There is an option to automatically place the REF and VALUE texts in the center of the part. There is an option to automatically darken a pin named `1` `A` `A1` `a`

`Schematic Constructor-1.2:`

* You can disable JPEG images from being inverted when printed. For example, when you have a background scheme in JPEG format, you can make yourself a dark theme by inverting the colors of the picture (menu File-> Polyline picture-> Invert). In the PDF print dialog box, check the Disable inversion of pictures checkbox, in this case there will be no color inversion in the PDF file

* Multiple PCB files can be attached to a single schematic file. You can even assign an individual PCB file to each page. The settings are in the **File -> Netlist Settings menu**

* Improved switching of active page.

* You can create a part without a footprint attribute. In this case, this part will not be included in the netlist.

* In the Edit text dialog, the Right-Top Alignment checkbox has a third state

* In the Print to PDF dialog box, when you uncheck the Print All Pages checkbox, the PDF file name is set by the name of the current print page

* On the selected polyline segment, you can use the **Select similar polylines** right-click menu to find all similar polylines, and then use the new function  **Replace polyline pattern** (menu **Tools -> Graphic correction**) to select a different shape for these polylines. This is useful when, for example, you want to replace the shape of the net labels.

* When drawing nets it is useful to use magnetic vertices to hit the pin. The F4 button in the polyline drawing mode allows you to disable / enable the magnet. The same feature is now available in the mode of dragging polyline vertices, which makes it possible to completely abandon the use of global grid.

* Copying complex parts increments the suffix to eliminate duplication, similar to how it is done with regular parts 

* Improved jumping to parts from the schematic editor to the PCB editor and vice versa. On the highlighted designation, a menu of the right button **Start dragging part on PCB** appeared, which (as opposed to jumping to the part) moves the part to the center of the screen

* In the part import dialog box, in addition to the parts list, there is now a list of projects that use a specific part from the list, so when importing, you can select the file from which you want to import this part. Click on the path to the file and press the start button. But double-clicking on the file path will open this file and the program will jump to the selected part, which is also very useful.

* In the Part Attributes dialog (F1), you can select a footprint from your Freepcb library using an external library manager (the L button next to the FOOTPRINT attribute). Now the footprint selected there is automatically inserted into the Schematic Constructor dialog

![](pictures/presentation_2.png)

* Schematic editor 1.2 in the dialog box for importing a part (from another project) draws a part immediately when you click on the list, in addition, you can see in which projects which part was applied, open this project and jump to this part. If you have not worked with the Schematic Constructor yet, then I recommend that you familiarize yourself with version 1.2 in which the import of parts is made more advanced. 

***
### `Contacts`

* [User forum](https://groups.io/g/freepcb) You can use the forum of the first official version of FreePcb, which has now been ported to groups.io, and ask your question there. 
* If you have any suggestions related to FreePcb-2 or you do not want to submit your question for public review, send to email duxah@yahoo.com.
* If you want to improve the translation of this document, please send your file by email
* If you have your own libraries of footprints that you are ready to share with everyone, then you can send them to me, and I'll post them on the site.
* FreePcb-2 is involved in the development of industrial appliances and has been thoroughly tested to prevent errors. But if you find an error, please send me a report by e-mail with a description and screenshots so that I can fix it as soon as possible.

***

The text of this site is a translation from foreign language using Google inc. ©2019-2021
