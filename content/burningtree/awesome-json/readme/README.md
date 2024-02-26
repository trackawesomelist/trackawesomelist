# Awesome Json Overview

A curated list of awesome JSON libraries and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/burningtree/awesome-json/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 burningtree/awesome-json](https://github.com/burningtree/awesome-json) · ⭐ 1.3K · 🏷️ Miscellaneous

[ [Daily](/content/burningtree/awesome-json/README.md) / [Weekly](/content/burningtree/awesome-json/week/README.md) / Overview ]

---

# Awesome JSON [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome JSON libraries and resources.

Inspired by the [awesome (⭐289k)](https://github.com/sindresorhus/awesome) list.

*   [Awesome JSON](#awesome-json)
    *   [Applications](#applications)
    *   [Binary Serialization](#binary-serialization)
    *   [Browser Extensions](#browser-extensions)
    *   [Command-line tools](#command-line-tools)
    *   [Databases](#databases)
    *   [Datasets](#datasets)
    *   [Data modeling](#data-modeling)
    *   [Data generation](#data-generation)
    *   [Differencing](#differencing)
    *   [Editors](#editors)
    *   [Format Extensions](#format-extensions)
    *   [Frontend components](#frontend-components)
    *   [Libraries](#libraries)
    *   [Linters](#linters)
    *   [Online tools](#online-tools)
    *   [Schema Specifications](#schema-specifications)
    *   [Services](#services)
    *   [Supersets](#supersets)
    *   [Related formats](#related-formats)
    *   [Resources](#resources)
    *   [Templates](#templates)
    *   [Testing](#testing)
    *   [Text Editor Plugins](#text-editor-plugins)
    *   [Transformations](#transformations)
    *   [Tutorials](#tutorials)
    *   [Queries](#queries)
    *   [JSON Schema Frontend components](#json-schema-frontend-components)
    *   [JSON Schema Tools](#json-schema-tools)
    *   [JSON Schema Resources](#json-schema-resources)
    *   [JSON Schema Validators](#json-schema-validators)
    *   [Contribute](#contribute)

## Applications

*   [Dadroit JSON Viewer](https://dadroit.com) - Very fast JSON Viewer, supporting huge (multi gigabytes) files, JSON log (JSON-Lines and ndjson).

**OS X**

*   [Visual JSON](https://apps.apple.com/us/app/visual-json/id488709442?mt=12) ([github (⭐301)](https://github.com/youknowone/VisualJSON)) - simple JSON pretty-viewer for Mac OS X.
*   [JSONExport (⭐4.8k)](https://github.com/Ahmed-Ali/JSONExport) - convert a object to a class of one of the currently supported languages.

## Binary Serialization

*   [BSON](https://bsonspec.org/) - Binary JSON.
*   [MessagePack](https://msgpack.org/) - An extremely efficient object serialization library.
*   [UBJSON](https://ubjson.org/) - The universally compatible format specification for binary JSON.
*   [CBOR](https://datatracker.ietf.org/doc/html/rfc7049) - Concise Binary Object Representation.
*   [PSON (⭐457)](https://github.com/dcodeIO/PSON) - Protocol JSON, super efficient binary serialization format.
*   [JSON BinPack](https://www.jsonbinpack.org) - Space-efficient binary JSON serialization format based on JSON Schema.

## Browser Extensions

**Chrome**

*   [JSON Formatter](https://chromewebstore.google.com/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github (⭐3.6k)](https://github.com/callumlocke/json-formatter)) - Makes JSON easy to read. Open source.
*   [JSON Viewer](https://chromewebstore.google.com/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github (⭐3.2k)](https://github.com/tulios/json-viewer)) - It is a Chrome extension for printing JSON and JSONP.
*   [JSON Finder](https://chromewebstore.google.com/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github (⭐39)](https://github.com/rapee/jsonfinder)) - Browse like you do it in Finder.
*   [JSON Viewer Pro](https://chromewebstore.google.com/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc) ([github (⭐518)](https://github.com/rbrahul/Awesome-JSON-Viewer) - An open source Chrome extension for browsing JSON with syntax highlighting and folding, or as a visual graph.
*   [Discoverable JSON](https://chromewebstore.google.com/detail/json-manipulator-json-to/pcakbljjigdafljigcpbmjllkbhlncjg) ([github (⭐3)](https://github.com/noitcudni/discoverable-json)) - Gron inspired Extension. Convert a JSON document into javascript expressions. Comes with filter, remove, find-and-replace capabilities.

**Firefox**

*   [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github (⭐1.5k)](https://github.com/bhollis/jsonview)) - View JSON documents in the browser.

**Safari**

*   [JSONAce](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonace-56Q494QF3LL) ([github (⭐72)](https://github.com/acrogenesis/JSONAce)) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor.
*   [JSONView](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonview-56Q494QF3L) ([github (⭐293)](https://github.com/acrogenesis/jsonview-safari)) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser

## Command-line tools

*   [dsq (⭐3.5k)](https://github.com/multiprocessio/dsq) - Tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
*   [fx (⭐18k)](https://github.com/antonmedv/fx) - A interactive terminal tool.
*   [jo (⭐4.6k)](https://github.com/jpmens/jo) - A small utility to create JSON objects
*   [jsoncat (⭐27)](https://github.com/pantuza/jsoncat) - Pretty-print Json in terminal with colors and adjusting tabs size.
*   [jq (⭐28k)](https://github.com/jqlang/jq) - A lightweight and flexible command-line JSON processor.
*   [livejq (⭐10)](https://github.com/kunalsin9h/livejq) - An alternative `jq` implementation in rust for continuous parsing without crashing on invalid JSON
*   [json](http://trentm.com/json/) - A "json" command for massaging JSON on your Unix command line.
*   [json-search (⭐4)](https://github.com/cosmo-ray/json-search) - A small tool to search for objects/values in json files.
*   [jshon](https://web.archive.org/web/20240206155217/http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.
*   [jarg](http://jdp.github.io/jarg/) - Shorthand JSON and form encoding syntax in the shell.
*   [jsawk (⭐1.4k)](https://github.com/micha/jsawk) - Like awk, but for JSON.
*   [json-dotenv (⭐8)](https://github.com/decryptus/json-dotenv) - Manipulate and extract envfiles in json format.
*   [gron (⭐13k)](https://github.com/tomnomnom/gron) - Convert a JSON file into discrete assignments that are greppable.
*   [jid (⭐6.7k)](https://github.com/simeji/jid) - Incremental Digger. Drill down JSON interactively by using filtering queries like jq.
*   [jiq (⭐899)](https://github.com/fiatjaf/jiq) - It's `jid` with `jq`. You can drill down interactively by using `jq` filtering queries.
*   [jv (⭐117)](https://github.com/maxzender/jv) - jv (for jsonviewer) helps you view your JSON.
*   [jl (⭐473)](https://github.com/chrisdone/jl) - Functional sed for JSON.
*   [oj (⭐767)](https://github.com/ohler55/ojg) - A fast and flexible command line JSON processor.
*   [visidata (⭐7.3k)](https://github.com/saulpw/visidata) - A terminal spreadsheet-like tool for interactively exploring data.
*   [jc (⭐7.4k)](https://github.com/kellyjonbrazil/jc) - Converts the output of many CLI tools, file-types, and common strings into JSON
*   [logdy (⭐166)](https://github.com/logdyhq/logdy-core) - jq, tail, less, grep and awk merged together and available in a clean web UI.

## Databases

*   [MongoDB](https://www.mongodb.com/) - an open-source document database, and the leading NoSQL database.
*   [RethinkDB](https://rethinkdb.com/) - An open-source distributed document database with a pleasant and powerful query language.
*   [EJDB (⭐1.4k)](https://github.com/Softmotions/ejdb) - Embedded JSON Database engine published under MIT license. (C)
*   [lowdb (⭐21k)](https://github.com/typicode/lowdb) - Flat file database built on lodash API. (Javascript)
*   [Lawnchair (⭐2.1k)](https://github.com/brianleroux/lawnchair) - A lightweight clientside document store. (Javascript)
*   [JSON ODM (⭐100)](https://github.com/konsultaner/jsonOdm) - Object document mapper for JavaScript to use on the server or in the browser. (Javascript)
*   [JSON Server (⭐71k)](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds.
*   [Kinto (⭐4.3k)](https://github.com/Kinto/kinto) - A lightweight JSON storage service with synchronisation and sharing abilities.
*   [CouchDB](https://couchdb.apache.org/) - Seamless multi-master sync, that scales from Big Data to Mobile, with an Intuitive HTTP/JSON API and designed for Reliability.
*   [RxDB (⭐20k)](https://github.com/pubkey/rxdb) - Event-driven JSON-Database with JSON-Schema, mango-Query and CouchDB-sync. (Javascript)
*   [JSONlite (⭐843)](https://github.com/nodesocket/jsonlite) - A simple, self-contained, serverless, zero-configuration, json document store. (Bash)

## Datasets

*   [country.io](http://country.io/data/) - Various country related datasets, as JSON inc currency, country codes, names and more
*   [countries (⭐5.9k)](https://github.com/mledoze/countries) - World countries.
*   [vat-rates](http://jsonvat.com/) - VAT rates for all EU countries.
*   [MTG JSON](https://mtgjson.com/) - Up to date Magic the Gathering card data.
*   [Heartstone JSON](https://hearthstonejson.com/) - Up to date Hearthstone card data.
*   [getCountries()](https://peric.github.io/GetCountries/) - Generator for custom Countries data.

## Data modeling

*   [JSONModel (⭐6.9k)](https://github.com/jsonmodel/jsonmodel) - Magical Data Modelling Framework. (Objective-C)

## Data generation

*   [jsonymize (⭐17)](https://github.com/cameronhunter/jsonymize) - Reads data from standard input, anonymizes, then writes to standard output.
*   [dyson (⭐835)](https://github.com/webpro/dyson) - Server for dynamic, fake JSON. (node.js)

## Differencing

*   [JSONPatch](https://jsonpatch.com/) - A format for describing changes to a document.
*   [JSON-Patch (⭐1.7k)](https://github.com/Starcounter-Jack/JSON-Patch) - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript)
*   [jiff (⭐604)](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript)
*   [json-patch-php (⭐111)](https://github.com/mikemccabe/json-patch-php) - implementation of JSON-patch (IETF RFC 6902) (PHP)
*   [dffptch (⭐170)](https://github.com/paldepind/dffptch) - A micro library for diffing and patching using a compact diff format. (Javascript)
*   [jsondiffpatch (⭐4.6k)](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript)

## Editors

*   [FrontAid CMS](https://frontaid.io/) - Content Management System that supports arbitrary data model structures.
*   [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual editor built as an AngularJS directive.
*   [JSON Crack](https://jsoncrack.com/) - Display your JSON as a graph

## Format Extensions

*   [GeoJSON](https://geojson.org/) - A geospatial data interchange format.
*   [JSON-LD](https://json-ld.org/) - A lightweight Linked Data format.
*   [JSON-RPC](https://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
*   [JSONP](https://en.wikipedia.org/wiki/JSONP) - Safer cross-domain Ajax with JSON-P/JSONP.
*   [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
*   [JSON5](https://json5.org/) - a extension that aims to make it easier for humans to write and maintain by hand.
*   [JSON6 (⭐230)](https://github.com/d3x0r/json6) - JSON for Humans (ES6).
*   [JSON 1.1/JSONX](https://json-next.github.io/) - An evolved version 1.1 with format extension for humans incl. comments, unquoted and multi-line strings, optional and trailing commas and more.
*   [JSON Resume](https://jsonresume.org/) - The open source initiative to create standard for resumes.
*   [JSON Web Tokens](https://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
*   [JSON API](https://jsonapi.org/) - A standard for building APIs.
*   [Collection+JSON](http://amundsen.com/media-types/collection/) - A read/write hypermedia-type designed to support management and querying of simple collections.
*   [hal-json](https://stateless.group/hal_specification.html) - A set of conventions for expressing hyperlinks in either JSON or XML.
*   [JSON Activity Streams](https://activitystrea.ms/) - A format for syndicating social activities around the web.
*   [JSON-stat (⭐22)](https://github.com/jsonstat/jsonstat) - Simple lightweight format for data dissemination.
*   [/contribute.json](https://www.contributejson.org/) - Making open source contribution information easier to access, across projects.
*   [NDJSON](https://ndjson.org/) (Newline delimited JSON) - a standard for delimiting JSON in stream protocols.
*   [survey.js](https://surveyjs.io/form-library) - JSON based survey library.
*   [JSON Meta Application Protocol (JMAP)](https://jmap.io/) - A protocol for synchronising JSON-based data objects efficiently, with support for push and out-of-band binary data upload/download.
*   [J<sub>ack</sub>SON: JSON secret keeper (⭐18)](https://github.com/rosehgal/jackson) - JSONic way of storing secrets in config file.

## Frontend components

*   [JSON editor jQuery plugin (⭐560)](https://github.com/DavidDurman/FlexiJsonEditor) - component for you web apps/pages. (jQuery)
*   [jqTree](http://mbraak.github.io/jqTree/) - Widget for displaying a tree structure in html. (jQuery)
*   [jsTree](https://www.jstree.com/docs/json/) - jquery plugin, that provides interactive trees. (jQuery)
*   [Dynatable.js (⭐2.8k)](https://github.com/alfajango/jquery-dynatable) - A funner, semantic, HTML5+JSON, interactive table plugin. (jQuery)
*   [JSON Formatter (⭐369)](https://github.com/mohsen1/json-formatter) - Angular directive for collapsible JSON in HTML. (AngularJS)
*   [react-jsonschema-form](https://rjsf-team.github.io/react-jsonschema-form/) - A React component for building Web forms from JSON Schema. (React)
*   [@textea/json-viewer (⭐355)](https://github.com/TexteaInc/json-viewer) - A React component for JSON viewer. (React)
*   [ngx-formly (⭐2.7k)](https://github.com/ngx-formly/ngx-formly) - JSON powered / Dynamic forms for Angular

## Libraries

**C**

*   [Jansson (⭐2.9k)](https://github.com/akheron/jansson) - A C library for encoding, decoding and manipulating data.
*   [jsmn](https://zserge.com/jsmn.html) - A minimalistic parser in C. It can be easily integrated into the resource-limited projects or embedded systems.
*   [json-build (⭐33)](https://github.com/lcsmuller/json-build) - A minimalistic serializer in C. It can be easily integrated into the resource-limited projects or embedded systems.
*   [ojc (⭐34)](https://github.com/ohler55/ojc) - A fast JSON parser.

**C++**

*   [ArduinoJson (⭐6.5k)](https://github.com/bblanchon/ArduinoJson) - An efficient library for embedded systems.
*   [JSON++ (⭐40)](https://github.com/tunnuz/json) - A self contained Flex/Bison parser for C++11.
*   [json11 (⭐2.5k)](https://github.com/dropbox/json11) - A tiny library for C++11.
*   [Nlohmann JSON (⭐39k)](https://github.com/nlohmann/json) - A C++11 header-only class.
*   [RapidJSON (⭐14k)](https://github.com/Tencent/rapidjson) - A fast JSON parser/generator for C++ with both SAX/DOM style API
*   [simdjson (⭐18k)](https://github.com/simdjson/simdjson) - Parsing gigabytes of JSON per second.

**Clojure**

*   [data.json](https://github.com/clojure/data.json) - parser/generator to/from Clojure data structures.

**Fortran**

*   [JSON-Fortran (⭐313)](https://github.com/jacobwilliams/json-fortran) - A Fortran library for writing, reading, and manipulating JSON files and data structures.

**Go**

*   [ojg (⭐767)](https://github.com/ohler55/ojg) - A collection of high performance JSON processing and generating tool.

**Haskell**

*   [aeson-qq (⭐79)](https://github.com/sol/aeson-qq) - JSON quasiquoter for Haskell.
*   [json-schema](http://hackage.haskell.org/package/json-schema) - JSON Schema library for Haskell
*   [hjsonschema](http://hackage.haskell.org/package/hjsonschema) - JSON Schema Draft 4 library for Haskell

**Java**

*   [JSON-java (⭐4.4k)](https://github.com/stleary/JSON-java) - A reference implementation.
*   [Fast JSON Processor (⭐26k)](https://github.com/alibaba/fastjson)
*   [Gson (⭐23k)](https://github.com/google/gson) - A Java library to convert JSON to Java objects and vice-versa.
*   [Jackson (⭐8.7k)](https://github.com/FasterXML/jackson) - A multi-purpose Java library for processing JSON data format.
*   [moshi (⭐9.4k)](https://github.com/square/moshi) - A modern JSON library for Android and Java.
*   [essential-json (⭐1)](https://github.com/arkanovicz/essential-json) - A lightweight Java library for serialization, parsing and manipulation with a clean and precise API.
*   [dsl-json (⭐980)](https://github.com/ngs-doo/dsl-json) - A very fast streaming JSON library. Operates on byte arrays.
*   [mjson (⭐81)](https://github.com/bolerio/mjson) - Lean JSON Library for Java, with a compact, elegant API.

**Javascript**

*   [JSON-js (⭐8.6k)](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript.
*   [JSON 3](https://bestiejs.github.io/json3/) - A modern implementation.
*   [oboe.js (⭐4.7k)](https://github.com/jimhigson/oboe.js) - A streaming approach, speeds up web applications by providing parsed objects before the response completes.
*   [FracturedJsonJs](https://www.npmjs.com/package/fracturedjsonjs) - A JSON formatter that produces human-readable but fairly compact output.

**Objective-C**

*   [JSONKit (⭐6.2k)](https://github.com/johnezang/JSONKit) - Objective-C library.
*   [SBJson (⭐3.7k)](https://github.com/SBJson/SBJson) - Parse one or more chunks of data.

**Perl**

*   [JSON::Tiny (⭐11)](https://github.com/daoswald/JSON-Tiny) - Perl module for encoding and decoding JSON in a minimalistic way.

**PL/SQL**

*   [PL/JSON (⭐429)](https://github.com/pljson/pljson) - A generic JSON object written in PL/SQL.

**PHP**

*   [Webmozart JSON (⭐357)](https://github.com/webmozart/json) - A robust decoder/encoder with support for schema validation.

**Python**

*   [simplejson (⭐1.6k)](https://github.com/simplejson/simplejson) - A simple, fast, extensible encoder/decoder
*   [jsonpickle](http://jsonpickle.github.io/) - Library for serializing any arbitrary object graph.
*   [metamagic.json](https://pypi.org/project/metamagic.json/) - An ultra-fast Python 3 implementation of a JSON encoder.

**Ruby**

*   [oj (⭐3.1k)](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem.
*   [MultiJSON (⭐745)](https://github.com/intridea/multi_json) - A generic swappable back-end for JSON handling.

**React**

*   [json2react (⭐167)](https://github.com/txgruppi/json2react) - Use JSON to create React Stateless Components.

**.NET**

*   [jsonfx (⭐380)](https://github.com/jsonfx/jsonfx) - serialization framework for .NET.
*   [jsonapi-consumer (⭐6)](https://github.com/OKTAYKIR/jsonapi-consumer) - Client framework for consuming JSONAPI based APIs on the [JSON API standard](https://jsonapi.org).
*   [FracturedJson](https://www.nuget.org/packages/FracturedJson) - A formatter that produces human-readable but fairly compact output.

**Scala**

*   [spray-json (⭐970)](https://github.com/spray/spray-json) - A lightweight, clean and simple implementation in Scala.
*   [circe (⭐2.5k)](https://github.com/circe/circe) - Yet another JSON library for Scala.
*   [scala-jsonapi (⭐108)](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON:API spec with Play, Spray and/or Circe backends.
*   [jsoniter-scala (⭐698)](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs.

**Shell**

*   [jshn](https://openwrt.org/docs/guide-developer/jshn) - JSON parsing and generation library in for shell scripts (Ash/Bash)

**Swift**

*   [SwiftyJSON (⭐22k)](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with data in Swift.

## Linters

*   [jsonlint (⭐1.9k)](https://github.com/zaach/jsonlint) - Parser and validator with a CLI. (Javascript)
*   [JSON Lint (⭐1.3k)](https://github.com/Seldaek/jsonlint) - PHP linter. (PHP)

## Online tools

*   [JSONLint](https://jsonlint.com/) - The JSON Validator.
*   [JSONCompare](https://jsoncompare.com/) - The Advanced Version of the JSON Linter.
*   [JSONMate](https://www.jsonmate.com/) - JSON editor, inspector and beautifier.
*   [JSON Editor online](https://jsoneditoronline.org/) - A web-based tool to view, edit and format.
*   [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw Code.
*   [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - Formatter to help with debugging.
*   [JSON Generator](https://json-generator.com/) - Tool for generating random data.
*   [FakeJSON](https://fakejson.com/) - Web API to quickly generate fake data for your application.
*   [JSON to CSV](https://konklone.io/json/) - A free, in-browser JSON to CSV converter.
*   [CSV to JSON](https://alef.website/tools/csv-to-json) - Easy, privacy-friendly and offline-first online csv to json converter
*   [json2csharp](https://json2csharp.com/) - Generate c# classes from a json string or url.
*   [JSON Utils](http://jsonutils.com/) - Site for generating C#, VB.Net, and Javascript classes from JSON.
*   [geojson.io](https://geojson.io/) - Simply edit GeoJSON map data.
*   [jq play](https://jqplay.org/) - A playground for jq.
*   [json2yaml](https://www.json2yaml.com/) - Convert JSON to YAML online.
*   [JSON Selector Generator](http://jsonselector.com/) - A simple GUI for generating the selectors to access.
*   [JSON.fr](https://www.json.fr/) - Fully client-side validator and formatter.
*   [ObjGen](https://www.objgen.com/json) - Online live JSON generator.
*   [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping.
*   [Extends Class](https://extendsclass.com/json-diff.html) - Diff tool to compare two files.
*   [JSON Schema Validate API](https://assertible.com/json-schema-validation) - A simple and free JSON Schema Validation API.
*   [JSONPerf](https://jsonperf.com) - A Visual, Unbiased and Up-to-Date JSON Performance Benchmark.
*   [FracturedJson](https://j-brooke.github.io/FracturedJson/) - Formatter that produces human-readable but fairly compact output.

## Schema Specifications

*   [JSON Schema](https://json-schema.org/) - a JSON based format for defining the structure of JSON data.
*   [Itemscript](https://code.google.com/archive/p/itemscript/) - Language for validating and specifying values.
*   [Kwalify (⭐21)](https://github.com/kvs/kwalify) - A parser, schema validator, and data binding tool
*   [Rx](https://rx.codesimply.com/) - Simple, Extensible Schemata.

## Services

*   [Exchange Rate API](https://www.exchangerate-api.com) - A simple and free API for currency exchange rate data.
*   [ipinfo.io](https://ipinfo.io) - JSON IP and GeoIP REST API.
*   [JSONProxy (⭐300)](https://github.com/afeld/jsonp) - Simple HTTP proxy that enables cross-domain requests to any JSON API.
*   [Myjson](http://myjson.com/) - A simple store for your web or mobile app.
*   [Telize](https://www.telize.com/) - JSON IP and GeoIP REST API.
*   [jsonpad](https://jsonpad.io/) - a simple JSON storage platform.

## Supersets

*   [YAML](https://yaml.org) - A human friendly data serialization standard for all programming languages.
*   [HanSON (⭐152)](https://github.com/timjansen/hanson) - JSON for Humans - with unquoted identifiers, multi-line strings and comments.
*   [μson (⭐69)](https://github.com/burningtree/uson) (uson) - a shorthand for JSON.
*   [HOCON (⭐6.1k)](https://github.com/lightbend/config/blob/master/HOCON.md) - Human-Optimized Config Object Notation.
*   [ASON (⭐2)](https://github.com/sadmac7000/libason) - A semantically complete superset of JSON (draft).
*   [TOML (⭐19k)](https://github.com/toml-lang/toml) - A minimal configuration file format that's easy to read due to obvious semantics.
*   [HCL (⭐5k)](https://github.com/hashicorp/hcl) - A structured configuration language that is both human and machine friendly.

## Tutorials

*   [Introducing JSON](http://json.org/)
*   [JSON Tutorial](https://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JavaScript Object Notation (JSON).
*   [JSON - Rosetta Code](https://rosettacode.org/wiki/JSON) - Basic operations in different languages (57 languages in this moment).
*   [What is JSON and how to use it](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - Video tutorial for beginners.
*   [jq Primer: Munging JSON Data](https://andrew.gibiansky.com/) - How jq can be used to process JSON files just as effectively as traditional Unix tools.

## Related formats

*   [AXON (⭐22)](https://github.com/intellimath/pyaxon) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
*   [CSON (⭐1.3k)](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. JSON for CoffeeScript objects.
*   [MSON (⭐895)](https://github.com/apiaryio/mson) - Markdown syntax compatible with describing JSON and JSON Schema.
*   [ArchieML](http://archieml.org/) - Structured text format optimized for human writability.

## Resources

*   [Type-o-rama (⭐244)](https://github.com/stereobooster/type-o-rama) - JS type systems interportability, comparison of different JS type systems and conversion between them.
*   [Awesome jq (⭐707)](https://github.com/fiatjaf/awesome-jq) - A curated list of awesome jq tools and resources.

## Templates

*   [Jsonnet](https://jsonnet.org/) - A domain specific configuration language that helps you define JSON data.
*   [rabl (⭐3.7k)](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)
*   [json2html](http://json2html.com/) - HTML templating library with wrappers for both jQuery and Node.js. (Javascript)

## Testing

*   [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).
*   [JSONassert (⭐960)](https://github.com/skyscreamer/JSONassert) - Write JSON unit tests in less code. Great for testing REST interfaces. (Java)
*   [JsonUnit (⭐845)](https://github.com/lukas-krecan/JsonUnit) - A library that simplifies JSON comparison in unit tests. It's strongly inspired by XmlUnit.
*   [JSON Parsing Test Suite (⭐822)](https://github.com/nst/JSONTestSuite) - A very complete test suite and validation framework.

## Text Editor Plugins

**Emacs**

*   [JSON Reformat (⭐172)](https://github.com/gongo/json-reformat) - Reformat tool.

**Vim**

*   [vim-json (⭐1.2k)](https://github.com/elzr/vim-json) - A better JSON for Vim: distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing. Pathogen-friendly.

**Visual Studio Code**

*   [FracturedJsonVsc](https://marketplace.visualstudio.com/items?itemName=j-brooke.fracturedjsonvsc) - Formatter that produces human-readable but fairly compact output.

**Neovim**

*   [nvim-jqx (⭐263)](https://github.com/gennaro-tedesco/nvim-jqx) - Browse and query json files in neovim from the quickfix window. (Lua)

## Transformations

*   [json-sharp (⭐6)](https://github.com/globocom/json-sharp) - Javascript tool to process operations on pure JSON objects. (Javascript)
*   [json2json (⭐188)](https://github.com/joelvh/json2json) - Transform (reformat) structures from one to another. (Javascript)
*   [trans (⭐177)](https://github.com/gabesoft/trans) - The ultimate object transformer. (Javascript)
*   [osmtogeojson (⭐661)](https://github.com/tyrasd/osmtogeojson) - Converts OSM data to GeoJSON. (Javascript)
*   [fast-xml-parser (⭐2.3k)](https://github.com/NaturalIntelligence/fast-xml-parser) - Fast XML to JSON and vice versa javascript/JSON conversion.
*   [x2js (⭐991)](https://github.com/abdolence/x2js) - XML to JSON and vice versa javascript conversion functions. (Javascript)
*   [JSONC (⭐645)](https://github.com/tcorral/JSONC) - JSON compressor and decompressor. (Javascript)
*   [JsonMapper (⭐1.5k)](https://github.com/cweiske/jsonmapper) - Map nested structures onto PHP classes (PHP)
*   [SassyJSON (⭐169)](https://github.com/KittyGiraudel/SassyJSON) - Sass-powered API. (Sass)
*   [json.human.js](http://marianoguerra.github.io/json.human.js/) - A small library to convert a JSON object into a human readable HTML representation that is easy to style for different purposes.
*   [JSONtoFoundation (⭐42)](https://github.com/fmscode/JSONtoFoundation) - OS X utility that converts a JSON object to a Foundation object that can be used in Cocoa/Cocoa Touch development. (Swift)
*   [fanci (⭐30)](https://github.com/liip/fanci) - Extract, rename and transform JSON based on a template. (node.js)
*   [Pinch (⭐27)](https://github.com/Baggz/Pinch) - String.replace for JavaScript objects. (Javascript)
*   [deepjson](http://deepjson.jacoborus.codes/) - A better way to load big json config files. (node.js)
*   [jsontl (⭐7)](https://github.com/DoublePrecisionSoftware/jsontl) - allow transformation using a JSON-based transformation language. (node.js)
*   [json-transforms (⭐136)](https://github.com/ColinEberhardt/json-transforms) - A recursive, pattern-matching, approach to transforming JSON structures.
*   [normalizr (⭐21k)](https://github.com/paularmstrong/normalizr) - Normalizes nested JSON according to a schema. (Javascript)
*   [JSON-populate (⭐152)](https://github.com/eiriklv/json-populate) - Tool for populating JSON data with infinitely recursive circular references. Sort of like Falcor, but for plain JSON.
*   [CircularJSON (⭐601)](https://github.com/WebReflection/circular-json) - JSON does not handle circular references. Now it does.
*   [Sawmill (⭐109)](https://github.com/logzio/sawmill) - JSON transformation library (Java)
*   [nimnjs (⭐45)](https://github.com/NaturalIntelligence/nimnjs) - JSON to nimn bidirectional converter.
*   [stylops (⭐0)](https://github.com/cruel-intentions/stylops) - CSS subset to JSON conversion. (node.js)

## Queries

*   [dasel (⭐4.7k)](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to [jq (⭐28k)](https://github.com/jqlang/jq) / [yq (⭐2.4k)](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
*   [JMESPath](https://jmespath.org/) - A query language for JSON.
*   [JSON Mask (⭐859)](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. (Javascript)
*   [JSONiq](https://www.jsoniq.org/) - The JSON Query Language.
*   [ObjectPath](https://objectpath.org/) - The agile query language for semi-structured data. (Python)
*   [DefiantJS](https://www.defiantjs.com/) - Lightning-fast searches using XPath expressions, and transform using XSL. (Javascript)
*   [JSONSelect (⭐1.6k)](https://github.com/lloyd/JSONSelect) - CSS-like selectors. (Javascript)
*   [JSONPath](https://goessner.net/articles/JsonPath/) - XPath implementation. (Javascript/PHP)
*   [searchjs (⭐307)](https://github.com/deitch/searchjs) - A library for filtering based on a json SQL-like language.
*   [json-rel (⭐16)](https://github.com/slurmulon/json-where) - Transparent references in JSON.
*   [JSONata](https://jsonata.org/) - Query and transformation language used in Node-RED, supports function expressions.

## JSON Schema Frontend components

*   [JSON Editor (⭐5.8k)](https://github.com/jdorn/json-editor) - JSON Schema Based Editor. (jQuery)
*   [angular-schema-form (⭐2.5k)](https://github.com/json-schema-form/angular-schema-form) - Generate forms. (AngularJS)
*   [JSON Schema View (⭐50)](https://github.com/mohsen1/json-schema-view) - An AngularJS directive for rendering JSON Schema in HTML (AngularJS)
*   [Angular JSON Schema Form (⭐30)](https://github.com/mohsen1/angular-json-schema-form) - Angular directive for making forms out of JSON Schema. (AngularJS)
*   [AlpacaJS](http://www.alpacajs.org) - Generates JSON Schema driven forms on top of Bootstrap, jQuery Mobile, jQuery UI and HTML (jQuery)

## JSON Schema Tools

*   [prmd (⭐2.1k)](https://github.com/interagent/prmd) - Tools and doc generation for HTTP APIs.
*   [generate-schema (⭐1k)](https://github.com/Nijikokun/generate-schema) - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart.
*   [Docson (⭐491)](https://github.com/lbovet/docson) - Documentation for your types.
*   [Orderly JSON (⭐219)](https://github.com/lloyd/orderly) - A textual format for describing JSON compiled into JSONSchema.
*   [jsonschema2pojo (⭐6.1k)](https://github.com/joelittlejohn/jsonschema2pojo) - Generates Java types and annotates those types for data-binding with Jackson 1.x or 2.x, Gson, etc.
*   [Matic (⭐174)](https://github.com/mattyod/matic) - Build tool for generating HTML documentation.
*   [JSON Schema + Faker (⭐3.2k)](https://github.com/json-schema-faker/json-schema-faker) - Fake your schemas.
*   [DLL.js (⭐67)](https://github.com/moll/js-ddl) - Gets you a JSON Schema from PostgreSQL or SQLite3.
*   [JSONSchema.net](https://jsonschema.net//) - JSON Schema generator from JSON object.
*   [js-schema (⭐387)](https://github.com/molnarg/js-schema) - A new way of describing object schemas in JavaScript. It has a clean and simple syntax, and it is capable of serializing to/from the popular JSON Schema format.
*   [aptos (⭐150)](https://github.com/pennsignals/aptos) - A tool for validating data using JSON Schema and converting JSON Schema documents into different data-interchange formats.
*   [JSON Schema $Ref Parser (⭐878)](https://github.com/APIDevTools/json-schema-ref-parser) - Parse, resolve, and dereference JSON Schema $ref pointers

## JSON Schema Resources

*   [Understanding JSON Schema](https://spacetelescope.github.io/understanding-json-schema/) - A website aiming to provide more accessible documentation for JSON schema.
*   [JSON Schema Store](https://www.schemastore.org/json/) - A collection of popular schemas.
*   [Using JSON Schema](http://usingjsonschema.com/) - a Book and GitHub project, showing how JSON Schema can be used for a variety of tasks and in different programming contexts.
*   [Awesome JSON Schema (⭐91)](https://github.com/sourcemeta/awesome-jsonschema) - A curated list of awesome JSON Schema resources, tutorials, tools, and more.

## JSON Schema Validators

**Javascript and Node.js**

*   [json-schema-benchmark (⭐380)](https://github.com/ebdrup/json-schema-benchmark) - Performance benchmark for Node.js validators.
*   [is-my-json-valid (⭐955)](https://github.com/mafintosh/is-my-json-valid) - A validator that uses code generation to be extremely fast.
*   [jsen (⭐156)](https://github.com/bugventure/jsen) - A validator built for speed.
*   [themis (⭐60)](https://github.com/playlyfe/themis) - A blazing fast validator.
*   [jsck (⭐158)](https://github.com/pandastrike/jsck) - JSON Schema Compiled checK.
*   [z-schema (⭐338)](https://github.com/zaggino/z-schema) - validator written in JavaScript for NodeJS and Browsers.
*   [jjv (⭐196)](https://github.com/acornejo/jjv) - Javascript Library for Schema Validation.
*   [request-validator (⭐0)](https://github.com/bugventure/request-validator) - Flexible request validator middleware for express and connect.
*   [tv4 (⭐1.2k)](https://github.com/geraintluff/tv4) - Tiny Validator.
*   [ajv (⭐13k)](https://github.com/ajv-validator/ajv) - The fastest validator. Supports v5/6 proposals.

**Java and Kotlin**

*   [Medeia Validator (⭐57)](https://github.com/worldturner/medeia-validator) - Compliant (draft-04/06/07) and fast streaming validator written in Kotlin

**PHP**

*   [JSON Schema for PHP (⭐3.5k)](https://github.com/justinrainbow/json-schema) - PHP implementation of JSON schema.
*   [JSON Guard](https://json-guard.thephpleague.com) - A validator for JSON Schema Draft 4.

**Python**

*   [jsonschema (⭐4.4k)](https://github.com/python-jsonschema/jsonschema) - Python implementation of jsonschema.
*   [JSON Schema Toolkit (⭐30)](https://github.com/petrounias/json-schema-toolkit) - Programmatic building of JSON schemas (recursive field mappings) with validation, a Django JSON Field, and native PostgreSQL JSON type constraints.

**Ruby**

*   [Ruby JSON Schema Validator (⭐1.5k)](https://github.com/voxpupuli/json-schema) - validating against a JSON schema conforming to JSON Schema Draft 4.

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/burningtree/awesome-json/blob/master/README.md/CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

