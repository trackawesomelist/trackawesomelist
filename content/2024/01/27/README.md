# Awesome List Updates on Jan 27, 2024

10 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Software Patreons](/content/uraimo/awesome-software-patreons/README.md)

### Open Source Projects

*   [Bottles](https://usebottles.com/funding/) - Easily manage and run Windows apps on Linux.
*   [OptiKey](https://www.patreon.com/OptiKey), [#2](https://github.com/sponsors/JuliusSweetland) - Full computer control and speech with your eyes.
*   [Sonic Pi](https://www.patreon.com/samaaron) - Code-based music creation and performance tool.

### Open Source Projects / Operating Systems

*   [PostmarketOS](https://opencollective.com/postmarketos) - A real Linux distribution for phones.

## [2. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/README.md)

### Software / Groupware

*   [Tine](https://www.tine-groupware.de/) - Software for digital collaboration in companies and organizations. From powerful groupware functionalities to clever add-ons, tine combines everything to make daily team collaboration easier. ([Source Code (⭐10)](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`

## [3. Awesome Vue](/content/vuejs/awesome-vue/README.md)

### Projects Using Vue.js / Open Source

*   [vue3-realworld-app (⭐31)](https://github.com/rofixro/vue3-realworld-app) - 🖖 Best practices for building RealWorld with Vue3

## [4. Awesome Git Hooks](/content/CompSciLauren/awesome-git-hooks/README.md)

### Git Hook Scripts / pre-commit

*   [dotenvx (⭐919)](https://github.com/CompSciLauren/awesome-git-hooks/blob/master/pre-commit-hooks/dotenvx.hook) - Prevent committing your `.env` file(s) to code. <img width="14" src="https://github.com/CompSciLauren/awesome-git-hooks/raw/master/bash-icon.png" alt="Bash Icon">

## [5. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **What is the RAG (Retrieval-Augmented Generation)?**

*   RAG (Retrieval-Augmented Generation) : Integrates the retrieval (searching) into LLM text generation. RAG helps the model to “look up” external information to improve its responses. [cite](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7) \[25 Aug 2023]

    <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/RAG.png" alt="sk" width="400"/> -->

### **Retrieval-Augmented Generation: Research Papers**

*   [Benchmarking Large Language Models in Retrieval-Augmented Generation](https://arxiv.org/abs/2309.01431): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.01431)]: Retrieval-Augmented Generation Benchmark (RGB) is proposed to assess LLMs on 4 key abilities \[4 Sep 2023]:

    1.  Noise robustness (External documents contain noises, struggled with noise above 80%)
    2.  Negative rejection (External documents are all noises, Highest rejection rate was only 45%)
    3.  Information integration (Difficulty in summarizing across multiple documents, Highest accuracy was 60-67%)
    4.  Counterfactual robustness (Failed to detect factual errors in counterfactual external documents.)
*   <details>

    <summary>Expand</summary>

    *   [Active Retrieval Augmented Generation](https://arxiv.org/abs/2305.06983) : \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.06983)]: Forward-Looking Active REtrieval augmented generation (FLARE): FLARE iteratively generates a temporary next sentence and check whether it contains low-probability tokens. If so, the system retrieves relevant documents and regenerates the sentence. Determine low-probability tokens by `token_logprobs in OpenAI API response`. [git (⭐545)](https://github.com/jzbjyb/FLARE/blob/main/src/templates.py) \[11 May 2023]
    *   [Self-RAG](https://arxiv.org/pdf/2310.11511.pdf): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.11511)] 1. `Critic model C`: Generates reflection tokens (IsREL (relevant,irrelevant), IsSUP (fullysupported,partially supported,nosupport), IsUse (is useful: 5,4,3,2,1)). It is pretrained on data labeled by GPT-4. 2. `Generator model M`: The main language model that generates task outputs and reflection tokens. It leverages the data labeled by the critic model during training. 3. `Retriever model R`: Retrieves relevant passages. The LM decides if external passages (retriever) are needed for text generation. [git (⭐1.6k)](https://github.com/AkariAsai/self-rag) \[17 Oct 2023]
    *   [A Survey on Retrieval-Augmented Text Generation](https://arxiv.org/abs/2202.01110): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2202.01110)]: This paper conducts a survey on retrieval-augmented text generation, highlighting its advantages and state-of-the-art performance in many NLP tasks. These tasks include Dialogue response generation, Machine translation, Summarization, Paraphrase generation, Text style transfer, and Data-to-text generation. \[2 Feb 2022]
    *   [Retrieval meets Long Context LLMs](https://arxiv.org/abs/2310.03025): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.03025)]: We demonstrate that retrieval-augmentation significantly improves the performance of 4K context LLMs. Perhaps surprisingly, we find this simple retrieval-augmented baseline can perform comparable to 16K long context LLMs. \[4 Oct 2023]
    *   [FreshLLMs](https://arxiv.org/abs/2310.03214): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.03214)]: Fresh Prompt, Google search first, then use results in prompt. Our experiments show that FreshPrompt outperforms both competing search engine-augmented prompting methods such as Self-Ask (Press et al., 2022) as well as commercial systems such as Perplexity.AI. [git](https://www.github.com/freshllms/freshqa) \[5 Oct 2023]
    *   [RECOMP: Improving Retrieval-Augmented LMs with Compressors](https://arxiv.org/abs/2310.04408): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.04408)]: 1. We propose RECOMP (Retrieve, Compress, Prepend), an intermediate step which compresses retrieved documents into a textual summary prior to prepending them to improve retrieval-augmented language models (RALMs). 2. We present two compressors – an `extractive compressor` which selects useful sentences from retrieved documents and an `abstractive compressor` which generates summaries by synthesizing information from multiple documents. 3. Both compressors are trained. \[6 Oct 2023]
    *   [Retrieval-Augmentation for Long-form Question Answering](https://arxiv.org/abs/2310.12150): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.12150)]: 1. The order of evidence documents affects the order of generated answers 2. the last sentence of the answer is more likely to be unsupported by evidence. 3. Automatic methods for detecting attribution can achieve reasonable performance, but still lag behind human agreement. `Attribution in the paper assesses how well answers are based on provided evidence and avoid creating non-existent information.` \[18 Oct 2023]
    *   [INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning](https://arxiv.org/abs/2401.06532): INTERS covers 21 search tasks across three categories: query understanding, document understanding, and query-document relationship understanding. The dataset is designed for instruction tuning, a method that fine-tunes LLMs on natural language instructions. [git (⭐190)](https://github.com/DaoD/INTERS) \[12 Jan 2024]
    *   [RAG vs Fine-tuning](https://arxiv.org/abs/2401.08406): Pipelines, Tradeoffs, and a Case Study on Agriculture. \[16 Jan 2024]
    *   [The Power of Noise: Redefining Retrieval for RAG Systems](https://arxiv.org/abs/2401.14887): No more than 2-5 relevant docs + some amount of random noise to the LLM context maximizes the accuracy of the RAG. \[26 Jan 2024]
    *   [Corrective Retrieval Augmented Generation (CRAG)](https://arxiv.org/abs/2401.15884): Retrieval Evaluator assesses the retrieved documents and categorizes them as Correct, Ambiguous, or Incorrect1. For Ambiguous and Incorrect documents, the method uses Web Search to improve the quality of the information. The refined and distilled documents are then used to generate the final output. \[29 Jan 2024] CRAG implementation by LangGraph [git (⭐4.2k)](https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_crag.ipynb)
    *   [RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://arxiv.org/abs/2401.18059): Introduce a novel approach to retrieval-augmented language models by constructing a recursive tree structure from documents. [git (⭐33k)](https://github.com/run-llama/llama_index/blob/main/llama-index-packs/llama-index-packs-raptor/README.md) `pip install llama-index-packs-raptor` / [git (⭐25)](https://github.com/profintegra/raptor-rag) \[31 Jan 2024]
    *   [CRAG: Comprehensive RAG Benchmark](https://arxiv.org/abs/2406.04744): a factual question answering benchmark of 4,409 question-answer pairs and mock APIs to simulate web and Knowledge Graph (KG) search [ref](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024) \[7 Jun 2024]
    *   [PlanRAG](https://arxiv.org/abs/2406.12430): Decision Making. Decision QA benchmark, DQA. Plan -> Retrieve -> Make a decision (PlanRAG) [git (⭐99)](https://github.com/myeon9h/PlanRAG) \[18 Jun 2024]

    </details>

### **RAG Pipeline & Advanced RAG**

*   How to optimize RAG pipeline: [Indexing optimization](https://newsletter.theaiedge.io/p/how-to-optimize-your-rag-pipelines) \[24 Oct 2023]
*   [Graph RAG](https://medium.com/@nebulagraph/graph-rag-the-new-llm-stack-with-knowledge-graphs-e1e902c504ed): NebulaGraph proposes the concept of Graph RAG, which is a retrieval enhancement technique based on knowledge graphs. [demo](https://www.nebula-graph.io/demo) \[8 Sep 2023]

### **Azure Reference Architectures** / **Azure AI Search**

*   A set of capabilities designed to improve relevance in these scenarios. We use a combination of hybrid retrieval (vector search + keyword search) + semantic ranking as the most effective approach for improved relevance out-of–the-box. `TL;DR: Retrieval Performance; Hybrid search + Semantic rank > Hybrid search > Vector only search > Keyword only` [ref](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/azure-cognitive-search-outperforming-vector-search-with-hybrid/ba-p/3929167) \[18 Sep 2023]

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files\acs-hybrid.png" alt="acs" width="350"/>

### **Semantic Kernel** / **Feature Roadmap**

*   .NET Semantic Kernel SDK: 1. Renamed packages and classes that used the term “Skill” to now use “Plugin”. 2. OpenAI specific in Semantic Kernel core to be AI service agnostic 3. Consolidated our planner implementations into a single package [ref](https://devblogs.microsoft.com/semantic-kernel/introducing-the-v1-0-0-beta1-for-the-net-semantic-kernel-sdk/) \[10 Oct 2023]

### **Semantic Kernel** / **Code Recipes**

*   Chat Copilot Sample Application: A reference application for building a chat experience using Semantic Kernel. Leveraging plugins, planners, and AI memories. [git (⭐1.9k)](https://github.com/microsoft/chat-copilot) \[Apr 2023]
*   Semantic Kernel Recipes: A collection of C# notebooks [git (⭐162)](https://github.com/johnmaeda/SK-Recipes) \[Mar 2023]
*   Deploy Semantic Kernel with Bot Framework [ref](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/deploy-semantic-kernel-with-bot-framework/ba-p/3928101) [git (⭐49)](https://github.com/Azure/semantic-kernel-bot-in-a-box) \[26 Oct 2023]
*   Semantic Kernel-Powered OpenAI Plugin Development Lifecycle [ref](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/semantic-kernel-powered-openai-plugin-development-lifecycle/ba-p/3967751) \[30 Oct 2023]
*   SemanticKernel Implementation sample to overcome Token limits of Open AI model.
    Semantic Kernel でトークンの限界を超えるような長い文章を分割してスキルに渡して結果を結合したい (zenn.dev)
    [ref](https://zenn.dev/microsoft/articles/semantic-kernel-10) \[06 May 2023]

### **Semantic Kernel** / **Semantic Kernel Planner**

*   Semantic Kernel Planner [ref](https://devblogs.microsoft.com/semantic-kernel/semantic-kernel-planners-actionplanner/) \[24 Jul 2023]

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files\sk-evolution_of_planners.jpg" alt="sk-plan" width="390"/>

### **Semantic Kernel** / **Semantic Function**

*   Prompt Template language Key takeaways

### **Langchain Quick Start: How to Use** / DSPy optimizer

*   `code\deeplearning.ai\langchain-chat-with-your-data`: DeepLearning.ai LangChain: Chat with Your Data
*   `code\deeplearning.ai\langchain-llm-app-dev`: LangChain for LLM Application Development

### **MLLM (multimodal large language model)** / **GPT series release date**

*   Benchmarking Multimodal LLMs.
    *   LLaVA-1.5 achieves SoTA on a broad range of 11 tasks incl. SEED-Bench.
    *   [SEED-Bench](https://arxiv.org/abs/2307.16125): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.16125)]: Benchmarking Multimodal LLMs [git (⭐275)](https://github.com/AILab-CVC/SEED-Bench) \[30 Jul 2023]

        <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/multi-llm.png" width="180" /> -->

### **Learning and Supplementary Materials** / Korean

*   [Large Language Model Course (⭐34k)](https://github.com/mlabonne/llm-course): Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks. \[Jun 2023]

## [6. Awesome Kotlin](/content/KotlinBy/awesome-kotlin/README.md)

### Android / Projects

*   [inorichi/tachiyomi](https://github.com/inorichi/tachiyomi) - Free and open source manga reader for Android.

## [7. Urban and Regional Planning Resources](/content/APA-Technology-Division/urban-and-regional-planning-resources/README.md)

### Public Data Resources / Equity and Environmental Justice

*   [STEAP](https://maps.dot.gov/fhwa/steap/) - The Screening Tool for Equity Analysis of Projects (STEAP) is a census sampling tool that allows rapid screening of potential project locations anywhere in the United States to support Title VI, environmental justice, and other socioeconomic data analyses.

## [8. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### (requires Neovim 0.5)

*   [lopi-py/luau-lsp.nvim (⭐33)](https://github.com/lopi-py/luau-lsp.nvim) - A luau-lsp extension to improve your experience.

## [9. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Deep Learning Packages / Visualization Tools

*   [Resseract Lite (⭐4)](https://github.com/abistarun/resseract-lite)

## [10. Awesome Rails](/content/gramantin/awesome-rails/README.md)

### Gems / Other external resources

*   [solid\_queue (⭐1.4k)](https://github.com/basecamp/solid_queue) - A gem to Database-backed Active Job backend [:red\_circle:](https://rubygems.org/gems/solid_queue)

---

- Prev: [Jan 28, 2024](/content/2024/01/28/README.md)
- Next: [Jan 26, 2024](/content/2024/01/26/README.md)