### Export to DXF

The Infobox menu contains an application that converts the `* .fpc` file to the `* .dxf` mechanical format. Open the circuit board project dxf_export.fpc which is located in the "examples" folder. Select `Export->DXF` from the Infobox right-click menu. In `FreePcb-2-032`, the program window looks like this:

![](pictures/dxf_exp_1.png)

If you want to export copper tracks, pads, or circuit boards, simply select the checkboxes in the corresponding checkboxes and click OK. The file will be created in a separate folder in the same directory as the original `* .fpc` file.
In addition to simply exporting to a flat drawing, this program is able to export volumetric primitives, such as a rectangle, a triangle, an oval, extruded along the Z axis. These shapes are attached to the footprint of the part and you get something like a library of cases that is saved in the directory with the executable file: `..\ FPC_EXE \ FreePcb_ExportDXF \ dxf_lib.csv`
To browse \ edit the library of 3d cases, click the Edit DXF library button. A new window will appear:

![](pictures/dxf_exp_2.png)

To make an overview of all the details in the project, click the Draw button, which is located at the bottom of the program window. By default, this button draws on the screen all the enclosures that are present in the project. To start editing a specific part, simply click on its drawing with the left mouse button. Then go to the editor by clicking on the Editor tab. Here on the left is a table, in each line of which the parameters of the figure that you want to display in the DXF file are set, as well as the binding of this figure to the part on the circuit board. The leftmost column is this binding to the figure, that is, the text in the first column is nothing more than the Package attribute of the part, which you can view / change in the FreePcb-2 part properties dialog box.

![](pictures/dxf_exp_2.png)

In the second column, you specify the shape of the figure. It can be:

* Rect
* Oval
* Triangle
* Sector
* Pin
* Arc
* Silk

In the third, fourth, and fifth columns, you specify the sizes of X, Y, and Z, respectively

In the sixth, seventh and eighth columns, you specify the angle of rotation of the figure (XY, XZ and YZ, respectively)

Finally, in the last three columns, you specify the displacement of the figure along the X, Y, and Z axes
