# FrontEnd-Bootstrap-Document
Document for Basic Bootstrap classes,jumbotron,container,colors,grid layout
# Content:
  - Basic Bootstrap Classes,
  - Jumbotron and container classes
  - Text classes and colors 
  - Grid Layout
# What is Bootstrap?
It is the most popular HTML, CSS, and JavaScript framework for developing responsive, mobile-first websites.
Bootstrap 4 is the newest version of Bootstrap,
Bootstrap is a free front-end framework for faster and easier web development

**What is Responsive Web Design?**
	Responsive web design is about creating web sites which automatically adjust themselves to look good on all devices, from small phones to large desktops.

# How to include bootstrap into our html?
**We can add in two ways**
- online: just copay and past bootstrapy style links in header tag
- offline: download the css,jquery,js files from getbootstrap.com and place your downloaded files into respective folder then give the reference link in html header tag

### Bootstrap classes:
> Class is nothing but collection of variables and methods is knows as a class. In Bootstrap we can represent every thing in class using class name and it have predefind classes

**Example:**

1.Containers : Bootstrap requires a containing element to wrap site contents

	<div class=“container”>…..</div>
	
2.Grid System: Grid systems are used for creating page layouts through a series of rows and columns that house your content

	<div class=‘row’>
		<div class='col'>.....</div>
		<div class='col'>.....</div>
		<div class='col'>.....</div>
		
	</div>
3.Alignment classes:  We can align the text using this classes in  paragraph tags,header tags, etc

     <p class=“text-left>Text data</p
     <p class=“text-right>Text of right</p>
     <p class=“text-center> Text of center</p>
4.Transformation Classes: We can text captiliztion

     <p class=‘text-lowercase’>lowercase data</p>
     <p class= ‘text-uppercase’>uppercase data</p>
     <p class=‘text-capitalize’>capitalize data</p>
     
 That are the some basic classes, we have so many classes please refer <a href="www.google.com">getbootstrap.com</a>
 
 ### Colors:
 
 > Bootstrap 4 offers classes you can use to add color depending on the context the element is being used in.
This component of Bootstrap 4 can make reading your code easier by providing contextual clues through the class names.
Using different prefixes, these classes can be used for both Bootstrap text color and background color, as well as coloring elements.

***Example***

* Background Color:
    <h1 style="background-color:DodgerBlue;">Hello World</h1> (or)
    <h1 style="background-color:rgb(255, 99, 71);">Hello world</h1> (or)	
    <h1 style="background-color:#ff6347;">Hello world</h1>

* Text Color:
    <h1 style="color:Tomato;">Hello World</h1>
	
* Border Color:
   <h1 style="border:2px solid Tomato;">Hello World</h1>


