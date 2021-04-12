## Split PCB net

Here both pins of this part have one common net. 

![Split PCB net](pictures/edit_tr9_4.png)

Sometimes you need to divide the net into two different ones, while preserving all the routes and polygons. The net can only be divided by Ratline.
To successfully divide the net into two parts, you must:

1) Select the Ratline by which you want to cut the net
2) Check this Ratline for the ability to split the network: try removing it. If the Ratline has disappeared, then it will not work to divide the net, otherwise the verification is successful and you can split the net here. Highlight this segment and press F7 (Split Net).

![Break PCB net](pictures/split_net1.png)

![Explode PCB net](pictures/split_net2.png)

A new net "N2" has formed, which can be renamed. When the pin is highlighted, press F5 (Edit Net)

