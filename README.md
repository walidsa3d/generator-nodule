# generator-nodejs

A node.js module scaffolding generator for [Yeoman](http://yeoman.io).

[![Build Status](https://secure.travis-ci.org/walidsa3d/generator-nodule.png?branch=master)](https://travis-ci.org/eugeneware/generator-nodejs)

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

* package-json - initialized with the answers to all your questions.
* Gruntfile.js (if grunt is selected) - configured to use the following grunt modules:
    * grunt-complexity - show code complexity
    * grunt-contrib-watch - watch for changes then run tests
    * grunt-mocha-cli - run mocha tests (because `mocha -w` sucks)
* .travis.yml - set up so you can push and get [travis-ci](http://travis-ci.org)
   continous integration tests.
* .gitignore - ignore the usual cruft.
* LICENSE - MIT license initialized with your details.
* README.md - Initialized with your details and travis-ci badges.
* index.js - Initial library file
* test/index.js - First unit test in the test framework of your choosing
  (ie. mocha, tape, or redtape)

