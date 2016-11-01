# css-flex-align-content 1.0.6

Css module of single purpose classes for flex align content

#### Stats

339 | 28 | 56
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-align-content
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-flex-align-content
```

ssh:
```
git clone git@github.com:tachyons-css/css-flex-align-content.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-align-content";
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
<link rel="stylesheet" href="http://unpkg.com/css-flex-align-content@1.0.6/css/css-flex-align-content.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-align-content">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FLEX ALIGN CONTENT
*/
.ac-fs { -ms-flex-line-pack: start; align-content: flex-start; }
.ac-fe { -ms-flex-line-pack: end; align-content: flex-end; }
.ac-c { -ms-flex-line-pack: center; align-content: center; }
.ac-sb { -ms-flex-line-pack: justify; align-content: space-between; }
.ac-sa { -ms-flex-line-pack: distribute; align-content: space-around; }
.ac-s { -ms-flex-line-pack: stretch; align-content: stretch; }
.ac-i { -ms-flex-line-pack: inherit; align-content: inherit; }
@media screen and (min-width: 48em) {
 .ac-fs-ns { -ms-flex-line-pack: start; align-content: flex-start; }
 .ac-fe-ns { -ms-flex-line-pack: end; align-content: flex-end; }
 .ac-c-ns { -ms-flex-line-pack: center; align-content: center; }
 .ac-sb-ns { -ms-flex-line-pack: justify; align-content: space-between; }
 .ac-sa-ns { -ms-flex-line-pack: distribute; align-content: space-around; }
 .ac-s-ns { -ms-flex-line-pack: stretch; align-content: stretch; }
 .ac-i-ns { -ms-flex-line-pack: inherit; align-content: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ac-fs-m { -ms-flex-line-pack: start; align-content: flex-start; }
 .ac-fe-m { -ms-flex-line-pack: end; align-content: flex-end; }
 .ac-c-m { -ms-flex-line-pack: center; align-content: center; }
 .ac-sb-m { -ms-flex-line-pack: justify; align-content: space-between; }
 .ac-sa-m { -ms-flex-line-pack: distribute; align-content: space-around; }
 .ac-s-m { -ms-flex-line-pack: stretch; align-content: stretch; }
 .ac-i-m { -ms-flex-line-pack: inherit; align-content: inherit; }
}
@media screen and (min-width: 64em) {
 .ac-fs-l { -ms-flex-line-pack: start; align-content: flex-start; }
 .ac-fe-l { -ms-flex-line-pack: end; align-content: flex-end; }
 .ac-c-l { -ms-flex-line-pack: center; align-content: center; }
 .ac-sb-l { -ms-flex-line-pack: justify; align-content: space-between; }
 .ac-sa-l { -ms-flex-line-pack: distribute; align-content: space-around; }
 .ac-s-l { -ms-flex-line-pack: stretch; align-content: stretch; }
 .ac-i-l { -ms-flex-line-pack: inherit; align-content: inherit; }
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

