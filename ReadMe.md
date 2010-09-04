#Place Holder jQuery Plugin

This plugin will enable html5 placeholder attribute work in all browsers.

To use just include the plugin file along with jQuery. Then in your dom.ready function select the input elements you want to use then call `placeholder()` on them.

    (function($) {
        $(document).ready(function() {
            $("input[placeholder]").placeholder();
        });
    })(jQuery);

Your input elements need to have the placeholder attribute on them.

    <input type="text" name="first-name" id="first-name" placeholder="John" />

##Feature Plans

Some sort of feature detection in order to let browsers who support placeholder work natively.

##About

Originally inspired by [@robertbanh](http://forrst.com/people/robertbanh)'s [post on Forrst](http://forr.st/~ylp). You can also find the code on [github](http://github.com/ajcates/placeholder).

Also thanks to [@ejetzer](http://forrst.com/people/ejetzer) for suggesting a better way of selecting placeholder input elements.