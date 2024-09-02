# Awesome Actions Overview

A curated list of awesome actions to use on GitHub

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/sdras/awesome-actions/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 sdras/awesome-actions](https://github.com/sdras/awesome-actions) · ⭐ 25K · 🏷️ Development Environment

[ [Daily](/content/sdras/awesome-actions/README.md) / [Weekly](/content/sdras/awesome-actions/week/README.md) / Overview ]

---

<p align="center">
  <br>
    <img src="https://github.com/sdras/awesome-actions/raw/main/awesome-actions.png" width="150"/>
  <br>
</p>

# Awesome Actions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<!--lint ignore no-dead-urls-->![GitHub Actions status | sdras/awesome-actions](https://github.com/sdras/awesome-actions/workflows/Lint%20Awesome%20List/badge.svg)](https://github.com/sdras/awesome-actions/actions?workflow=Lint+Awesome+List)

> A curated list of awesome things related to GitHub Actions.

Actions are triggered by GitHub platform events directly in a repo and run on-demand workflows either on Linux, Windows or macOS virtual machines or inside a container in response. With GitHub Actions you can automate your workflow from idea to production.

## Contents

*   [Official Resources](#official-resources)
    *   [Workflow Examples](#workflow-examples)
    *   [Official Actions](#official-actions)
    *   [Create your Actions](#create-your-actions)
*   [Community Resources](#community-resources)
    *   [GitHub Tools and Management](#github-tools-and-management)
    *   [Collection of Actions](#collection-of-actions)
    *   [Utility](#utility)
    *   [Static Analysis](#static-analysis)
    *   [Dynamic Analysis](#dynamic-analysis)
    *   [Monitoring](#monitoring)
    *   [Pull Requests](#pull-requests)
    *   [GitHub Pages](#github-pages)
    *   [Notifications and Messages](#notifications-and-messages)
    *   [Deployment](#deployment)
    *   [External Services](#external-services)
    *   [Frontend Tools](#frontend-tools)
    *   [Machine Learning Ops](#machine-learning-ops)
    *   [Build](#build)
    *   [Database](#database)
    *   [Networking](#networking)
    *   [Localization](#localization)
    *   [Fun](#fun)
    *   [Cheat Sheet](#cheat-sheet)
*   [Tutorials](#tutorials)

## Official Resources

*   [Official Site](https://github.com/features/actions)
*   [Official Documentation](https://help.github.com/en/actions)
*   [Official Actions organization](https://github.com/actions)
    *   [actions/virtual-environments (⭐9.8k)](https://github.com/actions/virtual-environments) - GitHub Actions virtual environments.
    *   [actions/runner (⭐4.7k)](https://github.com/actions/runner) - The Runner for GitHub Actions.
*   [GitHub Blog Announcement](https://github.blog/2018-10-17-action-demos/)

### Workflow Examples

*   [actions/starter-workflows (⭐8.8k)](https://github.com/actions/starter-workflows) - Starter workflow management.
*   [actions/example-services (⭐247)](https://github.com/actions/example-services) - Example workflows using service containers.

### Official Actions

<!--lint disable no-dead-urls-->

#### Workflow Tool Actions

Tool actions for your workflow.

<!--lint ignore awesome-spell-check-->

*   [actions/checkout (⭐5.7k)](https://github.com/actions/checkout) - Setup your repository on your workflow.
*   [actions/upload-artifact (⭐3.1k)](https://github.com/actions/upload-artifact) - Upload artifacts from your workflow.
*   [actions/download-artifact (⭐1.4k)](https://github.com/actions/download-artifact) - Download artifacts from your build.
*   [actions/cache (⭐4.4k)](https://github.com/actions/cache) - Cache dependencies and build outputs in GitHub Actions.
*   [actions/github-script (⭐4.1k)](https://github.com/actions/github-script) - Write a script for GitHub API and the workflow contexts.

#### Actions for GitHub Automation

Automate management for issues, pull requests, and releases.

*   [actions/create-release (⭐1.3k)](https://github.com/actions/create-release) - An Action to create releases via the GitHub Release API.
*   [actions/upload-release-asset (⭐684)](https://github.com/actions/upload-release-asset) - An Action to upload a release asset via the GitHub Release API.
*   [actions/first-interaction (⭐756)](https://github.com/actions/first-interaction) - An action for filtering pull requests and issues from first-time contributors.
*   [actions/stale (⭐1.3k)](https://github.com/actions/stale) - Marks issues and pull requests that have not had recent interaction.
*   [actions/labeler (⭐1.9k)](https://github.com/actions/labeler) - An action for automatically labelling pull requests.
*   [actions/delete-package-versions (⭐340)](https://github.com/actions/delete-package-versions) - Delete versions of a package from GitHub Packages.

#### Setup Actions

Set up your GitHub Actions workflow with a specific version of your programming languages.

*   [actions/setup-node: Node.js (⭐3.8k)](https://github.com/actions/setup-node)
*   [actions/setup-python: Python (⭐1.6k)](https://github.com/actions/setup-python)
*   [actions/setup-go: Go (⭐1.4k)](https://github.com/actions/setup-go)
*   [actions/setup-dotnet: .NET core sdk (⭐935)](https://github.com/actions/setup-dotnet)
*   [actions/setup-haskell: Haskell (GHC and Cabal) (⭐70)](https://github.com/actions/setup-haskell)
*   [actions/setup-java: Java (⭐1.5k)](https://github.com/actions/setup-java)
*   [actions/setup-ruby: Ruby (⭐171)](https://github.com/actions/setup-ruby)
*   [actions/setup-elixir: Elixir (⭐154)](https://github.com/actions/setup-elixir)
*   [actions/setup-julia: Julia (⭐90)](https://github.com/julia-actions/setup-julia)

### Create your Actions

#### JavaScript and TypeScript Actions

*   [actions/toolkit (⭐4.9k)](https://github.com/actions/toolkit) - The GitHub ToolKit for developing GitHub Actions.
*   [actions/hello-world-javascript-action (⭐234)](https://github.com/actions/hello-world-javascript-action) - A template to demonstrate how to build a JavaScript action.
*   [actions/javascript-action (⭐948)](https://github.com/actions/javascript-action) - Create a JavaScript Action.
*   [actions/typescript-action (⭐2k)](https://github.com/actions/typescript-action) - Create a TypeScript Action.
*   [actions/http-client (⭐71)](https://github.com/actions/http-client) - A lightweight HTTP client optimized for use with actions, TypeScript with generics and async await.

#### Docker Container Actions

*   [actions/hello-world-docker-action (⭐162)](https://github.com/actions/hello-world-docker-action) - A template to demonstrate how to build a Docker action.
*   [actions/container-toolkit-action (⭐116)](https://github.com/actions/container-toolkit-action) - Template repo for creating container actions using actions/toolkit.

## Community Resources

### GitHub Tools and Management

*   [Declaratively setup GitHub Labels (⭐188)](https://github.com/lannonbr/issue-label-manager-action)
*   [Action to sync GitHub labels in the declarative way (⭐196)](https://github.com/micnncim/action-label-syncer)
*   [Add releases to GitHub (⭐166)](https://github.com/elgohr/Github-Release-Action)
*   [Publish a docker image to Dockerhub (⭐778)](https://github.com/elgohr/Publish-Docker-Github-Action)
*   [Create an issue using content from a file (⭐137)](https://github.com/peter-evans/create-issue-from-file)
*   [Publish GitHub Releases with Assets (⭐4k)](https://github.com/softprops/action-gh-release)
*   [GitHub Project Automation+ (⭐322)](https://github.com/alex-page/github-project-automation-plus) - Automate GitHub Project cards with any webhook event.
*   [Run GitHub Actions Locally with a web interface (⭐248)](https://github.com/phishy/wflow)
*   [Run GitHub Actions Locally in Terminal (⭐54k)](https://github.com/nektos/act)
*   [Build and Publish Android debug APK (⭐66)](https://github.com/ShaunLWM/action-release-debugapk)
*   [Generate sequential build numbers for GitHub Actions (⭐138)](https://github.com/einaregilsson/build-number)
*   [Push Git changes to GitHub repository without authentication difficulties (⭐1.2k)](https://github.com/ad-m/github-push-action)
*   [Generate release notes based on your events (⭐115)](https://github.com/Decathlon/release-notes-generator-action)
*   [Create a GitHub wiki page based on the provided markdown file (⭐94)](https://github.com/Decathlon/wiki-page-creator-action)
*   [Label your Pull Requests auto-magically (using committed files) (⭐95)](https://github.com/Decathlon/pull-request-labeler-action)
*   [Add Label to your Pull Requests based on the author team name (⭐49)](https://github.com/JulienKode/team-labeler-action)
*   [Get a list of file changes with PR/Push (⭐166)](https://github.com/trilom/file-changes-action)
*   [Use private actions in any workflow (⭐168)](https://github.com/InVisionApp/private-action-loader)
*   [Label Your Issues Using the Issue's Contents (⭐34)](https://github.com/damccorm/tag-ur-it)
*   [Rollback a GitHub Release (⭐57)](https://github.com/author/action-rollback)
*   [Lock Closed Issues and Pull Requests after a Period of Inactivity (⭐309)](https://github.com/dessant/lock-threads)
*   [Get Commit Difference Count Between Two Branches (⭐7)](https://github.com/jessicalostinspace/commit-difference-action)
*   [Generate Release Notes Based on Git References (⭐137)](https://github.com/metcalfc/changelog-generator)
*   [Enforce Policies on GitHub Repositories and Commits (⭐424)](https://github.com/talos-systems/conform)
*   [Auto Label Issue Based on Issue Description (⭐49)](https://github.com/Renato66/auto-label)
*   [Update Configured GitHub Actions to the Latest Versions (⭐8)](https://github.com/fabasoad/ghacu)
*   [Create Issue Branch (⭐322)](https://github.com/robvanderleek/create-issue-branch)
*   [Remove Old Artifacts (⭐319)](https://github.com/c-hive/gha-remove-artifacts)
*   [Expose Git Commit Data As Environment Variables (⭐38)](https://github.com/rlespinasse/git-commit-data-action)
*   [Sync Defined Files/Binaries to Wiki or External Repositories (⭐8)](https://github.com/kai-tub/external-repo-sync-action)
*   [Create/Update/Delete a GitHub Wiki Page Based on Any File (⭐63)](https://github.com/Andrew-Chen-Wang/github-wiki-action)
*   [Prow GitHub Actions (⭐91)](https://github.com/jpmcb/prow-github-actions) - Automation of policy enforcement, chat-ops, and automatic PR merging.
*   [Check GitHub Status in your Workflow (⭐33)](https://github.com/crazy-max/ghaction-github-status)
*   [Manage Labels on GitHub (create/rename/update/delete) as Code (⭐138)](https://github.com/crazy-max/ghaction-github-labeler)
*   [Continuous Distribution of Funding to your Project Contributors and Dependencies (⭐122)](https://github.com/protontypes/libreselery)
*   [Herald Rules for GitHub: Add Subscribers, Assignees, Labels, and More to Your PR (⭐53)](https://github.com/gagoar/use-herald-action)
*   [GitHub Codeowners Validator (⭐217)](https://github.com/mszostok/codeowners-validator) - Ensures the correctness of your GitHub CODEOWNERS file. It supports public and private GitHub repositories and also GitHub Enterprise installations.
*   [Copybara Action (⭐97)](https://github.com/olivr/copybara-action) - Move and transform code between repositories (ideal to maintain several repos from one monorepo).

### Collection of Actions

*   [Use HashiCorp's Terraform (⭐1.3k)](https://github.com/hashicorp/setup-terraform)
*   [GitHub Actions for Yarn 1 (⭐297)](https://github.com/Borales/actions-yarn)
*   [GitHub Actions for Yarn 2 (⭐15)](https://github.com/sergioramos/yarn-actions)
*   [GitHub Actions for Golang (⭐133)](https://github.com/cedrickring/golang-action)
*   [GitHub Actions for R and accompanying #rstats package](http://maxheld.de/ghactions/)
*   [GitHub Actions for WordPress (⭐415)](https://github.com/10up/actions-wordpress/)
*   [GitHub Actions for Composer (⭐33)](https://github.com/MilesChou/composer-action)
*   [GitHub Actions for Flutter (⭐2.2k)](https://github.com/subosito/flutter-action)
*   [GitHub Actions for PHP (⭐2.9k)](https://github.com/shivammathur/setup-php)
*   [GitHub Actions for Rust](https://github.com/actions-rs)
*   [GitHub Actions for Android (⭐181)](https://github.com/Malinskiy/action-android)
*   [GitHub Actions for Logtalk and Prolog](https://github.com/logtalk-actions)
*   [GitHub Actions for Deno (⭐181)](https://github.com/denolib/setup-deno)
*   [GitHub Actions for Unity (⭐954)](https://github.com/webbertakken/unity-actions)
*   [Octions - GitHub Actions for GitHub REST API (⭐38)](https://github.com/maxkomarychev/octions)
*   [GitHub Actions for Docker (⭐163)](https://github.com/docker/github-actions)
*   [GitHub Actions for AWS (⭐116)](https://github.com/clowdhaus/aws-github-actions)
*   [Actions Hub](https://github.com/actionshub)

### Utility

*   [Setup `ssh-agent` (⭐1.2k)](https://github.com/webfactory/ssh-agent) - Run `ssh-agent` with additional SSH keys to access private repositories.
*   [GitHub Actions Badges for your README (⭐198)](https://github.com/atrox/github-actions-badge)
*   [GitHub Actions for Python project with poetry (⭐422)](https://github.com/abatilo/actions-poetry)
*   [GitHub Actions for Python project with pyenv (⭐39)](https://github.com/gabrielfalcao/pyenv-action)
*   [GitHub Actions to compile LaTeX documents (⭐1.1k)](https://github.com/xu-cheng/latex-action)
*   [Update Maxmind Databases (⭐5)](https://github.com/meetup/maxmind-updater)
*   [Debug with SSH over tmate (⭐2.9k)](https://github.com/mxschmitt/action-tmate) - Debug the Action directly by providing a SSH connection.
*   [Unlock git-crypt files (⭐46)](https://github.com/sliteteam/github-action-git-crypt-unlock)
*   [Golang CGO cross compiler (⭐64)](https://github.com/crazy-max/ghaction-xgo)
*   [Run your job on another architecture: arm32, aarch64 and others (⭐677)](https://github.com/uraimo/run-on-arch-action)
*   [Generate a table of contents (⭐220)](https://github.com/technote-space/toc-generator)
*   [Automatically add Label or Assignee to an Issue (⭐60)](https://github.com/Naturalclar/issue-action)
*   [Action to send LGTM reaction as image or GIF when we say lgtm (⭐80)](https://github.com/micnncim/action-lgtm-reaction)
*   [Generate build numbers across multiple scopes (⭐20)](https://github.com/zyborg/gh-action-buildnum)
*   [Publish GitHub release artifacts (⭐137)](https://github.com/skx/github-action-publish-binaries)
*   [Jekyll Diff Action (⭐6)](https://github.com/David-Byrne/jekyll-diff-action) - Diffs the built Jekyll site after a change, and comments the result back to GitHub.
*   [Branch Protection Bot (⭐72)](https://github.com/benjefferies/branch-protection-bot) - Temporarily disable and re-enable "Include administrators" option in branch protection.
*   [Wait for commit statuses (⭐98)](https://github.com/WyriHaximus/github-action-wait-for-status) - Wait until all statuses and checks are successful or any of them has failed and set its status output accordingly.
*   [Get Latest Tag (⭐182)](https://github.com/WyriHaximus/github-action-get-previous-tag) - Get the previous tag from git.
*   [Create Milestone (⭐16)](https://github.com/WyriHaximus/github-action-create-milestone) - Create a new open milestone given the title and description.
*   [Close Milestone (⭐4)](https://github.com/WyriHaximus/github-action-close-milestone) - Close the given milestone.
*   [Action to enforce branch naming rules (⭐77)](https://github.com/deepakputhraya/action-branch-name)
*   [Expose slug of some GitHub variables](https://github.com/marketplace/actions/github-slug)
*   [awesome-lint as a GitHub Action (⭐20)](https://github.com/max/awesome-lint)
*   [Edit JSON File (⭐12)](https://github.com/deef0000dragon1/json-edit-action)
*   [Build Slate documentation (⭐18)](https://github.com/Decathlon/slate-builder-action)
*   [Read Properties (⭐21)](https://github.com/christian-draeger/read-properties) - Read values from `.properties` files.
*   [Write Properties (⭐14)](https://github.com/christian-draeger/write-properties) - Write values to `.properties` files.
*   [Autotag (⭐74)](https://github.com/butlerlogic/action-autotag) - Automatically generate a new tag when the manifest file (i.e. `package.json`) version changes.
*   [Apply templates with Jinja2 (⭐43)](https://github.com/cuchi/jinja2-action) - Use the Jinja2 template engine to generate files from templates.
*   [Has Changes (⭐31)](https://github.com/UnicornGlobal/has-changes-action) - Check if there are code changes from previous steps.
*   [Mind Your Language Action (⭐17)](https://github.com/tailaiw/mind-your-language-action) - Detect offensive comments in issues and pull requests, and warn senders.
*   [YAML/JSON/XML Converter (⭐27)](https://github.com/fabasoad/yaml-json-xml-converter-action) - Converts YAML/JSON/XML file formats interchangeably.
*   [NSFW Detection (⭐16)](https://github.com/fabasoad/nsfw-detection-action) - Detect NSFW content in committed files.
*   [Has Changed Path (⭐220)](https://github.com/MarceloPrado/has-changed-path) - Conditionally run actions based on changed paths.
*   [Linguist (⭐6)](https://github.com/fabasoad/linguist-action) - Checks a repository and produces information about used languages in output.
*   [Twilio Voice Call (⭐14)](https://github.com/fabasoad/twilio-voice-call-action/) - Make Twilio voice call with defined text.
*   [Setup Xcode (⭐278)](https://github.com/maxim-lobanov/setup-xcode) - Switch between pre-installed versions of Xcode for macOS images.
*   [Setup Xamarin (⭐33)](https://github.com/maxim-lobanov/setup-xamarin) - Switch between pre-installed versions of Xamarin and Mono for macOS images.
*   [Memer Action (⭐36)](https://github.com/Bhupesh-V/memer-action) - A GitHub Action for Programmer Memes xD.
*   [Setup Cocoapods (⭐31)](https://github.com/maxim-lobanov/setup-cocoapods) - Setup specific version of Cocoapods.
*   [Public IP (⭐111)](https://github.com/haythem/public-ip) - Queries GitHub actions runner's public IP address.
*   [GitHub Actions for Lazarus/FPC (⭐45)](https://github.com/gcarreno/setup-lazarus)
*   [Twilio Fax (⭐5)](https://github.com/fabasoad/twilio-fax-action/) - Sends a document by fax using your Twilio account.
*   [Setup Kubernetes tools (⭐74)](https://github.com/yokawasa/action-setup-kube-tools) - Install Kubernetes tools (kubectl, kustomize, helm, kubeval, conftest, and yq) on the runner.
*   [Setup Elastic Cloud Control Tool (⭐5)](https://github.com/yokawasa/action-setup-ecctl) - Install a specific version of ecctl on the runner.
*   [PowerShell Script (⭐47)](https://github.com/Amadevus/pwsh-script) - Run PowerShell scripts with workflow contexts (e.g. `$github.token`) and cmdlets, return value => action output.
*   [Upload and Scan Files with VirusTotal (⭐155)](https://github.com/crazy-max/ghaction-virustotal)
*   [Import a GPG Key (⭐311)](https://github.com/crazy-max/ghaction-import-gpg)
*   [Compress with UPX (⭐55)](https://github.com/crazy-max/ghaction-upx) - The Ultimate Packer for eXecutables.
*   [Pull the New Go Module Version Into the Proxy Cache (⭐26)](https://github.com/andrewslotin/go-proxy-pull-action) - Ensures the latest version of your Go module is in the proxy cache. Also updates the pkg.go.dev documentation upon release.
*   [Delete Run Artifacts](https://github.com/marketplace/actions/delete-run-artifacts) - Deletes all artifacts at the end of a workflow run.
*   [GitHub Environment Variables Action (⭐182)](https://github.com/FranzDiebold/github-env-vars-action) - Expose environment variables such as the branch/tag name, repository slug, and ref slug.
*   [GitHub Action Locks (⭐16)](https://github.com/abatilo/github-action-locks/blob/master/README.md) - Guarantee atomic execution of your GitHub Action workflows.
*   [Paths Filter (⭐2.1k)](https://github.com/dorny/paths-filter) - Conditionally run actions based on files modified by PR, feature branch or pushed commits.
*   [Minisauras (⭐48)](https://github.com/TeamTigers/minisauras) -  Pulls all the JavaScript and CSS files from your base branch, minify them and creates a pull-request with a new branch.
*   [Website to GIF (⭐108)](https://github.com/PabloLec/website-to-gif) - Turn any webpage into a GIF to display on your README, docs, etc.
*   [Interactive Inputs - Runtime workflow inputs (⭐1)](https://github.com/boasiHQ/interactive-inputs) - Add dynamic inputs at runtime for your GitHub Actions workflows

#### Environments

*   [Create an envfile (⭐400)](https://github.com/SpicyPizza/create-envfile)
*   [Export global environment variables for succeeding build steps (⭐6)](https://github.com/zweitag/github-actions)
*   [Programmatically set environment variables for use in subsequent steps (⭐50)](https://github.com/allenevans/set-env)
*   [Install Conda environments for Python (⭐1)](https://github.com/goanpeca/setup-miniconda)
*   [Setup NativeScript (⭐4)](https://github.com/hrueger/setup-nativescript)
*   [Create a JSON Environment File (⭐15)](https://github.com/schdck/create-env-json)

#### Dependencies

*   [Install NPM Dependencies with Caching (⭐649)](https://github.com/bahmutov/npm-install)
*   [Highlight New NPM Dependencies (⭐26)](https://github.com/hiwelo/new-dependencies-action) - Comments on pull requests newly added NPM dependencies information.
*   [Cache NPM Dependencies (⭐17)](https://github.com/c-hive/gha-npm-cache)
*   [Cache Yarn Dependencies (⭐91)](https://github.com/c-hive/gha-yarn-cache)

#### Semantic Versioning

*   [Next SemVers (⭐58)](https://github.com/WyriHaximus/github-action-next-semvers) - Output the next version for major, minor, and patch version based on the given semver version.
*   [Get latest SemVer and branch name given a search string (⭐5)](https://github.com/jessicalostinspace/github-action-get-regex-branch)
*   [Cut Release Branch (⭐10)](https://github.com/jessicalostinspace/cut-release-action) - Cuts a release branch given a branch prefix and optional semantic version.
*   [Increment Semantic Version (⭐84)](https://github.com/christian-draeger/increment-semantic-version) - Bump a given semantic version (SemVer), depending on given release type.

### Static Analysis

*   [PHPStan Static code analyzer Action (⭐96)](https://github.com/OskarStark/phpstan-ga)
*   [GraphQL Inspector Action (⭐1.6k)](https://github.com/kamilkisiela/graphql-inspector)
*   [PowerShell static analysis with PSScriptAnalyzer (⭐71)](https://github.com/devblackops/github-action-psscriptanalyzer)
*   [Run tfsec, with reviewdog output on the PR (⭐71)](https://github.com/reviewdog/action-tfsec)

#### Testing

*   [Run Tests through Puppeteer, the Headless Chrome Node API (⭐93)](https://github.com/ianwalter/puppeteer)
*   [xUnit Slack Reporter: Sends summary of tests from xUnit reports to a Slack channel (⭐12)](https://github.com/ivanklee86/xunit-slack-reporter)
*   [Run codeception tests (⭐15)](https://github.com/joelwmale/codeception-action)
*   [Run TestCafe tests (⭐37)](https://github.com/DevExpress/testcafe-action)
*   [Run Unity tests (⭐205)](https://github.com/webbertakken/unity-test-runner)
*   [Run Cypress E2E tests (⭐1.3k)](https://github.com/cypress-io/github-action)
*   [Test Ansible roles with Molecule (⭐56)](https://github.com/robertdebock/molecule-action)
*   [Run performance testing with artillery.io (⭐9)](https://github.com/kenju/github-actions-artillery)
*   [Detect Flaky Tests with BuildPulse (⭐7)](https://github.com/Workshop64/buildpulse-action)
*   [Display Inline Code Annotations for Jest Tests (⭐16)](https://github.com/IgnusG/jest-report-action)
*   [Run Julia tests (⭐56)](https://github.com/julia-actions/julia-runtest)

#### Linting

*   [PHP Coding Standards Fixer Action (⭐183)](https://github.com/OskarStark/php-cs-fixer-ga)
*   [Runs Hadolint against a Dockerfile within a repository (⭐14)](https://github.com/burdzwastaken/hadolint-action)
*   [Run ESLint, with reviewdog output on the PR (⭐233)](https://github.com/reviewdog/action-eslint)
*   [JavaScript-based linter for \*.workflow files (⭐15)](https://github.com/OmarTawfik/github-actions-js)
*   [Lint terraform files using tflint, with reviewdog output on the PR (⭐107)](https://github.com/reviewdog/action-tflint)
*   [autopep8: Automatically formats Python code to conform to the PEP 8 style guide (⭐84)](https://github.com/peter-evans/autopep8)
*   [Run `ergebnis/composer-normalize` to ensure your PHP project has a normalized `composer.json` (⭐25)](https://github.com/ergebnis/composer-normalize-action)
*   [Run `stolt/lean-package-validator` to ensure your package has only the required `runtime` artifacts (⭐0)](https://github.com/raphaelstolt/lean-package-validator-action)
*   [Run Go lint checks on PR event (⭐10)](https://github.com/ArangoGutierrez/GoLinty-Action)
*   [Node.js - Automatically run the `format` and/or `lint` script used by the package (⭐36)](https://github.com/MarvinJWendt/run-node-formatter)
*   [Stylelinter - GitHub Action that runs stylelint (⭐21)](https://github.com/exelban/stylelint)
*   [Run stylelint, with reviewdog output on the PR (⭐46)](https://github.com/reviewdog/action-stylelint)
*   [PyCodeStyle Action - A GitHub Action that leaves a comment on your PR with pycodestyle (autopep8) feedback (⭐8)](https://github.com/ankitvgupta/pycodestyle-action)
*   [wemake-python-styleguide - The strictest and most opinionated python linter ever, with optional reviewdog output on the PR (⭐2.5k)](https://github.com/wemake-services/wemake-python-styleguide)
*   [Run TSLint with status checks and file diff annotations (⭐34)](https://github.com/mooyoul/tslint-actions)
*   [Lint Pull Request commits with commitlint (⭐358)](https://github.com/wagoid/commitlint-github-action)
*   [Run vint, with reviewdog output on the PR (⭐10)](https://github.com/reviewdog/action-vint)
*   [Run mispell, with reviewdog output on the PR (⭐88)](https://github.com/reviewdog/action-misspell)
*   [Run golangci-lint, with reviewdog output on the PR (⭐210)](https://github.com/reviewdog/action-golangci-lint)
*   [Run shellcheck, with reviewdog output on the PR (⭐100)](https://github.com/reviewdog/action-shellcheck)
*   [Catch insensitive, inconsiderate writing in your markdown docs (⭐11)](https://github.com/theashraf/alex-action)
*   [Run dotenv-linter - Lints your .env files like a charm, with optional reviewdog output on the PR (⭐274)](https://github.com/wemake-services/dotenv-linter)
*   [Run dotenv-linter, with reviewdog output on the PR (⭐15)](https://github.com/mgrachev/action-dotenv-linter)
*   [Show and auto-fix linting errors for many programming languages (⭐565)](https://github.com/samuelmeuli/lint-action)
*   [PHP\_CodeSniffer With Annotations (⭐55)](https://github.com/chekalsky/phpcs-action)
*   [Linter for markdown (with presets) (⭐78)](https://github.com/avto-dev/markdown-lint)
*   [Stylelint problem matcher to create annotations (⭐19)](https://github.com/xt0rted/stylelint-problem-matcher)
*   [Run sqlcheck on the PR to identifies anti-patterns in SQL queries (⭐24)](https://github.com/yokawasa/action-sqlcheck)
*   [Validate Fastlane Supply Metadata Against the Play Store Guidelines (⭐22)](https://github.com/ashutoshgngwr/validate-fastlane-supply-metadata)
*   [Run Golint to lint your Golang code (⭐6)](https://github.com/Jerome1337/golint-action)

#### Security

*   [A vulnerability scanner for your docker images (⭐31)](https://github.com/phonito/phonito-scanner-action)
*   [Automatically approve and merge Dependabot updates (⭐310)](https://github.com/ridedott/dependabot-auto-merge-action)
*   [Run dlint security linter on your Python code (⭐3)](https://github.com/xen0l/dlint-check)
*   [AWS Secrets Manager Actions (⭐62)](https://github.com/say8425/aws-secrets-manager-actions) - Define AWS Secrets Manager secrets to environment values.
*   [Linting your AWS IAM policy documents for correctness and security issues (⭐35)](https://github.com/xen0l/iam-lint)
*   [Secret Spreader (⭐37)](https://github.com/webfactory/secret-spreader) - Not an action per se, but a tool to manage Actions Secrets across a list of repositories.
*   [Secrets Sync Action (⭐312)](https://github.com/google/secrets-sync-action) - Action syncs secrets across multiple repositories.
*   [Snyk Test Action (⭐500)](https://github.com/snyk/actions)
*   [Manage Your GitHub Actions Secrets With A Simple CLI (⭐43)](https://github.com/unfor19/githubsecrets)
*   [SecretHub (⭐47)](https://github.com/secrethub/actions) - Have a single source of truth for your secrets and load them into GitHub Actions on demand.

#### Code Coverage

*   [Scan code with SonarCloud (⭐588)](https://github.com/sonarsource/sonarcloud-github-action)
*   [Send your code coverage to codecov.io (⭐1.4k)](https://github.com/codecov/codecov-action)
*   [Publishing code coverage to CodeClimate (⭐199)](https://github.com/paambaati/codeclimate-action)
*   [Update repository go report card (⭐12)](https://github.com/creekorful/goreportcard-action)

### Dynamic Analysis

*   [Run Gofmt to check Golang code formatting (⭐13)](https://github.com/Jerome1337/gofmt-action)
*   [Run Goimports to check Golang imports order (⭐5)](https://github.com/Jerome1337/goimports-action)

### Monitoring

*   [Audit a webpage with Google Chrome's Lighthouse tests (⭐342)](https://github.com/jakejarvis/lighthouse-action)
*   [Runs Lighthouse and posts results to PRs and Slack (⭐476)](https://github.com/foo-software/lighthouse-check-action)
*   [Run Lighthouse in CI using GitHub Actions (⭐1.2k)](https://github.com/treosh/lighthouse-ci-action)
*   [Continuous Benchmarking and Benchmark Visualization for Go (⭐141)](https://github.com/bobheadxi/gobenchdata)
*   [Size Limit Action (⭐446)](https://github.com/andresz1/size-limit-action) - Comments cost comparison of your JS in PRs and rejects them if limit is exceeded.
*   [Check bundlephobia (⭐51)](https://github.com/carlesnunez/check-my-bundlephobia) - Comments new and modified package size according to bundlephobia.io website and rejects PR on threshold surpassed.

### Pull Requests

*   [Set PR Reviewers Based on Assignees (⭐122)](https://github.com/pullreminders/assignee-to-reviewer-action)
*   [Open or Update PR on Branch Push (with Branch Selection) (⭐173)](https://github.com/vsoch/pull-request-action)
*   [Automatically Rebase a PR (⭐679)](https://github.com/cirrus-actions/rebase)
*   [Label PR once it has a Specified Number of Approvals (⭐191)](https://github.com/pullreminders/label-when-approved-action)
*   [Add Labels to a PR based on Matched File Patterns (⭐63)](https://github.com/banyan/auto-label)
*   [Auto-Approve PRs (⭐404)](https://github.com/hmarr/auto-approve-action)
*   [Automatically add Reviewers to PR based on the Configuration File (⭐291)](https://github.com/kentaro-m/auto-assign-action)
*   [Add Labels to a PR based on Branch Name Patterns (⭐244)](https://github.com/TimonVS/pr-labeler-action)
*   [Add Labels to a PR based on Total Size of the Diff (⭐89)](https://github.com/pascalgn/size-label-action)
*   [Automatically merge PRs That Are Ready (⭐834)](https://github.com/pascalgn/automerge-action)
*   [Verify That PRs Contain a Ticket Reference (⭐73)](https://github.com/vijaykramesh/pr-lint-action)
*   [Create a PR for Changes to your Repository in the Actions Workspace (⭐2.1k)](https://github.com/peter-evans/create-pull-request)
*   [Lint a PR (⭐119)](https://github.com/seferov/pr-lint-action)
*   [ChatOps for PRs (⭐74)](https://github.com/machine-learning-apps/actions-chatops)
*   [Prefix Title and Body of a PR Based on Text Extracted from Branch Name (⭐79)](https://github.com/tzkhan/pr-update-action)
*   [Block Autosquash Commits (⭐18)](https://github.com/xt0rted/block-autosquash-commits-action)
*   [Automatically Bump and Tag on Merge (⭐755)](https://github.com/anothrNick/github-tag-action)
*   [Automatically Update PRs with Outdated Checks and Squash and Merge the Ones Matching All Branch Protections (⭐140)](https://github.com/tibdex/autosquash)
*   [Merge Pal - Automatically Update and Merge PRs (⭐32)](https://github.com/maxkomarychev/merge-pal-action)
*   [Enforce naming convention on pull request title (⭐125)](https://github.com/deepakputhraya/action-pr-title)
*   [Pull Request Stuck Notifier](https://github.com/jrylan/github-action-stuck-pr-notifier)
*   [Lint pull request name with commitlint (Awesome if you squash merge !) (⭐78)](https://github.com/JulienKode/pull-request-name-linter-action)
*   [Block PR merges when Checks for target branches are failing (⭐6)](https://github.com/cirrus-actions/branch-guard)
*   [Get generated static site screenshots updated by Pull Request (⭐21)](https://github.com/ssowonny/diff-pages-action)
*   [Add Labels Depending if the Pull Request Still in Progress (⭐5)](https://github.com/AlbertHernandez/working-label-action)
*   [Ticket Check Action (⭐41)](https://github.com/neofinancial/ticket-check-action) - Automatically add a ticket or issue number to the start of all Pull Request titles.
*   [Pull Request Lint With Regex (⭐65)](https://github.com/MorrisonCole/pr-lint-action)
*   [Pull Request Landmines (⭐33)](https://github.com/tylermurry/github-pr-landmine)
*   [Annotate a GitHub Pull Request Based on a Checkstyle XML-Report (⭐189)](https://github.com/staabm/annotate-pull-request-from-checkstyle)
*   [Pull Request Stats (⭐349)](https://github.com/flowwer-dev/pull-request-stats) -  Print relevant stats about reviewers.
*   [Pull Request Description Enforcer](https://github.com/derkinderfietsen/pr-description-enforcer) - Enforces description on pull requests.

### GitHub Pages

*   [Deploy a Zola site to GitHub Pages (⭐221)](https://github.com/shalzz/zola-deploy-action)
*   [Build Hugo static content site and publish it to gh-pages branch (⭐42)](https://github.com/khanhicetea/gh-actions-hugo-deploy-gh-pages)
*   [Build a Jekyll site—with Custom Jekyll Plugins & Build Scripts—and deploy it back to the Gh-Pages Branch (⭐118)](https://github.com/BryanSchuetz/jekyll-deploy-gh-pages)
*   [Google Dataset Search Metadata](https://www.github.com/openschemas/extractors/) - And other schema.org extractors to make datasets discoverable from GitHub pages.
*   [GitHub Actions for deploying to GitHub Pages with Static Site Generators (⭐4.6k)](https://github.com/peaceiris/actions-gh-pages)
*   [GitHub Action for Hexo (⭐30)](https://github.com/heowc/action-hexo)
*   [Deploy Google Analytics stats to GitHub Pages (⭐14)](https://github.com/cristianpb/analytics-google)
*   [A Jupyter Notebook Blogging Platform Powered by GitHub Actions, Pages and Jekyll (⭐3.5k)](https://github.com/fastai/fastpages)
*   [Deploy A Static Site to GitHub Pages (⭐27)](https://github.com/appleboy/gh-pages-action) - Deploy to custom directory and ignore folder/file.
*   [Deploy to GitHub Pages with Advanced Settings (⭐455)](https://github.com/crazy-max/ghaction-github-pages)

### Notifications and Messages

*   [Send a Discord notification (⭐394)](https://github.com/Ilshidur/action-discord)
*   [Post a Slack message as a bot (⭐270)](https://github.com/pullreminders/slack-action)
*   [Send an SMS from GitHub Actions using Nexmo (⭐14)](https://github.com/nexmo-community/nexmo-sms-action)
*   [Send an SMS from GitHub Actions using Clockworksms (⭐3)](https://github.com/bharathvaj1995/clockwork-sms-action)
*   [Send a Telegram Message (⭐811)](https://github.com/appleboy/telegram-action)
*   [Send a File or Text Message to Discord (custom define color, username or avatar) (⭐97)](https://github.com/appleboy/discord-action)
*   [Collaborate on tweets using pull requests (⭐4)](https://github.com/gr2m/twitter-together)
*   [Send a Push Notification via Push by Techulus (⭐71)](https://github.com/techulus/push-github-action)
*   [Send email with SendGrid (⭐32)](https://github.com/peter-evans/sendgrid-action)
*   [Send a Push Notification via Join (⭐5)](https://github.com/ShaunLWM/action-join)
*   [New package version checker for npm (⭐24)](https://github.com/MeilCli/npm-update-check-action)
*   [New package version checker for NuGet (⭐9)](https://github.com/MeilCli/nuget-update-check-action)
*   [New package version checker for Gradle (⭐16)](https://github.com/MeilCli/gradle-update-check-action)
*   [Send a Push Notification via Pushbullet (⭐8)](https://github.com/ShaunLWM/action-pushbullet)
*   [Create an Outlook Calendar Event using Microsoft Graph (⭐10)](https://github.com/anoopt/ms-graph-create-event)
*   [Watch for GitHub Wiki page changes and post to Slack (⭐15)](https://github.com/benmatselby/gollum-page-watcher-action)
*   [Send an SMS using MessageBird (⭐4)](https://github.com/nikitasavinov/messagebird-sms-action)
*   [Reply to Stale Bots (⭐32)](https://github.com/c-hive/fresh-bot)
*   [Send an Embed Message to Discord (⭐168)](https://github.com/sarisia/actions-status-discord)
*   [Keep Your PRs in Sync With Teamwork Tasks (⭐64)](https://github.com/Teamwork/github-sync)
*   [Send Microsoft Teams Notification (⭐36)](https://github.com/opsless/ms-teams-github-actions)

### Deployment

*   [Deploy to Netlify (⭐374)](https://github.com/netlify/actions)
*   [Deploy a Probot App using Actions](https://probot.github.io/docs/deployment/#github-actions)
*   [Deploy a playlist to Spotify (⭐114)](https://github.com/swinton/SpotHub)
*   [Deploy VS Code extensions with vsce (⭐87)](https://github.com/lannonbr/vsce-action)
*   [Purge Cloudflare cache after updating a website (⭐133)](https://github.com/jakejarvis/cloudflare-purge-action)
*   [Deploy your DNS configuration using DNS Control (⭐79)](https://github.com/koenrh/dnscontrol-action)
*   [Deploy a Theme to Shopify (⭐129)](https://github.com/pgrimaud/action-shopify)
*   [Trigger multiple GitLab CI Pipeline (⭐65)](https://github.com/appleboy/gitlab-ci-action)
*   [Trigger multiple Jenkins Jobs (⭐90)](https://github.com/appleboy/jenkins-action)
*   [GitHub Action for Homebrew Tap (⭐12)](https://github.com/izumin5210/action-homebrew-tap)
*   [Copy files and artifacts via SSH (⭐1.2k)](https://github.com/appleboy/scp-action)
*   [Executing remote ssh commands (⭐4.6k)](https://github.com/appleboy/ssh-action)
*   [Publish a Python distribution package to PyPI (⭐888)](https://github.com/pypa/gh-action-pypi-publish)
*   [Deploy Static Website to Azure Storage (⭐17)](https://github.com/feeloor/azure-static-website-deploy)
*   [Cross platform Chocolatey CLI to build and publish packages (⭐73)](https://github.com/crazy-max/ghaction-chocolatey)
*   [Deploy iOS Pod Library to Cocoapods (⭐38)](https://github.com/michaelhenry/deploy-to-cocoapods-github-action)
*   [GitHub Action for TencentCloud Serverless (⭐3)](https://github.com/Juliiii/action-scf)
*   [Publish npm (pre)releases (⭐15)](https://github.com/epeli/npm-release/)
*   [Deploy a static site to Surge.sh (⭐80)](https://github.com/yavisht/deploy-via-surge.sh-github-action-template)
*   [GitHub Action for GoReleaser, a release automation tool for Go projects (⭐851)](https://github.com/goreleaser/goreleaser-action)
*   [FTP Deploy Action, Deploys a GitHub project to a FTP server using GitHub actions (⭐3.7k)](https://github.com/SamKirkland/FTP-Deploy-Action)
*   [Publish Article to Dev.to (⭐24)](https://github.com/tylerauerbeck/publish-to-dev.to-action)
*   [Action For Semantic Release (⭐528)](https://github.com/cycjimmy/semantic-release-action)
*   [Deploy a Collection to Ansible Galaxy (⭐88)](https://github.com/artis3n/ansible_galaxy_collection)
*   [Publish module to Puppet Forge (⭐8)](https://github.com/barnumbirr/action-forge-publish)
*   [Build and publish Electron apps (⭐654)](https://github.com/samuelmeuli/action-electron-builder)
*   [Publish a Maven package (⭐101)](https://github.com/samuelmeuli/action-maven-publish)
*   [Build and deploy a theme to Ghost CMS (⭐352)](https://github.com/TryGhost/action-deploy-theme)
*   [Deploy an Ansible role to Ansible Galaxy (⭐32)](https://github.com/robertdebock/galaxy-action)
*   [Publish one or more JS modules to a registry (⭐9)](https://github.com/author/action-publish)
*   [Publish a package with 2FA using Slack (⭐11)](https://github.com/erezrokah/2fa-with-slack-action)
*   [Serialize Workflow Runs in Continuous Deployment Pipelines (⭐289)](https://github.com/softprops/turnstyle)
*   [Netlify Deploy GitHub Action for each commit (⭐325)](https://github.com/nwtgck/actions-netlify)
*   [Run Ansible Playbooks (⭐30)](https://github.com/arillso/action.playbook)
*   [Publish a Python Distribution Package to Anaconda Cloud (⭐27)](https://github.com/fcakyon/conda-publish-action)
*   [Deploy VS Code Extension to Visual Studio Marketplace or the Open VSX Registry (⭐203)](https://github.com/HaaLeo/publish-vscode-extension)
*   [Deploy a YouTube Video to Anchor.fm Podcast (⭐126)](https://github.com/Schrodinger-Hat/youtube-to-anchorfm)
*   [Deploy with AWS CodeDeploy (⭐21)](https://github.com/webfactory/create-aws-codedeploy-deployment)

#### Docker

*   [Update a Docker Hub repository description from README.md (⭐323)](https://github.com/peter-evans/dockerhub-description)
*   [Publish Docker Images to the GitHub Package Registry (GPR) (⭐53)](https://github.com/machine-learning-apps/gpr-docker-publish)
*   [Update a repository's "Full description" on Docker Hub (⭐4)](https://github.com/mpepping/github-actions/tree/master/docker-hub-metadata)
*   [Build and publish docker images to any registry using Kaniko (⭐119)](https://github.com/outillage/kaniko-action)
*   [Monitor and limit your docker image size (⭐118)](https://github.com/wemake-services/docker-image-size-limit)
*   [Publish Docker Images to the Amazon Elastic Container Registry (ECR) (⭐22)](https://github.com/appleboy/docker-ecr-action)
*   [Build And Push Your Docker Images Caching Each Stage To Reduce Build Time (⭐341)](https://github.com/whoan/docker-build-with-cache-action)
*   [Set up Docker Buildx (⭐226)](https://github.com/crazy-max/ghaction-docker-buildx)
*   [Convert Branch or Tag Name Into Docker-Compatible Image Tag (⭐5)](https://github.com/ankitvgupta/ref-to-tag-action/)
*   [Update a Container Repository Description From README.md](https://github.com/marketplace/actions/update-container-description-action) - Supported Registries: Docker Hub, Quay, Harbor.

#### Kubernetes

*   [Deploy to any Cloud or Kubernetes Using Pulumi (⭐250)](https://github.com/pulumi/actions)
*   [Deploy to Kubernetes with kubectl (⭐213)](https://github.com/steebchen/kubectl)
*   [Get Kubeconfig File From Google Kubernetes Engine (GKE) (⭐13)](https://github.com/machine-learning-apps/gke-kubeconfig)
*   [Kustomize Kubernetes Config YAMLs (⭐45)](https://github.com/karancode/kustomize-github-action)
*   [Create a Kubernetes Cluster for Testing Using Krucible (⭐4)](https://github.com/Krucible/krucible-github-action)

#### AWS

*   [Sync/upload a directory to an AWS S3 bucket (⭐1k)](https://github.com/jakejarvis/s3-sync-action)
*   [Deploy Lambda code to an existing function (⭐387)](https://github.com/appleboy/lambda-action)

#### Terraform

*   [Generate terraform documentation (⭐38)](https://github.com/Dirrk/terraform-docs) - Uses terraform-docs to generate docs for terraform modules.
*   [An example of using Terraform to validate and apply GitHub administration (⭐2)](https://github.com/asgharlabs/github-terraform/tree/master/.github/workflows)

### External Services

*   [Use a Jenkinsfile (⭐198)](https://github.com/jonico/jenkinsfile-runner-github-actions)
*   [GitHub Action for Firebase (⭐919)](https://github.com/w9jds/firebase-action)
*   [GitHub Action for Contentful Migration CLI (⭐15)](https://github.com/Shy/contentful-action)
*   [GitHub Actions for Pixela (a-know/pi) (⭐12)](https://github.com/peaceiris/actions-pixela)
*   [GitHub Action for Google Cloud Platform (GCP) (⭐228)](https://github.com/exelban/gcloud)
*   [Upload files to any OpenStack Swift service provider (⭐1)](https://github.com/iksaku/openstack-swift-action)
*   [GitHub Action for sending Stack Overflow posts to Slack (⭐17)](https://github.com/logankilpatrick/StackOverflowBot)
*   [Assume AWS role (⭐23)](https://github.com/nordcloud/aws-assume-role/)
*   [Generate Custom Response using JSONbin (⭐6)](https://github.com/fabasoad/jsonbin-action)

### Frontend Tools

*   [Execute Gradle task (⭐29)](https://github.com/MrRamych/gradle-actions)
*   [JS Build Actions (⭐53)](https://github.com/elstudio/actions-js-build) - Run Grunt or Gulp build tasks and commit file changes.
*   [GitHub Action for Gatsby CLI (⭐47)](https://github.com/jzweifel/gatsby-cli-github-action)
*   [Runs a WebPageTest audit and prints the results as commit comment (⭐57)](https://github.com/JCofman/webPagetestAction)
*   [GitHub Actions for Hugo extended (⭐1.4k)](https://github.com/peaceiris/actions-hugo)
*   [Generate OG Image (⭐39)](https://github.com/BoyWithSilverWings/generate-og-image) - Generate customisable open graph images from Markdown files.
*   [GitHub Actions for mdBook (⭐289)](https://github.com/peaceiris/actions-mdbook)
*   [Setup Mint (⭐11)](https://github.com/fabasoad/setup-mint-action) - Setup Mint (programming language for writing single page applications).
*   [Gatsby AWS S3 Deployment (⭐47)](https://github.com/jonelantha/gatsby-s3-action) - Deploy Gatsby to S3 (supports CloudFront).

### Machine Learning Ops

*   [Submitting Argo Workflows (Cloud Agnostic) (⭐38)](https://github.com/machine-learning-apps/actions-argo)
*   [Submitting Argo Workflows to GKE (⭐16)](https://github.com/machine-learning-apps/gke-argo)
*   [Query Experiment Tracking Results From Weights & Biases (⭐60)](https://github.com/machine-learning-apps/wandb-action)
*   [Run Parameterized Jupyter Notebooks (⭐69)](https://github.com/yaananth/run-notebook)
*   [Compile, Deploy and Run Kubeflow Pipeline (⭐35)](https://github.com/NikeNano/kubeflow-github-action)
*   [Automatically Dockerize A Data-Science Repo As A Jupyter Server (⭐140)](https://github.com/jupyterhub/repo2docker-action)
*   [Azure Machine Learning With GitHub Actions (⭐125)](https://github.com/machine-learning-apps/ml-template-azure)

### Build

*   [run-cmake (⭐176)](https://github.com/lukka/run-cmake) - Multi platform action to build C/C++ software with [CMake](https://cmake.org) and [Ninja](https://ninja-build.org/).
*   [run-vcpkg (⭐186)](https://github.com/lukka/run-vcpkg) - Multi platform action to build and install C/C++ dependencies with [vcpkg (⭐23k)](https://github.com/microsoft/vcpkg).
*   [Build Go applications for multiplatform (⭐6)](https://github.com/izumin5210/action-go-crossbuild)
*   [Generate \~/.m2/settings.xml for Maven builds (⭐71)](https://github.com/whelk-io/maven-settings-xml-action)
*   [Run Pascal Script (⭐6)](https://github.com/fabasoad/pascal-action)
*   [Setup Brainfuck (⭐2)](https://github.com/fabasoad/setup-brainfuck-action) - Setup brainfuck interpreter.
*   [Publish Go Binaries to GitHub Release Assets (⭐485)](https://github.com/wangyoucao577/go-release-action)
*   [Setup COBOL (⭐12)](https://github.com/fabasoad/setup-cobol-action)
*   [Check Gradle version (⭐7)](https://github.com/madhead/check-gradle-version) - Keep your Gradle version up to date.

### Database

*   [Setup Cassandra Schema (⭐2)](https://github.com/fabasoad/setup-cassandra-action) - Running scripts from the provided folder on top of Cassandra cluster.

### Networking

*   [Setup ZeroTier (⭐45)](https://github.com/zerotier/github-action) - Connect your runner to a ZeroTier network.

### Localization

*   [Find and automatically fix typos and grammar issues in your code (⭐146)](https://github.com/sobolevn/misspell-fixer-action)
*   [Translation (⭐40)](https://github.com/fabasoad/translation-action) - Translate text from any language to any language.

### Fun

*   [Add equivalent of a like button in your README (⭐9)](https://github.com/ariary/Readme-Like-Button) - Visualize community approval on some part of your readme (can be used as a poll).

### Cheat Sheet

*   [GitHub Actions Branding Cheat Sheet](https://haya14busa.github.io/github-action-brandings/)

## Tutorials

*   [Continuous deployment of Next.js app with Up](https://medium.com/@romanenko/simple-ci-for-next-js-projects-with-apex-up-github-actions-6f0b1b9a5400)
*   [Converting Docker-based Actions to JavaScript/TypeScript](https://httgp.com/converting-github-actions-from-docker-to-javascript/)
*   [GitHub Actions CI for Swift/iOS Projects](https://medium.com/rosberryapps/github-actions-ci-for-swift-projects-c129baceed1a)
*   [Working with GitHub Actions](https://jeffrafter.com/working-with-github-actions)
*   [GitHub Actions for Rails Developers](https://www.youtube.com/watch?v=gGUXydw22zw)
*   [GitHub Actions Advent Calendar](https://www.edwardthomson.com/blog/github_actions_advent_calendar.html)
*   [Zero Downtime Laravel Deployments with GitHub Actions](https://atymic.dev/blog/github-actions-laravel-ci-cd/)
*   [Building Custom GitHub Actions Pluralsight Course](https://www.pluralsight.com/courses/building-custom-github-actions/)
*   [Continuously Deploying Django to DigitalOcean with Docker and GitHub Actions](https://testdriven.io/blog/deploying-django-to-digitalocean-with-docker-and-github-actions/)
*   [Deploying Self-Hosted GitHub Actions Runners with Docker](https://testdriven.io/blog/github-actions-docker/) - Deploy self-hosted GitHub Actions runners with Docker and Docker Swarm to DigitalOcean.
*   [Setup Auto-scaled self-hosted GitHub Actions Runners on AWS Spot-instances](https://040code.github.io/2020/05/25/scaling-selfhosted-action-runners)
*   [Getting the Gist of GitHub Actions](https://gist.github.com/br3ndonland/f9c753eb27381f97336aa21b8d932be6)

> Please don't hesitate to make a PR if you have more resources to share. Check out [contributing.md](https://github.com/sdras/awesome-actions/blob/main/README.md/contributing.md) for more information.

