HTML is Hyper Text Markup Language
HTML is the code that is used to
structure a web page and its content.
The component used to design the
structure of websites are called HTML tags.

Basic HTML Page
<!DOCTYPE html> //tells browser you are using HTML5
<html>//root of an html document
<head>//container for metadata

<title>My First Page</title>//page title
</head>
<body> //contains all data rendered by the browser
<p>hello world</p> //paragraph tag
</body>
</html>

HTML mainly contains --> text,images,Audio and video
Text->heading tag, paragraph, pre...
image->img 
audio->audio
video->video

Heading Tag
------------------
Used to display headings in HTML
h1 (most important)
h2
h3
h4
h5
(least important)

Paragraph Tag
------------------------
Used to add paragraphs in HTML
<p> This is a sample paragraph </p>

Anchor Tag
--------------------
Used to add links to your page
<a href="https://google.com"> Google </a>

Image Tag
---------------
Used to add images to your page
<img src="/image.png" alt="Random Image">

Br Tag
---------------
Used to add next line(line breaks) to your page
<br>

Bold, Italic & Underline Tags
---------------------------------
Used to highlight text in your page
<b> Bold </b> 
<i> Italic </i> 
<u> Underline </u>

Big & Small Tags
-----------------------
Used to display big & small text on your page
<big> Big </big> 
<small> Small </small>

Hr Tag
--------------
Used to display a horizontal ruler, used to separate content
<hr>

Subscript & Superscript Tag
------------------------------
Used to display a horizontal ruler, used to separate content
<sub> subscript </sub> 
H O
2
<sup> superscript </sup> 
n
A + B

Pre Tag
Used to display text as it is (without ignoring spaces & next line)
<pre> This
is a sample
text.     
</pre>

iframe Tag
---------------------
website inside website
<iframe src="link">  Link </option>

Audio Tag
---------------------
<audio src="./audio/sample-3s.mp3" width="300px" height="200px" controls>My Audio</audio>

Video Tag
-------------------
<video src="myVid.mp4">  My Video </video>
Attributes- controls- height- width- loop- autoplay

BlockElement and Inline Element
-------------------------------------
1.Block Element (takes full width) and starts in next line
2.Inline Elemen (takes width as per size) continue in same line.

Block Element
------------------
<div>
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<nav>
<noscript>
<ol>
<p>
<pre>
<h1>-<h6>
<header>
<hr>
<li>
<section>
<table>
<tfoot>
<ul>
<dt>
<main>
<video

Inline Element
-------------------
<span>
<a>
<abbr>
<acronym>
<b>
<bdo>
<big>
<br>
<button>
<dfn>
<em>
<i>
<img>
<input>
<kbd>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<label>
<map>
<object>
<tt>
<strong>
<sub>
<sup>
<textarea>
<cite>
<code>
<var>
<time>

List in HTML
Lists are used to represent real life list data.
unordered
<ul>
<li> Apple </li>
<li> Mango </li>
</ul>
ordered
<ol>
<li> Apple </li>
<li> Mango </li>
</ol>

Tables in HTML
---------------------------
Tables are used to represent real life table data.
<tr> used to display table row
<td>
<th>
used to display table data
used to display table header

Tables in HTML
<table>
<tr>
    <th> Name </th>
    <th> Roll No </th>
</tr>
<tr>
    <td> Madhuri </td>
    <td> 21 </td>
</tr>
</table

Caption in Tables
<caption> Student Data </caption 


thead & tbody in Tables
<thead> to wrap table head 
<tbody> to wrap table body

colspan attribute
colspan="n" 
used to create cells which spans over multiple columns


Form in HTML
Forms are used to collect data from the user
Eg- sign up/login/help requests/contact me
<form>
form content
</form

Action in Form
--------------
Action attribute is used to define what action needs to be
performed when a form is submitted, where it is connected with backend 
<form action="/action.php" >

Form Element :
Input:
<input type="text" placeholder="Enter Name">

Label:
<label for="id1"> 
<input type="radio" value="class X" name="class"  id="id1">
</label> 
<label for="id2"> 
</label> 
<input type="radio" value="class X" name="class"  id="id2">

Class & Id:
<div id="id1" class="group1"> 
</div> 
<div id="id2"> class="group1">
</div>

Checkbox
<label for="id1"> 
<input type="checkbox" value="class X" name="class"  id="id1">
</label> 
<label for="id2"> 
</label> 
<input type="checkbox" value="class X" name="class"  id="id2">

Textarea
<textarea name="feedback" id="feedback" placeholder="Please add Feedback">
</textarea>

Select
<select name="city" id="city"> 
<option value="Delhi">  Delhi </option>
<option value="Mumbai">  Mumbai </option>
<option value="Banglore">  bangalore </option>
</select>
