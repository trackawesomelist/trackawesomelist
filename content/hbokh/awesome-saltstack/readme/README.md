# Awesome Saltstack Overview

🧂 A collaborative curated list of awesome SaltStack resources, tutorials and other salted stuff.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/hbokh/awesome-saltstack/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 hbokh/awesome-saltstack](https://github.com/hbokh/awesome-saltstack) · ⭐ 488 · 🏷️ Miscellaneous

[ [Daily](/content/hbokh/awesome-saltstack/README.md) / [Weekly](/content/hbokh/awesome-saltstack/week/README.md) / Overview ]

---

# Awesome SaltStack [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A collaborative curated list of awesome SaltStack resources, tutorials and other salted stuff.

<!--lint ignore double-link-->

[<img src="https://user-images.githubusercontent.com/519955/35341388-d8c0cf0e-0125-11e8-9831-51f13fab58c7.jpg" width="100%">](https://www.saltstack.com/)

SaltStack is the other configuration management system built with Python.\
It takes a new approach to infrastructure management by developing software that is easy enough to get running in seconds, scalable enough to manage tens of thousands of servers, and fast enough to control and communicate with them in milliseconds.\
SaltStack software manages system infrastructure and the application stacks that run on it and is used by web-scale application developers, DevOps teams and systems administrators.

A :gem: means **really *awesome / useful***.

## Contents

*   [Official resources](#official-resources)
*   [Tutorials](#tutorials)
*   [Code](#code)
*   [Integrations](#integrations)
*   [Books](#books)
*   [Videos](#videos)
*   [Tools](#tools)
*   [Presentations](#presentations)
*   [Blogposts and opinions](#blogposts-and-opinions)
*   [Discussions](#discussions)
*   [Community](#community)
*   [Formulas](#formulas)
*   [Cheat sheets](#cheat-sheets)
*   [Uncategorized](#uncategorized)
*   [Attic](#attic)

## Official resources

<!--lint ignore double-link-->

*   [SaltStack site](https://www.saltstack.com/) - Company website.
*   [Salt Project site](https://saltproject.io/) - Salt Project (Salt Open Source) website.
*   [vRealize Automation SaltStack Config](https://www.vmware.com/products/vrealize-automation/saltstack-config.html) - vRealize Automation SaltStack Config website at VMware (new name for commercial SaltStack product).
*   [GitHub repo (⭐13k)](https://github.com/saltstack/salt) - Salt's source code, issues discussion and collaboration.
*   [GitLab repo](https://gitlab.com/saltstack/open) - Salt Project's eventual new home.
*   [SaltStack Documentation](https://docs.saltproject.io/en/latest/) - Official documentation.
*   [Salt in 10 minutes](https://docs.saltproject.io/en/latest/topics/tutorials/walkthrough.html) - Official walkthrough.

<!--lint ignore awesome-list-item-->

*   [SaltStack Get Started](https://docs.saltproject.io/en/getstarted/) - These tutorials walk you through the basics of getting SaltStack up and running. :gem:
*   [Training and certification](https://www.saltstack.com/products/saltstack-training/) - Official training.
*   [Jinja2 documentation](http://jinja.pocoo.org/docs/latest/) - This official documentation covers the used templating language in Salt.
*   [Salt Module Contributions (⭐173)](https://github.com/saltstack/salt-contrib) - Salt modules developed by the community.

## Tutorials

<!--lint ignore awesome-list-item-->

*   [About SaltStack](http://www.yet.org/2016/09/salt/) - Extensive blogpost with lots of in-depth information. :gem:
*   [A dive into SaltStack](https://opencredo.com/a-dive-into-salt-stack/) - SaltStack uncovered - Configuration management has been a big leap forward for System Engineers.
*   [How To Use Salt Cloud Map Files to Deploy App Servers and an Nginx Reverse Proxy](https://www.digitalocean.com/community/tutorials/how-to-use-salt-cloud-map-files-to-deploy-app-servers-and-an-nginx-reverse-proxy) - Walkthrough on how to use Salt Cloud Map Files to deploy application servers and an Nginx reverse proxy.
*   [An Introduction to SaltStack Terminology and Concepts](https://www.digitalocean.com/community/tutorials/an-introduction-to-saltstack-terminology-and-concepts) - Part 1 of 6 in the series *Managing Development Environments with SaltStack*.
*   [SaltStack Infrastructure: Installing the Salt Master](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-installing-the-salt-master) - Part 2 of 6 in the series *Managing Development Environments with SaltStack*.
*   [SaltStack Infrastructure: Configuring Salt-Cloud to Spin Up DigitalOcean Resources](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-configuring-salt-cloud-to-spin-up-digitalocean-resources) - Part 3 of 6 in the series *Managing Development Environments with SaltStack*.
*   [SaltStack Infrastructure: Creating Salt States for Nginx Web Servers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-nginx-web-servers) - Part 4 of 6 in the series *Managing Development Environments with SaltStack*.
*   [SaltStack Infrastructure: Creating Salt States for HAProxy Load Balancers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-haproxy-load-balancers) - Part 5 of 6 in the series *Managing Development Environments with SaltStack*.
*   [SaltStack Infrastructure: Creating Salt States for MySQL Database Servers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-mysql-database-servers) - Part 6 in the series *Managing Development Environments with SaltStack*.
*   [Getting Started with SaltStack - the Other Configuration Management System Built with Python](https://www.linuxjournal.com/content/getting-started-salt-stack-other-configuration-management-system-built-python) - A Linux Journal "Getting started" from 2013.
*   [Create an army of Salt minions on DigitalOcean](http://www.aaronbell.com/lets-make-salt-minions-on-digitalocean/) - Combine the simplicity of Salt with DigitalOcean's snapshot and image feature.
*   [Vagrant & SaltStack Quickstart Tutorial](https://hittaruki.info/post/vagrant-saltstack-tutorial/) - Getting started with SaltStack and Vagrant.
*   [Salt-API, A Crash Course](https://thereluctanttecchie.blogspot.com/2014/01/salt-api-crash-course.html) - Get a barebones salt-api proof of concept up and running.
*   [Revised Getting Started with SaltStack - Part 1](https://www.infracloud.io/blog/revised-getting-started-with-saltstack-part-1/) - Simple setup and play around on the command line.
*   [SaltStack Examples](https://www.unixmen.com/saltstack-examples/) - Will teach you some of default functions in a quick way.
*   [Getting Started with Saltstack and salt-workspace](https://blog.badgerops.net/getting-started-with-salt-workspace/) - Learning SaltStack by setting up a salt-workspace.
*   [Getting started with Salt Structure](https://blog.badgerops.net/getting-started-with-salt-structure-2/) - Learn how to setup a structured SaltStack workspace.
*   [Introduction to SaltStack (⭐19)](https://github.com/redmage123/Introduction-to-Saltstack) - A two day course designed to quickly introduce System Administrators and Application Developers on how to start using Saltstack.
*   [The Simplest Way to Learn SaltStack](https://medium.com/@timlwhite/the-simplest-way-to-learn-saltstack-cd9f5edbc967) - Start to learn the basics of SaltStack by setting it up in Docker.
*   [SaltStack - Quick Guide](https://www.tutorialspoint.com/saltstack/saltstack_quick_guide.htm) - Part of the larger "Learn SaltStack"-tutorial at Tutorials Point.
*   [Upgrading Salt to Python 3](https://salt.tips/upgrading-salt-to-python-3/) - How to switch SaltStack from Python2 to Python3.
*   [Salt Guides and Tutorials, by Linode](https://www.linode.com/docs/guides/applications/configuration-management/salt/) - A good collection of Salt guides and tutorials created and managed by Linode.

## Code

*   [valentin2105/Kubernetes-Saltstack (⭐204)](https://github.com/valentin2105/Kubernetes-Saltstack) - Saltstack recipe to deploy Kubernetes cluster from scratch.
*   [madflojo/masterless-salt-base (⭐27)](https://github.com/madflojo/masterless-salt-base) - Quickly bootstrap a generic(ish) Ubuntu server. One that is ready to host Docker containers.

## Integrations

*   [Jenkins Salt API Plugin](https://plugins.jenkins.io/saltstack/) - This plugin sends a SaltStack API message as a build step.
*   [Rundeck (⭐7)](https://github.com/amendlik/salt-gen-resource) - Generate Rundeck node resources from the Salt Mine.

## Books

*   [O'Reilly - Salt Essentials](http://shop.oreilly.com/product/0636920033240.do) - By Craig Sebenik, Thomas Hatch.
*   [O'Reilly - Network Automation at Scale](https://www.cloudflare.com/network-automation-at-scale-ebook/) - By Mircea Ulinic and Seth House (an ebook sponsored by Cloudflare).
*   [Leanpub - SaltStack For DevOps](https://leanpub.com/saltstackfordevops) - By Aymen El Amri.
*   [Leanpub - Getting Started with SaltStack](https://leanpub.com/gettingstartedwithsaltstack) - By Ben Hosmer.
*   [Packt - Learning SaltStack, 2nd ed.](https://www.packtpub.com/networking-and-servers/learning-saltstack-second-edition) - By Colton Myers.
*   [Packt - Mastering SaltStack, 2nd ed.](https://www.packtpub.com/networking-and-servers/mastering-saltstack-second-edition) - By Joseph Hall.
*   [Packt - Extending SaltStack](https://www.packtpub.com/networking-and-servers/extending-saltstack) - By Joseph Hall.
*   [Packt - Salt Cookbook](https://www.packtpub.com/networking-and-servers/salt-cookbook) - By Anirban Saha.

## Videos

<!--lint ignore awesome-list-item-->

*   [SaltStack](https://www.youtube.com/user/saltstack) - SaltStack's official YouTube channel.
*   [Salt Project on Twitch](https://www.twitch.tv/saltprojectoss) - Salt Project's official Twitch channel.
*   [Managing Your Infrastructure with SaltStack](https://www.youtube.com/watch?v=y-zQUqMHRX4\&t=35s) - PyCon 2015 - April 11, 2015 - Colton Myers.
*   [Testing Salt States with Docker](https://www.youtube.com/watch?v=_xO7wj19OzI) - SaltStack PDX - June 23, 2015 - Jason Denning.
*   [Beyond Configuration Management with SaltStack for Event-Driven Infrastructure](https://www.youtube.com/watch?v=cMCH6EizVVc) - Southern California Linux Expo - January 23, 2016 - David Boucha.
*   [Automation and Orchestration with SaltStack and Twilio](https://vimeo.com/162183524) - Devops Chicago - March 2, 2016 - Nathan Brooks.
*   [SaltStack for FreeBSD](https://www.youtube.com/watch?v=HijG0hWebZk\&list=PL5yV8umka8YQOr1wm719In5LITdGzQMOF) - A 7-part video crash course on SaltStack for FreeBSD.
*   [SaltConf15 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_8BqpIDKlCTqHZI2mkysTvZ) - There were more than 60 talks delivered at SaltConf15 and we recorded all of them.
*   [SaltConf16 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-sVwcRliUQ-VGDb2qvwpx_) - Video recordings of SaltConf16 presentations.
*   [SaltConf17 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-8yJxp-nSlmM9KYEQH4fgj) - Video recordings of SaltConf17 presentations delivered by SaltStack customers and partners.
*   [SaltConf18 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-wsL5HZqtTuvV80Y6dqmQE) - Video recordings of SaltConf18 presentations.
*   [SaltConf19 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_8E03aA45ZncgwTrI96ky2m) - Video recordings of SaltConf19 presentations.
*   [SaltConf20 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl__frIm2HOGPm1GrcVQkOZTe) - Video recordings of SaltConf20 presentations.

## Tools

*   [SaltGUI (⭐386)](https://github.com/erwindon/SaltGUI) - A web interface for managing SaltStack based infrastructure.
*   [Silica](https://gitlab.com/perfecto25/silica) - A Flask-based lightweight Salt web console.
*   [Molten (⭐208)](https://github.com/martinhoefling/molten) - Molten is a WebUI for the REST API exposed by Saltstack.
*   [salt-pepper](https://pypi.org/project/salt-pepper/) - A CLI Frontend to the salt-api systems.
*   [salt-sproxy (⭐102)](https://github.com/mirceaulinic/salt-sproxy) - Salt plugin to automate the management and configuration of devices and applications, without running (Proxy) Minions.
*   [salt-lint (⭐121)](https://github.com/warpnet/salt-lint/) - Checks Salt state files (SLS) for practices and behavior that could potentially be improved.
*   [Alcali](https://alcali.dev/) - A web based tool for monitoring and administrating Saltstack Salt.
*   [ISalt (⭐62)](https://github.com/mirceaulinic/isalt) - IPython-based command shell for interactive Salt programming.

## Presentations

*   [Getting Started with SaltStack](https://speakerdeck.com/pycon2014/getting-started-with-saltstack-by-peter-baumgartner) - By Peter Baumgartner.
*   [An introduction to infrastructure management with SaltStack](https://www.slideshare.net/saltstack/an-overvisaltstack-presentation-clean) - By Aurelien Geron.
*   [Saltpad: A SaltStack Web GUI](https://speakerdeck.com/lothiraldan/saltpad-a-saltstack-web-gui) - By Boris Feld.
*   [Intro to SaltStack](http://www.justincarmony.com/slides/salt-tutorial/) - By Justin Carmony.
*   [salt-deconstructed](http://salt-decon.carson-anderson.com/) - Video and presentation (slides & PDF) by Carson Anderson.

## Blogposts and opinions

*   [Docker with SaltStack](https://opsnotice.xyz/docker-with-saltstack/) - How-to use SaltStack on a virtual cloud server based on Debian or Ubuntu.
*   [One week of Salt: frustrations and reflections](https://stevebennett.me/2014/02/17/one-week-of-salt-frustrations-and-reflections/) - First hand experiences from a Chef user.
*   [Getting started with SaltStack by example: Automatically Installing nginx](http://bencane.com/2013/09/03/getting-started-with-saltstack-by-example-automatically-installing-nginx/) - A good getting started guide for both Salt master and minions.
*   [SaltStack: Manage entries in unmanaged files with File Blockreplace](https://makina-corpus.com/blog/metier/2014/saltstack-manage-entries-in-unmanaged-files-with-file-blockreplace) - How to use the SaltStack's core `file.blockreplace`.
*   [SaltStack: Keeping Salt Pillar data encrypted using GPG](http://fabianlee.org/2016/10/18/saltstack-keeping-salt-pillar-data-encrypted-using-gpg/) - On secure encryption/decryption of pillar data.
*   [Secure Pillar in SaltStack with GPG](https://gijs.io/2017/02/28/secure-pillar-data-in-saltstack-with-gpg/) - Encrypting your pillar data can be done with GPG.
*   [Network-Automation with Salt, NAPALM and Kubernetes](http://blog.simonmetzger.de/2018/02/salt-napalm-k8s-network-automation/) - How to manage legacy devices that are not able to install software natively on themselves.
*   [Using Salt like Ansible](https://duncan.codes/2016/05/18/using-salt-like-ansible.html) - How to use Salt in a way similar to Ansible.
*   [Using Salt with reclass](http://www.yet.org/2016/10/reclass/) - Use class inheritance to define nodes roles and avoid duplication.
*   [Text editor plugins for Salt states and YAML/Jinja](https://salt.tips/text-editor-plugins-for-salt-states-and-yaml-jinja/) - Covers plugins for different editors when writing Salt states.
*   [Writing a custom Salt Grain](https://blog.badgerops.net/writing-a-custom-salt-grain/) - Writing a custom Salt Grain, and why you might want to.
*   [Building Self-Healing Applications](http://bencane.com/2014/12/30/building-self-healing-applications-with-salt-api/) - Automate the detection and first action to correct errors in your infrastructure.
*   [Testing your salt states with kitchen-salt](https://blog.gtmanfred.com/kitchen-salt.html) -  Make it easy to test salt states or formulas independently of a production environment.
*   [Salt Sudo](https://medium.com/@mike.reider/using-saltstack-for-emergency-sudoers-access-tempsudo-d5417e528e4d) - Using Salt custom modules to manage sudo access for users.
*   [Complex User management with Saltstack (using Py! renderer)](https://medium.com/@mike.reider/complex-user-management-with-saltstack-using-py-renderer-a4caa5cf229a) - Using a centralized User YAML file that contains all users' data.
*   [Vagrant Provisioning with SaltStack](https://medium.com/@Joachim8675309/vagrant-provisioning-with-saltstack-50dab12ce6c7) - Provisioning Virtual System using Masterless Salt Stack.
*   [Salt DevKit with External Formulas](https://medium.com/@Joachim8675309/salt-devkit-with-external-formulas-9e38d8b90cd7) - Local Development with Vagrant using external Salt formulas.

<!--lint ignore awesome-list-item-->

*   [Prometheus - Auto-deploying Consul and Exporters using Saltstack](https://yetiops.net/posts/prometheus-consul-saltstack-part-1-linux/) - How to deploy SaltStack, Consul and the Prometheus Node Exporter on Linux. :gem:
*   [Network Automation at Scale](https://mirceaulinic.net/2017-02-14-network-automation-tutorial/) - Up and running in 60 minutes.
*   [SaltStack Overview](https://saidvandeklundert.net/2020-03-20-saltstack-overview/) - An excellent overview and introduction of Salt.
*   [Parsing Command Output in Saltstack with JC](https://blog.kellybrazil.com/2020/09/15/parsing-command-output-in-saltstack-with-jc/) - How to easily parse remote command output in SaltStack, using `jc`.

## Discussions

<!--lint ignore no-repeat-punctuation-->

*   [Reddit: Vagrat, SaltStack, Ansible, Docker, Chef, Puppet, Packer.. Something](https://www.reddit.com/r/sysadmin/comments/2fmkvq/vagrat_saltstack_ansible_docker_chef_puppet/) - Discussion on Reddit, started Sept. 2014 in `/r/sysadmin`.

## Community

*   [Salt IRC chat](https://web.libera.chat/?channels=#salt) - IRC about Salt on Libera Chat.
*   [SaltStack Community Slack](https://saltstackcommunity.slack.com/) - Official SaltStack Slack Community ([Signup Link](https://saltstackcommunity.herokuapp.com)).
*   [SaltStack on Reddit](https://www.reddit.com/r/saltstack/) - SaltStack subreddit.
*   [#saltstack on Network to Code Slack](https://networktocode.slack.com/archives/C0NL8RRMX) - #saltstack channel on Network To Code Slack ([Signup Link](https://networktocode.herokuapp.com/)).
*   [#saltstack on VMware {code} Community Slack](https://vmwarecode.slack.com/archives/C01CASFRWG0) - #saltstack channel on VMware {code} Community Slack ([Signup Link](https://code.vmware.com/web/code/join)).
*   [Twitter feed](https://twitter.com/Salt_Project_OS) - Official Salt Project Twitter account.
*   [Mailing list](https://groups.google.com/forum/#!forum/salt-users) - Salt-users mailinglist on Google Groups.
*   [SaltStack Meetups](https://www.meetup.com/pro/saltstack/) - Worldwide Meetup groups.
*   [SaltConf](https://saltconf.com/) - Annual user conference for SaltStack customers, users, partners, developers and community members.
*   [Facebook](https://www.facebook.com/SaltProjectOSS/) - Official Salt Project Facebook account.

## Formulas

*   [SaltStack Formulas](https://github.com/saltstack-formulas/) - A central collection of formula repositories for SaltStack.
*   [Salt Formulas](https://github.com/salt-formulas) - A community developed SaltStack formulas ecosystem.
*   [Writing SaltStack formulas](http://ryepup.unwashedmeme.com/blog/2015/03/16/writing-saltstack-formulas/) - An overview on writing SaltStack formulas.

<!--lint ignore awesome-list-item-->

*   [Salt Formulas](http://www.yet.org/2016/09/salt-formulas/) In-depth blogpost about Salt Formulas. :gem:

## Cheat sheets

*   [SaltStack Cheat Sheet Plus (⭐31)](https://github.com/fmdlc/saltstack-cheatsheet) - By Facu de la Cruz.
*   [Salt Commands cheat sheet](https://sites.google.com/site/mrxpalmeiras/saltstack/salt-cheat-sheet) - List of common Salt commands.
*   [SaltStack Wiki (⭐13k)](https://github.com/saltstack/salt/wiki/Cheat-Sheet) - Cheat sheet in the SaltStack GitHub Wiki.

## Uncategorized

*   [Salt (software)](https://en.wikipedia.org/wiki/Salt_\(software\)) - Wikipedia (English).

## Attic

*   [How To Install Salt on Ubuntu 12.04](https://www.digitalocean.com/community/tutorials/how-to-install-salt-on-ubuntu-12-04) - Part 1 of 2 in the series *An Introduction to Salt*.
*   [How To Create Your First Salt Formula](https://www.digitalocean.com/community/tutorials/how-to-create-your-first-salt-formula) - Part 2 in the series *An Introduction to Salt*.
*   [Automated Provisioning of DigitalOcean Cloud Servers with Salt Cloud on Ubuntu 12.04](https://www.digitalocean.com/community/tutorials/automated-provisioning-of-digitalocean-cloud-servers-with-salt-cloud-on-ubuntu-12-04) - Walkthrough on automated provisioning of DigitalOcean Cloud Servers with Salt Cloud on Ubuntu 12.04.
*   [How To Install and Configure Salt Master and Minion Servers on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-salt-master-and-minion-servers-on-ubuntu-14-04) - SaltStack installation walkthrough for Ubuntu 14.04.
*   [Docker Swarm 1.12 Cluster Orchestration with SaltStack](https://btmiller.com/2016/11/27/docker-swarm-1.12-cluster-orchestration-with-saltstack.html) - Let's see how we can automate the spin-up of a cluster using SaltStack.

