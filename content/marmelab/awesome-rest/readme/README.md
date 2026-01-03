# Awesome Rest Overview

A collaborative list of great resources about RESTful API architecture, development, test, and performance

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/marmelab/awesome-rest/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 marmelab/awesome-rest](https://github.com/marmelab/awesome-rest) · ⭐ 3.8K · 🏷️ Miscellaneous

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
    *   [.Net](#net-clients)
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

*   [Architectural Styles and the Design of Network-based Software Architectures](https://roy.gbiv.com/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST
*   [HTTP API design guide extracted from work on the Heroku Platform API (⭐14k)](https://github.com/interagent/http-api-design)
*   [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
*   [How to design a REST API?](https://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
*   [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html) - Explained by Martin Fowler, originally presented by Leonard Richardson at the [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
*   [Enterprise Integration Using REST](https://martinfowler.com/articles/enterpriseREST.html) - Discusses the constraints and flexibility that you have with nonpublic APIs, and lessons learned from doing large scale RESTful integration across multiple teams.
*   [HATEOAS](https://web.archive.org/web/20201111235328/timelessrepo.com/haters-gonna-hateoas) - Clear explanation on what HATEOAS is, and why you should use it.
*   [How to GET a cup of coffee](https://www.infoq.com/articles/webber-rest-workflow/)
*   [REST API Tutorial](https://www.restapitutorial.com/) - RestApiTutorial.com is dedicated to tracking REST API best practices and making resources available to enable quick reference and self education for the development crafts-person.
*   [API-Security-Checklist (⭐23k)](https://github.com/shieldfy/API-Security-Checklist) - Best practices about REST API security

### Guidelines

*   [Adidas REST API Guidelines (⭐397)](https://github.com/adidas/api-guidelines/blob/master/rest-api-guidelines/rest.md) - Adidas REST API Guidelines define standards and guidelines for building REST APIs at adidas.
*   [Atlassian REST API design guidelines version 1](https://developer.atlassian.com/server/framework/atlassian-sdk/atlassian-rest-api-design-guidelines-version-1/) - This document provides guidelines to Atlassian developers who are designing REST APIs for Atlassian applications.
*   [Cisco REST API Guide (⭐119)](https://github.com/CiscoDevNet/api-design-guide) - Guidelines for designing REST APIs at Cisco.
*   [Google Cloud API design guide](https://cloud.google.com/apis/design/) - Guidelines Google follows when designing Cloud APIs and other Google APIs (REST APIs and gRPC APIs).
*   [Haufe API Style Guide (⭐242)](https://github.com/Haufe-Lexware/api-style-guide) - Guidelines created by Haufe-Lexware CTO team.
*   [Microsoft REST API Guidelines (⭐23k)](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) - The Microsoft REST API Guidelines, as a design principle, encourages application developers to have resources accessible to them via a RESTful HTTP interface.
*   [Restful API Guidelines by Zalando (⭐3.1k)](https://github.com/zalando/restful-api-guidelines) - Developing Restful APIs: A Comprehensive Set of Guidelines.

## Standards

*   [JSON API](https://jsonapi.org/) - Standard for building APIs in JSON.
*   [RAML](https://raml.org/) - Simple and succinct way to describe RESTful API.
*   [JSend (⭐1.7k)](https://github.com/omniti-labs/jsend) - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
*   [OData](https://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
*   [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) - Simple format that gives a consistent and easy way to hyperlink between resources in your API.
*   [JSON-LD](https://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
*   [Hydra](https://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
*   [Schema.org](https://schema.org) - Collection of schemas describing common data models.
*   [OpenAPI](https://openapis.org/) - Formerly known as the Swagger Specification, OpenAPI specifcation is the world’s most popular description format for defining Restful APIs.

## Clients

### PHP Clients

*   [Guzzle](https://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services.
*   [Buzz (⭐1.9k)](https://github.com/kriswallsmith/buzz) - Another lightweight HTTP client.
*   [unirest for PHP (⭐1.3k)](https://github.com/Mashape/unirest-php) - Simplified, lightweight HTTP client library.

### JavaScript Clients

*   [restangular (⭐7.8k)](https://github.com/mgonto/restangular) - AngularJS service to handle REST API properly and easily.
*   [restful.js (⭐963)](https://github.com/marmelab/restful.js) - JS client for interacting with server-side RESTful resources.
*   [traverson (⭐460)](https://github.com/basti1302/traverson) - A Hypermedia API/HATEOAS Client for Node.js and the Browser
*   [raml-client-generator (⭐121)](https://github.com/mulesoft/raml-client-generator) - Generates static client libs for js.

### Node.js Clients

*   [restler (⭐2k)](https://github.com/danwrong/restler) - REST client library for node.js.
*   [unirest for Node.js (⭐957)](https://github.com/Mashape/unirest-nodejs) - Simplified, lightweight HTTP client library.

### Ruby Clients

*   [RESTClient (⭐5.2k)](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
*   [Spyke (⭐905)](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner.
*   [excon (⭐1.2k)](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.
*   [httparty (⭐5.9k)](https://github.com/jnunemaker/httparty) - Makes HTTP fun again!
*   [Net::HTTP](https://ruby-doc.org/3.2.0/stdlibs/net/Net/HTTP.html) - Net::HTTP provides a rich library which can be used to build HTTP user-agents.
*   [raml-ruby-client-generator (⭐1)](https://github.com/zlx/raml-ruby-client-generator) - Auto generate API client from a RAML file.

### Go Clients

*   [gopencils (⭐453)](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
*   [resty (⭐11k)](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.

### .NET Clients

*   [RestSharp (⭐9.8k)](https://github.com/restsharp/RestSharp) - Simple REST and HTTP API client for .NET
*   [Refit (⭐9.3k)](https://github.com/reactiveui/refit) - The automatic type-safe REST library for Xamarin and .NET
*   [Flurl](https://flurl.dev) - Fluent, portable, testable REST/HTTP client library
*   [RestEase (⭐1.1k)](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable. Heavily inspired by Refit
*   [Tiny.RestClient (⭐210)](https://github.com/jgiacomini/Tiny.RestClient) - Simpliest Fluent REST client for .NET.
*   [RestLess (⭐112)](https://github.com/letsar/RestLess) - The automatic type-safe-reflectionless REST API client library for .Net Standard.
*   [Apizr (⭐171)](https://github.com/Respawnsive/Apizr) - Refit-based web api client, but resilient (retry, connectivity, cache, auth, log, priority, etc...).

### Generators

*   [openapi-generator (⭐26k)](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3).

## Servers

### Directly On Top Of A RMDB

*   [postgrest (⭐26k)](https://github.com/begriffs/postgrest) - Serve a fully RESTful API directly from an existing PostgreSQL database.
*   [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.
*   [pREST (⭐4.5k)](https://github.com/prest/prest) - A fully RESTful API from any existing PostgreSQL database written in Go.

### Node.js

*   [node-restify (⭐11k)](https://github.com/restify/node-restify) - Framework specifically meant for REST API.
*   [Sails.js](https://sailsjs.org/) - Node.js Web framework embedding a command to generate automatically a REST API.
*   [mers (⭐343)](https://github.com/jspears/mers) - Express service exposing Mongoose finders as RESTful API.
*   [flatiron/resourceful (⭐355)](https://github.com/flatiron/resourceful) - Isomorphic Resource engine for JavaScript.
*   [loopback](https://loopback.io/) - Powerful Node.js framework for creating APIs and easily connecting to backend data sources.
*   [Feathers](https://feathersjs.com/) - is a real-time, micro-service web framework that gives you control over your data via RESTful resources, sockets and flexible plug-ins.
*   [Expressa (⭐449)](https://github.com/thomas4019/expressa) - Express middleware for creating APIs from JSON schemas with a simple admin editor and permissions model.
*   [rest-hapi (⭐1.2k)](https://github.com/JKHeadley/rest-hapi) - Generate RESTful API based on mongoose models that supports relational data.
*   [Nestjsx/crud (⭐4.3k)](https://github.com/nestjsx/crud) - Generate CRUD controllers and services for RESTful API with NestJS and TypeORM.

### PHP

*   [Microrest (⭐185)](https://github.com/marmelab/microrest.php) - Micro-web application providing a REST API on top of any relational database.
*   [Negotiation (⭐1.4k)](https://github.com/willdurand/Negotiation) - Content negotiation library.
*   [Drest (⭐87)](https://github.com/leedavis81/drest) - Library for exposing Doctrine entities as REST resource endpoints.
*   [Restler (⭐1.4k)](https://github.com/Luracast/Restler) - Lightweight framework to expose PHP methods as RESTful web API.
*   [HAL (⭐201)](https://github.com/blongden/hal) - Hypertext Application Language (HAL) builder library.
*   [Apigility (⭐442)](https://github.com/zfcampus/zf-apigility-skeleton) - API builder built with Zend Framework 2.
*   [phprest (⭐305)](https://github.com/phprest/phprest) - Specialized REST microframework for PHP.
*   [Hateoas (⭐1k)](https://github.com/willdurand/Hateoas) - PHP library to support implementing representations for HATEOAS REST web services.
*   [Fusio (⭐2.1k)](https://github.com/apioo/fusio) - Open source API management platform.

#### Symfony2

*   [REST APIs with Symfony2: the Right Way](https://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - Complete guide to build a state-of-the-art REST API with Symfony2 framework.
*   [FOSRestBundle (⭐2.8k)](https://github.com/FriendsOfSymfony/FOSRestBundle) - Bundle handling view, routing, error handling, etc. for your REST API.
*   [stanlemon/rest-bundle (⭐121)](https://github.com/stanlemon/rest-bundle) - Build a REST API based on Doctrine entities using conventions over configuration.
*   [BazingaHateoasBundle (⭐296)](https://github.com/willdurand/BazingaHateoasBundle) - Integrate the [Hateoas (⭐1k)](https://github.com/willdurand/Hateoas) library into a Symfony2 application.
*   [Symfony REST Edition (⭐632)](https://github.com/gimler/symfony-rest-edition) - Start with a Symfony2 application with all REST-friendly bundles pre-configured.
*   [NgAdminGeneratorBundle (⭐75)](https://github.com/marmelab/NgAdminGeneratorBundle) - Boostrap ng-admin configuration based on `stanlemon/rest-bundle`.
*   [DunglasApiBundle (⭐2.5k)](https://github.com/dunglas/DunglasApiBundle) - Build a REST API which follow Hydra/JSON-LD specification.
*   [API Platform (⭐9.1k)](https://github.com/api-platform/api-platform) - Specialize Symfony edition for the creation of hypermedia REST APIs.
*   [NelmioApiDocBundle (⭐2.3k)](https://github.com/nelmio/NelmioApiDocBundle) - Generate documentation for your REST API from annotations.

### PowerShell

*   [Pode (⭐1k)](https://github.com/Badgerati/Pode) - Pode is an cross-platform, open-source, community-supported web server and REST API framework for PowerShell developers

### Python

*   [Django REST framework](https://www.django-rest-framework.org/) - Powerful and flexible toolkit that makes it easy to build Web APIs.
*   [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
*   [flask-restful](https://flask-restful.readthedocs.org/) - Extension for Flask that adds support for quickly building REST APIs.
*   [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
*   [sandman (⭐2.3k)](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.
*   [restless](https://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
*   [Python Eve](https://python-eve.org/) - Eve is an open source Python REST API framework designed for human beings. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services.
*   [Ramses](https://ramses.readthedocs.org/en/stable/) - Makes RAML files executable by generating production-ready APIs from them at runtime.
*   [Flask-Potion (⭐490)](https://github.com/biosustain/potion) - Flask-Potion is a powerful Flask extension for building RESTful JSON APIs. It also provides several Clients for easier access to the API.
*   [apistar (⭐5.6k)](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3.
*   [Falcon (⭐9.8k)](https://github.com/falconry/falcon) - Falcon is a bare-metal Python web API framework for building high-performance microservices, app backends, and higher-level frameworks.
*   [FastAPI (⭐94k)](https://github.com/tiangolo/fastapi) - FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. With automatic API documentation using Swagger UI and ReDoc, based on OpenAPI and JSON Schema.
*   [Zato](https://zato.io) - Platform for building server-side integrations, automations and API backends in Python.

### Ruby

*   [Grape](https://www.ruby-grape.org) - Opinionated micro-framework for creating REST-like APIs in Ruby.
*   [Rails](https://guides.rubyonrails.org/api_app.html) - RailsGuides: Using Rails for API-only applications.

### Go

*   [gocrud (⭐305)](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
*   [go-json-rest (⭐3.5k)](https://github.com/ant0ine/go-json-rest) - Thin layer on top of `net/http` that helps building RESTful APIs easily.
*   [sleepy (⭐670)](https://github.com/dougblack/sleepy) - RESTful micro-framework written in Go.
*   [restit (⭐55)](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
*   [go-relax (⭐154)](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
*   [go-rest (⭐128)](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
*   [go-restful (⭐5.1k)](https://github.com/emicklei/go-restful) - A declarative highly readable framework for building restful API's.
*   [Resoursea (⭐35)](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.

### Java

*   [RestExpress (⭐940)](https://github.com/RestExpress/RestExpress) - Netty-based, highly performant, lightweight, container-less, plugin-extensible, framework that is ideal for microservice architectures.
*   [Vertx-Web (⭐1.1k)](https://github.com/vert-x3/vertx-web) - Vert.x-Web is a set of building blocks for building web applications with Vert.x, a toolkit for building reactive applications on the JVM.
*   [Dropwizard (⭐8.6k)](https://github.com/dropwizard/dropwizard) - A framework for developing ops-friendly, high-performance, RESTful web services.

### Scala

*   [Chaos (⭐250)](https://github.com/mesosphere/chaos) - A lightweight framework for writing REST services in Scala.

### Haskell

*   [Rest for Haskell (⭐386)](https://github.com/silkapp/rest) - This package allows you to create REST APIs in Haskell. These APIs can be run in different web frameworks. They can also be used to automatically generate documentation as well as client libraries.

## Testing

### Querying

*   [httpie (⭐37k)](https://github.com/jkbrzt/httpie) - Command line HTTP client, far more dev-friendly than `curl`.
*   [resty (⭐2.7k)](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines (bash or zsh).
*   [jq (⭐33k)](https://github.com/stedolan/jq) - Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
*   [HttpMaster](https://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.
*   [Http-console (⭐1.5k)](https://github.com/cloudhead/http-console) - Command line interface for HTTP that let you *speak HTTP like a local*
*   [HTTP Prompt (⭐9.1k)](https://github.com/eliangcs/http-prompt) - HTTP Prompt is an interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt\_toolkit.
*   [rest-assured (⭐7.1k)](https://github.com/rest-assured/rest-assured) - Java DSL for easy testing of REST services.
*   [Insomnia (⭐38k)](https://github.com/getinsomnia/insomnia) - Cross-platform HTTP and GraphQL Client
*   [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Make HTTP requests with a simple web-based HTTP client.
*   [TestMace](https://testmace.com) - Cross-platform simple but powerful IDE for API automation testing.
*   [Milkman (⭐1.3k)](https://github.com/warmuuh/milkman) - Extensible cross-platform request/response workbench, not only for http calls.
*   [Schemathesis (⭐2.9k)](https://github.com/schemathesis/schemathesis) - Property-based testing tool for web applications built with Open API and GraphQL specifications.
*   [Step CI (⭐1.8k)](https://github.com/stepci/stepci) - Open-source framework for API Quality Assurance, which tests REST, GraphQL and gRPC automated and from Open API spec.
*   [RestQA (⭐93)](https://github.com/restqa/restqa) - A REST API testing Framework based on BDD / Gherkin to manage microservice local testing.

### Mocking

*   [FakeRest (⭐451)](https://github.com/marmelab/FakeRest) - Redirect fetch() calls to a client-side fake REST API.
*   [json-server (⭐76k)](https://github.com/typicode/json-server) - Serve a REST API from fixture files using quick prototyping.
*   [RequestBin](https://requestbin.com/) - Inspect and debug webhook requests sent by your clients or third-party APIs.
*   [httpbin](https://httpbin.org) - HTTP request and response service - a/k/a Swiss Army Knife for HTTP.
*   [MockServer](https://www.mock-server.com/) - Easy mocking of any system you integrate with via HTTP or HTTPS.
*   [Request Baskets (⭐416)](https://github.com/darklynx/request-baskets) - Service to collect HTTP requests and inspect them via RESTful API or web UI.
*   [DuckRails (⭐1.7k)](https://github.com/iridakos/duckrails) - Mock quickly & dynamically API endpoints.
*   [Mockoon](https://mockoon.com) - Easily create mock APIs locally. No remote deployment, no account required, open source.
*   [Mockintosh](https://mockintosh.io/) - A mock server generator that's capable to generate RESTful APIs and communicate with the message queues to mimick asynchronous tasks.
*   [Mockae](https://mockae.com/) - Fake REST API powered by Lua.

### Validating

*   [JSON Schema](http://json-schema.org/) - Declarative language that allows you to annotate and validate JSON documents

### Public REST APIs To Use In Tests

*   [Public APIS (⭐389k)](https://github.com/public-apis/public-apis) - Explore The Largest API Directory In The Galaxy.
*   [APIs.guru](https://APIs.guru) - Wikipedia for Web APIs, each API has OpenAPI/Swagger description.
*   [JSON Placeholder](https://jsonplaceholder.typicode.com/) - Fake REST API abput posts, users and comments

## Documentation

*   [Swagger](https://swagger.io/) - Documentation/querying web interface for REST APIs.
*   [API doc](https://apidocjs.com/) - Inline Documentation for RESTful web APIs.
*   [raml2html (⭐1.1k)](https://github.com/raml2html/raml2html) - Generates HTML documentation from a RAML file.
*   [ReDoc (⭐25k)](https://github.com/Rebilly/ReDoc/) - OpenAPI/Swagger-powered three-panel documentation.
*   [Slate (⭐36k)](https://github.com/lord/slate) - Beautiful and responsive three-panel API documentation using Middleman.
*   [Optic (⭐1.5k)](https://github.com/opticdev/optic) - Maintain an accurate API specification without writing OpenAPI/Swagger. Works with any Stack
*   [Zudoku](https://zudoku.dev/) - Create clean, consistent API docs with Zudoku — open source, extensible, and developer-first

## API Gateway

*   [Kong (⭐42k)](https://github.com/Kong/kong) - Scalable, distributed, and plugin oriented API gateway backed by Nginx.
*   [Tyk API Gateway (⭐11k)](https://github.com/TykTechnologies/tyk) - Lightweight API gateway with analytics logging, written in Go.
*   [API Umbrella (⭐2.1k)](https://github.com/NREL/api-umbrella) - API management platform for exposing web services, with web interface and analytics, written in Lua.
*   [WSO2 API Management (⭐952)](https://github.com/wso2/product-apim) - API management tool with lightweight gateway and API lifecycle management, written in Java.
*   [Express Gateway (⭐3k)](https://github.com/ExpressGateway/express-gateway) - Microservices API Gateway built on top of ExpressJS (Node.js).
*   [KrakenD (⭐6.7k)](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway with middleware. Written in Go.
*   [AWS API Gateway](https://aws.amazon.com/api-gateway/) - Fully managed service that helps developers to create, publish, maintain, monitor, and secure APIs at any scale.
*   [Zuplo](https://zuplo.com/) - OpenAPI-Powered API & MCP Management platform for Security, Deployment, and Documentation. Add auth, rate-limiting, and monetization to your API or MCP Server in minutes, written in TypeScript & Go.

## SaaS Tools

*   [Nango (⭐6.3k)](https://github.com/NangoHQ/nango) - Native integrations framework to consume REST APIs (open-source).
*   [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
*   [Ping-API](https://ping-api.com/) - Automated API Monitoring & Testing.
*   [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
*   [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
*   [Apigee](https://apigee.com) - Apigee is the leading provider of API technology and services for enterprises and developers.
*   [3scale](https://www.3scale.net/) - Nginx based API gateway to integrate internal and external API services with 3scale's API Management Platform.
*   [Assertible](https://assertible.com) - Continuously test and monitor your APIs after deployments and across environments.
*   [Moesif](https://www.moesif.com) - API Analytics for Debugging, Monitoring, and Usage Tracking for RESTful and GraphQL.
*   [Beeceptor](https://beeceptor.com/) - An HTTP inspecting, mocking and proxing service. Gives named endpoints for creating mock API endpoints and simulate responses.
*   [Apitally](https://apitally.io) - Analytics, request logging and monitoring for REST APIs with a focus on simplicity and data privacy.

## Miscellaneous

*   [shadcn-admin-kit (⭐698)](https://github.com/marmelab/shadcn-admin-kit) - Build internal tools, admin panels, B2B apps, and dashboards on top of any REST API
*   [react-admin (⭐26k)](https://github.com/marmelab/react-admin) - Add a ReactJS admin GUI to any RESTful API.
*   [ng-admin (⭐3.9k)](https://github.com/marmelab/ng-admin) - Add an AngularJS admin GUI to any RESTful API.
*   [swagger-codegen (⭐18k)](https://github.com/swagger-api/swagger-codegen) - Auto generation of client libraries or server stubs given an OpenAPI specification (formerly known as the Swagger Specification).
*   [Linx](https://linx.software) - Low-code API platform. Build, debug and host REST APIs

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](httsp://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

