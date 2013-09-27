sticky-footer
=============

Basic files to create a css sticky footer on a web page.

This sticky footer consists only of CSS and HTML. It is glued to the bottom of the page, but stays below the content when the browser window is not high enough to show both the page and the footer.

I found it somewhere on the internet, but am not sure where exactly. I fine tuned it a little and added some explanation in the css file.

Open index.html and see it at work by resizing the height of browser window.

The framework of the html page consists of a 'page' div and a 'footer' div. Both divs have only one child div with class 'wrapper' with a top padding (or top border) of at least 1px to stop the top margins of nested elements from collapsing with the content and footer divs. For the technical stuff see sticky-footer.css.

Should work in all modern browsers on all systems, no guarantees.
