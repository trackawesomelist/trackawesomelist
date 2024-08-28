# Awesome List Updates on May 31, 2024

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Blazor](/content/AdrienTorris/awesome-blazor/README.md)

### Videos / Others

*   [On .NET Live: Generating sound in Blazor with Blazor.WebAudio](https://www.youtube.com/watch?v=gVZJohJq3c8) - June 3, 2024 - Are you using audio in your Blazor applications? This week, Kristoffer Stube joins us to talk about Blazor.WebAudio, a Blazor library for playing, generating, and analyzing sound! This library and the libraries surrounding it enable developers to make rich interactive applications in a safe fashion.
*   [Build an AI-powered content composer in Blazor using OpenAI GPT](https://www.youtube.com/watch?v=KinUUsGkK_s) - ![duration](https://img.shields.io/badge/Duration:%20-17%20min-%230094FF?style=flat-square\&cacheSeconds=maxAge\&logo=youtube) May 22, 2024 - Learn how to build an AI-powered content composer using GPT-3.5 Turbo and Syncfusion Blazor components. Effortlessly create content on any topic and automatically adjust its tone, format, and length—all in one place.

## [2. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### Blogs / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ninja-squad](https://blog.ninja-squad.com/)
*   [Tomas Trajan](https://tomastrajan.medium.com/)
*   [Igor Katsuba](https://blog.katsuba.dev/)

### GraphQL / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [buoy (⭐7)](https://github.com/buoy-graphql/buoy) - A GraphQL client for Angular built on top of Apollo.

### HTTP / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-generic-rest-service (⭐0)](https://github.com/jm2097/ngx-generic-rest-service) - Wrapper for Angular services.
*   [@ngify/http (⭐98)](https://github.com/ngify/ngify/tree/main/packages/http) - A reactive HTTP client in the form of `@angular/common/http`, offers the following major features: typed response objects, streamlined error handling, request and response interception.

### Integrations / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-papaparse (⭐91)](https://github.com/alberthaff/ngx-papaparse) - [Papa Parse](https://www.papaparse.com) wrapper.

### Charts / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ng-flowchart (⭐138)](https://github.com/joel-wenzel/ng-flowchart) - A lightweight Angular Library for building drag and drop flow charts. Chart behavior and steps are customizable. Data can be exported or uploaded in json format.

### Misc Components / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [@ui-router/angular (⭐351)](https://github.com/ui-router/angular) - [UI-Router](https://ui-router.github.io) for Angular: State-based routing for Angular.
*   [ngx-csv-parser (⭐25)](https://github.com/tofiqquadri/ngx-csv-parser) - CSV Parser for Angular by Developers Hive.

## [3. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Search / Diagnostics

*   [MagicDuck/grug-far.nvim (⭐586)](https://github.com/MagicDuck/grug-far.nvim) - Buffer-based live search and replace with full power of `rg` flags. Grug like!

## [4. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [cdh (⭐1)](https://github.com/johncassol/cdh) - Allows users to manage and navigate through a history of directories they have visited. It maintains a history file of directories and provides several commands to interact with this history.

### Completions / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [zpacman (⭐0)](https://github.com/Yttehs-HDX/zsh-zpacman/) - Add tab completions for [zpacman](https://github.com/Yttehs-HDX/zpacman.git).

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [pronto (arzezak) (⭐0)](https://github.com/arzezak/pronto) - A super simple prompt with decorators for the current directory and `git` information.
*   [pronto (jthat) (⭐1)](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.

## [5. Awesome Bitcoin](/content/igorbarinov/awesome-bitcoin/README.md)

### Open Source Wallets

*   [Coin Wallet](https://coin.space/)

## [6. Awesome Developer First](/content/agamm/awesome-developer-first/README.md)

### Feature Flags

*   [Statsig](https://statsig.com/) - All-in-one platform spanning across analytics, feature flagging, and A/B testing. Free for up to 1m metered events per month.

## [7. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **LlamaIndex**

*   LlamaIndex Toolkits: `LlamaHub`: A library of data loaders for LLMs [git (⭐3.4k)](https://github.com/run-llama/llama-hub) \[Feb 2023] / `LlamaIndex CLI`: a command line tool to generate LlamaIndex apps [ref](https://llama-2.ai/llamaindex-cli/) \[Nov 2023] / `LlamaParse`: A unique parsing tool for intricate documents [git (⭐2.3k)](https://github.com/run-llama/llama_parse) \[Feb 2024]

    <details>
      <summary>High-Level Concepts</summary>

    *   Query engine vs Chat engine

        1.  The query engine wraps a `retriever` and a `response synthesizer` into a pipeline, that will use the query string to fetch nodes (sentences or paragraphs) from the index and then send them to the LLM (Language and Logic Model) to generate a response
        2.  The chat engine is a quick and simple way to chat with the data in your index. It uses a `context manager` to keep track of the conversation history and generate relevant queries for the retriever. Conceptually, it is a `stateful` analogy of a Query Engine.

    *   Storage Context vs Settings (p.k.a. Service Context)

        *   Both the Storage Context and Service Context are data classes.

        <!-- ```python
        index = load_index_from_storage(storage_context, service_context=service_context)
        ``` -->

        1.  Introduced in v0.10.0, ServiceContext is replaced to Settings object.
        2.  Storage Context is responsible for the storage and retrieval of data in Llama Index, while the Service Context helps in incorporating external context to enhance the search experience.
        3.  The Service Context is not directly involved in the storage or retrieval of data, but it helps in providing a more context-aware and accurate search experience.

    ```python
    # The storage context container is a utility container for storing nodes, indices, and vectors.
    class StorageContext:
      docstore: BaseDocumentStore
      index_store: BaseIndexStore
      vector_store: VectorStore
      graph_store: GraphStore
    ```

    ```python
    # The service context container is a utility container for LlamaIndex index and query classes.
    class ServiceContext:
      llm_predictor: BaseLLMPredictor
      prompt_helper: PromptHelper
      embed_model: BaseEmbedding
      node_parser: NodeParser
      llama_logger: LlamaLogger
      callback_manager: CallbackManager
    ```

    ```python
    @dataclass
    class _Settings:
      # lazy initialization
      _llm: Optional[LLM] = None
      _embed_model: Optional[BaseEmbedding] = None
      _callback_manager: Optional[CallbackManager] = None
      _tokenizer: Optional[Callable[[str], List[Any]]] = None
      _node_parser: Optional[NodeParser] = None
      _prompt_helper: Optional[PromptHelper] = None
      _transformations: Optional[List[TransformComponent]] = None
    ```

       </details>

### **Memory Optimization** / **Llama Finetuning**

*   [CPU vs GPU vs TPU](https://newsletter.theaiedge.io/p/how-to-scale-model-training): The threads are grouped into thread blocks. Each of the thread blocks has access to a fast shared memory (SRAM). All the thread blocks can also share a large global memory. (high-bandwidth memories (HBM). `HBM Bandwidth: 1.5-2.0TB/s vs SRAM Bandwidth: 19TB/s ~ 10x HBM` \[27 May 2024]

### **Other techniques and LLM patterns** / **Llama Finetuning**

*   [Kolmogorov-Arnold Networks (KANs)](https://arxiv.org/abs/2404.19756): KANs use activation functions on connections instead of nodes like Multi-Layer Perceptrons (MLPs) do. Each weight in KANs is replaced by a learnable 1D spline function. KANs’ nodes simply sum incoming signals without applying any non-linearities. [git (⭐14k)](https://github.com/KindXiaoming/pykan) \[30 Apr 2024] / [ref](https://www.dailydoseofds.com/a-beginner-friendly-introduction-to-kolmogorov-arnold-networks-kan/): A Beginner-friendly Introduction to Kolmogorov Arnold Networks (KAN) \[19 May 2024]

### **Build an LLMs from scratch: picoGPT and lit-gpt** / **GPT series release date**

*   [llm.c (⭐23k)](https://github.com/karpathy/llm.c): LLM training in simple, raw C/CUDA \[Apr 2024]
    *   Reproducing GPT-2 (124M) in llm.c in 90 minutes for $20 [ref (⭐23k)](https://github.com/karpathy/llm.c/discussions/481)

### **Learning and Supplementary Materials** / Korean

*   [DAIR.AI](https://github.com/dair-ai): Machine learning & NLP research ([omarsar github](https://github.com/omarsar))
    *   [ML Papers of The Week (⭐9.7k)](https://github.com/dair-ai/ML-Papers-of-the-Week) \[Jan 2023]
*   [Daily Dose of Data Science (⭐764)](https://github.com/ChawlaAvi/Daily-Dose-of-Data-Science) \[Dec 2022]
*   [Machine learning algorithms (⭐11k)](https://github.com/rushter/MLAlgorithms): ml algorithms or implementation from scratch \[Oct 2016]

---

- Prev: [Jun 01, 2024](/content/2024/06/01/README.md)
- Next: [May 30, 2024](/content/2024/05/30/README.md)