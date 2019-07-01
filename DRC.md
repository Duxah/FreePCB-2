### How to make DRC?
FreePCB has a Design Rule Checker that checks your project for compliance with a set of design rules. Selecting Tools > Design Rule Check pops up the following dialog:

 ![](pictures/DRC.png)

trace width           	| The minimum trace width allowed

pad to pad            	| The minimum distance from the edge of one pad to another on a different net (a warning is displayed if the distance is less on same net)

pad to trace          	| The minimum distance from the edge of a pad to a trace on a different net

trace to trace        	| The minimum distance from the edge of a trace to a trace on a different net (this is the initial clearance value of the SET_CLEARANCE function)

hole to pad or trace  	| The minimum distance from the edge of a hole to a pad or trace on a different net (a warning is displayed if the distance is less on same net)

hole to hole          	| The minimum distance from the edge of a hole to the edge of another hole

annular ring (pins)   	| The minimum width of copper surrounding a hole for a pin

annular ring (vias)   	| The minimum width of copper surrounding a hole for a via

board edge to any copper 	| The minimum clearance between any copper feature and the edge of the board

board edge to hole    	| The minimum clearance between the edge of a hole and the edge of the board

copper area to copper area 	| The minimum clearance between copper areas, and also between a copper pour (full hatch pattern) and another object on a different net
