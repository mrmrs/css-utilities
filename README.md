# CSS UTILITIES

  Mobile-first classes for css-utilities.
  Set the desired css-utilities on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-utilities
```
View on [npm](https://www.npmjs.org/package/css-utilities)


## File Size

1.3K utilities.css
398B utilities.min.css

## The Code
```
 *  http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/
 *
 *  <div class="media attribution">
 *
 *    <a href="http://twitter.com/stubbornella" class="img">
 *      <img src="http://stubbornella.com/profile_image.jpg" alt="me" />
 *    </a>
 *
 *    <div class="bd">
 *      @Stubbornella 14 minutes ago
 *    </div>
 *
 *   </div>
 */



/*
 * The Flag Object
 * Built by @csswizzrdry
 * http://csswizardry.com/2013/05/the-flag-object/
 *
 *
 * Use to vertically center text against an image.
 *
 *  <div class="flag">
 *      <div class="flag--img">
 *          <img src="" alt="">
 *      </div>
 *      <div class="flag--bd">
 *          <p></p>
 *      </div>
 *  </div>
 *
 */

.flag {
    display: table;
    width: 100%;
}

.flag--img,
.flag--bd {
    display: table-cell;
    vertical-align: middle;

    .flag--top & {
        vertical-align: top;
    }

    .flag--bottom & {
        vertical-align: bottom;
    }

}

.flag--img {
    padding-right: 10px;

    > img {
        display: block;
        max-width: none;
    }

    .flag--rev & {
        padding-right: 0;
        padding-left: 10px;
    }

}

.flag--body {
    width: 100%;
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

