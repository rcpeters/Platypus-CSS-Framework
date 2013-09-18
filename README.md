# PlatypusCSS #

Minimalistic CSS Stylesheet for Responsive Web Design [Based on Bootstrap 3]. It is not a Framework. It includes Normalize.

## GETTING STARTED ##

	Comparison between Bootstrap (version 2.3 and 3) and Platypus

```html
<!-- Bootstrap 2.3 (You need to specify if the content will be fluid) -->
<div class="container-fluid">
	<div class="row-fluid">
		<div class="span8 offset2">			
		</div>
		<div class="span2">			
		</div>
	</div>
</div>

<!-- Bootstrap 3 (Already fluid) --> 
<div class="container">
	<div class="row">
		<div class="col-sm-8 col-sm-offset-2">
		</div>
		<div class="col-sm-2">
		</div>
	</div>
</div>

<!-- Platypus (Already fluid) --> 
<div class="box"> 
	<div class="row">
		<div class="s8 so2">
		</div>
		<div class="s2">
		</div>
	</div>
</div>
```

## HOW TO USE PLATYPUS ##

Just include platypus.min.css stylesheet and the conditional tags for IE7 to your HTML files, as follows:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Platypus template</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Platypus -->
    <link href="css/platypus.min.css" rel="stylesheet" media="screen">
    <!--[if lt IE 8]>
  		<link rel="stylesheet" href="css/platypus.ie7.min.css">
	<![endif]-->    
    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="../../assets/js/html5shiv.js"></script>
      <script src="../../assets/js/respond.min.js"></script>
    <![endif]-->    
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```

Main container elements:

	.box  -> Main container
	.row  -> A row

Platypus uses 12 colums for every row. You can use infinite rows, but only 12 colums per row. 

	Target:

	.xs[rows] 		Extra Small -> Mobile devices 
	.s[rows] 		Small       -> Tablet
	.m[rows] 		Mediaum     -> PC
	.l[rows] 		Large       -> PC (widescreen) 

Example of a predefined Platypus class: 

	xs10    -> Extra Small target, 10 columns 

	.[target]l 	-> push (left)

	.[target]r 	-> pull (right)

	.[target]o[rows] 	-> offset (margin-left), example: mo2

	*** xs doesn't has offset

## CONTACT ##

* Fran Ramírez Monge
* Contact: info@hexplusoft.com
* Website: www.franrmz.com