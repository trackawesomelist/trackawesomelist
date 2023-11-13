# Awesome Playwright Overview

A curated list of awesome tools, utils and projects using Playwright

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mxschmitt/awesome-playwright/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 mxschmitt/awesome-playwright](https://github.com/mxschmitt/awesome-playwright) · ⭐ 533 · 🏷️ Testing

[ [Daily](/content/mxschmitt/awesome-playwright/README.md) / [Weekly](/content/mxschmitt/awesome-playwright/week/README.md) / Overview ]

---

# Awesome Playwright [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools, utils and projects using Playwright

[Playwright (⭐56k)](https://github.com/microsoft/playwright) is a Node.js library to automate Firefox, WebKit and Chromium based browsers via a single API.

## Contents

*   [Integrations](#integrations)
*   [Language Support](#language-support)
*   [Utils](#utils)
*   [Reporters](#reporters)
*   [Showcases](#showcases)
*   [Guides](#guides)
*   [Contribute](#contribute)

## Integrations

*   [jest-playwright (⭐513)](https://github.com/playwright-community/jest-playwright/) - Jest adapter for running Playwright.
*   [CodeceptJS (⭐4k)](https://github.com/Codeception/CodeceptJS) - Supercharged End 2 End Testing Framework for Node.js.
*   [chrome-aws-lambda (⭐3.1k)](https://github.com/alixaxel/chrome-aws-lambda#usage-with-playwright) - Support for running Microsoft's Playwright on AWS Lambda and Google Cloud Functions.
*   [playwright-chrome-recorder (⭐10)](https://github.com/AndrewUsher/playwright-chrome-recorder) - Export Playwright tests from Google Chrome DevTools' recordings programmatically.
*   [Playwright Chrome Recorder Extension (⭐6)](https://github.com/AndrewUsher/playwright-recorder-extension) - Export DevTools Recordings as Playwright Tests directly from the DevTools Recorder Panel.
*   [playwright-github-action (⭐291)](https://github.com/microsoft/playwright-github-action) - GitHub Action to install all the required dependencies.
*   [playwright-pytest (⭐366)](https://github.com/microsoft/playwright-pytest/) - Official Pytest plugin for using Playwright pages with fixtures.
*   [heroku-playwright-buildpack (⭐42)](https://github.com/mxschmitt/heroku-playwright-buildpack) - Heroku buildpack for running Playwright on a Heroku Dyno.
*   [axe-playwright (⭐150)](https://github.com/abhinaba-ghosh/axe-playwright) - Custom commands for Playwright to run accessibility (a11y) checks with axe-core.
*   [expect-axe-playwright (⭐18)](https://github.com/Widen/expect-axe-playwright) - Expect matchers to perform Axe accessibility tests in your Playwright tests.
*   [cucumber-playwright (⭐296)](https://github.com/Tallyb/cucumber-playwright) - A starter repo for writing E2E tests based on Cucumber with Playwright using Typescript.
*   [artillery-engine-playwright (⭐126)](https://github.com/artilleryio/artillery-engine-playwright) - Load testing with Playwright.
*   [playwright-bdd (⭐97)](https://github.com/vitalets/playwright-bdd) - BDD testing with Playwright runner and CucumberJS.

## Language Support

*   [playwright](https://git.io/JT2bj) - Official Playwright in Node.js (JavaScript and TypeScript).
*   [playwright-python (⭐9.6k)](https://github.com/microsoft/playwright-python) - Official Playwright port to Python.
*   [playwright-dotnet (⭐2.1k)](https://github.com/microsoft/playwright-dotnet) - Official Playwright port to .NET.
*   [playwright-java (⭐878)](https://github.com/microsoft/playwright-java) - Official Playwright port to Java.
*   [playwright-go (⭐1.5k)](https://github.com/playwright-community/playwright-go) - Playwright port for Golang.
*   [playwright-ruby-client (⭐218)](https://github.com/YusukeIwaki/playwright-ruby-client) - Playwright port for Ruby.
*   [playwright-cr (⭐17)](https://github.com/naqvis/playwright-cr) - Playwright port for Crystal.
*   [playwright-rust (⭐238)](https://github.com/octaltree/playwright-rust) - Playwright port for Rust.
*   [playwright-perl (⭐20)](https://github.com/teodesian/playwright-perl) - Playwright port for Perl.

## Utils

*   [Ask Playwright](https://ray.run/ask) - Accurate answers to Playwright questions provided by LLM trained on the latest Playwright documentation.
*   [Try Playwright](https://try.playwright.tech) - Interactive playground for running Playwright tests.
*   [query-selector-shadow-dom (⭐216)](https://github.com/Georgegriff/query-selector-shadow-dom) - Extend the selectors engine by selecting Shadow DOM roots.
*   [playwright-fluent (⭐145)](https://github.com/hdorgeval/playwright-fluent) - Fluent API Wrapper around Playwright.
*   [headless-testing](https://headlesstesting.com) - Connect your Playwright tests with browsers in the Cloud.
*   [expect-playwright (⭐142)](https://github.com/playwright-community/expect-playwright) - Expect utility matcher functions to simplify expect statements for the usage with Playwright Test or Jest Playwright.
*   [eslint-plugin-playwright (⭐163)](https://github.com/playwright-community/eslint-plugin-playwright) - ESLint plugin for your Playwright testing needs.
*   [Moon (⭐189)](https://github.com/aerokube/moon) - Tools for executing Playwright tests in parallel in a Kubernetes cluster.
*   [playwright-test-coverage (⭐51)](https://github.com/anishkny/playwright-test-coverage) - Plugin to collect code coverage from running Playwright tests.
*   [Playwright Test for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright) - Official Playwright test extension for VS Code.
*   [Maestro for IntelliJ](https://plugins.jetbrains.com/plugin/18100-maestro) - Playwright plugin for IntelliJ.
*   [playwright-elements](https://www.npmjs.com/package/playwright-elements) - Playwright test extension for more powerful page object implementation.
*   [Playwright-cleanup](https://www.npmjs.com/package/playwright-cleanup) - A Playwright cleanup tool that simplifies test cleanup by undoing any changes to the testing environment.
*   [Playwright-performance](https://www.npmjs.com/package/playwright-performance) - A plugin that helps you optimize the speed and efficiency of web applications by measuring and analyzing the performance of ANY tested flow using Playwright.
*   [playwright-python-language-injection (⭐0)](https://github.com/Mattwmaster58/playwright-python-language-injection) - Language injection definitions for CSS/JS syntax highlighting when using `python-playwright` in PyCharm.
*   [playwright-ui5 (⭐3)](https://github.com/detachhead/playwright-ui5) - Custom selector engine for sapui5.
*   [playwright-xpath (⭐3)](https://github.com/detachhead/playwright-xpath) - Custom selector engine for xpath 2 and 3.
*   [ZeroStep (⭐12)](https://github.com/zerostep-ai/zerostep) - AI actions and assertions for Playwright.

## Reporters

*   [playwright-tesults-reporter (⭐0)](https://github.com/tesults/playwright-tesults-reporter) - A library for uploading test results to Tesults from Playwright.
*   [monocart-reporter (⭐95)](https://github.com/cenfun/monocart-reporter) - A playwright test reporter, shows suites/cases/steps in html grid.
*   [allure-playwright (⭐181)](https://github.com/allure-framework/allure-js/tree/master/packages/allure-playwright) - Allure integration with Playwright Test framework.
*   [playwright-xray (⭐11)](https://github.com/inluxc/playwright-xray) - Playwright Xray Reporter, send test executions to Jira / Xray.
*   [currents-dev](https://currents.dev/) - A Cloud Dashboard to debug, troubleshoot and analyze parallel Playwright CI tests.

## Showcases

*   [Demo.Playwright (⭐193)](https://github.com/MarcusFelling/Demo.Playwright) - Various testing scenarios with Playwright, using the official test-runner and scripts authored in TypeScript.
*   [playwright-jest-examples (⭐95)](https://github.com/playwright-community/playwright-jest-examples) - Examples of the Jest Playwright tools in combination to test popular sites.
*   [VS Code (⭐153k)](https://github.com/microsoft/vscode) - Playwright is used to run cross-browser tests on their web builds.
*   [TypeScript (⭐95k)](https://github.com/microsoft/TypeScript) - Playwright is used test typescript.js across browsers.
*   [Elastic APM JS agent (⭐263)](https://github.com/elastic/apm-agent-rum-js) - Playwright is used to run benchmark tests across browsers.
*   [Blockstack (⭐259)](https://github.com/blockstack/ux) - Playwright is used to run cross-browser UI tests.
*   [xterm.js (⭐16k)](https://github.com/xtermjs/xterm.js) - Playwright is used to run cross-browser integration tests.
*   [Heroku Playwright Example (⭐19)](https://github.com/mxschmitt/heroku-playwright-example) - Example using Playwright on Heroku.
*   [Todo App with Playwright (⭐11)](https://github.com/burakkantarci/playwright-todo-app) - Comprehensive Todo app with APIs, E2E tests with GitHub Actions enabled.

## Guides

*   [theheadless.dev](https://theheadless.dev) - Practical guides and runnable examples on Playwright (and Puppeteer).
*   [playwright.tech](https://playwright.tech) - A central home for tutorials, tooling, and showcases of the Playwright ecosystem.
*   [playwrightsolutions.com](https://playwrightsolutions.com) - Curated Selection of Playwright Automated Test Problems and Solutions.

## Contribute

Contributions welcome! Read the [contribution guidelines (⭐530)](https://github.com/mxschmitt/awesome-playwright/blob/master/CONTRIBUTING.md) first.

