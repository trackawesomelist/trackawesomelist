# Awesome Rest Overview

A collaborative list of great resources about RESTful API architecture, development, test, and performance

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/marmelab/awesome-rest/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 marmelab/awesome-rest](https://github.com/marmelab/awesome-rest) · ⭐ 3.2K · 🏷️ Miscellaneous

[ [Daily](/content/marmelab/awesome-rest/README.md) / [Weekly](/content/marmelab/awesome-rest/week/README.md) / Overview ]

---

# Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collaborative list of great resources about RESTful API architecture, development, test, and performance. Feel free to contribute to this on-going list.

*   [Design](#design)
    *   [Guidelines](#guidelines)
*   [Standards](#standards)
*   [Clients](#clients)
    *   [PHP](#php-clients)
    *   [Client-side JavaScript](#javascript-clients)
    *   [Node.js](#nodejs-clients)
    *   [Ruby](#ruby-clients)
    *   [Go](#go-clients)
    *   [Generators](#generators)
*   [Servers](#servers)
    *   [Directly On Top Of A RMDB](#directly-on-top-of-a-rmdb)
    *   [Node.js](#nodejs)
    *   [PHP](#php)
    *   [Symfony2](#symfony2)
    *   [Python](#python)
    *   [Ruby](#ruby)
    *   [Go](#go)
    *   [Java](#java)
    *   [Haskell](#haskell)
*   [Testing](#testing)
    *   [Querying](#querying)
    *   [Mocking](#mocking)
    *   [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
*   [Documentation](#documentation)
*   [API Gateway](#api-gateway)
*   [SaaS Tools](#saas-tools)
*   [Miscellaneous](#miscellaneous)

## Design

*   [Architectural Styles and
    the Design of Network-based Software Architectures](https://www.ics.uci.edu/\~fielding/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST
*   [HTTP API design guide extracted from work on the Heroku Platform API (⭐14k)](https://github.com/interagent/http-api-design)
*   [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
*   [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
*   [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - Explained by Martin Fowler, originally presented by Leonard Richardson at the [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
*   [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) - Discusses the constraints and flexibility that you have with nonpublic APIs, and lessons learned from doing large scale RESTful integration across multiple teams.
*   [HATEOAS](https://web.archive.org/web/20201111235328/timelessrepo.com/haters-gonna-hateoas) - Clear explanation on what HATEOAS is, and why you should use it.
*   [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)
*   [REST API Tutorial](http://www.restapitutorial.com/) - RestApiTutorial.com is dedicated to tracking REST API best practices and making resources available to enable quick reference and self education for the development crafts-person.
*   [API-Security-Checklist (⭐19k)](https://github.com/shieldfy/API-Security-Checklist) - Best practices about REST API security

### Guidelines

*   [Adidas REST API Guidelines (⭐222)](https://github.com/adidas/api-guidelines/blob/master/rest-api-guidelines/rest.md) - Adidas REST API Guidelines define standards and guidelines for building REST APIs at adidas.
*   [Atlassian REST API design guidelines version 1](https://developer.atlassian.com/server/framework/atlassian-sdk/atlassian-rest-api-design-guidelines-version-1/) - This document provides guidelines to Atlassian developers who are designing REST APIs for Atlassian applications.
*   [Cisco REST API Guide (⭐89)](https://github.com/CiscoDevNet/api-design-guide) - Guidelines for designing REST APIs at Cisco.
*   [Google Cloud API design guide](https://cloud.google.com/apis/design/) - Guidelines Google follows when designing Cloud APIs and other Google APIs (REST APIs and gRPC APIs).
*   [Haufe API Style Guide (⭐187)](https://github.com/Haufe-Lexware/api-style-guide) - Guidelines created by Haufe-Lexware CTO team.
*   [Microsoft REST API Guidelines (⭐20k)](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) - The Microsoft REST API Guidelines, as a design principle, encourages application developers to have resources accessible to them via a RESTful HTTP interface.
*   [Restful API Guidelines by Zalando (⭐1.8k)](https://github.com/zalando/restful-api-guidelines) - Developing Restful APIs: A Comprehensive Set of Guidelines.

## Standards

*   [JSON API](http://jsonapi.org/) - Standard for building APIs in JSON.
*   [RAML](http://raml.org/) - Simple and succinct way to describe RESTful API.
*   [JSend](http://labs.omniti.com/labs/jsend) - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
*   [OData](http://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
*   [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) - Simple format that gives a consistent and easy way to hyperlink between resources in your API.
*   [JSON-LD](http://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
*   [Hydra](http://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
*   [Schema.org](http://schema.org) - Collection of schemas describing common data models.
*   [OpenAPI](https://openapis.org/) - Formerly known as the Swagger Specification, OpenAPI specifcation is the world’s most popular description format for defining Restful APIs.

## Clients

### PHP Clients

*   [Guzzle](http://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services.
*   [Buzz (⭐1.9k)](https://github.com/kriswallsmith/buzz) - Another lightweight HTTP client.
*   [unirest for PHP (⭐1.3k)](https://github.com/Mashape/unirest-php) - Simplified, lightweight HTTP client library.

### JavaScript Clients

*   [restangular (⭐7.9k)](https://github.com/mgonto/restangular) - AngularJS service to handle REST API properly and easily.
*   [restful.js (⭐971)](https://github.com/marmelab/restful.js) - JS client for interacting with server-side RESTful resources.
*   [traverson (⭐424)](https://github.com/basti1302/traverson) - A Hypermedia API/HATEOAS Client for Node.js and the Browser
*   [raml-client-generator (⭐120)](https://github.com/mulesoft/raml-client-generator) - Generates static client libs for js.

### Node.js Clients

*   [restler (⭐2k)](https://github.com/danwrong/restler) - REST client library for node.js.
*   [unirest for Node.js (⭐943)](https://github.com/Mashape/unirest-nodejs) - Simplified, lightweight HTTP client library.

### Ruby Clients

*   [RESTClient (⭐5.2k)](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
*   [Spyke (⭐773)](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner.
*   [excon (⭐1.1k)](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.
*   [httparty (⭐5.6k)](https://github.com/jnunemaker/httparty) - Makes HTTP fun again!
*   [Net::HTTP](http://ruby-doc.org/stdlib/libdoc/net/http/rdoc/Net/HTTP.html) - Net::HTTP provides a rich library which can be used to build HTTP user-agents.
*   [raml-ruby-client-generator (⭐1)](https://github.com/zlx/raml-ruby-client-generator) - Auto generate API client from a RAML file.

### Go Clients

*   [gopencils (⭐440)](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
*   [resty (⭐7.1k)](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.

### Generators

*   [openapi-generator (⭐15k)](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3).

## Servers

### Directly On Top Of A RMDB

*   [postgrest (⭐20k)](https://github.com/begriffs/postgrest) - Serve a fully RESTful API directly from an existing PostgreSQL database.
*   [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.
*   [pREST (⭐3.5k)](https://github.com/prest/prest) - A fully RESTful API from any existing PostgreSQL database written in Go.

### Node.js

*   [node-restify (⭐11k)](https://github.com/restify/node-restify) - Framework specifically meant for REST API.
*   [Sails.js](http://sailsjs.org/) - Node.js Web framework embedding a command to generate automatically a REST API.
*   [mers (⭐344)](https://github.com/jspears/mers) - Express service exposing Mongoose finders as RESTful API.
*   [Baucis (⭐651)](https://github.com/wprl/baucis) - Build scalable REST API based on your Mongoose entities.
*   [flatiron/resourceful (⭐354)](https://github.com/flatiron/resourceful) - Isomorphic Resource engine for JavaScript.
*   [loopback](http://loopback.io/) - Powerful Node.js framework for creating APIs and easily connecting to backend data sources.
*   [Feathers](http://feathersjs.com/) - is a real-time, micro-service web framework that gives you control over your data via RESTful resources, sockets and flexible plug-ins.
*   [Expressa (⭐401)](https://github.com/thomas4019/expressa) - Express middleware for creating APIs from JSON schemas with a simple admin editor and permissions model.
*   [rest-hapi (⭐1.2k)](https://github.com/JKHeadley/rest-hapi) - Generate RESTful API based on mongoose models that supports relational data.
*   [Nestjsx/crud (⭐3.3k)](https://github.com/nestjsx/crud) - Generate CRUD controllers and services for RESTful API with NestJS and TypeORM.

### PHP

*   [Microrest (⭐187)](https://github.com/marmelab/microrest.php) - Micro-web application providing a REST API on top of any relational database.
*   [Negotiation (⭐1.3k)](https://github.com/willdurand/Negotiation) - Content negotiation library.
*   [Drest (⭐88)](https://github.com/leedavis81/drest) - Library for exposing Doctrine entities as REST resource endpoints.
*   [Restler (⭐1.4k)](https://github.com/Luracast/Restler) - Lightweight framework to expose PHP methods as RESTful web API.
*   [HAL (⭐204)](https://github.com/blongden/hal) - Hypertext Application Language (HAL) builder library.
*   [Apigility (⭐450)](https://github.com/zfcampus/zf-apigility-skeleton) - API builder built with Zend Framework 2.
*   [phprest (⭐313)](https://github.com/phprest/phprest) - Specialized REST microframework for PHP.
*   [Hateoas (⭐998)](https://github.com/willdurand/Hateoas) - PHP library to support implementing representations for HATEOAS REST web services.
*   [Fusio (⭐1.2k)](https://github.com/apioo/fusio) - Open source API management platform.

#### Symfony2

*   [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - Complete guide to build a state-of-the-art REST API with Symfony2 framework.
*   [FOSRestBundle (⭐2.7k)](https://github.com/FriendsOfSymfony/FOSRestBundle) - Bundle handling view, routing, error handling, etc. for your REST API.
*   [stanlemon/rest-bundle (⭐123)](https://github.com/stanlemon/rest-bundle) - Build a REST API based on Doctrine entities using conventions over configuration.
*   [lakion/Lionframe](http://lakion.com/lionframe) - Glu between several community libraries to ease API development.
*   [BazingaHateoasBundle (⭐292)](https://github.com/willdurand/BazingaHateoasBundle) - Integrate the [Hateoas (⭐998)](https://github.com/willdurand/Hateoas) library into a Symfony2 application.
*   [Symfony REST Edition (⭐635)](https://github.com/gimler/symfony-rest-edition) - Start with a Symfony2 application with all REST-friendly bundles pre-configured.
*   [NgAdminGeneratorBundle (⭐75)](https://github.com/marmelab/NgAdminGeneratorBundle) - Boostrap ng-admin configuration based on `stanlemon/rest-bundle`.
*   [DunglasApiBundle (⭐2.2k)](https://github.com/dunglas/DunglasApiBundle) - Build a REST API which follow Hydra/JSON-LD specification.
*   [API Platform (⭐7.7k)](https://github.com/api-platform/api-platform) - Specialize Symfony edition for the creation of hypermedia REST APIs.
*   [NelmioApiDocBundle (⭐2.1k)](https://github.com/nelmio/NelmioApiDocBundle) - Generate documentation for your REST API from annotations.

### PowerShell

*   [Pode (⭐556)](https://github.com/Badgerati/Pode) - Pode is an cross-platform, open-source, community-supported web server and REST API framework for PowerShell developers

### Python

*   [Django REST framework](http://www.django-rest-framework.org/) - Powerful and flexible toolkit that makes it easy to build Web APIs.
*   [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
*   [flask-restful](http://flask-restful.readthedocs.org/) - Extension for Flask that adds support for quickly building REST APIs.
*   [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
*   [hug](http://www.hug.rest/) - Lightweight and fast API Framework.
*   [sandman (⭐2.3k)](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.
*   [restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
*   [Python Eve](http://python-eve.org/) - Eve is an open source Python REST API framework designed for human beings. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services.
*   [Ramses](https://ramses.readthedocs.org/en/stable/) - Makes RAML files executable by generating production-ready APIs from them at runtime.
*   [Flask-Potion (⭐491)](https://github.com/biosustain/potion) - Flask-Potion is a powerful Flask extension for building RESTful JSON APIs. It also provides several Clients for easier access to the API.
*   [apistar (⭐5.6k)](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3.
*   [Falcon (⭐9k)](https://github.com/falconry/falcon) - Falcon is a bare-metal Python web API framework for building high-performance microservices, app backends, and higher-level frameworks.
*   [FastAPI (⭐52k)](https://github.com/tiangolo/fastapi) - FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. With automatic API documentation using Swagger UI and ReDoc, based on OpenAPI and JSON Schema.

### Ruby

*   [Grape](http://www.ruby-grape.org) - Opinionated micro-framework for creating REST-like APIs in Ruby.
*   [Rails](http://guides.rubyonrails.org/api_app.html) - RailsGuides: Using Rails for API-only applications.

### Go

*   [gocrud (⭐311)](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
*   [go-json-rest (⭐3.5k)](https://github.com/ant0ine/go-json-rest) - Thin layer on top of `net/http` that helps building RESTful APIs easily.
*   [sleepy (⭐678)](https://github.com/dougblack/sleepy) - RESTful micro-framework written in Go.
*   [restit (⭐55)](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
*   [go-relax (⭐153)](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
*   [go-rest (⭐124)](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
*   [go-restful (⭐4.7k)](https://github.com/emicklei/go-restful) - A declarative highly readable framework for building restful API's.
*   [Goat (⭐156)](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
*   [Resoursea (⭐33)](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
*   [Zerver](https://github.com/cosiner/zerver) - Zerver is a expressive, modular, feature completed RESTful framework.

### Java

*   [RestExpress (⭐939)](https://github.com/RestExpress/RestExpress) - Netty-based, highly performant, lightweight, container-less, plugin-extensible, framework that is ideal for microservice architectures.
*   [Vertx-Web (⭐1k)](https://github.com/vert-x3/vertx-web) - Vert.x-Web is a set of building blocks for building web applications with Vert.x, a toolkit for building reactive applications on the JVM.
*   [Dropwizard (⭐8.3k)](https://github.com/dropwizard/dropwizard) - A framework for developing ops-friendly, high-performance, RESTful web services.

### Scala

*   [Chaos (⭐250)](https://github.com/mesosphere/chaos) - A lightweight framework for writing REST services in Scala.

### Haskell

*   [Rest for Haskell (⭐388)](https://github.com/silkapp/rest) - This package allows you to create REST APIs in Haskell. These APIs can be run in different web frameworks. They can also be used to automatically generate documentation as well as client libraries.

## Testing

### Querying

*   [httpie (⭐25k)](https://github.com/jkbrzt/httpie) - Command line HTTP client, far more dev-friendly than `curl`.
*   [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - Chrome extension essential to test manually REST API.
*   [resty (⭐2.6k)](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines (bash or zsh).
*   [jq (⭐24k)](https://github.com/stedolan/jq) - Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
*   [HttpMaster](http://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.
*   [Http-console (⭐1.4k)](https://github.com/cloudhead/http-console) - Command line interface for HTTP that let you *speak HTTP like a local*
*   [HTTP Prompt (⭐8.6k)](https://github.com/eliangcs/http-prompt) - HTTP Prompt is an interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt\_toolkit.
*   [rest-assured (⭐6.1k)](https://github.com/rest-assured/rest-assured) - Java DSL for easy testing of REST services.
*   [Insomnia (⭐25k)](https://github.com/getinsomnia/insomnia) - Cross-platform HTTP and GraphQL Client
*   [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Make HTTP requests with a simple web-based HTTP client.
*   [TestMace](https://testmace.com) - Cross-platform simple but powerful IDE for API automation testing.
*   [Milkman (⭐853)](https://github.com/warmuuh/milkman) - Extensible cross-platform request/response workbench, not only for http calls.
*   [Schemathesis (⭐1.5k)](https://github.com/schemathesis/schemathesis) - Property-based testing tool for web applications built with Open API and GraphQL specifications.
*   [Step CI (⭐844)](https://github.com/stepci/stepci) - Open-source framework for API Quality Assurance, which tests REST, GraphQL and gRPC automated and from Open API spec.

### Mocking

*   [RequestBin](https://requestbin.com/) - Inspect and debug webhook requests sent by your clients or third-party APIs.
*   [httpbin](http://httpbin.org) - HTTP request and response service - a/k/a Swiss Army Knife for HTTP.
*   [FakeRest (⭐396)](https://github.com/marmelab/FakeRest) - Patch XMLHttpRequest to fake a REST API client-side.
*   [json-server (⭐65k)](https://github.com/typicode/json-server) - Serve a REST API from fixture files using quick prototyping.
*   [Mocky.io](http://www.mocky.io/) - Free online service to create fake HTTP responses.
*   [MockServer](https://www.mock-server.com/) - Easy mocking of any system you integrate with via HTTP or HTTPS.
*   [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - Mock RESTful API based on swagger schema
*   [Request Baskets (⭐188)](https://github.com/darklynx/request-baskets) - Service to collect HTTP requests and inspect them via RESTful API or web UI.
*   [DuckRails (⭐1.7k)](https://github.com/iridakos/duckrails) - Mock quickly & dynamically API endpoints.
*   [Mockoon](https://mockoon.com) - Easily create mock APIs locally. No remote deployment, no account required, open source.
*   [Mockintosh](https://mockintosh.io/) - A mock server generator that's capable to generate RESTful APIs and communicate with the message queues to mimick asynchronous tasks.

### Public REST APIs To Use In Tests

*   [Deck of Cards API](http://deckofcardsapi.com) - Open API for simulating a deck of cards.
*   [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - The world's largest API repository.
*   [Public APIS](https://www.publicapis.com/) - Explore The Largest API Directory In The Galaxy.
*   [Marvel Comics API](http://developer.marvel.com/) - Query characters, stories, events about Marvel superheroes.
*   [JSON Placeholder](http://jsonplaceholder.typicode.com/) - Free online REST service that you can use whenever you need some fake data.
*   [APIs.guru](http://APIs.guru) - Wikipedia for Web APIs, each API has OpenAPI/Swagger description.
*   [The Cat API](http://theCatAPI.com) - Public API for Cats Images, Facts and Jokes.

## Documentation

*   [Swagger](http://swagger.io/) - Documentation/querying web interface for REST APIs.
*   [API doc](http://apidocjs.com/) - Inline Documentation for RESTful web APIs.
*   [raml2html (⭐1.1k)](https://github.com/raml2html/raml2html) - Generates HTML documentation from a RAML file.
*   [ReDoc (⭐19k)](https://github.com/Rebilly/ReDoc/) - OpenAPI/Swagger-powered three-panel documentation.
*   [Slate (⭐35k)](https://github.com/lord/slate) - Beautiful and responsive three-panel API documentation using Middleman.
*   [Optic (⭐1k)](https://github.com/opticdev/optic) - Maintain an accurate API specification without writing OpenAPI/Swagger. Works with any Stack

## API Gateway

*   [Kong (⭐34k)](https://github.com/Kong/kong) - Scalable, distributed, and plugin oriented API gateway backed by Nginx.
*   [Tyk API Gateway (⭐7.9k)](https://github.com/TykTechnologies/tyk) - Lightweight API gateway with analytics logging, written in Go.
*   [API Umbrella (⭐1.8k)](https://github.com/NREL/api-umbrella) - API management platform for exposing web services, with web interface and analytics, written in Lua.
*   [WSO2 API Management (⭐655)](https://github.com/wso2/product-apim) - API management tool with lightweight gateway and API lifecycle management, written in Java.
*   [Express Gateway (⭐2.8k)](https://github.com/ExpressGateway/express-gateway) - Microservices API Gateway built on top of ExpressJS (Node.js).
*   [KrakenD (⭐5.3k)](https://github.com/devopsfaith/krakend) Ultra performant API Gateway with middleware. Written in Go.

## SaaS Tools

*   [Nango (⭐169)](https://github.com/NangoHQ/nango) - Native integrations framework to consume REST APIs (open-source).
*   [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
*   [Ping-API](https://ping-api.com/) - Automated API Monitoring & Testing.
*   [import.io Magic](https://magic.import.io/) - Create a REST API from any website in one click.
*   [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
*   [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
*   [Apigee](https://apigee.com) - Apigee is the leading provider of API technology and services for enterprises and developers.
*   [3scale](https://www.3scale.net/) - Nginx based API gateway to integrate internal and external API services with 3scale's API Management Platform.
*   [Assertible](https://assertible.com) - Continuously test and monitor your APIs after deployments and across environments.
*   [Moesif](https://www.moesif.com) - API Analytics for Debugging, Monitoring, and Usage Tracking for RESTful and GraphQL.
*   [Beeceptor](https://beeceptor.com/) - An HTTP inspecting, mocking and proxing service. Gives named endpoints for creating mock API endpoints and simulate responses.

## Miscellaneous

*   [react-admin (⭐21k)](https://github.com/marmelab/react-admin) - Add a ReactJS admin GUI to any RESTful API.
*   [ng-admin (⭐4k)](https://github.com/marmelab/ng-admin) - Add an AngularJS admin GUI to any RESTful API.
*   [swagger-codegen (⭐15k)](https://github.com/swagger-api/swagger-codegen) - Auto generation of client libraries or server stubs given an OpenAPI specification (formerly known as the Swagger Specification).
*   [Lumber (⭐2.1k)](https://github.com/ForestAdmin/lumber) - Generate the admin interface of your application.
*   [Linx](https://linx.software) - Low-code API platform. Build, debug and host REST APIs

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

