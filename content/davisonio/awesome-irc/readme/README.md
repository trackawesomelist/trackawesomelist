# Awesome Irc Overview

A curated list of awesome IRC resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/davisonio/awesome-irc/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 davisonio/awesome-irc](https://github.com/davisonio/awesome-irc) · ⭐ 687 · 🏷️ Miscellaneous

[ [Daily](/content/davisonio/awesome-irc/README.md) / [Weekly](/content/davisonio/awesome-irc/week/README.md) / Overview ]

---

# Awesome IRC [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) resources.

A list of tools, software & other resources related to the Internet Relay Chat (IRC) protocol.

IRC (Internet Relay Chat) is an open source protocol that can be used for multi-user text based communication through channels.

## Contents

*   [Clients](#clients)
*   [Bouncers](#bouncers)
    *   [Self-hosted](#self-hosted)
    *   [Hosted](#hosted)
*   [Daemons](#daemons)
*   [Services](#services)
*   [Bots](#bots)
*   [Frameworks](#frameworks)
    *   [Bridges](#bridges)
*   [Channels](#channels)
    *   [Discovery](#discovery)
    *   [Platforms](#platforms)
    *   [Programming](#programming)
*   [Networks](#networks)
*   [Articles](#articles)
*   [Guides](#guides)
*   [Protocol](#protocol)
*   [Miscellaneous](#miscellaneous)

### Clients

*You use these to connect to IRC.*

*   [Komanda](https://komanda.io) - Designed for people who write code (beta). ([source (⭐1.8k)](https://github.com/mephux/komanda)) `Linux`
*   [Textual](https://www.codeux.com/textual/) - Very customizable, ZNC integration, iCloud sync ($4.99). ([source (⭐1.8k)](https://github.com/Codeux-Software/Textual)) `macOS`
*   [LimeChat](http://limechat.net/mac/) - One window for multiple servers, keyboard shortcuts, fast & stable. ([source (⭐1.5k)](https://github.com/psychs/limechat)) `macOS` `iOS`
*   [HexChat](https://hexchat.github.io) - Based on XChat, easy to use, spell check & multiple languages. ([source (⭐2.8k)](https://github.com/hexchat/hexchat)) `Windows` `macOS` `Linux`
*   [gamja](https://sr.ht/\~emersion/gamja/) - A simple IRC web client. ([source](https://git.sr.ht/\~emersion/gamja)) `Web`
*   [Kiwi IRC](https://kiwiirc.com) - Powerful modern IRC messenger for the web. ([source (⭐690)](https://github.com/kiwiirc/kiwiirc), [demo](https://kiwiirc.com/nextclient/)) `Web`
*   [CIRC](https://flackr.github.io/circ/) - Uses the chrome.sockets APIs to connect directly to IRC servers without needing a proxy. ([source (⭐395)](https://github.com/flackr/circ)) `Chrome`
*   [Quassel](https://quassel-irc.org) - Distributed (clients can attach to and detach from a central core that stays permanently online. ([source (⭐666)](https://github.com/quassel/quassel)) `Linux` `macOS` `Windows`
*   [Yaaic](https://www.yaaic.org) - Multi-server/channel support, SASL support, Smooth channel scrolling / swiping. ([source (⭐331)](https://github.com/pocmo/Yaaic)) `Android`
*   [relay.js (⭐156)](https://github.com/Fauntleroy/relay.js) - Focuses on making IRC less intimidating and easier to use. `Web`
*   [Circe (⭐365)](https://github.com/jorgenschaefer/circe) - For use in Emacs, sane defaults. `Emacs`
*   [Smuxi](https://smuxi.im) - User-friendly, based on GNOME / GTK+. ([source (⭐154)](https://github.com/meebey/smuxi)) `Linux` `Windows` `macOS`
*   [KvIRC](http://www.kvirc.net) - Free, portable, based on Qt GUI toolkit. ([source (⭐199)](https://github.com/kvirc/KVIrc)) `Linux` `macOS` `Windows`
*   [Konversation](https://konversation.kde.org) - User-friendly client built on the KDE Platform. ([source (⭐36)](https://github.com/KDE/konversation)) `Linux`
*   [sic](https://tools.suckless.org/sic/) - **S**imple **I**RC **c**lient - a terminal client in less than 250 lines of C. `Linux`
*   [irssi](https://irssi.org) - Terminal client, multi-protocol friendly for module authors, GPLv2. `Linux` `macOS` `Cygwin` `BSD`
*   [Revolution IRC (⭐446)](https://github.com/MCMrARM/revolution-irc) - Feature-full, actively maintained Android IRC client. ([source (⭐446)](https://github.com/MCMrARM/revolution-irc)) `Android`
*   [AdiIRC](https://adiirc.com) - Never has a client offered such granular settings for every aspect of the IRC experience. ([features](https://dev.adiirc.com/projects/adiirc/wiki/Features), [screenshots](https://dev.adiirc.com/projects/adiirc/wiki/Screenshots)) `Windows` `WINE`
*   [IRC for Android™](https://www.countercultured.net/android/) Android/Chrome OS client for power users, with ZNC built-ins, notification logic, reliable DCC, keybinds for hardware keyboards, etc. `Android` `ChromeOS`
*   [Iridium](https://appcenter.elementary.io/com.github.avojak.iridium/) - Friendly IRC client built in Vala and GTK, designed for elementary OS. ([source (⭐49)](https://github.com/avojak/iridium)) `Linux`

*More? Clients that include bouncers are found [below](#bouncers).*

### Bouncers

*Useful for disconnecting and reconnecting without losing the chat session.*

#### Hosted

*   [IRCCloud](https://www.irccloud.com) - Group chat for teams, friends, and communities. stay connected, chat from anywhere, and never miss a message (+client) (£0-£3.50/month).
    *   [iOS App (⭐259)](https://github.com/irccloud/ios) - Official. `Objective-C`
    *   [Android App (⭐268)](https://github.com/irccloud/android) - Official. `Java`
    *   [Nimbus (⭐151)](https://github.com/jnordberg/irccloudapp) - Standalone client. `macOS` `Objective-C`

#### Self-hosted

*   [Convos](https://convos.chat) - Always online web IRC client. ([source (⭐907)](https://github.com/convos-chat/convos), [demo](https://demo.convos.chat)) `Perl` `JavaScript` `Web`
*   [ZNC](https://wiki.znc.in/ZNC) - Most popular. many different plugins. ([source (⭐1.9k)](https://github.com/znc/znc)) `C++`
*   [BIP IRC Proxy](https://bip.milkypond.org) - Always online, lightweight and secure Open Source IRC proxying with backlogging. ([source](https://projects.duckcorp.org/projects/bip/repository)) `C`
*   [TheLounge](https://thelounge.chat) - Responsive, self-hosted & support for multiple users. ([source (⭐4.9k)](https://github.com/thelounge/thelounge), [demo](https://demo.thelounge.chat/)) `JavaScript` `Node.js` `Web`
*   [WeeChat](https://weechat.org) - A fast, light and extensible chat client. ([source (⭐2.6k)](https://github.com/weechat/weechat)) `Linux` `macOS` `Windows`
*   [soju](https://git.sr.ht/\~emersion/soju) - A user-friendly IRC bouncer. `Go`

### Daemons

*Used for running your own IRC server or network.*

*   [ircd.js (⭐529)](https://github.com/alexyoung/ircd.js) - Server will allow clients to connect, join channels, change topics; basic stuff.
*   [InspIRCd](https://www.inspircd.org) - Modular, stable, written from scratch. ([source (⭐1k)](https://github.com/inspircd/inspircd))
*   [miniircd (⭐374)](https://github.com/jrosdahl/miniircd) - Very simple and limited.
*   [ngIRCd](https://ngircd.barton.de) - Portable and lightweight for small or private networks. ([source (⭐351)](https://github.com/ngircd/ngircd))
*   [Ergo (⭐1.8k)](https://github.com/ergochat/ergo) - Modern server that's portable and designed around specifications (bleeding-edge IRCv3 support).
*   [RobustIRC](https://robustirc.net) - IRC server without netsplits. ([source (⭐158)](https://github.com/robustirc/robustirc/))

### Services

*Used to provide user accounts and bots like NickServ/ChanServ to your network.*

*   [Atheme](https://atheme.github.io) - Designed for large networks with high scalability requirements. ([source (⭐353)](https://github.com/atheme/atheme))
*   [anope](https://anope.org) - Designed for flexibility and ease of use. ([source (⭐279)](https://github.com/anope/anope))

### Bots

*IRC users which provide services for humans, e.g. integrations or information.*

*   [Sopel](https://sopel.chat) - Tonnes of ready made features, tutorial, fully documented. ([source (⭐921)](https://github.com/sopel-irc/sopel)) `Python`
*   [Limnoria (⭐567)](https://github.com/ProgVal/Limnoria) - Robust, user friendly, developer friendly. `Python`
*   [Twitch Plays (⭐263)](https://github.com/aidanrwt/twitch-plays) - Takes input from the chat and presses the corresponding key. `Python`
*   [Skybot (⭐242)](https://github.com/rmmh/skybot) - Main goals are simplicity and power. `Python`
*   [talkbackbot](https://geekchick77.dreamwidth.org/472.html) - Responds to configured trigger phrases with quotes from notable women. ([source (⭐182)](https://github.com/jessamynsmith/talkbackbot)) `Python`
*   [lazybot (⭐150)](https://github.com/Raynes/lazybot) - User-friendly and powerful. `Clojure`
*   [IRC-BF](https://gitlab.com/ddevault/bf-irc-bot) - `Brainfuck`
*   [geordi (⭐183)](https://github.com/Eelis/geordi) - Compiles and runs C++ code snippets. `C++`
*   [CloudBot (⭐60)](https://github.com/TotallyNotRobots/CloudBot) - Simple, fast, expandable. `Python`
*   [yossarian-bot (⭐29)](https://github.com/woodruffw/yossarian-bot) - Large default plugin set, Cinch-based. `Ruby`
*   [helga (⭐46)](https://github.com/shaunduncan/helga) - Pluggable chat bot supporting multiple protocols. `Python`
*   [EveIRC (⭐7)](https://github.com/Inspyre-Technologies/EveIRC) - Extendable chat/channel/server-managenent service-providing bot. Using the [Cinch Framework (⭐1k)](https://github.com/cinchrb/cinch). `Ruby`
*   [BitBot (⭐126)](https://github.com/jesopo/bitbot) - Modular, event-driven bot featuring a REST API, individual user settings and much more. [bitbot.dev](https://bitbot.dev) `Python`
*   [Cardinal (⭐92)](https://github.com/JohnMaguire/Cardinal) - Python Twisted IRC bot with a focus on ease of plugin development. ([source (⭐92)](https://github.com/JohnMaguire/Cardinal)) `Python`

### Frameworks

*Helpful to write bots or integrate IRC with applications.*

*   [node-irc (⭐42)](https://github.com/Throne3d/node-irc) `JavaScript`
*   [goirc (⭐472)](https://github.com/fluffle/goirc) - Event-based, stateful, lacking documentation. `Go`
*   [Hubot IRC Adapter (⭐307)](https://github.com/nandub/hubot-irc) - The IRC adapter for hubot. `JavaScript`
*   [go-ircevent (⭐445)](https://github.com/thoj/go-ircevent) - Event-based. `Go`
*   [pyaib (⭐338)](https://github.com/facebook/pyaib) - Easy to use framework for writing bots. `Python`
*   [slate-irc (⭐203)](https://github.com/slate/slate-irc) - Plugin system, simple api, arbitrary input stream, debug support. `JavaScript`
*   [PircBotX (⭐206)](https://github.com/pircbotx/pircbotx) - Event based IRC Library with a straightforward API (updated fork of [PircBot](http://www.jibble.org/pircbot.php)). `Java`
*   [IRC::Client (⭐13)](https://github.com/raku-community-modules/IRC-Client) - `Perl6` based extendable IRC client framework.
*   [irccd](http://projects.malikania.fr/irccd/) - Flexible IRC bot customizable with Javascript. `C++`.

#### Bridges

*Sends messages back and forth.*

*   [discord-irc (⭐1.1k)](https://github.com/reactiflux/discord-irc) - Discord ↔ IRC. `JavaScript`
*   [slack-irc (⭐592)](https://github.com/ekmartin/slack-irc) - Slack ↔ IRC. `JavaScript`
*   [irc-slack (⭐159)](https://github.com/insomniacslk/irc-slack) - Slack ↔ IRC. `Go`
*   [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - XMPP, Jabber, Google Talk, MSN Messenger, Yahoo! Messenger, AIM, ICQ, Twitter API, HipChat ↔ IRC. `C`
*   [teleirc (⭐116)](https://github.com/RITlug/teleirc) - Telegram ↔ IRC. `JavaScript`
*   [toxirc (⭐21)](https://github.com/endoffile78/toxirc) - Tox ↔ IRC. `C`
*   [skyweb2irc (⭐4)](https://github.com/ProgVal/skyweb2irc) - Skype (webclient API) ↔ IRC. `Javascript`
*   [matterbridge (⭐5.2k)](https://github.com/42wim/matterbridge) - IRC ↔ Mattermost ↔ Discord ↔ XMPP ↔ Gitter ↔ Slack ↔ Discord ↔ Telegram ↔ ... `Go`

### Channels

*IRC channels.*

#### Discovery

*   [netsplit.de Search](https://netsplit.de/channels/) - Searches 563 different networks.
*   [mibbit Search](https://search.mibbit.com) - Searches networks listed [here](https://search.mibbit.com/networks).
*   [KiwiIRC Search](https://kiwiirc.com/search) - Searches 318 different networks.

#### Platforms

*   [#ubuntu](https://wiki.ubuntu.com/IRC/ChannelList)@Libera.Chat - Official Ubuntu support channel. ([rules](https://wiki.ubuntu.com/IRC/Guidelines))

### Networks

*A collection of IRC servers is known as a network.*

*   [Libera.Chat](https://libera.chat) - Network mostly focused on free and open source projects, run by former freenode staff.
*   [Snoonet](https://snoonet.org) - Community of redditors and subreddits. ([rules](https://snoonet.org/rules/))
*   [OFTC](https://oftc.net) - Community for free and open source software communities.
*   [LibertaCasa](https://liberta.casa) - Privacy endorsing community serving as a safe and open space for the discussion of various topics.

### Articles

*Articles and blog posts about IRC.*

*   [Please don't use Slack for FOSS projects](https://drewdevault.com/2015/11/01/Please-stop-using-slack.html) - Drew DeVault's Blog.
*   [IRC Networks Under Systematic Attack From Governments](https://www.quakenet.org/articles/102-press-release-irc-networks-under-systematic-attack-from-governments) - QuakeNet.
*   [IRC is dead, long live IRC](https://www.pingdom.com/blog/irc-is-dead-long-live-irc/) - Pingdom.
*   [IRC Has Lost 60% Of Its Users Since 2003, But Life As A Robot Is Just Beginning](https://techcrunch.com/2013/01/06/irc-has-lost-60-of-its-users-since-2003-but-life-as-a-robot-is-just-beginning/) - Alex Williams (TechCrunch).

### Guides

*How-to's, documentation and books.*

*   [#irchelp](https://www.irchelp.org) - A vast amount of reasonably up-to-date information.

### Protocol

*Information and resources about the IRC protocol itself.*

*   [IRCv3 Working Group](https://ircv3.net) - A group of IRC software authors working to enhance, improve, maintain and standardize the IRC protocol. ([source (⭐82)](https://github.com/ircv3/ircv3.github.io))
*   [Modern IRC Documents](https://modern.ircdocs.horse) - An attempt to write an update to the original IRC protocol. documentation ([source (⭐153)](https://github.com/ircdocs/modern-irc))
*   [IRC Definition Files](https://defs.ircdocs.horse) - Lists of numerics, modes, ISUPPORT tokens and other protocol details. ([source (⭐61)](https://github.com/ircdocs/irc-defs))
*   [grawity's IRC docs (⭐50)](https://github.com/grawity/irc-docs) - Collection of misc IRC protocol documentation.
*   [Protocol Statistics](https://stats.ircdocs.horse) - Statistics around the server software in use on networks today. ([source (⭐6)](https://github.com/ircdocs/irc-stats))
*   [IRC Parser Tests (⭐34)](https://github.com/ircdocs/parser-tests) - A CC0 set of test suites, to ensure IRC message parsers are consistent.
*   [DareNET Archives](https://archives.darenet.org) - IRC Archives for old hard to find IRC related software.

### Miscellaneous

*Items that belong on the list but defy classification.*

*   [superseriousstats (⭐88)](https://github.com/tommyrot/superseriousstats) - Fast and efficient program to create statistics out of various types of chat logs. `PHP` `Web`

## Use

The best ways to use this list are:

*   by browsing the [contents](#contents)
*   by using <kbd>command</kbd> + <kbd>F</kbd> to search the contents

This list also uses tags to help when searching the contents:

*   **Language** - `Python`, `Java`, `C++`, `Go`, `JavaScript`, `Ruby`, `C` etc.
*   **Platform** - `Web`, `macOS`, `Windows`, `Linux`, `Chrome` etc.

## Credits

**[Craig Davison](https://davison.io)**

[![GitHub](https://img.shields.io/github/followers/davisonio.svg?style=social\&label=Follow%20@davisonio)](https://github.com/davisonio) [![Twitter](https://img.shields.io/twitter/follow/davisonio.svg?style=social)](https://twitter.com/davisonio)

...and [contributors (⭐685)](https://github.com/davisonio/awesome-irc/graphs/contributors).

**[Contributions are welcome! (⭐685)](https://github.com/davisonio/awesome-irc/blob/master/contributing.md)**

## License

Unless otherwise stated:

*   Copyright © 2016+ [Craig Davison](https://davison.io). Licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

