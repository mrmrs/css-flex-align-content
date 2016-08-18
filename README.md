# css-flex-align-content 0.0.7

Css module of single purpose classes for flex align content

#### Stats

284 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-align-content
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-align-content
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-align-content";
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
<link rel="stylesheet" href="path/to/module/css/css-flex-align-content">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX ALIGN CONTENT
*/
.ac-fs { align-content: flex-start; }
.ac-fe { align-content: flex-end; }
.ac-c { align-content: center; }
.ac-sb { align-content: space-between; }
.ac-sa { align-content: space-around; }
.ac-s { align-content: stretch; }
.ac-i { align-content: inherit; }
@media screen and (min-width: 48em) {
 .ac-fs-ns { align-content: flex-start; }
 .ac-fe-ns { align-content: flex-end; }
 .ac-c-ns { align-content: center; }
 .ac-sb-ns { align-content: space-between; }
 .ac-sa-ns { align-content: space-around; }
 .ac-s-ns { align-content: stretch; }
 .ac-i-ns { align-content: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ac-fs-m { align-content: flex-start; }
 .ac-fe-m { align-content: flex-end; }
 .ac-c-m { align-content: center; }
 .ac-sb-m { align-content: space-between; }
 .ac-sa-m { align-content: space-around; }
 .ac-s-m { align-content: stretch; }
 .ac-i-m { align-content: inherit; }
}
@media screen and (min-width: 64em) {
 .ac-fs-l { align-content: flex-start; }
 .ac-fe-l { align-content: flex-end; }
 .ac-c-l { align-content: center; }
 .ac-sb-l { align-content: space-between; }
 .ac-sa-l { align-content: space-around; }
 .ac-s-l { align-content: stretch; }
 .ac-i-l { align-content: inherit; }
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
