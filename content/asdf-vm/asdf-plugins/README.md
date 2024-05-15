# Track Asdf Plugins Updates Daily

Convenience shortname repository for asdf community plugins

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/asdf-vm/asdf-plugins/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 asdf-vm/asdf-plugins](https://github.com/asdf-vm/asdf-plugins) · ⭐ 1.1K · 🏷️ Computer Science

[ Daily / [Weekly](/content/asdf-vm/asdf-plugins/week/README.md) / [Overview](/content/asdf-vm/asdf-plugins/readme/README.md) ]

## [Feb 13, 2023](/content/2023/02/13/README.md)

### Contributing a new Plugin / `asdf-community`

*   Install repo dependencies: `asdf install`
*   Add the plugin to the repository `README.md` *Plugin List* table.
*   Create a file with the shortname you wish to be used by asdf in `plugins/<name>`. The contents should be `repository = <your_repo>`.
    *   eg: `printf "repository = https://github.com/asdf-vm/asdf-nodejs.git\n" > plugins/nodejs`
*   Test your code : `scripts/test_plugin.bash --file plugins/<name>`
*   Format your code & this README: `scripts/format.bash`

## [Sep 11, 2021](/content/2021/09/11/README.md)

### Creating a new Plugin

*   Read the [creating plugins guide (⭐20k)](https://github.com/asdf-vm/asdf/blob/master/docs/plugins/create.md)

## [Jul 16, 2021](/content/2021/07/16/README.md)

### Creating a new Plugin

*   Consider using our [Template (⭐98)](https://github.com/asdf-vm/asdf-plugin-template) which has the core functionality to tools published to GitHub releases and CI for GitHub/GitLab/CircleCI out of the box.

### Contributing a new Plugin / `asdf-community`

*   Create a PR following the instructions in the PR template.