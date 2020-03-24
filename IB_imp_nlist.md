`Loading extern netlist`

In Infobox, you can download a netlist from another project or a previous version of the current project in PADS-PCB format. This will make it possible to compare the list of parts on the printed circuit board with the list of parts in the netlist by three attributes: RefDes, Value, Footprint. It will also provide an opportunity to compare pin networks and see discrepancies between netlists. In the InfoBox settings, select the visibility of the CNetlist column and then there select Load Netlist in the drop-down list as shown in the screenshot. When you upload a netlist, the comparison result will be displayed in the CNetlist column for each part. The result can take the following values:

1) only on the board - means that the part with this designation (RefDes) is not in the loaded netlist.
2) only in netlist - means that the part with this designation (RefDes) is not in the PCB design.
3) footprint only - means that a part with this designation (RefDes) is found in both lists of networks and the Value attribute is the same for them, but the footprints are different.
4) value only - means that a part with such a designation (RefDes) is found in both lists of networks and the Footprint attribute is the same, but the value attribute is different.
5) all matches - full coincidence of the RefDes, Value, Footprint attributes.
