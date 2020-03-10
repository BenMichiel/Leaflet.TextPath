Leaflet.TextPath
================

Shows a text along a Polyline.

This is a fork of https://github.com/makinacorpus/Leaflet.TextPath

Leaflet versions
-----

The version on the `gh-pages` branch targets Leaflet `1.3.1`.

Credits
-------

https://github.com/makinacorpus/Leaflet.TextPath

The main idea comes from Tom Mac Wright's *[Getting serious about SVG](http://mapbox.com/osmdev/2012/11/20/getting-serious-about-svg/)*


Changelog
---------

### 1.2.4 ###

* Now also works in IE.

### 1.2.3 ###

* Now also works on FireFox with Angular and changing base url.

### 1.2.2 ###

* Now also works on other pane than overlay-pane.
* First change on https://github.com/BenMichiel/Leaflet.TextPath

### 1.2.1 ###

Latest change on https://github.com/makinacorpus/Leaflet.TextPath

### 1.1.0 ###

* Add the orientation option (#27, thanks @kirkau)

### 1.0.2 ###

* Allow HTTP and HTTPS to access the demo (#39, thanks @sonny89 and @leplatrem)

### 1.0.1 ###

* Fix text centering for vertical lines (#33, #34, #38, thanks @msgoloborodov)

### 1.0.0 ###

**Breaking changes**

* Text is now shown on top by default. Set option ``below`` to true to put the text below the layer.

### 0.2.2 ###

* Fix bug when removing layer whose text was removed (fixes #18) (thanks Victor Gomes)
* Fix path width when using options.center (fixes #17) (thanks Brent Miller).

### 0.2.1 ###

* Fix layer order (fixes #5) (thanks Albin Larsson)

### 0.2.0 ###

* Stay on top after bringToFront
* Clean-up and fix `onAdd` and `onRemove`
* Fire mouse events from underlying text layer (thanks Lewis Christie)

### 0.1.0 ###

* Initial working version



Authors
-------

Many thanks to [all contributors](https://github.com/makinacorpus/Leaflet.TextPath/graphs/contributors) !

[![Makina Corpus](http://depot.makina-corpus.org/public/logo.gif)](http://makinacorpus.com)
