<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Things HTML / CSS (kinda)</title>
    <link href="index.css" rel="stylesheet" type="text/css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
</head>
<header>All Things HTML / CSS (kinda)</header>


<body>
<h1>Important HTML</h1>
<!-- Table Tags -->

  <article>
      <table>
          <caption>Tables</caption>
          <tbody>
              <tr>
                  <th>Tag</th>
                  <th>Name</th>
                  <th>Description</th>
              </tr>
              <tr>
                  <td>&lt;table&gt;</td>
                  <td>Table</td>
                  <td>The wrapper element to create a table</td>
                </tr>
              <tr>
                  <td>&lt;tbody&gt;</td>
                  <td>Table Body</td>
                  <td>The actual rows of the table</td>
              </tr>
              <tr>
                  <td>&lt;thead&gt;</td>
                  <td>Table Head</td>
                  <td>Creates a table header</td>
              </tr>
              <tr>
                  <td>&lt;caption&gt;</td>
                  <td>Caption</td>
                  <td>Creates a caption (much like table header)</td>
              </tr>
              <tr>
                <td>&lt;tr&gt;</td>
                <td>Table Row</td>
                <td>Creates a new row to add data &lt;td&gt; elements</td>
              </tr>
                            <tr>
                <td>&lt;td&gt;</td>
                <td>Table Data</td>
                <td>Creates a new row of data for the &lt;td&gt; elements</td>
              </tr>
              <tr>
                <td>&lt;tfoot&gt;</td>
                <td>Table Footer</td>
                <td>The set of rows that are defined as the footer (under &lt;tbody&gt;)</td>
              </tr>
          </tbody>
          <tfoot>
              <tr>
                <td colspan="3">
                    <em>Remember to:</em>
                    <ul>
                    <li>use &lt;colspan&gt; to go across multiple columns</li>
                    <li>use &lt;rowspan&gt; to go across multiple rows</li>

                    <li>create segments that represent each row: &lt;tr&gt; + &lt;td&gt; or &lt;th&gt;</li>
                    <li><em>&lt;table&gt;, Table,</em> and <em>The wrapper element to create a table</em> is in one &lt;tr&gt; segment in the code</li>
                    </td>
                    </ul>
              </tr>
          </tfoot>
      </table>
<br>
<!-- Top Used HTML Elements as of 30.3.2021 -->
      <table>
          <caption>Top Usage HTML Elements</caption>
          <tbody>
            <tr>
                <th>Tag</th>
                <th>Name</th>
                <th>Description</th>
            </tr>
              <tr>
                <td>&lt;!DOCTYPE HTML&gt;</td>
                <td>Doctype Declaration</td>
                <td>The declaration of the document type</td>
              </tr>
              <tr>
                <td>&lt;h1&gt;, &lt;h2&gt;, &lt;h1&gt;, etc.</td>
                <td>Headers</td>
                <td>There are 6 headers, each smaller than the last</td>
              </tr>
              <tr>
                <td>&lt;p&gt;</td>
                <td>Paragraph</td>
                <td>Creates a new paragraph</td>
              </tr>
              <tr>
                <td>&lt;a&gt;</td>
                <td>Attribute</td>
                <td>Attributes are used to provide additional information on elements. Can be used with href="" when adding a link</td>             </td>
              </tr>
              <tr>
                <td>&lt;br&gt;</td>
                <td>Break</td>
                <td>Adds a line</td>
              </tr>
              <tr>
                <td>&lt;img&gt;</td>
                <td>Image</td>
                <td>Creates an image link with src="" which can be a URL or a relative link and alt="" which is alternative text</td>
              </tr>
              <tr>
                <td>&lt;video&gt;</td>
                <td>Video</td>
                <td>Creates an video link with src="" which can be a URL or a relative link and alt="" which is alternative text</td>
              </tr>
              <tr>
                <td>&lt;em&gt;, &lt;b&gt;, &lt;i&gt;</td>
                <td>Emphasis, Bold, and Italic</td>
                <td>HTML inline instead of CSS</td>
              </tr>
              <tr>
                <td>&lt;ul&gt;, &lt;ol&gt;</td>
                <td>Unordered List, Ordered List</td>
                <td>Creates lists wrapping &lt;li&gt; elements</td>
              </tr>
          </tbody>
      </table>
<br>
</article> 

<aside>
<h1>CSS Selectors</h1>
<!-- Class and ID selectors for CSS-->
    <h3>Class Element</h3>  
      <ul>
          <li>Written in HTML as class="<em>the class name</em>"</li>
          <li>Written in CSS as <em>the class name</em> {}</li>
      </ul>
      <h3>Class Selector</h3>  
      <ul>
          <li>Written in HTML as class="<em>the class name</em>"</li>
          <li>Written in CSS as ".<em>the class name</em>" {}</li>
      </ul>
      <h3>ID</h3>  
      <ul>
          <li>Written in HTML as id="<em>the ID name</em>"</li>
          <li>Written in CSS as "<em>#the ID name</em>" {}</li>
      </ul>
      <h3>Grouped Selectors</h3>  
      <ul>
          <li>Written in HTML as class="<em>the class name</em>"</li>
          <li>Written in CSS as <em>the class name</em>, <em>the class name</em>, <em>the class name</em>, {}</li>
      </ul>
      <h3>Universal</h3>  
      <ul>
          <li>Written in CSS as "<em>* (asterisk)</em>"" {}</li>
      </ul>
    </aside>
    
<article>
    <h1>Important CSS</h1>
    <table>
        <caption>Colors</caption>
        <tbody>
          <tr>
              <th>Code</th>
              <th>Description</th>
          </tr>
          <tr>
              <td>color: ""</td>
              <td>Font color</td>
          </tr>
          <tr>
            <td>background-color: ""</td>
            <td>Background color of the block</td>
        </tr>
        <tr>
            <th colspan="2">Ways to write color</th>
        </tr>
        <tr><td colspan="2">Hex: #000000</td></tr>
        <tr><td colspan="2">RGB: rgb(256, 256, 256)</td></tr>
        <tr><td colspan="2">HSL: hsl(9, 100%, 64%)</td></tr>
        <tr><td colspan="2">RGBA: rgba(256, 256, 256, 0.5) - adds opacity/transparency</td></tr>
        <tr><td colspan="2">HSLA: hsla(9, 100%, 64%, 0.5) - adds opacity/transparency</td></tr>
        </tbody>
    <table>

</article>
</body>
</html>
