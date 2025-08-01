# Awesome Fastapi Overview

A curated list of awesome things related to FastAPI

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mjhea0/awesome-fastapi/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 mjhea0/awesome-fastapi](https://github.com/mjhea0/awesome-fastapi) · ⭐ 10K · 🏷️ Back-End Development

[ [Daily](/content/mjhea0/awesome-fastapi/README.md) / [Weekly](/content/mjhea0/awesome-fastapi/week/README.md) / Overview ]

---

<!--lint disable double-link-->

# Awesome FastAPI | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to FastAPI.

[FastAPI](https://fastapi.tiangolo.com/) is a modern, high-performance, batteries-included Python web framework that's perfect for building RESTful APIs.

## Contents

*   [Third-Party Extensions](#third-party-extensions)
    *   [Admin](#admin)
    *   [Auth](#auth)
    *   [Databases](#databases)
    *   [Developer Tools](#developer-tools)
    *   [Email](#email)
    *   [Utils](#utils)
*   [Resources](#resources)
    *   [Official Resources](#official-resources)
    *   [External Resources](#external-resources)
    *   [Podcasts](#podcasts)
    *   [Articles](#articles)
    *   [Tutorials](#tutorials)
    *   [Talks](#talks)
    *   [Videos](#videos)
    *   [Courses](#courses)
    *   [Best Practices](#best-practices)
*   [Hosting](#hosting)
    *   [PaaS](#paas)
    *   [IaaS](#iaas)
    *   [Serverless](#serverless)
*   [Projects](#projects)
    *   [Boilerplate](#boilerplate)
    *   [Docker Images](#docker-images)
    *   [Open Source Projects](#open-source-projects)
*   [Sponsors](#sponsors)

## Third-Party Extensions

### Admin

*   [FastAPI Admin (⭐3.3k)](https://github.com/fastapi-admin/fastapi-admin) - Functional admin panel that provides a user interface for performing CRUD operations on your data. Currently only works with the Tortoise ORM.
*   [FastAPI Amis Admin (⭐1.3k)](https://github.com/amisadmin/fastapi-amis-admin) - A high-performance, efficient and easily extensible FastAPI admin framework.
*   [Piccolo Admin (⭐364)](https://github.com/piccolo-orm/piccolo_admin) - A powerful and modern admin GUI, using the Piccolo ORM.
*   [SQLAlchemy Admin (⭐2.3k)](https://github.com/aminalaee/sqladmin) - Admin Panel for FastAPI/Starlette that works with SQLAlchemy models.
*   [Starlette Admin (⭐811)](https://github.com/jowilf/starlette-admin) - Admin framework for FastAPI/Starlette, supporting SQLAlchemy, SQLModel, MongoDB, and ODMantic.

### Auth

*   [AuthX (⭐958)](https://github.com/yezz123/AuthX) - Customizable Authentications and Oauth2 management for FastAPI.
*   [FastAPI Auth (⭐166)](https://github.com/dmontagu/fastapi-auth) - Pluggable auth that supports the OAuth2 Password Flow with JWT access and refresh tokens.
*   [FastAPI Azure Auth (⭐537)](https://github.com/Intility/fastapi-azure-auth) - Azure AD authentication for your APIs with single and multi tenant support.
*   [FastAPI Cloud Auth (⭐350)](https://github.com/tokusumi/fastapi-cloudauth) - Simple integration between FastAPI and cloud authentication services (AWS Cognito, Auth0, Firebase Authentication).
*   [FastAPI Login (⭐678)](https://github.com/maxrdu/fastapi_login) - Account management and authentication (based on [Flask-Login (⭐3.6k)](https://github.com/maxcountryman/flask-login)).
*   [FastAPI JWT Auth (⭐716)](https://github.com/IndominusByte/fastapi-jwt-auth) - JWT auth (based on [Flask-JWT-Extended (⭐1.6k)](https://github.com/vimalloc/flask-jwt-extended)).
*   [FastAPI Permissions (⭐542)](https://github.com/holgi/fastapi-permissions) - Row-level permissions.
*   [FastAPI Security (⭐154)](https://github.com/jacobsvante/fastapi-security) - Implements authentication and authorization as dependencies in FastAPI.
*   [FastAPI Simple Security (⭐373)](https://github.com/mrtolkien/fastapi_simple_security) - Out-of-the-box API key security manageable through path operations.
*   [FastAPI Users (⭐5.4k)](https://github.com/fastapi-users/fastapi-users) - Account management, authentication, authorization.

### Databases

#### ORMs

*   [Edgy ORM (⭐292)](https://github.com/dymmond/edgy) - Complex databases made simple.
*   [FastAPI SQLAlchemy (⭐658)](https://github.com/mfreeborn/fastapi-sqlalchemy) - Simple integration between FastAPI and [SQLAlchemy](https://www.sqlalchemy.org/).
*   [Fastapi-SQLA (⭐294)](https://github.com/dialoguemd/fastapi-sqla) - SQLAlchemy extension for FastAPI with support for pagination, asyncio, and pytest.
*   [FastAPIwee (⭐20)](https://github.com/Ignisor/FastAPIwee) - A simple way to create REST API based on [PeeWee (⭐12k)](https://github.com/coleifer/peewee) models.
*   [GINO (⭐2.7k)](https://github.com/python-gino/gino) - A lightweight asynchronous ORM built on top of SQLAlchemy core for Python asyncio.
    *   [FastAPI Example (⭐446)](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
*   [ORM (⭐1.8k)](https://github.com/encode/orm) - An async ORM.
*   [ormar](https://collerek.github.io/ormar/) - Ormar is an async ORM that uses Pydantic validation and can be used directly in FastAPI requests and responses so you are left with only one set of models to maintain. Alembic migrations included.
    *   [FastAPI Example](https://collerek.github.io/ormar/latest/fastapi/) - Using FastAPI with ormar.
*   [Piccolo (⭐1.6k)](https://github.com/piccolo-orm/piccolo) - An async ORM and query builder, supporting Postgres and SQLite, with batteries (migrations, security, etc).
    *   [FastAPI Examples (⭐22)](https://github.com/piccolo-orm/piccolo_examples) - Using FastAPI with Piccolo.
*   [Prisma Client Python (⭐2k)](https://github.com/RobertCraigie/prisma-client-py) - An auto-generated, fully type safe ORM powered by Pydantic and tailored specifically for your schema - supports SQLite, PostgreSQL, MySQL, MongoDB, MariaDB and more.
    *   [FastAPI Example (⭐2k)](https://github.com/RobertCraigie/prisma-client-py/tree/main/examples/fastapi-basic)
*   [Tortoise ORM](https://tortoise.github.io) - An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django.
    *   [FastAPI Example](https://tortoise.github.io/examples/fastapi.html) - An example of the Tortoise-ORM FastAPI integration.
    *   [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
    *   [Aerich (⭐944)](https://github.com/tortoise/aerich) - Tortoise ORM migrations tools.
*   [Saffier ORM (⭐61)](https://github.com/tarsil/saffier) - The only Python ORM you will ever need.
*   [SQLModel](https://sqlmodel.tiangolo.com/) - SQLModel (which is powered by Pydantic and SQLAlchemy) is a library for interacting with SQL databases from Python code, with Python objects.

#### Query Builders

*   [asyncpgsa (⭐419)](https://github.com/CanopyTax/asyncpgsa) - A wrapper around [asyncpg (⭐7.4k)](https://github.com/MagicStack/asyncpg) for use with [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).
*   [Databases (⭐3.9k)](https://github.com/encode/databases) - Async SQL query builder that works on top of the [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) expression language.
*   [PyPika (⭐2.7k)](https://github.com/kayak/pypika) - A SQL query builder that exposes the full richness of the SQL language.

#### ODMs

*   [Beanie (⭐2.4k)](https://github.com/BeanieODM/beanie) - Asynchronous Python ODM for MongoDB, based on [Motor](https://motor.readthedocs.io/en/stable/) and [Pydantic](https://docs.pydantic.dev/latest/), which supports data and schema migrations out of the box.
*   [MongoEngine](http://mongoengine.org/) - A Document-Object Mapper (think ORM, but for document databases) for working with MongoDB from Python.
*   [Motor](https://motor.readthedocs.io/) - Asynchronous Python driver for MongoDB.
*   [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM integrated with [Pydantic](https://docs.pydantic.dev/latest/).
*   [PynamoDB (⭐2.5k)](https://github.com/pynamodb/PynamoDB) - A pythonic interface to Amazon's DynamoDB.

#### Other Tools

*   [Pydantic-SQLAlchemy (⭐1.3k)](https://github.com/tiangolo/pydantic-sqlalchemy) - Convert SQLAlchemy models to [Pydantic](https://docs.pydantic.dev/latest/) models.
*   [FastAPI-CamelCase](https://nf1s.github.io/fastapi-camelcase/) - CamelCase JSON support for FastAPI utilizing [Pydantic](https://docs.pydantic.dev/latest/).
    *   [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - Accompanying blog post from the author of the extension.

### Developer Tools

*   [FastAPI Code Generator (⭐1.2k)](https://github.com/koxudaxi/fastapi-code-generator) - Create a FastAPI app from an OpenAPI file, enabling schema-driven development.
*   [FastAPI Client Generator (⭐340)](https://github.com/dmontagu/fastapi_client) - Generate a mypy- and IDE-friendly API client from an OpenAPI spec.
*   [FastAPI Cruddy Framework (⭐34)](https://github.com/mdconaway/fastapi-cruddy-framework) - A companion library to FastAPI designed to bring the development productivity of Ruby on Rails, Ember.js or Sails.js to the FastAPI ecosystem.
*   [FastAPI MVC (⭐678)](https://github.com/fastapi-mvc/fastapi-mvc) - Developer productivity tool for making high-quality FastAPI production-ready APIs.
*   [FastAPI Profiler (⭐266)](https://github.com/sunhailin-Leo/fastapi_profiler) - A FastAPI Middleware of joerick/pyinstrument to check your service performance.
*   [FastAPI Versioning (⭐722)](https://github.com/DeanWay/fastapi-versioning) - API versioning.
*   [Jupyter Notebook REST API (⭐82)](https://github.com/Invictify/Jupter-Notebook-REST-API) - Run your Jupyter notebooks as RESTful API endpoints.
*   [Manage FastAPI (⭐1.8k)](https://github.com/ycd/manage-fastapi) - CLI tool for generating and managing FastAPI projects.
*   [msgpack-asgi (⭐173)](https://github.com/florimondmanca/msgpack-asgi) - Automatic [MessagePack](https://msgpack.org/) content negotiation.

### Email

*   [FastAPI Mail (⭐814)](https://github.com/sabuhish/fastapi-mail) - Lightweight mail system for sending emails and attachments (individual and bulk).

### Utils

*   [Apitally (⭐97)](https://github.com/apitally/apitally-py) - API analytics, monitoring, and request logging for FastAPI.
*   [ASGI Correlation ID (⭐500)](https://github.com/snok/asgi-correlation-id) - Request ID logging middleware.
*   [FastAPI Cache (⭐222)](https://github.com/comeuplater/fastapi_cache) - A simple lightweight cache system.
*   [FastAPI Cache (⭐1.6k)](https://github.com/long2ice/fastapi-cache) - A tool to cache FastAPI response and function results, with support for Redis, Memcached, DynamoDB, and in-memory backends.
*   [FastAPI Chameleon (⭐140)](https://github.com/mikeckennedy/fastapi-chameleon) - Adds integration of the Chameleon template language to FastAPI.
*   [FastAPI CloudEvents (⭐35)](https://github.com/sasha-tkachev/fastapi-cloudevents) - [CloudEvents](https://cloudevents.io/) integration for FastAPI.
*   [FastAPI Contrib (⭐638)](https://github.com/identixone/fastapi_contrib) - Opinionated set of utilities: pagination, auth middleware, permissions, custom exception handlers, MongoDB support, and Opentracing middleware.
*   [FastAPI FastCRUD (⭐1.2k)](https://github.com/benavlabs/fastcrud)) - Robust async CRUD operations and flexible endpoint creation utilities.
*   [FastAPI Events (⭐502)](https://github.com/melvinkcx/fastapi-events) - Asynchronous event dispatching/handling library for FastAPI and Starlette.
*   [FastAPI FeatureFlags (⭐66)](https://github.com/Pytlicek/fastapi-featureflags) - Simple implementation of feature flags for FastAPI.
*   [FastAPI Injectable (⭐155)](https://github.com/JasperSui/fastapi-injectable) - Use FastAPI's dependency injection outside route handlers in CLI tools, background tasks, workers, and more.
*   [FastAPI Jinja (⭐71)](https://github.com/AGeekInside/fastapi-jinja) - Adds integration of the Jinja template language to FastAPI.
*   [FastAPI Lazy (⭐116)](https://github.com/yezz123/fastango) - Lazy package to start your project using FastAPI.
*   [FastAPI Limiter (⭐598)](https://github.com/long2ice/fastapi-limiter) - A request rate limiter for FastAPI.
*   [FastAPI Listing (⭐55)](https://github.com/danielhasan1/fastapi-listing) - A library to design/build listing APIs using component-based architecture, inbuilt query paginator, sorter, django-admin like filters & much more.
*   [FastAPI MQTT (⭐285)](https://github.com/sabuhish/fastapi-mqtt) - An extension for the MQTT protocol.
*   [FastAPI Opentracing (⭐24)](https://github.com/wesdu/fastapi-opentracing) - Opentracing middleware and database tracing support for FastAPI.
*   [FastAPI Pagination (⭐1.4k)](https://github.com/uriyyo/fastapi-pagination) - Pagination for FastAPI.
*   [FastAPI Plugins (⭐470)](https://github.com/madkote/fastapi-plugins) - Redis and Scheduler plugins.
*   [FastAPI ServiceUtils (⭐33)](https://github.com/skallfass/fastapi_serviceutils) - Generator for creating API services.
*   [FastAPI SocketIO (⭐334)](https://github.com/pyropy/fastapi-socketio) - Easy integration for FastAPI and SocketIO.
*   [FastAPI Utilities (⭐2.1k)](https://github.com/fastapiutils/fastapi-utils) - Reusable utilities: class-based views, response inferring router, periodic tasks, timing middleware, SQLAlchemy session, OpenAPI spec simplification.
*   [FastAPI Websocket Pub/Sub (⭐16)](https://github.com/authorizon/fastapi_websocket_pubsub) - The classic pub/sub pattern made easily accessible and scalable over the web and across your cloud in realtime.
*   [FastAPI Websocket RPC (⭐8)](https://github.com/authorizon/fastapi_websocket_rpc) - RPC (bidirectional JSON RPC) over Websockets made easy, robust, and production ready.
*   [OpenTelemetry FastAPI Instrumentation (⭐863)](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation/opentelemetry-instrumentation-fastapi) - Library provides automatic and manual instrumentation of FastAPI web frameworks, instrumenting http requests served by applications utilizing the framework.
*   [Prerender Python Starlette (⭐16)](https://github.com/BeeMyDesk/prerender-python-starlette) - Starlette middleware for Prerender.
*   [Prometheus FastAPI Instrumentator (⭐1.2k)](https://github.com/trallnag/prometheus-fastapi-instrumentator) - A configurable and modular Prometheus Instrumentator for your FastAPI application.
*   [SlowApi (⭐1.5k)](https://github.com/laurents/slowapi) - Rate limiter (based on [Flask-Limiter](https://flask-limiter.readthedocs.io)).
*   [Starlette Context (⭐500)](https://github.com/tomwojcik/starlette-context) - Allows you to store and access the request data anywhere in your project, useful for logging.
*   [Starlette Exporter (⭐319)](https://github.com/stephenhillier/starlette_exporter) - One more prometheus integration for FastAPI and Starlette.
*   [Starlette OpenTracing (⭐65)](https://github.com/acidjunk/starlette-opentracing) - Opentracing support for Starlette and FastAPI.
*   [Starlette Prometheus (⭐292)](https://github.com/perdy/starlette-prometheus) - Prometheus integration for FastAPI and Starlette.
*   [Strawberry GraphQL (⭐4.3k)](https://github.com/strawberry-graphql/strawberry) - Python GraphQL library based on dataclasses.

## Resources

### Official Resources

*   [Documentation](https://fastapi.tiangolo.com/) - Comprehensive documentation.
*   [Tutorial](https://fastapi.tiangolo.com/tutorial/) - Official tutorial showing you how to use FastAPI with most of its features, step by step.
*   [Source Code (⭐87k)](https://github.com/fastapi/fastapi) - Hosted on GitHub.
*   [Discord](https://discord.com/invite/VQjSZaeJmf) - Chat with other FastAPI users.

### External Resources

*   [TestDriven.io FastAPI](https://testdriven.io/blog/topics/fastapi/) - Multiple FastAPI-specific articles that focus on developing and testing production-ready RESTful APIs, serving up machine learning models, and more.

### Podcasts

*   [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - In this episode of [Podcast Init](https://www.pythonpodcast.com/), the creator of FastAPI, [Sebastián Ramirez](https://tiangolo.com/), shares his motivations for building FastAPI and how it works under the hood.
*   [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) - Nice overview of the project.

### Articles

*   [FastAPI has Ruined Flask Forever for Me](https://medium.com/data-science/fastapi-has-ruined-flask-forever-for-me-73916127da)
*   [Why we switched from Flask to FastAPI for production machine learning](https://medium.com/@calebkaiser/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) - In-depth look at why you may want to move from Flask to FastAPI.

### Tutorials

*   [Async SQLAlchemy with FastAPI](https://stribny.name/posts/fastapi-asyncalchemy/) - Learn how to use SQLAlchemy asynchronously.
*   [Build and Secure an API in Python with FastAPI](https://blog.yezz.me/blog/Build-and-Secure-an-API-in-Python-with-FastAPI) - Secure and maintain an API based on FastAPI and SQLAlchemy.
*   [Deploy Machine Learning Models with Keras, FastAPI, Redis and Docker](https://medium.com/analytics-vidhya/deploy-machine-learning-models-with-keras-fastapi-redis-and-docker-4940df614ece)
*   [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - Develop and test an asynchronous API with FastAPI, Postgres, Pytest, and Docker using Test-Driven Development.
*   [FastAPI for Flask Users](https://amitness.com/posts/fastapi-vs-flask) - Learn FastAPI with a side-by-side code comparison to Flask.
*   [Getting started with GraphQL in Python with FastAPI and Ariadne](https://blog.yezz.me/blog/Getting-started-with-GraphQL-in-Python-with-FastAPI-and-Ariadne) - Generate a FullStack playground using FastAPI, GraphQL and Ariadne.
*   [Implementing FastAPI Services – Abstraction and Separation of Concerns](https://camillovisini.com/coding/abstracting-fastapi-services) - FastAPI application and service structure for a more maintainable codebase.
*   [Introducing FARM Stack - FastAPI, React, and MongoDB](https://www.mongodb.com/developer/languages/python/farm-stack-fastapi-react-mongodb/) - Getting started with a complete FastAPI web application stack.
*   [Multitenancy with FastAPI, SQLAlchemy and PostgreSQL](https://mergeboard.com/blog/6-multitenancy-fastapi-sqlalchemy-postgresql/) - Learn how to make FastAPI applications multi-tenant ready.
*   [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) - Comparison of Flask vs FastAPI.
*   [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/posts/real-time-data-streaming-using-fastapi-and-websockets/) - Learn how to stream data from FastAPI directly into a real-time chart.
*   [Running FastAPI applications in production](https://stribny.name/posts/fastapi-production/) - Use Gunicorn with systemd for production deployments.
*   [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) - Use FastAPI to quickly and easily deploy and serve machine learning models in Python as a RESTful API.
*   [Streaming video with FastAPI](https://stribny.name/posts/fastapi-video/) - Learn how to serve video streams.
*   [Using Hypothesis and Schemathesis to Test FastAPI](https://testdriven.io/blog/fastapi-hypothesis/) - Apply property-based testing to FastAPI.

### Talks

*   [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) - From the talk by Sebastian Ramirez you will learn how to easily build a production-ready web (JSON) API for your ML models with FastAPI, including best practices by default.
*   [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) - This talk shows how to build a simple REST API for a database from the ground up using FastAPI.

### Videos

*   [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) - A you build a web-based stock screener with FastAPI, you'll be introduced to many of FastAPI's features, including Pydantic models, dependency injection, background tasks, and SQLAlchemy integration.
*   [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) - Use FastAPI to build a web application programming interface (RESTful API).
*   [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI\&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) - See how to do numeric validations with FastAPI.
*   [FastAPI vs. Django vs. Flask](https://www.youtube.com/watch?v=9YBAOYQOzWs) - Which framework is best for Python in 2020? Which uses async/await the best? Which is the fastest?
*   [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) - Build a machine learning API with FastAPI.

### Courses

*   [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) - Learn how to build, test, and deploy a text summarization microservice with Python, FastAPI, and Docker.
*   [Modern APIs with FastAPI and Python](https://training.talkpython.fm/courses/modern-fastapi-apis) - A course designed to get you creating new APIs running in the cloud with FastAPI quickly.
*   [Full Web Apps with FastAPI Course](https://training.talkpython.fm/courses/full-html-web-applications-with-fastapi) - You'll learn to build full web apps with FastAPI, equivalent to what you can do with Flask or Django.
*   [The Definitive Guide to Celery and FastAPI](https://testdriven.io/courses/fastapi-celery/) - Learn how to add Celery to a FastAPI application to provide asynchronous task processing.

### Best Practices

*   [FastAPI Best Practices (⭐12k)](https://github.com/zhanymkanov/fastapi-best-practices) - Collection of best practices in a GitHub repo.

## Hosting

### PaaS

(Platforms-as-a-Service)

*   [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
*   [Deta](https://www.deta.sh/) ([example](https://dev.to/athulcajay/fastapi-deta-ni5))
*   [Fly](https://fly.io) ([tutorial](https://fly.io/docs/python/frameworks/fastapi/), [Deploy from a Git repo (⭐7)](https://github.com/fly-apps/hello-fastapi))
*   [Google App Engine](https://cloud.google.com/appengine)
*   [Heroku](https://www.heroku.com/) ([Step-by-step tutorial](https://tutlinks.com/create-and-deploy-fastapi-app-to-heroku/), [ML model on Heroku tutorial](https://testdriven.io/blog/fastapi-machine-learning/))
*   [Microsoft Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)

### IaaS

(Infrastructure-as-a-Service)

*   [AWS EC2](https://aws.amazon.com/ec2/)
*   [Google Compute Engine](https://cloud.google.com/compute)
*   [Digital Ocean](https://www.digitalocean.com/)
*   [Linode](https://www.linode.com/)

### Serverless

Frameworks:

*   [Chalice (⭐11k)](https://github.com/aws/chalice)
*   [Mangum](https://mangum.io/) - Adapter for running ASGI applications with AWS Lambda and API Gateway.
*   [Vercel](https://vercel.com/) - (formerly Zeit) ([example (⭐85)](https://github.com/Snailedlt/Markdown-Videos)).

Compute:

*   [AWS Lambda](https://aws.amazon.com/lambda/) ([example (⭐133)](https://github.com/iwpnd/fastapi-aws-lambda-example))
*   [Google Cloud Functions](https://cloud.google.com/functions)
*   [Azure Functions](https://azure.microsoft.com/en-us/products/functions/)
*   [Google Cloud Run](https://cloud.google.com/run) ([example (⭐199)](https://github.com/anthonycorletti/cloudrun-fastapi))

## Projects

### Boilerplate

*   [Full Stack FastAPI and PostgreSQL - Base Project Generator (⭐35k)](https://github.com/fastapi/full-stack-fastapi-template) - Full Stack FastAPI Template
    , which includes FastAPI, React, SQLModel, PostgreSQL, Docker, GitHub Actions, automatic HTTPS, and more (developed by the creator of FastAPI, [Sebastián Ramírez](https://github.com/tiangolo)).
*   [FastAPI and Tortoise ORM (⭐138)](https://github.com/prostomarkeloff/fastapi-tortoise) - Powerful but simple template for web APIs w/ FastAPI (as web framework) and Tortoise-ORM (for working via database without headache).
*   [FastAPI Model Server Skeleton (⭐473)](https://github.com/eightBEC/fastapi-ml-skeleton) - Skeleton app to serve machine learning models production-ready.
*   [cookiecutter-spacy-fastapi (⭐533)](https://github.com/microsoft/cookiecutter-spacy-fastapi) - Quick deployments of spaCy models with FastAPI.
*   [cookiecutter-fastapi (⭐571)](https://github.com/arthurhenrique/cookiecutter-fastapi) - Cookiecutter template for FastAPI projects using: Machine Learning, Poetry, Azure Pipelines and pytest.
*   [openapi-python-client (⭐1.6k)](https://github.com/openapi-generators/openapi-python-client) - Generate modern FastAPI Python clients (via FastAPI) from OpenAPI.
*   [Pywork (⭐11)](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) generator to scaffold a FastAPI app.
*   [fastapi-gino-arq-uvicorn (⭐446)](https://github.com/leosussan/fastapi-gino-arq-uvicorn) - Template for a high-performance async REST API, in Python. FastAPI + GINO + Arq + Uvicorn (w/ Redis and PostgreSQL).
*   [FastAPI and React Template (⭐2.4k)](https://github.com/Buuntu/fastapi-react) - Full stack cookiecutter boilerplate using FastAPI, TypeScript, Docker, PostgreSQL, and React.
*   [FastAPI Nano (⭐937)](https://github.com/rednafi/fastapi-nano) - Simple FastAPI template with factory pattern architecture.
*   [FastAPI template (⭐2.4k)](https://github.com/s3rius/FastAPI-template) - Flexible, lightweight FastAPI project generator. It includes support for SQLAlchemy, multiple databases, CI/CD, Docker, and Kubernetes.
*   [FastAPI on Google Cloud Run (⭐199)](https://github.com/anthonycorletti/cloudrun-fastapi) - Boilerplate for API building with FastAPI, SQLModel, and Google Cloud Run.
*   [FastAPI with Firestore (⭐48)](https://github.com/anthonycorletti/firestore-fastapi) - Boilerplate for API building with FastAPI and Google Cloud Firestore.
*   [fastapi-alembic-sqlmodel-async (⭐1.1k)](https://github.com/jonra1993/fastapi-alembic-sqlmodel-async) - This is a project template which uses FastAPI, Alembic, and async SQLModel as ORM.
*   [fastapi-starter-project (⭐122)](https://github.com/mirzadelic/fastapi-starter-project) - A project template which uses FastAPI, SQLModel, Alembic, Pytest, Docker, GitHub Actions CI.
*   [Full Stack FastAPI and MongoDB - Base Project Generator (⭐665)](https://github.com/mongodb-labs/full-stack-fastapi-mongodb) - Full stack, modern web application generator, which includes FastAPI, MongoDB, Docker, Celery, React frontend, automatic HTTPS and more.
*   [Uvicorn Poetry FastAPI Project Template (⭐14)](https://github.com/max-pfeiffer/uvicorn-poetry-fastapi-project-template) - Cookiecutter project template for starting a FastAPI application. Runs in a Docker container with Uvicorn ASGI server on Kubernetes. Supports AMD64 and ARM64 CPU architectures.

### Docker Images

*   [inboard (⭐200)](https://github.com/br3ndonland/inboard) - Docker images to power your FastAPI apps and help you ship faster.
*   [uvicorn-gunicorn-fastapi-docker (⭐2.8k)](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - Docker image with Uvicorn managed by Gunicorn for high-performance FastAPI web applications in Python 3.7 and 3.6 with performance auto-tuning.
*   [uvicorn-gunicorn-poetry (⭐45)](https://github.com/max-pfeiffer/uvicorn-gunicorn-poetry) - Docker image with Gunicorn using Uvicorn workers for running Python web applications. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.
*   [uvicorn-poetry (⭐54)](https://github.com/max-pfeiffer/uvicorn-poetry) - Docker image with Uvicorn ASGI server for running Python web applications on Kubernetes. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.

### Open Source Projects

*   [Astrobase (⭐68)](https://github.com/anthonycorletti/astrobase) - Simple, fast, and secure deployments anywhere.
*   [Awesome FastAPI Projects (⭐1.5k)](https://github.com/Kludex/awesome-fastapi-projects) - Organized list of projects that use FastAPI.
*   [Bitcart (⭐677)](https://github.com/bitcart/bitcart) - Platform for merchants, users and developers which offers easy setup and use.
*   [Bali (⭐283)](https://github.com/bali-framework/bali) - Simplify Cloud Native Microservices development base on FastAPI and gRPC.
*   [Bunnybook (⭐301)](https://github.com/pietrobassi/bunnybook) - A tiny social network built with FastAPI, React+RxJs, Neo4j, PostgreSQL, and Redis.
*   [Coronavirus-tg-api (⭐14)](https://github.com/egbakou/coronavirus-tg-api) - API for tracking the global coronavirus (COVID-19, SARS-CoV-2) outbreak.
*   [Dispatch (⭐5.9k)](https://github.com/Netflix/dispatch) - Manage security incidents.
*   FastAPI CRUD Example:
    *   [Async flavor (⭐470)](https://github.com/testdrivenio/fastapi-crud-async)
    *   [Sync Flavor (⭐78)](https://github.com/testdrivenio/fastapi-crud-sync)
*   [FastAPI with Observability (⭐850)](https://github.com/Blueswen/fastapi-observability) - Observe FastAPI app with three pillars of observability: Traces (Tempo), Metrics (Prometheus), Logs (Loki) on Grafana through OpenTelemetry and OpenMetrics.
*   [DogeAPI (⭐155)](https://github.com/yezz123/DogeAPI) - API with high performance to create a simple blog and CRUD with OAuth2PasswordBearer.
*   [FastAPI Websocket Broadcast (⭐139)](https://github.com/kthwaite/fastapi-websocket-broadcast) - Websocket 'broadcast' demo.
*   [FastAPI with Celery, RabbitMQ, and Redis (⭐558)](https://github.com/GregaVrbancic/fastapi-celery) - Minimal example utilizing FastAPI and Celery with RabbitMQ for task queue, Redis for Celery backend, and Flower for monitoring the Celery tasks.
*   [FuturamaAPI (⭐155)](https://github.com/koldakov/futuramaapi) - A REST and GraphQL playground built with best practices, providing WebSockets, SSE, callbacks, secret messages, and more.
*   [JeffQL (⭐31)](https://github.com/yezz123/JeffQL/) - Simple authentication and login API using GraphQL and JWT.
*   [JSON-RPC Server (⭐317)](https://github.com/smagafurov/fastapi-jsonrpc) - JSON-RPC server based on FastAPI.
*   [Mailer (⭐61)](https://github.com/rclement/mailer) - Dead-simple mailer micro-service for static websites.
*   [Markdown-Videos (⭐85)](https://github.com/Snailedlt/Markdown-Videos) - API for generating thumbnails to embed into your markdown content.
*   [Nemo (⭐15)](https://github.com/harshitsinghai77/nemo-backend) - Be productive with Nemo.
*   [OPAL (Open Policy Administration Layer) (⭐15)](https://github.com/authorizon/opal) - Real-time authorization updates on top of Open-Policy; built with FastAPI, Typer, and FastAPI WebSocket pub/sub.
*   [Polar (⭐5.8k)](https://github.com/polarsource/polar) - A funding and monetization platform for developers, built with FastAPI, SQLAlchemy, Alembic, and Arq.
*   [RealWorld Example App - mongo (⭐446)](https://github.com/markqiu/fastapi-mongodb-realworld-example-app)
*   [RealWorld Example App - postgres (⭐2.9k)](https://github.com/nsidnev/fastapi-realworld-example-app)
*   [redis-streams-fastapi-chat (⭐247)](https://github.com/leonh/redis-streams-fastapi-chat) - A simple Redis Streams backed chat app using Websockets, Asyncio and FastAPI/Starlette.
*   [Sprites as a service (⭐312)](https://github.com/ljvmiranda921/sprites-as-a-service) - Generate your personal 8-bit avatars using Cellular Automata.
*   [Slackers (⭐78)](https://github.com/uhavin/slackers) - Slack webhooks API.
*   [TermPair (⭐1.6k)](https://github.com/cs01/termpair) - View and control terminals from your browser with end-to-end encryption.
*   [Universities (⭐69)](https://github.com/ycd/universities) - API service for obtaining information about +9600 universities worldwide.

## Sponsors

Please support this open source project by checking out our sponsors:

<a href="https://testdriven.io/courses/tdd-fastapi/?ref=awesome-fastapi" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="https://github.com/mjhea0/awesome-fastapi/raw/main/images/testdriven.svg"></a>

