# URI Plugin Template

The URI Plugin Template repository is a base template for building WordPress plugins with gulp, PHP Code Sniffer, and Travis CI.

## How do I get set up?

There are a few things you need to do to get up and running:

1. Download [master.zip](https://github.com/uriweb/uri-plugin-template/archive/master.zip) and unzip it

2. Rename `.gitattributes-sample` to `.gitattributes`

3. Rename the main plugin file [`uri-plugin-template.php`](https://github.com/uriweb/uri-plugin-template/blob/master/uri-plugin-template.php) and update its header comment fields (including the `@package` tag) to match your new plugin.

4. Update [`package.json`](https://github.com/uriweb/uri-plugin-template/blob/master/package.json) with your new plugin name, description, repository, etc.

5. Update the `@package` tag in [`script.js`](https://github.com/uriweb/uri-plugin-template/blob/master/src/script.js) file in the [`src`](https://github.com/uriweb/uri-plugin-template/blob/master/src) directory.

6. Finally, gulp runs a task to update the plugin version number from `package.json`, so you don't have to update it in two places.  However, gulp looks for the main plugin file by name in order to do this, so you'll need to update [`gulp.js`](https://github.com/uriweb/uri-plugin-template/blob/e7208805f9fedd83c29739de3307e91a0e64aaea/gulpfile.js#L86) to reflect the new name.

Once you're done with these steps, head over to [SETUP.md](https://github.com/uriweb/uri-plugin-template/blob/master/SETUP.md) to get developer tools going.


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