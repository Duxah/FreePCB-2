### Export P-CAD (ACCEL ASCII)

For successful export to the Tango P-cad format (Altium supported), you need to know a few nuances.

* Move the origin to the lower left edge of the board to exclude the negative coordinates of any objects from the design.

* RefDes should not contain special characters, such as .- \ /% # *, etc.

* Multipins will be divided into different pins since not supported in this format

* Inverse polygons are not supported and will be converted to regular polygons.

From the right-click menu of the Infobox window, select the Export P-cad menu item
