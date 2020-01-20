When the PCB project is put into production at your enterprise, it makes sense to store in a special library the nomenclature of parts identified by the combination of VALUE & PACKAGE parameters. You can at any time through Infobox find out in which project this or that part was used.

1) Open the circuit board project whose parts list you want to export.
2) Remove from the list parts that do not have the Value and Package attributes, for this, type the line! --- in the filter box as shown in the figure.
3) Create a value library file by selecting Add Part Values ​​to Storage from the right-click menu.

These files are created in the directory with the infobox application in the VPL folder (which stands for Value & Package List). They can not be moved because they are also used by other applications (e.g. 'Compare PCB assemly kit'). You can open these files with notepad and browse.

Now, to force Infobox to search for details from the Value & Package repository that we created, you just need to clear the list of infobox details.

1) Type some kind of confusion in the REF filter box as shown in the figure. Now the list is empty.
2) Enter the desired attribute in the VALUE or PACKAGE box.

When the infobox parts list is empty, the infobox searches for elements among the VPL libraries. The background color turns gray - this means that the elements are found in the VPL library and not in the current PCB project. By clicking on any list element in the header of the info box, we see the name of the VPL file.
