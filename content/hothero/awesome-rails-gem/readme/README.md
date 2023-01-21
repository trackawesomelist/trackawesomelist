# Awesome Rails Gem Overview

A collection of awesome Ruby Gems for Rails development.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/hothero/awesome-rails-gem/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 hothero/awesome-rails-gem](https://github.com/hothero/awesome-rails-gem) · ⭐ 2.8K · 🏷️ Back-End Development

[ [Daily](/content/hothero/awesome-rails-gem/README.md) / [Weekly](/content/hothero/awesome-rails-gem/week/README.md) / Overview ]

---

# Awesome Rails Gem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails product/service.

*   [Rails Gem List](#rails-gem-list)
    *   [User](#user)
    *   [Active Record](#active-record)
    *   [Plugins](#plugins)
    *   [API](#api)
    *   [Email](#email)
    *   [File Uploading](#file-uploading)
    *   [Searching](#searching)
    *   [Scheduled/Recurrence Jobs](#scheduledrecurrence-jobs)
    *   [View Helper](#view-helper)
    *   [Environment Variables](#environment-variables)
    *   [Admin Panel](#admin-panel)
    *   [Logging](#logging)
    *   [Debug](#debug)
    *   [Coding Style](#coding-style)
    *   [Testing](#testing)
    *   [Production](#production)
    *   [Error Logging](#error-logging)
    *   [Database](#database)

## User

### Authentication

*   [Devise (⭐23k)](https://github.com/plataformatec/devise/) - Devise is a flexible authentication solution for Rails based on Warden.
*   [Knock (⭐2.1k)](https://github.com/nsarno/knock) - Seamless JWT authentication for Rails API.
*   [Clearance (⭐3.6k)](https://github.com/thoughtbot/clearance) - Rails authentication with email & password.
*   [Devise token auth (⭐3.4k)](https://github.com/lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs.
*   [Sorcery (⭐1.3k)](https://github.com/Sorcery/sorcery) - Magical Authentication for Rails. Supports ActiveRecord, DataMapper, Mongoid and MongoMapper.

### Authorization

*   [Pundit (⭐7.8k)](https://github.com/elabs/pundit) - Pundit provides a set of helpers which guide you in leveraging regular Ruby classes and object oriented design patterns to build a simple, robust and scaleable authorization system.
*   [cancancan (⭐5.2k)](https://github.com/CanCanCommunity/cancancan) - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries.
*   [rolify (⭐3k)](https://github.com/RolifyCommunity/rolify) - Role management library with resource scoping.
*   [acl9 (⭐858)](https://github.com/be9/acl9/) - Acl9 is a role-based authorization system that provides a concise DSL for securing your Rails application.

### Omniauth

*   [omniauth-facebook (⭐1.3k)](https://github.com/mkdynamic/omniauth-facebook)
*   [omniauth-google-oauth2 (⭐1.3k)](https://github.com/zquestz/omniauth-google-oauth2)
*   [omniauth-weibo-oauth2 (⭐138)](https://github.com/beenhero/omniauth-weibo-oauth2)
*   [omniauth-twitter (⭐574)](https://github.com/arunagw/omniauth-twitter)
*   [omniauth-github (⭐431)](https://github.com/intridea/omniauth-github)
*   [omniauth-linkedin-oauth2 (⭐110)](https://github.com/decioferreira/omniauth-linkedin-oauth2)

## Active Record

*   [Enumerize (⭐1.7k)](https://github.com/brainspec/enumerize) - Enumerated attributes with I18n and ActiveRecord/Mongoid support. It can be integrated with Simple Form.
*   [counter\_culture (⭐1.7k)](https://github.com/magnusvk/counter_culture) - Turbo-charged counter caches for your Rails app. Huge improvements over the Rails standard counter caches.
*   [custom\_counter\_cache (⭐59)](https://github.com/cedric/custom_counter_cache) - A simple approach to creating a custom counter cache that can be used across multiple models.
*   [Sequenced (⭐370)](https://github.com/djreimer/sequenced) - Sequenced is a simple gem that generates scoped sequential IDs for ActiveRecord models.
*   [FriendlyId (⭐5.9k)](https://github.com/norman/friendly_id) - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.
*   [AASM (⭐4.6k)](https://github.com/aasm/aasm) - State machines for Ruby classes (plain Ruby, Rails Active Record, Mongoid).
*   [PaperTrail (⭐6.4k)](https://github.com/airblade/paper_trail) - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning.
*   [paranoia (⭐2.8k)](https://github.com/rubysherpas/paranoia) - ActiveRecord plugin allowing you to hide and restore records without actually deleting them.
*   [Validates (⭐151)](https://github.com/kaize/validates) - Validates provides collection of useful custom validators for Rails applications, including:
    *   EmailValidator
    *   UrlValidator
    *   SlugValidator
    *   MoneyValidator
    *   IpValidator
    *   AssociationLengthValidator
    *   AbsolutePathValidator
    *   UriComponentValidator
    *   ColorValidator
    *   EanValidator (EAN-8 & EAN-13)
*   [globalize (⭐2.1k)](https://github.com/globalize/globalize) - Rails I18n de-facto standard library for ActiveRecord model/data translation.
*   [deep\_cloneable (⭐750)](https://github.com/moiristo/deep_cloneable) - This gem gives every ActiveRecord::Base object the possibility to do a deep clone that includes user specified associations.
*   [social\_shares (⭐331)](https://github.com/Timrael/social_shares) - Check how many times url was shared in social networks.
*   [public\_activity (⭐2.9k)](https://github.com/chaps-io/public_activity) - Easy activity tracking for models - similar to Github's Public Activity.
*   [goldiloader (⭐1.2k)](https://github.com/salsify/goldiloader) - Automatic ActiveRecord eager loading to reduce the number of database queries run by your application.
*   Tagging
    *   [ActsAsTaggableOn (⭐4.9k)](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.
    *   [closure\_tree (⭐1.7k)](https://github.com/mceachen/closure_tree) - Easily and efficiently make your ActiveRecord models support hierarchies.
*   [ActionStore (⭐393)](https://github.com/rails-engine/action-store) - Store different kind of actions (Like, Follow, Star, Block ...) in one table via ActiveRecord Polymorphic Association.

## Plugins

*   [Spreadsheet (⭐1.1k)](https://github.com/zdavatz/spreadsheet) - Library is designed to read and write Spreadsheet Documents.
*   [Chartkick (⭐6k)](https://github.com/ankane/chartkick) - Chartkick helps your to create beautiful Javascript charts with one line of Ruby.
*   [kaminari (⭐21)](https://github.com/amatsuda/kaminari) - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3 and 4.
*   [CKEditor (⭐2.2k)](https://github.com/galetahub/ckeditor) - CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor. [ckeditor.com](http://ckeditor.com)
*   [HTML::Pipeline (⭐2.2k)](https://github.com/jch/html-pipeline) - GitHub HTML processing filters and utilities. This module includes a small framework for defining DOM based content filters and applying them to user provided content.
*   [Slack Notifier (⭐1.5k)](https://github.com/stevenosloan/slack-notifier) is a simple wrapper to send notifications to [Slack](https://slack.com/) webhooks.
*   [Rails ERD (⭐3.8k)](https://github.com/voormedia/rails-erd) - Generate Entity-Relationship Diagrams for Rails applications.
*   [Parity (⭐876)](https://github.com/thoughtbot/parity) - Shell commands for development, staging, and production parity for Heroku apps.
*   [Airbrussh (⭐509)](https://github.com/mattbrictson/airbrussh) - Airbrussh pretties up your SSHKit and Capistrano output

## API

*   [Grape (⭐9.6k)](https://github.com/ruby-grape/grape) - Microframework to create REST-ful APIs in Ruby.
*   [ActiveModel::Serializers (⭐5.2k)](https://github.com/rails-api/active_model_serializers) - Serializer brings convention over configuration to your JSON generation.
*   [Jbuilder (⭐4.1k)](https://github.com/rails/jbuilder) - Jbuilder gives you a simple DSL for declaring JSON structures that beats massaging giant hash structures. This is particularly helpful when the generation process is fraught with conditionals and loops.
*   [rest-client (⭐5.2k)](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
*   [has\_scope (⭐1.6k)](https://github.com/plataformatec/has_scope) - Map incoming controller parameters to named scopes in your resources.
*   Documentation
    *   [Grape Swagger (⭐1k)](https://github.com/ruby-grape/grape-swagger) - Autogenerate documentation on Grape API.
    *   [Grape Swagger UI (⭐23k)](https://github.com/swagger-api/swagger-ui) - Display documentation that is generated using Grape Swagger.
    *   [apiary](https://apiary.io/) - Work together to quickly design, prototype, document and test APIs.
    *   [apiblueprint](https://apiblueprint.org) - API Documentation with powerful tooling.

## Email

*   [letter\_opener (⭐3.5k)](https://github.com/ryanb/letter_opener) - Preview mail in the browser instead of sending.

## File Uploading

*   [Carrierwave (⭐8.7k)](https://github.com/carrierwaveuploader/carrierwave) - Carrierwave is a classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks.
    *   [carrierwave\_backgrounder (⭐724)](https://github.com/lardawge/carrierwave_backgrounder) - Offload CarrierWave's image processing and storage to a background process using Delayed Job, Resque, Sidekiq, Qu, Queue Classic or Girl Friday.
    *   [CarrierWave Crop (⭐94)](https://github.com/kirtithorat/carrierwave-crop/) - Carrierwave extension to crop uploaded images using Jcrop plugin with preview.
    *   [CarrierWave ImageOptimizer (⭐210)](https://github.com/jtescher/carrierwave-imageoptimizer) - This gem allows you to simply optimize CarrierWave images via jpegoptim or optipng using the image\_optimizer gem.
*   [remotipart (⭐1k)](https://github.com/JangoSteve/remotipart) - Rails jQuery file uploads via standard Rails "remote: true" forms.
*   [MiniMagick (⭐2.7k)](https://github.com/minimagick/minimagick) - MiniMagick is a ruby wrapper for ImageMagick or GraphicsMagick command line.
*   [fog (⭐4.3k)](https://github.com/fog/fog) - Fog is the Ruby cloud services library, top to bottom.
*   [refile (⭐2.5k)](https://github.com/refile/refile) - Refile is a modern file upload library for Ruby applications. It is simple, yet powerful.
*   [Paperclip (⭐9.1k)](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord.
*   [Dragonfly](http://markevans.github.io/dragonfly) - Dragonfly is for on-the-fly file processing - suitable for images or other attachments
*   [shrine (⭐3k)](https://github.com/janko-m/shrine) -File Attachment toolkit for Ruby applications

## Searching

*   [ransack (⭐5.3k)](https://github.com/activerecord-hackery/ransack) - Ransack enables the creation of both simple and advanced search forms for your Ruby on Rails application.
*   [elasticsearch-rails (⭐3k)](https://github.com/elastic/elasticsearch-rails) - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails.
*   [Chewy (⭐1.8k)](https://github.com/toptal/chewy) - High-level Elasticsearch Ruby framework based on the official elasticsearch-ruby client.
*   [pg\_search (⭐967)](https://github.com/Casecommons/pg_search) - pg\_search builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search
*   [sunspot (⭐3k)](https://github.com/sunspot/sunspot) - Sunspot is a Ruby library for expressive, powerful interaction with the Solr search engine. Sunspot is built on top of the RSolr library, which provides a low-level interface for Solr interaction; Sunspot provides a simple, intuitive, expressive DSL backed by powerful features for indexing objects and searching for them.
*   [searchkick (⭐6k)](https://github.com/ankane/searchkick) - Intelligent search made easy with Rails and Elasticsearch.

## Scheduled/Recurrence Jobs

*   [Whenever (⭐8.6k)](https://github.com/javan/whenever) - Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs.
*   [Resque (⭐9.2k)](https://github.com/resque/resque) - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
*   [Rufus-Scheduler (⭐2.3k)](https://github.com/jmettraux/rufus-scheduler) - Rufus-scheduler is a Ruby gem for scheduling pieces of code (jobs). It understands running a job AT a certain time, IN a certain time, EVERY x time or simply via a CRON statement.
*   [Delayed Job (⭐4.7k)](https://github.com/collectiveidea/delayed_job) - Database based asynchronous priority queue system.
*   [Sidekiq (⭐12k)](https://github.com/mperham/sidekiq) - Simple, efficient background processing for Ruby.
    *   [sidetiq (⭐1.2k)](https://github.com/tobiassvn/sidetiq) - Recurring jobs for sidekiq.
    *   [sidekiq-cron (⭐1.6k)](https://github.com/ondrejbartas/sidekiq-cron) - Scheduler / Cron for Sidekiq jobs
    *   [sidekiq-scheduler (⭐1.5k)](https://github.com/Moove-it/sidekiq-scheduler) - Lightweight job scheduler extension for Sidekiq
*   [Sucker Punch (⭐2.6k)](https://github.com/brandonhilkert/sucker_punch) - Sucker punch is a single-process Ruby asynchronous processing library.

## View Helper

*   [formtastic (⭐5.2k)](https://github.com/justinfrench/formtastic) - Formtastic is a Rails FormBuilder DSL (with some other goodies) to make it far easier to create beautiful, semantically rich, syntactically awesome, readily stylable and wonderfully accessible HTML forms in your Rails applications
*   [Simple Form (⭐8k)](https://github.com/plataformatec/simple_form) - Simple form aims to be as flexible as possible while helping you with powerful components to create your forms. The basic goal of Simple Form is to not touch your way of defining the layout, letting you find the better design for your eyes.
*   [Nested Form (⭐1.8k)](https://github.com/ryanb/nested_form) - This is a Rails gem for conveniently manage multiple nested models in a single form. It does so in an unobtrusive way through jQuery or Prototype. It can also be integrated with Simple Form.
*   [meta-tags (⭐2.5k)](https://github.com/kpumuk/meta-tags) - Search Engine Optimization (SEO) plugin for Ruby on Rails applications.
*   [active\_link\_to (⭐826)](https://github.com/comfy/active_link_to) - active\_link\_to adds css 'active' class to your links.
*   [cells (⭐3k)](https://github.com/apotonick/cells) - Cells allow you to encapsulate parts of your UI into components into view models. View models, or cells, are simple ruby classes that can render templates.
*   [i18n Country Code Select (⭐25)](https://github.com/onomojo/i18n_country_select) - I18n Country Code Select Form Helper for Rails 3 & 4.
*   [Subdivision Select (⭐19)](https://github.com/cllns/subdivision_select) - A Rails plugin to populate a state/province select box from country\_select.
*   [cocoon (⭐3.1k)](https://github.com/nathanvda/cocoon) - Dynamic nested forms using jQuery made easy

## Environment Variables

*   [Config (⭐2k)](https://github.com/railsconfig/config) - Multi-environment YAML style configurations that helps easily manage environment specific settings in an easy and usable manner.
*   [Figaro (⭐3.7k)](https://github.com/laserlemon/figaro) - Figaro is very simple, Heroku-friendly Rails app configuration using ENV and a single YAML file.
*   [dotenv (⭐6.2k)](https://github.com/bkeepers/dotenv) - Dotenv is a gem that allows you to set your environment variables in .env file, and it will load it in to ENV.
*   [opsworks-dotenv (⭐8)](https://github.com/mikamai/opsworks-dotenv) - Opsworks-dotenv let you configure the environment for you Rails application using OpsWorks, Chef and Dotenv.

## Admin Panel

*   [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.
    *   [active\_skin (⭐423)](https://github.com/rstgroup/active_skin): Flat skin for active admin.
*   [RailsAdmin (⭐7.7k)](https://github.com/sferik/rails_admin) - RailsAdmin is a Rails engine that provides an easy-to-use interface for managing your data.
*   [Typus](https://github.com/typus/typus) - Typus is a control panel for Ruby on Rails applications to allow trusted users edit structured content.
*   [administrate (⭐5.5k)](https://github.com/thoughtbot/administrate) - A Rails engine that helps you put together a super-flexible admin dashboard.
*   [Trestle (⭐1.8k)](https://github.com/TrestleAdmin/trestle) - A modern, responsive admin framework for Ruby on Rails

## Logging

*   [Impressionist (⭐1.5k)](https://github.com/charlotte-ruby/impressionist) - Impressionist can log page impressions (technically action impressions), but it is not limited to that. You can log impressions multiple times per request. And you can also attach it to a model. The goal of this project is to provide customizable stats that are immediately accessible in your application as opposed to using Google Analytics and pulling data using their API.
*   [Ahoy (⭐3.7k)](https://github.com/ankane/ahoy) - Ahoy provides a solid foundation to track visits and events in Ruby, JavaScript, and native apps.
*   [Lograge (⭐3.2k)](https://github.com/roidrage/lograge) - An attempt to tame Rails' default policy to log everything.

## Debug

*   [byebug (⭐3.3k)](https://github.com/deivid-rodriguez/byebug) - Byebug is a simple to use, feature rich debugger for Ruby 2. It uses the new TracePoint API for execution control and the new Debug Inspector API for call stack navigation, so it doesn't depend on internal core sources.
    *   [pry-byebug (⭐1.9k)](https://github.com/deivid-rodriguez/pry-byebug) - Pry navigation commands via byebug.
*   [pry-rails (⭐1.3k)](https://github.com/rweng/pry-rails) - Avoid repeating yourself, use pry-rails instead of copying the initializer to every rails project. This is a small gem which causes rails console to open pry. It therefore depends on pry.
*   [awesome\_print (⭐4k)](https://github.com/awesome-print/awesome_print) - Awesome Print is a Ruby library that pretty prints Ruby objects in full color exposing their internal structure with proper indentation.
*   [web-console (⭐1.3k)](https://github.com/rails/web-console) - Web Console is a debugging tool for your Ruby on Rails applications.
*   [spring (⭐2.7k)](https://github.com/rails/spring) - Spring is a Rails application preloader. It speeds up development by keeping your application running in the background so you don't need to boot it every time you run a test, rake task or migration.
*   [rails-footnotes (⭐1.5k)](https://github.com/josevalim/rails-footnotes) - Rails footnotes displays footnotes in your application for easy debugging, such as sessions, request parameters, cookies, filter chain, routes, queries, etc.
*   [g (⭐108)](https://github.com/jugyo/g) - The Kernel.g that works like Kernel.p by using terminal-notifier or growl.
*   [terminal-notifier (⭐6k)](https://github.com/julienXX/terminal-notifier) - terminal-notifier is a command-line tool to send Mac OS X User Notifications, which are available in Mac OS X 10.8 and higher.
*   [letter\_opener (⭐3.5k)](https://github.com/ryanb/letter_opener) - Preview email in the default browser instead of sending it. This means you do not need to set up email delivery in your development environment, and you no longer need to worry about accidentally sending a test email to someone else's address.
*   [Better Errors (⭐6.8k)](https://github.com/charliesome/better_errors) - Better errors replaces the standard Rails error page with a much better and more useful error page.
    *   If you would like to use Better Errors' advanced features (REPL, local/instance variable inspection, pretty stack frame names), you need to add the [binding\_ \_of\_\_caller (⭐640)](https://github.com/banister/binding_of_caller).
*   [RailsPanel (⭐3.7k)](https://github.com/dejan/rails_panel) - RailsPanel is a Chrome extension for Rails development that will end your tailing of development.log.

## Coding Style

*   [RuboCop (⭐12k)](https://github.com/bbatsov/rubocop) - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide (⭐16k)](https://github.com/bbatsov/ruby-style-guide).
*   [Rails Best Practice (⭐4.1k)](https://github.com/railsbp/rails_best_practices) - Rails best practice is a code metric tool to check the quality of rails codes.
*   [Metric Fu (⭐608)](https://github.com/metricfu/metric_fu) - A fist full of code metrics
*   [Pronto (⭐2.5k)](https://github.com/mmozuras/pronto) - Quick automated code review of your changes

## Testing

*   [rspec-rails (⭐4.9k)](https://github.com/rspec/rspec-rails) - Rspec-rails is a testing framework for Rails 3.x and 4.x.
*   [Capybara (⭐9.7k)](https://github.com/jnicklas/capybara) - Capybara helps you test web applications by simulating how a real user would interact with your app. And drivers:
    *   [capybara-webkit (⭐2k)](https://github.com/thoughtbot/capybara-webkit) - Capybara-webkit is a capybara driver that uses Webkit via QtWebkit.
    *   [selenium-webdriver (⭐26)](https://github.com/vertis/selenium-webdriver) - Selenium-webdriver provides ruby bindings for WebDriver.
    *   [poltergeist (⭐2.5k)](https://github.com/teampoltergeist/poltergeist) - Poltergeist allows you to run your Capybara tests on a headless WebKit browser, provided by PhantomJS.
    *   [page-object (⭐646)](https://github.com/cheezy/page-object) - Page-object is a simple gem that assists in creating flexible page objects for testing browser based applications.
*   [factory\_bot (⭐7.6k)](https://github.com/thoughtbot/factory_bot) - Factory\_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin\_user, and so on), including factory inheritance.
*   [factory\_bot\_rails (⭐2.9k)](https://github.com/thoughtbot/factory_bot_rails) - Factory\_bot\_rails provides Rails integration for factory\_bot.
*   [factory\_factory\_girl (⭐46)](https://github.com/st0012/factory_factory_girl) - FactoryFactoryGirl lets you generate factory files more efficiently with naming rules.
*   [Database Cleaner (⭐2.8k)](https://github.com/DatabaseCleaner/database_cleaner) - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis.
*   [shoulda-matchers (⭐3.3k)](https://github.com/thoughtbot/shoulda-matchers) - Shoulda-matchers provides serveral matchers for testing common Rails functionality.
*   [ResponseCodeMatchers (⭐57)](https://github.com/r7kamura/response_code_matchers) - ResponseCodeMatchers provides rspec matchers to match http response code.
*   [SimpleCov (⭐4.5k)](https://github.com/colszowka/simplecov) - SimpleCov is a code coverage analysis tool for Ruby.
*   [Timecop (⭐3.2k)](https://github.com/travisjeffery/timecop) - A gem providing "time travel" and "time freezing" capabilities, making it dead simple to test time-dependent code.
*   [VCR (⭐5.4k)](https://github.com/vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.

### Security

*   [brakeman (⭐6.5k)](https://github.com/presidentbeef/brakeman) - Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.
*   [bundle-audit (⭐2.5k)](https://github.com/rubysec/bundler-audit) - bundler-audit is a patch-level verification tool for Bundler which checks for vulnerable versions of gems and insecure gem sources.
*   [Secure Headers (⭐3k)](https://github.com/twitter/secureheaders) -  Secure Headers will automatically apply several headers that are related to security.

## Production

*   [Capistrano (⭐12k)](https://github.com/capistrano/capistrano) - Remote multi-server automation tool.
*   [Slowpoke (⭐280)](https://github.com/ankane/slowpoke) - Rack::Timeout is great. Slowpoke makes it better.
*   [Rack Attack (⭐5.2k)](https://github.com/kickstarter/rack-attack) - Rack middleware to blocking & throttling.
*   [Responders (⭐2k)](https://github.com/plataformatec/responders) - A set of Rails responders to dry up your application.
*   [production\_rails (⭐1.7k)](https://github.com/ankane/production_rails) - Best practices for running Rails in production.
*   [Mina (⭐4.3k)](https://github.com/mina-deploy/mina) - fast deployer and server automation tool.

## Error Logging

*   [Rollbar (⭐433)](https://github.com/rollbar/rollbar-gem) - Exception tracking and logging from Ruby to Rollbar.
*   [Airbrake (⭐934)](https://github.com/airbrake/airbrake) - Notifier gem for integrating apps with Airbrake
*   [Errbit (⭐4.2k)](https://github.com/errbit/errbit) - Open source notifier gem compliant with Airbrake.

## Database

*   [rails\_db (⭐1.4k)](https://github.com/igorkasyanchuk/rails_db) - Rails Database Viewer and SQL Query Runner

## Asset Pipeline

*   [Alaska (⭐54)](https://github.com/mavenlink/alaska) - ExecJS runtime with persistent connection to nodejs, speeds up your coffeescript compilation process during development and deployment.

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/hothero/awesome-rails-gem/blob/master/README.md/contributing.md) first.

