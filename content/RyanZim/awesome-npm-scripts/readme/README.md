# Awesome Npm Scripts Overview

Everything awesome related to npm scripts and using npm as a build tool.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/RyanZim/awesome-npm-scripts/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 RyanZim/awesome-npm-scripts](https://github.com/RyanZim/awesome-npm-scripts) · ⭐ 678 · 🏷️ Programming Languages

[ [Daily](/content/RyanZim/awesome-npm-scripts/README.md) / [Weekly](/content/RyanZim/awesome-npm-scripts/week/README.md) / Overview ]

---

<!--lint ignore awesome-heading-->

# Awesome npm Scripts [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/RyanZim/awesome-npm-scripts/raw/master/npm-logo.png" align="right" width="150">](https://www.npmjs.com)

> Everything awesome for using npm as a build tool.

You might also like [awesome-npm (⭐4.1k)](https://github.com/sindresorhus/awesome-npm).

**Notice: I'm currently too busy to actively expand this list; therefore, I've decided to make this an [OPEN Open Source Project](http://openopensource.github.io/). Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit.**

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

*   [Articles](#articles)
*   [Videos/Talks](#videostalks)
*   [Task Runners](#task-runners)
*   [File Watchers](#file-watchers)
*   [Dev Servers](#dev-servers)
*   [Cross-platform Utilities](#cross-platform-utilities)
    *   [Utility Packs](#utility-packs)
*   [Other Utilities](#other-utilities)
*   [Miscellaneous](#miscellaneous)
*   [Cross-platform Shell Reference](#cross-platform-shell-reference)
*   [`npm run` Reference](#npm-run-reference)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Articles

*   [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/) - Blog post by Keith Cirkel.
*   [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) - Sequel to »Why we should stop using Grunt & Gulp«.
*   [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8) -  Article by Cory House.
*   [Helpers and tips for npm run scripts](http://michael-kuehnel.de/tooling/2018/03/22/helpers-and-tips-for-npm-run-scripts.html) - Blog post by Michael Kühnel covering advanced topics.
*   [Running cross-platform tasks via npm package scripts](https://exploringjs.com/nodejs-shell-scripting/ch_package-scripts.html) - The most comprehensive guide to using npm Scripts by Dr. Axel Rauschmayer.

## Videos/Talks

*   [Advanced front-end automation with npm scripts](https://www.youtube.com/watch?v=0RYETb9YVrk) - Talk at Nordic.js 2015 by Kate Hudson.
*   [How to create a build system with npm scripts](http://www.penta-code.com/how-to-create-a-build-system-with-npm-scripts/) - Video tutorial series on setting up a front-end build system.

## Task Runners

Tools for running multiple commands or npm scripts in parallel or sequentially.

*   [script-runner (⭐25)](https://github.com/paulpflug/script-runner) - Simple task runner with a terse syntax.
*   [npm-run-all (⭐5k)](https://github.com/mysticatea/npm-run-all) - Fully featured task runner.
*   [redrun (⭐110)](https://github.com/coderaiser/redrun) - Expand scripts from package.json to improve execution speed.

## File Watchers

Tools to watch your source files and run a build command whenever any of the files change.

*   [onchange (⭐775)](https://github.com/Qard/onchange) - `onchange <glob> -- <command>`.
*   [watch (⭐1.2k)](https://github.com/mikeal/watch) - `watch <command> <directory>`.

## Dev Servers

*   [http-server (⭐12k)](https://github.com/indexzero/http-server) - Simple zero-configuration command-line http server.
*   [live-server (⭐4k)](https://github.com/tapio/live-server) - Simple development http server with live reload capability.

## Cross-platform Utilities

Utilities to perform common command-line tasks without worrying about cross-platform compatibility.

*   [rimraf (⭐4.9k)](https://github.com/isaacs/rimraf) - Delete files or directories; like `rm -rf`.
*   [del-cli (⭐265)](https://github.com/sindresorhus/del-cli) - Safer file and folder deletion.
*   [mkdirp](https://github.com/substack/node-mkdirp) - Create a directory, creating parent directories if needed; like `mkdir -p`.
*   [cpr (⭐76)](https://github.com/davglass/cpr) - `cp -r` for Node.js.
*   [cpy-cli (⭐279)](https://github.com/sindresorhus/cpy-cli) - File/directory copying/renaming.
*   [copyfiles (⭐345)](https://github.com/calvinmetcalf/copyfiles) - Copy a list of files into a directory.
*   [sync-files (⭐42)](https://github.com/byteclubfr/node-sync-files) - `rsync`-like directory syncing with watch mode.
*   [echo-cli (⭐6)](https://github.com/iamakulov/echo-cli) - Cross-platform `echo` with JS escape sequence support.
*   [clear-cli (⭐46)](https://github.com/sindresorhus/clear-cli) - Clear the terminal.
*   [cross-env (⭐5.9k)](https://github.com/kentcdodds/cross-env) - Set environment variables for scripts, unix-style.
*   [cross-os (⭐34)](https://github.com/milewski/cross-os) - Run platform-specific npm scripts.
*   [ntee (⭐23)](https://github.com/stefanmaric/ntee) - Utility that reads from standard input and writes to standard output and files; like Unix `tee`.
*   [catw](https://github.com/substack/catw) - Print a file to stdout, with optional watch mode; sorta like Unix `cat`.

### Utility Packs

*   [shx (⭐1.4k)](https://github.com/shelljs/shx) - Collection of common Unix utilities implemented in Node.js; example usage: `shx rm somefile`.

## Other Utilities

*   [hashmark (⭐194)](https://github.com/keithamus/hashmark) -  Take contents of a file and output as new file with a hash in the name.
*   [gzip-size-cli (⭐180)](https://github.com/sindresorhus/gzip-size-cli) - Get the gzipped size of a file or stdin.
*   [opn-cli (⭐370)](https://github.com/sindresorhus/opn-cli) - Open websites, files, executables, etc. with the user's preferred application.
*   [headr (⭐3)](https://github.com/heldr/headr) - Add header / banner info to a file.
*   [Bower files CLI (⭐3)](https://github.com/thompsonemerson/bower-files-cli) - Get main bower files on the command line.
*   [cli-error-notifier (⭐64)](https://github.com/micromata/cli-error-notifier) - Send native desktop notifications when npm scripts fail.

## Miscellaneous

*   [screwy (⭐106)](https://github.com/samueleaton/screwy) - The npm scripts GUI.
*   [Forrest (⭐338)](https://github.com/stefanjudis/forrest) - npm scripts desktop client.
*   [run-npm (⭐180)](https://github.com/timoxley/npm-run) - Run locally-installed node module executables. Useful for debugging npm scripts.
*   [npm-quick-run (⭐131)](https://github.com/bahmutov/npm-quick-run) - Quickly run npm scripts by prefix without typing the full name.
*   [edit-script (⭐9)](https://github.com/RyanZim/edit-script) - Edit npm scripts from the command line without worrying about JSON escaping.
*   [ntl (⭐872)](https://github.com/ruyadorno/ntl) - Interactive cli menu to list and run npm scripts.

## Cross-platform Shell Reference

A quick reference of the shell operators & commands that work the same on Unix and Windows.

*   Use `&&` to run commands in sequence. If a command fails, the script exits.
*   Use `|` to pipe the stdout of one command into the stdin of the next. (`do-something | something else`)
*   Use `>` to write the stdout of a command to a file. (`do-something > file`)
*   Use `<` to send the contents of a file to a command's stdin. (`command < file`)
*   Use `cd <dir>` to change the current working directory to `<dir>`. Note that `cd` alone prints the current working directory on windows, but changes the working directory to `~` on \*nix.

## `npm run` Reference

You can use `npm run-script` or `npm run`; they both do the same thing, but `npm run` is shorter.

*   Run just `npm run` to print a list of scripts.
*   Running `npm run script` (where `script` is the name of your script) will run `prescript`, `script`, and `postscript`; in that order.
    *   You can't nest `pre` and `post` hooks (i.e. `preprescript` won't work).
*   You can pass arguments to your scripts by passing `--` to `npm run`, followed by the arguments. Example: Given the script `"mocha": "mocha"`, you can run `npm run mocha -- --reporter xunit`. This effectively runs `mocha --reporter xunit`.
*   Running `npm test` is the same as running `npm run test`. The same applies to `npm start` and `npm stop`.
*   You can run `npm run <script> -s` to silence the default npm output (useful for calling a script within another script).

## Contributing

See [CONTRIBUTING.md (⭐677)](https://github.com/RyanZim/awesome-npm-scripts/blob/master/CONTRIBUTING.md).

