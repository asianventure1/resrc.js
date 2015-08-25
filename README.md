![ReSRC Logo](http://www.resrc.it/img/github/logo-github.png)

[resrc.js](http://www.resrc.it/docs/javascript/0.9) - Responsive Image Library
==========================================================================

resrc.js is a small, mobile friendly responsive image JavaScript library that produces pixel perfect images on demand.
The library requires your images to be served via [ReSRC](http://www.resrc.it) - The Responsive Image Service. Link your images to our simple service and let us take care of everything!

Register your domain for a [FREE TRIAL](http://www.resrc.it/signup).

## Features

* HiDPI (retina) Support
* CSS background Support
* [Plugin support](https://github.com/resrcit/resrc.plugin-boilerplate.js) for features such as: [art direction](https://github.com/resrcit/resrc.breakpoint.js), [sharding](https://github.com/resrcit/resrc.shard.js) etc
* Pinch and zoom Image support (Currently iOS only)
* No multiple requests for the same image
* Remote image fallback
* Pixel rounding support
* Placeholder image support
* Supports the popular ‘Mobile First’ approach
* Optional http image requests for image down sizing
* Does not use device detection via user-agents or cookies

## Browser Support ##
resrc.js has extensive browser support on Windows/Mac/Linux/iOS/Android.  
We have made sure it works on **Internet Explorer 6** and above.

![Browser Support](http://www.resrc.it/img/github/browser-icons.png)

## Demos ##
[Simple](http://jsfiddle.net/tpq17026) | [Custom Options](http://jsfiddle.net/sgqfrfus) | [Preview approach (aka: Mobile First)](http://jsfiddle.net/jtv1u9j9) | [Art Direction](http://jsfiddle.net/enobsrm0)

## Examples ##
[Simple](https://github.com/resrcit/resrc.js/blob/master/examples/simple.html) | [CSS Background](https://github.com/resrcit/resrc.js/blob/master/examples/css-background.html) | [Preview approach (aka: Mobile First)](https://github.com/resrcit/resrc.js/blob/master/examples/preview-mobilefirst.html) 

## Plugins ##

resrc.js supports plugins so you can add any additional functionality you may require. [Learn More](https://github.com/resrcit/resrc.plugin-boilerplate.js)

## Latest Release: 0.9.5

For a full list of releases and changes please see the [CHANGELOG](https://github.com/resrcit/resrc.js/blob/master/CHANGELOG.md).

## Documentation

Please see [DOCUMENTATION](http://www.resrc.it/docs/javascript/0.9).

## Running Tests [![Build Status](https://travis-ci.org/resrcit/resrc.js.svg)](https://travis-ci.org/resrcit/resrc.js)

To run the tests, simply run ```npm install``` if you haven't already, followed by ```npm test```.

## Building a minified release

The repository does not contain a minified resrc.min.js file - this is only generated
for [RELEASES](https://github.com/resrcit/resrc.js/releases). To build your own minified copy
for use in development simply run ```npm install``` if you haven't already, followed by ```grunt build```.
This will generate a resrc.min.js file in the `dist` subdirectory.

## Team

resrc.js is actively developed by [Dom](https://github.com/domfee). [Ed](https://github.com/ejthurgo) works his magic server side, building the core engine. 

[![Dom Fee](https://avatars0.githubusercontent.com/u/2632889?v=2&s=100)](https://github.com/domfee) | [![Ed Thurgood](https://avatars0.githubusercontent.com/u/6924421?v=2&s=100)](https://github.com/ejthurgo)
--- | --- | 
[Dom Fee](https://github.com/domfee) | [Ed Thurgood](https://github.com/ejthurgo)

## Contributing

Please see the [CONTRIBUTING](https://github.com/resrcit/resrc.js/blob/master/CONTRIBUTING.md) file for guidelines.

## Contact

Please get in touch via: [EMAIL](mailto:support@resrc.it).

## License

Copyright (C) 2014-2015 by [ReSRC LTD](http://www.resrc.it)
Licensed under the GNU GENERAL PUBLIC LICENSE, Version 2, June 1991

Please see [LICENSE](https://github.com/resrcit/resrc.js/blob/master/LICENSE).