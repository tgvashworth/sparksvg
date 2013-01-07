# Spark SVG — [sparksvg.me](http://sparksvg.me)

![OMG Sparklines](http://i.phuu.net/Lz7N/Screen%20Shot%202013-01-06%20at%2021.03.15.png)

Mothereffin' SVG sparklines.

Orignally by [Stuart Langridge](http://kryogenix.org/days/2012/12/30/simple-svg-sparklines), based on an idea from [Jeremy Keith](http://adactio.com/journal/5941/).

## Basic usage

### line.svg

```html
<embed src="//sparksvg.me/line.svg?0,4,7,10,8,12,9,7,3,0" type="image/svg+xml"></embed>
```

![Example Line SVG](http://i.phuu.net/Ly00/Screen%20Shot%202013-01-06%20at%2012.09.42.png)

### bar.svg

```html
<embed src="//sparksvg.me/bar.svg?0,4,7,10,8,12,9,7,3,0" type="image/svg+xml"></embed>
```

![Example Bar SVG](http://i.phuu.net/Ly4g/Screen%20Shot%202013-01-06%20at%2012.52.59.png)

### circle.svg

The `circle.svg` redraws itself when the page is resized, so it's always looking smart. Excepting in buggy Firefox, where it can't get its height properly and tries to guess.

```html
<embed src="//sparksvg.me/circle.svg?0,4,7,10,8,12,9,7,3,0" type="image/svg+xml"></embed>
```

![Example Circle SVG](http://i.phuu.net/Lyym/Screen%20Shot%202013-01-06%20at%2020.41.46.png)

## Tested & working in

Using the [test page](http://sparksvg.me/test.html). **Feel free to do your own testing.**

### OSX 10.8.2

- Chrome
  - 23.0.1271.101
  - 26.0.1376.0 canary
- Firefox **(circles are buggy)**
  - 17.0.1
  - Nightly 20.0a1 (2012-12-11)
- Safari
  - 6.0.2
- Opera
  - 12.11
  - Next 12.50 internal

### Windows XP (via browserstack)

- Chrome
  - 23.0
  - 24.0
- Firefox
  - 16.0
  - 17.0 beta
- Safari
  - 5.1
- Opera
  - 12.10

### Windows 7 (via browserstack)

- IE
  - 9
- Chrome
  - 23.0
  - 24.0
- Firefox
  - 16.0
  - 17.0 beta
- Safari
  - 5.1
- Opera
  - 12.10

### Windows 8 (via browserstack)

- IE
  - 10.0
  - 10.0 metro **using `<object>` doesn't work - recommending `<embed>`**

## License

Copyright (c) 2012 Stuart Langridge & Tom Ashworth

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
