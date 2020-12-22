_Warning! This document has been translated into English from another language. The author is not responsible for the inaccuracy of the translation, if any._

***
### `Introduction`

* 1 to 16 copper layers
* Board size up to 60 inches by 60 inches
* Uses English or metric units (i.e. mils or mm) for most functions.
* Footprint Wizard and Footprint Editor for creating or modifying footprints
* Import and automatic export of PADS-PCB lists when saving file
* Import and export to mechanical format DXF
* Import and export Pcad ASCII files (is maintained by Altium)
* Exports extended Gerber files (RS274X) and Excellon drill files
* Design rule checker
* Autosave

### `View`

[![PCB](/pictures/img2.png)](https://freepcb.dev)

***
### `About`
FreePcb is a unique PCB design program with a function key interface. Version 2.0 presented on this site is a fork of version [1.359](http://freepcb.com), taken for revision in 2014. FreePcb-2 contains new features not available in version 1.359 and provides more freedom for circuit board developers. If you don’t want to waste your time mastering complex PCB design applications, download FreePcb-2, which can do a lot of what CADs can do, but is easy to learn and takes up little disk space on your computer. FreePcb-2 does not have a huge number of buttons as in other CAD systems, the purpose of which is not immediately clear. There are only 9 buttons (F1 ... F9), the Functions of which change depending on the type of the selected element (part, vertex of trace, segment and etc.), so FreePcb-2 can be studied even without instructions. There is also a right-click context menu with additional features. In FreePcb, you can create a netlist manually by adding parts and then connecting their pins. But you can also import a netlist in the PADS-PCB format from any external circuit editor, for example [TinyCad](https://www.tinycad.net). The first version of the [schematic editor](https://freepcb.dev/ECDS.html) is being prepared for release, which will work in tandem with `FreePcb-2-033` and is scheduled for release in 2020

If at least one of the following programs is installed on your computer:

* `ViewMate` 

[![](pictures/pentalogix_logo.jpg)](https://www.pentalogix.com/)

* `GerberLogix` 

[![](pictures/EasyLogix.png)](https://www.easylogix.de/) 

* `Gerbv (GEDA's Gerber Viewer)` 

[![](pictures/gerbv_250x60.png)](http://gerbv.geda-project.org/)

You will be able to upload gerber files into it for viewing, using the menu command directly from the FreePcb-2 window. (available from November 26, 2019)

![](pictures/gerbv.png)

***
### `Advantages`
1. accessibility (it does not have a limit on the number of pins, footprint libraries or any other parameters),
2. ease of learning (creating a manual for version 2-033),
3. reduction of time for the development of printed circuit boards (A distinctive feature of FreePcb and FreePcb-2 from other PCB-editors is an interface using function keys, which speeds up the process of editing a printed circuit board for an experienced user),
4. saving computer memory (takes ~ 50MB hard drive),
but at the same time includes almost all the tools needed for professional use. 

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

* (schematic editor) Schematic Constructor 1.1 lists "Value @ Footprint" parts that have ever been used in other projects. This list is loaded at the first call of the import window (F1 key) and in general significantly improves the function of importing a part from another project

* Added "pour copper" button so that you can pour copper area without using external program Areas.exe. Select side of ghost area and  press F4 button

* Option "drag the part here by pulling the ratline". When you place parts in a new project, it is very common for related parts to be far apart and off the screen. Highlight the ratline and press F5 to get that part

* Optimized scrolling for large projects

* Moving stub tracks with the part while moving the part. If a track connects the pins of the same part, then it will also move with the part. To bypass this option, select the pin of the part and then move the part with the keyboard arrows

* Highlighting details on the board from the schematic editor. Select the parts with the mouse frame and click the View -> Switch to PCB menu

* "Swap the pins of a part on a printed circuit board." The long-awaited function has been completed. In FreePcb2.1, you can swap two pins of the same part in the PCB editor (most often this is needed, for example, for microcontrollers), and the program will automatically change this in the circuit file. The schematic file and the PCB file should usually be stored in the same folder and have the same file name, such as Example.fpc and Example.cds. If the schematic file is open while changing pins, the program will restart it after making changes. If the schematic file is modified and not saved, the program will warn you and the process will be interrupted until you save the schematic file.

***

![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/cloud-down.png) 

# [Download](Download.md)

![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/По%20рукам.png) If you like, post [this](pictures/logo.png) picture on your website. Have fun using FreePcb-2.

You can participate in the improvement of the application. Feel free to write a message regarding working with FREEPCB2 so that we can release the official version FreePcb2.1 & Schematic Constructor 1.1 as soon as possible. Working together is always more efficient.

***
### `Partners`

[![](pictures/LLC_IP.png)](https://interpribor.com) 
[]([![](pictures/LOCARUS_LOGO.png)](https://locarus.ru) )
[![](pictures/jlcpcb.png)](https://jlcpcb.com) 
[]([![](pictures/pselectro.png)](http://www.pselectro.ru) )
[![](pictures/arius.png)](https://www.arius.com) 
[]([![](pictures/bittele.png)](https://www.7pcb.com) )
[![](pictures/zofzpcb.png)](https://zofzpcb.com) 

_[to learn more...](partners.md)_

***
### `Contacts`

* [User forum](https://groups.io/g/freepcb) You can use the forum of the first official version of FreePcb, which has now been ported to groups.io, and ask your question there. 
* If you have any suggestions related to FreePcb-2 or you do not want to submit your question for public review, send to email `duxah@yahoo.com`.
* If you want to improve the translation of this document, please send your file by email
* If you have your own libraries of footprints that you are ready to share with everyone, then you can send them to me, and I'll post them on the site.
* FreePcb-2 is involved in the development of industrial appliances and has been thoroughly tested to prevent errors. But if you find an error, please send me a report by e-mail with a description and screenshots so that I can fix it as soon as possible.

***
### `useful links`
1. [License](LICENSE)
2. [FreePcb user guide 1-359](https://github.com/Duxah/FreePCB-2/raw/master/FreePcb-2/bin/doc/freepcb_user_guide.pdf)
3. [FreePcb-2 "How to.." guide 2020](/How_to.md)
4. [How to make a schematic design](/How_to_cd.md)
5. [About this development fork](/About_development.md)
6. [For software developers](developers.md)

***
### `Get started with FreePcb-2`

[Start learning FreePcb-2](/How_to.md)

The text of this site is a translation from foreign language using Google inc. ©2019-2020
