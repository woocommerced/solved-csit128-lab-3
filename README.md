Download Link: https://assignmentchef.com/product/solved-csit128-lab-3
<br>
Last week, we developed a web page to display a fictional “World Gurning Competition”.

In this week’s exercise, you will follow the steps below to add CSS styling to this web page. We will practice all 3 different ways to add styling to the web page:

<ul>

 <li><strong>inline</strong> (using a style attribute in HTML elements),​</li>

 <li><strong>document</strong> (using style element in the HTML head section), and​</li>

 <li><strong>external</strong> (using external CSS files).​</li>

</ul>

When you complete this exercise, the webpage will look like the following:

Part 1. Inline CSS

Make a copy of the web page competition.html​         that you developed last week into a new file​ called competition1.html​        . We will use ​  <strong>inline CSS</strong>​      for it. Follow the steps below to modify the​       file competition1.html​           .​

Step 1. Using font-size property

<em>The </em>​<strong><em>font-size</em></strong>​<em> CSS property sets the size of the font. </em>

Last week we used the HTML font tag to set the font size and color for the text World​ Gurning Competition and the smiley face. Now we will use CSS instead.​

Remove all the font tags from the text World​ Gurning Competition and the smiley face, and put all of them into a single paragraph tag (p). In this paragraph tag, use inline CSS to set font-size to 50px.​

In the first table row tag (tr), use inline CSS to set font-size​ to 40px.​

In all the table data tags (td) on the ranking column, use inline CSS to set font-size​ to 60px.​

Step 2. Using color property

<em>The </em>​<strong><em>color</em></strong>​<em> CSS property sets the foreground color value of an element’s text. </em>

Put the word World​ into​ a span tag; and in this span tag, use inline CSS to set color​ to orange​ .​ Put the word Gurning​ into​ another span tag, and use inline CSS to set color​ to pink​ .​ Put the word Competition ​ into a 3rd span tag and use inline CSS to set ​       color​ to ​ blue​ .​

In the first table row tag (tr), use inline CSS to set color​ to ​ navy​           .​

In all the table data tags (td) on the ranking column, use inline CSS to set color​ to ​ maroon​     .​

In all the unordered list tags (ul), use inline CSS to set color​ to ​ green​  .​

In all the list item tags (li) that contain the team leader, use inline CSS to set color​ to ​ purple​ .​

Step 3. Using background-color property

<em>The </em>​<strong><em>background-color</em></strong>​<em> CSS property sets the background color of an element. </em>

In the paragraph tag (p) that contains the text World​ Gurning Competition,​ use inline CSS to set background-color​         to ​ #ff000010​ .​

In the first table row tag (tr), use inline CSS to set background-color​ to ​ #00000010​         .​

In the table row tags (tr) that correspond to the odd ranking numbers, use inline CSS to set background-color to ​ #cc007711​ .​

In the table row tags (tr) that correspond to the even ranking numbers, use inline CSS to set background-color to ​ #55ff7720​ .​

step 4. Using padding property

<em>The </em>​<strong><em>padding</em></strong>​<em> CSS property sets the padding area on all four sides of an element. This property is a shorthand for the following properties: </em>​<strong><em>padding-bottom</em></strong>​<em>, <strong>padding-left</strong></em>​<em><sup>, </sup></em>​<strong><em>padding-right</em></strong>​<em><sup>, </sup></em>​<strong><em>padding-top</em></strong>​<em>. </em>

In the paragraph tag (p) that contains the text World​ Gurning Competition,​ use inline CSS to set padding​ to ​ 30​ px.​




In all the table header tag (th), use inline CSS to set padding​ to ​ 20​ px.​

In all the table data tag (td), use inline CSS to set padding​ to ​ 20​ px.​

In all the list item tags (li), use inline CSS to set padding​ to ​ 10​ px.​

<strong> </strong>Step 5. Using text-align and vertical-align properties

<em>The </em>​<strong><em>text-align</em></strong>​<em> CSS property sets the horizontal alignment of a block element or table-cell box. </em>

<em>The </em>​<strong><em>vertical-align</em></strong>​<em> CSS property sets vertical alignment of an inline, inline-block or table-cell box. </em>

