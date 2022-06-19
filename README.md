# FreePcb-2.3

***

_This document has been translated into English from another language (the author is not responsible for the inaccuracy of the translation, if any)_

***

### `Improvements`

`FreePcb-2.3:`

* Improved display of the merge name

* Open the PCB file and from the PCB editor switch to the schematic editor by selecting the "View-> Switch To PCB" menu. Now in the PCB editor, when you hover the mouse cursor over a pin, the same pin is highlighted in the schematic 

* The outline line is always shown as a solid fill in the color of the "Board Outline" layer for visual convenience

* Added "Protection" option to the "Project" menu. This can be useful after the design and order of the printed circuit boards from the factory has been completed. By enabling protection, you will not be able to edit the file 

* The netlist generated from the schematic editor is automatically loaded in the PCB editor by clicking the YES button 

* In the footprint of a part, you can place a cutout in the board. Wherever you move the part, the cut will move with it. Press F1 to add a cutout (in the footprint editor)

* The solder mask on the pins is displayed in Transparent mode

* Automatic alignment to ratlines. When positioning, the pins of different parts connected to each other are almost always located on the same axis - horizontal or vertical. for example, when we put a capacitor near the microcontroller leg. Previously, to align, you had to use the Alignment menu or press the Align softkey. Now this happens automatically if the ratline offset is less than the grid spacing. Select a sufficiently large Placement grid at the top of the window - for example 0.5mm to see how this function works. And if you do not want to use this function, then select a smaller grid step, or temporarily turn off the visibility of the Ratlines layer

* If you want to make all layers visible, then you can do it by pressing a single button on the keyboard: [~] it is located next to the [1] button. Click again to restore the previous visibility of the layers. If your project contains more than 2 layers, then press this button a third time, and only the inner layers will be shown. 

* You can keep track of the full length of a net or trace when you move a trace segment using the arrow keys on your keyboard. This parameter is displayed in the status bar at the bottom. The same happens when you move a group of selected trace segments.

`Schematic Constructor-1.3:`

* Added a page comparison option to the PROJECT menu. The partlists and netlists on similar pages can be compared and then the differences can be displayed in the listbox. Double click on the list allows you to jump to the object. Double click on the list allows you to jump to the object

![](pictures/presentation_1.png)

* Option to add standard objects using a frame with the mouse. To activate this menu press F3 (Add polyline) or F4 (Repeat polyline). You can quickly draw the following shapes:

1) Rectangle (F1 button)

2) Square (F2 button)

3) Circle (F3 button)

4) Oval (F5 button)

5) Ellipse (F6 button)

6) Rounded rectangle (F7 key)

7) Cloud (F8 button)

* Schematic Constructor 1.3 can read the names of footprints of other PCB editors (in particular, P-cad). If you are using the Schematic Constructor, but for some reason do not want to use FreePcb2 to route printed circuit boards, then you can specify the path to the library of your CAD system so that the Schematic Constructor downloads footprint names for itself and then suggests them in the drop-down list.

* Improved polyline properties editing menu. Select the side of the polyline and press F7 (Polyline properties). You can change the color of the polygon fill and make it lighter in relation to the color of the polyline itself (from 3% to 70% of the main tone). This option also works when exporting to PDF.

* The "Select" item and the "Unselect" item have been added to the main menu "Editing". Thus, you can select only polylines or only attributes, etc., in order to then edit the properties of a group of objects (for example change the text size or the polyline width)

* Added menu item "Open from project folder" to the "File" menu. This is a tree menu that allows you to directly open files from the project folder, bypassing the standard file dialog box 

* Improved "Magnet" function that helps when drawing connections between pins. The magnet works when the cursor approaches not only the vertex of the polyline but also its side

* Added "Protection" option to the "Project" menu. By enabling protection, you will not be able to edit the file 

* You can create project branches with index increments in filenames whenever you want to make new changes to a completed project. The branch folder will appear next to the project folder. This option automatically changes all texts that match the file name (increments the index) inside the new schematic and PCB file, so as not to do it manually. This "Item" is in the Project menu

* Lines style grid is displayed in Transparent mode 

* Improved import of parts from another project. You can check the "import with default polylines width" checkbox. In this case, the width of the polylines for the part will always be the same, as specified in the project options. And another super useful improvement is that if the pattern of the imported part is already present in the current project, then it is replaced from the local library

* Added "Component Description" item to the right-click menu on the part. The program can create a text file or a PDF file to store any information about a component (a component is for example "10MOhm @ 0805"). You can also attach an existing Datasheet of this part

* When there are many different netmarks in the project, you can quickly duplicate the netmark by selecting it by net name. The panel with label names is located on the left of the main window (under the selection mask). To activate this panel, right-click on any polyline with the network name attribute and select the "Add to favorites" menu

* You can see the pin list of any part. For example, if in your project you drew a microcontroller that, say, has 20 pins, but the maximum number in the pin names, say 30, then the program will display a list of 30 pins of which some will have the status "not connected" or "missing" ... (Right-click menu on any part, then "Get Pin List") 

* It is possible to hide all images attached to polylines. The picture will remain attached to the polyline, but will not be displayed on the display

* The dialog box for importing parts from other projects (F1 - Import Part) loads three attributes of the used parts - Value, Footprint and RefDes, so that you can find the part by prefix. For example, filter out in the list only capacitors (C) or resistors (R), etc. (before that there were only two attributes - Value and Footprint)

![](pictures/presentation_2.png)

* You can make PDF with the parts highlighted on the page. Just select the parts in the usual way (with the mouse frame, by calling Project >> RefList, or through the Partlist window) and open the print window to PDF. You can also print a fragment of a page to PDF by highlighting the fragment of the diagram along with text attributes. To do this, move the mouse frame twice over the same fragment (that is, select the fragment with the frame, then, without removing the selection, select it again using the frame). After that, open the print window to PDF via the File >> Print to PDF menu or press the standard CTRL + P combination

***

*The text of this site is a translation from foreign language using Google inc. ©2019-2021
If you want to improve the translation of this content, please send your file by email*
