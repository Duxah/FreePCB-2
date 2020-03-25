### `Loading part list`

In Infobox, you can download the partlist in the form of a text table. This will make it possible to compare the list of parts on the printed circuit board with the list of parts in the table by three attributes: RefDes, Value, Footprint. The table should contain three columns with attributes. The order of the columns can be: RefDes Value Footprint, or this: RefDes Footprint Value. This table can be generated from another application or can be created manually. Select the visibility of the CNetlist column in the Infobox settings and then there select the Load Partlist in the drop-down list as shown in the screenshot. When you upload a netlist, the comparison result will be displayed in the CNetlist column for each part. The result can take the following values:

1) `only on the board` - means that the part with this designation (RefDes) is not in the loaded netlist.
2) `only in netlist` - means that the part with this designation (RefDes) is not in the PCB design.
3) `footprint only` - means that a part with this designation (RefDes) is found in both lists of nets and the Value attribute is the same for them, but the footprints are different.
4) `value only` - means that a part with such a designation (RefDes) is found in both lists of nets and the Footprint attribute is the same, but the value attribute is different.
5) `footprint&value` - means that a part with such a designation (RefDes) is found in both lists of nets but the value and footprint attributes is different.
6) `all matches` - full coincidence of the RefDes, Value, Footprint attributes.

To correct differences between the attributes, click on the row of the selected part and press `F1` to open the window for editing the attribute of the part. For example, if we see the status 4 (Value only), then we need to fix the Value attribute.It must be borne in mind that the previous values of all attributes will remain in the Infobox list until you click the Save file button in the main FreePcb window (then the Infobox list will be updated).
