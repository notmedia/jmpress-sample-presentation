jmpress Sample Presentation
--------------------

This labs project is designed to test the implementation of several technologies.

* [jmpress](https://github.com/shama/jmpress.js/) - jQuery plugin to build a website on the infinite canvas
* [bundle](http://gembundler.com/git.html) - The best way to manage your application's dependencies
* [sass](http://sass-lang.com/) - Syntactically Awesome Stylesheets
* [compass](http://compass-style.org/) - SASS extentions that do nearly everything
* [guard](https://github.com/guard/guard) - Guard is a command line tool to easily handle events on file system modifications
* [guard-livereload](https://github.com/guard/guard-livereload) - Guard::LiveReload automatically reload your browser when 'view' files are modified


Prerequisites
=============

This project requires Ruby and RubyGems and the LiveReload browser plugin: [Chrome](https://chrome.google.com/webstore/detail/jnihajbhpnppcggbcgedagnkighmdlei), [Safari](https://github.com/downloads/mockko/livereload/LiveReload-1.6.2.safariextz), [Firefox](https://addons.mozilla.org/firefox/addon/livereload/), IE... Seriously?

If you are using OSX, you should also install [Command Line Tools](http://stackoverflow.com/questions/9329243/xcode-4-4-command-line-tools) before the installation instructions.

Installation
============

To install:

	git clone https://github.com/notmedia/jmpress-sample-presentation.git
	cd jmpress-sample-presentation
	gem install bundle (may require sudo)
	bundle
	guard

Then:

	Open folder in localhost, enable LiveReload browser plugin
	Edit html or scss files to see live reload
	Experiment with jmpress

Author
======

James Tomasino, github@jamestomasino.com, [http://jamestomasino.com](http://jamestomasino.com)
