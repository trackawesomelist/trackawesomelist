# Awesome Eslint Overview

A list of awesome ESLint plugins, configs, etc.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/dustinspecker/awesome-eslint/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 dustinspecker/awesome-eslint](https://github.com/dustinspecker/awesome-eslint) · ⭐ 3.3K · 🏷️ Programming Languages

[ [Daily](/content/dustinspecker/awesome-eslint/README.md) / [Weekly](/content/dustinspecker/awesome-eslint/week/README.md) / Overview ]

---

# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://eslint.org/assets/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](https://github.com/dustinspecker/awesome-eslint/blob/master/readme.md/contributing.md).

## Contents

*   [Configs](#configs)
    *   [Configs by Well-Known Companies/Organizations](#configs-by-well-known-companiesorganizations)
    *   [Other Prominent Configs (100 stars or so)](#other-prominent-configs-100-stars-or-so)
    *   [Other Configs](#other-configs)
*   [Preconfigured Configs with ESLint Set up](#preconfigured-configs-with-eslint-set-up)
*   [Plugins](#plugins)
    *   [Code Quality](#code-quality)
    *   [Compatibility](#compatibility)
    *   [CSS in JS](#css-in-js)
    *   [Deprecation](#deprecation)
    *   [Embedded](#embedded)
    *   [Frameworks](#frameworks)
    *   [Languages and Environments](#languages-and-environments)
    *   [Libraries](#libraries)
    *   [Misc](#misc)
    *   [Practices and Specific ES Features](#practices-and-specific-es-features)
    *   [Performance](#performance)
    *   [Security](#security)
    *   [Style](#style)
    *   [Testing Tools](#testing-tools)
*   [Parsers](#parsers)
*   [Formatters](#formatters)
*   [Globals](#globals)
*   [Tools](#tools)
*   [Developing for ESLint](#developing-for-eslint)
*   [Tutorials](#tutorials)
*   [Installation and Setup](#installation-and-setup)

## Configs

### Configs by Well-Known Companies/Organizations

*   [Airbnb (⭐128k)](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide (⭐128k)](https://github.com/airbnb/javascript).
*   [Airbnb-babel (⭐2)](https://github.com/davidjbradshaw/eslint-config-airbnb-babel) - Airbnb's ESLint config with Babel Support.
*   [Airbnb-typescript (⭐855)](https://github.com/iamturns/eslint-config-airbnb-typescript) - Airbnb's ESLint config with TypeScript support.
*   [Alloy (⭐2.4k)](https://github.com/AlloyTeam/eslint-config-alloy) - Progressive ESLint config for your React/Vue/TypeScript projects.
*   [ESLint (⭐21k)](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team.
*   [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
*   [Google (⭐1.7k)](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml).
*   [React App (⭐98k)](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app) - Sharable config for [React](https://reactjs.org) projects.
*   [Shopify (⭐401)](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md) - Shareable config for [Shopify's style guide (⭐246)](https://github.com/Shopify/javascript).
*   [Wikimedia (⭐19)](https://github.com/wikimedia/eslint-config-wikimedia) - Shareable config for [Wikimedia's style guide](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by [MediaWiki](https://www.mediawiki.org/).

### Other Prominent Configs (100 stars or so)

*   [Auto (⭐356)](https://github.com/davidjbradshaw/eslint-config-auto) - Automatically configure ESLint based on your project's dependencies.
*   [Canonical (⭐318)](https://github.com/gajus/eslint-config-canonical) - Shareable config for [Canonical style guide (⭐17)](https://github.com/gajus/canonical).

<!-- lint disable double-link -->

*   [Standard (⭐2.4k)](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style (⭐28k)](https://github.com/feross/standard).
*   [XO (⭐237)](https://github.com/xojs/eslint-config-xo) - Shareable config for [XO (⭐6.9k)](https://github.com/xojs/xo).

### Other Configs

*   [Adjunct (⭐41)](https://github.com/davidjbradshaw/eslint-config-adjunct) - A reasonable collection of plugins to use alongside your main ESLint configuration.
*   [Ash-Nazg (⭐5)](https://github.com/brettz9/eslint-config-ash-nazg) - One config to rule them all!
*   [Cecilia (⭐5)](https://github.com/SandroMiguel/eslint-config-cecilia) - ESLint configuration for awesome projects.
*   [ES (⭐27)](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code.
*   [Hardcore (⭐193)](https://github.com/EvgenyOrekhov/eslint-config-hardcore) - The most strict (but practical) ESLint config out there.
*   [Problems (⭐60)](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
*   [Supermind (⭐4)](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style.

## Preconfigured Configs with ESLint Set up

*   [Node.js Standard Style (⭐5)](https://github.com/geek/node-style) - Node.js core config.
*   [prettier-standard (⭐855)](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed.
*   [Standard (⭐28k)](https://github.com/feross/standard) - JavaScript Standard Style.
*   [Superlint (⭐3)](https://github.com/supermind/superlint) - JavaScript Supermind Style.
*   [XO (⭐6.9k)](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️.
*   [Healthier (⭐74)](https://github.com/KidkArolis/healthier) - Code style agnostic version of Standard, perfect companion to Prettier.

## Plugins

### Code Quality

*   [GitHub (⭐194)](https://github.com/github/eslint-plugin-github) - Misc. rules from GitHub.
*   [SonarJS (⭐826)](https://github.com/SonarSource/eslint-plugin-sonarjs) - Rules detecting bugs and suspicious patterns.
*   [Unicorn (⭐2.8k)](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules.
*   [@mysticatea/eslint-plugin (⭐25)](https://github.com/mysticatea/eslint-plugin) - Misc. rules.
*   [@brettz9/eslint-plugin (⭐1)](https://github.com/brettz9/eslint-plugin) - Misc. rules. of `@mysticatea` without the personal config.

### Compatibility

*   [Compat (⭐2.9k)](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatibility of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
*   [ecmascript-compat (⭐37)](https://github.com/robatwilliams/es-compat) - Disable ECMAScript language features not supported by your browserslist targets.
*   [es (⭐92)](https://github.com/mysticatea/eslint-plugin-es) - Disable specific ECMAScript language versions or individual features.
*   [es5 (⭐53)](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage).
*   [ie11 (⭐14)](https://github.com/Volox/eslint-plugin-ie11) - Detect unsupported ES6 features in IE11.

### CSS in JS

*   [CSS-modules (⭐128)](https://github.com/atfzl/eslint-plugin-css-modules) - Lint undefined or unused rules for css modules.
*   [Emotion (⭐16k)](https://github.com/emotion-js/emotion/tree/master/packages/eslint-plugin) - ESLint rules for emotion.
*   Styled Components
    *   [Better Styled Components (⭐55)](https://github.com/tinloof/eslint-plugin-better-styled-components) - Auto fixable ESlint's rules for styled components.
    *   [styled-components-a11y (⭐106)](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y) - A11y for Styled Components.

### Deprecation

*   [deprecate (⭐65)](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used.
*   [deprecation (⭐127)](https://github.com/gund/eslint-plugin-deprecation) - Identifies use of
    jsdoc `@deprecated` functions.
*   [disable (⭐52)](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments.

### Embedded

*   [HTML (⭐376)](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags.
*   [Markdown (⭐292)](https://github.com/eslint/eslint-plugin-markdown) - Linting for JavaScript inside of Markdown.

### Frameworks

*   [Angular (⭐1.3k)](https://github.com/angular-eslint/angular-eslint) - Linting rules for Angular (v2+).
*   [AngularJS (⭐613)](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's AngularJS Styleguide (⭐24k)](https://github.com/johnpapa/angular-styleguide).
*   [Astro (⭐43)](https://github.com/ota-meshi/eslint-plugin-astro) - Plugin for [Astro components](https://docs.astro.build/en/core-concepts/astro-components/).
*   [Backbone (⭐95)](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone.
*   [Custom Elements (⭐45)](https://github.com/github/eslint-plugin-custom-elements) - Rules by GitHub for Custom Elements.
*   [Ember (⭐254)](https://github.com/ember-cli/eslint-plugin-ember) - Linting rules for Ember.
*   [Hapi (⭐21)](https://github.com/continuationlabs/eslint-plugin-hapi) - Linting rules for hapi.
*   [Meteor (⭐116)](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules.
*   React
    *   [JSX a11y (⭐2.9k)](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements.
    *   [React (⭐8.1k)](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX.
    *   [React Hooks (⭐196k)](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - Linting rules for React Hooks.
    *   [React Native (⭐663)](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules.
    *   [React-Redux (⭐70)](https://github.com/DianaSuvorova/eslint-plugin-react-redux) - React-Redux specific linting rules.
*   [Solid (⭐79)](https://github.com/joshwilsonvu/eslint-plugin-solid) - Linting rules for Solid and JSX.
*   [Svelte (⭐339)](https://github.com/sveltejs/eslint-plugin-svelte3) - Linting rules for Svelte v3 Components.
*   Vue
    *   [VueJS (⭐3.9k)](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS.
    *   [VueJS Scoped CSS (⭐61)](https://github.com/future-architect/eslint-plugin-vue-scoped-css) - Plugin for Scoped CSS in VueJS.

### Languages and Environments

*   [AssemblyScript](https://www.npmjs.com/package/@shopify/eslint-plugin-assemblyscript) - Rules for enforcing restrictions on TypeScript toward AssemblyScript compliance.
*   [eslint-plugin-eslint-plugin (⭐132)](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins.
*   [Coffee (⭐11)](https://github.com/aminland/eslint-plugin-coffee) - Enables linting CoffeeScript files with, with optional linting rules from the Coffeelint library.
*   Flow
    *   [Flow (⭐1.1k)](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules.
    *   [Flow Errors (⭐409)](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin.
*   [HTML (⭐76)](https://github.com/yeonjuan/html-eslint) - ESLint plugin for HTML.
*   JSON
    *   [JSON (⭐162)](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files.
    *   [JSON, package.json (⭐34)](https://github.com/Bkucera/eslint-plugin-json-format) - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
    *   [JSON with Comments (⭐63)](https://github.com/ota-meshi/eslint-plugin-jsonc) - ESLint plugin for JSON, JSONC and JSON5.
    *   [JSON Schema (⭐33)](https://github.com/ota-meshi/eslint-plugin-json-schema-validator) - Validates data defined in JavaScript, JSON, YAML and TOML using JSON Schema Validator.
*   [MDX (⭐153)](https://github.com/mdx-js/eslint-mdx/tree/master/packages/eslint-plugin-mdx) - ESLint Parser/Plugin for MDX.
*   [Node (⭐895)](https://github.com/mysticatea/eslint-plugin-node) - Additional ESLint's rules for Node.js.
*   [SQL (⭐66)](https://github.com/gajus/eslint-plugin-sql) - SQL linting rules for ESLint.
*   [TOML (⭐10)](https://github.com/ota-meshi/eslint-plugin-toml) - ESLint plugin for TOML.
*   [TypeScript (⭐12k)](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin) - Linting rules for TypeScript.
*   [YAML (⭐39)](https://github.com/ota-meshi/eslint-plugin-yml) - ESLint plugin for YAML.

### Libraries

*   GraphQL
    *   [dotansimha/graphql-eslint (⭐577)](https://github.com/dotansimha/graphql-eslint) - Validates, prettifies and checks your GraphQL operations and GraphQL schema for best-practices.
    *   [apollostack/eslint-plugin-graphql (⭐1.2k)](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema.
*   [TypeGraphQL (⭐15)](https://github.com/borremosch/eslint-plugin-type-graphql) - Linting rules for TypeGraphQL, targeted at finding common mistakes.
*   [jQuery (⭐25)](https://github.com/wikimedia/eslint-plugin-no-jquery) - Linting rules for jQuery, including versioned configs for deprecated features.
*   [JSDoc (⭐751)](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments (including the JavaScript within `@example`).
*   Lodash
    *   [Lodash (⭐246)](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules.
    *   [Lodash/fp (⭐148)](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules.
    *   [Lodash template (⭐16)](https://github.com/ota-meshi/eslint-plugin-lodash-template) - Plugin for Lodash template/Underscore template.
    *   [Microtemplates (⭐4)](https://github.com/platinumazure/eslint-plugin-microtemplates) (Used in Lodash and Underscore.js)
*   [Mongodb (⭐17)](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native Node.js driver linting rules.
*   [Ramda (⭐117)](https://github.com/ramda/eslint-plugin-ramda) - Ramda specific linting rules.
*   [RequireJS (⭐28)](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS.

### Misc

*   [Diff (⭐78)](https://github.com/paleite/eslint-plugin-diff) - Run ESLint on your changed lines only. Also supports CI!
*   [Misc (⭐3)](https://github.com/ilyub/eslint-plugin-misc) - Miscellaneous rules including rules for creating custom checks and wrapping (modifying) third-party rules.
*   [Notice (⭐21)](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too!
*   [Only-Error (⭐9)](https://github.com/davidjbradshaw/eslint-plugin-only-error) - Convert all rules to errors.
*   [Only-Warn (⭐115)](https://github.com/bfanger/eslint-plugin-only-warn) - Convert all rules to warnings.
*   [PutOut (⭐396)](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout) - an ESLint plugin integrates [putout (⭐396)](https://github.com/coderaiser/putout) linter into ESLint.
*   [TypeLint (⭐174)](https://github.com/yarax/eslint-plugin-typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.
*   [Woke (⭐23)](https://github.com/amwmedia/eslint-plugin-woke) - Helps catch insensitive words, promoting an inclusive codebase.

### Practices and Specific ES Features

*   [array-func (⭐72)](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.
*   [arrow functions (⭐288)](https://github.com/getify/eslint-plugin-proper-arrows) - ESLint rules to ensure proper arrow function definitions.
*   [Babel (⭐42k)](https://github.com/babel/babel/tree/main/eslint/babel-eslint-plugin) - Adds replacements for built-in rules to include Babel features.
*   [boundaries (⭐294)](https://github.com/javierbrea/eslint-plugin-boundaries) - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
*   [ESLint Comments (⭐293)](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.).
*   [eslint-plugin-hexagonal-architecture (⭐128)](https://github.com/CodelyTV/eslint-plugin-hexagonal-architecture) - A plugin that helps you to enforce hexagonal architecture best practices.
*   [eslint-plugin-write-good-comments (⭐14)](https://github.com/kantord/eslint-plugin-write-good-comments) - Enforce good writing style in comments.
*   [fp (⭐940)](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming.
*   [functional (⭐552)](https://github.com/jonaskello/eslint-plugin-functional) - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
*   [Immutable (⭐909)](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript.
*   [import (⭐4.4k)](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names.
*   [new-with-error (⭐22)](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`.

<!-- lint ignore awesome-spell-check -->

*   [no-argument-spread (⭐2)](https://github.com/causalhq/eslint-plugin-no-argument-spread) - Lints against expressions like `Math.max(...args)` that can lead to a stack overflow for large arrays.
*   [no-constructor-bind (⭐10)](https://github.com/markalfred/eslint-plugin-no-constructor-bind) - Encourages use of class properties by reporting use of `this` with `bind` or setting state in constructors.
*   [no-inferred-method-name (⭐27)](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
*   [no-loops (⭐114)](https://github.com/buildo/eslint-plugin-no-loops) - It's 2019 and you still use loops?
*   [no-restricted-syntax (⭐4)](https://github.com/brettz9/eslint-plugin-query) - Show queried syntax's content in messages.
*   [no-use-extend-native (⭐50)](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects.
*   [Promise (⭐760)](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises.
*   [pure (⭐29)](https://github.com/purely-functional/eslint-plugin-pure) - Enforce pure functions (without side effects).
*   [RegExp (⭐187)](https://github.com/ota-meshi/eslint-plugin-regexp) - ESLint plugin for finding regexp mistakes and style guide violations.
*   [sort-keys-fix (⭐72)](https://github.com/leo-buneev/eslint-plugin-sort-keys-fix) - Adds fixer for ESLint `sort-keys` rule.
*   [this (⭐15)](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`.
*   [toplevel (⭐14)](https://github.com/HKalbasi/eslint-plugin-toplevel) - An eslint plugin for disallow side effect at module toplevel.

### Performance

*   [clean-regex (⭐274)](https://github.com/RunDevelopment/eslint-plugin-clean-regex) - JavaScript regex linter that aims to help write better regular expressions by pointing out errors and suggesting improvements.
*   [DOM (⭐9)](https://github.com/amilajack/eslint-plugin-dom)
*   [Optimize Regex (⭐62)](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals.
*   Perf-Standard [plugin (⭐20)](https://github.com/Raynos/eslint-plugin-perf-standard) and [Config (⭐3)](https://github.com/Raynos/eslint-config-perf-standard)

### Security

*   [no-secrets (⭐94)](https://github.com/nickdeis/eslint-plugin-no-secrets) - An eslint plugin that detects potential secrets/credentials.
*   [no-unsanitized (⭐168)](https://github.com/mozilla/eslint-plugin-no-unsanitized) - Checks for `innerHTML`, `outerHTML`, etc.
*   [pii (⭐3)](https://github.com/shiva-hack/eslint-plugin-pii) - Checks and enforces PII Compliance of the code. i.e. no email address, birth date, IP address or phone number in comments or string literals.
*   ScanJS [config (⭐90)](https://github.com/mozfreddyb/eslint-config-scanjs) and [plugin (⭐27)](https://github.com/mozfreddyb/eslint-plugin-scanjs-rules) - Security-related rules.
*   [Security (⭐1.8k)](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security.
*   [xss (⭐48)](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production.

### Style

*   [const case](https://www.npmjs.com/package/eslint-plugin-const-case) - Enforce capitalization of constant primitive literals.
*   [editorconfig (⭐8)](https://github.com/platinumazure/eslint-plugin-editorconfig) - Derive rules from [`.editorconfig`](https://editorconfig.org/).
*   [filenames (⭐266)](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your JavaScript files.
*   [Simple import sort (⭐1.2k)](https://github.com/lydell/eslint-plugin-simple-import-sort) - Easy autofixable import sorting.
*   [Switch case (⭐12)](https://github.com/lukeapage/eslint-plugin-switch-case) - Switch-case-specific linting rules for ESLint.
*   [padding (⭐4)](https://github.com/mu-io/eslint-plugin-padding) - Allows/disallows padding between statements.

### Testing Tools

*   [AVA (⭐227)](https://github.com/avajs/eslint-plugin-ava) - Linting rules for AVA.
*   Chai
    *   [expect practices (⭐27)](https://github.com/turbo87/eslint-plugin-chai-expect)
    *   [with unused expressions (⭐49)](https://github.com/ihordiachenko/eslint-plugin-chai-friendly)
    *   [permitted keywords (⭐1)](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords)
    *   [with chai-as-promised plugin (⭐2)](https://github.com/fintechstudios/eslint-plugin-chai-as-promised)
    <!-- lint disable double-link -->
    *   [globals (⭐2)](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
*   [Cucumber (⭐6)](https://github.com/darrinholst/eslint-plugin-cucumber) - Linting rules for Cucumber.
*   [Cypress (⭐583)](https://github.com/cypress-io/eslint-plugin-cypress) - Linting rules for Cypress.
*   [Jasmine (⭐94)](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine.
*   Jest
    *   [Enforcing practices (⭐971)](https://github.com/jest-community/eslint-plugin-jest) - Linting rules for Jest.
    *   [Enforcing consistent formatting (⭐123)](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) - Formatting rules for Jest.
    *   [Jest-async](https://www.npmjs.com/package/eslint-plugin-jest-async) - Async linting rule for Jest.
    *   [Jest-DOM (⭐293)](https://github.com/testing-library/eslint-plugin-jest-dom) - Linting rules for Jest-DOM.
*   Mocha
    *   [Enforcing practices (⭐268)](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha.
    *   [Enforcing manageability (⭐11)](https://github.com/onechiporenko/eslint-plugin-mocha-cleanup/)
*   [QUnit (⭐26)](https://github.com/platinumazure/eslint-plugin-qunit) - Linting rules for QUnit.
*   [TestCafe-Community (⭐2)](https://github.com/testcafe-community/eslint-plugin-testcafe-community) - TestCafe linting rules with env globals (fork from [TestCafe globals (⭐15)](https://github.com/miherlosev/eslint-plugin-testcafe)).
*   [Testing Library (⭐774)](https://github.com/testing-library/eslint-plugin-testing-library) - Linting rules for Testing Library.

## Parsers

*   [Babel (⭐3k)](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features.
*   [TypeScript (⭐12k)](https://github.com/typescript-eslint/typescript-eslint) - A TypeScript parser that produces output compatible with ESLint.
*   [BrightScript (⭐44)](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules.
*   [GraphQL (⭐577)](https://github.com/dotansimha/graphql-eslint) - Parser for the GraphQL AST. Includes parser, plugin, processor (for non-graphql files) and rules.

## Formatters

<!-- ignore is to keep "github" lower-case -->

<!--lint ignore awesome-spell-check-->

*   [badger (⭐4)](https://github.com/brettz9/eslint-formatter-badger) - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
*   [git-log (⭐36)](https://github.com/JamieMason/eslint-formatter-git-log) - ESLint Formatter featuring Git Author, Date, and Hash.
*   [github (⭐76)](https://github.com/hipstersmoothie/eslint-formatter-github) - See ESLint errors and warnings directly in pull requests.
*   [gitlab](https://gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
*   [mo (⭐31)](https://github.com/fengzilong/eslint-formatter-mo) - Good-lookin' ESLint formatter and also for delightful reading experience.
*   [SARIF](https://www.npmjs.com/package/@microsoft/eslint-formatter-sarif) - Generate a results in a SARIF format so it can be imported into tools like GitHub Advanced Security.
*   [summary-chart (⭐7)](https://github.com/davidjbradshaw/eslint-formatter-summary-chart) - Format ESLint output into a bar chart.

## Globals

*   [Restricted Globals (⭐16)](https://github.com/sidoshi/eslint-restricted-globals) - Expect `window` qualifier on globals that may otherwise be confusable as local variables.
*   [ES and browser globals (⭐260)](https://github.com/sindresorhus/globals) (originally from ESLint)
*   [chai globals (⭐2)](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
*   [TestCafe globals (⭐15)](https://github.com/miherlosev/eslint-plugin-testcafe) - `fixture` & `test` globals for TestCafe.

## Tools

*   [eslint-define-config (⭐128)](https://github.com/Shinigami92/eslint-define-config) - Provide a `defineConfig` function for `.eslintrc.js` files.
*   [es-file-traverse (⭐2)](https://github.com/brettz9/es-file-traverse) - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
*   [eslint-find-rules (⭐186)](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config.
*   [eslint-index (⭐18)](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files.
*   [eslint-interactive (⭐113)](https://github.com/mizdra/eslint-interactive) - The CLI tool to fix huge number of ESLint errors.
*   [eslint-multiplexer (⭐7)](https://github.com/pimlie/eslint-multiplexer) - Multiplex eslint results and merge results for common files.
*   [eslint-nibble (⭐554)](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time.
*   [eslint-rule-documentation (⭐30)](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule.
*   [eslint-watch (⭐184)](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode.
*   [codacy-eslint (⭐12)](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint.
*   [esprint (⭐639)](https://github.com/pinterest/esprint) - Run ESLint across multiple threads.
*   [generator-eslint (⭐165)](https://github.com/eslint/generator-eslint) - Generate ESLint
    plugin and rules with [Yeoman](http://yeoman.io/).
*   [editor-info (⭐4)](https://github.com/fisker/editor-info) - Detect whether one is within an editor/IDE and which type, allowing one to tweak ESLint configuration accordingly.
*   [eslint-dashboard (⭐11)](https://github.com/fengzilong/eslint-dashboard) - Interactive ESLint workflow that lives in your terminal.
*   [eslint-remote-tester (⭐101)](https://github.com/AriPerkkio/eslint-remote-tester) - CLI tool for testing given ESlint rules against multiple repositories at once.

## Developing for ESLint

*   [eslint-doc-generator (⭐59)](https://github.com/bmish/eslint-doc-generator) - Generate documentation for your ESLint plugin including a rules table for your readme and header for your rule docs.
*   [eslint-docs (⭐3)](https://github.com/j-f1/eslint-docs) - Keep your rule descriptions up-to-date across the repository.

## Tutorials

*   [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
*   [Lint Like It's 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
*   [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics.
*   [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint.
*   [Plugin Module with Mixins](https://chrysanthium.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration.
*   [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.

## Installation and Setup

*   [Lintier (⭐9)](https://github.com/josh-stillman/lintier) - CLI to quickly scaffold an ESLint & Prettier setup in a TypeScript project.

