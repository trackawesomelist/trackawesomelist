# Awesome List Updates on Feb 05, 2025

9 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Agi Cocosci](/content/YuzheSHI/awesome-agi-cocosci/README.md)

### Bayesian Modeling / Generative Model

*   [Cooperative Training of Descriptor and Generator Networks](https://ieeexplore.ieee.org/abstract/document/8519332) - ***IEEE Transactions on Pattern Analysis and Machine Intelligence***, 2018. \[[All Versions](https://scholar.google.com/scholar?cluster=18202808849093155435)]. This paper studies the cooperative training of two generative models for image modeling and synthesis. Both models are parametrized by convolutional neural networks (ConvNets). The first model is a deep energy-based model, whose energy function is defined by a bottom-up ConvNet, which maps the observed image to the energy. We call it the descriptor network. The second model is a generator network, which is a non-linear version of factor analysis. It is defined by a top-down ConvNet, which maps the latent factors to the observed image. The maximum likelihood learning algorithms of both models involve MCMC sampling such as Langevin dynamics. This work observes that the two learning algorithms can be seamlessly interwoven into a cooperative learning algorithm that can train both models simultaneously. Specifically, within each iteration of the cooperative learning algorithm, the generator model generates initial synthesized examples to initialize a finite-step MCMC that samples and trains the energy-based descriptor model. After that, the generator model learns from how the MCMC changes its synthesized examples. That is, the descriptor model teaches the generator model by MCMC, so that the generator model accumulates the MCMC transitions and reproduces them by direct ancestral sampling.

## [2. Awesome Integration](/content/stn1slv/awesome-integration/README.md)

### Projects / API Management

*   [Gravitee.io API Management (⭐214) (⭐212)](https://github.com/gravitee-io/gravitee-api-management) - A flexible, lightweight, and open-source API management solution that provides comprehensive API management capabilities and helps you manage your APIs with ease.
*   [WSO2 API Manager (⭐873) (⭐873)](https://github.com/wso2/product-apim) - A fully open-source API management platform that provides comprehensive API management capabilities and allows you to manage APIs with ease.

### Projects / API Design

*   [OpenAPI Diff (⭐860) (⭐855)](https://github.com/OpenAPITools/openapi-diff) - Compare OpenAPI specs with version control and visualize the differences in HTML or Markdown format.
*   [Spectral (⭐2.6k) (⭐2.6k)](https://github.com/stoplightio/spectral) - Detect and fix errors in your JSON/YAML files using this linter tool that supports OpenAPI 3.0 & 2.0 and AsyncAPI.
*   [Zally (⭐917) (⭐915)](https://github.com/zalando/zally) - Ensure the quality of your OpenAPI specs with this linter tool that provides extensive analysis and feedback.

### Projects / API Documentation

*   [OpenAPI Explorer (⭐321) (⭐318)](https://github.com/Rhosys/openapi-explorer) - A tool for generating user interfaces from OpenAPI specifications, making it easier for software engineers to visualize and interact with APIs.
*   [Stoplight Elements (⭐1.9k) (⭐1.9k)](https://github.com/stoplightio/elements) - Beautiful API documentation powered by OpenAPI and Markdown. Use these UI components to create API reference documentation, or more complete documentation with Markdown articles covering tutorials, how-to guides, etc.
*   [Zudoku (⭐133) (⭐128)](https://github.com/zuplo/zudoku) - An open-source, OpenAPI powered, highly customizable API documentation framework for building quality developer experiences.

### Projects / API Gateway

*   [Gloo Edge (⭐54) (⭐39)](https://github.com/solo-io/gloo) - An Envoy Proxy-based API Gateway that provides advanced traffic management, security, and observability features for modern microservices architectures.
*   [KrakenD API Gateway (⭐2.1k) (⭐2.1k)](https://github.com/devopsfaith/krakend-ce) - An ultra-high performance API Gateway that leverages middlewares for fast and efficient API management.
*   [Traefik (⭐53k) (⭐53k)](https://github.com/traefik/traefik) - A modern, open-source API Gateway that is designed to handle dynamic container environments such as Kubernetes, Docker Swarm, and Mesos. It provides load balancing, SSL/TLS termination, rate limiting, circuit breaking, and more.

### Projects / API Testing

*   Mocking tools
    *   [Imposter (⭐380) (⭐377)](https://github.com/outofcoffee/imposter) - Mock server for REST APIs, OpenAPI (and Swagger) specifications, SOAP web services (and WSDL files), Salesforce and HBase APIs.
    *   [Microcks (⭐1.5k) (⭐1.5k)](https://github.com/microcks/microcks) - Open-source Kubernetes-native tool for API mocking and testing, supporting AsyncAPI, OpenAPI, Postman Collections, etc.
    *   [Mockable](https://www.mockable.io/) - Simple configurable service to mock out RESTful API or SOAP web-services.
    *   [Mockbin (⭐103) (⭐100)](https://github.com/zuplo/mockbin) - Easily generate custom endpoints to test HTTP requests, and view the request logs from that API for free.
    *   [Mockoon (⭐6.8k) (⭐6.8k)](https://github.com/mockoon/mockoon) - Easy-to-use tool for designing and running mock REST APIs.
    *   [MockServer (⭐4.6k) (⭐4.7k)](https://github.com/mock-server/mockserver) - Easy mocking of any system you integrate with via HTTP or HTTPS.
    *   [Mocky (⭐2k) (⭐2.1k)](https://github.com/MockyAbstract/Mocky) - Free and unlimited online service for generating custom HTTP responses.
    *   [Prism (⭐4.4k) (⭐4.4k)](https://github.com/stoplightio/prism) - Open-source HTTP mock server that can mimic your API's behavior as if you already built it.
    *   [WireMock (⭐6.4k) (⭐6.4k)](https://github.com/tomakehurst/wiremock) - Mock your APIs for fast, robust, and comprehensive testing.

### Projects / Data Mapping Solution

*   [AltasMap (⭐199) (⭐199)](https://github.com/atlasmap/atlasmap) - A web-based data mapping solution that simplifies integration between Java, XML, CSV, and JSON data sources. Its interactive user interface makes configuring integrations easy.

### Projects / ESB

*   [WSO2 Enterprise Integrator (⭐382) (⭐381)](https://github.com/wso2/product-ei) - An API-centric, cloud-native, and distributed integration platform designed to provide a robust solution for software engineers.

### Projects / Integration Frameworks

*   [Ballerina (⭐3.7k) (⭐3.7k)](https://github.com/ballerina-platform/ballerina-lang) - An open-source programming language that simplifies the creation, usage, and combination of network services.
*   [Frank!Framework (⭐135) (⭐134)](https://github.com/frankframework/frankframework) - A Low-Code Java-based messaging framework to connect your system and application data, that is completely configurable through XML configurations.

### Projects / Workflow engine

*   [Bonita (⭐161) (⭐160)](https://github.com/bonitasoft/bonita-engine) - An open-source BPMN engine that comes with a designer and optional development environment, making it easier to build and automate complex business processes.

### Resources / API Specification

*   [CloudEvents (⭐5.2k) (⭐5.2k)](https://github.com/cloudevents/spec) -  A specification for describing event data in common formats to provide interoperability across services, platforms and systems.

### Resources / Data Formats

*   [NDJSON (⭐704) (⭐701)](https://github.com/ndjson/ndjson-spec) - A standard for delimiting JSON objects in stream protocols. It allows for efficient processing of large JSON datasets and is widely used in big data processing.
*   [YAML (⭐365) (⭐359)](https://github.com/yaml/yaml-spec) - A human-friendly and easy-to-read data serialization format that is widely used for configuration files and data exchange. It supports rich data types and is compatible with most programming languages.

## [3. Awesome Mac](/content/jaywcjlove/awesome-mac/README.md)

### Developer Tools / Command Line Tools

*   [Television (⭐1.9k)](https://github.com/alexpasmantier/television) - A very fast general purpose fuzzy finder TUI. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/alexpasmantier/television) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

## [4. Awesome Ios](/content/vsouza/awesome-ios/README.md)

### Command Line

*   [Ashen (⭐103)](https://github.com/colinta/Ashen) - A framework for writing terminal applications in Swift.
*   [Linenoise (⭐146)](https://github.com/andybest/linenoise-swift) - A pure Swift replacement for readline
*   [Progress (⭐348)](https://github.com/jkandzi/Progress.swift) - Add beautiful progress bars to your loops.
*   [Swift Argument Parser (⭐3.4k)](https://github.com/apple/swift-argument-parser) - Straightforward, type-safe argument parsing for Swift
*   [SwiftCLI (⭐866)](https://github.com/jakeheis/SwiftCLI) - A powerful framework for developing CLIs in Swift

## [5. Awesome Agriculture](/content/brycejohnston/awesome-agriculture/README.md)

### Farm Management Systems and Record Keeping

*   [LiteFarm (⭐134)](https://github.com/LiteFarmOrg/LiteFarm) - LiteFarm is the world’s first community-led, not-for-profit, Farm management system

## [6. Awesome Jamstack](/content/automata/awesome-jamstack/README.md)

### API / Forms

*   [Form.taxi](https://form.taxi) - An endpoint for HTML forms to handle submissions with ease. It offers a rich feature set with email notifications, file uploads, submissions archive, GDPR-compliant data processing and a lot more.

## [7. Awesome Vue](/content/vuejs/awesome-vue/README.md)

### Components & Libraries / UI Components

*   [vue-smooth-picker (⭐217)](https://github.com/hiyali/vue-smooth-picker) - A SmoothPicker for Vue 3 (like native datetime picker of iOS)

## [8. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### Unspecified / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ng-verse (⭐18)](https://github.com/lukonik/ng-verse) - A collection of feature-rich Angular components, directives, and pipes. Unlike traditional UI libraries, it requires no installation—just copy and paste what you need into your project.  Check the [docs](https://www.ng-verse.dev/) for more.

## [9. Free Programming Books (English, By Programming Language)](/content/EbookFoundation/free-programming-books/README.md)

### Zig / Vulkan

*   [Introduction to Zig](https://pedropark99.github.io/zig-book) - Pedro Duarte Faria (HTML)
*   [Zig Language Reference](https://ziglang.org/documentation/master) (HTML)

---

- Next: [Feb 04, 2025](/content/2025/02/04/README.md)