# Awesome Python Overview

An opinionated list of awesome Python frameworks, libraries, software and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/vinta/awesome-python/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 vinta/awesome-python](https://github.com/vinta/awesome-python) · ⭐ 287K · 🏷️ Programming Languages

[ [Daily](/content/vinta/awesome-python/README.md) / [Weekly](/content/vinta/awesome-python/week/README.md) / Overview ]

---

# Awesome Python

An opinionated list of awesome Python frameworks, libraries, tools, software and resources.

> The **#10 most-starred repo on GitHub**. Put your product where Python developers discover tools. [Become a sponsor](https://github.com/vinta/awesome-python/blob/master/README.md/SPONSORSHIP.md).

# Categories

**AI & ML**

*   [AI and Agents](#ai-and-agents)
*   [Deep Learning](#deep-learning)
*   [Machine Learning](#machine-learning)
*   [Natural Language Processing](#natural-language-processing)
*   [Computer Vision](#computer-vision)
*   [Recommender Systems](#recommender-systems)

**Web**

*   [Web Frameworks](#web-frameworks)
*   [Web APIs](#web-apis)
*   [Web Servers](#web-servers)
*   [WebSocket](#websocket)
*   [Template Engines](#template-engines)
*   [Web Asset Management](#web-asset-management)
*   [Authentication](#authentication)
*   [Admin Panels](#admin-panels)
*   [CMS](#cms)
*   [Static Site Generators](#static-site-generators)

**HTTP & Scraping**

*   [HTTP Clients](#http-clients)
*   [Web Scraping](#web-scraping)
*   [URL Manipulation](#url-manipulation)
*   [Email](#email)

**Database & Storage**

*   [ORM](#orm)
*   [Database Drivers](#database-drivers)
*   [Database](#database)
*   [Caching](#caching)
*   [Search](#search)
*   [Serialization](#serialization)

**Data & Science**

*   [Data Analysis](#data-analysis)
*   [Data Validation](#data-validation)
*   [Data Visualization](#data-visualization)
*   [Geolocation](#geolocation)
*   [Science](#science)
*   [Quantum Computing](#quantum-computing)

**Developer Tools**

*   [Algorithms and Design Patterns](#algorithms-and-design-patterns)
*   [Interactive Interpreter](#interactive-interpreter)
*   [Code Analysis](#code-analysis)
*   [Testing](#testing)
*   [Debugging Tools](#debugging-tools)
*   [Build Tools](#build-tools)
*   [Documentation](#documentation)
*   [Editor Plugins and IDEs](#editor-plugins-and-ides)

**DevOps**

*   [DevOps Tools](#devops-tools)
*   [Distributed Computing](#distributed-computing)
*   [Task Queues](#task-queues)
*   [Job Schedulers](#job-schedulers)
*   [Logging](#logging)
*   [Processes](#processes)
*   [Network Virtualization](#network-virtualization)
*   [RPC Servers](#rpc-servers)

**CLI & GUI**

*   [Command-line Interface Development](#command-line-interface-development)
*   [Command-line Tools](#command-line-tools)
*   [GUI Development](#gui-development)

**Text & Documents**

*   [Text Processing](#text-processing)
*   [HTML Manipulation](#html-manipulation)
*   [File Format Processing](#file-format-processing)
*   [File Manipulation](#file-manipulation)

**Media**

*   [Image Processing](#image-processing)
*   [Audio Processing](#audio-processing)
*   [Video Processing](#video-processing)
*   [Game Development](#game-development)

**Python Language**

*   [Implementations](#implementations)
*   [Built-in Classes Enhancement](#built-in-classes-enhancement)
*   [Functional Programming](#functional-programming)
*   [Asynchronous Programming](#asynchronous-programming)
*   [Date and Time](#date-and-time)

**Python Toolchain**

*   [Environment Management](#environment-management)
*   [Package Management](#package-management)
*   [Package Repositories](#package-repositories)
*   [Distribution](#distribution)
*   [Configuration Files](#configuration-files)

**Security**

*   [Cryptography](#cryptography)
*   [Penetration Testing](#penetration-testing)

**Miscellaneous**

*   [Hardware](#hardware)
*   [Microsoft Windows](#microsoft-windows)
*   [Miscellaneous](#miscellaneous)

***

**AI & ML**

## AI and Agents

*Libraries for building AI applications, LLM integrations, and autonomous agents.*

*   Frameworks
    *   [autogen (⭐56k)](https://github.com/microsoft/autogen) - A programming framework for building agentic AI applications.
    *   [crewai (⭐46k)](https://github.com/crewAIInc/crewAI) - A framework for orchestrating role-playing autonomous AI agents for collaborative task solving.
    *   [dspy (⭐33k)](https://github.com/stanfordnlp/dspy) - A framework for programming, not prompting, language models.
    *   [instructor (⭐13k)](https://github.com/567-labs/instructor) - A library for extracting structured data from LLMs, powered by Pydantic.
    *   [langchain (⭐130k)](https://github.com/langchain-ai/langchain) - Building applications with LLMs through composability.
    *   [llama\_index (⭐48k)](https://github.com/run-llama/llama_index) - A data framework for your LLM application.
    *   [pydantic-ai (⭐15k)](https://github.com/pydantic/pydantic-ai) - A Python agent framework for building generative AI applications with structured schemas.
*   Pretrained Models and Inference
    *   [diffusers (⭐33k)](https://github.com/huggingface/diffusers) - A library that provides pretrained diffusion models for generating and editing images, audio, and video.
    *   [transformers (⭐158k)](https://github.com/huggingface/transformers) - A framework that lets you easily use pretrained transformer models for NLP, vision, and audio tasks.
    *   [vllm (⭐73k)](https://github.com/vllm-project/vllm) - A high-throughput and memory-efficient inference and serving engine for LLMs.

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning (⭐28k)](https://github.com/ChristosChristofidis/awesome-deep-learning).*

*   [jax (⭐35k)](https://github.com/google/jax) - a library for high-performance numerical computing with automatic differentiation and JIT compilation.
*   [keras (⭐64k)](https://github.com/keras-team/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano.
*   [pytorch-lightning (⭐31k)](https://github.com/Lightning-AI/pytorch-lightning) - Deep learning framework to train, deploy, and ship AI products Lightning fast.
*   [pytorch (⭐98k)](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
*   [stable-baselines3 (⭐13k)](https://github.com/DLR-RM/stable-baselines3) - PyTorch implementations of Stable Baselines (deep) reinforcement learning algorithms.
*   [tensorflow (⭐194k)](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.

## Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning (⭐72k)](https://github.com/josephmisiti/awesome-machine-learning#python).*

*   [catboost (⭐8.8k)](https://github.com/catboost/catboost) - A fast, scalable, high performance gradient boosting on decision trees library.
*   [feature\_engine (⭐2.2k)](https://github.com/feature-engine/feature_engine) - sklearn compatible API with the widest toolset for feature engineering and selection.
*   [karateclub (⭐2.3k)](https://github.com/benedekrozemberczki/karateclub) - Unsupervised machine learning toolbox for graph structured data.
*   [h2o (⭐7.5k)](https://github.com/h2oai/h2o-3) - Open Source Fast Scalable Machine Learning Platform.
*   [lightgbm (⭐18k)](https://github.com/microsoft/LightGBM) - A fast, distributed, high performance gradient boosting framework.
*   [mindsdb (⭐39k)](https://github.com/mindsdb/mindsdb) - MindsDB is an open source AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries.
*   [pgmpy (⭐3.2k)](https://github.com/pgmpy/pgmpy) - A Python library for probabilistic graphical models and Bayesian networks.
*   [scikit-learn (⭐65k)](https://github.com/scikit-learn/scikit-learn) - The most popular Python library for Machine Learning with extensive documentation and community support.
*   [spark.ml](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library for distributed computing.
*   [xgboost (⭐28k)](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library.

## Natural Language Processing

*Libraries for working with human languages.*

*   General
    *   [gensim (⭐16k)](https://github.com/RaRe-Technologies/gensim) - Topic Modeling for Humans.
    *   [langid.py (⭐2.5k)](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
    *   [nltk (⭐15k)](https://github.com/nltk/nltk) - A leading platform for building Python programs to work with human language data.
    *   [pattern (⭐8.9k)](https://github.com/clips/pattern) - A web mining module.
    *   [polyglot (⭐2.4k)](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages.
    *   [spacy (⭐33k)](https://github.com/explosion/spaCy) - A library for industrial-strength natural language processing in Python and Cython.
    *   [stanza (⭐7.7k)](https://github.com/stanfordnlp/stanza) - The Stanford NLP Group's official Python library, supporting 60+ languages.
*   Chinese
    *   [funnlp (⭐79k)](https://github.com/fighting41love/funNLP) - A collection of tools and datasets for Chinese NLP.
    *   [jieba (⭐35k)](https://github.com/fxsjy/jieba) - The most popular Chinese text segmentation library.
    *   [pkuseg-python (⭐6.7k)](https://github.com/lancopku/pkuseg-python) - A toolkit for Chinese word segmentation in various domains.
    *   [snownlp (⭐6.6k)](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.

## Computer Vision

*Libraries for Computer Vision.*

*   [easyocr (⭐29k)](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 40+ languages supported.
*   [kornia (⭐11k)](https://github.com/kornia/kornia/) - Open Source Differentiable Computer Vision Library for PyTorch.
*   [opencv (⭐5.2k)](https://github.com/opencv/opencv-python) - Open Source Computer Vision Library.
*   [pytesseract (⭐6.3k)](https://github.com/madmaze/pytesseract) - A wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
*   [tesserocr (⭐2.2k)](https://github.com/sirfz/tesserocr) - Another simple, Pillow-friendly, wrapper around the `tesseract-ocr` API for OCR.

## Recommender Systems

*Libraries for building recommender systems.*

*   [annoy (⭐14k)](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
*   [implicit (⭐3.8k)](https://github.com/benfred/implicit) - A fast Python implementation of collaborative filtering for implicit datasets.
*   [lightfm (⭐5.1k)](https://github.com/lyst/lightfm) - A Python implementation of a number of popular recommendation algorithms.
*   [scikit-surprise (⭐6.8k)](https://github.com/NicolasHug/Surprise) - A scikit for building and analyzing recommender systems.
*   [spotlight (⭐3k)](https://github.com/maciejkula/spotlight) - Deep recommender models using PyTorch.

**Web**

## Web Frameworks

*Traditional full stack web frameworks. Also see [Web APIs](#web-apis).*

*   Synchronous
    *   [django (⭐87k)](https://github.com/django/django) - The most popular web framework in Python.
        *   [awesome-django (⭐1.9k)](https://github.com/shahraizali/awesome-django)
    *   [flask (⭐71k)](https://github.com/pallets/flask) - A microframework for Python.
        *   [awesome-flask (⭐13k)](https://github.com/humiaozuzu/awesome-flask)
    *   [pyramid (⭐4.1k)](https://github.com/Pylons/pyramid) - A small, fast, down-to-earth, open source Python web framework.
        *   [awesome-pyramid (⭐570)](https://github.com/uralbash/awesome-pyramid)
    *   [fasthtml (⭐6.9k)](https://github.com/AnswerDotAI/fasthtml) - The fastest way to create an HTML app.
        *   [awesome-fasthtml (⭐79)](https://github.com/amosgyamfi/awesome-fasthtml)
    *   [masonite (⭐2.4k)](https://github.com/MasoniteFramework/masonite) - The modern and developer centric Python web framework.
*   Asynchronous
    *   [litestar (⭐8.1k)](https://github.com/litestar-org/litestar) - Production-ready, capable and extensible ASGI Web framework.
    *   [microdot (⭐2.1k)](https://github.com/miguelgrinberg/microdot) - The impossibly small web framework for Python and MicroPython.
    *   [reflex (⭐28k)](https://github.com/reflex-dev/reflex) – A framework for building reactive, full-stack web applications entirely with python .
    *   [tornado (⭐22k)](https://github.com/tornadoweb/tornado) - A web framework and asynchronous networking library.

## Web APIs

*Libraries for building RESTful and GraphQL APIs.*

*   Django
    *   [django-rest-framework (⭐30k)](https://github.com/encode/django-rest-framework) - A powerful and flexible toolkit to build web APIs.
    *   [django-tastypie (⭐4k)](https://github.com/django-tastypie/django-tastypie) - Creating delicious APIs for Django apps.
    *   [strawberry-django (⭐488)](https://github.com/strawberry-graphql/strawberry-django) - Strawberry GraphQL integration with Django.
*   Flask
    *   [eve (⭐6.7k)](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions.
    *   [flask-api (⭐1.5k)](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask.
    *   [flask-restful (⭐6.9k)](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
*   Pyramid
    *   [cornice (⭐390)](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid.
*   Framework Agnostic
    *   [falcon (⭐9.8k)](https://github.com/falconry/falcon) - A high-performance framework for building cloud APIs and web app backends.
    *   [fastapi (⭐96k)](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs with Python 3.6+ based on standard Python type hints.
    *   [graphene (⭐8.3k)](https://github.com/graphql-python/graphene/) - GraphQL framework for Python.
    *   [hug (⭐6.9k)](https://github.com/hugapi/hug) - A Python 3 framework for cleanly exposing APIs.
    *   [sandman2 (⭐2k)](https://github.com/jeffknupp/sandman2) - Automated REST APIs for existing database-driven systems.
    *   [sanic (⭐19k)](https://github.com/sanic-org/sanic) - A Python 3.6+ web server and web framework that's written to go fast.
    *   [webargs (⭐1.4k)](https://github.com/marshmallow-code/webargs) - A friendly library for parsing HTTP request arguments with built-in support for popular web frameworks.

## Web Servers

*ASGI and WSGI compatible web servers.*

*   ASGI
    *   [daphne (⭐2.7k)](https://github.com/django/daphne) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP.
    *   [granian (⭐5.2k)](https://github.com/emmett-framework/granian) - A Rust HTTP server for Python applications built on top of Hyper and Tokio, supporting WSGI/ASGI/RSGI.
    *   [hypercorn (⭐1.5k)](https://github.com/pgjones/hypercorn) - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.
    *   [uvicorn (⭐10k)](https://github.com/encode/uvicorn) - A lightning-fast ASGI server implementation, using uvloop and httptools.
*   WSGI
    *   [gunicorn (⭐10k)](https://github.com/benoitc/gunicorn) - Pre-forked, ported from Ruby's Unicorn project.
    *   [uwsgi (⭐3.5k)](https://github.com/unbit/uwsgi) - A project aims at developing a full stack for building hosting services, written in C.
    *   [waitress (⭐1.6k)](https://github.com/Pylons/waitress) - Multi-threaded, powers Pyramid.
    *   [werkzeug (⭐6.8k)](https://github.com/pallets/werkzeug) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## WebSocket

*Libraries for working with WebSocket.*

*   [autobahn-python (⭐2.5k)](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
*   [channels (⭐6.3k)](https://github.com/django/channels) - Developer-friendly asynchrony for Django.
*   [websockets (⭐5.6k)](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients with a focus on correctness and simplicity.

## Template Engines

*Libraries and tools for templating and lexing.*

*   [genshi (⭐97)](https://github.com/edgewall/genshi) - Python templating toolkit for generation of web-aware output.
*   [jinja (⭐12k)](https://github.com/pallets/jinja) - A modern and designer friendly templating language.
*   [mako (⭐430)](https://github.com/sqlalchemy/mako) - Hyperfast and lightweight templating for the Python platform.

## Web Asset Management

*Tools for managing, compressing and minifying website assets.*

*   [django-compressor (⭐2.9k)](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file.
*   [django-pipeline (⭐1.5k)](https://github.com/jazzband/django-pipeline) - An asset packaging library for Django.
*   [django-storages (⭐2.9k)](https://github.com/jschneier/django-storages) - A collection of custom storage back ends for Django.
*   [fanstatic (⭐13)](https://github.com/zopefoundation/fanstatic) - Packages, optimizes, and serves static file dependencies as Python packages.
*   [flask-assets (⭐459)](https://github.com/miracle2k/flask-assets) - Helps you integrate webassets into your Flask app.
*   [webassets (⭐935)](https://github.com/miracle2k/webassets) - Bundles, optimizes, and manages unique cache-busting URLs for static resources.

## Authentication

*Libraries for implementing authentication schemes.*

*   OAuth
    *   [authlib (⭐5.2k)](https://github.com/lepture/authlib) - JavaScript Object Signing and Encryption draft implementation.
    *   [django-allauth (⭐10k)](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works."
    *   [django-oauth-toolkit (⭐3.3k)](https://github.com/jazzband/django-oauth-toolkit) - OAuth 2 goodies for Django.
    *   [oauthlib (⭐3k)](https://github.com/oauthlib/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic.
*   JWT
    *   [pyjwt (⭐5.6k)](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.
    *   [python-jose (⭐1.7k)](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python.
*   Permissions
    *   [django-guardian (⭐3.9k)](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions for Django 1.2+
    *   [django-rules (⭐2k)](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

## Admin Panels

*Libraries for administrative interfaces.*

*   [ajenti (⭐7.9k)](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
*   [django-grappelli (⭐3.9k)](https://github.com/sehmaschine/django-grappelli) - A jazzy skin for the Django Admin-Interface.
*   [django-unfold (⭐3.4k)](https://github.com/unfoldadmin/django-unfold) - Elevate your Django admin with a stunning modern interface, powerful features, and seamless user experience.
*   [flask-admin (⭐6.1k)](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask.
*   [func-to-web (⭐386)](https://github.com/offerrall/FuncToWeb) - Instantly create web UIs from Python functions using type hints. Zero frontend code required.
*   [jet-bridge (⭐1.8k)](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django).
*   [wooey (⭐2.2k)](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.

## CMS

*Content Management Systems.*

*   [django-cms (⭐11k)](https://github.com/django-cms/django-cms) - The easy-to-use and developer-friendly enterprise CMS powered by Django.
*   [feincms (⭐1.1k)](https://github.com/feincms/feincms) - One of the most advanced Content Management Systems built on Django.
*   [indico (⭐2k)](https://github.com/indico/indico) - A feature-rich event management system, made @ [CERN](https://en.wikipedia.org/wiki/CERN).
*   [wagtail (⭐20k)](https://github.com/wagtail/wagtail) - A Django content management system.

## Static Site Generators

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

*   [lektor (⭐3.9k)](https://github.com/lektor/lektor) - An easy to use static CMS and blog engine.
*   [makesite (⭐1.9k)](https://github.com/sunainapai/makesite) - Simple, lightweight, and magic-free static site/blog generator (< 130 lines).
*   [nikola (⭐2.7k)](https://github.com/getnikola/nikola) - A static website and blog generator.
*   [pelican (⭐13k)](https://github.com/getpelican/pelican) - Static site generator that supports Markdown and reST syntax.

**HTTP & Scraping**

## HTTP Clients

*Libraries for working with HTTP.*

*   [aiohttp (⭐16k)](https://github.com/aio-libs/aiohttp) - Asynchronous HTTP client/server framework for asyncio and Python.
*   [httpx (⭐15k)](https://github.com/encode/httpx) - A next generation HTTP client for Python.
*   [requests (⭐54k)](https://github.com/psf/requests) - HTTP Requests for Humans.
*   [treq (⭐606)](https://github.com/twisted/treq) - Python requests like API built on top of Twisted's HTTP client.
*   [urllib3 (⭐4k)](https://github.com/urllib3/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly.

## Web Scraping

*Libraries to automate web scraping and extract web content.*

*   [browser-use (⭐81k)](https://github.com/browser-use/browser-use) - Make websites accessible for AI agents with easy browser automation.
*   [crawl4ai (⭐62k)](https://github.com/unclecode/crawl4ai) - An open-source, LLM-friendly web crawler that provides lightning-fast, structured data extraction specifically designed for AI agents.
*   [feedparser (⭐2.3k)](https://github.com/kurtmckee/feedparser) - Universal feed parser.
*   [grab (⭐2.5k)](https://github.com/lorien/grab) - Site scraping framework.
*   [html2text (⭐2.1k)](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.
*   [lassie (⭐630)](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans.
*   [mechanicalsoup (⭐4.9k)](https://github.com/MechanicalSoup/MechanicalSoup) - A Python library for automating interaction with websites.
*   [micawber (⭐674)](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs.
*   [newspaper (⭐15k)](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python.
*   [python-readability (⭐2.9k)](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool.
*   [requests-html (⭐14k)](https://github.com/psf/requests-html) - Pythonic HTML Parsing for Humans.
*   [scrapy (⭐61k)](https://github.com/scrapy/scrapy) - A fast high-level screen scraping and web crawling framework.
*   [sumy (⭐3.7k)](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages.
*   [toapi (⭐3.6k)](https://github.com/gaojiuli/toapi) - Every web site provides APIs.

## URL Manipulation

*Libraries for parsing URLs.*

*   [furl (⭐2.8k)](https://github.com/gruns/furl) - A small Python library that makes parsing and manipulating URLs easy.
*   [purl (⭐303)](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation.

## Email

*Libraries for sending and parsing email.*

*   [flanker (⭐1.6k)](https://github.com/mailgun/flanker) - An email address and Mime parsing library.
*   [imbox (⭐1.2k)](https://github.com/martinrusev/imbox) - Python IMAP for Humans.
*   [mailer (⭐294)](https://github.com/marrow/mailer) - High-performance extensible mail delivery framework.
*   [modoboa (⭐3.5k)](https://github.com/modoboa/modoboa) - A mail hosting and management platform including a modern Web UI.
*   [yagmail (⭐2.7k)](https://github.com/kootenpv/yagmail) - Yet another Gmail/SMTP client.

**Database & Storage**

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

*   Relational Databases
    *   [django.db.models](https://docs.djangoproject.com/en/dev/topics/db/models/) - The Django ORM.
    *   [sqlalchemy (⭐12k)](https://github.com/sqlalchemy/sqlalchemy) - The Python SQL Toolkit and Object Relational Mapper.
        *   [awesome-sqlalchemy (⭐3k)](https://github.com/dahlia/awesome-sqlalchemy)
    *   [dataset (⭐4.9k)](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL.
    *   [peewee (⭐12k)](https://github.com/coleifer/peewee) - A small, expressive ORM.
    *   [pony (⭐3.8k)](https://github.com/ponyorm/pony/) - ORM that provides a generator-oriented interface to SQL.
    *   [sqlmodel (⭐18k)](https://github.com/fastapi/sqlmodel) - SQLModel is based on Python type annotations, and powered by Pydantic and SQLAlchemy.
    *   [tortoise-orm (⭐5.5k)](https://github.com/tortoise/tortoise-orm) - An easy-to-use asyncio ORM inspired by Django, with relations support.
*   NoSQL Databases
    *   [beanie (⭐2.7k)](https://github.com/BeanieODM/beanie) - An asynchronous Python object-document mapper (ODM) for MongoDB.
    *   [mongoengine (⭐4.3k)](https://github.com/MongoEngine/mongoengine) - A Python Object-Document-Mapper for working with MongoDB.
    *   [odmantic (⭐1.2k)](https://github.com/art049/odmantic) - Sync and Async ODM for MongoDB built on top of Pydantic for model definition and validation.
    *   [pynamodb (⭐2.6k)](https://github.com/pynamodb/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).

## Database Drivers

*Libraries for connecting and operating databases.*

*   MySQL - [awesome-mysql (⭐2.6k)](https://github.com/shlomi-noach/awesome-mysql)
    *   [mysqlclient (⭐2.5k)](https://github.com/PyMySQL/mysqlclient) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork).
    *   [pymysql (⭐7.8k)](https://github.com/PyMySQL/PyMySQL) - A pure Python MySQL driver compatible to mysql-python.
*   PostgreSQL - [awesome-postgres (⭐12k)](https://github.com/dhamaniasad/awesome-postgres)
    *   [psycopg (⭐2.3k)](https://github.com/psycopg/psycopg) - The most popular PostgreSQL adapter for Python.
*   SQlite - [awesome-sqlite (⭐388)](https://github.com/planetopendata/awesome-sqlite)
    *   [sqlite-utils (⭐2k)](https://github.com/simonw/sqlite-utils) - Python CLI utility and library for manipulating SQLite databases.
    *   [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQlite interface compliant with DB-API 2.0.
*   Other Relational Databases
    *   [clickhouse-driver (⭐1.3k)](https://github.com/mymarilyn/clickhouse-driver) - Python driver with native interface for ClickHouse.
    *   [pymssql (⭐881)](https://github.com/pymssql/pymssql) - A simple database interface to Microsoft SQL Server.
*   NoSQL Databases
    *   [cassandra-driver (⭐1.4k)](https://github.com/datastax/python-driver) - The Python Driver for Apache Cassandra.
    *   [django-mongodb-backend (⭐218)](https://github.com/mongodb/django-mongodb-backend) - Official MongoDB database backend for Django.
    *   [pymongo (⭐4.3k)](https://github.com/mongodb/mongo-python-driver) - The official Python client for MongoDB.
    *   [redis-py (⭐14k)](https://github.com/redis/redis-py) - The Python client for Redis.

## Database

*Databases implemented in Python.*

*   [chromadb (⭐27k)](https://github.com/chroma-core/chroma) - An open-source embedding database for building AI applications with embeddings and semantic search.
*   [duckdb (⭐37k)](https://github.com/duckdb/duckdb) - An in-process SQL OLAP database management system; optimized for analytics and fast queries, similar to SQLite but for analytical workloads.
*   [pickledb (⭐1.1k)](https://github.com/patx/pickledb) - A simple and lightweight key-value store for Python.
*   [tinydb (⭐7.5k)](https://github.com/msiemens/tinydb) - A tiny, document-oriented database.
*   [ZODB (⭐750)](https://github.com/zopefoundation/ZODB) - A native object database for Python. A key-value and object graph database.

## Caching

*Libraries for caching data.*

*   [beaker (⭐545)](https://github.com/bbangert/beaker) - A WSGI middleware for sessions and caching.
*   [django-cache-machine (⭐885)](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models.
*   [django-cacheops (⭐2.3k)](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
*   [dogpile.cache (⭐291)](https://github.com/sqlalchemy/dogpile.cache) - dogpile.cache is a next generation replacement for Beaker made by the same authors.
*   [hermescache](https://pypi.org/project/HermesCache/) - Python caching library with tag-based invalidation and dogpile effect prevention.
*   [pylibmc (⭐493)](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](https://libmemcached.org/libMemcached.html) interface.
*   [python-diskcache (⭐2.8k)](https://github.com/grantjenks/python-diskcache) - SQLite and file backed cache backend with faster lookups than memcached and redis.

## Search

*Libraries and software for indexing and performing search queries on data.*

*   [django-haystack (⭐3.8k)](https://github.com/django-haystack/django-haystack) - Modular search for Django.
*   [elasticsearch-dsl-py (⭐3.9k)](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
*   [elasticsearch-py (⭐4.4k)](https://github.com/elastic/elasticsearch-py) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
*   [pysolr (⭐697)](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for [Apache Solr](https://lucene.apache.org/solr/).
*   [whoosh (⭐657)](https://github.com/mchaput/whoosh) - A fast, pure Python search engine library.

## Serialization

*Libraries for serializing complex data types.*

*   [marshmallow (⭐7.2k)](https://github.com/marshmallow-code/marshmallow) - A lightweight library for converting complex objects to and from simple Python datatypes.
*   [msgpack (⭐2.1k)](https://github.com/msgpack/msgpack-python) - MessagePack serializer implementation for Python.
*   [orjson (⭐8k)](https://github.com/ijl/orjson) - Fast, correct JSON library.
*   [pysimdjson (⭐761)](https://github.com/TkTech/pysimdjson) - A Python bindings for [simdjson (⭐23k)](https://github.com/lemire/simdjson).
*   [python-rapidjson (⭐532)](https://github.com/python-rapidjson/python-rapidjson) - A Python wrapper around [RapidJSON (⭐15k)](https://github.com/Tencent/rapidjson).
*   [ultrajson (⭐4.5k)](https://github.com/esnme/ultrajson) - A fast JSON decoder and encoder written in C with Python bindings.

**Data & Science**

## Data Analysis

*Libraries for data analysis.*

*   [aws-sdk-pandas (⭐4.1k)](https://github.com/aws/aws-sdk-pandas) - Pandas on AWS.
*   [datasette (⭐11k)](https://github.com/simonw/datasette) - An open source multi-tool for exploring and publishing data.
*   [desbordante (⭐469)](https://github.com/desbordante/desbordante-core/) - An open source data profiler for complex pattern discovery.
*   [optimus (⭐1.5k)](https://github.com/hi-primus/optimus) - Agile Data Science Workflows made easy with PySpark.
*   [pandas (⭐48k)](https://github.com/pandas-dev/pandas) - A library providing high-performance, easy-to-use data structures and data analysis tools.
*   [pathway (⭐60k)](https://github.com/pathwaycom/pathway) - Real-time data processing framework for Python with reactive dataflows.
*   [akshare (⭐17k)](https://github.com/jindaxiang/akshare) - A financial data interface library, built for human beings!
*   [edgartools (⭐1.8k)](https://github.com/dgunning/edgartools) - Library for downloading structured data from SEC EDGAR filings and XBRL financial statements.
*   [openbb (⭐63k)](https://github.com/OpenBB-finance/OpenBB) - A financial data platform for analysts, quants and AI agents.
*   [polars (⭐38k)](https://github.com/pola-rs/polars) - A fast DataFrame library implemented in Rust with a Python API.
*   [yfinance (⭐22k)](https://github.com/ranaroussi/yfinance) - Easy Pythonic way to download market and financial data from Yahoo Finance.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

*   [cerberus (⭐3.3k)](https://github.com/pyeve/cerberus) - A lightweight and extensible data validation library.
*   [colander (⭐464)](https://github.com/Pylons/colander) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
*   [jsonschema (⭐4.9k)](https://github.com/python-jsonschema/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python.
*   [pydantic (⭐27k)](https://github.com/pydantic/pydantic) - Data validation using Python type hints.
*   [schema (⭐2.9k)](https://github.com/keleshev/schema) - A library for validating Python data structures.
*   [schematics (⭐2.6k)](https://github.com/schematics/schematics) - Data Structure Validation.
*   [voluptuous (⭐1.8k)](https://github.com/alecthomas/voluptuous) - A Python data validation library.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript (⭐35k)](https://github.com/sorrycc/awesome-javascript#data-visualization).*

*   Plotting
    *   [altair (⭐10k)](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python.
    *   [bokeh (⭐20k)](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
    *   [bqplot (⭐3.7k)](https://github.com/bloomberg/bqplot) - Interactive Plotting Library for the Jupyter Notebook.
    *   [matplotlib (⭐23k)](https://github.com/matplotlib/matplotlib) - A Python 2D plotting library.
    *   [plotly (⭐18k)](https://github.com/plotly/plotly.py) - Interactive graphing library for Python.
    *   [plotnine (⭐4.5k)](https://github.com/has2k1/plotnine) - A grammar of graphics for Python based on ggplot2.
    *   [pygal (⭐2.8k)](https://github.com/Kozea/pygal) - A Python SVG Charts Creator.
    *   [pyqtgraph (⭐4.3k)](https://github.com/pyqtgraph/pyqtgraph) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
    *   [seaborn (⭐14k)](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.
    *   [ultraplot (⭐278)](https://github.com/ultraplot/UltraPlot) - Matplotlib wrapper for publication-ready scientific figures with minimal code. Includes advanced subplot management, panel layouts, and batteries-included geoscience plotting.
    *   [vispy (⭐3.6k)](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL.
*   Specialized
    *   [cartopy (⭐1.6k)](https://github.com/SciTools/cartopy) - A cartographic python library with matplotlib support.
    *   [pygraphviz (⭐834)](https://github.com/pygraphviz/pygraphviz/) - Python interface to [Graphviz](http://www.graphviz.org/).
*   Dashboards and Apps
    *   [gradio (⭐42k)](https://github.com/gradio-app/gradio) - Build and share machine learning apps, all in Python.
    *   [streamlit (⭐44k)](https://github.com/streamlit/streamlit) - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

*   [django-countries (⭐1.5k)](https://github.com/SmileyChris/django-countries) - A Django app that provides a country field for models and forms.
*   [geodjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
*   [geojson (⭐984)](https://github.com/jazzband/geojson) - Python bindings and utilities for GeoJSON.
*   [geopandas (⭐5.1k)](https://github.com/geopandas/geopandas) - Python tools for geographic data (GeoSeries/GeoDataFrame) built on pandas.
*   [geopy (⭐4.8k)](https://github.com/geopy/geopy) - Python Geocoding Toolbox.

## Science

*Libraries for scientific computing. Also see [Python-for-Scientists (⭐356)](https://github.com/TomNicholas/Python-for-Scientists).*

*   Core
    *   [numba (⭐11k)](https://github.com/numba/numba) - Python JIT compiler to LLVM aimed at scientific Python.
    *   [numpy (⭐32k)](https://github.com/numpy/numpy) - A fundamental package for scientific computing with Python.
    *   [scipy (⭐15k)](https://github.com/scipy/scipy) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
    *   [statsmodels (⭐11k)](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
    *   [sympy (⭐14k)](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
*   Biology and Chemistry
    *   [biopython (⭐4.9k)](https://github.com/biopython/biopython) - Biopython is a set of freely available tools for biological computation.
    *   [cclib (⭐396)](https://github.com/cclib/cclib) - A library for parsing and interpreting the results of computational chemistry packages.
    *   [openbabel (⭐1.3k)](https://github.com/openbabel/openbabel) - A chemical toolbox designed to speak the many languages of chemical data.
    *   [rdkit (⭐3.3k)](https://github.com/rdkit/rdkit) - Cheminformatics and Machine Learning Software.
*   Physics and Engineering
    *   [astropy (⭐5.1k)](https://github.com/astropy/astropy) - A community Python library for Astronomy.
    *   [obspy (⭐1.3k)](https://github.com/obspy/obspy) - A Python toolbox for seismology.
    *   [pydy (⭐409)](https://github.com/pydy/pydy) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
    *   [PythonRobotics (⭐29k)](https://github.com/AtsushiSakai/PythonRobotics) - This is a compilation of various robotics algorithms with visualizations.
*   Simulation and Modeling
    *   [pathsim (⭐334)](https://github.com/pathsim/pathsim) - A block-based system modeling and simulation framework with a browser-based visual editor.
    *   [pymc (⭐9.5k)](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit.
    *   [simpy](https://gitlab.com/team-simpy/simpy) - A process-based discrete-event simulation framework.
*   Other
    *   [colour (⭐2.5k)](https://github.com/colour-science/colour) - Implementing a comprehensive number of colour theory transformations and algorithms.
    *   [manim (⭐37k)](https://github.com/ManimCommunity/manim) - An animation engine for explanatory math videos.
    *   [networkx (⭐17k)](https://github.com/networkx/networkx) - A high-productivity software for complex networks.
    *   [shapely (⭐4.4k)](https://github.com/shapely/shapely) - Manipulation and analysis of geometric objects in the Cartesian plane.

## Quantum Computing

*Libraries for quantum computing.*

*   [Cirq (⭐4.9k)](https://github.com/quantumlib/Cirq) — A Google-developed framework focused on hardware-aware quantum circuit design for NISQ devices.
*   [pennylane (⭐3.1k)](https://github.com/PennyLaneAI/pennylane) — A hybrid quantum-classical machine learning library with automatic differentiation support.
*   [qiskit (⭐7.1k)](https://github.com/Qiskit/qiskit) — An IBM-backed quantum SDK for building, simulating, and running circuits on real quantum hardware.
*   [qutip (⭐2k)](https://github.com/qutip/qutip) - Quantum Toolbox in Python.

**Developer Tools**

## Algorithms and Design Patterns

*Python implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms (⭐25k)](https://github.com/tayllan/awesome-algorithms).*

*   Algorithms
    *   [algorithms (⭐25k)](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms.
    *   [python-ds (⭐3.1k)](https://github.com/prabhupant/python-ds) - A collection of data structure and algorithms for coding interviews.
    *   [sortedcontainers (⭐3.9k)](https://github.com/grantjenks/python-sortedcontainers) - Fast and pure-Python implementation of sorted collections.
    *   [thealgorithms (⭐219k)](https://github.com/TheAlgorithms/Python) - All Algorithms implemented in Python.
*   Design Patterns
    *   [python-cqrs (⭐44)](https://github.com/vadikko2/python-cqrs) - Event-Driven Architecture Framework with CQRS/CQS, Transaction Outbox, Saga orchestration.
    *   [python-patterns (⭐43k)](https://github.com/faif/python-patterns) - A collection of design patterns in Python.
    *   [transitions (⭐6.5k)](https://github.com/pytransitions/transitions) - A lightweight, object-oriented finite state machine implementation.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

*   [bpython (⭐2.8k)](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter.
*   [jupyter (⭐13k)](https://github.com/jupyter/notebook) - A rich toolkit to help you make the most out of using Python interactively.
    *   [awesome-jupyter (⭐4.6k)](https://github.com/markusschanta/awesome-jupyter)
*   [marimo (⭐20k)](https://github.com/marimo-team/marimo) - Transform data and train models, feels like a next-gen notebook, stored as Git-friendly Python.
*   [ptpython (⭐5.4k)](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit (⭐10k)](https://github.com/jonathanslenders/python-prompt-toolkit).

## Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis (⭐14k)](https://github.com/mre/awesome-static-analysis).*

*   Code Analysis
    *   [code2flow (⭐4.5k)](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    *   [prospector (⭐2.1k)](https://github.com/PyCQA/prospector) - A tool to analyze Python code.
    *   [vulture (⭐4.4k)](https://github.com/jendrikseipp/vulture) - A tool for finding and analyzing dead Python code.
*   Code Linters
    *   [bandit (⭐7.9k)](https://github.com/PyCQA/bandit) - A tool designed to find common security issues in Python code.
    *   [flake8 (⭐3.8k)](https://github.com/PyCQA/flake8) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
        *   [awesome-flake8-extensions (⭐1.3k)](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
    *   [pylint (⭐5.7k)](https://github.com/pylint-dev/pylint) - A fully customizable source code analyzer.
    *   [ruff (⭐46k)](https://github.com/astral-sh/ruff) - An extremely fast Python linter and code formatter.
*   Code Formatters
    *   [black (⭐41k)](https://github.com/psf/black) - The uncompromising Python code formatter.
    *   [isort (⭐6.9k)](https://github.com/timothycrosley/isort) - A Python utility / library to sort imports.
    *   [yapf (⭐14k)](https://github.com/google/yapf) - Yet another Python code formatter from Google.
*   Static Type Checkers, also see [awesome-python-typing (⭐2k)](https://github.com/typeddjango/awesome-python-typing)
    *   [mypy (⭐20k)](https://github.com/python/mypy) - Check variable types during compile time.
    *   [pyre-check (⭐7.2k)](https://github.com/facebook/pyre-check) - Performant type checking.
    *   [ty (⭐18k)](https://github.com/astral-sh/ty) - An extremely fast Python type checker and language server.
    *   [typeshed (⭐5k)](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types.
*   Refactoring
    *   [bowler (⭐1.6k)](https://github.com/facebookincubator/Bowler) - Safe code refactoring for modern Python.
    *   [rope (⭐2.2k)](https://github.com/python-rope/rope) - Rope is a python refactoring library.
*   Static Type Annotations Generators
    *   [monkeytype (⭐5k)](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types.
    *   [pytype (⭐5k)](https://github.com/google/pytype) - Pytype checks and infers types for Python code - without requiring type annotations.

## Testing

*Libraries for testing codebases and generating test data.*

*   Testing Frameworks
    *   [hypothesis (⭐8.5k)](https://github.com/HypothesisWorks/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library.
    *   [nose2 (⭐822)](https://github.com/nose-devs/nose2) - The successor to `nose`, based on `unittest2`.
    *   [pytest (⭐14k)](https://github.com/pytest-dev/pytest) - A mature full-featured Python testing tool.
    *   [robotframework (⭐11k)](https://github.com/robotframework/robotframework) - A generic test automation framework.
    *   [scanapi (⭐1.5k)](https://github.com/scanapi/scanapi) - Automated Testing and Documentation for your REST API.
    *   [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
*   Test Runners
    *   [green (⭐806)](https://github.com/CleanCut/green) - A clean, colorful test runner.
    *   [nox (⭐1.5k)](https://github.com/wntrblm/nox) - Flexible test automation for Python.
    *   [tox (⭐3.9k)](https://github.com/tox-dev/tox) - Auto builds and tests distributions in multiple Python versions
*   GUI / Web Testing
    *   [locust (⭐28k)](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
    *   [playwright (⭐14k)](https://github.com/microsoft/playwright-python) - Python version of the Playwright testing and automation library.
    *   [pyautogui (⭐12k)](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
    *   [schemathesis (⭐3.1k)](https://github.com/kiwicom/schemathesis) - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
    *   [selenium (⭐34k)](https://github.com/SeleniumHQ/selenium) - Python bindings for [Selenium](https://selenium.dev/) [WebDriver](https://selenium.dev/documentation/webdriver/).
    *   [splinter (⭐2.8k)](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
*   Mock
    *   [doublex](https://pypi.org/project/doublex/) - Powerful test doubles framework for Python.
    *   [freezegun (⭐4.5k)](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    *   [httmock (⭐472)](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
    *   [httpretty (⭐2.2k)](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
    *   [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    *   [mocket (⭐309)](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support.
    *   [responses (⭐4.3k)](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
    *   [vcrpy (⭐3k)](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
*   Object Factories
    *   [factory\_boy (⭐3.8k)](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python.
    *   [mixer (⭐954)](https://github.com/klen/mixer) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.
    *   [polyfactory (⭐1.4k)](https://github.com/litestar-org/polyfactory) - mock data generation library with support to classes (continuation of `pydantic-factories`)
*   Code Coverage
    *   [coverage (⭐3.3k)](https://github.com/coveragepy/coveragepy) - Code coverage measurement.
*   Fake Data
    *   [faker (⭐19k)](https://github.com/joke2k/faker) - A Python package that generates fake data.
    *   [mimesis (⭐4.8k)](https://github.com/lk-geimfari/mimesis) - is a Python library that help you generate fake data.

## Debugging Tools

*Libraries for debugging code.*

*   pdb-like Debugger
    *   [ipdb (⭐2k)](https://github.com/gotcha/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
    *   [pudb (⭐3.2k)](https://github.com/inducer/pudb) - A full-screen, console-based Python debugger.
*   Tracing
    *   [manhole (⭐400)](https://github.com/ionelmc/python-manhole) - Debugging UNIX socket connections and present the stacktraces for all threads and an interactive prompt.
    *   [python-hunter (⭐866)](https://github.com/ionelmc/python-hunter) - A flexible code tracing toolkit.
*   Profiler
    *   [py-spy (⭐15k)](https://github.com/benfred/py-spy) - A sampling profiler for Python programs. Written in Rust.
    *   [vprof (⭐4k)](https://github.com/nvdv/vprof) - Visual Python profiler.
*   Others
    *   [django-debug-toolbar (⭐8.4k)](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django.
    *   [flask-debugtoolbar (⭐981)](https://github.com/pallets-eco/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
    *   [icecream (⭐10k)](https://github.com/gruns/icecream) - Inspect variables, expressions, and program execution with a single, simple function call.
    *   [memory\_graph (⭐771)](https://github.com/bterwijn/memory_graph) - Visualize Python data at runtime to debug references, mutability, and aliasing.

## Build Tools

*Compile software from source code.*

*   [bitbake (⭐509)](https://github.com/openembedded/bitbake) - A make-like build tool for embedded Linux.
*   [buildout (⭐613)](https://github.com/buildout/buildout) - A build system for creating, assembling and deploying applications from multiple parts.
*   [invoke (⭐4.7k)](https://github.com/pyinvoke/invoke) - A tool for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
*   [platformio (⭐8.9k)](https://github.com/platformio/platformio-core) - A console tool to build code with different development platforms.
*   [pybuilder (⭐2k)](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python.
*   [doit (⭐2k)](https://github.com/pydoit/doit) - A task runner and build tool.
*   [scons (⭐2.4k)](https://github.com/SCons/scons) - A software construction tool.

## Documentation

*Libraries for generating project documentation.*

*   [sphinx (⭐7.7k)](https://github.com/sphinx-doc/sphinx/) - Python Documentation generator.
    *   [awesome-sphinxdoc (⭐973)](https://github.com/yoloseem/awesome-sphinxdoc)
*   [diagrams (⭐42k)](https://github.com/mingrammer/diagrams) - Diagram as Code.
*   [mkdocs (⭐22k)](https://github.com/mkdocs/mkdocs/) - Markdown friendly documentation generator.
*   [pdoc (⭐2.5k)](https://github.com/mitmproxy/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries.

## Editor Plugins and IDEs

*   [elpy (⭐1.9k)](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment.
*   [jedi-vim (⭐5.3k)](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python.
*   [PTVS (⭐2.6k)](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio.
*   [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
*   [Python for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - The official VSCode extension with rich support for Python.
*   [python-mode (⭐5.5k)](https://github.com/python-mode/python-mode) - An all in one plugin for turning Vim into a Python IDE.
*   [spyder (⭐9.2k)](https://github.com/spyder-ide/spyder) - Open Source Python IDE.
*   [YouCompleteMe (⭐26k)](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi (⭐6.1k)](https://github.com/davidhalter/jedi)-based completion engine for Python.

**DevOps**

## DevOps Tools

*Software and libraries for DevOps.*

*   Cloud Providers
    *   [boto3 (⭐9.7k)](https://github.com/boto/boto3) - Python interface to Amazon Web Services.
    *   [s3cmd (⭐4.9k)](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront.
*   Configuration Management
    *   [ansible (⭐68k)](https://github.com/ansible/ansible) - A radically simple IT automation platform.
    *   [cloudinit (⭐3.6k)](https://github.com/canonical/cloud-init) - A multi-distribution package that handles early initialization of a cloud instance.
    *   [openstack](https://www.openstack.org/) - Open source software for building private and public clouds.
    *   [pyinfra (⭐4.9k)](https://github.com/pyinfra-dev/pyinfra) - A versatile CLI tools and python libraries to automate infrastructure.
    *   [saltstack (⭐15k)](https://github.com/saltstack/salt) - Infrastructure automation and management system.
*   SSH-style Deployment
    *   [fabric (⭐15k)](https://github.com/fabric/fabric) - A simple, Pythonic tool for remote execution and deployment.
*   Process Management
    *   [supervisor (⭐9k)](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.
*   Monitoring
    *   [psutil (⭐11k)](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module.
    *   [sentry-python (⭐2.2k)](https://github.com/getsentry/sentry-python) - Sentry SDK for Python.
*   Git Hooks
    *   [pre-commit (⭐15k)](https://github.com/pre-commit/pre-commit) - A framework for managing and maintaining multi-language pre-commit hooks.
*   Backup
    *   [borg (⭐13k)](https://github.com/borgbackup/borg) - A deduplicating archiver with compression and encryption.
*   Serverless
    *   [python-lambda (⭐1.5k)](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying Python code in AWS Lambda.
    *   [zappa (⭐3.7k)](https://github.com/zappa/Zappa) - A tool for deploying WSGI applications on AWS Lambda and API Gateway.
*   Chaos Engineering
    *   [chaostoolkit (⭐2k)](https://github.com/chaostoolkit/chaostoolkit) - A Chaos Engineering toolkit & Orchestration for Developers.

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

*   Batch Processing
    *   [dask (⭐14k)](https://github.com/dask/dask) - A flexible parallel computing library for analytic computing.
    *   [luigi (⭐19k)](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs.
    *   [mpi4py (⭐902)](https://github.com/mpi4py/mpi4py) - Python bindings for MPI.
    *   [pyspark (⭐43k)](https://github.com/apache/spark) - [Apache Spark](https://spark.apache.org/) Python API.
    *   [joblib (⭐4.3k)](https://github.com/joblib/joblib) - A set of tools to provide lightweight pipelining in Python.
    *   [ray (⭐42k)](https://github.com/ray-project/ray/) - A system for parallel and distributed Python that unifies the machine learning ecosystem.
*   Stream Processing
    *   [kafka-python (⭐5.9k)](https://github.com/dpkp/kafka-python) - The Python client for Apache Kafka.
    *   [streamparse (⭐1.5k)](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data via [Apache Storm](http://storm.apache.org/).

## Task Queues

*Libraries for working with task queues.*

*   [celery (⭐28k)](https://github.com/celery/celery) - An asynchronous task queue/job queue based on distributed message passing.
    *   [flower (⭐7.1k)](https://github.com/mher/flower) - Real-time monitor and web admin for Celery.
*   [dramatiq (⭐5.2k)](https://github.com/Bogdanp/dramatiq) - A fast and reliable background task processing library for Python 3.
*   [huey (⭐5.9k)](https://github.com/coleifer/huey) - Little multi-threaded task queue.
*   [mrq (⭐896)](https://github.com/pricingassistant/mrq) - A distributed worker task queue in Python using Redis & gevent.
*   [rq (⭐11k)](https://github.com/rq/rq) - Simple job queues for Python.

## Job Schedulers

*Libraries for scheduling jobs.*

*   [airflow (⭐45k)](https://github.com/apache/airflow) - Airflow is a platform to programmatically author, schedule and monitor workflows.
*   [apscheduler (⭐7.4k)](https://github.com/agronholm/apscheduler) - A light but powerful in-process task scheduler that lets you schedule functions.
*   [dagster (⭐15k)](https://github.com/dagster-io/dagster) - An orchestration platform for the development, production, and observation of data assets.
*   [prefect (⭐22k)](https://github.com/PrefectHQ/prefect) - A modern workflow orchestration framework that makes it easy to build, schedule and monitor robust data pipelines.
*   [schedule (⭐12k)](https://github.com/dbader/schedule) - Python job scheduling for humans.
*   [SpiffWorkflow (⭐1.9k)](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python.
*   [taskflow](https://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## Logging

*Libraries for generating and working with logs.*

*   [logbook (⭐1.5k)](https://github.com/getlogbook/logbook) - Logging replacement for Python.
*   [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.
*   [loguru (⭐24k)](https://github.com/Delgan/loguru) - Library which aims to bring enjoyable logging in Python.
*   [structlog (⭐4.7k)](https://github.com/hynek/structlog) - Structured logging made easy.

## Processes

*Libraries for starting and communicating with OS processes.*

*   [delegator.py (⭐1.7k)](https://github.com/amitt001/delegator.py) - [Subprocesses](https://docs.python.org/3/library/subprocess.html) for Humans 2.0.
*   [sarge (⭐35)](https://github.com/vsajip/sarge) - Yet another wrapper for subprocess.
*   [sh (⭐7.2k)](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

*   [mininet (⭐5.8k)](https://github.com/mininet/mininet) - A popular network emulator and API written in Python.
*   [napalm (⭐2.4k)](https://github.com/napalm-automation/napalm) - Cross-vendor API to manipulate network devices.
*   [pox (⭐652)](https://github.com/noxrepo/pox) - A Python-based SDN control applications, such as OpenFlow SDN controllers.
*   [scapy (⭐12k)](https://github.com/secdev/scapy) - A brilliant packet manipulation library.

## RPC Servers

*RPC-compatible servers.*

*   [rpyc (⭐1.7k)](https://github.com/tomerfiliba/rpyc) (Remote Python Call) - A transparent and symmetric RPC library for Python
*   [zerorpc (⭐3.2k)](https://github.com/0rpc/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/).

**CLI & GUI**

## Command-line Interface Development

*Libraries for building command-line applications.*

*   Command-line Application Development
    *   [argparse](https://docs.python.org/3/library/argparse.html) - (Python standard library) Command-line option and argument parsing.
    *   [cement (⭐1.3k)](https://github.com/datafolklabs/cement) - CLI Application Framework for Python.
    *   [click (⭐17k)](https://github.com/pallets/click/) - A package for creating beautiful command line interfaces in a composable way.
    *   [cliff (⭐260)](https://github.com/openstack/cliff) - A framework for creating command-line programs with multi-level commands.
    *   [python-fire (⭐28k)](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object.
    *   [python-prompt-toolkit (⭐10k)](https://github.com/prompt-toolkit/python-prompt-toolkit) - A library for building powerful interactive command lines.
    *   [typer (⭐19k)](https://github.com/tiangolo/typer) - Modern CLI framework that uses Python type hints. Built on Click and Pydantic.
*   Terminal Rendering
    *   [alive-progress (⭐6.3k)](https://github.com/rsalmei/alive-progress) - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
    *   [asciimatics (⭐4.3k)](https://github.com/peterbrittain/asciimatics) - A package to create full-screen text UIs (from interactive forms to ASCII animations).
    *   [bashplotlib (⭐1.9k)](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal.
    *   [colorama (⭐3.8k)](https://github.com/tartley/colorama) - Cross-platform colored terminal text.
    *   [rich (⭐56k)](https://github.com/Textualize/rich) - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
    *   [textual (⭐35k)](https://github.com/Textualize/textual) - A framework for building interactive user interfaces that run in the terminal and the browser.
    *   [tqdm (⭐31k)](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI.

## Command-line Tools

*Useful CLI-based tools for productivity.*

*   Productivity Tools
    *   [cookiecutter (⭐25k)](https://github.com/cookiecutter/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
    *   [copier (⭐3.2k)](https://github.com/copier-org/copier) - A library and command-line utility for rendering projects templates.
    *   [doitlive (⭐3.6k)](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal.
    *   [fpp (⭐5.2k)](https://github.com/facebook/PathPicker) - Select files out of bash output.
    *   [thefuck (⭐96k)](https://github.com/nvbn/thefuck) - Correcting your previous console command.
    *   [tmuxp (⭐4.5k)](https://github.com/tmux-python/tmuxp) - A [tmux (⭐43k)](https://github.com/tmux/tmux) session manager.
    *   [xonsh (⭐9.2k)](https://github.com/xonsh/xonsh/) - A Python-powered shell. Full-featured and cross-platform.
    *   [youtube-dl (⭐140k)](https://github.com/ytdl-org/youtube-dl/) - A command-line program to download videos from YouTube and other video sites.
*   CLI Enhancements
    *   [httpie (⭐38k)](https://github.com/httpie/cli) - A command line HTTP client, a user-friendly cURL replacement.
    *   [iredis (⭐2.7k)](https://github.com/laixintao/iredis) - Redis CLI with autocompletion and syntax highlighting.
    *   [litecli (⭐3.2k)](https://github.com/dbcli/litecli) - SQLite CLI with autocompletion and syntax highlighting.
    *   [mycli (⭐12k)](https://github.com/dbcli/mycli) - MySQL CLI with autocompletion and syntax highlighting.
    *   [pgcli (⭐13k)](https://github.com/dbcli/pgcli) - PostgreSQL CLI with autocompletion and syntax highlighting.

## GUI Development

*Libraries for working with graphical user interface applications.*

*   Desktop
    *   [customtkinter (⭐13k)](https://github.com/tomschimansky/customtkinter) - A modern and customizable python UI-library based on Tkinter.
    *   [dearpygui (⭐15k)](https://github.com/RaylockLLC/DearPyGui/) - A Simple GPU accelerated Python GUI framework
    *   [enaml (⭐1.6k)](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declarative Syntax like QML.
    *   [kivy (⭐19k)](https://github.com/kivy/kivy) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
    *   [pyglet (⭐2.2k)](https://github.com/pyglet/pyglet) - A cross-platform windowing and multimedia library for Python.
    *   [pygobject (⭐156)](https://github.com/GNOME/pygobject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
    *   [PyQt](https://www.riverbankcomputing.com/static/Docs/PyQt6/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
    *   [pyside (⭐119)](https://github.com/pyside/pyside-setup) - Qt for Python offers the official Python bindings for [Qt](https://www.qt.io/), this is same as PyQt but it's the official binding with different licensing.
    *   [tkinter](https://docs.python.org/3/library/tkinter.html) - (Python standard library) The standard Python interface to the Tcl/Tk GUI toolkit.
    *   [toga (⭐5.3k)](https://github.com/beeware/toga) - A Python native, OS native GUI toolkit.
    *   [wxPython (⭐2.6k)](https://github.com/wxWidgets/Phoenix) - A blending of the wxWidgets C++ class library with the Python.
*   Web-based
    *   [flet (⭐16k)](https://github.com/flet-dev/flet) - Cross-platform GUI framework for building modern apps in pure Python.
    *   [nicegui (⭐16k)](https://github.com/zauberzeug/nicegui) - An easy-to-use, Python-based UI framework, which shows up in your web browser.
    *   [pywebview (⭐5.8k)](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component.
*   Terminal
    *   [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
    *   [urwid (⭐3k)](https://github.com/urwid/urwid) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
*   Wrappers
    *   [gooey (⭐22k)](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line.

**Text & Documents**

## Text Processing

*Libraries for parsing and manipulating plain texts.*

*   General
    *   [babel (⭐1.4k)](https://github.com/python-babel/babel) - An internationalization library for Python.
    *   [chardet (⭐2.5k)](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector.
    *   [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    *   [ftfy (⭐4k)](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically.
    *   [Levenshtein (⭐1.3k)](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity.
    *   [pangu.py (⭐276)](https://github.com/vinta/pangu.py) - Paranoid text spacing.
    *   [pyfiglet (⭐1.5k)](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python.
    *   [pypinyin (⭐5.3k)](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi (漢字) to pinyin (拼音).
    *   [textdistance (⭐3.5k)](https://github.com/orsinium/textdistance) - Compute distance between sequences with 30+ algorithms.
    *   [unidecode (⭐602)](https://github.com/avian2/unidecode) - ASCII transliterations of Unicode text.
*   Slugify
    *   [awesome-slugify (⭐491)](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode.
    *   [python-slugify (⭐1.6k)](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII.
    *   [unicode-slugify (⭐328)](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency.
*   Unique identifiers
    *   [hashids (⭐1.4k)](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
    *   [shortuuid (⭐2.2k)](https://github.com/skorokithakis/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs.
*   Parser
    *   [pygments (⭐2.1k)](https://github.com/pygments/pygments) - A generic syntax highlighter.
    *   [pyparsing (⭐2.5k)](https://github.com/pyparsing/pyparsing) - A general purpose framework for generating parsers.
    *   [python-nameparser (⭐702)](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components.
    *   [python-phonenumbers (⭐3.7k)](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers.
    *   [python-user-agents (⭐1.5k)](https://github.com/selwin/python-user-agents) - Browser user agent parser.
    *   [sqlparse (⭐4k)](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser.

## HTML Manipulation

*Libraries for working with HTML and XML.*

*   [beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
*   [cssutils (⭐89)](https://github.com/jaraco/cssutils) - A CSS library for Python.
*   [html5lib (⭐1.2k)](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments.
*   [justhtml (⭐1.1k)](https://github.com/EmilStenstrom/justhtml/) - A pure Python HTML5 parser that just works.
*   [lxml (⭐3k)](https://github.com/lxml/lxml) - A very fast, easy-to-use and versatile library for handling HTML and XML.
*   [markupsafe (⭐685)](https://github.com/pallets/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python.
*   [pyquery (⭐2.4k)](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML.
*   [untangle (⭐631)](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access.
*   [xmldataset (⭐80)](https://github.com/spurin/xmldataset) - Simple XML Parsing.
*   [xmltodict (⭐5.7k)](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.

## File Format Processing

*Libraries for parsing and manipulating specific text formats.*

*   General
    *   [docling (⭐56k)](https://github.com/docling-project/docling) - Library for converting documents into structured data.
    *   [kreuzberg (⭐6.7k)](https://github.com/kreuzberg-dev/kreuzberg) - High-performance document extraction library with a Rust core, supporting 62+ formats including PDF, Office, images with OCR, HTML, email, and archives.
    *   [pyelftools (⭐2.2k)](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information.
    *   [tablib (⭐4.8k)](https://github.com/jazzband/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
    *   [textract (⭐4.5k)](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc.
*   Office
    *   [docxtpl (⭐2.6k)](https://github.com/elapouya/python-docx-template) - Editing a docx document by jinja2 template
    *   [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    *   [pyexcel (⭐1.3k)](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files.
    *   [python-docx (⭐5.5k)](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
    *   [python-pptx (⭐3.2k)](https://github.com/scanny/python-pptx) - Python library for creating and updating PowerPoint (.pptx) files.
    *   [xlsxwriter (⭐3.9k)](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel .xlsx files.
    *   [xlwings (⭐6)](https://github.com/ZoomerAnalytics/xlwings) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
*   PDF
    *   [pdf\_oxide (⭐421)](https://github.com/yfedoseev/pdf_oxide) - A fast PDF library for text extraction, image extraction, and markdown conversion, powered by Rust.
    *   [pdfminer.six (⭐6.9k)](https://github.com/pdfminer/pdfminer.six) - Pdfminer.six is a community maintained fork of the original PDFMiner.
    *   [pikepdf (⭐2.7k)](https://github.com/pikepdf/pikepdf) - A powerful library for reading and editing PDF files, based on qpdf.
    *   [PyPDF2 (⭐9.9k)](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
    *   [reportlab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
    *   [weasyprint (⭐8.7k)](https://github.com/Kozea/WeasyPrint) - A visual rendering engine for HTML and CSS that can export to PDF.
*   Markdown
    *   [markdown-it-py (⭐1.3k)](https://github.com/executablebooks/markdown-it-py) - Markdown parser with 100% CommonMark support, extensions, and syntax plugins.
    *   [markdown (⭐4.2k)](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown.
    *   [markitdown (⭐91k)](https://github.com/microsoft/markitdown) - Python tool for converting files and office documents to Markdown.
    *   [mistune (⭐3k)](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown.
*   YAML
    *   [pyyaml (⭐2.9k)](https://github.com/yaml/pyyaml) - YAML implementations for Python.
*   TOML
    *   [tomllib](https://docs.python.org/3/library/tomllib.html) - (Python standard library) Parse TOML files.
*   CSV
    *   [csvkit (⭐6.4k)](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV.
*   Archive
    *   [unp (⭐455)](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily.

## File Manipulation

*Libraries for file manipulation.*

*   [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
*   [path.py (⭐1.1k)](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html).
*   [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) A cross-platform, object-oriented path library.
*   [python-magic (⭐2.9k)](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library.
*   [watchdog (⭐7.3k)](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.
*   [watchfiles (⭐2.4k)](https://github.com/samuelcolvin/watchfiles) - Simple, modern and fast file watching and code reload in python.

**Media**

## Image Processing

*Libraries for manipulating images.*

*   [pillow (⭐13k)](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
*   [pymatting (⭐1.9k)](https://github.com/pymatting/pymatting) - A library for alpha matting.
*   [python-barcode (⭐649)](https://github.com/WhyNotHugo/python-barcode) - Create barcodes in Python with no extra dependencies.
*   [python-qrcode (⭐4.9k)](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator.
*   [pyvips (⭐788)](https://github.com/libvips/pyvips) - A fast image processing library with low memory needs.
*   [quads (⭐1.2k)](https://github.com/fogleman/Quads) - Computer art based on quadtrees.
*   [scikit-image (⭐6.5k)](https://github.com/scikit-image/scikit-image) - A Python library for (scientific) image processing.
*   [thumbor (⭐10k)](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
*   [wand (⭐1.5k)](https://github.com/emcconville/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.

## Audio Processing

*Libraries for manipulating audio and its metadata.*

*   Audio
    *   [audioflux (⭐3.3k)](https://github.com/libAudioFlux/audioFlux) - A library for audio and music analysis, feature extraction.
    *   [audioread (⭐536)](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
    *   [dejavu (⭐6.7k)](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
    *   [gtts (⭐2.6k)](https://github.com/pndurette/gTTS) - Python library and CLI tool for converting text to speech using Google Translate TTS.
    *   [kapre (⭐946)](https://github.com/keunwoochoi/kapre) - Keras Audio Preprocessors.
    *   [librosa (⭐8.3k)](https://github.com/librosa/librosa) - Python library for audio and music analysis.
    *   [matchering (⭐2.4k)](https://github.com/sergree/matchering) - A library for automated reference audio mastering.
    *   [mingus (⭐926)](https://github.com/bspaans/python-mingus) - An advanced music theory and notation package with MIDI file and playback support.
    *   [pyAudioAnalysis (⭐6.2k)](https://github.com/tyiannak/pyAudioAnalysis) - Audio feature extraction, classification, segmentation and applications.
    *   [pydub (⭐9.7k)](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
    *   [TimeSide (⭐394)](https://github.com/Parisson/TimeSide) - Open web audio processing framework.
*   Metadata
    *   [beets (⭐15k)](https://github.com/beetbox/beets) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
    *   [eyed3 (⭐630)](https://github.com/nicfit/eyeD3) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
    *   [mutagen (⭐1.9k)](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata.
    *   [tinytag (⭐805)](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.

## Video Processing

*Libraries for manipulating video and GIFs.*

*   [moviepy (⭐14k)](https://github.com/Zulko/moviepy) - A module for script-based movie editing with many formats, including animated GIFs.
*   [scikit-video (⭐151)](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.
*   [vidgear (⭐3.7k)](https://github.com/abhiTronix/vidgear) - Most Powerful multi-threaded Video Processing framework.

## Game Development

*Awesome game development libraries.*

*   [arcade (⭐2k)](https://github.com/pythonarcade/arcade) - Arcade is a modern Python framework for crafting games with compelling graphics and sound.
*   [cocos (⭐638)](https://github.com/los-cocos/cocos) - A framework for building 2D games, demos, and other graphical/interactive applications.
*   [harfang3d (⭐641)](https://github.com/harfang3d/harfang3d) - Python framework for 3D, VR and game development.
*   [panda3d (⭐5.1k)](https://github.com/panda3d/panda3d) - 3D game engine developed by Disney.
*   [py-sdl2 (⭐338)](https://github.com/py-sdl/py-sdl2) - A ctypes based wrapper for the SDL2 library.
*   [pygame (⭐8.7k)](https://github.com/pygame/pygame) - Pygame is a set of Python modules designed for writing games.
*   [pyopengl (⭐399)](https://github.com/mcfletch/pyopengl) - Python ctypes bindings for OpenGL and it's related APIs.
*   [renpy (⭐6.3k)](https://github.com/renpy/renpy) - A Visual Novel engine.

**Python Language**

## Implementations

*Implementations of Python.*

*   [clpython (⭐394)](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp.
*   [cpython (⭐72k)](https://github.com/python/cpython) - Default, most widely used implementation of the Python programming language written in C.
*   [cython (⭐11k)](https://github.com/cython/cython) - Optimizing Static Compiler for Python.
*   [ironpython (⭐2.7k)](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#.
*   [micropython (⭐22k)](https://github.com/micropython/micropython) - A lean and efficient Python programming language implementation.
*   [PeachPy (⭐2k)](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python.
*   [pypy (⭐1.7k)](https://github.com/pypy/pypy) - A very fast and compliant implementation of the Python language.
*   [pyston (⭐2.5k)](https://github.com/pyston/pyston/) - A Python implementation using JIT techniques.

## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

*   [attrs (⭐5.7k)](https://github.com/python-attrs/attrs) - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions.
*   [bidict (⭐1.6k)](https://github.com/jab/bidict) - Efficient, Pythonic bidirectional map data structures and related functionality.
*   [box (⭐2.8k)](https://github.com/cdgriffith/Box) - Python dictionaries with advanced dot notation access.

## Functional Programming

*Functional Programming with Python.*

*   [coconut (⭐4.3k)](https://github.com/evhub/coconut) - A variant of Python built for simple, elegant, Pythonic functional programming.
*   [cytoolz (⭐1.1k)](https://github.com/pytoolz/cytoolz/) - Cython implementation of `Toolz`: High performance functional utilities.
*   [functools](https://docs.python.org/3/library/functools.html) - (Python standard library) Higher-order functions and operations on callable objects.
*   [funcy (⭐3.5k)](https://github.com/Suor/funcy) - A fancy and practical functional tools.
*   [more-itertools (⭐4k)](https://github.com/erikrose/more-itertools) - More routines for operating on iterables, beyond `itertools`.
*   [returns (⭐4.2k)](https://github.com/dry-python/returns) - A set of type-safe monads, transformers, and composition utilities.
*   [toolz (⭐5.1k)](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries.

## Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio (⭐5k)](https://github.com/timofurrer/awesome-asyncio).*

*   [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    *   [awesome-asyncio (⭐5k)](https://github.com/timofurrer/awesome-asyncio)
*   [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
*   [gevent (⭐6.4k)](https://github.com/gevent/gevent) - A coroutine-based Python networking library that uses [greenlet (⭐1.8k)](https://github.com/python-greenlet/greenlet).
*   [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
*   [trio (⭐7.2k)](https://github.com/python-trio/trio) - A friendly library for async concurrency and I/O.
*   [twisted (⭐6k)](https://github.com/twisted/twisted) - An event-driven networking engine.
*   [uvloop (⭐12k)](https://github.com/MagicStack/uvloop) - Ultra fast asyncio event loop.

## Date and Time

*Libraries for working with dates and times.*

*   [arrow (⭐9k)](https://github.com/arrow-py/arrow) - A Python library that offers a sensible and human-friendly approach to creating, manipulating, formatting and converting dates, times and timestamps.
*   [dateutil (⭐2.6k)](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
*   [pendulum (⭐6.6k)](https://github.com/sdispater/pendulum) - Python datetimes made easy.
*   [zoneinfo](https://docs.python.org/3/library/zoneinfo.html) - (Python standard library) IANA time zone support. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.

**Python Toolchain**

## Environment Management

*Libraries for Python version and virtual environment management.*

*   [pyenv (⭐44k)](https://github.com/pyenv/pyenv) - Simple Python version management.
    *   [pyenv-win (⭐7.1k)](https://github.com/pyenv-win/pyenv-win) - Pyenv for Windows, Simple Python version management.
*   [uv (⭐81k)](https://github.com/astral-sh/uv) - An extremely fast Python version, package and project manager, written in Rust.
*   [virtualenv (⭐5k)](https://github.com/pypa/virtualenv) - A tool to create isolated Python environments.

## Package Management

*Libraries for package and dependency management.*

*   [conda (⭐7.3k)](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
*   [mamba (⭐8k)](https://github.com/mamba-org/mamba) - A reimplementation of the `conda` package manager in C++.
*   [pip (⭐10k)](https://github.com/pypa/pip) - The package installer for Python.
*   [pipx (⭐13k)](https://github.com/pypa/pipx) - Install and Run Python Applications in Isolated Environments. Like `npx` in Node.js.
*   [poetry (⭐34k)](https://github.com/sdispater/poetry) - Python dependency management and packaging made easy.
*   [uv (⭐81k)](https://github.com/astral-sh/uv) - An extremely fast Python version, package and project manager, written in Rust.

## Package Repositories

*Local PyPI repository server and proxies.*

*   [bandersnatch (⭐527)](https://github.com/pypa/bandersnatch/) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
*   [devpi (⭐1.1k)](https://github.com/devpi/devpi) - PyPI server and packaging/testing/release tool.
*   [warehouse (⭐4k)](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI).

## Distribution

*Libraries to create packaged executables for release distribution.*

*   [cx-Freeze (⭐1.5k)](https://github.com/marcelotduarte/cx_Freeze) - It is a Python tool that converts Python scripts into standalone executables and installers for Windows, macOS, and Linux.
*   [Nuitka (⭐15k)](https://github.com/Nuitka/Nuitka) - Compiles Python programs into high-performance standalone executables (cross-platform, supports all Python versions).
*   [py2app (⭐421)](https://github.com/ronaldoussoren/py2app) - Freezes Python scripts (Mac OS X).
*   [py2exe (⭐995)](https://github.com/py2exe/py2exe) - Freezes Python scripts (Windows).
*   [pyarmor (⭐5k)](https://github.com/dashingsoft/pyarmor) - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.
*   [pyinstaller (⭐13k)](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform).
*   [shiv (⭐1.9k)](https://github.com/linkedin/shiv) - A command line utility for building fully self-contained zipapps (PEP 441), but with all their dependencies included.

## Configuration Files

*Libraries for storing and parsing configuration options.*

*   [configobj (⭐337)](https://github.com/DiffSK/configobj) - INI file parser with validation.
*   [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.
*   [dynaconf (⭐4.3k)](https://github.com/dynaconf/dynaconf) - Dynaconf is a configuration manager with plugins for Django, Flask and FastAPI.
*   [hydra (⭐10k)](https://github.com/facebookresearch/hydra) - Hydra is a framework for elegantly configuring complex applications.
*   [python-decouple (⭐3k)](https://github.com/HBNetwork/python-decouple) - Strict separation of settings from code.

**Security**

## Cryptography

*   [cryptography (⭐7.5k)](https://github.com/pyca/cryptography) - A package designed to expose cryptographic primitives and recipes to Python developers.
*   [paramiko (⭐9.7k)](https://github.com/paramiko/paramiko) - The leading native Python SSHv2 protocol library.
*   [pynacl (⭐1.2k)](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.

## Penetration Testing

*Frameworks and tools for penetration testing.*

*   [fsociety (⭐12k)](https://github.com/Manisso/fsociety) - A Penetration testing framework.
*   [setoolkit (⭐15k)](https://github.com/trustedsec/social-engineer-toolkit) - A toolkit for social engineering.
*   [sherlock (⭐74k)](https://github.com/sherlock-project/sherlock) - Hunt down social media accounts by username across social networks.
*   [sqlmap (⭐37k)](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.

**Miscellaneous**

## Hardware

*Libraries for programming with hardware.*

*   [bleak (⭐2.4k)](https://github.com/hbldh/bleak) - A cross platform Bluetooth Low Energy Client for Python using asyncio.
*   [mouse (⭐961)](https://github.com/boppreh/mouse) - Hook and simulate global mouse events on Windows and Linux.
*   [pynput (⭐2.1k)](https://github.com/moses-palmer/pynput) - A library to control and monitor input devices.

## Microsoft Windows

*Python programming on Microsoft Windows.*

*   [pythonnet (⭐5.4k)](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR).
*   [pywin32 (⭐5.5k)](https://github.com/mhammond/pywin32) - Python Extensions for Windows.
*   [winpython (⭐2.2k)](https://github.com/winpython/winpython) - Portable development environment for Windows 10/11.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

*   [blinker (⭐2k)](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system.
*   [boltons (⭐6.9k)](https://github.com/mahmoud/boltons) - A set of pure-Python utilities.
*   [itsdangerous (⭐3.1k)](https://github.com/pallets/itsdangerous) - Various helpers to pass trusted data to untrusted environments.
*   [pluginbase (⭐1.1k)](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python.
*   [tryton (⭐171)](https://github.com/tryton/tryton) - A general-purpose business framework.

# Resources

Where to discover learning resources or new Python libraries.

## Newsletters

*   [Awesome Python Newsletter](http://python.libhunt.com/newsletter)
*   [Pycoder's Weekly](https://pycoders.com/)
*   [Python Tricks](https://realpython.com/python-tricks/)
*   [Python Weekly](https://www.pythonweekly.com/)

## Podcasts

*   [Django Chat](https://djangochat.com/)
*   [PyPodcats](https://pypodcats.live)
*   [Python Bytes](https://pythonbytes.fm)
*   [Python Test](https://podcast.pythontest.com/)
*   [Talk Python To Me](https://talkpython.fm/)
*   [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines (⭐286k)](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

***

If you have any question about this opinionated list, do not hesitate to contact [@VintaChen](https://twitter.com/VintaChen) on Twitter.

