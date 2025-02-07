# Awesome Libgdx Overview

🎮 📝 A curated list of libGDX resources to help developers make awesome games.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rafaskb/awesome-libgdx/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 rafaskb/awesome-libgdx](https://github.com/rafaskb/awesome-libgdx) · ⭐ 1K · 🏷️ Gaming

[ [Daily](/content/rafaskb/awesome-libgdx/README.md) / [Weekly](/content/rafaskb/awesome-libgdx/week/README.md) / Overview ]

---

[![Awesome libGDX Logo](https://github.com/rafaskb/awesome-libgdx/raw/master/logo.png "Awesome libGDX Logo")](https://libgdx.com/)

# Awesome libGDX [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Latest libGDX Version](https://img.shields.io/maven-central/v/com.badlogicgames.gdx/gdx?color=e74a45\&label=Latest%20libGDX%20Version\&style=flat-square)](https://search.maven.org/artifact/com.badlogicgames.gdx/gdx)

> <a href="https://libgdx.com/"><img src="https://libgdx.com/assets/images/logo.png" alt="libGDX Logo" align="right" style="margin-right: 25px" height=40></a>
>
> [libGDX](https://libgdx.com/) is a relatively low level, free, open source cross platform game development framework written in Java.
>
> This list is a curated collection of awesome resources, tools, tutorials, and projects using the [libGDX](https://libgdx.com/) game framework to help developers make *awesome* games, conforming to the [Awesome Manifesto (⭐335k)](https://github.com/sindresorhus/awesome/blob/master/awesome.md).
>
> Contributions *very welcome* but first see [Contributing](#contributing).

***

## Contents

*   [Resources](#resources)
    *   [Artificial Intelligence](#algorithms-and-ai)
    *   [Controllers](#controllers)
    *   [Editors](#editors)
    *   [Entity Component System (ECS)](#entity-component-system-ecs)
    *   [Physics](#physics)
    *   [Services](#services)
    *   [Setup and Deployment](#setup-and-deployment)
    *   [User Interface](#user-interface)
    *   [Visual Effects](#visual-effects)
    *   [Audio](#audio)
    *   [Others](#others)
*   [Tutorials](#tutorials)
    *   [Getting Started](#getting-started)
    *   [Advanced](#advanced)
*   [Assets](#assets)
*   [Community](#community)
*   [Other Lists](#other-lists)

***

## Resources

*Resources that can be used in libGDX code to boost the framework's capabilities.*

### Algorithms and AI

*   [gdx-ai (⭐1.2k)](https://github.com/libgdx/gdx-ai) - Artificial Intelligence framework featuring Steering Behaviors, Formation Motion, Pathfinding, Behavior Trees and Finite State Machines.
*   [Simple Graphs (⭐44)](https://github.com/earlygrey/simple-graphs) - A java library for graph data structures and algorithms (including fast pathfinding).

### Controllers

*   [gdx-controllers (⭐72)](https://github.com/libgdx/gdx-controllers) - Adds support to gamepads and joysticks.
*   [gdx-controllerutils (⭐60)](https://github.com/MrStahlfelge/gdx-controllerutils) - Adds Scene2D button input support, user configurable button mappings and hotplugging for LWJGL2.
*   [sdl2gdx (⭐76)](https://github.com/electronstudio/sdl2gdx) - Powerful gamepad implementation using SDL. Supports hundreds of controllers under the same mapping, rumble, and hotplugging.

### Editors

*   [HyperLap2D (⭐379)](https://github.com/rednblackgames/HyperLap2D) - Visual editor for complex 2D worlds and scenes with a runtime for libGDX.
*   [Mundus (⭐162)](https://github.com/JamesTKhan/Mundus) - World/level editor for 3D worlds with a runtime for libGDX.
*   [Spine](http://esotericsoftware.com/) - Skeleton-based animation tool that focuses specifically on 2D animation for games.

### Entity Component System (ECS)

*   [Artemis-odb (⭐783)](https://github.com/junkdog/artemis-odb) - High performance java based Entity-Component-System framework.
*   [Ashley (⭐875)](https://github.com/libgdx/ashley) - A Java entity system inspired by Ash & Artemis.

### Physics

*   [Box2D](https://libgdx.com/wiki/extensions/physics/box2d) - One of the most popular physics libraries for 2D games.
*   [Bullet](https://libgdx.com/wiki/extensions/physics/bullet/bullet-physics) - 3D Collision Detection and Rigid Body Dynamics Library.
*   [jbump (⭐31)](https://github.com/tommyettinger/jbump) - Easy to implement AABB collision detection useful for platformers and other simple 2D games.

### Services

*   [gdx-facebook (⭐59)](https://github.com/TomGrill/gdx-facebook) - Provides cross-platform support for Facebook Graph API.
*   [gdx-fireapp (⭐63)](https://github.com/mk-5/gdx-fireapp) - Cross-platform API for Firebase.
*   [gdx-firebase (⭐35)](https://github.com/TomGrill/gdx-firebase) - Cross-platform (only Desktop/Android) API for Firebase.
*   [gdx-gameanalytics (⭐32)](https://github.com/MrStahlfelge/gdx-gameanalytics) - Game Analytics REST API client implementation for libGDX. Works on all backends.
*   [gdx-gamesvcs (⭐113)](https://github.com/MrStahlfelge/gdx-gamesvcs) - Easy integration of gameservices, such as Google Play Games, Apple Game Center, and more.
*   [gdx-pay (⭐224)](https://github.com/libgdx/gdx-pay) - Provides a cross-platform API for InApp purchasing.
*   [steamworks4j (⭐483)](https://github.com/code-disaster/steamworks4j) - A thin wrapper which allows Java applications to access the Steamworks C++ API.

### Setup and Deployment

*   [gdx-liftoff (⭐543)](https://github.com/tommyettinger/gdx-liftoff) - A modern setup tool for libGDX that supports more backends and allows adding libraries with one click.
*   [libgdx-library-template (⭐14)](https://github.com/tommyettinger/libgdx-library-template) - A skeleton project for making new libraries, since they need different config.
*   [Packr (⭐2.6k)](https://github.com/libGDX/packr) - Packages your JAR, assets and a JVM for distribution on Windows, Linux and macOS.

### User Interface

*   [Freetype](https://libgdx.com/wiki/extensions/gdx-freetype) - Generate BitmapFonts of your desired size on the fly from lightweight .ttf font files.
*   [gdx-dialogs (⭐78)](https://github.com/TomGrill/gdx-dialogs) - Provides cross-platform support for native dialogs.
*   [gdx-skins (⭐505)](https://github.com/czyzby/gdx-skins) - Free Scene2D GUI skins.
*   [InGameConsole (⭐132)](https://github.com/StrongJoshua/libGDX-inGameConsole) - Allows a developer to add a console (similar to how it is featured in Source games) to their game.
*   [msdf-gdx (⭐34)](https://github.com/maltaisn/msdf-gdx) - Provides lightweight utilities to draw high-quality MSDF (multi-channel signed distance field) text on libGDX.
*   [PieMenu (⭐80)](https://github.com/payne911/PieMenu) - Radial menus for Scene2D that are highly flexible and easy to customize.
*   [Ray3K Skins](https://ray3k.wordpress.com/artwork/) - Free Scene2D.UI skins with example code, custom drawables, and experimental features.
*   [Skin Composer (⭐435)](https://github.com/raeleus/skin-composer) - Create skins for libGDX scene2d.ui with a graphical interface.
*   [TenPatch (⭐48)](https://github.com/raeleus/TenPatch) - An alternative to libGDX's 9patch implementation that implements multiple stretch regions.
*   [TextraTypist (⭐96)](https://github.com/tommyettinger/textratypist) - Like TypingLabel (below), but also supports styles, emoji, multiple fonts, clickable links, etc.
*   [TypingLabel (⭐152)](https://github.com/rafaskb/typing-label) - A libGDX Label that appears as if it was being typed in real time.
*   [VisUI (⭐733)](https://github.com/kotcrab/vis-ui) - Allows to create nice looking UI in libGDX using scene2d.ui. Note this is not a UI editor.

### Visual Effects

*   [Box2DLights (⭐256)](https://github.com/libgdx/box2dlights) - 2D lighting framework that uses Box2D for raycasting and OpenGL ES 2.0 for rendering.
*   [colorful-gdx (⭐76)](https://github.com/tommyettinger/colorful-gdx) - Expands how tinting can affect colors; also has many pre-written shaders.
*   [HackLights (⭐24)](https://github.com/aliasifk/HackLights) - Lightweight framebuffer based lighting engine for libGDX.
*   [gdx-vfx (⭐191)](https://github.com/crashinvaders/gdx-vfx) - Flexible post-processing shader visual effects based on libgdx-contribs-postprocessing.
*   [libgdx-screenmanager (⭐102)](https://github.com/crykn/libgdx-screenmanager) - A screen manager for libGDX supporting various transition effects
*   [Particle Park (⭐69)](https://github.com/raeleus/Particle-Park) - A showcase of downloadable particle effects with live previews.
*   [Shape Drawer (⭐187)](https://github.com/earlygrey/shapedrawer) - A performant alternative to ShapeRenderer that avoids Batch flushing.
*   [gdx-gltf (⭐214)](https://github.com/mgsx-dev/gdx-gltf) - GLTF 3D file format support (import/export), PBR shaders, and others advanced rendering.
*   [gdx-graph (⭐46)](https://github.com/MarcinSc/gdx-graph) - Provides a GUI to design your rendering pipeline and shaders, and a library to easily incorporate them into your games.

### Audio

*   [TuningFork (⭐31)](https://github.com/Hangman/TuningFork) - Advanced 3D audio features for libGDX desktop users.
*   [gdx-miniaudio (⭐50)](https://github.com/rednblackgames/gdx-miniaudio) - Advanced Cross Platform Audio Engine for libGDX based on MiniAudio.
*   [gdx-sfx (⭐20)](https://github.com/spookygames/gdx-sfx) - Some goodies for better sound effects in libGDX.
*   [gdx-pd (⭐27)](https://github.com/mgsx-dev/gdx-pd) - Pure Data extension for libGDX.

### Others

*   [anim8-gdx (⭐41)](https://github.com/tommyettinger/anim8-gdx) - Allows saving (animated) GIFs and PNGs from sequences of Pixmaps, with configurable dithering if needed.
*   [gdx-dbgagent (⭐30)](https://github.com/PokeMMO/gdx-dbgagent) - Java Agent for debugging common issues, like objects not being disposed and constants such as Color.WHITE being modified.
*   [gdx-jnigen (⭐65)](https://github.com/libgdx/gdx-jnigen) - Small library that allows C/C++ code to be written inline with Java source code.
*   [gdxGifRecorder (⭐37)](https://github.com/Anuken/GDXGifRecorder) - A utility class that records a GIF and saves it automatically.
*   [KTX (⭐1.4k)](https://github.com/libktx/ktx) - Kotlin extensions and utilities for libGDX.
*   [noise4j (⭐102)](https://github.com/czyzby/noise4j) - Simple map generators based on various procedural content generation tutorials.
*   [Texture Packer GUI (⭐618)](https://github.com/crashinvaders/gdx-texture-packer-gui) - A simple way to pack and manage texture atlases for libGDX game framework.
*   [libGDX Plugin (⭐147)](https://github.com/BlueBoxWare/LibGDXPlugin) - A plugin for IntelliJ IDEA and Android Studio that adds a number of libGDX features and tools, such as color previews and additional inspections for common mistakes.

## Tutorials

*Tutorials for newbies and seasoned developers alike.*

### Getting Started

*   [Official libGDX Wiki](https://libgdx.com/wiki/) - Official libGDX wiki that contains a huge amount of information.
*   [Tann's Hello libGDX](https://colourtann.github.io/HelloLibgdx/) - An excellent guide for beginners on how to create a game from scratch.
*   [Development Tutorial Playlist by Phillip Mod Dev](https://www.youtube.com/playlist?list=PLLwCf-qdpyEnB_FO_1HkUFh7smwGNjAaC) - A series of videos going over the basics of libGDX.
*   [Brandon Grasley's Space Shooter Game](https://www.youtube.com/playlist?list=PLfd-5Q3Fwq0WKrkEKw12nqpfER3MG5_Wi) - Video tutorial series on making a complete Android game from scratch.
*   [Creating a Launcher](https://youtu.be/3l5F7f7vfTU) - Video tutorial on using libGDX to make a game launcher.
*   [Deploying with JPackage (⭐435)](https://github.com/raeleus/skin-composer/wiki/libGDX-and-JPackage) - A tutorial on deploying libGDX games with JPackage via Gradle commands.
*   [JSON in Game Dev](http://mana-break.blogspot.com/2014/06/power-of-json-in-game-development-items.html) - General tutorial on using JSON for storing data.
*   [Progress Bar Design (⭐435)](https://github.com/raeleus/skin-composer/wiki/The-Man-Who-Killed-Hitler-and-then-The-Progress-Bar) - Discusses the pros and cons of different progress bar design techniques with examples.
*   [libGDX External Tutorials](https://libgdx.com/wiki/articles/external-tutorials) - Big list of official unofficial tutorials.
*   [Scene2D.UI From the Ground Up (⭐435)](https://github.com/raeleus/skin-composer/wiki/From-the-Ground-Up:-Scene2D.UI-Tutorials) - Covers the basics of UI design in Scene2D, libGDX's premiere scene graph and layout toolkit.

### Advanced

*   [Code Hotswapping](https://youtu.be/zKfh6WuaikQ) - Video tutorial on enabling code hotswapping for libGDX projects to increase productivity.
*   [Dynamic Textures with Pixmap](https://javadocmd.com/blog/libgdx-dynamic-textures-with-pixmap/) - Details how to create a mask using Pixmaps.
*   [iOS Deployment Tutorial](https://link.medium.com/vgYo0mSi3W) - Deploying to iOS in 2019 using RoboVM.
*   [Sub-pixel Perfect Smooth Scrolling](http://code-disaster.com/2016/02/subpixel-perfect-smooth-scrolling.html) - Pixel-perfect smooth scrolling.
*   [Introduction to 3D Series](https://www.youtube.com/playlist?list=PLjUR2MkQ0cuHZ70Ps8F9WMyoyKHKAbYvQ) - A tutorial series on libGDX 3D using gdx-gltf.

### General Learning Material

*   [Book of Shaders (⭐6.1k)](https://github.com/patriciogonzalezvivo/thebookofshaders) - Step-by-step guide through the abstract and complex universe of Fragment Shaders. GLSL.
*   [Game Programming Patterns](https://gameprogrammingpatterns.com/) - Architecture and design patterns for games.

## Assets

*Collection of free and high quality assets to get your game to the next level.*

*   [Kenney Assets](https://kenney.nl/) - High quality assets for your game, from 2D and 3D art to sound effects.
*   [OpenGameArt.org](https://opengameart.org/) - Repository offering a variety of open content assets.
*   [Game-Icons.net](http://game-icons.net/) - Repository containing heaps of cool game related graphics.
*   [Jsfxr](https://chr15m.itch.io/jsfxr) - Quickly create unique sound effects by pressing a few buttons, excellent for prototyping.
*   [freesound.org](https://freesound.org/) - Huge collaborative database of audio snippets, samples, recordings, bleeps.

## Community

*Get in touch with other libGDX developers to collaborate and get help.*

*   [Discord](https://discord.gg/4S8pQqc) - An active chat with various leaders from the community available every day. **Recommended**
*   [Reddit](https://www.reddit.com/r/libgdx/) - Unofficial subreddit for libGDX. Not a lot of activity.

## Other Lists

*Other awesome lists that might be useful to libGDX developers.*

*   [Game Networking (⭐7.5k)](https://github.com/MFatihMAR/Awesome-Game-Networking) - A Curated List of Game Network Programming Resources.
*   [Game Talks (⭐1.1k)](https://github.com/hzoo/awesome-gametalks) - A curated list of gaming talks (development, design, etc).
*   [Java (⭐42k)](https://github.com/akullpp/awesome-java) - A curated list of awesome Java frameworks, libraries and software.
*   [Kotlin (⭐11k)](https://github.com/KotlinBy/awesome-kotlin) - A curated list of awesome Kotlin related stuff.
*   [Magic Tools (⭐14k)](https://github.com/ellisonleao/magictools) - A list of Game Development resources to make magic happen.
*   [Game Accessibility Guidelines](http://gameaccessibilityguidelines.com/) - A straightforward reference for inclusive game design, to ensure that games are just as fun for as wide a range of people as possible. **Recommended**
*   [Awesome Gamedev (⭐2.4k)](https://github.com/Calinou/awesome-gamedev) - A collection of free software and free culture resources for making amazing games.

***

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/rafaskb/awesome-libgdx/blob/master/readme.md/contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

