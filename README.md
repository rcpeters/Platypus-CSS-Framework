# PlatypusCSS #

Minimalistic CSS Framework for Responsive Web Design [Based on Bootflat, but without depending on Bootstrap, it has its own core].

## GETTING STARTED ##

	Comparison between Bootstrap 3 and Platypus

```html
<!-- Bootstrap 3 (Already fluid) --> 
<div class="container">
	<div class="row">
		<div class="col-md-8 col-sm-8 col-xs-6">
			This is a test
		</div>
		<div class="col-md-8 col-sm-8 col-xs-6">
			Testing Bootstrap 3
		</div>
	</div>
</div>

<!-- Platypus (Already fluid) --> 
<div class="container"> 
	<div class="row">
		<div class="desktop-8 tablet-8 mobile-6">
			This is a test
		</div>
		<div class="desktop-4 tablet-8 mobile-6">
			Testing Platypus CSS
		</div>
	</div>
</div>
```

## HOW TO USE PLATYPUS ##

Just include platypus.min.css stylesheet to your HTML files, as follows:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Platypus!</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Platypus -->
    <link href="css/platypus.css" rel="stylesheet" media="screen">    
    <script src="js/prefixfree.min.js"></script>
    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="js/html5shiv.js"></script>
      <script src="js/respond.min.js"></script>
    <![endif]-->    
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```

Main container elements:

	.container  -> Main container
	.row  -> A row

Platypus uses 12 columns for every row. You can use infinite rows, 12 columns per row. 

	Target:

	.mobile-[columns] 		Extra Small -> Mobile devices 
	.tablet-[columns] 		Small       -> Tablet
	.desktop-[columns] 		Mediaum     -> PC
	.wide-[columns] 		Large       -> PC (widescreen) 

Example of a predefined Platypus class: 

	mobile-10    -> Extra Small target, 10 columns 

	.[target]l 	-> push (left)

	.[target]r 	-> pull (right)

	.[target]o[columns] 	-> offset (margin-left)

	*** mobile doesn't has offset

## CONTACT ##

* Fran Ramírez Monge
* Contact: jframonge@gmail.com