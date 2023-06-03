# Awesome Zig Overview

A list of awesome projects related to Zig

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/catdevnull/awesome-zig/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 catdevnull/awesome-zig](https://github.com/catdevnull/awesome-zig) · ⭐ 205 · 🏷️ Programming Languages

[ [Daily](/content/catdevnull/awesome-zig/README.md) / [Weekly](/content/catdevnull/awesome-zig/week/README.md) / Overview ]

---

# Awesome Zig [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[<img src="https://github.com/catdevnull/awesome-zig/raw/main/./zig-logo.svg" align="right" width="100">](https://ziglang.org)

A general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software.

## Contents

*   [Algorithms and data structures](#algorithms-and-data-structures)
*   [Allocators and memory](#allocators-and-memory)
*   [Audio](#audio)
*   [Bootables](#bootables)
*   [Compilers and interpreters](#compilers-and-interpreters)
*   [Database](#database)
*   [Editor plugins](#editor-plugins)
*   [Emulators](#emulators)
*   [Game tools and libraries](#game-tools-and-libraries)
*   [Games](#games)
*   [GUI](#gui)
*   [Misc libraries](#misc-libraries)
*   [Network](#network)
    *   [HTTP](#http)
*   [Web](#web)
*   [System tools](#system-tools)
*   [Zig development tools](#zig-development-tools)
    *   [Package managers](#package-managers)
*   [Parser](#parser)
*   [Learning resources](#learning-resources)
*   [C/C++ libraries packaged for Zig](#cc-libraries-packaged-for-zig)
*   [Other](#other)

## Algorithms and data structures

*   [ziglibs/s2s (⭐80)](https://github.com/ziglibs/s2s) - Binary serialization format and library.
*   [BarabasGitHub/LZig4 (⭐4)](https://github.com/BarabasGitHub/LZig4) - LZ4 implementation.
*   [DutchGhost/ArrayVec (⭐14)](https://github.com/DutchGhost/ArrayVec) - An array with a vector feeling.
*   [emekoi/deque.zig (⭐9)](https://github.com/emekoi/deque.zig) - A lock free chase-lev deque.
*   [kristoff-it/zig-cuckoofilter (⭐69)](https://github.com/kristoff-it/zig-cuckoofilter) - Production-ready Cuckoo Filters for any C ABI compatible target.
*   [marijnfs/zigtimsort (⭐5)](https://github.com/marijnfs/zigtimsort) - TimSort implementation.
*   [Sahnvour/zig-containers (⭐7)](https://github.com/Sahnvour/zig-containers) - A container library.
*   [Srekel/zig-sparse-set (⭐49)](https://github.com/Srekel/zig-sparse-set) - Sparse sets, supporting both SOA and AOS style.
*   [hexops/xorfilter (⭐168)](https://github.com/hexops/xorfilter) - Xor Filters for checking if a key is part of a set.
*   [JakubSzark/zig-string (⭐113)](https://github.com/JakubSzark/zig-string) - UTF-8 string data structure.

## Allocators and memory

*   [fengb/zee\_alloc (⭐71)](https://github.com/fengb/zee_alloc) - Tiny allocator primarily targeting WebAssembly.
*   [mdsteele/ziegfried (⭐19)](https://github.com/mdsteele/ziegfried) - A general-purpose memory allocator.
*   [suirad/Seal (⭐6)](https://github.com/suirad/Seal) - An allocator that wraps another allocator and detects if memory is leaked after usage.
*   [Hejsil/zig-gc (⭐31)](https://github.com/Hejsil/zig-gc) - A super simple mark-and-sweep garbage collector.

## Audio

*   [Hejsil/zig-midi (⭐16)](https://github.com/Hejsil/zig-midi)
*   [hazeycode/zig-alsa (⭐1)](https://github.com/hazeycode/zig-alsa) - Bindings for ALSA (libasound).
*   [dantecatalfamo/sndio-zig (⭐1)](https://github.com/dantecatalfamo/sndio-zig) - Bindings for [sndio](https://sndio.org).
*   [orhun/linuxwave (⭐369)](https://github.com/orhun/linuxwave) - Generate music from the entropy of Linux.

## Bootables

*   [AndreaOrru/zen (⭐311)](https://github.com/AndreaOrru/zen) - Experimental operating system.
*   [andrewrk/clashos (⭐192)](https://github.com/andrewrk/clashos) - Multiplayer arcade game for bare metal Raspberry Pi 3 B+.
*   [andrewrk/HellOS (⭐186)](https://github.com/andrewrk/HellOS) - "hello world" x86 kernel example.
*   [chivay/vmt (⭐6)](https://github.com/chivay/vmt) - Toy OS.
*   [DorianXGH/Lukarnel (⭐14)](https://github.com/DorianXGH/Lukarnel) - A microkernel with Rust microservices.
*   [iguessthislldo/georgios (⭐36)](https://github.com/iguessthislldo/georgios) - Hobby Operating System.
*   [jzck/kernel-zig (⭐389)](https://github.com/jzck/kernel-zig) - Hobby x86 kernel.
*   [markfirmware/zig-bare-metal-microbit (⭐29)](https://github.com/markfirmware/zig-bare-metal-microbit) - Bare metal microbit program.
*   [markfirmware/zig-bare-metal-raspberry-pi (⭐64)](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) - Bare metal raspberry pi program.
*   [MasterQ32/RetrOS (⭐47)](https://github.com/MasterQ32/RetrOS) - A retro-style gaming console running on bare x86 metal.
*   [nrdmn/uefi-examples (⭐38)](https://github.com/nrdmn/uefi-examples) - UEFI examples.
*   [nrdmn/uefi-paint (⭐39)](https://github.com/nrdmn/uefi-paint) - UEFI-bootable touch paint app.
*   [rafaelbreno/zig-os (⭐20)](https://github.com/rafaelbreno/zig-os) - A simple OS following Philipp Oppermann's posts "Writing an OS in Rust".
*   [SamTebbs33/pluto (⭐361)](https://github.com/SamTebbs33/pluto) - An x86 kernel.
*   [sjdh02/trOS (⭐44)](https://github.com/sjdh02/trOS) - Tiny aarch64 baremetal OS thingy.
*   [tralamazza/embedded\_zig (⭐56)](https://github.com/tralamazza/embedded_zig) - Minimal embedded ARM example (STM32F103 blue pill).
*   [yvt/zig-armv8m-test (⭐8)](https://github.com/yvt/zig-armv8m-test) - Example app for Armv8-M + TrustZone.
*   [ZeeBoppityZagZiggity/ZBZZ.OS (⭐6)](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS) - An operating system built for RISCV.

## Compilers and interpreters

*   [oven-sh/bun (⭐42k)](https://github.com/oven-sh/bun) - Incredibly fast JavaScript runtime, bundler, transpiler and package manager – all in one.
*   [Vexu/bog (⭐419)](https://github.com/Vexu/bog) - Small, strongly typed, embeddable language.
*   [LoLa Programming Language](https://lola.random-projects.net/) - ([GitHub (⭐152)](https://github.com/MasterQ32/LoLa)) An embeddable programming language for game scripting.
*   [squeek502/zua (⭐115)](https://github.com/squeek502/zua) - An implementation of Lua 5.1 for learning purposes.
*   [CurtisFenner/zsmol (⭐7)](https://github.com/CurtisFenner/zsmol) - The new Smol compiler and reference.
*   [dantecatalfamo/brainfuck-zig (⭐5)](https://github.com/dantecatalfamo/brainfuck-zig) - Brainfuck interpreter.
*   [dantecatalfamo/mruby-zig (⭐25)](https://github.com/dantecatalfamo/mruby-zig) - [mruby](https://mruby.org/) bindings.
*   [dantecatalfamo/wren-zig (⭐25)](https://github.com/dantecatalfamo/wren-zig) - [wren](https://wren.io/) bindings.
*   [fubark/cyber (⭐781)](https://github.com/fubark/cyber) - Fast and concurrent scripting.

## Database

*   [coilhq/tigerbeetle (⭐2.5k)](https://github.com/coilhq/tigerbeetle) - A distributed financial accounting database designed for mission critical safety and performance.
*   [kristoff-it/redis-cuckoofilter (⭐215)](https://github.com/kristoff-it/redis-cuckoofilter) - Hashing-function agnostic Cuckoo filters for Redis.
*   [kristoff-it/zig-okredis (⭐151)](https://github.com/kristoff-it/zig-okredis) - Zero-allocation Client for Redis 6+.
*   [leroycep/sqlite-zig (⭐34)](https://github.com/leroycep/sqlite-zig) - SQLite bindings.
*   [vrischmann/zig-cassandra (⭐4)](https://github.com/vrischmann/zig-cassandra) - Client for Cassandra 2.1+.
*   [vrischmann/zig-sqlite (⭐210)](https://github.com/vrischmann/zig-sqlite) - SQLite wrapper.

## Editor plugins

*   [MarioAriasC/zig-support (⭐62)](https://github.com/MarioAriasC/zig-support) - Language support for JetBrains IDEs (IntelliJ, CLion and others)
*   [isaachier/ztags (⭐16)](https://github.com/isaachier/ztags) - Ctags implementation for Zig.
*   [Tetralux/sublime-zig (⭐2)](https://github.com/Tetralux/sublime-zig) - My own, more lightweight, syntax highlighting for Zig.
*   [ziglang/sublime-zig-language (⭐62)](https://github.com/ziglang/sublime-zig-language) - Zig language support for Sublime Text.
*   [ziglang/vscode-zig (⭐327)](https://github.com/ziglang/vscode-zig) - Zig language support for VSCode.
*   [ziglang/zig-mode (⭐102)](https://github.com/ziglang/zig-mode) - Zig mode for Emacs.
*   [ziglang/zig.vim (⭐301)](https://github.com/ziglang/zig.vim) - Vim configuration for Zig.
*   [zigtools/zls (⭐1.5k)](https://github.com/zigtools/zls) - Zig LSP implementation + Zig Language Server.

## Emulators

*   [fengb/fundude (⭐154)](https://github.com/fengb/fundude) - Gameboy emulator for WASM.
*   [GrooveStomp/chip8-zig (⭐4)](https://github.com/GrooveStomp/chip8-zig) - CHIP-8 emulator.
*   [sourgrasses/ichigo](https://github.com/sourgrasses/ichigo) - Virtual Boy emulator.
*   [floooh/kc85.zig (⭐37)](https://github.com/floooh/kc85.zig) - A KC85 emulator.
*   [Arwalk/ChipZ (⭐0)](https://github.com/Arwalk/ChipZ) A simple Chip8 emulator (library and executable).

## Game tools and libraries

*   [hexops/mach (⭐1.8k)](https://github.com/hexops/mach) - Game engine and graphics toolkit.
*   [michal-z/zig-gamedev (⭐1.5k)](https://github.com/michal-z/zig-gamedev) - DirectX 12 game development ecosystem.
*   [floooh/sokol-zig (⭐182)](https://github.com/floooh/sokol-zig) - [Sokol (⭐4.6k)](https://github.com/floooh/sokol) bindings.
*   [TM35-Metronome/metronome (⭐33)](https://github.com/TM35-Metronome/metronome) - A set of tools for modifying and randomizing Pokémon games.
*   [TM35-Metronome/tm35-nds (⭐10)](https://github.com/TM35-Metronome/tm35-nds) - A library for working with Nintendo DS roms.
*   [user00e00/sudokuinzig (⭐4)](https://github.com/user00e00/sudokuinzig) - Simple and robust sudoku solver.
*   [wendigojaeger/ZigGBA (⭐300)](https://github.com/wendigojaeger/ZigGBA) - SDK for creating Game Boy Advance games using Zig.
*   [hazeycode/brucelib](https://github.com/hazeycode/brucelib) - Monorepo of modules for programming cross-platforms games, simulations, engines & editors.

## Games

*   [Akuli/curses-minesweeper (⭐14)](https://github.com/Akuli/curses-minesweeper) - Minesweeper game written in curses.
*   [andrewrk/tetris (⭐251)](https://github.com/andrewrk/tetris) - A simple tetris clone.
*   [fabioarnold/snake-zig (⭐8)](https://github.com/fabioarnold/snake-zig) - A simple snake clone.
*   [Stenodyon/blink (⭐13)](https://github.com/Stenodyon/blink) - A game about building logic with lasers.
*   [thejoshwolfe/legend-of-swarkland (⭐81)](https://github.com/thejoshwolfe/legend-of-swarkland) - Hack-n-slash roguelike inspired by NetHack.
*   [tiehuis/zstack (⭐3)](https://github.com/tiehuis/zstack) - Line-race tetris mode.
*   [kooparse/zalgebra (⭐155)](https://github.com/kooparse/zalgebra) - Linear algebra library for games and real-time computer graphics.
*   [floooh/pacman.zig (⭐146)](https://github.com/floooh/pacman.zig) - A Pacman clone.
*   [dantecatalfamo/OpenCSE (⭐1)](https://github.com/dantecatalfamo/OpenCSE) - Free implementation of the Can't Stop Express dice game.

## GUI

*   [capy-ui/capy (⭐802)](https://github.com/capy-ui/capy) - Cross-platform library for making true native GUIs.
*   [david-vanderson/gui (⭐56)](https://github.com/david-vanderson/gui) - Immediate mode GUI for Zig.
*   [Aransentin/ZWL (⭐84)](https://github.com/Aransentin/ZWL) - Zig Windowing Library.
*   [prime31/zig-upaya (⭐125)](https://github.com/prime31/zig-upaya) - GUI toolkit.
*   [fubark/cosmic (⭐289)](https://github.com/fubark/cosmic) - GUI toolkit.
*   [batiati/IUPforZig (⭐90)](https://github.com/batiati/IUPforZig) - Zig idiomatic and type-checked bindings for IUP Portable User Interface Toolkit.
*   [andrewrk/zig-sdl (⭐64)](https://github.com/andrewrk/zig-sdl) - Self-contained SDL2 package for Zig.
*   [Snektron/vulkan-zig (⭐243)](https://github.com/Snektron/vulkan-zig) - Vulkan binding generator.
*   [Avokadoen/zig\_vulkan (⭐36)](https://github.com/Avokadoen/zig_vulkan) - Toy renderer using Vulkan and GLFW.
*   [andrewrk/zig-vulkan-triangle (⭐72)](https://github.com/andrewrk/zig-vulkan-triangle) - Simple triangle displayed using Vulkan, GLFW, and Zig.
*   [kassane/QML-zig (⭐46)](https://github.com/kassane/qml_zig) - QML bindings.
*   [cshenton/learnopengl (⭐110)](https://github.com/cshenton/learnopengl) - [Learn OpenGL](https://learnopengl.com) tutorials ported to Zig.
*   [ifreund/river (⭐2.3k)](https://github.com/ifreund/river) - Dynamic wayland compositor that takes inspiration from dwm and bspwm.
*   [Nelarius/weekend-raytracer-zig (⭐78)](https://github.com/Nelarius/weekend-raytracer-zig) - An implementation of the "Ray Tracing in One Weekend" book.
*   [SpexGuy/Zig-Gltf-Display (⭐20)](https://github.com/SpexGuy/Zig-Gltf-Display) - A program that displays glTF files using Vulkan.
*   [tiehuis/zig-raytrace (⭐12)](https://github.com/tiehuis/zig-raytrace) - Simple raytracer.
*   [donpdonp/zootdeck (⭐31)](https://github.com/donpdonp/zootdeck) - Fediverse GTK Desktop Reader.
*   [MasterQ32/ZigPaint (⭐7)](https://github.com/MasterQ32/ZigPaint) - A simple paint application. Used to create an OpenGL loader/wrapper and a minimal UI system.

## Misc libraries

*   [natecraddock/ziglua (⭐81)](https://github.com/natecraddock/ziglua) - Bindings for the Lua C API.
*   [ryoppippi/zigcv (⭐67)](https://github.com/ryoppippi/zigcv) - Bindings for OpenCV4.
*   [BraedonWooding/Lazy-Zig (⭐32)](https://github.com/BraedonWooding/Lazy-Zig) - Linq.
*   [DutchGhost/maybeuninit (⭐1)](https://github.com/DutchGhost/maybeuninit) - MaybeUninit.
*   [emekoi/log.zig (⭐11)](https://github.com/emekoi/log.zig) - A thread-safe logging library.
*   [kprotty/zap (⭐334)](https://github.com/kprotty/zap) - A collection of libraries which provide interfaces over the system for writing high performance applications.
*   [mlarouche/zigimg (⭐240)](https://github.com/mlarouche/zigimg) - Zig library for reading and writing different image formats.
*   [ziglibs/known-folders (⭐154)](https://github.com/ziglibs/known-folders) - Provides access to well-known folders across several operating systems.
*   [SasLuca/zig-nanoid (⭐21)](https://github.com/SasLuca/zig-nanoid) - Battle-tested, tiny, secure, URL-friendly, unique string ID generator. Now available in pure Zig.
*   [kassane/libvlc-zig (⭐10)](https://github.com/kassane/libvlc-zig) - Zig bindings for libVLC media framework.
*   [karlseguin/log.zig (⭐40)](https://github.com/karlseguin/log.zig) - Structured logging library.
*   [dantecatalfamo/9p-zig (⭐3)](https://github.com/dantecatalfamo/9p-zig) - 9P2000 client/server library.

## Network

*   [MasterQ32/zig-network (⭐282)](https://github.com/MasterQ32/zig-network) - Small network abstraction layer around TCP & UDP.
*   [dantecatalfamo/zig-dns (⭐50)](https://github.com/dantecatalfamo/zig-dns) - Experimental DNS library implemented in zig.
*   [euantorano/ip.zig (⭐12)](https://github.com/euantorano/ip.zig) - Library for working with IP Addresses.
*   [lun-4/zigdig (⭐28)](https://github.com/lun-4/zigdig) - Naive DNS client library.
*   [marler8997/netpunch (⭐9)](https://github.com/marler8997/netpunch) - Outbound proxy protocol.
*   [remeh/statsd-zig (⭐4)](https://github.com/remeh/statsd-zig) - Basic DogStatsD UDP server.

### HTTP

*   [Luukdegram/apple\_pie (⭐147)](https://github.com/Luukdegram/apple_pie) - HTTP 1.0/1.1 Server implementation.
*   [truemedian/zfetch (⭐60)](https://github.com/truemedian/zfetch) - HTTP(S) client based on iguanaTLS.
*   [ducdetronquito/requestz (⭐102)](https://github.com/ducdetronquito/requestz) - HTTP client based on h11.
*   [ducdetronquito/h11 (⭐102)](https://github.com/ducdetronquito/h11) - I/O-free HTTP/1.1 implementation inspired by hyper/h11.
*   [lun-4/ziget (⭐13)](https://github.com/lun-4/ziget) - Simple wget without libc.
*   ~~[Vexu/routez (⭐234)](https://github.com/Vexu/routez) - HTTP server.~~
*   [frmdstryr/zhp (⭐298)](https://github.com/frmdstryr/zhp) - Featureful HTTP server.
*   [axgdev/telegram\_echobot\_zig (⭐4)](https://github.com/axgdev/telegram_echobot_zig) - Telegram echo bot.
*   [karlseguin/http.zig (⭐51)](https://github.com/karlseguin/http.zig) - HTTP/1.1 server.
*   [zigzap/zap (⭐210)](https://github.com/zigzap/zap) - blazingly fast, robust HTTP server.

## Web

*   [andrewrk/lua-in-the-browser (⭐26)](https://github.com/andrewrk/lua-in-the-browser) - Using Zig to build Lua for WebAssembly.
*   [karlseguin/websocket.zig (⭐110)](https://github.com/karlseguin/websocket.zig) - A WebSocket implementation.
*   [kivikakk/htmlentities.zig (⭐7)](https://github.com/kivikakk/htmlentities.zig) - HTML5 entity data.
*   [meheleventyone/zig-wasm-test (⭐41)](https://github.com/meheleventyone/zig-wasm-test) - A minimal WebAssembly example using Zig's build system.
*   [shritesh/zig-wasm-dom (⭐103)](https://github.com/shritesh/zig-wasm-dom) - Zig + WebAssembly + JS + DOM.
*   [shritesh/zigfmt-web (⭐34)](https://github.com/shritesh/zigfmt-web) - Zig fmt on the web.
*   [zigwasm/wasm-zig (⭐22)](https://github.com/zigwasm/wasm-zig) - Common WASM runtime binding to C API.
*   [zigwasm/wasmer-zig (⭐43)](https://github.com/zigwasm/wasmer-zig) - Bindings for the Wasmer WebAssembly runtime.
*   [zigwasm/wasmtime-zig (⭐82)](https://github.com/zigwasm/wasmtime-zig) - Bindings of Wasmtime.
*   [batiati/mustache-zig (⭐64)](https://github.com/batiati/mustache-zig) - Mustache implementation.
*   [floscodes/zerve (⭐11)](https://github.com/floscodes/zerve) - Simple framework for writing web services and web apps.

## System tools

*   [pbui-project/pbui-main (⭐89)](https://github.com/pbui-project/pbui-main) - BSD/Linux core utilities written in Zig.
*   [hspak/brightnessztl (⭐4)](https://github.com/hspak/brightnessztl) - A CLI to control device backlight.
*   [thejoshwolfe/hexdump-zip (⭐5)](https://github.com/thejoshwolfe/hexdump-zip) - Produce an annotated hexdump of a zipfile.
*   [kubkon/zacho (⭐34)](https://github.com/kubkon/zacho) - Zig's Mach-O parser.

## Zig development tools

*   [marler8997/zigup (⭐299)](https://github.com/marler8997/zigup) - Download and manage zig compilers.
*   [korandoru/setup-zig (⭐6)](https://github.com/korandoru/setup-zig) - Set up a specific version of Zig environment on GitHub Actions.

### Package managers

*   [zigtools/zpm (⭐65)](https://github.com/zigtools/zpm) - Unofficial Zig package manager.
*   [mattnite/gyro (⭐550)](https://github.com/mattnite/gyro) - Package manager with an index, build runner, and build dependencies.
*   [nektro/zigmod (⭐510)](https://github.com/nektro/zigmod) - Zig package manager.
*   [cheetah/asdf-zig (⭐18)](https://github.com/cheetah/asdf-zig) - Zig plugin for the ASDF package manager.

## Parser

*   [darithorn/zig-toml (⭐68)](https://github.com/darithorn/zig-toml) - A TOML parser.
*   [Himujjal/zig-json5 (⭐24)](https://github.com/Himujjal/zig-json5) - JSON5 parser resembling the `std.json` APIs.
*   [chwayne/rem (⭐74)](https://github.com/chwayne/rem) - An HTML parsing library.
*   [goto-bus-stop/ziguid (⭐7)](https://github.com/goto-bus-stop/ziguid) - GUID parsing/stringifying.
*   [Hejsil/zig-clap (⭐435)](https://github.com/Hejsil/zig-clap) - Simple command line argument parsing library.
*   [sam701/zig-cli (⭐50)](https://github.com/sam701/zig-cli) - Package for building command line apps.
*   [kivikakk/libpcre.zig (⭐16)](https://github.com/kivikakk/libpcre.zig) - Bindings to libpcre for Perl-compatible regular expressions.
*   [kivikakk/koino (⭐92)](https://github.com/kivikakk/koino) - CommonMark/GitHub Flavored Markdown parser and HTML renderer.
*   [kubkon/zig-yaml (⭐72)](https://github.com/kubkon/zig-yaml) - YAML parser.
*   [sreehax/zig-ini (⭐2)](https://github.com/sreehax/zig-ini) - .ini parser.
*   [Nulo/ini-parser](https://gitea.nulo.in/Nulo/ini-parser) - .ini parser.
*   [tiehuis/zig-regex (⭐86)](https://github.com/tiehuis/zig-regex) - A regex implementation.
*   [tiehuis/zig-ryu (⭐14)](https://github.com/tiehuis/zig-ryu) - Port of [ryu (⭐1k)](https://github.com/ulfjack/ryu).
*   [Vexu/zuri (⭐43)](https://github.com/Vexu/zuri) - URI parser.
*   [vi/zigmkv (⭐10)](https://github.com/vi/zigmkv) - Matroska/webm (mkv) parser.
*   [winksaville/zig-parse-args (⭐0)](https://github.com/winksaville/zig-parse-args) - Parse command line arguments.
*   [winksaville/zig-parse-number (⭐0)](https://github.com/winksaville/zig-parse-number) - Implement ParseNumber which can parse any TypeId.Int or TypeId.Float.
*   [gernest/base32 (⭐7)](https://github.com/gernest/base32) - Base32 encoding/decoding.
*   [caolan/zig-netstring](https://git.sr.ht/~caolan/zig-netstring) - Netstring parser.
*   [Arwalk/zig-protobuf (⭐66)](https://github.com/Arwalk/zig-protobuf) - Implementation of Protocol Buffers v3 leveraging Zig's comptime.
*   [iddev5/inon (⭐10)](https://github.com/iddev5/inon) - Data configuration file format.
*   [naneros/ztoml](https://codeberg.org/naneros/ztoml.git) - TOMLv1.0.0 parser and convert TOML to JSON.

## Learning resources

*   [belse-de/zig-tut (⭐13)](https://github.com/belse-de/zig-tut) - A collection of small projects and tutorials to learn Zig.
*   [Sobeston/ziglearn (⭐337)](https://github.com/Sobeston/ziglearn) - Zig learning resources.
*   [ratfactor/ziglings (⭐2.9k)](https://github.com/ratfactor/ziglings) - Learn Zig by fixing tiny example programs.

## C/C++ libraries packaged for Zig

These C/C++ libraries were packaged to be used with the Zig build and packaging system (build.zig.)

### C

*   [andrewrk/SDL (⭐19)](https://github.com/andrewrk/SDL) - Simple Directmedia Layer.
*   [andrewrk/ffmpeg (⭐21)](https://github.com/andrewrk/ffmpeg) - library only.
*   [andrewrk/libgroove (⭐277)](https://github.com/andrewrk/libgroove)
*   [andrewrk/libsoundio (⭐1.7k)](https://github.com/andrewrk/libsoundio/tree/zig-pkg)
*   [kassane/openssl (⭐1)](https://github.com/kassane/openssl) - crypto, providers & ssl libraries only.
*   [kassane/libbpf (⭐0)](https://github.com/kassane/libbpf) - BPF CO-RE (Compile Once – Run Everywhere).
*   [kassane/winpthreads (⭐3)](https://github.com/kassane/winpthreads-zigbuild) - MinGW pthread library.

### C++

*   [andrewrk/libchromaprint (⭐0)](https://github.com/andrewrk/libchromaprint)
*   [kassane/asio (⭐1)](https://github.com/kassane/asio) - (non-boost) Networking I/O library (w/ event-loop, C++14/17/20).
*   [kassane/fmt (⭐0)](https://github.com/kassane/fmt)
*   [kassane/hana (⭐0)](https://github.com/kassane/hana) - (boost-hana) Meta-programming library (header-only, C++14/17/20).>
*   [kassane/catch2 (⭐0)](https://github.com/kassane/catch2) - Unit testing library (C++14/17/20).
*   [kassane/outcome (⭐0)](https://github.com/kassane/outcome) - (non-boost) Error handler (C++14/17/20).
*   [kassane/json (⭐0)](https://github.com/kassane/json) - jsoncpp ported to Zig packaging.
*   [kassane/range (⭐0)](https://github.com/kassane/range-v3) - modern range library (C++14/17/20).
*   [kassane/libzmq (⭐0)](https://github.com/kassane/libzmq) - ZeroMQ core engine in C++ library.

## Other

*   [All Your Codebase](https://allyourcodebase.com/) - Development status of Zig and its' ecosystem.
*   [zig.pm](https://zig.pm/) - A community-maintained repository of Zig packages.
*   [hspak/geteltorito-zig (⭐7)](https://github.com/hspak/geteltorito-zig) - Geteltorito re-write in Zig.
*   [momumi/x86-zig (⭐27)](https://github.com/momumi/x86-zig) - Library for assembling x86.
*   [nrdmn/ilo\_license\_key (⭐12)](https://github.com/nrdmn/ilo_license_key) - ILO license key library.
*   [vegecode/svd2zig (⭐28)](https://github.com/vegecode/svd2zig) - Convert System View Description (svd) files to Zig headers for baremetal development.
*   [mqttiotstuff/iotmonitor (⭐16)](https://github.com/mqttiotstuff/iotmonitor) - MQTT IotMonitor tools, save time to monitor mqtt agents or devices.
*   [ve-nt/outfieldr](https://gitlab.com/ve-nt/outfieldr) - [TLDR (⭐44k)](https://github.com/tldr-pages/tldr) client.
*   [kubkon/zig-ios-example (⭐82)](https://github.com/kubkon/zig-ios-example) - Minimal `build.zig` for targeting iOS.
*   [ynuwenhof/zigbraten (⭐1)](https://github.com/ynuwenhof/zigbraten) - Proof of concept internal cheat for Cube 2: Sauerbraten.

