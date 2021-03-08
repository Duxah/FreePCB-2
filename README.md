_Warning! by downloading this repository in the usual way, you will get the most recent debug version, which may contain errors. To download the stable version go to the [download page](https://freepcb.dev/Downloads.html)_

***

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

FreePcb is a unique PCB design program with a function key interface. Version 2.0 presented on this site is a fork of version [1.359](http://freepcb.com), taken for revision in 2014. FreePcb-2 contains new features not available in version 1.359 and provides more freedom for circuit board developers. If you don’t want to waste your time mastering complex PCB design applications, download FreePcb-2, which can do a lot of what CADs can do, but is easy to learn and takes up little disk space on your computer. FreePcb-2 does not have a huge number of buttons as in other CAD systems, the purpose of which is not immediately clear. There are only 9 buttons (F1 ... F9), the Functions of which change depending on the type of the selected element (part, vertex of trace, segment and etc.), so FreePcb-2 can be studied even without instructions. There is also a right-click context menu with additional features. 

***
### [`Schematic Constructor`](https://freepcb.dev/ECDS.html)

In FreePcb, you can create a netlist manually by adding parts and then connecting their pins. But you can also import a netlist in the PADS-PCB format from FreePCB2 compatible Schematic Editor. See description on [this page](https://freepcb.dev/ECDS.html)

![](pictures/ECDS.gif)

***
### `Uploading Gerber files`

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
2. ease of learning (see useful links),
3. reduction of time for the development of printed circuit boards (A distinctive feature of FreePcb and FreePcb-2 from other PCB-editors is an interface using function keys, which speeds up the process of editing a printed circuit board for an experienced user),
4. saving computer memory (takes ~ 50MB hard drive),
but at the same time includes almost all the tools needed for professional use. 

***
### `Latest improvements and new features`

`FreePcb-2.2:`

* When you swap the pins in the PCB editor, the same pins are automatically swapped in the schematic file. (How to swap pins is described in [PDF-1.359](https://github.com/Duxah/FreePCB-2/raw/master/FreePcb-2/bin/doc/freepcb_user_guide.pdf)). If both pins have the text attribute "description", then they are also swapped. If one of the pins does not have this attribute, then you can change it in the pop-up dialog box.

* As you move a group of objects using the arrows on the keyboard, FreePcb2 automatically aligns the copper trace segments that start from the pins outside the group.

* You can add a grid of vias to the area of ​​any copper area. This function is in the top menu `Addition`

![](pictures/presentation_1.png)

* You can highlight any net by selecting it in the NETS dialog and then clicking OK.

* Improved switching of layer view. If you repeatedly press the 1 button on the keyboard, then the bottom copper layer will be enabled / disabled.

`Schematic Constructor-1.2:`

* You can disable JPEG images from being inverted when printed. For example, when you have a background scheme in JPEG format, you can make yourself a dark theme by inverting the colors of the picture (menu File-> Polyline picture-> Invert). In the PDF print dialog box, check the Disable inversion of pictures checkbox, in this case there will be no color inversion in the PDF file

* Multiple PCB files can be attached to a single schematic file. You can even assign an individual PCB file to each page. The settings are in the File-> Netlist Settings menu 

***

![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/cloud-down.png) 

# [Download](Download.md)
# [](unavailable.md)


![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/По%20рукам.png) If you like, post [this](pictures/logo.png) picture on your website. Have fun using FreePcb-2.

You can participate in the improvement of the application. Feel free to write a message regarding working with FREEPCB2 so that we can release the official version FreePcb2.2 & Schematic Constructor 1.2 as soon as possible. Working together is always more efficient.

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

The text of this site is a translation from foreign language using Google inc. ©2019-2021
