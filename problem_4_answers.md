Questions

The domain() function is the data range upon which the scale is calculated. What does d3.selectAll("tbody tr")[0].length-1 mean?
Maps the domainof the color to be the number of states. By doing so, the range becomes 0 - 50 instead of 3 - 9 in the example dataset and 
this inturn colors all the cells as red. By appying the range to be the min and max value, the cells are colored from orange to silver. 

Add the snippet in your code. Describe, in words, what the following function calls return: color(0), color(10) and color(150)?
returns the color at index 0, 10, 150. If the index it outside range it still returns color outside of the specified range. 
color(0) is the orange-red. color(150) since its is outside the range returns a color of shade blue. 

If the array passed to domain() was the minimum and maximum rate values, how would that change the scale? In what situations would this be appropriate?
If the domain is the min and the max instead of 1 - 50, the color domain shrinks which means thy are more evenly spread on the range and 
result in the cells being colored from ornage to silver instead of all orange. 