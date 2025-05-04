# Awesome Fiber Overview

✨ A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/gofiber/awesome-fiber/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 gofiber/awesome-fiber](https://github.com/gofiber/awesome-fiber) · ⭐ 663 · 🏷️ Back-End Development

[ [Daily](/content/gofiber/awesome-fiber/README.md) / [Weekly](/content/gofiber/awesome-fiber/week/README.md) / Overview ]

---

# Awesome Fiber [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://gofiber.io">
  <picture alt="Fiber Logo" align="right" style="margin-right: 25px">
    <source height="75" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo-dark.svg">
    <img height="75" alt="Fiber Logo" align="right" style="margin-right: 25px" src="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo.svg">
  </picture>
</a>

> **Fiber** is an [Express (⭐67k)](https://github.com/expressjs/express) inspired **web framework** built on top of [Fasthttp (⭐22k)](https://github.com/valyala/fasthttp), the **fastest** HTTP engine for [Go](https://golang.org/doc/). Designed to **ease** things up for **fast** development with **zero memory allocation** and **performance** in mind.

A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools. <br>

## Contents

<!--lint disable awesome-toc-->

<!--lint disable awesome-git-repo-age-->

*   [⚙️ Middlewares](#%EF%B8%8F-middlewares)
    *   [🧬 Core](#-core)
    *   [🔗 External](#-external)
    *   [💻 Contrib](#-contrib)
    *   [🌱 Third Party](#-third-party)
*   [🚧 Boilerplates](#-boilerplates)
*   [📁 Recipes](#-recipes)
*   [🛠️ Tools](#%EF%B8%8F-tools)
*   [📖 Articles](#-articles)
*   [📺 Videos](#-videos)
*   [🤖 Benchmarks](#-benchmarks)

## ⚙️ Middlewares

Where to discover Fiber middlewares.

### 🧬 Core

List of middlewares that are included within the Fiber framework.

*   [Adaptor (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/adaptor) - Converter for net/http handlers to/from Fiber request handlers.
*   [BasicAuth (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/basicauth) - Basic auth middleware provides an HTTP basic authentication. It calls the next handler for valid credentials and 401 Unauthorized for missing or invalid credentials.
*   [Cache (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/cache) - Intercept and cache responses.
*   [Compress (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/compress) - Compression middleware for Fiber, it supports `deflate`, `gzip` and `brotli` by default.
*   [CORS (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/cors) - Enable cross-origin resource sharing (CORS) with various options.
*   [CSRF (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/csrf) - Protect from CSRF exploits.
*   [Earlydata (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/earlydata) - Early data support for Fiber.
*   [Encrypt Cookie (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/encryptcookie) - Encrypt middleware which encrypts cookie values.
*   [EnvVar (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/envvar) - Expose environment variables with providing an optional config.
*   [ETag (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/etag) - ETag middleware that lets caches be more efficient and save bandwidth, as a web server does not need to resend a full response if the content has not changed.
*   [Expvar (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/expvar) - Expvar middleware that serves via its HTTP server runtime exposed variants in the JSON format.
*   [Favicon (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/favicon) - Ignore favicon from logs or serve from memory if a file path is provided.
*   [FileSystem (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/filesystem) - FileSystem middleware for Fiber, special thanks and credits to Alireza Salary.
*   [Helmet (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/helmet) - Helps secure your apps by setting various HTTP headers.
*   [Idempotency (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/idempotency) - Idempotency middleware for Fiber allows for fault-tolerant APIs where duplicate requests.
*   [Keyauth (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/keyauth) - Key auth middleware provides a key based authentication.
*   [Limiter (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/limiter) - Rate-limiting middleware. Use to limit repeated requests to public APIs and/or endpoints such as password reset.
*   [Logger (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/logger) - HTTP request/response logger.
*   [Monitor (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/monitor) - Monitor middleware that reports server metrics, inspired by express-status-monitor.
*   [Pprof (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/pprof) - Pprof middleware that serves via its HTTP server runtime profiling data in the format expected by the pprof visualization tool.
*   [Proxy (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/proxy) - Allows you to proxy requests to a multiple servers.
*   [Recover (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/recover) - Recover middleware recovers from panics anywhere in the stack chain and handles the control to the centralized ErrorHandler.
*   [Redirect (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/redirect) - Redirect middleware for Fiber.
*   [RequestID (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/requestid) - Adds a requestid to every request.
*   [Rewrite (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/rewrite) - Rewrite middleware rewrites the URL path based on provided rules. It can be helpful for backward compatibility or just creating cleaner and more descriptive links.
*   [Session (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/session) - Session middleware. NOTE: This middleware uses our Storage package.
*   [Skip (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/skip) - Skip middleware that skips a wrapped handler is a predicate is true.
*   [Timeout (⭐36k)](https://github.com/gofiber/fiber/tree/master/middleware/timeout) - Adds a max time for a request and forwards to ErrorHandler if it is exceeded.

### 🔗 External

List of externally hosted middleware modules and maintained by the [Fiber team](https://github.com/orgs/gofiber/people).

*   [storage (⭐295)](https://github.com/gofiber/storage) - Premade storage drivers that implement the Storage interface, designed to be used with various Fiber middlewares.
*   [template (⭐288)](https://github.com/gofiber/template) - This package contains 8 template engines that can be used with Fiber v1.10.x Go version 1.13 or higher is required.

### ‍💻 Contrib

List of third party middlewares and maintained by the Fiber team and community.

*   [casbin (⭐254)](https://github.com/gofiber/contrib/tree/main/casbin) - Casbin middleware for Fiber.
*   [circuitbreaker (⭐254)](https://github.com/gofiber/contrib/tree/main/circuitbreaker) - Circuit Breaker middleware for Fiber.
*   [fiberi18n (⭐254)](https://github.com/gofiber/contrib/tree/main/fiberi18n) - Middleware for i18n support in Fiber.
*   [fibernewrelic (⭐254)](https://github.com/gofiber/contrib/tree/main/fibernewrelic) - NewRelic middleware for Fiber. The middleware handles NewRelic insturmentation.
*   [fibersentry (⭐254)](https://github.com/gofiber/contrib/tree/main/fibersentry) - Sentry support for Fiber.
*   [fiberzap (⭐254)](https://github.com/gofiber/contrib/tree/main/fiberzap) - Zap logging support for Fiber.
*   [jwt (⭐254)](https://github.com/gofiber/contrib/tree/main/jwt) - JWT returns a JSON Web Token (JWT) auth middleware.
*   [opafiber (⭐254)](https://github.com/gofiber/contrib/tree/main/opafiber) - Open Policy Agent middleware for Fiber. The middleware handles running Rego policies.
*   [otelfiber (⭐254)](https://github.com/gofiber/contrib/tree/main/otelfiber) - OpenTelemetry support for Fiber.
*   [paseto (⭐254)](https://github.com/gofiber/contrib/tree/main/paseto) - PASETO returns a Web Token (PASETO) auth middleware.
*   [swagger (⭐254)](https://github.com/gofiber/contrib/tree/main/swagger) - Swagger middleware for Fiber. The middleware handles Swagger UI.
*   [websocket (⭐254)](https://github.com/gofiber/contrib/tree/main/websocket) - Based on Fasthttp WebSocket for Fiber with Locals support!

### 🌱 Third Party

List of middlewares that are created by the Fiber community.

*   [shareed2k/fiber\_tracing (⭐12)](https://github.com/shareed2k/fiber_tracing) - Middleware trace requests on Fiber framework with OpenTracing API.
*   [shareed2k/fiber\_limiter (⭐13)](https://github.com/shareed2k/fiber_limiter) - Limiter using redis as store for rate limit with two algorithms for choosing sliding window, gcra leaky bucket.
*   [ansrivas/fiberprometheus (⭐191)](https://github.com/ansrivas/fiberprometheus) - Prometheus middleware for gofiber.
*   [sacsand/gofiber-firebaseauth (⭐25)](https://github.com/sacsand/gofiber-firebaseauth) - Fiber Firebase Auth Middleware.
*   [aschenmaker/fiber-health-check (⭐10)](https://github.com/aschenmaker/fiber-health-check) - Health-check middleware support health-check for Fiber️ framework.
*   [elastic/apmfiber (⭐424)](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) - APM Agent for Go Fiber.
*   [eozer/fiber\_ldapauth (⭐4)](https://github.com/eozer/fiber_ldapauth) - LDAP Authentication Middleware for Fiber.
*   [darkweak/souin (⭐787)](https://github.com/darkweak/souin) - HTTP cache, RFC compliant, alternative to Varnish available as a middleware.
*   [witer33/fiberpow (⭐13)](https://github.com/witer33/fiberpow) - Anti DDoS/Bot Middleware with a customizable Proof Of Work challenge.
*   [beyer-stefan/gofiber-minifier (⭐2)](https://github.com/beyer-stefan/gofiber-minifier) - Minifying middleware for HTML5, CSS3, and JavaScript.
*   [joffref/opa-middleware (⭐21)](https://github.com/Joffref/opa-middleware) - Provides an OPA middleware integration for fiber.
*   [vladfr/fiber-servertiming (⭐2)](https://github.com/vladfr/fiber-servertiming) - A middleware to add Server-Timing headers based on the W3C Server-Timing Spec.
*   [airbrake/gobrake (⭐105)](https://github.com/airbrake/gobrake/tree/master/examples/fiber) - An Airbrake middleware that reports performance data (route stats).
*   [samber/slog-fiber (⭐75)](https://github.com/samber/slog-fiber) - A logger middleware that uses Go slog library.
*   [mikhail-bigun/fiberlogrus (⭐10)](https://github.com/mikhail-bigun/fiberlogrus) - A logger middleware that uses logrus and its structured logging features.
*   [Idan-Fishman/fiber-bind (⭐14)](https://github.com/Idan-Fishman/fiber-bind) - Request schema validator middleware that validates sources such as the request body, query string parameters, route parameters and even form files.
*   [rodrigoodhin/fiper](https://gitlab.com/rodrigoodhin/fiper) - FiPer is a library that provides Fiber with Role Based Access Control (RBAC) using JWT and with database persistence using two ORM libraries are supported: Gorm and Bun.
*   [zeiss/fiber-goth (⭐5)](https://github.com/ZEISS/fiber-goth) - Simple middleware to integrate authentication to your Fiber applications.
*   [zeiss/fiber-authz (⭐7)](https://github.com/ZEISS/fiber-authz) - A middleware to secure routes in Fiber with a defined RBAC model.
*   [zeiss/fiber-htmx (⭐0)](https://github.com/ZEISS/fiber-htmx) - A middleware for using HTMX in Fiber.
*   [jsorb84/ssefiber (⭐2)](https://github.com/jsorb84/ssefiber) - A basic SSE Implementation for Fiber.
*   [streamerd/fibergun (⭐4)](https://github.com/streamerd/fibergun) - A GunDB middleware for Fiber. Enables easy integration of GunDB, a decentralized database.
*   [apitally/apitally-go (⭐1)](https://github.com/apitally/apitally-go) - Simple API monitoring tool for Fiber. Tracks API usage, errors, and performance, and includes request logging and alerting features.

## 🚧 Boilerplates

Premade boilerplates for Fiber.

*   [gofiber/boilerplate (⭐459)](https://github.com/gofiber/boilerplate) - Official fiber boilerplate.
*   [fiber-boilerplate (⭐282)](https://github.com/thomasvvugt/fiber-boilerplate) - A boilerplate for the Fiber web framework.
*   [sujit-baniya/fiber-boilerplate (⭐420)](https://github.com/sujit-baniya/fiber-boilerplate) - Boilerplate on the top of fiber web framework with many middlewares and features.
*   [goravel/fiber (⭐17)](https://github.com/goravel/fiber) - Laravel similar boilerplate with support for Fiber.
*   [create-go-app/fiber-go-template (⭐1k)](https://github.com/create-go-app/fiber-go-template) - Fiber backend template for Create Go App CLI.
*   [efectn/fiber-boilerplate (⭐81)](https://github.com/efectn/fiber-boilerplate) - Simple and scalable boilerplate to build powerful and organized REST projects with Fiber.
*   [embedmode/fiberseed (⭐40)](https://github.com/embedmode/fiberseed) - Fiber boilerplate api with many middlewares.
*   [GalvinGao/gofiber-template (⭐120)](https://github.com/GalvinGao/gofiber-template) - A production-ready, container-first opinionated gofiber project template. Config by envvars, DI by go.uber.org/fx, Database by uptrace/bun, with out-of-the-box MVC folder structure and CI/CD support.
*   [mikhail-bigun/go-app-template (⭐17)](https://github.com/mikhail-bigun/go-app-template) - Clean architecture Go application boilerplate with enriched Fiber implementation.
*   [felipeafonso/go-htmx-starter (⭐1)](https://github.com/FelipeAfonso/go-htmx-starter) - A front-end opinionated boilerplate for Go + HTMX development, using Tailwind and Vite for Bundling and Hot Reloading.
*   [amrebada/go-modules (⭐16)](https://github.com/amrebada/go-modules) - Nest JS like structure for Go Fiber.
*   [ingeniousambivert/fiber-bootstrapped (⭐2)](https://github.com/ingeniousambivert/fiber-bootstrapped) - A toolkit for Go projects embracing a service-centric architecture, inspired by the principles of FeathersJS.
*   [sebajax/go-vertical-slice-architecture (⭐31)](https://github.com/sebajax/go-vertical-slice-architecture) - Vertical Slice Architecture code archetype using Fiber and Uber dig. A maintainable, and scalable code organization.
*   [go-rat/fiber-skeleton (⭐3)](https://github.com/go-rat/fiber-skeleton) - Fiber skeleton to powers web projects, support wire-based dependency injection.

## 📁 Recipes

Recipes for Fiber.

*   [gofiber/recipes (⭐3.3k)](https://github.com/gofiber/recipes) - Official Fiber cookbook.
*   [kiyonlin/fiblar-demo (⭐3)](https://github.com/kiyonlin/fiblar-demo) - Fiber v1 + angular demo.
*   [koddr/tutorial-go-fiber-rest-api (⭐389)](https://github.com/koddr/tutorial-go-fiber-rest-api) - Tutorial for building a restful api with fiber.
*   [firebase007/go-rest-api-with-fiber (⭐56)](https://github.com/firebase007/go-rest-api-with-fiber) - Demo project with fiber, logging, basicAuth and postgresql.
*   [chawk/go\_fiber\_quickstart (⭐18)](https://github.com/chawk/go_fiber_quickstart) - Fiber quick start example project.
*   [EricLau1/go-fiber-auth-api (⭐55)](https://github.com/EricLau1/go-fiber-auth-api) - Golang Authentication API with Fiber MongoDB and JWT.
*   [alpody/golang-fiber-realworld-example-app (⭐134)](https://github.com/alpody/golang-fiber-realworld-example-app) - Example real world backend API built with Fiber, Gorm, Swagger.
*   [paundraP/golang-starter-template (⭐5)](https://github.com/paundraP/Go-Starter-Template) - Golang REST API with authentication, authorization, and integrated payment gateway support.

## 🛠️ Tools

Several tools to make Fiber usage easier.

*   [go-dawn/dawn (⭐18)](https://github.com/go-dawn/dawn) - Dawn is an opinionated web framework that provides rapid development capabilities which on top of Fiber.
*   [tompston/gomakeme (⭐11)](https://github.com/tompston/gomakeme) - Generate boilerplate + endpoints for Fiber or Gin REST APIs.
*   [ryanbekhen/feserve (⭐8)](https://github.com/ryanbekhen/feserve) - Feserve is a lightweight application or docker image to serve frontend and load balancer applications.
*   [deepmap/oapi-codegen (⭐7k)](https://github.com/deepmap/oapi-codegen) - Generate Go client and server boilerplate from OpenAPI 3 specifications.
*   [Alibaba/opentelemetry-go-auto-instrumentation (⭐554)](https://github.com/alibaba/opentelemetry-go-auto-instrumentation) - A tool to monitor fiber application without changing any code with OpenTelemetry APIs.

## 📖 Articles

Articles about Fiber written by the community.

*   [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
*   [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
*   [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
*   [Go Fiber by Examples: How can the Fiber Web Framework be useful?](https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a)
*   [Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers](https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j)
*   [Getting started with Fiber](https://dev.to/fenny/getting-started-with-fiber-36b6)
*   [Building an Express-style API in Go with Fiber](https://blog.logrocket.com/express-style-api-go-fiber/)
*   [Fiber v1.9.6 How to improve performance by 817% and stay fast, flexible and friendly?](https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6)
*   [Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager](https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t)
*   [Building a Basic REST API in Go using Fiber](https://tutorialedge.net/golang/basic-rest-api-go-fiber/)
*   [Creating Fast APIs In Go Using Fiber](https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9)
*   [Is switching from Express to Fiber worth it?](https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1)
*   [Fiber v1.8. What's new, updated and re-thinked?](https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h)
*   [Fiber released v1.7! What's new and is it still fast, flexible and friendly?](https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf)
*   [Welcome to Fiber — an Express.js styled web framework written in Go with ❤️](https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497)
*   [Blazing Fast Unit Tests - Fiber/fasthttp/http Internals](https://medium.com/trendyol-tech/golang-blazing-fast-unit-tests-fiber-fasthttp-http-internals-and-optimizing-http-server-tests-bbd1fe7b944b)
*   [Building Microservices in Go : Part 1 - Project Setup, Dockerization](https://saadfarhan124.medium.com/building-microservices-in-go-part-1-e7e58893bc5e)
*   [Building Microservices in Go : Part 2 - Live Reload](https://saadfarhan124.medium.com/building-microservices-in-go-part-2-f9c6c535805c)
*   [Building Microservices in Go : Part 3 - Database, Models, Migrations](https://saadfarhan124.medium.com/building-microservices-in-go-part-3-database-models-migrations-a4455121bb11)
*   [Build a REST API from scratch with Go, Docker & Postgres](https://dev.to/divrhino/build-a-rest-api-from-scratch-with-go-and-docker-3o54)
*   [Build a fullstack app with Go Fiber, Docker, and Postgres](https://dev.to/divrhino/build-a-fullstack-app-with-go-fiber-docker-and-postgres-1jg6)
*   [Create a CRUD app with Go Fiber, docker, and Postgres](https://dev.to/divrhino/create-a-crud-app-with-go-fiber-docker-and-postgres-47e3)

## 📺 Videos

Video tutorials created by the community about Fiber.

*   [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)

## 🤖 Benchmarks

Several benchmarks to compare Fiber with other frameworks.

*   [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20\&hw=ph\&test=json) - Project provides performance measures across a wide field of web application frameworks.
*   [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - Project aims to measure the differences between the various programming language frameworks.
*   [go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) - This benchmark suite aims to compare the performance of Go web frameworks.

### 👍 Contributing

Contribution guidelines can be found on [CONTRIBUTING.md (⭐663)](https://github.com/gofiber/awesome-fiber/blob/master/CONTRIBUTING.md)

