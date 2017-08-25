Starfinder Theme
===============

This theme is designed to be used in Tiddlywiki to write Starfinder modules.

## Setup

To enable custom CSS themes you must modify your core template shadow tiddler to insert a custom HTML link referencing the .css file from this theme.

1. Open your tiddlywiki and search for the Shadow tiddler category in the right menu.
2. Edit a tiddler called $:/core/templates/tiddlywiki5.html.
3. Add the following line in the head section:
`<link rel="stylesheet" href="./themes/StarfinderTheme/stylesheet.css"/>` 
Now you only need to copy the theme files into that location (relative to you tiddlywiki root folder) and reload the page.

## Setup for Node.js server

If you are using Tiddlywiki through the Node.js server method, the previous method won't work. The easiest method is to create a new tiddler named `Stylesheet` with the tag `$:/tags/Stylesheet` and paste the contents of the `stylesheet.css` into that tiddler. Upon saving the tiddler, you should see the theme being applied. For further info on defining CSS styles in this way, check this [link](http://tiddlywiki.com/static/Using%2520Stylesheets.html).
