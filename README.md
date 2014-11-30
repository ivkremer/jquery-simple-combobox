jQuery Simple Combobox plugin
=============================

A jQuery combobox plugin. You can use it for autocomplete (search, etc).

Usage
-----

You can find reference in index.html and see [fiddles here](http://jsfiddle.net/user/ivkremer/fiddles/ "JSFiddle") to understand its features.

To change the name of a plugin in your code you need to modify ```var pname = 'scombobox';``` line (starting the script). Make sure your CSS class prefixes correspond this name.

### IE8 compatibility ###

This plugin uses the following JS native stuff:

```JavaScript
String.prototype.trim()
Object.keys()
Array.prototype.indexOf()
console.warn()
```

To provide IE8 support add this methods to your project (see [js/missed.js](https://github.com/ivkremer/jquery-simple-combobox/blob/master/js/missed.js) file).

Thanks to
---------

* [danieltim300](https://github.com/danieltim300)
* [taitranvn](https://github.com/taitranvn)
* [Jo Weiser](https://github.com/joweiser)
* [Dmitry Gubernatorov](https://github.com/dgubernatorov-softheme)
* [policecomplaints](https://github.com/policecomplaints)
* [Christophe Olinger](https://github.com/olingerc)
* [Allan Laal](https://github.com/allanlaal)
* [RyanPaddyFronde](https://github.com/RyanPaddyFronde)
* [Chris Meza](https://github.com/cmeza)
* [Dima Snisarenko](https://github.com/InSearch)
* [John Murray](https://github.com/gjsjohnmurray)

For bug reporting, feature proposing and improving this project.

License
-------

The MIT License (MIT)

Copyright (c) 2014 Ilya Kremer
