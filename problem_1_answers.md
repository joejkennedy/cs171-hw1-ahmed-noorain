Questions

When looking at the table's DOM or source code:


What does the colspan="3" attribute of the <th> node do?

The colspan attribute tells the browser to create a cell that spans more than one column. Cells with colspan > 1 will range over mutiple other cells creating a merged cell effect. 



List all the styles (e.g. border width, text alignment, etc.) applied to the th element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.

align="center"

padding: 3px;
line-height: 1.22em;
margin: 0;
th[Attributes Style] {
text-align: -webkit-center;
}

th {
font-weight: bold;
}

td, th {
display: table-cell;
vertical-align: inherit;
}

.main-content table {
border-collapse: collapse;
}

border-color: gray;

body {
font: 13px Tahoma, Arial, Helvetica, clean, sans-serif;
}




What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?
The source code reflects your HTML structure before any JavaScript is loaded. While the contents can’t be edited, it’s useful to see the HTML Safari receives from the server.

The DOM tree is fully editable. Of course, your edits are temporary, so any changes you make are lost in a browser refresh. To save changes you make to the DOM tree, select the root html node and press Command-C, which copies the DOM structure to you clipboard as HTML.