# tachyons-debug-grid 1.0.0

Base CSS module for Tachyons

#### Stats

267 | 4 | 4
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
<link rel="stylesheet" href="http://npmcdn.com/tachyons-debug-grid@1.0.0/css/tachyons-debug-grid.min.css" />
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
.debug-grid { background: transparent url( http://tachyons.io/img/8-grid-blue-alpha.png ) repeat top left; }
.debug-grid-16 { background: transparent url( http://tachyons.io/img/16-grid-blue-alpha.png ) repeat top left; }
.debug-grid-8-solid { background: white url( http://tachyons.io/img/8-grid.jpg ) repeat top left; }
.debug-grid-16-solid { background: white url( http://tachyons.io/img/16-grid.png ) repeat top left; }
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

