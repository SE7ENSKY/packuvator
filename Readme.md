# Packuvator

 Render Jade/CoffeeScript/Stylus template directory into HTML/JS/CSS zip archive.

## Installation

```bash
$ npm install -g packuvator
```

### Example

```
packuvator <input dir> <output dir>
```

### Features

 - render Jade templates to HTML files
 - load jade locals from js/coffee files from data directory
 - render Stylus stylesheets to CSS files
 - render CoffeeScript script to JS files
 - remove source .styl, .coffee, .jade
 - ignore files such as includes, mixins and other with .packuvator_ignore file

### Requirements
 - requires .packuvator_ignore file in input dir. By default, it contains:
```
^\/includes
^\/layouts
^\/data
```

### Authors

  - [Se7enSky studio](http://www.se7ensky.com/)
  - [Ivan Kravchenko](http://github.com/krava)

## License 

(The MIT License)

Copyright (c) 2013 Se7enSky studio &lt;info@se7ensky.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
