# Track Asdf Plugins Updates Weekly

Convenience shortname repository for asdf community plugins

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/asdf-vm/asdf-plugins/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 asdf-vm/asdf-plugins](https://github.com/asdf-vm/asdf-plugins) · ⭐ 1K · 🏷️ Computer Science

[ [Daily](/content/asdf-vm/asdf-plugins/README.md) / Weekly / [Overview](/content/asdf-vm/asdf-plugins/readme/README.md) ]

## [Feb 13 - Feb 19, 2023](/content/2023/7/README.md)

### Contributing a new Plugin / `asdf-community`

*   Install repo dependencies: `asdf install`
*   Add the plugin to the repository `README.md` *Plugin List* table.
*   Create a file with the shortname you wish to be used by asdf in `plugins/<name>`. The contents should be `repository = <your_repo>`.
    *   eg: `printf "repository = https://github.com/asdf-vm/asdf-nodejs.git\n" > plugins/nodejs`
*   Test your code : `scripts/test_plugin.bash --file plugins/<name>`
*   Format your code & this README: `scripts/format.bash`

## [Sep 06 - Sep 12, 2021](/content/2021/36/README.md)

### Creating a new Plugin

*   Read the [creating plugins guide (⭐19k)](https://github.com/asdf-vm/asdf/blob/master/docs/plugins/create.md)

## [Jul 12 - Jul 18, 2021](/content/2021/28/README.md)

### Creating a new Plugin

*   Consider using our [Template (⭐88)](https://github.com/asdf-vm/asdf-plugin-template) which has the core functionality to tools published to GitHub releases and CI for GitHub/GitLab/CircleCI out of the box.

### Contributing a new Plugin / `asdf-community`

*   Create a PR following the instructions in the PR template.