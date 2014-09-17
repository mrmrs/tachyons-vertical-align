# TACHYONS-VERTICAL-ALIGN

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-vertical-align
```
or download the css on github and include in your project.

## The Code
```

/*
   VERTICAL ALIGN
*/

.v-base     { vertical-align: baseline; }
.v-sub      { vertical-align: sub; }
.v-sup      { vertical-align: super; }
.v-txt-top  { vertical-align: text-top; }
.v-txt-btm  { vertical-align: text-bottom; }
.v-mid      { vertical-align: middle; }
.v-top      { vertical-align: top; }
.v-btm      { vertical-align: bottom; }

@include break(not-small) {
  .v-base-ns     { vertical-align: baseline; }
  .v-sub-ns      { vertical-align: sub; }
  .v-sup-ns      { vertical-align: super; }
  .v-txt-top-ns  { vertical-align: text-top; }
  .v-txt-btm-ns  { vertical-align: text-bottom; }
  .v-mid-ns      { vertical-align: middle; }
  .v-top-ns      { vertical-align: top; }
  .v-btm-ns      { vertical-align: bottom; }
}

@include break(medium) {
  .v-base-m     { vertical-align: baseline; }
  .v-sub-m      { vertical-align: sub; }
  .v-sup-m      { vertical-align: super; }
  .v-txt-top-m  { vertical-align: text-top; }
  .v-txt-btm-m  { vertical-align: text-bottom; }
  .v-mid-m      { vertical-align: middle; }
  .v-top-m      { vertical-align: top; }
  .v-btm-m      { vertical-align: bottom; }
}

@include break(large) {
  .v-base-l     { vertical-align: baseline; }
  .v-sub-l      { vertical-align: sub; }
  .v-sup-l      { vertical-align: super; }
  .v-txt-top-l  { vertical-align: text-top; }
  .v-txt-btm-l  { vertical-align: text-bottom; }
  .v-mid-l      { vertical-align: middle; }
  .v-top-l      { vertical-align: top; }
  .v-btm-l      { vertical-align: bottom; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

