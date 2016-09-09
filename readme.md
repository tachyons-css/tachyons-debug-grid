# tachyons-debug-grid 1.0.1

Base CSS module for Tachyons

#### Stats

345 | 4 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-debug-grid
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-debug-grid
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-debug-grid.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-debug-grid";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-debug-grid@1.0.1/css/tachyons-debug-grid.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-debug-grid">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   DEBUG GRID

   Can be useful for debugging layout issues
   or helping to make sure things line up perfectly.
   Just tack one of these classes onto a parent element.

*/
/* variables */
.debug-grid { background-image: -webkit-repeating-linear-gradient( left, transparent, transparent 7px, #cdecff 8px ), -webkit-repeating-linear-gradient( top, transparent, transparent 7px, #cdecff 8px ); background-image: repeating-linear-gradient( to right, transparent, transparent 7px, #cdecff 8px ), repeating-linear-gradient( to bottom, transparent, transparent 7px, #cdecff 8px ); }
.debug-grid-16 { background-image: -webkit-repeating-linear-gradient( left, transparent, transparent 15px, #cdecff 16px ), -webkit-repeating-linear-gradient( top, transparent, transparent 15px, #cdecff 16px ); background-image: repeating-linear-gradient( to right, transparent, transparent 15px, #cdecff 16px ), repeating-linear-gradient( to bottom, transparent, transparent 15px, #cdecff 16px ); }
.debug-grid-8-solid { background-image: -webkit-repeating-linear-gradient( left, transparent, transparent 7px, #cdecff 8px ), -webkit-repeating-linear-gradient( top, #fff, #fff 7px, #cdecff 8px ); background-image: repeating-linear-gradient( to right, transparent, transparent 7px, #cdecff 8px ), repeating-linear-gradient( to bottom, #fff, #fff 7px, #cdecff 8px ); }
.debug-grid-16-solid { background-image: -webkit-repeating-linear-gradient( left, transparent, transparent 15px, #cdecff 16px ), -webkit-repeating-linear-gradient( top, #fff, #fff 15px, #cdecff 16px ); background-image: repeating-linear-gradient( to right, transparent, transparent 15px, #cdecff 16px ), repeating-linear-gradient( to bottom, #fff, #fff 15px, #cdecff 16px ); }
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

