jquery.betterFader.js
=====================

By Chris Pappas <chris@nexventures.com>
---------------------------------------

* Version:	0.1
* Date: 	2009-08-24
* Author: 	Chris Pappas
* Email: 	chris@nexventures.com
* Web: 	http://nexventures.com

This plugin is based on the work of T. Baldes http://medienfreunde.com

Much thanks to T. Baldes at medienfreunde.com for his very nice InnerFade plugin.

I have fixed up this plugin to make it fit my needs. I simply added a customizable delay into the 'fade' animations. Next few versions will add delays into slide transition and fix up other parts.

Examples
--------


	<ul id="news">
	  <li>content 1</li>
	  <li>content 2</li>
	  <li>content 3</li>
	</ul>


	$('#news').innerfade({
	  animationtype: Type of animation 'fade' or 'slide' (Default: 'fade'),
	  speed: Fading-/Sliding-Speed in milliseconds or keywords (slow, normal or fast) (Default: 'normal'),
	  timeoutCurrent: Time between the fades in milliseconds (Default: '2000'),
	  timeoutBetween: Time between the fades in milliseconds (Default: '500'),
	  type: Type of slideshow: 'sequence', 'random' or 'random_start' (Default: 'sequence'),
	  containerheight: Height of the containing element in any css-height-value (Default: 'auto'),
	  runningclass: CSS-Class which the container gets applied (Default: 'innerfade'),
	  children: optional children selector (Default: null)
	});
