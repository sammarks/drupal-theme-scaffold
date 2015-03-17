# Scaffold

This repository is a basic scaffold for all templates I create. It uses the following technologies:

- Bower
- Gulp
- Node.JS
- SCSS

Basically, it sets up the style folders and `gulpfile` to jumpstart creating a new mockup or template.

To get started, all you have to do is `cd` to the `.npm` folder of the repository, and then type:

	npm install
	gulp
	
Gulp will start, compile all of your CSS assets, move fonts to where they're supposed to go, and
then watch for any changes to your stylesheets, fonts, or Javascripts.

## The .npm Folder

The `.npm` folder is important because Drupal will pick up on .info files created by
the node modules and try to load them as themes. If we put all the node modules inside
a hidden folder, we don't run into this problem. The only caveat is that the `gulpfile`
must go inside that folder as well.
