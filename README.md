# generator-nodule

A node.js module generator for [Yeoman](http://yeoman.io).

[![Build Status](https://secure.travis-ci.org/walidsa3d/generator-nodule.png?branch=master)](https://travis-ci.org/walidsa3d/generator-nodule)

### Installation

To install generator-nodule from npm, run:

```
$ npm install -g generator-nodule
```

Finally, initiate the generator:

```
$ yo nodule
```
This generator will install the following files:

* package-json.
* Gruntfile.js : configured to use the following grunt modules:
    * grunt-complexity - show code complexity
    * grunt-contrib-watch - watch for changes then run tests
    * grunt-mocha-cli - run mocha tests
    * grunt-bump - easily release versions
* .travis.yml : for continous integration.
* .gitignore : ignore the usual stuff.
* LICENSE - MIT license initialized with your details.
* README.md - Initialized with your details and travis-ci badges.
* index.js - dummy javascript file
* test/index.js - unit tests using moch and chai

