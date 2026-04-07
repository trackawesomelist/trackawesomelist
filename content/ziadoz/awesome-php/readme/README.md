# Awesome Php Overview

A curated list of amazingly awesome PHP libraries, resources and shiny things.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/ziadoz/awesome-php/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 ziadoz/awesome-php](https://github.com/ziadoz/awesome-php) · ⭐ 32K · 🏷️ Programming Languages

[ [Daily](/content/ziadoz/awesome-php/README.md) / [Weekly](/content/ziadoz/awesome-php/week/README.md) / Overview ]

---

# Awesome PHP [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome PHP libraries, resources, and useful tools.

## Contributing and Collaborating

Please see [CONTRIBUTING (⭐32k)](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT (⭐32k)](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING (⭐32k)](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) for details.

## Table of Contents

*   [Awesome PHP](#awesome-php)
    *   [Composer Repositories](#composer-repositories)
    *   [Dependency Management](#dependency-management)
    *   [Dependency Management Extras](#dependency-management-extras)
    *   [Frameworks](#frameworks)
    *   [Framework Extras](#framework-extras)
    *   [Content Management Systems](#content-management-systems-cms)
    *   [Components](#components)
    *   [Micro Frameworks](#micro-frameworks)
    *   [Micro Framework Extras](#micro-framework-extras)
    *   [Routers](#routers)
    *   [Templating](#templating)
    *   [Static Site Generators](#static-site-generators)
    *   [HTTP](#http)
    *   [Scraping](#scraping)
    *   [Middlewares](#middlewares)
    *   [URL](#url)
    *   [Email](#email)
    *   [Files](#files)
    *   [Streams](#streams)
    *   [Dependency Injection](#dependency-injection)
    *   [Imagery](#imagery)
    *   [Testing](#testing)
    *   [Continuous Integration](#continuous-integration)
    *   [Documentation](#documentation)
    *   [Security](#security)
    *   [Passwords](#passwords)
    *   [Code Analysis](#code-analysis)
    *   [Code Quality](#code-quality)
    *   [Static Analysis](#static-analysis)
    *   [Architectural](#architectural)
    *   [Debugging and Profiling](#debugging-and-profiling)
    *   [Error Tracking and Monitoring Services](#error-tracking-and-monitoring-services)
    *   [Build Tools](#build-tools)
    *   [Task Runners](#task-runners)
    *   [Navigation](#navigation)
    *   [Asset Management](#asset-management)
    *   [Geolocation](#geolocation)
    *   [Date and Time](#date-and-time)
    *   [Event](#event)
    *   [Logging](#logging)
    *   [E-commerce](#e-commerce)
    *   [PDF](#pdf)
    *   [Office](#office)
    *   [Database](#database)
    *   [Migrations](#migrations)
    *   [NoSQL](#nosql)
    *   [Queue](#queue)
    *   [Search](#search)
    *   [Command Line](#command-line)
    *   [Authentication and Authorization](#authentication-and-authorization)
    *   [Markup and CSS](#markup-and-css)
    *   [JSON](#json)
    *   [Strings](#strings)
    *   [Numbers](#numbers)
    *   [Filtering, Sanitizing and Validation](#filtering-sanitizing-and-validation)
    *   [API](#api)
    *   [Caching and Locking](#caching-and-locking)
    *   [Data Structure and Storage](#data-structure-and-storage)
    *   [Notifications](#notifications)
    *   [Deployment](#deployment)
    *   [Internationalisation and Localisation](#internationalisation-and-localisation)
    *   [Serverless](#serverless)
    *   [Configuration](#configuration)
    *   [LLMs](#llms)
    *   [Third Party APIs](#third-party-apis)
    *   [Extensions](#extensions)
    *   [Miscellaneous](#miscellaneous)
*   [Software](#software)
    *   [PHP Installation](#php-installation)
    *   [Development Environment](#development-environment)
    *   [Virtual Machines](#virtual-machines)
    *   [Text Editors and IDEs](#text-editors-and-ides)
    *   [Web Applications](#web-applications)
    *   [Infrastructure](#infrastructure)
*   [Resources](#resources)
    *   [PHP Websites](#php-websites)
    *   [PHP Books](#php-books)
    *   [PHP Videos](#php-videos)
    *   [PHP Conferences](#php-conferences)
    *   [PHP Podcasts](#php-podcasts)
    *   [PHP Newsletters](#php-newsletters)
    *   [PHP Reading](#php-reading)
    *   [PHP Internals Reading](#php-internals-reading)

### Composer Repositories

*Composer Repositories.*

*   [Firegento](https://packages.firegento.com/) - Magento Module Composer Repository.
*   [Packagist](https://packagist.org/) - The PHP Package Repository.
*   [Packalyst](https://packalyst.com/) - The Laravel package repository.
*   [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
*   [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management

*Libraries for dependency and package management.*

*   [Composer](https://getcomposer.org/) - A package and dependency manager.
*   [Composer Installers](https://github.com/composer/installers) - A multi-framework Composer library installer.
*   [Phive](https://phar.io/) - A PHAR manager.
*   [Pickle (⭐1.7k)](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer.
*   [Pie (⭐1.8k)](https://github.com/php/pie) - The official PHP installer for extensions.

### Dependency Management Extras

*Extras related to dependency management.*

*   [Composer Merge Plugin (⭐999)](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several `composer.json` files.
*   [Composer Normalize (⭐1.1k)](https://github.com/ergebnis/composer-normalize) - A plugin for normalizing `composer.json` files.
*   [Composer Patches (⭐1.7k)](https://github.com/cweagans/composer-patches) - A plugin for Composer to apply patches.
*   [Composer Prefer Lowest Validator (⭐22)](https://github.com/dereuromark/composer-prefer-lowest) - A plugin to check if minimum dependencies can be installed and tested.
*   [Composer Require Checker (⭐991)](https://github.com/maglnet/ComposerRequireChecker) - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
*   [Composer Unused (⭐1.7k)](https://github.com/composer-unused/composer-unused) - A CLI Tool to scan for unused composer packages.
*   [Repman](https://repman.io) - A private PHP package repository manager and Packagist proxy.
*   [Satis (⭐3.3k)](https://github.com/composer/satis) - A static Composer repository generator.

### Frameworks

*Web development frameworks.*

*   [CakePHP](https://cakephp.org/) - A rapid application development framework.
*   [CodeIgniter](https://codeigniter.com/) - A powerful PHP framework with a very small footprint.
*   [Ecotone](https://docs.ecotone.tech/) - A Service Bus for PHP based on architectural principles of DDD CQRS and Event Sourcing.
*   [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
*   [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
*   [Nette](https://nette.org) - A web framework comprised of mature components.
*   [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
*   [Spiral](https://spiral.dev/) - A high-performance PHP/Go framework.
*   [Symfony](https://symfony.com/) - A set of reusable components and a web framework.
*   [Tempest (⭐2.2k)](https://github.com/tempestphp/tempest-framework) - A framework that gets out of your way.
*   [Yii2 (⭐14k)](https://github.com/yiisoft/yii2/) - A fast, secure, and efficient web framework.

### Framework Extras

*Extras related to web development frameworks.*

*   [CakePHP CRUD (⭐375)](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
*   [Filament PHP](https://filamentphp.com/) - A powerful open source UI framework for Laravel.
*   [Inertia.js](https://inertiajs.com/) - An adapter for building single-page applications using server-side routing and controllers, without a separate API.
*   [LaravelS (⭐3.9k)](https://github.com/hhxsv5/laravel-s) - An out-of-the-box adapter between Laravel/Lumen and Swoole.
*   [Livewire](https://livewire.laravel.com/) - Powerful, dynamic, front-end UIs without leaving PHP.

### Content Management Systems (CMS)

*Tools for managing digital content.*

*   [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium-sized business and non-profits (a fork of Drupal).
*   [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
*   [CraftCMS (⭐3.6k)](https://github.com/craftcms/cms) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
*   [Drupal](https://new.drupal.org/home) - An enterprise level CMS.
*   [Grav (⭐15k)](https://github.com/getgrav/grav) - A modern flat-file CMS.
*   [Joomla](https://www.joomla.org/) - Another leading CMS.
*   [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
*   [Magento (⭐12k)](https://github.com/magento/magento2) - A widely used open-source e-commerce platform.
*   [Moodle](https://moodle.org/) - An open-source learning platform.
*   [OctoberCMS](https://octobercms.com/) - A CMS built on Laravel.
*   [OpenMage (⭐913)](https://github.com/OpenMage/magento-lts) - Fork of EoL Magento 1 e-commerce platform.
*   [Pico CMS](https://picocms.org/) - A lightweight flat-file CMS.
*   [Silverstripe](https://www.silverstripe.org/) - A simple, flexible, and secure CMS.
*   [Statamic](https://statamic.com/) - A flat-file and Git-based CMS built on Laravel.
*   [Sulu](https://sulu.io/) - A user- and developer-friendly CMS built on the Symfony Framework.
*   [TYPO3](https://typo3.org) - An enterprise level CMS.
*   [WinterCMS](https://wintercms.com) - A community-maintained fork of OctoberCMS built on Laravel.
*   [WordPress (⭐21k)](https://github.com/WordPress/WordPress) - A blogging platform and CMS.

### Components

*Standalone components from web development frameworks and development groups.*

*   [Aura](https://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
*   [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
*   [Laminas Components](https://docs.laminas.dev/components/) - The components that make the Laminas Framework.
*   [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
*   [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
*   [Spatie Open Source](https://spatie.be/open-source) - A collection of open-source PHP and Laravel packages.
*   [Symfony Packages](https://symfony.com/packages) - Decoupled libraries for PHP applications.

### Micro Frameworks

*Micro frameworks and routers.*

*   [Laravel Zero](https://laravel-zero.com) - A micro-framework for console applications.
*   [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas.
*   [Minicli (⭐1.1k)](https://github.com/minicli/minicli) - Minimalist, dependency-free framework for building CLI-centric PHP applications.
*   [Silly (⭐931)](https://github.com/mnapoli/silly) - A micro-framework for CLI applications.
*   [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras

*Extras related to micro frameworks and routers.*

*   [Slim Skeleton (⭐1.6k)](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
*   [Slim PHP View (⭐273)](https://github.com/slimphp/PHP-View) - A simple PHP renderer for Slim.

### Routers

*Libraries for handling application routing.*

*   [Aura.Router (⭐502)](https://github.com/auraphp/Aura.Router) - A full-featured routing library.
*   [Fast Route (⭐5.3k)](https://github.com/nikic/FastRoute) - A fast routing library.
*   [Klein (⭐2.7k)](https://github.com/klein/klein.php) - A flexible router.
*   [Route (⭐663)](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.

### Templating

*Libraries and tools for templating and lexing.*

*   [Latte](https://latte.nette.org/) - The safest and truly intuitive templates for PHP.
*   [MtHaml (⭐357)](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
*   [Mustache (⭐3.3k)](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
*   [PHPTAL](https://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
*   [Plates](https://platesphp.com/) - A native PHP templating library.
*   [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
*   [Twig](https://twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators

*Tools for pre-processing content to generate web pages.*

*   [Cecil](https://cecil.app/) - A simple and powerful content-driven static site generator.
*   [Couscous](https://couscous.io) - A tool for converting Markdown documentation into websites.
*   [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
*   [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.

### HTTP

*Libraries for working with HTTP.*

*   [Buzz (⭐1.9k)](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
*   [Guzzle (⭐23k)](https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
*   [HTTPlug](https://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
*   [Nyholm PSR-7 (⭐1.3k)](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation. Very strict and very fast.
*   [PHP VCR](https://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
*   [Requests (⭐3.6k)](https://github.com/WordPress/Requests) - A simple HTTP library.
*   [Retrofit (⭐155)](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients.
*   [Saloon (⭐2.4k)](https://github.com/saloonphp/saloon) - A framework for building beautiful API integrations and SDKs.
*   [Symfony HTTP Client (⭐2k)](https://github.com/symfony/http-client) - A component to fetch HTTP resources synchronously or asynchronously.
*   [Laminas Diactoros (⭐543)](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP Message implementation.

### Scraping

*Libraries for scraping websites and detecting crawlers.*

*   [Chrome PHP (⭐2.6k)](https://github.com/chrome-php/chrome) - Instrument headless Chrome/Chromium instances from PHP.
*   [CrawlerDetect (⭐2.3k)](https://github.com/JayBizzle/Crawler-Detect) - A PHP class for detecting bots/crawlers/spiders via the user agent.
*   [DiDOM (⭐2.2k)](https://github.com/Imangazaliev/DiDOM) - A super-fast HTML scrapper and parser.
*   [Embed (⭐2.1k)](https://github.com/php-embed/Embed) - An information extractor from any web service or page.
*   [PHP Spider (⭐1.3k)](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider.
*   [Symfony Panther (⭐3.1k)](https://github.com/symfony/panther) - A browser testing and web crawling library for PHP and Symfony.

### Middlewares

*Libraries for building application using middlewares.*

*   [PSR-15 Middlewares (⭐412)](https://github.com/middlewares/psr15-middlewares) - Inspiring collection of handy middlewares.
*   [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.
*   [Laminas Stratigility (⭐57)](https://github.com/laminas/laminas-stratigility) - Middleware for PHP built on top of PSR-7.

### URL

*Libraries for parsing URLs.*

*   [PHP Domain Parser (⭐1.2k)](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
*   [sabre/uri (⭐293)](https://github.com/sabre-io/uri) - A functional URI manipulation library.
*   [Uri (⭐1.1k)](https://github.com/thephpleague/uri) - Another URL manipulation library.

### Email

*Libraries for sending and parsing email.*

*   [CssToInlineStyles (⭐5.8k)](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
*   [ddeboer/imap (⭐915)](https://github.com/ddeboer/imap) - Object-oriented, fully tested PHP IMAP library.
*   [Email Reply Parser (⭐650)](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
*   [Fetch (⭐506)](https://github.com/tedious/Fetch) - An IMAP library.
*   [Mautic (⭐9.4k)](https://github.com/mautic/mautic) - Email marketing automation.
*   [PHPMailer (⭐22k)](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
*   [Stampie (⭐294)](https://github.com/Stampie/Stampie) - A library for email services such as [SendGrid](https://www.twilio.com/en-us/sendgrid), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).
*   [Symfony Mailer (⭐1.6k)](https://github.com/symfony/mailer) - A powerful library for creating and sending emails.

### Files

*Libraries for file manipulation and MIME type detection.*

*   [CSV (⭐3.5k)](https://github.com/thephpleague/csv) - A CSV data manipulation library.
*   [Flysystem (⭐14k)](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems.
*   [Gaufrette (⭐2.5k)](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
*   [PHP FFmpeg (⭐5k)](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.
*   [UnifiedArchive (⭐279)](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.
*   [Parquet (⭐55)](https://github.com/flow-php/parquet) - PHP implementation of Parquet file format.

### Streams

*Libraries for working with streams.*

*   [ByteStream](https://amphp.org/byte-stream) - An asynchronous stream abstraction.

### Dependency Injection

*Libraries that implement the dependency injection design pattern.*

*   [Aura.Di (⭐352)](https://github.com/auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
*   [Acclimate (⭐219)](https://github.com/AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators.
*   [Auryn (⭐726)](https://github.com/rdlowrey/Auryn) - A recursive dependency injector.
*   [Container (⭐864)](https://github.com/thephpleague/container) - Another flexible dependency injection container.
*   [Disco (⭐139)](https://github.com/bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container.
*   [PHP-DI](https://php-di.org/) - A dependency injection container that supports autowiring.
*   [Pimple (⭐2.7k)](https://github.com/silexphp/Pimple) - A tiny dependency injection container.
*   [Symfony DI (⭐4.2k)](https://github.com/symfony/dependency-injection) - A dependency injection container component.

### Imagery

*Libraries for manipulating images.*

*   [Color Extractor (⭐1.3k)](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
*   [Glide (⭐2.6k)](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
*   [Image Hash (⭐2k)](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
*   [Image Optimizer (⭐912)](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
*   [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
*   [Intervention Image (⭐14k)](https://github.com/Intervention/image) - Another image manipulation library.
*   [PHP Image Workshop (⭐860)](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.
*   [PHP QR Code (⭐2.3k)](https://github.com/chillerlan/php-qrcode/) - QR Code generator and reader.

### Testing

*Libraries for testing codebases and generating test data.*

*   [Alice (⭐2.5k)](https://github.com/nelmio/alice) - An expressive fixture generation library.
*   [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
*   [Codeception (⭐4.9k)](https://github.com/Codeception/Codeception) - A full stack testing framework.
*   [Faker (⭐3.9k)](https://github.com/fakerphp/faker) - A fake data generator library.
*   [Foundry (⭐782)](https://github.com/zenstruck/foundry) - A fixture factory generation library for Doctrine.
*   [Infection (⭐2.2k)](https://github.com/infection/infection) - An AST-based PHP Mutation testing framework.
*   [Kahlan (⭐1.1k)](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
*   [Mink](https://mink.behat.org/en/latest/) - Web acceptance testing.
*   [Mockery (⭐11k)](https://github.com/mockery/mockery) - A mock object library for testing.
*   [Nette Tester (⭐483)](https://github.com/nette/tester) - A productive and enjoyable parallel unit testing framework.
*   [ParaTest (⭐2.5k)](https://github.com/paratestphp/paratest) - A parallel testing library for PHPUnit.
*   [Pest](https://pestphp.com/) - A testing framework with a focus on simplicity.
*   [Phake (⭐475)](https://github.com/phake/phake) - Another mock object library for testing.
*   [PHP-Mock (⭐369)](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
*   [PHP MySQL Engine (⭐560)](https://github.com/vimeo/php-mysql-engine) - A MySQL engine written in pure PHP.
*   [PHPSpec (⭐1.9k)](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
*   [PHPT](https://php.github.io/php-src/miscellaneous/writing-tests.html) - A test tool used by PHP itself.
*   [PHPUnit (⭐20k)](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
*   [PHPUnit Polyfills (⭐183)](https://github.com/Yoast/PHPUnit-Polyfills/) - Simplifies running PHPUnit tests on multiple PHPUnit versions.
*   [Prophecy (⭐8.5k)](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
*   [VFS Stream (⭐1.4k)](https://github.com/bovigo/vfsStream) - A virtual filesystem stream wrapper for testing.

### Continuous Integration

*Libraries and applications for continuous integration.*

*   [CircleCI](https://circleci.com) - A continuous integration platform.
*   [GitLab CI](https://about.gitlab.com/solutions/continuous-integration/) - A continuous integration platform.
*   [Jenkins](https://www.jenkins.io/) - A continuous integration platform with [PHP support](https://www.jenkins.io/solutions/php/).
*   [SemaphoreCI](https://semaphore.io/) - A continuous integration platform for open-source and private projects.
*   [Travis CI](https://www.travis-ci.com) - A continuous integration platform.
*   [Setup PHP (⭐3.2k)](https://github.com/shivammathur/setup-php) - A GitHub Action for PHP.

### Documentation

*Libraries for generating project documentation.*

*   [APIGen (⭐2.2k)](https://github.com/apigen/apigen) - Another API documentation generator.
*   [daux.io (⭐828)](https://github.com/dauxio/daux.io) - A documentation generator that uses Markdown files.
*   [phpDocumentor](https://phpdoc.org/) - A documentation generator.
*   [phpDox](https://phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation).
*   [Scramble (⭐2k)](https://github.com/dedoc/scramble) - Automatically generates OpenAPI documentation from your code without annotations.
*   [zircote/swagger-php (⭐5.3k)](https://github.com/zircote/swagger-php) - Generate OpenAPI documentation for your RESTful API.

### Security

*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

*   [AntiXSS (⭐705)](https://github.com/voku/anti-xss) - A library that tries to preventing Cross-Site Scripting (XSS) attacks by blacklisting.
*   [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium (⭐14k)](https://github.com/jedisct1/libsodium).
*   [Optimus (⭐1.3k)](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
*   [OWASP](https://owasp.org/) - Explore the world of cyber security.
*   [PHPGGC (⭐3.8k)](https://github.com/ambionics/phpggc) - A library of PHP unserializable payloads along with a tool to generate them.
*   [PHP Encryption (⭐3.9k)](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
*   [PHPSecLib (⭐5.6k)](https://github.com/phpseclib/phpseclib) - A pure PHP secure communications library.
*   [Roave Security Advisories (⭐2.9k)](https://github.com/Roave/SecurityAdvisories) - This package ensures that your application doesn't have installed dependencies with known security vulnerabilities.
*   [Secure Headers (⭐547)](https://github.com/BePsvPT/secure-headers) - A package that adds security related headers to HTTP response.
*   [SQLMap (⭐37k)](https://github.com/sqlmapproject/sqlmap) - An automatic SQL injection and database takeover tool.
*   [Zap (⭐15k)](https://github.com/zaproxy/zaproxy) - An integrated penetration testing tool for web applications.

### Passwords

*Libraries and tools for working with and storing passwords.*

*   [GenPhrase (⭐118)](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
*   [Password Validator (⭐142)](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
*   [Password-Generator (⭐303)](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
*   [phpass](https://www.openwall.com/phpass/) - A portable password hashing framework.
*   [Zxcvbn PHP (⭐868)](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.

### Code Analysis

*Libraries and tools for analysing, parsing and manipulating codebases.*

*   [Better Reflection (⭐1.2k)](https://github.com/Roave/BetterReflection) - An AST-based reflection library that allows analysis and manipulation of code.
*   [Bladestan (⭐363)](https://github.com/bladestan/bladestan) - A PHPStan extension for static analysis of Blade templates.
*   [Code Climate](https://codeclimate.com) - An automated code review.
*   [Editorconfig-Checker (⭐74)](https://github.com/editorconfig-checker/editorconfig-checker.php) - A command line utility which verifies that your files implement your `.editorconfig` rules.
*   [GrumPHP (⭐4.3k)](https://github.com/phpro/grumphp) - A PHP code-quality tool.
*   [PHP AST Viewer](https://php-ast-viewer.com/) - A tool for viewing the Abstract Syntax Tree of PHP code.
*   [PHP Magic Number Detector (⭐579)](https://github.com/povils/phpmnd) - A library that detects magic numbers in code.
*   [PHP Parser (⭐17k)](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
*   [PHP Semantic Versioning Checker (⭐434)](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
*   [Phpactor (⭐1.8k)](https://github.com/phpactor/phpactor) - PHP completion, refactoring and introspection tool.
*   [PHPQA (⭐561)](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
*   [Rector (⭐10k)](https://github.com/rectorphp/rector) - A tool to upgrade and refactor code.
*   [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code (⭐438)](https://github.com/scrutinizer-ci/php-analyzer).
*   [UBench (⭐563)](https://github.com/devster/ubench) - A simple micro-benchmark library.

### Code Quality

*Libraries for managing code quality, formatting and linting.*

*   [CaptainHook (⭐1.1k)](https://github.com/captainhook-git/captainhook) - An easy-to-use and flexible Git hook library.
*   [Laravel Pint (⭐3.1k)](https://github.com/laravel/pint) - A coding standards fixer library for Laravel.
*   [PHP CodeSniffer (⭐1.5k)](https://github.com/PHPCSStandards/PHP_CodeSniffer) - A library that detects and can auto-fix PHP, CSS and JS coding standard violations.
*   [PHP CS Fixer (⭐13k)](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) - A coding standards fixer library.
*   [PHP CS Fixer Configurator](https://mlocati.github.io/php-cs-fixer-configurator/) - A web application to help configure PHP CS Fixer rule sets.
*   [PHP Mess Detector (⭐2.4k)](https://github.com/phpmd/phpmd) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
*   [PHPCheckstyle (⭐166)](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.

### Static Analysis

*Libraries for performing static analysis of PHP code.*

*   [Dead Code Detector (⭐346)](https://github.com/shipmonk-rnd/dead-code-detector) - A PHPStan extension for finding unused PHP code.
*   [Deptrac (⭐1)](https://github.com/qossmic/deptrac) - A static analysis tool for enforcing dependency rules between architectural layers.
*   [Exakat (⭐378)](https://github.com/exakat/exakat) - A static analysis engine for PHP.
*   [Larastan (⭐6.4k)](https://github.com/larastan/larastan) - A PHPStan wrapper for Laravel that adds static analysis to Laravel projects.
*   [Mago (⭐3k)](https://github.com/carthage-software/mago) - A toolchain for PHP that aims to improve the developer experience.
*   [phan (⭐5.6k)](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
*   [PHP Architecture Tester (⭐1.2k)](https://github.com/carlosas/phpat) - Easy-to-use architecture testing tool for PHP.
*   [PHPCompatibility (⭐2.3k)](https://github.com/PHPCompatibility/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer.
*   [PHPDoc Parser (⭐1.5k)](https://github.com/phpstan/phpdoc-parser) - Next-gen phpDoc parser with support for intersection types and generics.
*   [PHP Metrics (⭐2.6k)](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
*   [PHPStan (⭐14k)](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool.
*   [Psalm (⭐5.8k)](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications.

### Architectural

*Libraries related to design patterns, programming approaches and ways to organize code.*

*   [Design Patterns PHP (⭐22k)](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
*   [Finite (⭐1.3k)](https://github.com/yohang/Finite) - A simple PHP finite state machine.
*   [Functional PHP (⭐2k)](https://github.com/lstrojny/functional-php) - A functional programming library.
*   [Iter (⭐1.1k)](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
*   [IterTools PHP (⭐149)](https://github.com/markrogoyski/itertools-php) - A library that provides functionality for working with iterable entities (similar to itertools library in Python).
*   [Pipeline (⭐1k)](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
*   [Porter (⭐613)](https://github.com/ScriptFUSION/Porter) - Data import abstraction library for consuming Web APIs and other data sources.
*   [RulerZ (⭐879)](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern.

### Debugging and Profiling

*Libraries and tools for debugging errors and profiling code.*

*   [APM](https://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
*   [Barbushin PHP Console (⭐1.3k)](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
*   [Kint (⭐2.8k)](https://github.com/kint-php/kint) - A debugging and profiling tool.
*   [LaraDumps (⭐1.3k)](https://github.com/laradumps/laradumps) - A debugging tool for Laravel with a dedicated desktop application.
*   [Metrics (⭐322)](https://github.com/beberlei/metrics) - A simple metrics API library.
*   [PCOV (⭐772)](https://github.com/krakjoe/pcov) - A self-contained code coverage compatible driver.
*   [PHP Console (⭐525)](https://github.com/Seldaek/php-console) - A web debugging console.
*   [PHP Debug Bar](https://php-debugbar.com/) - A debugging toolbar.
*   [PHPBench (⭐2k)](https://github.com/phpbench/phpbench) - A benchmarking framework.
*   [PHPSpy (⭐1.5k)](https://github.com/adsr/phpspy) - A low-overhead sampling profiler.
*   [Symfony VarDumper (⭐7.4k)](https://github.com/symfony/var-dumper) - A variable dumper component.
*   [Tracy (⭐1.8k)](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
*   [Trap (⭐261)](https://github.com/buggregator/trap) - An extended variable dumper with a web interface and IDE plugin.
*   [Whoops (⭐13k)](https://github.com/filp/whoops) - A pretty error-handling library.
*   [xDebug (⭐3.4k)](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
*   [XHProf (⭐2.6k)](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
*   [Z-Ray](https://www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Error Tracking and Monitoring Services

*Self-hosted or cloud-based application performance monitoring & error tracking tools*

*   [Blackfire](https://www.blackfire.io) - A low-overhead code profiler.
*   [Buggregator](https://buggregator.dev) - A debug server that aggregates var-dumps, profiling data, emails, logs and Sentry events.
*   [BugSnag](https://www.bugsnag.com/) - Error and Real User Monitoring.
*   [Honeybadger](https://www.honeybadger.io/) - Error Tracking & Application Monitoring for Developers.
*   [Rollbar](https://rollbar.com/) - Error Logging & Tracking Service for Software Teams.
*   [Sentry](https://sentry.io/welcome/) - Application Performance Monitoring & Error Tracking Software.
*   [Tideways](https://tideways.com/) - Monitoring and profiling tool.

### Build Tools

*Project build and automation tools.*

*   [Box (⭐1.3k)](https://github.com/box-project/box) - A utility to build PHAR files.
*   [PHPacker (⭐411)](https://github.com/phpacker/phpacker) - A PHAR builder that compiles PHP apps to standalone executables.
*   [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.
*   [RMT (⭐458)](https://github.com/liip/RMT) - A library for versioning and releasing software.

### Task Runners

*Libraries for automating and running tasks.*

*   [Jobby (⭐1k)](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
*   [Robo (⭐2.7k)](https://github.com/consolidation/Robo) - A PHP task runner with object-oriented configurations.

### Navigation

*Tools for building navigation structures.*

*   [KnpMenu (⭐1.4k)](https://github.com/KnpLabs/KnpMenu) - A menu library.
*   [Menu (⭐759)](https://github.com/spatie/menu) - A flexible menu library with a fluent interface.

### Asset Management

*Tools for managing, compressing and minifying website assets.*

*   [JShrink (⭐761)](https://github.com/tedious/JShrink) - A JavaScript minifier library.
*   [Laravel Mix (⭐5.2k)](https://github.com/laravel-mix/laravel-mix) - An elegant wrapper around Webpack for the 80% use case.
*   [Symfony Asset (⭐3.2k)](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets.
*   [Symfony Encore (⭐2.2k)](https://github.com/symfony/webpack-encore) - A simple but powerful API for processing and compiling assets built around Webpack.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

*   [Country List (⭐5.2k)](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
*   [GeoCoder](https://geocoder-php.org/) - A geocoding library.
*   [GeoJSON (⭐305)](https://github.com/jmikola/geojson) - A GeoJSON implementation.
*   [GeoTools (⭐1.4k)](https://github.com/thephpleague/geotools) - A library of geo-related tools.
*   [PHPGeo (⭐1.6k)](https://github.com/mjaschen/phpgeo) - A simple geo library.

### Date and Time

*Libraries for working with dates and times.*

*   [Business Time (⭐317)](https://github.com/kylekatarnls/business-time) - A Carbon extension for handling business hours and working days.
*   [CalendR (⭐465)](https://github.com/yohang/CalendR) - A calendar management library.
*   [Carbon (⭐17k)](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
*   [Chronos (⭐1.4k)](https://github.com/cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time.
*   [Moment.php (⭐969)](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.
*   [PHP RRule (⭐695)](https://github.com/rlanvin/php-rrule) - A library for working with recurring dates and times based on the iCalendar RRule spec.
*   [Yasumi (⭐1.1k)](https://github.com/azuyalabs/yasumi) - A library to help you calculate the dates and names of holidays.

### Event

*Libraries that are event-driven or implement non-blocking event loops.*

*   [Amp (⭐4.4k)](https://github.com/amphp/amp) - An event-driven non-blocking I/O library.
*   [Broadway (⭐1.5k)](https://github.com/broadway/broadway) - An event source and CQRS library.
*   [CakePHP Event (⭐22)](https://github.com/cakephp/event) - An event dispatcher library.
*   [Elephant.io (⭐135)](https://github.com/ElephantIO/elephant.io) - Yet another web socket library.
*   [Evenement (⭐1.3k)](https://github.com/igorw/evenement) - An event dispatcher library.
*   [Event (⭐1.6k)](https://github.com/thephpleague/event) - An event library with a focus on domain events.
*   [Fast CGI Client (⭐564)](https://github.com/hollodotme/fast-cgi-client) - A client to make synchronous/asynchronous requests through php-fpm socket.
*   [FrankenPHP](https://frankenphp.dev/) - A modern PHP app server written in Go.
*   [Pawl (⭐614)](https://github.com/ratchetphp/Pawl) - An asynchronous web socket client.
*   [Prooph Event Store (⭐548)](https://github.com/prooph/event-store) - An event source component to persist event messages.
*   [PHP Defer (⭐307)](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP.
*   [Ratchet (⭐6.4k)](https://github.com/ratchetphp/Ratchet) - A web socket library.
*   [ReactPHP (⭐9.1k)](https://github.com/reactphp/reactphp) - An event-driven non-blocking I/O library.
*   [RxPHP (⭐1.7k)](https://github.com/ReactiveX/RxPHP) - A reactive extension library.
*   [Swoole (⭐19k)](https://github.com/swoole/swoole-src) - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
*   [Workerman (⭐12k)](https://github.com/walkor/Workerman) - An event-driven non-blocking I/O library.

### Logging

*Libraries for generating and working with log files.*

*   [Monolog (⭐21k)](https://github.com/Seldaek/monolog) - A comprehensive logger.

### E-commerce

*Libraries and applications for taking payments and building online e-commerce stores.*

*   [Money (⭐4.8k)](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
*   [Brick Money (⭐1.9k)](https://github.com/brick/money) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
*   [OmniPay (⭐6k)](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
*   [Payum (⭐1.9k)](https://github.com/payum/payum) - A payment abstraction library.
*   [Shopsys Framework (⭐346)](https://github.com/shopsys/shopsys/) - An open source e-commerce platform for in-house development teams.
*   [Shopware (⭐3.3k)](https://github.com/shopware/shopware) - Highly customizable e-commerce software.
*   [Swap (⭐1.3k)](https://github.com/florianv/swap) - An exchange rates library.
*   [Sylius](https://sylius.com/) - An open source e-commerce solution.

### PDF

*Libraries and software for working with PDF files.*

*   [Browsershot (⭐5.2k)](https://github.com/spatie/browsershot) - Convert HTML to an image, PDF or string.
*   [Dompdf (⭐11k)](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
*   [Gotenberg (⭐367)](https://github.com/gotenberg/gotenberg-php) - A PHP client for interacting with Gotenberg.
*   [Snappy (⭐4.5k)](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
*   [TCPDF](https://tcpdf.org/) - An open source PHP class for generating PDF documents.

### Office

*Libraries for working with office suite documents.*

*   [PHPPowerPoint (⭐1.4k)](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
*   [PHPWord (⭐7.5k)](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
*   [PHPSpreadsheet (⭐14k)](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
*   [OpenSpout (⭐1.1k)](https://github.com/openspout/openspout) - A community driven fork of `box/spout`, a PHP library to read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way.

### Database

*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

*   [Atlas.Orm (⭐429)](https://github.com/atlasphp/Atlas.Orm) - A data mapper implementation for your persistence model in PHP.
*   [Aura.Sql (⭐563)](https://github.com/auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator.
*   [Aura.SqlQuery (⭐457)](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
*   [Baum (⭐2.2k)](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
*   [CakePHP ORM (⭐149)](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern.
*   [Cycle ORM (⭐1.3k)](https://github.com/cycle/orm) - PHP DataMapper, ORM.
*   [Doctrine Extensions (⭐4.1k)](https://github.com/doctrine-extensions/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
*   [Doctrine](https://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
*   [Laravel Eloquent (⭐2.8k)](https://github.com/illuminate/database) - A simple ORM.
*   [ProxyManager (⭐5k)](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
*   [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
*   [Slimdump (⭐187)](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL.
*   [Spot2 (⭐599)](https://github.com/spotorm/spot2) - A MySQL datamapper ORM.

### Migrations

*Libraries to help manage database schemas and migrations.*

*   [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.
*   [Phinx (⭐4.5k)](https://github.com/cakephp/phinx) - Another database migration library.
*   [PHPMig (⭐571)](https://github.com/davedevelopment/phpmig) - Another migration management library.
*   [Ruckusing (⭐503)](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

### NoSQL

*Libraries for working with "NoSQL" backends.*

*   [MongoDB (⭐921)](https://github.com/mongodb/mongo-php-driver) - MongoDB PHP Driver.
*   [MongoDB PHP Library (⭐1.6k)](https://github.com/mongodb/mongo-php-library) - The official high-level MongoDB PHP library built on top of the MongoDB PHP Driver.
*   [Predis (⭐7.8k)](https://github.com/predis/predis) - A feature-complete Redis library.

### Queue

*Libraries for working with event and task queues.*

*   [BunnyPHP (⭐741)](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
*   [Pheanstalk (⭐1.9k)](https://github.com/pheanstalk/pheanstalk) - A Beanstalkd client library.
*   [PHP AMQP (⭐4.6k)](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
*   [Tarantool Queue (⭐65)](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
*   [Thumper (⭐276)](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.
*   [Enqueue (⭐2.2k)](https://github.com/php-enqueue/enqueue-dev) - A message queue package for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.

### Search

*Libraries and software for indexing and performing search queries on data.*

*   [Elastica (⭐2.3k)](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
*   [ElasticSearch PHP (⭐5.3k)](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
*   [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
*   [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines.

### Command Line

*Libraries related to the command line.*

*   [Aura.Cli (⭐102)](https://github.com/auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
*   [CLI Menu (⭐1.9k)](https://github.com/php-school/cli-menu) - A library for building CLI menus.
*   [CLIFramework (⭐435)](https://github.com/c9s/CLIFramework) - A command-line framework that supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
*   [CLImate (⭐1.9k)](https://github.com/thephpleague/climate) - A library for outputting colors and special formatting.
*   [Commando (⭐803)](https://github.com/nategood/commando) - Another simple command line opt parser.
*   [Cron Expression (⭐4.9k)](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
*   [GetOpt (⭐342)](https://github.com/getopt-php/getopt-php) - A command line opt parser.
*   [GetOptionKit (⭐149)](https://github.com/c9s/GetOptionKit) - Another command line opt parser.
*   [PsySH (⭐9.8k)](https://github.com/bobthecow/psysh) - Another PHP REPL.
*   [ShellWrap (⭐738)](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.

### Authentication and Authorization

*Libraries for implementing user authentication and authorization.*

*   [Aura.Auth (⭐134)](https://github.com/auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters.
*   [SocialConnect Auth (⭐562)](https://github.com/socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
*   [Json Web Token (⭐7.5k)](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information.
*   [OAuth 1.0 Client (⭐998)](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
*   [OAuth 2.0 Client (⭐3.8k)](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.
*   [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
*   [OAuth2 Server](https://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
*   [Paseto (⭐3.4k)](https://github.com/paragonie/paseto) - Platform-Agnostic Security Tokens.
*   [PHP oAuthLib (⭐1.1k)](https://github.com/daviddesberg/PHPoAuthLib) - Another OAuth library.
*   [TwitterOAuth (⭐4.3k)](https://github.com/abraham/twitteroauth) - A Twitter OAuth library.

### Markup and CSS

*Libraries for working with markup and CSS formats.*

*   [Cebe Markdown (⭐1k)](https://github.com/cebe/markdown) - A fast and extensible Markdown parser.
*   [CommonMark PHP (⭐2.9k)](https://github.com/thephpleague/commonmark) - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
*   [Decoda (⭐192)](https://github.com/milesj/decoda) - A lightweight markup parser library.
*   [Djot (⭐22)](https://github.com/php-collective/djot-php) - A PHP parser for [Djot](https://djot.net/), a modern light markup language (successor of Markdown).
*   [Essence (⭐770)](https://github.com/essence/essence) - A library for extracting web media.
*   [Embera (⭐353)](https://github.com/mpratt/Embera) - An Oembed consumer library.
*   [HTML to Markdown (⭐1.9k)](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
*   [HTML5 PHP (⭐1.8k)](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
*   [Parsedown (⭐15k)](https://github.com/erusev/parsedown) - Another Markdown parser.
*   [PHP CSS Parser (⭐1.8k)](https://github.com/MyIntervals/PHP-CSS-Parser) - A Parser for CSS Files written in PHP.
*   [PHP Markdown (⭐3.5k)](https://github.com/michelf/php-markdown) - A Markdown parser.
*   [Shiki PHP (⭐305)](https://github.com/spatie/shiki-php) - A [Shiki (⭐13k)](https://github.com/shikijs/shiki) code highlighting package in PHP.
*   [VObject (⭐596)](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects.

### JSON

*Libraries for working with JSON.*

*   [JSON Lint (⭐1.3k)](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
*   [JSONMapper (⭐218)](https://github.com/JsonMapper/JsonMapper) - A library for mapping JSON to PHP objects.
*   [Lazy JSON (⭐254)](https://github.com/cerbero90/lazy-json) - A memory-efficient lazy parser for large JSON files.

### Strings

*Libraries for parsing and manipulating strings.*

*   [Agent (⭐4.8k)](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
*   [ANSI to HTML5 (⭐253)](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
*   [Color Jizz (⭐285)](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colors.
*   [Device Detector (⭐3.5k)](https://github.com/matomo-org/device-detector) - Another library for parsing user agent strings.
*   [Hyphenation (⭐54)](https://github.com/heiglandreas/Org_Heigl_Hyphenator) - Text hyphenation based on the TeX hyphenation algorithm.
*   [Jieba-PHP (⭐1.4k)](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
*   [Mobile-Detect (⭐11k)](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
*   [Patchwork UTF-8 (⭐79)](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
*   [Portable ASCII (⭐574)](https://github.com/voku/portable-ascii) - A library to convert strings to ASCII.
*   [Portable UTF-8 (⭐519)](https://github.com/voku/portable-utf8) - A string manipulation library with UTF-8 safe replacement methods.
*   [Slugify (⭐2.9k)](https://github.com/cocur/slugify) - A library to convert strings to slugs.
*   [SQL Formatter (⭐3.9k)](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
*   [Stringy (⭐178)](https://github.com/voku/Stringy) - A string manipulation library with multibyte support.
*   [Url highlight (⭐102)](https://github.com/vstelmakh/url-highlight) - A library for parsing URLs from text and converting them into clickable links.
*   [URLify (⭐673)](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
*   [UUID (⭐13k)](https://github.com/ramsey/uuid) - A library for generating UUIDs.

### Numbers

*Libraries for working with numbers.*

*   [Brick Math (⭐2.1k)](https://github.com/brick/math) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
*   [ByteUnits (⭐167)](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
*   [DecimalObject (⭐25)](https://github.com/php-collective/decimal-object) - A value object to handle decimals/floats easily and more precisely.
*   [IP (⭐257)](https://github.com/darsyn/ip) - An immutable value object for working with IPv4 and IPv6 addresses.
*   [PHP Conversion (⭐132)](https://github.com/cniska/php-conversion) - Another library for converting between units of measure.
*   [PHP Units of Measure (⭐22)](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
*   [MathPHP (⭐2.4k)](https://github.com/markrogoyski/math-php) - A math library for PHP.

### Filtering, Sanitizing and Validation

*Libraries for filtering, sanitizing and validating data.*

*   [Assert (⭐2.4k)](https://github.com/beberlei/assert) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
*   [Aura.Filter (⭐158)](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
*   [CakePHP Validation (⭐42)](https://github.com/cakephp/validation) - Another validation library.
*   [Filterus (⭐448)](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
*   [HTML Purifier (⭐3.4k)](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
*   [ISO-codes (⭐801)](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according to standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
*   [JSON Schema (⭐3.6k)](https://github.com/jsonrainbow/json-schema) - A [JSON Schema](https://json-schema.org/) validation library.
*   [LibPhoneNumber for PHP (⭐5k)](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
*   [MetaYaml (⭐103)](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
*   [Respect Validation (⭐5.9k)](https://github.com/Respect/Validation) - A simple validation library.
*   [Symfony HTML Sanitizer (⭐279)](https://github.com/symfony/html-sanitizer) - An HTML sanitizer library.
*   [Valitron (⭐1.6k)](https://github.com/vlucas/valitron) - Another validation library.
*   [Valinor (⭐1.5k)](https://github.com/CuyZ/Valinor) - A library for mapping to strongly typed value objects.
*   [Volan (⭐45)](https://github.com/serkin/Volan) - Another simplified validation library.

### API

*Libraries and web tools for developing APIs.*

*   [API Platform](https://api-platform.com) - Expose in minutes a hypermedia REST API that embraces JSON-LD, Hydra format.
*   [Laminas API Tool Skeleton (⭐53)](https://github.com/laminas-api-tools/api-tools-skeleton) - An API builder built with the Laminas Framework.
*   [HAL (⭐201)](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
*   [Hateoas (⭐1k)](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
*   [Jane (⭐677)](https://github.com/janephp/janephp/) - An OpenApi client generator with validation support.
*   [Negotiation (⭐1.4k)](https://github.com/willdurand/Negotiation) - A content negotiation library.
*   [Restler (⭐1.4k)](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
*   [PackageGenerator (⭐435)](https://github.com/WsdlToPhp/PackageGenerator) - Package Generator generates a PHP SDK from any WSDL.

### Caching and Locking

*Libraries for caching data and acquiring locks.*

*   [APIx Cache (⭐114)](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasizing cache tagging and indexing.
*   [CacheTool (⭐1.8k)](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
*   [CakePHP Cache (⭐49)](https://github.com/cakephp/cache) - A caching library.
*   [Doctrine Cache (⭐7.9k)](https://github.com/doctrine/cache) - A caching library.
*   [Metaphore (⭐100)](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect.
*   [Stash (⭐962)](https://github.com/tedious/Stash) - Another library for caching.
*   [Laminas Cache (⭐106)](https://github.com/laminas/laminas-cache) - Another caching library.
*   [Lock (⭐946)](https://github.com/php-lock/lock) - A lock library to provide exclusive execution.

### Data Structure and Storage

*Libraries that implement data structure or storage techniques.*

*   [CakePHP Collection (⭐89)](https://github.com/cakephp/collection) - A simple collections library.
*   [Fractal (⭐3.5k)](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output.
*   [JsonMapper (⭐1.6k)](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
*   [JSON Machine (⭐1.3k)](https://github.com/halaxa/json-machine) - Provides iteration over huge JSONs using simple `foreach`.
*   [msgpack.php (⭐406)](https://github.com/rybakit/msgpack.php) - A pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format.
*   [Serializer (⭐2.3k)](https://github.com/schmittjoh/serializer) - A library for serializing and de-serializing data.
*   [YaLinqo (⭐451)](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
*   [Laminas Serializer (⭐34)](https://github.com/laminas/laminas-serializer) - Another library for serialising and de-serialising data.

### Notifications

*Libraries for working with notification software.*

*   [JoliNotif (⭐1.4k)](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc).

### Deployment

*Libraries for project deployment.*

*   [Deployer (⭐11k)](https://github.com/deployphp/deployer) - A deployment tool.
*   [Envoy (⭐1.6k)](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.

### Internationalisation and Localisation

*Libraries for Internationalization (I18n) and Localization (L10n).*

*   [Aura.Intl (⭐89)](https://github.com/auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
*   [CakePHP I18n (⭐28)](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers.

### Serverless

*Libraries and tools to help build serverless web applications.*

*   [Bref](https://bref.sh/) - Serverless PHP on AWS Lambda.
*   [OpenWhisk](https://openwhisk.apache.org/) - An open-source serverless cloud platform.
*   [Serverless Framework](https://www.serverless.com/framework) - An open-source framework for building serverless applications.
*   [Laravel Vapor](https://vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

### Configuration

*Libraries and tools for configuration.*

*   [PHP Dotenv (⭐14k)](https://github.com/vlucas/phpdotenv) - Parse and load environment variables from `.env` files.
*   [Symfony Dotenv (⭐3.8k)](https://github.com/symfony/dotenv) - Parse and load environment variables from `.env` files.
*   [Toml (⭐0)](https://github.com/php-collective/toml) - A TOML parser and encoder with AST access and error recovery.

### LLMs

*Libraries for working with Large Language Models.*

*   [Anthropic (⭐46)](https://github.com/mozex/anthropic-php) - A PHP client for the Anthropic API, supporting messages, streaming, tool use, and batch processing.
*   [Anthropic for Laravel (⭐71)](https://github.com/mozex/anthropic-laravel) - A Laravel wrapper for the Anthropic PHP client with Facades, config publishing, and testing fakes.
*   [Instructor for PHP (⭐310)](https://github.com/cognesy/instructor-php) - Structured data outputs with LLMs, in PHP.
*   [LLPhant (⭐1.4k)](https://github.com/LLPhant/LLPhant) - A comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain.
*   [OpenAI Client (⭐5.8k)](https://github.com/openai-php/client) - OpenAI PHP is a supercharged community-maintained PHP API client that allows you to interact with OpenAI API.
*   [OpenAI Client for Laravel (⭐3.7k)](https://github.com/openai-php/laravel) - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API.
*   [PHP Mistral AI SDK (⭐15)](https://github.com/SoftCreatR/php-mistral-ai-sdk) - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects.

### Third Party APIs

*Libraries for accessing third party APIs.*

*   [Amazon Web Service SDK (⭐6.2k)](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
*   [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
*   [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
*   [Github (⭐2.2k)](https://github.com/KnpLabs/php-github-api) - A library to interface with the Github API.
*   [Mailgun (⭐1.1k)](https://github.com/mailgun/mailgun-php) - The official Mailgun PHP API.
*   [Stripe (⭐4k)](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
*   [Twilio (⭐1.6k)](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.

### Extensions

*Libraries to help build PHP extensions.*

*   [PHP CPP](https://www.php-cpp.com/) - A C++ library for developing PHP extensions.
*   [Zephir (⭐3.4k)](https://github.com/zephir-lang/zephir) - A compiled language between PHP and C++ for developing PHP extensions.

### Miscellaneous

*Useful libraries or utilities that don't fit into the categories above.*

*   [Annotations (⭐6.7k)](https://github.com/doctrine/annotations) - An annotation library (part of Doctrine).
*   [BotMan (⭐6.2k)](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chatbots.
*   [ClassPreloader (⭐376)](https://github.com/ClassPreloader/ClassPreloader) - A library for optimizing autoloading.
*   [Ganesha (⭐661)](https://github.com/ackintosh/ganesha) - A PHP implementation of Circuit Breaker pattern.
*   [Hprose-PHP (⭐2.1k)](https://github.com/hprose/hprose-php) - A cross-language RPC.
*   [Laravel Serializable Closure (⭐600)](https://github.com/laravel/serializable-closure) - A library that allows Closures to be serialized.
*   [noCAPTCHA (⭐366)](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
*   [Pagerfanta (⭐1.6k)](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
*   [Safe (⭐2.5k)](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false.

# Software

*Software for creating a development environment.*

### PHP Installation

*Tools to help install and manage PHP on your computer.*

*   [Brew PHP Switcher (⭐1k)](https://github.com/philcook/brew-php-switcher) - Brew PHP switcher.
*   [Homebrew](https://brew.sh/) - A package manager for macOS.
*   [PHP Brew (⭐5.5k)](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer.
*   [PHP Build (⭐1k)](https://github.com/php-build/php-build) - Another PHP version installer.
*   [Static PHP CLI (⭐1.8k)](https://github.com/crazywhalecc/static-php-cli) - Build or [download](https://dl.static-php.dev/static-php-cli/) static versions of PHP CLI and FPM.

### Development Environment

*Software and tools for creating and sharing a development environment.*

*   [Ansible](https://www.redhat.com/en/ansible-collaborative) - A radically simple orchestration framework.
*   [DDEV (⭐3.5k)](https://github.com/ddev/ddev) - A local web development environment system for PHP.
*   [Docker](https://www.docker.com/) - A containerization platform.
*   [Docker PHP Extension Installer (⭐4.9k)](https://github.com/mlocati/docker-php-extension-installer) - Easily install PHP extensions in Docker containers.
*   [Docksal (⭐716)](https://github.com/docksal/docksal) - Unified, Docker :whale: powered web development environments for macOS, Windows, and Linux.
*   [Expose (⭐4.5k)](https://github.com/exposedev/expose) - An open-source PHP tunneling service.
*   [Lando](https://lando.dev/) - Push-button development environments.
*   [Laravel Homestead](https://laravel.com/docs/master/homestead) - A local development environment for Laravel.
*   [Laravel Herd](https://herd.laravel.com/windows) - A one click PHP development environment for macOS and Windows.
*   [Laradock](https://laradock.io/) - A full PHP development environment based on Docker.
*   [PHPMon](https://phpmon.app/) - A macOS menu bar app for managing PHP installations (works with [Laravel Valet](https://laravel.com/docs/master/valet)).
*   [Puppet](https://www.puppet.com) - A server automation framework and application.
*   [Solo (⭐1.2k)](https://github.com/soloterm/solo) - A terminal application to manage processes for a Laravel application.
*   [Takeout (⭐1.6k)](https://github.com/tighten/takeout) - A Docker-based development-only dependency manager.
*   [Vagrant](https://developer.hashicorp.com/vagrant) - A portable development environment utility.

### Virtual Machines

*Alternative PHP virtual machines.*

*   [Hack](https://hacklang.org/) - A programming language for HHVM.
*   [HHVM (⭐19k)](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
*   [PeachPie (⭐2.5k)](https://github.com/peachpiecompiler/peachpie) - PHP compiler and runtime for .NET and .NET Core.

### Text Editors and IDEs

*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

*   [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
*   [Apache NetBeans](https://netbeans.apache.org/front/main/index.html) - An IDE with support for PHP and HTML5.
*   [PhpEd](https://www.nusphere.com/products/phped.htm) - An IDE with professional commercial debugger.
*   [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
*   [VS Code](https://code.visualstudio.com/) - An open source code editor.

### Web Applications

*Web-based applications and tools.*

*   [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
*   [Adminer](https://www.adminer.org/en/) - Database management in a single PHP file.
*   [Cachet (⭐15k)](https://github.com/cachethq/cachet) - The open source status page system.
*   [Lychee (⭐6.4k)](https://github.com/electerious/Lychee) - An easy to use and great looking photo-management-system.
*   [Leantime](https://leantime.io) - Strategic project management system for the non project manager.
*   [MailCatcher (⭐6.7k)](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
*   [Mailpit (⭐9k)](https://github.com/axllent/mailpit) - An email and SMTP testing tool for developers.
*   [phpMyAdmin (⭐7.8k)](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
*   [PHP Queue (⭐664)](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
*   [phpRedisAdmin (⭐3.2k)](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](https://redis.io/) databases.
*   [PHPSandbox](https://phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure

*Infrastructure for providing PHP applications and services.*

*   [appserver.io (⭐961)](https://github.com/appserver-io/appserver) - A multithreaded application server for PHP, written in PHP.
*   [php-pm (⭐6.6k)](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.
*   [RoadRunner (⭐8.4k)](https://github.com/roadrunner-server/roadrunner) - High-performance PHP application server, load-balancer and process manager.

# Resources

Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites

*Useful PHP-related websites.*

*   [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
*   [Laravel News](https://laravel-news.com/) - The official Laravel blog.
*   [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
*   [PHP FIG](https://www.php-fig.org/) - The PHP Framework Interoperability Group.
*   [PHP Package Development Standards](https://php-pds.com/) - Package development standards for PHP.
*   [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
*   [PHP The Right Way](https://phptherightway.com/) - A PHP best practice quick reference guide.
*   [PHP UG](https://php.ug) - A website to help people locate their nearest PHP user group (UG).
*   [PHP Watch](https://php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
*   [Unit Testing Tips](https://testing-tips.sarvendev.com/) - Unit Testing Tips by examples in PHP.

### PHP Books

*Fantastic PHP-related books.*

*   [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
*   [Functional Programming in PHP](https://www.functionalphp.com/) - A book on applying functional programming principles and techniques in PHP.
*   [Mastering Object-Orientated PHP](https://masteringobjectorientedphp.com/) - A book about object-orientated PHP by Brandon Savage.
*   [PHP Cookbook](https://www.oreilly.com/library/view/php-cookbook/9781098121310/) - This cookbook provides code recipes to help you resolve a variety of coding issues.
*   [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
*   [Scaling PHP Applications](https://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
*   [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
*   [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
*   [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos

*Fantastic PHP-related videos.*

*   [Laracasts](https://laracasts.com) - Screencasts about Laravel, Vue JS and more.
*   [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
*   [Program With Gio](https://www.youtube.com/playlist?list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-) - PHP 8 course by Gio.
*   [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
*   [SymfonyCasts](https://symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Conferences

*PHP conferences.*

*   [Laracon EU](https://www.youtube.com/@LaraconEU) - Laracon EU is a 2-day event for people who are interested in learning Laravel and related technologies, or who want to share their knowledge with others.
*   [PHP\[TEK\]](https://phptek.io/) - The longest-running web developer conference in the United States that has a focus on the PHP programming language.
*   [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.

### PHP Podcasts

*Podcasts with a focus on PHP topics.*

*   [Laravel News Podcast](https://podcast.laravel-news.com/) - The Laravel News Podcast brings you all the latest news and events related to the Laravel PHP Framework.
*   [Mostly Technical](https://mostlytechnical.com/) - Hosted by Ian Landsman and Aaron Francis, Mostly Technical is a lively discussion on Laravel, business, and an eclectic mix of related topics.
*   [No Compromises](https://show.nocompromises.io/) - Two seasoned salty programming veterans talk best practices based on years of working with Laravel SaaS teams.
*   [North Meets South Web Podcast](https://www.northmeetssouth.audio/) - Jacob Bennett and Michael Dyrynda conquer a 14.5 hour time difference to talk about life as web developers.
*   [Over Engineered](https://overengineered.fm/) - A podcast in mini-series where we explore unimportant programming questions in extreme detail.
*   [PHP Internals News](https://phpinternals.news) - A podcast about PHP internals.
*   [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
*   [php\[podcast\] episodes from php\[architect\]](https://www.phparch.com/podcast/) - The official podcast of php\[architect] the industry's leading tech magazine and publisher focused on PHP and web development.
*   [PHPUgly](https://www.phpugly.com/) - The ramblings of a few overworked PHP Developers.
*   [The Laracasts Snippet](https://laracasts.simplecast.com) - The Laracasts snippet, each episode, offers a single thought on some aspect of web development.
*   [The Laravel Podcast](https://laravelpodcast.com/) - Laravel and PHP development news and discussion.
*   [The PHP Roundtable](https://phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

### PHP Newsletters

*PHP-related news directly to your inbox.*

*   [PHP Weekly](https://www.phpweekly.com/) - A weekly newsletter about PHP.

### PHP Reading

*PHP-related reading materials.*

*   [php\[architect\]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### PHP Internals Reading

*Reading materials related to the PHP internals or performance.*

*   [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
*   [Externals](https://externals.io/) - PHP internal discussions.
*   [PHP RFC Watch (⭐127)](https://github.com/beberlei/php-rfc-watch) - Watch the latest PHP [RFCs](https://wiki.php.net/rfc).
*   [PHP Internals Book](https://www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.

