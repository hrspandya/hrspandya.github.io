---
layout: post
title: What is Modernizr and Why use it?
category: Browser Support
tags: Browser Support with Polyfill and Modernizr
year: 2015
month: 8
day: 19
published: true
summary: Polyfill is a piece of code which certain browsers are lacking, For example -- IE6 not supporting local storage feature. Polifill comes to rescue and fill the void with javascript. But how do you check if browser lacks certain features and how would you add polyfill to only those browsers which needs them. Solution is simple, use Modernizr my friend.
image: post_one.jpg
---



<div class="row">	
	<div class="span9 columns">
	  <h2>Polyfill + Modernizr</h2>
	  <p>
	  	Polyfill is a piece of code which certain browsers are lacking, For example -- IE6 not supporting local storage feature. But does that mean that we wait untill everybody in world moves to latest browser so that we can start using awesome HTML5, ES6, or CSS3 features???  No, Solution is simple, developers write polyfills which mimics the lacking features in older browsers. Using polyfills now you can use this awesome features wihout worrying about unhappy users.

	  	<br><br>
	  	But Polyfill is javascript code. More javascript files you load slower your page will be. 

	  	<br><br>
	  	Hmm, Well there is better way, Wouldn't it be better if we could check if my browser can support certain features or not? 

	  	<br><br>

	  	Also wouldn't it be better if we only loaded the polyfill javascript file if my browser does not support certain feature. 

	  	<br>
	  	<br>

	  	Use Modernizr my friend.
	  </p>  	  
	  
	  <hr>

	  <h2>Understand by Example</h2>
	  <p>
	  	<iframe width="100%" height="600" src="https://www.youtube.com/embed/QwgyM_i7-Qs" frameborder="0" allowfullscreen></iframe>
	  </p>  	

	  <hr>	  	  	  

	  <h2>In Conclusion</h2>
	  <p>
	  	Rememeber polyfills can be written for missing CSS, HTML or Javascript functionalities. Its best way to keep utilizing latest features of modern browsers.

	  	<br><br>
	  	<a href="https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills" target="_blank">Here is very helpful link for many polyfills : Polyfills </a>

	  	<br><br>
	  	<strong>NOTE: </strong> <a href="http://alistapart.com/article/taking-advantage-of-html5-and-css3-with-modernizr" target="_blank">Learn about Modernizr for easy Polyfilling</a>

	  </p>	  

	  <hr>

	</div>
</div> 




