# Awesome Coq Overview

A curated list of awesome Coq libraries, plugins, tools, verification projects, and resources [maintainers=@anton-trunov,@palmskog]

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/coq-community/awesome-coq/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 coq-community/awesome-coq](https://github.com/coq-community/awesome-coq) · ⭐ 193 · 🏷️ Programming Languages

[ [Daily](/content/coq-community/awesome-coq/README.md) / [Weekly](/content/coq-community/awesome-coq/week/README.md) / Overview ]

---

# Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/coq-community/awesome-coq/raw/master/coq-logo.svg" align="right" width="100" alt="coq-community logo" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

> A curated list of awesome Coq libraries, plugins, tools, and resources.

The [Coq proof assistant](https://coq.inria.fr) provides a formal language to write mathematical definitions, executable algorithms, and theorems, together with an environment for semi-interactive development of machine-checked proofs.

Contributions welcome! Read the [contribution guidelines (⭐193)](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) first.

## Contents

*   [Projects](#projects)
    *   [Frameworks](#frameworks)
    *   [User Interfaces](#user-interfaces)
    *   [Libraries](#libraries)
    *   [Package and Build Management](#package-and-build-management)
    *   [Plugins](#plugins)
    *   [Tools](#tools)
    *   [Type Theory and Mathematics](#type-theory-and-mathematics)
    *   [Verified Software](#verified-software)
*   [Resources](#resources)
    *   [Community](#community)
    *   [Blogs](#blogs)
    *   [Books](#books)
    *   [Course Material](#course-material)
    *   [Tutorials and Hints](#tutorials-and-hints)

***

## Projects

### Frameworks

*   [ConCert (⭐77)](https://github.com/AU-COBRA/ConCert) - Framework for smart contract testing and verification featuring a code extraction pipeline to several smart contract languages.
*   [CoqEAL (⭐62)](https://github.com/CoqEAL/CoqEAL) - Framework to ease change of data representations in proofs.
*   [FCF (⭐43)](https://github.com/adampetcher/fcf) - Framework for proofs of cryptography.
*   [Fiat (⭐138)](https://github.com/mit-plv/fiat) - Mostly automated synthesis of correct-by-construction programs.
*   [FreeSpec (⭐50)](https://github.com/lthms/FreeSpec) - Framework for modularly verifying programs with effects and effect handlers.
*   [Hybrid](https://www.site.uottawa.ca/\~afelty/HybridCoq/) - System for reasoning using higher-order abstract syntax representations of object logics.
*   [Iris](https://iris-project.org) - Higher-order concurrent separation logic framework.
*   [Q\*cert (⭐50)](https://github.com/querycert/qcert) - Platform for implementing and verifying query compilers.
*   [VCFloat (⭐11)](https://github.com/VeriNum/vcfloat) - Framework for verifying C programs with floating-point computations.
*   [Verdi (⭐539)](https://github.com/uwplse/verdi) - Framework for formally verifying distributed systems implementations.
*   [VST](https://vst.cs.princeton.edu) - Toolchain for verifying C code inside Coq in a higher-order concurrent, impredicative separation logic that is sound w\.r.t. the Clight language of the CompCert compiler.

### User Interfaces

*   [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - Standalone graphical tool for interacting with Coq.
*   [Coqtail (⭐196)](https://github.com/whonore/Coqtail) - Interface for Coq based on the Vim text editor.
*   [Proof General](https://proofgeneral.github.io) - Generic interface for proof assistants based on the extensible, customizable text editor Emacs.
*   [Company-Coq (⭐326)](https://github.com/cpitclaudel/company-coq) - IDE extensions for Proof General's Coq mode.
*   [jsCoq (⭐0)](https://github.com/ejgallego/jscoq) - Port of Coq to JavaScript, which enables running Coq projects in a browser.
*   [Jupyter kernel for Coq (⭐76)](https://github.com/EugeneLoy/coq_jupyter) - Coq support for the Jupyter Notebook web environment.
*   [VsCoq (⭐206)](https://github.com/coq-community/vscoq) - Extension for the Visual Studio Code and VSCodium editors.

### Libraries

*   [ALEA (⭐21)](https://github.com/coq-community/alea) - Library for reasoning on randomized algorithms.
*   [Algebra Tactics (⭐28)](https://github.com/math-comp/algebra-tactics) - Ring and field tactics for Mathematical Components.
*   [Bignums (⭐20)](https://github.com/coq/bignums) - Library of arbitrarily large numbers.
*   [Bedrock Bit Vectors (⭐25)](https://github.com/mit-plv/bbv) - Library for reasoning on fixed precision machine words.
*   [CertiGraph (⭐10)](https://github.com/Salamari/CertiGraph) - Library for reasoning about directed graphs and their embedding in separation logic.
*   [CoLoR (⭐28)](https://github.com/fblanqui/color) - Library on rewriting theory, lambda-calculus and termination, with sub-libraries on common data structures extending the Coq standard library.
*   [coq-haskell (⭐153)](https://github.com/jwiegley/coq-haskell) - Library smoothing the transition to Coq for Haskell users.
*   [CoqInterval](https://gitlab.inria.fr/coqinterval/interval/) - Tactics for performing proofs of inequalities on expressions of real numbers.
*   [Coq record update (⭐38)](https://github.com/tchajed/coq-record-update) - Library which provides a generic way to update Coq record fields.
*   [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Extended alternative standard library for Coq.
*   [ExtLib (⭐117)](https://github.com/coq-community/coq-ext-lib) - Collection of theories and plugins that may be useful in other Coq developments.
*   [FCSL-PCM (⭐21)](https://github.com/imdea-software/fcsl-pcm) - Formalization of partial commutative monoids as used in verification of pointer-manipulating programs.
*   [Flocq](https://gitlab.inria.fr/flocq/flocq) - Formalization of floating-point numbers and computations.
*   [Formalised Undecidable Problems (⭐88)](https://github.com/uds-psl/coq-library-undecidability) - Library of undecidable problems and reductions between them.
*   [Hahn (⭐27)](https://github.com/vafeiadis/hahn) - Library for reasoning on lists and binary relations.
*   [Interaction Trees (⭐165)](https://github.com/DeepSpec/InteractionTrees) - Library for representing recursive and impure programs.
*   [LibHyps (⭐15)](https://github.com/Matafou/LibHyps) - Library of Ltac tactics to manage and manipulate hypotheses in proofs.
*   [MathComp Extra (⭐4)](https://github.com/thery/mathcomp-extra) - Extra material for the Mathematical Components library, including the AKS primality test and RSA encryption and decryption.
*   [Mczify (⭐20)](https://github.com/math-comp/mczify) - Library enabling Micromega arithmetic solvers to work when using Mathematical Components number definitions.
*   [Metalib (⭐64)](https://github.com/plclub/metalib) - Library for programming language metatheory using locally nameless variable binding representations.
*   [Paco](http://plv.mpi-sws.org/paco/) - Library for parameterized coinduction.
*   [Regular Language Representations (⭐29)](https://github.com/coq-community/reglang) - Translations between different definitions of regular languages, including regular expressions and automata.
*   [Relation Algebra (⭐37)](https://github.com/damien-pous/relation-algebra) - Modular formalization of algebras with heterogeneous binary relations as models.
*   [Simple IO (⭐24)](https://github.com/Lysxia/coq-simple-io) - Input/output monad with user-definable primitive operations.
*   [TLC (⭐27)](https://github.com/charguer/tlc) - Non-constructive alternative to Coq's standard library.

### Package and Build Management

*   [coq\_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - Build tool distributed with Coq and based on generating a makefile.
*   [Coq Nix Toolbox (⭐24)](https://github.com/coq-community/coq-nix-toolbox) - Nix helper scripts to automate local builds and continuous integration for Coq.
*   [Coq Package Index](https://coq.inria.fr/opam/www/) - Collection of Coq packages based on opam.
*   [Coq Platform (⭐118)](https://github.com/coq/platform) - Curated collection of packages to support Coq use in industry, education, and research.
*   [coq-community Templates (⭐10)](https://github.com/coq-community/templates) - Templates for generating configuration files for Coq projects.
*   [Docker-Coq (⭐29)](https://github.com/coq-community/docker-coq) - Docker images for many versions of Coq.
*   [Docker-MathComp (⭐6)](https://github.com/math-comp/docker-mathcomp) - Docker images for many combinations of versions of Coq and the Mathematical Components library.
*   [Docker-Coq GitHub Action](https://github.com/marketplace/actions/docker-coq-action) - GitHub container action that can be used with Docker-Coq or Docker-MathComp.
*   [Dune](https://dune.build) - Composable and opinionated build system for OCaml and Coq (former jbuilder).
*   [Nix](https://nixos.org/nix/) - Package manager for Linux and other Unix systems, supporting atomic upgrades and rollbacks.
*   [Nix Coq packages](https://search.nixos.org/packages?channel=unstable\&query=coqPackages) - Collection of Coq-related packages for Nix.
*   [opam](https://opam.ocaml.org) - Flexible and Git-friendly package manager for OCaml and Coq with multiple compiler support.

### Plugins

*   [AAC Tactics (⭐29)](https://github.com/coq-community/aac-tactics) - Tactics for rewriting universally quantified equations, modulo associativity and commutativity of some operator.
*   [Coq-Elpi (⭐85)](https://github.com/LPCIC/coq-elpi) - Extension framework based on λProlog providing an extensive API to implement commands and tactics.
*   [CoqHammer (⭐184)](https://github.com/lukaszcz/coqhammer) - General-purpose automated reasoning hammer tool that combines learning from previous proofs with the translation of problems to automated provers and the reconstruction of found proofs.
*   [Equations (⭐191)](https://github.com/mattam82/Coq-Equations) - Function definition package for Coq.
*   [Gappa](https://gitlab.inria.fr/gappa/coq) - Tactic for discharging goals about floating-point arithmetic and round-off errors.
*   [Hierarchy Builder (⭐67)](https://github.com/math-comp/hierarchy-builder) - Collection of commands for declaring Coq hierarchies based on packed classes.
*   [Itauto](https://gitlab.inria.fr/fbesson/itauto) - SMT-like tactics for combined propositional reasoning about function symbols, constructors, and arithmetic.
*   [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - Experimental typed tactic language similar to Coq's classic Ltac language.
*   [MetaCoq (⭐265)](https://github.com/MetaCoq/metacoq) - Project formalizing Coq in Coq and providing tools for manipulating Coq terms and developing certified plugins.
*   [Mtac2 (⭐48)](https://github.com/Mtac2/Mtac2) - Plugin adding typed tactics for backward reasoning.
*   [Paramcoq (⭐44)](https://github.com/coq-community/paramcoq) - Plugin to generate parametricity translations of Coq terms.
*   [QuickChick (⭐223)](https://github.com/QuickChick/QuickChick) - Plugin for randomized property-based testing.
*   [SMTCoq (⭐128)](https://github.com/smtcoq/smtcoq) - Tool that checks proof witnesses coming from external SAT and SMT solvers.
*   [Tactician](https://coq-tactician.github.io) - Interactive tool which learns from previously written tactic scripts across all the installed Coq packages and suggests the next tactic to be executed or tries to automate proof synthesis fully.
*   [Unicoq (⭐45)](https://github.com/unicoq/unicoq) - Plugin that replaces the existing unification algorithm with an enhanced one.

### Tools

*   [Alectryon (⭐178)](https://github.com/cpitclaudel/alectryon) - Collection of tools for writing technical documents that mix Coq code and prose.
*   [Autosubst 2 (⭐13)](https://github.com/uds-psl/autosubst2) - Tool that generates Coq code for handling binders in syntax, such as for renaming and substitutions.
*   [CFML](https://gitlab.inria.fr/charguer/cfml2) - Tool for proving properties of OCaml programs in separation logic.
*   [coq2html (⭐24)](https://github.com/xavierleroy/coq2html) - Alternative HTML documentation generator for Coq.
*   [coqdoc](https://coq.inria.fr/refman/using/tools/coqdoc.html) - Standard documentation tool that generates LaTeX or HTML files from Coq code.
*   [CoqOfOCaml (⭐183)](https://github.com/clarus/coq-of-ocaml) - Tool for generating idiomatic Coq from OCaml code.
*   [coq-dpdgraph (⭐79)](https://github.com/coq-community/coq-dpdgraph) - Tool for building dependency graphs between Coq objects.
*   [coq-scripts (⭐6)](https://github.com/JasonGross/coq-scripts) - Scripts for dealing with Coq files, including tabulating proof times.
*   [coq-tools (⭐34)](https://github.com/JasonGross/coq-tools) - Scripts for manipulating Coq developments.
    *   [`find-bug.py`](https://github.com/JasonGross/coq-tools/blob/master/find-bug.py) - Automatically minimizes source files producing an error, creating small test cases for Coq bugs.
    *   [`absolutize-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/absolutize-imports.py) - Processes source files to make loading of dependencies robust against shadowing of file names.
    *   [`inline-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/inline-imports.py) - Creates stand-alone source files from developments by inlining the loading of all dependencies.
    *   [`minimize-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/minimize-requires.py) - Removes loading of unused dependencies.
    *   [`move-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/move-requires.py) - Moves all dependency loading statements to the top of source files.
    *   [`move-vernaculars.py`](https://github.com/JasonGross/coq-tools/blob/master/move-vernaculars.py) - Lifts many vernacular commands and inner lemmas out of proof script blocks.
    *   [`proof-using-helper.py`](https://github.com/JasonGross/coq-tools/blob/master/proof-using-helper.py) - Modifies source files to include proof annotations for faster parallel proving.
*   [Cosette (⭐594)](https://github.com/uwdb/Cosette) - Automated solver for reasoning about SQL query equivalences.
*   [hs-to-coq (⭐64)](https://github.com/plclub/hs-to-coq) - Converter from Haskell code to equivalent Coq code.
*   [lngen (⭐27)](https://github.com/plclub/lngen) - Tool for generating locally nameless Coq definitions and proofs.
*   [Menhir](http://gallium.inria.fr/\~fpottier/menhir/) - Parser generator that can output Coq code for verified parsers.
*   [mCoq (⭐23)](https://github.com/EngineeringSoftware/mcoq) - Mutation analysis tool for Coq projects.
*   [Ott (⭐268)](https://github.com/ott-lang/ott) - Tool for writing definitions of programming languages and calculi that can be translated to Coq.
*   [PyCoq (⭐40)](https://github.com/ejgallego/pycoq) - Set of bindings and libraries for interacting with Coq from inside Python 3.
*   [Roosterize (⭐14)](https://github.com/EngineeringSoftware/roosterize) - Tool for suggesting lemma names in Coq projects.
*   [Sail (⭐398)](https://github.com/rems-project/sail) - Tool for specifying instruction set architecture semantics of processors and generating Coq definitions.
*   [SerAPI (⭐111)](https://github.com/ejgallego/coq-serapi) - Tools and OCaml library for (de)serialization of Coq code to and from JSON and S-expressions.
*   [Trakt (⭐12)](https://github.com/ecranceMERCE/trakt) - Generic goal preprocessing tool for proof automation tactics.

### Type Theory and Mathematics

*   [Analysis (⭐139)](https://github.com/math-comp/analysis) - Library for classical real analysis compatible with Mathematical Components.
*   [Category Theory in Coq (⭐672)](https://github.com/jwiegley/category-theory) - Axiom-free formalization of category theory.
*   [Completeness and Decidability of Modal Logic Calculi (⭐5)](https://github.com/coq-community/comp-dec-modal) - Soundness, completeness, and decidability for the logics K, K\*, CTL, and PDL.
*   [CoqPrime (⭐23)](https://github.com/thery/coqprime) - Library for certifying primality using Pocklington and Elliptic Curve certificates.
*   [CoRN (⭐105)](https://github.com/coq-community/corn) - Library of constructive real analysis and algebra.
*   [Coqtail Math (⭐14)](https://github.com/coq-community/coqtail-math) - Library of mathematical results ranging from arithmetic to real and complex analysis.
*   [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - Formalization of classical real analysis compatible with the standard library and focusing on usability.
*   [Finmap (⭐45)](https://github.com/math-comp/finmap) - Extension of Mathematical Components with finite maps, sets, and multisets.
*   [Four Color Theorem (⭐121)](https://github.com/coq-community/fourcolor) - Formal proof of the Four Color Theorem, a landmark result of graph theory.
*   [Gaia (⭐21)](https://github.com/coq-community/gaia) - Implementation of books from Bourbaki's Elements of Mathematics, including set theory and number theory.
*   [GeoCoq (⭐146)](https://github.com/GeoCoq/GeoCoq) - Formalization of geometry based on Tarski's axiom system.
*   [Graph Theory (⭐25)](https://github.com/coq-community/graph-theory) - Formalized graph theory results.
*   [Homotopy Type Theory (⭐1.1k)](https://github.com/HoTT/HoTT) - Development of homotopy-theoretic ideas.
*   [Infotheo (⭐59)](https://github.com/affeldt-aist/infotheo) - Formalization of information theory and linear error-correcting codes.
*   [Mathematical Components](http://math-comp.github.io) - Formalization of mathematical theories, focusing in particular on group theory.
*   [Math Classes (⭐147)](https://github.com/coq-community/math-classes) - Abstract interfaces for mathematical structures based on type classes.
*   [Monae (⭐62)](https://github.com/affeldt-aist/monae) - Monadic effects and equational reasoning.
*   [Odd Order Theorem (⭐21)](https://github.com/math-comp/odd-order) - Formal proof of the Odd Order Theorem, a landmark result of finite group theory.
*   [Puiseuxth (⭐3)](https://github.com/roglo/puiseuxth) - Proof of Puiseux's theorem and computation of roots of polynomials of Puiseux's series.
*   [UniMath (⭐788)](https://github.com/UniMath/UniMath) - Library which aims to formalize a substantial body of mathematics using the univalent point of view.

### Verified Software

*   [CompCert](http://compcert.inria.fr) - High-assurance compiler for almost all of the C language (ISO C99), generating efficient code for the PowerPC, ARM, RISC-V and x86 processors.
*   [Ceramist (⭐117)](https://github.com/certichain/ceramist) - Verified hash-based approximate membership structures such as Bloom filters.
*   [Fiat-Crypto (⭐519)](https://github.com/mit-plv/fiat-crypto) - Cryptographic primitive code generation.
*   [Functional Algorithms Verified in SSReflect (⭐25)](https://github.com/clayrat/fav-ssr) - Purely functional verified implementations of algorithms for searching, sorting, and other fundamental problems.
*   [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
*   [Jasmin (⭐132)](https://github.com/jasmin-lang/jasmin) - Formalized language and verified compiler for high-assurance and high-speed cryptography.
*   [JSCert (⭐195)](https://github.com/jscert/jscert) - Coq specification of ECMAScript 5 (JavaScript) with verified reference interpreter.
*   [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Formal model of a Rust core language and type system, a logical relation for the type system, and safety proofs for some Rust libraries.
*   [Prosa](https://gitlab.mpi-sws.org/RT-PROOFS/rt-proofs) - Definitions and proofs for real-time system schedulability analysis.
*   [RISC-V Specification in Coq (⭐82)](https://github.com/mit-plv/riscv-coq) - Definition of the RISC-V processor instruction set architecture and extensions.
*   [Tarjan and Kosaraju (⭐8)](https://github.com/math-comp/tarjan) - Verified implementations of algorithms for topological sorting and finding strongly connected components in finite graphs.
*   [Vélus](http://velus.inria.fr) - Verified compiler for a Lustre/Scade-like dataflow synchronous language.
*   [Verdi Raft (⭐165)](https://github.com/uwplse/verdi-raft) - Implementation of the Raft distributed consensus protocol, verified in Coq using the Verdi framework.

## Resources

### Community

*   [Official Coq website](https://coq.inria.fr)
*   [Official Coq manual](https://coq.inria.fr/refman/)
*   [Official Coq standard library](https://coq.inria.fr/stdlib/)
*   [Official Coq Discourse forum](https://coq.discourse.group)
*   [Official Coq Zulip chat](https://coq.zulipchat.com)
*   [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
*   [Official Coq wiki (⭐4k)](https://github.com/coq/coq/wiki)
*   [Official Coq Twitter](https://twitter.com/CoqLang)
*   [Coq Zulip chat archive](https://coq.gitlab.io/zulip-archive/)
*   [Coq subreddit](https://www.reddit.com/r/Coq/)
*   [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
*   [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
*   [Coq tag on Proof Assistants Stack Exchange](https://proofassistants.stackexchange.com/questions/tagged/coq)
*   [Coq keyword on Zenodo](https://zenodo.org/search?q=keywords%3A%22Coq%22)
*   [coq-community package maintenance project (⭐66)](https://github.com/coq-community/manifesto)
*   [Mathematical Components wiki (⭐444)](https://github.com/math-comp/math-comp/wiki)
*   [100 famous theorems proved using Coq (⭐39)](https://github.com/coq-community/coq-100-theorems)
*   [Planet Coq link aggregator](https://coq.pl-a.net)

### Blogs

*   [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
*   [Gagallium](http://gallium.inria.fr/blog)
*   [Gregory Malecha's blog](https://gmalecha.github.io)
*   [Guillaume Claret's Coq blog](http://coq-blog.clarus.me)
*   [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
*   [Lysxia's blog](https://blog.poisson.chat)
*   [MIT PLV blog posts on Coq](https://plv.csail.mit.edu/blog/category/coq.html)
*   [PLClub Blog](https://www.seas.upenn.edu/\~plclub/blog/)
*   [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
*   [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
*   [Thomas Letan's blog posts on Coq](https://soap.coffee/\~lthms/#coq)

### Books

*   [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - The first book dedicated to Coq.
*   [Software Foundations](https://softwarefoundations.cis.upenn.edu) - Series of Coq-based textbooks on logic, functional programming, and foundations of programming languages, aimed at being accessible to beginners.
*   [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - Textbook about practical engineering with Coq which teaches advanced practical tricks and a very specific style of proof.
*   [Program Logics for Certified Compilers](https://www.cs.princeton.edu/\~appel/papers/plcc.pdf) - Book that explains how to construct program logics using separation logic, accompanied by a formal model in Coq which is applied to the Clight programming language and other examples.
*   [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - Book that simultaneously provides a general introduction to formal logical reasoning about the correctness of programs and to using Coq for this purpose.
*   [Programs and Proofs](https://ilyasergey.net/pnp/) - Book that gives a brief and practically-oriented introduction to interactive proofs in Coq which emphasizes the computational nature of inductive reasoning about decidable propositions via a small set of primitives from the SSReflect proof language.
*   [Computer Arithmetic and Formal Proofs](http://iste.co.uk/book.php?id=1238) - Book that describes how to formally specify and verify floating-point algorithms in Coq using the Flocq library.
*   [The Mathematical Components book](https://math-comp.github.io/mcb/) - Book oriented towards mathematically inclined users, focusing on the Mathematical Components library and the SSReflect proof language.
*   [Modeling and Proving in Computational Type Theory (⭐39)](https://github.com/uds-psl/MPCTT) - Book covering topics in computational logic using Coq, including foundations, canonical case studies, and practical programming.
*   [Hydras & Co. (⭐37)](https://github.com/coq-community/hydra-battles) - Continuously in-progress book and library on Kirby and Paris' hydra battles and other entertaining formalized mathematics in Coq, including a proof of the Gödel-Rosser first incompleteness theorem.

### Course Material

*   [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) - Introduction to using separation logic to reason about sequential imperative programs in Coq.
*   [Floating-Point Numbers and Formal Proof (⭐5)](https://github.com/thery/FlocqLecture) - Introductory course on Coq real numbers and floating-point numbers from the Flocq library.
*   [Introduction to the Theory of Computation](https://gitlab.com/umb-svl/turing) - Formalization to support an undergraduate course on the theory of computation, including languages and Turing machines.
*   [Lectures on Software Foundations (⭐39)](https://github.com/clarksmr/sf-lectures) - Material on the Software Foundations series of textbooks, including a series of YouTube videos.
*   [Mechanized Semantics (⭐39)](https://github.com/xavierleroy/cdf-mech-sem) - Coq sources for a course on programming language semantics at Collège de France.
*   [Proofs and Reliable Programming using Coq](https://team.inria.fr/stamp/proofs-and-reliable-programming-using-coq-2022/) - Introduction to developing and verifying programs with Coq.

### Tutorials and Hints

*   [Coq'Art Exercises and Tutorials (⭐75)](https://github.com/coq-community/coq-art) - Coq code and exercises from the Coq'Art book, including additional tutorials.
*   [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - Introduction to how Coq can be used to define logical concepts and functions and reason about them.
*   [Coq requirements in Common Criteria evaluations](https://www.ssi.gouv.fr/uploads/2014/11/anssi-requirements-on-the-use-of-coq-in-the-context-of-common-criteria-evaluations-v1.1-en.pdf) - Guide on how to write readable and reviewable Coq code in high assurance applications.
*   [Lemma Overloading (⭐25)](https://github.com/coq-community/lemma-overloading) - Demonstration of design patterns for programming and proving with canonical structures.
*   [MathComp Tutorial Materials (⭐12)](https://github.com/math-comp/tutorial_material) - Source code for Mathematical Components tutorials.
*   [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - Basics of using Coq to write formal proofs.
*   [Tricks in Coq (⭐395)](https://github.com/tchajed/coq-tricks) - Tips, tricks, and features that are hard to discover.

