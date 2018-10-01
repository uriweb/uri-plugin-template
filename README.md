# URI Plugin Template

The URI Plugin Template repository is a base template for building WordPress plugins with gulp, PHP Code Sniffer, and Travis CI.

## How do I get set up?

There are a few things you need to do to get up and running:

1. Rename the main plugin file [`uri-plugin-template.php`](https://github.com/uriweb/uri-plugin-template/blob/master/uri-plugin-template.php) and update its header comment fields to match your new plugin.  Be sure to update the `@package` tag too.

2. URI Plugin Template ships with a [`package.json`](https://github.com/uriweb/uri-plugin-template/blob/master/package.json) file that's populated with information you'll want to change, such as the plugin name, description, repository, etc.

3. gulp runs a task to update the plugin version number from `package.json`, so you don't have to update it in two places.  However, gulp looks for the main plugin file by name in order to do this, so you'll need to update [`gulp.js`](https://github.com/uriweb/uri-plugin-template/blob/master/gulp.js) to reflect the new name.

3. The [`script.js`](https://github.com/uriweb/uri-plugin-template/blob/master/src/script.js) file in the [`src`](https://github.com/uriweb/uri-plugin-template/blob/master/src) directory has a `@package` tag, just like the main plugin file.  Make sure this one's updated too.

Once you're done with these steps, you can move on to [setup](https://github.com/uriweb/uri-plugin-template/blob/master/SETUP.md).


## Plugin Details

[![Master Build Status](https://travis-ci.org/uriweb/uri-plugin-template.svg?branch=master "Master build status")](https://travis-ci.org/uriweb/uri-plugin-template)
[![CodeFactor](https://www.codefactor.io/repository/github/uriweb/uri-plugin-template/badge/master)](https://www.codefactor.io/repository/github/uriweb/uri-plugin-template/overview/master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/77712193bd8643f88fad1fbdc8a02c87)](https://www.codacy.com/app/uriweb/uri-plugin-template?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=uriweb/uri-plugin-template&amp;utm_campaign=Badge_Grade)
[![devDependencies Status](https://david-dm.org/uriweb/uri-plugin-template/dev-status.svg)](https://david-dm.org/uriweb/uri-plugin-template?type=dev)

URI Plugin Template  
A base template for building WordPress plugins with gulp, PHP Code Sniffer, and Travis CI.

Contributors: Brandon Fuller  
Tags: plugins  
Requires at least: 4.0  
Tested up to: 4.9  
Stable tag: 0.1.0  