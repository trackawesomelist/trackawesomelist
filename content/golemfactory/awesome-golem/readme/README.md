# Awesome Golem Overview

A community-curated list of awesome projects and resources related to the Golem peer-to-peer computational resources marketplace.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/golemfactory/awesome-golem/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 golemfactory/awesome-golem](https://github.com/golemfactory/awesome-golem) · ⭐ 138 · 🏷️ Decentralized Systems

[ [Daily](/content/golemfactory/awesome-golem/README.md) / [Weekly](/content/golemfactory/awesome-golem/week/README.md) / Overview ]

---

# Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)

[<img src="https://github.com/golemfactory/awesome-golem/raw/main/golem-logo.svg" align="right" width="150">](https://golem.network/)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and applications on Golem!

The users of Golem run the reference implementation in the form of the Rust implementation, Yagna. Together the users make up the Golem Network, a P2P marketplace for computational resources where individuals can act as one of the two non-exclusive roles; a provider selling idle resources, or a requestor buying resources to run tasks.

## Contents

*   [Golem](#golem)
*   [Thorg](#thorg)
*   [Network Statistics](#network-statistics)
*   [Apps](#apps)
    *   [Docker](#docker)
    *   [Testing](#testing)
    *   [VPN](#vpn)
    *   [Games](#games)
    *   [CLI Tools](#cli-tools)
    *   [Video Transcoding and Editing](#video-transcoding-and-editing)
    *   [Data Analysis](#data-analysis)
    *   [Data Simulation](#data-simulation)
    *   [Data Optimization](#data-optimization)
    *   [Finance](#finance)
    *   [Machine Learning](#machine-learning)
    *   [Deep Learning](#deep-learning)
    *   [RNG](#rng)
    *   [Password Recovery](#password-recovery)
    *   [DeFi](#defi)
    *   [User Interfaces](#user-interfaces)
    *   [Miscellaneous](#miscellaneous)
*   [Bounties and Rewards](#bounties-and-rewards)
*   [Developer and Requestor Resources](#developer-and-requestor-resources)
*   [Provider Resources](#provider-resources)
    *   [Monitoring](#monitoring)
    *   [Provisioning](#provisioning)
*   [Learning Resources](#learning-resources)
    *   [Presentations and Workshop Material](#presentations-and-workshop-material)
    *   [Unraveling Golem's The Next Milestone Blog Series](#unraveling-golems-the-next-milestone-blog-series)
    *   [GitHub Digest Blog Series](#github-digest-blog-series)
*   [Community](#community)

## Golem

*   [Golem Network Platform](https://www.golem.network/platform) - Learn the Golem platform on the official Golem Network website.
*   [Golem Factory GitHub](https://github.com/golemfactory) - Where you can find the open source code of all things Golem.
*   [Yagna GitHub (⭐264)](https://github.com/golemfactory/yagna) - The official Rust implementation of Golem.
*   [Golem Community Chat](https://chat.golem.network/) - Join the community and team open discussion on Discord.
*   [Reddit](https://reddit.com/r/GolemProject) - Golem Network discussion on the Reddit platform.
*   [Twitter](https://twitter.com/golemproject) - The Golem Project Twitter.
*   [Blog](http://blog.golemproject.net/) - The official blog where you can find the most reliable information on announcements, summaries and updates.

## Thorg

*   [About Thorg](https://www.thorg.io/about) - Learn what the Thorg miner does.
*   [Thorg Usage](https://www.thorg.io/usage) - Understand the depths of Thorg.
*   [Twitter](https://twitter.com/minewiththorg) - The official Twitter of Thorg.

## Network Statistics

*   [Golem Network Stats](https://stats.golem.network) - Statistics tracking tasks and provider resource utilization in the Golem Network.
*   [Golem Stats backend (⭐1)](https://github.com/cryptobench/golem-stats-backend) - Backend of the Golem Network Statistics page including API endpoint URLs.
*   [Stats API Documentation](https://docs.stats.golem.network/) - API endpoints that the Golem Network Stats page uses to display its data.

## Apps

*   [Golem SLATE](https://golem-slate.xyz/) - Hosted code pen SPA for writing a requester script to have work computed by the network. Utilizes dockerized yagna environments to communicate with the Golem Network in the background.
*   [Chess On Golem](https://chessongolem.app/) - Hosted Chess app to play against the providers of the network utilizing the Stockfish open source Chess engine.
*   [Go le' Machin (⭐2)](https://github.com/DEUTSCHKLUB/go-le-m) - Web based bulk image editor that allows users to upload multiple images and apply bulk actions to them.

### Docker

*   [Golem Requestor Node (⭐6)](https://github.com/DerekJarvis/general-golem) - Dockerized requestor environment. Pass in the py script, it sets up the daemon and runs it.

### Testing

*   [Golem Test Harness (Goth) (⭐10)](https://github.com/golemfactory/goth) - Tool with the purpose of speeding up your development process and making it more enjoyable for application creators.
*   [Golem-afl (⭐2)](https://github.com/sladecek/golem-afl) - An experimental test-fuzzing framework. Assists in finding security holes.
*   [Golem Cargo Test (⭐2)](https://github.com/sladecek/golem_cargo_test) - An adaptive distributed test executor for Rust projects.
*   [Golem CI (⭐5)](https://github.com/hhio618/golem-ci) - Decentralized task pipeline.
*   [Golem SLATE (⭐5)](https://github.com/deutschklub/golem-slate) - Open source repository for Golem SLATE described in the above Apps section.
*   [ThorgPress (⭐1)](https://github.com/figurestudios/thorgpress) - A tool to benchmark providers and unveil their true capabilities beyond what can be seen through the marketplace.

### VPN

*   [Yagna httpx client (⭐1)](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) - VPN usage on Yagna demonstrating communication with a provider-based HTTP server the way you communicate with any other HTTP server.
*   [Golem Provider with network access (⭐2)](https://github.com/jedbrooke/golem-network-requestor) - A requstor that acts as a http proxy for running providers, allowing them to access the wider internet.

### Games

*   [Golem Sudoku (⭐2)](https://github.com/Dodecane/golem-sudoku) - Game of Sudoku with size variants.
*   [HSOG-requester (⭐1)](https://github.com/ChrisHelmsC/hsog-requestor) - Helps the HearthStone community in the design and building of decks by running a large number of simulated games.
*   [ChessOnGolem (⭐11)](https://github.com/broadcastmonkey/ChessOnGolem) - Open source repository for Chess described in first Apps section. Includes React frontend for the 2 AI's playing against each other through the Golem backend.
*   [Golem Fleet Battle Simulator (⭐2)](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator) - System for calculating the results of a battle between two opposing starship fleets. Used in the iOS game Rock Paper Frigate to determine the result of PvP fleet battles.

### CLI Tools

*   [Golem Completion Engine (⭐1)](https://github.com/krunch3r76/gc__enhanced_completion) - Enhanced bash completion engine that extends built-in completions by providing contextual help for golemsp and yagna.
*   [Golocity (⭐6)](https://github.com/davidstyers/golocity) - Build and deploy your dockerized applications on the Golem Network in just two commands.
*   [gc\_\_push\_image (⭐1)](https://github.com/figurestudios/gc__push_image) - A CLI tool that publishes the GVMI image to Skynet, making users able to change the image\_url without self-hosting/giving up control.

### Video Transcoding and Editing

*   [Golem Network Video Transcoder (⭐1)](https://github.com/Doc-Saintly/golem-video) - Sample app to transcode videos. Select your transcoding profile and then upload your videos.
*   [Golem Transcoding requestor (⭐4)](https://github.com/Edhendil/golem-transcoding) - React + Spring based webapp accepting video files as input and transcoding these files into different formats.
*   [Golem Auto Editor (⭐4)](https://github.com/jedbrooke/golem-auto-editor) - Run Auto-Editor to automatically perform some video editing functions, offload the video processing to Golem.

### Data Analysis

*   [Flan (⭐3)](https://github.com/nestorbonilla/flan) - Tool for entrepreneurs that provide customized analysis of millions of worldwide trade value records giving them a bold guideline about what sectors they would need to take more attention to.
*   [Golem Lorenz-attractor (⭐0)](https://github.com/hhio618/golem-lorenz-attractor) - A system of three coupled, first-order, nonlinear differential equations which describe the trajectory of a particle through time.
*   [Golem Geomandel (⭐1)](https://github.com/Edhendil/golem-geomandel) - Python script for generating sequences of Mandelbrot images centered on a single point and with zoom increasing in each image.
*   [Golem COVID (⭐1)](https://github.com/iRhonin/golem-covid) - Creates images of new deaths per million related to COVID. After all images generated, it will gather them and create a gif.
*   [Golem Parallel Matplotlib (⭐0)](https://github.com/CoeJoder/golem-parallel-matplotlib) - Various statistical analyses are performed on circadian rhythm measurements in human test subjects.
*   [Full-Text Search Engine (⭐2)](https://github.com/niklr/golem-fulltext-search) - A search engine service that goes through text files.

### Data Simulation

*   [cadCAD Golem (⭐5)](https://github.com/rogervs/cadcadgolem) - Package wrapper for cadCAD to dispatch the simulation workload to multiple Golem nodes. Supports Jupyter Notebook.
*   [Golem Array (⭐5)](https://github.com/johngrantuk/golem-array) - Antenna array design and simulation.
*   [Limit visualization (⭐1)](https://github.com/vporton/limit-visualization) - Plots graphs with various limits. Supports discontinous graphs.
*   [GolemGraphWavePair (⭐1)](https://github.com/smiley1983/golemGraphWavePair) - Generates graph frames, then combine them into an animation.
*   [Golemized strong-gravitational-lense (⭐1)](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - Simple distributed computing hack that simulates a physical phenomena called gravitional lensing.

### Data Optimization

*   [Golem or-tools (⭐1)](https://github.com/Doc-Saintly/golem-ortools) - Uses the or-tools Constraint Programming library to solve problems.
*   [No more COFUD (⭐1)](https://github.com/DEUTSCHKLUB/no-more-COFUD) - Calculates how to fit the most people into a space while keeping 2 meters distance between each other.
*   [Mutta Puffs (⭐1)](https://github.com/DeveloperInProgress/Mutta-Puffs) - Sports league scheduler that solves the Travelling Tournament Problem for a given set of teams using Population-based Simulated Annealing.

### Finance

*   [ZKSync .csv export (⭐0)](https://github.com/blue-notes-robot/zksync-csv-export) - Scrapes ZKSync to generate financial data in a .csv file.

### Machine Learning

*   [DeML-Golem (⭐31)](https://github.com/anshuman73/DeML-Golem) - Decentralised Machine Learning using Federated Learning to combine the sub-step models, it trains on different provider nodes into a full fleged model.
*   [Golem Image Classifier (⭐5)](https://github.com/ControlCplusControlV/Golem-Image-Classifier) - Train and classify images through an active service.

### Deep Learning

*   [Mlg (⭐2)](https://github.com/rezahsnz/mlg) - CNN predict services, a deep learning application that distributes popular CNNs pre-trained with ImageNet datasets.
*   [Deepart Golem (⭐3)](https://github.com/echinocacti/deepart_golem) - Makes art using distributed computing by running a tensorflow app, uploading your content and style picture.

### RNG

*   [Gandom (⭐1)](https://github.com/rezahsnz/gandom) - Extract random streams from providers. Supports two PRNGs, one based on Chaos machines and the other that makes use of Sodium.
*   [Entropythief (⭐3)](https://github.com/krunch3r76/entropythief) - Get random entropy at a steal of a rate from multiple providers utilizing the linux entropy source or Intel's RDRAND cpu instruction (inspired by Gandom).

### Password Recovery

*   [Golem-JTR (⭐0)](https://github.com/hhio618/golem-jtr) - Run John The Ripper to recover a password.
*   [Yacat](https://handbook.golem.network/requestor-tutorials/task-processing-development/task-example-2-hashcat) - Hashcat password-recovery step-by-step.

### DeFi

*   [Golem Staking Pool incentivize system for GLM holders (⭐6)](https://github.com/masaun/GLM-stake-pool) - A smart contract in order to provide the opportunity of yield farming for GLM token holders.
*   [Magic-doll (⭐1)](https://github.com/bakaoh/magic-doll) - Sumer is a DeFi application that people may delegate their Splinterland card to earn passive income. Its core is `Kyle`, a Golem app that does all the computation to pick the best team to play for each match.

### User Interfaces

*   [Golem UI (⭐1)](https://github.com/shri4net/golem-hackathon-2020) - Electron user interface for Yagna.

### Miscellaneous

*   [Gc\_\_ListOffers (⭐3)](https://github.com/krunch3r76/gc__listoffers) - List offers by providers on the Golem Network with a GUI.
*   [Gc\_\_gvmi\_hash (⭐2)](https://github.com/krunch3r76/gc__gvmi_hash) - Recalculate the hash of gvmi image file. Solves the issue of having lost the hash of a previously uploaded image or if you're unsure if a key corresponds to a specific image.
*   [gvm-vim (⭐0)](https://github.com/canokaue/gvm-vim) - Golemized docker image for compiling the VIM editor.
*   [YaJSapi fork with greeting example (⭐1)](https://github.com/rezahsnz/yajsapi) - Simple Node.js requestor app that greets you. It writes some important message to a file and then downloads it for you, the basic eskeleton of a requestor app. Look in `examples/greetings`.
*   [Golem Image Sharpening (⭐0)](https://github.com/visualNext/golem) - A tool to sharpen images.
*   [Filterms (⭐3)](https://github.com/krunch3r76/filterms) - Market-strategy for whitelisting or blacklisting as a Golem requestor (yapapi).
*   [golem-bulk-image-handler (⭐1)](https://github.com/figurestudios/golem-bulk-image-handler) - Takes an input image and processes it in many different ways using the Pillow library.

## Bounties and Rewards

*   [GLM Rewards Program](https://blog.golemproject.net/community-incentives-program/) - A program that incentivizes activity within development, support, content creation, and more.
*   [Gitcoin Bounties](https://gitcoin.co/golemfactory/bounties) - A collection of open bounties and hackathons hosted on Gitcoin.

## Developer and Requestor Resources

*   [Yagna handbook](https://handbook.golem.network/) - Handbook for the Golem, implementation name, Yagna.
*   [Yagna Python API docs](https://yapapi.readthedocs.io/) - Documentation for Yapapi.
*   [Releases List (⭐264)](https://github.com/golemfactory/yagna/releases) - GitHub releases of Yagna.
*   [Requestor flash tutorial](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development) - Get started quick and create your first tasks/request on Golem.
*   [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - Use the Yagna tag if you have an interesting question you'd like answered.
*   [Breakdown of blender.js](https://docs.google.com/document/d/e/2PACX-1vRONc0RRaqImJumYQ3SmILtLo4jiCYgtE0AO3JfpMy0b0-BjAU8TvlIHdtbrs5cDrMbuPFv7khE47MO/pub) - JS guide for developers to get a better idea of how to run a task with the JavaScript API.
*   [EasyYagnaJS (⭐2)](https://github.com/figurestudios/easy-yagna-js) - Copies over Node.js dependencies directly to the provider, making developers not have to use Docker in their workflow.
*   [push-gvmi (⭐1)](https://github.com/figurestudios/push-gvmi) - A GitHub action that automatically builds and uploads the GVMI image to Golem plus a way to scrape the newest hash for local usage.

## Provider Resources

*   [Provider Tutorial](https://handbook.golem.network/provider-tutorials/provider-tutorial) - Get started as a Provider on Golem Network using the handbook.
*   [Provider FAQ (⭐9)](https://github.com/figurestudios/community-golem-docs/blob/main/providing/provider-faq.md) - Community curated list of commonly asked questions and answers.
*   [Yagna-binaries for aarch64 (⭐7)](https://github.com/MarijnStevens/yagna-binaries) - Build for 64 bit arm architecture to be able to run as a provider on a system such as a Raspberry Pi.
*   [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - Script that checks the median of the prices on stats.golem.network and updates all 3 values on the provider node related to price.
*   [Golem Price Updater (⭐4)](https://github.com/jedbrooke/golem-price-updater) - Automatically adjust the price for your Golem node based on the current price of GLM.

### Monitoring

*   [Golem Provider dashboard (⭐5)](https://github.com/vciancio/golem-dashboard) - ReactJS dashboard made to quickly gather status from your provider nodes without having to SSH into them.
*   [Golem Provider dashboard backend / GolemBar (⭐3)](https://github.com/vciancio/golem-node-server) - Flask backend that collects the data from the provider that's then used with the dashboard project above.

### Provisioning

*   [Ansible ya\_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - Ansible role that deploys a Golem provider automatically with minimal configuration required.
*   [WSL (⭐1)](https://github.com/r34x/WSL) - Allows Windows users to run Golem within Windows Subsystem for Linux. Removing the requirement of Windows users needing to use a Virtual Machine.
*   [Golem Provider Terraform (⭐2)](https://github.com/nemani/golem-provider-terraform) - Terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
*   [Automatic Golem (⭐7)](https://github.com/r34x/Automatic-Golem) - Setup a Golem Provider with simple instructions and logs guiding you through the process.
*   [Golem Provider Node (⭐12)](https://github.com/alexandre-abrioux/golem-node) - Docker version of a node to help you get started running as a provider in a Docker container quick.
*   [Golem Provider node (⭐4)](https://github.com/blue-notes-robot/golem-node) - Fork of Alxexandre-abrioux project above that allows to dynamically generate config files from ENV variables and specify how many replicas you'd like to spawn.
*   [Scalable golem provider (⭐0)](https://github.com/cryptobench/scaleable-golem-provider) - Spawn x amount of providers using Docker.

## Learning Resources

### Presentations and Workshop Material

*   [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - Live workshop diving into how any developer with Python or JS coding experience can start build applications running on Golem.
*   [Golem: Growing an ecosystem the Golem way with María Paula Fernández at 0xHack](https://youtu.be/FmrdyU90NVE) - High-level overview and introduction to Golem as a project.
*   [Golem Workshop at H3LLO Decentralization](https://gist.github.com/zakaprov/5366bffa49b3c116748bf9b5b73c602c) - List of resources containing a live-coding hackathon workshop and relevant resources to help developers understand and requesting on Golem.
*   [Mainnet Requestor quickstart Walk-through](https://youtu.be/GcdTq3i_wdY) - Video walk-through of the requestor quick-start handbook guide to get a request on Golem Network testnet and then mainnet using the Yagna Python API.
*   [Mainnet Provider quickstart Walk-through](https://youtu.be/RITdKtEOV_E) - Video walk-through of the provider handbook guide to start sharing computational resources the Golem Network.

### Unraveling Golem's The Next Milestone Blog Series

*   [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - Introduction to the Yagna implementation of Golem.
*   [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - Fundamental architectural concepts which constitute the foundations of the new implemenation of Golem, Yagna.
*   [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - The elements of Golem's reference architecture, and illustrates how they interact to form a working ecosystem, being the Golem Network.

### GitHub Digest Blog Series

*   [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - Understanding the Golem Repositories.
*   [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - Diving into the Golem Repositories.
*   [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - Diving into Pull Requests of the Golem repositories.
*   [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - Diving into latest releases in the Golem repositories.
*   [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - Diving into the Golem alpha testnet.
*   [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - SGX proof-of-concept for Golem.
*   [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Decentralization of the Golem marketplace.
*   [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - Awesome Golem and next steps to Alpha 3.
*   [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD provider support, network metrics and improved proposal handling.
*   [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - Improvements from community feedback.
*   [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - Easy log collection.
*   [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - We are on MAINNET and gathering feedback.
*   [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - Progressing faster with the help of the Golem community.
*   [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - Towards the next major release.
*   [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - Awesome, Goth improvements and towards Beta 3.
*   [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - VPN, ARM binaries for requestors, and custom usage counters.

## Community

*   [Golem Network Discussion Group](https://t.me/GolemProject) - Community driven Telegram channel.
*   [Reddit Golem Stat Bot (⭐3)](https://github.com/figurestudios/golem-stat-bot) - Scrapes Reddit posts on /r/GolemProject, and replies if specific keywords/commands are found.
*   [Golem God](https://github.com/Shreyas-Dev-ITB/Golem-God) - Gives out "bot coins" for activity, and lets users exchange and withdraw them to tokens when they have enough.

## Contributing

Pull requests and issues with suggestions to Awesome Golem are welcome! Please read the [contributing](https://github.com/golemfactory/awesome-golem/blob/main/README.md/contributing.md) guidelines before submitting a PR.

