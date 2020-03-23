### View paste mask status of pins.

There is a case when you need to see certain PCB parts, all pins of which do not have a paste mask. For example, if your parts installer puts only smd parts on a printed circuit board, then you will need to prepare the file by removing parts with through pins from it. 
Ifobox has a column that shows the state of the paste mask for each pin of parts. Go to the PIN tab, then right-click on the pin list field and enter the settings menu. Here, in the settings window, select the `'Pin Paste mask check'` option. Close the settings window, and now the `'Paste'` column is displayed in our main infobox. In the cells of this column you can find the following words:

1) `On`
2) `Off`
3) `On (All)`
4) `Off (All)`

If you probably understand everything with the first two points, then the word `'All'` in the third and fourth points means that all pins related to this part have the same status. For example, if the pin status of part R1.1 has the value `'On (All)'`, this means that both R1.2 and R1.3 ... and R1.X - also have the status 'On'.

In the filter cell, just enter the line `'Off ('` to filter the parts that do not contain paste. Then you can go to the `PARTS` tab and highlight these details using the right-click menu. (`Highlight all`)
