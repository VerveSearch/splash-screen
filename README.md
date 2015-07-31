# splash-screen

A plugin that creates a responsive splash screen for your landing page. 
You can click if off specifiying an element that will listen to the onlick event, or simply
by clicking outside the splash screen. 

## Dependencies

1.jquery.min.js

## Usage

Attributes:
contentElSelector : the selector of an element to use as a content;
hideElementSelector: add a selector to listen to click event; 
hideOnClick: Add a click event listener to the backdrop;
onClick : overwrite default hide() action;


```javascript

	$('.content').SplashScreen({
 		hideElementSelector : '.button', 
		hideOnClick : false,
    	onClick: function(el,ev){
    		el.hide();
    	}
	});
 

```	