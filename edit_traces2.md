## How to edit copper traces

It may be necessary to insert a two-pin part in the route branch, so that, for example, then divide the net into 2 different ones.

I will show you with a simple example how to do this. 

Put the part in the place where there will be a gap, then add two [additional nodes](add_vertex.md) to the segment of the route. 

![How to edit copper traces](pictures/edit_tr9_1.png)

[Connect](edit_traces.md) these nodes to the pins. 

![How to edit copper traces](pictures/edit_tr9_2.png)

Now route these segments (when the rat line segment is highlighted, press `F4(Route)` to start dragging the trace)

![How to edit copper traces](pictures/edit_tr9_3.png)

Now delete the extra segment by pressing the `F9(Delete Segment)` button.

![How to edit copper traces](pictures/edit_tr9_4.png)

Now you can [divide](split_net.md) the net into 2 different.

