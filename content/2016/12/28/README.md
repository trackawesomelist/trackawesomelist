# Awesome List Updates on Dec 28, 2016

2 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Qt](/content/JesseTG/awesome-qt/README.md)

### Communities / Official

*   [IRC](https://webchat.freenode.net/?channels=%23qt%2C%23qt-quick%2C%23qt-creator%2C%23qt-chat) - For real-time chat with other Qt developers and users.  The most popular channels are on Freenode, and include `#qt`, `#qt-quick`, `#qt-creator`, and `#qt-chat`.
    *   For a full list of Qt-related IRC channels, see [here](https://wiki.qt.io/Online_Communities#IRC_channels).
    *   Note that the linked webchat client is *not* a part of the Qt project, and is provided by the author of this list for convenience only.  These channels can be accessed through any IRC client.

### Tools / Official Tools

*   [Qt Installer Framework](https://doc.qt.io/qtinstallerframework) [:octocat: (⭐147)](https://github.com/qtproject/installer-framework) - Nobody seems to talk about this, but Qt also provides a way to write an installer for your application.  Does not support creation of macOS disk images, app bundles, or Linux packages, so be mindful of that when considering your project's distribution.
    *   [`macdeployqt`](https://doc.qt.io/qt-5/osx-deployment.html) [:octocat: (⭐125)](https://github.com/qt/qttools/tree/dev/src/macdeployqt) - Generates macOS application bundles for Qt projects.
*   [qmake](https://doc.qt.io/qt-5/qmake-manual.html) [:octocat: (⭐1.8k)](https://github.com/qt/qtbase/tree/dev/qmake) - The bundled build system designed for Qt, though it can be used for non-Qt projects.
*   `qtdiag` [:octocat: (⭐125)](https://github.com/qt/qttools/tree/dev/src/qtdiag) - Command-line tool that prints out a lot of information pertaining to both your Qt installation and your system in general.  No link because there's no dedicated web page; just run `qtdiag` on the command line.  Excellent for troubleshooting.
*   `qmleasing` [:octocat: (⭐146)](https://github.com/qt/qtdeclarative/tree/dev/tools/qmleasing) - Lets you make easing curves suitable for QML, though if you understand the underlying math there's no reason you couldn't use the resulting numbers elsewhere.

### Tools / Third-Party Tools

*   [CMake](https://doc.qt.io/qt-5/cmake-manual.html) [:octocat: (⭐5.2k)](https://github.com/Kitware/CMake) - General C++ build tool that happens to have great Qt support.
*   [moc-ng (⭐185)](https://github.com/woboq/moc-ng) [:octocat: (⭐185)](https://github.com/woboq/moc-ng) - Alternative implementation of `moc` that's binary-compatible with Qt's version.
*   [Qt-Inspector (⭐350)](https://github.com/robertknight/Qt-Inspector) [:octocat: (⭐350)](https://github.com/robertknight/Qt-Inspector) - Inspection tool with similar goals to GammaRay, though much simpler.

### Bindings in Other Languages / Third-Party Tools

*   [Mono/.NET languages (via QtSharp) (⭐557)](https://github.com/ddobrev/QtSharp) [:octocat: (⭐557)](https://github.com/ddobrev/QtSharp) - Experimental wrapper for Qt that allows it to be used by .NET-based languages such as C#.  Young, but active.

### Libraries / Integrations

*   [QScintilla](https://riverbankcomputing.com/software/qscintilla) [:package:](https://www.riverbankcomputing.com/software/qscintilla/download) - Absurdly versatile and customizable text editor widget that provides syntax highlighting, code completion, code folding, recordable macros, and *much* more.  Built around [Scintilla](http://www.scintilla.org).  Created by the same company that developed [PyQt](https://riverbankcomputing.com/software/pyqt).

### Libraries / New Functionality

*   [DOtherSide (⭐175)](https://github.com/filcuc/DOtherSide) [:octocat: (⭐175)](https://github.com/filcuc/DOtherSide) - Binding for QML in C, primarily designed as an API for *other* languages to support QML.
*   [Marble](https://marble.kde.org) [:package:](https://cgit.kde.org/marble.git) - Virtual globe and map that can be used standalone or embedded within other applications.
*   [QNodeView (⭐186)](https://github.com/gwihlidal/QNodeView) [:octocat: (⭐186)](https://github.com/gwihlidal/QNodeView) - Widget that lets you create and edit nodes in a graph similar to the kind provided by Unreal Engine, Substance Designer, or PureData.
*   [QtAV](http://www.qtav.org) [:octocat: (⭐3.3k)](https://github.com/wang-bin/QtAV) - Actively developed multimedia framework.
*   [Qtilities](https://jpnaude.github.io/Qtilities) [:octocat: (⭐123)](https://github.com/JPNaude/Qtilities) - Powerful set of libraries that provide GUI, logging, testing, configuration, and project functionality (among other things) for your application.
*   [QtitanChart](http://www.devmachines.com/qtitanchart-overview) - Chart generation framework.  Commercial.

### Books / New Functionality

*   [Game Programming Using Qt: Beginner's Guide](https://www.packtpub.com/game-development/game-programming-using-qt) by Witold Wysota and Lorenz Haas - Good place to start learning how to program games with QML.
*   [Application Development with Qt Creator - 2nd Edition](https://www.packtpub.com/application-development/application-development-qt-creator-second-edition), by [Ray Rischpater](http://www.lothlorien.com/kf6gpe) - Beginner's guide to Qt, with a lot of focus on Qt Creator and its associated tools.
*   [Qt 5 Blueprints](https://www.packtpub.com/application-development/qt-5-blueprints), by [Symeon Huang](https://github.com/librehat) - Seems to be about the overall structure of a Qt project.
*   [Mastering Qt 5](https://www.packtpub.com/application-development/mastering-qt-5), by [Guillaume Lazar](https://github.com/GuillaumeLazar) and [Robin Penea](https://github.com/synapticvoid) [:octocat: (⭐189)](https://github.com/PacktPublishing/Mastering-Qt-5) - Not your daddy's Qt.  Tips and tricks for the experienced.  The source code used in the book is available for free.
*   [Qt5 Cadaques](https://qmlbook.github.io) [:octocat: (⭐2.4k)](https://github.com/qmlbook/qmlbook) - Free book that focuses on QML, named for this town in northeastern Spain that the authors vacationed to once.

### Software that Uses Qt / New Functionality

*   [KDE](https://www.kde.org) [:octocat:](https://github.com/KDE) - One of the most popular desktop environments for Linux.
*   [RUBE](https://www.iforce2d.net/rube) - Level design tool for any game that uses the Box2D physics engine.
*   [Yabause](https://yabause.org) [:octocat: (⭐319)](https://github.com/Yabause/yabause) - Sega Saturn emulator.

## [2. Awesome Network Analysis](/content/briatte/awesome-network-analysis/README.md)

### Professional Groups / Research Groups (USA)

*   [Northeastern University Center for Complex Network Research](https://www.northeastern.edu/research/centers/center-for-complex-network-research-ccnr/) - Led by Albert-László Barabási.

### Review Articles / Biological, Ecological and Disease Networks

*   [Interactome Networks and Human Disease](http://barabasi.com/f/326.pdf) (*Cell*, 2011).
*   [Network Biology: Understanding the Cell’s Functional Organization](http://barabasi.com/f/147.pdf) - Accessible introduction to (cellular) network analysis (*Nature Reviews Genetics*, 2004).
*   [Network Medicine: A Network-based Approach to Human Disease](http://barabasi.com/f/320.pdf) (*Nature Review Genetics*, 2011).

### Review Articles / Complex and Multilayer Networks

*   [Statistical Mechanics of Complex Networks](http://barabasi.com/f/103.pdf) (*Reviews of Modern Physics*, 2002).

### Selected Papers / Social, Economic and Political Networks

*   [Scale-Free Networks](http://barabasi.com/f/124.pdf), by Albert-László Barabási and Eric Bonabeau - Early, accessible formulation of the “networks are everywhere” argument (*Scientific American*, 2003).

---

- Prev: [Dec 29, 2016](/content/2016/12/29/README.md)
- Next: [Dec 27, 2016](/content/2016/12/27/README.md)