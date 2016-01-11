**css3-mediaqueries.js** by Wouter van der Graaf is a JavaScript library to make IE 5+, Firefox 1+ and Safari 2 transparently parse, test and apply [CSS3 Media Queries](http://www.w3.org/TR/css3-mediaqueries/). Firefox 3.5+, Opera 7+, Safari 3+ and Chrome already offer native support.

**UPDATE: Google discontinued the downloads section. Download newest version 1.0 from here:**

**https://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js***

Usage: just include the script in your pages.

(And you should combine and compress with other scripts and include it just before `</body>` for better page speed - but you already knew that).

Write your media queries like you would for browsers with native support. The script will parse your CSS and apply the styles for positive media query tests realtime (also when you resize).

**Note:** Doesn't work on @import'ed stylesheets (which you shouldn't use anyway for performance reasons). Also won't listen to the media attribute of the `<link>` and `<style>` elements.

Happy media querying!