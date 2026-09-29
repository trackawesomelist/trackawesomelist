# Awesome Scala Native Overview

 Compilation of Scala Native resources and libraries 

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/tindzk/awesome-scala-native/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 tindzk/awesome-scala-native](https://github.com/tindzk/awesome-scala-native) · ⭐ 278 · 🏷️ Programming Languages

[ [Daily](/content/tindzk/awesome-scala-native/README.md) / [Weekly](/content/tindzk/awesome-scala-native/week/README.md) / Overview ]

---

# Awesome Scala Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="http://www.scala-native.org/"><img alt="Scala Native" align="right" width="250" height="250" src="https://github.com/tindzk/awesome-scala-native/raw/master/logo.png"></a>

[Scala Native](http://www.scala-native.org/) is an optimising ahead-of-time compiler for the [Scala programming language](https://www.scala-lang.org/). Traditionally, a virtual machine, the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine), was required to run Scala programs. Scala Native taps into the compiler to emit [LLVM intermediate representation](http://llvm.org/docs/LangRef.html) rather than JVM bytecode. Then, the [LLVM](http://llvm.org/) compiler infrastructure is used to produce native libraries and executables. Given that Scala Native executables are stand-alone programs, they generally have a shorter start-up time and low memory consumption. This opens up new avenues to deploy Scala programs where previously the virtual machine would be the limiting factor. For example, developers could write programs for the command line or embedded devices.

## Contents

*   [Awesome Scala Native ](#awesome-scala-native-)
    *   [Contents](#contents)
    *   [Tutorials and Examples](#tutorials-and-examples)
    *   [Build Tools](#build-tools)
    *   [Functional Programming](#functional-programming)
    *   [Unit Tests](#unit-tests)
    *   [Bindings](#bindings)
    *   [File Formats and Parsers](#file-formats-and-parsers)
    *   [Databases](#databases)
    *   [Web Development](#web-development)
    *   [Concurrency](#concurrency)
    *   [Logging](#logging)
    *   [Console](#console)
    *   [Robotics](#robotics)
    *   [Programs](#programs)
    *   [Infrastructure](#infrastructure)
    *   [Licence](#licence)

## Tutorials and Examples

*   [Giter8 template for a minimal Scala Native project (⭐80)](https://github.com/scala-native/scala-native.g8) - Official [Giter8](http://www.foundweekends.org/giter8/) template for a minimal Scala Native project.
*   [Hands on Scala Native (⭐32)](https://github.com/MasseGuillaume/hands-on-scala-native) - Tutorial for implementing a bandwidth monitor with Ncurses.
*   [Starter for Scala Native (⭐27)](https://github.com/GnaneshKunal/scala-native-starter) - Scala Native project that links to a custom C library.
*   [Building C code using sbt-jni (⭐6)](https://github.com/nadavwr/scala-native-sbt-jni-example) - Example for compiling C code in a Scala Native project using [sbt-jni (⭐136)](https://github.com/jodersky/sbt-jni).
*   [Example project with external dependencies (⭐54)](https://github.com/lihaoyi/scala-native-example-app) - Example project that uses external dependencies to generate HTML and run a test suite.
*   [Starter for Gtk+ Projects (⭐2)](https://github.com/jokade/scalanative-gtk-seed.g8) - [Giter8](http://www.foundweekends.org/giter8/) template for Scala Native GUI projects using [Gtk+](https://developer.gnome.org/gtk3/stable/index.html).
*   [Modern systems programming with scala native](https://pragprog.com/titles/rwscala/modern-systems-programming-with-scala-native/) book.
*   [Write a simple CLI application in Scala Native (⭐11)](https://github.com/ItoYo16u/prettytable-native)

## Build Tools

*   [sbt](https://www.scala-sbt.org/) - Scala's standard build tool.
*   [Mill (⭐2.8k)](https://github.com/com-lihaoyi/mill) - Build tool striving for simplicity, inspired by [Bazel](https://www.bazel.build/).
*   [Bloop (⭐942)](https://github.com/scalacenter/bloop) - Scala build server and command-line tool for fast developer workflows.
*   [Seed (⭐238)](https://github.com/tindzk/seed) - Build tool based on Bloop. Focuses on user experience and cross-platform builds, inspired by [Cargo (⭐16k)](https://github.com/rust-lang/cargo).

## Functional Programming

*   [Shapeless (⭐3.4k)](https://github.com/milessabin/shapeless) - Library for generic programming.
*   [Squants (⭐931)](https://github.com/typelevel/squants) - DSL for quantities, units of measure and dimensional analysis.
*   [scalaz (⭐4.7k)](https://github.com/scalaz/scalaz) - Type classes and instances for data structures.
*   [nobox (⭐33)](https://github.com/xuwei-k/nobox) - Immutable primitive array wrapper without boxing.
*   [PPrint (⭐248)](https://github.com/lihaoyi/PPrint) - Pretty-print values and types.
*   [SourceCode (⭐543)](https://github.com/lihaoyi/sourcecode) - Implicits providing meta data similar to `__LINE__` in C.
*   [reactify (⭐93)](https://github.com/outr/reactify) - Functional Reactive Programming framework for Scala.
*   [chimney (⭐1.3k)](https://github.com/scalalandio/chimney) - Boilerplate-free data transformations.
*   [Quicklens (⭐852)](https://github.com/softwaremill/quicklens) - Modify deeply nested case class fields.
*   [Cats (⭐5.5k)](https://github.com/typelevel/cats) - Abstractions for functional programming in Scala.

## Unit Tests

*   [µTest (⭐508)](https://github.com/lihaoyi/utest) - Library for unit tests.
*   [minitest (⭐182)](https://github.com/monix/minitest) - Lightweight testing library.
*   [scalaprops (⭐282)](https://github.com/scalaprops/scalaprops) - Library for property-based testing.
    *   [scalaprops-shapeless (⭐10)](https://github.com/scalaprops/scalaprops-shapeless) - Generation of arbitrary ADT instances.
    *   [scalaprops-cross-example (⭐4)](https://github.com/scalaprops/scalaprops-cross-example) - Cross-platform example.
*   [ScalaCheck (⭐2k)](https://github.com/typelevel/scalacheck) - Property-based testing for Scala.
*   [ScalaTest (⭐1.2k)](https://github.com/scalatest/scalatest) - Testing library.
*   [specs2 (⭐734)](https://github.com/etorreborre/specs2) - Software Specifications for Scala.
*   [Makeshift (⭐1)](https://github.com/nadavwr/makeshift) - Library for unit tests.
*   [MUnit (⭐472)](https://github.com/scalameta/munit) - Scala testing library with actionable errors and extensible APIs.

## Bindings

*   [cmark (⭐16)](https://github.com/sparsetech/cmark-scala) - Bindings for the [cmark (⭐2k)](https://github.com/commonmark/cmark) CommonMark parser library.
*   [libuv (⭐10)](https://github.com/TimothyKlim/scala-native-libuv) - Bindings for [libuv (⭐27k)](https://github.com/libuv/libuv), a library for asynchronous I/O.
*   [SDL2 and OpenGL (⭐45)](https://github.com/regb/scalanative-graphics-bindings) - Bindings for the graphical frameworks [SDL2](https://www.libsdl.org/) and [OpenGL](https://www.opengl.org).
*   [Cocoa (⭐22)](https://github.com/jokade/scalanative-cocoa) - Bindings for the macOS graphical framework [Cocoa](https://en.wikipedia.org/wiki/Cocoa_\(API\)).
*   [GNU Scientific Library (⭐3)](https://github.com/ruivieira/scala-gsl) - Bindings for [GNU Scientific Library (GSL)](https://www.gnu.org/software/gsl).
*   [BLAS (⭐39)](https://github.com/ekrich/sblas) - Bindings for [BLAS](http://www.netlib.org/blas/), a library for Linear Algebra.
*   [Gtk+ (⭐28)](https://github.com/jokade/scalanative-gtk) - Bindings for the [GTK+](https://www.gtk.org/) graphical toolkit.
*   [libsoup (⭐3)](https://github.com/jokade/scalanative-libsoup) - Bindings for the [libsoup](https://wiki.gnome.org/Projects/libsoup) HTTP client/server library.
*   [libui (⭐75)](https://github.com/lolgab/scalaui) - GUI framework based on [libui (⭐11k)](https://github.com/andlabs/libui).
*   [GStreamer (⭐3)](https://github.com/jokade/scalanative-gstreamer) - Bindings for the [GStreamer](https://gstreamer.freedesktop.org) multimedia framework.
*   [Qt (⭐9)](https://github.com/jokade/scalanative-qt5) - Bindings for [Qt](https://www.qt.io).
*   [ncurses (⭐9)](https://github.com/edadma/ncurses) - Bindings for the [GNU Ncurses Library](https://www.gnu.org/software/ncurses/).
*   [readline (⭐0)](https://github.com/edadma/readline) - Bindings for the [GNU Readline Library](https://www.gnu.org/software/readline/).
*   [libsndfile (⭐2)](https://github.com/edadma/libsndfile) - Bindings for the [Libsndfile](https://tiswww.cwru.edu/php/chet/libsndfile/rltop.html) C library for sampled sound manipulation.
*   [libpng (⭐1)](https://github.com/edadma/libpng) - Bindings for the [libpng](http://www.libpng.org/) C reference library for reading and writing PNGs.
*   [libcairo (⭐3)](https://github.com/edadma/libcairo) - Bindings for the [Cairo](https://www.cairographics.org/) 2D graphics C library.
*   [cairo-xlib (⭐0)](https://github.com/edadma/cairo-xlib) - Bindings for the [Cairo](https://www.cairographics.org/) 2D graphics [XLib Surfaces](https://www.cairographics.org/manual/cairo-XLib-Surfaces.html) with bindings for [XLib](https://www.x.org/releases/current/doc/libX11/libX11/libX11.html) as well.
*   [libyaml (⭐0)](https://github.com/edadma/libyaml) - Bindings for the [LibYAML](https://pyyaml.org/wiki/LibYAML) C library for parsing [YAML](https://yaml.org/).
*   [iup (⭐2)](https://github.com/edadma/iup) - Bindings for the [IUP](https://www.tecgraf.puc-rio.br/iup/) multi-platform toolkit for building graphical user interfaces.

## File Formats and Parsers

*   [msgpack4z (⭐5)](https://github.com/msgpack4z/msgpack4z-native) - Implementation of [MessagePack](https://msgpack.org/), a binary serialisation format.
*   [FastParse (⭐1.1k)](https://github.com/com-lihaoyi/fastparse) - Library for defining and running parsers.
*   [scalatags (⭐773)](https://github.com/com-lihaoyi/scalatags) - HTML/XML construction and rendering.
*   [Pine (⭐110)](https://github.com/sparsetech/pine) - HTML/XML parsing, manipulation and rendering.
*   [scala-json (⭐63)](https://github.com/MediaMath/scala-json) - JSON parser.
*   [uPickle (⭐767)](https://github.com/com-lihaoyi/upickle) - uPickle: a simple, fast, dependency-free JSON & Binary (MessagePack) serialization library for Scala
*   [toml-scala (⭐30)](https://github.com/sparsetech/toml-scala) - [TOML (⭐21k)](https://github.com/toml-lang/toml) parser with codec derivation.
*   [argonaut (⭐543)](https://github.com/argonaut-io/argonaut) - Purely functional JSON parser and library.
*   [ScalaPB (⭐1.3k)](https://github.com/scalapb/ScalaPB) - [Protocol Buffer](https://developers.google.com/protocol-buffers/) compiler for Scala.
    *   [scalapb-argonaut (⭐2)](https://github.com/scalapb-json/scalapb-argonaut) - JSON and Protocol Buffer converters for ScalaPB based on [Argonaut](http://argonaut.io).
*   [sconfig (⭐135)](https://github.com/ekrich/sconfig) - [HOCON (⭐135)](https://github.com/ekrich/sconfig/blob/master/docs/original/HOCON.md) parser.
*   [squiggly (⭐3)](https://github.com/edadma/squiggly) - Cross-platform template language for Scala, inspired by Liquid and Hugo templates.

## Databases

*   [scala-native-jdbc (⭐16)](https://github.com/lolgab/scala-native-jdbc) - Port of the database access layer [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) to Scala Native.
*   [SQLite4S (⭐39)](https://github.com/david-bouyssie/sqlite4s) - Port of the Java library [Sqlite4java](https://bitbucket.org/almworks/sqlite4java). Includes bindings for the SQLite native library.
*   [libpq4s (⭐4)](https://github.com/david-bouyssie/libpq4s) - Scala wrapper around the async PostgreSQL C library libpq.
*   [skunk (⭐1.7k)](https://github.com/typelevel/skunk) -  A data access library for Scala + Postgres.

## Web Development

*   [Trail (⭐82)](https://github.com/sparsetech/trail) - Routing library.
*   [sttp (⭐1.5k)](https://github.com/softwaremill/sttp) - HTTP Client library.
*   [snunit (⭐148)](https://github.com/lolgab/snunit) - Scala Native HTTP server based on NGINX Unit.

## Concurrency

*   [scala-native-loop (⭐58)](https://github.com/scala-native/scala-native-loop) - Event loop and async-oriented IO for Scala Native
*   [castor (⭐149)](https://github.com/com-lihaoyi/castor) - Lightweight, typed Actor library for Scala.
*   [Leucine (⭐14)](https://github.com/devlaam/Leucine) - Small cross-platform actor framework

## Logging

*   [scribe (⭐553)](https://github.com/outr/scribe) - Fast and simple logging library.
*   [slogging (⭐52)](https://github.com/jokade/slogging) - [Typesafe-logging (⭐924)](https://github.com/lightbend/scala-logging) and [SLF4J](https://www.slf4j.org/)-compatible logging library based on macros.

## Console

*   [fansi (⭐237)](https://github.com/com-lihaoyi/fansi) - Library for creating [ANSI-coloured strings](https://en.wikipedia.org/wiki/ANSI_escape_code).
*   [scopt (⭐1.4k)](https://github.com/scopt/scopt) - Command-line argument parser.
*   [scala-optparse-applicative (⭐16)](https://github.com/xuwei-k/optparse-applicative) - Port of Haskell's CLI argument parsing library [optparse-applicative](https://hackage.haskell.org/package/optparse-applicative).
*   [scallop (⭐684)](https://github.com/scallop/scallop) - A simple Scala CLI parsing library.
*   [mainargs (⭐215)](https://github.com/com-lihaoyi/mainargs) - Small, dependency-free library for command line argument parsing in Scala.
*   [decline (⭐678)](https://github.com/bkirwi/decline) - A composable command-line parser for Scala.

## Robotics

*   [Potassium (⭐20)](https://github.com/Team846/potassium) - Framework for writing robot software.
*   [WPILib (⭐7)](https://github.com/Team846/scala-native-wpilib) - Reimplementation of the [FIRST Robotics WPILib libraries](http://first.wpi.edu/FRC/roborio/release/docs/java/).

## Programs

*   [sglgears (⭐15)](https://github.com/Milyardo/sglgears) - Port of GL [gears.c (⭐16)](https://github.com/JoakimSoderberg/mesademos/blob/master/src/xdemos/glxgears.c).
*   [k8s-cli (⭐3)](https://github.com/fsat/k8s-cli) - CLI tools to generate [Kubernetes](https://kubernetes.io/) resources for [Akka](https://akka.io/), [Play Framework](https://www.playframework.com/) and [Lagom](https://www.lagomframework.com/)-based applications.
*   [Coursier (⭐2.1k)](https://github.com/coursier/coursier) - Coursier's [`bootstrap` command](https://get-coursier.io/docs/cli-native-bootstrap) generates native launchers.
*   [fractals (⭐7)](https://github.com/Rusty-Bike/fractals) - A self-similar fractal generator with basic animation support.

## Infrastructure

*   [Seed Docker image](https://hub.docker.com/r/tindzk/seed/tags) - Docker image for cross-platform builds with [Seed (⭐238)](https://github.com/tindzk/seed).
*   [scala-native-sbt-docker](https://github.com/ScalaWilliam/scala-native-sbt-docker) - Docker image for Scala Native and sbt.

## Licence

<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /></a><br />This work is licenced under a <a rel="licence" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Licence</a>.

