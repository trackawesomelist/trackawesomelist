# Awesome Django Overview

A curated list of awesome things related to Django

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/wsvincent/awesome-django/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 wsvincent/awesome-django](https://github.com/wsvincent/awesome-django) · ⭐ 9.3K · 🏷️ Programming Languages

[ [Daily](/content/wsvincent/awesome-django/README.md) / [Weekly](/content/wsvincent/awesome-django/week/README.md) / Overview ]

---

# Awesome Django [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

<a class="github-fork-ribbon right-top" href="https://github.com/wsvincent/awesome-django" data-ribbon="Fork me on GitHub" title="Fork me on GitHub">Fork me on GitHub</a>

> A curated list of awesome things related to Django. Maintained by [William Vincent](https://github.com/wsvincent) and [Jeff Triplett](https://github.com/jefftriplett).

<br>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/django-logo-negative.svg">
  <img alt="Dark and Light mode version of the Django logo" src="https://github.com/wsvincent/awesome-django/raw/main/./assets/django-logo-positive.svg">
</picture>
</div>

<br>

Please consider supporting Django by making a donation to the <a rel="sponsored" href="https://www.djangoproject.com/fundraising/">Django Software Foundation</a>,
sponsoring via <a rel="sponsored" href="https://github.com/sponsors/django">GitHub Sponsors</a>,
or buying <a rel="sponsored" href="https://django.threadless.com/">official merchandise</a>.

## Contents

<!--lint disable awesome-toc-->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

*   [Third-Party Packages](#third-party-packages)
    *   [Admin](#admin)
    *   [APIs](#apis)
    *   [Async](#async)
    *   [Caching](#caching)
    *   [Commands](#commands)
    *   [Configuration](#configuration)
    *   [Content Management Systems](#content-management-systems)
    *   [Database Connectors](#database-connectors)
    *   [ECommerce](#ecommerce)
    *   [Editors](#editors)
    *   [Files/Images](#filesimages)
    *   [Forms](#forms)
    *   [Full-stack frameworks](#full-stack-frameworks)
    *   [General](#general)
    *   [Internationalisation](#i18n)
    *   [Logging](#logging)
    *   [Mailing](#mailing)
    *   [Model Fields](#model-fields)
    *   [Models](#models)
    *   [Performance](#performance)
    *   [Permissions](#permissions)
    *   [Search](#search)
    *   [Search Engine Optimisation](#search-engine-optimisation)
    *   [Security](#security)
    *   [Static Assets](#static-assets)
    *   [Task Queues](#task-queues)
    *   [Templates](#templates)
    *   [Testing](#testing)
    *   [URLs](#urls)
    *   [Users](#users)
    *   [Views](#views)
*   [Python Packages](#python-packages)
*   [Resources](#resources)
    *   [Official Resources](#official-resources)
    *   [Educational](#educational)
    *   [Community](#community)
    *   [Conferences](#conferences)
    *   [Job Boards](#job-boards)
    *   [Newsletters](#newsletters)
    *   [Podcasts](#podcasts)
    *   [Books](#books)
*   [Hosting](#hosting)
    *   [PaaS (Platforms-as-a-Service)](#paas-platforms-as-a-service)
    *   [IaaS (Infrastructure-as-a-Service)](#iaas-infrastructure-as-a-service)
*   [Projects](#projects)
    *   [Boilerplate](#boilerplate)
    *   [Open Source Projects](#open-source-projects)
*   [Django REST Framework](#django-rest-framework)
    *   [DRF Resources](#drf-resources)
    *   [DRF Tutorials](#drf-tutorials)
*   [Wagtail](#wagtail)
    *   [Wagtail Resources](#wagtail-resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!--lint enable awesome-toc-->

## Third-Party Packages

*For a complete listing of all available packages, see [Django Packages](https://djangopackages.org/)*

### Admin

*   [django-grappelli (⭐3.8k)](https://github.com/sehmaschine/django-grappelli) - A jazzy skin for the admin.
*   [django-jazzmin (⭐1.6k)](https://github.com/farridav/django-jazzmin) - Drop-in theme for django admin, that utilises AdminLTE 3 & Bootstrap 4 to make yo' admin look jazzy.
*   [django-hijack (⭐1.5k)](https://github.com/arteria/django-hijack) - Admins can log in and work on behalf of other users without having to know their credentials.
*   [django-import-export (⭐3k)](https://github.com/django-import-export/django-import-export) - Django application and library for importing and exporting data with admin integration.
*   [django-admin-honeypot (⭐1k)](https://github.com/dmpayton/django-admin-honeypot) - Configure a honeypot to see who's trying to hack your site.
*   [django-loginas (⭐367)](https://github.com/skorokithakis/django-loginas) - "Log in as user" for the Django admin.
*   [impostor (⭐159)](https://github.com/avallbona/Impostor) - Impostor is a Django application which allows staff members to login as a different user by using their own username and password.
*   [django-impersonate](https://pypi.org/project/django-impersonate/) - Allow superusers to “impersonate” other non-superuser accounts.
*   [django-admin-env-notice (⭐315)](https://github.com/dizballanze/django-admin-env-notice) - Visually distinguish environments in Django Admin, for example: `development`, `staging`, `production`.
*   [django-admin-interface (⭐1.8k)](https://github.com/fabiocaccamo/django-admin-interface) - Customize Admin by the admin itself(color, header. title,logo) and  popup windows replaced by modals.
*   [django-material-admin (⭐321)](https://github.com/MaistrenkoAnton/django-material-admin) - Material design for django administration.
*   [django-related-admin (⭐69)](https://github.com/PetrDlouhy/django-related-admin) - A helper library that allows you to write list\_displays accross foreign key relationships.
*   [django-semantic-admin (⭐142)](https://github.com/globophobe/django-semantic-admin) - Django Semantic UI admin theme.
*   [django-jet-reboot (⭐405)](https://github.com/b1go/django-jet-reboot) - Django Jet is modern template for Django admin interface with improved functionality.
*   [django-baton (⭐876)](https://github.com/otto-torino/django-baton) - A cool, modern and responsive django admin application based on bootstrap 5.
*   [django-admin-sortable2 (⭐756)](https://github.com/jrief/django-admin-sortable2) - Generic drag-and-drop ordering for objects in the Django admin interface.
*   [django-unfold (⭐1.7k)](https://github.com/unfoldadmin/django-unfold) - Modern Django admin theme for seamless interface development

### APIs

<!--lint disable double-link-->

*   [django-rest-framework (⭐28k)](https://github.com/encode/django-rest-framework) - Web APIs for Django.
*   [django-cors-headers (⭐5.4k)](https://github.com/adamchainz/django-cors-headers) - If your back-end and front-end are on different servers, you need this.
*   [dj-rest-auth (⭐1.7k)](https://github.com/jazzband/dj-rest-auth) - Authentication for Django Rest Framework.
*   [django-rest-knox (⭐1.1k)](https://github.com/James1345/django-rest-knox) - Authentication Module for django-rest-auth.
*   [djoser (⭐2.5k)](https://github.com/sunscrapers/djoser) - REST implementation of Django auth.
*   [djaq (⭐75)](https://github.com/paul-wolf/djaq) - An instant remote API to Django models with a powerful query language.
*   [django-rest-framework-simplejwt (⭐4k)](https://github.com/davesque/django-rest-framework-simplejwt) - JSON web tokens for DRF.
*   [django-webpack-loader (⭐2.5k)](https://github.com/owais/django-webpack-loader) - Transparently use webpack with Django.
*   [drf-yasg (⭐3.4k)](https://github.com/axnsan12/drf-yasg) - Automated generation of real Swagger/OpenAPI 2.0 schemas from Django REST Framework code.
*   [graphene-django (⭐4.3k)](https://github.com/graphql-python/graphene-django) - GraphQL for Django.
*   [graphene-django-filter (⭐19)](https://github.com/devind-team/graphene-django-filter) - Advanced filters implementing and/or/not operators in GraphQL for Django.
*   [django-ninja](https://django-ninja.rest-framework.com/) - Django Ninja - Fast Django REST framework based on type annotations.
*   [django-tastypie (⭐3.9k)](https://github.com/django-tastypie/django-tastypie) - Creating delicious APIs for Django apps since 2010.
*   [drf-spectacular (⭐2.3k)](https://github.com/tfranzel/drf-spectacular) - Sane and flexible OpenAPI 3 schema generation for Django REST framework.
*   [django-webhook (⭐182)](https://github.com/danihodovic/django-webhook) - A plug-and-play Django app for sending outgoing webhooks on model changes.

<!--lint enable double-link-->

### Async

*   [channels (⭐6.1k)](https://github.com/django/channels/) - Async support for Django.
*   [starlette (⭐10k)](https://github.com/encode/starlette) - ASGI framework.

### Caching

*   [django-cachalot (⭐1.2k)](https://github.com/noripyt/django-cachalot) - Caches your Django ORM queries and automatically invalidates them.
*   [django-cacheops (⭐2.1k)](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.

### Commands

*   [django-extensions (⭐6.5k)](https://github.com/django-extensions/django-extensions/) - Custom management extensions, notably `runserver_plus` and `shell_plus`.
*   [django-click (⭐249)](https://github.com/GaretJax/django-click) - Write Django management commands using the [click CLI library](https://click.palletsprojects.com).
*   [django-dbbackup (⭐975)](https://github.com/django-dbbackup/django-dbbackup) - Management commands to help backup and restore your project database and media files.
*   [django-liquidb (⭐21)](https://github.com/Gusakovskiy/django-liquidb) - Django application to simplify migration management and changes in states of db scheme.
*   [django-migration-zero (⭐48)](https://github.com/ambient-innovation/django-migration-zero/) - Holistic implementation of "migration zero" pattern for Django covering local changes and in-production database adjustments.
*   [django-typer (⭐66)](https://github.com/bckohan/django-typer) - Write Django management commands using the [Typer CLI library](https://typer.tiangolo.com).

### Configuration

<!--lint disable double-link-->

*   [confidential (⭐73)](https://github.com/candidco/confidential) - Manage configs and secrets (with CLI support).
*   [django-environ (⭐3k)](https://github.com/joke2k/django-environ) - Environment variables.
*   [django-split-settings (⭐1.1k)](https://github.com/sobolevn/django-split-settings) - Organize multiple settings files.
*   [django-constance (⭐1.7k)](https://github.com/jazzband/django-constance) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.
*   [django-configurations (⭐1.1k)](https://github.com/jazzband/django-configurations) - eases Django project configuration by relying on the composability of Python classes and following principles of [the twelve-factor app](https://12factor.net/config).
*   [dynaconf](https://www.dynaconf.com/django/) - Dynaconf loads django settings from multiple sources (multiple file formats, env vars, redis, vault, etcd), manages secrets, and allows for different merging strategies all following [the twelve-factor app](https://12factor.net/config).
*   [django-extra-settings (⭐516)](https://github.com/fabiocaccamo/django-extra-settings) - Config and manage typed extra settings using just the django admin.
*   [environs (⭐1.2k)](https://github.com/sloria/environs) - Simplified environment variable parsing that comes with a [Django helper (⭐1.2k)](https://github.com/sloria/environs#usage-with-django) that installs additional packages.

<!--lint enable double-link-->

*   [django-classy-settings (⭐34)](https://github.com/funkybob/django-classy-settings) - Class based settings to keep your environments in order, with easy access to typed environment variables.
*   [django-content-settings](https://django-content-settings.readthedocs.io/en/latest/) - easily create and manage editable typed variables directly from the Django admin panel.

### Content Management Systems

<!--lint disable double-link-->

*   [wagtail (⭐18k)](https://github.com/wagtail/wagtail) - Popular Django content management system (CMS). See [awesome-wagtail (⭐2k)](https://github.com/springload/awesome-wagtail) too.
*   [mezzanine (⭐4.8k)](https://github.com/stephenmcd/mezzanine) - CMS framework.
*   [django-cms (⭐10k)](https://github.com/divio/django-cms) - CMS for Django.
*   [feincms (⭐941)](https://github.com/feincms/feincms) - An extensible Django-based CMS.
*   [puput (⭐624)](https://github.com/APSL/puput) - Blog app features with Wagtail.

<!--lint enable double-link-->

### Database Connectors

*   [djongo (⭐1.9k)](https://github.com/doableware/djongo) - Django and MongoDB database connector.

### ECommerce

*   [saleor (⭐21k)](https://github.com/mirumee/saleor) - GraphQL-based Django E-Commerce Platform.
*   [django-shop (⭐3.2k)](https://github.com/awesto/django-shop) - Django-based shop system.
*   [shuup (⭐2.2k)](https://github.com/shuup/shuup) - Django E-Commerce Platform.
*   [django-oscar (⭐6.2k)](https://github.com/django-oscar/django-oscar) - Domain-driven e-commerce for Django.

### Editors

<!--lint ignore awesome-list-item-->

*   [django-markdownx (⭐854)](https://github.com/adi-/django-markdownx) - Comprehensive Markdown plugin built for Django.
*   [django-markdown-editor (⭐813)](https://github.com/agusmakmun/django-markdown-editor) - Awesome Django Markdown Editor, supported for Bootstrap & Semantic-UI.
*   [django-business-logic (⭐214)](https://github.com/dgk/django-business-logic) - Visual DSL framework for Django.
*   [django-quill-editor (⭐193)](https://github.com/LeeHanYeong/django-quill-editor) - Makes Quill.js easy to use on Django Forms and admin sites.
*   [django-summernote (⭐1k)](https://github.com/summernote/django-summernote) - Summernote is a simple WYSIWYG editor.
*   [django-tinymce (⭐1.3k)](https://github.com/jazzband/django-tinymce) - TinyMCE integration for Django.
*   [django-prose (⭐197)](https://github.com/withlogicco/django-prose) - A light weight editor to content creation.
*   [django-ace (⭐134)](https://github.com/django-ace/django-ace) - ACE integration for Django.

### Files/Images

*   [django-cleanup (⭐1.1k)](https://github.com/un1t/django-cleanup) - Zero configuration file/image removal for local and remote files.
*   [django-imagekit (⭐2.3k)](https://github.com/matthewwithanm/django-imagekit) - Django app for processing images for thumbnail, black-and-white and sizes.
*   [django-pictures (⭐248)](https://github.com/codingjoe/django-pictures) - Responsive cross-browser image library using modern codes like AVIF & WebP.
*   [sorl-thumbnail (⭐1.7k)](https://github.com/jazzband/sorl-thumbnail) - Thumbnails for Django.

### Forms

*   [django-bleach (⭐148)](https://github.com/marksweb/django-bleach/) - Integrate bleach into forms and models. See `django-nh3` as an alternative.
*   [django-crispy-forms (⭐5k)](https://github.com/django-crispy-forms/django-crispy-forms/) - DRY Django forms.
*   [django-floppyforms (⭐841)](https://github.com/jazzband/django-floppyforms) - Full control of form rendering.
*   [django-formtools (⭐805)](https://github.com/jazzband/django-formtools) - For form previous and multi-step forms, previously part of Django until 1.8.
*   [django-widget-tweaks (⭐2.1k)](https://github.com/jazzband/django-widget-tweaks) - Tweak form field rendering in templates.
*   [django-autocomplete-light (⭐1.8k)](https://github.com/yourlabs/django-autocomplete-light) - Add autocompletion to forms.
*   [django-shapeshifter (⭐175)](https://github.com/kennethlove/django-shapeshifter) - A class-based view to handle multiple forms in one view.

### Full-stack frameworks

*   [Django-Bridge (⭐116)](https://github.com/django-bridge/django-bridge) - The simple way to build React frontends for Django applications.
*   [ReactPy (⭐7.9k)](https://github.com/reactive-python/reactpy) - It's React, but in Python. Insert dynamically rendered Python into Django templates using the [ReactPy-Django module (⭐327)](https://github.com/reactive-python/reactpy-django).
*   [Reactor (⭐633)](https://github.com/edelvalle/reactor/) - Phoenix LiveView, but for Django.
*   [Sockpuppet](https://sockpuppet.argpar.se/) - Build reactive applications with the Django tooling you already know and love.
*   [Unicorn](https://www.django-unicorn.com/) - A reactive component framework that progressively enhances a normal Django view, makes AJAX calls in the background, and dynamically updates the DOM.
*   [iommi (⭐759)](https://github.com/TriOptima/iommi) - Toolkit for development of CRUD applications without writing HTML or JavaScript.

### General

*   [django-data-browser (⭐344)](https://github.com/tolomea/django-data-browser) - Interactive, user-friendly database explorer.
*   [django-filter (⭐4.4k)](https://github.com/carltongibson/django-filter) - Powerful filters based on Django QuerySets.
*   [django-sql-explorer (⭐2.8k)](https://github.com/groveco/django-sql-explorer) - Share data via SQL queries.
*   [django-tables2 (⭐1.9k)](https://github.com/jieter/django-tables2) - HTML tables with pagination/sorting.
*   [django-maintenance-mode (⭐474)](https://github.com/fabiocaccamo/django-maintenance-mode) - Shows a 503 error page when maintenance-mode is on.
*   [django-freeze (⭐94)](https://github.com/fabiocaccamo/django-freeze) - Convert your dynamic django site to a static one with one line of code.
*   [django-nh3 (⭐23)](https://github.com/marksweb/django-nh3) - Django integration with for nh3 and is an alternative for django-bleach.
*   [Weblate (⭐4.5k)](https://github.com/WeblateOrg/weblate) - Weblate is a copylefted libre software web-based continuous localization system, used by over 2500 libre projects and companies in more than 165 countries.
*   [Django-Classy-Doc (⭐23)](https://github.com/nanuxbe/django-classy-doc) - Document your own code in the style of CCBV and CDRF.[https://github.com/nanuxbe/django-classy-doc (⭐23)](https://github.com/nanuxbe/django-classy-doc)

### <a id="i18n"></a> Internationalisation (i18n)

*   [django-localflavor (⭐828)](https://github.com/django/django-localflavor) - A collection of functionality that is useful for particular countries or cultures. Previously a part of the Django core.
*   [django-modeltrans (⭐64)](https://github.com/zostera/django-modeltrans) - Translate Django model fields in a JSONField.
*   [django-modeltranslations (⭐1.4k)](https://github.com/deschler/django-modeltranslation) -  Translates Django models using a registration approach.
*   [django-rosetta (⭐1.1k)](https://github.com/mbi/django-rosetta) - Rosetta provides a UI to read and write your project's gettext catalogs within the Django Admin.

### Logging

*   [django-guid (⭐450)](https://github.com/JonasKs/django-guid) - Inject a GUID (Correlation-ID) into every log message in a Django request.
*   [DRF-API-Logger (⭐307)](https://github.com/vishalanandl177/DRF-API-Logger) - An API Logger for your Django Rest Framework project.

### Monitoring

*   [django-prometheus (⭐1.4k)](https://github.com/korfuri/django-prometheus) - Export Django monitoring metrics to Prometheus.
*   [django-mixin (⭐49)](https://github.com/adinhodovic/django-mixin) - Monitoring mixin for Django-prometheus. A set of Grafana dashboards and Prometheus rules for Django.

### Mailing

*   [django-pony-express (⭐59)](https://github.com/ambient-innovation/django-pony-express) - Class-based emails including a test suite for Django.

### Model Fields

*   [django-any-urlfield (⭐51)](https://github.com/edoburu/django-any-urlfield) - An improved URL selector to choose between internal models and external URLs.
*   [django-colorfield (⭐619)](https://github.com/fabiocaccamo/django-colorfield) - Color field for django models with a nice color-picker widget.
*   [django-model-utils (⭐2.7k)](https://github.com/jazzband/django-model-utils) - Django model mixins and utilities.
*   [django-money (⭐1.7k)](https://github.com/django-money/django-money) - Money fields for forms/models.
*   [django-phonenumber-field (⭐1.5k)](https://github.com/stefanfoulis/django-phonenumber-field) - Model/form field for normalized phone numbers.
*   [django-streamfield (⭐124)](https://github.com/raagin/django-streamfield) - Simple StreamField for plain Django admin (based on Wagtail CMS StreamField idea).

### Models

*   [django-lifecycle (⭐1.3k)](https://github.com/rsinger86/django-lifecycle) - Declarative model lifecycle hooks, an alternative to Signals.
*   [django-mptt (⭐2.9k)](https://github.com/django-mptt/django-mptt) - Modified Preorder Tree Traversal; working with trees of Model instances.
*   [django-taggit (⭐3.3k)](https://github.com/jazzband/django-taggit/) - Simple model tags.
*   [django-reversion (⭐3k)](https://github.com/etianen/django-reversion) - Version control for model instances.
*   [django-simple-history (⭐2.2k)](https://github.com/jazzband/django-simple-history) - Store model history and view/revert changes from the admin.
*   [django-polymorphic (⭐1.6k)](https://github.com/django-polymorphic/django-polymorphic) - Django-polymorphic simplifies using inherited models in Django projects.
*   [django-recurrence (⭐478)](https://github.com/django-recurrence/django-recurrence) - Utility for working with recurring dates in Django.
*   [django-treenode (⭐664)](https://github.com/fabiocaccamo/django-treenode) - Abstract model/admin for tree based stuff.
*   [django-auto-prefetch (⭐353)](https://github.com/tolomea/django-auto-prefetch) - Automatically prefetch foreign key values as needed.

### Performance

*   [django-perf-rec](https://cur.at/GHUO6cn?m=web) - Keep detailed records of the performance of your Django code.
*   [New Relic](https://newrelic.com/python/django) - Time middleware, views, and SQL queries.
*   [Scout](https://scoutapm.com/docs/python/django) - Time middleware, template rendering, and SQL queries with automatic N+1 detection.
*   [django-query-profiler (⭐140)](https://github.com/django-query-profiler/django-query-profiler) - Django query profiler to help resolve N+1 queries.
*   [django-silk (⭐4.4k)](https://github.com/jazzband/django-silk) - Live profiling and inspection of HTTP requests and database queries.
*   [py-spy (⭐13k)](https://github.com/benfred/py-spy) - Sampling profiler for Python programs.
*   [pyinstrument (⭐6.5k)](https://github.com/joerick/pyinstrument) - Call stack profiler for Python, Django, Flask, FastAPI.

### Permissions

*   [django-role-permissions (⭐727)](https://github.com/vintasoftware/django-role-permissions) - Django app for role-based permissions management.
*   [django-guardian (⭐3.6k)](https://github.com/django-guardian/django-guardian) - Per object permissions in Django.
*   [django-rules (⭐1.9k)](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions, built from the ground up for Django.

### Search

*   [django-haystack (⭐3.6k)](https://github.com/django-haystack/django-haystack) - Modular search for Django.
*   [django-watson (⭐1.2k)](https://github.com/etianen/django-watson) - Full-text search plugin.
*   [django-admin-search (⭐78)](https://github.com/shinneider/django-admin-search) - Modal filter for django admin.
*   [django-elasticsearch-dsl (⭐1k)](https://github.com/django-es/django-elasticsearch-dsl) - Elasticsearch DSL integration for Django.

### Search Engine Optimisation

*   [django-check-seo (⭐156)](https://github.com/kapt-labs/django-check-seo) - Check SEO of pages.

### Security

*   [django-csp (⭐556)](https://github.com/mozilla/django-csp) - Adds [Content-Security-Policy](http://www.w3.org/TR/CSP/) headers to Django.
*   [django-feature-policy (⭐98)](https://github.com/adamchainz/django-feature-policy) - Set the draft security HTTP header `Feature-Policy` on a Django app.
*   [django-protected-media (⭐66)](https://github.com/cobusc/django-protected-media) - Manages media that are considered sensitive in a protected fashion.
*   [DJ Checkup](https://djcheckup.com) - Runs several checks on your deployed Django site to check for common security mistakes.

### Static Assets

*   [django-storages (⭐2.7k)](https://github.com/jschneier/django-storages) - A single library to support multiple custom storage backends for Django.
*   [django-compressor (⭐2.8k)](https://github.com/django-compressor/django-compressor/) - Compress JavaScript/CSS into a single cached file.
*   [easy-thumbnails (⭐1.4k)](https://github.com/SmileyChris/easy-thumbnails) - Image thumbnails for Django.
*   [whitenoise (⭐2.5k)](https://github.com/evansd/whitenoise) - Simplified static file serving for Python websites.

### Task Queues

*   [beatserver (⭐141)](https://github.com/rajasimon/beatserver) - A periodic task scheduler for Django.
*   [django-q2 (⭐354)](https://github.com/django-q2/django-q2) - A multiprocessing distributed task queue for Django.
*   [django-rq (⭐1.8k)](https://github.com/rq/django-rq) - Integration for Redis Queue.
*   [django-redis (⭐2.9k)](https://github.com/niwinz/django-redis) - Full-featured Redis cache backend for Django.
*   [celery (⭐25k)](https://github.com/celery/celery) - Robust and broker-agnostic task queues for bigger, performance-focused projects.
*   [flower (⭐6.4k)](https://github.com/mher/flower) - Flower is a web-based tool for monitoring and administrating Celery clusters.
*   [django-celery-beat (⭐1.7k)](https://github.com/celery/django-celery-beat) - A periodic task scheduler with database configured by Django's Admin Panel.
*   [celery-exporter (⭐408)](https://github.com/danihodovic/celery-exporter) - Prometheus & Grafana monitoring of Celery tasks.
*   [django-dramatiq (⭐347)](https://github.com/Bogdanp/django_dramatiq) - Task processing library with a focus on simplicity, reliability, and performance.
*   [django-celery-results (⭐684)](https://github.com/celery/django-celery-results) -  Celery result backend with Django.

### Templates

*   [curlylint](https://www.curlylint.org/) - Experimental HTML templates linting for Jinja, Nunjucks, Django templates, Twig, Liquid.
*   [django-components (⭐1.1k)](https://github.com/EmilStenstrom/django-components/) - A way to create simple reusable template components in Django.
*   [django-template-partials (⭐443)](https://github.com/carltongibson/django-template-partials/) - Reusable named inline partials for the Django Template Language.
*   [djhtml (⭐574)](https://github.com/rtts/djhtml) - Django/Jinja template indenter.
*   [djlint](https://www.djlint.com/) - Lint & Format HTML Templates.
*   [slippers](https://mitchel.me/slippers/) - Build reusable components in Django without writing a single line of Python.
*   [JinjaX](https://jinjax.scaletti.dev/) - Super components powers for your Jinja templates.
*   [django-cotton](https://django-cotton.com/) - Goodbye `{% raw %}{%{% endraw %} extends, block, include {% raw %}%}{% endraw %}`, Hello `<c-component />`. Bringing modern UI composition to Django.

### Testing

*   [django-debug-toolbar (⭐8.1k)](https://github.com/jazzband/django-debug-toolbar/) - Configurable panels to debug requests/responses.
*   [pytest-django (⭐1.4k)](https://github.com/pytest-dev/pytest-django) - Use pytest features in Django.
*   [django-test-migrations (⭐521)](https://github.com/wemake-services/django-test-migrations) - Test django schema and data migrations, including migrations' order.
*   [django-test-plus (⭐611)](https://github.com/revsys/django-test-plus/) - Useful additions to Django's default TestCase.
*   [factory-boy (⭐3.5k)](https://github.com/FactoryBoy/factory_boy) - Test fixtures replacement.
*   [django-waffle (⭐1.1k)](https://github.com/django-waffle/django-waffle) - A feature flipper for Django.
*   [model-bakery (⭐829)](https://github.com/model-bakers/model_bakery) - Object factory for Django (rename of legacy Model Mommy project).
*   [django-fakery (⭐114)](https://github.com/fcurella/django-fakery) - An easy-to-use implementation of Creation Methods for Django, backed by Faker.
*   [drf-openapi-tester (⭐118)](https://github.com/snok/drf-openapi-tester) - Django test utility for validating Swagger 2.0 and OpenAPI 3.0 documentation.
*   [django-google-optimize (⭐40)](https://github.com/adinhodovic/django-google-optimize) - Django application designed to make running server side Google Optimize A/B tests easy.
*   [django-pattern-library (⭐364)](https://github.com/torchbox/django-pattern-library) - Pattern library generator for Django templates, to help testing of UI components.
*   [storybook-django (⭐104)](https://github.com/torchbox/storybook-django) - Develop Django UI components in isolation, with Storybook.

### URLs

*   [dj-database-url (⭐1.5k)](https://github.com/jacobian/dj-database-url) - Database URLs.
*   [urlman (⭐117)](https://github.com/andrewgodwin/urlman) - A nicer way to do URLs for Django models.
*   [django-robots (⭐460)](https://github.com/jazzband/django-robots) - This is a basic Django application to manage robots.txt files following the robots exclusion protocol, complementing the Django Sitemap contrib app.
*   [django-redirects (⭐67)](https://github.com/fabiocaccamo/django-redirects) - Redirects as they should be, with full control.

### Users

*   [django-allauth (⭐9.4k)](https://github.com/pennersr/django-allauth/) - Improved user registration including social auth.
*   [django-allauth-ui (⭐251)](https://github.com/danihodovic/django-allauth-ui/) - Better looking templates for django-allauth.
*   [django-improved-user (⭐147)](https://github.com/jambonsw/django-improved-user) - A custom Django user that authenticates via email. Follows identity and authentication best practices.
*   [django-organizations (⭐1.3k)](https://github.com/bennylope/django-organizations/) - Multi-user accounts for Django projects.
*   [django-cas-ng (⭐381)](https://github.com/django-cas-ng/django-cas-ng) - Django-cas-ng is Django CAS (Central Authentication Service) 1.0/2.0/3.0 client library to support SSO (Single Sign On) and Single Logout (SLO).
*   [django-guest-user (⭐74)](https://github.com/julianwachholz/django-guest-user) - Allow visitors to use your site like a regular user and register later.

### Views

*   [django-braces (⭐2k)](https://github.com/brack3t/django-braces) - Reusable, generic mixins.
*   [django-easy-audit (⭐723)](https://github.com/soynatan/django-easy-audit) - Keep track of user actions.
*   [django-extra-views (⭐1.4k)](https://github.com/AndrewIngram/django-extra-views) - Extra class-based generic views.
*   [django-vanilla-views (⭐985)](https://github.com/tomchristie/django-vanilla-views) - Simpler class-based views in Django.
*   [django-stronghold (⭐396)](https://github.com/mgrouchy/django-stronghold) - Makes all your Django views default login\_required.
*   [neapolitan (⭐480)](https://github.com/carltongibson/neapolitan) - Quick CRUD views for Django.

## Python Packages

*A short list of Python packages that work well with Django.*

*   [bleach (⭐2.6k)](https://github.com/mozilla/bleach) - Sanitize your inputs/forms.
*   [black (⭐39k)](https://github.com/psf/black) - Uncompromising Python code formatter.
*   [coveragepy (⭐3k)](https://github.com/nedbat/coveragepy) - Code coverage measurement.
*   [faker (⭐18k)](https://github.com/joke2k/faker) - Faker is a Python package that generates fake data for you.
*   [huey (⭐5.2k)](https://github.com/coleifer/huey) - A little task queue for Python.
*   [nplusone (⭐998)](https://github.com/jmcarp/nplusone) - Auto-detect n+1 queries.
*   [pillow (⭐12k)](https://github.com/python-pillow/Pillow) - Python Imaging Library.
*   [pytest (⭐12k)](https://github.com/pytest-dev/pytest/) - Testing framework.
*   [python-decouple (⭐2.8k)](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code.
*   [python-slugify (⭐1.5k)](https://github.com/un33k/python-slugify) - Returns unicode slugs.
*   [sentry-python (⭐1.9k)](https://github.com/getsentry/sentry-python) - Error reporting SDK.
*   [python-socketio (⭐4k)](https://github.com/miguelgrinberg/python-socketio) - Python implementation of the Socket.IO\_ realtime client and server. [(create Socket.io Django server instance)](https://python-socketio.readthedocs.io/en/latest/server.html?highlight=django#creating-a-server-instance)

## Resources

### Official Resources

<!--lint ignore double-link--> 

*   [Project Website](https://www.djangoproject.com/) - Official Django website.
*   [Documentation](https://docs.djangoproject.com/en/dev/) - Comprehensive documentation for all Django versions.
*   [Polls Tutorial](https://docs.djangoproject.com/en/dev/intro/tutorial01/) - Build a polls tutorial while learning Django internals.
*   [Source Code (⭐79k)](https://github.com/django/django/) - Hosted on GitHub.

### Educational

*   [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) - Use function-based views to build a blog app.
*   [LearnDjango](https://learndjango.com/) - Tutorials and premium courses on Django and Django REST Framework.
*   [Adam Johnson](https://adamj.eu/tech/) - Adam is on the Technical Board of Django and regularly writes tutorials.
*   [Photon Designer - Django tutorials](https://photondesigner.com/articles) - Django tutorials by Tom Dekan on how to build Django apps simply - from how to build an instant messenger with Django, add instant search, to using Google Drive as a database. Updated regularly.
*   [TestDriven](https://testdriven.io/blog/) - Multiple Django-specific tutorials on topics like Docker, payments, and more.
*   [Classy Class-Based Views](https://ccbv.co.uk/) - Detailed descriptions of methods/properties/attributes for each generic class-based view.
*   [Classy Django Forms (⭐28)](https://github.com/ana-balica/classy-django-forms) - Detailed descriptions of methods/properties/attributes for each form class.
*   [Classy Django REST Framework](http://www.cdrf.co) - Detailed descriptions with methods/attributes for DRF class-based views and serializers.
*   [Simple is Better than Complex](https://simpleisbetterthancomplex.com/) - Regularly updated website with many tutorials and tips on Django.
*   [Full Stack Python's Django Page](https://www.fullstackpython.com/django.html) - Explanation of Django philosophy and links to other resources and tutorials.
*   [RealPython](https://realpython.com/tutorials/django/) - Many high-quality tutorials on Django.
*   [Mozilla Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) - Create a lending library app.
*   [Matt Layman](https://www.mattlayman.com) - Regular tutorials and deep-dives on Django topics.
*   [Django Styleguide (⭐5k)](https://github.com/HackSoftware/Django-Styleguide) - Styleguide for Django with best practices and examples.
*   [Django Template Tags and Filters](https://www.djangotemplatetagsandfilters.com/) - Additional docs on Django's 57 built-in template filters and 27 template tags.
*   [Django for Everybody](https://www.dj4e.com/) - A complete course for webdev beginners focused on Django.
*   [CS50W](https://cs50.harvard.edu/web/2020/) - Harvard's University introductory course to web development, it explains Django as backend framework.

### Community

<!--lint disable double-link-->

*   [Django Forum](https://forum.djangoproject.com/) - Official Discourse board.
*   [Community Page](https://www.djangoproject.com/community/) - Featuring feeds of Community Blog Posts, Jobs, and more.
*   [Local Django Communities Page](https://www.djangoproject.com/community/local/) – Featuring local events all around the world.
*   [Django Users Google Group](https://groups.google.com/forum/#!forum/django-users/) - Very active discussion board for questions/answers.
*   [Developers Google Group](https://groups.google.com/forum/#!forum/django-developers/) - For contributions to Django itself only.
*   [Mastodon](https://fosstodon.org/@django) - For official announcements on updates, security fixes, etc.
*   [Twitter](https://twitter.com/djangoproject/) - For official announcements on updates, security fixes, etc.
*   [Discord Server](https://discord.com/invite/xcRH6mN4fa) - Django Discord Community.
*   IRC Channel - Chat with other Django users at irc://irc.freenode.net/django.
*   [Djangonaut Space](https://djangonaut.space) - Free peer-mentoring program for the Django community to launch people into the universe of open source contributions.

<!--lint enable double-link-->

### Conferences

*   [DjangoCon US](https://djangocon.us/) ([YouTube Channel](https://www.youtube.com/channel/UC0yY6a79pPY9J0ShIHRf6yw))
*   [DjangoCon Europe](https://djangocon.eu/) ([YouTube Channel](https://www.youtube.com/user/djangoconeurope))
*   [DjangoCon AU](https://djangocon.com.au/)
*   [DjangoCon Africa](https://djangocon.africa/)
*   [Django Day Copenhagen](https://djangoday.dk/)
*   [PyCon US](https://us.pycon.org/) ([YouTube Channel](https://www.youtube.com/channel/UCsX05-2sVSH7Nx3zuk3NYuQ))
*   [PyCon Australia](https://pycon-au.org/) ([YouTube Channel](https://www.youtube.com/user/PyConAU))
*   [Euro Python](https://europython.eu/) ([YouTube Channel](https://www.youtube.com/user/PythonItalia))
*   [Django Under the Hood](https://www.youtube.com/channel/UC9T1dhIlL_8Va9DxvKRowBw/videos)
*   [DjangoCongress JP](https://djangocongress.jp/) ([YouTube Channel](https://www.youtube.com/@djangocongressjp3623))
*   [Complete listing of all PyCons globally](https://pycon.org)

### Job Boards

*   [Django News Jobs](https://jobs.django-news.com/) - A Django job board that also aggregates other job boards.
*   [Django Gigs](https://djangogigs.com) - This platform caters specifically to freelance and full-time Django developers.
*   [Django Jobs](https://djangojobs.net) - Django jobs posting for hiring Django Python developers.
*   [Python.org Job Boards](https://www.python.org/jobs/) - While not exclusively for Django, this job board is hosted by the official Python website and features a range of Python and Django-related job opportunities.

### Newsletters

*   [Django News](https://django-news.com) - Weekly newsletter on announcements, articles, projects, and talks.

### Podcasts

*   [Django Chat](https://djangochat.com/) - A weekly podcast from William Vincent and Django Fellow Carlton Gibson with discussions of core Django concepts and regular guests.
*   [Django Riffs](https://djangoriffs.com) - A new podcast from Matt Layman.
*   [Running in Production](https://runninginproduction.com/tags/django) - Focused on tech stacks with many episodes specifically on Django.
*   [TalkPython](https://talkpython.fm/) - The leading Python podcast with several episodes on Django.
*   [Podcast Init](https://www.pythonpodcast.com/) - A popular Python podcast that features Django guests on occasion.

### Books

*Django 5*

*   [Boost Your Django DX](https://adamchainz.gumroad.com/l/byddx)
*   [Django 5 By Example](https://www.packtpub.com/en-us/product/django-5-by-example-9781805125457)
*   [Django in Action](https://www.manning.com/books/django-in-action)
*   [Django for Beginners, Fifth Edition](https://djangoforbeginners.com/)

*Django 4*

*   [Django for APIs: Build web APIs with Python and Django](https://djangoforapis.com/)
*   [Django for Professionals: Production websites with Python and Django](https://djangoforprofessionals.com/)
*   [Understand Django: An Exploration of the Django Web Framework](https://www.mattlayman.com/understand-django/)

*Django 3*

*   [Speed Up Your Django Tests](https://adamj.eu/tech/2020/05/04/new-book-speed-up-your-django-tests/)
*   [Two Scoops of Django 3.x: Best Practices for the Django Web Framework](https://www.feldroy.com/books/two-scoops-of-django-3-x)
*   [A Wedge of Django: Covers Python 3.8 and Django 3.x](https://www.feldroy.com/books/a-wedge-of-django)

## Hosting

### PaaS (Platforms-as-a-Service)

*   [Appliku](https://appliku.com)
*   [Dokku](https://dokku.com)
*   [Divio](https://www.divio.com)
*   [Fly](https://fly.io)
*   [Google Cloud](https://cloud.google.com/python/django/)
*   [Heroku](https://www.heroku.com)
*   [Microsoft Azure](https://azure.microsoft.com/en-us/develop/python/)
*   [Piku (⭐5.7k)](https://github.com/piku/piku)
*   [Platform.sh](https://platform.sh)
*   [PythonAnywhere](https://www.pythonanywhere.com)
*   [Railway](https://railway.app)
*   [Render](https://render.com)
*   [Vercel](https://vercel.com/home)

### IaaS (Infrastructure-as-a-Service)

*   [Digital Ocean](https://www.digitalocean.com)
*   [Linode](https://www.linode.com)
*   [Amazon Lightsail](https://aws.amazon.com/lightsail/)
*   [Hetzner](https://www.hetzner.com)

## Projects

### Boilerplate

*   [cookiecutter-django (⭐12k)](https://github.com/pydanny/cookiecutter-django/) - A full-bodied starter project, highly customizable.
*   [django-base-site (⭐378)](https://github.com/epicserve/django-base-site/) - A Django site with many common third-party packages pre-installed.
*   [djangox (⭐2.1k)](https://github.com/wsvincent/djangox/) - Batteries included starter project for Pip, Pipenv, or Docker.
*   [DRFx (⭐482)](https://github.com/wsvincent/drfx/) - A DRF starter with user auth, Pipenv, and other goodies.
*   [django-project-template (⭐714)](https://github.com/jpadilla/django-project-template) - A deliberately basic project that has multiple staging environments and Heroku deployment config.
*   [django-docker-template (⭐188)](https://github.com/amerkurev/django-docker-template) - Dockerized Django with Postgres, Gunicorn, and Traefik (with auto renew Let's Encrypt).
*   [django-startproject (⭐185)](https://github.com/jefftriplett/django-startproject) - Django start project template with batteries.
*   [wemake-django-template (⭐2k)](https://github.com/wemake-services/wemake-django-template/) - Bleeding edge Django template focused on code quality and security.
*   [django-webpack-starter (⭐59)](https://github.com/khadegd/django-webpack-starter) - Django Webpack starter template for using Webpack 4.
*   [sos-django-template (⭐20)](https://github.com/erayerdin/sos-django-template) - Django starter template with separate dev and production settings.
*   [django-docker-heroku-template (⭐36)](https://github.com/bfirsh/django-docker-heroku-template) - A template with Docker, GitHub Actions, and Heroku set up for dev/test/prod, plus various other best practices.
*   [cookiecutter-vue-django (⭐206)](https://github.com/ilikerobots/cookiecutter-vue-django) - Django + Vue starter project fusing Vue SFCs & Django Templates.
*   [launchr (⭐234)](https://github.com/jayfk/launchr) - Launchr is a specialized Django starter template for SaaS web apps.
*   [sidewinder (⭐192)](https://github.com/stribny/sidewinder/) - A Django starter kit that focuses on good defaults, developer experience, and deployment.
*   [Falco (⭐358)](https://github.com/tobi-de/falco) - Enhance your Django developer experience: CLI and Guides for the Modern Django Developer.

### Open Source Projects

*   [Blog app with users and forms (⭐1.2k)](https://github.com/wsvincent/djangoforbeginners/tree/master/ch7-blog-app-with-users/)
*   [Newspaper app with custom user model, full user auth (⭐1.2k)](https://github.com/wsvincent/djangoforbeginners/tree/master/ch15-comments)
*   [pythonic-news (⭐518)](https://github.com/sebst/pythonic-news) - Hacker News clone.
*   [Behavior-Driven Development with Aloe (⭐43)](https://github.com/testdrivenio/django-aloe-bdd/)
*   [Image Sharing Blog (⭐89)](https://github.com/MeNsaaH/soMedia)
*   [Bootcamp: An enterprise social network (⭐2.3k)](https://github.com/vitorfs/bootcamp)
*   [Zulip (⭐21k)](https://github.com/zulip/zulip/) - Open-source team chat.
*   [Django-CRM (⭐1.9k)](https://github.com/MicroPyramid/Django-CRM/) - Open Source Python CRM based on Django.
*   [django-job-portal (⭐549)](https://github.com/manjurulhoque/django-job-portal) - Job portal application using Django.
*   [Built with Django](https://builtwithdjango.com) - Curated list of awesome Django projects.
*   [PostHog (⭐21k)](https://github.com/PostHog/posthog) - Open-source product analytics.
*   [HyperKitty](https://gitlab.com/mailman/hyperkitty) - A web interface to access GNU Mailman v3 archives.
*   [Healthchecks (⭐8.1k)](https://github.com/healthchecks/healthchecks) - A Cron Monitoring Tool written in Python & Django.
*   [Flagsmith (⭐4.8k)](https://github.com/Flagsmith/flagsmith) - Open-source Feature Flagging, Remote Config, and AB testing.
*   [OpenContracts (⭐684)](https://github.com/JSv4/OpenContracts) - enterprise-grade document analytics platform that combines automated PDF parsing, vector embeddings, and LLM integration.

## Django REST Framework

*The most popular way to build web APIs with Django.*

### DRF Resources

<!--lint disable double-link-->

*   [Official Documentation](https://www.django-rest-framework.org/)
*   [DRF Source Code (⭐28k)](https://github.com/encode/django-rest-framework)
*   [awesome-django-rest-framework (⭐1.3k)](https://github.com/nioperas06/awesome-django-rest-framework)

<!--lint enable double-link-->

### DRF Tutorials

<!--lint ignore double-link-->

*   [Official REST Framework - A Beginner's Guide](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)
*   [Building APIs with Django and DRF](https://books.agiliq.com/projects/django-api-polls-tutorial/en/latest/)
*   [DRF with React](https://www.valentinog.com/blog/drf/)
*   [Making React and Django play well together](https://fractalideas.com/blog/making-react-and-django-play-well-together/)

## Wagtail

*Wagtail, the powerful CMS for modern websites.*

### Wagtail Resources

<!--lint disable double-link-->

*   [Official website](https://wagtail.org/)
*   [Developer documentation](https://docs.wagtail.org/en/stable/)
*   [User documentation](https://guide.wagtail.org/en-latest/)
*   [Wagtail Source Code (⭐18k)](https://github.com/wagtail/wagtail/)
*   [awesome-wagtail (⭐2k)](https://github.com/springload/awesome-wagtail)
*   [This week in Wagtail](https://wagtail.org/this-week-in-wagtail/) - A (most) weekly email with updates from the Wagtail core team.
*   [Wagtail Space](https://www.wagtail.space/) - Wagtail CMS events around the world.

<!--lint enable double-link-->

