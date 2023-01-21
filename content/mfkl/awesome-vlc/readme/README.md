# Awesome Vlc Overview

👻 A curated list of awesome VLC and LibVLC resources. 

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mfkl/awesome-vlc/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 mfkl/awesome-vlc](https://github.com/mfkl/awesome-vlc) · ⭐ 66 · 🏷️ Media

[ [Daily](/content/mfkl/awesome-vlc/README.md) / [Weekly](/content/mfkl/awesome-vlc/week/README.md) / Overview ]

---

# Awesome VLC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://cdn.worldvectorlogo.com/logos/vlc.svg" align="right" alt="VLC" width="128">](https://github.com/mfkl/awesome-vlc)

> [VLC](https://www.videolan.org/vlc/) is a free and open source cross-platform multimedia player and framework that plays most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols.

This is a list of awesome resources about VLC and LibVLC.

## Contents

*   [Docs](#docs)
*   [VLC native plugins](#vlc-native-plugins)
*   [VLC lua extensions](#vlc-lua-extensions)
*   [Apps](#apps)
*   [Bindings](#bindings)
*   [Tutorials](#tutorials)
*   [Ebook](#ebook)
*   [Community](#community)

## Docs

*   [videolan.org](https://www.videolan.org/) - Where it all starts.
*   [LibVLC API docs](https://videolan.videolan.me/vlc/group__libvlc.html) - Docs for LibVLC's engine. C APIs.
*   [Wiki](https://wiki.videolan.org/) - Lots of great info on here.
*   [Code & Bug tracker](https://code.videolan.org/videolan/vlc/-/issues) - Recently moved from Trac, contains a lot of valuable info on bugs and feature requests.
*   [CLI flags](https://wiki.videolan.org/VLC_command-line_help) - A comprehensive list of all VLC commandline flags. Really useful for searching random flags that you come across in the wild.

## VLC native plugins

*   [vlc-pause-click-plugin (⭐674)](https://github.com/nurupo/vlc-pause-click-plugin) - Plugin for VLC that pauses/plays video on mouse click.
*   [vlc-tip-plugin (⭐43)](https://github.com/aklexel/vlc-tip-plugin) - TIP (translate it, please) is a plugin for VLC media player that helps you to study languages by watching videos.
*   [vlc-bittorrent (⭐345)](https://github.com/johang/vlc-bittorrent) - A bittorrent plugin for VLC.
*   [vlc-plugin-marker (⭐4)](https://github.com/nemosharma6/vlc-plugin-marker) - The marker plugin provides you the ability to mark important sections of a video. These sections can be viewed later without the need to search for it in the entire video.
*   [vlc-win10smtc (⭐13)](https://github.com/spmn/vlc-win10smtc) - Plugin that integrates VLC Media Player with Windows 10 System Media Transport Controls (SMTC).
*   [vlc-mixer (⭐0)](https://github.com/lachie/vlc-mixer) - Audio mixer VLC plugin written in Zig.

## VLC lua extensions

*   [VideoLAN addons website](https://addons.videolan.org/browse/) - VideoLAN addons website.
*   [vlc-delete (⭐40)](https://github.com/surrim/vlc-delete) - VLC extension to remove videos from the hard disk.
*   [TraktForVLC (⭐294)](https://github.com/XaF/TraktForVLC) - Automatically trakt.tv what you're watching on VLC.
*   [playlist-youtube-vlc (⭐0)](https://github.com/Abstraxt-AA/playlist-youtube-vlc) - Lua plugin to parse Youtube playlists.
*   [vlc-super-skipper (⭐6)](https://github.com/Trevelopment/vlc-super-skipper) - Automatically Skip Opening and Ending Sequences.

## Apps

*   [VLC desktop](https://code.videolan.org/videolan/vlc) - The original Desktop app running on Linux/Windows (Qt) and macOS (Cocoa).
*   [VLC iOS](https://code.videolan.org/videolan/vlc-ios) - VLC for iOS is the official port of VLC on the iOS/tvOS platforms.
*   [VLC Android](https://code.videolan.org/videolan/vlc-android) - VLC for Android, Android TV and ChromeOS.
*   [VLC Benchmark (Beta)](https://code.videolan.org/videolan/vlc-bench) - Video decoding and rendering benchmark tool, based on VLC.

## Bindings

*   [VLCKit](https://code.videolan.org/videolan/VLCKit) - The libvlc bindings for macOS, iOS, iPadOS and tvOS in Objective-C.
*   [libvlcjni](https://code.videolan.org/videolan/vlc-android/-/tree/master/libvlc) - The libvlc bindings for the Android platform.
*   [vlc-unity](https://code.videolan.org/videolan/vlc-unity) - Unity3D integration for VLC.
*   [python-vlc (⭐312)](https://github.com/oaubert/python-vlc) - Python vlc bindings.
*   [vlcj (⭐953)](https://github.com/caprica/vlcj) -  Java framework for the vlc media player (desktop).
*   [LibVLCSharp (⭐1.1k)](https://github.com/videolan/libvlcsharp) - Cross-platform .NET/Mono bindings for LibVLC.
*   [libvlc-go (⭐326)](https://github.com/adrg/libvlc-go) - Go bindings for libVLC and high-level media player interface.
*   [libvlcpp](https://code.videolan.org/videolan/libvlcpp/) - C++ bindings for libvlc.
*   [vlc.js (beta)](https://code.videolan.org/jbk/vlc.js) - WebAssembly support for LibVLC.
*   [flutter\_vlc\_player (⭐386)](https://github.com/solid-software/flutter_vlc_player) - Flutter bindings to LibVLC.
*   [dart\_vlc (⭐416)](https://github.com/alexmercerind/dart_vlc) - Dart bindings for libvlc.
*   [WebChimera.js (⭐666)](https://github.com/RSATom/WebChimera.js) - Electron bindings for libvlc.
*   [libvlc-zig (⭐5)](https://github.com/kassane/libvlc-zig) - Zig bindings for libVLC.

## Tutorials

*   [HLS Record tutorial](https://mfkl.github.io/hls/2018/10/10/How-to-record-HLS-stream-with-LibVLCSharp-and-.NET-Core.html) - How to record an HLS stream with LibVLCSharp and .NET Core.
*   [RTSP mosaic tutorial](https://mfkl.github.io/libvlc/rtsp/xamarin/forms/2018/12/05/crossplatform-RTSP-mosaic-views-with-libvlcsharp.html) - Cross-platform RTSP Mosaic views with LibVLCSharp.
*   [MediaElement tutorial](https://doumer.me/vlc-media-player-in-xamarinforms-alternative-avplayer-andmediaplayer) - VLC Media Player control in Xamarin Forms.

## Ebook

*   [The Good Parts of LibVLC](https://mfkl.gumroad.com/l/libvlc-good-parts) - The first ebook about the VideoLAN non-profit organization and the opensource LibVLC developer SDK.

## Community

*   [Stack Overflow - LibVLC](https://stackoverflow.com/questions/tagged/libvlc) - LibVLC on Stack Overflow.
*   [Stack Overflow - VLC](https://stackoverflow.com/questions/tagged/vlc) - VLC on Stack Overflow.
*   [Mailing Lists](https://www.videolan.org/support/lists.html) - VideoLAN developer mailing lists.
*   [IRC](https://wiki.videolan.org/Contact_VideoLAN/#IRC) - The VideoLAN IRC information.
*   [Forum](https://forum.videolan.org/) - The official VideoLAN forum.
*   [LibVLC Discord](https://discord.gg/3h3K3JF) - The official LibVLC Community Discord Server.
*   [Twitter](https://twitter.com/videolan) - The official VideoLAN Twitter account.
*   [Reddit](https://www.reddit.com/r/vlc) - Unofficial VLC community on Reddit.

## Contributing

[Contributions](https://github.com/mfkl/awesome-vlc/blob/main/README.md/contributing.md) are welcome!

