Questions

When looking at the table's DOM or source code:


What does the colspan="3" attribute of the <th> node do?

The colspan attribute tells the browser to create a cell that spans more than one column. Cells with colspan > 1 will range over mutiple other cells creating a merged cell effect. 



List all the styles (e.g. border width, text alignment, etc.) applied to the th element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.


This is listed as an attr style.
th[Attributes Style] {
text-align: -webkit-center;
}

This euqivalent is align="center"

This is from the user agent stylesheet. 
th {
font-weight: bold;
}

td, th {
display: table-cell;
vertical-align: inherit;
}


All the ones listed below are inherited:
padding: 3px;
line-height: 1.22em;
margin: 0;
.main-content table {
border-collapse: collapse;
}
border-color: gray;
body {
font: 13px Tahoma, Arial, Helvetica, clean, sans-serif;
}



What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?
The HTML source code reflects HTML structure before any JavaScript is loaded. Whereas DOM is a parsed version which includes the expansion of the script logic in terms of adding attr etc. 

The DOM tree is fully editable which is an additional benefit to developers. 