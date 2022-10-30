# Track Awesome Heroku Updates Daily

A curated list of helpful Heroku resources.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/ianstormtaylor/awesome-heroku/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 ianstormtaylor/awesome-heroku](https://github.com/ianstormtaylor/awesome-heroku) · ⭐ 280 · 🏷️ Platforms

[ Daily / [Weekly](/content/ianstormtaylor/awesome-heroku/week/README.md) / [Overview](/content/ianstormtaylor/awesome-heroku/readme/README.md) ]

## [Jun 29, 2019](/content/2019/06/29/README.md)

### Deployment

*   `article` [Deploying Django to Heroku With Docker](https://testdriven.io/blog/deploying-django-to-heroku-with-docker/) — looks at how to deploy a Django app to Heroku with Docker via the Heroku Container Runtime

## [Jun 14, 2019](/content/2019/06/14/README.md)

### Architecture

*   `article` [Split Frontend from Backend on Heroku with npm and NodeJS](https://medium.com/@spygi/scalable-cost-effective-web-architectures-for-heroku-eb8f1f55a4b6) - hands-on guide to deploy a microservices web application in Heroku using npm and NodeJS.

## [Jul 23, 2018](/content/2018/07/23/README.md)

### Deployment

*   `article` [Six Tips for Mastering your Procfile](https://medium.com/@adam_41691/six-tips-for-mastering-your-procfile-64ea1207b779) — improvements for how you run your Heroku processes.

## [Jun 18, 2018](/content/2018/06/18/README.md)

### Blogs

*   `blog` [Heroku Blog](https://blog.heroku.com) — the official Heroku blog.

## [Apr 05, 2016](/content/2016/04/05/README.md)

### General

*   `book` [Heroku Cookbook](http://www.amazon.com/Heroku-Cookbook-Mike-Coutermarsh/dp/1782177949) — step-by-step recipes to solve the challenges of administering and scaling a real-world production web application on Heroku.

## [Mar 18, 2016](/content/2016/03/18/README.md)

### Deployment

*   `official` [Preboot](https://devcenter.heroku.com/articles/preboot) — explains how to use the "Preboot" feature to enable zero-downtime deployments, which can be tricky to get right.

### Development

*   `official` [Managing Multiple Environments for an App](https://devcenter.heroku.com/articles/multiple-environments) — a good primer on how to think about managing the different pieces of each environment.

### Postgres

*   `plugin` [heroku-buildpack-pgbouncer (⭐333)](https://github.com/heroku/heroku-buildpack-pgbouncer) — a buildpack that allows for transaction pooling using [`stunnel`](https://www.stunnel.org/index.html) and [`pgbouncer`](https://wiki.postgresql.org/wiki/PgBouncer) to avoid hitting connection limits.

## [Mar 17, 2016](/content/2016/03/17/README.md)

### Analytics

*   `tool` [Metabase](http://www.metabase.com/docs/v0.13.3/operations-guide/running-metabase-on-heroku.html) — a beta of Metadata as an app that can be deployed directly to Heroku.

### Architecture

*   `article` [Exploring Microservices Architecure on Heroku](http://blog.codeship.com/exploring-microservices-architecture-on-heroku/) — explores why Heroku eliminates a lot of the tooling you need to worry about when working with microservices.
*   `article` [Heroku and SOA](https://www.rdegges.com/2014/heroku-and-soa/) — discusses why Heroku is perfectly suited to building a service-oriented architecture for your projects.

### Deployment

*   `article` [Automating our Heroku deployments from Jenkins](https://www.paulfurley.com/automating-heroku-deployments-from-jenkins/) — explains how you'd go about automating certain parts of deployment like enabling maintenance mode, copying your database from production to staging, running migrations against staging, etc.
*   `question` [How do you ignore files when deploying to Heroku?](http://stackoverflow.com/questions/12523435/how-do-i-ignore-folders-and-files-when-pushing-to-heroku-with-a-rails-app) — the answer to a common question about `.gitignore` like functionality.

### Domains

*   `article` [Configuring CloudFlare DNS for a Heroku app](http://www.higherorderheroku.com/articles/cloudflare-dns-heroku/) — a walkthrough of how to use CloudFlare as your DNS provider.
*   `article` [Hosting multiple Heroku apps on a single domain](https://pilot.co/blog/hosting-multiple-heroku-apps-on-a-single-domain/) — an article on how to share the same domain between multiple Heroku applications.
*   `question` [How do you host multiple Heroku apps on a single domain?](http://stackoverflow.com/questions/19119164/multiple-heroku-apps-on-a-single-domain) — a StackOverflow question with a few responses to a the common question of how to serve multiple Heroku apps from different paths instead of subdomains.

### General

*   `book` [The Heroku Hacker's Guide](http://www.theherokuhackersguide.com/) — an ebook that covers a lot of the basics in maintaining and scaling a project on Heroku.

### Meta

*   `official` [The big kickoff](https://blog.heroku.com/archives/2007/10/30/the_big_kickoff) — the first ever Heroku blog article.
*   `article` [Heroku isn't for idiots](https://www.rdegges.com/2012/heroku-isnt-for-idiots/) — explains Heroku's advantages and why it's not just for side projects.
*   `article` [My Heroku values](https://brandur.org/heroku-values) — a great series of takeaways from [Brandur Leach](https://twitter.com/brandur) when he left Heroku.
*   `talk` [Buildpack Adventure](http://buildpack-adventure.herokuapp.com/) — a cool slideshow about Heroku's buildpacks, and what the open-source community is hacking together with them.

### Postgres

*   `official` [Heroku Postgres](https://www.heroku.com/postgres) — the landing page explaining with it is.

### Scaling

*   `tool` [HireFire](https://www.hirefire.io/) — a SaaS tool that automatically scales your Heroku dynos up and down as load requires.

### Security

*   `article` [Set up CloudFlare's free SSL on Heroku](https://robots.thoughtbot.com/set-up-cloudflare-free-ssl-on-heroku) — walks you through the exact steps to setting up free SSL via Cloudflare.

### Toolbelt

*   `official` [Toolbelt Download](https://toolbelt.heroku.com/) — where to download the Heroku toolbelt.
*   `plugin` [heroku-accounts (⭐1.2k)](https://github.com/ddollar/heroku-accounts) — makes it easy to work with multiple accounts at once from the command line.
*   `plugin` [heroku-pg-extras (⭐1.3k)](https://github.com/heroku/heroku-pg-extras) — a toolbelt plugin that adds extra useful plugins for working with Postgres. Things like analyzing cache hit rates, outlier queries, unused indexes, table sizes, etc.

### Goodbye...

*   `tool` [dokku](http://dokku.viewdocs.io/dokku/) — a self-hosted, docker-based, Heroku-compliant platform.