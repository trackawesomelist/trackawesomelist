# Track Awesome Fiber Updates Weekly

✨ A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/gofiber/awesome-fiber/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 gofiber/awesome-fiber](https://github.com/gofiber/awesome-fiber) · ⭐ 783 · 🏷️ Back-End Development

[ [Daily](/content/gofiber/awesome-fiber/README.md) / Weekly / [Overview](/content/gofiber/awesome-fiber/readme/README.md) ]

## [Feb 16 - Feb 22, 2026](/content/2026/7/README.md)

### ⚙️ Middlewares / 🧬 Core

*   [Adaptor (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/adaptor) - Converter for net/http handlers to/from Fiber request handlers.
*   [BasicAuth (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/basicauth) - Basic auth middleware provides an HTTP basic authentication. It calls the next handler for valid credentials and 401 Unauthorized for missing or invalid credentials.
*   [Cache (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/cache) - Intercept and cache responses.
*   [Compress (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/compress) - Compression middleware for Fiber, it supports `deflate`, `gzip` and `brotli` by default.
*   [CORS (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/cors) - Enable cross-origin resource sharing (CORS) with various options.
*   [CSRF (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/csrf) - Protect from CSRF exploits.
*   [Earlydata (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/earlydata) - Early data support for Fiber.
*   [Encrypt Cookie (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/encryptcookie) - Encrypt middleware which encrypts cookie values.
*   [EnvVar (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/envvar) - Expose environment variables with providing an optional config.
*   [ETag (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/etag) - Lets caches be more efficient and save bandwidth, as a web server does not need to resend a full response if the content has not changed.
*   [Expvar (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/expvar) - Serves runtime exposed variants in JSON format via its HTTP server.
*   [Favicon (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/favicon) - Ignore favicon from logs or serve from memory if a file path is provided.
*   [Healthcheck (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/healthcheck) - Adds health-check endpoints for readiness and liveness probes.
*   [Helmet (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/helmet) - Helps secure your apps by setting various HTTP headers.
*   [Idempotency (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/idempotency) - Enables fault-tolerant APIs when duplicate requests occur.
*   [Keyauth (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/keyauth) - Key auth middleware provides a key based authentication.
*   [Limiter (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/limiter) - Rate-limiting middleware. Use to limit repeated requests to public APIs and/or endpoints such as password reset.
*   [Logger (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/logger) - HTTP request/response logger.
*   [Pprof (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/pprof) - Serves runtime profiling data in the format expected by the pprof visualization tool.
*   [Proxy (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/proxy) - Allows you to proxy requests to a multiple servers.
*   [Recover (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/recover) - Recovers from panics anywhere in the stack chain and hands control to the centralized ErrorHandler.
*   [Redirect (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/redirect) - Handles HTTP redirects in Fiber.
*   [RequestID (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/requestid) - Adds a requestid to every request.
*   [Responsetime (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/responsetime) - Adds an `X-Response-Time` header to responses.
*   [Rewrite (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/rewrite) - Rewrites the URL path based on provided rules for backward compatibility or cleaner links.
*   [Session (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/session) - Provides session management. NOTE: This middleware uses our Storage package.
*   [Skip (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/skip) - Skips a wrapped handler when a predicate is true.
*   [Static (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/static) - Serves static files from a local or custom file system.
*   [Timeout (⭐39k)](https://github.com/gofiber/fiber/tree/main/middleware/timeout) - Adds a max time for a request and forwards to ErrorHandler if it is exceeded.

### ⚙️ Middlewares / ‍💻 Contrib

*   [casbin (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/casbin) - Authorization middleware for Fiber powered by Casbin.
*   [circuitbreaker (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/circuitbreaker) - Circuit breaker middleware for Fiber.
*   [fgprof (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/fgprof) - Fiber profiling support via fgprof.
*   [hcaptcha (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/hcaptcha) - Bot-protection middleware using hCaptcha.
*   [i18n (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/i18n) - Internationalization middleware built on go-i18n.
*   [jwt (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/jwt) - JSON Web Token (JWT) auth middleware.
*   [loadshed (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/loadshed) - Load-shedding middleware to protect Fiber services under pressure.
*   [monitor (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/monitor) - Server metrics monitor middleware for Fiber.
*   [newrelic (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/newrelic) - New Relic instrumentation support for Fiber.
*   [opa (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/opa) - Open Policy Agent (OPA) middleware support for Fiber.
*   [otel (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/otel) - OpenTelemetry middleware support for Fiber.
*   [paseto (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/paseto) - Platform-Agnostic Security Tokens (PASETO) auth middleware.
*   [sentry (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/sentry) - Error monitoring and reporting integration for Fiber with Sentry.
*   [socketio (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/socketio) - Socket.IO-inspired WebSocket wrapper middleware for Fiber.
*   [swaggo (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/swaggo) - Middleware for serving Swag-generated API docs in Fiber.
*   [swaggerui (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/swaggerui) - Swagger UI middleware for serving OpenAPI specs in Fiber.
*   [testcontainers (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/testcontainers) - Service implementation for integrating Testcontainers with Fiber.
*   [WebSocket (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/websocket) - Fasthttp-based WebSocket integration for Fiber with `fiber.Ctx` support.
*   [zap (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/zap) - Logging middleware support for Fiber with Zap.
*   [zerolog (⭐284)](https://github.com/gofiber/contrib/tree/main/v3/zerolog) - Logging middleware support for Fiber with Zerolog.

### ⚙️ Middlewares / 🌱 Third Party

*   [DavidHoenisch/fiber-coraza (⭐1)](https://github.com/DavidHoenisch/fiber-coraza) - Coraza WAF middleware for Fiber, providing web application firewall protection with ModSecurity-compatible rules.

## [Nov 10 - Nov 16, 2025](/content/2025/45/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [oaswrap/fiberopenapi (⭐92)](https://github.com/oaswrap/spec/tree/main/adapter/fiberopenapi) - Fiber adapter for OpenAPI 3.x specification generation with automatic route documentation.

### 📖 Articles / 🌱 Third Party

*   [Build a REST API from scratch with Go, Docker & PostgreSQL](https://dev.to/divrhino/build-a-rest-api-from-scratch-with-go-and-docker-3o54)
*   [Build a fullstack app with Go Fiber, Docker, and PostgreSQL](https://dev.to/divrhino/build-a-fullstack-app-with-go-fiber-docker-and-postgres-1jg6)
*   [Create a CRUD app with Go Fiber, Docker, and PostgreSQL](https://dev.to/divrhino/create-a-crud-app-with-go-fiber-docker-and-postgres-47e3)

## [May 26 - Jun 01, 2025](/content/2025/21/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [narmadaweb/limiter (⭐1)](https://github.com/narmadaweb/limiter) - A high-performance Redis-backed rate limiter middleware for Fiber, supporting fixed window, sliding window, and token bucket algorithms.
*   [narmadaweb/gonify (⭐1)](https://github.com/narmadaweb/gonify) - Fiber Minifying middleware for HTML5, CSS3, JavaScript, Json, XML and SVG.

## [May 12 - May 18, 2025](/content/2025/19/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [newrelic/go-agent (⭐826)](https://github.com/newrelic/go-agent/tree/master/v3/integrations/nrfiber) - Official New Relic middleware for Fiber that manages instrumentation for New Relic monitoring.

## [May 05 - May 11, 2025](/content/2025/18/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [apitally/apitally-go (⭐7)](https://github.com/apitally/apitally-go) - Simple API monitoring tool for Fiber. Tracks API usage, errors, and performance, and includes request logging and alerting features.

## [Mar 24 - Mar 30, 2025](/content/2025/12/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [felipeafonso/go-htmx-starter (⭐3)](https://github.com/FelipeAfonso/go-htmx-starter) - A front-end opinionated boilerplate for Go + HTMX development, using Tailwind and Vite for Bundling and Hot Reloading.

## [Feb 24 - Mar 02, 2025](/content/2025/8/README.md)

### 🛠️ Tools / 🌱 Third Party

*   [Alibaba/opentelemetry-go-auto-instrumentation (⭐780)](https://github.com/alibaba/opentelemetry-go-auto-instrumentation) - A tool to monitor fiber application without changing any code with OpenTelemetry APIs.

## [Feb 17 - Feb 23, 2025](/content/2025/7/README.md)

### 📁 Recipes / 🌱 Third Party

*   [paundraP/golang-starter-template (⭐6)](https://github.com/paundraP/Go-Starter-Template) - Golang REST API with authentication, authorization, and integrated payment gateway support.

## [Jan 27 - Feb 02, 2025](/content/2025/4/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [goravel/fiber (⭐28)](https://github.com/goravel/fiber) - Laravel similar boilerplate with support for Fiber.
*   [go-rat/fiber-skeleton (⭐3)](https://github.com/go-rat/fiber-skeleton) - Fiber skeleton to powers web projects, support wire-based dependency injection.

## [Nov 18 - Nov 24, 2024](/content/2024/47/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [streamerd/fibergun (⭐4)](https://github.com/streamerd/fibergun) - A GunDB middleware for Fiber. Enables easy integration of GunDB, a decentralized database.

## [Mar 25 - Mar 31, 2024](/content/2024/13/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [beyer-stefan/gofiber-minifier (⭐2)](https://github.com/beyer-stefan/gofiber-minifier) - Minifying middleware for HTML5, CSS3, and JavaScript.

## [Mar 11 - Mar 17, 2024](/content/2024/11/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [jsorb84/ssefiber (⭐2)](https://github.com/jsorb84/ssefiber) - A basic SSE Implementation for Fiber.

## [Feb 19 - Feb 25, 2024](/content/2024/8/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [zeiss/fiber-goth (⭐5)](https://github.com/ZEISS/fiber-goth) - Simple middleware to integrate authentication to your Fiber applications.
*   [zeiss/fiber-authz (⭐7)](https://github.com/ZEISS/fiber-authz) - A middleware to secure routes in Fiber with a defined RBAC model.
*   [zeiss/fiber-htmx (⭐5)](https://github.com/ZEISS/fiber-htmx) - A middleware for using HTMX in Fiber.

### 🚧 Boilerplates / 🌱 Third Party

*   [ingeniousambivert/fiber-bootstrapped (⭐2)](https://github.com/ingeniousambivert/fiber-bootstrapped) - A toolkit for Go projects embracing a service-centric architecture, inspired by the principles of FeathersJS.
*   [sebajax/go-vertical-slice-architecture (⭐50)](https://github.com/sebajax/go-vertical-slice-architecture) - Vertical Slice Architecture code archetype using Fiber and Uber dig. A maintainable, and scalable code organization.

## [Sep 04 - Sep 10, 2023](/content/2023/36/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [rodrigoodhin/fiper](https://gitlab.com/rodrigoodhin/fiper) - FiPer is a library that provides Fiber with Role Based Access Control (RBAC) using JWT and with database persistence using two ORM libraries are supported: Gorm and Bun.

## [Aug 14 - Aug 20, 2023](/content/2023/33/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [amrebada/go-modules (⭐15)](https://github.com/amrebada/go-modules) - Nest JS like structure for Go Fiber.

## [Jul 10 - Jul 16, 2023](/content/2023/28/README.md)

### 📁 Recipes / 🌱 Third Party

*   [alpody/golang-fiber-realworld-example-app (⭐146)](https://github.com/alpody/golang-fiber-realworld-example-app) - Example real world backend API built with Fiber, Gorm, Swagger.

## [Jun 26 - Jul 02, 2023](/content/2023/26/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [Idan-Fishman/fiber-bind (⭐14)](https://github.com/Idan-Fishman/fiber-bind) - Request schema validator middleware that validates sources such as the request body, query string parameters, route parameters and even form files.

### 🛠️ Tools / 🌱 Third Party

*   [deepmap/oapi-codegen (⭐8k)](https://github.com/deepmap/oapi-codegen) - Generate Go client and server boilerplate from OpenAPI 3 specifications.

## [May 15 - May 21, 2023](/content/2023/20/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [mikhail-bigun/go-app-template (⭐19)](https://github.com/mikhail-bigun/go-app-template) - Clean architecture Go application boilerplate with enriched Fiber implementation.

## [May 01 - May 07, 2023](/content/2023/18/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [samber/slog-fiber (⭐93)](https://github.com/samber/slog-fiber) - A logger middleware that uses Go slog library.

## [Feb 06 - Feb 12, 2023](/content/2023/6/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [mikhail-bigun/fiberlogrus (⭐10)](https://github.com/mikhail-bigun/fiberlogrus) - A logger middleware that uses logrus and its structured logging features.

## [Jan 30 - Feb 05, 2023](/content/2023/5/README.md)

### 🛠️ Tools / 🌱 Third Party

*   [ryanbekhen/feserve (⭐9)](https://github.com/ryanbekhen/feserve) - Feserve is a lightweight application or Docker image to serve frontend and load balancer applications.

## [Jan 16 - Jan 22, 2023](/content/2023/3/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [airbrake/gobrake (⭐107)](https://github.com/airbrake/gobrake/tree/master/examples/fiber) - An Airbrake middleware that reports performance data (route stats).

## [Nov 14 - Nov 20, 2022](/content/2022/46/README.md)

### 📖 Articles / 🌱 Third Party

*   [Building Microservices in Go : Part 1 - Project Setup, Dockerization](https://saadfarhan124.medium.com/building-microservices-in-go-part-1-e7e58893bc5e)
*   [Building Microservices in Go : Part 2 - Live Reload](https://saadfarhan124.medium.com/building-microservices-in-go-part-2-f9c6c535805c)
*   [Building Microservices in Go : Part 3 - Database, Models, Migrations](https://saadfarhan124.medium.com/building-microservices-in-go-part-3-database-models-migrations-a4455121bb11)

## [Nov 07 - Nov 13, 2022](/content/2022/45/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [GalvinGao/gofiber-template (⭐131)](https://github.com/GalvinGao/gofiber-template) - A production-ready, container-first opinionated gofiber project template. Config by envvars, DI by go.uber.org/fx, Database by uptrace/bun, with out-of-the-box MVC folder structure and CI/CD support.

## [Oct 31 - Nov 06, 2022](/content/2022/44/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [vladfr/fiber-servertiming (⭐2)](https://github.com/vladfr/fiber-servertiming) - A middleware to add Server-Timing headers based on the W3C Server-Timing Spec.

## [Oct 10 - Oct 16, 2022](/content/2022/41/README.md)

### 📺 Videos / 🌱 Third Party

*   [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)

## [Sep 12 - Sep 18, 2022](/content/2022/37/README.md)

### 📖 Articles / 🌱 Third Party

*   [Blazing Fast Unit Tests - Fiber/fasthttp/http Internals](https://medium.com/trendyol-tech/golang-blazing-fast-unit-tests-fiber-fasthttp-http-internals-and-optimizing-http-server-tests-bbd1fe7b944b)

## [Aug 22 - Aug 28, 2022](/content/2022/34/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [joffref/opa-middleware (⭐22)](https://github.com/Joffref/opa-middleware) - Provides an OPA middleware integration for fiber.

## [May 16 - May 22, 2022](/content/2022/20/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [witer33/fiberpow (⭐15)](https://github.com/witer33/fiberpow) - Anti DDoS/Bot Middleware with a customizable Proof Of Work challenge.

## [Apr 11 - Apr 17, 2022](/content/2022/15/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [darkweak/souin (⭐932)](https://github.com/darkweak/souin) - HTTP cache, RFC compliant, alternative to Varnish available as a middleware.

## [Apr 04 - Apr 10, 2022](/content/2022/14/README.md)

### 🚧 Boilerplates / 🌱 Third Party

*   [efectn/fiber-boilerplate (⭐84)](https://github.com/efectn/fiber-boilerplate) - Simple and scalable boilerplate to build powerful and organized REST projects with Fiber.

## [Mar 28 - Apr 03, 2022](/content/2022/13/README.md)

### ⚙️ Middlewares / 🌱 Third Party

*   [shareed2k/fiber\_tracing (⭐12)](https://github.com/shareed2k/fiber_tracing) - Middleware trace requests on Fiber framework with OpenTracing API.
*   [shareed2k/fiber\_limiter (⭐14)](https://github.com/shareed2k/fiber_limiter) - Limiter using Redis as store for rate limit with two algorithms for choosing sliding window, gcra leaky bucket.
*   [ansrivas/fiberprometheus (⭐208)](https://github.com/ansrivas/fiberprometheus) - Prometheus middleware for gofiber.
*   [sacsand/gofiber-firebaseauth (⭐26)](https://github.com/sacsand/gofiber-firebaseauth) - Fiber Firebase Auth Middleware.
*   [aschenmaker/fiber-health-check (⭐10)](https://github.com/aschenmaker/fiber-health-check) - Health-check middleware support health-check for Fiber️ framework.
*   [elastic/apmfiber (⭐424)](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) - APM Agent for Go Fiber.
*   [eozer/fiber\_ldapauth (⭐4)](https://github.com/eozer/fiber_ldapauth) - LDAP Authentication Middleware for Fiber.

### 🚧 Boilerplates / 🌱 Third Party

*   [gofiber/boilerplate (⭐494)](https://github.com/gofiber/boilerplate) - Official fiber boilerplate.
*   [fiber-boilerplate (⭐287)](https://github.com/thomasvvugt/fiber-boilerplate) - A boilerplate for the Fiber web framework.
*   [sujit-baniya/fiber-boilerplate (⭐433)](https://github.com/sujit-baniya/fiber-boilerplate) - Boilerplate on the top of fiber web framework with many middlewares and features.
*   [create-go-app/fiber-go-template (⭐1.1k)](https://github.com/create-go-app/fiber-go-template) - Fiber backend template for Create Go App CLI.
*   [embedmode/fiberseed (⭐40)](https://github.com/embedmode/fiberseed) - Fiber boilerplate api with many middlewares.

### 📁 Recipes / 🌱 Third Party

*   [kiyonlin/fiblar-demo (⭐3)](https://github.com/kiyonlin/fiblar-demo) - Fiber v1 + angular demo.
*   [koddr/tutorial-go-fiber-rest-api (⭐398)](https://github.com/koddr/tutorial-go-fiber-rest-api) - Tutorial for building a restful api with fiber.
*   [firebase007/go-rest-api-with-fiber (⭐58)](https://github.com/firebase007/go-rest-api-with-fiber) - Demo project with fiber, logging, basicAuth and postgresql.
*   [chawk/go\_fiber\_quickstart (⭐18)](https://github.com/chawk/go_fiber_quickstart) - Fiber quick start example project.
*   [EricLau1/go-fiber-auth-api (⭐55)](https://github.com/EricLau1/go-fiber-auth-api) - Golang Authentication API with Fiber MongoDB and JWT.

### 🤖 Benchmarks / 🌱 Third Party

*   [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20\&hw=ph\&test=json) - Project provides performance measures across a wide field of web application frameworks.
*   [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - Project aims to measure the differences between the various programming language frameworks.
*   [go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) - This benchmark suite aims to compare the performance of Go web frameworks.

## [Feb 28 - Mar 06, 2022](/content/2022/9/README.md)

### ⚙️ Middlewares / 🔗 External

*   [storage (⭐318)](https://github.com/gofiber/storage) - Premade storage drivers that implement the Storage interface, designed to be used with various Fiber middlewares.
*   [template (⭐309)](https://github.com/gofiber/template) - This package contains 8 template engines that can be used with Fiber v1.10.x Go version 1.13 or higher is required.

### 📁 Recipes / 🌱 Third Party

*   [gofiber/recipes (⭐3.4k)](https://github.com/gofiber/recipes) - Official Fiber cookbook.

### 🛠️ Tools / 🌱 Third Party

*   [go-dawn/dawn (⭐18)](https://github.com/go-dawn/dawn) - Dawn is an opinionated web framework that provides rapid development capabilities which on top of Fiber.
*   [tompston/gomakeme (⭐10)](https://github.com/tompston/gomakeme) - Generate boilerplate + endpoints for Fiber or Gin REST APIs.

### 📖 Articles / 🌱 Third Party

*   [Go Fiber by Examples: How can the Fiber Web Framework be useful?](https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a)
*   [Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers](https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j)
*   [Getting started with Fiber](https://dev.to/fenny/getting-started-with-fiber-36b6)
*   [Fiber v1.9.6 How to improve performance by 817% and stay fast, flexible and friendly?](https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6)
*   [Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager](https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t)
*   [Is switching from Express to Fiber worth it?](https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1)
*   [Fiber v1.8. What's new, updated and re-thinked?](https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h)
*   [Fiber released v1.7! What's new and is it still fast, flexible and friendly?](https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf)

## [Feb 21 - Feb 27, 2022](/content/2022/8/README.md)

### 📖 Articles / 🌱 Third Party

*   [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
*   [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
*   [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
*   [Building an Express-style API in Go with Fiber](https://blog.logrocket.com/express-style-api-go-fiber/)
*   [Building a Basic REST API in Go using Fiber](https://tutorialedge.net/golang/basic-rest-api-go-fiber/)
*   [Creating Fast APIs In Go Using Fiber](https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9)
*   [Welcome to Fiber — an Express.js styled web framework written in Go with ❤️](https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497)