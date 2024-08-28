# Awesome List Updates on May 13, 2024

8 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Free for Dev](/content/ripienaar/free-for-dev/README.md)

### Design and UI

*   [movingpencils.com](https://movingpencils.com) — Fast, browser-based vector editor. Completely free.

## [2. Awesome Playcanvas](/content/playcanvas/awesome-playcanvas/README.md)

### Browser Games

*   [Build Land](https://poki.com/en/g/build-land) - Grow your island by collecting resources.

### Product Configurators

*   [Norqain](https://norqain.com/pages/watch-configurator) - Watch configurator.

## [3. Awesome Vite](/content/vitejs/awesome-vite/README.md)

### Templates / React

*   [React Tanning (⭐3)](https://github.com/padunk/react-tanning) - Starter template with `React + Vite + TypeScript + TanStack + Tailwind`.

### PHP / Community

*   [PHP-Vite (⭐20)](https://github.com/mindplay-dk/php-vite) - Integration for PHP, Composer package, no framework dependencies.

### Apps/Websites / Community

*   [Dataviz Explorer (⭐15)](https://github.com/fehmisener/dataviz-explorer) - A tool for large CSV, database, and real-time visualization with interactive plots using `Highcharts`, `Chart.js`, `React`, `JavaScript`, `Material UI` and `GitHub Actions with Coverage Report`.

## [4. Awesome Terraform](/content/shuaibiyy/awesome-terraform/README.md)

### Self-Hosted Registries / Miscellaneous

*   [terralist (⭐307)](https://github.com/terralist/terralist) - Terraform Private Registry for modules and providers manageable from a REST API.

## [5. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Vector Database Comparison**

*   Milvus (A cloud-native vector database) Embedded [git (⭐29k)](https://github.com/milvus-io/milvus) \[Sep 2019]: Alternative option to replace PineCone and Redis Search in OSS. It offers support for multiple languages, addresses the limitations of RedisSearch, and provides cloud scalability and high reliability with Kubernetes.
*   [Pinecone](https://docs.pinecone.io): A fully managed cloud Vector Database. Commercial Product \[Jan 2021]
*   [Weaviate (⭐11k)](https://github.com/weaviate/weaviate): Store both vectors and data objects. \[Jan 2021]
*   [Chroma (⭐14k)](https://github.com/chroma-core/chroma): Open-source embedding database \[Oct 2022]
*   [Qdrant (⭐20k)](https://github.com/qdrant/qdrant): Written in Rust. Qdrant (read: quadrant) \[May 2020]
*   [Redis extension for vector search, RedisVL (⭐200)](https://github.com/RedisVentures/redisvl): Redis Vector Library (RedisVL) \[Nov 2022]
*   [A SQLite extension for efficient vector search, based on Faiss! (⭐1.7k)](https://github.com/asg017/sqlite-vss) \[Jan 2023]

### **Microsoft Azure OpenAI relevant LLM Framework** / **Lucene based search engine with OpenAI Embedding**

*   [SAMMO (⭐301)](https://github.com/microsoft/sammo): A general-purpose framework for prompt optimization. [ref](https://www.microsoft.com/en-us/research/blog/sammo-a-general-purpose-framework-for-prompt-optimization/) \[April 2024]

### **LangChain chain type: Chains & Summarizer** / DSPy optimizer

*   Chains [ref (⭐0)](https://github.com/RutamBhagat/LangChainHCCourse1/blob/main/course_1/chains.ipynb)
    *   SimpleSequentialChain: A sequence of steps with single input and output. Output of one step is input for the next.
    *   SequentialChain: Like SimpleSequentialChain but handles multiple inputs and outputs at each step.
    *   MultiPromptChain: Routes inputs to specialized sub-chains based on content. Ideal for different prompts for different tasks.
*   Summarizer
    *   stuff: Sends everything at once in LLM. If it's too long, an error will occur.
    *   map\_reduce: Summarizes by dividing and then summarizing the entire summary.
    *   refine: (Summary + Next document) => Summary
    *   map\_rerank: Ranks by score and summarizes to important points.

### **Prompt Engineering** / **Prompt Template Language**

*   [Many-Shot In-Context Learning](https://arxiv.org/abs/2404.11018): Transitioning from few-shot to many-shot In-Context Learning (ICL) can lead to significant performance gains across a wide variety of generative and discriminative tasks \[17 Apr 2024]

### **Prompt Guide & Leaked prompts** / **Prompt Template Language**

*   [Awesome ChatGPT Prompts (⭐108k)](https://github.com/f/awesome-chatgpt-prompts) \[Dec 2022]
*   [Awesome Prompt Engineering (⭐3.6k)](https://github.com/promptslab/Awesome-Prompt-Engineering) \[Feb 2023]
*   [Awesome-GPTs-Prompts (⭐4.9k)](https://github.com/ai-boost/awesome-prompts) \[Jan 2024]
*   Leaked prompts of [GPTs (⭐28k)](https://github.com/linexjlin/GPTs) \[Nov 2023] and [Agents (⭐7.9k)](https://github.com/LouisShark/chatgpt_system_prompt) \[Nov 2023]

### **Memory Optimization** / **Llama Finetuning**

*   Transformer cache key-value tensors of context tokens into GPU memory to facilitate fast generation of the next token. However, these caches occupy significant GPU memory. The unpredictable nature of cache size, due to the variability in the length of each request, exacerbates the issue, resulting in significant memory fragmentation in the absence of a suitable memory management mechanism.
*   To alleviate this issue, PagedAttention was proposed to store the KV cache in non-contiguous memory spaces. It partitions the KV cache of each sequence into multiple blocks, with each block containing the keys and values for a fixed number of tokens.
*   [PagedAttention](https://arxiv.org/abs/2309.06180) : vLLM: Easy, Fast, and Cheap LLM Serving with PagedAttention, 24x Faster LLM Inference [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/vLLM_pagedattention.pdf). [ref](https://vllm.ai/) \[12 Sep 2023]

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/pagedattn.png" width="390">

    *   PagedAttention for a prompt “the cat is sleeping in the kitchen and the dog is”. Key-Value pairs of tensors for attention computation are stored in virtual contiguous blocks mapped to non-contiguous blocks in the GPU memory.
*   [TokenAttention (⭐2.2k)](https://github.com/ModelTC/lightllm) an attention mechanism that manages key and value caching at the token level. [git (⭐2.2k)](https://github.com/ModelTC/lightllm/blob/main/docs/TokenAttention.md) \[Jul 2023]
*   [Flash Attention](https://arxiv.org/abs/2205.14135): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2205.14135)] \[27 May 2022] / [FlashAttention-2](https://arxiv.org/abs/2307.08691): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.08691)] \[17 Jul 2023]: An method that reorders the attention computation and leverages classical techniques (tiling, recomputation). Instead of storing each intermediate result, use kernel fusion and run every operation in a single kernel in order to avoid memory read/write overhead. [git (⭐13k)](https://github.com/Dao-AILab/flash-attention) -> Compared to a standard attention implementation in PyTorch, FlashAttention-2 can be up to 9x faster / [FlashAttention-3](https://arxiv.org/abs/2407.08608) \[11 Jul 2024]

### **Other techniques and LLM patterns** / **Llama Finetuning**

*   [Better & Faster Large Language Models via Multi-token Prediction](https://arxiv.org/abs/2404.19737): Suggest that training language models to predict multiple future tokens at once \[30 Apr 2024]

### **OpenAI's Roadmap and Products** / **OpenAI's plans according to Sam Altman**

*   Model Spec: Desired behavior for the models in the OpenAI API and ChatGPT [ref](https://cdn.openai.com/spec/model-spec-2024-05-08.html) \[8 May 2024] [ref](https://twitter.com/yi_ding/status/1788281765637038294): takeaway

### **Context constraints** / **GPT series release date**

*   [Introducing 100K Context Windows](https://www.anthropic.com/index/100k-context-windows): hundreds of pages, Around 75,000 words; \[11 May 2023] [demo](https://youtu.be/2kFhloXz5_E) Anthropic Claude
*   [“Needle in a Haystack” Analysis](https://bito.ai/blog/claude-2-1-200k-context-window-benchmarks/) \[21 Nov 2023]: Context Window Benchmarks; Claude 2.1 (200K Context Window) vs [GPT-4 (⭐1.4k)](https://github.com/gkamradt/LLMTest_NeedleInAHaystack); [Long context prompting for Claude 2.1](https://www.anthropic.com/index/claude-2-1-prompting) `adding just one sentence, “Here is the most relevant sentence in the context:”, to the prompt resulted in near complete fidelity throughout Claude 2.1’s 200K context window.` \[6 Dec 2023]
*   [Rotary Positional Embedding (RoPE)](https://arxiv.org/abs/2104.09864): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2104.09864)] / [ref](https://blog.eleuther.ai/rotary-embeddings/) / [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/RoPE.pdf) \[20 Apr 2021]
    *   How is this different from the sinusoidal embeddings used in "Attention is All You Need"?
        1.  Sinusoidal embeddings apply to each coordinate individually, while rotary embeddings mix pairs of coordinates
        2.  Sinusoidal embeddings add a `cos` or `sin` term, while rotary embeddings use a multiplicative factor.
        3.  Rotary embeddings are applied to positional encoding to K and V, not to the input embeddings.
*   [Lost in the Middle: How Language Models Use Long Contexts](https://arxiv.org/abs/2307.03172): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.03172)] \[6 Jul 2023]
    1.  Best Performace when relevant information is at beginning
    2.  Too many retrieved documents will harm performance
    3.  Performacnce decreases with an increase in context
*   [Structured Prompting: Scaling In-Context Learning to 1,000 Examples](https://arxiv.org/abs/2212.06713): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2212.06713)] \[13 Dec 2022]
    1.  Microsoft's Structured Prompting allows thousands of examples, by first concatenating examples into groups, then inputting each group into the LM. The hidden key and value vectors of the LM's attention modules are cached. Finally, when the user's unaltered input prompt is passed to the LM, the cached attention vectors are injected into the hidden layers of the LM.
    2.  This approach wouldn't work with OpenAI's closed models. because this needs to access \[keys] and \[values] in the transformer internals, which they do not expose. You could implement yourself on OSS ones. [cite](https://www.infoq.com/news/2023/02/microsoft-lmops-tools/) \[07 Feb 2023]
*   [Ring Attention](https://arxiv.org/abs/2310.01889): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.01889)]: 1. Ring Attention, which leverages blockwise computation of self-attention to distribute long sequences across multiple devices while overlapping the communication of key-value blocks with the computation of blockwise attention. 2. Ring Attention can reduce the memory requirements of Transformers, enabling us to train more than 500 times longer sequence than prior memory efficient state-of-the-arts and enables the training of sequences that exceed 100 million in length without making approximations to attention. 3. we propose an enhancement to the blockwise parallel transformers (BPT) framework. [git (⭐595)](https://github.com/lhao499/llm_large_context) \[3 Oct 2023]
*   [LLM Maybe LongLM](https://arxiv.org/abs/2401.01325): Self-Extend LLM Context Window Without Tuning. With only four lines of code modification, the proposed method can effortlessly extend existing LLMs' context window without any fine-tuning. \[2 Jan 2024]
*   [Giraffe](https://arxiv.org/abs/2308.10882): Adventures in Expanding Context Lengths in LLMs. A new truncation strategy for modifying the basis for the position encoding.  [ref](https://blog.abacus.ai/blog/2023/08/22/giraffe-long-context-llms/) \[2 Jan 2024]
*   [Leave No Context Behind](https://arxiv.org/abs/2404.07143): Efficient `Infinite Context` Transformers with Infini-attention. The Infini-attention incorporates a compressive memory into the vanilla attention mechanism. Integrate attention from both local and global attention. \[10 Apr 2024]

### **Trustworthy, Safe and Secure LLM** / **GPT series release date**

*   [Trustworthy LLMs](https://arxiv.org/abs/2308.05374): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2308.05374)]: Comprehensive overview for assessing LLM trustworthiness; Reliability, safety, fairness, resistance to misuse, explainability and reasoning, adherence to social norms, and robustness. \[10 Aug 2023]
    <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/llm-trustworthiness.png" width="450"> -->

### **GPT for Domain Specific** / **GPT series release date**

*   [TimeGPT](https://nixtla.github.io/nixtla/): The First Foundation Model for Time Series Forecasting [git (⭐2.9k)](https://github.com/Nixtla/neuralforecast) \[Mar 2023]
*   [BioGPT](https://arxiv.org/abs/2210.10341): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2210.10341)]: Generative Pre-trained Transformer for Biomedical Text Generation and Mining [git (⭐4.3k)](https://github.com/microsoft/BioGPT) \[19 Oct 2022]
*   [MeshGPT](https://nihalsid.github.io/mesh-gpt/): Generating Triangle Meshes with Decoder-Only Transformers \[27 Nov 2023]
*   [BloombergGPT](https://arxiv.org/abs/2303.17564): A Large Language Model for Finance \[30 Mar 2023]
*   [Galactica](https://arxiv.org/abs/2211.09085): A Large Language Model for Science \[16 Nov 2022]
*   [EarthGPT](https://arxiv.org/abs/2401.16822): A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain \[30 Jan 2024]
*   [SaulLM-7B](https://arxiv.org/abs/2403.03883): A pioneering Large Language Model for Law \[6 Mar 2024]
*   [Huggingface StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder): [git](https://huggingface.co/bigcode/starcoder) \[May 2023]
*   [Code Llama](https://arxiv.org/abs/2308.12950): Built on top of Llama 2, free for research and commercial use. [ref](https://ai.meta.com/blog/code-llama-large-language-model-coding/) / [git (⭐16k)](https://github.com/facebookresearch/codellama) \[24 Aug 2023]
*   [Devin AI](https://preview.devin.ai/): Devin is an AI software engineer developed by Cognition AI \[12 Mar 2024]
*   [OpenDevin](https://github.com/OpenDevin): an open-source project aiming to replicate Devin \[Mar 2024]
*   [FrugalGPT](https://arxiv.org/abs/2305.05176): LLM with budget constraints, requests are cascaded from low-cost to high-cost LLMs. [git (⭐165)](https://github.com/stanford-futuredata/FrugalGPT) \[9 May 2023]

### **MLLM (multimodal large language model)** / **GPT series release date**

*   Vision capability to a LLM [ref](https://cloud.google.com/blog/products/ai-machine-learning/multimodal-generative-ai-search/) \[22 Aug 2023]

    *   The model has three sub-models:
        1.  A model to obtain image embeddings
        2.  A text model to obtain text embeddings
        3.  A model to learn the relationships between them
    *   This is analogous to adding vision capability to a LLM.

        <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/cocoa.gif" width="200" />

### **Generative AI Landscape** / **GPT series release date**

*   [The Generative AI Revolution: Exploring the Current Landscape](https://pub.towardsai.net/the-generative-ai-revolution-exploring-the-current-landscape-4b89998fcc5f) : [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/gen-ai-landscape.pdf) \[28 Jun 2023]
*   [Diffusion Models vs. GANs vs. VAEs: Comparison of Deep Generative Models](https://pub.towardsai.net/diffusion-models-vs-gans-vs-vaes-comparison-of-deep-generative-models-67ab93e0d9ae) \[12 May 2023]

### **LLM Materials for East Asian Languages** / Japanese

*   [AI事業者ガイドライン](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/) \[Apr 2024]

### **LLM Materials for East Asian Languages** / Korean

*   [Machine Learning Study 혼자 해보기 (⭐2.6k)](https://github.com/teddylee777/machine-learning) \[Sep 2018]
*   [LangChain 한국어 튜토리얼 (⭐922)](https://github.com/teddylee777/langchain-kr) \[Feb 2024]

### **Agents: AutoGPT and Communicative Agents** / Tool use: LLM to Master APIs

*   [Gorilla: An API store for LLMs](https://arxiv.org/abs/2305.15334): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.15334)]: Gorilla: Large Language Model Connected with Massive APIs [git (⭐11k)](https://github.com/ShishirPatil/gorilla) \[24 May 2023]

    1.  Used GPT-4 to generate a dataset of instruction-api pairs for fine-tuning Gorilla.

    2.  Used the abstract syntax tree (AST) of the generated code to match with APIs in the database and test set for evaluation purposes.

    > Another user asked how Gorilla compared to LangChain; Patil replied: LangChain is a terrific project that tries to teach agents how to use tools using prompting. Our take on this is that prompting is not scalable if you want to pick between 1000s of APIs. So Gorilla is a LLM that can pick and write the semantically and syntactically correct API for you to call! A drop in replacement into LangChain! [cite](https://www.infoq.com/news/2023/07/microsoft-gorilla/) \[04 Jul 2023]
*   [Meta: Toolformer](https://arxiv.org/abs/2302.04761): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2302.04761)]: Language Models That Can Use Tools, by MetaAI [git (⭐1.9k)](https://github.com/lucidrains/toolformer-pytorch) \[9 Feb 2023]
*   [ToolLLM](https://arxiv.org/abs/2307.16789): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.16789)]: : Facilitating Large Language Models to Master 16000+ Real-world APIs [git (⭐4.7k)](https://github.com/OpenBMB/ToolBench) \[31 Jul 2023]

### **Section 11: Datasets for LLM Training** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   [MS MARCO Web Search (⭐301)](https://github.com/microsoft/MS-MARCO-Web-Search): A large-scale information-rich web dataset, featuring millions of real clicked query-document labels \[Apr 2024]

## [6. Awesome Rust](/content/rust-unofficial/awesome-rust/README.md)

### Applications / Utilities

*   [Mobslide (⭐342)](https://github.com/thewh1teagle/mobslide) - Desktop application that turns your smartphone into presentation remote controller.
*   [Vibe (⭐619)](https://github.com/thewh1teagle/vibe) - Transcribe audio or video in every language on every platform.

## [7. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### RxJS / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-observable-lifecycle (⭐34)](https://github.com/cloudnc/ngx-observable-lifecycle) - Library for observing the lifecycle of an (ivy compiled) angular component.
*   [rx-sandbox (⭐172)](https://github.com/kwonoj/rx-sandbox) - Marble diagram DSL based test suite for RxJS.
*   [observer-spy (⭐375)](https://github.com/hirezio/observer-spy) - This library makes RxJS Observables testing easy!
*   [ngx-operators (⭐136)](https://github.com/nilsmehlhorn/ngx-operators) - RxJS operators for Angular.
*   [rxjs-toolbox (⭐10)](https://github.com/kievsash/rxjs-toolbox) - Set of custom operators and handy factory functions for RxJS.
*   [subscribable-things (⭐42)](https://github.com/chrisguttandin/subscribable-things) - A collection of reactive wrappers for various browser APIs.
*   [ngx-rxjs-zone-scheduler (⭐32)](https://github.com/ftischler/ngx-rxjs-zone-scheduler) - A library for Angular providing RxJS schedulers to run some kind of work inside or outside of `NgZone`.
*   [rxjs-broker (⭐24)](https://github.com/chrisguttandin/rxjs-broker) - An RxJS message broker for WebRTC DataChannels and WebSockets.
*   [rxjs-insights (⭐359)](https://github.com/ksz-ksz/rxjs-insights) - See through the observables.

## [8. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [brave (⭐0)](https://github.com/troykelly/oh-my-zsh-brave) - Manages [Brave](https://brave.com) profiles. With this plugin, you can start the Brave Browser with a specific user profile by using the brave command followed by the profile's name. The plugin also implements autocompletion for the profile names so you won't have to type the entire profile name manually.
*   [explain-shell (brokentoaster) (⭐2)](https://github.com/brokentoaster/zsh-explainshell) - Uses [lynx](https://lynx.browser.org/) to look up the current command line on [explainshell.com](https://explainshell.com).
*   [explain-shell (gmatheu) (⭐27)](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
*   [fixnumpad-osx (⭐3)](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
*   [goenv (cda0) (⭐0)](https://github.com/CDA0/zsh-goenv/) - Plugin for installing, updating and loading `goenv`.
*   [ollama (⭐11)](https://github.com/plutowang/zsh-ollama-command) - Integrates the OLLAMA AI model with [fzf (⭐63k)](https://github.com/junegunn/fzf) to provide intelligent command suggestions based on user input requirements.
*   [raspberryPi4Temperature (⭐0)](https://github.com/KidesLeo/RaspberryPi4TemperaturePromptPlugin) - Puts the Raspberry Pi temperature into a spaceship prompt segment
*   [ros2-env (⭐0)](https://github.com/Butakus/ros2-env) - Manage [ROS 2](https://github.com/ros2) environment and workspaces.

### Completions / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [tofu (⭐0)](https://github.com/marknefedov/oh-my-zsh-tofu) - Autoloads tab completions for `tofu`.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [candy-fantasy (⭐0)](https://github.com/fffelix-huang/candy-fantasy) - Modified version of [Candy Kingdowm (⭐172k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/candy-kingdom.zsh-theme)theme.

---

- Prev: [May 14, 2024](/content/2024/05/14/README.md)
- Next: [May 12, 2024](/content/2024/05/12/README.md)