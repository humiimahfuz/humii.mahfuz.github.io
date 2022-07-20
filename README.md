<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="Stylesheet" href="styles.css">
    <title>Web Dev CheatSheet</title>
    <h1 id="top">Web Development Cheatsheet</h1>
</head>
<body>
    <div class="navbar">
    <nav id="navbar"> 
       <ul><strong><a href="#tags">HTML Tags</a> </strong> </ul>
       <ul><strong><a href="#att">HTML Attributes</a></strong> </ul>
       <ul><strong><a href="#selectors">CSS Selectors</a></strong> </ul>
       <ul><strong><a href="#properties">CSS Properties</a></strong> </ul>
       <ul><strong><a href="#pseudo">CSS Pseudo-Classes</a></strong></ul>
   </nav>
   </div>
  <!--Section 1-->
    <div>
    <h2 id="tags">HTML Tags</h2>
    <table>
        <thead>
            <th id="empty"></th>
            <th>Tags</th>
            <th>HTML Element</th>
            <th>Explanation</th>
            <th>Additional Comments</th>
        </thead>
    <tbody>
        <tr> <!--row 1 of HTML table tags-->
            <td class= "span" rowspan="6"> <strong>HTML Table</strong></td>
            <td>&lt;table&gt;</td>
            <td>Table</td>
            <td>Wrapper element for all HTML tables</td>
            <td></td>
        </tr>
        <tr> <!--row 2-->
          <td>&lt;thead&gt;</td>
          <td>Table Head</td>
          <td>Sections out the heading portion of a table</td>
          <td></td>
        </tr>
        <tr> <!--row 3-->
          <td>&lt;tbody&gt;</td>
          <td>Table Body</td>
          <td>Sections out the body of a table that contains actual data</td>
          <td></td>
        </tr>
        <tr> <!--row 4-->
            <td>&lt;tr&gt;</td>
            <td>Table Row</td>
            <td>Signifies the start of a new row</td>
            <td></td>
        </tr>
        <tr> <!--row 5-->
            <td>&lt;td&gt;</td>
            <td>Table Data</td>
            <td>Defines the cell of a table that contains acual data</td>
            <td></td>
        </tr>
        <tr> <!--row 6-->
             <td>&lt;tfoot&gt;</td>
             <td>Table Footer</td>
             <td>Sections out the footer content of a table</td>
             <td></td>
        </tr>
        <tr> <!--row 1 of HTML media tags-->
            <td class= "span" rowspan="4"><strong>HTML Media</strong></td>
            <td>&lt;video&gt;</td>
            <td>Video</td>
            <td>To show a video in HTML</td>
            <td class="comment"> Attributes include:
                <ul>
                 <li>width</li>
                 <li>height</li>
                 <li>controls/autoplay</li>
                </ul>    
            </td>
        </tr>
        <tr> <!--row 2-->
            <td>&lt;img&gt;</td>
            <td>Image</td>
            <td>To show an image in HTML</td>
            <td class="comment">Must include:
              <ul>
                <li>src attribute for the image location</li>
                <li>alt attribute for an alternate description</li>
              </ul>
            </td>
        </tr>
        <tr> <!--row 3-->
            <td>&lt;audio&gt;</td>
            <td>Audio</td>
            <td>To play an audio file in HTML</td>
            <td class="comment">Include the controls attribute</td>
        </tr>
        <tr> <!--row 4-->
            <td>&lt;source&gt;</td>
            <td>Source</td>
            <td>Allows you to specify alternate locations of the audio file for browser compatability</td>
            <td class="comment"c>Used during &lt;audio&gt; and &lt;video&gt;</td>
        </tr>
    </tbody>
    </table>
   </div>
