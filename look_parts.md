## how the parts might look in the Schematic Constructor 1.1

![Free PCB schematic capture](pictures/example.png)

Or Multiple part:

![Circuit Design Software](pictures/multi_part_2.png)

## How to create a complex part? (since v1.1)

Sometimes in multi-channel diagrams it is convenient to create complex parts to duplicate repeating blocks. A complex part is a small electrical diagram inside the part of the Schematic Constructor. In general terms, this is created like this: On a separate page that is not included in any netlist, draw the part with the leads inward (and not outward, as in a normal part), set the name of the part (this is the RefDes attribute), for example CHANNEL. 

![schematic design example](pictures/look_part1.png)

Place a circuit diagram of ordinary parts inside this part and connect it to the leads of the part: CHANNEL.

![Hierarchical symbol](pictures/look_part2.png)

![Schematic Constructor](pictures/look_part3.png)

On the main page where you have the electrical diagram of the project, draw a rectangle. Then, by selecting the side of this rectangle and pressing F1, in the polyline attributes dialog box, select the Outline of complex part script. 

![Schematic drawing Software](pictures/look_part6.png)

Then, next to the contour line of the complex part, draw a pin polyline in contact with the contour polyline, and in the polyline attributes dialog box, select the Pin of complex part script and enter the appropriate parameters.

![Free schematic editor](pictures/look_part7.png)

Draw the rest of the pins and repeat the procedure (pin 2 and pin 3) 

![Electronic Circuit Design Software](pictures/look_part5.png)

All parts of this channel in the netlist will be named as follows: R1A, R2A (Suffix A will be added)

![Reference designator](pictures/hint_1.png)

Now you're done.
