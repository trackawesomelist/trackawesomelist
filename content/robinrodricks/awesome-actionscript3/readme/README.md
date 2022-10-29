# Awesome Actionscript3 Overview

A curated list of awesome libraries and components for ActionScript 3 and Adobe AIR.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/robinrodricks/awesome-actionscript3/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 robinrodricks/awesome-actionscript3](https://github.com/robinrodricks/awesome-actionscript3) · ⭐ 187 · 🏷️ Programming Languages

[ [Daily](/content/robinrodricks/awesome-actionscript3/README.md) / [Weekly](/content/robinrodricks/awesome-actionscript3/week/README.md) / Overview ]

---

[<img src="https://rawgit.com/hgupta9/awesome-actionscript3/master/AS3_AIR.png" align="right" width="150">](https://www.adobe.com/products/air.html)

# Awesome ActionScript 3 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome libraries and components for ActionScript 3 and Adobe AIR.

[Adobe AIR](https://en.wikipedia.org/wiki/Adobe_AIR) provides a single set of APIs to build cross-platform desktop/mobile applications and games. [ActionScript 3](https://en.wikipedia.org/wiki/ActionScript) is the programming language for AIR. Powerful native functionality such as file system, SQLite, sensors are included by default. To add missing functionality, you can build ANEs (Air Native Extensions) coded in the native language (eg VC++ for Windows, Java for Android, Swift/Objective-C for iOS). To build mobile apps/games with GPU-rendered graphics, use the [Starling](https://gamua.com/starling/) framework and optionally the [Feathers UI](https://feathersui.com/). Adobe AIR is very popular in the mobile gaming space.

Contributions welcome. To add a useful project simply create an [Issue](https://github.com/hgupta9/awesome-actionscript3/issues).

## Contents

*   [Development Tools](#development-tools)
*   [Frameworks](#frameworks)
*   [User Interface](#user-interface)
*   [Multimedia](#multimedia)
*   [Database](#database)
*   [File Formats](#file-formats)
*   [Networking](#networking)
*   [Utilities](#utilities)
*   [Runtimes](#runtimes)
*   [AIR Native Extensions](#air-native-extensions)

## Development Tools

*This section includes commercial tools as well as free/open source tools.*

#### Code Editors

*   [FlashDevelop](http://flashdevelop.org/) - Premiere free & open-source IDE for AS3 & AIR, with code completion, debugging, and more.
*   [Powerflasher FDT](http://fdt.powerflasher.com/) - Commercial IDE built on the Eclipse platform for development of Adobe Flash/AIR content.
*   [Adobe Flash Builder](https://www.adobe.com/products/flash-builder.html) - Commercial IDE for building applications on the Flex framework (with advanced debugging tools).
*   [Moonshine IDE](http://moonshine-ide.com/) - Moonshine is a free and open source middleweight IDE built with ActionScript 3 for ActionScript 3, Apache Flex®, Apache FlexJS® and Feathers development with Cloud and Desktop support.
*   [IntelliJ IDEA](https://www.jetbrains.com/help/idea/building-actionscript-and-flex-applications.html) - Commercial IDE that supports many different languages including AS3.
*   [Visual Studio Code](https://as3mxml.com/) - An AS3 & MXML language extension for Visual Studio Code. Runs on Windows, macOS, and Linux.

#### Live Debuggers

*   [Adobe Scout](https://www.adobe.com/products/scout.html) - Advanced visual profiling and debugging tool for AIR apps & games (supports Stage3D).
*   [De-Monster Debugger](https://github.com/MrTact/monsterdebugger) - Advanced tool to debug graphics and data from a live AIR application.
*   [De-Monster Debugger (Starling)](https://github.com/joshtynjala/monsterdebugger-client-starling) - Fork of De-Monster Debugger with support for Starling Framework.

#### Asset Creators

*   [Adobe Animate CC](https://www.adobe.com/products/animate.html) - Premiere vector graphics and animation toolset for vector/spritesheet creation.
*   [TILED Map Editor](http://www.mapeditor.org/) - Flexible tile map editor compatible with various AS3 game engines.
*   [FlashMovieClipConverter](https://github.com/zenrobin/FlashMovieClipConverter) - Converts a Flash MovieClip to a Starling IAnimatable Sprite.

#### SWF Obfuscators

*   [secureSWF](http://www.kindi.com/) - Commercial AS3/AIR obfuscator with renaming, asset encryption and automatic code optimization.
*   [irrFuscator](http://www.ambiera.com/irrfuscator/) - Commercial AS3 obfuscator for Flash and Flex SWF files.

#### SWF Inspectors

*   [SWFWire](https://github.com/magicalhobo/SWFWire) - Advanced SWF Decompiler, Inspector and Debugger Tools ([website](http://www.swfwire.com/)).
*   [Velocity9](https://github.com/velocity9/Inspector) - Basic SWF Inspector.

#### SWF Decompilers

*   [AS3Sorcerer](http://www.as3sorcerer.com/) - Premiere AS3 decompiler with 99% decompilation accuracy (supports SWF/SWC, Alchemy opcodes).
*   [Sothink Decompiler](http://www.sothink.com/product/flashdecompiler/) - Advanced decompiler for AS2/AS3 (supports asset extraction and conversion of SWF to FLA/Flex).

#### ANE Dev Tools

*   [FreSharp](https://github.com/tuarua/FreSharp) - Build ANEs using C# with this C# wrapper for FlashRuntimeExtensions .
*   [Swift-IOS-ANE](https://github.com/tuarua/Swift-IOS-ANE) - ANE starter kit written in Swift 3 for iOS 10 .

## Frameworks

#### MVC Frameworks

*   [PureMVC](https://github.com/PureMVC/puremvc-as3-standard-framework) - Industry-standard MVC framework for Flash ([multicore](https://github.com/PureMVC/puremvc-as3-multicore-framework)).
*   [Robotlegs](https://github.com/robotlegs/robotlegs-framework) - Dependency injection, module/view/command management framework for Flash.
*   [Hummingbird](https://github.com/flashapi/hummingbird) - Build and deploy robust MVC applications for AS3, Mobile and the Starling Framework.
*   [Apollo](https://github.com/LaurentZuijdwijk/Apollo) - Dependency injection and messaging framework, which can be used as the basis for MVC projects.
*   [Somacore](https://github.com/soundstep/somacore_framework) - Lightweight event-based AS3 MVC framework.
*   [Kote](https://github.com/whitered/Kote) - Fast and lightweight MVC framework that brings together the best of PureMVC and as3-signals.
*   [StarlingMVC](https://github.com/CreativeBottle/starlingMVC) - IOC Framework for Starling based games.

#### UI Frameworks

*   [Starling](https://gamua.com/starling/) - High-performance 2D graphics engine built on Stage3D. API identical to Flash API. ([github](https://github.com/Gamua/Starling-Framework), [help](http://wiki.starling-framework.org/start)).
*   [Feathers UI](https://feathersui.com/) - User interface components for Starling Framework ([github](https://github.com/BowlerHatLLC/feathers), [help](https://feathersui.com/help/index.html)).
*   [Flow](https://github.com/artman/Flow) - Layout, effects, data binding and remoting framework to be used instead of Flex.
*   [AS3Commons UI](https://github.com/AS3Commons/as3commons-ui) - Layouting, focus and keyboard management framework.
*   [Swiz](https://github.com/swiz/swiz-framework) - Brutally simple micro-architecture for creating RIAs with AS3 and Adobe Flex.
*   [Hiddenwood](https://github.com/raweden/Project-Hiddenwood) - User interface library developed for a web app project, written in AS3 and in a MVC pattern.
*   [Elastic-Lists](https://github.com/MoritzStefaner/Elastic-Lists) - Fluid and powerful interface for facet browsing.
*   [Apache Flex®](https://flex.apache.org/) - The Apache Flex® SDK is the evolution of the popular Adobe Flex SDK. The Apache Flex® SDK is an application development framework for easily building Flash-based applications for mobile devices, web browsers, and desktop platforms.
*   [Apache Royale®](http://royale.apache.org/) - The Apache Royale® project is developing a next-generation of the Apache Flex® SDK. Royale has the goal of allowing applications developed in MXML and ActionScript to not only run in the Flash/AIR runtimes, but also to run natively in the browser without Flash, on mobile devices as a PhoneGap/Cordova application, and in embedded JS environments such as Chromium Embedded Framework. Royale has the potential to allow your MXML and ActionScript code to run in even more places than Flash currently does.

#### Game Frameworks

*   [CitrusEngine](http://citrusengine.com/) - Professional-grade game engine built built on Starling & Away3D.
*   [StarlingPunk](https://github.com/asaia/StarlingPunk) - Framework built on Starling to add structure and organization to your game projects.
*   [FlashPunk](https://github.com/useflashpunk/FlashPunk) - Framework to build 2D games. Provides graphics, events, inputs, animation, etc.
*   [Flixel](https://github.com/AdamAtomic/flixel) - Useful base classes that you can extend to make your own game objects.
*   [Tetragon](https://github.com/NothingInteractive/tetragon) - Cross-platform framework to build any kind of game. Provides resource management, debugging facilities, multi-locale support, layered extendability, a game-oriented data structure, and more.
*   [Pixelizer](https://github.com/johanp/Pixelizer) - Component based game engine to build 2D games. Provides rendering, animation, input, etc.
*   [AS3isolib](https://github.com/as3isolib/as3isolib.v1) - Isometric Library developed to assist in creating isometrically projected games.
*   [IsoHill](https://github.com/jadbox/IsoHill-Game-Engine) - GPU-based Isometric engine built on Starling, with TILED map parser, layers, etc ([website](http://www.isohill.com/)).
*   [YCanvas](https://github.com/jozefchutka/YCanvas) - High-performance 2D tile renderer and world map renderer.
*   [ND2D](https://github.com/lrrrs/nd2d) - GPU-accelerated 2D game engine using Stage3D ([ND2Dx](https://github.com/NoRabbit/ND2Dx)).
*   [Nexus](https://github.com/tversteeg/Nexus) - GPU-accelerated 2D game engine using Stage3D.

#### 3D Frameworks

*   [AwayBuilder](http://awaytools.com/awaybuilder/) - Visual workflow tool to import, optimise and bake 3D assets from a variety of sources.
*   [Away3D](https://github.com/away3d/away3d-core-fp11) - Open-source GPU-accelerated 3D engine for Flash Player 11+ ([examples](https://github.com/away3d/away3d-examples-fp11)).
*   [Away3D OpenFL](https://github.com/away3d/away3d-core-openfl) - Away3D for Neko, HTML5 and native CPP. ([examples](https://github.com/away3d/away3d-examples-openfl)).
*   [AwayPhysics FP11](https://github.com/away3d/awayphysics-core-fp11) - Away Physics - 3D physics library for the Away3D FP 11 ([examples](https://github.com/away3d/awayphysics-examples-fp11)).
*   [Alternativa3D](https://github.com/AlternativaPlatform/Alternativa3D) - Alternativa3D GPU accelerated 3D engine ([examples](https://github.com/AlternativaPlatform/Alternativa3DExamples)).
*   [Flare3D](http://flare3d.com/) - Commercial 3D platform with high-performance engine and Level-editor IDE.
*   [Zen3D](https://github.com/hgupta9/Zen3D) - High-performance 3D engine for Adobe Flash & AIR (GPU based).

#### Animation

*   [GreenSock GSAP](https://greensock.com/gsap-as) - The industry-standard animation library for Flash (TweenLite, TweenMax) ([github](https://github.com/greensock/GreenSock-AS3)).
*   [GTween](http://gskinner.com/libraries/gtween/) - Small but robust library for programmatic tweening, animation, and transitions.
*   [DragonBones](http://dragonbones.github.io/) - High-speed skeletal animation using Starling, and tools to export animations from Flash Pro.
*   [FlashEff2](http://www.flasheff.com/) - Premiere programmatic animation library with 100+ transitions and text effects.
*   [FlashEffNano](http://www.flasheffnano.com/) - FlashEff transition library optimized for mobile devices, with 20+ transitions in 750 styles.
*   [StarlingGAFPlayer](https://github.com/zenrobin/StarlingGAFPlayer) - Play back GAF animations using Starling (animations authored in Flash Pro).

#### Signals

*   [AS3-signals](https://github.com/robertpenner/as3-signals) - New approach for AS3 events inspired by C# events and signals/slots in Qt.
*   [react-as3](https://github.com/tconkling/react-as3) - Signals/slots and functional reactive programming library.
*   [Signaller](https://github.com/whitered/Signaller) - Signals implementation with restricted rights for dispatching.
*   [Fa-as3](https://github.com/fabrikagency/fa-as3) - Write less, do more framework, modeled like jQuery.

#### Functional

*   [AS3FP](https://github.com/jadbox/AS3FP) - Collection of functional idioms based on Haskell and Coffeescript.
*   [Raix](https://github.com/richardszalay/raix) - Reactive And Interactive eXtensions simplifies working with interactive data (arrays) or reactive data (events).
*   [Fxp-as3](https://github.com/j3k0/fxp-as3) - Functional library inspired by the "mostly adequate guide".

#### Unit Testing

*   [AS3unit](https://github.com/Hoten/as3unit) - Unit testing framework for ActionScript 3.
*   [hamcrest-as3](https://github.com/drewbourne/hamcrest-as3) - Matcher objects allowing 'match' rules to be defined declaratively.
*   [expect.as](https://github.com/krzysztof-o/expect.as) - BDD-style assertion library for ActionScript 3.
*   [AS3spec](https://github.com/f1337/as3spec) - Tiny BDD framework for AS3, inspired by Bacon and RSpec.
*   [Flexunit](https://github.com/flexunit/flexunit) - FlexUnit project for Actionscript 3 and Flex projects.
*   [ASunit](https://github.com/patternpark/asunit) - The only unit test framework that supports Flash Players 6, 7, 8, 9 and 10.
*   [RobotEyes](https://github.com/Stray/RobotEyes) - End-to-end testing for TDD. Hybrid of WindowLicker and Drew Bourne's Mockolate.

## User Interface

#### UI Components

*   [MinimalComps](https://github.com/minimalcomps/minimalcomps) - Minimal ActionScript 3.0 UI Components for Flash.
*   [MadComponents](https://github.com/danfreeman/MadComponents) - Popular Mobile UI Framework for AS3 / AIR.
*   [AsWing](https://github.com/dreamsxin/AsWing) - Open Source Flash ActionScript GUI framework.
*   [GPUI](https://github.com/inspirit/GPUI) - Tiny GUI Library based on Stage3D (GPU).
*   [Falcon](https://github.com/HendrixString/Falcon) - responsive/flexible mobile ui controls for Feathers.
*   [Flex-maps](https://github.com/igorcosta/flex-maps) - Definitive solution for maps in Apache Flex.
*   [FlexBook](https://github.com/blvz/FlexBook) - Awesome Page Flip component for Flex.
*   [Flex-Android-Material-Skins](https://github.com/quick6black/flex-Android-Material-Skins) - Android Material Design skins for Flex Mobile components.

#### Starling Components

*   [TabbedApplication](https://github.com/pol2095/Feathers-Extension-Tabbed-Application) - View-based navigation model with swipe to navigate tabs.
*   [DataGrid](https://github.com/pol2095/Feathers-Extension-DataGrid) - Displays a datagrid with column headings and smooth scrolling.
*   [DataTree](https://github.com/pol2095/Feathers-Extension-Tree) - Displays hierarchical data arranged as an expandable tree.
*   [Canvas](https://github.com/pol2095/Feathers-Extension-Canvas) - Supports basic vector drawing functionality.
*   [CircleProgress](https://github.com/pol2095/Feathers-Extension-CircleProgress) - Displays progress using a radial progressbar.
*   [ZoomableControl](https://github.com/pol2095/Feathers-Extension-ZoomableControl) - Allows a pinch to zoom using the multitouch inputs.
*   [Toaster](https://github.com/pol2095/Feathers-Extension-Toaster) - Simple feedback about an operation in a small popup. .
*   [Google Maps](https://github.com/ZwickTheGreat/feathers-maps) - Google Maps for Starling, optimized for mobile devices.

#### Layout

*   [Adobe TLF](https://github.com/apache/flex-tlf) - Adobe/Apache Flex Text Layout Framework (TLF).
*   [TinyTLF](https://github.com/joelhooks/tinytlf) - Versatile text layout framework built on top of the Flash Text Engine for Flash/Flex.
*   [TransformManager](https://greensock.com/TransformManager) - By Greensock. Interactive scaling/rotating/moving of DisplayObjects.
*   [TransformTool](https://github.com/senocular/TransformTool) - Free Transform Tool (AS, JS) for manipulating objects in 2D space.
*   [Argilla-Mosaic](https://github.com/folletto/Argilla-Mosaic) - Dynamic layout library.
*   [xrope](https://github.com/evan-liu/xrope) - Simple layout library for native AS3 display objects.
*   [miglayout-as](https://github.com/develar/miglayout-as) - Port of MigLayout, a superbly versatile Flash/Flex/FlashCocoa (SWT/Swing/JavaFX) layout manager.

#### Multi Touch

*   [TUIO Client](https://github.com/lagerkoller/tuio-as3) - Common framework for multi-touch hardware, supporting TUIO/FLC and TUIO/TCP ([web](http://www.tuio.org/?flash)).
*   [Gestouch](https://github.com/fljot/Gestouch) - Multitouch gesture recognition library for building better Natural User Interfaces.
*   [Gestures.IO](https://github.com/GesturesIO/gesturesio-as3) - Simplifies the way you create gesture-based Natural Interactions.
*   [TouchScript](https://github.com/TouchScript/TouchScript.as3) - Multitouch framework that makes handling complex gesture interactions on large touch surfaces easier.

#### Game Controllers

*   [AS3dpad](https://github.com/duckleg/as3dpad) - A virtual touchscreen gamepad designed for Adobe AIR Mobile (Android/iOS).
*   [Gamepad](https://github.com/iainlobb/Gamepad) - Simulates an analog joystick input using the keyboard.
*   [Advanced\_Joystick](https://github.com/justjoeyuk/Advanced_Joystick) - Joystick for the Starling Framework, designed for Adobe AIR Mobile.
*   [AS3-Controller-Input](https://github.com/arkeus/as3-controller-input) - Interact with Ouya and Xbox360 game controllers from Adobe AIR.

## Multimedia

#### Augmented Reality

*   [FLARToolKit](https://github.com/Saqoosha/FLARToolKit) - AS3 port of the industry standard ARToolkit library, for Flash Player 11. ([website](http://www.libspark.org/wiki/saqoosha/FLARToolKit/en)).
*   [FLAREmulator](https://github.com/theflashbum/FLAREmulator) - Test AR demos to see what works and what doesn't with or without a webcam.
*   [FLARManager](http://words.transmote.com/wp/flarmanager/) - Lightweight framework for building augmented reality apps, using FLARToolkit/flare.tracker/flare.NFT.
*   [NyARToolkitAS3](https://github.com/nyatla/NyARToolkitAS3) - NyARToolkit AS3 edition. Marker based Augmented reality library.
*   [EZFLAR](https://github.com/tcha-tcho/EZFLAR) - A little wrapper to ease the way AR works.
*   [IN2AR](https://github.com/inspirit/IN2ARSDKExamples) - SDK for IN2AR cross-platform Augmented Reality Engine.

#### Data Visualization

*   [Axiis](https://github.com/hgupta9/AxiisCharts) - Data visualization framework with line, bar, wedge, column, cluster, area, smith and treemap charts.
*   [Open Flash Charts](https://sourceforge.net/projects/openflashchart/) - Line charts, Area charts, Bar charts, Pie charts, Scatter charts.
*   [Flare](https://github.com/prefuse/Flare) - charts and graphs, supports data management, visual encoding, animation, and interaction techniques.
*   [clearmaps](https://github.com/sunlightlabs/clearmaps) - Mapping framework for data visualization.
*   [redada](https://github.com/geraldo/redada) - Interactive visualization of weighted graphs using GraphML files.
*   [Flextreemap](https://github.com/joshtynjala/flextreemap) - TreeMap data visualization component for Adobe Flex.
*   [GraphVisualizer](https://github.com/armisael/GraphVisualizer) - A Flex 3 + ActionScript 3 web software to draw dynamic graphcs.
*   [Weave](https://github.com/WeaveTeam/Weave) - Web-based Analysis and Visualization Environment.
*   [Social-grid](https://github.com/Instrument/social-grid) - Abstract Grid Visualization for Social Media.

#### Camera

*   [CameraDetection](https://github.com/cataclysmicrewind/CameraDetection) - Camera detection.
*   [Fluocam](https://github.com/Fluocode/Fluocam) - Virtual camera for Starling applications.
*   [WebcamRecorder](https://github.com/Stupeflix/WebcamRecorder) - Chromeless video/audio/still image recording from webcams.
*   [FlashyWrappers](https://github.com/rainbowcreatures/FlashyWrappers) - Recording video from AIR apps on Windows/Android/iOS/OSX.

#### Image

*   [Scale9Image](https://github.com/Tibus/Scale9Image) - Optimized scale9Grid image for starling.
*   [ASImageLib](https://github.com/terrynoya/ASImageLib) - BMP/PNG decoder for actionscript.
*   [Async-Image-Encoders](https://github.com/LeeBurrows/Async-Image-Encoders) - Asynchronously encode BitmapData objects into image file format.
*   [Flip-Planes-AS3](https://github.com/jamesflorentino/Flip-Planes-AS3) - Photo slideshow effects.
*   [AS3-transitions-lib](https://github.com/foo123/as3-transitions-lib) - Image Transitions Library.
*   [Inspirit Image](https://github.com/hgupta9/InspiritImage) - FFT, SURF, edge detection, fluid solver, etc.
*   [Inspirit GPUImage](https://github.com/inspirit/GPUImage) - Framework for GPU-based image processing.
*   [AS3potrace](https://github.com/PowerflasherBR/as3potrace) - POTrace implementation, to trace bitmap images to vector.
*   [ATF-Encoder](https://github.com/plepers/ATF-Encoder) - Encode/decode ATF (Adobe Texture Format) files in pure AS3.
*   [AS3-klt](https://github.com/motemen/as3-klt) - Kanade-Lucas-Tomasi feature tracker implementation.

#### Font

*   [Firetype](https://github.com/MaxDidIt/firetype) - Parse OpenType fonts and render them using Stage3D.
*   [BMFontRenderer](https://github.com/bengarney/BMFontRenderer) - AS3 renderer for bitmap font data in the BMFont format.
*   [HanFont](https://github.com/kyoji2/HanFont) - AIR app for Chinese Font Embeding in ActionScript.
*   [Ficon.as](https://github.com/dv/Ficon.as) - Library to easily include icon fonts.

#### Particle

*   [Flint](https://github.com/richardlord/Flint) - Particle Engine for Flash and Flex.
*   [Desuade Partigen](http://desuade.com/partigen) - Desuade Partigen particle generation system ([github](https://github.com/andrewfitz/desuade)).
*   [Angulex](https://github.com/cosmindolha/ParticleDesigner) - Particle Designer for the Starling framework (ActionScript 3).
*   [SAP](https://github.com/gonchar/SAP) - Particle System for Starling.
*   [Starling-Particles](https://github.com/Gamua/Starling-Extension-Particle-System) - Particle system for the Starling framework, compatible with the "Particle Designer" from 71squared.com.
*   [MotionParticleSprite](https://github.com/bjeld/motionparticlesprite) - Design motion paths in Flash Pro and use it to guide Starling particles.

#### Panorama Viewer

*   [Pantaloons](https://github.com/EyeSee360/Pantaloons) - Panoramic viewing in Flash Player.
*   [SaladoPlayer](https://github.com/mstandio/SaladoPlayer) - Panorama viewer.
*   [PanoramicViewer](https://github.com/BrianMehrman/PanoramicViewer) - 3D Panoramic Viewer.
*   [Sphere\_panorama](https://github.com/suzumura-ss/flash_sphere_panorama) - Panorama player with equirectangular texture written in AS3 (Alternativa3D).
*   [CuTy](https://github.com/fieldOfView/CuTy) - QTVR Panorama viewer based on Flash 10.

#### QR Code

*   [Zxing AS3](https://github.com/zxing/zxing/tree/c1df162b95e07928afbd4830798cc1408af1ac67/actionscript) - QR code detection and generation ([docs](https://zxing.github.io/zxing/)).
*   [AS3-qrcode-encoder](https://github.com/jbpin/as3-qrcode-encoder) - QR code encoder in as3.
*   [qrcode-as](https://github.com/yanbe/qrcode-as) - QR Code reader which supports webcam on Windows, Mac and Linux.

#### Sound

*   [SoundAS](https://github.com/treefortress/SoundAS) - Modern & lightweight sound manager for AS3.
*   [Standingwave3](https://github.com/maxl0rd/standingwave3) - Dynamic audio library.
*   [Standingwave3-addons](https://github.com/charlesclements/standingwave3-addons) - Addons for SW3.
*   [Soundtouch-as3](https://github.com/also/soundtouch-as3) - AS3 Port of the SoundTouch Sound Processing Library.
*   [SeiON](https://github.com/cardin/SeiON) - Sound Management Library.
*   [AS3-Sound-Manager](https://github.com/GrupoW/as3-Sound-Manager)- Upgraded version of the Sound Manager Class from Matt Przybylski.
*   [AS3sfxr](https://github.com/SFBTom/as3sfxr) - Port of sfxr from C++ to AS3, using the new sound and file capabilities of Flash Player 10.
*   [AS3-audio](https://github.com/singuerinc/as3-audio) - Audio Management in Actionscript.
*   [SiON](https://github.com/keim/SiON) - Flash Software Synthesizer.
*   [FlashWavRecorder](https://github.com/michalstocki/FlashWavRecorder) - Recording audio and saving as a WAV.
*   [Local-recorder](https://github.com/pauln/local-audio-recorder) - Local audio recorder (no streaming server required).  Currently requires Flash Player 10.1 or above.
*   [Jukebox](https://github.com/AlwynW/Jukebox) - Music manager for Actionscript 3 projects.
*   [Flod](https://github.com/photonstorm/Flod) - Amiga SoundTracker (MOD) and FastTracker (XM) Replay Library.

#### Video Player

*   [Flowplayer](https://github.com/flowplayer/flash) - Flowplayer Flash, the video player for the Web.
*   [Goplayer](https://github.com/dbrock/goplayer) - Modern open-source video player written in ActionScript 3.
*   [OSFlashVideoPlayer](https://github.com/FlashJunior/OSFlashVideoPlayer) - Open source flash video player.
*   [F4player](https://github.com/gokercebeci/f4player) - Open Source AS3 Flash Video Player.
*   [dashas](https://github.com/castlabs/dashas) - MPEG-DASH player written in ActionScript.
*   [hlsplayer](https://github.com/erlyvideo/hlsplayer) - HLS player for OSMF flash framework.
*   [vgaplayer](https://github.com/euske/vgaplayer) - Open source player for Adobe Flash Media Server streams (RTMP).

## Database

#### SQLite

*   [AS3Query](https://github.com/kemsky/as3Query) - Another SQLite ORM and query DSL for ActionScript.
*   [AIRdb](https://github.com/dkeskar/airdb) - AIR ORM for using client-side SQLite within AIR and Flex apps. Supports ActiveRecord style models, migrations and associations.
*   [Flexine](https://github.com/riadvice/Flexine) - SQLite ORM for AIR.
*   [AIR-sqlite](https://github.com/probertson/air-sqlite) - Utilities for working with SQLite databases in AIR.

#### MongoDB

*   [MongoAS3](https://github.com/s9tpepper/MongoAS3) - MongoDB driver.
*   [ActionMongo](https://github.com/RIAlizer/ActionMongo) - MongoDB driver.

#### CouchDB

*   [AS3couchdb](https://github.com/bustardcelly/as3couchdb) - Client-side API for interacting with a CouchDB instance.
*   [Soup](https://github.com/dima/soup) - Mixing CouchDB, Sinatra, AIR and RestfulX to create an offline/online ready app with undo/redo capabilities.

#### MySQL

*   [AS3mysql](https://github.com/hgupta9/as3mysql) - Driver for the MySQL open source database.

#### PostgreSQL

*   [Pegasus](https://github.com/uhoh-itsmaciek/pegasus) - Driver for the PostgreSQL open source database.

#### DynamoDB

*   [AWS-dynamodb](https://github.com/ferf/aws-dynamodb-actionscript) - Driver for accessing Amazon's AWS DynamoDB.

#### Redis

*   [AS3redis](https://github.com/zhangq0355/as3redis) - Driver for Redis.

## File Formats

#### Archives

*   [FZip](https://github.com/claus/fzip) - Mature library to load, modify and create standard ZIP archives.
*   [ASZip](https://code.google.com/archive/p/aszip/) - Generate ZIP archives from AS3.
*   [Untar-Worker](https://github.com/mesmotronic/as3-worker-untar) - TAR extraction using AS3 Workers (background threads).

#### 3D Formats

*   [AsCollada](https://github.com/timknip/ascollada) - Parse COLLADA 3D model files ([fork](https://github.com/david-gregory/ascollada)).
*   [AsBlender](https://github.com/timknip/asblender) - Parse Blender .BLEND files.
*   [AS3-bvh-parser](https://github.com/rkn14/as3-bvh-parser) - Parse BVH files.
*   [EasyAGAL](https://github.com/Barliesque/EasyAGAL) - Simplifies development of AGAL shaders with code completion, code hinting,  macros, etc.

#### CSV

*   [CSV4AS3](https://github.com/lizardon/CSV4AS3) - CSV library ported from Apache Commons CSV.
*   [Csvlib](https://github.com/51systems/csvlib) - CSV parser.

#### CSS

*   [AS3csslib](https://github.com/heyfrench/as3csslib) - CSS3 parser, selector and style engine for ActionScript 3.0.
*   [Fcss](https://github.com/theflashbum/fcss) - Flash Cascading StyleSheet Library.
*   [Stylekit-as3](https://github.com/videojuicer/stylekit-as3) -  Skinnable user interfaces using CSS3.
*   [Sass4as](https://github.com/jeremyruppel/sass4as) - Syntactically Awesome Stylesheets for ActionScript 3.
*   [Jakute-CSS](https://github.com/kakenbok/Jakute-Styling-Engine) - Jakute is a CSS framework for ActionScript/Flash.
*   [CSS.as](https://gist.github.com/trxcllnt/1161266) - Single-file CSS parser, part of TinyTLF project.

#### BSON

*   [ActionBSON](https://github.com/fminzoni/ActionBSON) - BSON data encoder/decoder.
*   [MongoAS3](https://github.com/s9tpepper/MongoAS3) - MongoDB Driver which includes BSON I/O.

#### EXIF

*   [AS3-exif-lib](https://github.com/unstoppable/actionscript-exif-reading-lib) - Parse JPEG EXIF data.
*   [Exif-as3](https://github.com/bashi/exif-as3) - Parse JPEG EXIF data.

#### FXG

*   [Fxg-as3-lib](https://github.com/pixelami/fxg-as3-lib) - Pure AS3 FXG rendering library (both runtime rendering and mxml supported).
*   [Fxg2as3](https://github.com/ZackPierce/fxg2as3) - Converting FXG markup into executable Actionscript 3 code.

#### GIF

*   [AS3gif](https://github.com/audreyt/as3gif) - Play and encode Animated GIFs.
*   [GIF Player](https://github.com/theturtle32/Flash-Animated-GIF-Library) - Play Animated GIFs in Flash.
*   [Async-gif-decoder](https://github.com/honzabrecka/async-gif-decoder) - Asynchronous GIF decoder & player.

#### ICAL

*   [AS3iCAL](https://github.com/nicolai86/as3.iCal) - iCal parser based on the RFC2445 specification.

#### JSON

*   [Actionjson](https://github.com/mherkender/actionjson) - Faster, more advanced ActionScript 3 JSON library.
*   [Jameson](https://github.com/mattupstate/jameson) - JSON Document Object Mapper.
*   [Serialkiller](https://github.com/benbjohnson/serialkiller) - JSON & XML serialization library.
*   [JsonMapper](https://github.com/kemsky/JsonMapper) - Typed JSON parser.
*   [JSONTools](https://github.com/s9tpepper/JSONTools) - JSON errors, the speed of the JSWoof JSON library, and E4X style queries dubbed E4J.

#### Markdown

*   [Showdown.as](https://gist.github.com/cstrahan/648771) - Port of showdown.js.
*   [Actiondown](https://github.com/bbeaumont/Actiondown) - Port of Javascript Showdown.
*   [Markdownlib](https://github.com/Corsaair/markdownlib) - Implementation of Markdown.

#### MP3

*   [AS3id3lib](https://github.com/devxoul/as3id3lib) - Parse MP3 ID3 data.
*   [AS3Icy](https://github.com/claus/as3icy) - Decode and play live MP3 streams from Shoutcast, Icecast and Limewire.

#### PDF

*   [AlivePDF](https://code.google.com/archive/p/alivepdf/) - Client side PDF generation ([github](https://github.com/riadvice/alivepdf)).
*   [PurePDF](https://github.com/sephiroth74/purePDF) - Complete PDF library, port of Java iText.
*   [HalcyonPDF](https://github.com/systemed/halcyon_pdf) - OpenStreetMap PDF renderer.
*   [PDFCase](https://github.com/dickclaus/pdfcase) - PDF Library.
*   [PDFView](https://github.com/jankapunkt/PDFView) - PDF viewer built from scratch.

#### PSD

*   [AS3-psd-parser](https://github.com/warrenseine/as3-psd-parser) - Parse Photoshop PSD files and render as BitmapData objects.

#### SWF

*   [AS3swf](https://github.com/claus/as3swf) - Low level library to parse, create, modify and publish SWF files.
*   [AS3abc](https://github.com/imcj/as3abc) - Low level library to parse, create, modify and publish ABC (Actionscript Block Code) files.
*   [SWFWire](https://github.com/magicalhobo/SWFWire) - SWF Decompiler and Inspector Tools.
*   [Abc-abstraction](https://github.com/krilnon/abc-abstraction) - Allows ABC to be analyzed, manipulated, packaged back into an SWF, and run.

#### SVG

*   [AS3SVGRenderer](https://github.com/LucasLorentz/AS3SVGRenderer) - SVG Renderer for Flash Player.
*   [SVGParser](https://github.com/millermedeiros/SVGParser) - SVG parser and renderer to FIVe3D and HTML5 canvas.

#### XML

*   [XMLSerializer](https://github.com/vapesolius/XMLSerializer) - Library which allows data serialisation from ActionScript to XML and from XML to ActionScript.
*   [DynamicXMLParser](https://github.com/lmgerhard/DynamicXMLParser) - Dynamic parse xml content into predefined data classes (actionscript 3).
*   [Nudge](https://github.com/pluglimited/Nudge) - Framework to serialize/deserialize objects as XML.
*   [AStream](https://github.com/kokorin/AStream) - XML to Object (and vice versa) mapping library written in AS3. Compatible with XStream.

#### XLSX

*   [AS3-xlsx-reader](https://github.com/childoftv/as3-xlsx-reader) - Parse Open XML Excel (.XLSX) or Open Office spreadsheets.

## Networking

#### Data Loader

*   [GreenSock LoaderMax](https://github.com/greensock/GreenSock-AS3) - Provides an easy and powerful way to load assets at runtime.
*   [BulkLoader](https://github.com/arthur-debert/BulkLoader) - Bulk asset loading library for Actionscript.
*   [AssetLoader](https://github.com/Matan/AssetLoader) - Multi-file/asset loader for AS3 built on AS3Signals.

#### Hardware

*   [AS3midilib](https://github.com/heyfrench/as3midilib) - Work with MIDI files and MIDI input/output devices.
*   [AS3glue](https://code.google.com/archive/p/as3glue/) - Communication for Arduino boards.
*   [AS3-arduino](https://github.com/quetwo/as3-arduino-connector) - Connecting Arduino Prototyping board to Adobe AIR.
*   [AIRkinect](https://github.com/AS3NUI/airkinect-2-core) - ANE for integrating with Microsoft Kinect. ([examples](https://github.com/AS3NUI/airkinect-2-examples)).
*   [KinectGate](https://github.com/cleoag/KinectGate) - KinectSDK to AS3 socket gate.
*   [Kinect-Gestures](https://github.com/tonybeltramelli/Air-Kinect-Gesture-Lib) - AIR Kinect Gesture Library.
*   [OpenTSPS](https://github.com/labatrockwell/openTSPS) - TSPS is a cross platform Toolkit for Sensing People in Spaces. It performs openCV operations on live video (Kinect, web camera, etc) and sends it to clients as JSON (via WebSockets), OSC, TUIO, or TCP.
*   [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - Integrate with the LeapMotion sensor (provides Gestures, Image, Skeleton/Bone @ 210 FPS).

#### Servers

*   [AIRhttp](https://github.com/leopoldodonnell/airhttp) - HTTP Server for Adobe AIR.
*   [AIR-Server](https://github.com/wouterverweirder/AIR-Server) - Socket Server library for Adobe AIR.

#### OAuth

*   [Actionscript-oauth2](https://github.com/charlesbihis/actionscript-oauth2) - Interfacing with OAuth 2.0 services.
*   [oauth-flex](https://github.com/oauth-io/oauth-flex) - OAuth.io plugin for Apache Flex/ActionScript.
*   [oauth-as3](https://github.com/mlepicki/oauth-as3) - Mavenized, RSL version of oauth-as3 library - OAuth for ActionScript 3.

#### HTTP

*   [Hendrix-HTTP](https://github.com/HendrixString/Hendrix-HttP-AiR) - Lightweight HTTP library for ActionScript 3 (as3) inspired by Square's OkHttp.
*   [HTTPForm](https://github.com/dv/HTTPForm) - Emulate a multipart/form-data HTML form submission request, including file upload.
*   [AS3httpclient](https://github.com/abdul/as3httpclient) - HTTP client implementation.
*   [AS3httpclient](https://github.com/gabriel/as3httpclient) - HTTP client implementation.
*   [Amazon Web Services](https://github.com/satoshi7/ActionScript-API-for-AWS-Amazon-Web-Services-) - AS3 API for AWS.

#### P2P

*   [P2Plocal](https://github.com/palkan/as3_p2plocal) - Local RTMFP connections.
*   [Android-Flash-P2P](https://github.com/beautifycode/Android-Flash-P2P) - P2P Communication between a Client.swf and an Android Device with AIR.
*   [NetGrouper](https://github.com/walpolea/NetGrouper) - Wrapper for NetGroup and RTMFP Multicasting abilities to create quick P2P multiplayer games over local networks or Adobe Cirrus.
*   [HydraP2P](https://github.com/devboy/HydraP2P) - Simplifies the peer-to-peer API introduced in Flash Player 10.1.
*   [GroupP2P](https://github.com/oohazard/GroupP2P) - P2P-based netgroup.
*   [HLS-P2P](https://github.com/lava-tech/hls-p2p) - Flash OSMF based hybrid cdn\&p2p hls solution.
*   [P2Pmessaging](https://github.com/dreamsocket/actionscript-p2p_messaging) - Simple messaging framework for doing P2P in Flash.
*   [ArcusNode](https://github.com/OpenRTMFP/ArcusNode) - RTMFP Rendevouz Service For Peer Assisted Networking With Adobe Flash on Node JS.

#### Sockets

*   [AS3WebSocket](https://github.com/theturtle32/AS3WebSocket) - WebSocket client implementation for the final WebSocket Draft RFC6455.
*   [SmartSocket](https://github.com/XaeroDegreaz/SmartSocket) - SmartSocket is a Java and PHP socket server engine, to make creating multi-user applications quick and painless.
*   [FlashSocket.IO](https://github.com/simb/FlashSocket.IO) - Clients connect to Socket.IO servers from AS3/AIR clients.
*   [Socket.io](https://github.com/ascorbic/socket-io-actionscript) - Socket.IO Actionscript 3 client.
*   [AMFsocket](https://github.com/chadrem/amf_socket) - Bi-directional RPC library for high performance network communication.
*   [Sockpuppet](https://github.com/rjungemann/sockpuppet) - Complete Ruby/ActionScript socket client/server with AMF.
*   [Socket.io-flash](https://github.com/sinnus/socket.io-flash) - Communication to Socket.IO v.0.8+ servers.
*   [ws-flash-client](https://github.com/youurayy/ws-flash-client) - Reliable minimalistic WebSocket client (uses Adobe Flash where native WebSocket is not available).

#### Protocols

*   [GIT](https://github.com/nexussays/git-as3) - Client-side implementation of Git.
*   [AIRplay](https://github.com/mikkoh/AS3-Airplay) - Client-side implementation of Apple's Airplay.
*   [TeaTime](https://github.com/aemoncannon/croqodile) - AS3/Erlang implementation of the Croquet project's TeaTime protocol.
*   [XMPP](https://github.com/lyokato/as3xmppclient) - Client-side implementation of XMPP library.
*   [XMPP](https://github.com/bluef/kuching) - Lightweight implementation of XMPP library.
*   [AMQP](https://github.com/0x6e6562/as3-amqp) - Client-side implementation of the 0-8 version of AMQP.
*   [NTP](https://github.com/charlespalen/AS3-NTP-Implementation) - Client-side implementation of NTP Client (Network Time Protocol).
*   [FUDI](https://github.com/matthiasbreuer/FUDI-as3) - Client-side implementation of the Puredata FUDI protocol.
*   [BDD Cucumber](https://github.com/flashquartermaster/Cuke4AS3) - A BDD Cucumber wire protocol implementation for Flash ActionScript.

#### Email

*   [AIRXMail](https://github.com/hgupta9/AirXMail) - Complete client-side email library supporting SMTP, POP3 and IMAP4.
*   [AS3Mailer](https://github.com/Matan/AS3Mailer) - Sends email using server script or invokes a mailto.

## Utilities

#### Artificial Intelligence

*   [FiniteStateMachine](https://github.com/pzUH/FiniteStateMachine) - Finite State Machine for AI bot/agent.
*   [N-GramPredictor](https://github.com/pzUH/N-GramPredictor) - n-Gram predictor for AI bot/agent.
*   [Naive-BayesPredictor](https://github.com/pzUH/Naive-BayesPredictor) - Naive-Bayes predictor for AI bot/agent.
*   [HierarchicalStateMachine](https://github.com/pzUH/HierarchicalStateMachine) - Hierarchical State Machine for AI bot/agent.
*   [Godmode-as3](https://github.com/tconkling/godmode-as3) - Behavior tree implementation (artificial intelligence).
*   [DecisionTree](https://github.com/pzUH/DecisionTree) - Binary decision tree for AI bot/agent.
*   [FuzzyStateMachine](https://github.com/pzUH/FuzzyStateMachine) - Fuzzy State Machine (FuSM) for AI bot/agent.
*   [SmartKid](https://github.com/skyfeiyun/SmartKid) - Powerful AI engine for 2D & 3D games.

#### Async

*   [EasyAS-Worker](https://github.com/myflashlab/easyAS-Worker) - Simplified wrapper for AIR Workers.
*   [Worker-from-class](https://github.com/bortsen/worker-from-class) - Create Workers from Class definitions.

#### Crypto

*   [BlooddyCrypto](https://github.com/blooddy/blooddy_crypto) - High-performance library for processing binary data. This library contains MD5, SHA-1, SHA-2, Base64, CRC32, JSON, PNG/JPEG encoders.
*   [AS3Crypto](https://github.com/timkurvers/as3-crypto) - Fork of Henri Torgemane's excellent cryptography library ([patched](https://github.com/lyokato/as3crypto_patched)).
*   [AS3corelib](https://github.com/mikechambers/as3corelib) -  MD5 and SHA1 hashing, Image encoders, and JSON serialization.
*   [ASCrypt](https://github.com/Meychi/ASCrypt) - Crypto library with a similar API for multiple languages.
*   [Nexuslib](https://github.com/nexussays/nexuslib-as3) - Reflection, serialization, seeded random number generation, cryptography, networking, and more.
*   [Hashlib](https://github.com/Corsaair/hashlib) - Over 30 different hashing functions.
*   [XXTEA-AS3](https://github.com/xxtea/xxtea-as3) - XXTEA encryption algorithm library for ActionScript 3.
*   [Gibberish-AES](https://github.com/NordMike/gibberish-aes-as3) - A fully OpenSSL compliant ActionScript 3 library for AES encryption.

#### Data

*   [AS3Commons Collections](https://github.com/AS3Commons/as3commons-collections) - Sophisticated and high-performance collections & iterators for AS3.

#### Geometry

*   [AS3geometry](https://github.com/alecmce/as3geometry) - Primitives, Polygons, Intersections, etc.
*   [AS3GeomAlgo](https://github.com/azrafe7/as3GeomAlgo) - Collection of geometry algorithms. Port of hxGeomAlgo.
*   [Coral](https://github.com/richardlord/Coral) - High-performance classes for 3D mathematics (Point, Vector, Matrix, Quaternion).
*   [Csg.as](https://github.com/timknip/csg.as) - Constructive Solid Geometry on 3D meshes.
*   [PathUtils](https://github.com/alinakipoglu/Actionscript-PathUtils) - Working with quadratic, bezier and line sequences.
*   [Hilbert](https://github.com/nodename/Hilbert) - Port of Hilbert curve from cortesi/scurve.
*   [AS3AStar](https://github.com/tomnewton/AS3AStar) - Fast A-Star pathfinding algorithm.
*   [A-star\_pathfinder](https://github.com/kevhiggins/a-star_pathfinder) - A-Star pathfinding interface for tile based maps.
*   [As3Pathfinder](https://github.com/azakhary/As3Pathfinder) - Grid Path finding Library written using Dijkstra's algorithm.

#### Math

*   [AS3Units](https://github.com/erussell/AS3Units) - Port of NGUnits. Parsing, formatting, and converting between units of measure.
*   [AS3LinAlg](https://github.com/inspirit/AS3LinAlg) - Linear Algebra library (Jacobi SVD, Eigen Vectors/Values, Cholesky LU, etc).
*   [Performance Primitives](https://github.com/martinkallman/performance-as3) - High-performance math modeled on the Intel Performance Primitives.
*   [Zexpression](https://github.com/Xorcerer/zexpression) - Parse and evalate math expressions with functions and variables.
*   [FlexibleMatrix](https://github.com/Lukx/FlexibleMatrix) - A multi purpose Matrix class.
*   [AS3eval](http://eval.hurlant.com/) - Packages the Tamarin ESC compiler to work within Flash Player. ([alternate](https://github.com/SimonRichardson/as3-eval)).
*   [FlashFormulaEditor](https://github.com/zasdfgbnm/FlashFormulaEditor) - Formula editor made in Adobe Flex.

#### Text

*   [Linkify-as3](https://github.com/CodeCatalyst/linkify-as3) - Convert URLs, e-mail addresses, phone numbers, into clickable links.
*   [AS3hyphenation](https://github.com/gka/as3hyphenation) - Port of the Javascript text hyphenation library Hyphenator.js.

## Runtimes

#### Emulators

*   [NES Emulator](https://github.com/nesbox/emulator) - Emulator of NES, Super Nintendo, Sega Mega Drive, GameBoy video consoles.
*   [Commodore 64 Emulator](https://github.com/claus/fc64) - A low level Commodore 64 emulator written in Actionscript 3.
*   [8080 Emulator](https://github.com/ozipi/As3_SpaceInvaders_Emulator) - An actionscript 3 space invaders emulator based on the intel 8080 processor.
*   [8-bit VM](https://github.com/OutOfTheVoid/AS3-8-bit-VM) - An eight bit virtual machine written in actionscript.

#### Interpreters

*   [JS](https://github.com/theturtle32/RhinoAS3) - RhinoJS, Port of Mozilla's Rhino JavaScript interpreter.
*   [Simple JS](https://github.com/sixsided/Simplified-JavaScript-Interpreter) - AS3-based Javascript interpreter.
*   [MIL](https://github.com/ser1zw/MIL) - A MIL language VM and interpreter written in ActionScript.
*   [TALES](https://github.com/oaubert/tales4as) - TALES interpreter for ActionScript.
*   [Scheme](https://github.com/hrundik/fScheme) - Scheme interpreter in ActionScript.
*   [Lisp](https://github.com/rzubek/as_lisp) - Lisp dialect written in Actionscript, with compiler and bytecode interpreter.
*   [Lisp Compiler](https://github.com/aemoncannon/las3r) - A lisp compiler for the AVM2.
*   [CannonML](https://github.com/abiyasa/cannonml_as3) - keim's CannonML (shmup scripting language) interpreter.

## AIR Native Extensions

#### Audio ANE

*   [SongPicker](https://github.com/richpixel/SongPickerANE) - A song picker/player ANE for iOS and Android.
*   [SilentSwitch](https://github.com/StickSports/ANE-Silent-Switch) - ANE for iOS to mute sounds if the hardware silent switch is on.
*   [VolumePro](https://github.com/myflashlab/VolumePro-ANE) - Control native music stream volume and you can listen to the volume changes.
*   [SystemVolume](https://github.com/nweber/SystemVolumeNativeExtension) - Interact with the system volume for iOS and Android devices.

#### Multimedia ANE

*   [WebView (Tuarua)](https://github.com/tuarua/WebViewANE) - Modern WebView for OSX 10.10+, Windows Desktop, iOS 9.0+ and Android 21+. Uses CEF (Chromium Embedded Framework) on Windows, WKWebView on iOS/OSX, and WebView on Android.
*   [WebView (FlashLab)](https://github.com/myflashlab/webView-ANE) - Replacement for StageWebView, allows calling Javascript functions from AIR.
*   [AVANE](https://github.com/tuarua/AVANE) - For building video encoding applications using FFmpeg.
*   [PDF](https://github.com/myflashlab/PDF-ANE) - Lets you open PDF files from your AIR mobile apps. Supported on Android and iOS.
*   [VideoPlayer](https://github.com/myflashlab/videoPlayer-ANE) - Play video files in Android or iOS native video player.
*   [SurfaceVideoPlayer](https://github.com/myflashlab/surfaceVideoPlayer-ANE) - SurfacePlayer ANE helps you play video files inside your air mobile projects.
*   [Speech](https://github.com/myflashlab/speech-ANE) - Convert strings to voice files and vice versa fully in the background.
*   [MyAR](https://github.com/myflashlab/AR-ANE-Samples) - AR ANE supporting Android and iOS 64-bit based on Metaio's SDK.
*   [QR-zbar](https://github.com/saumitrabhave/qr-zbar-ane) - ANE for QR Code Reader.
*   [Barcode](https://github.com/myflashlab/barcode-ANE) - Scan almost any barcode type with this super fast barcode scanner ANE.
*   [Bullet](https://github.com/mziwisky/bullet-ane) - Bullet physics simulation library.

#### File System ANE

*   [FileChooser](https://github.com/myflashlab/fileChooser-ANE) - Enable users to select a file from the device filesystem.
*   [ZipManager](https://github.com/myflashlab/zipManager-ANE) - Zip or unzip large zip archives super fast using native process on Android and iOS.
*   [Spotlight](https://github.com/myflashlab/Spotlight-ANE) - Integrate with iOS 9 Spotlight Search, to index search items and user generated content.

#### Networking ANE

*   [Firebase](https://github.com/myflashlab/Firebase-ANE) - API for Google Firebase on Android and iOS with 100% identical ActionScript API.
*   [DownloadManager](https://github.com/myflashlab/downloadManager-ANE) - Download large data files with pause/resume support.
*   [BitTorrent](https://github.com/tuarua/BitTorrentANE) - For building BitTorrent enabled applications.

#### Hardware ANE

*   [Bluetooth](https://github.com/myflashlab/bluetooth-ANE) - Scan for other devices, connect to and pair with them and transfer data between them.
*   [GPS](https://github.com/myflashlab/GPS-ANE) - Get current device GPS location as fast as possible by automatically checking the best available provider.
*   [GoogleVR](https://github.com/myflashlab/GoogleVR-ANE) - Google Virtual Reality SDK available to AIR developers.
*   [Joystick-ANE](https://github.com/StackAndHeap/joystick-ane) - ANE Joystick Library.
*   [AIRControl](https://github.com/AlexanderOMara/AIRControl) - Adobe AIR Game Controller ANE.
*   [AIROUYAController](https://github.com/gaslightgames/AIROUYAController) - ANE for the OUYA Controller.
*   [AIRKinectv2](https://github.com/Tastenkunst/AIRKinectv2) - ANE for Microsoft Kinect v2 for Windows SDK.
*   [Serial/MIDI/DMX](https://github.com/benkuper/AIR-NativeExtensions) - AIRBonjour, NativeSerial, NativeDMXController, NativeMIDI, VirtualMIDI, ExtendedMouse.
*   [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - ANE for LeapMotion sensor (provides Gestures, Image, Skeleton/Bone @ 210 FPS).

#### System ANE

*   [TaskbarProgress](https://github.com/tuarua/TaskbarProgressANE) - Display taskbar progress on OSX & Windows 7/8/10 .
*   [DesktopToast](https://github.com/tuarua/DesktopToastANE) - Display interactive toast notifications in Windows 8/10 and OSX.
*   [AlarmManager](https://github.com/myflashlab/alarmManager-ANE) - Run a scheduled task even if your AIR app is closed.
*   [InAppPayments](https://github.com/myflashlab/inAppPayments-ANE) - Identical in-app-billing and in-app-purchase ANE for Android and iOS.
*   [PermissionCheck](https://github.com/myflashlab/PermissionCheck-ANE) - Check and request for permissions in your Adobe Air app.
*   [RateMe](https://github.com/myflashlab/RateMe-ANE) - Ask your users to rate your app in the most efficient way.
*   [Statusbar](https://github.com/myflashlab/Statusbar-ANE) - Control the Statusbar in your AIR apps in runtime.
*   [Badge](https://github.com/myflashlab/Badge-ANE) - Control the iOS badge value.
*   [WinDebug](http://www.henke37.cjb.net/windebug/) - Windows ANE to control applications, windows, memory, breakpoints, metadata, registry, etc.
*   [Can-Open-URL](https://github.com/StickSports/ANE-Can-Open-URL) - ANE for iOS to detect whether an app is installed to handle a specific URL scheme.

#### Social ANE

*   [Facebook](https://github.com/myflashlab/facebook-ANE) - Integrate Facebook SDK into your AIR apps.
*   [GCM](https://github.com/myflashlab/GCM-ANE) - Use Google Cloud messaging on Android and iOS. .
*   [Baidu](https://github.com/lilili87222/baidu-ane-for-ios-and-android) - Baidu ANE for for iOS and Android.

#### Analytics ANE

*   [Admob](https://github.com/myflashlab/Admob-ANE) - Admob ANE.
*   [GameServices](https://github.com/myflashlab/GameServices-ANE) - Google Game Services for Android+iOS.
*   [MoPub](https://github.com/StickSports/MoPub-ANE) - ANE for MoPub advertising.
*   [UMAnalytics](https://github.com/ColerYu/ANE-UMAnalytics) - ANE for UMAnalytics SDK (iOS and Android).
*   [Localytics](https://github.com/randori/ANE-Localytics) - Localytics analytics for mobile Adobe AIR applications (iOS & Android).
*   [Testflight](https://github.com/jlopez/ane-testflight) - Apple TestFlight ANE.
*   [HockeyApp](https://github.com/airext/hockeyapp) - ANE for the Hockeyapp testing & distribute platform.
*   [Chartboost](https://github.com/ChartBoost/air) - ANE for the Chartboost SDK with compile scripts.

