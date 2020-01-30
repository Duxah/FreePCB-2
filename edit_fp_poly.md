# How to edit polyline?

When the polyline node is selected, a menu appears where you can:

* `F1 (SET_POSITION)` - set the position of this vertex in coordinates.
* `F2 (SELECT_ALL)` - select the entire polyline. After clicking, all vertices of this polyline will be selected, and the button bar will change to edit a group of objects.
* `F3 (ALIGN_SIDES)` - align the sides at an angle of 45 or 90 degrees
* `F4 (MOVE)` - enter the drag mode of the polyline node.
* `F5 (SET_ORIGIN)` - set the origin to this place.
* `F6 (DELETE)` - delete the vertex.
* `F7` `F8` - align on `X` or `Y` coordinates of another line or pad. Click on the node of another line or on the pad, and then click on the node that you want to align. And now press F7 or F8 depending on the axis of alignment.

When the polyline node is selected, a menu appears where you can:

* `F1 (SET_WIDTH)` - set the width of this polyline, as well as a choice: fill polygon or polyline.
* `F2 (STRAIGHT/ARC_CW/ARC_CCW)` - if the side is not vertical and not horizontal, then you can make an elliptical arc (1/4 ellipse) from a straight line.
* `F3 (ADD_CORNER)` - если линия является прямой то эта кнопка активна. Нажмите чтобы вставить дополнительную вершину в этот сегмент полилинии.
* `F4 (HATCH)` - если линия является замкнутой(см. F1) то эта кнопка становится активной. Нажмите чтобы залить или очистить область внутри контура полилинии.
* `F5 (HIDE)` - вы можете скрыть линию. В этом случае она не будет отображаться в PCB-редакторе печатной платы, и ее не будет в гербер-файлах.
* `F6` - transfer the polyline to the copper layer for example to draw an antenna. Complex shapes can be drawn with a closed polyline.

![](pictures/antenna1.png)

![](pictures/antenna2.png)

You can create a part consisting of several. To do this, select the Import Footprint menu item and import other footprints into the current footprint.

![](pictures/multi_part.png)

* `F8` -  also you can move the polyline to the notes layer.

# ![return](How_to.md)
