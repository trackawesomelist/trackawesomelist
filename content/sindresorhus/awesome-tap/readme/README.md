# Awesome Tap Overview

Useful resources for the Test Anything Protocol

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/sindresorhus/awesome-tap/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 sindresorhus/awesome-tap](https://github.com/sindresorhus/awesome-tap) · ⭐ 583 · 🏷️ Testing

[ [Daily](/content/sindresorhus/awesome-tap/README.md) / [Weekly](/content/sindresorhus/awesome-tap/week/README.md) / Overview ]

---

# Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)

> Useful resources for the [Test Anything Protocol](https://testanything.org)

TAP is a simple text-based interface between testing modules in a test harness.

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*

## Contents

*   [Reporters](#reporters)
*   [Producers](#producers)
*   [Consumers](#consumers)
*   [Tools](#tools)
*   [Articles](#articles)
*   [Tutorials](#tutorials)
*   [Documentation](#documentation)
*   [Community](#community)

## Reporters

### JavaScript

*   [tap-dot (⭐35)](https://github.com/scottcorgan/tap-dot) - Dotted output.
*   [tap-spec (⭐278)](https://github.com/scottcorgan/tap-spec) - Mocha-like spec reporter.
*   [tap-nyan (⭐144)](https://github.com/calvinmetcalf/tap-nyan) - Nyan cat.
*   [tap-min (⭐6)](https://github.com/derhuerst/tap-min) - Minimal output.
*   [tap-difflet (⭐48)](https://github.com/namuol/tap-difflet) - Minimal output with diffing.
*   [tap-diff (⭐92)](https://github.com/axross/tap-diff) - Human-friendly output with diffing.
*   [tap-simple (⭐6)](https://github.com/joeybaker/tap-simple) - Simple output.
*   [faucet (⭐540)](https://github.com/substack/faucet) - Human-readable summarizer.
*   [tap-mocha-reporter (⭐23)](https://github.com/isaacs/tap-mocha-reporter) - Use any of the [Mocha reporters (⭐23)](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters).
*   [tap-summary (⭐42)](https://github.com/zoubin/tap-summary) - Summarized output.
*   [tap-pessimist (⭐15)](https://github.com/clux/tap-pessimist) - Only shows failed tests.
*   [tap-prettify (⭐34)](https://github.com/toolness/tap-prettify) - Nice readable output with diffing.
*   [tap-colorize](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability.
*   [tap-bail (⭐19)](https://github.com/juliangruber/tap-bail) - Bail out when the first test fails.
*   [tap-notify (⭐59)](https://github.com/axross/tap-notify) - Notifier for macOS, Linux and Windows.
*   [tap-json (⭐24)](https://github.com/gummesson/tap-json) - JSON output.
*   [ava-tap-json (⭐1)](https://github.com/yovasx2/ava-tap-json) - JSON output with AVA compatibility.
*   [tap-xunit (⭐42)](https://github.com/aghassemi/tap-xunit) - xUnit output.
*   [tap-teamcity (⭐8)](https://github.com/smockle/tap-teamcity) - Output for TeamCity.

## Producers

Things that produce TAP output.

### JavaScript

*   [AVA (⭐20k)](https://github.com/sindresorhus/ava) - Futuristic test runner (`$ ava --tap`).
*   [tap (⭐2.1k)](https://github.com/isaacs/node-tap) - TAP test framework for Node.js.
*   [tape (⭐5.7k)](https://github.com/substack/tape) - TAP-producing test harness for Node.js and browsers.
*   [ESLint](https://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter (`$ eslint --format=tap`).
*   [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers (`$ mocha reporter=tap`).
*   [qunit-tap (⭐73)](https://github.com/twada/qunit-tap) - TAP output for QUnit.
*   [jasmine-reporters (⭐397)](https://github.com/larrymyers/jasmine-reporters) - TAP output for Jasmine.
*   [karma-tap-reporter (⭐7)](https://github.com/fumiakiy/karma-tap-reporter) - TAP output for Karma.
*   [mos (⭐109)](https://github.com/zkochan/mos) - Markdown file generator and tester (`$ mos test --tap`).
*   [zora (⭐474)](https://github.com/lorenzofox3/zora) - TAP-producing test runner that works with ES2015 without Babel.

### Swift

*   [TAP (⭐21)](https://github.com/swiftdocorg/tap) - A Swift package for the Test Anything Protocol (v13).

### Fish

*   [Fishtape (⭐310)](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish.

### Bash

*   [bats (⭐7.1k)](https://github.com/sstephenson/bats) - Bash Automated Testing System.
*   [ShellSpec (⭐772)](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for POSIX shells.

[More…](https://testanything.org/producers.html)

## Consumers

Things that consume TAP output.

### JavaScript

*   [tap-parser (⭐115)](https://github.com/substack/tap-parser) - TAP parser.
*   [tap-out (⭐23)](https://github.com/scottcorgan/tap-out) - TAP parser.
*   [yamlish (⭐22)](https://github.com/isaacs/yamlish) - YAML-block parser.

[More…](https://testanything.org/consumers.html)

## Tools

### JavaScript

*   [tap-dev-tool (⭐29)](https://github.com/Jam3/tap-dev-tool) - Prettify TAP in the browser console.
*   [tap-merge (⭐13)](https://github.com/anko/tap-merge) - Merge multiple TAP streams.
*   [smokestack (⭐244)](https://github.com/hughsk/smokestack) - Run TAP tests in a browser and write the output to `stdout`.
*   [chutney (⭐5)](https://github.com/derhuerst/chutney) - Run TAP tests at Sauce Labs. Lightweight [smokestack (⭐244)](https://github.com/hughsk/smokestack) alternative.

### Python

*   [tappy (⭐119)](https://github.com/mblayman/tappy) - Tools for working with TAP.

## Articles

*   [Understand the Test Anything Protocol](https://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)

## Tutorials

*   [test-anything (⭐167)](https://github.com/finnp/test-anything) - Learn to test anything with TAP through an interactive workshop.

## Documentation

*   [Specification](https://testanything.org/tap-version-13-specification.html)
*   [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)

## Community

*   [Discuss (⭐67)](https://github.com/TestAnything/Specification/issues)
*   [Reddit](https://www.reddit.com/r/testanythingprotocol)
*   [Stack Overflow](https://stackoverflow.com/questions/tagged/tap)

