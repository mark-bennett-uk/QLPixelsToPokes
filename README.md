# QL Pixels to Pokes

Spreadsheet that turns pixel graphics into Sinclair QL SuperBASIC pokes

I wanted to add some static pixel graphics to a SuperBASIC program and found that drawing them using the built in SuperBASIC commands was time consuming, fiddly and imprecise. 
So, I looked for another way to do it and came up with an Excel spreadsheet that converts coloured pixels into QL screen memory data.

To use it enter the colour numbers 0 to 7 in the pixel grid on the sheets, in sheet 1 the cells A27 to P47. 
There are 16 pixels across and 21 down, approximately a square of QL pixels in 8 colour mode.

The program below the grid has procedures for writing the data to an array and another for writing some of the array to the screen memory area. 
The program line numbers are set by the blue numbers at the top of the sheet, change these number to renumber the code lines.

The data is created by manipulating the colours in binary to create the required memory data values.

There are 4 sheets in the spreadsheet so 4 graphics can be created at a time, but more can easily be attached.
