# CSS FLEX ALIGN CONTENT

  Mobile-first classes for css-flex-align-content.
  Set the desired css-flex-align-content on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-flex-align-content
```
View on [npm](https://www.npmjs.org/package/css-flex-align-content)


## File Size

1.3K flex-align-content.css
1.0K flex-align-content.min.css
242B minified and gzipped

## The Code
```
.ac-fs { align-content: flex-start; }
.ac-fe { align-content: flex-end; }
.ac-c {  align-content: center; }
.ac-sb { align-content: space-between; }
.ac-sa { align-content: space-around; }
.ac-s {  align-content: stretch; }
.ac-i {  align-content: inherit; }

@media screen and (min-width: 48em) {
  .ac-fs-ns { align-content: flex-start; }
  .ac-fe-ns { align-content: flex-end; }
  .ac-c-ns {  align-content: center; }
  .ac-sb-ns { align-content: space-between; }
  .ac-sa-ns { align-content: space-around; }
  .ac-s-ns {  align-content: stretch; }
  .ac-i-ns {  align-content: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ac-fs-m { align-content: flex-start; }
  .ac-fe-m { align-content: flex-end; }
  .ac-c-m {  align-content: center; }
  .ac-sb-m { align-content: space-between; }
  .ac-sa-m { align-content: space-around; }
  .ac-s-m {  align-content: stretch; }
  .ac-i-m {  align-content: inherit; }
}

@media screen and (min-width: 64em)  {
  .ac-fs-l { align-content: flex-start; }
  .ac-fe-l { align-content: flex-end; }
  .ac-c-l {  align-content: center; }
  .ac-sb-l { align-content: space-between; }
  .ac-sa-l { align-content: space-around; }
  .ac-s-l {  align-content: stretch; }
  .ac-i-l {  align-content: inherit; }
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

