Questions

Consider the provided sample code this Gist and answer the following questions:

What's missing? Is this bar chart usable in its current form?

The existing sample code doesnt label the axis, it doesnt provide an easy way to rank or sort the data. It lacks functionality such 
as sort, filter, selection.

What is the role of each of the three nested levels of g elements? (keep in mind you'll be adding a title to the chart)


g elements allow the elements to be grouped and make it easier to manager the elements. The first g is for the entire chart. The second g is for components such as title etc which are also part of the chart and the third g is for the components related to building the bar (svg,rect, text, text).


Complete the implementation section below. Is there any consequence if you add the text elements before or after the rect elements? Why?


No. Since they are grouped there is no consequence. If it was not grouped, after sorting each element would be required to be moved and transformed. Since the text is anchored it doesnt make any difference as both are anchored. 
