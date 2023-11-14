# Awesome Swift Overview

A collaborative list of awesome Swift libraries and resources. Feel free to contribute!

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/matteocrippa/awesome-swift/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 matteocrippa/awesome-swift](https://github.com/matteocrippa/awesome-swift) · ⭐ 24K · 🏷️ Programming Languages

[ [Daily](/content/matteocrippa/awesome-swift/README.md) / [Weekly](/content/matteocrippa/awesome-swift/week/README.md) / Overview ]

---

# Awesome Swift

<!-- 

PLEASE DO NOT UPDATE THIS FILE, UPDATE CONTENTS.JSON INSTEAD. THANK YOU :-)

 -->

|                                                                           Awesome                                                                           |   Linux   | Projects |      Updated      |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------: | :------: | :---------------: |
| [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) | :penguin: |   1050   | November 13, 2023 |

### Contents

*   [Guides](#guides)
    *   [Newsletter](#newsletter)
    *   [Official Guides](#official-guides)
    *   [Style Guides](#style-guides)
    *   [Third party Guides](#third-party-guides)
*   [Boilerplates](#boilerplates)
*   [REPL](#repl)
*   [Editor Support](#editor-support)
    *   [Emacs](#emacs)
    *   [Google Colaboratory](#google-colaboratory)
    *   [Vim](#vim)
*   [Benchmark](#benchmark)
*   [Converters](#converters)
*   [Other Awesome Lists](#other-awesome-lists)
*   [Dependency Managers](#dependency-managers)
*   [Patterns](#patterns)
*   [Misc](#misc)
*   [Libs](#libs)
    *   [Accessibility](#accessibility)
    *   [AI](#ai)
    *   [Algorithm](#algorithm)
    *   [Analytics](#analytics)
    *   [Animation](#animation)
    *   [API](#api)
    *   [App Routing](#app-routing)
    *   [App Store](#app-store)
    *   [Audio](#audio)
    *   [Augmented Reality](#augmented-reality)
    *   [Authentication](#authentication)
    *   [Bots](#bots)
    *   [Cache](#cache)
    *   [Chart](#chart)
    *   [Chat](#chat)
    *   [Colors](#colors)
    *   [Command Line](#command-line)
    *   [Concurrency](#concurrency)
    *   [Currency](#currency)
    *   [Data Management](#data-management)
        *   [CBOR](#cbor)
        *   [Core Data](#core-data)
        *   [CSV](#csv)
        *   [Firebase](#firebase)
        *   [GraphQL](#graphql)
        *   [JSON](#json)
        *   [Key Value Store](#key-value-store)
        *   [MongoDB](#mongodb)
        *   [Multi Database](#multi-database)
        *   [ORM](#orm)
        *   [Other Data](#other-data)
        *   [Realm](#realm)
        *   [SQL drivers](#sql-drivers)
        *   [SQLite](#sqlite)
        *   [TOML](#toml)
        *   [XML](#xml)
        *   [YAML](#yaml)
        *   [ZIP](#zip)
    *   [Date](#date)
    *   [Dependency Injection](#dependency-injection)
    *   [Device](#device)
    *   [Documentation](#documentation)
    *   [Email](#email)
    *   [Embedded Systems](#embedded-systems)
        *   [Peripherals](#peripherals)
    *   [Events](#events)
    *   [Files](#files)
    *   [Fonts](#fonts)
    *   [Game Engine](#game-engine)
        *   [2D](#game-engine-2d)
    *   [Games](#games)
    *   [Gesture](#gesture)
    *   [Hardware](#hardware)
        *   [3D Touch](#3d-touch)
        *   [Bluetooth](#bluetooth)
        *   [Camera](#camera)
            *   [Barcode](#barcode)
        *   [Haptic Feedback](#haptic-feedback)
        *   [iBeacon](#ibeacon)
        *   [Sensors](#sensors)
    *   [Images](#images)
    *   [Key Value Coding](#key-value-coding)
    *   [Keyboard](#keyboard)
    *   [Kit](#kit)
    *   [Layout](#layout)
        *   [Auto Layout](#auto-layout)
    *   [Localization](#localization)
    *   [Location](#location)
    *   [Logging](#logging)
    *   [Maps](#maps)
    *   [Math](#math)
    *   [Natural Language Processing](#natural-language-processing)
    *   [Network](#network)
        *   [HTML](#html)
        *   [Messaging Protocol](#messaging-protocol)
        *   [SOAP](#soap)
        *   [Socket](#socket)
        *   [Webserver](#webserver)
    *   [OCR](#ocr)
    *   [Optimization](#optimization)
    *   [PDF](#pdf)
    *   [Quality](#quality)
    *   [Scripting](#scripting)
    *   [SDK](#sdk)
    *   [Security](#security)
        *   [Cryptography](#cryptography)
        *   [Keychain](#keychain)
    *   [Streaming](#streaming)
    *   [Styling](#styling)
    *   [SVG](#svg)
    *   [System](#system)
    *   [Testing](#testing)
        *   [Mock](#mock)
    *   [Text](#text)
    *   [Thread](#thread)
    *   [UI](#ui)
        *   [Alert](#alert)
        *   [Blur](#blur)
        *   [Button](#button)
        *   [Calendar](#calendar)
        *   [Cards](#cards)
        *   [Form](#form)
        *   [HUD](#hud)
        *   [Label](#label)
        *   [Menu](#menu)
        *   [Pagination](#pagination)
        *   [Payment](#payment)
        *   [Permissions](#permissions)
        *   [Scroll Bars](#scroll-bars)
        *   [StackView](#stackview)
        *   [Switch](#switch)
        *   [Tab](#tab)
        *   [Template](#template)
        *   [TextField](#textfield)
        *   [Transition](#transition)
        *   [3D](#ui-3d)
        *   [UICollectionView](#uicollectionview)
        *   [UITableView](#uitableview)
        *   [Walkthrough](#walkthrough)
    *   [Utility](#utility)
    *   [Validation](#validation)
        *   [Phone Numbers](#phone-numbers)
    *   [Version Manager](#version-manager)
    *   [Video](#video)
*   [Serverless](#serverless)

## Guides

*An awesome list of Swift related guides.*

### Newsletter

[back to top](#readme)

*   [Open Source Updates for Swift Projects](https://ossp-updates.beehiiv.com/) - A bi-weekly newsletter to give you the latest updates on popular and unknown open source projects written or related to Swift.

### Official Guides

[back to top](#readme)

*   [API Design Guidelines](https://www.swift.org/documentation/api-design-guidelines/) - Official Swift API design guidelines.
*   [Apple eBook](https://books.apple.com/us/book/the-swift-programming-language-swift-5-7/id881256329) - Official Apple eBook for Swift beginners.
*   [Getting Started](https://www.swift.org/getting-started/) - Find information about the how to use the Swift programming language.
*   [Introducing SwiftUI](https://developer.apple.com/tutorials/swiftui) - Official SwiftUI tutorial with 4+ hours of content and interactive tutorials.

### Style Guides

[back to top](#readme)

*   [Airbnb (⭐2.1k)](https://github.com/airbnb/swift) - Airbnb's Official Style Guide.
*   [Google](https://google.github.io/swift/) - This style guide is based on Apple’s excellent Swift standard library style and also incorporates feedback from usage across multiple Swift projects within Google.
*   [LinkedIn (⭐1.4k)](https://github.com/linkedin/swift-style-guide) - LinkedIn's Official Style Guide.
*   [Raywenderlich (⭐13k)](https://github.com/kodecocodes/swift-style-guide) - Raywenderlich guide, a must read.

### Third party Guides

[back to top](#readme)

*   [30 Days of Swift (⭐11k)](https://github.com/allenwong/30DaysofSwift) - A cool 30 days tutorial.
*   [About Swift (⭐79)](https://github.com/NicolaLancellotti-About/About-Swift) - A playground about the Swift language.
*   [Awesome Swift Education (⭐5.6k)](https://github.com/hsavit1/Awesome-Swift-Education) - An organized list of essential Swift Language Topics.
*   [Conferences.digital (⭐766)](https://github.com/zagahr/Conferences.digital) - Watch conference videos in a native macOS app.
*   [Developing iOS Apps with Swift](https://podcasts.apple.com/us/podcast/developing-ios-11-apps-with-swift/id1315130780) - Stanford course by Paul Hegarty.
*   [Hacking With Swift](https://www.hackingwithswift.com) - Complete training course that teaches app development through 30 hands-on projects, for free.
*   [Ray Wenderlich Tutorials, Videos, Podcasts and books](https://www.kodeco.com) - High quality programming tutorials.
*   [Swift & SwiftUI Tutorials](https://janeshswift.com) - SwiftUI learning with Ease.
*   [Swift Education](https://github.com/swifteducation) - A community of educators sharing materials for teaching Swift and app development.
*   [swift-tips (⭐968)](https://github.com/vincent-pradeilles/swift-tips) - A series of useful tips by Vincent Pradeilles.
*   [SwiftDoc](https://swiftdoc.org/) - Auto-generated documentation.
*   [SwiftGuide CN (⭐16k)](https://github.com/ipader/SwiftGuide) - A Chinese written guide.
*   [SwiftTips (⭐4k)](https://github.com/JohnSundell/SwiftTips) - A collection of useful tips by John Sundell.

## Boilerplates

*   [iOS project template (⭐397)](https://github.com/messeb/ios-project-template) - iOS project template with fastlane lanes, Travis CI jobs and GitHub integrations of Codecov, HoundCI for SwiftLint and Danger.
*   [Model-View-Presenter template (⭐25)](https://github.com/onl1ner/ios-mvp-template) - A flexible and easy template created to speed up the development of your iOS application based on the MVP pattern.
*   [Swift Module Template (⭐434)](https://github.com/fulldecent/swift5-module-template) - An opinionated starting point for awesome, reusable modules.

## REPL

*   [Online Swift Playground](http://online.swiftplayground.run) - Online Swift Playground.

## Editor Support

*Support for your favorite editors.*

### Emacs

[back to top](#readme)

*   [swift-mode (⭐357)](https://github.com/swift-emacs/swift-mode) - Emacs support, including partial flycheck error support.

### Google Colaboratory

[back to top](#readme)

*   [swift-colab (⭐93)](https://github.com/philipturner/swift-colab) - Run Swift in a browser.

### Vim

[back to top](#readme)

*   [swift-vim (⭐806)](https://github.com/keith/swift.vim) - Vim runtime files.
*   [vim-polyglot (⭐5.4k)](https://github.com/sheerun/vim-polyglot) - Language pack for vim that includes vim-swift.

## Benchmark

*   [xcprofiler (⭐331)](https://github.com/giginet/xcprofiler) - Command line utility to profile compilation time.

## Converters

*   [Swiftify](https://swiftify.com/#/converter/code/) - Objective-C to Swift online code converter and Xcode extension.
*   [Zolang (⭐143)](https://github.com/Zolang/Zolang) :penguin: - A DSL for generating code in multiple programming languages.

## Other Awesome Lists

*Check out apps on these projects:*

*   [Awesome iOS Interview (⭐1.1k)](https://github.com/dashvlas/awesome-ios-interview) - List of the questions that helps you to prepare for the interview.
*   [awesome-macOS (⭐15k)](https://github.com/iCHAIT/awesome-macOS) - A curated list of awesome applications, softwares, tools and shiny things for macOS.
*   [example-ios-apps (⭐927)](https://github.com/jogendra/example-ios-apps) - An amazing list for people who are beginners and learning ios development and for ios developers who need any example app or feature.
*   [open-source-ios-apps (⭐37k)](https://github.com/dkhamsing/open-source-ios-apps) - A collaborative list of open-source iOS Apps.
*   [open-source-mac-os-apps (⭐37k)](https://github.com/serhii-londar/open-source-mac-os-apps) - Awesome list of open source applications for macOS.

## Dependency Managers

*Dependency manager software for Swift.*

*   [Accio (⭐651)](https://github.com/JamitLabs/Accio) - A SwiftPM based dependency manager for iOS & Co. with improvements over Carthage.
*   [Carthage (⭐15k)](https://github.com/Carthage/Carthage) - A new dependency manager.
*   [CocoaPods (⭐14k)](https://github.com/CocoaPods/CocoaPods) - The most used dependency manager.
*   [Mint (⭐2.2k)](https://github.com/yonaskolb/Mint) - A package manager that installs and runs Swift command line tools.
*   [swift-package-manager (⭐9.4k)](https://github.com/apple/swift-package-manager) - SPM is the Package Manager for the Swift Programming Language.

## Patterns

*   [App Architecture (⭐2k)](https://github.com/objcio/app-architecture) - A sample Code of the App Architecture Book.
*   [CleanArchitectureRxSwift (⭐3.8k)](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift.
*   [Design-Patterns-In-Swift (⭐15k)](https://github.com/ochococo/Design-Patterns-In-Swift) - Design Patterns.
*   [GoodReactor (⭐31)](https://github.com/GoodRequest/GoodReactor) - ⚛️ GoodReactor is a Redux-inspired Reactor framework for communication between the View Model, View Controller, and Coordinator.
*   [Reactant (⭐372)](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS.
*   [ReduxUI (⭐41)](https://github.com/gre4ixin/ReduxUI) - Redux framework for easy use with SwiftUI.
*   [Spin (⭐120)](https://github.com/Spinners/Spin.Swift) - Provides a versatile Feedback Loop implementation working with RxSwift, ReactiveSwift and Combine.
*   [StateViewController (⭐309)](https://github.com/davidask/StateViewController) - Stateful UIVIewController composition — the MVC cure for Massive View Controllers.
*   [SwiftUI Atom Properties (⭐230)](https://github.com/ra1028/swiftui-atom-properties) - A Reactive Data-Binding and Dependency Injection Library for SwiftUI x Concurrency.
*   [The Composable Architecture (⭐9.9k)](https://github.com/pointfreeco/swift-composable-architecture) - A library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind.
*   [Viperit (⭐507)](https://github.com/ferranabello/Viperit) - Viper Framework for iOS.

## Misc

*Miscellaneous Swift related projects*

*   [Beak (⭐578)](https://github.com/yonaskolb/Beak) - A command line interface for your Swift scripts.
*   [BetterCodable (⭐1.6k)](https://github.com/marksands/BetterCodable) - Level up your `Codable` structs through property wrappers. The goal of these property wrappers is to avoid implementing a custom `init(from decoder: Decoder)` throws and suffer through boilerplate.
*   [CodableWrappers (⭐482)](https://github.com/GottaGetSwifty/CodableWrappers) - A Collection of PropertyWrappers to make custom Serialization of Codable Types easy.
*   [Fugen (⭐78)](https://github.com/almazrafi/Fugen) - A command line tool for exporting resources and generating code from your Figma files.
*   [Model2App (⭐137)](https://github.com/Q-Mobile/Model2App) - Turn your data model into a working CRUD app.
*   [Surmagic (⭐297)](https://github.com/gurhub/surmagic) - Create XCFrameworks with ease! A Command Line Tool to create XCFramework for multiple platforms at one shot! iOS, Mac Catalyst, tvOS, macOS, and watchOS.
*   [SwagGen (⭐617)](https://github.com/yonaskolb/SwagGen) :penguin: - A command line tool for generating a REST API from a Swagger spec based off Stencil templates.
*   [Swiftbrew (⭐145)](https://github.com/swiftbrew/Swiftbrew) - Homebrew for Swift packages.
*   [SwiftGen (⭐8.9k)](https://github.com/SwiftGen/SwiftGen) - A suite of tools to auto-generate code for various assets of your project.
*   [SwiftKit (⭐824)](https://github.com/SvenTiigi/SwiftKit) - Start your next Open-Source Swift Framework 📦.
*   [SwiftPlate (⭐1.8k)](https://github.com/JohnSundell/SwiftPlate) - Easily generate cross platform framework projects from the command line.
*   [Toybox (⭐129)](https://github.com/giginet/Toybox) - Xcode Playground management made easy.
*   [Tuist (⭐3.8k)](https://github.com/tuist/tuist) - An open source command line tool to create, maintain and interact with your Xcode projects at scale.
*   [xc (⭐22)](https://github.com/s2mr/xc) - A tool to open the Xcode project file by the specified version.
*   [xcbeautify (⭐784)](https://github.com/tuist/xcbeautify) - Little beautifier tool for xcodebuild.
*   [XcodeGen (⭐6.5k)](https://github.com/yonaskolb/XcodeGen) - Tool for generating Xcode projects from a YAML file and your project directory.
*   [xcodeproj (⭐1.9k)](https://github.com/tuist/xcodeproj) - A library to read, update and write Xcode projects and workspaces.

## Libs

*Here you can find a list of snippets and libs for your Swift projects.*

### Accessibility

[back to top](#readme)

*   [Capable (⭐253)](https://github.com/chrs1885/Capable) - Keep track of accessibility settings, leverage high contrast colors, and use scalable fonts to enable users with disabilities to use your app.

### AI

*Libs for AI based projects (Machine Learning, Neural Networks etc).* [back to top](#readme)

*   [CoreML-Models (⭐6k)](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models.
*   [DL4S (⭐96)](https://github.com/palle-k/DL4S) - Automatic differentiation, fast tensor operations and dynamic neural networks from CNNs and RNNs to transformers.
*   [OpenAI (⭐1.1k)](https://github.com/MacPaw/OpenAI) - Swift package for OpenAI public API.

### Algorithm

[back to top](#readme)

*   [Algorithm (⭐828)](https://github.com/CosmicMind/Algorithm) - A toolset for writing algorithms and probability models.
*   [BTree (⭐1.3k)](https://github.com/attaswift/BTree) - Fast sorted collections for Swift using in-memory B-trees.
*   [swift-algorithm-club (⭐28k)](https://github.com/kodecocodes/swift-algorithm-club) - Algorithms and data structures, with explanations.
*   [SwiftLCS (⭐213)](https://github.com/Frugghi/SwiftLCS) :penguin: - implementation of the longest common subsequence (LCS) algorithm.

### Analytics

*Analytics related libraries to easily track your app usage* [back to top](#readme)

*   [Tracker Aggregator (⭐21)](https://github.com/kafejo/Tracker-Aggregator) - Versatile analytics abstraction layer.
*   [Umbrella (⭐611)](https://github.com/devxoul/Umbrella) - Analytics abstraction layer.

### Animation

*Libs to help with animation* [back to top](#readme)

*   [Advance (⭐4.5k)](https://github.com/timdonnelly/Advance) - A powerful animation framework for iOS, tvOS, and OS X.
*   [ChainPageCollectionView (⭐782)](https://github.com/jindulys/ChainPageCollectionView) - Fancy two-level collection view layout and animation.
*   [CocoaSprings (⭐63)](https://github.com/MacPaw/CocoaSprings) - Interactive spring animations for iOS/macOS.
*   [Comets (⭐607)](https://github.com/cruisediary/Comets) - Animating Particles.
*   [Ease (⭐1.3k)](https://github.com/roberthein/Ease) - Animate everything with Ease.
*   [EasyAnimation (⭐3k)](https://github.com/icanzilb/EasyAnimation) - A library to take the power of UIView\.animateWithDuration(\_:, animations:...) to a whole new level.
*   [Elephant (⭐131)](https://github.com/s2mr/Elephant) - Elegant SVG animation kit.
*   [FlightAnimator (⭐583)](https://github.com/AntonTheDev/FlightAnimator) - Natural Blocks Based Core Animation Framework.
*   [Gemini (⭐3.1k)](https://github.com/shoheiyokoyama/Gemini) - Gemini is rich scroll based animation framework.
*   [IBAnimatable (⭐8.7k)](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable.
*   [Interpolate (⭐1.8k)](https://github.com/marmelroy/Interpolate) - Interpolation framework for creating interactive gesture-driven animations.
*   [lottie-ios (⭐25k)](https://github.com/airbnb/lottie-ios) - An iOS library to natively render After Effects vector animations.
*   [Pastel (⭐3.5k)](https://github.com/cruisediary/Pastel) - Gradient animation effect like Instagram.
*   [Poi (⭐65)](https://github.com/HideakiTouhara/Poi) - Poi makes you use card UI like tinder UI .You can use it like tableview method.
*   [Presentation (⭐3k)](https://github.com/hyperoslo/Presentation) - A library to help you to make tutorials, release notes and animated pages.
*   [Pulsator (⭐1.4k)](https://github.com/shu223/pulsator) - Pulse animation for iOS.
*   [Sica (⭐1.1k)](https://github.com/cats-oss/Sica) - Simple Interface Core Animation. Run type-safe animation sequencially or parallelly.
*   [Spring (⭐14k)](https://github.com/MengTo/Spring) - A library to simplify iOS animations.
*   [SpriteKitEasingSwift (⭐113)](https://github.com/craiggrummitt/SpriteKitEasingSwift) - Better Easing for SpriteKit.
*   [spruce-ios (⭐3.4k)](https://github.com/willowtreeapps/spruce-ios) - Choreograph animations on the screen.
*   [Stellar (⭐2.9k)](https://github.com/AugustRush/Stellar) - A Physical animation library.
*   [TheAnimation (⭐221)](https://github.com/marty-suzuki/TheAnimation) - Type-safe CAAnimation wrapper. It makes preventing to set wrong type values.
*   [ViewAnimator (⭐7.1k)](https://github.com/marcosgriselli/ViewAnimator) - Brings your UI to life with just one line.
*   [YapAnimator (⭐1.9k)](https://github.com/yapstudios/YapAnimator) - Your fast and friendly physics-based animation system.

### API

*Quick libs to get access to third party API services* [back to top](#readme)

*   [GitHubAPI (⭐81)](https://github.com/serhii-londar/GithubAPI) - Implementation of GitHub REST API v3.
*   [PXGoogleDirections (⭐267)](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper.
*   [RandomUserSwift (⭐96)](https://github.com/dingwilson/RandomUserSwift) - Framework to Generate Random Users - An Unofficial SDK for randomuser.me.
*   [reddift (⭐241)](https://github.com/sonsongithub/reddift) - reddit API wrapper.
*   [Swifter Twitter (⭐2.4k)](https://github.com/mattdonnelly/Swifter) - Twitter framework.
*   [Swiftkube (⭐109)](https://github.com/swiftkube/client) :penguin: - Swift client for Kubernetes.
*   [SwiftlySalesforce (⭐133)](https://github.com/mike4aday/SwiftlySalesforce) - Framework for rapid development of native iOS apps that integrate with Salesforce.
*   [SwiftyInsta (⭐222)](https://github.com/TheM4hd1/SwiftyInsta) - Private and Tokenless Instagram RESTful API.

### App Routing

*Internal app routing systems.* [back to top](#readme)

*   [Appz (⭐1.2k)](https://github.com/SwiftKitz/Appz) - Launch external apps and deeplink with ease.
*   [Crossroad (⭐413)](https://github.com/giginet/Crossroad) - :oncoming\_bus: Crossroad is an URL router focused on handling Custom URL Schemes.
*   [LightRoute (⭐92)](https://github.com/SpectralDragon/LiteRoute) - Routing between VIPER modules.
*   [Linker (⭐137)](https://github.com/MaksimKurpa/Linker) - Lightweight way to handle internal and external deeplinks for iOS.
*   [MonarchRouter (⭐39)](https://github.com/nikans/MonarchRouter) - Declarative state- and URL-based router. Complex automatic View Controllers hierarchy transitions. Time-tested server-side conventions.
*   [RxFlow (⭐1.8k)](https://github.com/RxSwiftCommunity/RxFlow) - RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.
*   [SwiftCurrent (⭐305)](https://github.com/wwt/SwiftCurrent) - Manage complex workflows wherever Swift can be built. It comes with built-in support for UIKit, Storyboards, and SwiftUI.
*   [SwiftRouter (⭐275)](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS.
*   [URLNavigator (⭐3.1k)](https://github.com/devxoul/URLNavigator) - Elegant URL Routing.

### App Store

*Libs to help with apple app store, in app purchases and receipt validation.* [back to top](#readme)

*   [Apphud (⭐168)](https://github.com/apphud/ApphudSDK) - Lightweight library to easily handle auto-renewable subscriptions with no backend required.
*   [AppReview (⭐74)](https://github.com/mezhevikin/AppReview) - A tiny library to request review on the AppStore via SKStoreReviewController.
*   [InAppPurchase (⭐288)](https://github.com/jinSasaki/InAppPurchase) - A Simple, Lightweight and Safe framework for In App Purchase.
*   [merchantkit (⭐1.1k)](https://github.com/benjaminmayo/merchantkit) - A modern In-App Purchases management framework for iOS.
*   [SwiftyStoreKit (⭐6.4k)](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases framework.

### Audio

*Libs to work with audio* [back to top](#readme)

*   [AudioKit (⭐10k)](https://github.com/audiokit/AudioKit) - Powerful audio synthesis, processing and analysis, without the steep learning curve.
*   [AudioPlayer (⭐706)](https://github.com/delannoyk/AudioPlayer) - A wrapper around AVPlayer with some cool features.
*   [AudioPlayerSwift (⭐275)](https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio (basic and advanced usage) in iOS, OS X and tvOS apps.
*   [Beethoven (⭐779)](https://github.com/vadymmarkov/Beethoven) - An audio processing library for pitch detection of musical signals.
*   [FDSoundActivatedRecorder (⭐278)](https://github.com/fulldecent/FDSoundActivatedRecorder) - Start recording when the user speaks.
*   [FDWaveformView (⭐1.2k)](https://github.com/fulldecent/FDWaveformView) - An easy way to display an audio waveform in your app.
*   [ModernAVPlayer (⭐276)](https://github.com/noreasonprojects/ModernAVPlayer) - Persistence AVPlayer to resume playback after bad network connection even in background mode.
*   [MusicKit (⭐599)](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music.
*   [Soundable (⭐94)](https://github.com/ThXou/Soundable) - Soundable allows you to play sounds, single and in sequence, in a very easy way.
*   [SwiftAudioPlayer (⭐504)](https://github.com/tanhakabir/SwiftAudioPlayer) - Simple audio player for iOS that streams and performs realtime audio manipulations with AVAudioEngine.
*   [SwiftySound (⭐1.2k)](https://github.com/adamcichy/SwiftySound) - Simple library that lets you play sounds with a single line of code.
*   [voice-overlay-ios (⭐526)](https://github.com/algolia/voice-overlay-ios) - An overlay that gets your user’s voice permission and input as text in a customizable UI.

### Augmented Reality

[back to top](#readme)

*   [ARHeadsetKit (⭐114)](https://github.com/philipturner/ARHeadsetKit) - High-level framework for using $5 Google Cardboard to replicate Microsoft Hololens.
*   [ARKit-CoreLocation (⭐5.4k)](https://github.com/ProjectDent/ARKit-CoreLocation) - Combines the high accuracy of AR with the scale of GPS data.
*   [ARKit-Navigation (⭐302)](https://github.com/chriswebb09/ARKitNavigationDemo) - Navigation in augmented reality with MapKit.
*   [ARVideoKit (⭐1.6k)](https://github.com/AFathi/ARVideoKit) - Capture & record ARKit videos, photos, Live Photos, and GIFs.

### Authentication

*Easy way to manage auth in your apps.* [back to top](#readme)

*   [Cely (⭐167)](https://github.com/cely-tools/Cely) - A Plug-n-Play login framework.
*   [LinkedInSignIn (⭐35)](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to log in and retrieve an access token from LinkedIn.
*   [LoginKit (⭐660)](https://github.com/IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.
*   [ReCaptcha (⭐259)](https://github.com/fjcaetano/ReCaptcha) - \[In]visible ReCaptcha for iOS.
*   [SpotifyLogin (⭐344)](https://github.com/spotify/SpotifyLogin) - Authenticate with the Spotify API.

### Bots

*Libs to build bot* [back to top](#readme)

*   [Telegram Bot SDK (⭐369)](https://github.com/rapierorg/telegram-bot-swift) :penguin: - Unofficial SDK.
*   [Telegrammer (⭐286)](https://github.com/givip/Telegrammer) :penguin: - Open-source framework for Telegram Bots developers. It was built on top of Apple/SwiftNIO which help to demonstrate excellent performance.

### Cache

[back to top](#readme)

*   [AwesomeCache (⭐1.3k)](https://github.com/aschuch/AwesomeCache) - Manage cache easy.
*   [Cache (⭐2.8k)](https://github.com/hyperoslo/Cache) - Nothing but Cache.
*   [CachyKit (⭐125)](https://github.com/Sadmansamee/CachyKit) - A Caching Library that can cache JSON, Image, Zip or AnyObject with expiry date/TTYL and force refresh.
*   [Cachyr (⭐125)](https://github.com/nrkno/yr-cachyr) - A small key-value data cache for iOS, macOS and tvOS.
*   [Carlos (⭐641)](https://github.com/spring-media/Carlos) - A simple but flexible cache.
*   [EVURLCache (⭐296)](https://github.com/evermeer/EVURLCache) - If you want to make your app still works when it's offline.
*   [MemoryCache (⭐78)](https://github.com/yysskk/MemoryCache) - Type-safe memory cache.

### Chart

[back to top](#readme)

*   [Charts (⭐27k)](https://github.com/danielgindi/Charts) - Beautiful charts for iOS/tvOS/OSX (port of MPAndroidChart).
*   [ChartView (⭐5k)](https://github.com/AppPear/ChartView) - Swift package for displaying beautiful charts effortlessly
*   [FLCharts (⭐259)](https://github.com/francescoleoni98/FLCharts) - Easy to use and highly customizable charts library for iOS.
*   [ScrollableGraphView (⭐5.3k)](https://github.com/philackm/ScrollableGraphView) - Adaptive scrollable graph view for iOS to visualise simple discrete datasets.
*   [SwiftChart (⭐1k)](https://github.com/gpbl/SwiftChart) - A simple line and area charting library for iOS. Supports multiple series, partially filled series and touch events.
*   [SwiftCharts (⭐2.5k)](https://github.com/ivanschuetz/SwiftCharts) - Highly customizable charts for iOS.
*   [SwiftUICharts (⭐746)](https://github.com/willdale/SwiftUICharts) - A charts / plotting library for SwiftUI. Works on macOS, iOS, watchOS, and tvOS and has accessibility and Localization features built in.
*   [TKRadarChart (⭐207)](https://github.com/TBXark/TKRadarChart) - A customizable radar chart.

### Chat

*Libs to get access to build chat app* [back to top](#readme)

*   [Chatto (⭐4.4k)](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications.
*   [ExyteChat (⭐316)](https://github.com/exyte/chat) - SwiftUI Chat UI framework with fully customizable message cells, input view, and a built-in media picker
*   [InputBarAccessoryView (⭐1.1k)](https://github.com/nathantannar4/InputBarAccessoryView) - A simple and easily customizable InputAccessoryView for making powerful input bars with autocomplete and attachments.
*   [MessageKit (⭐5.8k)](https://github.com/MessageKit/MessageKit) - A community-driven replacement for JSQMessagesViewController.
*   [MessengerKit (⭐1.5k)](https://github.com/steve228uk/MessengerKit) - A UI framework for building messenger interfaces.
*   [Real-time Chat with Firebase (⭐709)](https://github.com/instamobile/messenger-iOS-chat-swift-firestore) - Functional real-time chat app with Firebase Firestore using MessageKit.

### Colors

*Interesting snippets related to color management and utility.* [back to top](#readme)

*   [ChromaColorPicker (⭐559)](https://github.com/joncardasis/ChromaColorPicker) - An intuitive and fun iOS color picker.
*   [ColorKit (⭐677)](https://github.com/Boris-Em/ColorKit) - Advanced color manipulation for iOS.
*   [DynamicColor (⭐2.9k)](https://github.com/yannickl/DynamicColor) - An extension to manipulate colors easily.
*   [Gradients (⭐797)](https://github.com/Gradients/Gradients) - A curated collection of splendid 180+ gradients.
*   [Hue (⭐3.5k)](https://github.com/zenangst/Hue) - Hue is the all-in-one coloring utility that you'll ever need.
*   [PrettyColors (⭐172)](https://github.com/jdhealy/PrettyColors) - Styles and colors text in the Terminal with ANSI escape codes. Conforms to ECMA Standard 48.
*   [SheetyColors (⭐103)](https://github.com/chrs1885/SheetyColors) - An action sheet styled color picker for iOS.
*   [SwiftGen-Colors (⭐8.9k)](https://github.com/SwiftGen/SwiftGen#uicolor) - A tool to auto-generate `enums` for your `UIColor` constants.
*   [SwiftHEXColors (⭐689)](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor.
*   [UIColor-Hex-Swift (⭐1.2k)](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Hex to UIColor converter.
*   [UIGradient (⭐260)](https://github.com/dqhieu/UIGradient) - A simple and powerful library for using gradient layer, image, color.

### Command Line

*Create command line applications.* [back to top](#readme)

*   [Ashen (⭐93)](https://github.com/colinta/Ashen) - A framework for writing terminal applications in Swift. Based on The Elm Architecture.
*   [Commander (⭐1.5k)](https://github.com/kylef/Commander) :penguin: - Compose beautiful command line interfaces.
*   [Guaka (⭐1.1k)](https://github.com/nsomar/Guaka) :penguin: - The smart and beautiful (POSIX compliant) command line framework.
*   [LineNoise (⭐130)](https://github.com/andybest/linenoise-swift) :penguin: - A zero-dependency replacement for readline.
*   [nef (⭐265)](https://github.com/bow-swift/nef) - A set of command line tools that lets you have compile time verification of your documentation written as Xcode Playground.
*   [Progress.swift (⭐327)](https://github.com/jkandzi/Progress.swift) :penguin: - Add beautiful progress bars to your command line.
*   [Swift Argument Parser (⭐3.1k)](https://github.com/apple/swift-argument-parser) - Straightforward, type-safe argument parsing for Swift.
*   [SwiftCLI (⭐833)](https://github.com/jakeheis/SwiftCLI) :penguin: - A powerful framework that can be used to develop a CLI.
*   [Swiftline (⭐1.2k)](https://github.com/nsomar/Swiftline) - A set of tools to help you create command line applications.
*   [SwiftShell (⭐1k)](https://github.com/kareman/SwiftShell) - A library for creating command-line applications and running shell commands.
*   [SwiftyTextTable (⭐295)](https://github.com/scottrhoyt/SwiftyTextTable) :penguin: - A lightweight library to generate text tables.

### Concurrency

*Easier ways to work with concurrency.* [back to top](#readme)

*   [async+ (⭐170)](https://github.com/async-plus/async-plus) :penguin: - A chainable interface for Swift 5.5's async/await.
*   [AsyncNinja (⭐155)](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives.
*   [Futures (⭐58)](https://github.com/davidask/Futures) :penguin: - Lightweight promises for iOS, macOS, tvOS, watchOS, and server-side.
*   [GroupWork (⭐41)](https://github.com/quanvo87/GroupWork) :penguin: - Easy concurrent, asynchronous tasks.
*   [Hydra (⭐2k)](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code.
*   [Queuer (⭐1k)](https://github.com/FabrizioBrancati/Queuer) :penguin: - A queue manager, built on top of OperationQueue and Dispatch (aka GCD).
*   [SwiftCoroutine (⭐827)](https://github.com/belozierov/SwiftCoroutine) :penguin: - Coroutines for iOS, macOS and Linux.
*   [Throttler (⭐91)](https://github.com/boraseoksoon/Throttler) - Throttle massive number of asynchronous inputs in a single drop of one line API.
*   [Venice (⭐1.5k)](https://github.com/Zewo/Venice) :penguin: - Communicating sequential processes (CSP), Linux ready.

### Currency

[back to top](#readme)

### Data Management

[back to top](#readme)

#### CBOR

*Concise Binary Object Representation.* [back to top](#readme)

*   [CBORCoding (⭐29)](https://github.com/SomeRandomiOSDev/CBORCoding) :penguin: - Easy CBOR encoding and decoding for iOS, macOS, tvOS and watchOS.

#### Core Data

*No more pain with Core Data, here are some interesting libs to handle data management.* [back to top](#readme)

*   [AERecord (⭐303)](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper library for iOS.
*   [CloudCore (⭐142)](https://github.com/deeje/CloudCore/) - Robust CloudKit synchronization: offline editing, relationships, shared and public databases, and more.
*   [CoreStore (⭐3.9k)](https://github.com/JohnEstropia/CoreStore) - simple and elegant way to handle Core Data.
*   [DataKernel (⭐17)](https://github.com/mrdekk/DataKernel) - DataKernel is a minimalistic wrapper around Core Data stack to ease persistence operations. No external dependencies.
*   [Graph (⭐874)](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for Core Data.
*   [JSQCoreDataKit (⭐615)](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack.
*   [JustPersist (⭐165)](https://github.com/justeat/JustPersist) - Easiest and safest way to do persistence on iOS with Core Data support out of the box.
*   [QueryKit (⭐1.5k)](https://github.com/QueryKit/QueryKit) - An easy way to play with Core Data filtering.
*   [Skopelos (⭐235)](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data.
*   [SugarRecord (⭐2.1k)](https://github.com/modo-studio/SugarRecord) - Helps with Core Data and Realm.

#### CSV

*Helpful libraries to parse from and serialize to comma-separated value representations.* [back to top](#readme)

*   [CodableCSV (⭐413)](https://github.com/dehesa/CodableCSV) :penguin: - Read and write CSV files row-by-row or through Swift's Codable interface.
*   [CSVParser (⭐85)](https://github.com/Nero5023/CSVParser) :penguin: - Fast parser for CSV.

#### Firebase

[back to top](#readme)

*   [Ballcap (⭐228)](https://github.com/1amageek/Ballcap-iOS) - Ballcap is a database schema design framework for Cloud Firestore.

#### GraphQL

[back to top](#readme)

*   [SociableWeaver (⭐73)](https://github.com/NicholasBellucci/SociableWeaver) - Build declarative GraphQL queries and mutations.

#### JSON

*Struggling using json data? Here are some interesting ways to handle it.* [back to top](#readme)

*   [AlamofireObjectMapper (⭐2.7k)](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into objects using ObjectMapper.
*   [Alembic (⭐116)](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON.
*   [Argo (⭐3.5k)](https://github.com/thoughtbot/Argo) - JSON parsing library.
*   [Arrow (⭐381)](https://github.com/freshOS/Arrow) - Elegant JSON Parsing.
*   [Decodable (⭐1k)](https://github.com/Anviking/Decodable) :penguin: - JSON parsing.
*   [Elevate (⭐612)](https://github.com/Nike-Inc/Elevate) - JSON parsing framework that makes parsing simple, reliable and composable.
*   [EVReflection (⭐965)](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable.
*   [HandyJSON (⭐4.2k)](https://github.com/alibaba/handyjson) - A handy JSON-object serialization/deserialization library.
*   [Himotoki (⭐801)](https://github.com/ikesyo/Himotoki) - A type-safe JSON decoding library.
*   [JASON (⭐1k)](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators.
*   [JSONHelper (⭐785)](https://github.com/isair/JSONHelper) - Lightning fast JSON deserialization and value conversion library for iOS & OS X.
*   [JSONNeverDie (⭐453)](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die.
*   [ObjectMapper (⭐9.1k)](https://github.com/tristanhimmelman/ObjectMapper) - JSON object mapper.
*   [PMJSON (⭐361)](https://github.com/postmates/PMJSON) - JSON encoding/decoding library.
*   [Sextant (⭐42)](https://github.com/KittyMac/Sextant) :penguin: - High performance JSONPath queries
*   [SwiftyJSON (⭐22k)](https://github.com/SwiftyJSON/SwiftyJSON) - A lib for JSON with error handling.
*   [SwiftyJSONAccelerator (⭐943)](https://github.com/insanoid/SwiftyJSONAccelerator) - macOS app to generate Swift 5 models for JSON (with Codeable).

#### Key Value Store

[back to top](#readme)

*   [Default (⭐473)](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support.
*   [Defaults (⭐1.6k)](https://github.com/sindresorhus/Defaults) - Strongly-typed UserDefaults with support for Codable and key observation.
*   [DefaultsKit (⭐1.4k)](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS.
*   [Prephirences (⭐563)](https://github.com/phimage/Prephirences) - Manage application preferences, NSUserDefaults, iCloud, Keychain and more.
*   [SecureDefaults (⭐222)](https://github.com/vpeschenkov/SecureDefaults) - A lightweight wrapper over UserDefaults & NSUserDefaults with an extra AES-256 encryption layer.
*   [Storez (⭐67)](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage.
*   [SwiftStore (⭐119)](https://github.com/hemantasapkota/SwiftStore) - A Key-Value store backed by LevelDB.
*   [SwiftyUserDefaults (⭐4.8k)](https://github.com/sunshinejr/SwiftyUserDefaults) - Cleaner, nicer syntax for NSUserDefaults.
*   [Zephyr (⭐899)](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud.

#### MongoDB

[back to top](#readme)

*   [MongoKitten (⭐677)](https://github.com/orlandos-nl/MongoKitten) :penguin: - MongoDB Connector.
*   [Perfect-MongoDB (⭐54)](https://github.com/PerfectlySoft/Perfect-MongoDB) :penguin: - A stand-alone wrapper around the mongo-c client library, enabling access to MongoDB servers.

#### Multi Database

*Data management layers that involve multiple sources.* [back to top](#readme)

*   [ModelAssistant (⭐27)](https://github.com/ssamadgh/ModelAssistant) - Elegant library to manage the interactions between view and model.
*   [PersistenceKit (⭐155)](https://github.com/Teknasyon-Teknoloji/PersistenceKit) - Store and retrieve Codable objects to various persistence layers, in a couple lines of code!
*   [Shallows (⭐626)](https://github.com/dreymonde/Shallows) - Your lightweight persistence toolbox.

#### ORM

[back to top](#readme)

*   [fluent (⭐1.3k)](https://github.com/vapor/fluent) :penguin: - Simple ActiveRecord implementation.
*   [Perfect-CRUD (⭐63)](https://github.com/PerfectlySoft/Perfect-CRUD) :penguin: - CRUD is an object-relational mapping (ORM) system using Codable protocol.

#### Other Data

*Other ways to persist data* [back to top](#readme)

*   [CoreXLSX (⭐758)](https://github.com/CoreOffice/CoreXLSX) - Excel spreadsheet (XLSX) format support.
*   [Disk (⭐3k)](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data.
*   [EVCloudKitDao (⭐644)](https://github.com/evermeer/EVCloudKitDao) - Simplified access to CloudKit with support for subscriptions and local caching.
*   [KeyPathKit (⭐416)](https://github.com/vincent-pradeilles/KeyPathKit) - KeyPathKit provides a seamless syntax to manipulate data using typed keypaths.
*   [LeetCode-Swift (⭐4.7k)](https://github.com/soapyigu/LeetCode-Swift) - Solutions to LeetCode interview questions.
*   [Pencil (⭐89)](https://github.com/naru-jpn/pencil) - Write any value to file.
*   [StorageManager (⭐48)](https://github.com/iAmrSalman/StorageManager) - Safe and easy way to use FileManager as Database.

#### Realm

[back to top](#readme)

*   [Realm (⭐16k)](https://github.com/realm/realm-swift) - Realm is a mobile database: a replacement for Core Data & SQLite.
*   [RealmWrapper (⭐72)](https://github.com/k-lpmg/RealmWrapper) - Safe and easy wrappers for RealmSwift.
*   [Unrealm (⭐530)](https://github.com/arturdev/Unrealm) - Unrealm enables you to easily store Swift native Classes, Structs and Enums into Realm.

#### SQL drivers

[back to top](#readme)

*   [MySQL Swift (⭐159)](https://github.com/novi/mysql-swift) :penguin: - MySQL client library.
*   [Perfect-MySQL (⭐122)](https://github.com/PerfectlySoft/Perfect-MySQL) :penguin: - A stand-alone wrapper around the MySQL client library, enabling access to MySQL servers.
*   [Perfect-PostgreSQL (⭐51)](https://github.com/PerfectlySoft/Perfect-PostgreSQL) :penguin: - A stand-alone wrapper around the libpq client library, enabling access to PostgreSQL servers.

#### SQLite

*Are you interested in storing your app data using SQLite? Here are some interesting resources.* [back to top](#readme)

*   [GRDB.swift (⭐6.2k)](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit.
*   [SQLite.swift (⭐9.2k)](https://github.com/stephencelis/SQLite.swift) - Framework wrapping SQLite3. Small. Simple. Safe.
*   [SQLiteDB (⭐579)](https://github.com/FahimF/SQLiteDB) - SQLite wrapper.

#### TOML

*Tom's Obvious, Minimal Language.* [back to top](#readme)

*   [TOMLDecoder (⭐66)](https://github.com/dduan/TOMLDecoder) - Latest TOML standard, decoded.

#### XML

*If you prefer to manage XML data formatted entries, here are some helpful libs* [back to top](#readme)

*   [AEXML (⭐979)](https://github.com/tadija/AEXML) - xml wrapper.
*   [CheatyXML (⭐24)](https://github.com/lobodart/CheatyXML) - A powerful framework designed to manage XML easily.
*   [SwiftyXML (⭐100)](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML.
*   [SWXMLHash (⭐1.3k)](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing.
*   [XMLCoder (⭐746)](https://github.com/MaxDesiatov/XMLCoder) - XMLEncoder & XMLDecoder based on Codable protocols from the standard library.
*   [XMLMapper (⭐109)](https://github.com/gcharita/XMLMapper) - A simple way to map XML to Objects.

#### YAML

[back to top](#readme)

*   [YamlSwift (⭐396)](https://github.com/behrang/YamlSwift) - Load YAML and JSON documents.
*   [Yams (⭐1k)](https://github.com/jpsim/Yams) :penguin: - Sweet YAML parser.

#### ZIP

[back to top](#readme)

*   [Zip (⭐2.4k)](https://github.com/marmelroy/Zip) - Framework for zipping and unzipping files.
*   [Zip Foundation (⭐2.1k)](https://github.com/weichsel/ZIPFoundation) - A library to create, read and modify ZIP archive files.

### Date

*Handle date formatting easily.* [back to top](#readme)

*   [AnyDate (⭐188)](https://github.com/Kawoou/AnyDate) - Date & Time API inspired from Java 8 DateTime API.
*   [Chronology (⭐2.1k)](https://github.com/davedelong/time) - Building a better date/time library.
*   [DateHelper (⭐1.5k)](https://github.com/melvitax/DateHelper) - Simple date helper.
*   [Datez (⭐261)](https://github.com/SwiftKitz/Datez) - Library for dealing with `NSDate`, `NSCalendar`, `NSDateComponents`, and `NSTimeInterval`.
*   [Datify (⭐43)](https://github.com/hemangshah/Datify) - Easypeasy date functions.
*   [NVDate (⭐177)](https://github.com/novalagung/nvdate) - Date extension library.
*   [SwiftDate (⭐7.4k)](https://github.com/malcommac/SwiftDate) - Easy NSDate Management.
*   [Time (⭐1.1k)](https://github.com/dreymonde/Time) - Type-safe time calculations, powered by generics.
*   [Timepiece (⭐2.6k)](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions.
*   [TrueTime.swift (⭐557)](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes (NTP library).
*   [TypedDate (⭐18)](https://github.com/Ryu0118/swift-typed-date) - Enhancing Date handling by enabling type-level customization of date components

### Dependency Injection

*Dependency injection libs* [back to top](#readme)

*   [Cleanse (⭐1.7k)](https://github.com/square/Cleanse) - A Lightweight Dependency Injection Framework by Square.
*   [Corridor (⭐61)](https://github.com/symentis/Corridor) - A Coreader-like Dependency Injection μFramework.
*   [Deli (⭐135)](https://github.com/kawoou/Deli) - Deli is an easy-to-use Dependency Injection(DI).
*   [DIKit (⭐101)](https://github.com/Liftric/DIKit) - Dependency Injection Framework for Swift, inspired by KOIN.
*   [Dip (⭐962)](https://github.com/AliSoftware/Dip) - A simple Dependency Injection Container.
*   [DITranquillity (⭐403)](https://github.com/ivlevAstef/DITranquillity/) - Dependency injection framework with tranquility.
*   [Locatable (⭐116)](https://github.com/vincent-pradeilles/locatable) - A micro-framework that leverages Property Wrappers to implement the Service Locator pattern.
*   [Pure (⭐367)](https://github.com/devxoul/Pure) - A way to do a dependency injection without a DI container.
*   [Swinject (⭐6k)](https://github.com/Swinject/Swinject) - A dependency injection framework.
*   [Typhoon (⭐2.7k)](https://github.com/appsquickly/Typhoon) - Dependency injection toolkit.
*   [Weaver (⭐723)](https://github.com/scribd/Weaver) - A declarative, easy-to-use and safe Dependency Injection framework.

### Device

*A collection of libs to recognize your device.* [back to top](#readme)

*   [Device (⭐1.6k)](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size.
*   [Device.swift (⭐220)](https://github.com/schickling/Device.swift) - Super-lightweight library to detect used device.
*   [DeviceKit (⭐4.2k)](https://github.com/devicekit/DeviceKit) - DeviceKit is a value-type replacement of UIDevice.
*   [Deviice (⭐62)](https://github.com/andrealufino/Deviice) - Swift library to easily check the current device and some more info about it.
*   [Luminous (⭐332)](https://github.com/andrealufino/Luminous) - Get everything you need to know about the device.
*   [Thingy (⭐60)](https://github.com/bojan/Thingy) - A modern device detection and querying library.
*   [UIDeviceComplete (⭐415)](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces.

### Documentation

*Generate documentation for Swift code* [back to top](#readme)

*   [jazzy (⭐7.3k)](https://github.com/realm/jazzy/) - Soulful docs.
*   [SourceDocs (⭐364)](https://github.com/SourceDocs/SourceDocs) - Generate Markdown reference documentation that lives with your code.

### Email

[back to top](#readme)

### Embedded Systems

*Build your embedded Linux projects on a RaspberryPi, BeagleBone, C.H.I.P. and other boards.* [back to top](#readme)

*   [SwiftyGPIO (⭐1.3k)](https://github.com/uraimo/SwiftyGPIO) :penguin: - Interact with Linux GPIO/SPI/PWM on ARM.

#### Peripherals

*Interact with specific external peripherals.* [back to top](#readme)

### Events

*Alternatives to NSNotificationCenter, Key-Value-Observation, or delegation.* [back to top](#readme)

*   [Bond (⭐4.2k)](https://github.com/DeclarativeHub/Bond) - Binding framework.
*   [Combinative (⭐108)](https://github.com/noppefoxwolf/Combinative) - UI event handling using Apple's combine framework.
*   [EmitterKit (⭐570)](https://github.com/aleclarson/emitter-kit) - Implementation of event emitters and listeners.
*   [FutureKit (⭐755)](https://github.com/FutureKit/FutureKit) - Future/Promises Library.
*   [Katana (⭐2.2k)](https://github.com/BendingSpoons/katana-swift) - Write apps a la React and Redux.
*   [LightweightObservable (⭐135)](https://github.com/fxm90/LightweightObservable) - A lightweight implementation of an observable sequence that you can subscribe to.
*   [NoticeObserveKit (⭐149)](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type.
*   [Notificationz (⭐77)](https://github.com/SwiftKitz/Notificationz) - Helping you own `NSNotificationCenter` by providing a simple, customizable adapter.
*   [Observable (⭐369)](https://github.com/roberthein/Observable) - The easiest way to observe values.
*   [OneWay (⭐64)](https://github.com/DevYeom/OneWay) - State management with unidirectional data flow.
*   [OpenCombine (⭐2.6k)](https://github.com/OpenCombine/OpenCombine) - Open source implementation of Apple's Combine framework for processing values over time.
*   [PMKVObserver (⭐708)](https://github.com/postmates/PMKVObserver/) - Modern thread-safe and type-safe key-value observing.
*   [PromiseKit (⭐14k)](https://github.com/mxcl/PromiseKit) - Async promise programming lib.
*   [ReactiveCocoa (⭐20k)](https://github.com/ReactiveCocoa/ReactiveCocoa) - ReactiveCocoa (RAC) is a Cocoa framework inspired by Functional Reactive Programming. It provides APIs for composing and transforming streams of values over time.
*   [ReactorKit (⭐2.6k)](https://github.com/ReactorKit/ReactorKit) - A framework for reactive and unidirectional application architecture.
*   [ReSwift (⭐7.5k)](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow.
*   [RxSwift (⭐24k)](https://github.com/ReactiveX/RxSwift) - Microsoft Reactive Extensions (Rx).
*   [Signals (⭐457)](https://github.com/artman/Signals) - Replaces delegates and notifications.
*   [SwiftEventBus (⭐1.1k)](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS.
*   [Tempura (⭐705)](https://github.com/BendingSpoons/tempura-swift) - A holistic approach to iOS development, inspired by Redux and MVVM.
*   [Tokamak (⭐2.3k)](https://github.com/TokamakUI/Tokamak) - React-like declarative API for building native UI components with easy to use one-way data binding.
*   [Tomorrowland (⭐116)](https://github.com/lilyball/Tomorrowland) - Lightweight Promises.
*   [TopicEventBus (⭐55)](https://github.com/mcmatan/topicEventBus) - Publish–subscribe design pattern implementation framework, with ability to publish events by topic.
*   [VueFlux (⭐331)](https://github.com/ra1028/VueFlux) - Unidirectional Data Flow State Management Architecture - Inspired by Vuex and Flux.
*   [When (⭐262)](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises.

### Files

[back to top](#readme)

*   [FileKit (⭐2.3k)](https://github.com/nvzqz/FileKit) - Simple and expressive file management.
*   [FileProvider (⭐10)](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files for iOS/tvOS and macOS.
*   [KZFileWatchers (⭐1.1k)](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote.
*   [PathKit (⭐1.4k)](https://github.com/kylef/PathKit) :penguin: - Effortless path operations.
*   [Pathos (⭐111)](https://github.com/dduan/Pathos) :penguin: - Efficient Unix file management.

### Fonts

*A collection of font related snippets.* [back to top](#readme)

*   [FontAwesome.swift (⭐1.6k)](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your projects.
*   [FontBlaster (⭐1.1k)](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app.
*   [Inkwell (⭐152)](https://github.com/ninjaprox/Inkwell) - An inkwell to use custom fonts on the fly.
*   [IoniconsKit (⭐313)](https://github.com/keitaoouchi/IoniconsKit) - Use ionicons as UIImage / UIFont in your projects.
*   [OcticonsKit (⭐54)](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects.
*   [SwiftIconFont (⭐1.2k)](https://github.com/segecey/SwiftIconFont) - Fontawesome, Iconic, Ionicons, Octicon ports.
*   [SwiftIcons (⭐787)](https://github.com/ranesr/SwiftIcons) - Library for Font Icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather.
*   [SwiftUI-FontIcon (⭐108)](https://github.com/huybuidac/SwiftUIFontIcon) - Font icons for SwiftUI: font awesome, ionicons, material icons.
*   [SYSymbol (⭐185)](https://github.com/Nirma/SFSymbol) - All the SFSymbols at your fingertips.
*   [UIFontComplete (⭐1.3k)](https://github.com/Nirma/UIFontComplete) - Font management (System & Custom) for iOS and tvOS.

### Game Engine

[back to top](#readme)

*   [glide engine (⭐474)](https://github.com/cocoatoucher/Glide) - SpriteKit and GameplayKit based engine for making 2d games, with practical examples and tutorials.
*   [Raylib for Swift (⭐80)](https://github.com/STREGAsGate/Raylib) :penguin: - A Cross-Platform Swift package for Raylib. Builds Raylib from source so no need to fiddle with libraries. Just add as a dependency in you game package and go!

#### 2D

[back to top](#readme)

*   [ImagineEngine (⭐1.8k)](https://github.com/JohnSundell/ImagineEngine) - Blazing fasst 2D gaming engine.

### Games

[back to top](#readme)

*   [FDChessboardView (⭐77)](https://github.com/fulldecent/FDChessboardView) - A view controller for chess boards
*   [Sage (⭐376)](https://github.com/nvzqz/Sage) :penguin: - A cross-platform chess library.

### Gesture

[back to top](#readme)

*   [ShowTime (⭐487)](https://github.com/KaneCheshire/ShowTime) - Show off your iOS taps and gestures for demos and videos with just one line of code.
*   [SwiftyGestureRecognition (⭐162)](https://github.com/b3ll/SwiftyGestureRecognition) - UIGestureRecognizers in Xcode Playgrounds.
*   [SwipyCell (⭐251)](https://github.com/moritzsternemann/SwipyCell) - UITableViewCell implementing swiping to trigger actions (known from the Mailbox App).
*   [Tactile (⭐716)](https://github.com/delba/Tactile) - A safer and more idiomatic way to respond to gestures and control events.

### Hardware

*A category dedicated to hardware related libs* [back to top](#readme)

#### 3D Touch

*Easy handle new 3D Touch / Force Touch feature thanks to these libs.* [back to top](#readme)

#### Bluetooth

*Wrappers around CoreBluetooth* [back to top](#readme)

*   [BlueCap (⭐702)](https://github.com/troystribling/BlueCap) - Wrapper around CoreBluetooth and much more.
*   [Bluejay (⭐1.1k)](https://github.com/steamclock/bluejay) - A simple framework for building reliable Bluetooth LE apps.
*   [BluetoothKit (⭐2.2k)](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.
*   [RxBluetoothKit (⭐1.4k)](https://github.com/polidea/RxBluetoothKit) - iOS & OSX Bluetooth library for RxSwift.
*   [SwiftyBluetooth (⭐199)](https://github.com/jordanebelanger/SwiftyBluetooth) - Simple and reliable closure based wrapper around CoreBluetooth.

#### Camera

*Awesome camera libs* [back to top](#readme)

*   [CameraBackground (⭐63)](https://github.com/yonat/CameraBackground) - Show camera layer as a background to any UIView.
*   [CameraKit-iOS (⭐653)](https://github.com/CameraKit/camerakit-ios) - Massively increase camera performance and ease of use in your next project.
*   [FDTake (⭐322)](https://github.com/fulldecent/FDTake) - Easily take a photo or video or choose from library.
*   [Fusuma (⭐2.5k)](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature.
*   [MediaPicker (⭐207)](https://github.com/exyte/mediapicker) - SwiftUI customizable media picker - supports camera and gallery with albums
*   [NextLevel (⭐2.1k)](https://github.com/NextLevel/NextLevel) - Rad Media Capture.

##### Barcode

*Barcode, QR-code, other code readers* [back to top](#readme)

*   [BarcodeScanner (⭐1.7k)](https://github.com/hyperoslo/BarcodeScanner) - A simple and beautiful barcode scanner view controller.
*   [EFQRCode (⭐4.5k)](https://github.com/EFPrefix/EFQRCode) - A better way to operate quick response code.
*   [QRCodeReader.swift (⭐1.3k)](https://github.com/yannickl/QRCodeReader.swift) - Simple QRCode reader.

#### Haptic Feedback

*Libraries that involve the use of Haptic Feedback* [back to top](#readme)

*   [Haptica (⭐742)](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator.

#### iBeacon

*Interested in using iBeacon in your Swift project? Here some interesting resources.* [back to top](#readme)

*   [SwiftLocation (⭐3.3k)](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring.

#### Sensors

*Manage your device sensors in a faster and easier way* [back to top](#readme)

### Images

*An interesting list of image related libs..* [back to top](#readme)

*   [Agrume (⭐703)](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer.
*   [AlamofireImage (⭐3.9k)](https://github.com/Alamofire/AlamofireImage) - AlamofireImage is an image component library for Alamofire.
*   [APNGKit (⭐2.2k)](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS.
*   [ATGMediaBrowser (⭐209)](https://github.com/altayer-digital/ATGMediaBrowser) - Image slide-show viewer with multiple predefined transition styles, and with ability to create new transitions with ease.
*   [AXPhotoViewer (⭐631)](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos.
*   [BlockiesSwift (⭐60)](https://github.com/Boilertalk/BlockiesSwift) - Unique blocky identicons/profile picture generator.
*   [Brightroom (⭐3k)](https://github.com/muukii/Brightroom) - An image editor and engine using CoreImage.
*   [CTPanoramaView (⭐1k)](https://github.com/scihant/CTPanoramaView) - A library that displays spherical or cylindrical panoramas with touch or motion based controls.
*   [DTPhotoViewerController (⭐280)](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController to display single photo or collection of photos, inspired by Facebook photo viewer.
*   [FacebookImagePicker (⭐234)](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker.
*   [FaceCrop (⭐45)](https://github.com/Ancestry/FaceCrop) - Detect and center faces in your images using Apple’s Vision Framework.
*   [FlexibleImage (⭐824)](https://github.com/kawoou/FlexibleImage) - A simple way to play with images.
*   [FMPhotoPicker (⭐709)](https://github.com/congnd/FMPhotoPicker) - A modern, simple and zero-dependency photo picker with an elegant and customizable image editor.
*   [gifu (⭐3k)](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS.
*   [GPUImage 2 (⭐4.8k)](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed framework for GPU-accelerated video and image processing.
*   [GPUImage 3 (⭐2.6k)](https://github.com/BradLarson/GPUImage3) - GPUImage 3 is a BSD-licensed framework for GPU-accelerated video and image processing using Metal.
*   [HanekeSwift (⭐5.2k)](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS with extra love for images.
*   [Harbeth (⭐380)](https://github.com/yangKJ/Harbeth) - Metal API for GPU accelerated Graphics and Video and Camera filter framework.
*   [ImageDetect (⭐301)](https://github.com/Feghal/ImageDetect) - Detect and crop faces, barcodes and texts in image with iOS 11 Vision API.
*   [ImageLoader (⭐293)](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS.
*   [ImageScout (⭐974)](https://github.com/kaishin/ImageScout) - Implementation of [fastimage](https://pypi.org/project/fastimage/0.2.1/) - supports PNG, GIF, and JPEG.
*   [ImageViewer (⭐2.5k)](https://github.com/Krisiacik/ImageViewer) - An image viewer à la Twitter.
*   [ImgixSwift (⭐24)](https://github.com/imgix/imgix-swift) - Easily update image urls to be fast and responsive.
*   [JLStickerTextView (⭐483)](https://github.com/Textcat/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image.
*   [Kanvas (⭐288)](https://github.com/tumblr/kanvas-ios) - A iOS library for adding effects, drawings, text, stickers, and making GIFs from existing media or the camera.
*   [Kingfisher (⭐22k)](https://github.com/onevcat/Kingfisher) - Image download and caching.
*   [LetterAvatarKit (⭐220)](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars.
*   [Lightbox (⭐1.6k)](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app.
*   [MapleBacon (⭐341)](https://github.com/JanGorman/MapleBacon) - Image download and caching library.
*   [MCScratchImageView (⭐358)](https://github.com/Minecodecraft/MCScratchImageView) - A custom ImageView that is used to cover the surface of other view like a scratch card, user can swipe the mulch to see the view below.
*   [Moa (⭐333)](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS.
*   [Nuke (⭐7.6k)](https://github.com/kean/Nuke) - Advanced framework for loading, caching, processing, displaying and preheating images.
*   [PassportScanner (⭐453)](https://github.com/evermeer/PassportScanner) - Scan the MRZ code of a passport and extract the first name, last name, passport number, nationality, date of birth, expiration date and personal number.
*   [Rough (⭐99)](https://github.com/bakhtiyork/Rough) - Rough lets you draw in a sketchy, hand-drawn-like, style.
*   [Sharaku (⭐1.5k)](https://github.com/makomori/Sharaku) - Image filtering UI library like Instagram.
*   [Snowflake (⭐954)](https://github.com/onmyway133/Snowflake) - Work with SVG.
*   [SwiftDraw (⭐228)](https://github.com/swhitty/SwiftDraw) - Library that converts SVG images to UIImage, NSImage and generates CoreGraphics source code.
*   [SwiftGen-Assets (⭐8.9k)](https://github.com/SwiftGen/SwiftGen#assets-catalogs) - A tool to auto-generate `enums` for all your `UIImages` from your Assets Catalogs.
*   [SwiftSVG (⭐1.9k)](https://github.com/mchoe/SwiftSVG) - A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView).
*   [SwiftWebImage (⭐44)](https://github.com/geekaurora/SwiftWebImage) - 🚀SwiftUI Image downloader with performant LRU mem/disk cache.
*   [SwiftyGif (⭐1.9k)](https://github.com/kirualex/SwiftyGif) - High performance GIF engine.
*   [TinyCrayon (⭐1.8k)](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps.
*   [Toucan (⭐2.4k)](https://github.com/gavinbunney/Toucan) - Image processing api.
*   [UIImageColors (⭐3.2k)](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage.
*   [YPImagePicker (⭐4.2k)](https://github.com/Yummypets/YPImagePicker) - Instagram-like image picker & filters for iOS.
*   [ZImageCropper (⭐228)](https://github.com/ZaidPathan/ZImageCropper) - Crop image in any shape.

### Key Value Coding

*Libraries for key-value coding* [back to top](#readme)

### Keyboard

*Do you want to create your own customized keyboard? Here are some interesting resources* [back to top](#readme)

*   [IHKeyboardAvoiding (⭐1.4k)](https://github.com/IdleHandsApps/IHKeyboardAvoiding) - An elegant solution for keeping any UIView visible when the keyboard is being shown. No UIScrollView required.
*   [IQKeyboardManager (⭐16k)](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
*   [ISEmojiView (⭐486)](https://github.com/isaced/ISEmojiView) - Emoji Keyboard for iOS
*   [KeyboardHideManager (⭐56)](https://github.com/bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS.
*   [KeyboardShortcuts (⭐1.5k)](https://github.com/sindresorhus/KeyboardShortcuts) - Add user-customizable global keyboard shortcuts to your macOS app. Includes a Cocoa and SwiftUI component.
*   [Ribbon (⭐297)](https://github.com/chriszielinski/Ribbon) - 🎀 A simple cross-platform toolbar/custom input accessory view library for iOS & macOS.
*   [Typist (⭐1.1k)](https://github.com/totocaster/Typist) - Small, drop-in UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center.

### Kit

*Libraries for coding with a simplified API* [back to top](#readme)

*   [BFKit-Swift (⭐997)](https://github.com/FabrizioBrancati/BFKit-Swift) :penguin: - A collection of useful classes, structs and extensions to develop Apps faster.
*   [C4iOS (⭐977)](https://github.com/C4Labs/C4iOS) - Harnesses the power of native iOS programming with a simplified API.

### Layout

*Libs to help you with layout.* [back to top](#readme)

*   [AnimatedTabBar (⭐198)](https://github.com/exyte/AnimatedTabBar) - A tabbar with a number of preset animations.
*   [BrickKit (⭐606)](https://github.com/wayfair-archive/brickkit-ios) - Create complex and responsive layouts in a simple way.
*   [CGLayout (⭐44)](https://github.com/k-o-d-e-n/CGLayout) :penguin: - Powerful autolayout framework, that can manage UIView(NSView), CALayer, not rendered views and etc. Provides placeholders.
*   [FlexLayout (⭐1.8k)](https://github.com/layoutBox/FlexLayout) - Nice and clean interface to the highly optimized Facebook yoga Flexbox implementation.
*   [Grid (⭐1.5k)](https://github.com/exyte/Grid) - The most powerful Grid container missed in SwiftUI.
*   [LayoutLess (⭐433)](https://github.com/DeclarativeHub/Layoutless) - Write less UI Code.
*   [Neon (⭐4.6k)](https://github.com/mamaral/Neon) - A powerful programmatic UI layout framework.
*   [PinLayout (⭐2.2k)](https://github.com/layoutBox/PinLayout) - Fast Views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable. \[iOS/macOS/tvOS]
*   [Scaling Header Scroll View (⭐751)](https://github.com/exyte/ScalingHeaderScrollView) - A scroll view with a sticky header which shrinks as you scroll. Written with SwiftUI.
*   [Static (⭐1.3k)](https://github.com/venmo/Static) - A simple static table views for iOS.
*   [Stevia (⭐3.3k)](https://github.com/freshOS/Stevia) - Elegant view layout for iOS.

#### Auto Layout

*Bored of using storyboard? Give a try to declarative auto layout libs.* [back to top](#readme)

*   [Bamboo (⭐74)](https://github.com/wordlessj/Bamboo) - Auto Layout (and manual layout) in one line.
*   [Cartography (⭐7.3k)](https://github.com/robb/Cartography) - Declarative auto layout lib for your project.
*   [Cassowary (⭐111)](https://github.com/tribalworldwidelondon/CassowarySwift) - A linear constraint solving library using the same algorithm as AutoLayout.
*   [Cupcake (⭐286)](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS.
*   [DeviceLayout (⭐169)](https://github.com/cruisediary/DeviceLayout) - AutoLayout can be set differently for each device.
*   [EasyPeasy (⭐1.9k)](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy.
*   [EasySwiftLayout (⭐350)](https://github.com/Pimine/EasySwiftLayout) - Lightweight Swift framework for Apple's Auto-Layout.
*   [EZLayout (⭐25)](https://github.com/alexliubj/EZAnchor) - An easier and faster way to code Autolayout.
*   [HypeUI (⭐116)](https://github.com/hyperconnect/HypeUI) - 🌺 HypeUI is a implementation of Apple's SwiftUI DSL style based on UIKit
*   [KVConstraintKit (⭐91)](https://github.com/keshavvishwkarma/KVConstraintKit) - An Impressive Autolayout DSL for iOS, tvOS & OSX.
*   [MisterFusion (⭐315)](https://github.com/marty-suzuki/MisterFusion) - DSL for AutoLayout, supports Size Class.
*   [Mortar (⭐83)](https://github.com/jmfieldman/Mortar) - A concise but flexible DSL for creating Auto Layout constraints and adding subviews.
*   [NorthLayout (⭐40)](https://github.com/banjun/NorthLayout) - Fast path to layout using Visual Format Language (VFL) with extended syntax.
*   [PureLayout (⭐7.6k)](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & OS X Auto Layout.
*   [SnapKit (⭐20k)](https://github.com/SnapKit/SnapKit) - Autolayout DSL for iOS & OS X.
*   [Swiftstraints (⭐119)](https://github.com/Skyvive/Swiftstraints) - Powerful auto-layout framework that lets you write constraints in one line of code.
*   [TinyConstraints (⭐3.9k)](https://github.com/roberthein/TinyConstraints) - TinyConstraints is the syntactic sugar that makes Auto Layout sweeter for human use.

### Localization

*Frameworks that helps with localizing your app* [back to top](#readme)

*   [BartyCrouch (⭐1.3k)](https://github.com/FlineDev/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs.
*   [CrowdinSDK (⭐109)](https://github.com/crowdin/mobile-sdk-ios) - Delivers all new translations from Crowdin project to the application immediately.
*   [IBLocalizable (⭐463)](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable.
*   [L10n-swift (⭐310)](https://github.com/Decybel07/L10n-swift) - Localization of an application with ability to change language "on the fly" and support for plural forms in any language.
*   [LocalizationKit (⭐1.2k)](https://github.com/willpowell8/LocalizationKit_iOS) - Realtime dynamic localization of your app with remote management so you can manage maintain and deploy translations without resubmitting app.
*   [Localize (⭐286)](https://github.com/andresilvagomez/Localize) - Localize apps using e.g. regular expressions in Localizable.strings.
*   [Localize-Swift (⭐3k)](https://github.com/marmelroy/Localize-Swift) - Localize apps using e.g. regular expressions in Localizable.strings.
*   [Locheck (⭐89)](https://github.com/Asana/locheck) - Validate .strings and .stringsdict files for errors
*   [SwiftGen-L10n (⭐8.9k)](https://github.com/SwiftGen/SwiftGen#localizablestrings) - A tool to auto-generate `enums` for all your Localizable.strings keys (with appropriate associated values if those strings contains printf-format placeholders like `%@`).
*   [Translatio (⭐20)](https://github.com/andrealufino/Translatio) - Super lightweight library that helps you to localize strings, even directly in storyboards.

### Location

[back to top](#readme)

*   [AsyncLocationKit (⭐157)](https://github.com/AsyncSwift/AsyncLocationKit) - Wrapper for Apple CoreLocation framework with Modern Concurrency Swift (async/await).
*   [STLocationRequest (⭐639)](https://github.com/SvenTiigi/STLocationRequest) - An elegant and simple 3D Flyover Location Request Screen.

### Logging

*Utilities for writing to and reading from the device log* [back to top](#readme)

*   [AEConsole (⭐148)](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App.
*   [CleanroomLogger (⭐1.3k)](https://github.com/emaloney/CleanroomLogger) - Configurable and extensible high-level logging API that is simple, lightweight and performant.
*   [Duration (⭐325)](https://github.com/SwiftStudies/Duration) :penguin: - Lightweight logging library focused on reporting timings for operations.
*   [Gedatsu (⭐528)](https://github.com/bannzai/gedatsu) - Provide readable format about AutoLayout error console log.
*   [HeliumLogger (⭐176)](https://github.com/Kitura/HeliumLogger) :penguin: - IBM's lightweight logging framework.
*   [Printer (⭐66)](https://github.com/hemangshah/printer) - A fancy logger for your next app.
*   [Puppy (⭐132)](https://github.com/sushichop/Puppy) :penguin: - A flexible logging library that supports multiple transports and platforms.
*   [QorumLogs (⭐782)](https://github.com/Esqarrouth/QorumLogs) - Logging Utility for Xcode & Google Docs.
*   [Rainbow (⭐1.8k)](https://github.com/onevcat/Rainbow) :penguin: - Delightful console output.
*   [SwiftyBeaver (⭐5.8k)](https://github.com/SwiftyBeaver/SwiftyBeaver) :penguin: - Multi-platform logging during development & release.
*   [TinyConsole (⭐2k)](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app.
*   [TraceLog (⭐52)](https://github.com/tonystone/tracelog) :penguin: - Dead Simple: logging the way it's meant to be!  Runs on iOS, macOS, and Linux.
*   [Watchdog (⭐1.9k)](https://github.com/wojteklu/Watchdog) - Utility for logging excessive blocking on the main thread.
*   [WatchdogInspector (⭐514)](https://github.com/tapwork/WatchdogInspector) - A logging tool to show the current framerate (fps) in the status bar of your iOS app.
*   [Willow (⭐1.3k)](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library.
*   [XCGLogger (⭐3.9k)](https://github.com/DaveWoodCom/XCGLogger) - Full featured & Configurable logging utility with log levels, timestamps, and line numbers.

### Maps

[back to top](#readme)

*   [Cluster (⭐1.3k)](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering.
*   [FlyoverKit (⭐703)](https://github.com/SvenTiigi/FlyoverKit) - FlyoverKit enables you to present stunning 360° flyover views on your MKMapView with zero effort while maintaining full configuration possibilities.
*   [GEOSwift (⭐1.4k)](https://github.com/GEOSwift/GEOSwift) - Make it easier to work with geographic models and calculate intersections, overlapping, projections etc.
*   [LocoKit (⭐1.5k)](https://github.com/sobri909/LocoKit) - A location and activity recording framework for iOS.

### Math

[back to top](#readme)

*   [Arithmosophi (⭐66)](https://github.com/phimage/Arithmosophi) - Set of protocols for Arithmetic and Logical operations.
*   [BigInt (⭐734)](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic.
*   [DDMathParser (⭐841)](https://github.com/davedelong/DDMathParser) - DDMathParser makes it easy to parse a String and evaluate it as a mathematical expression.
*   [SigmaSwiftStatistics (⭐682)](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation.
*   [Upsurge (⭐180)](https://github.com/alejandro-isaza/Upsurge) - Simple and fast matrix and vector math.

### Natural Language Processing

[back to top](#readme)

### Network

*A list of libs that allow you to decrease the amount of time spent dealing with http requests.* [back to top](#readme)

*   [Alamofire (⭐40k)](https://github.com/Alamofire/Alamofire) :penguin: - Elegant networking.
*   [APIKit (⭐2k)](https://github.com/ishkawa/APIKit) - Library for building type-safe web API client.
*   [Ciao (⭐59)](https://github.com/AlTavares/Ciao) - Publish and discover services using mDNS (Bonjour, Zeroconf).
*   [CodyFire (⭐251)](https://github.com/CodyFlame/CodyFire) - Powerful Codable API requests builder and manager for iOS. Based on Alamofire.
*   [Conduit (⭐52)](https://github.com/mindbody/Conduit) - Robust networking for web APIs.
*   [Connectivity (⭐1.6k)](https://github.com/rwbutler/Connectivity) - 🌐 Makes Internet connectivity detection more robust by detecting Wi-Fi networks without Internet access.
*   [Dots (⭐39)](https://github.com/iAmrSalman/Dots) - Lightweight Concurrent Networking Framework.
*   [GoodNetworking (⭐31)](https://github.com/GoodRequest/GoodNetworking) - 📡 GoodNetworking simplifies HTTP networking.
*   [Heimdallr.swift (⭐634)](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS.
*   [Just (⭐1.4k)](https://github.com/dduan/Just) :penguin: - HTTP for Humans (a python-requests style HTTP library).
*   [Malibu (⭐11)](https://github.com/hyperoslo/Malibu) - A networking library built on promises.
*   [Moya (⭐15k)](https://github.com/Moya/Moya) - Network abstraction layer.
*   [MultiPeer (⭐215)](https://github.com/dingwilson/MultiPeer) - A wrapper for the MultipeerConnectivity framework for automatic offline data transmission between devices.
*   [Netfox (⭐3.5k)](https://github.com/kasketis/netfox) - A lightweight, one line setup, network debugging library.
*   [Netswift (⭐25)](https://github.com/MrSkwiggs/Netswift) - A type-safe, high-level networking solution.
*   [OAuth2 (⭐1.1k)](https://github.com/p2/OAuth2) - oauth2 auth lib.
*   [OAuthSwift (⭐3.2k)](https://github.com/OAuthSwift/OAuthSwift) - OAuth library for iOS.
*   [Pitaya (⭐845)](https://github.com/johnlui/Pitaya) :penguin: - HTTP / HTTPS networking library just incidentally execute on machines.
*   [PMHTTP (⭐505)](https://github.com/postmates/PMHTTP) - HTTP framework with a focus on REST and JSON.
*   [Postal (⭐650)](https://github.com/snipsco/Postal) - Framework providing simple access to common email providers.
*   [Reachability.swift (⭐7.8k)](https://github.com/ashleymills/Reachability.swift) - A replacement for Apple's Reachability with closures.
*   [ReactiveAPI (⭐78)](https://github.com/sky-uk/ReactiveAPI) - Write clean, concise and declarative network code relying on URLSession, with the power of RxSwift. Inspired by Retrofit.
*   [ResponseDetective (⭐1.9k)](https://github.com/netguru/ResponseDetective) - A non-intrusive framework for intercepting any outgoing requests and incoming responses between your app and server for debugging purposes.
*   [RxNetworks (⭐192)](https://github.com/yangKJ/RxNetworks) - Network API With RxSwift + Moya + HandyJSON + Plugins.
*   [ShadowsocksX-NG (⭐32k)](https://github.com/shadowsocks/ShadowsocksX-NG) - A fast tunnel proxy that helps you bypass firewalls.
*   [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for REST APIs that untangles stateful messes. An alternative to callback- and delegate-based networking.
*   [SolarNetwork (⭐102)](https://github.com/ThreeGayHub/SolarNetwork) - Elegant network abstraction layer.
*   [SwiftHTTP (⭐1.9k)](https://github.com/daltoniam/SwiftHTTP) - NSURLSession wrapper.
*   [SwiftyOAuth (⭐476)](https://github.com/delba/SwiftyOAuth) - A small OAuth library with a built-in set of providers.
*   [TermiNetwork (⭐95)](https://github.com/billp/TermiNetwork) - 🌏 A zero-dependency networking solution for building modern and secure iOS, watchOS, macOS and tvOS applications.
*   [TRON (⭐537)](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire.
*   [Wormholy (⭐2.2k)](https://github.com/pmusolino/Wormholy) - iOS network debugging, like a wizard 🧙‍.

#### HTML

*Need to manipulate contents from html easily?* [back to top](#readme)

*   [Fuzi (⭐1k)](https://github.com/cezheng/Fuzi) - A fast & lightweight XML/HTML parser with XPath & CSS support.
*   [Kanna (⭐2.4k)](https://github.com/tid-kijyun/Kanna) - Another XML/HTML parser.
*   [SwiftSoup (⭐4.2k)](https://github.com/scinfu/SwiftSoup) :penguin: - HTML Parser, with best of DOM, CSS, and jquery.
*   [WKZombie (⭐1.2k)](https://github.com/mkoehnke/WKZombie) - Headless browser.

#### Messaging Protocol

[back to top](#readme)

*   [CocoaMQTT (⭐1.5k)](https://github.com/emqx/CocoaMQTT) - MQTT for iOS and OS X.
*   [Perfect-Notifications (⭐114)](https://github.com/PerfectlySoft/Perfect-Notifications) - iOS Notifications for Linux and OS X.

#### SOAP

[back to top](#readme)

*   [SOAPEngine (⭐479)](https://github.com/priore/SOAPEngine) - Generic SOAP client to access SOAP Web Services using iOS, Mac OS X, and Apple TV.

#### Socket

[back to top](#readme)

*   [BlueSocket (⭐1.4k)](https://github.com/Kitura/BlueSocket) - IBM's cross platform low level socket framework.
*   [BlueSSLService (⭐95)](https://github.com/Kitura/BlueSSLService) - SSL/TLS add-in for IBM's low level socket framework.
*   [DNWebSocket (⭐36)](https://github.com/GlebRadchenko/DNWebSocket) - Object-Oriented, Autobahn tested WebSocket Library (RFC 6455).
*   [RxWebSocket (⭐56)](https://github.com/fjcaetano/RxWebSocket) - Reactive WebSockets.
*   [Socket.IO (⭐5.1k)](https://github.com/socketio/socket.io-client-swift) :penguin: - Socket.IO client for iOS/OS X.
*   [sockets (⭐574)](https://github.com/vapor-community/sockets) :penguin: - TCP, UDP; Client, Server; Linux, OS X.
*   [Starscream (⭐7.9k)](https://github.com/daltoniam/Starscream) - Websockets for iOS and OSX.
*   [SwiftSocket (⭐1.6k)](https://github.com/swiftsocket/SwiftSocket) - Simple TCP socket library.
*   [SwiftWebSocket (⭐1.5k)](https://github.com/tidwall/SwiftWebSocket) - A high performance WebSocket client library .

#### Webserver

*Would you like host a webserver in your device? Here you can find how to do it.* [back to top](#readme)

*   [Ambassador (⭐176)](https://github.com/envoy/Ambassador) - Super lightweight web framework based on SWSGI.
*   [Curassow (⭐396)](https://github.com/kylef-archive/Curassow) :penguin: - HTTP server using the pre-fork worker model.
*   [Embassy (⭐581)](https://github.com/envoy/Embassy) :penguin: - Super lightweight async HTTP server library.
*   [Kitura (⭐7.6k)](https://github.com/Kitura/Kitura) :penguin: - IBM's web framework and server for web services.
*   [Lightning (⭐314)](https://github.com/skylab-inc/Lightning) :penguin: - Multiplatform Single-threaded Non-blocking Web and Networking Framework.
*   [Noze.io (⭐306)](https://github.com/NozeIO/Noze.io) :penguin: - Evented I/O streams like Node.js.
*   [Perfect (⭐14k)](https://github.com/PerfectlySoft/Perfect) :penguin: - Server-side Swift. The Perfect library, application server, connectors and example apps.
*   [swifter (⭐3.8k)](https://github.com/httpswift/swifter) :penguin: - Http server with routing handler.
*   [Vapor (⭐23k)](https://github.com/vapor/vapor) :penguin: - Elegant web framework that works on iOS, OS X, and Ubuntu.
*   [Zewo (⭐1.9k)](https://github.com/Zewo/Zewo) :penguin: - Server-Side Swift.

### OCR

[back to top](#readme)

*   [SwiftOCR (⭐4.6k)](https://github.com/NMAC427/SwiftOCR) - Neural Network based OCR lib.

### Optimization

[back to top](#readme)

### PDF

[back to top](#readme)

*   [PDFGenerator (⭐742)](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF. Generate PDF from view(s) or image(s).
*   [SimplePDF (⭐243)](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly.
*   [UXMPDFKit (⭐273)](https://github.com/uxmstudio/UXMPDFKit) - A PDF viewer and annotator that can be embedded in iOS applications.

### Quality

[back to top](#readme)

*   [AnyLint (⭐119)](https://github.com/Flinesoft/AnyLint) :penguin: - Lint anything by combining the power of Swift & regular expressions.
*   [IBLinter (⭐951)](https://github.com/IBDecodable/IBLinter) - A linter tool for Interface Builder.
*   [L10nLint (⭐38)](https://github.com/s2mr/L10nLint) - A linter tool for Localizable.strings.
*   [swift-mod (⭐100)](https://github.com/ra1028/swift-mod) - A tool for Swift code modification intermediating between code generation and formatting.
*   [SwiftCop (⭐542)](https://github.com/andresinaka/SwiftCop) - A validation library which inspired by the clarity of Ruby On Rails Active Record validations.
*   [SwiftFormat (⭐7.1k)](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code.
*   [SwiftLint (⭐18k)](https://github.com/realm/SwiftLint) - A tool to enforce coding conventions.
*   [Swimat (⭐1.6k)](https://github.com/Jintin/Swimat) - Xcode plugin to format code.
*   [Tailor (⭐1.4k)](https://github.com/sleekbyte/tailor) :penguin: - Cross-platform static analyzer that helps you to write cleaner code and avoid bugs.

### Scripting

[back to top](#readme)

*   [Swift for Scripting (⭐267)](https://github.com/artemnovichkov/Swift-For-Scripting) - A hand-curated collection of useful and informative scripting material.

### SDK

[back to top](#readme)

### Security

[back to top](#readme)

*   [SecurePropertyStorage (⭐469)](https://github.com/alexruperez/SecurePropertyStorage) - Helps you define secure storages for your properties using Swift property wrappers.

#### Cryptography

*Deal with cryptography method easily* [back to top](#readme)

*   [BlueCryptor (⭐186)](https://github.com/Kitura/BlueCryptor) - IBM's Cross Platform Crypto library.
*   [BlueRSA (⭐126)](https://github.com/Kitura/BlueRSA) - IBM's Cross Platform RSA Crypto library.
*   [CryptoSwift (⭐9.8k)](https://github.com/krzyzanowskim/CryptoSwift) :penguin: - Crypto related functions and helpers.
*   [IDZSwiftCommonCrypto (⭐475)](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library.
*   [JOSESwift (⭐178)](https://github.com/airsidemobile/JOSESwift) - A framework for the JOSE standards JWS, JWE, and JWK.
*   [RNCryptor (⭐3.3k)](https://github.com/RNCryptor/RNCryptor) - CCCryptor (Apple's AES encryption) wrappers for iOS and Mac.
*   [SCrypto (⭐39)](https://github.com/sgl0v/scrypto) - Elegant interface to access the CommonCrypto routines.
*   [Siphash (⭐262)](https://github.com/attaswift/SipHash) - Simple and secure hashing with the SipHash algorithm.
*   [Swift-Sodium (⭐497)](https://github.com/jedisct1/swift-sodium) - Interface to the Sodium library for common crypto operations for iOS and OS X.
*   [Themis (⭐1.8k)](https://github.com/cossacklabs/themis) - Multilanguage framework for making typical encryption schemes easy to use: data at rest, authenticated data exchange, transport protection, authentication, and so on.

#### Keychain

[back to top](#readme)

*   [GoodPersistence (⭐32)](https://github.com/GoodRequest/GoodPersistence) - 💾 GoodPersistence simplifies caching data in keychain and UserDefaults. Using a property wrappers.
*   [keychain-swift (⭐2.6k)](https://github.com/evgenyneu/keychain-swift) - Helper functions for saving text in Keychain securely for iOS, OS X, tvOS and watchOS.
*   [KeychainAccess (⭐7.6k)](https://github.com/kishikawakatsumi/KeychainAccess) - Simple wrapper for Keychain that works on iOS and OS X.
*   [Latch (⭐57)](https://github.com/endocrimes/Latch) - A simple Keychain Wrapper for iOS.
*   [SwiftKeychainWrapper (⭐1.6k)](https://github.com/jrendel/SwiftKeychainWrapper) - Simple static wrapper for the iOS Keychain to allow you to use it in a similar fashion to user defaults.

### Streaming

[back to top](#readme)

*   [HaishinKit (⭐2.6k)](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS, tvOS.
*   [Live (⭐2.4k)](https://github.com/ltebean/Live) - Demonstrate how to build a live broadcast app.

### Styling

[back to top](#readme)

*   [Stylist (⭐289)](https://github.com/yonaskolb/Stylist) - Define UI styles in a hot-loadable external yaml or json file.
*   [SwiftTheme (⭐2.5k)](https://github.com/wxxsw/SwiftTheme) - Powerful theme/skin manager for iOS 8+.
*   [Themes (⭐240)](https://github.com/onmyway133/EasyTheme) - Theme management.

### SVG

[back to top](#readme)

*   [SVGView (⭐456)](https://github.com/exyte/SVGView) - SVG parser and renderer written in SwiftUI.

### System

[back to top](#readme)

*   [BlueSignals (⭐92)](https://github.com/Kitura/BlueSignals) - IBM's Cross Platform OS signal handling library.
*   [LaunchAtLogin (⭐1.4k)](https://github.com/sindresorhus/LaunchAtLogin) - Easily add 'Launch at Login' functionality to your sandboxed macOS app.
*   [SystemKit (⭐346)](https://github.com/beltex/SystemKit/) - OS X system library.

### Testing

*A collection of testing frameworks.* [back to top](#readme)

*   [DVR (⭐651)](https://github.com/venmo/DVR) - A simple network testing framework.
*   [Erik (⭐564)](https://github.com/phimage/Erik) - An headless browser to access and manipulate webpages using javascript allowing to run functional tests.
*   [Fakery (⭐1.7k)](https://github.com/vadymmarkov/Fakery) - Fake data generator.
*   [Mussel (⭐70)](https://github.com/UrbanCompass/Mussel) - A framework for easily testing Push Notifications, Universal Links and Routing in XCUITests.
*   [Nimble (⭐4.7k)](https://github.com/Quick/Nimble) - A matcher framework.
*   [OHHTTPStubs (⭐5k)](https://github.com/AliSoftware/OHHTTPStubs) - A testing library designed to stub your network requests easily.
*   [Quick (⭐9.7k)](https://github.com/Quick/Quick) :penguin: - Quick is a behavior-driven development framework.
*   [SBTUITestTunnel (⭐312)](https://github.com/Subito-it/SBTUITestTunnel) - UI testing library for interact with network requests, stub CLLocationManager and UNUserNotificationCenter, and fine grain scrolling in table/collection/scroll views
*   [Sizes (⭐1.2k)](https://github.com/marcosgriselli/Sizes) - Test your app on different device and font sizes.
*   [SnapshotTest (⭐41)](https://github.com/parski/SnapshotTest) - Snapshot testing tool for iOS and tvOS.
*   [Spectre (⭐399)](https://github.com/kylef/Spectre) :penguin: - BDD Framework.
*   [SwiftCheck (⭐1.4k)](https://github.com/typelift/SwiftCheck) - A testing library that automatically generates random data for testing program properties.
*   [UI Testing Cheat Sheet (⭐2.1k)](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - Answers to common "How do I test this with UI Testing?" questions with a working example app.
*   [XCTest (⭐1.1k)](https://github.com/apple/swift-corelibs-xctest) - The XCTest Project, A Swift core library for providing unit test support.

#### Mock

[back to top](#readme)

*   [AutoMockable (⭐42)](https://github.com/vincent-pradeilles/AutoMocker) - A framework that leverages the type system to let you easily create mocked instances of your data types.
*   [Cuckoo (⭐1.6k)](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework.
*   [Mocker (⭐998)](https://github.com/WeTransfer/Mocker) - Mock Alamofire and URLSession requests without touching your code implementation
*   [Mockingbird (⭐194)](https://github.com/Farfetch/mockingbird) - Simplify software testing, by easily mocking any system using HTTP/HTTPS, allowing a team to test and develop against a service that is not complete, unstable or just to reproduce planned cases.
*   [Mockingjay (⭐1.5k)](https://github.com/kylef/Mockingjay) - An elegant library for stubbing HTTP requests with ease.
*   [Mockit (⭐122)](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework, inspired by the famous Mockito for Java.
*   [MockSwift (⭐86)](https://github.com/leoture/MockSwift) - Mock Framework that uses the power of property wrappers.

### Text

*A collection of text projects.* [back to top](#readme)

*   [Attributed (⭐754)](https://github.com/Nirma/Attributed) - Modern µframework for attributed strings.
*   [AttributedTextView (⭐432)](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links, hashtags and mentions.
*   [BonMot (⭐3.5k)](https://github.com/Rightpoint/BonMot) - Beautiful, easy attributed strings for iOS.
*   [Croc (⭐130)](https://github.com/JKalash/Croc) - A lightweight Emoji parsing and querying library.
*   [edhita (⭐1.3k)](https://github.com/tnantoka/edhita) - Fully open source text editor for iOS.
*   [MarkdownKit (⭐740)](https://github.com/bmoliveira/MarkdownKit) - A simple and customizable Markdown Parser.
*   [MarkdownView (⭐1.9k)](https://github.com/keitaoouchi/MarkdownView) - iOS Markdown view.
*   [MarkyMark (⭐293)](https://github.com/M2Mobi/Marky-Mark) - Converts Markdown into native views or attributed strings.
*   [Notepad (⭐851)](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting.
*   [OEMentions (⭐48)](https://github.com/omar14/OEMentions) - An easy way to add mentions to uitextview like Facebook and Instagram.
*   [Parsey (⭐58)](https://github.com/rxwei/Parsey) - Parser combinator framework that supports source location tracking, backtracking prevention, and rich error messages.
*   [Pluralize.swift (⭐196)](https://github.com/joshualat/Pluralize.swift) - Great String Pluralize Extension.
*   [PredicateFlow (⭐102)](https://github.com/andreadelfante/PredicateFlow) - PredicateFlow is a builder that allows you to write amazing, strong-typed and easy-to-read NSPredicate.
*   [PrediKit (⭐539)](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS & OS X inspired by SnapKit.
*   [Regex by crossroadlabs (⭐331)](https://github.com/crossroadlabs/Regex) :penguin: - Very easy to use Regular Expressions library with rich functionality. Features both operator `=~` and method based APIs. Unit tests covered.
*   [Regex by sindresorhus (⭐320)](https://github.com/sindresorhus/Regex) - Swifty regular expressions, fully tested & documented, and with correct Unicode handling.
*   [RichEditorView (⭐1.9k)](https://github.com/cjwirth/RichEditorView) -  RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing.
*   [Sprinter (⭐166)](https://github.com/nicklockwood/Sprinter) - A library for formatting strings.
*   [SwiftRichString (⭐3k)](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library.
*   [SwiftVerbalExpressions (⭐595)](https://github.com/VerbalExpressions/SwiftVerbalExpressions) - VerbalExpressions porting.
*   [SwiftyAttributes (⭐1.6k)](https://github.com/eddiekaiger/SwiftyAttributes) - Extensions that make it a breeze to work with attributed strings.
*   [Tagging (⭐117)](https://github.com/k-lpmg/Tagging) - A TextView that provides easy to use tagging feature for Mention or Hashtag.
*   [Texstyle (⭐79)](https://github.com/rosberry/texstyle) - Texstyle allows you to format attributed strings easily.
*   [TextAttributes (⭐2.2k)](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings.
*   [TextBuilder (⭐210)](https://github.com/davdroman/TextBuilder) - Like a SwiftUI ViewBuilder, but for Text.
*   [TwitterTextEditor (⭐2.9k)](https://github.com/twitter/TwitterTextEditor) - A standalone, flexible API that provides a full featured rich text editor for iOS applications.
*   [VEditorKit (⭐480)](https://github.com/GeekTree0101/VEditorKit) - Lightweight and Powerful Editor Kit.

### Thread

*Threading, task-based or asynchronous programming, Grand Central Dispatch (GCD) wrapper* [back to top](#readme)

*   [Async (⭐4.6k)](https://github.com/duemunk/Async) - Syntactic sugar for Grand Central Dispatch.
*   [AwaitKit (⭐752)](https://github.com/yannickl/AwaitKit) - The ES7 Async/Await control flow.
*   [Each (⭐761)](https://github.com/dalu93/Each) - Each is a NSTimer bridge library.
*   [GCDTimer (⭐189)](https://github.com/hemantasapkota/GCDTimer) - A well-tested GCD timer.
*   [Schedule (⭐1.8k)](https://github.com/luoxiu/Schedule) :penguin: - A missing lightweight task scheduler with an incredibly human-friendly syntax.
*   [SwiftyTimer (⭐1.2k)](https://github.com/radex/SwiftyTimer) - API for NSTimer.

### UI

*A collection of pre-packaged transitions & cool ui stuffs.* [back to top](#readme)

*   [ActivityIndicatorView (⭐1.2k)](https://github.com/exyte/ActivityIndicatorView) - A number of preset loading indicators created with SwiftUI.
*   [AECoreDataUI (⭐303)](https://github.com/tadija/AERecord) - Core Data driven UI.
*   [AGCircularPicker (⭐624)](https://github.com/agilie/AGCircularPicker) - Helpful component for creating a controller aimed to manage any calculated parameter.
*   [AMScrollingNavbar (⭐6.1k)](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView.
*   [Arale (⭐45)](https://github.com/supercomputra/Arale) - A custom stretchable header view for UIScrollView or any its subclasses with UIActivityIndicatorView support for content reloading.
*   [BadgeHub (⭐809)](https://github.com/jogendra/BadgeHub) - Make any UIView a full fledged animated notification center. It is a way to quickly add a notification badge icon to a UIView.
*   [BatteryView (⭐51)](https://github.com/yonat/BatteryView) - Simple battery shaped UIView.
*   [BetterSafariView (⭐487)](https://github.com/stleamist/BetterSafariView) - A better way to present a SFSafariViewController or start a ASWebAuthenticationSession in SwiftUI.
*   [BottomSheet (⭐210)](https://github.com/joomcode/BottomSheet) - Powerful Bottom Sheet component with content based size, interactive dismissal and navigation controller support.
*   [BreakOutToRefresh (⭐2.5k)](https://github.com/dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit.
*   [BulletinBoard (⭐5.3k)](https://github.com/alexisakers/BulletinBoard) - Generates and manages contextual cards displayed at the bottom of the screen.
*   [CapturePreventionKit (⭐24)](https://github.com/Jaesung-Jung/CapturePreventionKit) - Provides `Label` and `ImageView` for `screen capture prevention`.
*   [CircularProgress (⭐545)](https://github.com/sindresorhus/CircularProgress) - Circular progress indicator for your macOS app.
*   [ClassicKit (⭐2.2k)](https://github.com/Baddaboo/ClassicKit) - A collection of classic-style UI components.
*   [ContainerController (⭐442)](https://github.com/mrustaa/ContainerController) - UI Component. This is a copy swipe-panel from app: Apple Maps, Stocks
*   [CountryPickerView (⭐476)](https://github.com/kizitonwose/CountryPickerView) - A simple, customizable view for efficiently collecting country information in iOS apps.
*   [CustomSegue (⭐123)](https://github.com/phimage/CustomSegue) - Custom segue for OSX Storyboards with slide and cross fade effects.
*   [DeckTransition (⭐2.2k)](https://github.com/HarshilShah/DeckTransition) - A library to recreate the iOS 10 Apple Music now playing transition.
*   [DockProgress (⭐1.1k)](https://github.com/sindresorhus/DockProgress) - Show progress in your macOS app's Dock icon.
*   [Dodo (⭐874)](https://github.com/evgenyneu/Dodo) - A message bar for iOS.
*   [Doric Design System Foundation (⭐95)](https://github.com/jayeshk/Doric) - Protocol oriented, type safe, scalable design system foundation framework for iOS.
*   [DropDown (⭐2.4k)](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS.
*   [Elissa (⭐171)](https://github.com/KitchenStories/Elissa) - Displays a notification on top of a UITabBarItem or any UIView anchor view to reveal additional information.
*   [EstMusicIndicator (⭐468)](https://github.com/Aufree/ESTMusicIndicator) - Music play indicator like iTunes.
*   [Family (⭐250)](https://github.com/zenangst/Family) - A child view controller framework that makes setting up your parent controllers as easy as pie.
*   [FAQView (⭐472)](https://github.com/mukeshthawani/faqview) - An easy to use FAQ view for iOS.
*   [Fashion (⭐131)](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles.
*   [FlagKit (⭐3k)](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web.
*   [FlexibleHeader (⭐70)](https://github.com/k-lpmg/FlexibleHeader) - A container view that responds to scrolling of UIScrollView.
*   [FloatRatingView (⭐545)](https://github.com/glenyi/FloatRatingView) - Floating rating system.
*   [Fluid Slider (⭐1.9k)](https://github.com/Ramotion/fluid-slider) - A slider widget with a popup bubble displaying the precise value selected.
*   [GaugeKit (⭐1k)](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges.
*   [GMStepper (⭐922)](https://github.com/gmertk/GMStepper) - A stepper with a sliding label in the middle.
*   [GradientProgressBar (⭐527)](https://github.com/fxm90/GradientProgressBar) - An animated gradient progress bar.
*   [GRMustache (⭐587)](https://github.com/groue/GRMustache.swift) - Flexible Mustache templates.
*   [GrowingTextView (⭐1k)](https://github.com/KennethTsang/GrowingTextView) - UITextView that supports auto growing, placeholder and length limit.
*   [HGCircularSlider (⭐2.5k)](https://github.com/HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application.
*   [HidesNavigationBarWhenPushed (⭐54)](https://github.com/gontovnik/HidesNavigationBarWhenPushed) - A library, which adds the ability to hide navigation bar when view controller is pushed via hidesNavigationBarWhenPushed flag.
*   [HorizontalDial (⭐210)](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram.
*   [HPParallaxHeader (⭐47)](https://github.com/ngochiencse/HPParallaxHeader) - Simple parallax header for UIScrollView.
*   [IGColorPicker (⭐277)](https://github.com/iGenius-Srl/IGColorPicker) - A customizable color picker for iOS.
*   [InstantSearch iOS (⭐588)](https://github.com/algolia/instantsearch-ios) - A library of widgets and helpers to build instant-search features on iOS.
*   [KALoader (⭐107)](https://github.com/Kirillzzy/KALoader) - Beautiful animated placeholders for showing loading of data.
*   [KMNavigationBarTransition (⭐3.4k)](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations.
*   [KMPlaceholderTextView (⭐803)](https://github.com/MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder.
*   [LeeGo (⭐967)](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks.
*   [LicensePlist (⭐2.3k)](https://github.com/mono0926/LicensePlist) - A command-line tool that automatically generates a Plist of all your dependencies.
*   [LiquidLoader (⭐1.3k)](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation.
*   [LoadingShimmer (⭐1.5k)](https://github.com/jogendra/LoadingShimmer) - An easy way to add a shimmering effect to any view with just one line of code. It is useful as an unobtrusive loading indicator.
*   [Macaw (⭐5.9k)](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support.
*   [Magnetic (⭐1.5k)](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music).
*   [Mandoline (⭐895)](https://github.com/blueapron/Mandoline) - An iOS picker view to serve all your 'picking' needs.
*   [MantleModal (⭐90)](https://github.com/canalesb93/MantleModal) - A simple modal resource that uses a UIScrollView to allow the user to close the modal by dragging it down.
*   [Material (⭐12k)](https://github.com/CosmicMind/Material) - Express your creativity with Material, an animation and graphics framework for Google's Material Design and Apple's Flat UI.
*   [Material Components for iOS (⭐4.7k)](https://github.com/material-components/material-components-ios) - Modular and customizable Material Design UI components.
*   [MaterialKit (⭐2.5k)](https://github.com/nghialv/MaterialKit) - Material design components.
*   [MediaBrowser (⭐646)](https://github.com/younatics/MediaBrowser) - Simple iOS photo and video browser with optional grid view, captions and selections.
*   [MPParallaxView (⭐1.7k)](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect.
*   [MultiSelectSegmentedControl (⭐298)](https://github.com/yonat/MultiSelectSegmentedControl) - UISegmentedControl remake that supports selecting multiple segments, vertical stacking, combining text and images.
*   [MultiSlider (⭐409)](https://github.com/yonat/MultiSlider) - UISlider clone with multiple thumbs and values, range highlight, optional snap intervals, optional value labels, either vertical or horizontal.
*   [MXParallaxHeader (⭐1.7k)](https://github.com/maxep/MXParallaxHeader) - Simple parallax header for UIScrollView.
*   [MZFormSheetPresentationController (⭐978)](https://github.com/m1entus/MZFormSheetPresentationController) - Provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet.
*   [NeumorphismKit (⭐45)](https://github.com/y-okudera/NeumorphismKit) - Neumorphism framework for UIKit.
*   [NextGrowingTextView (⭐1.8k)](https://github.com/FluidGroup/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above.
*   [NVActivityIndicatorView (⭐10k)](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations.
*   [OverlayContainer (⭐1.1k)](https://github.com/applidium/OverlayContainer) - OverlayContainer makes it easier to develop overlay based interfaces, such as the one presented in the Apple Maps or Stocks apps.
*   [Partition Kit (⭐238)](https://github.com/kieranb662/PartitionKit) - A SwiftUI Library for creating resizable partitions for View Content.
*   [Popovers (⭐1.6k)](https://github.com/aheze/Popovers) - A library to present popovers. Simple, modern, and highly customizable. Not boring!
*   [Preferences (⭐1.3k)](https://github.com/sindresorhus/Preferences) - Add a preferences window to your macOS app in minutes.
*   [ProgressIndicatorView (⭐174)](https://github.com/exyte/ProgressIndicatorView) - A progress indicator view library written in SwiftUI.
*   [PullToDismiss (⭐481)](https://github.com/sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar.
*   [RangeSeekSlider (⭐700)](https://github.com/WorldDownTown/RangeSeekSlider) - A customizable range slider like a UISlider for iOS.
*   [Reel search (⭐2.5k)](https://github.com/Ramotion/reel-search) - Option list managed as a reel.
*   [ResizingTokenField (⭐105)](https://github.com/tadejr/ResizingTokenField) - A UICollectionView-based token field which provides intrinsic content height.
*   [RetroProgress (⭐18)](https://github.com/hyperoslo/RetroProgress) - Retro looking progress bar straight from the 90s.
*   [SectionedSlider (⭐364)](https://github.com/LeonardoCardoso/SectionedSlider) - Control Center Slider.
*   [SelectionDialog (⭐117)](https://github.com/kciter/SelectionDialog) - Simple selection dialog.
*   [ShadowView (⭐410)](https://github.com/PierrePerrin/ShadowView) - Make shadows management easy on UIView.
*   [Shiny (⭐790)](https://github.com/efremidze/Shiny) - Iridescent Effect View (inspired by Apple Pay Cash).
*   [ShowSomeProgress (⭐104)](https://github.com/stoneburner/ShowSomeProgress) - Animated Progress and Activity Indicators for iOS apps.
*   [SkeletonView (⭐12k)](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting.
*   [SKPhotoBrowser (⭐2.5k)](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers.
*   [Spots](https://github.com/hyperoslo) - Spots is a view controller framework that makes your setup and future development blazingly fast.
*   [SpreadsheetView (⭐45)](https://github.com/kishikawakatsumi/SpreadsheetView) - Full configurable spreadsheet view user interfaces for iOS applications.
*   [StarryStars (⭐174)](https://github.com/peterprokop/StarryStars) - Display & edit ratings, fully customizable from interface builder.
*   [StatefulViewController (⭐2.1k)](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states.
*   [StepProgressView (⭐362)](https://github.com/yonat/StepProgressView) - Step-by-step progress view with labels and shapes. A good replacement for UIActivityIndicatorView and UIProgressView.
*   [SweetCurtain (⭐117)](https://github.com/multimediasuite/SweetCurtain) - Really sweet and easy bottom pullable sheet implementation. You can find a similar implementation in applications like Apple Maps, Find My, Stocks, etc.
*   [SwiftyUI (⭐340)](https://github.com/haoking/SwiftyUI) - High performance and lightweight UIView, UIImage, UIImageView, UIlabel, UIButton and more.
*   [TagListView (⭐2.6k)](https://github.com/ElaWorkshop/TagListView) - Simple but highly customizable iOS tag list view.
*   [Toaster (⭐1.7k)](https://github.com/devxoul/Toaster) - Notification toasts.
*   [Twinkle (⭐605)](https://github.com/piemonte/Twinkle) - Easy way to make elements in your iOS app twinkle.
*   [UIPheonix (⭐29)](https://github.com/MKGitHub/UIPheonix) - Easy, flexible, dynamic and highly scalable UI framework + concept for reusable component/control-driven apps.
*   [UltraDrawerView (⭐217)](https://github.com/super-ultra/UltraDrawerView) - Lightweight, fast and customizable Drawer View implementation identical to Apple Maps, Stocks and etc.
*   [URLEmbeddedView (⭐646)](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card.
*   [Wallet](https://github.com/russ-stamant/Wallet) - A replica of the Apple's Wallet interface. Add, delete or present your cards and passes.
*   [Windless (⭐948)](https://github.com/ParkGwangBeom/Windless) - Windless makes it easy to implement invisible layout loading view.
*   [WSTagsField (⭐1.3k)](https://github.com/whitesmith/WSTagsField) - An iOS text field that represents different Tags.
*   [YMTreeMap (⭐127)](https://github.com/yahoo/YMTreeMap) - Treemap / Heatmap layout engine, based on Squarified.
*   [YNSearch (⭐1.2k)](https://github.com/younatics/YNSearch) - Awesome fully customizable search view like Pinterest.

#### Alert

*Libs to display alert, action sheet, notification, popup.* [back to top](#readme)

*   [Alertift (⭐286)](https://github.com/sgr-ksmt/Alertift) - Modern, easy UIAlertController wrapper.
*   [Alerts Pickers (⭐5.6k)](https://github.com/dillidon/alerts-and-pickers) - Advanced usage of UIAlertController with TextField, DatePicker, PickerView, TableView and CollectionView.
*   [ALRT (⭐97)](https://github.com/mshrwtnb/alrt) - An easier constructor for UIAlertController. Present an alert from anywhere.
*   [AwaitToast (⭐143)](https://github.com/k-lpmg/AwaitToast) - 🍞 An async waiting toast with basic toast. Inspired by facebook posting toast.
*   [CDAlertView (⭐1.1k)](https://github.com/candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup.
*   [CFNotify (⭐494)](https://github.com/JT501/CFNotify) - A customizable framework to create draggable alert views.
*   [EZAlertController (⭐366)](https://github.com/thellimist/EZAlertController) - Easy UIAlertController.
*   [GSMessage (⭐709)](https://github.com/wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+.
*   [Kamagari (⭐78)](https://github.com/tasanobu-zz/Kamagari) - Simple UIAlertController builder class.
*   [Loaf (⭐1.1k)](https://github.com/schmidyy/Loaf) - A simple framework for easy iOS Toasts.
*   [MijickPopupView (⭐472)](https://github.com/Mijick/PopupView) - Present any popup in no time. Keep your code clean.
*   [NotificationBanner (⭐4.7k)](https://github.com/Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS.
*   [PMAlertController (⭐2.5k)](https://github.com/pmusolino/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController.
*   [PopupDialog (⭐3.9k)](https://github.com/orderella/PopupDialog) - A simple, customizable popup dialog. Replaces UIAlertController alert style.
*   [PopupView (⭐2.7k)](https://github.com/exyte/PopupView) - Toasts and popups library written with SwiftUI.
*   [SCLAlertView (⭐5.3k)](https://github.com/vikmeup/SCLAlertView-Swift) - Animated Alert view.
*   [Sheet (⭐333)](https://github.com/ParkGwangBeom/Sheet) - Actionsheet with navigation features such as the Flipboard App.
*   [SPAlert (⭐2.1k)](https://github.com/ivanvorobei/SPAlert) - Native popup from Apple Music & Feedback in AppStore. Contains Done & Heart presets.
*   [StatusAlert (⭐845)](https://github.com/LowKostKustomz/StatusAlert) - Display Apple system-like self-hiding status alerts without interrupting user flow.
*   [SweetAlert (⭐2k)](https://github.com/codestergit/SweetAlert-iOS) - Alert system.
*   [Swift-Prompts (⭐733)](https://github.com/GabrielAlva/Swift-Prompts) - Design custom prompts with a great scope of options to choose from.
*   [SwiftEntryKit (⭐6.4k)](https://github.com/huri000/SwiftEntryKit) - A simple and versatile pop-up presenter.
*   [SwiftMessages (⭐7k)](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS.
*   [SwiftOverlays (⭐629)](https://github.com/peterprokop/SwiftOverlays) - various popups and notifications.
*   [Toast-Swift (⭐365)](https://github.com/BastiaanJansen/Toast-Swift) - An easy to use library to create iOS 14 and newer style toasts.
*   [XLActionController (⭐3.3k)](https://github.com/xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller.
*   [Zingle (⭐111)](https://github.com/hemangshah/Zingle) - An alert will display underneath your UINavigationBar.

#### Blur

[back to top](#readme)

*   [VisualEffectView (⭐1k)](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color.

#### Button

[back to top](#readme)

*   [AHDownloadButton (⭐478)](https://github.com/amerhukic/AHDownloadButton) - Customizable download button with progress and transition animations. It is based on Apple's App Store download button.
*   [DOFavoriteButton (⭐3.6k)](https://github.com/okmr-d/DOFavoriteButton) - Cute Animated Button.
*   [ExpandableButton (⭐97)](https://github.com/DimaMishchenko/ExpandableButton) - Customizable and easy to use expandable button.
*   [FloatingButton (⭐923)](https://github.com/exyte/FloatingButton) - Easily customizable floating button menu created with SwiftUI.
*   [Floaty (⭐1.5k)](https://github.com/kciter/Floaty) - Floating Action Button for iOS.
*   [IGStoryButtonKit (⭐36)](https://github.com/KaoruMuta/IGStoryButtonKit) - Easy-to-use button with rich animation inspired by instagram stories.
*   [LGButton (⭐2.3k)](https://github.com/loregr/LGButton) - A fully customisable subclass of the native UIControl which allows you to create beautiful buttons without writing any line of code.
*   [LTHRadioButton (⭐369)](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty animation.
*   [MultiToggleButton (⭐83)](https://github.com/yonat/MultiToggleButton) - A UIButton subclass that implements tap-to-toggle button text (like the camera flash and timer buttons).
*   [NFDownloadButton (⭐430)](https://github.com/LeonardoCardoso/NFDownloadButton) - Revamped Download Button. It's kinda a reverse engineering of Netflix's app download button.
*   [PMSuperButton (⭐724)](https://github.com/pmusolino/PMSuperButton) - A powerful UIButton with super powers, customizable from Storyboard.
*   [RadioGroup (⭐190)](https://github.com/yonat/RadioGroup) - The missing iOS radio buttons group.
*   [SwiftShareBubbles (⭐174)](https://github.com/takecian/SwiftShareBubbles) - Animated social share buttons control for iOS.
*   [TransitionButton (⭐1.4k)](https://github.com/AladinWay/TransitionButton) - UIButton subclass for loading and transition animation.

#### Calendar

[back to top](#readme)

*   [CalendarKit (⭐2.4k)](https://github.com/richardtop/CalendarKit) - Fully customizable calendar day view.
*   [CalendarView (⭐571)](https://github.com/mmick66/CalendarView) - Calendar Component, It features both vertical and horizontal layout (and scrolling) and the display of native calendar events.
*   [DateTimePicker (⭐1.9k)](https://github.com/itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time.
*   [ElegantCalendar (⭐737)](https://github.com/ThasianX/ElegantCalendar) - The elegant full screen calendar missed in SwiftUI.
*   [HorizonCalendar (⭐2.6k)](https://github.com/airbnb/HorizonCalendar) - A declarative, performant, iOS calendar UI component that supports use cases ranging from simple date pickers all the way up to fully-featured calendar apps.
*   [JTAppleCalendar (⭐7.4k)](https://github.com/patchthecode/JTAppleCalendar) - UI calendar handler.
*   [KVKCalendar (⭐463)](https://github.com/kvyatkovskys/KVKCalendar) - A most fully customization calendar for Apple platforms 📅
*   [Workaholic (⭐115)](https://github.com/hemangshah/Workaholic) - A GitHub-like work contribution timeline.

#### Cards

[back to top](#readme)

*   [CardNavigation (⭐44)](https://github.com/james01/CardNavigation) - A navigation controller that displays its view controllers as an interactive stack of cards.
*   [CardParts (⭐2.5k)](https://github.com/intuit/CardParts) - A reactive, card-based UI framework built on UIKit for iOS developers.
*   [VerticalCardSwiper (⭐1.3k)](https://github.com/JoniVR/VerticalCardSwiper) - A marriage between the Shazam Discover UI and Tinder, built with UICollectionView.

#### Form

[back to top](#readme)

*   [Carbon (⭐1.3k)](https://github.com/ra1028/Carbon) - 🚴 A declarative library for building component-based user interfaces in UITableView and UICollectionView.
*   [Eureka (⭐12k)](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder.
*   [FDBarGauge (⭐26)](https://github.com/fulldecent/FDBarGauge) - Simulate the level indicator on an audio mixing board
*   [Former (⭐1.3k)](https://github.com/ra1028/Former) - A fully customizable library for easy creating UITableView based form.
*   [ObjectForm (⭐179)](https://github.com/haojianzong/ObjectForm) - A simple yet powerful library to build form for your class models.
*   [SwiftyFORM (⭐1.1k)](https://github.com/neoneye/SwiftyFORM) - Forms that can be validated.

#### HUD

[back to top](#readme)

*   [EZLoadingActivity (⭐609)](https://github.com/Esqarrouth/EZLoadingActivity) - Lightweight loading activity HUD.
*   [GradientLoadingBar (⭐885)](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar.
*   [KRProgressHUD (⭐661)](https://github.com/krimpedance/KRProgressHUD) - A beautiful and customizable progress HUD.
*   [PKHUD (⭐3.8k)](https://github.com/pkluz/PKHUD) - Reimplementation of the Apple HUD.

#### Label

[back to top](#readme)

*   [ActiveLabel (⭐4.4k)](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http\://).
*   [Atributika (⭐1.3k)](https://github.com/psharanda/Atributika) - TConvert text with HTML tags, links, hashtags, mentions into NSAttributedString. Make them clickable with UILabel drop-in replacement.
*   [CountdownLabel (⭐949)](https://github.com/suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function.
*   [GlitchLabel (⭐1k)](https://github.com/kciter/GlitchLabel) - Glitching UILabel for iOS.
*   [IncrementableLabel (⭐80)](https://github.com/tbaranes/IncrementableLabel) - An UILabel subclass to (de)increment numbers in an UILabel.
*   [KDEDateLabel (⭐114)](https://github.com/delannoyk/KDEDateLabel) - An UILabel subclass that updates itself to make time ago's format easier.
*   [LTMorphingLabel (⭐7.9k)](https://github.com/lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel.
*   [Nantes (⭐1.1k)](https://github.com/instacart/Nantes) - TTTAttributedLabel replacement.
*   [TriLabelView (⭐165)](https://github.com/mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS.

#### Menu

[back to top](#readme)

*   [AKSwiftSlideMenu (⭐283)](https://github.com/ashishkakkad8/AKSwiftSlideMenu) - Slide Menu (Drawer).
*   [CircleMenu (⭐3.4k)](https://github.com/Ramotion/circle-menu) - CircleMenu is a simple, elegant UI menu with a circular layout and material design animations.
*   [ENSwiftSideMenu (⭐1.8k)](https://github.com/evnaz/ENSwiftSideMenu) - Sliding side menu.
*   [FanMenu (⭐723)](https://github.com/exyte/fan-menu) - Menu with a circular layout based on Macaw.
*   [FlowingMenu (⭐976)](https://github.com/yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects.
*   [GuillotineMenu (⭐2.9k)](https://github.com/Yalantis/GuillotineMenu) - Guillotine style menu.
*   [HHFloatingView (⭐94)](https://github.com/hemangshah/HHFloatingView) - An easy to use and setup floating view for your app.
*   [InteractiveSideMenu (⭐705)](https://github.com/handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu.
*   [KWDrawerController (⭐156)](https://github.com/Kawoou/KWDrawerController) - Drawer view controller that easy to use.
*   [MenuItemKit (⭐851)](https://github.com/cxa/MenuItemKit) - `UIMenuItem` with image and block (closure) support.
*   [Pagemenu (⭐5.3k)](https://github.com/PageMenu/PageMenu) - Pagination enabled view controller.
*   [PagingKit (⭐1.4k)](https://github.com/kazuhiro4949/PagingKit) - PagingKit provides customizable menu UI.
*   [Panels (⭐1.5k)](https://github.com/antoniocasero/Panels) - Panels is a framework to easily add sliding panels to your application.
*   [Parchment (⭐3.2k)](https://github.com/rechsteiner/Parchment) - A paging view controller with a highly customizable menu, built on UICollectionView.
*   [PopMenu (⭐1.6k)](https://github.com/CaliCastle/PopMenu) - 😎 A cool and customizable popup style action sheet for iOS.
*   [SideMenu (⭐5.6k)](https://github.com/jonkykong/SideMenu) - Simple side menu control for iOS inspired by Facebook. Right and Left sides. No coding required.
*   [SlideMenuControllerSwift (⭐3.4k)](https://github.com/dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app.
*   [SwipeMenuViewController (⭐1.3k)](https://github.com/yysskk/SwipeMenuViewController) - Swipable tab and menu View and ViewController.
*   [XLPagerTabStrip (⭐6.9k)](https://github.com/xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS.
*   [YNDropDownMenu (⭐1.3k)](https://github.com/younatics/YNDropDownMenu) - Adorable iOS drop down menu.

#### Pagination

[back to top](#readme)

*   [CHIPageControl (⭐3.3k)](https://github.com/ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl.
*   [FlexiblePageControl (⭐790)](https://github.com/shima11/FlexiblePageControl) - A flexible UIPageControl like Instagram.
*   [iPages (⭐168)](https://github.com/benjaminsage/iPages) - Quickly implement swipable page views in SwiftUI 📝.
*   [Pageboy (⭐1.9k)](https://github.com/uias/Pageboy) - A simple, highly informative page view controller.
*   [PageController (⭐412)](https://github.com/hirohisa/PageController) - Infinite paging controller.
*   [SlideController (⭐418)](https://github.com/touchlane/SlideController) - It is a nice alternative for UIPageViewController built using power of generic types. Swipe between pages with an interactive title navigation control. Configure horizontal or vertical chains for unlimited pages amount.

#### Payment

[back to top](#readme)

*   [AnimatedCardInput (⭐38)](https://github.com/netguru/AnimatedCardInput) - Customisable and easy to use Credit Card UI.
*   [Caishen (⭐762)](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS.
*   [iCard (⭐339)](https://github.com/eliakorkmaz/iCard) - Bank Card Generator using SnapKit DSL.
*   [MFCard (⭐363)](https://github.com/MobileFirstInc/MFCard) - Easily integrate Credit Card payments in iOS App.
*   [TPInAppReceipt (⭐587)](https://github.com/tikhop/TPInAppReceipt) - A lightweight, pure-Swift library for reading and validating Apple In App Purchase Receipt locally.

#### Permissions

[back to top](#readme)

*   [AREK (⭐954)](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission.
*   [Permission (⭐2.9k)](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS.
*   [SPPermission (⭐5.4k)](https://github.com/ivanvorobei/SPPermissions) - Simple request permission with native UI and interactive animation.

#### Scroll Bars

[back to top](#readme)

*   [DMScrollBar (⭐22)](https://github.com/batanus/DMScrollBar) - Best in class customizable ScrollBar for any type of ScrollView with Decelerating, Bounce & Rubber band mechanisms and many many more.

#### StackView

[back to top](#readme)

*   [StackViewController (⭐868)](https://github.com/seedco/StackViewController) - Simplify the use of UIStackView.
*   [TZStackView (⭐1.2k)](https://github.com/tomvanzummeren/TZStackView) - An iOS9 UIStackView layout component re-implemented for iOS 7 and 8.

#### Switch

[back to top](#readme)

*   [MJMaterialSwitch (⭐68)](https://github.com/JaleelNazir/MJMaterialSwitch) - A Customizable Switch UI for iOS, Inspired from Google's Material Design.
*   [paper-switch (⭐2.9k)](https://github.com/Ramotion/paper-switch) - RAMPaperSwitch is a material design UI module which paints over the parent view when the switch is turned on.
*   [Switch (⭐145)](https://github.com/T-Pham/Switch) - A switch control with full Interface Builder support.

#### Tab

[back to top](#readme)

*   [Adaptive Tab Bar (⭐2k)](https://github.com/Ramotion/adaptive-tab-bar) - Adaptive tab bar.
*   [Animated Tab Bar (⭐11k)](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a module for adding animation to tab bar items.
*   [CardTabBar (⭐199)](https://github.com/yusadogru/CardTabBar) - Adding animation to iOS tabbar items.
*   [CircleBar (⭐856)](https://github.com/softhausHQ/CircleBar) - A fun, easy-to-use tab bar navigation controller for iOS.
*   [ColorMatchTabs (⭐1.4k)](https://github.com/Yalantis/ColorMatchTabs) - Interesting way to display tabs.
*   [DTPagerController (⭐290)](https://github.com/tungvoduc/DTPagerController) - Container view controller to display a set of ViewControllers in a horizontal scroll view.
*   [ESTabBarController (⭐5k)](https://github.com/eggswift/ESTabBarController) - A highly customizable TabBarController component, which is inherited from UITabBarController.
*   [HHTabBarView (⭐149)](https://github.com/hemangshah/HHTabBarView) - A lightweight customized tab bar view.
*   [PolioPager (⭐176)](https://github.com/YuigaWada/PolioPager) - A flexible TabBarController with search tab like SNKRS.
*   [TabBar (⭐302)](https://github.com/onl1ner/TabBar) - Highly customizable tab bar for SwiftUI applications.
*   [Tabman (⭐2.7k)](https://github.com/uias/Tabman) - A powerful paging view controller with indicator bar.
*   [TabPageViewController (⭐1.4k)](https://github.com/EndouMari/TabPageViewController) - Paging view controller and scroll tab view.

#### Template

[back to top](#readme)

*   [Stencil (⭐2.3k)](https://github.com/stencilproject/Stencil) - Simple and powerful template language.
*   [SwiftCssParser (⭐278)](https://github.com/100mango/SwiftCssParser) - Extensible CSS parser.
*   [Temple (⭐30)](https://github.com/GoodRequest/Temple) - 🗂️ Most advanced project and file templates.

#### TextField

[back to top](#readme)

*   [CBPinEntryView (⭐189)](https://github.com/Fawxy/CBPinEntryView) - Easy to use, very customisable pin entry.
*   [CHIOTPField (⭐263)](https://github.com/ChiliLabs/CHIOTPField) - A set of textfields that can be used for One-time passwords, SMS codes, PIN codes, etc.
*   [DTTextField (⭐338)](https://github.com/iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label.
*   [FloatingLabelTextFieldSwiftUI (⭐426)](https://github.com/kishanraja/FloatingLabelTextFieldSwiftUI) - FloatingLabelTextFieldSwiftUI is a small and lightweight SwiftUI framework written in completely SwiftUI (not using UIViewRepresentable) that allows to create beautiful and customisable floating label textfield!
*   [HTYTextField (⭐313)](https://github.com/hanton/HTYTextField) - A UITextField with bouncy placeholder.
*   [iTextField ⌨️ (⭐99)](https://github.com/benjaminsage/iTextField) - A fully-wrapped `UITextField` that works entirely in SwiftUI 🦅.
*   [PasswordTextField (⭐308)](https://github.com/PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforces good password policies.
*   [SkyFloatingLabelTextField (⭐4k)](https://github.com/Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern".
*   [StyledTextKit (⭐1.2k)](https://github.com/GitHawkApp/StyledTextKit) - Declarative building and fast rendering attributed string library.
*   [TextFieldCounter (⭐437)](https://github.com/serralvo/TextFieldCounter) - UITextField character counter with lovable UX.
*   [TextFieldEffects (⭐5.9k)](https://github.com/raulriera/TextFieldEffects) - Several ready to use effects for UITextFields.
*   [UITextField-Navigation (⭐446)](https://github.com/T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields. Highly customizable.
*   [VKPinCodeView (⭐96)](https://github.com/Sunspension/VKPinCodeView) - Simple and elegant UI component for input PIN.

#### Transition

[back to top](#readme)

*   [BubbleTransition (⭐3.3k)](https://github.com/andreamazz/BubbleTransition) - Bubble transition in an easy way.
*   [Cards XI (⭐4.2k)](https://github.com/PaoloCuscela/Cards) - Awesome iOS 11 AppStore's Card Views.
*   [EasyTransitions (⭐1.7k)](https://github.com/marcosgriselli/EasyTransitions) - A simple way to create custom interactive UIViewController transitions.
*   [Hero (⭐22k)](https://github.com/HeroTransitions/Hero) - Elegant transition library for iOS.
*   [ImageTransition (⭐214)](https://github.com/shtnkgm/ImageTransition) - ImageTransition is a library for smooth animation of images during transitions.
*   [Jelly (⭐2.4k)](https://github.com/SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code.
*   [LiquidSwipe (⭐427)](https://github.com/exyte/LiquidSwipe) - Liquid navigation animation
*   [MijickNavigattie (⭐53)](https://github.com/Mijick/Navigattie) - Easy navigation with SwiftUI.
*   [MusicPlayerTransition (⭐642)](https://github.com/xxxAIRINxxx/MusicPlayerTransition) - Custom interactive transition like Apple Music iOS App.
*   [NavigationTransitions (⭐496)](https://github.com/davdroman/swiftui-navigation-transitions) - Pure SwiftUI Navigation transitions.
*   [PanSlip (⭐103)](https://github.com/k-lpmg/PanSlip) - Use PanGesture to dismiss view on UIViewController and UIView.
*   [PinterestSwift (⭐1.9k)](https://github.com/demonnico/PinterestSwift) - Pinterest style transition.
*   [RevealingSplashView (⭐1.2k)](https://github.com/PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by the Twitter splash.
*   [SamuraiTransition (⭐276)](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat cutting animations.
*   [SPLarkController (⭐974)](https://github.com/ivanvorobei/SPLarkController) - Custom transition between two controller. Translate to top.
*   [SPStorkController (⭐2.7k)](https://github.com/ivanvorobei/SPStorkController) - Now playing controller from Apple Music. Customisable height.
*   [StarWars.iOS (⭐3.8k)](https://github.com/Yalantis/StarWars.iOS) - Transition animation to crumble view-controller into tiny pieces.
*   [Transition (⭐2.6k)](https://github.com/Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions.

#### 3D

[back to top](#readme)

*   [Insert3D (⭐91)](https://github.com/Viktoo/Insert3D) - The fastest 🚀 way to embed a 3D model.

#### UICollectionView

[back to top](#readme)

*   [ASCollectionView (⭐372)](https://github.com/abdullahselek/ASCollectionView) - Lightweight custom collection view inspired by Airbnb.
*   [AZCollectionViewController (⭐94)](https://github.com/AfrozZaheer/AZCollectionViewController) - Easy way to integrate pagination with dummy views in CollectionView, make Instagram Discover withing minutes.
*   [Blueprints (⭐990)](https://github.com/zenangst/Blueprints) - A framework that is meant to make your life easier when working with collection view flow layouts.
*   [BouncyLayout (⭐4.2k)](https://github.com/roberthein/BouncyLayout) - Collection view layout that makes your cells bounce.
*   [CardsLayout (⭐825)](https://github.com/filletofish/CardsLayout) - Nice card-designed custom CollectionView layout.
*   [CenteredCollectionView (⭐1.3k)](https://github.com/BenEmdon/CenteredCollectionView) - A lightweight UICollectionViewLayout that pages and centers it's cells.
*   [CheckmarkCollectionViewCell (⭐64)](https://github.com/yonat/CheckmarkCollectionViewCell) - UICollectionViewCell with checkbox when it isSelected and empty circle when not - like Photos.app 'Select' mode.
*   [CollectionViewShelfLayout (⭐376)](https://github.com/pitiphong-p/CollectionViewShelfLayout) - A UICollectionViewLayout subclass displays its items as rows of items similar to the App Store Feature tab without a nested UITableView/UICollectionView hack.
*   [CollectionViewSlantedLayout (⭐2.3k)](https://github.com/yacir/CollectionViewSlantedLayout) - UICollectionViewLayout to show slanted content.
*   [Drag and Drop UICollectionView (⭐522)](https://github.com/mmick66/KDDragAndDropCollectionView) - Dragging and Dropping data across multiple UICollectionViews.
*   [FSPagerView (⭐6.9k)](https://github.com/WenchaoD/FSPagerView) - Elegant Screen Slide Library. It is extremely helpful for making Banner View、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders.
*   [Gliding Collection (⭐1.5k)](https://github.com/Ramotion/gliding-collection) - Gliding Collection is a smooth, flowing, customizable decision for a UICollectionView Controller.
*   [GoodProvider (⭐27)](https://github.com/GoodRequest/GRProvider) - 🚀 UITableView and UICollectionView provider to simplify basic scenarios of showing the data.
*   [GravitySlider (⭐1k)](https://github.com/ApplikeySolutions/GravitySlider) - Beautiful alternative to the standard UICollectionView flow layout.
*   [ShelfView-iOS (⭐268)](https://github.com/tdscientist/ShelfView-iOS) - iOS custom view to display books on shelf.
*   [SimpleSource (⭐98)](https://github.com/Squarespace/simple-source) - Easy and type-safe iOS table and collection views.
*   [SwiftSpreadsheet (⭐637)](https://github.com/stuffrabbit/SwiftSpreadsheet) - Fully customizable spreadsheet CollectionViewLayout.
*   [TagCellLayout (⭐353)](https://github.com/riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments.
*   [UICollectionViewSplitLayout (⭐240)](https://github.com/yahoojapan/UICollectionViewSplitLayout) - UICollectionViewSplitLayout makes collection view more responsive.
*   [VegaScroll (⭐2.9k)](https://github.com/AppliKeySolutions/VegaScroll) - Lightweight animation flowlayout for UICollectionView.

#### UITableView

[back to top](#readme)

*   [AZTableViewController (⭐73)](https://github.com/AfrozZaheer/AZTableViewController) - Elegant and easy way to integrate pagination with placeholder views.
*   [CollapsibleTableSectionViewController (⭐353)](https://github.com/jeantimex/CollapsibleTableSectionViewController) - A library to support collapsible sections in a table view.
*   [DGElasticPullToRefresh (⭐3.8k)](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh.
*   [DiffableDataSources (⭐830)](https://github.com/ra1028/DiffableDataSources) - 💾 A library for backporting UITableView/UICollectionViewDiffableDataSource.
*   [DTTableViewManager (⭐452)](https://github.com/DenTelezhkin/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types.
*   [ExpandableCell (⭐761)](https://github.com/younatics/ExpandableCell) - Fully refactored YNExapnadableCell with more concise, bug free. Easiest usage of expandable & collapsible cell for iOS. You can customize expandable UITableViewCell whatever you like. ExpandableCell is made because insertRows and deleteRows is hard to use. Just inheirt ExpandableDelegate.
*   [FDTextFieldTableViewCell (⭐26)](https://github.com/fulldecent/FDTextFieldTableViewCell) - Adds a UITextField to the cell and places it correctly.
*   [folding-cell (⭐10k)](https://github.com/Ramotion/folding-cell) - Folding cell transition.
*   [GridView (⭐846)](https://github.com/KyoheiG3/GridView) - Can be customized as a time table, spreadsheet, paging and more.
*   [HGPlaceholders (⭐2.2k)](https://github.com/HamzaGhazouani/HGPlaceholders) - Nice library to show placeholders and Empty States for any UITableView/UICollectionView in your project.
*   [OKTableViewLiaison (⭐84)](https://github.com/okcupid/OKTableViewLiaison) - Framework to help you better manage UITableViews.
*   [ParallaxHeader (⭐1k)](https://github.com/romansorochak/ParallaxHeader) - Simple way to add parallax header to UIScrollView/UITableView.
*   [Persei (⭐3.5k)](https://github.com/Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView.
*   [PullToRefreshSwift (⭐537)](https://github.com/dekatotoro/PullToRefreshSwift) - PullToRefresh library.
*   [QuickTableViewController (⭐546)](https://github.com/bcylin/QuickTableViewController) - A simple way to create a UITableView for settings.
*   [ReverseExtension (⭐1.7k)](https://github.com/marty-suzuki/ReverseExtension) - UITableView extension that enables the insertion of cells the from bottom of a table view.
*   [SelectionList (⭐115)](https://github.com/yonat/SelectionList) - Simple single-selection or multiple-selection checklist, based on UITableView.
*   [Shoyu (⭐277)](https://github.com/xai3/Shoyu) - Easier way to represent the structure of UITableView.
*   [SwiftyComments (⭐223)](https://github.com/tsucres/SwiftyComments) - Nested hierarchy of expandable/collapsible cells to easily build elegant discussion threads.
*   [SwipeCellKit (⭐6.1k)](https://github.com/SwipeCellKit/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app.
*   [WLEmptyState (⭐316)](https://github.com/wizeline/WLEmptyState) - A component that lets you customize the view when the dataset of UITableView is empty.
*   [YNExpandableCell (⭐454)](https://github.com/younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS.

#### Walkthrough

[back to top](#readme)

*   [AwesomeSpotlightView (⭐319)](https://github.com/aleksandrshoshiashvili/AwesomeSpotlightView) - Create tutorial or coach tour.
*   [BWWalkthrough (⭐2.8k)](https://github.com/ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App.
*   [ConcentricOnboarding (⭐1.2k)](https://github.com/exyte/ConcentricOnboarding) - SwiftUI library for a walkthrough or onboarding flow with tap actions.
*   [Gecco (⭐14)](https://github.com/xai3/Gecco) - Spotlight view for iOS.
*   [Instructions (⭐5.1k)](https://github.com/ephread/Instructions) - A library to create app walkthroughs and guided tours.
*   [OnboardKit (⭐508)](https://github.com/NikolaKirev/OnboardKit) - Customisable user onboarding for your iOS app.
*   [PaperOnboarding (⭐3.3k)](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design UI slider.
*   [SuggestionsKit (⭐69)](https://github.com/huemae/SuggestionsKit) - Library for educating users about features in app.
*   [SwiftyOnboard (⭐1.2k)](https://github.com/juanpablofernandez/SwiftyOnboard) - An iOS framework that allows developers to create beautiful onboarding experiences.
*   [SwiftyWalkthrough (⭐372)](https://github.com/ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps.

### Utility

*Some interesting utilities to help you in your projects* [back to top](#readme)

*   [AlexaSkillsKit (⭐177)](https://github.com/choefele/AlexaSkillsKit) - Develop custom Alexa Skills.
*   [ApplyStyleKit (⭐208)](https://github.com/shindyu/ApplyStyleKit) - Elegantly, Apply style to UIKit using Method Chain.
*   [Basis (⭐317)](https://github.com/typelift/Basis) - Pure Declarative Programming.
*   [Bow (⭐642)](https://github.com/bow-swift/bow) - Companion library for Typed Functional Programming.
*   [CallbackURLKit (⭐325)](https://github.com/phimage/CallbackURLKit) - Implementation of x-callback-url (Inter app communication).
*   [Closures (⭐1.7k)](https://github.com/vhesener/Closures) - Swifty closures for UIKit and Foundation.
*   [Codextended (⭐1.5k)](https://github.com/JohnSundell/Codextended) - Extensions giving Codable API type inference super powers.
*   [Curry (⭐493)](https://github.com/thoughtbot/Curry) - Function currying.
*   [Delegated (⭐704)](https://github.com/dreymonde/Delegated) - Closure-based delegation without memory leaks.
*   [DifferenceKit (⭐3.4k)](https://github.com/ra1028/DifferenceKit) - 💻 A fast and flexible O(n) difference algorithm framework.
*   [Differific (⭐124)](https://github.com/zenangst/Differific) - A fast and convenient diffing framework.
*   [Dollar (⭐4.2k)](https://github.com/ankurp/Dollar) - Similar to Lo-Dash or Underscore in Javascript.
*   [DuctTape (⭐176)](https://github.com/marty-suzuki/DuctTape) - 📦 KeyPath dynamicMemberLookup based syntax sugar for Swift.
*   [EtherWalletKit (⭐140)](https://github.com/SteadyAction/EtherWalletKit) - Ethereum Wallet Toolkit for iOS - You can implement Ethereum wallet without a server and blockchain knowledge.
*   [ExceptionCatcher (⭐116)](https://github.com/sindresorhus/ExceptionCatcher) - Catch Objective-C exceptions.
*   [EZSwiftExtensions (⭐3k)](https://github.com/goktugyil/EZSwiftExtensions) - How standard types and classes were supposed to work.
*   [FluentQuery (⭐147)](https://github.com/MihaelIsaev/FluentQuery) :penguin: - Powerful and easy to use Query Builder.
*   [GoodExtensions-iOS (⭐28)](https://github.com/GoodRequest/GoodExtensions-iOS) - 📑 GoodExtensions is a collection of useful and frequently used extensions.
*   [GoodUIKit (⭐29)](https://github.com/GoodRequest/GoodUIKit) - 📑 GoodUIKit is an extensions library filled with reusable UI snippets for faster and more efficient development.
*   [Highlighter (⭐930)](https://github.com/younatics/Highlighter) - Highlight whatever you want! Highlighter will magically find UI objects such as UILabel, UITextView, UITexTfield, UIButton in your UITableViewCell or other Class.
*   [LifetimeTracker (⭐2.9k)](https://github.com/krzysztofzablocki/LifetimeTracker) - Surface retain cycle / memory issues right as you develop your application.
*   [Lumos (⭐151)](https://github.com/sushinoya/Lumos) - An easy-to-use API for Objective-C runtime functions.
*   [ObjectiveKit (⭐847)](https://github.com/marmelroy/ObjectiveKit) - API for Objective C runtime functions.
*   [OpenSourceController (⭐51)](https://github.com/floriangbh/OpenSourceController) - The simplest way to display the librarie's licences used in your application.
*   [Percentage (⭐266)](https://github.com/sindresorhus/Percentage) - Make percentages more readable and type-safe.
*   [Periphery (⭐4.5k)](https://github.com/peripheryapp/periphery) - A tool to identify unused code in Swift projects.
*   [Playbook (⭐1.1k)](https://github.com/playbook-ui/playbook-ios) - 📘A library for isolated developing UI components and automatically snapshots of them.
*   [PrivacyFlash Pro (⭐150)](https://github.com/privacy-tech-lab/privacyflash-pro) - Generate a privacy policy for your Swift iOS app from its code.
*   [protobuf-swift (⭐937)](https://github.com/alexeyxo/protobuf-swift) - ProtocolBuffers.
*   [Prototope](http://khan.github.io/Prototope/) - Library of lightweight interfaces for prototyping, bridged to JS.
*   [R.swift (⭐9.3k)](https://github.com/mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues.
*   [RandomKit (⭐1.5k)](https://github.com/nvzqz/RandomKit/) :penguin: - Random data generation.
*   [ReadabilityKit (⭐822)](https://github.com/exyte/ReadabilityKit) - Preview extractor for news, articles and full-texts.
*   [ResourceKit (⭐89)](https://github.com/bannzai/ResourceKit) - Enable autocomplete use resources.
*   [Result (⭐2.5k)](https://github.com/antitypical/Result) - Type modelling the success/failure of arbitrary operations.
*   [Rugby (⭐606)](https://github.com/swiftyfinch/Rugby) - 🏈 Cache CocoaPods for faster rebuild and indexing Xcode project.
*   [Runes (⭐829)](https://github.com/thoughtbot/Runes) - Functional operators: flatMap, map, apply.
*   [Solar (⭐538)](https://github.com/ceeK/Solar) - Calculate sunrise and sunset times given a location.
*   [SpriteKit+Spring (⭐248)](https://github.com/ataugeron/SpriteKit-Spring) - SpriteKit API reproducing UIView's spring animations with SKAction.
*   [Sugar (⭐1.1k)](https://github.com/hyperoslo/Sugar) - Something sweet that goes great with your Cocoa.
*   [swift-protobuf (⭐4.3k)](https://github.com/apple/swift-protobuf) :penguin: - A plugin and runtime library for using Google's Protocol Buffer.
*   [SwiftAutoGUI (⭐25)](https://github.com/NakaokaRei/SwiftAutoGUI) - Used to programmatically control the mouse & keyboard. A library for manipulating macOS with Swift.
*   [SwiftBoost (⭐183)](https://github.com/sparrowcode/SwiftBoost) - Collection of Swift-extensions to boost development process.
*   [Swiftbot (⭐55)](https://github.com/noppefoxwolf/Swiftbot) - run swift code on slack.
*   [SwifterSwift (⭐13k)](https://github.com/SwifterSwift/SwifterSwift) - A handy collection of more than 500 native extensions to boost your productivity.
*   [SwiftGen-Storyboard (⭐8.9k)](https://github.com/SwiftGen/SwiftGen#uistoryboard) - A tool to auto-generate `enums` for all your Storyboards, Scenes and Segues constants + appropriate convenience accessors.
*   [SwiftLinkPreview (⭐1.4k)](https://github.com/LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all information such as title, relevant texts and images.
*   [SwiftPlantUML (⭐500)](https://github.com/MarcoEidinger/SwiftPlantUML) - A command-line tool and Swift Package to generate UML class from your Swift source code. Also available as Xcode Source Editor Extension.
*   [SwiftRandom (⭐559)](https://github.com/thellimist/SwiftRandom) - A tiny generator of random data.
*   [SwiftRater (⭐331)](https://github.com/takecian/SwiftRater) - A utility that reminds your iPhone app's users to review the app.
*   [SwiftTweaks (⭐1.4k)](https://github.com/khan/swifttweaks) - Tweak your iOS app without recompiling.
*   [Swiftx (⭐218)](https://github.com/typelift/Swiftx) - Functional data types and functions for any project.
*   [SwiftyUtils (⭐543)](https://github.com/tbaranes/SwiftyUtils) - All the reusable code that we need in each project.
*   [Swiftz (⭐3.3k)](https://github.com/typelift/Swiftz) - Functional programming.
*   [Then (⭐4.1k)](https://github.com/devxoul/Then) - Super sweet syntactic sugar for initializers.
*   [TSAO (⭐138)](https://github.com/lilyball/swift-tsao) - Type-Safe Associated Objects.
*   [URLQueryItemEncoder (⭐63)](https://github.com/pitiphong-p/URLQueryItemEncoder) - An Encoder for encoding any Encodable value into an array of URLQueryItem.
*   [UTIKit (⭐251)](https://github.com/cockscomb/UTIKit) - an UTI (Uniform Type Identifier) wrapper.
*   [Vaccine (⭐303)](https://github.com/zenangst/Vaccine) - Make your apps immune to recompile-decease.
*   [WeakableSelf (⭐76)](https://github.com/vincent-pradeilles/weakable-self) - A micro-framework to encapsulate \[weak self] and guard statements within closures.
*   [WhatsNew (⭐1.5k)](https://github.com/BalestraPatrick/WhatsNew) - Showcase new features after an app update similar to Pages, Numbers and Keynote.
*   [WhatsNewKit (⭐3.5k)](https://github.com/SvenTiigi/WhatsNewKit) - Showcase your awesome new app features.
*   [XestiMonitors (⭐271)](https://github.com/eBardX/XestiMonitors) - An extensible monitoring framework.
*   [ZamzamKit (⭐268)](https://github.com/ZamzamInc/ZamzamKit) - A collection of micro utilities and extensions for Standard Library, Foundation and UIKit.

### Validation

*A collection of validation libs.* [back to top](#readme)

*   [ATGValidator (⭐51)](https://github.com/altayer-digital/ATGValidator) - Rule based validation framework with form and card validation support for iOS.
*   [FormValidatorSwift (⭐498)](https://github.com/ustwo/formvalidator-swift) - Allows you to validate inputs of text fields and text views in a convenient way.
*   [Input Mask (⭐566)](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS.
*   [RxValidator (⭐154)](https://github.com/vbmania/RxValidator) - Simple, Extensible, Flexible Validation Checker.
*   [SwiftValidator (⭐1.4k)](https://github.com/SwiftValidatorCommunity/SwiftValidator) - A rule-based validation library.
*   [SwiftValidators (⭐240)](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS (inspired by validator.js).
*   [ValidatedPropertyKit (⭐956)](https://github.com/SvenTiigi/ValidatedPropertyKit) - Easily validate your Properties with Property Wrappers 👮.

#### Phone Numbers

*Libs to manage phone numbers.* [back to top](#readme)

*   [NKVPhonePicker (⭐144)](https://github.com/NikKovIos/NKVPhonePicker) - An UITextField subclass to simplify country code's picking.
*   [PhoneNumberKit (⭐4.9k)](https://github.com/marmelroy/PhoneNumberKit) - Framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber.

### Version Manager

[back to top](#readme)

*   [AppVersionMonitor (⭐258)](https://github.com/eure/AppVersionMonitor) - Monitor iOS app version easily.
*   [Siren (⭐4.1k)](https://github.com/ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade.
*   [Version (⭐179)](https://github.com/mrackwitz/Version) - Version represents and compares semantic versions.
*   [Version Tracker Swift (⭐85)](https://github.com/tbaranes/VersionTrackerSwift) - Versions tracker for your iOS, OS X, and tvOS app.

### Video

[back to top](#readme)

*   [BMPlayer (⭐1.9k)](https://github.com/BrikerMan/BMPlayer) - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide.
*   [Cabbage (⭐1.5k)](https://github.com/VideoFlint/Cabbage) - A video composition framework build on top of AVFoundation.
*   [Kitsunebi (⭐258)](https://github.com/noppefoxwolf/Kitsunebi) - Overlay alpha channel video animation player view using OpenGLES.
*   [MMPlayerView (⭐729)](https://github.com/MillmanY/MMPlayerView) - Custom AVPlayerLayer on view and transition player with good effect like YouTube and Facebook.
*   [MobilePlayer (⭐3k)](https://github.com/sahin/mobileplayer-ios) - A powerful and completely customizable media player for iOS.
*   [NextLevelSessionExporter (⭐243)](https://github.com/NextLevel/NextLevelSessionExporter) - Export and transcode media.
*   [Player (⭐2k)](https://github.com/piemonte/Player) - iOS video player, simple drop in component for playing and streaming media.
*   [PlayerView (⭐130)](https://github.com/davidlondono/PlayerView) - Easy to use video player using a UIView, manage rate of reproduction, screenshots and callbacks-delegate for player state.
*   [PryntTrimmerView (⭐789)](https://github.com/HHK1/PryntTrimmerView) - Trim and crop videos.
*   [SwiftFFmpeg (⭐444)](https://github.com/sunlubo/SwiftFFmpeg) - A wrapper for the FFmpeg C API.
*   [SwiftVideoBackground (⭐344)](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementating a video background.
*   [Swifty360Player (⭐165)](https://github.com/abdullahselek/Swifty360Player) - iOS 360-degree video player streaming from an AVPlayer.
*   [YiVideoEditor (⭐108)](https://github.com/coderyi/YiVideoEditor) - a library for rotating, cropping, adding layers (watermark) and as well as adding audio (music) to the videos.

## Serverless

*   [Azure Functions for Swift (⭐86)](https://github.com/SalehAlbuga/azure-functions-swift) :penguin: - Swift Worker for Azure Functions.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/matteocrippa/awesome-swift/blob/master/README.md/.github/CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors (⭐24k)](https://github.com/matteocrippa/awesome-swift/graphs/contributors); you rock!!

