# Static Site Builder

A grunt-based scaffolding project for static sites. Allows users to compile handlebars templates, minify CSS, uglify JS, etc., without a server.

## Installation

Requires Node and Grunt:

* Node.js / npm: [http://nodejs.org/download/](http://nodejs.org/download/ "node.js / npm")

* Grunt: [http://gruntjs.com/getting-started](http://gruntjs.com/getting-started "Grunt")

Run the following in this project's root directory:

    $ npm install

## Usage

In order to build the site from the src/ folder (i.e. compile Handlebars files to HTML, minify CSS, etc.), run the following command (again, from the root directory of this project):

    $ grunt

Even better, you can use the following command to make Grunt automatically build whenever a src file has changed:

    $ grunt watch

In order to view this website, you should run a small HTTP server from the build/ directory. I highly recommend using python's SimpleHTTPServer:

    $ python -m SimpleHTTPServer

When ready to deploy your site, only deploy the build/ directory to your server.

## License

The MIT License (MIT)

Copyright (c) 2014 Ryan Hansberry

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

