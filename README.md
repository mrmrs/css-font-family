# CSS FONT FAMILY

  Mobile-first classes for css-font-family.
  Set the desired css-font-family on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-font-family
```
View on [npm](https://www.npmjs.org/package/css-font-family)


## File Size

1.2K font-family.css
1.0K font-family.min.css
241B minified and gzipped

## The Code
```
.serif {        font-family: georgia, serif; }
.sans-serif {   font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
.font-fantasy { font-family: fantasy; }
.font-cursive { font-family: cursive; }
.font-mono {    font-family: monospace; }

@media screen and (min-width: 48em) {
  .serif-ns        { font-family: georgia, serif; }
  .sans-serif-ns   { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
  .font-fantasy-ns { font-family: fantasy; }
  .font-cursive-ns { font-family: cursive; }
  .font-mono-ns    { font-family: monospace; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .serif-m        { font-family: georgia, serif; }
  .sans-serif-m   { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
  .font-fantasy-m { font-family: fantasy; }
  .font-cursive-m { font-family: cursive; }
  .font-mono-m    { font-family: monospace; }
}

@media screen and (min-width: 64em)  {
  .serif-l        { font-family: georgia, serif; }
  .sans-serif-l   { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
  .font-fantasy-l { font-family: fantasy; }
  .font-cursive-l { font-family: cursive; }
  .font-mono-l    { font-family: monospace; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

