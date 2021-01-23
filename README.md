# Advanced-HTML-Workshop
Advanced HTML Workshop Plan -By Joseph Charuhas  

About / Introduction  

HTML is the language in which most websites are written. HTML is used to create pages and make them functional.  

CSS is the code used to make a webpage look visually appealing and will breifly be covered in this workshop as well  

  

Getting Started  

Open up an editor  

notepad or vscode or and other plane scripting or wysiwyg Editor will suffice   

Explaining the Project 

 In this project you will learn moreof the design aspects of html as well as how to make a portfolio 

Refresher from the beginner course 

Start off with <!DOCTYPE html>  - this specifies that html is being used.  

For all of the following use the appropriate end tag (</TAGNAME>) at the end of each section   

Next <html> - this shows that the next part of the code is HTML  

Side note if you put another programming language ie: Java script you would be able to script in that language   

Next <head> - this is where your page name and title go  

Use <title> some title</title> to set your page title (what will be at the top of the browser)  

Use <meta> This is where information about the document is stored. </meta>  

Next <body> - This is where the content of the page goes.  

The body tab most commonly includes pictures, text, tables, forms, ect.  

Use <h1>some header</h1> for your headers  

Use <p> type paragraph here </p>  for your paragraph  

list of other keys  

  

  

  

  

  

  

  

  

Inserting images  

Use <img src="image.jpg"> to insert images  

It is a common practice to use an alt when making an image an alt is a description of the image  

Alts often look like <img src="yourimage.jpg" alt="Describe the image">  

Though not necessary exact positions can be placed using x and y cords  

Inserting Tables  

When drawing a table we must open an element with the <table> opening tag. Inside this tag, we structure the table using the table rows, <tr>, and cells, <td>. getting 

Making a portfolio 

Things to include in a portfolio 

 Who You Are.  

Add a short description telling the reader about who you are 

What You Do. 

This part of the portfolio could be what sort of projects you have created 

Way to Get In Touch. 

Usually in the footer the in touch section is where you can plug your socials and or email 

Layout design  

The use of multiple pictures and columns are essential for an eye catching and appealing website 

Creating the html for the portfolio 

<!-- MAIN (Center website) --> 
<div class="main"> 
  
<hr> 
  
<h2>PORTFOLIO</h2> 
<p>text under title</p> 
  
<!-- Portfolio Gallery Grid --> 
<div class="row"> 
   <div class="column"> 
     <div class="content"> 
       <img src=" image.jpg" alt="imageName" style="width:100%"> 
       <h3>My Work</h3> 
       <p>text about the work listed</p> 
     </div> 
   </div> 
   <div class="column"> 
     <div class="content"> 
       <img src=" image.jpg" alt="imageName" style="width:100%"> 
       <h3>My Work</h3> 
       <p> text about the work listed </p> 
     </div> 
   </div> 
   <div class="column"> 
     <div class="content"> 
       <img src=" image.jpg" alt="imageName" style="width:100%"> 
       <h3>My Work</h3> 
       <p> text about the work listed </p> 
     </div> 
   </div> 
   <div class="column"> 
     <div class="content"> 
       <img src="image.jpg" alt="imageName" style="width:100%"> 
       <h3>My Work</h3> 
       <p> text about the work listed </p> 
     </div> 
   </div> 
</div> 
  
<div class="content"> 
   <img src=" image.jpg" alt="imageName" style="width:100%"> 
   <h3>Some Other Work</h3> 
   <p> text about the work listed </p> 
</div> 
  
<!-- END MAIN --> 
</div> 

Creating the CSS for the  

* { 
   box-sizing: border-box; 
} 
  
body { 
   background-color: #f1f1f1; 
   padding: 20px; 
   font-family: Arial; 
} 
  
/* Center website */ 
.main { 
   max-width: 1000px; 
   margin: auto; 
} 
  
h1 { 
   font-size: 50px; 
   word-break: break-all; 
} 
  
.row { 
   margin: 8px -16px; 
} 
  
/* Add padding BETWEEN each column (if you want) */ 
.row, 
.row > .column { 
   padding: 8px; 
} 
  
/* Create four equal columns that floats next to each other */ 
.column { 
   float: left; 
   width: 25%; 
} 
  
/* Clear floats after rows */ 
.row:after { 
   content: ""; 
   display: table; 
   clear: both; 
} 
  
/* Content */ 
.content { 
   background-color: white; 
   padding: 10px; 
} 
  
/* Responsive layout - makes a two column-layout instead of four columns */ 
@media screen and (max-width: 900px) { 
   .column { 
     width: 50%; 
   } 
} 
  
/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */ 
@media screen and (max-width: 600px) { 
   .column { 
     width: 100%; 
   } 
} 

End the workshop 

Release everyone 
