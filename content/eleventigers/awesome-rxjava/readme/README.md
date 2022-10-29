# Awesome Rxjava Overview

Useful resources for working with RxJava

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/eleventigers/awesome-rxjava/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 eleventigers/awesome-rxjava](https://github.com/eleventigers/awesome-rxjava) · ⭐ 282 · 🏷️ Programming Languages

[ [Daily](/content/eleventigers/awesome-rxjava/README.md) / [Weekly](/content/eleventigers/awesome-rxjava/week/README.md) / Overview ]

---

# Awesome RxJava [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="http://reactivex.io/assets/Rx_Logo_S.png" align="right" width="100">](http://reactivex.io/)

> Useful resources for working with [RxJava](https://github.com/ReactiveX/RxJava)

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

## Bindings

*   [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Android specific bindings for RxJava.
*   [RxBinding](https://github.com/JakeWharton/RxBinding) - RxJava binding APIs for Android UI widgets from the platform and support libraries.
*   [rx-preferences](https://github.com/f2prateek/rx-preferences) - Reactive `SharedPreferences` for Android.
*   [RxPermissions](https://github.com/tbruyelle/RxPermissions) - Android M runtime permissions powered by RxJava.
*   [SQLBrite](https://github.com/square/sqlbrite) - A lightweight wrapper around SQLiteOpenHelper and ContentResolver which introduces reactive stream semantics to queries.
*   [Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) - Small library that wraps Google Play Service API in brilliant RxJava Observables reducing boilerplate to minimum.
*   [ReactiveNetwork](https://github.com/pwittchen/ReactiveNetwork) - Android library listening network connection state and change of the WiFi signal strength with RxJava Observables.
*   [ReactiveSensors](https://github.com/pwittchen/ReactiveSensors) - Android library monitoring hardware sensors with RxJava Observables.
*   [RxPalette](https://github.com/hzsweers/RxPalette) - RxJava bindings for the Palette library on Android.
*   [rxjava-jdbc](https://github.com/davidmoten/rxjava-jdbc) - Efficient execution and functional composition of database calls using jdbc and RxJava Observables.
*   [rxjava-file](https://github.com/davidmoten/rxjava-file) - RxJava observables for files including NIO events.
*   [RxTuples](https://github.com/pakoito/RxTuples) - Simple tuples to use with RxJava.
*   [RxAnimationBinding](https://github.com/blipinsk/RxAnimationBinding) - RxJava binding APIs for Android's animations.

## Utilities

*   [RxJavaAsyncUtil](https://github.com/ReactiveX/RxJavaAsyncUtil) - Async utilities for RxJava.
*   [RxJavaJoins](https://github.com/ReactiveX/RxJavaJoins) - Joins operators for RxJava.
*   [RxJavaMath](https://github.com/ReactiveX/RxJavaMath) - Math operators for RxJava.
*   [RxJavaString](https://github.com/ReactiveX/RxJavaString) -
    String and Byte operators for RxJava.
*   [RxJavaComputationExpressions](https://github.com/ReactiveX/RxJavaComputationExpressions) - Computation expressions for RxJava.
*   [rxjava-extras](https://github.com/davidmoten/rxjava-extras) - Utilities for use with RxJava.
*   [RxActions](https://github.com/pakoito/RxActions) - Simple ActionN composition to use with RxJava.
*   [RxRelay](https://github.com/JakeWharton/RxRelay) - RxJava types that are both an Observable and an Action1.
*   [Frodo](https://github.com/android10/frodo) - Android Library for Logging RxJava Observables and Subscribers.
*   [RxPartialApplication](https://github.com/pakoito/RxPartialApplication) - Simple partial application for FuncN and ActionN on RxJava.
*   [RxCurrying](https://github.com/pakoito/RxCurrying) - Simple currying for FuncN and ActionN on RxJava.
*   [RxEither](https://github.com/eleventigers/rxeither) - Either type for RxJava.
*   [RxReplayingShare](https://github.com/JakeWharton/RxReplayingShare) - An RxJava transformer which combines replay(1), publish(), and refCount() operators.
*   [RxFunctions](https://github.com/pakoito/RxFunctions) - Advanced Function composition to use with RxJava.
*   [rxlint](https://bitbucket.org/littlerobots/rxlint) - An Android lint rule for RxJava code.
*   [RxComprehensions](https://github.com/pakoito/RxComprehensions) - Reduce boilerplate in RxJava by abstracting chained flatMaps, concatMaps and switchMaps.

## Testing

*   [assertj-rx](https://github.com/ribot/assertj-rx) - AssertJ assertions for RxJava Observables.
*   [rxpresso](https://github.com/novoda/rxpresso) - Easy Espresso UI testing for Android applications using RxJava.

## Guides

*   [RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) - Learning RxJava for Android by example.
*   [Intro-To-RxJava](https://github.com/Froussios/Intro-To-RxJava) - An extensive tutorial on RxJava.

## Articles

*   [Rx glitches aren't actually a problem](http://staltz.com/rx-glitches-arent-actually-a-problem.html) - Glitches are temporary inconsistencies emitted by Observables. André Staltz looks at why it's not really a problem.
*   [RxJava's repeatWhen and retryWhen, explained](http://blog.danlew.net/2016/01/25/rxjavas-repeatwhen-and-retrywhen-explained/) - `repeatWhen` and `retryWhen` are fairly baffling at first glance. Dan Lew explains the operators in depth.
*   [RxJava - The Problem with Subjects](http://tomstechnicalblog.blogspot.co.uk/2016/03/rxjava-problem-with-subjects.html) - Thomas Nield explains why `Subject` is not a panacea.

## Tools

*   [RxMarbles](http://rxmarbles.com/) - Interactive diagrams of Rx Observables.

## Community

*   [Google Group](http://groups.google.com/d/forum/rxjava)
*   [StackOverflow](http://stackoverflow.com/search?q=rx-java)
*   [`@RxJava` on Twitter](http://twitter.com/RxJava)
*   [`ReactiveX/RxJava` on Gitter](https://gitter.im/ReactiveX/RxJava)
*   [GitHub Issues](https://github.com/ReactiveX/RxJava/issues)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jokubas Dargis](http://jokubasdargis.net/) has waived all copyright and related or neighboring rights to this work.

