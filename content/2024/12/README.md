# Awesome List Updates on Mar 18 - Mar 24, 2024

45 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Cli Apps](/content/agarrharr/awesome-cli-apps/week/README.md)

### Files and Directories / Files

*   [organize-rt](https://gitlab.com/foxido/organize-rt) - organize-cli in Rust with more customization.

## [2. Awesome Godot](/content/godotengine/awesome-godot/week/README.md)

### 2D / Godot 3.2+

*   [Flappy Race (⭐25)](https://github.com/Jibby-Games/Flappy-Race) - A 2D online multiplayer game inspired by Flappy Bird and Mario Kart for desktop and HTML5.

## [3. Awesome Bitcoin](/content/igorbarinov/awesome-bitcoin/week/README.md)

### Blockchain API and Web services

*   [Bitquery.io](https://bitquery.io/) - Bitquery provides blockchain data, offering real-time streaming APIs for 40+ chains, NFT APIs, and a money flow investigation tool.

### Haskell Libraries

*   [Haskoin-core (⭐521)](https://github.com/haskoin/haskoin-core) - Haskoin Core is a library of Bitcoin and Bitcoin Cash functions written in Haskell.

### Read

*   [A Gentle Introduction to Bitcoin Core Development](https://medium.com/bitcoin-tech-talk/a-gentle-introduction-to-bitcoin-core-development-fdc95eaee6b8)

## [4. Awesome Datascience](/content/academic/awesome-datascience/week/README.md)

### Free Courses

*   [LLMOps: Building Real-World Applications With Large Language Models](https://www.comet.com/site/llm-course/) - Learn to build modern software with LLMs using the newest tools and techniques in the field.

## [5. Awesome Elixir](/content/h4cc/awesome-elixir/week/README.md)

### Artificial Intelligence

*   [GenAI (⭐13)](https://github.com/noizu-labs-ml/genai) - An extensible Generative AI Completion API Wrapper with basic chat completion with tool use support provided for Gemini, Anthropic, OpenAI, and Mistral models. ([Docs](https://hexdocs.pm/genai/GenAI.html)).

## [6. Awesome Go](/content/avelino/awesome-go/week/README.md)

### Other Software / Libraries for creating HTTP middlewares

*   [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.

## [7. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/week/README.md)

### **Retrieval-Augmented Generation: Research Papers**

*   [RAG for LLMs](https://arxiv.org/abs/2312.10997): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2312.10997)] 🏆Retrieval-Augmented Generation for Large Language Models: A Survey: `Three paradigms of RAG Naive RAG > Advanced RAG > Modular RAG`

### **Vector Database Comparison** / **Lucene based search engine with OpenAI Embedding**

*   [Is Cosine-Similarity of Embeddings Really About Similarity?](https://arxiv.org/abs/2403.05440): In linear matrix factorization, the use of regularization can impact, and in some cases, render cosine similarities meaningless. Regularization involves two objectives. The first objective applies L2-norm regularization to the product of matrices A and B, a process similar to dropout. The second objective applies L2-norm regularization to each individual matrix, similar to the weight decay technique used in deep learning. \[8 Mar 2024]

### **Microsoft Azure OpenAI relevant LLM Framework** / **Lucene based search engine with OpenAI Embedding**

*   [UFO (⭐7.5k)](https://github.com/microsoft/UFO): A UI-Focused Agent for Windows OS Interaction. \[Mar 2024]

### **LangChain Feature Matrix & Cheetsheet** / DSPy optimizer

*   [LangChain Cheetsheet KD-nuggets](https://www.kdnuggets.com/wp-content/uploads/LangChain_Cheat_Sheet_KDnuggets.pdf): LangChain Cheetsheet KD-nuggets [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/LangChain_kdnuggets.pdf) \[Aug 2023]
*   [RAG From Scratch (⭐2k)](https://github.com/langchain-ai/rag-from-scratch) \[Feb 2024]

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   [How to continue pretraining an LLM on new data](https://x.com/rasbt/status/1768629533509370279): `Continued pretraining` can be as effective as `retraining on combined datasets`. \[13 Mar 2024]

    <details>
    <summary>Expand: Continued pretraining</summary>

    Three training methods were compared:

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files\cont-pretraining.jpg" width="400"/>

    1.  Regular pretraining: A model is initialized with random weights and pretrained on dataset D1.
    2.  Continued pretraining: The pretrained model from 1) is further pretrained on dataset D2.
    3.  Retraining on combined dataset: A model is initialized with random weights and trained on the combined datasets D1 and D2.

    Continued pretraining can be as effective as retraining on combined datasets. Key strategies for successful continued pretraining include:

    1.  Re-warming: Increasing the learning rate at the start of continued pre-training.
    2.  Re-decaying: Gradually reducing the learning rate afterwards.
    3.  Data Mixing: Adding a small portion (e.g., 5%) of the original pretraining data (D1) to the new dataset (D2) to prevent catastrophic forgetting.

    </details>

### **RLHF (Reinforcement Learning from Human Feedback) & SFT (Supervised Fine-Tuning)** / **Llama Finetuning**

*   [Reinforcement Learning from Human Feedback (RLHF)](https://arxiv.org/abs/1909.08593)) is a process of pretraining and retraining a language model using human feedback to develop a scoring algorithm that can be reapplied at scale for future training and refinement. As the algorithm is refined to match the human-provided grading, direct human feedback is no longer needed, and the language model continues learning and improving using algorithmic grading alone. \[18 Sep 2019] [ref](https://huggingface.co/blog/rlhf) \[9 Dec 2022]
    *   `Proximal Policy Optimization (PPO)` is a reinforcement learning method using first-order optimization. It modifies the objective function to penalize large policy changes, specifically those that move the probability ratio away from 1. Aiming for TRPO (Trust Region Policy Optimization)-level performance without its complexity which requires second-order optimization.

### **Section 9: Applications and Frameworks** / Korean

*   [900 most popular open source AI tools](https://huyenchip.com/2024/03/14/ai-oss.html):🏆What I learned from looking at 900 most popular open source AI tools [list](https://huyenchip.com/llama-police) \[Mar 2024]

## [8. Awesome Creative Technology](/content/j0hnm4r5/awesome-creative-technology/week/README.md)

### Creative Technology

- Name: [**Artists & Engineers**](https://www.artistsandengineers.co.uk/)

  Locations: \[London]

  Keywords: production and technology studio, showrooms, concerts, art installations


- Name: [**batwin + robin productions**](https://www.batwinandrobin.com/)

  Locations: \[NYC]

  Keywords: environments, interactives, theaters, events


- Name: [**BRC Imagination Arts**](https://www.brcweb.com/)

  Locations: \[Burbank, CA] \[Edinburgh] \[Amsterdam]

  Keywords: brand and cultural stories, strategy, animation, digital and hybrid experiences


- Name: [**Bright**](https://brig.ht/)

  Locations: \[Paris]

  Keywords: data visualization, digital installations, experiential sites, video games

  Jobs: [🌐](https://brig.ht/contact)


- Name: [**Cocolab**](https://cocolab.mx/en/)

  Locations: \[Mexico City]

  Keywords: multimedia experiences, immersive walk, exhibitions, installations, multimedia museography


- Name: [**Cosm**](https://www.cosm.com/)

  Locations: \[Dallas] \[LA] \[City] \[Pittsburgh] \[Gurgaon]

  Keywords: immersive entertainment and media, planetariums, LED domes

  Jobs: [🌐](https://www.cosm.com/careers)


- Name: [**Digital Kitchen**](https://www.thisisdk.com)

  Locations: \[LA]

  Keywords: iconic main titles, multimedia content, imaginative experiences, and immersive spaces


- Name: [**DOTDOT**](https://dotdot.studio/about/)

  Locations: \[Auckland] \[NYC] \[Brisbane]

  Keywords: AR, music videos, interactive installations, games


- Name: [**Eos Lightmedia**](https://www.eoslightmedia.com/)

  Locations: \[Vancouver] \[NYC] \[Orlando]

  Keywords: lighting and audiovisual design, themed attractions, museums, architecture, public spaces, building facades, presentation centers, and public art installations


- Name: [**Midwest Immersive**](https://www.mwimmersive.com/)

  Locations: \[Chicago]

  Keywords: immersive experiences for brands and agencies, projection mapping, LED lighting, games and app development


- Name: [**Mousetrappe Media**](https://www.mousetrappe.com/)

  Locations: \[LA]

  Keywords: media design and production, architecturally mapped projection, immersive films, exhibits, attractions, and live events

  Jobs: [🌐](https://www.mousetrappe.com/244-2/jobs/)


- Name: [**Ouchhh Studio**](https://ouchhh.tv/)

  Locations: \[Istanbul]

  Keywords: public art, poetic public experiences, data as a paint, algorithm as a brush


- Name: [**Sparks**](https://www.wearesparks.com/)

  Locations: \[Philadelphia] \[Shanghai] \[Paris] \[Berlin] \[Amsterdam]

  Keywords: conferences, popups, event production, fabrication


- Name: [**Squint/Opera**](https://www.squintopera.com/about/)

  Locations: \[London] \[NYC] \[Dubai]

  Keywords: experience design for the built environment and musuems and attractions


- Name: [**Studio TheGreenEyl**](https://thegreeneyl.com/)

  Locations: \[Berlin] \[NYC]

  Keywords: exhibitions, installations, objects, images, interactions and algorithms


- Name: [**tamschick**](https://tamschick.com/)

  Locations: \[Berlin]

  Keywords: media and architectural narrative design, exhibitions, branded space, musuems

  Jobs: [🌐](https://tamschick.factorialhr.com/)


- Name: [**Tinker**](https://tinker.nl/en)

  Locations: \[Utrecht]

  Keywords: narrative spaces, musuems, experience design, consultancy


- Name: [**WHITEvoid**](https://www.whitevoid.com/)

  Locations: \[Berlin] \[Shanghai]

  Keywords: public or brand spaces and events, trade fair stands, shows and exhibitions, museums and festivals


- Name: [**y=f(x)**](https://www.yfxlab.com/)

  Locations: \[Amsterdam]

  Keywords: creative technology studio focused on the creation of overarching multimedia experiences, with specially crafted software and design



### Collectives & Practices

- Name: [**3-Legged Dog**](https://www.3ld.org/)

  Locations: \[NYC]

  Keywords: original works in theater, performance, dance, media and hybrid forms


- Name: [**NightLight Labs**](https://nightlight.io/)

  Locations: \[LA]

  Keywords: installations, activations, narrative experiences


- Name: [**Ultravioletto**](https://ultraviolet.to/)

  Locations: \[Rome]

  Keywords: exhibitions, fairs, museums, brand experiences and events



### Fabricators

- Name: [**5 Ten**](https://www.510visuals.com/)

  Locations: \[NYC]

  Keywords: LED technology design, fabrication, and integration


- Name: [**Bridgewater Studio**](https://www.bridgewaterstudio.net)

  Locations: \[Chicago]

  Keywords: full service design and fabrication

  Jobs: [🌐](https://www.bridgewaterstudio.net/about)



### Museums

- Name: [**Grumpy Sailor**](https://www.grumpysailor.com/)

  Locations: \[Sydney] \[Melbourne]

  Keywords: digital experiences, exhibit design, brands


- Name: [**RLMG**](https://www.rlmg.com/)

  Locations: \[Boston]

  Keywords: story-driven, interactive, dynamic, immersive, and educational installations for public spaces.



## [9. Awesome Transit](/content/CUTR-at-USF/awesome-transit/week/README.md)

### Reference resources

*   [GTFS.org](https://gtfs.org) official documentation site for the General Transit Feed Specification. Includes additional GTFS resources.
*   [Google Transit Developers](https://developers.google.com/transit/gtfs/) additional Google-specific documentation of GTFS.
*   [World Bank: Intro. to GTFS](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) free, online, self-paced course for learning about GTFS and GTFS Realtime.

### Local and regional groups

*   [German Open Transport Data Quality Meetup (⭐41)](https://github.com/transportkollektiv/meetup/wiki) - Bimonthly online meetup of the German-speaking open transport community dedicated to data quality.

### 3rd party GTFS URL directories

*   [The Mobility Database](https://mobilitydatabase.org/) - JSON and CSV files [on GitHub (⭐251)](https://github.com/MobilityData/mobility-database-catalogs) that is a repository of 2000+ mobility datasets across the world. Contains contents of OpenMobilityData/TransitFeeds.com.

## [10. Awesome Workflow Automation](/content/dariubs/awesome-workflow-automation/week/README.md)

### Tools

*   **[Zapier](https://zapier.com/)** - *[Review](https://productivity.directory/zapier)*: Simplifies workflow automation by connecting your apps and services.
*   **[IFTTT](https://ifttt.com/)** - *[Review](https://productivity.directory/ifttt)*: Enables integration and innovation across different platforms.
*   **[Microsoft Power Automate](https://flow.microsoft.com/)** - *[Review](https://productivity.directory/microsoft-power-automate)*: Focuses on streamlining repetitive tasks and paperless processes.
*   **[Make (formerly Integromat)](https://www.make.com/)** - *[Review](https://productivity.directory/make)*: Provides a platform for creative and efficient workflow automation.
*   **[ClickUp](https://clickup.com/)** - *[Review](https://productivity.directory/clickup)*: Serves as an all-in-one, customizable workspace.
*   **[Smartsheet](https://www.smartsheet.com/)** - *[Review](https://productivity.directory/smartsheet)*: Offers dynamic work management using a flexible platform.
*   **[Wrike](https://www.wrike.com/)** - *[Review](https://productivity.directory/wrike)*: Provides robust project management capabilities.
*   **[Airtable](https://airtable.com/)** - *[Review](https://productivity.directory/airtable)*: Facilitates building custom apps to meet workflow needs.
*   **[Lucidchart](https://www.lucidchart.com/)** - *[Review](https://productivity.directory/lucidchart)*: Offers diagramming for better workflow visualization.
*   **[ActivePieces](https://www.activepieces.com/)** - *[Review](https://productivity.directory/activepieces)*: An open-source tool for all-in-one automation.
*   **[n8n](https://n8n.io/)** - *[Review](https://productivity.directory/n8n)*: Specializes in technical workflow automation.
*   **[Automatisch](https://automatisch.io/)** - *[Review](https://productivity.directory/automatisch)*: An open-source business automation tool, similar to Zapier.
*   **[Huginn (⭐43k)](https://github.com/huginn/huginn)** - *[Review](https://productivity.directory/huginn)*: Allows the creation of agents that perform automated tasks online.

### Resources

*   [Productivity Tools List](https://productivity.directory) - A curated list of productivity tools and apps.

## [11. Awesome Opentofu](/content/virtualroot/awesome-opentofu/week/README.md)

### Media / Helpers

*   [CNCF - OpenTofu Day 2024](https://www.youtube.com/playlist?list=PLnVotLM2Qsyiw_6Pd_9WxRRLdrUAs3c1c)

## [12. Awesome Lowcode](/content/antdimot/awesome-lowcode/week/README.md)

### Marketing

*   [Datawave](https://datawave.app) - Startup Marketing Platform

## [13. Awesome Music](/content/ciconia/awesome-music/week/README.md)

### Music Notation

*   [mei-friend](https://mei-friend.mdw.ac.at) - a friendly, browser-based editor for music encodings.

## [14. Awesome Product Design](/content/ttt30ga/awesome-product-design/week/README.md)

### Methods / Decision Making

*   [Untools](https://untools.co) - Thinking tools and frameworks to help you solve problems, make decisions and understand systems.

### Methods / Research Plan

*   [Branding5](https://www.branding5.com/) - Make a brand positioning as a basis for your designs.

## [15. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/week/README.md)

### Software / Database Management

*   [CloudBeaver](https://dbeaver.com/) - Self-hosted management of databases, supports PostgreSQL, MySQL, SQLite and more. A web/hosted version of DBeaver. ([Source Code (⭐3.3k)](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`

### Software / File Transfer - Single-click & Drag-n-drop Upload

*   [Pairdrop (⭐4.2k)](https://github.com/schlagmichdoch/pairdrop) - Local file sharing in your browser, inspired by Apple's AirDrop (fork of Snapdrop). `GPL-3.0` `Docker`

### Software / Media Streaming - Video Streaming

*   [Tube Archivist](https://tubearchivist.com/) `⚠` - Organize, search, and enjoy your YouTube collection. Subscribe, download, and track viewed content with metadata indexing and a user-friendly interface. ([Source Code (⭐4.7k)](https://github.com/tubearchivist/tubearchivist), [Clients](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`

### Software / Miscellaneous

*   [beelzebub](https://beelzebub-honeypot.com/) `⚠` - Honeypot framework designed to provide a highly secure environment for detecting and analyzing cyber attacks. ([Demo](https://beelzebub-honeypot.com/docs/), [Source Code (⭐640)](https://github.com/mariocandela/beelzebub)) `MIT` `Docker/K8S/Go`

## [16. Awesome Tailwindcss](/content/aniftyco/awesome-tailwindcss/week/README.md)

### Tools

*   💼 [Gimli Tailwind](https://chromewebstore.google.com/detail/gimli-tailwind/fojckembkmaoehhmkiomebhkcengcljl) - Smart tools for Tailwind CSS as a browser extension.

## [17. Static Analysis](/content/analysis-tools-dev/static-analysis/week/README.md)

### Programming Languages / [Other](#other-1)

*   [DelphiLint (⭐79)](https://github.com/integrated-application-development/delphilint) — A Delphi IDE package providing on-the-fly code analysis and linting, powered by SonarDelphi.

## [18. Awesome Ai in Finance](/content/georgezouq/awesome-ai-in-finance/week/README.md)

### Others / Plugins

*   [Floom (⭐24)](https://github.com/FloomAI/Floom) AI gateway and marketplace for developers, enables streamlined integration and least volatile approach of AI features into products

## [19. Awesome Polars](/content/ddotta/awesome-polars/week/README.md)

### Resources / Blog posts

*   [How to start using Polars & DuckDB together for data analysis](https://ganguly-04.medium.com/how-to-start-using-polars-duckdb-together-for-data-analysis-ded30fcb0bd9) - A post that demonstrates the usage of Polars with DuckDB to perform similar data transformations as is done using Pandas by [@sumaniitm](https://github.com/sumaniitm).

## [20. Awesome Jmeter](/content/aliesbelik/awesome-jmeter/week/README.md)

### Best Practices

*   [Optimize JMeter for Large Scale Tests](https://blog.octoperf.com/optimize-jmeter-for-large-scale-tests/)

### Automation / Conversion

*   [har-convertor-jmeter-tool (⭐5)](https://github.com/vdaburon/har-convertor-jmeter-plugin) - Apache JMeter Plugin to convert a HAR file to a JMeter script and Record XML file.
*   [JMeter HAR Importer Plugin (⭐3)](https://github.com/Qytera-Gmbh/JMeterHARImporterPlugin) - JMeter plugin to import HTTP Archive (HAR) files into Apache JMeter.

### Performance Testing / RESTful API

*   [REST API Testing with JMeter. Step by Step Guide](https://blog.octoperf.com/rest-api-testing-with-jmeter-step-by-step-guide/)

### Community / Blogs

*   [OctoPerf Blog](https://blog.octoperf.com/categories/jmeter/) - OctoPerf blog about JMeter and load testing.

## [21. Awesome Cpp](/content/fffaraz/awesome-cpp/week/README.md)

### Concurrency

*   [libfork (⭐547)](https://github.com/ConorWilliams/libfork) - A bleeding-edge, lock-free, wait-free, continuation-stealing tasking library built on C++20's coroutines. \[MPL-2.0] [website](https://conorwilliams.github.io/libfork/)

### Miscellaneous

*   [fast\_io (⭐615)](https://github.com/cppfastio/fast_io) - Significantly faster input/output for C++20. \[MIT]

### Build Systems

*   [Ccache](https://ccache.dev/) - A fast C/C++ compiler cache. \[GPLv3]

## [22. Awesome Dotnet](/content/quozd/awesome-dotnet/week/README.md)

### Artificial Intelligence

*   [LLamaSharp (⭐2.4k)](https://github.com/SciSharp/LLamaSharp) - C#/.NET Binding of llama.cpp, run LLaMA/GPT model using C# without having to compile lama.cpp.

### Compilers, Transpilers and Languages

*   [IKVM](https://ikvm.org) - A Java Virtual Machine and Bytecode-to-IL Converter for .NET. Execute compiled Java code (bytecode) on .NET Framework or .NET Core.
*   [Lib.Harmony (⭐5.1k)](https://github.com/pardeike/Harmony) - Rewrite mono and C# methods at the runtime, Either write a method that will be executed, or edit the code of the method in IL, mainly used for game modding.

### Tools

*   [OctaneEngine (⭐227)](https://github.com/gregyjames/OctaneDownloader) - A high preformance multipart downloader with many features such as pause/resume support, asynchronous progress, and throttling.

### WPF

*   [DeftSharp.Windows.Input (⭐58)](https://github.com/Empiree/DeftSharp.Windows.Input) - A simple keyboard/mouse event handler for Windows UI applications (WPF, MAUI, Avalonia)

### Parser Library

*   [Parakeet (⭐66)](https://github.com/ara3d/parakeet) - A recursive descent parsing library with operator overloading for C#.

## [23. Awesome Acg](/content/soruly/awesome-acg/week/README.md)

### Mobile Apps

*   [Mihon (⭐8.8k)](https://github.com/mihonapp/mihon) - Free and open source manga reader for Android. \[English]

## [24. ALL About RSS](/content/AboutRSS/ALL-about-RSS/week/README.md)

### Miniflux / Outline Processor Markup Language

*   [miniflux-theme-reeder (⭐99)](https://github.com/rootknight/Miniflux-Theme-Reeder) [![Open-Source Software](https://github.com/AboutRSS/ALL-about-RSS/raw/master/media/open-source.png)](https://github.com/rootknight/Miniflux-Theme-Reeder)

## [25. Awesome Langchain](/content/kyrolabs/awesome-langchain/week/README.md)

### Other LLM Frameworks / Videos Playlists

*   [uAgents (⭐795)](https://github.com/fetchai/uAgents): A fast and lightweight framework for creating decentralized agents with ease. ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=social)

## [26. Awesome Embedded Rust](/content/rust-embedded/awesome-embedded-rust/week/README.md)

### no-std crates / WIP

*   [lakers](https://crates.io/crates/lakers): Microcontroller-optimized [EDHOC](https://datatracker.ietf.org/doc/draft-ietf-lake-edhoc/) implementation, with bindings for C and Python - ![crates.io](https://img.shields.io/crates/v/lakers.svg)

## [27. Awesome Clojure](/content/razum2um/awesome-clojure/week/README.md)

### Data Validation

*   [Guardrails (⭐221)](https://github.com/fulcrologic/guardrails)
*   [Malli (⭐1.4k)](https://github.com/metosin/malli)

## [28. Awesome Integration](/content/stn1slv/awesome-integration/week/README.md)

### Resources / API Specification

*   [OpenAPI (ex.Swagger) (⭐28k) (⭐29k)](https://github.com/OAI/OpenAPI-Specification) - A language-agnostic specification for creating RESTful APIs that enables both humans and machines to understand the capabilities of a service without the need for source code or documentation.

## [29. Awesome Game Remakes](/content/radek-sprta/awesome-game-remakes/week/README.md)

### FPS

*   [SurrealEngine (⭐409)](https://github.com/dpjudas/SurrealEngine) - The goal of this project is to reimplement enough of the original Unreal Engine to make the Unreal Tournament (UT99) maps playable.

### Simulator

*   [Free Stars: The Ur-Quan Masters](https://sc2.sourceforge.net/) - Open source version of the classic Star Control 2.

## [30. Awesome Cyber Security University](/content/brootware/awesome-cyber-security-university/week/README.md)

### Free Beginner Blue Team Path / Level 1 - Tools

*   [Volatility](https://cyberdefenders.org/blueteam-ctf-challenges/redline/) - Intro to memory analysis with volatility.

## [31. Awesome Falsehood](/content/kdeldycke/awesome-falsehood/week/README.md)

### Emails

*   [`libvldmail`](https://github.com/dertuxmalwieder/libvldmail) - A library that implements RFC-based checks for e-mail addresses.

## [32. Free for Dev](/content/ripienaar/free-for-dev/week/README.md)

### PaaS

*   [appwrite](https://appwrite.io) - Unlimited projects with no project pausing (supports websockets) and authentication service. 1 Database, 3 Buckets, 5 Functions per project in free tier.

### Tunneling, WebRTC, Web Socket Servers and Other Routers

*   [serveo](https://serveo.net/) — Expose local servers to the internet. No installation, no signup. Free subdomain, no limits.

## [33. Awesome Typescript](/content/dzharii/awesome-typescript/week/README.md)

### Tools / Playground

*   [ParaglideJS](https://inlang.com/m/gerre34r/library-inlang-paraglideJs) - An i18n compiler that generates fully typesafe translations

### Web / Playground

*   :octocat: [Langfuse (⭐4.9k)](https://github.com/langfuse/langfuse) - Open source LLM engineering platform 🪢 - Tracing, Prompt Mgmt, Evaluations, Analytics

## [34. Awesome Neovim](/content/rockerBOO/awesome-neovim/week/README.md)

### Web Development / Diagnostics

*   [luckasRanarison/tailwind-tools.nvim (⭐309)](https://github.com/luckasRanarison/tailwind-tools.nvim) - Unofficial TailwindCSS tooling.

### Tree-sitter Supported Colorscheme / Diagnostics

*   [kevinm6/kurayami.nvim (⭐6)](https://github.com/kevinm6/kurayami.nvim) - Dark (only) theme.
*   [loganswartz/sunburn.nvim (⭐14)](https://github.com/loganswartz/sunburn.nvim) - A colorscheme sitting somewhere between pastels and solarized, emphasizing readability and hue uniformity above all else.

### Colorscheme Creation / Diagnostics

*   [loganswartz/polychrome.nvim (⭐16)](https://github.com/loganswartz/polychrome.nvim) - A colorscheme micro-framework, with support for specifying colors directly in many different formats (sRGB, HSL, Oklab, XYZ and more, with intelligent chroma clipping), live editing preview, and a simple DSL.

### Debugging / Diagnostics

*   [Willem-J-an/visidata.nvim (⭐20)](https://github.com/Willem-J-an/visidata.nvim) - Render pandas dataframes in nvim-dap using the power of visidata.

### Preconfigured Configuration / Diagnostics

*   [StratOS-Linux/StratVIM (⭐12)](https://github.com/StratOS-Linux/StratVIM) - A full-fledged Neovim distribution included by default in [StratOS](https://github.com/StratOS-Linux), an upcoming Arch-based Linux distro.

## [35. Awesome Directus](/content/directus-community/awesome-directus/week/README.md)

### Extensions / Community

*   [Umami Analytics (⭐0)](https://github.com/egidiusmengelberg/directus-extension-umami) - Add Umami analytics to Directus.

## [36. Urban and Regional Planning Resources](/content/APA-Technology-Division/urban-and-regional-planning-resources/week/README.md)

### Platforms and Software Resources / AI in Planning Tools and Platforms

*   [Anthropic](https://www.anthropic.com/) - Anthropic provides access to a class of advanced large language models called Claude designed to provide human-like text responses and engage in conversational interactions.

### Platforms and Software Resources / Economic Development and Econometric Platforms

*   [Remi](https://www.remi.com/) - REMI is a leading provider of state, local, and national macroeconomic policy analysis models.

## [37. Awesome Playcanvas](/content/playcanvas/awesome-playcanvas/week/README.md)

### AR/VR/XR

*   [Viverse](https://www.viverse.com/) - Open platform for virtual worlds and environments developed by HTC.

## [38. Awesome Terraform](/content/shuaibiyy/awesome-terraform/week/README.md)

### Providers / Vendor supported providers

*   [terraform-provider-coder (⭐29)](https://github.com/coder/terraform-provider-coder) - Provider for [Coder](https://coder.com)

### Tools / Community providers

*   [asdf (⭐232)](https://github.com/asdf-community/asdf-hashicorp) - HashiCorp plugin for the [asdf (⭐21k)](https://github.com/asdf-vm/asdf) version manager

## [39. Awesome Quant](/content/wilsonfreitas/awesome-quant/week/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Finance (⭐1.8k)](https://github.com/shashankvemuri/Finance) - 150+ quantitative finance Python programs to help you gather, manipulate, and analyze stock market data.
*   [101\_formulaic\_alphas (⭐12)](https://github.com/ram-ki/101_formulaic_alphas) - Implementation of [101 formulaic alphas](https://arxiv.org/ftp/arxiv/papers/1601/1601.00991.pdf) using qstrader.

## [40. Awesome Vite](/content/vitejs/awesome-vite/week/README.md)

### Templates / React

*   [ReTail (⭐1)](https://github.com/nikolailehbrink/retail) - Starter template for building Full Stack WEB applications with `Remix` using `TypeScript`, `Tailwind CSS`, `Prettier` and `ESLint`.
*   [vite-react-redux-saga-typescript (⭐2)](https://github.com/Dulajdeshan/vite-react-redux-saga-typescript) - Starter template with `React`, `TypeScript`, `Redux (Redux Toolkit)`, `Saga`, `React Testing Library`, `ESLint`, `Prettier` and `Husky`.

### Templates / GitHub

*   [github-action-template (⭐8)](https://github.com/hywax/github-action-template) - Starter template for GitHub Actions, Typescript, ESLint, Vitest, Husky, Conventional Commits.

### Framework-agnostic Plugins / Integrations

*   [vite-plugin-px-rem-vw (⭐6)](https://github.com/zscumt123/vite-plugin-px-rem-vw) - Integrate PostCSS plugin pxTorem and pxTovw.

### Framework-agnostic Plugins / Bundling

*   [vite-plugin-robots (⭐7)](https://github.com/kolirt/vite-plugin-robots) - Generating `robots.txt`.

### Framework-agnostic Plugins / Transformers

*   [@tomjs/vite-plugin-html (⭐3)](https://github.com/tomjs/vite-plugin-html) - Support compression, loading, CDN and others for `index.html`.
*   [@tomjs/vite-plugin-iconify (⭐2)](https://github.com/tomjs/vite-plugin-iconify) - Inject the global variable `IconifyProviders` into `index.html` for `iconify`, and support local area network and custom url.

### Framework-agnostic Plugins / Helpers

*   [vite-plugin-vitepress-auto-nav (⭐16)](https://github.com/Xaviw/vite-plugin-vitepress-auto-nav) - Automatically generates `sidebar` and `nav` configurations by scanning directories, based on VitePress.

### Libraries / Community

*   [Vinxi (⭐1.6k)](https://github.com/nksaraf/vinxi) - The Full Stack JavaScript SDK. Allows adding SSR to a Vite app.

## [41. Awesome Data Engineering](/content/igorbarinov/awesome-data-engineering/week/README.md)

### Data Lake Management

*   [Project Nessie (⭐937)](https://github.com/projectnessie/nessie) - Project Nessie is a Transactional Catalog for Data Lakes with Git-like semantics. Works with Apache Iceberg tables.

### Community / Podcasts

*   [The Data Stack Show](https://datastackshow.com/) - A show where they talk to data engineers, analysts, and data scientists about their experience around building and maintaining data infrastructure, delivering data and data products, and driving better outcomes across their businesses with data.

## [42. Awesome Agi Cocosci](/content/YuzheSHI/awesome-agi-cocosci/week/README.md)

### Domain Specific Language / Design Practises

*   [No Grammar to Rule Them All: A Survey of JSON-style DSLs for Visualization](https://ieeexplore.ieee.org/abstract/document/9904438) - ***IEEE Transactions on Visualization and Computer Graphics***, 2022. \[[All Versions](https://scholar.google.com/scholar?cluster=17206818917381447796)]. A survey on the design and implementation of 57 JSON-style DSLs for a variety of visualization and visual interaction tasks, suggesting that no one DSL will be able to capture all of them without compromising essential parts of its domain design.

### Domain Specific Language / Declarative DSL Applications

*   [OpenLaw](https://docs.openlaw.io/) - ***OpenLaw\.io***. It is now possible to model all or parts of legal agreements using code (smart contracts), decreasing the cost and friction of creating, securing, and generating binding legal agreements. Lawyers lack basic tools to build these dynamic, “smart” contracts in a way that is enforceable and understandable to a legal professional. OpenLaw is a technology stack to help power next generation "smart" legal agreements, with a domain-specific markup language, a integration framework, and a series of general applications.

### Domain Specific Language / DSL Program Synthesis

*   [Errors are Useful Prompts: Instruction Guided Task Programming with Verifier-Assisted Iterative Prompting](https://arxiv.org/abs/2303.14100) - 2023. \[[All Versions](https://scholar.google.com/scholar?cluster=8063693456660536915)]. \[[Code (⭐37)](https://github.com/ac-rad/xdl-generation)]. \[[Website](https://ac-rad.github.io/clairify/)]. This paper proposes CLAIRIFY, an approach that combines automatic iterative prompting with program verification to ensure programs written in data-scarce domain-specific language are syntactically valid and incorporate environment constraints.

## [43. Awesome Rust](/content/rust-unofficial/awesome-rust/week/README.md)

### Libraries / Network programming

*   VPN
    *   [defguard/wireguard-rs (⭐135)](https://github.com/DefGuard/wireguard-rs) - A multi-platform library providing a unified high-level API for managing WireGuard interfaces using native OS kernel and userspace WireGuard protocol implementations

### Libraries / Peripherals

*   Fingerprint reader
    *   [alvaroparker/libfprint-rs (⭐11)](https://github.com/alvaroparker/libfprint-rs) \[[libfprint-rs](https://crates.io/crates/libfprint-rs)] - Libfprint-rs provides a wrapper around the Linux libfprint library.

## [44. Awesome Mac](/content/jaywcjlove/awesome-mac/week/README.md)

### Reading and Writing Tools / Others

*   [Highlights](https://highlightsapp.net) - The PDF Reader for Research on Mac, iPad & iPhone. ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

## [45. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/week/README.md)

### [zsh-mgr](https://github.com/amt911/zsh-mgr)

*   Auto-updates all plugins.
*   Auto-updates itself.
*   Configurable time interval for both auto-updaters.

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [git-switch-branch-skim (⭐0)](https://github.com/okhiroyuki/zsh-git-switch-branch-skim) - Allows you to switch `git` branches with [skim (⭐5k)](https://github.com/lotabout/skim)
*   [select-history-skim (⭐0)](https://github.com/okhiroyuki/zsh-select-history-skim) Rummage through your history with [skim (⭐5k)](https://github.com/lotabout/skim).
*   [tinted-shell (⭐59)](https://github.com/tinted-theming/tinted-shell) - Adds a script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [bahman (⭐1)](https://github.com/bahmanworld/bahman-zsh-theme) - Requires Nerd Font. Has `git` status decorator.
*   [bigshrimp (⭐1)](https://github.com/taksyon/BigShrimp-zsh-theme) - A clear and concise theme that includes decorators for username\@host, current directory and `git` status.
*   [tho (⭐0)](https://github.com/codingtho/tho-zsh-theme) - Includes decorators for `git` status & current directory.

---

- Prev: [Mar 25 - Mar 31, 2024](/content/2024/13/README.md)
- Next: [Mar 11 - Mar 17, 2024](/content/2024/11/README.md)