In the paragraph tag (p) that contains the text World​ Gurning Competition,​ use inline CSS to set text-align​ to ​ center​ .​




Last week we used the attributes align​ and valign​ for the table header tag (th) and table data tag (td). This week we will use CSS, so we now remove all the attributes align​ and valign​ from the th and td tags.

In all the table header tags (th) and table data tags (td) of the 1st column, use inline CSS to set text-align to ​ right​ and ​ vertical-align​ to ​ top​ .​

In all the table header tags (th) and table data tags (td) of the 2nd column, use inline CSS to set text-align to ​ center​ and ​ vertical-align​ to ​ top​ .​

In all the table header tags (th) and table data tags (td) of the 3rd column, use inline CSS to set text-align to ​ left​ and ​ vertical-align​ to ​ top​ .​

Step 6. Using border-style, border-color and border-width properties

<em>The </em>​<strong><em>border-style</em></strong>​<em> CSS property sets the line style for all four sides of an element’s border. This property is a shorthand for the following properties: <strong>border-bottom-style</strong></em>​<em>, </em>​<strong><em>border-left-style</em></strong>​<em>, </em>​<strong><em>border-right-style</em></strong>​<em>, </em>​<strong><em>border-top-style</em></strong>​<em>. The values are: none, hidden, dotted, dashed, solid, double, groove, ridge, inset, outset. </em>

<em>The </em>​<strong><em>border-color</em></strong>​<em> CSS property sets the color of an element’s border. This property is a shorthand for the following properties: </em>​<strong><em>border-bottom-color</em></strong>​<em>, <strong>border-left-color</strong></em>​<em>, </em>​<strong><em>border-right-color</em></strong>​<em>, </em>​<strong><em>border-top-color</em></strong>​<em>. </em>

<em>The </em>​<strong><em>border-width</em></strong>​<em> CSS property sets the width of an element’s border. This property is a shorthand for the following properties: </em>​<strong><em>border-bottom-width</em></strong>​<em>, <strong>border-left-width</strong></em>​<em>, </em>​<strong><em>border-right-width</em></strong>​<em>, </em>​<strong><em>border-top-width</em></strong>​<em>. </em>

In the paragraph tag (p) that contains the text World​ Gurning Competition,​ use inline CSS to set border-style​ to ​ dotted​ , ​ border-color​ to ​ red​ , ​ border-width​ to ​ 5​ px​.

In all the table header tags (th), use inline CSS to set border-style​ to dashed​ ,​ border-color​ to black​ , ​ border-width​ to ​ 5​ px.​

In all the table data tags (td), use inline CSS to set border-style​ to solid​ ,​ border-color​ to gray, ​ border-width​       to ​ 1​ px.​

Step 7. Using border-collapse and border-spacing properties

<em>The </em>​<strong><em>border-collapse</em></strong>​<em> CSS property sets whether cells inside a table have shared or separate borders. The values are: collapse, separate. </em>

<em>The </em>​<strong><em>border-spacing</em></strong>​<em> CSS property sets the distance between the borders of adjacent table cells. This property applies only when </em>​<strong><em>border-collapse</em></strong>​<em> is separate. </em>

In the table tag (table), remove the attribute border​ .​

In the table tag, use inline CSS to set border-style​ to dotted​ ,​ border-collapse​ to separate,​ border-spacing​ to 10​ px.​ Observe what it looks like for the table border and table cell borders.

Now, in the above table tag, use inline CSS to set border-style​ to none​ ,​ border-collapse​ to collapse​ .​ Observe what it looks like for the table border and table cell borders this time. Notice the difference?!

<h1>Part 2. Document CSS</h1>

Make a copy of the web page competition.html​         that you developed last week into a new file​ called competition2.html​        . We will use ​  <strong>document CSS</strong>​           for it. In the head element, add a style​     tag. Follow the steps below to modify the file competition2.html​    .​

Step 1. Using font-size property

<em>The </em>​<strong><em>font-size</em></strong>​<em> CSS property sets the size of the font. </em>

Remove all the font tags from the text World​          Gurning Competition and the smiley face, and put them into a single paragraph tag (p). Give this paragraph tag the id called competitionPara​ .​

