# Awesome Gideros Overview

A curated list of awesome Gideros resources, classes and tips.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/stetso/awesome-gideros/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 stetso/awesome-gideros](https://github.com/stetso/awesome-gideros) · ⭐ 23 · 🏷️ Gaming

[ [Daily](/content/stetso/awesome-gideros/README.md) / [Weekly](/content/stetso/awesome-gideros/week/README.md) / Overview ]

---

# Awesome Gideros [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<h1 align="center">
	<a href="http://giderosmobile.com"><img width="200" src="https://github.com/stetso/awesome-gideros/raw/master/gideros_logo.png" alt="Awesome Gideros"></a>
	<br>
	<br>
</h1>

A curated list of awesome resources for the [Gideros Game Development Framework](http://giderosmobile.com/) that allows you to easily create games and apps for Android, iOS, HTML5, WinRT and Desktop (Windows, OSX). Please feel free to contribute to the list by making a pull request.

## Contents

*   [Getting Started](#getting-started)
*   [Resources](#resources)
    *   [Tutorials and Tips](#tutorials-and-tips)
    *   [Full game examples](#full-game-examples)
    *   [Publications](#publications)
    *   [IDEs and Editors](#ides-and-editors)
    *   [Graphics and Shaders](#graphics-and-shaders)
    *   [Scene Managment](#scene-management)
    *   [Input](#input)
    *   [Animation and Tweens](#animation-and-tweens)
    *   [Tilemaps](#tilemaps)
    *   [Camera](#camera)
    *   [Audio](#audio)
    *   [Saving and Loading](#saving-and-loading)
    *   [Monetization](#monetization)
    *   [GUI](#gui)
    *   [3D](#3d)
    *   [Plugins](#plugins)
*   [Useful Lua-Libraries](#useful-lua-libraries)
*   [License and Contriuting](#license-and-contributing)

## Getting Started

*   [Download Gideros](http://giderosmobile.com/download) - Get Gideros here (it is free but donations are welcome!).
*   [Getting Started Manual](http://docs.giderosmobile.com) - Check here first to get an overview of the framework.
*   [API Reference](http://docs.giderosmobile.com/reference/) - Whenever you need to figure something out- this is the first place to go.
*   [Forum](http://giderosmobile.com/forum/) - Join the very helpful community.
*   [Online Editor](http://giderosmobile.com/code/) - Try Gideros in your browser without installing anything.
*   [Online Examples](http://giderosmobile.com/examples) - See some of the capabilites of Gideros in your browser.
*   [Developer Guide](http://giderosmobile.com/guide) - Official list of guides and tutorials.

## Resources

*A collection of resources (blog and forum entries, websites, packages etc) for Gideros*

### Tutorials and Tips

*   [Introductory Video Tutorial](https://www.youtube.com/watch?v=IRLxBijIX50) - By one of the maintainers of Gideros.
*   [Publishing to Android](http://giderosmobile.com/forum/discussion/6894/publishing-tutorial#Item_7) - Getting started with publishing to Android.
*   [Improving performance](http://giderosmobile.com/forum/discussion/4892/software-improve-what-kind-of-skills-do-you-need) - Forum thread with hints about improving the performance of Gideros apps.
*   [Desktop API](http://giderosmobile.com/forum/discussion/5870/new-desktop-api-test/p1) - Overview of the Desktop API to manipulate mouse cursor and window decorations.

### Full game examples

*   [Simple square-dodge game](http://bluebilby.com/2013/05/08/gideros-mobile-tutorial-creating-your-first-game/) - Introductory tutorial about creating a simple square-dodge game.
*   [Top-down roguelike Tutorial](https://programmingbymoonlight.com/roguelike-intro/) - Extensive tutorial series about making a turn-based roguelike in Gideros.
*   [Breakout Clone](http://blog.hotbutteredgames.com/post/143878823915/gideros-tutorial-a-simple-box2d-game-gideros-is-a) - Tutorial about creating a Breakout-like game using Gideros and Box2D.
*   ["Grab the treasure" course](http://www.moosader.com/learn/introduction-to-mobile-game-development/) - Comprehensive getting-started guide to Gideros by developing a small game.

### Publications

*Books about Gideros*

*   [Gideros Mobile Game Development](https://www.packtpub.com/game-development/gideros-mobile-game-development) - Comprehensive book about developing a game for mobile with Gideros.
*   [Learn Lua for iOS Game Development](http://www.apress.com/us/book/9781430246626) - Introducing a variety of Lua-based game development frameworks including Gideros.

### IDEs and Editors

*Code editors and plugins that work with Gideros*

*   [Using ZeroBrane Studio with Gideros](http://www.indiedb.com/tutorials/gideros-with-zerobrane) - Introductory tutorial for using ZBS with Gideros Remote Preview.
*   [Live Coding with Gideros and ZeroBrane Studio](https://www.youtube.com/watch?v=wPYvJxFxMkM) - Video showing the live coding capabilities of ZBS and Gideros.
*   [ZeroBrane Studio integration and debugging](https://www.youtube.com/watch?v=GIipyzSpSr0) - Video tutorial by the creator of ZBS.
*   [Visual Studio Code plugin](https://marketplace.visualstudio.com/items?itemName=devCAT.lua-debug) - With Gideros support (Windows only).
*   [Sublime Text 3 plugin](http://giderosmobile.com/forum/discussion/5218/gideros-sublime-text-3-package-for-osx-windows-version-0-10/p1) - Adding Gideros support to ST3.

### Graphics and Shaders

*   [Shaders in Gideros](http://bit.ly/2pkF09m) - Introductory text about shaders in Gideros.
*   [Shadertoy viewer](http://giderosmobile.com/forum/discussion/6667/shadertoy-viewer-beta-shaders-from-www-shadertoy-com-in-gideros/p1) - Check out shaders from Shadertoy using Gideros.
*   [Intro to clipping and the RenderTarget](http://www.indiedb.com/engines/gideros/tutorials/clipping-in-gideros-with-rendertarget) - Text-based tutorial on how to use the RenderTarget class to create a clipping effect.

### Scene Management

*   [SceneManager](http://appcodingeasy.com/Gideros-Mobile/Manage-Scenes-in-Gideros-Mobile) - Easily switch between scenes with or without transitions.
*   [Passing variables using the SceneManager](http://giderosmobile.com/forum/discussion/1474/passing-variables-with-scene-manager/p1) - Passing variables to the next scene when using the scene manager.

### Input

*   [GidSwipe (⭐0)](https://github.com/stetso/GidSwipe) - Easy to use tap and swipe manager for mobile.
*   [Gestures](http://appcodingeasy.com/Gideros-Mobile/Detecting-Gestures-in-Gideros) - Define and detect complex gestures from points a list of points.
*   [Accelerometer](http://appcodingeasy.com/Gideros-Mobile/Using-Accelerometer-with-Box2d-in-Gideros) - Quick example of how to use the device accelerometer as input.
*   [Shake detection](http://appcodingeasy.com/Gideros-Mobile/Gideros-Shake-detection) - Small snippet to detect device shake.

### Animation and Tweens

*   [GTween](http://appcodingeasy.com/Gideros-Mobile/Gideros-GTween-with-easing) - Tween sprite variables with this library (comes with all the easing functions you need).
*   [Animation using MovieClip](http://bluebilby.com/2013/05/12/gideros-mobile-tutorial-animated-movieclips/) - Tutorial on how to animate sprites using the MovieClip class.
*   [Spriteheet animation class (⭐2)](https://github.com/nascode/gideros_animsheet) - Class that helps with creating and playing animations from spritesheets.

### Tilemaps

*   [Collision with Tilemaps](http://giderosmobile.com/forum/discussion/6353/collision-with-any-object/p1) - Examples and suggestions on how to make stuff collide with the tiles in your tilemap.

### Camera

*   [Smooth camera with Drag and Pinch-to-Zoom](http://giderosmobile.com/forum/discussion/2715/camera-class-with-kinetics-and-pinch-to-zoom/p1) - Useful class implementation for a camera in a mobile game.

### Audio

*   [Intro to using audio with Gideros](http://bluebilby.com/2013/04/18/gideros-mobile-tutorial-playing-music-and-sound-effects/) - Tutorial about generating and using sounds with Gideros.

### Saving and Loading

*   [Using JSON](http://giderosmobile.com/forum/discussion/6918/saving-and-loading-data-files#Item_1) - Loading and saving manually via JSON.
*   [DataSaver module](http://appcodingeasy.com/Gideros-Mobile/Save-and-load-data-module-for-Gideros-Mobile) - User-friendly wrapper to make saving and loading data as easy as possible.
*   [Encrypting save files](http://giderosmobile.com/forum/discussion/5625/simple-savegame-encryption/p1) - Some ideas (with code) about securing the save files from unwanted manipulation.

### Monetization

*   [Admob integration](http://giderosmobile.com/forum/discussion/5801/tuto-video-tutorial-how-to-add-admob-plugin-to-your-app) - Video tutorial about integrating Admob into your game.
*   [Google Service integration](http://giderosmobile.com/forum/discussion/5806/tuto-video-tutorial-how-to-add-google-services-to-your-app) - Second part of the Admob tutorial showing Google Play Service integration.

### GUI

*   [Layout (⭐8)](https://github.com/Nlcke/layout) - Comprehensive Gideors GUI framework ([forum entry](http://giderosmobile.com/forum/discussion/6651/layout-gideros-gui-framework#Item_23)).
*   [Button class](http://appcodingeasy.com/Gideros-Mobile/Gideros-mobile-button-class) - Simple class for creating clickable buttons.
*   [AceSlide class](http://appcodingeasy.com/Gideros-Mobile/Easy-input-for-choosing-packages-or-levels-in-Gideros-Mobile) - Sliding UI-Element that can be used for example for level selection.

### 3D

*Note: 3D support is still in development but if you like to play around with it already, here are some starting points*

*   [Tutorial using 3D in Gideros](https://www.youtube.com/watch?v=IfHwdJD6ad8) - Introduction by one of the maintainers of Gideros.

### Plugins

*   [SKStoreReview (⭐0)](https://github.com/mertkurum/GiderosStoreReview) - Gideros Plugin for SKStoreReviewController iOS 10.3+.
*   [C++ plugin development](http://giderosmobile.com/forum/discussion/1025/step-by-step-how-to-write-a-c-plugin-and-deploy-it-to-the-desktop-windows-player) - Getting started with Gideros plugin development in C++.

## Useful Lua-Libraries

*General Lua libraries that are useful in gamedev but are not Gideros specific*

*   [lume (⭐761)](https://github.com/rxi/lume) - Great collection of functions that are useful for game development.
*   [inspect (⭐1.1k)](https://github.com/kikito/inspect.lua) - Easily pretty-print your tables to the console in a readable way.
*   [jumper](http://yonaba.github.io/Jumper/) - Super-fast grid-based pathfinding for Lua.
*   [bump (⭐769)](https://github.com/kikito/bump.lua) - Simple, flexible and fast library for collision detection using axis-aligned bounding boxes (from version 2017.8 onwards Gideros contains a C-port of the library with the same API that should be used instead [cbump](https://wiki.giderosmobile.com/index.php/Bump).
*   [Bresenham (⭐13)](https://github.com/rm-code/Bresenham) - Bresenham's line algorithm, implemented in Lua.

## Related Awesome Lists

*   [awesome-lua (⭐3.2k)](https://github.com/LewisJEllis/awesome-lua)
*   [awesome-love2d (⭐2.5k)](https://github.com/love2d-community/awesome-love2d)
*   [awesome-gamedev (⭐13)](https://github.com/mbrukman/awesome-gamedev)

## License and Contributing

Please contribute to the list. Simply read the [contribution guidelines](https://github.com/stetso/awesome-gideros/blob/master/readme.md/contributing.md) to get started.

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

