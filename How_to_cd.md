# `Schematic Constructor v1.0`

***
How to make a schematic design

To prevent the player slider from obstructing the bottom panel with buttons, it is recommended to expand it to full screen when watching a video. Flashing orange buttons on the bottom panel means that the corresponding button has been pressed on the keyboard. But you can also click on it with the mouse if you prefer. Let's go!

1) First specify the project folder and then enter the project name in the main line. The program will create a folder of the same name in which it will place your project. In the course of work, many different files associated with the project will appear in this folder. The Schematic Constructor can import parts from other projects by pressing the F1 button, and for this, all projects must be stored in a shared folder. The new version of `Schematic Constructor (1.1)` has a parameter called "index to project folder". It indicates the storage depth of the project relative to the main folder. By default, it is 1, but if your project is stored inside a folder of another project, then set the value to 2.

<iframe src="https://player.vimeo.com/video/510964622" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

2) The Schematic Constructor comes with a template file, `Template.cds`, which has a frame with captions. Insert this file into your project to get started. You can edit the `Template.cds` file like a normal project, change this frame, and save. In Schematic Constructor you can attach any image in `BMP` or `JPEG` format to any polyline. The image takes the size of the rectangle that describes the polyline, so you can set the image to any size. It should be noted that there is a fundamental difference between importing a BMP and a JPEG file. A JPEG file is uploaded with preservation of the entire color gamut and is supported by the built-in `PDF` printer, while BMP is uploaded as a background image, where the color of the first pixel in the file is replaced by the color of the working background of the program screen (for copying or other purposes), it is not printed ...

<iframe src="https://player.vimeo.com/video/510964771" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

3) This video shows you how to change the polyline layer and thickness. After you have completely drawn your schematic design, you can select all the lines with a frame and give them the same thickness if you want.
You can move any polyline on different layer, or add a new line by placing it on one of the following layers:

  - ownerless layer
  - first front layer
  - second front layer
  - the first back layer
  - second back layer 
  
You can add up to 14 more back layers via the `Project` >> `Options` menu.

<iframe src="https://player.vimeo.com/video/510965047" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

4) In the Schematic Constructor, any polyline has 6 text attributes:

 - Ref Des (part name)
 - Part Value
 - Footprint
 - pin name
 - net name
- Description

Therefore, if you see any text in the file, then know that it always belongs to the polyline (when the text is selected, the polyline is highlighted). You can set the polyline attributes through the `Set Attr` dialog box, first select the polyline segment and then press` F1`. When you assign a text attribute to the polyline, for example `RefDes`, the polyline is moved to the corresponding reserved layer` Part Outline` / if you enter the attribute `Pin Name`, then to the layer` Pin line` / if you enter the attribute `Net Name`, then in layer `Net Polyline`. So, there are 3 reserved layers where you cannot manually move the polyline.

 - Part outline
 - Pin line
 - Net Polyline

<iframe src="https://player.vimeo.com/video/510965271" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

5) Draw all the polylines of the part on the ownerless layer, set the pin name attribute on the corresponding polylines. Then select the entire group and set the RefDes, Value and Footprint attributes - and the part is ready. You can then import this part from another project. 

<iframe src="https://player.vimeo.com/video/510965399" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

6) You can make another part from one part by copying and modifying it. Edit text attributes without going into the polyline attributes dialog box, but through the text properties dialog box. Click on the text and press `F1`. If you want to hide the text, then set it to zero size and thickness. 

<iframe src="https://player.vimeo.com/video/510965598" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

7) Enable drag mode by pressing the F2 button. In this mode, you can continuously drag from place to place any object, such as text. Grab RefDes if you want to move three part attributes at once in one click - RefDes, Value, Footprint. 

<iframe src="https://player.vimeo.com/video/510966010" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

8) You need to know that when the part is rotated by an angle not multiple of 90 degrees, the part may lose its snapping to the grid, but it rotates without graphic distortion. If you want to bind the vertices to the grid, then select the menu item Project >> Adapt to grid, but graphics distortion is inevitable.
You can combine diodes into a merger. Select 4 diodes and press F2 (Add Merge). In the dialog box, enter a name for the merge, for example Diode Bridge. Now, when you click on any of the diodes, the entire group will be selected.

<iframe src="https://player.vimeo.com/video/510966162" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

9) 

<iframe src="https://player.vimeo.com/video/510966367" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

10) 

<iframe src="https://player.vimeo.com/video/510966500" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

11) 

<iframe src="https://player.vimeo.com/video/510966629" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

12) 

<iframe src="https://player.vimeo.com/video/510966777" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

13) 

<iframe src="https://player.vimeo.com/video/510966946" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

14) 

<iframe src="https://player.vimeo.com/video/510967070" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

15) Press the F9 key to generate all networks on the current page. By default, the program will create network names in the NETxxxxx format.
When a polyline segment is selected, press the N hotkey to highlight the entire net. A complete list of hotkeys can be found in the HELP menu

<iframe src="https://player.vimeo.com/video/510967267" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

16) 

<iframe src="https://player.vimeo.com/video/510967395" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

17) 

<iframe src="https://player.vimeo.com/video/510967559" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>


# [`home`](https://freepcb.dev)


