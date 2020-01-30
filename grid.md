### Grids

There are three grids in `FREEPCB`:

- visible grid (which can be disabled on the layer panel in the left part of the window)
- grid for parts.
- grid for tracing.

Using the F7 button (in no selection mode), the Visible grid view can be selected either as a dot or a strip.

### Configuration file 

All default settings are stored in the file DEFAULT.CFG which is located in the root directory of FREEPCB. You can open this file in a text editor and carefully modify it, observing the format.

### Editable grid value.

The entire list of grid sizes is stored in the file DEFAULT.CFG. But you can change the step of the visible grid or placement grid directly from the main program window. This grid is temporary and will not be saved when the program is closed, it is used when there is a need for a non-standard grid step.

![](pictures/editable_grid.png)

### Meshless routing mode. 

More convenient mode, because additional vertices are not created when starting the trace from the pad when the pad is not on the grid nodes. To switch to meshless routing mode, select a grid step value of 0

![](pictures/meshless.png)

# [return](How_to.md)
