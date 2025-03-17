# Awesome Asyncio Overview

A curated list of awesome Python asyncio frameworks, libraries, software and resources

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/timofurrer/awesome-asyncio/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 timofurrer/awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) · ⭐ 4.7K · 🏷️ Programming Languages

[ [Daily](/content/timofurrer/awesome-asyncio/README.md) / [Weekly](/content/timofurrer/awesome-asyncio/week/README.md) / Overview ]

---

> \[!WARNING]
> This project is looking for a new home. I'm no longer maintaining it.
> Please let me know if you want to take over maintainance for it.
> Write me an email to [timo@furrer.life](https://github.com/timofurrer/awesome-asyncio/blob/main/README.md/mailto:timo@furrer.life)

# Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2014.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request (⭐4.7k)](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) with your suggestion.

## Contents

*   [Web Frameworks](#web-frameworks)
*   [Message Queues](#message-queues)
*   [Database Drivers](#database-drivers)
*   [Networking](#networking)
*   [GraphQL](#graphql)
*   [Testing](#testing)
*   [Alternative Loops](#alternative-loops)
*   [Misc](#misc)
*   [Writings](#writings)
*   [Talks](#talks)
*   [Alternatives to asyncio](#alternatives-to-asyncio)

***

## Web Frameworks

*Libraries to build web applications.*

*   [FastAPI (⭐82k)](https://github.com/tiangolo/fastapi) - A very high performance Python 3.6+ API framework based on type hints. Powered by Starlette and Pydantic.
*   [Django](https://www.djangoproject.com/) - An established, high-level Python web framework with a huge community and ecosystem.
*   [Starlette (⭐11k)](https://github.com/encode/starlette) - A lightweight ASGI framework/toolkit for building high performance services.
*   [aiohttp (⭐15k)](https://github.com/KeepSafe/aiohttp) - Http client/server for asyncio (PEP-3156).
*   [sanic (⭐18k)](https://github.com/channelcat/sanic) - Python 3.5+ web server that's written to go fast.
*   [Quart (⭐3.2k)](https://github.com/pallets/quart) - An asyncio web microframework with the same API as Flask.
*   [autobahn (⭐2.5k)](https://github.com/crossbario/autobahn-python) - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers.
*   [websockets (⭐5.3k)](https://github.com/aaugustin/websockets/) - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
*   [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.
*   [uvicorn (⭐9k)](https://github.com/encode/uvicorn) - The lightning-fast ASGI server.

## Message Queues

*Libraries to implement applications using message queues.*

*   [aioamqp (⭐280)](https://github.com/Polyconseil/aioamqp) - AMQP implementation using asyncio.
*   [pyzmq (⭐3.8k)](https://github.com/zeromq/pyzmq) - Python bindings for ZeroMQ.
*   [aiozmq (⭐425)](https://github.com/aio-libs/aiozmq) - Alternative Asyncio integration with ZeroMQ.
*   [crossbar (⭐2k)](https://github.com/crossbario/crossbar) - Crossbar.io is a networking platform for distributed and microservice applications.
*   [asyncio-nats (⭐966)](https://github.com/nats-io/asyncio-nats) - Client for the NATS messaging system.
*   [aiokafka (⭐1.2k)](https://github.com/aio-libs/aiokafka) - Client for Apache Kafka.

## Database Drivers

*Libraries to connect to databases.*

*   [asyncpg (⭐7.2k)](https://github.com/MagicStack/asyncpg) - Fast PostgreSQL Database Client Library for Python/asyncio.
*   [asyncpgsa (⭐416)](https://github.com/CanopyTax/asyncpgsa) - Asyncpg with sqlalchemy core support.
*   [aiopg (⭐1.4k)](https://github.com/aio-libs/aiopg/) - Library for accessing a PostgreSQL database.
*   [aiomysql (⭐1.8k)](https://github.com/aio-libs/aiomysql) - Library for accessing a MySQL database
*   [aioodbc (⭐311)](https://github.com/aio-libs/aioodbc) - Library for accessing a ODBC databases.
*   [motor (⭐2.5k)](https://github.com/mongodb/motor) - The async Python driver for MongoDB.
*   [redis-py (⭐13k)](https://github.com/redis/redis-py) - Redis Python Client (which includes [aioreadis (⭐2.3k)](https://github.com/aio-libs/aioredis) now).
*   [aiocouchdb (⭐53)](https://github.com/aio-libs/aiocouchdb) - CouchDB client built on top of aiohttp (asyncio).
*   [aioinflux (⭐160)](https://github.com/plugaai/aioinflux) - InfluxDB client built on top of aiohttp.
*   [aioes (⭐97)](https://github.com/aio-libs/aioes) - Asyncio compatible driver for elasticsearch.
*   [peewee-async (⭐744)](https://github.com/05bit/peewee-async) - ORM implementation based on [peewee (⭐11k)](https://github.com/coleifer/peewee) and aiopg.
*   [GINO (⭐2.7k)](https://github.com/fantix/gino) - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg (⭐7.2k)](https://github.com/MagicStack/asyncpg) dialect.
*   [Tortoise ORM (⭐4.9k)](https://github.com/tortoise/tortoise-orm) - native multi-backend ORM with Django-like API and easy relations management.
*   [Databases (⭐3.9k)](https://github.com/encode/databases) - Async database access for SQLAlchemy core, with support for PostgreSQL, MySQL, and SQLite.
*   [Prisma Client Python (⭐2k)](https://github.com/RobertCraigie/prisma-client-py) - An auto-generated, fully type safe ORM powered by Pydantic and tailored specifically for your schema - supports SQLite, PostgreSQL, MySQL, MongoDB, MariaDB and more.
*   [Piccolo (⭐1.5k)](https://github.com/piccolo-orm/piccolo) - An ORM / query builder which can work in async and sync modes, with a nice admin GUI, and ASGI middleware.
*   [Beanie](https://beanie-odm.dev) - An async MongoDB ODM built on [motor (⭐2.5k)](https://github.com/mongodb/motor) and [Pydantic](https://pydantic-docs.helpmanual.io).

## Networking

*Libraries to communicate in your network.*

*   [AsyncSSH (⭐1.6k)](https://github.com/ronf/asyncssh) - Provides an asynchronous client and server implementation of the SSHv2 protocol.
*   [aiodns (⭐547)](https://github.com/saghul/aiodns) - Simple DNS resolver for asyncio.
*   [aioping (⭐84)](https://github.com/stellarbit/aioping) - Fast asyncio implementation of ICMP (ping) protocol.
*   [httpx (⭐14k)](https://github.com/encode/httpx) - asynchronous HTTP client for Python 3 with [requests (⭐53k)](https://github.com/psf/requests) compatible API.

## GraphQL

*Libraries to build GraphQL servers.*

*   [Ariadne](https://ariadnegraphql.org) - Schema-first Python library for implementing GraphQL servers.
*   [Tartiflette](https://tartiflette.io/) - Schema-first Python 3.6+ GraphQL engine built on top of `libgraphqlparser`.
*   [Strawberry](https://strawberry.rocks) - Code-first Python 3 GraphQL server with Django, Flask and FastAPI/Starlette support.

## Testing

*Libraries to test asyncio based applications.*

*   [aiomock (⭐27)](https://github.com/nhumrich/aiomock/) - A python mock library that supports async methods.
*   [asynctest (⭐309)](https://github.com/Martiusweb/asynctest/) - Enhance the standard unittest package with features for testing. asyncio libraries
*   [pytest-asyncio (⭐1.5k)](https://github.com/pytest-dev/pytest-asyncio) - Pytest support for asyncio.
*   [aresponses (⭐104)](https://github.com/CircleUp/aresponses) - Asyncio http mocking. Similar to the [responses (⭐4.2k)](https://github.com/getsentry/responses) library used for [requests (⭐53k)](https://github.com/requests/requests).
*   [aioresponses (⭐533)](https://github.com/pnuckowski/aioresponses) - Helper for mock/fake web requests in Python aiohttp package.

## Alternative Loops

*Alternative asyncio loop implementations.*

*   [uvloop (⭐11k)](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv.

## Misc

*Other awesome asyncio libraries.*

*   [aiochan (⭐169)](https://github.com/zh217/aiochan) - CSP-style concurrency with channels, select and multiprocessing on top of asyncio.
*   [aiocache (⭐1.2k)](https://github.com/argaen/aiocache) - Cache manager for different backends.
*   [aiofiles (⭐3k)](https://github.com/Tinche/aiofiles/) - File support for asyncio.
*   [aiopath (⭐176)](https://github.com/alexdelorenzo/aiopath) - Asynchronous `pathlib` for asyncio.
*   [aiodebug (⭐62)](https://github.com/qntln/aiodebug) - A tiny library for monitoring and testing asyncio programs.
*   [aiorun (⭐453)](https://github.com/cjrh/aiorun) - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown.
*   [aiosc (⭐36)](https://github.com/artfwo/aiosc) -  Lightweight Open Sound Control implementation.
*   [aioserial (⭐136)](https://github.com/changyuheng/aioserial) - A drop-in replacement of [pySerial (⭐3.3k)](https://github.com/pyserial/pyserial).
*   [aiozipkin (⭐187)](https://github.com/aio-libs/aiozipkin) - Distributed tracing instrumentation for asyncio with zipkin
*   [asgiref (⭐1.5k)](https://github.com/django/asgiref) - Backend utils for ASGI to WSGI integration, includes sync\_to\_async and async\_to\_sync function wrappers.
*   [async\_property (⭐90)](https://github.com/ryananguiano/async_property) - Python decorator for async properties.
*   [ruia (⭐1.8k)](https://github.com/howie6879/ruia) - An async web scraping micro-framework based on asyncio.
*   [kubernetes\_asyncio (⭐382)](https://github.com/tomplus/kubernetes_asyncio) - Asynchronous client library for Kubernetes.
*   [aiomisc (⭐390)](https://github.com/aiokitchen/aiomisc) - Miscellaneous utils for `asyncio`.
*   [taskiq](https://taskiq-python.github.io/) - Asynchronous distributed task manager (like celery, but async).

## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

*   [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
*   [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - Generators, Coroutines, Native Coroutines and async/await.
*   [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
*   [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.
*   [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - A spiritual successor to WSGI, intended to provide a standard interface between async-capable Python web servers, frameworks, and applications.
*   [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - A no-buzzword first principles introduction to the internal workings of asyncio.
*   [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - This tutorial looks at how to develop and test an asynchronous API with FastAPI using Test-Driven Development (TDD).
*   [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio) - Learn how to speed up slow Python code with concurrent programming and the cutting-edge asyncio library.

## Talks

*Recordings of awesome talks about asyncio.*

*   [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 keynote (David Beazley).
*   [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - 8-part code walkthrough (Philip Guo).
*   [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8\&t=132s) - EuroPython 2016 (Yury Selivanov).
*   [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 keynote (David Beazley).
*   [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017 (Miguel Grinberg).
*   [Demystifying Python's Async and Await Keywords](https://www.youtube.com/watch?v=F19R_M4Nay4) - JetBrains TV 2020 (Michael Kennedy)

## Alternatives to asyncio

*Alternative approaches to async programming in Python, some of which attempt to support some compatibility with `asyncio`, others are not compatible at all.*

*   [curio (⭐4.1k)](https://github.com/dabeaz/curio) - The coroutine concurrency library.
    *   [Curio-Asyncio Bridge (⭐4.1k)](https://github.com/dabeaz/curio/issues/190) - basic curio -> asyncio coroutine bridge.
*   [trio (⭐6.4k)](https://github.com/python-trio/trio) - Pythonic async I/O for humans and snake people.
    *   [trio-asyncio (⭐191)](https://github.com/python-trio/trio-asyncio) - re-implementation of the asyncio mainloop on top of Trio.
*   [AnyIO (⭐1.9k)](https://github.com/agronholm/anyio) - High level asynchronous concurrency and networking framework that works on top of either trio or asyncio.

