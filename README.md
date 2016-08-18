# css-font-family 0.0.7

Css module of single purpose classes for font family

#### Stats

276 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-font-family
```

#### With Git

```
git clone https://github.com/tachyons-css/css-font-family
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-font-family";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-font-family">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FONT FAMILY
*/
.serif { font-family: georgia, serif; }
.sans-serif { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
.font-fantasy { font-family: fantasy; }
.font-cursive { font-family: cursive; }
.font-mono { font-family: monospace; }
@media screen and (min-width: 48em) {
 .serif-ns { font-family: georgia, serif; }
 .sans-serif-ns { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
 .font-fantasy-ns { font-family: fantasy; }
 .font-cursive-ns { font-family: cursive; }
 .font-mono-ns { font-family: monospace; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .serif-m { font-family: georgia, serif; }
 .sans-serif-m { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
 .font-fantasy-m { font-family: fantasy; }
 .font-cursive-m { font-family: cursive; }
 .font-mono-m { font-family: monospace; }
}
@media screen and (min-width: 64em) {
 .serif-l { font-family: georgia, serif; }
 .sans-serif-l { font-family: avenir, 'avenir next', helvetica, arial, sans-serif; }
 .font-fantasy-l { font-family: fantasy; }
 .font-cursive-l { font-family: cursive; }
 .font-mono-l { font-family: monospace; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
