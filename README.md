Cocoapod Badges
===============

[![NSStringMask](http://cocoapod-badges.herokuapp.com/v/nsstringmask/badge.png)](http://cocoadocs.org/docsets/NSStringMask) NSStringMask's lastest version badge

Cocoapod badges are status badges to inform a pod's latest version deployed to [Cocoapods](http://cocoapods.org)!

The badges are created from `SVG`, thanks to [olivierlacan/shields](https://github.com/olivierlacan/shields) repo that provides badges to:

- [Code Climate](https://codeclimate.com/changelog/510d4fde56b102523a0004bf)
- [Coveralls](https://coveralls.io/r/kaize/nastachku)
- [Gemfury/RubyGems](http://badge.fury.io/)
- [Gemnasium](http://blog.tech-angels.com/post/43141047457/gemnasium-v3-aka-gemnasium)
- [Travis CI](http://about.travis-ci.org/docs/user/status-images/)

No images are generated. The badges are `SVG` files interpreted by the browser. They may be saved, but if you look at their source code, you'll be able to see the `SVG` xml file.

The "badge service" is hosted at [Heroku](https://www.heroku.com/)

# Usage

Simple enough, all you have to do is replace the `$PODNAME` bellow with the name of a pod and the badge will automatically fetch the latest release in [Cocoapods](http://cocoapods.org)!

	http://cocoapod-badges.herokuapp.com/v/$PODNAME/badge.png


AFNetworking: [![$AFNetworking](http://cocoapod-badges.herokuapp.com/v/afnetworking/badge.png)](http://cocoadocs.org/docsets/AFNetworking)

# Warning

The project fetches the latest version through [Cocoapod](http://cocoapods.org)'s pod list file available [here](http://cocoadocs.org/documents.jsonp), therefore, it's not updated in real time!

Currently, the configuration was set to update the file hourly, so, if your badge is not updated immediately after you release a new version, give it a little time to figure it out!

# License

NSStringMask is licensed under the MIT License:

Copyright (c) 2013 Flávio Caetano ([http://flaviocaetano.com](http://flaviocaetano.com))

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.