# Next Gen JavaScript Boilerplate

## Introduction

> This project is first to train with tools like [babeljs.io](https://babeljs.io/), [es2015](https://babeljs.io/docs/learn-es2015/)... And then I used it as Boilerplate for my es6/es2015 projects.

## Requirements

 * [nodejs](http://nodejs.org/)
 * [Gulp](http://gulpjs.com/)
 * [sass](http://sass-lang.com/)

## Optional

 * [Mongodb](http://www.mongodb.org/)
  * [Install on Ubuntu](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/)
  * [Install on OS X](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/)

## Installation

* `$ git clone git@github.com:kiki-le-singe/next-gen-javascript-boilerplate.git`
* `$ cd next-gen-javascript-boilerplate`
* `$ npm install`

## Gulp tasks

* `$ gulp serve`

Then serve the app on `localhost:3000` with [Browsersync](http://www.browsersync.io/) and opens your default browser

* `$ gulp serve --stub`

Makes the same thing that the above command, except that the 'stub' option allows to enabled or not the retrieving of fake datas.

* `$ gulp test`

Coming soon...

* `$ gulp dist`

Coming soon...

* `$ gulp build`

Coming soon...

* `$ gulp docs`

Coming soon...

* `$ gulp plato`

Coming soon...

* `$ gulp changelog`

Coming soon...

## Included JavaScript libraries

 * [browserify](http://browserify.org/)
 * [jQuery](http://jquery.com/)
 * [Lo-Dash](http://lodash.com/)

## Build Tools

 * [ESlint](http://eslint.org/)
 * [Babel](https://babeljs.io/)

## Included SASS libraries/framework

 * [Bourbon](http://bourbon.io/)

 > A simple and lightweight mixin library for Sass.

 * [Bourbon NEAT](http://neat.bourbon.io/)

 > A lightweight semantic grid framework for Sass and Bourbon.

## API

By default the root access for the API is http://localhost:3000/api. Available example: http://localhost:3000/api/tools

## Tips and tricks

 * [mongo-express](https://www.npmjs.org/package/mongo-express)

 > If you use MongoDB, look at this node modules. It's an convenient admin interface for MongoDB.

### Experimental ES7 features

 * [Babel - What are the various transformers?](http://babeljs.io/docs/advanced/transformers/)
 * [Babel - How to use experimental ES7 features](https://babeljs.io/docs/usage/experimental/)
 * [babelify](https://www.npmjs.com/package/babelify)

 > babelify - Set stage option to 0 for to have all ES7 experimental features

## Encountered problems

 * [Fast browserify builds with watchify](https://github.com/gulpjs/gulp/blob/master/docs/recipes/fast-browserify-builds-with-watchify.md)
