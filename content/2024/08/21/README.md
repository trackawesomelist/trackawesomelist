# Awesome List Updates on Aug 21, 2024

12 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Retrieval-Augmented Generation: Research Papers**

*   <details>

    <summary>Expand: Benchmarking Large Language Models in Retrieval-Augmented Generation</summary>

    1.  Noise robustness (External documents contain noises, struggled with noise above 80%)

    2.  Negative rejection (External documents are all noises, Highest rejection rate was only 45%)

    3.  Information integration (Difficulty in summarizing across multiple documents, Highest accuracy was 60-67%)

    4.  Counterfactual robustness (Failed to detect factual errors in counterfactual external documents.)

    </details>

### **LlamaIndex**

*   [Building and Productionizing RAG](https://docs.google.com/presentation/d/1rFQ0hPyYja3HKRdGEgjeDxr0MSE8wiQ2iu4mDtwR6fc/edit#slide=id.p): [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/archive/LlamaIndexTalk_PyDataGlobal.pdf): Optimizing RAG Systems 1. Table Stakes 2. Advanced Retrieval: Small-to-Big 3. Agents 4. Fine-Tuning 5. Evaluation \[Nov 2023]
*   [A Cheat Sheet and Some Recipes For Building Advanced RAG](https://blog.llamaindex.ai/a-cheat-sheet-and-some-recipes-for-building-advanced-rag-803a9d94c41b) RAG cheat sheet shared above was inspired by [RAG survey paper](https://arxiv.org/abs/2312.10997). [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/advanced-rag-diagram-llama-index.png) \[Jan 2024]
*   [Fine-Tuning a Linear Adapter for Any Embedding Model](https://medium.com/llamaindex-blog/fine-tuning-a-linear-adapter-for-any-embedding-model-8dd0a142d383): Fine-tuning the embeddings model requires you to reindex your documents. With this approach, you do not need to re-embed your documents. Simply transform the query instead. \[7 Sep 2023]
*   4 RAG techniques implemented in [llama\_index (⭐34k)](https://github.com/jerryjliu/llama_index) / [cite](https://x.com/ecardenas300/status/1704188276565795079) \[20 Sep 2023] / [git (⭐432)](https://github.com/weaviate/recipes/tree/main/integrations/llamaindex)
*   SQL Router Query Engine: Query router that can reference your vector database or SQL database
*   Sub Question Query Engine: Break down the complex question into sub-questions
*   Recursive Retriever + Query Engine: Reference node relationships, rather than only finding a node (chunk) that is most relevant.
*   Self Correcting Query Engines: Use an LLM to evaluate its own output.

### **RLHF (Reinforcement Learning from Human Feedback) & SFT (Supervised Fine-Tuning)** / **Llama Finetuning**

*   `Supervised Fine-Tuning (SFT)` fine-tuning a pre-trained model on a specific task or domain using labeled data. This can cause more significant shifts in the model’s behavior compared to RLHF. <br/> <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/rlhf-dpo.png" width="400" />

### **Large Language Models (in 2023)** / **GPT series release date**

*   [LLM Pre-training and Post-training Paradigms](https://sebastianraschka.com/blog/2024/new-llm-pre-training-and-post-training.html) \[17 Aug 2024] <br/> <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/llm-dev-pipeline-overview.png" width="350" />

## [2. Awesome Polars](/content/ddotta/awesome-polars/README.md)

### Libraries/Packages/Scripts / Polars plugins

*   [polars-distance (⭐38)](https://github.com/ion-elgreco/polars-distance) - Polars plugin for pairwise distance functions by [@ion-elgreco](https://github.com/ion-elgreco).

### Libraries/Packages/Scripts / Python

*   [PDS(polars-ds) (⭐299)](https://github.com/abstractqqq/polars_ds_extension) - A modern take on data science and traditional tabular machine learning with Polars. It provides Python modules that help with EDA tasks for Polars dataframes, machine learning pipelines that are native to Polars (cleaner and faster than Sklearn). In addition, it contains Polars plugin functions that turns many common numerical, statistical functions, least squares, KNN queries, and many other ML metrics into expressions that are executable inside a Polars dataframe.[@abstractqqq](https://github.com/abstractqqq).

## [3. Awesome Go](/content/avelino/awesome-go/README.md)

### Actor Model

*   [Ergo (⭐2.7k)](https://github.com/ergo-services/ergo) - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang.
*   [Goakt (⭐79)](https://github.com/Tochemey/goakt) - Fast and Distributed Actor framework using protocol buffers as message for Golang.
*   [Hollywood (⭐1.1k)](https://github.com/anthdm/hollywood) - Blazingly fast and light-weight Actor engine written in Golang.
*   [ProtoActor (⭐5k)](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin.

### Artificial Intelligence

*   [fun](https://gitlab.com/tozd/go/fun) - The simplest but powerful way to use large language models (LLMs) in Go.

## [4. Awesome Rust](/content/rust-unofficial/awesome-rust/README.md)

### Applications / Utilities

*   [dcapal (⭐52)](https://github.com/dcapal/dcapal) - DcaPal is a free, no registration, online tool to help you keep your portfolio balanced with dollar cost averaging investments.

## [5. Awesome Kotlin](/content/KotlinBy/awesome-kotlin/README.md)

### Libraries/Frameworks / Web

*   [allangomes/kotlinwind.css (⭐6)](https://github.com/allangomes/kotlinwind.css) - Kotlin DSL for CSS based on Tailwind.

## [6. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### Accessibility / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [digital.gov](https://digital.gov/guides/accessibility-for-teams/) - Accessibility for teams guide from USA government.
*   [WAI](https://www.w3.org/WAI/) - The W3C Web Accessibility Initiative (WAI) develops standards and support materials to help you understand and implement accessibility.
*   [webaim](https://webaim.org/) - Web accessibility in mind.
*   [WAVE](https://wave.webaim.org/) - WAVE Web Accessibility Evaluation Tools.
*   [axe Accessibility Linter](https://marketplace.visualstudio.com/items?itemName=deque-systems.vscode-axe-linter) - Accessibility linting for HTML, Angular, React, Markdown, Vue, and React Native.
*   [Angular Material CDK - a11y](https://material.angular.io/cdk/a11y/overview) - The a11y package provides a number of tools to improve accessibility.
*   [PrimeNG](https://primeng.org/guides/accessibility) - PrimeNG accessibility guide.
*   [astral-accessibility (⭐18)](https://github.com/verto-health/astral-accessibility) - An open-source accessibility widget written in Angular.

## [7. Awesome Mysql](/content/shlomi-noach/awesome-mysql/README.md)

### Analysis

*   [Dolphie (⭐565)](https://github.com/charles-001/dolphie) - a modern terminal tool for real-time analytics into MySQL/MariaDB & ProxySQL

## [8. Awesome Ai Tools](/content/mahseema/awesome-ai-tools/README.md)

### Code / Developer tools

*   [AI Kernel Explorer (⭐4)](https://github.com/mathiscode/ai-kernel-explorer) - Explore the Linux kernel source code with AI-generated summaries.

### Audio / AI Music Generators

*   [Splash Pro](https://www.splashpro.com) - [Review](https://theresanai.com/splash-pro) - A versatile platform offering intuitive music creation tools for all skill levels.
*   [AIVA](https://www.aiva.ai) - [Review](https://theresanai.com/aiva) - AI composer specializing in classical and cinematic music creation.
*   [Mubert](https://www.mubert.com) - [Review](https://theresanai.com/mubert) - Real-time generative music tailored for different use cases.
*   [Soundraw](https://soundraw.io) - [Review](https://theresanai.com/soundraw) - Allows users to customize music compositions based on mood and style.
*   [Beatoven.ai](https://www.beatoven.ai) - [Review](https://theresanai.com/beatoven-ai) - AI-driven music generation focused on evoking specific emotions.
*   [Boomy](https://www.boomy.com) - [Review](https://theresanai.com/boomy) - Democratizes music creation with quick track generation and monetization.
*   [Ecrett Music](https://www.ecrettmusic.com) - [Review](https://theresanai.com/ecrett-music) - Designed for video creators, offering royalty-free music.
*   [Loudly](https://www.loudly.com) - [Review](https://theresanai.com/loudly) - Combines AI music generation with a social platform for collaboration.
*   [Soundful](https://www.soundful.com) - [Review](https://theresanai.com/soundful) - High-quality, royalty-free music for content creators.

## [9. Awesome Integration](/content/stn1slv/awesome-integration/README.md)

### Projects / API Documentation

*   [DapperDox (⭐398) (⭐397)](https://github.com/DapperDox/dapperdox) - An open-source API documentation generator and server for OpenAPI/Swagger specifications, with customizable documentation, automated updates, and easy sharing.

### Projects / Workflow engine

*   [Cadence (⭐8.1k) (⭐8.1k)](https://github.com/uber/cadence) - A fault-tolerant, stateful code platform that makes it easier to build and manage complex, long-running applications.

## [10. Awesome Mac](/content/jaywcjlove/awesome-mac/README.md)

### Reading and Writing Tools / Markdown Tools

*   [Archimedes](https://furnacecreek.org/archimedes/) - Native macOS Markdown editor geared toward mathematical writing with inline LaTeX support.

### Communication / Collaboration and Team Tools

*   [Unite](https://furnacecreek.org/unite/) - The only native GroupMe app for Mac.

## [11. Awesome Generative Deep Art](/content/filipecalegario/awesome-generative-deep-art/README.md)

### Critical Views about Generative AI

*   [Generative AI is not the panacea we’ve been promised | Eric Siegel for Big Think+ - YouTube](https://www.youtube.com/watch?v=B2zCWJBnfuE)
*   [Thoughts on GenAI by James Gosling](https://www.linkedin.com/pulse/thoughts-genai-james-gosling-nab0c/)

### Image Segmentation / Deforum

*   [Content Studio AI](https://contentstudioai.com/): Faceless Video Generator

## [12. Awesome Tailwindcss](/content/aniftyco/awesome-tailwindcss/README.md)

### UI Libraries, Components & Templates

*   🧩 [Motion Primitives](https://motion-primitives.com) - React motion components built with Tailwind CSS and Framer Motion.

---

- Prev: [Aug 22, 2024](/content/2024/08/22/README.md)
- Next: [Aug 20, 2024](/content/2024/08/20/README.md)