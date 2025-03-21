# Awesome Cakephp Overview

A curated list of amazingly awesome CakePHP plugins, resources and shiny things. 

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/FriendsOfCake/awesome-cakephp/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 FriendsOfCake/awesome-cakephp](https://github.com/FriendsOfCake/awesome-cakephp) · ⭐ 913 · 🏷️ Back-End Development

[ [Daily](/content/FriendsOfCake/awesome-cakephp/README.md) / [Weekly](/content/FriendsOfCake/awesome-cakephp/week/README.md) / Overview ]

---

# Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome **CakePHP 5.x+** plugins, resources and shiny things.

If you are looking for previous CakePHP resources please visit:

*   the [CakePHP 2.x version (⭐913)](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) of this awesome list
*   the [CakePHP 3.x version (⭐913)](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake3) of this awesome list
*   the [CakePHP 4.x version (⭐913)](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake4) of this awesome list
*   this wiki with a [list of not-yet upgraded plugins (⭐913)](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

Additional lists you might find useful:

*   [CakePHP Plugins](https://plugins.cakephp.org)
*   [Awesome PHP (⭐31k)](https://github.com/ziadoz/awesome-php)
*   [Awesome Awesomeness (⭐32k)](https://github.com/bayandin/awesome-awesomeness)

> For those wondering; this list differs from plugins.cakephp.org by supporting
> plugin subparts (instead of only the whole plugin/repo), more granular
> grouping and the primary focus on task-specific functionality.

## Table of Contents

*   [Plugins](#plugins)
    *   [APM](#apm)
    *   [Architecture](#architecture)
    *   [Asset Management](#asset-management)
    *   [Auditing / Logging](#auditing--logging)
    *   [Authentication and Authorization](#authentication-and-authorization)
    *   [Caching](#caching)
    *   [Code Analysis](#code-analysis)
    *   [Debugging](#debugging)
    *   [Email](#email)
    *   [File Manipulation](#file-manipulation)
    *   [Filtering and Validation](#filtering-and-validation)
    *   [Geolocation](#geolocation)
    *   [I18n](#i18n)
    *   [Imagery](#imagery)
    *   [Libs](#libs)
    *   [Markup](#markup)
    *   [Migration](#migration)
    *   [Miscellaneous](#miscellaneous)
    *   [Navigation](#navigation)
    *   [NoSQL](#nosql)
    *   [Notifications](#notifications)
    *   [ORM / Database / Datamapping](#orm--database--datamapping)
    *   [PDF](#pdf)
    *   [Queue](#queue)
    *   [REST and API](#rest-and-api)
    *   [Search](#search)
    *   [Security](#security)
    *   [SEO](#seo)
    *   [Skeleton](#skeleton)
    *   [Social](#social)
    *   [Templating](#templating)
    *   [Testing](#testing)
    *   [Third Party APIs](#third-party-apis)
*   [Software](#software)
    *   [Development Environment](#development-environment)
*   [Web Applications](#web-applications)
    *   [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
    *   [Demo](#demo)
*   [Resources](#resources)
    *   [Help](#help)
    *   [CakePHP Websites](#cakephp-websites)
    *   [CakePHP Books and Articles](#cakephp-books-and-articles)
    *   [CakePHP Videos](#cakephp-videos)
    *   [CakePHP Tutorials](#cakephp-tutorials)
    *   [CakePHP Reading and Listening](#cakephp-reading-and-listening)
    *   [CakePHP Internals Reading](#cakephp-internals-reading)
*   [Conferences](#conferences)
*   [Contributing](#contributing)

# Plugins

## APM

*Plugins for Application Performance Monitoring.*

## Architecture

*   [Burzum/CakeServiceLayer plugin (⭐67)](https://github.com/burzum/cakephp-service-layer) - Service layer and domain/business model implementation.

## Asset Management

*Tools for managing, compressing and minifying website assets.*

*   [AssetCompress plugin (⭐371)](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
*   [AssetMix plugin (⭐33)](https://github.com/ishanvyas22/asset-mix) - Provides integration with [Laravel Mix](https://laravel-mix.com) asset compilation.

## Auditing / Logging

*Plugins for auditing and logging.*

*   [AuditStash plugin (⭐79)](https://github.com/lorenzo/audit-stash) - Flexible and rock solid audit log tracking.
*   [DatabaseLog plugin (⭐44)](https://github.com/dereuromark/CakePHP-DatabaseLog) - Simple and stand-alone logging to database instead of files.
*   [Muffin/Footprint plugin (⭐95)](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer.
*   [Version plugin (⭐50)](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities.

## Authentication and Authorization

*Plugins and libraries for implementing authentication and authorization.*

*   [ADmad/SocialAuth plugin (⭐51)](https://github.com/ADmad/cakephp-social-auth) - A plugin which allows you to authenticate using social providers like Facebook/Google/Twitter etc. using [SocialConnect/auth (⭐554)](https://github.com/SocialConnect/auth) social sign on library.
*   [ApiTokenAuthenticator plugin (⭐3)](https://github.com/rrd108/api-token-authenticator) - A simple token authentication plugin for CakePHP REST APIs.
*   [Authentication plugin (⭐116)](https://github.com/cakephp/authentication) - Official CakePHP authentication middleware plugin.
*   [Authorization plugin (⭐75)](https://github.com/cakephp/authorization) - Official CakePHP authorization stack.
*   [CakeDC/Users plugin (⭐525)](https://github.com/CakeDC/users) - Complete user management (admin panel, remember me, etc), Social login (FB, Twitter, LinkedIn, Google, Instagram), RBAC, API and more.
*   [TinyAuth plugin (⭐129)](https://github.com/dereuromark/cakephp-tinyauth) - Authentication and role-based (single/multi) authorization as very light-weight approach.
*   [Tools:Passwordable (⭐335)](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior (⭐335)](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) for a DRY approach on password hashing.
*   [TwoFactorAuth plugin (⭐37)](https://github.com/andrej-griniuk/cakephp-two-factor-auth) - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth (⭐1.1k)](https://github.com/RobThree/TwoFactorAuth) library.

## Caching

*Plugins for caching data.*

*   [Cache plugin (⭐33)](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.
*   [CakeDC/CachedRouting plugin (⭐4)](https://github.com/CakeDC/cakephp-cached-routing) - Provides a cached version of the RoutingMiddleware to improve the load time of routes.

## Code Analysis

*Plugins for analyzing, parsing and manipulation codebases.*

*   [cakedc/cakephp-phpstan (⭐38)](https://github.com/CakeDC/cakephp-phpstan) - A PHPStan extension to resolve CakePHP magic around getter return types for the static analyzer.
*   [IdeHelper plugin (⭐186)](https://github.com/dereuromark/cakephp-ide-helper) - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code.
*   [IdeHelperExtra plugin (⭐2)](https://github.com/dereuromark/cakephp-ide-helper-extra) - Useful IdeHelper addons for other plugins or custom use cases.
*   [lordsimal/cakephp-psalm (⭐2)](https://github.com/LordSimal/cakephp-psalm) - A Psalm extension to resolve CakePHP magic around getter return types for the static analyzer.
*   [TestHelper plugin (⭐7)](https://github.com/dereuromark/cakephp-test-helper) - Provides testing enhancements and TDD support as browser backend.

## Debugging

*Plugins for debugging and local development.*

*   [AssociationsDebugger plugin (⭐11)](https://github.com/zunnu/associations-debugger) - A plugin that draws your model associations as diagram.
*   [CakephpWhoops plugin (⭐14)](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops (⭐13k)](https://github.com/filp/whoops).
*   [DebugKit plugin (⭐847)](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
*   [Execution order (⭐21)](https://github.com/dereuromark/executionorder) - A demo app to display the execution order of files, methods and callbacks.
*   [Sentry plugin (⭐10)](https://github.com/lordsimal/cakephp-sentry) A plugin to seamlessly integrate Sentry for errors and exceptions.
*   [Setup plugin (⭐34)](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools.

## Email

*Plugins for sending and parsing email.*

*   [Queue plugin (⭐306)](https://github.com/dereuromark/cakephp-queue) - A dependency-free queue-based mail solution using Mailer/Email class, allowing re-queue on (network) failure.
*   [SendGrid plugin (⭐5)](https://github.com/sprintcube/cakephp-sendgrid) - Email transport plugin for sending email via SendGrid API.

## File Manipulation

*Plugins for file manipulation.*

*   [FileStorage plugin (⭐4)](https://github.com/dereuromark/cakephp-file-storage) - Flexible file storage and upload plugin.
*   [Josegonzalez/Upload plugin (⭐551)](https://github.com/FriendsOfCake/cakephp-upload) - A customisable plugin that uses [Flysystem](https://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.).

## Filtering and Validation

*Plugins for filtering and validating data.*

*   see Cake/Localized below.

## Geolocation

*Plugins for geocoding addresses and working with latitudes and longitudes.*

*   [Geo plugin (⭐49)](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## I18n

*Plugins for I18n (Internationalization) and L10n (Localization).*

*   [ADmad/I18n plugin (⭐44)](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools.
*   [Cake/Localized plugin (⭐211)](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.

## Imagery

*Plugins for manipulating images.*

*   [ADmad/Glide plugin (⭐34)](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](https://glide.thephpleague.com/) image manipulation library.
*   [QrCodePlugin (⭐9)](https://github.com/dereuromark/cakephp-qrcode/) - Easily render SVG/PNG QR Codes for your app.

## Libs

*Useful libraries or tools that don't fit in any of the other categories.*

*   [Chronos (⭐1.4k)](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
*   [Composer Installers (⭐1.4k)](https://github.com/composer/installers) - A multi framework Composer library installer.
*   [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
*   [Graphviz (⭐73)](https://github.com/alexandresalome/graphviz) - A Graphviz library.
*   [Rocketeer (⭐2.7k)](https://github.com/rocketeers/rocketeer) - PHP task runner and deployment package.

## Markup

*Plugins for working with markup.*

*   [Markup plugin (⭐3)](https://github.com/dereuromark/cakephp-markup) - Allows to use PHP or JS based syntax highlighting.

## Migration

*Plugins and resources around migration and upgrading.*

*   [Migrations plugin (⭐137)](https://github.com/cakephp/migrations) - (DB) Migration plugin.
*   [Upgrade app (⭐110)](https://github.com/cakephp/upgrade) - Official upgrade app for 3.x=>4.x and 4.x=>5.x.
*   [Upgrade app (extended) (⭐24)](https://github.com/dereuromark/upgrade) - An extended upgrade app for 3.x=>4.x and some 5.x snippets.
*   [Upgrade/Migration Guide](https://book.cakephp.org/5/en/appendices.html) - Official migration guide.

## Miscellaneous

*Misc plugins and libraries.*

*   [Ajax plugin (⭐56)](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests.
*   [CakeDC/Enum plugin (⭐30)](https://github.com/CakeDC/enum) - A plugin to add enumeration list support to your app.
*   [CakeDto plugin (⭐24)](https://github.com/dereuromark/cakephp-dto) - Quickly generate useful data transfer objects for your app (mutable/immutable), replacing messy arrays and leveraging your IDE through typehinting and autocomplete.
*   [Calendar plugin (⭐16)](https://github.com/dereuromark/cakephp-calendar) - For generating basic calendars. Includes IcalView for ICS calendar file generation.
*   [Feedback plugin (⭐6)](https://github.com/dereuromark/cakephp-feedback) - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form.
*   [Flash plugin (⭐12)](https://github.com/dereuromark/cakephp-flash) - More powerful flash messages for your application.
*   [Inertia plugin (⭐10)](https://github.com/CakeDC/cakephp-inertia) - Plugin for connecting a Vue 3 app and use an API interface using a middleware.
*   [OPCache Preloader (⭐11)](https://github.com/cnizzardini/cakephp-preloader) - An OPCache Preloader for CakePHP applications.
*   [Setup:Maintenance (⭐34)](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
*   [Shim plugin (⭐37)](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
*   [Tools plugin (⭐335)](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells and more.

## Navigation

*Tools for building navigation structures.*

*   [Icings/Menu plugin (⭐12)](https://github.com/icings/menu) - A [KnpMenu (⭐1.4k)](https://github.com/KnpLabs/KnpMenu) seasoned menu plugin for CakePHP.

## NoSQL

*Plugins for working with "NoSQL" backends.*

## Notifications

*Plugins for working with notification software.*

## ORM / Database / Datamapping

*Plugins that implement object-relational mapping or data-mapping techniques.*

*   [ADmad/Sequence plugin (⭐44)](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records.
*   [CakeDecimal plugin (⭐8)](https://github.com/dereuromark/cakephp-decimal) - A value object approach on handling decimals.
*   [Duplicatable plugin (⭐52)](https://github.com/riesenia/cakephp-duplicatable) - Behavior for duplicating entities including related data.
*   [Lampager/Cake plugin (⭐5)](https://github.com/lampager/lampager-cakephp) - Rapid pagination without using OFFSET.
*   [Muffin/Orderly plugin (⭐22)](https://github.com/usemuffin/orderly) - Allows setting default order for your tables.
*   [Muffin/Trash plugin (⭐85)](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP.
*   [Itosho/EasyQuery plugin (⭐26)](https://github.com/itosho/easy-query) - Behavior for easily generating some complicated queries like (bulk) insert/upsert etc.
*   [Icings/Partitionable plugin (⭐16)](https://github.com/icings/partitionable) - Partitionable associations allowing for basic limiting per group.

## PDF

*Plugins and software for working with PDF files.*

*   [CakePdf plugin (⭐375)](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## Queue

*Plugins for working with event and task queues.*

*   [Queue plugin (⭐36)](https://github.com/cakephp/queue) - CakePHP core queue system for the [php-queue](https://php-enqueue.github.io) queue library.
*   [Queue plugin (⭐306)](https://github.com/dereuromark/cakephp-queue) - A minimal and dependency-free queue solution.
*   [QueueScheduler plugin (⭐6)](https://github.com/dereuromark/cakephp-queue-scheduler) - A dependency-free crontab-like scheduler as DB driven solution and addon to Queue (dereuromark) plugin.

## REST and API

*Plugins and web tools for developing REST-ful APIs.*

*   [CRUD plugin (⭐374)](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production-ready code.
*   [CakeDC/Api plugin (⭐61)](https://github.com/CakeDC/cakephp-api) - All-in-one solution to provide a complete API. It includes versioning, renderers, CRUD, authentication, extensions (paginate, filter, HATEOAS), and much more.
*   [FractalTransformerView plugin (⭐19)](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - A plugin which allows using [Fractal transformers](https://fractal.thephpleague.com/transformers/) for your API output.
*   [MixerApi](https://mixerapi.com) - Streamline development of modern RESTful APIs for your team's CakePHP project.
*   [SwaggerBake plugin (⭐60)](https://github.com/cnizzardini/cakephp-swagger-bake) - This plugin automatically builds OpenAPI from your existing models and routes for display in Swagger and Redoc.

## Search

*Plugins and software for indexing and performing search queries on data.*

*   [Cake/ElasticSearch plugin (⭐85)](https://github.com/cakephp/elastic-search) - Alternative ORM using [Elasticsearch](https://www.elastic.co/) as its backend.
*   [CakeDC/SearchFilter plugin (⭐0)](https://github.com/CakeDC/search-filter) - Powerful and flexible solution for implementing advanced search functionality. Provides a robust set of tools for creating dynamic, user-friendly search interfaces with minimal effort.
*   [PlumSearch plugin (⭐19)](https://github.com/skie/plum_search) - Implements custom, flexible and extendable search strategies. Implements PRG pattern.
*   [Search plugin (⭐171)](https://github.com/FriendsOfCake/search) - Provides easy searching/filtering for paginated views using PRG pattern.
*   [Tags plugin (⭐15)](https://github.com/dereuromark/cakephp-tags) - For tagging and finding tagged records.

## Security

*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

*   [Captcha plugin (⭐10)](https://github.com/dereuromark/cakephp-captcha) - Simple, unobtrusive and extendable captcha solution providing by default an image based math captcha.
*   [Expose plugin (⭐9)](https://github.com/dereuromark/cakephp-expose) - Expose entities through additional UUIDs instead of their AIID primary keys to obfuscate those IDs and data associated with these numerically ordered values.
*   [Muffin/Obfuscate plugin (⭐36)](https://github.com/usemuffin/obfuscate) - Primary key obfuscation/shortening using UUIDs, HashIds, Optimus, Tiny and/or custom obfuscation strategies.
*   [Muffin/Throttle plugin (⭐63)](https://github.com/usemuffin/throttle) - A plugin for rate limiting (API) requests.
*   [Recaptcha plugin (⭐21)](https://github.com/ctlabvn/Recaptcha) - Simple, lightweight Google Recaptcha v2.

## SEO

*Search Engine Optimization.*

*   [Muffin/Slug plugin (⭐35)](https://github.com/UseMuffin/Slug) - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.
*   [Tools:Slugged (⭐335)](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.

## Skeleton

*Plugins and repositories around app skeletons.*

*   [App template (⭐372)](https://github.com/cakephp/app) - An empty CakePHP project for use with composer.
*   [BS flavored App template (⭐2)](https://github.com/dereuromark/cakephp-app) - An empty CakePHP project with BS5 and FontAwesome out of the box.

## Social

*Plugins around social features.*

*   [Comments plugin (⭐2)](https://github.com/dereuromark/cakephp-comments) - Allows users to comment records, supporting different formats.
*   [Favorites plugin (⭐3)](https://github.com/dereuromark/cakephp-favorites) - Allows users to star/like/favor records.
*   [Ratings plugin (⭐9)](https://github.com/dereuromark/cakephp-ratings) - Allows users to rate records and displays ratings.

## Templating

*Plugins for templating and lexing.*

*   [Bake plugin (⭐111)](https://github.com/cakephp/bake) - Provides code generation functionality.
*   [BootstrapUI plugin (⭐344)](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 4/5 integration.
*   [CsvView plugin (⭐176)](https://github.com/FriendsOfCake/cakephp-csvview) - A view class to easily generate CSV.
*   [Feed plugin (⭐13)](https://github.com/dereuromark/cakephp-feed) - Containing an RssView class to easily generate (complex) RSS feeds.
*   [Meta plugin (⭐8)](https://github.com/dereuromark/cakephp-meta) - Makes handling meta tags and SEO-relevant HTML markup DRY and easy.
*   [Templating (⭐2)](https://github.com/dereuromark/cakephp-templating) - HTML snippets as value objects, (Font) icons, and templating topics.
*   [Tools:Tree (⭐335)](https://github.com/dereuromark/cakephp-tools) - Tree helper to work with Core Tree behavior and handle tree structure output.
*   [TwigView plugin (⭐14)](https://github.com/cakephp/twig-view) - A plugin to use the Twig Templating Language for views.
*   [XlsView plugin (⭐0)](https://github.com/impronta48/cakephp-xlsview) - A view class to easily generate XLS using PHPSpreadsheet.

## Testing

*Plugins/Tools for testing codebases and generating test data.*

*   [CakePHP CodeSniffer rules (⭐236)](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
*   [CakephpFixtureFactories plugin (⭐85)](https://github.com/pakacuda/cakephp-fixture-factories) - Create your fixtures dynamically on a test basis, accelerate the writing and maintenance of your tests.
*   [FriendsOfCake/Fixturize plugin (⭐24)](https://github.com/FriendsOfCake/fixturize) - More efficient inserting fixtures when running test suites by decreasing amount of inserts (mysql only).

## Third Party APIs

*Plugins for accessing third party APIs.*

# Software

*Software for creating a development environment.*

## Development Environment

*Software and tools for creating a sandboxed development environment.*

*   [CakePHP Docker (⭐29)](https://github.com/cnizzardini/cakephp-docker) - A cakephp/app template for docker.
*   [CakePHP Vagrant Setup (⭐5)](https://github.com/cpierce/cakephp-vagrant-setup) - Tool for spinning up multiple CakePHP vanilla dev environments.
*   [DDEV](https://ddev.readthedocs.io/en/stable/) - Docker based local env.
*   [Devilbox](https://devilbox.readthedocs.io/en/latest/) - A docker development environment for (CakePHP) apps to be auto-setup including a lot of tools.
*   [Docker (⭐31)](https://github.com/stefanvangastel/docker-cakephp) - CakePHP in a docker container environment.
*   [Galley](https://gitlab.com/amayer5125/galley) - A small Docker dev environment for CakePHP development which includes a simple command line utility.
*   [NetBeans (⭐46)](https://github.com/junichi11/cakephp3-netbeans) -  This package provides support for CakePHP in NetBeans 8.1+.
*   [Oven (⭐141)](https://github.com/CakeDC/oven) - Setup your favorite framework with 1 file and 1 click.
*   [Puppet](https://puppetlabs.com/) - A server automation framework and application.
*   [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

IDE specific compatibility information and tips can be found [here (⭐186)](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips).

## Web Applications

## CMS and applications built on CakePHP

*   [baserCMS (⭐178)](https://github.com/baserproject/basercms) - This is a website development framework with RESTful APIs. Installable as a plugin for CakePHP.

## Demo

*Web-based (demo) applications and tools.*

*   [BlogMVC (⭐8)](https://github.com/Kareylo/BlogMVC-CakePHP3) - A simple Blog example with CakePHP based on [BlogMVC Project (⭐214)](https://github.com/Grafikart/BlogMVC).
*   [Bookmarkr (⭐17)](https://github.com/lorenzo/cakephp3-bookmarkr) A bookmarking application built with the CRUD plugin.
*   [Fluentd + Grafana Loki demo application (⭐1)](https://github.com/ishanvyas22/cakephp-loki-demo) - A demo application to send CakePHP docker container logs to [Grafana Loki](https://grafana.com/logs/) via [Fluentd](https://www.fluentd.org/).
*   [RealWorld (⭐104)](https://github.com/gothinkster/cakephp-realworld-example-app) - Example CakePHP codebase containing real world examples (CRUD, auth, advanced patterns and more) that adheres to the [RealWorld (⭐81k)](https://github.com/gothinkster/realworld-example-apps) spec and API.
*   [Sandbox](https://sandbox.dereuromark.de) - A sandbox CakePHP application with lots of demos and plugin showcasings.
*   [Query Examples (⭐56)](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
*   [Xeta (⭐52)](https://github.com/XetaIO/Xeta) - A resource to help people starting with CakePHP.
*   [Vue.js Demo App (⭐49)](https://github.com/ishanvyas22/cakephpvue-spa) - A CakePHP + VueJS single page application skeleton.

# Resources

Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help

*Where to get help.*

*   [Official CakePHP Forum](https://discourse.cakephp.org/) - This is for generic questions and alike.
*   [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.

## CakePHP Websites

*Useful and current CakePHP-related websites and blogs.*

*   [CakeDC](https://www.cakedc.com/articles) - Articles around CakePHP.
*   [dereuromark.de](https://www.dereuromark.de) - An extensive CakePHP core dev blog.
*   [josediazgonzalez.com](https://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
*   [mark-story.com](https://mark-story.com) - CakePHP lead dev blog.

## CakePHP Books and Articles

*Fantastic CakePHP-related (e)books and other reading material.*

## CakePHP Videos

*Fantastic CakePHP-related videos.*

*   [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.

## CakePHP Tutorials

*Must-do tutorials.*

*   [Official Content Management Tutorial](https://book.cakephp.org/5/en/tutorials-and-examples/cms/installation.html)

## CakePHP Reading and Listening

*Documentation and CakePHP-related reading and listening materials.*

*   [CakePHP Cookbook(!)](https://book.cakephp.org/) - The official CakePHP documentation.

## CakePHP Internals Reading

*Reading materials related to the CakePHP internals and decisions.*

*   [Top 10 (and more) core contributors (⭐8.7k)](https://github.com/cakephp/cakephp/graphs/contributors) - Give 'em a hand.

# Conferences

## Official

*International conference.*

*   [cakefest.org](https://cakefest.org/) - Annual CakePHP Conference.

## MeetUps

*Regional meet-ups.*

*   [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - MeetUps in Germany.

# Contributing

Please see [CONTRIBUTING](https://github.com/FriendsOfCake/awesome-cakephp/blob/master/README.md/CONTRIBUTING.md) for details.

## Credits

awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors (⭐913)](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors), too.

