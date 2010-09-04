#Place Holder jQuery Plugin

This plugin will enable html5 placeholder attribute work in all browsers.

To use just include the plugin file along with jQuery. Then in your dom.ready function select the input elements you want to use then call `placeholder()` on them.

	(function($) {
		$(document).ready(function() {
			$(".placeholder").placeholder();
		});
	})(jQuery);

Your input elements need to have the placeholder attribute on them.

	<input class="placeholder" type="text" name="first-name" id="first-name" placeholder="Smith" />


Originally inspired by [@robertbanh](http://forrst.com/people/robertbanh)'s [post on Forrst](http://forr.st/~ylp).