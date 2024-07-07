# Awesome List Updates on Jun 14, 2024

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Blazor](/content/AdrienTorris/awesome-blazor/README.md)

### Videos / Others

*   [Blazor and Orchard Core with Peter Matthews - Orchard Core Pair Programming by Lombiq](https://www.youtube.com/watch?v=IZioflrC1Ho) - June 17, 2024 - Join this session of Orchard Core Pair Programming by Lombiq! In these, we do an hour of pair programming with an Orchard Core community member about a project of theirs. We learn together a lot, share best practices, and write some good code. All this is live, and you can join us with your questions!
*   [Building Real-Time Web Applications with Blazor and Akka.NET](https://www.youtube.com/watch?v=jRYVp_lySl8) - ![duration](https://img.shields.io/badge/Duration:%20-79%20min-%230094FF?style=flat-square\&cacheSeconds=maxAge\&logo=youtube) June 13, 2024 - This talk presents how you can use Akka.NET and Blazor to build scalable, streaming web applications without JavaScript or any fuss. Pure C# end to end.
*   [ASP.NET Community Standup: Static web asset improvements in .NET 9](https://www.youtube.com/watch?v=PkQgcEUCnQk) - ![duration](https://img.shields.io/badge/Duration:%20-57%20min-%230094FF?style=flat-square\&cacheSeconds=maxAge\&logo=youtube) June 11, 2024 - Learn about some of the static web asset improvements coming in .NET 9.

### Articles / Others

*   [Blazor Basics: Blazor Render Modes in .NET 8](https://www.telerik.com/blogs/blazor-basics-blazor-render-modes-net-8) - June 12, 2024 - This article is about the new Blazor render modes in .NET 8, including ServerInteractivity, WebAssemblyInteractivity, AutoInteractivity and static server-side rendering (SSR).
*   [The usage of Blazor.Diagrams](https://www.slaveoftime.fun/blog/the-usage-of-blazor.diagrams) - June 11, 2024 - How to use Blazor.Diagrams.

## [2. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### Blogs / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [Tomasz Ducin](https://ducin.dev/blog)

### Books / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [Angular for Enterprise Applications](https://angularforenterprise.com/home) - `Packt Publishing`

### Node / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [create-tauri-app (⭐940)](https://github.com/tauri-apps/create-tauri-app) - Rapidly scaffold out a new Tauri app project.

### Markdown / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-remark (⭐5)](https://github.com/ericleib/ngx-remark) - Render markdown with custom Angular templates.

## [3. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Vector Database Comparison**

*   [pgvector (⭐10k)](https://github.com/pgvector/pgvector): Open-source vector similarity search for Postgres \[Apr 2021] / [pgvectorscale (⭐612)](https://github.com/timescale/pgvectorscale): 75% cheaper than pinecone \[Jul 2023]

### **DSPy** / DSPy optimizer

*   Automatic Few-Shot Learning

    *   As a rule of thumb, if you don't know where to start, use `BootstrapFewShotWithRandomSearch`.

    *   If you have very little data, e.g. 10 examples of your task, use `BootstrapFewShot`.

    *   If you have slightly more data, e.g. 50 examples of your task, use `BootstrapFewShotWithRandomSearch`.

    *   If you have more data than that, e.g. 300 examples or more, use `BayesianSignatureOptimizer`.
*   Automatic Instruction Optimization

    *   `COPRO`: Repeat for a set number of iterations, tracking the best-performing instructions.

    *   `MIPRO`: Repeat for a set number of iterations, tracking the best-performing combinations (instructions and examples).
*   Automatic Finetuning

    *   If you have been able to use one of these with a large LM (e.g., 7B parameters or above) and need a very efficient program, compile that down to a small LM with `BootstrapFinetune`.

### **Prompt Guide & Leaked prompts** / **Prompt Template Language**

*   [In-The-Wild Jailbreak Prompts on LLMs (⭐1.6k)](https://github.com/verazuo/jailbreak_llms): A dataset consists of 15,140 ChatGPT prompts from Reddit, Discord, websites, and open-source datasets (including 1,405 jailbreak prompts). Collected from December 2022 to December 2023 \[Aug 2023]

### **Finetuning** / **Prompt Template Language**

*   [LoRA learns less and forgets less](https://arxiv.org/abs/2405.09673): Compared to full training, LoRA has less learning but better retention of original knowledge. \[15 May 2024]

### **Other techniques and LLM patterns** / **Llama 2 Finetuning**

*   [What We’ve Learned From A Year of Building with LLMs](https://applied-llms.org/): A practical guide to building successful LLM products, covering the tactical, operational, and strategic.  \[8 June 2024]
*   [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752) \[1 Dec 2023] [git (⭐12k)](https://github.com/state-spaces/mamba): 1. Structured State Space (S4) - Class of sequence models, encompassing traits from RNNs, CNNs, and classical state space models. 2. Hardware-aware (Optimized for GPU) 3. Integrating selective SSMs and eliminating attention and MLP blocks [ref](https://www.unite.ai/mamba-redefining-sequence-modeling-and-outforming-transformers-architecture/) / A Visual Guide to Mamba and State Space Models [ref](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mamba-and-state) \[19 FEB 2024]
    *   [Mamba-2](https://arxiv.org/abs/2405.21060): 2-8X faster \[31 May 2024]

### **Trustworthy, Safe and Secure LLM** / **GPT series release date**

*   [Extracting Concepts from GPT-4](https://openai.com/index/extracting-concepts-from-gpt-4/): Sparse Autoencoders identify key features, enhancing the interpretability of language models like GPT-4. They extract 16 million interpretable features using GPT-4's outputs as input for training. \[6 Jun 2024]

### **MLLM (multimodal large language model)** / **GPT series release date**

*   [MiniCPM-V (⭐7.9k)](https://github.com/OpenBMB/MiniCPM-V): MiniCPM-Llama3-V 2.5: A GPT-4V Level Multimodal LLM on Your Phone \[Jan 2024]

### **Section 9: Applications and Frameworks** / Korean

*   [Awesome LLM Apps (⭐2.4k)](https://github.com/Shubhamsaboo/awesome-llm-apps): A curated collection of awesome LLM apps built with RAG and AI agents. \[Apr 2024]

### **LLMOps: Large Language Model Operations** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   [Ragas (⭐5.7k)](https://github.com/explodinggradients/ragas): Evaluation framework for your Retrieval Augmented Generation (RAG) \[May 2023]
*   [DeepEval (⭐2.4k)](https://github.com/confident-ai/deepeval): LLM evaluation framework. similar to Pytest but specialized for unit testing LLM outputs. \[Aug 2023]

## [4. Awesome Ironsworn](/content/Billiam/awesome-ironsworn/README.md)

### Resources / Ironsworn

*   [Starforged Moves Starter](https://akavel.itch.io/starforged-moves-starter) - Cheatsheet of the most important moves in Starforged, aimed especially at new players
*   [Starswoosh](https://www.drivethrurpg.com/en/product/443900/Starswoosh-An-Ironsworn-Starforged-Quick-Reference-For-Your-eReader) - Starforged quick reference for e-readers

## [5. Awesome Inertiajs](/content/innocenzi/awesome-inertiajs/README.md)

### Adapters / Server-side

*   💜 [Django (⭐248)](https://github.com/inertiajs/inertia-django)
*   💜 [Phoenix (⭐68)](https://github.com/inertiajs/inertia-phoenix)
*   [Phoenix (⭐85)](https://github.com/devato/inertia_phoenix)

## [6. Awesome Vue](/content/vuejs/awesome-vue/README.md)

### Components & Libraries / UI Components

*   [vue-wheel-spinner (⭐1)](https://github.com/ilyasozkurt/vue-wheel-spinner) - A simple, customizable wheel of fortune component. [See Demo](https://vue-wheel-spinner-demo.vercel.app/)

## [7. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Utility / Diagnostics

*   [ChuufMaster/buffer-vacuum (⭐7)](https://github.com/ChuufMaster/buffer-vacuum) - Set a maximum number of buffers to keep open and intelligently delete the oldest buffers over the maximum.

---

- Prev: [Jun 15, 2024](/content/2024/06/15/README.md)
- Next: [Jun 13, 2024](/content/2024/06/13/README.md)