# Awesome Swift Playgrounds Overview

A List of Awesome Swift Playgrounds

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/uraimo/Awesome-Swift-Playgrounds/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 uraimo/Awesome-Swift-Playgrounds](https://github.com/uraimo/Awesome-Swift-Playgrounds) · ⭐ 3.8K · 🏷️ Programming Languages

[ [Daily](/content/uraimo/Awesome-Swift-Playgrounds/README.md) / [Weekly](/content/uraimo/Awesome-Swift-Playgrounds/week/README.md) / Overview ]

---

# Awesome Swift Playgrounds [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)  ![155 playgrounds](https://img.shields.io/badge/Playgrounds:-155-orange.svg)

> A curated list of awesome Swift playgrounds.

### Contributing

Please take a quick look at the [contribution guidelines (⭐3.8k)](https://github.com/uraimo/awesome-swift-playgrounds/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors (⭐3.8k)](https://github.com/uraimo/awesome-swift-playgrounds/graphs/contributors); you rock!

If you see a playground here that does not work anymore with the current release of Xcode or is not a good fit, please submit a pull request to improve this file or consider updating it, thank you!

### Downloading all the playgrounds

Unless otherwise indicated, all playgrounds are compatible with Swift 3.

All the playgrounds are available as submodules in the `playgrounds/` directory, to download them all in one go, just clone this repository with `git clone --recursive https://github.com/uraimo/Awesome-Swift-Playgrounds.git` or execute `git submodule update --init` after you have cloned the repository the usual way.

Apple's playgrounds distributed as zip archives have to be downloaded manually.

### Tags

🌟 = My personal favorites

🍁 = Swift 4+ Playground

⏳ = Pre-Swift 3 Playground

### Contents

*   [PlaygroundBooks](#playgroundbooks)
*   [Learning Swift](#learning-swift)
*   [Learning Swift: Advanced Topics](#learning-swift-advanced-topics)
    *   [Design Patterns](#design-patterns)
    *   [Protocol Oriented Programming](#protocol-oriented-programming)
    *   [Functional Reactive Programming](#functional-reactive-programming)
*   [Apple's Playgrounds](#apples-playgrounds)
*   [WWDC Students Submissions](#wwdc-students-submissions)
*   [Playgrounds about Playgrounds](#playgrounds-about-playgrounds)
*   [Playgrounds from Playgroundbooks](#playgrounds-from-playgroundbooks)
*   [Theoretical Computer Science](#theoretical-computer-science)
    *   [Algorithms and Data Structures](#algorithms-and-data-structures)
    *   [Languages](#languages)
    *   [Machine Learning](#machine-learning)
*   [UIKit And Graphics](#uikit-and-graphics)
    *   [Core Image](#core-image)
    *   [Metal](#metal)
    *   [Animations](#animations)
    *   [SpriteKit](#spritekit)
*   [Audio](#audio)
*   [Mathematics](#mathematics)
*   [Libraries and APIs](#libraries-and-apis)
*   [Playground sets](#playground-sets)
*   [Miscellaneous](#miscellaneous)

## PlaygroundBooks

*Playgrounds that can be run on your iPad*

*   [Guilloche Pattern Playground Book (⭐16)](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁
*   [Accessibility (⭐5)](https://github.com/xReee/wwdc2018) - Accessibility for iOS developers. 🍁
*   [TJBot Playground (⭐33)](https://github.com/jweisz/tjbot-playground) - Swift Playground for interacting with IBM's TJBot. 🍁
*   [Tree Trouble Playbook (⭐22)](https://github.com/joelrorseth/Tree-Trouble) - An interactive Swift Playground Book about Binary Search Trees.
*   [Auto Pong (⭐12)](https://github.com/cardoso/AutoPong) - A tutorial to implement a pong based on a simple AI.
*   [Neural Network Playground (⭐378)](https://github.com/hetelek/Neural-Network-Playground) - A neural network Swift playground, with no third party dependencies.
*   [Window Manager Playground (⭐40)](https://github.com/steventroughtonsmith/windowmanager-playgroundbook) - Playground for an experimental window manager.
*   [AudioKit Playground Book (⭐188)](https://github.com/audiokit/Playgrounds) - A set of playgrounds using AudioKit designed for the iPad Playgrounds app.
*   [Numsw (⭐132)](https://github.com/sonsongithub/numsw) - A swift playground book that mimics some of the features of numpy and jupyter notebook.
*   [File Browser Playground (⭐203)](https://github.com/steventroughtonsmith/files-playgroundbook) - Simple File Browser for Swift Playgrounds on iOS.
*   [Geometry with Swift (⭐8)](https://github.com/dbbudd/Geometry-Swift-PlaygroundBook) - In this course your students will learn the fundamentals of Swift 3 programming, using geometry as their context for learning.
*   [Image Filtering (⭐77)](https://github.com/lennet/image-filtering) - A Swift playgroundbook about Image Filtering. 🍁🌟
*   [Spacetime Rhapsody (⭐22)](https://github.com/hollisliu/Spacetime-Rhapsody) - A Swift Playground visualizing gravity based on Einstein's Theory of General Relativity. 🌟
*   [Neural Network (⭐57)](https://github.com/lennet/neuralnetwork) - A Swift PlaygroundBook about Neural Networks. 🍁
*   [coreml-playground (⭐40)](https://github.com/kkk669/coreml-playground) - Core ML examples for Swift Playgrounds. 🍁
*   [SF Symbols Viewer (⭐14)](https://github.com/kkk669/SF-Symbols-Viewer) - An SF Symbols Viewer for Swift Playgrounds. 🍁
*   [jscore-playground (⭐17)](https://github.com/kkk669/jscore-playground) - A JavaScript REPL using JavaScriptCore. 🍁
*   [Accessible Reality (⭐23)](https://github.com/aheze/AccessibleReality) - for learning the basics of ARKit through interactive lessons. 🍁

## Learning Swift

*Some interesting playgrounds to learn Swift*

*   [What's new in Swift 4 (⭐1.8k)](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showing off the new features in Swift 4.0. 🍁 🌟
*   [What's new in Swift 4.2 (⭐879)](https://github.com/ole/whats-new-in-swift-4-2) - An Xcode playground showing off the new features in Swift 4.2. 🍁 🌟
*   [Codable Playground (⭐16)](https://github.com/filip-zielinski/CodablePlayground) - Playground that demonstrates advanced uses of Codable. 🍁
*   [Generics In Swift](https://github.com/LukeSkywalker55/Generics-In-Swift) - Playground that explains generics. 🍁
*   [Swift String Cheat Sheet (⭐58)](https://github.com/kharrison/Playground-Strings) - A quick guide to using Strings with Swift. 🍁
*   [About Swift (⭐73)](https://github.com/NicolaLancellotti-About/About-Swift) - A playground about Swift language.  🍁
*   [The Swift Programming Language Playgrounds (⭐218)](https://github.com/danielpi/Swift-Playgrounds) - 40+ playgrounds, one for each chapter of Apple's Swift book. 🌟
*   [Swift Hack Pack (⭐20)](https://github.com/GuildSA/swift-hack-pack) - Collection of playgrounds that teaches Swift.
*   [The Swift Summary Book (⭐1.7k)](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language. 🌟
*   [Swifter Tips (⭐126)](https://github.com/swifter-tips/Playground) - Examples for every feature of the Swift language.
*   [MPCS51032 UChicago iOS Course (⭐7)](https://github.com/uchicago-mobi/mcps51032-2017-spring-playground) - Playgrounds from the 2017 Spring iOS course of the University of Chicago.

## Learning Swift: Advanced Topics

*Advanced topics, useful once you have mastered the basics of the language*

*   [A Swift Introduction to Core Data (⭐149)](https://github.com/andyshep/CoreDataPlaygrounds) - Learn Core Data experimenting directly in this playground. 🌟
*   [TDDSwiftPlayground (⭐53)](https://github.com/sshrpe/TDDSwiftPlayground) - Demonstration of using Swift Playgrounds in Test Driven Development with XCTest.
*   [Concurrency on iOS (⭐33)](https://github.com/sammyd/2017AtSwift_Concurrency) - Concurrency and Parallelism in iOS.
*   [Modern Core Data (⭐35)](https://github.com/dfreniche/modern-core-data-playground) - An introduction to Core Data.
*   [Swift DSL Example (⭐19)](https://github.com/cfdrake/swift-dsl-example) - Implementation of a DSL in Swift.
*   [Katan (⭐25)](https://github.com/marciok/katan) - A micro web server that replies "Hello world!" to every request, an example of how to use sockets in Swift.
*   [Swift Regular Expressions (⭐10)](https://github.com/ogulcan/SwiftRegEx) - A playground to learn regular expressions with Swift.
*   [Network Stack (⭐34)](https://github.com/AndrejKolar/NetworkStack) - Clean & simple Swift networking stack playground.
*   [Swiftly Typed Resources (⭐73)](https://github.com/jstart/Swiftly-Typed-Resources) - A playground showing how Swift makes Strings, Colors, Fonts, Images, etc easier to deal with. ⏳
*   [Swift KVO Closures (⭐11)](https://github.com/rectalogic/KVOPlayground) - Swift KVO playground. ⏳
*   [Swift Date Tutorial (⭐7)](https://github.com/liuyubobobo/Swift-NSDate-Tutorial) - Learn everythig about NSDate. ⏳
*   [Swift And C (⭐6)](https://github.com/MacMark/SwiftAndC) - Examples about using C with Swift. ⏳
*   [Swift Memory Management (⭐3)](https://github.com/ndethore/swift-memory-management) - How to avoid retain cycles, from [this post](http://detho.re/2016/01/21/writing-memory-efficient-swift-code/). ⏳

### Design Patterns

*   [The Principles of OOD in Swift 4 (⭐1.8k)](https://github.com/ochococo/OOD-Principles-In-Swift) - The Principles of OOD based on Uncle Bob articles.🍁
*   [Design Patterns Playground (⭐26)](https://github.com/edopelawi/DesignPatternsPlayground) - Learning GoF's Design Patterns in Swift 3.
*   [iOS Design Patterns (⭐128)](https://github.com/haxpor/ios-design-patterns) - Sample projects for MVC, MVP, MVVM, and VIPER.
*   [Design Patterns in Swift (⭐14k)](https://github.com/ochococo/Design-Patterns-In-Swift) - Design patterns in Swift 3.
*   [GOF Swift (⭐118)](https://github.com/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) - Learn all 23 Gang of Four patterns using Swift.

### Protocol Oriented Programming

*   [Swift Diagram Playgrounds (⭐269)](https://github.com/alskipp/Swift-Diagram-Playgrounds) - Adaptation of the Protocol-Oriented Programming in Swift talk from WWDC 2015.
*   [Swift Protocol Extensions (⭐20)](https://github.com/davidahouse/SwiftProtocolExtensions) - A playground to explore Protocol Extensions. ⏳
*   [Battleship Example (⭐12)](https://github.com/vichudson1/Battleship-POP-Example) - An example of how to use Protocol Oriented Programming with the battleship game. ⏳

### Functional Reactive Programming

*   [ReactiveCocoa Playground (⭐97)](https://github.com/nikita-leonov/ReactiveCocoaPlayground) - The easiest way to get a taste of ReactiveCocoa. ⏳
*   [Swift Reactive Playground (⭐27)](https://github.com/ColinEberhardt/SwiftReactivePlayground) - Companion to the article: ReactiveCocoa made Simple With Swift. ⏳

## Apple's Playgrounds

*Playgrounds from Apple, usually presented at some WWDC*

*   [Apple's Mandelbrot Playground (⭐22)](https://github.com/palmerc/Mandelbrot-Swift-Playground) - A playground with the mandelbrot fractal (updated to Swift 3 by @palmerc, @kemalenver).
*   [Interactive Newton's Cradle (⭐9)](https://github.com/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) - Apple's interactive playground of a Newton's Cradle where collisions and gravity are applyed with UIKit dynamics. 🌟 (updated to Swift 3 by @p-sun)
*   [Apple's Balloons Playground](https://developer.apple.com/swift/blog/downloads/Balloons.zip) - The balloons playground showed at WWDC14. ⏳
*   [Apple's Crustacean Playground](https://developer.apple.com/sample-code/wwdc/2015/downloads/Crustacean.zip) - Protocol-Oriented Programming with Value Types. ⏳
*   [Apple's Swift Standard Library Playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) - experiment with Swift standard library types and high-level concepts using visualizations and practical examples. ⏳

## WWDC Students Submissions

*Playgrounds submitted by students for the WWDC scholarship*

*   [2022 (⭐58)](https://github.com/wwdc/2022)
*   [2021 (⭐167)](https://github.com/wwdc/2021)
*   [2020 (⭐206)](https://github.com/wwdc/2020)
*   [2019 (⭐282)](https://github.com/wwdc/2019)
*   [2018 (⭐267)](https://github.com/wwdc/2018)
*   [2017 (⭐244)](https://github.com/wwdc/2017)
*   [2016 (⭐82)](https://github.com/wwdc/2016)
*   [2015 (⭐130)](https://github.com/wwdc/2015)
*   [2014 (⭐186)](https://github.com/wwdc/2014)

## Playgrounds about Playgrounds

*Playgrounds that describe what you can do with playgrounds*

*   [XCTest Playground (⭐52)](https://github.com/Liquidsoul/XCTestPlayground) - Better looking tests for playgrounds.
*   [Interactive Playground (⭐52)](https://github.com/dasdom/InteractivePlayground) - Exploring interactivity in Playgrounds.
*   [Mondrian (⭐3)](https://github.com/timbellay/Mondrian) - Make iOS app mockups in Swift 2.x playgrounds. ⏳

## Playgrounds from Playgroundbooks

*Playgrounds derived from iPad Swift Playgroundbooks*

*   [iPad Swift Playgrounds (⭐23)](https://github.com/kushtaneja/iPad_Swift_Playgrounds) - The sample playgroundbooks converted to playgrounds.

## Theoretical Computer Science

*   [Functional Debug View (⭐37)](https://github.com/tomquist/DebugView) - Playground to visualize functional programming with graphical sequences. 🍁 🌟
*   [OOP with Functions in Swift (⭐58)](https://github.com/iamleeg/OOPInFPInSwift) - Object-Oriented Programming in Functional Programming in Swift. 🍁
*   [Logician (⭐191)](https://github.com/mdiep/Logician) - Logic programming in Swift. 🌟
*   [Function Composition in Swift (⭐58)](https://github.com/ijoshsmith/function-composition-in-swift) - Exploration of function composition in Swift. 🌟
*   [Swift Adventures in Monad Land (⭐170)](https://github.com/alskipp/Swift-Adventures-In-Monad-Land) - Learn about monads.
*   [Functional Design Patterns (⭐5)](https://github.com/cmvicentehe/FunctionalProgrammingDesignPatterns) - A few functional programming concept and patterns.
*   [Learn about transducers (⭐79)](https://github.com/mbrandonw/learn-transducers-playground) - A little tutorial that explains transducers. ⏳
*   [Swift Functors, Applicatives, and Monads in Pictures (⭐67)](https://github.com/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) - Companion to the article: Swift Functors, Applicatves, and Monads in Pictures. ⏳
*   [Functors in Swift (⭐6)](https://github.com/mokagio/Swift-Functor-Introduction-Playground) - A playground to introduce Functors in Swift, and their practical usage. ⏳

### Algorithms and Data Structures

*Algorithms and data structures implemented in Swift*

*   [Animated Sorting Algorithms (⭐32)](https://github.com/p-sun/Animated-Sorting-Algorithms) - Swift 4 playgrounds to view and manipulate sorting algorithms.🍁
*   [Expressions (⭐398)](https://github.com/mpangburn/Expressions) - Arithmetic and logical expressions elegantly modeled and visualized using protocol-oriented binary trees.🍁
*   [Swift Algorithm Club (⭐27k)](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift with explanations. 🌟
*   [Sorting Experiments (⭐5)](https://github.com/adrfer/Sort) - Alluring experiments with sorting algorithms in Swift, sort of.
*   [Visual Binary Trees (⭐57)](https://github.com/akpw/VisualBinaryTrees) - Effortless visualization of arbitrary Binary Trees, along with their pluggable traversal implementations. 🌟
*   [Julia Fractal Playground (⭐254)](https://github.com/gongzhang/julia-set-playground#julia-set-playground) - A Swift playground that generates beautiful Julia set fractal images.
*   [A Star (⭐33)](https://github.com/Dev1an/A-Star) - Protocol oriented A\* pathfinding algorithm implementation in Swift 4.🍁
*   [DataStructures Playground (⭐15)](https://github.com/oliverfoggin/DataStructuresPlayground) - Data Structures and Algorithms in Swift. ⏳
*   [Swiftography (⭐8)](https://github.com/sketchytech/Swiftography) - Standard cryptographic algorithms in a Swift Playground. ⏳
*   [Algorithms Playground (⭐5)](https://github.com/ashokgelal/AlgorithmsPlayground) - Various algorithm implementation in Swift. ⏳
*   [The Jelly Bean Problem (⭐2)](https://github.com/kyleweiner/Jelly-Bean-Problem) - The Jelly Bean problem from Wait But Why. ⏳
*   [Euclidean Strings (⭐1)](https://github.com/modulusMathews/ReEuclid) - A playground leveraging ReSwift to generate Euclidean Strings. ⏳

### Languages

*Programming language interpreters implemented in Swift*

*   [Introduction to Compilers (⭐404)](https://github.com/ahoppen/introduction-to-compilers) - Great introduction to the inner workings of compilers. 🍁🌟
*   [Pascal Interpreter (⭐277)](https://github.com/igorkulman/SwiftPascalInterpreter) - Simple Swift interpreter for the Pascal language inspired by the Let’s Build A Simple Interpreter article series. 🍁
*   [Write your own language: Mu (⭐1.1k)](https://github.com/marciok/Mu) - A playground explaining how to create a tiny programming language named Mu. 🌟
*   [ASM Swift (⭐101)](https://github.com/NSExceptional/ASM-Swift) - A playground for learning Assembly language through Swift. 🌟
*   [Let's build a compiler in Swift (⭐160)](https://github.com/mkchoi212/LBAC-Swift) - Let's Build a Compiler by Jack Crenshaw translated to Swift Playgrounds. 🌟
*   [Register VM (⭐5)](https://github.com/brianhill/register-vm-in-swift) - A register-based VM in a Swift playground. 🌟 ⏳
*   [Turtle Playground (⭐127)](https://github.com/dimsumthinking/TurtlePlayground) - A playground with Logo-like commands. 🌟 ⏳
*   [Swift Brainfuck (⭐8)](https://github.com/xavieryao/Swift-Brainfuck) - Brainfuck interpreter written in Swift using Playground. ⏳

### Machine Learning

*   [Emoji Intelligence (⭐1.3k)](https://github.com/BilalReffas/EmojiIntelligence) - Neural Network built in Apple Playground using Swift. 🌟

## UIKit And Graphics

*A list of playgrounds that demostrate various aspect of UIKit and other graphical frameworks*

*   [UIStackView Playground (⭐324)](https://github.com/dasdom/UIStackViewPlayground) - Interesting examples of use of UIStackViews.🌟
*   [Bezier Path Playgrounds (⭐26)](https://github.com/DigitalLeaves/BezierPathPlaygrounds) - Some playgrounds to better understand UIBezierPaths.
*   [UIKit playground (⭐43)](https://github.com/ralfebert/uikit-playground) - Playgrounds to experiment interactively with UIKit views.
*   [UIDynamic Playground (⭐4)](https://github.com/andresbrun/UIDynamicsPlayground) - Multiple Playgrounds using almost every behaviour of UIDynamic.
*   [WWDC16 Typography (⭐7)](https://github.com/tototti/wwdc16_typography_playground) 🇯🇵 - Draw a logo or any text with the WWDC16 ASCII texture.
*   [Animated GIF Playground (⭐1)](https://github.com/danielrhammond/GIF-Playground) - Swift playground for generating animated GIFs.
*   [RPClarity (⭐41)](https://github.com/RobotsAndPencils/RPClarity) - Shows a technique for blurring an image behind the characters behind one or more UILabels. ⏳
*   [Swift Clock (⭐28)](https://github.com/nickoneill/swiftclock) - An animated clock in a swift playground. ⏳
*   [WatchKit Asset Playground (⭐8)](https://github.com/cwimberger/WatchKitAssetPlayground) - A swift playground for creating awesome animations for your WatchKit Apps. ⏳
*   [Swift 2.0 Protocol Extension Example (⭐38)](https://github.com/jhurray/Swift2-Protocol-Extension-Example) - Showing how to use Swift2 protocol extensions to render errors in UIViews and UIViewControllers without subclassing or creating classes. ⏳
*   [Tinting (⭐0)](https://github.com/Jesse-calkin/tinting) - A small playground to demonstrate image tinting in UIKit. ⏳
*   [Ray tracing Playground (⭐16)](https://github.com/mhorga/Raytracing) - A playground and a series of articles on ray tracing, see also part [2 (⭐6)](https://github.com/mhorga/Raytracing2), [3 (⭐7)](https://github.com/mhorga/Raytracing3), [4 (⭐3)](https://github.com/mhorga/Raytracing4), [5 (⭐5)](https://github.com/mhorga/Raytracing5) 🌟 ⏳
*   [WWDC16 Logo Playground](https://github.com/krutarth/WWDC16Logo) - Drawing the WWDC16 logo in a playground. ⏳

### Core Image

*   [Interpolation Playground (⭐61)](https://github.com/FlexMonkey/Interpolation-Playground-) - Playground demonstrating lerp, smooth step, Catcall-Rom and others! ⏳
*   [CoreImage for Swift Playgrounds (⭐86)](https://github.com/FlexMonkey/CoreImageForSwiftPlaygrounds) - Growing collection of CoreImage playgrounds from the upcoming book "CoreImage For Swift". 🌟 ⏳
*   [Image Processor (⭐8)](https://github.com/mortenbrudvik/ImageProcessor) - Implementing different image filter algorithms. ⏳

### Metal

*   [Metalbrot (⭐82)](https://github.com/jtbandes/metalbrot-playground) - Interactive playground that draws the Mandelbrot fractal with Metal. 🌟
*   [METAL Playground (⭐52)](https://github.com/haawa799/METAL_Playground) - Apple Metal framework playground. 🌟 ⏳

### Animations

*   [Core Animation Swift Playgrounds (⭐34)](https://github.com/rmirabelli/CoreAnimationSwiftPlaygrounds) - A set of interesting Core Animation playgounds.
*   [UIViewPropertyAnimator Playground (⭐37)](https://github.com/mathewsanders/Scrubber) - Playground demonstrating UIViewPropertyAnimator.
*   [WWDC Crowd Simulator 2017 (⭐33)](https://github.com/neilsardesai/WWDC-Crowd-Simulator-2017) - A SpriteKit experiment to simulate the WWDC2017 logo crowd.
*   [Duet-Inspired Trail Effect (⭐25)](https://github.com/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) - How to get a Duet style trailing effect in SpriteKit.
*   [Additive Animations (⭐34)](https://github.com/d-ronnqvist/Additive-Animations-Playground) - Experiment with multiple additive animations in Core Animation. ⏳
*   [Core Animation Playground (⭐9)](https://github.com/knightsc/CoreAnimationPlayground) - Companion to Apple's Core Animation Programming Guide. ⏳
*   [Core Animation Timing (⭐1)](https://github.com/Kentzo/CoreAnimationTiming) - Playground demonstrating effects of CAMediaTiming properties. 🍁

### SpriteKit

*   [SceneKit ARKit Demo (⭐47)](https://github.com/mhanlon/ARKitDemoPlayground) - The Xcode 9 ARKit SpriteKit demo as a playground.🍁
*   [SpriteKit Swift 3 (⭐7)](https://github.com/MacMeDan/SpriteKitCollisions) - Playground for exploring Sprite Kit.
*   [SpriteKit Collisions (⭐32)](https://github.com/jaredmpayne/SpriteKitCollisionsPlayground) - Demonstrates how to perform physics collision detection using Swift and SpriteKit. ⏳
*   [SceneKit Examples (⭐19)](https://github.com/UCh/swift-scene-kit-playgrounds) - Experiment with SceneKit and Swift. ⏳
*   [Astronomy (⭐24)](https://github.com/cl7/Astronomy) - A 3D earth model written in swift playground using SceneKit.

## Audio

*Sounds and music*

*   [Bach Playground (⭐3)](https://github.com/dreamwieber/BachPlayground) - A Simple Swift Playground that plays a brief piece by Bach with AVAudioEngine and AVMIDIPlayer.
*   [PlayerNode Playground (⭐3)](https://github.com/genedelisa/PlayerNodePlayground) - Playground using AVAudioEngine with a playernode and effects to play an audio file. 🌟
*   [Miles (⭐31)](https://github.com/lalomts/Miles) - A Swift Playground that creates jazz improvisations in any key using AudioToolbox and AVFoundation.

## Mathematics

*Live math with playgrounds*

*   [Guilloche Pattern Playground Book (⭐16)](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁
*   [Lindenmayer Systems (⭐11)](https://github.com/henrinormak/lindenmayer) - A Swift playground exploring Lindemayer systems.
*   [Swift Natural Numbers (⭐3)](https://github.com/jakebromberg/Swift-Natural-Numbers) - A playground for implementing the natural numbers and more concepts in number theory.
*   [Polydoxical (⭐0)](https://github.com/kirkbyo/Polydoxical) - Interactive playground to experiment with roulettes and polygons.
*   [Abstract Algebra (⭐190)](https://github.com/taketo1024/SwiftyMath) - Abstract algebra concepts implemented in Swift.
*   [Swift Accelerate (⭐111)](https://github.com/haginile/SwiftAccelerate) - Using the Accelerate framework and Swift for Linear Algebra. ⏳
*   [Swifty Mathematics (⭐3)](https://github.com/DylanModesitt/swiftyMathematics) - A collection of swift playground about mathematics. ⏳
*   [Numerical Algorithms](https://www.raywenderlich.com/99559/numeric-algorithms-using-playgrounds) - Numerical argorithms playground from Ray Wenderlich. ⏳

## Libraries and APIs

*Library tutorials, in a playground*

*   [AudioKit Playgrounds](https://audiokit.io/playgrounds/) - 130+ Audio synthesis, processing, playback, and analysis playgrounds with AudioKit.
*   [AIToolbox (⭐774)](https://github.com/KevinCoble/AIToolbox/tree/master/Playgrounds) - A set of playgrounds showing machine learning algorithms, all implemented with pieces of the AIToolbox framework code.
*   [Cognitive Service APIs (⭐56)](https://github.com/codePrincess/playgrounds) - Get started with the Microsoft Cognitive Services APIs.
*   [Rx Playground (⭐6)](https://github.com/sgr-ksmt/RxPlayground) - A playground with RxSwift examples.

## Playground Sets

*Sets of playgrounds about various topics*

*   [Parks And Recreation (⭐170)](https://github.com/zwaldowski/ParksAndRecreation) - Great collection of interesting playgrounds, for fun and for profit. 🍁🌟
*   [URaimo's Playgrounds (⭐140)](https://github.com/uraimo/Swift-Playgrounds) - My playgrounds, various topics. 🍁
*   [Public Extensions (⭐299)](https://github.com/Jasdev/Public-Extension) - A set of useful extensions from [@PublicExtension](https://twitter.com/publicextension). 🌟
*   [ManuelCarlos's Playgrouds](https://github.com/manuelCarlos/Swift-Playgrounds) - Various playgrounds.
*   [Mgrebenets's Playgrounds (⭐9)](https://github.com/mgrebenets/playgrounds) - Various playgrounds.c 🌟
*   [Cocoa With Love Playgrounds (⭐89)](https://github.com/mattgallagher/CocoaWithLovePlaygrounds) - Playground versions of select articles from Cocoa with Love.  🌟
*   [Sketchytech's Playgrounds (⭐7)](https://github.com/sketchytech/SwiftPlaygrounds) - Various Playgrounds. 🌟 ⏳
*   [Swift fun playgrounds (⭐8)](https://github.com/madbat/Swift-fun-playgrounds) - A few playgrounds to showcase Swift peculiar features. ⏳
*   [BradLarson's Playgrounds (⭐20)](https://github.com/BradLarson/PersonalSwiftPlaygrounds) - Various playgrounds. ⏳
*   [Dmikusa's Playgrounds (⭐15)](https://github.com/dmikusa/swift_playgrounds) - Playgrounds that show basic Swift, JSON parsing, sending HTTP requests and basic file IO. ⏳
*   [Cananito's Playgrounds (⭐1)](https://github.com/Cananito/Playgrounds) - Various playgrounds. ⏳
*   [Uberbruns's Playgrounds (⭐4)](https://github.com/uberbruns/SwiftPlaygrounds) - Various playgrounds. ⏳

## Miscellaneous

*What doesn't fit anywhere else, but still awesome*

*   [Rubik's Cube (⭐17)](https://github.com/codelynx/CoreRubiksCube) - Implementing basic model and behavior of Rubic's Cube in Swift. 🍁
*   [Icon Creator (⭐37)](https://github.com/tnantoka/IconCreator) - Create app icons on Swift playground.
*   [2048 Playground (⭐40)](https://github.com/robin/2048_Playground) - The 2048 game implemented with a playground.
*   [SwiftShell (⭐19)](https://github.com/JustinJiaDev/SwiftShell) - Bash shell in a playground.
*   [LaunchPad Playground (⭐5)](https://github.com/Juniorlimaivd/LaunchPad-Playground) - A playground that simulates a real LaunchPad for making music.
*   [Super Maze (⭐8)](https://github.com/W00dL3cs/Super-Maze) - A programmatic maze generator and solver.
*   [Tic Tac Toe (⭐7)](https://github.com/aabosh/Tic-Tac-Toe) - Tic tac toe in a playground.
*   [Pixel Art Maker (⭐94)](https://github.com/BenEmdon/PixelArtMaker) - A playground where you can make pixel art.
*   [SwiftCoin (⭐32)](https://github.com/Thomvis/Swiftcoin) - A simplistic blockchain & cryptocurrency in a playground.
*   [SentimentlySwift (⭐12)](https://github.com/benbahrenburg/SentimentlySwift) - Sentiment analysis in Swift.
*   [SwiftChain](https://github.com/gg2001/SwiftChain) - Simple Cryptocurrency in a Swift Playground.
*   [Game Boards (⭐179)](https://github.com/joalbright/Gameboard) - Chess, checkers, tic-tac-toe, sudoku and many others in playground. 🌟 ⏳
*   [StarWars Seals (⭐3)](https://github.com/jeremyconkin/StarWarsSeals) - Emblems from Star Wars in Swift playgrounds via CoreGraphics and UIViews. ⏳
*   [SwiftFiles (⭐39)](https://github.com/sketchytech/SwiftFiles) - Save, Load and Delete files easily from within a Swift playground. ⏳
*   [Earth photos (⭐6)](https://github.com/jtbandes/DSCOVR.playground) - A slideshow of Earth photos taken by DSCOVR/EPIC. 🌟 ⏳

