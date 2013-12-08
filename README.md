jQuery Simple Combobox plugin
=============================

A jQuery combobox plugin.

Usage
-----

You can find reference in index.html and see [fiddles here](http://jsfiddle.net/user/ivkremer/fiddles/ "JSFiddle") to understand its features.

I'm sorry there is another name of a plugin in the fiddles currently, I am goint to fix it ASAP. By the way, you can change the name of a plugin in your code by changing ```var pname = 'scombobox';``` line (starting the script). Make sure your CSS class prefixes correcpond this name.

### IE8 compatibility ###

This plugin uses the following JS native stuff:

```JavaScript
String.prototype.trim()
Object.keys()
console.warn()
```

To provide IE8 support add this methods to your project.

License
-------

The MIT License (MIT)

Copyright (c) 2013 Ilya Kremer