Use CSS id selector to select the id competitionPara​ and set ​ font-size​ to 50px.​

In the first table row tag (tr), give it an id called headerRow​ .​ Use the document CSS to select the id headerRow and set ​ font-size​ to 40px.​

In all the table data tags (td) on the ranking column, set the class to rankingNumber​ .​ Use the document CSS to select the class rankingNumber​ and set ​ font-size​ to 60px.​

Step 2. Using color property

<em>The </em>​<strong><em>color</em></strong>​<em> CSS property sets the foreground color value of an element’s text. </em>

Put the word World​  into​   a span tag and give it an id called word1​    .​ Use CSS id selector to select the id word1​ and set ​           color​            to ​ orange​   .​

Put the word Gurning​ into​ another span tag and give it an id called word2​ .​ Use CSS id selector to select the id word2​ and set ​ color​ to ​ pink​ .​

Put the word Competition​ into a 3rd span tag and give it an id called word3​   .​ Use CSS id selector to select the id word3​   and set ​           color​            to ​ blue​        .​

Use the document CSS to select the id headerRow​ and set ​ color​ to ​ navy​       .​

Use the document CSS to select the class rankingNumber​ and set ​ color​ to ​ maroon​ .​

In all the unordered list tags (ul), set the class to memberList​ .​ Use the document CSS to select the class memberList​ and set ​ color​ to ​ green​ .​

In all the list item tags (li) that contain the team leader, set the class to leader​ .​ Use the document CSS to select the class leader​ and set ​ color​ to ​ purple​ .​

Step 3. Using background-color property

<em>The </em>​<strong><em>background-color</em></strong>​<em> CSS property sets the background color of an element. </em>

Use the document CSS to select the id competitionPara​          and set background-color​  to

#ff000010.​

Use the document CSS to select the id ​headerRow​ and set ​background-color​ to ​#00000010​

In the table row tags (tr) that correspond to the odd ranking numbers, set the class to ​oddRow​. In the table row tags (tr) that correspond to the even ranking numbers, set the class to ​evenRow​.

Use the document CSS to select the class ​oddRow​ and set ​background-color​ to ​#cc007711​.

Use the document CSS to select the class ​evenRow​ and set ​background-color​ to ​#55ff7720​.

Step 4. Using padding property

<em>The </em>​<strong><em>padding</em></strong>​<em> CSS property sets the padding area on all four sides of an element. This property is a shorthand for the following CSS properties: </em>​<strong><em>padding-bottom</em></strong>​<em>, <strong>padding-left</strong></em>​<em><sup>, </sup></em>​<strong><em>padding-right</em></strong>​<em><sup>, </sup></em>​<strong><em>padding-top</em></strong>​<em>. </em>

Use the document CSS to select the id ​competitionPara​ and set ​padding​ to ​30px​.

In the table tag, give it an id called ​teamTable​. Use the document CSS to select all the table header tags (th) which are descendants of the id ​teamTable​ and set ​padding​ to ​20px​.

Use the document CSS to select all the table data tags (td) which are descendants of the id teamTable​ and set ​padding​ to ​20px​.

Use the document CSS to select all the list item tags (li) which are children of the class ​memberList and set ​padding​ to ​10px​.

<h2>Step 5. Using text-align and vertical-align properties</h2>

<em>The </em>​<strong><em>text-align</em></strong>​<em> CSS property sets the horizontal alignment of a block element or table-cell box. </em>




<em>The </em>​<strong><em>vertical-align</em></strong>​<em> CSS property sets vertical alignment of an inline, inline-block or table-cell box. </em>

<strong> </strong>

Use the document CSS to select the id ​competitionPara​ and set ​text-align​ to ​center​.




Last week we used the attributes align​ and valign​ for the table header tag (th) and table data tag (td). This week we will use CSS, so we now remove all the attributes align​ and valign​ from the table header tags (th) and the table data tags (td).




In all the table header tags (th) and table data tags (td) of the 1st column, set the class to rankColumn.​ Use document CSS to select the class rankColumn​ and set text-align​ to right and ​ vertical-align​ to ​ top​ .​




