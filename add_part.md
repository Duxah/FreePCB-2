## How to add a new part?

Click F1 Add_part
 
![add pcb part](/pictures/add_part.png)
 
In the part properties dialog box, it is necessary to enter the name of the part in the REF line, and select a footprint from a library, the rest of the options are optional. You can immediately set the position of the part, as well as the side (TOP or BOTTOM) and the angle, for example, 45 degrees. The Package parameter is editable, but keep in mind that if you change it, the change will be applied to all parts using this footprint, because the Package is a property of the footprint, not the part.

`Useful information:` if the vertical slash character `|` is found in the REF line, then the letters and numbers following this character will not be displayed on the silk screen. In this way, you can make a copy of the printed circuit board while [maintaining the designation](pcb_view.md) of the parts in the layer of silk-screen printing.

