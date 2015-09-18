# PeakScroll
UI scroller for your long, wordy pages. Designed by [planlodge](https://github.com/planlodge).

[![Build Status](https://travis-ci.org/stevenbenner/jquery-powertip.svg?branch=master)](https://travis-ci.org/stevenbenner/jquery-powertip)
![Release Version](http://img.shields.io/github/release/stevenbenner/jquery-powertip.svg)
![License](https://img.shields.io/packagist/l/doctrine/orm.svg)

![Atom](https://raw.githubusercontent.com/planlodge/PeakScroll/master/demo/recording.gif)

## Getting Started

 1. Include jQuery in your code.
 2. Download and include the transimg.js file.
 3. Pick your selector and apply transimg method.

## Full Example

    <!DOCTYPE html>
	<html lang="en-US">
	<head>
	  <meta charset="utf-8">
	  <meta name="viewport" content="width=device-width, initial-scale=1">
	  <link rel="shortcut icon" href="http://palakmathur.in/images/icons/github.png" />
	  <title>Peak Scroll</title>
	  <meta name="description" content="">
	  <link rel="stylesheet" href="css/font-awesome/css/font-awesome.min.css" />
	  <link rel="stylesheet" href="css/peakScroll.min.css" />
	  <!-- demo purposes only -->
	  <link rel="stylesheet" href="demo/demo.css" />

	</head>
	<body>

	<center>
	<div id="wrapper">
	    <header id="top">
	        <h1>Peak Scroll</h1>
	        <p>The Friendly Back to Top Button.</p>
	  </header>

	  <section>

	    <div>
	      <p>
	        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	      </p>

	      <p>
	        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	      </p>

	      <p>
	        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	      </p>

	      <p>
	        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	      </p>
	    </div>
	  </section>



	    <footer>
	      <p>2015 Planlodge</p>
	    </footer>

	    <!-- include this somewhere on the page -->
	    <div class="peakScroll-up" title="Back to Top">
	          <a href="#top"><i class="fa fa-angle-up"></i></a>
	    </div>

	</div>
	</center>

	<script src="https://code.jquery.com/jquery-2.1.4.min.js"></script> 
	<script src="src/peakScroll.min.js"></script> 
	<script>
	$(function(){

	  $('body').peakScroll({fadeSpeed: 300, scrollSpeed: 900});

	});
	</script>

	</body>
	</html>
	

## License

PeakScroll is licensed under the [Apache license](http://opensource.org/licenses/MIT).

