# Awesome Django Overview

A curated list of awesome things related to Django

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/wsvincent/awesome-django/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 wsvincent/awesome-django](https://github.com/wsvincent/awesome-django) · ⭐ 7.6K · 🏷️ Programming Languages

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
    *   [Logging](#logging)
    *   [Model Fields](#model-fields)
    *   [Models](#models)
    *   [Performance](#performance)
    *   [Search](#search)
    *   [Search Engine Optimisation](#search-engine-optimisation)
    *   [Security](#security)
    *   [Static Assets](#static-assets)
    *   [Task Queues](#task-queues)
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

*   [django-grappelli (⭐3.5k)](https://github.com/sehmaschine/django-grappelli) - A jazzy skin for the admin.
*   [django-jazzmin (⭐1.4k)](https://github.com/farridav/django-jazzmin) - Drop-in theme for django admin, that utilises AdminLTE 3 & Bootstrap 4 to make yo' admin look jazzy.
*   [django-hijack (⭐1.4k)](https://github.com/arteria/django-hijack) - Admins can log in and work on behalf of other users without having to know their credentials.
*   [django-import-export (⭐2.8k)](https://github.com/django-import-export/django-import-export) - Django application and library for importing and exporting data with admin integration.
*   [django-admin-honeypot (⭐970)](https://github.com/dmpayton/django-admin-honeypot) - Configure a honeypot to see who's trying to hack your site.
*   [django-loginas (⭐358)](https://github.com/skorokithakis/django-loginas) - "Log in as user" for the Django admin.
*   [impostor (⭐147)](https://github.com/avallbona/Impostor) - Impostor is a Django application which allows staff members to login as a different user by using their own username and password.
*   [django-impersonate](https://pypi.org/project/django-impersonate/) - Allow superusers to “impersonate” other non-superuser accounts.
*   [django-admin-env-notice (⭐289)](https://github.com/dizballanze/django-admin-env-notice) - Visually distinguish environments in Django Admin, for example: `development`, `staging`, `production`.
*   [django-admin-interface (⭐1.5k)](https://github.com/fabiocaccamo/django-admin-interface) - Customize Admin by the admin itself(color, header. title,logo) and  popup windows replaced by modals.
*   [django-material-admin (⭐301)](https://github.com/MaistrenkoAnton/django-material-admin) - Material design for django administration.
*   [django-related-admin (⭐64)](https://github.com/PetrDlouhy/django-related-admin) - A helper library that allows you to write list\_displays accross foreign key relationships.
*   [django-semantic-admin (⭐91)](https://github.com/globophobe/django-semantic-admin) - Django Semantic UI admin theme.
*   [django-jet-reboot (⭐311)](https://github.com/b1go/django-jet-reboot) - Django Jet is modern template for Django admin interface with improved functionality.
*   [django-baton (⭐780)](https://github.com/otto-torino/django-baton) - A cool, modern and responsive django admin application based on bootstrap 5.
*   [django-admin-sortable2 (⭐663)](https://github.com/jrief/django-admin-sortable2) - Generic drag-and-drop ordering for objects in the Django admin interface.

### APIs

<!--lint disable double-link-->

*   [django-rest-framework (⭐27k)](https://github.com/encode/django-rest-framework) - Web APIs for Django.
*   [django-cors-headers (⭐5.1k)](https://github.com/adamchainz/django-cors-headers) - If your back-end and front-end are on different servers, you need this.
*   [dj-rest-auth (⭐1.4k)](https://github.com/jazzband/dj-rest-auth) - Authentication for Django Rest Framework.
*   [django-rest-knox (⭐997)](https://github.com/James1345/django-rest-knox) - Authentication Module for django-rest-auth.
*   [djoser (⭐2.4k)](https://github.com/sunscrapers/djoser) - REST implementation of Django auth.
*   [djaq (⭐67)](https://github.com/paul-wolf/djaq) - An instant remote API to Django models with a powerful query language.
*   [django-rest-framework-simplejwt (⭐3.6k)](https://github.com/davesque/django-rest-framework-simplejwt) - JSON web tokens for DRF.
*   [django-webpack-loader (⭐2.5k)](https://github.com/owais/django-webpack-loader) - Transparently use webpack with Django.
*   [drf-yasg (⭐3.2k)](https://github.com/axnsan12/drf-yasg) - Automated generation of real Swagger/OpenAPI 2.0 schemas from Django REST Framework code.
*   [graphene-django (⭐4.2k)](https://github.com/graphql-python/graphene-django) - GraphQL for Django.
*   [graphene-django-filter (⭐16)](https://github.com/devind-team/graphene-django-filter) - Advanced filters implementing and/or/not operators in GraphQL for Django.
*   [django-ninja](https://django-ninja.rest-framework.com/) - Django Ninja - Fast Django REST framework based on type annotations.
*   [django-tastypie (⭐3.9k)](https://github.com/django-tastypie/django-tastypie) - Creating delicious APIs for Django apps since 2010.
*   [drf-spectacular (⭐1.9k)](https://github.com/tfranzel/drf-spectacular) - Sane and flexible OpenAPI 3 schema generation for Django REST framework.

<!--lint enable double-link-->

### Async

*   [channels (⭐5.8k)](https://github.com/django/channels/) - Async support for Django.
*   [starlette (⭐8.8k)](https://github.com/encode/starlette) - ASGI framework.

### Caching

*   [django-cachalot (⭐1.1k)](https://github.com/noripyt/django-cachalot) - Caches your Django ORM queries and automatically invalidates them.
*   [django-cacheops (⭐1.9k)](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.

### Commands

*   [django-extensions (⭐6.2k)](https://github.com/django-extensions/django-extensions/) - Custom management extensions, notably `runserver_plus` and `shell_plus`.
*   [django-click (⭐228)](https://github.com/GaretJax/django-click) - Write Django management commands using the click CLI library.
*   [django-dbbackup (⭐802)](https://github.com/django-dbbackup/django-dbbackup) - Management commands to help backup and restore your project database and media files.
*   [django-liquidb (⭐15)](https://github.com/Gusakovskiy/django-liquidb) - Django application to simplify migration management and changes in states of db scheme.

### Configuration

<!--lint disable double-link-->

*   [confidential (⭐70)](https://github.com/candidco/confidential) - Manage configs and secrets (with CLI support).
*   [django-environ (⭐2.8k)](https://github.com/joke2k/django-environ) - Environment variables.
*   [django-split-settings (⭐1k)](https://github.com/sobolevn/django-split-settings) - Organize multiple settings files.
*   [django-constance (⭐1.6k)](https://github.com/jazzband/django-constance) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.
*   [django-configurations (⭐1k)](https://github.com/jazzband/django-configurations) - eases Django project configuration by relying on the composability of Python classes and following principles of [the twelve-factor app](https://12factor.net/config).
*   [dynaconf](https://www.dynaconf.com/django/) - Dynaconf loads django settings from multiple sources (multiple file formats, env vars, redis, vault, etcd), manages secrets, and allows for different merging strategies all following [the twelve-factor app](https://12factor.net/config).
*   [django-extra-settings (⭐392)](https://github.com/fabiocaccamo/django-extra-settings) - Config and manage typed extra settings using just the django admin.
*   [environs (⭐1k)](https://github.com/sloria/environs) - Simplified environment variable parsing that comes with a [Django helper (⭐1k)](https://github.com/sloria/environs#usage-with-django) that installs additional packages.

<!--lint enable double-link-->

### Content Management Systems

<!--lint disable double-link-->

*   [wagtail (⭐16k)](https://github.com/wagtail/wagtail) - Popular Django content management system (CMS). See [awesome-wagtail (⭐1.8k)](https://github.com/springload/awesome-wagtail) too.
*   [mezzanine (⭐4.7k)](https://github.com/stephenmcd/mezzanine) - CMS framework.
*   [django-cms (⭐9.6k)](https://github.com/divio/django-cms) - CMS for Django.
*   [feincms (⭐870)](https://github.com/feincms/feincms) - An extensible Django-based CMS.
*   [puput (⭐579)](https://github.com/APSL/puput) - Blog app features with Wagtail.

<!--lint enable double-link-->

### Database Connectors

*   [djongo (⭐1.8k)](https://github.com/doableware/djongo) - Django and MongoDB database connector.

### ECommerce

*   [saleor (⭐81)](https://github.com/mirumee/saleor) - GraphQL-based Django E-Commerce Platform.
*   [django-shop (⭐3.1k)](https://github.com/awesto/django-shop) - Django-based shop system.
*   [shuup (⭐2.1k)](https://github.com/shuup/shuup) - Django E-Commerce Platform.
*   [django-oscar (⭐5.9k)](https://github.com/django-oscar/django-oscar) - Domain-driven e-commerce for Django.

### Editors

<!--lint ignore awesome-list-item-->

*   [django-ckeditor (⭐2.3k)](https://github.com/shaunsephton/django-ckeditor) - Django admin CKEditor integration.
*   [django-markdownx (⭐789)](https://github.com/adi-/django-markdownx) - Comprehensive Markdown plugin built for Django.
*   [django-markdown-editor (⭐732)](https://github.com/agusmakmun/django-markdown-editor) - Awesome Django Markdown Editor, supported for Bootstrap & Semantic-UI.
*   [django-business-logic (⭐190)](https://github.com/dgk/django-business-logic) - Visual DSL framework for Django.
*   [django-quill-editor (⭐173)](https://github.com/LeeHanYeong/django-quill-editor) - Makes Quill.js easy to use on Django Forms and admin sites.
*   [django-summernote (⭐984)](https://github.com/summernote/django-summernote) - Summernote is a simple WYSIWYG editor.
*   [django-tinymce (⭐1.2k)](https://github.com/jazzband/django-tinymce) - TinyMCE integration for Django.
*   [django-prose (⭐147)](https://github.com/withlogicco/django-prose) - A light weight editor to content creation.
*   [django-ace (⭐125)](https://github.com/django-ace/django-ace) - ACE integration for Django.

### Files/Images

*   [django-cleanup (⭐982)](https://github.com/un1t/django-cleanup) - Zero configuration file/image removal for local and remote files.
*   [django-imagekit (⭐2.2k)](https://github.com/matthewwithanm/django-imagekit) - Django app for processing images for thumbnail, black-and-white and sizes.
*   [django-pictures (⭐160)](https://github.com/codingjoe/django-pictures) - Responsive cross-browser image library using modern codes like AVIF & WebP.
*   [sorl-thumbnail (⭐1.7k)](https://github.com/jazzband/sorl-thumbnail) - Thumbnails for Django.

### Forms

*   [django-bleach (⭐131)](https://github.com/marksweb/django-bleach/) - Integrate bleach into forms and models.
*   [django-crispy-forms (⭐4.8k)](https://github.com/django-crispy-forms/django-crispy-forms/) - DRY Django forms.
*   [django-floppyforms (⭐827)](https://github.com/jazzband/django-floppyforms) - Full control of form rendering.
*   [django-formtools (⭐701)](https://github.com/jazzband/django-formtools) - For form previous and multi-step forms, previously part of Django until 1.8.
*   [django-widget-tweaks (⭐1.9k)](https://github.com/jazzband/django-widget-tweaks) - Tweak form field rendering in templates.
*   [django-autocomplete-light (⭐1.7k)](https://github.com/yourlabs/django-autocomplete-light) - Add autocompletion to forms.
*   [django-shapeshifter (⭐170)](https://github.com/kennethlove/django-shapeshifter) - A class-based view to handle multiple forms in one view.

### Full-stack frameworks

*   [ReactPy (⭐7.2k)](https://github.com/reactive-python/reactpy) - It's React, but in Python. Insert dynamically rendered Python into Django templates using the [ReactPy-Django module (⭐240)](https://github.com/reactive-python/reactpy-django).
*   [Reactor (⭐586)](https://github.com/edelvalle/reactor/) - Phoenix LiveView, but for Django.
*   [Sockpuppet](https://sockpuppet.argpar.se/) - Build reactive applications with the Django tooling you already know and love.
*   [Unicorn](https://www.django-unicorn.com/) - A reactive component framework that progressively enhances a normal Django view, makes AJAX calls in the background, and dynamically updates the DOM.
*   [iommi (⭐539)](https://github.com/TriOptima/iommi) - Toolkit for development of CRUD applications without writing HTML or JavaScript.

### General

*   [django-data-browser (⭐257)](https://github.com/tolomea/django-data-browser) - Interactive, user-friendly database explorer.
*   [django-filter (⭐4.2k)](https://github.com/carltongibson/django-filter) - Powerful filters based on Django QuerySets.
*   [django-guardian (⭐3.5k)](https://github.com/django-guardian/django-guardian) - Per object permissions in Django.
*   [django-sql-explorer (⭐2.2k)](https://github.com/groveco/django-sql-explorer) - Share data via SQL queries.
*   [django-tables2 (⭐1.7k)](https://github.com/jieter/django-tables2) - HTML tables with pagination/sorting.
*   [django-maintenance-mode (⭐407)](https://github.com/fabiocaccamo/django-maintenance-mode) - Shows a 503 error page when maintenance-mode is on.
*   [django-freeze (⭐88)](https://github.com/fabiocaccamo/django-freeze) - Convert your dynamic django site to a static one with one line of code.
*   [Weblate (⭐3.9k)](https://github.com/WeblateOrg/weblate) - Weblate is a copylefted libre software web-based continuous localization system, used by over 2500 libre projects and companies in more than 165 countries.

### Logging

*   [django-guid (⭐371)](https://github.com/JonasKs/django-guid) - Inject a GUID (Correlation-ID) into every log message in a Django request.
*   [DRF-API-Logger (⭐263)](https://github.com/vishalanandl177/DRF-API-Logger) - An API Logger for your Django Rest Framework project.

### Model Fields

*   [django-any-urlfield (⭐43)](https://github.com/edoburu/django-any-urlfield) - An improved URL selector to choose between internal models and external URLs.
*   [django-colorfield (⭐519)](https://github.com/fabiocaccamo/django-colorfield) - Color field for django models with a nice color-picker widget.
*   [django-model-utils (⭐2.5k)](https://github.com/jazzband/django-model-utils) - Django model mixins and utilities.
*   [django-money (⭐1.5k)](https://github.com/django-money/django-money) - Money fields for forms/models.
*   [django-phonenumber-field (⭐1.4k)](https://github.com/stefanfoulis/django-phonenumber-field) - Model/form field for normalized phone numbers.
*   [django-streamfield (⭐101)](https://github.com/raagin/django-streamfield) - Simple StreamField for plain Django admin (based on Wagtail CMS StreamField idea).

### Models

*   [django-lifecycle (⭐1.2k)](https://github.com/rsinger86/django-lifecycle) - Declarative model lifecycle hooks, an alternative to Signals.
*   [django-mptt (⭐2.8k)](https://github.com/django-mptt/django-mptt) - Modified Preorder Tree Traversal; working with trees of Model instances.
*   [django-taggit (⭐3.1k)](https://github.com/jazzband/django-taggit/) - Simple model tags.
*   [django-reversion (⭐2.9k)](https://github.com/etianen/django-reversion) - Version control for model instances.
*   [django-simple-history (⭐2k)](https://github.com/jazzband/django-simple-history) - Store model history and view/revert changes from the admin.
*   [django-polymorphic (⭐1.5k)](https://github.com/django-polymorphic/django-polymorphic) - Django-polymorphic simplifies using inherited models in Django projects.
*   [django-recurrence (⭐440)](https://github.com/django-recurrence/django-recurrence) - Utility for working with recurring dates in Django.
*   [django-treenode (⭐502)](https://github.com/fabiocaccamo/django-treenode) - Abstract model/admin for tree based stuff.

### Performance

*   [django-perf-rec](https://cur.at/GHUO6cn?m=web) - Keep detailed records of the performance of your Django code.
*   [New Relic](https://newrelic.com/python/django) - Time middleware, views, and SQL queries.
*   [Scout](https://docs.scoutapm.com/#django) - Time middleware, template rendering, and SQL queries with automatic N+1 detection.
*   [django-query-profiler (⭐129)](https://github.com/django-query-profiler/django-query-profiler) - Django query profiler to help resolve N+1 queries.
*   [django-silk (⭐4.1k)](https://github.com/jazzband/django-silk) - Live profiling and inspection of HTTP requests and database queries.
*   [py-spy (⭐11k)](https://github.com/benfred/py-spy) - Sampling profiler for Python programs.
*   [pyinstrument (⭐5.6k)](https://github.com/joerick/pyinstrument) - Call stack profiler for Python, Django, Flask, FastAPI.

### Search

*   [django-haystack (⭐3.5k)](https://github.com/django-haystack/django-haystack) - Modular search for Django.
*   [django-watson (⭐1.1k)](https://github.com/etianen/django-watson) - Full-text search plugin.
*   [django-admin-search (⭐71)](https://github.com/shinneider/django-admin-search) - Modal filter for django admin.

### Search Engine Optimisation

*   [django-check-seo (⭐128)](https://github.com/kapt-labs/django-check-seo) - Check SEO of pages.

### Security

*   [django-csp (⭐492)](https://github.com/mozilla/django-csp) - Adds [Content-Security-Policy](http://www.w3.org/TR/CSP/) headers to Django.
*   [django-feature-policy (⭐84)](https://github.com/adamchainz/django-feature-policy) - Set the draft security HTTP header `Feature-Policy` on a Django app.
*   [django-protected-media (⭐58)](https://github.com/cobusc/django-protected-media) - Manages media that are considered sensitive in a protected fashion.
*   [DJ Checkup](https://djcheckup.com) - Runs several checks on your deployed Django site to check for common security mistakes.

### Static Assets

*   [django-storages (⭐2.5k)](https://github.com/jschneier/django-storages) - A single library to support multiple custom storage backends for Django.
*   [django-compressor (⭐2.7k)](https://github.com/django-compressor/django-compressor/) - Compress JavaScript/CSS into a single cached file.
*   [easy-thumbnails (⭐1.3k)](https://github.com/SmileyChris/easy-thumbnails) - Image thumbnails for Django.
*   [whitenoise (⭐2.3k)](https://github.com/evansd/whitenoise) - Simplified static file serving for Python websites.

### Task Queues

*   [beatserver (⭐137)](https://github.com/rajasimon/beatserver) - A periodic task scheduler for Django.
*   [django-q (⭐1.8k)](https://github.com/Koed00/django-q) - A multiprocessing distributed task queue.
*   [django-rq (⭐1.7k)](https://github.com/rq/django-rq) - Integration for Redis Queue.
*   [django-redis (⭐2.7k)](https://github.com/niwinz/django-redis) - Full-featured Redis cache backend for Django.
*   [celery (⭐22k)](https://github.com/celery/celery) - Robust and broker-agnostic task queues for bigger, performance-focused projects.
*   [flower (⭐5.9k)](https://github.com/mher/flower) - Flower is a web-based tool for monitoring and administrating Celery clusters.
*   [django-celery-beat (⭐1.4k)](https://github.com/celery/django-celery-beat) - A periodic task scheduler with database configured by Django's Admin Panel.
*   [celery-exporter (⭐304)](https://github.com/danihodovic/celery-exporter) - Prometheus & Grafana monitoring of Celery tasks.
*   [django-dramatiq (⭐300)](https://github.com/Bogdanp/django_dramatiq) - Task processing library with a focus on simplicity, reliability, and performance.

### Testing

*   [django-debug-toolbar (⭐7.7k)](https://github.com/jazzband/django-debug-toolbar/) - Configurable panels to debug requests/responses.
*   [pytest-django (⭐1.2k)](https://github.com/pytest-dev/pytest-django) - Use pytest features in Django.
*   [django-test-migrations (⭐456)](https://github.com/wemake-services/django-test-migrations) - Test django schema and data migrations, including migrations' order.
*   [django-test-plus (⭐581)](https://github.com/revsys/django-test-plus/) - Useful additions to Django's default TestCase.
*   [factory-boy (⭐3.2k)](https://github.com/FactoryBoy/factory_boy) - Test fixtures replacement.
*   [django-waffle (⭐1k)](https://github.com/django-waffle/django-waffle) - A feature flipper for Django.
*   [model-bakery (⭐724)](https://github.com/model-bakers/model_bakery) - Object factory for Django (rename of legacy Model Mommy project).
*   [django-fakery (⭐109)](https://github.com/fcurella/django-fakery) - An easy-to-use implementation of Creation Methods for Django, backed by Faker.
*   [drf-openapi-tester (⭐121)](https://github.com/snok/drf-openapi-tester) - Django test utility for validating Swagger 2.0 and OpenAPI 3.0 documentation.
*   [django-google-optimize (⭐41)](https://github.com/adinhodovic/django-google-optimize) - Django application designed to make running server side Google Optimize A/B tests easy.
*   [django-pattern-library (⭐298)](https://github.com/torchbox/django-pattern-library) - Pattern library generator for Django templates, to help testing of UI components.

### URLs

*   [dj-database-url (⭐1.4k)](https://github.com/jacobian/dj-database-url) - Database URLs.
*   [urlman (⭐115)](https://github.com/andrewgodwin/urlman) - A nicer way to do URLs for Django models.
*   [django-robots (⭐446)](https://github.com/jazzband/django-robots) - This is a basic Django application to manage robots.txt files following the robots exclusion protocol, complementing the Django Sitemap contrib app.
*   [django-redirects (⭐59)](https://github.com/fabiocaccamo/django-redirects) - Redirects as they should be, with full control.

### Users

*   [django-allauth (⭐8.4k)](https://github.com/pennersr/django-allauth/) - Improved user registration including social auth.
*   [django-improved-user (⭐132)](https://github.com/jambonsw/django-improved-user) - A custom Django user that authenticates via email. Follows identity and authentication best practices.
*   [django-organizations (⭐1.2k)](https://github.com/bennylope/django-organizations/) - Multi-user accounts for Django projects.
*   [django-cas-ng (⭐363)](https://github.com/django-cas-ng/django-cas-ng) - Django-cas-ng is Django CAS (Central Authentication Service) 1.0/2.0/3.0 client library to support SSO (Single Sign On) and Single Logout (SLO).

### Views

*   [django-braces (⭐1.9k)](https://github.com/brack3t/django-braces) - Reusable, generic mixins.
*   [django-easy-audit (⭐592)](https://github.com/soynatan/django-easy-audit) - Keep track of user actions.
*   [django-extra-views (⭐1.3k)](https://github.com/AndrewIngram/django-extra-views) - Extra class-based generic views.
*   [django-vanilla-views (⭐971)](https://github.com/tomchristie/django-vanilla-views) - Simpler class-based views in Django.
*   [django-stronghold (⭐391)](https://github.com/mgrouchy/django-stronghold) - Makes all your Django views default login\_required.

## Python Packages

*A short list of Python packages that work well with Django.*

*   [bleach (⭐2.6k)](https://github.com/mozilla/bleach) - Sanitize your inputs/forms.
*   [black (⭐35k)](https://github.com/psf/black) - Uncompromising Python code formatter.
*   [coveragepy (⭐2.7k)](https://github.com/nedbat/coveragepy) - Code coverage measurement.
*   [faker (⭐16k)](https://github.com/joke2k/faker) - Faker is a Python package that generates fake data for you.
*   [huey (⭐4.7k)](https://github.com/coleifer/huey) - A little task queue for Python.
*   [nplusone (⭐943)](https://github.com/jmcarp/nplusone) - Auto-detect n+1 queries.
*   [pillow (⭐11k)](https://github.com/python-pillow/Pillow) - Python Imaging Library.
*   [pytest (⭐11k)](https://github.com/pytest-dev/pytest/) - Testing framework.
*   [python-decouple (⭐2.6k)](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code.
*   [python-slugify (⭐1.4k)](https://github.com/un33k/python-slugify) - Returns unicode slugs.
*   [sentry-python (⭐1.6k)](https://github.com/getsentry/sentry-python) - Error reporting SDK.

## Resources

### Official Resources

<!--lint ignore double-link--> 

*   [Project Website](https://www.djangoproject.com/) - Official Django website.
*   [Documentation](https://docs.djangoproject.com/en/dev/) - Comprehensive documentation for all Django versions.
*   [Polls Tutorial](https://docs.djangoproject.com/en/dev/intro/tutorial01/) - Build a polls tutorial while learning Django internals.
*   [Source Code (⭐74k)](https://github.com/django/django/) - Hosted on GitHub.

### Educational

*   [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) - Use function-based views to build a blog app.
*   [LearnDjango](https://learndjango.com/) - Tutorials and premium courses on Django and Django REST Framework.
*   [Adam Johnson](https://adamj.eu/tech/) - Adam is on the Technical Board of Django and regularly writes tutorials.
*   [TestDriven](https://testdriven.io/blog/) - Multiple Django-specific tutorials on topics like Docker, payments, and more.
*   [Classy Class-Based Views](https://ccbv.co.uk/) - Detailed descriptions of methods/properties/attributes for each generic class-based view.
*   [Classy Django Forms (⭐24)](https://github.com/ana-balica/classy-django-forms) - Detailed descriptions of methods/properties/attributes for each form class.
*   [Classy Django REST Framework](http://www.cdrf.co) - Detailed descriptions with methods/attributes for DRF class-based views and serializers.
*   [Simple is Better than Complex](https://simpleisbetterthancomplex.com/) - Regularly updated website with many tutorials and tips on Django.
*   [Full Stack Python's Django Page](https://www.fullstackpython.com/django.html) - Explanation of Django philosophy and links to other resources and tutorials.
*   [RealPython](https://realpython.com/tutorials/django/) - Many high-quality tutorials on Django.
*   [Mozilla Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) - Create a lending library app.
*   [Matt Layman](https://www.mattlayman.com) - Regular tutorials and deep-dives on Django topics.
*   [Django Sites](https://www.djangosites.org/) - Comprehensive listing of sites built with Django.
*   [Django Styleguide (⭐4.1k)](https://github.com/HackSoftware/Django-Styleguide) - Styleguide for Django with best practices and examples.
*   [Django Template Tags and Filters](https://www.djangotemplatetagsandfilters.com/) - Additional docs on Django's 57 built-in template filters and 27 template tags.
*   [Django for Everybody](https://www.dj4e.com/) - A complete course for webdev beginners focused on Django.
*   [CS50W](https://cs50.harvard.edu/web/2020/) - Harvard's University introductory course to web development, it explains Django as backend framework.

### Community

<!--lint disable double-link-->

*   [Django Forum](https://forum.djangoproject.com/) - Official Discourse board.
*   [Community Page](https://www.djangoproject.com/community/) - Featuring feeds of Community Blog Posts, Jobs, and more.
*   [Django Users Google Group](https://groups.google.com/forum/#!forum/django-users/) - Very active discussion board for questions/answers.
*   [Developers Google Group](https://groups.google.com/forum/#!forum/django-developers/) - For contributions to Django itself only.
*   [Twitter](https://twitter.com/djangoproject/) - For official announcements on updates, security fixes, etc.
*   [Discord Server](https://discord.com/invite/xcRH6mN4fa) - Django Discord Community.
*   IRC Channel - Chat with other Django users at irc://irc.freenode.net/django.

<!--lint enable double-link-->

### Conferences

*   [DjangoCon US](https://djangocon.us/) ([YouTube Channel](https://www.youtube.com/channel/UC0yY6a79pPY9J0ShIHRf6yw))
*   [DjangoCon Europe](https://djangocon.eu/) ([YouTube Channel](https://www.youtube.com/user/djangoconeurope))
*   [DjangoCon AU](https://djangocon.com.au/)
*   [DjangoCon Africa](https://djangocon.africa/)
*   [Django Day Copenhagen (⭐7.6k)](https://github.com/wsvincent/awesome-django#conferences)
*   [PyCon US](https://us.pycon.org/2020/) ([YouTube Channel](https://www.youtube.com/channel/UCsX05-2sVSH7Nx3zuk3NYuQ))
*   [PyCon Australia](https://2019.pycon-au.org/) ([YouTube Channel](https://www.youtube.com/user/PyConAU))
*   [Euro Python](https://ep2019.europython.eu/) ([YouTube Channel](https://www.youtube.com/user/PythonItalia))
*   [Django Under the Hood](https://www.youtube.com/channel/UC9T1dhIlL_8Va9DxvKRowBw/videos)
*   [Complete listing of all PyCons globally](https://pycon.org)

### Newsletters

*   [Django News](https://django-news.com) - Weekly newsletter on announcements, articles, projects, and talks.

### Podcasts

*   [Django Chat](https://djangochat.com/) - A weekly podcast from William Vincent and Django Fellow Carlton Gibson with discussions of core Django concepts and regular guests.
*   [Django Riffs](https://djangoriffs.com) - A new podcast from Matt Layman.
*   [Running in Production](https://runninginproduction.com/tags/django) - Focused on tech stacks with many episodes specifically on Django.
*   [TalkPython](https://talkpython.fm/) - The leading Python podcast with several episodes on Django.
*   [Podcast Init](https://www.pythonpodcast.com/) - A popular Python podcast that features Django guests on occasion.

### Books

*Django 4.2*

*   [Django for Beginners: Build websites with Python and Django](https://djangoforbeginners.com/)

*Django 4.0*

*   [Boost Your Django DX](https://adamchainz.gumroad.com/l/byddx)
*   [Django for APIs: Build web APIs with Python and Django](https://djangoforapis.com/)
*   [Django for Professionals: Production websites with Python and Django](https://djangoforprofessionals.com/)
*   [Django 4 By Example: Build powerful and reliable Python web applications from scratch](https://www.amazon.com/dp/1801813051/)

*Django 3.2*

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

*   [cookiecutter-django (⭐11k)](https://github.com/pydanny/cookiecutter-django/) - A full-bodied starter project, highly customizable.
*   [django-base-site (⭐277)](https://github.com/epicserve/django-base-site/) - A Django site with many common third-party packages pre-installed.
*   [djangox (⭐1.8k)](https://github.com/wsvincent/djangox/) - Batteries included starter project for Pip, Pipenv, or Docker.
*   [DRFx (⭐452)](https://github.com/wsvincent/drfx/) - A DRF starter with user auth, Pipenv, and other goodies.
*   [django-project-template (⭐690)](https://github.com/jpadilla/django-project-template) - A deliberately basic project that has multiple staging environments and Heroku deployment config.
*   [docker-django (⭐177)](https://github.com/erroneousboat/docker-django/) - A quick starter guide for Django and Docker together.
*   [django-docker-template (⭐121)](https://github.com/amerkurev/django-docker-template) - Dockerized Django with Postgres, Gunicorn, and Traefik (with auto renew Let's Encrypt).
*   [django-startproject (⭐122)](https://github.com/jefftriplett/django-startproject) - Django start project template with batteries.
*   [wemake-django-template (⭐1.8k)](https://github.com/wemake-services/wemake-django-template/) - Bleeding edge Django template focused on code quality and security.
*   [django-webpack-starter (⭐58)](https://github.com/khadegd/django-webpack-starter) - Django Webpack starter template for using Webpack 4.
*   [sos-django-template (⭐19)](https://github.com/erayerdin/sos-django-template) - Django starter template with separate dev and production settings.
*   [django-docker-heroku-template (⭐31)](https://github.com/bfirsh/django-docker-heroku-template) - A template with Docker, GitHub Actions, and Heroku set up for dev/test/prod, plus various other best practices.
*   [cookiecutter-vue-django (⭐148)](https://github.com/ilikerobots/cookiecutter-vue-django) - Django + Vue starter project fusing Vue SFCs & Django Templates.
*   [launchr (⭐220)](https://github.com/jayfk/launchr) - Launchr is a specialized Django starter template for SaaS web apps.

### Open Source Projects

*   [Blog app with users and forms (⭐990)](https://github.com/wsvincent/djangoforbeginners/tree/master/ch7-blog-app-with-users/)
*   [Newspaper app with custom user model, full user auth (⭐990)](https://github.com/wsvincent/djangoforbeginners/tree/master/ch15-comments)
*   [pythonic-news (⭐466)](https://github.com/sebst/pythonic-news) - Hacker News clone.
*   [Behavior-Driven Development with Aloe (⭐32)](https://github.com/testdrivenio/django-aloe-bdd/)
*   [Image Sharing Blog (⭐54)](https://github.com/MeNsaaH/soMedia)
*   [Bootcamp: An enterprise social network (⭐2.2k)](https://github.com/vitorfs/bootcamp)
*   [Zulip (⭐19k)](https://github.com/zulip/zulip/) - Open-source team chat.
*   [Django-CRM (⭐1.6k)](https://github.com/MicroPyramid/Django-CRM/) - Open Source Python CRM based on Django.
*   [django-job-portal (⭐448)](https://github.com/manjurulhoque/django-job-portal) - Job portal application using Django.
*   [Built with Django](https://builtwithdjango.com) - Curated list of awesome Django projects.
*   [PostHog (⭐14k)](https://github.com/PostHog/posthog) - Open-source product analytics.
*   [HyperKitty](https://gitlab.com/mailman/hyperkitty) - A web interface to access GNU Mailman v3 archives.
*   [Healthchecks (⭐6.7k)](https://github.com/healthchecks/healthchecks) - A Cron Monitoring Tool written in Python & Django.
*   [Flagsmith (⭐3.2k)](https://github.com/Flagsmith/flagsmith) - Open-source Feature Flagging, Remote Config, and AB testing.

## Django REST Framework

*The most popular way to build web APIs with Django.*

### DRF Resources

<!--lint disable double-link-->

*   [Official Documentation](https://www.django-rest-framework.org/)
*   [DRF Source Code (⭐27k)](https://github.com/encode/django-rest-framework)
*   [awesome-django-rest-framework (⭐1.2k)](https://github.com/nioperas06/awesome-django-rest-framework)

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

*   [Official Documentation](https://wagtail.io/)
*   [Wagtail Source Code (⭐16k)](https://github.com/wagtail/wagtail/)
*   [awesome-wagtail (⭐1.8k)](https://github.com/springload/awesome-wagtail)
*   [This week in Wagtail](https://wagtail.io/this-week-in-wagtail/) - A (most) weekly email with updates from the Wagtail core team.
*   [Wagtail Space](https://www.wagtail.space/) - Wagtail CMS events around the world.

<!--lint enable double-link-->

