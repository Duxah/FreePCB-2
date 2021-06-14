# FreePcb-2-1

_Warning! This document has been translated into English from another language. The author is not responsible for the inaccuracy of the translation, if any._

***
### `Latest improvements and new features`

`FreePcb-2.1:`

* A checkbox has been added to the project options dialog box to control the display of merge names during editing. You can now turn off silk-screening altogether while routing the board

![](pictures/presentation_1.png)

* Now, while dragging a group of parts, you can break off the ratlines (which stretch) connected to the traces so as not to do this for each trace separately. The netlist, of course, remains unchanged.

![](pictures/presentation_2.png)

* (schematic editor) Added to the schematic editor a command to auto-update the file modification date. In the "description" attribute of the polyline, you must enter the following text `00.00.00|YYYY.MM.DD`(to show the date in international style) or like this: `00.00.00|MM/DD/YYYY`(to show the date in American style). For an example see the Template.cds file that comes with FreePcb-2

* (schematic editor) Also added other commands to the polyline attributes window. Complete list of commands:

  - Date
  - Link to part
  - Complex part polyline
  - Complex part pin
  - E-bus pin
  - BOM table inside a rectangle
  - Project file path

* (schematic editor) The PartList dialog now runs in the background and has a part search bar. Added a button to generate a TXT file from the list

* (schematic editor) Added a button to generate a BOM file

* Batch editing selected vias

* You can copy a copper area pattern to mechanical layer. Select the area side and press F9

* Added option for PNG rendering settings in CAM dialog

* Added checkbox for highlights layer selection in CAM dialog

* (schematic editor) `Schematic Constructor 1.1` lists "Value @ Footprint" parts that have ever been used in other projects. This list is loaded at the first call of the import window (F1 key) and in general significantly improves the function of importing a part from another project

* Added "pour copper" button so that you can pour copper area without using external program Areas.exe. Select side of ghost area and  press `F4` button

* Option "drag the part here by pulling the ratline". When you place parts in a new project, it is very common for related parts to be far apart and off the screen. Highlight the ratline and press `F5` to get that part

* Optimized scrolling for large projects

* Moving stub tracks with the part while moving the part. If a track connects the pins of the same part, then it will also move with the part. To bypass this option, select the pin of the part and then move the part with the keyboard arrows

* Highlighting parts on the board from the schematic editor. Select the parts with the mouse frame and click the `View -> Switch to PCB` menu or press `F9`

* "Swap the pins of a part on a printed circuit board." The long-awaited function has been completed. In FreePcb2.1, you can swap two pins of the same part in the PCB editor (most often this is needed, for example, for microcontrollers), and the program will automatically change this in the circuit file. The schematic file and the PCB file should usually be stored in the same folder and have the same file name, such as Example.fpc and Example.cds. If the schematic file is open while changing pins, the program will restart it after making changes. If the schematic file is modified and not saved, the program will warn you and the process will be interrupted until you save the schematic file.

* You can open the project folder by pressing F5, in the "nothing selected" mode.

***
### `Contacts`

* [User forum](https://groups.io/g/freepcb) You can use the forum of the first official version of FreePcb, which has now been ported to groups.io, and ask your question there. 
* If you have any suggestions related to FreePcb-2 or you do not want to submit your question for public review, send to email `duxah@yahoo.com`.
* If you want to improve the translation of this document, please send your file by email
* If you have your own libraries of footprints that you are ready to share with everyone, then you can send them to me, and I'll post them on the site.
* FreePcb-2 is involved in the development of industrial appliances and has been thoroughly tested to prevent errors. But if you find an error, please send me a report by e-mail with a description and screenshots so that I can fix it as soon as possible.

***

The text of this site is a translation from foreign language using Google inc. ©2019-2020
