**Q** What does the `colspan="3"` attribute of the `<th>` node do?

>It tells the browser that this row, which will hold the title or header of the entire table, should span three columns (i.e., the total number of columns that will be holding datapoints below). 

**Q** List all the styles (e.g. border width, text alignment, etc.) applied to the `th` element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.

>.main-content td, .main-content th {
padding: 3px;<br>
}  **(CSS STYLE gives space between data and table borders)**<br><br>

> body * {
line-height: 1.22em;
} (**CSS STYLE establishes height of cells?**)<br><br>

>[*] {
padding: 0; **<--OVERWRITTEN STYLE**<br>
margin: 0;
} (**CSS STYLE not sure what this does**)<br><br>

>th[Attributes Style] {
text-align: -webkit-center;
} (**HTML ATTRIBUTE established in th tag, sets text alignment**)<BR><BR>

>th {
font-weight: bold;
} (**CSS STYLE default or "user agent" styling for table headers**)<br><br>

>td, th {
display: table-cell;
vertical-align: inherit;
} (**CSS STYLE default or "user agent" styling for table cell vertical alignment**)


**Q** What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?

>The DOM inspector provides much more structural information at a glance. It is easy to search for specific elements within the page, and it provides insight into where certain attributes are being established (e.g. in a separate user stylesheet, as HTML attributes, CSS in the header, or inherited user agent styling). The raw sourcecode may be useful in viewing the  uninterpreted code? 

