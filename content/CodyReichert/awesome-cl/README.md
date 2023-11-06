# Track Awesome Cl Updates Daily

A curated list of awesome Common Lisp frameworks, libraries and other shiny stuff.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/CodyReichert/awesome-cl/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 CodyReichert/awesome-cl](https://github.com/CodyReichert/awesome-cl) · ⭐ 2.3K · 🏷️ Programming Languages

[ Daily / [Weekly](/content/CodyReichert/awesome-cl/week/README.md) / [Overview](/content/CodyReichert/awesome-cl/readme/README.md) ]

## [Nov 06, 2023](/content/2023/11/06/README.md)

### Graph databases

*   [neo4cl](https://codeberg.org/Equill/neo4cl) - a library for interacting with Neo4J. Sends Cypher queries to a Neo4J server, and decodes the responses into something useful for processing in CL. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0).
    *   and maybe: [cl-neo4j (⭐26)](https://github.com/kraison/cl-neo4j) - a thin neo4j RESTFUL client interface.

### Iteration

*   [cl-transducers](https://git.sr.ht/~fosskers/cl-transducers) - Ergonomic, efficient data processing. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).
    *   "Transducers are an ergonomic and extremely memory-efficient way to process a data source. Here “data source” means simple collections like Lists or Vectors, but also potentially large files or generators of infinite data."
    *   "It is, in general, the most complete implementation of the Transducer pattern."
    *   a "modern" API with `map`, `filter`, `take`, `repeat`, `cycle`, `fold`…

## [Oct 29, 2023](/content/2023/10/29/README.md)

### Deployment / Isomorphic web frameworks

*   [Cloud Init file for SBCL](https://git.sr.ht/%7Emarcuskammer/cloudinit/tree/main/item/sbcl-nginx.yml) - an init file for providers supporting the cloudinit format (DigitalOcean etc).

## [Oct 17, 2023](/content/2023/10/17/README.md)

### Utils / Third-party APIs

*   ⭐ [lparallel (⭐9)](https://github.com/sharplispers/lparallel) - A library for parallel programming. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause). Originally on [lmj/lparallel (⭐235)](https://github.com/lmj/lparallel).

## [Sep 18, 2023](/content/2023/09/18/README.md)

### Community / Interfaces to other package managers

*   [asdf-sbcl (⭐19)](https://github.com/smashedtoatoms/asdf-sbcl), a plugin for the universal package manager.
*   📹 [this Youtube video](https://www.youtube.com/watch?v=lGS4sr6AzKw) (by 40ants, 2023) on how to use alien-works-delivery and linux-packaging.

## [Sep 12, 2023](/content/2023/09/12/README.md)

### Miscellaneous

*   [cl-raylib (⭐10)](https://github.com/bohonghuang/claw-raylib) NEW in 2023 - fully auto-generated Common Lisp bindings to Raylib and Raygui using claw and cffi-object. Apache 2.0.
*   [glfw (⭐12)](https://github.com/shirakumo/glfw) NEW in 2023 - An up-to-date Common Lisp bindings library to the most recent GLFW OpenGL context management library.

## [Sep 05, 2023](/content/2023/09/05/README.md)

### Mobile

*   [NJSON (⭐11)](https://github.com/atlas-engineer/njson) - Parser-agnostic JSON indexing (with JSON Pointer support), destructuring, and validation framework. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### CLOS extensions

*   [nclasses (⭐2)](https://github.com/atlas-engineer/nclasses) - Syntactic sugar for class and generic function declarations. Fork of [hu.dwim.defclass-star (⭐5)](https://github.com/hu-dwim/hu.dwim.defclass-star). Features type inference, automatic accessors, inline initform syntax, automatic exports, and other conveniences. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Files and directories / Third-party APIs

*   [nfiles (⭐12)](https://github.com/atlas-engineer/nfiles) - File persistence, watching, data synchronization, (per user profile) path resolution, and structured data retrieval. Has pre-defined classes for configuration files, remote fetched files, data files, Lisp-readable files and many others. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Aug 30, 2023](/content/2023/08/30/README.md)

### C, C++

*   NEW [endatabas (⭐47)](https://github.com/endatabas/endb) - Schemaless SQL document database with full history. [AGPL-3.0](https://directory.fsf.org/wiki/License:Apache2.0).
    *   built in Common Lisp and Rust.
    *   in development, alpha product scheduled for Q2 of 2024. [roadmap](https://docs.endatabas.com/appendix/roadmap.html).

## [Jul 06, 2023](/content/2023/07/06/README.md)

### Reference

*   NEW! [CL CommunitySpec](https://cl-community-spec.github.io/pages/index.html) - a rendition of the Common Lisp ANSI Specification draft.
    *   with an interactive search, syntax highlighting! And open-source.
*   NEW! [novaspec](https://novaspec.org/) - a modern rendition of the CL ANSI draft.
    *   not open-source?

## [Jul 05, 2023](/content/2023/07/05/README.md)

### Mobile

*   [cl-jwk (⭐17)](https://github.com/dnaeon/cl-jwk) -  Common Lisp system for decoding public JSON Web Keys (JWK). BSD License.

## [Jun 16, 2023](/content/2023/06/16/README.md)

### C, C++

*   [cl-frugal-uuid (⭐13)](https://github.com/ak-coram/cl-frugal-uuid/) -  Common Lisp UUID library with zero dependencies. [MIT](https://opensource.org/licenses/MIT).

### Wrappers

*   [cl-duckdb (⭐23)](https://github.com/ak-coram/cl-duckdb) -  Common Lisp CFFI wrapper around the DuckDB C API. [MIT](https://opensource.org/licenses/MIT).

### Tools

*   [archlinux-cl (⭐3)](https://github.com/yitzchak/archlinux-cl) - Docker Arch Linux image with Common Lisp implementations (7 to this day). MIT.

### Miscellaneous

*   [CEDAR](https://gitlab.com/sasanidas/cedar) - an advance interactive development environment aiming to be Emacs compatible with all the features that come with it. (WIP)

### Reactive programming

*   [lwcells (⭐17)](https://github.com/kchanqvq/lwcells) - Light Weight Cells.
    *   LWCELLS is a dataflow extension to Common Lisp. It maintains a consistent state of cells according to functions specifying their relation. LWCELLS is designed to be simple, clean, compositional and flexible.

### Shells, shells interfaces / Third-party APIs

*   [unix-in-lisp (⭐96)](https://github.com/PuellaeMagicae/unix-in-lisp) -  Mount Unix system into Common Lisp image.
    *   Unix concepts are directly/shallowly embedded into Lisp (Unix commands become Lisp macros, Unix file become Lisp variables, Unix streams become lazy Lisp sequences, etc).

## [May 27, 2023](/content/2023/05/27/README.md)

### Miscellaneous

*   [nodgui](https://notabug.org/cage/nodgui) - Bindings for the Tk toolkit, based on Ltk, with syntax sugar and additional widgets. [LLGPL](http://opensource.franz.com/preamble.html).
    *   🎨 supports [tk custom themes](https://wiki.tcl-lang.org/page/List+of+ttk+Themes), such as [ttkthemes](https://ttkthemes.readthedocs.io/en/latest/themes.html) and [Forest-ttk-theme (⭐228)](https://github.com/rdbende/Forest-ttk-theme).

### Deployment / Isomorphic web frameworks

*   [common-lisp-heroku-example (⭐5)](https://github.com/fstamour/common-lisp-heroku-example) -  Example of Common Lisp server on Heroku using Docker.

## [May 26, 2023](/content/2023/05/26/README.md)

### C, C++

*   [gpgme](https://www.gnupg.org/download/index.en.html#gpgme) (GnuPG Made Easy) is the standard library to access GnuPG functions from programming languages. It provides an official Common Lisp system.
    *   [gpgme lisp sources](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpgme.git;a=tree;f=lang/cl;h=05151bdf839e513f534a1b423d59332a2e46fd5d;hb=HEAD) (not in Quicklisp). GPL2.

### Community

*   (NEW! as of May, 2023) [ocicl (⭐93)](https://github.com/ocicl/ocicl) - a new and experimental alternative to Quicklisp, built on tools from the world of containers. [MIT](https://opensource.org/licenses/MIT).

### HTTP clients / Interfaces to other package managers

*   [http2 (⭐30)](https://github.com/zellerin/http2/) -  HTTP/2 implementation in Common Lisp. [MIT](https://opensource.org/licenses/MIT).

### Lem / Third-party APIs

*   [Lem (⭐1.8k)](https://github.com/lem-project/lem) - a ready to use, Emacs-like, Slime-based
    editor tailored for Common Lisp development out of the box, as well as other programming languages with its built-in LSP client. With ncurses, Electron and SDL2 interfaces. [MIT](https://opensource.org/licenses/MIT).
    *   [Lem 2.0](https://github.com/lem-project/lem/releases/tag/v2.0.0), released on May, 2023, added the SDL2 frontend, thus mouse support, graphic capabilities and Windows support, among other new features.
    *   see also: an [opengl frontend (⭐36)](https://github.com/pupcraft/lem-opengl), [Lem in Docker (⭐4)](https://github.com/40ants/lem-docker), [lem-pareto (⭐31)](https://github.com/40ants/lem-pareto).

## [Apr 19, 2023](/content/2023/04/19/README.md)

### Theorem provers

*   [ACL2](https://www.cs.utexas.edu/users/moore/acl2/) - a logic and programming language in which you can model computer systems, together with a tool to help you prove properties of those models.
    *   used in the industry since the 1990s.
    *   it supports a subset of the ANSI standard Common Lisp programming language.
    *   "Companies that have used ACL2 regularly include AMD, Centaur Technology, IBM, Intel, Kestrel Institute, Motorola/Freescale, Oracle and Rockwell Collins." ([source](https://royalsocietypublishing.org/doi/10.1098/rsta.2015.0399))
    *   [Proofpad (⭐6)](https://github.com/calebegg/proof-pad/), an online IDE for ACL2.
    *   [ACL2 Sedan](http://acl2s.ccs.neu.edu/acl2s/doc/), an Eclipse plugin that provides a modern IDE for ACL2, used with students at universities.
        *   paper: [Using ACL2 to teach students about software testing](https://cgi.cse.unsw.edu.au/~eptcs/content.cgi?ACL22022).

### Others / Third-party APIs

*   [cl-telegram-bot](https://40ants.com/cl-telegram-bot/) - Telegram bot API. [MIT](https://opensource.org/licenses/MIT).
    *   [cl-telegram-bot-auto-api (⭐5)](https://github.com/aartaka/cl-telegram-bot-auto-api) - Alternative Telegram Bot API bindings, auto-generated from Telegram website. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Apr 12, 2023](/content/2023/04/12/README.md)

### Python

*   [py4cl2-cffi (⭐28)](https://github.com/digikar99/py4cl2-cffi) - CFFI based alternative to py4cl2.
    *   "When capable, the CFFI approach can be a 50 times faster than py4cl2."

### Others / OpenAPI, OData, OpenRPC

*   [openapi-generator](https://codeberg.org/kilianmh/openapi-generator) - OpenAPI client code generator. [AGPL-3.0](https://directory.fsf.org/wiki/License:ArtisticLicense2.0).
    *   Generation of OpenAPI ASDF/Quicklisp-loadable projects within one command,
    *   Support for path, (arbitrary) query, (arbitrary) header, (json) content parameters,
    *   Conversion of an OpenAPI spec into CLOS object -> explore API within inspector,
    *   Conversion of OpenAPI-2.0 or YAML files to OpenAPI-3.0 JSON with swagger converter (network connection required),
    *   etc.

### Date and time / Third-party APIs

*   [stopclock](https://github.com/Gleefre/stopclock) - a library for measuring time using (stop)clocks. It allows you to create a clock, pause it, resume it and change its speed. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

## [Mar 09, 2023](/content/2023/03/09/README.md)

### Utils / Third-party APIs

*   [Blackbird](https://orthecreedence.github.io/blackbird/) - a Promise implementation for Common Lisp [MIT](https://opensource.org/licenses/MIT).
    *   see also [promise (⭐11)](https://github.com/Shinmera/promise) - a basic promise datastructure, with timeouts. ZLIB.

## [Feb 27, 2023](/content/2023/02/27/README.md)

### Community

*   👍 [CLPM](https://www.clpm.dev) - A package manager for Common Lisp that strives to cleanly separate the package manager process itself from the client image that uses it. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
    *   CLPM comes as a pre-built binary, supports HTTPS by default, supports installing multiple package versions, supports versioned systems, and more.
*   [Quickutil (⭐85)](https://github.com/stylewarning/quickutil) - A utility manager, similar to Quicklisp, but for small utilities rather than whole libraries. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [redist (⭐9)](https://github.com/shirakumo/redist) - facilities to produce Quicklisp distributions.

## [Feb 21, 2023](/content/2023/02/21/README.md)

### Mobile

*   👍 [jzon (⭐115)](https://github.com/Zulu-Inuoe/jzon/) - a correct, safe and fast JSON parser. [MIT](https://opensource.org/licenses/MIT).
    *   jzon is the only CL JSON library which correctly declines all invalid inputs per the official JSON test suite and accepts all valid inputs per that suite.
    *   it doesn't crash on invalid input (jsown), doesn't choke on large datasets (Jonathan), and more.
    *   v1.0 released in the Quicklisp dist of February, 2023.
    *   "I believe jzon to be the superior choice and hope for it to become the new, true de-facto library in the world of JSON-in-CL once and for all."

### Community

*   [asdf-dependency-graph (⭐8)](https://github.com/digikar99/asdf-dependency-graph/) - A minimal wrapper around `dot` to generate an image of the dependencies graph.

### Others / Third-party APIs

*   [aws-sdk-lisp (⭐82)](https://github.com/pokepay/aws-sdk-lisp/) - Provides interfaces for each AWS services as individual systems. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
    *   incluse dozens of services: dsn, appstream, athena, cloudfront, codedeploy, cognito-\*, directconnect, dynamodb, dms, elasticache, email, events, kinesis, machinelearning, monitoring, s3, sms, storagegateway, workspaces…

### CSV / Third-party APIs

*   [csv-validator (⭐3)](https://github.com/KoenvdBerg/csv-validator) - Validates tabular CSV data using predefined validations, inspired from its Python homologue "Great Expectations". [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Feb 19, 2023](/content/2023/02/19/README.md)

### Data validation / Third-party APIs

*   [cl-semver (⭐12)](https://github.com/cldm/cl-semver) - Implementation of the [Semantic Versioning](https://semver.org) Specification. [MIT](https://opensource.org/licenses/MIT)

## [Feb 06, 2023](/content/2023/02/06/README.md)

### Miscellaneous

*   [CLOCC's elisp.lisp](https://sourceforge.net/p/clocc/hg/ci/default/tree/src/cllib/elisp.lisp) - Emacs Lisp in Common Lisp.
    *   implementation of the Emacs Lisp language as a Common Lisp package. \[1999]
    *   does not attempt to reimplement the library of functions provided in Emacs to manipulate buffers and other related objects, so it focuses on the "pure" Emacs Lisp language; but it was able to run the non-UI parts of the Emacs Calendar. (S. Monnier, M. Sperber)

### System administration / Third-party APIs

*   [cl-unix-cybernetics (⭐179)](https://github.com/cl-unix-cybernetics/cl-unix-cybernetics) (previously Adams) - UNIX system administration in Common Lisp. Not unlike Ansible, Chef or Puppet. [ISC](https://en.wikipedia.org/wiki/ISC_license).
    *   You describe your systems (hosts) using resources having properties. The properties are then probed and synchronized using only /bin/sh on the remote host, and /usr/bin/ssh on the control host.

## [Jan 23, 2023](/content/2023/01/23/README.md)

### Documentation builders / Third-party APIs

*   [sphinxcontrib-cldomain](https://sphinxcontrib-cldomain.russellsim.org/) -
    Extending Sphinx to cover Common Lisp. To build documentation with
    the same ease as sphinx would a Python project. [GPL3](http://www.gnu.org/copyleft/gpl.html)

### Git / Third-party APIs

*   [cl-git](https://cl-git.russellsim.org/) - a CFFI interface to the libgit2 library. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

## [Jan 18, 2023](/content/2023/01/18/README.md)

### JetBrains / Third-party APIs

*   [SLT](https://github.com/Enerccio/SLT) -  an IDE Plugin for Itellij/Jetbrains IDE lineup implementing support for Common Lisp via SBCL and Slime/Swank.
    *   🎉 NEW! Released in Jan, 2023.

## [Jan 17, 2023](/content/2023/01/17/README.md)

### Mobile

*   [hu.dwim.walker (⭐4)](https://github.com/hu-dwim/hu.dwim.walker) - a code walker and unwalker (aka AST parser and unparser). [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause). See also [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

## [Dec 31, 2022](/content/2022/12/31/README.md)

### Actors pattern / Third-party APIs

*   [lisp-actors (⭐63)](https://github.com/dbmcclain/Lisp-Actors), an "ongoing investigation into the use of the Actor model in Common Lisp, which has had the benefit of real-world application".
    *   it was part of the [Emotiq blockchain (⭐96)](https://github.com/emotiq/emotiq/blob/dev/src/test/blockchain-test.lisp) (a discontinued project)
    *   does remoting, includes a threading abstraction layer library similar to Bordeaux-Threads.
    *   ! it lacks unit tests.

### Online editors / Third-party APIs

*   [Riju](https://riju.codes/commonlisp), a "fast online playground for every programming language", supports Common Lisp (SBCL).

## [Dec 28, 2022](/content/2022/12/28/README.md)

### Community / Interfaces to other package managers

*   [alien-works-delivery (⭐32)](https://github.com/borodust/alien-works-delivery) - WIP system for delivering Common Lisp applications as executable bundles. For now it only supports AppImage format for Linux and MSIX for Windows, but .APK for Android and later MacOSX and iOS bundle formats are planned too.

## [Dec 13, 2022](/content/2022/12/13/README.md)

### Tools

*   [bit-smasher (⭐48)](https://github.com/thephoeron/bit-smasher) -  Common Lisp library for handling bit vectors, bit vector arithmetic, and type conversions. [MIT](https://opensource.org/licenses/MIT).

### Mobile

*   [shasht (⭐40)](https://github.com/yitzchak/shasht) -  Common Lisp JSON reading and writing for the Kzinti. [MIT](https://directory.fsf.org/wiki/License:Expat).
    *   " Shasht is one of the two new libraries that I particularly like and is already in quicklisp. It is fast, it handles null correctly, it encodes CLOS objects, structures and hash-tables. It can also do incremental encoding." Sabra Crolleton.

## [Nov 25, 2022](/content/2022/11/25/README.md)

### Others / Third-party APIs

*   [Ciao (⭐20)](https://github.com/kjinho/ciao) - an easy-to-use Common Lisp OAuth 2.0 client library. It is a port of the Racket OAuth 2.0 Client to Common Lisp. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

## [Nov 23, 2022](/content/2022/11/23/README.md)

### Miscellaneous

*   [Xelf](https://gitlab.com/dto/xelf/) - Extensible game library. Not available on Quicklisp. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).

### Iteration

*   [series](https://series.sourceforge.net/) - Functional style without any runtime penalty at all. [MIT](https://opensource.org/licenses/MIT).
*   [gtwiwtg](https://cicadas.surf/cgit/colin/gtwiwtg.git/about/) - A lazy sequences library. Similar to 'series' but not as complete. However it has a 'modern' API with stuff like `take`, `filter`, `for`, `fold`, etc. that is easy to use.

### Javascript / Isomorphic web frameworks

*   [Valtan (⭐206)](https://github.com/cxxxr/valtan) -  Common Lisp to JavaScript compiler.
*   [JACL](https://tailrecursion.com/JACL/) - an experimental Lisp system for the Web browser platform to explore new techniques for developing large Single Page Applications with Lisp.

### Others / Email

*   [sendgrid (⭐14)](https://github.com/vindarel/cl-sendgrid) - send emails with Sendgrid's API. [MIT](https://opensource.org/licenses/MIT).

### Actors pattern / Third-party APIs

*   👍 [Sento (⭐166)](https://github.com/mdbergmann/cl-gserver) - Sento (formerly cl-gserver) is a 'message passing' library/framework with actors similar to Erlang or Akka. It supports creating systems that should work reactive, require parallel computing and event based message handling. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0).

### Caching / Third-party APIs

*   [function-cache (⭐47)](https://github.com/AccelerationNet/function-cache) -  A Common Lisp function caching / memoization library. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Nov 17, 2022](/content/2022/11/17/README.md)

### Clojure

*   [Cloture (⭐356)](https://github.com/ruricolist/cloture) - Clojure in Common Lisp.
*   [cl-oju (⭐16)](https://github.com/eigenhombre/cl-oju/) - a few idioms, mostly relating to sequences, that I miss when writing Common Lisp. [MIT](https://opensource.org/licenses/MIT).
*   [clj-con (⭐21)](https://github.com/dtenny/clj-con) - Clojure-style concurrency operations in Common Lisp. [MIT](https://opensource.org/licenses/MIT).
*   [clj-re (⭐7)](https://github.com/dtenny/clj-re/) - Clojure-style regular expression functions.

### Typing

*   [typo (⭐33)](https://github.com/marcoheisig/Typo/) -  A portable type inference library for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

### Others / OpenAPI, OData, OpenRPC

*   [OpenRPC (⭐24)](https://github.com/40ants/openrpc) - OpenRPC implementation for Common Lisp. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   Automatic OpenRPC spec generation
    *   Automatic JSON-RPC client building by OpenRPC spec. This includes creation of Common Lisp classes and methods for making RPC requests and returning native CL objects.
    *   all JSON marshalling is done under the hood.

### Apps / Third-party APIs

*   [trivial-sanitize](https://notabug.org/cage/trivial-sanitize) -  clean html strings: `"<a>foo</a>"` → `"foo"`. [LLGPL](http://opensource.franz.com/preamble.html).
*   [testieren](https://cicadas.surf/cgit/colin/testiere.git/about/) - a testing utility where tests are included at the top of a `defun/t` form. They are run when you recompile your functions interactively. With mocking and stubbing support. [GPL3](http://www.gnu.org/copyleft/gpl.html).

### Macro helpers / Third-party APIs

*   [easy-macros (⭐18)](https://github.com/tdrhq/easy-macros/) -  an easy way to write 90% of your macros. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

## [Nov 02, 2022](/content/2022/11/02/README.md)

### Wrappers

*   [cl-ndbapi (⭐12)](https://github.com/datagraph/cl-ndbapi) - bindings to the C++ NDB API of [RonDB](https://www.rondb.com/), "the world's fastest key value store", by [Dydra](https://dydra.com/home). GPLv2.

## [Oct 24, 2022](/content/2022/10/24/README.md)

### Others / Third-party APIs

*   [lisp-pay (⭐22)](https://github.com/K1D77A/lisp-pay) - Wrappers around various payment processors: Paypal, Stripe, Coinpayments and BTCPayServer. [MIT](https://opensource.org/licenses/MIT).
*   [lunamech-matrix-api (⭐6)](https://github.com/K1D77A/lunamech-matrix-api) - A complete wrapper over the Client -> Server Matrix API. [MIT](https://opensource.org/licenses/MIT).

## [Oct 22, 2022](/content/2022/10/22/README.md)

### Notebooks / Third-party APIs

*   [common-lisp-jupyter (⭐191)](https://github.com/yitzchak/common-lisp-jupyter) - A Common Lisp kernel for Jupyter along with a library for building Jupyter kernels, based on Maxima-Jupyter by Robert Dodier which was based on cl-jupyter by Frederic Peschanski. [MIT](https://opensource.org/licenses/MIT).
    *   [jupyterlab-debugger-restarts (⭐2)](https://github.com/yitzchak/jupyterlab-debugger-restarts) - restart functionality for the JupyterLab debugger.
    *   [Cytoscape widget (⭐1)](https://github.com/yitzchak/cytoscape-clj) -  Cytoscape.js widget for common-lisp-jupyter.
    *   [Kekule widget (⭐1)](https://github.com/yitzchak/kekule-clj) -  Kekule.js widget for common-lisp-jupyter.
    *   [molecule viewer (⭐0)](https://github.com/yitzchak/jupyterlab-molviewer) - A molecule viewer for JupyterLab using ngl.
    *   [ngl widget (⭐1)](https://github.com/yitzchak/ngl-clj) -  A ngl widget (protein viewer) for common-lisp-jupyter.
    *   [sheet widget (⭐1)](https://github.com/yitzchak/sheet-clj) -  Data grid widget for common-lisp-jupyter.
*   [cl-jupyter (⭐198)](https://github.com/fredokun/cl-jupyter) - A Common Lisp kernel for Jupyter notebooks [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).

## [Oct 06, 2022](/content/2022/10/06/README.md)

### Mobile

*   [GNU CLISP](http://www.clisp.org/) - A GNU implementation; contains a compiler and an interpreter. [Standard conformance](http://www.gnu.org/software/clisp/impnotes.html). [GNU GPL3](http://www.gnu.org/copyleft/gpl.html). They develop [on Gitlab](https://gitlab.com/gnu-clisp/clisp).
    *   compiles to bytecode, its default REPL is more user friendly than SBCL's (with symbol completion and readline integration).
    *   however, it is not actively developed, it doesn't comply entirely to the ANSI standard, it is less performant than SBCL and it is lacking compatibility features.

## [Sep 24, 2022](/content/2022/09/24/README.md)

### Others / OpenAPI, OData, OpenRPC

*   [apispec (⭐31)](https://github.com/cxxxr/apispec) -  A Common Lisp library for handling Web API requests and responses. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   takes an OpenAPI3 yaml specification and allows to validate and parse HTTP request headers, parameters and bodies.

## [Sep 19, 2022](/content/2022/09/19/README.md)

### Miscellaneous

*   🆕 [cl-gtk4 (⭐182)](https://github.com/bohonghuang/cl-gtk4) -  GTK4/Libadwaita/WebKit binding for Common Lisp. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

## [Sep 07, 2022](/content/2022/09/07/README.md)

### Files and directories / Third-party APIs

*   [file-notify (⭐22)](https://github.com/shinmera/file-notify) - a cross-platform library for file change detection. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Sep 02, 2022](/content/2022/09/02/README.md)

### Miscellaneous

*   [ceramic](https://ceramic.github.io/) - Desktop web apps with Electron. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   [Electron-lisp-boilerplate (⭐5)](https://github.com/mikelevins/electron-lisp-boilerplate) - A rudimentary boilerplate for building Electron apps with embedded Lisp helper processes.
    *   Electron app skeleton: [electron-sbcl-sqlite (⭐27)](https://github.com/mikelevins/electron-sbcl-sqlite/)
    *   NOTE: the main idea in embedding a lisp web app in Electron is to start the lisp webserver as an async process and to point the Electron window to the localhost URL. That's it.

## [Aug 22, 2022](/content/2022/08/22/README.md)

### Coding platforms

*   [Codewars](https://docs.codewars.com/languages/commonlisp/) - a code training platform, with Common Lisp support (SBCL).

### HTML generators and templates / Isomorphic web frameworks

*   ⭐ [Djula (⭐139)](https://github.com/mmontone/djula) - A port of Django's template engine to Common Lisp. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   [cl-djula-tailwind (⭐8)](https://github.com/rajasegar/cl-djula-tailwind) - use TailwindCSS classe in your Djula templates without any JavaScript or Node.js tooling.

### Apps / Third-party APIs

*   [Resolve](https://github.com/GrammaTech/resolve) - A software for AST-based diff calculation, display, and automated resolution. Written in C++ and CL, you'll find Lisp utilities.

## [Aug 02, 2022](/content/2022/08/02/README.md)

### Others / Third-party APIs

*   ⭐ [maxima](http://maxima.sourceforge.net/) - Computer Algebra System. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html).
    *   [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/): a graphical frontend.
    *   [Maxima on Android](https://play.google.com/store/apps/details?id=jp.yhonda), built with ECL.
    *   [Maxima on Jupyter (⭐173)](https://github.com/robert-dodier/maxima-jupyter)
    *   it can be used via [SageMath](https://www.sagemath.org/) and [KDE Cantor](https://apps.kde.org/cantor/). Of course, with Emacs: [maxima-mode](https://gitlab.com/sasanidas/maxima) ([screenshot](https://community.linuxmint.com/img/screenshots/maxima-emacs.png)) and [maxima-interface (⭐13)](https://github.com/jmbr/maxima-interface) to ease the interface between Maxima and Common Lisp.
    *   it can be used [from a Lisp REPL](https://mahmoodsheikh36.github.io/post/20230510181916-maxima_in_lisp/).

### Documentation builders / Third-party APIs

*   [cl-livedocs (⭐2)](https://github.com/mmontone/cl-livedocs) - similar and newer, based on Webinfo, with full text search enabled by default.

## [Jul 30, 2022](/content/2022/07/30/README.md)

### Websockets / Isomorphic web frameworks

*   [clws (⭐71)](https://github.com/3b/clws) -  websockets server in CL, built on IOlib and libfixposix. No licence specified.
*   [Hunchensocket (⭐105)](https://github.com/joaotavora/hunchensocket) -  RFC6455 compliant WebSockets for Common Lisp, as an extension to Hunchentoot. [MIT](https://opensource.org/licenses/MIT).
*   [websocket-driver (⭐97)](https://github.com/fukamachi/websocket-driver) - based on Clack.

## [Jul 18, 2022](/content/2022/07/18/README.md)

### Changing the syntax

*   [clamp (⭐69)](https://github.com/malisper/Clamp) - Arc language's brevity and conciseness to Common Lisp. [Artistic License 2.0](https://directory.fsf.org/wiki/License:ArtisticLicense2.0).
    *   also [arc-compat (⭐11)](https://github.com/g000001/arc-compat) -  Arc compatible package. Perl Foundation's Artistic Licence 2.0.

### Websockets / Isomorphic web frameworks

*   [Portal (⭐27)](https://github.com/charJe/portal) - Portable websockets for Common Lisp, using usocket. [LLGPL](http://opensource.franz.com/preamble.html).

## [Jul 17, 2022](/content/2022/07/17/README.md)

### Function extensions

*   [nhooks (⭐12)](https://github.com/atlas-engineer/nhooks) - an enhanced implementation of hooks (extension points) with crucial improvements.

## [Jul 15, 2022](/content/2022/07/15/README.md)

### ORMs

*   👍 [mito (⭐255)](https://github.com/fukamachi/mito) - An ORM for Common Lisp with migrations, relationships and PostgreSQL support [LLGPL](http://opensource.franz.com/preamble.html).
    *   [mitho-auth (⭐19)](https://github.com/fukamachi/mito-auth), a mixin class for use authorization
    *   [mito-attachment (⭐15)](https://github.com/fukamachi/mito-attachment), a mixin class for file management outside of RDBMS.

### Websockets / Isomorphic web frameworks

*   👍 [usocket (⭐203)](https://github.com/usocket/usocket) - A portable TCP and UDP socket interface. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Web development utilities / Assets management

*   [Rock (⭐45)](https://github.com/eudoxia0/rock) - an asset manager for
    Common Lisp. It's basically a combination of Bower and
    webassets. [MIT](https://opensource.org/licenses/MIT).

### Web development utilities / Browser tests

*   [cl-webdriver-client (⭐17)](https://github.com/copyleft/cl-webdriver-client/) - a binding library to WebDriver (supports Selenium 4.0).

### Web development utilities / Form handling

*   👍 [cl-forms (⭐40)](https://github.com/mmontone/cl-forms) -  Web forms handling library for Common lisp. [MIT](https://opensource.org/licenses/MIT).

### Web development utilities / User login and password management

*   [cl-authentic (⭐6)](https://github.com/charJe/cl-authentic) -  Password management for Common Lisp (web) applications. [LLGPL](http://opensource.franz.com/preamble.html).
    *   safe password storage: cleartext-free, using your choice of hash algorithm through ironclad, storage in an SQL database,
    *   password reset mechanism with one-time tokens (suitable for mailing to users for confirmation),
    *   user creation optionally with confirmation tokens (suitable for mailing to users),
*   [mito-email-auth (⭐4)](https://github.com/40ants/mito-email-auth) - Helper to authenticate a website's users by sending them unique code by email.

### Others / Email

*   [trivial-imap (⭐2)](https://github.com/40ants/trivial-imap) - tries to make easy some common cases of working with IMAP servers, like reading emails from the server. A thin wrapper over post-office library (which is a fork of Franz's cl-imap). [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-smtp](https://gitlab.common-lisp.net/cl-smtp/cl-smtp) - CL-SMTP is a simple lisp smtp client.
*   [mailgun (⭐12)](https://github.com/40ants/mailgun) - A thin wrapper to post HTML emails through mailgun.com. [unlicence](http://unlicense.org/).
*   [cl-ses (⭐15)](https://github.com/CodyReichert/cl-ses/) - Library for AWS SES. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Others / Static site generators

*   [coleslaw (⭐541)](https://github.com/kingcons/coleslaw) and its
    [coleslaw-cli (⭐6)](https://github.com/40ants/coleslaw-cli) - Flexible
    Lisp Blogware similar to Frog, Jekyll, or Hakyll. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Others / Third-party APIs

*   [Aws-sign4 (⭐18)](https://github.com/rotatef/aws-sign4) - Common Lisp library for Amazon Web Services signing version 4. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html).
*   [zs3 (⭐38)](https://github.com/xach/zs3) - A library for working with Amazon's Simple Storage
    Service (S3) and CloudFront service. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [north](https://shinmera.github.io/north) - The successor to the South (Simple OaUTH) library, implementing the full oAuth 1.0a protocol, both client and server sides. Using North you can easily become an oAuth provider or consumer. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [avatar-api (⭐9)](https://github.com/eudoxia0/avatar-api) - Get avatars from Google+, Gravatar and others. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [chirp (⭐70)](https://github.com/Shinmera/chirp) - A Twitter client library. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [tooter (⭐39)](https://github.com/Shinmera/tooter) - a client library implementing the full v1 REST API protocol for Mastodon. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [cl-irc](https://www.common-lisp.net/project/cl-irc/) - An IRC client library. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-mediawiki (⭐19)](https://github.com/AccelerationNet/cl-mediawiki) - a wrapper around the MediaWiki api. [MIT](https://opensource.org/licenses/MIT).
*   [cl-openid (⭐3)](https://github.com/cl-openid/cl-openid) - An implementation of OpenID. [LLGPL](http://opensource.franz.com/preamble.html).
*   [cl-pushover (⭐2)](https://github.com/TeMPOraL/cl-pushover) -  Common Lisp bindings to Pushover. [MIT](https://opensource.org/licenses/MIT).
*   [humbler (⭐10)](https://github.com/Shinmera/humbler) - A Tumblr API interface. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [multiposter (⭐13)](https://github.com/Shinmera/multiposter) - post to multiple services simultaneously. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [stripe](https://git.mfiano.net/mfiano/stripe) - a client for the Stripe payment system. [MIT](https://opensource.org/licenses/MIT).

## [Jul 14, 2022](/content/2022/07/14/README.md)

### Persistent object databases

*   [cl-naive-store](https://gitlab.com/Harag/cl-naive-store) - a naive persisted, in memory (lazy loading), indexed, document store for Common Lisp. [MIT](https://opensource.org/licenses/MIT).
    *   see [the introductory blog post](https://zaries.wordpress.com/2022/05/31/cl-naive-store/)
    *   dare we add: used in production by the author's company (ASTN Group, see awesome-lisp-companies)

### Graph databases

*   [facts](https://github.com/cl-facts/facts) - an in-memory graph database with transactions and rollbacks, logging/replay and dumping/loading to/from disk. BSD-style license (ISC).

### Git / Third-party APIs

*   [git-api (⭐19)](https://github.com/fourier/git-api) - Common Lisp library to access a git repository. It doesn't need git or libgit installed. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Jul 11, 2022](/content/2022/07/11/README.md)

### Mobile

*   ⭐ [SBCL](http://www.sbcl.org/index.html) - Steel Bank Common Lisp. A fork of CMUCL; compiles to efficient machine code. [Standard compliance](http://www.sbcl.org/manual/index.html#ANSI-Conformance). Public domain, with some parts under [Expat](https://directory.fsf.org/wiki/License:Expat) and [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   see also: [sbcl-librarian (⭐76)](https://github.com/quil-lang/sbcl-librarian) -  Dynamic library delivery tools for SBCL. Create shared libraries that can be called from C or Python. MIT. [Blog post](https://mstmetent.blogspot.com/2022/04/using-lisp-libraries-from-other.html). [Full example (⭐76)](https://github.com/quil-lang/sbcl-librarian/tree/main/example).
    *   [SBCL-GOODIES (⭐26)](https://github.com/sionescu/sbcl-goodies) - Distributing binaries with Common Lisp and foreign libraries: libssl, libcrypto and libfixposix are statically baked in. [MIT](https://opensource.org/licenses/MIT).

### Changing the syntax

*   ⭐ [cl-interpol (⭐54)](https://github.com/edicl/cl-interpol/) - A set of reader modifications to allow string interpolation. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [mstrings](https://git.sr.ht/~shunter/mstrings) -  a reader macro to provide visually appealing multiline blocks. An M-string trims leading whitespace, concatenates lines together, etc. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [pythonic-string-reader (⭐17)](https://github.com/smithzvk/pythonic-string-reader) - A simple and unobtrusive read table modification inspired by Python's three quote strings. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-heredoc (⭐13)](https://github.com/outergod/cl-heredoc) - a ["heredocs" (⭐13)](https://github.com/outergod/cl-heredoc) dispatcher. [GPL3](http://www.gnu.org/copyleft/gpl.html). Allows to write: `#>eof>Write whatever (you) "want", no matter what characters, until the magic end sequence has been reached.eof`

### HTTP Servers / Hunchentoot plugins

*   [cl-tbnl-gserver-tmgr (⭐15)](https://github.com/mdbergmann/cl-tbnl-gserver-tmgr) -  Hunchentoot Gserver-based taskmanager. cl-gserver is an actor-like message-passing library (see below in "Actors pattern"). Experimental.

## [Jul 09, 2022](/content/2022/07/09/README.md)

### C, C++

*   [bp (⭐35)](https://github.com/rodentrabies/bp) - Bitcoin Protocol components in Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Jun 18, 2022](/content/2022/06/18/README.md)

### HTTP Servers / Clack plugins

*   [tiny-routes (⭐11)](https://github.com/jeko2000/tiny-routes) -  A tiny routing library for Common Lisp targeting Clack. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Jun 06, 2022](/content/2022/06/06/README.md)

### C, C++

*   ⭐ [Ironclad (⭐148)](https://github.com/sharplispers/ironclad) - A library of crypto functions for Common Lisp. Not considered secure, but is still useful for the message digest functions. [Expat](https://directory.fsf.org/wiki/License:Expat).

### ORMs

*   ⭐ [clsql](http://www.cliki.net/CLSQL) - An SQL database with a Common Lisp interface. [LLGPL](http://opensource.franz.com/preamble.html).

### Wrappers

*   ⭐ [postmodern](http://marijnhaverbeke.nl/postmodern/) - A library for interacting with PostgreSQL. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### C

*   ⭐ [CFFI (⭐395)](https://github.com/cffi/cffi) - Portable, easy-to-use C foreign function interface. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   [cffi-ops (⭐28)](https://github.com/bohonghuang/cffi-ops) - helps write concise CFFI-related code.
    *   [cffi-objects (⭐14)](https://github.com/bohonghuang/cffi-object) - enables fast and convenient interoperation with foreign objects.

### Miscellaneous

*   ⭐ [Sketch (⭐1.3k)](https://github.com/vydd/sketch) - A CL framework for the creation of electronic art, graphics, and lots more. [MIT](https://opensource.org/licenses/MIT).
*   ⭐ [CommonQt (⭐112)](https://github.com/commonqt/commonqt) - A Common Lisp binding for Qt4 via QtSmoke. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
    *   [CommonQt5 (⭐29)](https://github.com/commonqt/commonqt5/) - bindings for Qt5.
        *   warn: currently difficult to install. Used in production© by SISCOG.

### Mobile

*   ⭐ [CCL](https://github.com/CodyReichert/awesome-cl/blob/master//ccl.clozure.com/) - Clozure Common Lisp; compiler-only implementation, generates native code.  [LLGPL](http://opensource.franz.com/preamble.html).
*   ⭐ [alexandria](https://common-lisp.net/project/alexandria/) - A general-purpose utility library. Public domain.
*   ⭐ [trivia (⭐301)](https://github.com/guicho271828/trivia/) - Optimized pattern-matching library. [LLGPL](http://opensource.franz.com/preamble.html).

### CLOS extensions

*   ⭐ [closer-mop](http://cliki.net/closer-mop) - A compatibility layer that rectifies many absent or incorrect MOP features. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Iteration

*   ⭐ [iterate](https://common-lisp.net/project/iterate/) - An iteration construct for Common Lisp which is extensible and Lispier. [MIT](https://opensource.org/licenses/MIT).

### Community

*   ⭐ [Quicklisp](https://www.quicklisp.org/beta/) - A library manager containing many libraries, with easy depencency management. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   [ql-https (⭐11)](https://github.com/rudolfochrist/ql-https) - shell out to cURL and use HTTPS by default.
    *   [Quicklisp bundles](https://quicklisp.org/beta/bundles.html) -  self-contained sets of systems that are exported from Quicklisp and loadable without involving Quicklisp.

### HTTP Servers / Interfaces to other package managers

*   ⭐ [Hunchentoot](http://weitz.de/hunchentoot/) - A web server. [2-clause BSD](https://opensource.org/licenses/bsd-license.php)

### HTML generators and templates / Isomorphic web frameworks

*   ⭐ [cl-who](http://weitz.de/cl-who/) - The venerable HTML generator. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Utils / Third-party APIs

*   ⭐ [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/) - Portable, shared-state concurrency. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Job processing / Third-party APIs

*   ⭐ [cl-ppcre](http://weitz.de/cl-ppcre/) - Portable, Perl-compatible regular expressions. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Emacs / Third-party APIs

*   ⭐ [Slime (⭐1.8k)](https://github.com/slime/slime) - Superior Lisp Interaction Mode for Emacs; a full-blown environment for Common Lisp inside of Emacs. Public domain.

### Apps / Third-party APIs

*   ⭐ [esrap (⭐71)](https://github.com/scymtym/esrap) - Packrat parser. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   ⭐ [FiveAM](https://github.com/sionescu/fiveam) - Simple regression testing framework. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
    *   [fiveam-matchers (⭐8)](https://github.com/tdrhq/fiveam-matchers/) -  an extensible, composable matchers library for fiveam. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### Caching / Third-party APIs

*   [clache (⭐13)](https://github.com/html/clache) - General caching facility. Cache any Lisp object on disk or in memory. A cache can be persistent or have an expiration time. [LLGPL](http://opensource.franz.com/preamble.html).

### CSV / Third-party APIs

*   ⭐ [cl-csv (⭐113)](https://github.com/AccelerationNet/cl-csv) - A library for parsing CSV files. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Date and time / Third-party APIs

*   ⭐ [local-time](https://common-lisp.net/project/local-time/) - A development library for manipulating date and time information in a semi-standard manner. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Documentation builders / Third-party APIs

*   [mgl-pax (⭐64)](https://github.com/melisgl/mgl-pax) - Exploratory
    programming environment and documentation generator. one may
    accomplish similar effects as with Literate Programming, but
    documentation is generated from code, not vice versa. Code is first,
    code must look pretty, documentation is code. [MIT](https://opensource.org/licenses/MIT).
    *   see this [40ants fork (⭐15)](https://github.com/40ants/doc) for: a lighter core system, a JavaScript search index, multiple format output, HTML themes, RSS and Atom feed for the Changelog and more.
*   [Declt (⭐36)](https://github.com/didierverna/declt) - Reference manual generator for Common Lisp libraries. Builds a texinfo document that can be further processed into various formats, such as HTML or PDF. BSD.
*   [Codex (⭐85)](https://github.com/CommonDoc/codex) - A beautiful
    documentation system for Common Lisp. [MIT](https://opensource.org/licenses/MIT).
*   [QBook (⭐6)](https://github.com/mmontone/qbook) - generates HTML (or LaTeX) formatted code listings of Common Lisp source files. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   all comments started with 4 `;` (";;;;") are interpreted as documentation. Enhance the documentation with headings and directives.
    *   QBook acts as "a lightweight literate programming system, where Lisp code is not rendered inline, but in separate sections, and that makes the document more pleasant to navigate." @mmontone
*   [cl-bibtex (⭐24)](https://github.com/mkoeppe/cl-bibtex) - A compatible re-implementation of the BibTeX program in Common Lisp, with a BST-to-CL compiler. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
*   [docbrowser (⭐15)](https://github.com/lokedhs/docbrowser) - a server that generates documentation for the loaded systems on the fly.
    *   Its main page presents a list of all loaded systems in your Lisp image. Click on one system, and you get a page with three panes: functions, classes and variables. Click on a function to see its source, in context, with line numbers. Click on classes to see their slots and specializing functions.

### Literate programming / Third-party APIs

*   [literate-lisp (⭐51)](https://github.com/jingtaozf/literate-lisp) -  Load Common Lisp code blocks from Emacs' Org files. [MIT](https://opensource.org/licenses/MIT).
*   [erudite (⭐67)](https://github.com/mmontone/erudite) - Literate Programming System built with interactive development in mind. [MIT](https://opensource.org/licenses/MIT).

### Other / Third-party APIs

*   absolute de-facto libraries, like BordeauxThreads or Quicklisp,
    should be denoted with a ⭐ (Unicode code U+2B50).

## [Jun 02, 2022](/content/2022/06/02/README.md)

### Miscellaneous

*   ⭐ [ltk](http://www.peter-herth.de/ltk/) - A binding for the Tk toolkit. [LLGPL](http://opensource.franz.com/preamble.html) or [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
    *   [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - Provides LTk examples for the tkdocs tutorial.
    *   [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/) - A wrapper around the tklib/plotchart library to work with LTk. This includes over 20 different chart types (xy-plots, gantt charts, 3d-bar charts etc...).
*   [vk (⭐45)](https://github.com/JolifantoBambla/vk) -  Common Lisp/CFFI bindings for the Vulkan API. [MIT](https://opensource.org/licenses/MIT).

## [May 22, 2022](/content/2022/05/22/README.md)

### Matrix libraries / Third-party APIs

*   [magicl (⭐221)](https://github.com/quil-lang/magicl) - Matrix Algebra proGrams In Common Lisp based on BLAS/LAPACK and Expokit, by Rigetti Computing. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [May 18, 2022](/content/2022/05/18/README.md)

### Javascript / Isomorphic web frameworks

*   [sigil (⭐2)](https://github.com/BnMcGn/sigil) - A Parenscript to Javascript command line compiler and REPL. [MIT](https://opensource.org/licenses/MIT).
*   [cl-react (⭐66)](https://github.com/helmutkian/cl-react) -  Common Lisp (Parenscript) utilities for building web apps in ReactJs. MIT.
*   [Panic (⭐42)](https://github.com/michaeljforster/panic), a Parenscript library for React. Not in Quicklisp. [MIT](https://opensource.org/licenses/MIT). Its [TodoMVC example (⭐7)](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
*   [Parenscriptx (⭐24)](https://github.com/jasom/parenscriptx) -  Parenscript Macros to aid generating react code. [MIT](https://opensource.org/licenses/MIT).
*   [jscl-react (⭐17)](https://github.com/nilesr/jscl-react) -  A web framework for writing react components in common lisp using jscl. No license specified.

### XML / Third-party APIs

*   [CXML](https://common-lisp.net/project/cxml/) - XML parser and serializer, with a range of extension libraries. [LLGPL](http://opensource.franz.com/preamble.html).
    *   👍 has an incremental parser, allowing to parse big files.
    *   see the [FXML (⭐28)](https://github.com/ruricolist/FXML) fork, with fixes and new features. You should use it if your are parsing potentially ill-formed or malicious XML, or if you need to use Klacks with namespaces.

## [May 05, 2022](/content/2022/05/05/README.md)

### Mobile

*   [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master//www.cons.org/cmucl/) - An implementation from Carnegie Mellon University. Public domain. SBCL is a fork of CMUCL.
*   [Corman Lisp (⭐573)](https://github.com/sharplispers/cormanlisp) - a Common Lisp development environment for Microsoft Windows running on Intel platforms. [MIT](https://opensource.org/licenses/MIT).

### Deployment / Isomorphic web frameworks

*   [Platform.sh](https://platform.sh/blog/2019/lisp/) has Common Lisp support, so has [OVH](https://docs.ovh.com/ie/en/web-paas/languages-lisp/) through their Web PaaS partnership.

## [Apr 19, 2022](/content/2022/04/19/README.md)

### Miscellaneous

*   [file-select (⭐15)](https://github.com/Shinmera/file-select) -  A library to invoke the native system file dialog to select or create files. Zlib.

### XML / Third-party APIs

*   [Plump (⭐110)](https://github.com/Shinmera/plump) - A lenient XML parser. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [xpath (⭐6)](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html) - Implementation of the XML Path Language (XPath) Version 1.0. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
*   [s-xml](http://cliki.net/S-XML) - A basic parser. [LLGPL](http://opensource.franz.com/preamble.html).
*   [xmls (⭐18)](https://github.com/rpgoldman/xmls) - A small, simple, non-validating XML parser. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-feedparser (⭐24)](https://github.com/TBRSS/cl-feedparser) - A Common Lisp (RSS, Atom) feed parser. [LLGPL](http://opensource.franz.com/preamble.html)
*   [Buildnode (⭐19)](https://github.com/AccelerationNet/buildnode) - A common lisp library to ease interaction with CXML-dom, such as building Excel spreadsheets. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Emacs / Third-party APIs

*   [slime-star (⭐31)](https://github.com/mmontone/slime-star) - a SLIME configuration with extensions pre-installed, with also some custom utilities and menus:
    *   the Lisp system browser
    *   [SLIME doc contrib (⭐17)](https://github.com/mmontone/slime-doc-contribs) - enhance the default help buffer.
    *   [Quicklisp systems (⭐27)](https://github.com/mmontone/quicklisp-systems) - Search, browse and load Quicklisp systems from Emacs.
    *   [Quicksearch (⭐48)](https://github.com/tkych/quicksearch)
    *   [Slime breakpoints (⭐11)](https://github.com/mmontone/slime-breakpoints)
    *   [Slite (⭐48)](https://github.com/tdrhq/slite/) - a test runner for FiveAM.
    *   [Quicklisp-apropos (⭐9)](https://github.com/mmontone/quicklisp-apropos) - Perform `apropos` queries across libraries in Quicklisp (full-text search on symbol names, classes, documentation…).
    *   [slime-critic (⭐10)](https://github.com/mmontone/slime-critic) - the lisp critic gently critiques your code for bad patterns.

## [Mar 23, 2022](/content/2022/03/23/README.md)

### i18n / Third-party APIs

*   [translate (⭐8)](https://github.com/dkochmanski/translate) - seamless language localization. LLGPL.

## [Mar 11, 2022](/content/2022/03/11/README.md)

### Miscellaneous

*   [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml)- a library of functions for writing windowized GUIs for Windows, Mac and Linux. Proprietary with a free version.
    *   since Allegro 10.1 (March, 2022), the IDE and the Common Graphics toolkit [runs in the browser](https://franz.com/ftp/pri/acl/cgjs/doc.html).

## [Mar 09, 2022](/content/2022/03/09/README.md)

### Web frameworks / Isomorphic web frameworks

*   [Weblocks (⭐36)](https://github.com/40ants/reblocks) - A widgets-based framework with a built-in ajax update mechanism that "solves the JavaScript problem". [LLGPL](http://opensource.franz.com/preamble.html).

## [Mar 02, 2022](/content/2022/03/02/README.md)

### Web frameworks / Clack plugins

*   [radiance (⭐293)](https://github.com/Shirakumo/radiance) - A web application environment and framework . [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   👍 [Snooze (⭐197)](https://github.com/joaotavora/snooze) - A RESTful web framework. Web server agnostic. Currently has support for Hunchentoot and Clack. Routes are just functions and HTTP conditions are just Lisp conditions. [LLGPL](http://opensource.franz.com/preamble.html).

### Developer utilities / Third-party APIs

*   [journal (⭐38)](https://github.com/melisgl/journal) - a library for logging, tracing, record-and-replay testing and persistence. MIT.

## [Feb 13, 2022](/content/2022/02/13/README.md)

### Mobile

*   [LispWork's mobile runtime](http://www.lispworks.com/products/lw4mr.html) - Android and iOs.  Proprietary.
*   [LQML](https://gitlab.com/eql/lqml) - a lightweight ECL binding to QML (both Qt5 and Qt6) derived from EQL5. LGPL and public domain.

### Reference

*   [CDR](https://cdr.common-lisp.dev/) - Common Lisp Document Repository. a repository of documents that are of interest to the Common Lisp community. The most important property of a CDR document is that it will never change: if you refer to it, you can be sure that your reference will always refer to exactly the same document.
    *   the Common Lisp Document Repository is hosted at [Zenodo](https://zenodo.org/communities/cdr/).

## [Jan 27, 2022](/content/2022/01/27/README.md)

### Wrappers

*   [lmdb (⭐40)](https://github.com/antimer/lmdb) - Bindings to [LMDB](http://www.lmdb.tech/doc/), the Lightning Memory-mapped Database, an ACID key-value database with MultiVersion Concurrency Control.

### Miscellaneous

*   [cl-cffi-gtk (⭐137)](https://github.com/crategus/cl-cffi-gtk) - Binding for GTK+3. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
    *   a tutorial: [Learn Common Lisp by Example: GTK GUI with SBCL](https://dev.to/goober99/learn-common-lisp-by-example-gtk-gui-with-sbcl-5e5c)

### Community / Interfaces to other package managers

*   [MGL (⭐552)](https://github.com/melisgl/mgl) - a machine learning library for backpropagation neural networks, boltzmann machines, gaussian processes and more. [MIT](https://opensource.org/licenses/MIT).
    *   some parts originally contributed by Ravenpack International.
    *   used by its [author](https://github.com/melisgl) to [win (⭐127)](https://github.com/melisgl/higgsml) the Higgs Boson Machine Learning Challenge.
    *   more about the author: he also won the Google [AI Challenge](https://en.wikipedia.org/wiki/AI_Challenge) in 2010 using Common Lisp, but without MGL, as no machine learning was needed. A [related talk](https://www.youtube.com/watch?v=7sgERtZkycU) (59', 2013).

## [Dec 18, 2021](/content/2021/12/18/README.md)

### Web development utilities / User login and password management

*   [cl-cas (⭐1)](https://github.com/fferrere/cl-cas) - A library to help [CAS authenticaton](https://apereo.github.io/cas/6.0.x/protocol/CAS-Protocol.html) to Common Lisp web applications. Not in Quicklisp.
    *   [cas-middleware (⭐0)](https://github.com/fferrere/cas-middleware) - CAS authenticaton middleware for Caveman.
    *   [cas-demo (⭐2)](https://github.com/fferrere/cas-demo) - a demo project.

## [Nov 24, 2021](/content/2021/11/24/README.md)

### Beginner

*   📹 [Common Lisp Programming: from novice to effective developer](https://www.udemy.com/course/common-lisp-programming/?referralCode=2F3D698BBC4326F94358) - A learning video series on the Udemy platform (*full content under paid access*). Teaches the language basics, explains the ecosystem and shows real-world examples. By an active lisper and community contributor (@vindarel).
    > Thanks for supporting my work on Udemy. Also note that I release free coupons from time to time, and that Udemy often proposes drastic promotions, but you can ask me a free coupon too.

## [Nov 22, 2021](/content/2021/11/22/README.md)

### Others / Third-party APIs

*   [origin (⭐1)](https://github.com/mfiano/origin) - A native Lisp graphics math library with an emphasis on performance and correctness. Includes: vectors, matrices (up to 4x4), quaternions, single/double-float support, destructive/non-destructive operations, shaping & intersections. [MIT](https://opensource.org/licenses/MIT).

## [Nov 16, 2021](/content/2021/11/16/README.md)

### Querying HTML/DOM / Isomorphic web frameworks

*   👍 [lquery (⭐81)](https://github.com/Shinmera/lquery) - A jQuery-like HTML/DOM manipulation library. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Nov 15, 2021](/content/2021/11/15/README.md)

### Graph databases

*   [restagraph](https://github.com/equill/restagraph) - an app that dynamically generates REST APIs for a Neo4j database, using a schema defined within the database. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Nov 01, 2021](/content/2021/11/01/README.md)

### Advanced

*   [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - Updated version of "[Programming Algorithms](https://leanpub.com/progalgs)"; A comprehensive guide to writing efficient programs with data structures and algorithms in Lisp.

## [Oct 26, 2021](/content/2021/10/26/README.md)

### VSCode / Third-party APIs

*   [alive (⭐178)](https://github.com/nobody-famous/alive) -  Common Lisp Extension for VSCode. Public domain.
    *   see the Cookbook: [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)

## [Sep 29, 2021](/content/2021/09/29/README.md)

### Apps / Third-party APIs

*   [CLUnit2](https://notabug.org/cage/clunit2/) - A unit testing library. [MIT](https://opensource.org/licenses/MIT).

## [Sep 26, 2021](/content/2021/09/26/README.md)

### To third parties

*   [pzmq (⭐37)](https://github.com/orivej/pzmq) -  ZeroMQ 4.0+ Common Lisp bindings. Unlicense.

## [Sep 23, 2021](/content/2021/09/23/README.md)

### Compression / decompression / Third-party APIs

*   [archive (⭐30)](https://github.com/froydnj/archive) - a library for reading and creating archive (tar, cpio) files. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause). A pure Common Lisp replacement for the `tar` program.
    *   see its recent fork [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).

## [Sep 13, 2021](/content/2021/09/13/README.md)

### Typing

*   👍 [Coalton (⭐866)](https://github.com/coalton-lang/coalton/) - an efficient, statically typed functional programming language that supercharges Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Aug 24, 2021](/content/2021/08/24/README.md)

### Persistent object databases

*   [bknr.datastore (⭐90)](https://github.com/hanshuebner/bknr-datastore) - a CLOS-based lisp-only database in RAM with transaction logging persistence. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html). [licence](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).
    *   see also this [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
    *   an example web application using bknr.datastore: [screenshotbot-oss (⭐175)](https://github.com/screenshotbot/screenshotbot-oss).
    *   See also [bknr.cluster (⭐8)](https://github.com/tdrhq/bknr.cluster), if you want a highly-available replicated version of bknr.datastore.

### Utils / Third-party APIs

*   [cl-etcd (⭐10)](https://github.com/atgreen/cl-etcd) - Run etcd as an asynchronous inferior process.  [etcd](https://etcd.io/) is a strongly consistent, distributed key-value store. [AGPL-3.0](https://directory.fsf.org/wiki/License:AGPL-3.0).

### Command-line options parsers / Third-party APIs

*   👍 [Clingon (⭐103)](https://github.com/dnaeon/clingon) - a rich command-line options parser system.
    *   it may have the richest feature set: subcommands, generation of bash completion, support for various kinds of options (integers, booleans, counter, enums…), extensible…

## [Aug 09, 2021](/content/2021/08/09/README.md)

### Community

*   [quick-patch (⭐20)](https://github.com/tdrhq/quick-patch/) -  easily override quicklisp projects without using git submodules. MPL-2.0.

### Web development utilities / Web project skeletons and generators

*   [cl-cookieweb (⭐30)](https://github.com/vindarel/cl-cookieweb) - a  Cookiecutter template to start a web project. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause). Not in Quicklisp.
    *   Provides a working toy web app with the Hunchentoot web server, easy-routes, Djula templates, styled with Bulma, based on SQLite, with migrations, an example table definition and a test suite using FiveAM.
*   [make-like (⭐11)](https://github.com/container-lisp/make-like) - an application template builder for LIKE (Lisp In Kubernetes + Emacs) applications. [Apache2.0](https://directory.fsf.org/wiki/License:ArtisticLicense2.0).
    *   Makefile, podman support, GitHub Actions, Prometheus metrics support, TOML-style config.ini, easy-route preconfigured with health-check and more.
*   [cl-webapp-seed (⭐6)](https://github.com/rajasegar/cl-webapp-seed) - a simple web application boilerplate. Uses Hunchentoot, cl-who, deploys easily to Heroku. [MIT](https://opensource.org/licenses/MIT).

### Others / Web project skeletons and generators

*   [cl-wget](https://github.com/cl-wget/cl-wget) - Makes retrieving large files or mirroring entire websites easy. [AGPL-3.0](https://directory.fsf.org/wiki/License:ArtisticLicense2.0).
*   [trivial-download (⭐36)](https://github.com/eudoxia0/trivial-download) - Download files. [MIT](https://opensource.org/licenses/MIT).

### Writing, running scripts / Third-party APIs

*   [ScriptL (⭐69)](https://github.com/rpav/ScriptL) - Shell scripting made Lisp-like! Or, live-coding remote function calls for the shell. Write a command in the REPL, and run it instantly in the shell. [LLGPL](http://opensource.franz.com/preamble.html).
    *   similar and maybe simpler: [lserver](https://notabug.org/quasus/lserver/)

### Command-line options parsers / Third-party APIs

*   [Adopt (⭐28)](https://github.com/sjl/adopt/) - A Damn OPTion parsing library. [MIT](https://opensource.org/licenses/MIT).

## [Jul 23, 2021](/content/2021/07/23/README.md)

### System administration / Third-party APIs

*   [Consfigurator](https://spwhitton.name/tech/code/consfigurator/) - Lisp declarative configuration management system.  You can use it to configure hosts as root, deploy services as unprivileged users, build and deploy containers, and produce disc images. [GPL3](http://www.gnu.org/copyleft/gpl.html).

### Project skeletons / Third-party APIs

*   [cl-project (⭐218)](https://github.com/fukamachi/cl-project) - General modern project skeletons. [LLGPL](http://opensource.franz.com/preamble.html).
*   [cl-project-with-docs (⭐3)](https://github.com/40ants/cl-project-with-docs) - uses Sphinx and reStructured text to render nice and readable HTML documentation. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-cookieproject (⭐52)](https://github.com/vindarel/cl-cookieproject) -  Generate a ready-to-use Common Lisp project. Not in Quicklisp. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   test definitions, entry point to run from sources, build a binary, Roswell integration…

## [Jul 22, 2021](/content/2021/07/22/README.md)

### HTTP Servers / Clack plugins

*   [clath (⭐36)](https://github.com/BnMcGn/clath) - a single sign-on
    middleware for Clack. It allows basic login with OAuth1.0a, OAuth2
    and OpenID. At the time of writing, it supports authentication from
    Google, Twitter, LinkedIn, StackExchange, Reddit and Github. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### Shells, shells interfaces / Third-party APIs

*   [shcl (⭐296)](https://github.com/bradleyjensen/shcl) - a POSIX-like shell in Common Lisp. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### Apps / Third-party APIs

*   [Slite (⭐48)](https://github.com/tdrhq/slite/) - a SLIme-based TEst runner for FiveAM Tests. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)
    *   Slite interactively runs your Common Lisp tests (at the time of writing only FiveAM is supported). It allows you to see the summary of test failures, jump to test definitions, rerun tests with the debugger, all from inside Emacs.

## [Jul 08, 2021](/content/2021/07/08/README.md)

### Miscellaneous

*   [pngload-fast](https://git.mfiano.net/mfiano/pngload) - A PNG (Portable Network Graphics) image format decoder in portable Common Lisp with an emphasis on speed. [MIT](https://opensource.org/licenses/MIT).

## [Jun 21, 2021](/content/2021/06/21/README.md)

### Community

*   [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) on Libera Chat - main Common Lisp IRC channel.
*   [#lisp](https://irclog.tymoon.eu/libera/%23lisp) on Libera Chat - IRC channel for all Lisp dialects.
*   \#clschool on Libera Chat - IRC channel for learning Common Lisp.
*   \#lispcafe on Libera Chat - IRC channel for off-topic discussions.

## [Jun 01, 2021](/content/2021/06/01/README.md)

### CLOS extensions

*   [polymorphic functions (⭐47)](https://github.com/digikar99/polymorphic-functions) - A function type to dispatch on types instead of classes with partial support for dispatching on optional and keyword argument types. Still experimental (May, 2021). [MIT](https://opensource.org/licenses/MIT).
    *   polymorphic-functions dispatch on the types of the arguments supplied to it. This helps dispatching on specialized arrays as well as user-defined types.
    *   for differences with specialization-store and fast-generic-functions, see its README.

## [Apr 25, 2021](/content/2021/04/25/README.md)

### CLOS extensions

*   [slot-extra-options (⭐7)](https://github.com/some-mthfka/slot-extra-options) - lets you build a metaclass which in turn lets you specify extra slot options in its classes. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

### Community

*   [Qlot (⭐335)](https://github.com/fukamachi/qlot) - A project-local library installer, similar to Bundler or Virtualenv. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   how to [use it from the Lisp REPL (⭐9)](https://github.com/svetlyak40wt/qlot-without-roswell) without Roswell.
*   [Quicksys](https://lisp.com.br/quicksys/) - install systems from multiple Quicklisp distributions. [MIT](https://opensource.org/licenses/MIT).

### Apps / Third-party APIs

*   [cl-coveralls (⭐28)](https://github.com/fukamachi/cl-coveralls) - a helper
    library to post test coverage to Coveralls. See [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover). [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Date and time / Third-party APIs

*   [local-time-duration (⭐16)](https://github.com/enaeher/local-time-duration) -
    Duration processing library built on top of local-time. [MIT](https://opensource.org/licenses/MIT).
    *   see this fork: [humanize-duration (⭐8)](https://github.com/40ants/humanize-duration), that outputs only significant parts of a duration object. Has localization suport.

## [Apr 14, 2021](/content/2021/04/14/README.md)

### C, C++

*   [crypto-shortcuts (⭐20)](https://github.com/Shinmera/crypto-shortcuts) - Collection of common crypto shortcuts. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Persistent object databases

*   [ubiquitous (⭐23)](https://github.com/Shinmera/ubiquitous) - A library providing easy-to-use persistent configuration storage. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Miscellaneous

*   👍 [Qtools (⭐203)](https://github.com/Shinmera/qtools/) - A Qt toolkit, based on CommonQt. [zlib](https://directory.fsf.org/wiki/License:Zlib) Also [Qtools-ui (⭐28)](https://github.com/Shinmera/qtools-ui) (premade UI components), with [videos](https://www.youtube.com/watch?v=KwASFOhYta4\&index=7\&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).

### Portability layers

*   [trivial-arguments (⭐19)](https://github.com/Shinmera/trivial-arguments) - A portable library to retrieve the arguments list of a function. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [definitions (⭐15)](https://github.com/Shinmera/definitions) - a general definitions introspection library. It gives you the ability to retrieve definitions or bindings associated with designators such as symbols, packages, and names in general. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [dissect](https://shinmera.github.io/dissect) - when a lot of projects use the “trivial-backtrace” system that just gives them a string with a backtrace, Dissect allows you to capture, step, and completely inspect the stack trace on a variety of Lisp implementations. Also very useful for logging and other situations where execution is automatically continued, but the information of the current stack is still useful to store somewhere. [zlib](https://directory.fsf.org/wiki/License:Zlib).
    *   [ndebug (⭐4)](https://github.com/atlas-engineer/ndebug) - Framework for portable GUI (or any non-standard) debuggers, based on [dissect](https://shinmera.github.io/dissect) and [trivial-custom-debugger (⭐12)](https://github.com/phoe/trivial-custom-debugger). [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Iteration

*   [for](https://shinmera.github.io/for/) - A concise, lispy and extensible iteration macro. Unlike loop it is extensible and sensible, and unlike iterate it does not require code-walking and is easier to extend. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### HTML generators and templates / Isomorphic web frameworks

*   [clip](https://shinmera.github.io/clip) - An HTML template processor where the templates are written in HTML. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Deployment / Isomorphic web frameworks

*   👍 [deploy](https://shinmera.github.io/deploy) - A toolkit for binary deployment of Lisp applications, with extra support for foreign shared libraries. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Matrix libraries / Third-party APIs

*   [3d-matrices](https://shinmera.github.io/3d-matrices) - A library implementing common matrix calculations, with an emphasis on 2x2,3x3, and 4x4 matrices as commonly used in graphics. It provides some numerical functions as well, but those are not the focus. The library is heavily optimised, so it is not made of pretty code. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Event processing / Third-party APIs

*   [simple-tasks (⭐19)](https://github.com/Shinmera/simple-tasks) - A very simple task scheduling framework. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [deeds (⭐22)](https://github.com/Shinmera/deeds) - Deeds is an Extensible Event Delivery System. It allows for efficient event delivery to multiple handlers with a complex event filtering system. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Writing, running scripts / Third-party APIs

*   [cl-all (⭐16)](https://github.com/shinmera/cl-all) - A script to run Lisp snippets in multiple implementations. This allows you to quickly compare implementation behaviour and differences. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Apps / Third-party APIs

*   [Parachute (⭐89)](https://github.com/Shinmera/parachute) - An extensible and cross-compatible testing framework. With test dependencies, conditions, fixtures and restarts. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Data validation / Third-party APIs

*   [ratify (⭐28)](https://github.com/Shinmera/ratify) - A collection of utilities to ratify, validate and parse inputs. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Developer utilities / Third-party APIs

*   [trivial-benchmark (⭐34)](https://github.com/Shinmera/trivial-benchmark) - Tiny benchmarking library. [zlib](https://directory.fsf.org/wiki/License:Zlib).
    *   a [similar macro (⭐14)](https://github.com/aartaka/graven-image#benchmark-macro) with additional support for more implementations (ABCL, Allegro, CCL, CLISP, ECL).
    *   Indeed, most trivial-benchmark's metrics are only implemented on SBCL. On other implementations, it measures real and user-space time (and not bytes allocated (it does for ECL), system run-time or GC run-time).

### Documentation builders / Third-party APIs

*   [Staple](https://github.com/Shinmera/staple) - a tool to generate documentation pages using an HTML template. Uses the existing README, adds docstrings, crossreferences and links to the CLHS. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Files and directories / Third-party APIs

*   [pathname-utils (⭐11)](https://github.com/Shinmera/pathname-utils) - A collection of utilities to help with pathname operations. [zlib](https://directory.fsf.org/wiki/License:Zlib).
    *   [filesystem-utils (⭐11)](https://github.com/Shinmera/filesystem-utils) - deal with common problems with filesystems, such as listing files, probing file types, determining default directories, etc.
    *   [file-attributes (⭐10)](https://github.com/Shinmera/file-attributes) -  access to common file attributes (uid, gid, permissions, ctime, mtime, atime).

### Git / Third-party APIs

*   [legit](https://shinmera.github.io/legit/) - an interface to the Git binary. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### i18n / Third-party APIs

*   [oxenfurt (⭐13)](https://github.com/Shinmera/oxenfurt) - A  client library for the Oxford dictionary API. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [language-codes](https://shinmera.github.io/language-codes) - A database library for ISO language codes. [zlib](https://directory.fsf.org/wiki/License:Zlib)
*   [system-locale](https://shinmera.github.io/system-locale) - A library to retrieve the user's preferred language, so that your application may choose a sensible default. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [multilang-documentation](https://shinmera.github.io/multilang-documentation) - Allows writing docstrings in multiple languages, for truly internationally documented libraries. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Logging / Third-party APIs

*   [verbose](https://shinmera.github.io/verbose) - A fast and highly configurable logging framework. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Apr 12, 2021](/content/2021/04/12/README.md)

### Miscellaneous

*   [Trial (⭐714)](https://github.com/shirakumo/trial) - Trial is an OpenGL game engine with a heavy focus on modularity. It is supposed to provide a large toolkit of useful bits and pieces from which you can create a game. [zlib](https://directory.fsf.org/wiki/License:Zlib).
    *   the [Kandria](https://kandria.com/) game is built with Trial.
*   [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/) – with this small framework you would be able to make simple 2D games: draw basic geometric forms, images and text, play sounds and listen to mouse and keyboard input. [MIT](https://opensource.org/licenses/MIT).
*   [virality (⭐85)](https://github.com/bufferswap/ViralityEngine) - A component-based game engine written in Common Lisp [MIT](https://opensource.org/licenses/MIT).
*   [cl-gamepad](https://shirakumo.github.io/cl-gamepad) - Access to gamepads and joysticks on Windows, Mac OS, and Linux. [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [cl-mpg123](https://shirakumo.github.io/cl-mpg123) and [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 and libout123 respectively, giving you fast and easy to use mp3 decoding and cross-platform audio output. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Apr 10, 2021](/content/2021/04/10/README.md)

### C

*   [cl-cxx-jit (⭐46)](https://github.com/Islam0mar/CL-CXX-JIT) -  Common Lisp and C++ interoperation with JIT. [MIT](https://opensource.org/licenses/MIT).

### Shells, shells interfaces / Third-party APIs

*   [Lish (⭐92)](https://github.com/nibbula/lish) - `lish` may someday be a lisp shell. [GPL3](http://www.gnu.org/copyleft/gpl.html).
    *   supports tab-completion of executables in the path and Lisp symbols, allows to write and to mix shell commands and Lisp code, has a tiny REPL and an interactive debugger, and more.

## [Apr 04, 2021](/content/2021/04/04/README.md)

### Mobile

*   [cl-json (⭐8)](https://github.com/sharplispers/cl-json) - A highly customizable JSON encoder and decoder. [MIT](https://directory.fsf.org/wiki/License:Expat).

## [Apr 03, 2021](/content/2021/04/03/README.md)

### Apps / Third-party APIs

*   [cl-mock (⭐16)](https://github.com/Ferada/cl-mock) - Another mocking library. It has more features than Mockingbird, like pattern matching on the mocked call, etc.

## [Apr 01, 2021](/content/2021/04/01/README.md)

### Statistics / Third-party APIs

*   [lisp-stat](https://github.com/lisp-stat) - an environment for statistical computing, conceptually similar to R, that is also suitable for front-line production deployments. "It grew out of a desire to have an environment for rapidly prototyping analytical and A.I. solutions, and move directly to production environments with minimal friction."
    *   <https://lisp-stat.dev/>
    *   ships Luke Tierney's [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) (a predecessor of R) as well as newer libraries.

## [Mar 22, 2021](/content/2021/03/22/README.md)

### Iteration

*   [doplus (⭐7)](https://github.com/alessiostalla/doplus) – another extensible iteration library, similar to :for.

## [Mar 15, 2021](/content/2021/03/15/README.md)

### Developer utilities / Third-party APIs

*   [printv (⭐67)](https://github.com/danlentz/printv) -  A batteries-included tracing and debug-logging macro. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0).

## [Mar 09, 2021](/content/2021/03/09/README.md)

### Files and directories / Third-party APIs

*   [fof](https://gitlab.com/ambrevar/fof) - File-object finder Common Lisp library. Enable rapid file search, inspection and manipulation. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Feb 27, 2021](/content/2021/02/27/README.md)

### Monitoring / Isomorphic web frameworks

*   [rollbar.lisp (⭐2)](https://github.com/adventuring/rollbar.lisp) - interface to [Rollbar.com](https://rollbar.com/), an error tracking software.

## [Feb 12, 2021](/content/2021/02/12/README.md)

### Web frameworks / Isomorphic web frameworks

*   [CLOG (⭐1.3k)](https://github.com/rabbibotton/clog) - The Common Lisp Omnificent GUI. Uses web technology to produce graphical user interfaces for applications locally or remotely. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   CLOG is based on the ideas of GNOGA, a framework the author wrote for Ada and used in commercial production code since 2013.
*   [Interactive SSR (⭐34)](https://github.com/interactive-ssr/client/blob/master/main.org/) - ISSR allows you to make interactive web pages without writing client scripting. No knowledge about Javascript or DOM is necessary.
    *   it is not unlike Phoenix LiveView or Hotwire.

## [Feb 11, 2021](/content/2021/02/11/README.md)

### Emacs / Third-party APIs

*   [Emacs4CL (⭐339)](https://github.com/susam/emacs4cl) - A tiny Emacs initialization file to quickly set up vanilla Emacs for Common Lisp programming. Comes with a line-by-line explanation of every line of code in the initialization file.

## [Jan 25, 2021](/content/2021/01/25/README.md)

### Tools

*   [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - Docker images for ABCL, CCL, ECL, and SBCL on Windows (amd64) and Alpine and Debian (amd64, arm64, arm/v7) [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

## [Jan 13, 2021](/content/2021/01/13/README.md)

### Shells, shells interfaces / Third-party APIs

*   [cmd (⭐53)](https://github.com/ruricolist/cmd) - utility for running external programs. Protects against shell interpolation, built with multi-threaded programs in mind, Windows support. [MIT](https://opensource.org/licenses/MIT).
    *   `uiop:run-program` (synchronous) and `uiop:launch-program` (async) are shipped with ASDF and available on all modern implementations. See the [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).

## [Jan 06, 2021](/content/2021/01/06/README.md)

### Web Development

*   [Lisp for the Web](https://leanpub.com/lispweb) - A book that walks you through building a voting web application in three tiers.
*   [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - An introductory tutorial covering web server setup, routing, weblocks, templating, error handling, packaging, hot reloading, database connection, and deployment, amongst other topics in the current lisp web development ecosystem.

### Others / Third-party APIs

*   [Vellum (⭐68)](https://github.com/sirherrbatka/vellum) - Data Frames for Common Lisp. BSD\_2Clause.
*   [rtg-math (⭐50)](https://github.com/cbaggers/rtg-math/) - a selection of the math routines most commonly needed for making realtime graphics in lisp (2, 3 and 4 component vectors, 3x3 and 4x4 matrices, quaternions, spherical and polar coordinates). BSD\_2Clause.

### Matrix libraries / Third-party APIs

*   [lisp-matrix (⭐68)](https://github.com/blindglobe/lisp-matrix) - A matrix package. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Statistics / Third-party APIs

*   [common-lisp-stat (⭐168)](https://github.com/blindglobe/common-lisp-stat/) - Common Lisp statistics library. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Utils / Third-party APIs

*   [cmu-infix (⭐31)](https://github.com/rigetti/cmu-infix) - A library for writing infix mathematical notation in Common Lisp. See also [polisher (⭐5)](https://github.com/mrcdr/polisher).

## [Dec 17, 2020](/content/2020/12/17/README.md)

### Community / Interfaces to other package managers

*   [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - A BuildStream project for building Flatpak based runtime environments for Common Lisp applications.

### Utils / Third-party APIs

*   [calispel (⭐28)](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes)-like channels for common lisp. With blocking, optionally buffered channels and a "CSP select" statement. ISC-style.
    *   "It is complete, flexible and easy to use. I would recommend Calispel over Lparallel and ChanL." @Ambrevar. [discussion (⭐2.3k)](https://github.com/CodyReichert/awesome-cl/issues/290)

### Apps / Third-party APIs

*   [cl-phonetic (⭐24)](https://github.com/bgutter/cl-phonetic) - Phonetic pattern matching library for Common Lisp (intended to replace the Sylvia library for Python). [MIT](https://opensource.org/licenses/MIT).
*   [cl-string-generator (⭐22)](https://github.com/pokepay/cl-string-generator) -  Generate string from regular expression. [MIT](https://opensource.org/licenses/MIT).

### Plotting / Third-party APIs

*   [ADW-Charting](https://common-lisp.net/project/adw-charting/) - A simple chart drawing library written completely in Common Lisp. Also includes a backend to Google's chart service. BSD-like.

## [Dec 14, 2020](/content/2020/12/14/README.md)

### Tools

*   [bst (⭐8)](https://github.com/glv2/bst) - Binary Search Tree. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Dec 12, 2020](/content/2020/12/12/README.md)

### VSCode / Third-party APIs

*   [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode) - an extension to support syntax highlight, auto completion, documentation on hover, go to definition, compile & load file, REPL. It is [On GitHub (⭐36)](https://github.com/ailisp/commonlisp-vscode/).
*   [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - structural editing and navigation like Emacs.

## [Dec 01, 2020](/content/2020/12/01/README.md)

### Developer utilities / Third-party APIs

*   [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
    A portable wrapper to generate Lisp cores on demand to start REPL blazing fast.
    It can preload provided systems to help build a collection of specialized
    Lisp cores.

## [Nov 11, 2020](/content/2020/11/11/README.md)

### Tools

*   [bitfield (⭐22)](https://github.com/marcoheisig/bitfield) - Efficiently represent several finite sets or small integers as a single non-negative integer. [MIT](https://opensource.org/licenses/MIT).

### Clojure

*   [ABCLJ (⭐84)](https://github.com/lsevero/abclj) - dead easy  Clojure to Common lisp interop. EPL-2.0.

### Other books

*   [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)) by Ken Forbus and Johan de Kleer, made available for free by MIT Press - a  unique book among standard artificial intelligence texts in combining science and engineering, theory and craft to describe the construction of AI reasoning systems, and including code illustrating the ideas.

## [Nov 06, 2020](/content/2020/11/06/README.md)

### Community / Interfaces to other package managers

*   [clml (⭐259)](https://github.com/mmaul/clml) - originally developed by Mathematicl Systems Inc., a Japanese company. With a [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html). [LLGPL](http://opensource.franz.com/preamble.html).

## [Oct 26, 2020](/content/2020/10/26/README.md)

### Tools

*   👍 [FSet](https://common-lisp.net/project/fset) - A functional, set-theoretic collections data structure library. [LLGPL](http://opensource.franz.com/preamble.html).

### Lambda shorthands

*   [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore) - a tiny library of functional programming utils. `(f_ (+ _ _)) -> (lambda (_) (+ _ _))`. Public domain.

### HTTP clients / Interfaces to other package managers

*   👍 [Dexador (⭐334)](https://github.com/fukamachi/dexador) - An HTTP client, that aims at replacing Drakma. [MIT](https://opensource.org/licenses/MIT).

### Units / Third-party APIs

*   [physical-quantities (⭐31)](https://github.com/mrossini-ethz/physical-quantities) - a library that provides a numeric type with optional unit and/or uncertainty for computations with automatic error propagation. GPL2

### Job processing / Third-party APIs

*   [cl-cron (⭐13)](https://github.com/ciel-lang/cl-cron) - A simple tool that provides cron like facilities. [GPL3](http://www.gnu.org/copyleft/gpl.html).

### Apps / Third-party APIs

*   [parseq (⭐25)](https://github.com/mrossini-ethz/parseq) - a library for parsing sequences such as strings and lists using parsing expression grammars. Inspired by Esrap. GPL2.

### Compression / decompression / Third-party APIs

*   [zippy (⭐11)](https://github.com/Shinmera/zippy) -  A ZIP archive format library based on 3bz. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### PDF / Third-party APIs

*   [cl-pslib](https://notabug.org/cage/cl-pslib) - a (thin) wrapper around the [pslib](http://pslib.sourceforge.net/) library for generating PostScript files. Also [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode). [LLGPL](http://opensource.franz.com/preamble.html).

## [Oct 22, 2020](/content/2020/10/22/README.md)

### Miscellaneous

*   [cl-cuda (⭐264)](https://github.com/takagi/cl-cuda) - A library to use NVIDIA CUDA in Common Lisp programs. [LLGPL](http://opensource.franz.com/preamble.html).
*   [LispWork's CAPI](http://www.lispworks.com/products/capi.html) - A portable GUI toolkit, with mobile runtime. Proprietary, but comes with a free version.

### HTML generators and templates / Isomorphic web frameworks

*   [flute (⭐61)](https://github.com/ailisp/flute) - An easily composable HTML5 generation library with the most simplistic syntax. [MIT](https://opensource.org/licenses/MIT).
*   [lsx (⭐75)](https://github.com/fukamachi/lsx/) and [markup (⭐59)](https://github.com/moderninterpreters/markup) - Two JSX-like templating engines, where HTML tags are Common Lisp code. `markup` comes with an Emacs package.

### Utils / Third-party APIs

*   [STMX (⭐235)](https://github.com/cosmos72/stmx) -  High performance Transactional Memory for Common Lisp. [LLGPL](http://opensource.franz.com/preamble.html).

### REPLs / Third-party APIs

*   [sbcli](https://github.com/hellerve/sbcli) - a readline REPL for SBCL. With completion, quick commands, optional syntax highlighting (with pygments), and no interactive debugger. [GPL3](http://www.gnu.org/copyleft/gpl.html).

### Apps / Third-party APIs

*   [texp (⭐5)](https://github.com/eugeneia/texp/) - A DSL to generate TeX. [AGPL-3.0](https://directory.fsf.org/wiki/License:AGPL-3.0).

### Compression / decompression / Third-party APIs

*   [chipz (⭐16)](https://github.com/froydnj/chipz) - A decompression library. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [Salza2](http://www.xach.com/lisp/salza2/) - A library for creating compressed data. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Developer utilities / Third-party APIs

*   [glyphs](https://github.com/ahungry/glyphs/) - A library for cutting down the verboseness of Common Lisp in places. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Oct 12, 2020](/content/2020/10/12/README.md)

### Miscellaneous

*   [cl-liballegro (⭐48)](https://github.com/resttime/cl-liballegro) - Interface and bindings to the Allegro 5 game programming library. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Oct 08, 2020](/content/2020/10/08/README.md)

### C, C++

*   [with-c-syntax (⭐128)](https://github.com/y2q-actionman/with-c-syntax) - a fun package which introduces the C language syntax into Common Lisp. (Yes, this package is not for practical coding, I think.) WTFPL Licence.

### Function extensions

*   [cl-advice (⭐1)](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md) - an attempt of portable layer advice library for SBCL, CCL, LispWorks and Allegro. Not in Quicklisp.

## [Oct 05, 2020](/content/2020/10/05/README.md)

### HTTP Servers / Interfaces to other package managers

*   👍[Clack (⭐999)](https://github.com/fukamachi/clack) - A web application environment inspired by Rack and WSGI. [LLGPL](http://opensource.franz.com/preamble.html).  Provides a unified interface to a webserver of choice (default is Hunchentoot). With more [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).

## [Oct 01, 2020](/content/2020/10/01/README.md)

### Iteration

*   [trivial-do (⭐17)](https://github.com/yitzchak/trivial-do/) -  Additional dolist style macros for Common Lisp. [MIT](https://opensource.org/licenses/MIT).
*   [picl (⭐15)](https://github.com/anlsh/picl) - An (almost) complete port of Python's itertools package, complete with laziness where applicable, and not relying on cl-cont. [MIT](https://opensource.org/licenses/MIT).

## [Sep 30, 2020](/content/2020/09/30/README.md)

### Wrappers

*   [cl-mango (⭐1)](https://github.com/cmoore/cl-mango/) -  A minimalist CouchDB 2.x database client. BSD\_3Clause.
    *   See also [clouchdb](https://common-lisp.net/project/clouchdb/) - Library for interacting with CouchDB. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

## [Sep 19, 2020](/content/2020/09/19/README.md)

### HTTP Servers / Hunchentoot plugins

*   👍 [easy-routes (⭐50)](https://github.com/mmontone/easy-routes) - a routes handling system on top of Hunchentoot. It supports dispatch based on HTTP method, arguments extraction from the url path, decorators, url generation from route name, etc. [MIT](https://opensource.org/licenses/MIT).

### Linting, code formatting / Third-party APIs

*   [sblint (⭐114)](https://github.com/fukamachi/sblint) - a linter for Common Lisp source code using SBCL, suited for Reviewdog ([slides](http://www.slideshare.net/fukamachi/sblint)). [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
*   [trivial-formatter (⭐33)](https://github.com/hyotang666/trivial-formatter) - code formatter for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Sep 15, 2020](/content/2020/09/15/README.md)

### Non-deterministic, logic programming

*   [Temperance (⭐55)](https://github.com/sjl/temperance) - logic programming. [MIT](https://opensource.org/licenses/MIT). A focus on performance, with General Game Playing in mind.

## [Sep 14, 2020](/content/2020/09/14/README.md)

### APL

*   [April (⭐537)](https://github.com/phantomics/april) - The APL programming language (a subset thereof) compiling to Common Lisp. Replace hundreds of lines of number-crunching code with a single line of APL. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0).

### Iteration

*   [snakes (⭐45)](https://github.com/BnMcGn/snakes) - Python style generators for Common Lisp. Includes a port of itertools. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0).

### Community / Interfaces to other package managers

*   🚀 [sparser (⭐48)](https://github.com/ddmcdonald/sparser) - A natural language understanding system for English. [Eclipse](http://www.eclipse.org/legal/epl-v10.html).
    *   > a model-driven, rule-based language text analysis system for large volume, high-precision information extraction. At its heart, Sparser is a bottom-up, phrase-structure-based chart parser, optimized for semantic grammars and partial parsing.

### Job processing / Third-party APIs

*   [one-more-re-nightmare (⭐127)](https://github.com/no-defun-allowed/one-more-re-nightmare) - a fast-ish regular expression compiler in Common Lisp. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

### Shells, shells interfaces / Third-party APIs

*   [Clesh (⭐62)](https://github.com/Neronus/Clesh) - extends Common Lisp to embed shell code in a manner similar to perl's backtick. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Apps / Third-party APIs

*   [cl-yacc](https://github.com/jech/cl-yacc) - a LALR(1) parser generator. [MIT](https://opensource.org/licenses/MIT).
*   [cl-shlex (⭐6)](https://github.com/ruricolist/cl-shlex/) - simple lexical analyzer for shell-like syntaxes. [MIT](https://opensource.org/licenses/MIT).
*   [smug (⭐103)](https://github.com/drewc/smug) - parser combinators for Common Lisp. SMUG makes it simple to create quick extensible recursive descent parsers without funky syntax or impenetrable macrology. [MIT](https://opensource.org/licenses/MIT).

### i18n / Third-party APIs

*   [gettext (⭐9)](https://github.com/rotatef/gettext) -  a port of the gettext runtime to Common Lisp. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Sep 13, 2020](/content/2020/09/13/README.md)

### Data validation / Third-party APIs

*   [json-schema (⭐13)](https://github.com/fisxoj/json-schema) - A library for validating data against schemas of drafts 4, 6, 7, and 2019-09 of the [JSON Schema](https://json-schema.org/) standard. [LLGPL](http://opensource.franz.com/preamble.html).

## [Sep 08, 2020](/content/2020/09/08/README.md)

### C, C++

*   [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl) - an interactive REPL for the C language. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
*   [cl-ssh-keys (⭐18)](https://github.com/dnaeon/cl-ssh-keys) - Common Lisp system for generating and parsing of OpenSSH keys. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-bcrypt (⭐9)](https://github.com/dnaeon/cl-bcrypt) - Common Lisp system for parsing and generating bcrypt password hashes. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
    *   see also [cl-pass (⭐27)](https://github.com/eudoxia0/cl-pass), using pbkdf2.

### Python

*   [burgled-batteries (⭐108)](https://github.com/pinterface/burgled-batteries) - A bridge between Python and Common Lisp. The goal is that Lisp programs can use Python libraries. Not available on Quicklisp. [MIT](https://opensource.org/licenses/MIT).

### Deployment / Isomorphic web frameworks

*   [cube (⭐34)](https://github.com/xh4/cube) - Kubernetes client library for Common LISP generated from the Swagger specification. [MIT](https://opensource.org/licenses/MIT).

### Utils / Third-party APIs

*   [Moira (⭐25)](https://github.com/TBRSS/moira) -  Monitor and restart background threads. In-lisp process supervisor. [MIT](https://opensource.org/licenses/MIT).

## [Aug 20, 2020](/content/2020/08/20/README.md)

### Mobile

*   [cl-json-pointer (⭐10)](https://github.com/y2q-actionman/cl-json-pointer) - A JSON Pointer implementation. [MIT](https://opensource.org/licenses/MIT).

## [Aug 17, 2020](/content/2020/08/17/README.md)

### Graph databases

*   [cl-agraph (⭐24)](https://github.com/vseloved/cl-agraph), a minimal client for [AllegroGraph](https://allegrograph.com/). AllegroGraph is a horizontally distributed, multi-model (document and graph), entity-event knowledge graph technology. It is proprietary and has a free version with a limit of 5 million triples.

## [Aug 06, 2020](/content/2020/08/06/README.md)

### Sublime Text / Third-party APIs

*   [Sublime Text](http://www.sublimetext.com/3) (proprietary) has
    Common Lisp support with its SublimeREPL and
    [Slyblime (⭐45)](https://github.com/s-clerc/slyblime) packages. Slyblime
    is an implementation of SLY and it uses the same backend (SLYNK). It
    ships advanced features including a debugger with stack frame
    inspection.

## [Jul 31, 2020](/content/2020/07/31/README.md)

### Community

*   [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - a subreddit to ask questions and get help about Lisp

## [Jul 18, 2020](/content/2020/07/18/README.md)

### HTTP Servers / Hunchentoot plugins

*   [hunchentoot-errors (⭐9)](https://github.com/mmontone/hunchentoot-errors) - Augments Hunchentoot error pages and logs with request and session information. [MIT](https://opensource.org/licenses/MIT).

## [Jul 17, 2020](/content/2020/07/17/README.md)

### Community / Interfaces to other package managers

*   [linux-packaging](https://gitlab.com/ralt/linux-packaging) - build .deb, .rpm or .pkg packages for your application with a single ASDF declaration. Uses fpm under the hood. [MIT](https://opensource.org/licenses/MIT).
*   [cl-brewer (⭐11)](https://github.com/can3p/cl-brewer) - Homebrew formula builder for (command line) common lisp applications. Public domain.

## [Jul 14, 2020](/content/2020/07/14/README.md)

### Logging / Third-party APIs

*   ⭐ [log4cl (⭐76)](https://github.com/sharplispers/log4cl/) - Logging framework modelled after Log4J. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0). Advanced integration with Slime.
    *   [log4cl-json (⭐2)](https://github.com/40ants/log4cl-json) - JSON appender extension. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Jul 10, 2020](/content/2020/07/10/README.md)

### Graph databases

*   [vivace-graph (⭐142)](https://github.com/kraison/vivace-graph-v3) - graph database & Prolog implementation. Takes design inspiration from CouchDB, neo4j and AllegroGraph. It implements an ACID-compliant object graph model with user-defined indexes and map-reduce views. It also implements a master / slave replication scheme for redundancy and horizontal read scaling. Querying the graph is accomplished via a number of Lisp methods or via a Prolog-like query language. [MIT](https://opensource.org/licenses/MIT).
    *   "I have used Vivace Graph as an online catalog for millions of products, as the back end for a complex, adaptable VoIP-based IVR, as well as data store for several complex big data analysis systems, and finally as the engine for two recommender systems." (issue #23)
    *   "Why is vivace graph so fast? I have been comparing it with SQL-based approach and Neo4j, and vivace graph is much, much faster."

### Plotting / Third-party APIs

*   [kai (⭐83)](https://github.com/komi1230/kai) - A high-level plotter library for Common Lisp. A wrapper around the [Plotly](https://plotly.com/javascript/) JS library. [MIT](https://opensource.org/licenses/MIT).
*   [cl-spark (⭐92)](https://github.com/tkych/cl-spark) - sparkline strings for the console: `(spark '(1 1 2 3 5 8))` => "▁▁▂▃▅▇". [MIT](https://opensource.org/licenses/MIT).

## [Jul 09, 2020](/content/2020/07/09/README.md)

### Web Development

*   [Lisp Web Tales](https://leanpub.com/lispwebtales) - Simple tutorials using [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis (⭐180)](https://github.com/vseloved/cl-redis), [restas (⭐252)](https://github.com/archimag/restas), [SEXML (⭐22)](https://github.com/madnificent/SEXML), [Postmodern (⭐357)](https://github.com/marijnh/Postmodern), and more.

## [Jul 02, 2020](/content/2020/07/02/README.md)

### CLOS extensions

*   [dynamic-mixins (⭐28)](https://github.com/rpav/dynamic-mixins) - simple, dynamic class combination. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

## [Jun 30, 2020](/content/2020/06/30/README.md)

### Geany (experimental) / Third-party APIs

*   [Geany-lisp (⭐10)](https://github.com/jasom/geany-lisp) is an experimental lisp mode for the [Geany](https://geany.org/) editor.

## [Jun 24, 2020](/content/2020/06/24/README.md)

### Intermediate

*   [Lisp Tips (⭐102)](https://github.com/lisp-tips/lisp-tips/issues/) - A blog with useful tips and tricks. A continuation of [Common Lisp tips](http://lisptips.com/).
*   [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - A blog showcasing many Lisp libraries.

## [May 10, 2020](/content/2020/05/10/README.md)

### Beginner

*   [Lisp Koans (⭐3k)](https://github.com/google/lisp-koans) - The project guides the learner progressively through many Common Lisp language features.

## [May 06, 2020](/content/2020/05/06/README.md)

### ORMs

*   [cl-dbi (⭐188)](https://github.com/fukamachi/cl-dbi) - A database-independent interface for Common Lisp. [LLGPL](http://opensource.franz.com/preamble.html).
    *   [dbd-oracle (⭐4)](https://github.com/sergadin/dbd-oracle) - an Oracle database driver for CL-DBI. [LLGPL](http://opensource.franz.com/preamble.html).

### CLOS extensions

*   [fast-generic-functions (⭐86)](https://github.com/marcoheisig/fast-generic-functions) - Seal your generic functions for an extra boost in performance. [MIT](https://opensource.org/licenses/MIT).

### Macro helpers / Third-party APIs

*   [trivial-with-current-source-from (⭐33)](https://github.com/scymtym/trivial-with-current-source-form/) - Helps macro writers produce better errors for macro users. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Apr 30, 2020](/content/2020/04/30/README.md)

### Migration tools

*   [cl-migratum (⭐41)](https://github.com/dnaeon/cl-migratum) - a system which provides facilities for performing database schema migrations, designed to work with various databases. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [postmodern-passenger-pigeon (⭐6)](https://github.com/fisxoj/postmodern-passenger-pigeon/) - a migration manager for postmodern. No licence specified.

### Web frameworks / Clack plugins

*   [cl-rest-server (⭐64)](https://github.com/mmontone/cl-rest-server) - a library for writing REST web APIs. Features validation with schemas, annotations for logging, caching, permissions or authentication, documentation via Swagger, etc. [MIT](https://opensource.org/licenses/MIT).

### Others / OpenAPI, OData, OpenRPC

*   [cl-odata-client (⭐5)](https://github.com/copyleft/cl-odata-client) - Common Lisp client library for accessing [OData services](https://www.odata.org). [MIT](https://opensource.org/licenses/MIT).

## [Apr 21, 2020](/content/2020/04/21/README.md)

### Job processing / Third-party APIs

*   [SBCL's timers](http://www.sbcl.org/manual/#Timers), system-wide event schedulers.

## [Apr 14, 2020](/content/2020/04/14/README.md)

### HTML generators and templates / Isomorphic web frameworks

*   [TEN (⭐31)](https://github.com/mmontone/ten) - the completness of Djula meets the usability of Eco. [MIT](https://opensource.org/licenses/MIT).

### Writing, running scripts / Third-party APIs

*   [clawk (⭐43)](https://github.com/sharplispers/clawk) - an AWK implementation embedded into Common Lisp, to search files for lines and perform specified actions on its fields. BSD-style.

### Readline, ncurses and other graphical helpers / Third-party APIs

*   [replic (⭐30)](https://github.com/vindarel/replic/) - helpers to turn existing code into a readline application, with a focus on defining the completion of the commands' arguments. Also comes as a ready to use executable, that transforms a user's lispy init file into readline commands. [MIT](https://opensource.org/licenses/MIT).
*   [cl-ansi-term (⭐25)](https://github.com/vindarel/cl-ansi-term) - print
    colorized text, horizontal lines, progress bars, (un)ordered lists
    and tables on ANSI-compliant terminals. [GPL3](http://www.gnu.org/copyleft/gpl.html).

### Shells, shells interfaces / Third-party APIs

*   [Shelly (⭐64)](https://github.com/fukamachi/shelly) - execute Common Lisp
    functions like a shell command, without the need to write a command
    line arguments parser. And it also can be used as a Make-like
    build-tool. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Date and time / Third-party APIs

*   [periods (⭐28)](https://github.com/jwiegley/periods) - manipulating date/time objects at a higher level. With series-compatible data structure. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Mar 17, 2020](/content/2020/03/17/README.md)

### Erlang

*   [CLERIC (⭐33)](https://github.com/flambard/CLERIC) - a Common Lisp Erlang Interface. An implementation of the Erlang distribution protocol, comparable with erl\_interface and jinterface. [MIT](https://opensource.org/licenses/MIT).

### Apps / Third-party APIs

*   [CodePlayground](https://codeplayground.app/) - an iPhone and iPad app with Lisp support via CCL.

### Developer utilities / Third-party APIs

*   [GTFL](http://www.martin-loetzsch.de/gtfl/) - A graphical terminal for Lisp, meant for Lisp programmers who want to debug or visualize their own algorithms. A graphical trace in the browser. BSD-style.

## [Mar 10, 2020](/content/2020/03/10/README.md)

### Community

*   [Common Lisp chat](https://chat.hexstreamsoft.com/) - Keybase team with well-defined rules and retention policies.

### Vim & Neovim / Third-party APIs

*   [Vlime (⭐401)](https://github.com/vlime/vlime) - VLIME: Vim plus Lisp Is Mostly Evil. A Common Lisp dev environment for Vim (and Neovim). [MIT](https://opensource.org/licenses/MIT).

## [Mar 05, 2020](/content/2020/03/05/README.md)

### Deployment / Isomorphic web frameworks

*   [s2i-lisp (⭐28)](https://github.com/container-lisp/s2i-lisp) - Source-to-Image builder image based on CentOS or alternatively RHEL7 for building Common LISP images for OpenShift (and also Docker). It features an up-to-date SBCL with Quicklisp installation, SLIME or SLY integration and allows customization via environment variables. [Apache2](https://directory.fsf.org/wiki/License:Apache2.0)

### Others / Third-party APIs

*   [Petalisp (⭐403)](https://github.com/marcoheisig/Petalisp) - an attempt to
    generate high performance code for parallel computers by
    JIT-compiling array definitions. It works on a more
    fundamental level than NumPy, by providing even more powerful
    N-dimensional arrays, but just a few building blocks for working on
    them. [AGPL-3.0](https://directory.fsf.org/wiki/License:AGPL-3.0).

### Matrix libraries / Third-party APIs

*   [clem (⭐37)](https://github.com/slyrus/clem) - a matrix library. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

### REPLs / Third-party APIs

*   [magic-ed (⭐21)](https://github.com/sanel/magic-ed) - a tiny editing facility, where you can directly load, edit, manipulate and evaluate file or file content from the REPL, when going to a full IDE is too much. [MIT](https://opensource.org/licenses/MIT).

### Developer utilities / Third-party APIs

*   [cl-debug](https://github.com/LowH/cl-debug) - a cross-package debug facility. Provides a unified way to enable or disable debug-specific code. Debugging code can be enabled or disabled relative to program features denoted by either a symbol or a keyword. ISC licence.
*   [supertrace (⭐25)](https://github.com/fukamachi/supertrace) - Superior Common Lisp `trace` functionality for debugging/profiling. Trace many functions at once, use before and after hooks. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

### Security / Third-party APIs

*   [cl-isolated (⭐35)](https://github.com/kanru/cl-isolated) - A restricted environment for Common Lisp code evaluation [AGPL-3.0](https://directory.fsf.org/wiki/License:AGPL-3.0).

## [Feb 19, 2020](/content/2020/02/19/README.md)

### Monitoring / Isomorphic web frameworks

*   [cl-sentry-client (⭐22)](https://github.com/mmontone/cl-sentry-client) - a Sentry client for Common Lisp, the cloud-based error monitoring system. [MIT](https://opensource.org/licenses/MIT).

## [Feb 15, 2020](/content/2020/02/15/README.md)

### Miscellaneous

*   [cl-jpeg (⭐21)](https://github.com/sharplispers/cl-jpeg) - Baseline JPEG encoder and decoder library. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Developer utilities / Third-party APIs

*   [flight-recorder (⭐13)](https://github.com/vseloved/flight-recorder) - a robust REPL history facility.
*   [cl-flamegraph (⭐65)](https://github.com/40ants/cl-flamegraph) - A wrapper around SBCL's statistical profiler, to generate FlameGraph charts for Common Lisp programs. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Feb 11, 2020](/content/2020/02/11/README.md)

### C, C++

*   [Software-Evolution-Library (⭐158)](https://github.com/GrammaTech/sel) - The SEL enables the programmatic modification and evaluation of software (C/C++ support using Clang, compiled assembler, and linked ELF binaries). [GPL3](http://www.gnu.org/copyleft/gpl.html).

### C

*   [cl-bindgen (⭐23)](https://github.com/sdilts/cl-bindgen) - A command line tool and library for creating Common Lisp language bindings from C header files. [MIT](https://opensource.org/licenses/MIT).

## [Feb 05, 2020](/content/2020/02/05/README.md)

### Tools

*   [cl-competitive (⭐160)](https://github.com/privet-kitty/cl-competitive) - Common Lisp algorithms collection for competitive programming. Public domain, CCO or MIT.

### Readline, ncurses and other graphical helpers / Third-party APIs

*   [Linedit](https://common-lisp.net/project/linedit) - Readline-style
    library that provides customizable line-editing
    features. [MIT-style](https://common-lisp.net/project/linedit/license.html).

### Developer utilities / Third-party APIs

*   [tracer (⭐50)](https://github.com/TeMPOraL/tracer) - tracing profiler for Common Lisp, with output suitable for display in Chrome’s/Chromium’s Tracing Viewer. [MIT](https://opensource.org/licenses/MIT).

## [Feb 03, 2020](/content/2020/02/03/README.md)

### Iteration

*   [gmap (⭐16)](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp) - A concise and extensible iteration facility that has the advantage of integrating well with FSet (see the Data Structures section), as it was written by the same author. In Quicklisp as part of `misc-extensions`. Public domain.

### Typing

*   [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/) - a collection of macros for easy inclusion of type declarations for arguments in lambda lists. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html)

### Others / Third-party APIs

*   [array-operations (⭐42)](https://github.com/bendudson/array-operations) - a collection of functions and macros for manipulating Common Lisp arrays and performing numerical calculations with them. [MIT](https://opensource.org/licenses/MIT).
*   [cl-geometry (⭐48)](https://github.com/Ramarren/cl-geometry/) - a system for two dimensional computational geometry for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Jan 24, 2020](/content/2020/01/24/README.md)

### C

*   [cl-gobject-introspection (⭐44)](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/) FFI. Automatic bindings to call into the C library. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause). Generate a lisp interface with [gir2cl (⭐7)](https://github.com/kat-co/gir2cl). [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

## [Jan 06, 2020](/content/2020/01/06/README.md)

### Tools

*   [base-lisp-image (⭐35)](https://github.com/40ants/base-lisp-image) - base
    Docker image for Common Lisp projects with SBCL or CCL and the latest
    ASDF, Qlot and Roswell.

### Online editors / Third-party APIs

*   [Judge0 IDE](https://ide.judge0.com/?lUpj) is an online editor which supports Common Lisp (SBCL). [MIT](https://opensource.org/licenses/MIT).

## [Jan 02, 2020](/content/2020/01/02/README.md)

### Tools

*   [hash-set (⭐15)](https://github.com/samebchase/hash-set/) - a convenience library implementing hash sets on top of CL hash tables [The Unlicense](http://unlicense.org/)
*   [cl-containers](https://common-lisp.net/project/cl-containers/) - an extensive library of data structures and utilities - queues, trees, heaps, doubly-linked lists, sets, bags,... [MIT](https://opensource.org/licenses/MIT)

## [Dec 14, 2019](/content/2019/12/14/README.md)

### Miscellaneous

*   [IUP (⭐126)](https://github.com/lispnik/iup/) - CFFI bindings to the [IUP](https://www.tecgraf.puc-rio.br/iup/) Portable User Interface library (pre-ALPHA). IUP is cross-platform (Windows, macOS, GNU/Linux, with new Android, iOs, Cocoa and Web Assembly drivers), has many widgets, has a small api and is actively developed.

## [Dec 13, 2019](/content/2019/12/13/README.md)

### Mobile

*   [rutils (⭐234)](https://github.com/vseloved/rutils) - radical yet reasonable syntactic utilities for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Nov 26, 2019](/content/2019/11/26/README.md)

### C, C++

*   [cl-yesql (⭐57)](https://github.com/ruricolist/cl-yesql) - SQL statements live in their own files, in SQL syntax, and are imported into Lisp as functions. You are not limited to the features a DSL supports. Based on Clojure's Yesql. [MIT](https://opensource.org/licenses/MIT).

## [Nov 19, 2019](/content/2019/11/19/README.md)

### Tools

*   👍 [str (⭐267)](https://github.com/vindarel/cl-str) - a modern, simple and consistent string manipulation library. [MIT](https://opensource.org/licenses/MIT).
*   [trivial-extensible-sequences (⭐11)](https://github.com/Shinmera/trivial-extensible-sequences) - Portability library for the extensible sequences protocol ([SBCL documentation](http://www.sbcl.org/manual/#Extensible-Sequences)). [zlib](https://directory.fsf.org/wiki/License:Zlib).
*   [listopia (⭐28)](https://github.com/Dimercel/listopia) - a list manipulation library inspired by Haskell's Data.List. [LLGPL](http://opensource.franz.com/preamble.html).
*   👍 [access (⭐78)](https://github.com/AccelerationNet/access/) - Consistent and nested access to most common data structures. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [modf (⭐56)](https://github.com/smithzvk/modf) - a setf-like macro for functional programming.

### Mobile

*   [generic-cl (⭐118)](https://github.com/alex-gutev/generic-cl/) - Generic function interface to standard Common Lisp functions (equality, comparison, arithmetic, objects, iterator, sequences,…). [MIT](https://opensource.org/licenses/MIT). See also the more lightweight [generic-comparability (⭐14)](https://github.com/pnathan/generic-comparability). [LLGPL](http://opensource.franz.com/preamble.html).

### Changing the syntax

*   [cl21 (⭐898)](https://github.com/cl21/cl21) - An experimental project to move Common Lisp into the 21st century. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-syntax (⭐36)](https://github.com/m2ym/cl-syntax) - Reader syntax conventions. [LLGPL](http://opensource.franz.com/preamble.html).
*   [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax) - An indentation-sensitive reader system. Not available on Quicklisp. Public domain.
*   [cl-annot (⭐128)](https://github.com/m2ym/cl-annot) - Python-like annotations for Common Lisp. [LLGPL](http://opensource.franz.com/preamble.html).
    *   [cl-annot-revisit (⭐6)](https://github.com/y2q-actionman/cl-annot-revisit/) -  re-implementation of cl-annot. WTFPL.
*   [cl-reader (⭐10)](https://github.com/digikar99/reader) - A utility library
    intended at providing reader macros for lambdas, mapping, accessors,
    hash-tables and hash-sets. [MIT](https://opensource.org/licenses/MIT).

### Files and directories / Third-party APIs

*   [ppath (⭐26)](https://github.com/fourier/ppath) - Common Lisp's
    implementation of the Python's os.path module. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [mmap (⭐29)](https://github.com/Shinmera/mmap) - Portable mmap file memory mapping utility library. [zlib](https://directory.fsf.org/wiki/License:Zlib).

## [Nov 12, 2019](/content/2019/11/12/README.md)

### Mobile

*   [jonathan (⭐158)](https://github.com/Rudolph-Miller/jonathan) - A JSON encoder and decoder. [MIT](https://opensource.org/licenses/MIT).

### Community

*   [Planet Lisp](http://planet.lisp.org/) - A meta blog that collects the contents of various Lisp-related blogs.

## [Nov 03, 2019](/content/2019/11/03/README.md)

### CLOS extensions

*   [filtered-functions (⭐41)](https://github.com/pcostanza/filtered-functions) - enable the use of arbitrary predicates for selecting and applying methods. [MIT](https://opensource.org/licenses/MIT).

## [Oct 18, 2019](/content/2019/10/18/README.md)

### Persistent object databases

*   [cl-prevalence](https://common-lisp.net/project/cl-prevalence/) - in-memory database system. Implementation of Object Prevalence, in which business objects are kept live in memory and transactions are journaled for system recovery. [github fork (⭐28)](https://github.com/40ants/cl-prevalence). [LLGPL](http://opensource.franz.com/preamble.html).
    *   See also [cl-prevalence-multimaster (⭐3)](https://github.com/40ants/cl-prevalence-multimaster), to syncronize multiple cl-prevalence systems state.

### HTTP clients / Interfaces to other package managers

*   [fast-http (⭐333)](https://github.com/fukamachi/fast-http) - A fast HTTP request/response parser for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

### HTTP Servers / Interfaces to other package managers

*   [zaserve (⭐7)](https://github.com/gendl/aserve) - A portable fork of AllegroServe, by Franz Inc.  [LLGPL](http://opensource.franz.com/preamble.html).
*   [cl-http2-protocol (⭐102)](https://github.com/akamai/cl-http2-protocol) - a pure Common Lisp transport agnostic implementation of the HTTP/2 protocol at draft-14. [MIT](https://opensource.org/licenses/MIT).

### HTTP Servers / Hunchentoot plugins

*   [hunchentoot-cgi (⭐5)](https://github.com/slyrus/hunchentoot-cgi) - a library for executing CGI scripts from the hunchentoot webserver. [BSD](https://opensource.org/licenses/bsd-license.php).
*   [hunchentoot-multi-acceptor (⭐6)](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/) - Route multiple domains (virtual hosts) on a single hunchentoot acceptor using a single port. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### Javascript / Isomorphic web frameworks

*   ⭐ [Parenscript](https://common-lisp.net/project/parenscript/) - A translator from Common Lisp to Javascript. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause). See [Trident-mode (⭐72)](https://github.com/johnmastro/trident-mode.el), an Emacs mode that provides live interaction with the browser.[unlicence](http://unlicense.org/).
    *   [paren6 (⭐21)](https://github.com/BnMcGn/paren6/) - a set of ES6 macros for Parenscript.

### Others / Third-party APIs

*   [avm (⭐53)](https://github.com/takagi/avm) - Efficient and expressive arrayed vector math library with multi-threading and CUDA support. [MIT](https://opensource.org/licenses/MIT).

### Utils / Third-party APIs

*   [cl-coroutine (⭐59)](https://github.com/takagi/cl-coroutine) - a coroutine library. It uses the CL-CONT continuations library in its implementation. [MIT](https://opensource.org/licenses/MIT).

### Actors pattern / Third-party APIs

*   [erlangen (⭐65)](https://github.com/eugeneia/erlangen) - Distributed, asynchronous message passing system for Clozure Common Lisp. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html).
*   [Actors (⭐11)](https://github.com/aarvid/Actors) package for LispWorks ([announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)) [MIT](https://opensource.org/licenses/MIT).
*   [common-lisp-actors (⭐104)](https://github.com/naveensundarg/Common-Lisp-Actors) - a simple and easy to use Actor system. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).
*   [memento-mori (⭐32)](https://github.com/zkat/memento-mori)-  a library for writing robust, actor-based systems. It draws inspiration from Erlang/OTP, particularly its crash-first approach to high-availability systems, as well as Akka. [MIT](https://opensource.org/licenses/MIT).

### Date and time / Third-party APIs

*   [calendar-date (⭐8)](https://github.com/takagi/calendar-date) - a Gregorian calendar date library. [MIT](https://opensource.org/licenses/MIT).

## [Oct 11, 2019](/content/2019/10/11/README.md)

### Javascript / Isomorphic web frameworks

*   [remote-js (⭐33)](https://github.com/ceramic/remote-js) - send JavaScript from Common Lisp to a browser. [MIT](https://opensource.org/licenses/MIT).

## [Sep 29, 2019](/content/2019/09/29/README.md)

### Community / Interfaces to other package managers

*   [dh-quicklisp-buildapp (⭐7)](https://github.com/ralt/dh-quicklisp-buildapp) - debhelper utility to let you compile your quicklisp-based Common Lisp code into a buildapp binary in a .deb with almost no effort. [MIT](https://opensource.org/licenses/MIT).

## [Sep 17, 2019](/content/2019/09/17/README.md)

### Function extensions

*   [cl-hooks (⭐14)](https://github.com/scymtym/architecture.hooks/) - Hooks extension point mechanism (as known, e.g., from GNU Emacs). LGPL.
*   [method-hooks](https://gitlab.com/Gnuxie/method-hooks) - When CLOS method combination allow only one hook per method, this library allows an arbitrary number of them. Mozilla Public Licence.

### Typing

*   👍 [trivial-types (⭐63)](https://github.com/m2ym/trivial-types) - provides missing but important type definitions such as `proper-list`, `association-list`, `property-list` and `tuple`. [LLGPL](http://opensource.franz.com/preamble.html).

## [Aug 25, 2019](/content/2019/08/25/README.md)

### CLOS extensions

*   [inlined-generic-function (⭐108)](https://github.com/guicho271828/inlined-generic-function) -
    Bringing the speed of Static Dispatch to CLOS. [LLGPL](http://opensource.franz.com/preamble.html).
*   [static-dispatch (⭐70)](https://github.com/alex-gutev/static-dispatch) - allows standard generic function dispatch to be performed statically (at compile time) rather than dynamically (runtime). This is similar to what is known as "overloading" in languages such as C++ and Java. [MIT](https://opensource.org/licenses/MIT).

### Configuration / Third-party APIs

*   [chameleon (⭐17)](https://github.com/sheepduke/chameleon/) - a configuration management library shipped with profile support. [MIT](https://opensource.org/licenses/MIT).

### Logging / Third-party APIs

*   [a-cl-logger (⭐12)](https://github.com/AccelerationNet/a-cl-logger) - Logging library providing context sensitive logging of more than just strings to more than just local files or output streams. Features logstash support, json support, logger hierarchies, context sensitive logging, objects printed as an inspectable presentation,…

## [Aug 23, 2019](/content/2019/08/23/README.md)

### Others / Third-party APIs

*   [linear-programming](https://neil-lindquist.github.io/linear-programming/) – a library for solving linear programming problems. [MIT](https://opensource.org/licenses/MIT).

## [Aug 22, 2019](/content/2019/08/22/README.md)

### Reference

*   [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - The standard draft of the Common Lisp specifications, in a well formatted PDF with a sidebar.

### Other / Third-party APIs

*   [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/) - A small library for doing UTF-8-based I/O. BSD.

## [Aug 10, 2019](/content/2019/08/10/README.md)

### Deployment / Isomorphic web frameworks

*   [Heliohost](https://www.heliohost.org/) for a free hosting solution.

## [Aug 06, 2019](/content/2019/08/06/README.md)

### Mobile

*   [LispWorks](http://www.lispworks.com/) - an integrated cross-platform development tool for Common Lisp.
    *   reputed features include: the CAPI cross-platform and native GUI toolkit, the LispWorks IDE, the mobile platforme runtime (iOs, Android), its Java interface, the tree shaker to build lighter binaries, its KnowledgeWorks system for "rule-based, object-oriented, logical, functional and database programming", and more.
    *   has a free edition, with limitations (heap size limit, time limit).

## [Jul 30, 2019](/content/2019/07/30/README.md)

### Utils / Third-party APIs

*   [swank-crew (⭐36)](https://github.com/brown/swank-crew) - distributed computation framework implemented using Swank Client. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Jul 20, 2019](/content/2019/07/20/README.md)

### Lambda shorthands

*   [cl-punch (⭐21)](https://github.com/windymelt/cl-punch/) - Scala-like anonymous lambda literals. `(mapcar ^(* 2 _) '(1 2 3 4 5))`. [MIT](https://opensource.org/licenses/MIT).

## [Jul 10, 2019](/content/2019/07/10/README.md)

### Data validation / Third-party APIs

*   [sanity-clause (⭐46)](https://github.com/fisxoj/sanity-clause) - a data serialization/contract library for Common Lisp. Schemas can be property lists or class-based, allowing to check slots' types during `make-instance`. [LLGPL](http://opensource.franz.com/preamble.html).

## [Jul 08, 2019](/content/2019/07/08/README.md)

### CLOS extensions

*   [specialization-store (⭐28)](https://github.com/markcox80/specialization-store/) - generic functions based on types. Simplified BSD License variant.

## [Jul 07, 2019](/content/2019/07/07/README.md)

### Community

*   [Lisp Discord Server](https://discord.gg/hhk46CE)

## [Jun 22, 2019](/content/2019/06/22/README.md)

### .Net Core

*   [Bike (⭐122)](https://github.com/Lovesan/bike) - a cross-platform .Net Core interface. [MIT](https://opensource.org/licenses/MIT).

### Miscellaneous

*   [Foil](http://foil.sourceforge.net/) - A foreign object interface; works with the JVM and CLI. Not available on Quicklisp. [CPL 1.0](https://directory.fsf.org/wiki/License:CPLv1.0).

## [Jun 21, 2019](/content/2019/06/21/README.md)

### Community / Interfaces to other package managers

*   [babel2 (⭐5)](https://github.com/lucas8/Babel2/) - A Fluid Construction Grammar implementation, computational framework, and unification-based grammar formalism [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### Other scripting utilities / Third-party APIs

*   [WCL (⭐74)](https://github.com/wadehennessey/wcl) \[stalled] - allow hundreds of Lisp
    applications to be realistically available at once, while allowing
    several of them to run concurrently.  WCL accomplishes this by
    providing Common Lisp as a Unix shared library that can be linked with
    Lisp and C code to produce efficient applications.  For example, the
    executable for a Lisp version of the canonical `Hello World!`
    program requires only 20k bytes on 32 bit x86 Linux.  WCL also
    supports a full development environment, including dynamic file
    loading and debugging.  A modified version of GDB is used to debug WCL
    programs, providing support for mixed language debugging.
    *   a [paper](https://dl.acm.org/doi/abs/10.1145/141478.141560): "Delivering efficient Common Lisp applications under Unix".

## [Jun 18, 2019](/content/2019/06/18/README.md)

### Developer utilities / Third-party APIs

*   [repl-utilities (⭐49)](https://github.com/m-n/repl-utilities) - Ease
    common tasks at the REPL (print documentation, print external symbols,
    call hooks when loading a package,…). [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

## [May 23, 2019](/content/2019/05/23/README.md)

### Python

*   [cl4py (⭐82)](https://github.com/marcoheisig/cl4py) - The library cl4py (pronounce as clappy) allows Python programs to call Common Lisp libraries. [MIT](https://opensource.org/licenses/MIT).
*   [py4cl (⭐201)](https://github.com/bendudson/py4cl) - A library that allows Common Lisp code to access Python libraries. It is basically the inverse of cl4py. [MIT](https://opensource.org/licenses/MIT).
*   [cl-python (⭐359)](https://github.com/metawilm/cl-python) - an implementation of Python in Common Lisp. [LLGPL](http://opensource.franz.com/preamble.html), not under active development.

## [May 22, 2019](/content/2019/05/22/README.md)

### Utils / Third-party APIs

*   [cl-gearman (⭐22)](https://github.com/taksatou/cl-gearman) - a library for the [Gearman](http://gearman.org/) distributed job system. [LLGPL](http://opensource.franz.com/preamble.html).

## [May 16, 2019](/content/2019/05/16/README.md)

### Miscellaneous

*   [bodge-nuklear (⭐57)](https://github.com/borodust/bodge-nuklear) - Wrapper over the [Nuklear (⭐7.9k)](https://github.com/Immediate-Mode-UI/Nuklear) immediate mode GUI library. [MIT](https://opensource.org/licenses/MIT).

### Others / Third-party APIs

*   [cl-ana (⭐191)](https://github.com/ghollisjr/cl-ana) - Common Lisp data analysis library with emphasis on modularity and conceptual clarity. It aims to be a general purpose framework for analyzing small and large scale datasets, including binned data analysis and visualization. [GNU GPL3](http://www.gnu.org/copyleft/gpl.html).

## [May 15, 2019](/content/2019/05/15/README.md)

### Others / Third-party APIs

*   [numcl (⭐621)](https://github.com/numcl/numcl) - Numpy clone in Common Lisp. [LGPL3](https://www.gnu.org/licenses/lgpl-3.0.en.html).

## [Apr 17, 2019](/content/2019/04/17/README.md)

### CSV / Third-party APIs

*   [auto-text (⭐10)](https://github.com/defunkydrummer/auto-text) - automatic (encoding, end of line, column width, csv delimiter etc) detection for text files. [MIT](https://opensource.org/licenses/MIT). See also [inquisitor (⭐33)](https://github.com/t-sin/inquisitor) for detection of asian and far eastern languages.

## [Apr 08, 2019](/content/2019/04/08/README.md)

### Atom, Pulsar / Third-party APIs

*   [SLIMA (⭐63)](https://github.com/neil-lindquist/slima) allows you to
    interactively develop Common Lisp code, turning Atom (or now Pulsar) into a
    pretty good, and actively developped, Lisp IDE. [MIT](https://opensource.org/licenses/MIT).

## [Mar 13, 2019](/content/2019/03/13/README.md)

### Utils / Third-party APIs

*   [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
    a Common Lisp library offering a way of spawning threads and being
    informed when one any of them crash and die. [MIT](https://opensource.org/licenses/MIT).

## [Mar 01, 2019](/content/2019/03/01/README.md)

### Community

*   [Ultralisp](http://ultralisp.org/) - A Quicklisp distribution which updates every 5 minutes and to which one can add his project in one click. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Deployment / Isomorphic web frameworks

*   [cl-aws-runtime-test (⭐36)](https://github.com/y2q-actionman/cl-aws-custom-runtime-test) - An example of using Common Lisp (SBCL) as a custom runtime on AWS lambda. WTFPL.

## [Feb 26, 2019](/content/2019/02/26/README.md)

### Miscellaneous

*   [eql, eql5, eql5-android](https://gitlab.com/eql) - Embedded Qt4 and Qt5 Lisp, embedded in ECL, embeddable in Qt. Port of EQL5 to the Android platform. [MIT](https://opensource.org/licenses/MIT).

## [Feb 20, 2019](/content/2019/02/20/README.md)

### Tools

*   [cl-data-structures (⭐40)](https://github.com/sirherrbatka/cl-data-structures) - a portable collection of data structures and algorithms (mainly dicts and sequences, with some statistical functions). [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Feb 16, 2019](/content/2019/02/16/README.md)

### PDF / Third-party APIs

*   [cl-typesetting (⭐65)](https://github.com/mbattyani/cl-typesetting) and [cl-pdf (⭐106)](https://github.com/mbattyani/cl-pdf) - cross-platform Common Lisp libraries for generating PDF files. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

## [Jan 30, 2019](/content/2019/01/30/README.md)

### Tools

*   [cl-ctrie (⭐110)](https://github.com/danlentz/cl-ctrie) -
    lock-free, concurrent, key/value index with efficient memory-mapped persistence and fast transient storage models. [MIT](https://opensource.org/licenses/MIT).

### Javascript / Isomorphic web frameworks

*   [trident-mode (⭐72)](https://github.com/johnmastro/trident-mode.el), an Emacs minor mode for live Parenscript interaction.

### Monitoring / Isomorphic web frameworks

*   [prometheus.cl (⭐79)](https://github.com/deadtrickster/prometheus.cl) - Prometheus.io client. Grafana dashboard for SBCL and Hunchentoot metrics (memory, threads, requests per second,…). [MIT](https://opensource.org/licenses/MIT).
    *   [prometheus-g (⭐1)](https://github.com/40ants/prometheus-gc) - Extension for prometheus.cl which collects metrics about garbage collector state.

## [Jan 15, 2019](/content/2019/01/15/README.md)

### Date and time / Third-party APIs

*   [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date) - Miscellaneous date routines in Common Lisp, based around the ISO 8601 string representation. [LLGPL](http://opensource.franz.com/preamble.html).

## [Dec 21, 2018](/content/2018/12/21/README.md)

### Vim & Neovim / Third-party APIs

*   [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - A Quicklisp frontend for Neovim.

## [Dec 20, 2018](/content/2018/12/20/README.md)

### Lambda shorthands

*   [fn (⭐23)](https://github.com/cbaggers/fn) - a couple of lambda shorthand macros. `(fn* (+ _ _))  -->  (lambda (_) (+ _ _))`. Public domain.

### HTTP clients / Interfaces to other package managers

*   [Carrier (⭐37)](https://github.com/orthecreedence/carrier) - A lightweight, async HTTP client built on top of cl-async and fast-http. [MIT](https://opensource.org/licenses/MIT).

### Others / Third-party APIs

*   [Xecto (⭐42)](https://github.com/pkhuong/Xecto) - A library for regular array parallelism. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Event processing / Third-party APIs

*   [event-glue (⭐19)](https://github.com/orthecreedence/event-glue) - simple eventing abstraction. No dependencies. It can be used anywhere you need a generic event handling system. [MIT](https://opensource.org/licenses/MIT).

## [Dec 18, 2018](/content/2018/12/18/README.md)

### Eclipse / Third-party APIs

*   [Dandelion (⭐32)](https://github.com/Ragnaroek/dandelion) - a Common Lisp plugin for the Eclipse IDE.

## [Dec 13, 2018](/content/2018/12/13/README.md)

### Vim & Neovim / Third-party APIs

*   [Slimv\_box (⭐14)](https://github.com/justin2004/slimv_box) - slimv in a Docker container.

## [Dec 06, 2018](/content/2018/12/06/README.md)

### Mobile

*   [MOCL](https://wukix.com/mocl) - CL as a library for mobile devices (iOS & Android) and OSX.

## [Nov 30, 2018](/content/2018/11/30/README.md)

### Tools

*   [genhash (⭐15)](https://github.com/pnathan/genhash) – hash table implementation with API from generic methods. Public domain.

## [Nov 14, 2018](/content/2018/11/14/README.md)

### Community

*   [/r/Common\_Lisp](https://www.reddit.com/r/Common_Lisp/) - subreddit about Common Lisp
*   [common-lisp.net](https://common-lisp.net)
*   [lisp-lang.org](https://lisp-lang.org/)

## [Nov 08, 2018](/content/2018/11/08/README.md)

### HTTP Servers / Clack plugins

*   [clack-static-asset-middleware (⭐1)](https://github.com/fisxoj/clack-static-asset-middleware) - a cache-busting static asset middleware for the clack. [MIT](https://opensource.org/licenses/MIT).

## [Oct 30, 2018](/content/2018/10/30/README.md)

### Wrappers

*   [cl-sqlite (⭐63)](https://github.com/dmitryvk/cl-sqlite) - Bindings for SQLite. Public domain.
*   [cl-memcached (⭐21)](https://github.com/quasi/cl-memcached) - Fast, thread-safe interface to the Memcached object caching system. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-mongo (⭐138)](https://github.com/fons/cl-mongo) - MongoDB client. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-redis (⭐180)](https://github.com/vseloved/cl-redis) - Redis client. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-disque (⭐13)](https://github.com/CodyReichert/cl-disque) - Disque client. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-rethinkdb (⭐47)](https://github.com/orthecreedence/cl-rethinkdb) - RethinkDB client. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Tools

*   ⭐ [pgloader (⭐4.8k)](https://github.com/dimitri/pgloader) - a data loading tool for PostgreSQL. [PostgreSQL Licence](https://www.postgresql.org/about/licence/).

### C

*   👍[cl-autowrap (⭐201)](https://github.com/rpav/cl-autowrap) - Automatically parses header files into CFFI definitions. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

### Miscellaneous

*   [common-cv (⭐55)](https://github.com/byulparan/common-cv) - the OpenCV (Open Source Computer Vision Library) binding library for CommonLisp. No license specified.
*   [ftw (⭐55)](https://github.com/fjames86/ftw) - A Win32 GUI library. [MIT](https://opensource.org/licenses/MIT).

### Mobile

*   [ECL](https://common-lisp.net/project/ecl/) - Embeddable Common Lisp; compiles to C. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
*   [CLASP (⭐2.4k)](https://github.com/drmeister/clasp) - a new Common Lisp implementation that seamlessly interoperates with C++ libraries and programs using LLVM for compilation to native code. This allows Clasp to take advantage of a vast array of preexisting libraries and programs, such as out of the scientific computing ecosystem. [LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) (and others).
*   [Allegro CL](https://franz.com/products/allegro-common-lisp/) - provides the full ANSI Common Lisp standard with many extensions.
    *   reputed features include: the AllegroCache object persistence database system, the KnowledgeGraph system, its concurrent garbage collector, its web-based IDE, and more.
    *   has a free edition. It includes AllegroCache, with a size limit.

### Community

*   👍[Roswell (⭐1.7k)](https://github.com/roswell/roswell) - a Lisp implementation installer, script launcher and more. [MIT](https://opensource.org/licenses/MIT).

### HTML generators and templates / Isomorphic web frameworks

*   👍 [spinneret (⭐330)](https://github.com/ruricolist/spinneret) - Common Lisp HTML5 generator. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Utils / Third-party APIs

*   [lfarm (⭐102)](https://github.com/lmj/lfarm) - distributing work across machines (on top of lparallel and usocket). [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause)

### Emacs / Third-party APIs

*   👍 [Sly (⭐1.1k)](https://github.com/joaotavora/sly) - SLY is a fork of SLIME and contains multiple improvements upon it.
*   👍 [Portacle](https://shinmera.github.io/portacle/) - A portable and multiplatform Common Lisp environment: SBCL, Quicklisp, Emacs, Slime, Git.

### Configuration / Third-party APIs

*   👍 [py-configparser](https://common-lisp.net/project/py-configparser/) - reads and writes Python's ConfigParser-like configuration files. [MIT](https://opensource.org/licenses/MIT).

### Other / Third-party APIs

*   as such, the libraries we like best are marked with a 👍 (`1F44D`
    unicode character). See also the signs' explanation in the
    introduction.

## [Oct 28, 2018](/content/2018/10/28/README.md)

### Data validation / Third-party APIs

*   [clavier (⭐17)](https://github.com/mmontone/clavier) - General purpose validation library for Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Oct 24, 2018](/content/2018/10/24/README.md)

### Non-deterministic, logic programming

*   [Screamer (⭐218)](https://github.com/nikodemus/screamer) - augment Common
    Lisp with practically all of the functionality of both Prolog and
    constraint logic programming
    languages. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
    solving Project Euler puzzles. [MIT](https://opensource.org/licenses/MIT).
*   [Screamer+ (⭐6)](https://github.com/yakovzaytsev/screamer-plus) - increasing the expressiveness of SCREAMER. [MIT](https://opensource.org/licenses/MIT).

## [Oct 13, 2018](/content/2018/10/13/README.md)

### CSV / Third-party APIs

*   [cl-decimals (⭐19)](https://github.com/tlikonen/cl-decimals) - Decimal number parser and formatter. Public domain.

## [Oct 11, 2018](/content/2018/10/11/README.md)

### Community

*   [print-licenses (⭐19)](https://github.com/vindarel/print-licenses) - print licenses used by a project and its dependencies. [MIT](https://opensource.org/licenses/MIT).

## [Oct 10, 2018](/content/2018/10/10/README.md)

### Mobile

*   [cl-yacclyaml (⭐13)](https://github.com/mabragor/cl-yaclyaml) - a pure lisp YAML processor (loader, but not yet dumper). [GPL3](http://www.gnu.org/copyleft/gpl.html).
*   [cl-yaml](https://github.com/eudoxia0/cl-yaml.git) - a YAML parser and emitter built on top of libyaml. [MIT](https://opensource.org/licenses/MIT).

## [Oct 08, 2018](/content/2018/10/08/README.md)

### i18n / Third-party APIs

*   [cl-i18n](https://notabug.org/cage/cl-i18n) - an i18n library. Load translations from GNU gettext text or binary files or from its native format. Localisation helpers of plural forms. [LLGPL](http://opensource.franz.com/preamble.html).

## [Sep 28, 2018](/content/2018/09/28/README.md)

### Readline, ncurses and other graphical helpers / Third-party APIs

*   [cl-progress-bar (⭐17)](https://github.com/sirherrbatka/cl-progress-bar/) - progress bars, just like in Quicklisp ! [MIT](https://opensource.org/licenses/MIT).

### Other / Third-party APIs

*   by default, add a library to the end of its section.
*   two libraries very similar in scope should be side by side, or in a
    section of their own.
*   do some curation based on your experience and the state of the
    library's documentation. We do *not* aim at listing every existing
    CL library (see Cliki for that) nor to list every
    "popular" library (see Quicklisp stats).

## [Aug 22, 2018](/content/2018/08/22/README.md)

### Reactive programming

*   [Cells (⭐201)](https://github.com/kennytilton/cells) - an implementation of the dataflow programming paradigm, reactive spreadsheet-like expressiveness for CLOS. Used to build an [algebra learning system](http://tiltontec.com/). With [documentation (⭐19)](https://github.com/stefano/cells-doc/). Lisp LGPL.

### Job processing / Third-party APIs

*   [clerk (⭐19)](https://github.com/tsikov/clerk) - a cron-like scheduler with sane DSL. [MIT](https://opensource.org/licenses/MIT).

## [Aug 21, 2018](/content/2018/08/21/README.md)

### Contract programming

*   [quid-pro-quo (⭐93)](https://github.com/sellout/quid-pro-quo) - a contract
    programming library in the style of Eiffel’s Design by Contract ™. Public domain.

### Beginner

*   [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - Small Common Lisp tutorial covering the essentials.
*   [Successful Lisp](http://successful-lisp.blogspot.com/) - A good book for beginners with some programming background.

## [Aug 12, 2018](/content/2018/08/12/README.md)

### Miscellaneous

*   [okra](https://www.common-lisp.net/project/okra/manual.html) - CFFI bindings to Ogre. Not available on Quicklisp. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Javascript / Isomorphic web frameworks

*   [Wuwei (⭐76)](https://github.com/mtravers/wuwei/) - A toolkit to build Ajax-based web pages. [MIT](https://opensource.org/licenses/MIT).

## [Aug 07, 2018](/content/2018/08/07/README.md)

### Miscellaneous

*   [CocoaInterface (⭐31)](https://github.com/plkrueger/CocoaInterface/) -
    Cocoa interface for Clozure Common Lisp. Build Cocoa user interface
    windows dynamically using Lisp code and bypass the typical Xcode
    processes. It has
    [good documentation and a tutorial (⭐31)](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).

## [Jul 16, 2018](/content/2018/07/16/README.md)

### HTML generators and templates / Isomorphic web frameworks

*   [cl-closure-template (⭐71)](https://github.com/archimag/cl-closure-template) - Implementation of Google's Closure templates, where compiling a template creates a function that generates the result. [LLGPL](http://opensource.franz.com/preamble.html).

## [Jul 12, 2018](/content/2018/07/12/README.md)

### Miscellaneous

*   [lisp-magick-wand (⭐11)](https://github.com/TBRSS/lisp-magick-wand) - ImageMagick bindings. [BSD](https://directory.fsf.org/wiki/License:BSD_3Clause). Not in Quicklisp.

### HTTP Servers / Clack plugins

*   [live-reload (⭐8)](https://github.com/knobo/live-reload) - Live reload prototype for clack. [LLGPL](http://opensource.franz.com/preamble.html).

### i18n / Third-party APIs

*   [enchant (⭐17)](https://github.com/tlikonen/cl-enchant) - bindings for the Enchant spell-checker library. Public domain.

## [Jun 08, 2018](/content/2018/06/08/README.md)

### Mobile

*   [json-mop (⭐58)](https://github.com/gschjetne/json-mop) - A metaclass for bridging CLOS and JSON objects. [MIT](https://opensource.org/licenses/MIT).
*   [arrow-macros (⭐115)](https://github.com/hipeta/arrow-macros) - Clojure-like threading macros. [MIT](https://opensource.org/licenses/MIT).

## [Jun 06, 2018](/content/2018/06/06/README.md)

### Non-deterministic, logic programming

*   [cl-prolog2 (⭐27)](https://github.com/guicho271828/cl-prolog2) - Common Interface to ISO Prolog implementations from Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [May 24, 2018](/content/2018/05/24/README.md)

### Date and time / Third-party APIs

*   [cl-date-time-parser (⭐17)](https://github.com/tkych/cl-date-time-parser) - Parse date-time-string, liberally. Hides the difference between date-time formats, and enables to manage date and time as the one date-time format. [MIT](https://opensource.org/licenses/MIT).

## [May 02, 2018](/content/2018/05/02/README.md)

### Apps / Third-party APIs

*   [wiki-lang-detect (⭐29)](https://github.com/vseloved/wiki-lang-detect) -
    Text language identification using Wikipedia data. No license specified.

## [Apr 07, 2018](/content/2018/04/07/README.md)

### Event processing / Third-party APIs

*   [cl-flow (⭐49)](https://github.com/borodust/cl-flow/) -  Data-flowish computation tree library for non-blocking concurrent Common Lisp. [MIT](https://opensource.org/licenses/MIT).

## [Mar 16, 2018](/content/2018/03/16/README.md)

### C, C++

*   [emotiq (⭐96)](https://github.com/emotiq/emotiq) - a next-generation blockchain with an innovative natural-language approach to smart contracts. [MIT](https://opensource.org/licenses/MIT).

### Others / Web project skeletons and generators

*   [Postmaster (⭐8)](https://github.com/eudoxia0/postmaster) - A simple, easy-to-use SMTP/IMAP library. [Expat](https://directory.fsf.org/wiki/License:Expat).

## [Feb 12, 2018](/content/2018/02/12/README.md)

### Miscellaneous

*   [cl-svg (⭐37)](https://github.com/wmannis/cl-svg) - A basic library for producing SVG files. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [Varjo (⭐211)](https://github.com/cbaggers/varjo) - Lisp to GLSL translator. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

## [Feb 06, 2018](/content/2018/02/06/README.md)

### Miscellaneous

*   [dufy (⭐42)](https://github.com/privet-kitty/dufy) - exact color manipulation and conversion in various color models. [MIT](https://opensource.org/licenses/MIT).

## [Jan 28, 2018](/content/2018/01/28/README.md)

### Reference

*   [Minispec](https://lamberta.github.io/minispec/) - A friendlier, but less-complete, version of CLHS. Also contains documentation for some commonly-used CL libraries (such as Alexandria).

## [Jan 26, 2018](/content/2018/01/26/README.md)

### Job processing / Third-party APIs

*   [psychiq (⭐49)](https://github.com/fukamachi/psychiq) - redis-based background job processing for Common Lisp applications. Inspired by Ruby's Sidekiq and compatible with its web UI. [LLGPL](http://opensource.franz.com/preamble.html).

### Logging / Third-party APIs

*   [cl-fluent-logger (⭐10)](https://github.com/fukamachi/cl-fluent-logger) - A Common Lisp structured logger for [Fluentd](https://www.fluentd.org/).

## [Jan 19, 2018](/content/2018/01/19/README.md)

### Miscellaneous

*   [opticl (⭐176)](https://github.com/slyrus/opticl) - a library for representing and processing images. [BSD\_2Clause](https://directory.fsf.org/wiki/License:BSD_2Clause).

### Apps / Third-party APIs

*   [lake](https://github.com/takagi/lake) - a GNU make like build utility. [MIT](https://opensource.org/licenses/MIT).

## [Jan 18, 2018](/content/2018/01/18/README.md)

### Readline, ncurses and other graphical helpers / Third-party APIs

*   [cl-charms (⭐139)](https://github.com/HiTECNOLOGYs/cl-charms) - an
    interface to `libcurses` in Common Lisp. It provides both a raw,
    low-level interface to libcurses via CFFI, and a more higher-level
    lispier interface. [MIT](https://opensource.org/licenses/MIT).

## [Jan 17, 2018](/content/2018/01/17/README.md)

### To third parties

*   [cl-influxdb (⭐22)](https://github.com/mmaul/cl-influxdb/) - an interface to the Time Series Database InfluxDB. [MIT](https://opensource.org/licenses/MIT).

## [Jan 16, 2018](/content/2018/01/16/README.md)

### REPLs / Third-party APIs

*   [cl-repl (⭐141)](https://github.com/koji-kojiro/cl-repl) - an ipython-like REPL. With completion, shell commands, magic commands, debugger, etc. [MIT](https://opensource.org/licenses/MIT). With [colorthemes (⭐12)](https://github.com/koji-kojiro/lem-pygments-colorthemes).

## [Jan 10, 2018](/content/2018/01/10/README.md)

### To third parties

*   [dyna (⭐20)](https://github.com/Rudolph-Miller/dyna) - an AWS DynamoDB ORM. [MIT](https://opensource.org/licenses/MIT).

### Objective-C

*   [objc-lisp-bridge (⭐40)](https://github.com/fiddlerwoaroof/objc-lisp-bridge) -  A portable reader and bridge for interacting with Objective-C and Cocoa. [MIT](https://opensource.org/licenses/MIT).

### Miscellaneous

*   [cl-webkit (⭐48)](https://github.com/joachifm/cl-webkit) - A binding to WebKitGTK+. Also adds web browsing capabilities to an application, leveraging the full power of the WebKit browsing engine. [MIT](https://opensource.org/licenses/MIT).

## [Jan 09, 2018](/content/2018/01/09/README.md)

### Beginner

*   [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - A fun way to learn LISP while reading a comic book.

### Reference

*   [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - The simplified version of CLHS.

## [Jan 08, 2018](/content/2018/01/08/README.md)

### C, C++

*   [cmacro (⭐865)](https://github.com/eudoxia0/cmacro) - Lisp macros for C. [MIT](https://opensource.org/licenses/MIT).
*   [C-mera (⭐377)](https://github.com/kiselgra/c-mera) - a source-to-source compiler that utilizes Lisp's macro system for meta programming of C-like languages. [GPL3](http://www.gnu.org/copyleft/gpl.html).
*   [lispc (⭐526)](https://github.com/eratosthenesia/lispc) - a powerful "lispsy" macrolanguage for C. [MIT](https://opensource.org/licenses/MIT).

### Tools

*   [pileup](http://nikodemus.github.io/pileup/) - a portable, performant, and thread-safe binary heap for Common Lisp. [MIT](https://opensource.org/licenses/MIT).
*   [sycamore (⭐107)](https://github.com/ndantam/sycamore) -  a fast, purely functional data structure library. [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Emacs / Third-party APIs

*   [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/) - a Docker container for Common Lisp development environment. Ships SBCL, CCL, Roswell and Emacs25 with Slime.

## [Jan 07, 2018](/content/2018/01/07/README.md)

### CLOS extensions

*   [defclass-std (⭐36)](https://github.com/EuAndreh/defclass-std) - a shortcut macro to write DEFCLASS forms quickly. [LLGPL](http://opensource.franz.com/preamble.html).

## [Jan 06, 2018](/content/2018/01/06/README.md)

### C, C++

*   [cl-monero-tools (⭐18)](https://github.com/glv2/cl-monero-tools) -  Common Lisp toolbox to work with the Monero cryptocurrency. [GPL3](http://www.gnu.org/copyleft/gpl.html). Not in Quicklisp.
*   [peercoin-blockchain-parser (⭐4)](https://github.com/glv2/peercoin-blockchain-parser) - parse the blockchain contained in a file and export some of its data to a text file, a SQL script or a database. It can also create a database using the RPC of a Peercoin daemon as source of data instead of a blockchain file. LGPL3. Not in Quicklisp.
*   [peercoin-calculator (⭐2)](https://github.com/glv2/peercoin-calculator) - This program gives you the probability of generating a POS or POW block within 10 minutes, 24 hours, 31 days, 90 days and 1 year, as well as the reward that can be expected. GUI in Qt. [GPL3](http://www.gnu.org/copyleft/gpl.html). Not in Quicklisp.
*   [peercoin-vote (⭐5)](https://github.com/glv2/peercoin-vote) -  A voting system based on data from the blockchain (addresses and balances). [GPL3](http://www.gnu.org/copyleft/gpl.html). Not in Quicklisp.

## [Jan 05, 2018](/content/2018/01/05/README.md)

### Mobile

*   👍 [serapeum (⭐382)](https://github.com/TBRSS/serapeum/) - Another general-purpose utility library. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [anaphora](https://common-lisp.net/project/anaphora/) - A collection of anaphoric macros. Public domain.

## [Jan 04, 2018](/content/2018/01/04/README.md)

### Reference

*   [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - A modern public domain online version of chapters 5 and 6 of The Art of the Metaobject Protocol
*   [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - The original standard for Common Lisp before the ANSI spec.

### Date and time / Third-party APIs

*   [chronicity (⭐64)](https://github.com/chaitanyagupta/chronicity) - A natural language date and time parse, to parse strings like "3 days from now". [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Files and directories / Third-party APIs

*   ⭐ [uiop](https://common-lisp.net/project/asdf/uiop.html) and its `pathname` package
    (replaces [cl-fad](http://weitz.de/cl-fad/)). uiop is part of ASDF3
    and as thus is shipped in many implementations. [MIT](https://opensource.org/licenses/MIT).
*   [osicat](https://common-lisp.net/project/osicat/) - A lightweight operating system interface on POSIX-like systems (directory iteration and deletion, environment variables, file permissions, etc) [Expat](https://directory.fsf.org/wiki/License:Expat).

## [Jan 03, 2018](/content/2018/01/03/README.md)

### Community / Interfaces to other package managers

*   [qldeb (⭐4)](https://github.com/ralt/qldeb) -  Quicklisp systems to debian packages, along with [deb-packager (⭐4)](https://github.com/ralt/deb-packager) (simply create a debian package by defining an s-expression) and an introductory [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html). Both [MIT](https://opensource.org/licenses/MIT).
*   [ql-to-deb (⭐22)](https://github.com/dimitri/ql-to-deb) -  Update cl-\* debian packages from Quicklisp releases. WTFPL.

## [Dec 31, 2017](/content/2017/12/31/README.md)

### HTTP Servers / Clack plugins

*   [hermetic (⭐40)](https://github.com/eudoxia0/hermetic) - Security for Clack-based web applications. [Expat](https://directory.fsf.org/wiki/License:Expat).

## [Dec 17, 2017](/content/2017/12/17/README.md)

### Other / Third-party APIs

*   [corona (⭐48)](https://github.com/eudoxia0/corona) -  Create and manage virtual machines from Common Lisp <http://eudoxia.me/corona> [MIT](https://opensource.org/licenses/MIT).

## [Dec 15, 2017](/content/2017/12/15/README.md)

### Web frameworks / Clack plugins

*   [ningle (⭐257)](https://github.com/fukamachi/ningle) - A super-micro web framework. [LLGPL](http://opensource.franz.com/preamble.html).
    *   [jingle (⭐46)](https://github.com/dnaeon/cl-jingle) - based on ningle, adds  bells and whistles, such as middlewares.
        *   includes an OpenAPI and Swagger UI demo.

## [Dec 06, 2017](/content/2017/12/06/README.md)

### Community / Interfaces to other package managers

*   [antik](https://www.common-lisp.net/project/antik/) -  a foundation for scientific and engineering computation in Common Lisp. GPL. Also [mgl-mat (⭐65)](https://github.com/melisgl/mgl-mat) and [LLA (⭐88)](https://github.com/tpapp/lla).

## [Nov 29, 2017](/content/2017/11/29/README.md)

### HTTP Servers / Clack plugins

*   [clack-errors (⭐28)](https://github.com/eudoxia0/clack-errors) - Error page middleware for Clack. [LLGPL](http://opensource.franz.com/preamble.html).

## [Nov 27, 2017](/content/2017/11/27/README.md)

### Javascript / Isomorphic web frameworks

*   [SmackJack (⭐18)](https://github.com/aarvid/SmackJack) - An Ajax Common Lisp Library using parenscript to generate javascript and hunchentoot (for now) as the web server. Also allows a server-side lisp function to call a client-side parenscript one. [MIT](https://opensource.org/licenses/MIT).

## [Nov 25, 2017](/content/2017/11/25/README.md)

### Beginner

*   [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - A good tutorial to get up and code Common Lisp quickly.

## [Nov 24, 2017](/content/2017/11/24/README.md)

### Miscellaneous

*   [McCLIM](https://common-lisp.net/project/mcclim/) - An implementation of the Common Lisp Interface Manager, version II. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).

## [Nov 21, 2017](/content/2017/11/21/README.md)

### Apps / Third-party APIs

*   [montezuma (⭐45)](https://github.com/sharplispers/montezuma/) -  Full-text indexing and search for Common Lisp. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [mk-string-metrics (⭐20)](https://github.com/cbaggers/mk-string-metrics) -
    Calculate various string metrics efficiently in Common Lisp
    (Damerau-Levenshtein, Hamming, Jaro, Jaro-Winkler, Levenshtein,
    etc). [MIT](https://opensource.org/licenses/MIT).

### Configuration / Third-party APIs

*   [envy (⭐54)](https://github.com/fukamachi/envy) - Configuration switcher. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).

## [Nov 08, 2017](/content/2017/11/08/README.md)

### URI handling / Isomorphic web frameworks

*   [quri (⭐101)](https://github.com/fukamachi/quri) - Another URI library for
    Common Lisp. Supports userinfo, IPv6 hostname, encoding/decoding
    utilities,… [BSD\_3Clause](https://directory.fsf.org/wiki/License:BSD_3Clause).

## [Oct 30, 2017](/content/2017/10/30/README.md)

### Apps / Third-party APIs

*   [Check-it (⭐51)](https://github.com/DalekBaldwin/check-it) - A QuickCheck-style randomized property-based testing. [LLGPL](http://opensource.franz.com/preamble.html).

## [Oct 24, 2017](/content/2017/10/24/README.md)

### HTTP Servers / Clack plugins

*   [clack-pretend (⭐11)](https://github.com/BnMcGn/clack-pretend) - a testing
    and debugging tool for clack. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

## [Oct 08, 2017](/content/2017/10/08/README.md)

### Apps / Third-party APIs

*   [Mockingbird (⭐18)](https://github.com/Chream/mockingbird) - A small
    stubbing and mocking library for Common Lisp. Can also check wether
    a stubbed function was called, how many times and with which
    arguments. [MIT](https://opensource.org/licenses/MIT).

## [Oct 05, 2017](/content/2017/10/05/README.md)

### Notebooks / Third-party APIs

*   [Darkmatter](https://github.com/tamamu/darkmatter) - A
    notebook-style Common Lisp environment. [MIT](https://opensource.org/licenses/MIT).

## [Oct 02, 2017](/content/2017/10/02/README.md)

### Readline, ncurses and other graphical helpers / Third-party APIs

*   [cl-readline (⭐37)](https://github.com/vindarel/cl-readline) - a set of
    functions to edit lines as they are typed in, to maintain a list of
    previously-entered command lines, to recall and reedit them and
    perform csh-like history expansion.  Emacs and vi editing
    modes. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Sep 26, 2017](/content/2017/09/26/README.md)

### Others / Web project skeletons and generators

*   [find-port (⭐18)](https://github.com/eudoxia0/find-port) -  Programmatically find open ports. [MIT](https://opensource.org/licenses/MIT).

## [Sep 01, 2017](/content/2017/09/01/README.md)

### Plotting / Third-party APIs

*   [eazy-gnuplot (⭐60)](https://github.com/guicho271828/eazy-gnuplot) - a
    lispy, structure-less Gnuplot library. With its
    [cookbook](http://guicho271828.github.io/eazy-gnuplot/). [LLGPL](http://opensource.franz.com/preamble.html)

## [Jul 25, 2017](/content/2017/07/25/README.md)

### Markdown / Third-party APIs

*   [3bmd (⭐77)](https://github.com/3b/3bmd) - a markdown -> html converter. [MIT](https://opensource.org/licenses/MIT).

## [Jul 07, 2017](/content/2017/07/07/README.md)

### Plotting / Third-party APIs

*   [vgplot (⭐46)](https://github.com/volkers/vgplot) - an interface to the
    gnuplot plotting utility with the intention to resemble some of
    the plot commands of octave or matlab. [GPL3](http://www.gnu.org/copyleft/gpl.html).

## [Jul 04, 2017](/content/2017/07/04/README.md)

### Writing, running scripts / Third-party APIs

*   👍 [Roswell (⭐1.7k)](https://github.com/roswell/roswell#scripting-with-roswell) -
    a lisp installer and scripting environment (helper, launcher,
    installer) and more. [MIT](https://opensource.org/licenses/MIT).

## [Jun 28, 2017](/content/2017/06/28/README.md)

### Intermediate

*   [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)

## [May 29, 2017](/content/2017/05/29/README.md)

### Mobile

*   [ABCL](https://common-lisp.net/project/armedbear/) - Armed Bear Common Lisp; targets the JVM, compiles to bytecode. [Standard conformance](https://common-lisp.net/project/armedbear/faq.shtml#qa). [GNU GPL3](http://www.gnu.org/copyleft/gpl.html) with [Classpath exception](http://www.gnu.org/software/classpath/license.html).

### Intermediate

*   [Common Lisp Recipes](http://weitz.de/cl-recipes/) - **Common Lisp Recipes** is a collection of solutions to problems and answers to questions you are likely to encounter when writing real-world applications in Common Lisp. Published in 2015.

## [May 08, 2017](/content/2017/05/08/README.md)

### Beginner

*   [Practical Common Lisp](http://www.gigamonkeys.com/book/) - A good introductory text to Common Lisp, with practical examples.
*   [Land of Lisp](http://landoflisp.com/) - A fun, game-oriented introduction to Common Lisp.

### Advanced

*   [Let Over Lambda](http://letoverlambda.com/) - A book on advanced macro techniques. All eight chapters are available in the print copy.
*   [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham's amazing book on Lisp macros (and other interesting things).
*   [Object-Oriented Programming in Common Lisp: A Programmer's Guide to CLOS](http://www.goodreads.com/book/show/1175730.Object_Oriented_Programming_in_Common_LISP) - An old, but very thorough book on CLOS.
*   [Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp](http://norvig.com/paip.html) - A book on programming AI that covers some advanced Lisp.
    *   with a web version: [https://norvig.github.io/paip-lisp/](https://norvig.github.io/paip-lisp/#/)

### Reference

*   [Common Lisp Quick Reference](http://clqr.boundp.org/index.html) - A distilled, pocket-size version of the ANSI CL spec. Available for download as a PDF.
*   [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm) - The Common Lisp HyperSpec; the ANSI CL standard, in hypertext form.

### Intermediate

*   [ANSI Common Lisp](http://www.paulgraham.com/acl.html) - A thorough, practical covering of the entire language, with exercises. Not recommended as a starter text, due to [some caveats](http://www.cs.northwestern.edu/academics/courses/325/readings/graham/graham-notes.html).

## [Apr 26, 2017](/content/2017/04/26/README.md)

### URI handling / Isomorphic web frameworks

*   [cl-slug (⭐23)](https://github.com/EuAndreh/cl-slug) - a small library to make slugs, mainly for URIs, transform in CamelCase, remove accentuation and punctuation, for english and beyound. [LLGPL](http://opensource.franz.com/preamble.html).

### Other scripting utilities / Third-party APIs

*   [Parinfer](https://shaunlebron.github.io/parinfer/) - Parinfer is a way to edit lisp code that helps to keep both the indentation and the parenthesis balanced. It is easy to start with and yet it offers advanced features à la Paredit. It is available on many editors (Emacs, Vim, Neovim, Atom, Sublime Text, Visual Studio Code, LightTable, CodeMirror,…).

## [Mar 07, 2017](/content/2017/03/07/README.md)

### C, C++

*   [trivial-ssh (⭐39)](https://github.com/eudoxia0/trivial-ssh) - An SSH client library. [Expat](https://directory.fsf.org/wiki/License:Expat).

### ORMs

*   [crane (⭐196)](https://github.com/eudoxia0/crane) - Another ORM. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [datafly (⭐94)](https://github.com/fukamachi/datafly) - A lightweight database library. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [sxql (⭐331)](https://github.com/fukamachi/sxql) - A DSL for generating SQL. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).

### Java

*   [cl+j](https://common-lisp.net/project/cl-plus-j/) - A JNI-based interface to a JVM via CFFI. Not available on Quicklisp. Does not reliably work with all implementations. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Miscellaneous

*   [Vecto](http://www.xach.com/lisp/vecto/) - Simple vector drawing library. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
*   [zpng](http://www.xach.com/lisp/zpng/) - A library for creating PNG files. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
*   [cl-cairo2 (⭐59)](https://github.com/rpav/cl-cairo2) - Cairo bindings. [Boost 1.0](https://directory.fsf.org/wiki/License:Boost1.0)
*   [cl-gd](http://weitz.de/cl-gd/) - A library providing an interface to the GD graphics library. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
*   [cl-horde3d (⭐15)](https://github.com/anwyn/cl-horde3d/) - FFI bindings to the Horde3D graphics library. Not available on Quicklisp. [EPL 1.0](https://directory.fsf.org/wiki/License:EPLv1.0)
*   [cl-opengl (⭐266)](https://github.com/3b/cl-opengl) - CFFI bindings to OpenGL, GLU and GLUT APIs. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-sdl2 (⭐277)](https://github.com/lispgames/cl-sdl2) - Bindings for SDL2 using C2FFI. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [CLinch (⭐265)](https://github.com/BradWBeer/CLinch) - Common Lisp 2D/3D graphics engine for OpenGL. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
*   [donuts (⭐23)](https://github.com/tkych/donuts) - Graphviz interface for Common Lisp. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [lispbuilder-sdl (⭐184)](https://github.com/lispbuilder/lispbuilder) - A set of bindings for SDL. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [cl-gtk2 (⭐36)](https://github.com/dmitryvk/cl-gtk2) - A binding for GTK+2. [LLGPL](http://opensource.franz.com/preamble.html).

### Mobile

*   [jsown (⭐105)](https://github.com/madnificent/jsown) - A reader and writer for the JSON format. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Beginner

*   [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - A nice introduction into the language.

### Community / Interfaces to other package managers

*   [cl-nlp (⭐208)](https://github.com/vseloved/cl-nlp) - Natural language processing toolset. [Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0).

### HTTP Servers / Interfaces to other package managers

*   [wookie (⭐186)](https://github.com/orthecreedence/wookie) - Asynchronous HTTP server. [Expat](https://directory.fsf.org/wiki/License:Expat).

### HTML generators and templates / Isomorphic web frameworks

*   [eco (⭐38)](https://github.com/eudoxia0/eco) - Fast, flexible, designer-friendly template engine. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Javascript / Isomorphic web frameworks

*   [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/) - A translator from Javascript to Common Lisp. Not available on Quicklisp. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [parse-js](http://marijnhaverbeke.nl/parse-js/) - A package for parsing ECMAScript 3. [zlib](https://directory.fsf.org/wiki/License:Zlib).

### Websockets / Isomorphic web frameworks

*   [iolib (⭐138)](https://github.com/sionescu/iolib) - I/O library. [Expat](https://directory.fsf.org/wiki/License:Expat).
    *   "IOlib is to be a better and more modern I/O library than the standard Common Lisp library. It contains: a socket library, a DNS resolver, an I/O multiplexer, a pathname library and file-system utilities."

### Others / Web project skeletons and generators

*   [css-lite (⭐74)](https://github.com/paddymul/css-lite) - A CSS grammar. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Others / Third-party APIs

*   [GSLL](https://common-lisp.net/project/gsll/) - GNU Scientific Library for Lisp; allows the use of the GSL from Common Lisp. [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).

### Utils / Third-party APIs

*   [chanl (⭐163)](https://github.com/zkat/chanl) - Portable, channel-based concurrency. [Expat](https://directory.fsf.org/wiki/License:Expat), with parts under [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [cl-async (⭐258)](https://github.com/orthecreedence/cl-async) - A library for general-purpose, non-blocking programming. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Vim & Neovim / Third-party APIs

*   [SLIMV (⭐445)](https://github.com/kovisoft/slimv) - Superior Lisp Interaction Mode for Vim; a full-blown environment for Common Lisp inside of Vim. No license specified.

### Apps / Third-party APIs

*   [quicksearch (⭐48)](https://github.com/tkych/quicksearch) - Look up online libraries from the REPL. [Expat](https://directory.fsf.org/wiki/License:Expat).

### Other / Third-party APIs

*   [babel (⭐80)](https://github.com/cl-babel/babel) - A charset encoding/decoding library. [Expat](https://directory.fsf.org/wiki/License:Expat).
*   [fast-io (⭐138)](https://github.com/rpav/fast-io) - Fast octet-vector/stream I/O. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [named-readtables (⭐59)](https://github.com/melisgl/named-readtables) - Provides a readtable namespace, akin to package namespaces. [3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause).
*   [simple-currency (⭐7)](https://github.com/a0-prw/simple-currency) - A currency conversion library using daily information published by the ECB. [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD).
*   [trivial-garbage (⭐39)](https://github.com/trivial-garbage/trivial-garbage) - A portable finalizer, weak hash-table and weak pointer API. Public domain.

## [Dec 21, 2016](/content/2016/12/21/README.md)

### HTTP Servers / Interfaces to other package managers

*   [woo (⭐1.2k)](https://github.com/fukamachi/woo) - A fast non-blocking HTTP server on top of libev. [MIT](https://opensource.org/licenses/MIT).

### Web frameworks / Clack plugins

*   [Caveman (⭐750)](https://github.com/fukamachi/caveman) - A powerful web framework. [LLGPL](http://opensource.franz.com/preamble.html).
    Example projects: [Quickdocs](https://github.com/quickdocs)

### Javascript / Isomorphic web frameworks

*   [JSCL (⭐851)](https://github.com/jscl-project/jscl) - A CL-to-JS compiler designed to be self-hosting from day one. Lacks CLOS, format and loop.