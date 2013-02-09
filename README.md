# Stop Older Browsers

Trying to support older browsers is by far one of the most annoying challenges a web developer faces. Instead of supporting them, we should be educating users on what a browser is and how to get it upgraded. 

I kept making the exact same page for my projects, so I decided to make one universal one I can just plop in for my next one. Hopefully, it helps you too. It's a simple package- all it includes is a tiny HTML file with CSS embedded in it, plus an image. 

Of course, it works in IE6. 

### How to Install

Put ie6.html and ie6.png in the same directory. It doesn't really matter there. In every HTML file, add this code to redirect older browsers to this page. If you'd like to redirect **IE6** and below, use this code: 

	<!--[if lte IE 6]>
	<script type="text/javascript">
	<!--
	window.location = "ie6.html"
	//-->
	</script>
	<![endif]-->
	
And if you want to redirect **IE7** and below, use this code.

	<!--[if lte IE 7]>
	<script type="text/javascript">
	<!--
	window.location = "ie6.html"
	//-->
	</script>
	<![endif]-->
	
With either way, change window.location to wherever the redirection page is located. 

Enjoy! This is licensed under [WTFPL](http://wtfpl.net/txt/copying). 
