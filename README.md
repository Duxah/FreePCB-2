
***
### `Introduction`

* 1 to 16 copper layers
* Board size up to 60 inches by 60 inches
* Uses English or metric units (i.e. mils or mm) for most functions.
* Footprint Wizard and Footprint Editor for creating or modifying footprints
* Import and automatic export of PADS-PCB lists
* Import and export to mechanical format DXF
* Import and export Pcad ASCII files
* Exports extended Gerber files (RS274X) and Excellon drill files
* Design rule checker
* Autosave

### `View`

FreePcb-2 is suitable for medium circuit board design. Here, as an example of the view of the program window, a project of two printed circuit boards is shown, which contains more than 2000 pins (design for INTERPRIBOR LLC)

[![PCB](/pictures/img2.png)](https://interpribor.com)

***
### `About`
The FreePcb-2.000 or later program presented on this site is a development branch of version [1.359](http://freepcb.com), published in 2010. FreePcb-2 contains new features not available in version 1.359 and provides more freedom for circuit board developers. Start working with FreePcb-2 right now to feel the difference. If you don’t want to waste your time mastering complex CAD applications, download FreePcb-2, which can do almost everything the same, but is easy to learn and takes up little disk space on your computer. FreePcb-2 does not have a huge number of buttons (as in other CAD systems), the purpose of which is not immediately clear. There are only 9 buttons (F1, F2 ... F9), the Functions of which change depending on the type of the selected element, so FreePcb-2 can be studied even without instructions. There is also a right-click context menu with additional features. In FreePcb, you can create a netlist manually by adding parts and then connecting their pins. But you can also import a netlist in the PADS-PCB format from any external circuit editor, for example [TinyCad](https://www.tinycad.net).

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
2. ease of learning (creating a manual for version 2-032),
3. reduction of time for the development of printed circuit boards (A distinctive feature of FreePcb and FreePcb-2 from other PCB-editors is an interface using function keys, which speeds up the process of editing a printed circuit board for an experienced user),
4. saving computer memory (takes ~ 50MB hard drive),
but at the same time includes almost all the tools needed for professional use. 

***
### `Latest improvements and new features`

`Version 2-032 (2019-11-11):`

* When using the measurement tool, the angle is displayed

![](/pictures/m_tool4.png)

* Added testing of copper vector areas for breaking (Main menu DRC -> Check copper areas)

![](/pictures/torn.png)

* InfoBox shows the net in the mode of dragging a connection to a pin, for convenience when manually connecting pins

![](/pictures/IB_drag_con.png)

* InfoBox shows the number of parts in the filter

![](/pictures/IB_num_parts.png)

* R button performs filter reset function

* Pin status display is now much better

(this version will be available from November 11, 2019)

![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/cloud-down.png) The [download v2-032](https://github.com/Duxah/FreePCB-2/archive/master.zip) (portable version from 11/11/2019) includes a folder with the program, manual 1.359, footprint libraries, examples of printed circuit boards, a description of the 2.032 file format for developers.

![](https://raw.githubusercontent.com/Duxah/FreePCB/master/pictures/По%20рукам.png) If you like version 2-032, post [this](pictures/logo.png) link on your website. Have fun using FreePcb-2.

You can participate in the improvement of the application. Feel free to write a message regarding working with FREEPCB so that we can release the official version 2-032 as soon as possible. Working together is always more efficient.

***
### `Partners`

[![](pictures/LLC_IP.png)](https://interpribor.com) 
[![](pictures/LOCARUS_LOGO.png)](https://locarus.ru) 
[![](pictures/jlcpcb.png)](https://jlcpcb.com)

[![](pictures/pselectro.png)](http://www.pselectro.ru) 
[![](pictures/arius.png)](https://www.arius.com) 
[![](pictures/bittele.png)](https://www.7pcb.com)

_[to learn more...](partners.md)_

***
### `Contacts`

* [User forum](https://groups.io/freepcb) You can use the forum of the first official version of FreePcb, which has now been ported to groups.io, and ask your question there. 
* If you have any suggestions related to FreePcb-2 or you do not want to submit your question for public review, send to [email](https://freepcb.online/Discuss/).
* If you want to improve the translation of this document, please send your file by email from the site [freepcb.online](https://freepcb.online/Discuss/)
* If you have your own libraries of footprints that you are ready to share with everyone, then you can [send them to me](https://freepcb.online/Discuss/), and I'll post them on the site.
* FreePcb-2 is professionally used by the author in a large commercial company, and is thoroughly tested to prevent bugs. But if you find a bug, please send a report with a description and screenshots to me by [e-mail](https://freepcb.online/Discuss/), so that I can fix it right away

***
### `useful links`
1. [License](LICENSE)
2. [FreePcb user guide 1-359](https://github.com/Duxah/FreePCB-2/raw/master/FreePcb-2/bin/doc/freepcb_user_guide.pdf)
3. [FreePcb-2 "How to.." guide](/How_to.md)(is underway)
4. [About this development branch](/About_development.md)
5. [For software developers](developers.md)

***
### `Get started with FreePcb-2`

[Start learning FreePcb-2](/How_to.md)

The text of this site is a translation from Russian using Google inc. ©2019
