# draw.io-plugins

For snippets used as plugins in draw.io

## My Plugins

### [insertElementsWithMenu.js](https://github.com/holroy/draw.io-plugins/blob/master/insertElementsWithMenu.js) – Insert elements with meny

A draw.io plugin for inserting a custom text (or ellipse) element, either by keyboard Ctrl+Shift+T (or Ctrl+Shift+Q) or by menu. Inspired by the question [Looking for blackboard style note taking app (Scapple alternative)](//softwarerecs.stackexchange.com/q/21802/14982) from the [Software Recommendations](//softwarecs.stackexchange.com/) Stack Exchange site, I wrote an answer recommending [draw.io](//draw.io), and ended up creating this plugin to make it easier to insert a pure text element which could be linked.  


## Regarding draw.io plugins

### Getting proper links

See [Link and execute external JavaScript file hosted on GitHub](http://stackoverflow.com/questions/17341122/link-and-execute-external-javascript-file-hosted-on-github) for information on how to use links to github as links to the plugins. The gist of it is to use the raw link (or a tagged link) to the file you want to use as a plugin, and insert this on the front page of [rawgit.com](//rawgit.com/), and copy either the dev/testing link, or the production link for use in the plugin dialog of draw.io. 

### Add plugin to draw.io

Do the following to actually add the plugin to draw.io:

 * Navigate the menues to _Extras > Plugins..._
 * Hit the _Add_ button
 * Enter the URL to your javascript file
 * Hit the _Add_ button, and then the _Apply_ button
 * Reload the draw.io page, and accept the load of the plugin
 * Use your newly added plugin
