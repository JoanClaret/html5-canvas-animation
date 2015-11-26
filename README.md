3D lines animation with three.js 
========================================
...and an animated background color


Tags
-----------
HTML5, javascript, canvas, three.js, animation, colors.


What is?
-----------

I took a prebuild three.js [example](http://threejs.org/examples/#canvas_lines) and put a fancy animated background color, adjusted some parameters like number of lines, perspective and colors. Now is ready to use for everyone.

Online demo
-----------
[Check out the online demo](http://joanclaret.github.io/html5-canvas-animation/)


Preview
-----------

![html5 canvas animation preview](http://joanclaret.github.io/html5-canvas-animation/preview.png)



How it works?
-----------

### Javascript initialization

```html
<!-- Main library -->
<script src="js/three.min.js"></script>
      
<!-- Helpers -->
<script src="js/projector.js"></script>
<script src="js/canvas-renderer.js"></script>

<!-- Visualitzation adjustments -->
<script src="js/3d-lines-animation.js"></script>

<!-- Animated background color -->
<script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.2/jquery.min.js"></script>
<script src="js/color.js"></script>
```

### Layout

```html
<div class="canvas-wrap">
    <div class="canvas-content">
        <h1>Hello world</h1>
    </div>
    <div id="canvas" class="gradient"></div>
</div>
```

### Options

* The script is fully configurable (colors, lines, opacities, perspectives...) but you'll need to dive in to the code to adjust them. Download the files and start checking out the file 3d-lines-animation.js

### Follow the repository
★ Star and watch [this repo](https://github.com/JoanClaret/html5-canvas-animation) in order to stay updated with news about this plugin


License
-------

    The MIT License (MIT)

    Copyright (c) 2015 Joan Claret

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
    
Other useful  plugins
----------------------
* [Maximum Characters limit warning](https://github.com/JoanClaret/max-char-limit-warning): Get a warning when the max char limit has been exceeded with a jQuery plugin
* [jcSlider](http://joanclaret.github.io/jcSlider): A responsive slider jQuery plugin with CSS animations 
* [slide and swipe menu](http://joanclaret.github.io/slide-and-swipe-menu): A sliding swipe menu that works with touchSwipe library. 
* [jquery dynamic max height](http://joanclaret.github.io/jquery-dynamic-max-height) : Dynamic max height plugin for jQuery with CSS animation
