### Export to DXF

The Infobox menu contains an application that converts the `* .fpc` file to the `* .dxf` mechanical format. Select `Export->DXF` from the Infobox right-click menu. In `FreePcb-2-032`, the program window looks like this:

![](pictures/dxf_exp_1.png)

If you want to export copper tracks, pads, or circuit boards, simply select the checkboxes in the corresponding checkboxes and click OK. The file will be created in a separate folder in the same directory as the original `* .fpc` file.
In addition to simply exporting to a flat drawing, this program is able to export volumetric primitives, such as a rectangle, a triangle, an oval, extruded along the Z axis. These shapes are attached to the footprint of the part and you get something like a library of cases that is saved in the directory with the executable file:. . \ FPC_EXE \ FreePcb_ExportDXF \ dxf_lib.csv
To browse \ edit the library of 3d cases, click the Edit DXF library button. A new window will appear:

![](pictures/dxf_exp_2.png)