In all the table header tags (th) and table data tags (td) of the 2nd column, set the class to teamColumn.​ Use document CSS to select the class teamColumn​ and set text-align​ to center and ​ vertical-align​ to ​ top​ .​




In all the table header tags (th) and table data tags (td) of the 3rd column, set the class to memberColumn.​ Use document CSS to select the class memberColumn​ and set text-align​ to left and ​ vertical-align​ to ​ top​ .​




<h2>Step 6. Using border-style, border-color and border-width properties</h2>




<em>The </em>​<strong><em>border-style</em></strong>​<em> CSS property sets the line style for all four sides of an element’s border. This property is a shorthand for the following properties: <strong>border-bottom-style</strong></em>​<em>, </em>​<strong><em>border-left-style</em></strong>​<em>, </em>​<strong><em>border-right-style</em></strong>​<em>, </em>​<strong><em>border-top-style</em></strong>​<em>. The values are: none, hidden, dotted, dashed, solid, double, groove, ridge, inset, outset. </em>




<em>The </em>​<strong><em>border-color</em></strong>​<em> CSS property sets the color of an element’s border. This property is a shorthand for the following properties: </em>​<strong><em>border-bottom-color</em></strong>​<em>, <strong>border-left-color</strong></em>​<em>, </em>​<strong><em>border-right-color</em></strong>​<em>, </em>​<strong><em>border-top-color</em></strong>​<em>. </em>




<em>The </em>​<strong><em>border-width</em></strong>​<em> CSS property sets the width of an element’s border. This property is a shorthand for the following properties: </em>​<strong><em>border-bottom-width</em></strong>​<em>, <strong>border-left-width</strong></em>​<em>, </em>​<strong><em>border-right-width</em></strong>​<em>, </em>​<strong><em>border-top-width</em></strong>​<em>. </em>

<strong> </strong>

Use the document CSS to select the id competitionPara​ and set border-style​ to dotted​ ,​ border-color to ​ red​ , ​ border-width​ to ​ 5​ px.​

<strong> </strong>

Use the document CSS to select all the table header tags (th) which are descendants of the id teamTable and set border-style​ to dashed​ ,​ border-color​ to black​ ,​ border-width​ to 5​ px.​




Use the document CSS to select all the table data tags (td) which are descendants of the id teamTable and set border-style​ to solid​ ,​ ​border-color to gray​ ,​ border-width​ to

1px.​




<h2>Step 7. Using border-collapse and border-spacing properties</h2>




<em>The </em>​<strong><em>border-collapse</em></strong>​<em> CSS property sets whether cells inside a table have shared or separate borders. The values are: collapse, separate. </em>




<em>The </em>​<strong><em>border-spacing</em></strong>​<em> CSS property sets the distance between the borders of adjacent table cells. This property applies only when </em>​<strong><em>border-collapse</em></strong>​<em> is separate. </em>




In the table tag (table), remove the attribute border​ .​




Use document CSS to select the id teamTable​ and set border-style​ to dotted​ ,​ border-collapse to separate​ ,​ border-spacing​ to 10​ px​. Observe what it looks like for the table border and table cell borders.




Now, in the above document CSS id selector teamTable​ ​, set border-style​ to none​ ,​ border-collapse to collapse​ .​ Observe what it looks like for the table border and table cell borders this time. Notice the difference?!




<strong>         </strong>

<h1>Part 3. External CSS</h1>

Make a copy of the web page ​competition2.html​ that you developed in Part 2 above into a new file called ​competition3.html​. We will use ​<strong>external CSS</strong>​ for it.




Create a CSS file called ​competition.css​, make sure that the file extension is correct.




Use a text editor and open the file ​competition3.html​. Copy all the CSS code inside the style tag of ​competition3.html​ into the CSS file ​competition.css​. Save the CSS file competition.css​.




Remove all the CSS code and the style tag in the file ​competition3.html​. After that, in the head element, add a link tag:

&lt;link rel=”stylesheet” type=”text/css” href=”competition.css” /&gt;




Save the file ​competition3.html​ and use a web browser to open it. You will see that all the CSS styles will be displayed.