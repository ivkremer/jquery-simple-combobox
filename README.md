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
console.warn()
```

To provide IE8 support add this methods to your project (see [js/missed.js](https://github.com/ivkremer/jquery-simple-combobox/blob/master/js/missed.js) file).

Thanks to
---------

* [danieltim300](https://github.com/danieltim300)
* [taitranvn](https://github.com/taitranvn)
* [joweiser](https://github.com/joweiser)

For bug reporting and improving this project.

License
-------

The MIT License (MIT)

Copyright (c) 2014 Ilya Kremer
