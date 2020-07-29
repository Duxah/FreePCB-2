### `Schematic Constructor v1.0 (circuit design software)`

Program features:

* Support for multi-page schematic design

* Support for multi-graphic part symbols

* Export of netlist to PADS-PCB (supported by OrCad KiCad DipTrace Altium Eagle EasyEda, etc.)

* No component libraries required

* Ability to move part pins directly in the main schematic editor window.

* Importing a bitmap.

* Continuous numbering of parts

* Search for a part by attribute and import from adjacent projects

* Synchronizing attributes between pages

* DRC check

![](pictures/ECDS.gif)

### `Philosophy`

The multi-page editor is designed to be able to quickly create small electronic circuits without any libraries. Using a simple tool - polylines, you can draw a schematic diagram and create a netlist.

With Schematic Constructor, you no longer need to create graphic symbol libraries. The program is designed in such a way that there is no graphic symbol editor. This has some advantages, for example you can rename and move part pins right in the workspace. The graphic symbol for the same part may differ from project to project. If in one project you use microcontroller pins, in another you do not use them, but use completely different pins, then there is no need to save a graphic element to the library for each circuit. When you create a project for the first time, you draw the details of that project. Then, creating a second project, you can import parts from previous schematic projects created earlier in the Schematic Constructor into it. The program will search for a part by name or another attribute that you specify in the dialog box, and after finding this component will insert it into your current project. This way you don't have to go through the projects to find a part, but you should keep the project folders in one shared folder.

Special attention should be paid to the topic of hidden text in the schematic design. You should avoid hidden texts in the project, because they are not displayed when printing the diagram on paper, therefore it can lead to errors. Initially, the idea was to make it impossible to hide text attributes, such as the name of the footprint, or the name of the pin, but when using the editor in practice, this turned out to be a serious limitation, and this idea had to be abandoned. But on the other hand, an option was added to search for hidden footprint attributes to control them.

### `Connection to Freepcb`

Schematic Constructor and Freepcb-2 are self-contained software, they can be used separately from each other. By drawn a diagram in Schematic Constructor, you can design a PCB in another environment that supports PADS-PCB netlist import (eg KiCad). But if you choose FreePcb-2, then you have the advantage of being reminded when you make changes to the circuit, so you don't forget to import those changes to the PCB. Communication between the schematic editor and the PCB editor is done by exporting a netlist from the Schematic Constructor, and importing a netlist into Freepcb-2. The electrical diagram is the original source, so if after importing the netlist you want to modify the project (add / remove parts on the PCB), then you must start from the schematic diagram. This may seem like a kind of limitation, but this method of editing is classic and helps to avoid mistakes, unlike the option when you first make changes to the printed circuit board, and then to the circuit.

### `For whom`

Schematic Constructor is ideal for small projects. At the moment, the editor supports 8 pages, which can be linked (related numbering of parts) or stand-alone (when duplication of RefDes between pages is allowed). You can then export these pages to a PDF file. The orientation of the pages in the PDF file is automatically selected according to the layout orientation (Typically, the layout along the Y axis is less than the X axis - this is landscape orientation). The number of pages may be expanded in the future.

The program is equipped with an automatic check of design rules before creating a netlist. Checking the design for errors is divided into 2 stages. First, the networks are checked for contact and other errors during the generation of networks, and then the names of parts and pins are checked using the DRC dialog box, in which there is also control of the clearance of texts on the polyline. The output is a netlist, BOM file and parts list.

Support department:

If you have a question or suggestion related to Schematic Constructor, do not forget to write to duxah@yahoo.com

### `License`

Schematic Constructor is distributed under the FreeWare license. (free for individuals and organizations)

### [`Donate to development`](https://paypal.me/freepcb2)

You can donate to the freepcb.dev resource fund. The domain is not free. You can deposit any amount of money by assessing your profit and the share of participation of Schematic Constructor or freepcb-2 in your business. If you are using FreePcb-2 not in commercial interests, then you can do something useful, for example, place a link on your site, or make a video instruction for the programs. This is all considered a donation. All your donations are needed to support freepcb.dev.

The first release is scheduled for 2020