<!--Section 2-->
<div>
   <h2 id="att">HTML Attributes</h2>
    <table>
        <thead>
            <th>Attribute</th>
            <th>Belongs to</th>
            <th>Description</th>
        </thead>
        <tbody>
            <tr>
                <td>colspan</td>
                <td>&lt;td&gt;, &lt;th&gt;</td>
                <td>Defines how many columns a td element can span</td>
            </tr>
            <tr>
                <td>rowspan</td>
                <td>&lt;td&gt;, &lt;th&gt;</td>
                <td>Defines how many rows a td element can span</td>
            </tr>
            <tr>
                <td>src</td>
                <td>&lt;audio&gt;, &lt;img&gt;, &lt;video&gt;, &lt;embed&gt;, &lt;source&gt;</td>
                <td>Specifies media file location</td>
            </tr>
            <tr>
                <td>href</td>
                <td>&lt;a&gt;, &lt;link&gt;</td>
                <td>Specifies the URL of the page a link goes to</td>
            </tr>
            <tr>
              <td>alt</td>
              <td>&lt;img&gt;</td>
             <td>Alternate description if the image fails to load</td>
            </tr>
            <tr>
                <td>autoplay</td>
                <td>&lt;audio&gt;, &lt;video&gt;</td>
                <td>Will start playing as soon as the page loads</td>
            </tr>
            <tr>
                <td>rel</td>
                <td>&lt;link&gt;</td>
                <td>Specifies the relationship between linked documents</td>
            </tr>
            <tr>
                <td>blank</td>
                <td>&lt;a&gt;</td>
                <td>Species where to open up a linked document </td>
            </tr>
        </tbody>
    </table>
</div>
<!--Section 3-->
    <div>
    <h2 id="selectors">CSS Selectors</h2>
    <table>
        <thead>
            <th>Selector</th>
            <th>Example</th>
            <th>Description</th>
        </thead>
        <tbody>
            <tr>
                <td><em>.class</em></td>
                <td>.intro</td>
                <td>Selects all elements with class="intro"</td>
            </tr>
            <tr>
                <td><em>#id</em></td>
                <td>#firstname</td>
                <td>Selects all elements with id="firstname" </td>
            </tr>
            <tr>
                <td><em>*</em></td>
                <td>*</td>
                <td>Selects all elements</td>
            </tr>
            <tr>
                <td>::before</td>
                <td>p::before</td>
                <td>It will insert something before content of <em><strong>EACH</strong></em> &lt;p&gt; element</td>
            </tr>
        </tbody>
    </table>
    </div>
<!--Section 4-->
    <div>
    <h2 id="properties">CSS Properties</h2>
    <table>
        <thead>
            <th>Property</th>
            <th>Explanation</th>
        </thead>
        <tbody>
            <tr>
                <td>border-collapse</td>
                <td>Dictates whether table borders will collapse into a single border or be separate</td>
            </tr>
            <tr>
                <td>box-shadow</td>
                <td>Adds shadow to elements</td>
            </tr>
            <tr>
            <td>box-sizing</td>
            <td>Includes padding and border in height and width of an element</td>
            </tr>
            <tr>
                <td>float</td>
                <td>Specifies whether an element should float or not. Absolutely positioned elements will ignore this property.</td>
            </tr>
            <tr>
                <td>font-weight</td>
                <td>Specifies the thickness of the text</td>
            </tr>
            <tr>
                <td>opacity</td>
                <td>Specifies the transparency of an element</td>
            </tr>
            <tr>
                <td>z-index</td>
                <td>Specifies the stack order of elements. Does not work on static-positioned elements.</td>
            </tr>
            <tr>
                <td>text-transform</td>
                <td>Controls the capitalization of text</td>
            </tr>
            <tr> 
                <td>text-decoration</td>
                <td>Specifies the decoration added to the text</td>
            </tr>
        </tbody>
    </table>
    </div>
<!--Section 5-->
<div>
    <h2 id="pseudo">CSS Pseudo-Classes</h2>
    <table>
        <thead>
            <th>Pseudo-Class</th>
            <th>Explanation</th>
            <th>Additional Detail</th>
        </thead>
        <tbody>
            <tr>
                <td>:link</td>
                <td>Matches when a link has not been visited</td>
                <td>:link > :visited > :hover > :active</td>
            </tr>
            <tr>
                <td>:visited</td>
                <td>Matches when a link has been visited</td>
                <td>FYI: the visited and un-visited links on a navbar will be the same</td>
            </tr>
            <tr>
                <td>:hover</td>
                <td>Matches when a user is pointing their mouse over it</td>
                <td>Used in navigation bars and content links. Will not be activated by keyboard. <span id="hover"><em>:hover rule comes before the :active rule!</em></span></td>
            </tr>
            <tr>
                <td>:active</td>
                <td>Matches when a link has been clicked on</td>
                <td>Just an FYI: the :hover and :active interactions may be different and it will only be visible once you click on the link</td>
            </tr>
        </tbody>
    </table>
</div>
<p> <a href="#top">Back to Top</a></p>
</body>
</html>
