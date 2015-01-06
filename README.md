#slider
*Nice Slider Html *


##Demo
Live Demo:   http://freeslide.github.io/


##Usage
To use `freeslide.html`, reference the stylesheet in the `<head>` of your document (or you can place within your own stylesheet).

To work out of the box, you will need to make the following adjustments to your markup (classes can be changed in the stylesheet if you use something different):
* An outer `<div>` with a id of `wowslider-container1` 
* A list image (either ul or ol) 

```
<div id="wowslider-container1">
	<div class="ws_images"><ul>
		<li><img src="data1/images/yourImage.jpg" alt=" " title="" id="wows1_0"/></li>
		<li><a href="#"><img src="data1/images/yourImage.jpg" alt=" " title="" id="wows1_1"/></a></li>
		<li><img src="data1/images/yourImage.jpg" alt=" " title="" id="wows1_2"/></li>
	</ul></div>
	<div class="ws_bullets"><div>
		<a href="#" title="">1</a>
		<a href="#" title=" ">2</a>
		<a href="#" title=" ">3</a>
	</div></div>
	</div>
	<script type="text/javascript" src="engine1/wowslider.js"></script>
	<script type="text/javascript" src="engine1/script.js"></script>

```

That's it! Everything works out of the box with this setup. However, like any CSS plugin/snippet, you will probably want to stylize it to match your sites theme. I've separated all functional CSS from the presentational CSS so you can jump right in and change everything you need without breaking the plugin. Just edit as needed below the following CSS comment:

```
/*--------------------------------
 Presentation Styles (Editable)
---------------------------------*/
```

##Support
WebKit rendering engine makes up the vast majority of mobile browsers (iOS, Android, Nokia), so you can expect the same level of support for mobile browsing as you see in Chrome/Safari.

* Chrome 16.0+
* Safari 5.1+
* Firefox 4.0+
* Opera 12
* IE9*
* iOS 4.0+
* Android 2.3+