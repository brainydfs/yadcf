Yet Another DataTables Column Filter - (yadcf) - Non-linear step-size snap-slider
=====
 
Description:
=====

This fork allows you create custom, non-linear step sizes when using yadcf's slider.  
For example, if you want a slider to look like this:

|----|----|----|----|----|----|----|

0    2   25   100  500  600 10000 20000

Then this fork will help you.

Alternatively, open the example.html in this fork and use the slider to understand what I am referring to.

Code:
=====
The changes are in the jquery.dataTables.yadcf.js file and are in lines 1418-1431 and lines 1564-1599.  The comments should explain the relatively-easy process.
