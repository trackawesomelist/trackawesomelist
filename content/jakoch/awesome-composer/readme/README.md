# Awesome Composer Overview

 :sunglasses: A curated awesome list for Composer, Packagist, Satis, Plugins, Scripts, Composer related resources, tutorials.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/jakoch/awesome-composer/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 jakoch/awesome-composer](https://github.com/jakoch/awesome-composer) · ⭐ 870 · 🏷️ Programming Languages

[ [Daily](/content/jakoch/awesome-composer/README.md) / [Weekly](/content/jakoch/awesome-composer/week/README.md) / Overview ]

---

<!--lint disable double-link awesome-toc-->

# Awesome Composer [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) [![Build on Windows](https://github.com/jakoch/awesome-composer/actions/workflows/awesome-bot.yml/badge.svg?branch=main)](https://github.com/jakoch/awesome-composer/actions/workflows/awesome-bot.yml) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)](https://github.com/jakoch/awesome-composer/blob/main/README.md/)

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php (⭐31k)](https://github.com/ziadoz/awesome-php).

*Please read the [contribution guidelines (⭐870)](https://github.com/jakoch/awesome-composer/blob/main/.github/CONTRIBUTING.md) before contributing.*

## Composer

*   [Official Website](https://getcomposer.org/)
*   [GitHub (⭐29k)](https://github.com/composer/composer)
*   [Issues (⭐29k)](https://github.com/composer/composer/issues)
*   [Source (⭐29k)](https://github.com/composer/composer/tree/HEAD/src/Composer)
*   [Documentation](https://getcomposer.org/doc/)
*   [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
*   [Find Packages on Packagist](https://packagist.org/)
*   [CheatSheet](https://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.
*   [Composer Installers (⭐1.4k)](https://github.com/composer/installers) - Composer installers for multiple frameworks.

### Support

#### Stack Overflow

*   You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
*   [Ask a new question](https://stackoverflow.com/questions/ask?tags=composer-php+php)
*   [Find questions tagged `composer-php`](https://stackoverflow.com/questions/tagged/composer-php)

#### IRC

*   IRC channels are on `irc.freenode.org`: [#composer](https://webchat.freenode.net/#composer) for users and [#composer-dev](https://webchat.freenode.net/#composer-dev) for development.

***

## Plugins

*   [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
*   [Composer-Asset-Plugin (⭐890)](https://github.com/fxpio/composer-asset-plugin) - A npm/Bower Dependencies Manager for Composer.
*   [Composer-AWS (⭐77)](https://github.com/naderman/composer-aws) - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories).
*   [Composer-Composition (⭐105)](https://github.com/bamarni/composition) - Provides an API, for checking your environment at runtime.
*   [Composer-Suggest (⭐4)](https://github.com/nfreear/composer-suggest) - Enables you to install a custom group of suggested packages, based on keyword patterns.
*   [Composer-Versions-Check (⭐234)](https://github.com/Soullivaneuh/composer-versions-check) - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z").
*   [Composer-Changelogs (⭐589)](https://github.com/pyrech/composer-changelogs) - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file.
*   [Composer-Merge-Plugin (⭐945)](https://github.com/wikimedia/composer-merge-plugin) - Merges multiple `composer.json` files at Composer runtime.
*   [Composer-Bin-Plugin (⭐490)](https://github.com/bamarni/composer-bin-plugin) - Adds support for managing dependencies for multiple packages in a single repository or isolate bin dependencies.
*   [Composer-Inheritance-Plugin (⭐28)](https://github.com/theofidry/composer-inheritance-plugin) - Opinionated version of Wikimedia composer-merge-plugin to work in pair with Bamarni composer-bin-plugin.
*   [Composer-MonoRepo-Plugin (⭐305)](https://github.com/beberlei/composer-monorepo-plugin) - The plugin helps to manage dependencies for multiple packages in a single repository.
*   [Composer-Patches-Plugin (⭐79)](https://github.com/netresearch/composer-patches-plugin) - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top.
*   [Composer-Patches (⭐1.6k)](https://github.com/cweagans/composer-patches) - The plugin applies a patch from a local or remote file to any required package.
*   [Composer-Patches (⭐290)](https://github.com/vaimo/composer-patches) - Applies a patch from a local or remote file to any package that is part of a given composer project.
*   [Composer-Patchset (⭐8)](https://github.com/mageops/php-composer-plugin-patchset) - Automatically fetch, update and apply patches to any composer package with a twist - store the patchset as a composer package itself.
*   [Composer-Plugin-QA (⭐25)](https://github.com/Webysther/composer-plugin-qa) - Comprehensive Plugin for composer to execute PHP Quality assurance Tools.
*   [Composer-Cleanup-Plugin (⭐146)](https://github.com/barryvdh/composer-cleanup-plugin) - Removes tests & documentation folders from the vendor dir.
*   [Composer-Cleaner (⭐137)](https://github.com/dg/composer-cleaner) - The tool removes unnecessary files and directories from the vendor directory.
*   [Composer-Ignore-Plugin (⭐21)](https://github.com/lichunqiang/composer-ignore-plugin) - Enables you to remove files and folders from the vendor folder (to make a cleaner and smaller deployment to production). It's an alternative to `.gitattributes`.
*   [Composer-Vendor-Cleaner (⭐31)](https://github.com/liborm85/composer-vendor-cleaner) - Plugin removes unnecessary development files and directories from `vendor` directory by glob pattern syntax.
*   [Composer-Skrub (⭐86)](https://github.com/ssx/skrub) - The plugin helps to remove junk from Composer installations and trim build sizes.
*   [Drupal Vendor Hardening Composer Plugin (⭐15)](https://github.com/drupal/core-vendor-hardening) - Removes extraneous directories from the project's vendor directory & adds .htaccess and web.config files to the root of the project's vendor directory.
*   [Composer-Shared-Package-Plugin (⭐164)](https://github.com/Letudiant/composer-shared-package-plugin) - Allows you to share selected packages between your projects by creating symlinks.
*   [Composer-Symlinker (⭐18)](https://github.com/e-picas/composer-symlinker) - Enables you to load packages from different directories (instead of loading them from /vendor).
*   [Prestissimo (⭐6.2k)](https://github.com/hirak/prestissimo) - A parallel downloader using `phpext_curl`.
*   [Composer-Curl-Plugin (⭐5)](https://github.com/ngyuki/composer-curl-plugin) - The plugin uses `phpext_curl` for downloading packages.
*   [Composer-Custom-Directory-Installer (⭐139)](https://github.com/mnsami/composer-custom-directory-installer) - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (vendor folder).
*   [Composer-Dependency-Analyzer (⭐478)](https://github.com/shipmonk-rnd/composer-dependency-analyser) - The plugin helps to find dependency issues, including dead, unused, shadow and misplaced dependencies.
*   [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.
*   [Graph-Composer (⭐935)](https://github.com/clue/graph-composer) - Provides a graph visualization for your project's `composer.json` and its dependencies.
*   [PackageVersions (⭐3.2k)](https://github.com/Ocramius/PackageVersions) - Provides a very quick and easy access to installed composer dependency versions.
*   [PackageVersions Deprecated (⭐1.5k)](https://github.com/composer/package-versions-deprecated) - Is a fork of Ocramius/PackageVersions providing compatibility with Composer 1 and 2 on PHP 7+.
*   [Composer-Locator (⭐58)](https://github.com/mindplay-dk/composer-locator) - Provides a means of locating the installation path for a given Composer package name.
*   [PackageInfo (⭐7)](https://github.com/ThaDafinser/PackageInfo) - Enables you to retrieve all package informations (like version, tag, release date, description).
*   [Composer-Git-Hooks (⭐1.1k)](https://github.com/BrainMaestro/composer-git-hooks) - A library for easily managing git hooks in your composer config.
*   [Symfony-Flex (⭐4.2k)](https://github.com/symfony/flex) - Provides [recipe-based (⭐990)](https://github.com/symfony/recipes) installation and configuration management for Symfony packages.
*   [Narrowspark-Automatic (⭐13)](https://github.com/narrowspark/automatic) - Automates the most common tasks of applications, boost package downloads, adds a composer security audit and more.
*   [PHPCodeSniffer-Composer-Installer (⭐574)](https://github.com/PHPCSStandards/composer-installer) - The plugin enables you to install [PHP\_CodeSniffer (⭐11k)](https://github.com/squizlabs/PHP_CodeSniffer) coding standards (rulesets).
*   [Composer-Warmup (⭐181)](https://github.com/jderusse/composer-warmup) - The plugin adds the command `warmup-opcode` to Composer, which triggers the compilation of all PHP files discovered in your project into the Opcache.
*   [Foxy (⭐175)](https://github.com/fxpio/foxy) - Composer plugin that executes npm/yarn packages installation operations, when composer package is installed or updated.
*   [NodeJS-Installer (⭐107)](https://github.com/thecodingmachine/nodejs-installer) - Installer for Node.js and npm.
*   [Node-Composer (⭐6)](https://github.com/mariusbuescher/node-composer) - Installer for Node.js, npm and yarn.
*   [Imposter-Plugin (⭐151)](https://github.com/typisttech/imposter-plugin) - Wrapping all composer vendor packages inside your own namespace. Intended for WordPress plugins.
*   [Composer Preload (⭐205)](https://github.com/Ayesh/Composer-Preload) - The plugin generates a `vendor/preload.php` file to warm up the Opcache.
*   [PHP Inc (⭐5)](https://github.com/krakphp/php-inc) - Automatically includes files for autoload and autoload-dev to facilitate using functions and grouped definitions within composer loaded applications.
*   [Composer Registry Manager (⭐560)](https://github.com/slince/composer-registry-manager) - Enables you to switch between different composer repositories.
*   [Production-Dependencies-Guard (⭐87)](https://github.com/kalessil/production-dependencies-guard) - Prevents development packages from being added into require and getting into production environment.
*   [Composer-Plugin-Exclude-Files (⭐40)](https://github.com/mcaskill/composer-plugin-exclude-files) - A plugin for excluding files required by packages using the 'files' autoloading mechanism.
*   [Composer-Downloads-Plugin (⭐7)](https://github.com/civicrm/composer-downloads-plugin) - Lightweight mechanism to download external resources (ZIP/TAR files) with only a `url` and `path`.
*   [Private-Composer-Installer (⭐228)](https://github.com/ffraenz/private-composer-installer) - Install helper outsourcing sensitive keys from the package URL into environment variables.
*   [CycloneDX-PHP-Composer (⭐58)](https://github.com/CycloneDX/cyclonedx-php-composer) - Creates a [CycloneDX](https://cyclonedx.org/) "Software Bill-of-Materials" (SBOM) for the dependencies of a project. The SBOM enables dependency monitoring and risk analysis by [OWASP DependencyTrack](https://dependencytrack.org/).
*   [Composer-Compile-Plugin (⭐12)](https://github.com/civicrm/composer-compile-plugin) - Allow PHP libraries to define simple, freeform compilation tasks. Support post-install hooks in any package.
*   [Composer-Link (⭐63)](https://github.com/SanderSander/composer-link) - Adds the ability to link local packages for development.
*   [Composer-REPL (⭐102)](https://github.com/ramsey/composer-repl) - The plugin provides the `composer repl` command, which gives you a PHP language shell (read-eval-print loop).
*   [Composer-Diff (⭐160)](https://github.com/IonBazan/composer-diff) - Compares `composer.lock` changes and generates a Markdown report for usage in a pull request description.
*   [Composer-Velocita (⭐27)](https://github.com/isaaceindhoven/composer-velocita) - Fast and reliable Composer package downloads using [Velocita (⭐61)](https://github.com/isaaceindhoven/velocita-proxy): a caching reverse proxy that does not require you to modify your projects.

## Tools

*   [Composer SemVer Checker](https://semver.madewithlove.com/) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
*   [Composer-Yaml (⭐56)](https://github.com/igorw/composer-yaml) - This tool converts `composer.yml` to `composer.json`.
*   [Studio (⭐1.1k)](https://github.com/franzliedke/studio) - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project.
*   [OctoLinker Browser Extension (⭐5.3k)](https://github.com/OctoLinker/OctoLinker) - Enables you to navigate Composer/NPM dependencies on GitHub.
*   [ComposerRequireChecker (⭐930)](https://github.com/maglnet/ComposerRequireChecker) - A CLI tool to analyze dependencies and verify that no unknown imported symbols are used in the sources of a package.
*   [Composer-Unused (⭐1.5k)](https://github.com/composer-unused/composer-unused) - A CLI tool, which scans your code and shows unused Composer dependencies.
*   [Composer-Normalize (⭐1.1k)](https://github.com/ergebnis/composer-normalize) - The plugin helps to keep your `composer.json` file(s) consistent by restructuring and sorting entries (normalizing).
*   [Composer-Service (⭐174)](https://github.com/pborreli/composer-service) - Enables you to run Composer as a service on a remote server.
*   [Composer PreferLowest Checker (⭐20)](https://github.com/dereuromark/composer-prefer-lowest) - Strictly compare the specified minimum versions of your composer.json with the ones actually used by the prefer-lowest composer update command option.
*   [Bramus/Composer-Autocomplete (⭐96)](https://github.com/bramus/composer-autocomplete) - A Bash/Shell autocompletion script for Composer.
*   [Composer/Xdebug-Handler (⭐2.5k)](https://github.com/composer/xdebug-handler) - Helps you to restart a CLI process without loading the xdebug extension.
*   [Composer Semver Range Checker](https://gitlab.com/MattyRad/composer.guru) - A tool to help check the satisfiable ranges of a composer constraint.

## Scripts

*   [ParameterHandler (⭐929)](https://github.com/Incenteev/ParameterHandler) - Allows you to manage your ignored parameters when running a composer install or update.
*   [Tooly (⭐101)](https://github.com/tommy-muehle/tooly-composer-script) - Manage needed PHAR files in your project `composer.json`. Every PHAR file will be saved in the composer binary directory. Optional with GPG verification for every PHAR.
*   [Melody (⭐395)](https://github.com/sensiolabs/melody) - One-file composer scripts.
*   [Composer-Travis-Lint (⭐6)](https://github.com/raphaelstolt/composer-travis-lint) - Allows you to lint the Travis CI configuration file (`.travis.yml`).
*   [Composer-Multitest (⭐5)](https://github.com/raphaelstolt/composer-multitest) - Enables you to run a Composer script against multiple, locally installed PHP versions, which are managed by PHPBrew or phpenv.
*   [ScriptsDev (⭐69)](https://github.com/neronmoon/scriptsdev) - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode.
*   [PhantomJS-Installer (⭐151)](https://github.com/jakoch/phantomjs-installer) - A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.
*   [Composer-Vendor-Cleanup (⭐3)](https://github.com/0xch/composer-vendor-cleanup) - A script which removes whitelisted unnecessary files (like tests/docs etc.) from the vendor directory.
*   [Composer-Substitution-Plugin (⭐50)](https://github.com/villfa/composer-substitution-plugin) - A Composer plugin replacing placeholders in the `scripts` section by dynamic values.

## Services

*   [Dependabot](https://github.com/features/security/) - Dependabot is a dependency update service. It monitors and updates your dependencies by sending a pull-request. The service is free for public repos and personal account repos.

***

## Tutorials

*   [A beginners guide to Composer](https://www.digitalocean.com/community/tutorials/a-beginners-guide-to-composer)
*   [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
*   [Easy package management with Composer](https://code.tutsplus.com/easy-package-management-with-composer--net-25530t)
*   [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
*   [Composer Primer](https://daylerees.com/composer-primer/)
*   [PHP Composer Magento Tutorial by Alan Storm](https://alanastorm.com/php_composer_magento_tutorial/)
*   [Creating and Using Composer Packages](https://www.packtpub.com/en-us/learning/how-to-tutorials/creating-and-using-composer-packages/)

## Blogs

*   [Jordi Boggiano (seldaek)](https://seld.be/)
*   [Nils Adermann (naderman)](https://naderman.de/)
*   [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
*   [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)
*   [The long journey of making PHPs Composer memory-efficient and fast (toflar)](https://medium.com/@yanick.witschi/the-long-journey-of-making-phps-composer-memory-efficient-and-fast-63d12944aaa8)

## Videos

*   [Composer Best Practices 2018 - Nils Adermann @ scotphp18](https://www.youtube.com/watch?v=eQkFjMfyqFY)
*   [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
*   [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
*   [Composer Best Practices — Jordi Boggiano @ phptek 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
*   [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
*   [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
*   [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
*   [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)
*   [Composer 2 - Jordi Boggiano @ Symfony UK usergroup 2020](https://www.youtube.com/watch?v=BAgwWhRo82w)
*   [Lessons learned building the Composer internals - Jordi Boggiano @ CODEiD Odessa PHP Conference 2017](https://www.youtube.com/watch?v=pjvbn6TBZqM)

## Slides

*   Slides by Nils Adermann
    *   Source: <https://naderman.de/slippy/src/>
    *   [PHP Reinvented - How Composer helped shape the new way of writing PHP](https://naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
    *   [Composer Update](https://naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
    *   [Dependency Management with Composer PHP Reinvented](https://naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
    *   [Managing dependencies is
        more than running
        "composer update"](https://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf)
    *   [Composer
        Best Practices @ T3DD17](https://naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf)
    *   [Gain Control over your
        Dependencies with
        Private Packagist](https://naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf)
    *   [Composer.lock demystified](https://naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
    *   [Compoer In-Depth @ Contao Konferenz 2018](https://naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
    *   [Composer Best Practices 2018](https://naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
    *   [Developing and Deploying Magento with Composer Best Practices](https://naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
    *   [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](https://naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
*   Slides by Jordi Boggiano
    *   Source: <http://slides.seld.be/>
    *   [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
    *   [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
    *   [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
    *   [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
    *   [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)
    *   [Lessons Learned Building the Composer Internals (2018)](http://slides.seld.be/?file=2018-04-20+Lessons+Learned+Building+the+Composer+Internals.html)

***

## Packagist

[Packagist](https://packagist.org) is the PHP Package Repository.

### Setup a Packagist Mirror

*   [Packagist Mirror (⭐198)](https://github.com/Webysther/packagist-mirror) - This script helps to setup a packagist mirror. It is the maintained and stable version of [Packagist Crawler (⭐57)](https://github.com/hirak/packagist-crawler).
*   [Docker Image (⭐27)](https://github.com/Webysther/packagist-mirror-docker) - This Docker image helps to create a customized packagist mirror.
*   [Packagist Mirror from Indonesia (⭐31)](https://github.com/IndraGunawan/packagist-mirror) - Another implementation for creating a packagist mirror.

### Packagist Mirrors

About metadata mirrors: <https://packagist.org/mirrors>

*   North America
    *   Canada - [packagist.org](https://packagist.org) *Main mirror*
*   South America
    *   Brazil - [packagist.com.br](https://packagist.com.br)
*   Africa
    *   South Africa - [packagist.co.za](https://packagist.co.za)
*   Asia
    *   China - <https://pkg.xyz/>, <https://developer.aliyun.com/composer>
    *   India - <https://packagist.in/>
    *   Japan - [packagist.jp](https://packagist.jp)
    *   Korea - <https://packagist.kr/>

## Composer Repositories

### Registry Manager

*   [https://github.com/slince/composer-registry-manager (⭐560)](https://github.com/slince/composer-registry-manager) - The plugin helps you to switch between different composer repositories.

### Private repositories

*   [fxpio/tug (⭐40)](https://github.com/fxpio/tug) - Enables you to host a private Composer registry on AWS Serverless serving your private PHP packages, which are hosted on GitHub or GitLab services.

### Private Packagist

*   [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories.
*   [Private Packagist Enterprise](https://packagist.com) - On-premise self-hosted version of Private Packagist.
*   [Private Packagist API Client (⭐33)](https://github.com/packagist/private-packagist-api-client) - A PHP client for the Private Packagist API. The client handles authentication, signature generation and access to all endpoints.

### Repman

*   [repman.io](https://repman.io) & [repman-io/repman (⭐531)](https://github.com/repman-io/repman) - A Private PHP Package Repository Manager & Packagist Proxy.
*   [repman-io/composer-plugin (⭐11)](https://github.com/repman-io/composer-plugin) - This plugin enables downloading via Repman by adding a distribution mirror URL for all your dependencies (without need to update the `composer.lock` file).

## Packagist-compatible repositories

*   [WordPress Packagist](https://wpackagist.org/) - Mirrors the WordPress plugin and theme directories as a Composer repository.
*   [Asset Packagist](https://asset-packagist.org/) - Enables installation of Bower and NPM packages as native Composer packages.
*   [Firegento](https://packages.firegento.com/) - A Composer Repository providing Magento Modules.
*   [Drupal Packagist](https://www.drupal.org/node/2822344) - Composer repositories for Drupal 7 and 8 core, modules, and themes.
*   [Satis Server (⭐113)](https://github.com/lukaszlach/satis-server) - This docker container provides a Satis Server and enables you to run a private, self-hosted Composer repository with support for Git, Mercurial, and Subversion, HTTP API, HTTPs support, webhook handler and scheduled builds.
*   [Cloudsmith](https://cloudsmith.com/) - A fully managed package management SaaS with PHP/Composer support (and many others).
*   [Release Belt (⭐173)](https://github.com/Rarst/release-belt) - Self–hosted Composer repository implementation to quickly integrate ZIP files of third party non–Composer releases.
*   [Packeton (⭐441)](https://github.com/vtsykun/packeton) - Private self-hosted Composer repository for vendors. Fork of packagist with adding support for authorization, customer users, groups, webhooks.

### Satis

*   [GitLab-Composer (⭐163)](https://github.com/wemakecustom/gitlab-composer) - This is a branch/tag indexer for GitLab repositories.
*   [Satisfy (⭐524)](https://github.com/project-satisfy/satisfy) - Satis composer repository manager with a Web UI.
*   [Satis Control Panel (⭐151)](https://github.com/realshadow/satis-control-panel) - A simple web UI for managing your Satis Repository with optional CI integration.
*   [Satis Go (⭐96)](https://github.com/benschw/satis-go) - A web server for managing Satis configuration and hosting the generated Composer repository.

### Toran Proxy

*   [ToranProxy](https://toranproxy.com/) (deprecated) - In addition to providing a composer repository ToranProxy acts as a proxy server for Packagist and GitHub.

***

## Copyright

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.

