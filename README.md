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

	     <p style="background-color:DodgerBlue;">Hello World</p>   
	     <p style="background-color:rgb(255, 99, 71);">Hello world</p> 	
	     <p style="background-color:#ff6347;">Hello world</p>      

* Text Color:

     	<p style="color:Tomato;">Hello World</p>
	
* Border Color:

     	<p style="border:2px solid Tomato;">Hello World</p>
   
### Text color classes:

* -primary changes the color to blue #007bff.
* -info changes the color to teal #17a2b8.
* -success changes the color to green #28a745.
* -warning changes the color to yellow #ffc107.
* -danger changes the color to red #dc3545.
* -dark changes the color to dark gray #343a40.
* -secondary changes the color to gray #6c757d.
* -light changes the color to light gray #f8f9fa.
* -white changes the color to white #ffffff.

***Example:***

	<p>Use the contextual classes to provide "meaning through colors":</p>
  	<p class="text-muted">This text is muted.</p>
  	<p class="text-primary">This text is important.</p>
  	<p class="text-success">This text indicates success.</p>
  	<p class="text-info">This text represents some information.</p>
  	<p class="text-warning">This text represents a warning.</p>
  	<p class="text-danger">This text represents danger.</p>
  	<p class="text-secondary">Secondary text.</p>
  	<p class="text-dark">This text is dark grey.</p>
  	<p class="text-body">Default body color (often black).</p>
  	<p class="text-light">This text is light grey (on white background).</p>
	
### Jumbotron:
> A jumbotron indicates a big grey box for calling extra attention to some special content or information.

Two Types of Jumbotron:

1) Jumbotron: Flexed with width

		<div class="jumbotron">
			<h1>Bootstrap Jumbotron</h1>
		</div>
		
2) Jumbotron-fluid: Full width screen

		<div class="jumbotron jumbotron-fluid">
			<h1>Bootstrap Jumbotron-fluid of full width screen</h1>
		</div>
		
### Container:
> Bootstrap 4 also requires a containing element to wrap site contents.

Two Types of Container:

1) Container:It provides a responsive fixed width container

		<div class="container">
			<h1>Bootstrap container</h1>
		</div>

2) Container-fluid: It provides a full width container, spanning the entire width of the viewport

		<div class="container">
			<h1>Bootstrap container fluid</h1>
		</div>

### Grid Classes:

> Bootstrap's grid system is provides the data into Grid formate and allows up to 12 columns across the page. The grid system is responsive The columns will re-arrange automatically depending on the screen size

Types of Grid:

	.col     : extra small devices - screen width less than 576px
        .col-sm- : small devices - screen width equal to or greater than 576px
        .col-md- : medium devices - screen width equal to or greater than 768px
        .col-lg- : large devices - screen width equal to or greater than 992px
        .col-xl- : xlarge devices - screen width equal to or greater than 1200px




	

