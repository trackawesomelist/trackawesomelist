# Es6 Tools Overview

An aggregation of tooling for using ES6 today

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/addyosmani/es6-tools/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) · ⭐ 3.9K · 🏷️ Front-End Development

[ [Daily](/content/addyosmani/es6-tools/README.md) / [Weekly](/content/addyosmani/es6-tools/week/README.md) / Overview ]

---

# <img src="http://i.imgur.com/yy1sACZ.png" width="100px"/> ECMAScript 6 Tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Transpilers

*   [Babel (⭐42k)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime
*   [Traceur compiler (⭐8.2k)](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.
*   [es6ify (⭐600)](https://github.com/thlorenz/es6ify) - Traceur compiler wrapped as a [Browserify](http://browserify.org/) v2 transform
*   [babelify (⭐1.7k)](https://github.com/babel/babelify) - Babel transpiler wrapped as a [Browserify](http://browserify.org/) transform
*   [es6-transpiler (⭐217)](https://github.com/termi/es6-transpiler) - ES6 > ES5. Includes classes, destructuring, default parameters, spread
*   Square's [es6-module-transpiler (⭐1.2k)](https://github.com/esnext/es6-module-transpiler) - ES6 modules to AMD or CJS
*   Facebook's [regenerator (⭐3.7k)](https://github.com/facebook/regenerator) - transform ES6 yield/generator functions to ES5
*   Facebook's [jstransform (⭐481)](https://github.com/facebookarchive/jstransform) - A simple utility for pluggable JS syntax transforms. Comes with a small set of ES6 -> ES5 transforms
*   [defs (⭐118)](https://github.com/olov/defs) - ES6 block-scoped const and let variables to ES3 vars
*   [es6\_module\_transpiler-rails (⭐87)](https://github.com/DavyJonesLocker/es6_module_transpiler-rails) - ES6 Modules in the Rails Asset Pipeline
*   [Some Sweet.js macros (⭐235)](https://github.com/jlongster/es6-macros) that compile from ES6 to ES5
*   Bitovi's [transpile (⭐25)](https://github.com/stealjs/transpile) - Converts ES6 to AMD, CJS, and StealJS.
*   [regexpu (⭐218)](https://github.com/mathiasbynens/regexpu) — Transform Unicode-aware ES6 regular expressions to ES5
*   [Lebab (⭐5.5k)](https://github.com/mohebifar/lebab) - Transformations for ES5 code to ES6 (approximates)

## Build-time transpilation

### Gulp Plugins

*   Babel: [gulp-babel (⭐1.3k)](https://github.com/babel/gulp-babel)
*   Traceur: [gulp-traceur (⭐169)](https://github.com/sindresorhus/gulp-traceur)
*   Regenerator: [gulp-regenerator (⭐18)](https://github.com/sindresorhus/gulp-regenerator)
*   ES6 Module Transpiler: [gulp-es6-module-transpiler (⭐61)](https://github.com/ryanseddon/gulp-es6-module-transpiler)
*   es6-transpiler: [gulp-es6-transpiler (⭐47)](https://github.com/sindresorhus/gulp-es6-transpiler) - ES6 → ES5
*   es6-jstransform: [gulp-jstransform (⭐16)](https://github.com/hemanth/gulp-jstransform) - ES6 → ES5 using FB's [jstransform (⭐481)](https://github.com/facebook/jstransform)
*   regexpu: [gulp-regexpu (⭐4)](https://github.com/mathiasbynens/gulp-regexpu)
*   TypeScript: [gulp-typescript (⭐773)](https://github.com/ivogabe/gulp-typescript)

### Grunt Tasks

*   Babel: [grunt-babel (⭐436)](https://github.com/babel/grunt-babel) - Turn ES6+ code into vanilla ES5 with no runtime
*   Traceur: [grunt-traceur (⭐206)](https://github.com/aaronfrost/grunt-traceur) ES6 > ES5 transpilation, [grunt-traceur-build (⭐8)](https://github.com/tarruda/grunt-traceur-build)
*   ES6 Module Transpiler: [grunt-es6-module-transpiler (⭐85)](https://github.com/joefiorini/grunt-es6-module-transpiler)
*   Regenerator: [grunt-regenerator (⭐20)](https://github.com/sindresorhus/grunt-regenerator) - ES6 generator functions to ES5
*   [grunt-microlib (⭐29)](https://github.com/thomasboyt/grunt-microlib) - tools for libs using ES6 module transpiler (sample [Gruntfile (⭐7.3k)](https://github.com/jakearchibald/es6-promise/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
*   [grunt-defs (⭐5)](https://github.com/EE/grunt-defs) - ES6 block scoped const and let variables, to ES3
*   es6-transpiler: [grunt-es6-transpiler (⭐11)](https://github.com/sindresorhus/grunt-es6-transpiler) - ES6 → ES5
*   TypeScript: [grunt-ts (⭐323)](https://github.com/TypeStrong/grunt-ts) - ES6+ > ES5/ES3 transpilation

### Broccoli Plugins

*   Babel: [broccoli-babel-transpiler (⭐55)](https://github.com/babel/broccoli-babel-transpiler)
*   Traceur: [broccoli-traceur (⭐29)](https://github.com/sindresorhus/broccoli-traceur)
*   Regenerator: [broccoli-regenerator (⭐6)](https://github.com/sindresorhus/broccoli-regenerator)
*   ES6 Transpiler: [broccoli-transpiler (⭐11)](https://github.com/sindresorhus/broccoli-es6-transpiler)
*   ES6 Module Transpiler: [broccoli-es6-module-transpiler (⭐5)](https://github.com/mmun/broccoli-es6-module-transpiler)
*   ES6 fat arrow transpiler: [broccoli-es6-arrow](https://github.com/hemanth/broccoli-es6-arrow.git)
*   TypeScript: [broccoli-tsc (⭐1)](https://github.com/ngParty/broccoli-tsc)

### Brunch Plugins

*   Babel: [babel-brunch (⭐68)](https://github.com/babel/babel-brunch)
*   ES6 Module Transpiler: [es6-module-transpiler-brunch (⭐9)](https://github.com/gcollazo/es6-module-transpiler-brunch)
*   TypeScript: [typescript-brunch](https://github.com/joshheyse/typescript-brunch)

## Webpack plugins

*   Babel: [babel-loader (⭐4.7k)](https://github.com/babel/babel-loader)
*   Traceur: [traceur-compiler-loader (⭐4)](https://github.com/gdi2290/traceur-compiler-loader)
*   TypeScript: [awesome-typescript-loader (⭐2.4k)](https://github.com/s-panferov/awesome-typescript-loader)

## Duo plugins

*   Babel: [duo-babel (⭐13)](https://github.com/babel/duo-babel)
*   TypeScript: [duo-typescript (⭐0)](https://github.com/frankwallis/duo-typescript)

## Connect plugins

*   Babel: [babel-connect (⭐26)](https://github.com/babel/babel-connect)
*   TypeScript: [typescript-middleware (⭐9)](https://github.com/brn/typescript-middleware)

## Gobble plugins

*   Babel: [gobble-babel (⭐8)](https://github.com/babel/gobble-babel)
*   Traceur: [gobble-es6-transpiler (⭐1)](https://github.com/gobblejs/gobble-es6-transpiler)

## Jade plugins

*   Babel: [jade-babel (⭐39)](https://github.com/babel/jade-babel)
*   Traceur: [jade-traceur](https://www.npmjs.com/package/jade-traceur)

## Jest plugins

*   Babel: [babel-jest (⭐139)](https://github.com/babel/babel-jest)

## Karma plugins

*   Babel: [karma-babel-preprocessor (⭐167)](https://github.com/babel/karma-babel-preprocessor)
*   Traceur: [karma-traceur-preprocessor (⭐13)](https://github.com/karma-runner/karma-traceur-preprocessor)
*   TypeScript: [karma-typescript-preprocessor (⭐50)](https://github.com/sergeyt/karma-typescript-preprocessor)

## Sprockets plugins

*   Babel: [sprockets-es6](https://github.com/josh/sprockets-es6)
*   Traceur: [sprockets-traceur (⭐25)](https://github.com/gunpowderlabs/sprockets-traceur)
*   TypeScript: [typescript-rails (⭐256)](https://github.com/typescript-ruby/typescript-rails)

## Browser plugins

*   [Scratch JS (⭐349)](https://github.com/richgilbank/Scratch-JS) - A Chrome/Opera DevTools extension to run ES6 on a page with either Babel or Traceur
*   [generator-typescript (⭐19)](https://github.com/mrkev/generator-typescript) - Yeoman generator for TypeScript apps

## Mocha plugins

*   [Mocha Traceur (⭐15)](https://github.com/domenic/mocha-traceur) - A simple plugin for Mocha to pass JS files through the Traceur compiler

## Module Loaders

*   ES6 [Module Loader polyfill (⭐2.2k)](https://github.com/ModuleLoader/es6-module-loader) (compat with latest spec and Traceur)
*   [js-loaders (⭐54)](https://github.com/jorendorff/js-loaders) - Mozilla's spec-compliant loader prototype
*   [JSPM](http://jspm.io/) - ES6, AMD, CJS module loading/package management
*   [Babel Module Loader (⭐4.7k)](https://github.com/babel/babel-loader)
*   [beck.js (⭐5)](https://github.com/unscriptable/beck) - toolkit for ES6 Module Loader pipelines, shim for legacy environments

## Boilerplates

*   [es6-boilerplate (⭐88)](https://github.com/davidjnelson/es6-boilerplate) - Tooling to allow the community to use es6 now via traceur in conjunction with amd and browser global modules, with source maps, concatenation, minification, compression, and unit testing in real browsers.
*   [es6-jspm-gulp-boilerplate (⭐137)](https://github.com/alexweber/es6-jspm-gulp-boilerplate) - Tooling to allow the community to use es6 now via babel in conjunction jspm, with source maps, concatenation, minification, compression, and unit testing in real browsers using es6.

## Code generation

*   [generator-node-esnext (⭐4)](https://github.com/briandipalma/generator-node-esnext) - Yeoman generator for Traceur apps
*   [generator-es6-babel (⭐9)](https://github.com/HenriqueLimas/generator-es6-babel) - Yeoman generator for Babel apps
*   [generator-gulp-babelify (⭐3)](https://github.com/HenriqueLimas/generator-gulp-babelify) - Yeoman generator for [Babel](https://babeljs.io/), [Browserify](http://browserify.org/) and [Gulp](http://gulpjs.com/)
*   [grunt-init-es6](https://www.npmjs.com/package/grunt-init-es6) - scaffold node modules with unit tests, authored in ES6
*   [Loom generators with ES6 ember modules (⭐15)](https://github.com/ryanflorence/loom-generators-ember)
*   Brunch [plugin](https://www.npmjs.com/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

*   [core-js (⭐18k)](https://github.com/zloirock/core-js) - Modular and compact polyfills for ES6 including Symbols, Map, Set, Iterators, Promises, setImmediate, Array generics, etc. The standard library used by [Babel (⭐42k)](https://github.com/babel/babel).
*   [es6-shim (⭐3.1k)](https://github.com/paulmillr/es6-shim) - almost all new ES6 methods — from Map, Set, String, Array, Object, Object.is and more.
*   [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/harmony-collections)
*   Polymer's [WeakMap shim (⭐45)](https://github.com/Polymer/WeakMap)
*   [`String.prototype.startsWith`](https://github.com/mathiasbynens/String.prototype.startsWith)
*   [`String.prototype.endsWith`](https://github.com/mathiasbynens/String.prototype.endsWith)
*   [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at)
*   [`String.prototype.repeat`](https://github.com/mathiasbynens/String.prototype.repeat)
*   [`String.prototype.includes`](https://github.com/mathiasbynens/String.prototype.includes)
*   [`String.prototype.codePointAt`](https://github.com/mathiasbynens/String.prototype.codePointAt)
*   [`String.fromCodePoint`](https://github.com/mathiasbynens/String.fromCodePoint)
*   [`Array.prototype.find`](https://github.com/paulmillr/Array.prototype.find)
*   [`Array.prototype.findIndex`](https://github.com/paulmillr/Array.prototype.findIndex)
*   [`Array.from`](https://github.com/mathiasbynens/Array.from)
*   [`Array.of`](https://github.com/mathiasbynens/Array.of)
*   [`Object.assign`](https://github.com/sindresorhus/object-assign)
*   [`Number.isFinite`](https://github.com/sindresorhus/is-finite)
*   [`Math.sign`](https://github.com/sindresorhus/math-sign)
*   [`RegExp.prototype.match`](https://github.com/mathiasbynens/RegExp.prototype.match)
*   [`RegExp.prototype.search`](https://github.com/mathiasbynens/RegExp.prototype.search)
*   [es6-promise (⭐7.3k)](https://github.com/jakearchibald/es6-promise) - polyfill for Promises matching the ES6 API
*   [ES6 Map Shim (⭐24)](https://github.com/eriwen/es6-map-shim) - destructive shim that follows the latest specification as closely as possible.
*   [`Function.create`](https://github.com/walling/Function.create.js)
*   [ES6 shim (⭐1.4k)](https://github.com/inexorabletash/polyfill/blob/master/es6.md)
*   [ES6 Symbol polyfill (⭐179)](https://github.com/medikoo/es6-symbol)
*   [ES6 Map, Set, WeakMap (⭐4)](https://github.com/EliSnow/Blitz-Collections)
*   [harmony-reflect (⭐445)](https://github.com/tvcutsem/harmony-reflect) - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) (contains the [Proxy API](http://soft.vub.ac.be/\~tvcutsem/proxies/))
*   [ES5 based shims in pure CJS style](https://gist.github.com/medikoo/102b7d0e697627133788#list-of-ecmascript-6-shims) -  Array, Object, Number, Math and String functions/methods, plus Map, Set, Symbol and WeakMap objects

## Editors

*   ES6 syntax highlighting for [Sublime Text and TextMate (⭐32)](https://github.com/Benvie/JavaScriptNext.tmLanguage)
*   ES6 syntax support in [WebStorm](https://www.jetbrains.com/webstorm/) and [PhpStorm](https://www.jetbrains.com/phpstorm/), compilation to ES5 with [file watchers or task runners](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)
*   DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur
*   Grammar and transpilation [package (⭐474)](https://github.com/gandm/language-babel)  for [Atom](https://atom.io/)
*   Learn ES6 transpilation options in Webstorm [Read Blog Post](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)

## Parsers

*   [Esprima](http://esprima.org) - JavaScript parser supporting ES6, parses to [ESTree AST format (⭐4.3k)](https://github.com/estree/estree)
*   [Acorn (⭐8.8k)](https://github.com/ternjs/acorn) - A small, fast, JavaScript-based JavaScript parser with ES6 support, parses to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
*   [esparse (⭐115)](https://github.com/zenparsing/esparse) - ES6 parser written in ES6.
*   [Traceur compiler (⭐8.2k)](https://github.com/google/traceur-compiler) also has built-in parser available under `traceur.syntax.Parser`.

## Other

*   [ES.next showcase (⭐300)](https://github.com/sindresorhus/esnext-showcase) - real-world usage examples of ES6 features
*   [looper (⭐16)](https://github.com/wycats/looper) - static analysis tools for ES6
*   [es6-module-packager](https://www.npmjs.com/package/es6-module-packager)
*   [es-dependency-graph (⭐30)](https://github.com/yahoo/es-dependency-graph) and [grunt-es-dependency-graph (⭐3)](https://github.com/yahoo/grunt-es-dependency-graph) - Generate a list of imports and exports from ES6 module files, useful for preloading, bundling, etc.
*   [es6-import-validate (⭐6)](https://github.com/sproutsocial/es6-import-validate) and [grunt-es6-import-validate (⭐3)](https://github.com/sproutsocial/grunt-es6-import-validate) - validate matching named/default import statements in ES6 modules.
*   [let-er (⭐186)](https://github.com/getify/let-er) - transpiles [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) (not accepted into ES6) into either ES3 or ES6
*   [Recast (⭐4.3k)](https://github.com/benjamn/recast) - Esprima-based JavaScript syntax tree transformer, conservative pretty-printer, and automatic source map generator. Used by several of the transpilers listed above, including [regenerator (⭐3.7k)](https://github.com/facebook/regenerator) and [es6-arrow-function (⭐52)](https://github.com/esnext/es6-arrow-function).
*   [Paws on ES6 (⭐332)](https://github.com/hemanth/paws-on-es6) -  Minimalist examples of ES6 functionalities.
*   [ES6 on node](http://h3manth.com/new/blog/2013/es6-on-nodejs/) - How to use ES6 features in node.js.
*   [es6-translate (⭐5)](https://github.com/calvinmetcalf/es6-translate) - Uses the ES6 loader hooks to load (node flavored) commonjs packages in ES6.
*   [Isparta (⭐645)](https://github.com/douglasduteil/isparta)
*   [babel-node](https://babeljs.io/docs/usage/cli/#babel-node) - Run node cli with ES6 transpiling using Babel.
*   [ES6 Lab setup (⭐28)](https://github.com/hemanth/es6-lab-setup) - A simple setup for transpiling ES6 to ES5 using `Babel` or `traceur` with `gulp` and `jasmine` support.
*   [TypeScript](http://www.typescriptlang.org/) - A superset of ECMAScript with strict typing that aims to align with ES6
*   [Rollup](http://rollupjs.org/) - Rollup is a next-generation JavaScript module bundler. Author your app or library using ES2015 modules, then efficiently bundle them up into a single file for use in browsers and Node.js

