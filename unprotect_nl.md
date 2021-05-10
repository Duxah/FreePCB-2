## How to unprotect netlist?

 ![](/pictures/nets_menu.png)
 
There is an option in the main menu Project->Nets->NetlistProtected (Uncheck this box )
 
 ![](/pictures/nl_protected.png)
 
When netlist is protected, it is impossible:

* delete a part if at least one pin is connected
* change the part number
* connect pin to netlist
* remove pin from netlist

Your should know that:

* Parts with just one pin can be added to the netlist by dragging connection, and can also be removed from the PCB, if desired.
* Footprint can be changed if the number of pins does not become less.

