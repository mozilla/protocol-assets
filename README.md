# Protocol Assets

[![npm version](https://img.shields.io/npm/v/feather-icons.svg?style=flat-square)](https://www.npmjs.com/package/@mozilla-protocol/assets)

This repository contains a set of reusable assets for Mozilla's websites. These assets are available as both svg and png files. Assets include logos and icons.

Protocol icons are a derivative of [Feather icons](https://feathericons.com/), used under the [MIT License](https://github.com/colebemis/feather/blob/master/LICENSE)


What's included
-----------------

Icons
=====

For the most part icons are black SVGs. There are a few white variations for historical reasons. These have the sufix `-white` in the file name.

There is also a set of colorful "brand" icons in SVG format, in four different color schemes drawn from the Firefox brand palette.

Logos
=====

SVG logo and logo + wordmark files are included for a number of Mozilla and Firefox products. Sizing varies; you should declare the height and width you want when you use them.

### Variations

* `logo` = the logo is part of the file
* `word` = the wordmark is in the file
* `ver` = the logo is above the wordmark
* `hor` = the logo is to the left of the wordmark
* `stack` = each word in the wordmark is on a new line
* `flat` = the image is a single, solid color with no shading or gradients
* `white` = the image is intended for use on a dark background
  * if the image does not have "white" in the file name it's meant for use on a light background
* `og` = this is an open graph image for the product

Favicons are not included at this time; we encourage you to generate them yourself from the files included here.

Code of Conduct
---------------

This repository is governed by Mozilla's code of conduct and etiquette guidelines.
For more details, please see the [Mozilla Community Participation Guidelines][participation]
and [Developer Etiquette Guidelines][etiquette].

[participation]: https://www.mozilla.org/about/governance/policies/participation/
[etiquette]: https://bugzilla.mozilla.org/page.cgi?id=etiquette.html


License
-------

This software is licensed under the [MPL version 2.0][MPL]. For more
information, read the file ``LICENSE``.

[MPL]: https://www.mozilla.org/MPL/
