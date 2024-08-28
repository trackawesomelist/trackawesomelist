# Awesome List Updates on Jan 22 - Jan 28, 2024

34 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Flame](/content/flame-engine/awesome-flame/week/README.md)

### App Releases / Casual

*   Save The Potato [source-code (⭐32)](https://github.com/imaNNeo/save_the_potato) - 🥇 Winner of [Flame Game Jam 3.0](https://itch.io/jam/flame-jam-3/results) - Rotate the shields and save the potato from incoming orbs! By [imaNNeo](https://imanneo.dev). [for Android or iOS](http://savethepotato.com)

## [2. Awesome Software Patreons](/content/uraimo/awesome-software-patreons/week/README.md)

### Open Source Projects

*   [Bottles](https://usebottles.com/funding/) - Easily manage and run Windows apps on Linux.
*   [OptiKey](https://www.patreon.com/OptiKey), [#2](https://github.com/sponsors/JuliusSweetland) - Full computer control and speech with your eyes.
*   [Sonic Pi](https://www.patreon.com/samaaron) - Code-based music creation and performance tool.

### Open Source Projects / Operating Systems

*   [PostmarketOS](https://opencollective.com/postmarketos) - A real Linux distribution for phones.

## [3. Awesome Vue](/content/vuejs/awesome-vue/week/README.md)

### Projects Using Vue.js / Open Source

*   [vue3-realworld-app (⭐36)](https://github.com/rofixro/vue3-realworld-app) - 🖖 Best practices for building RealWorld with Vue3

## [4. Awesome Git Hooks](/content/CompSciLauren/awesome-git-hooks/week/README.md)

### Git Hook Scripts / pre-commit

*   [dotenvx (⭐919)](https://github.com/CompSciLauren/awesome-git-hooks/blob/master/pre-commit-hooks/dotenvx.hook) - Prevent committing your `.env` file(s) to code. <img width="14" src="https://github.com/CompSciLauren/awesome-git-hooks/raw/master/bash-icon.png" alt="Bash Icon">

## [5. Awesome Kotlin](/content/KotlinBy/awesome-kotlin/week/README.md)

### Android / Projects

*   [inorichi/tachiyomi](https://github.com/inorichi/tachiyomi) - Free and open source manga reader for Android.

## [6. Awesome Datascience](/content/academic/awesome-datascience/week/README.md)

### Deep Learning Packages / Visualization Tools

*   [Resseract Lite (⭐4)](https://github.com/abistarun/resseract-lite)

## [7. Awesome Rails](/content/gramantin/awesome-rails/week/README.md)

### Gems / Other external resources

*   [solid\_queue (⭐1.7k)](https://github.com/basecamp/solid_queue) - A gem to Database-backed Active Job backend [:red\_circle:](https://rubygems.org/gems/solid_queue)

## [8. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/week/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [hypnosnek (⭐0)](https://github.com/josephcourtney/hypnosnek) - Simple utilities with p10k integration for managing `python` environments.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [zap-robbyrussell (⭐1)](https://github.com/devadathanmb/zap-robbyrussell) - The OMZ robbyrussell theme, patched to add compatibility with [zap](https://www.zapzsh.com/).

## [9. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/week/README.md)

### **What is the RAG (Retrieval-Augmented Generation)?**

*   RAG (Retrieval-Augmented Generation) : Integrates the retrieval (searching) into LLM text generation. RAG helps the model to “look up” external information to improve its responses. [cite](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7) \[25 Aug 2023]

    <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/RAG.png" alt="sk" width="400"/> -->

### **Retrieval-Augmented Generation: Research Papers**

*   [Benchmarking Large Language Models in Retrieval-Augmented Generation](https://arxiv.org/abs/2309.01431): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.01431)]: Retrieval-Augmented Generation Benchmark (RGB) is proposed to assess LLMs on 4 key abilities \[4 Sep 2023]:
*   <details open>

    <summary>Expand: Research Papers</summary>

    *   [Active Retrieval Augmented Generation](https://arxiv.org/abs/2305.06983) : \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.06983)]: Forward-Looking Active REtrieval augmented generation (FLARE): FLARE iteratively generates a temporary next sentence and check whether it contains low-probability tokens. If so, the system retrieves relevant documents and regenerates the sentence. Determine low-probability tokens by `token_logprobs in OpenAI API response`. [git (⭐562)](https://github.com/jzbjyb/FLARE/blob/main/src/templates.py) \[11 May 2023]
    *   [Self-RAG](https://arxiv.org/pdf/2310.11511.pdf): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.11511)] 1. `Critic model C`: Generates reflection tokens (IsREL (relevant,irrelevant), IsSUP (fullysupported,partially supported,nosupport), IsUse (is useful: 5,4,3,2,1)). It is pretrained on data labeled by GPT-4. 2. `Generator model M`: The main language model that generates task outputs and reflection tokens. It leverages the data labeled by the critic model during training. 3. `Retriever model R`: Retrieves relevant passages. The LM decides if external passages (retriever) are needed for text generation. [git (⭐1.7k)](https://github.com/AkariAsai/self-rag) \[17 Oct 2023]
    *   [A Survey on Retrieval-Augmented Text Generation](https://arxiv.org/abs/2202.01110): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2202.01110)]: This paper conducts a survey on retrieval-augmented text generation, highlighting its advantages and state-of-the-art performance in many NLP tasks. These tasks include Dialogue response generation, Machine translation, Summarization, Paraphrase generation, Text style transfer, and Data-to-text generation. \[2 Feb 2022]
    *   [Retrieval meets Long Context LLMs](https://arxiv.org/abs/2310.03025): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.03025)]: We demonstrate that retrieval-augmentation significantly improves the performance of 4K context LLMs. Perhaps surprisingly, we find this simple retrieval-augmented baseline can perform comparable to 16K long context LLMs. \[4 Oct 2023]
    *   [FreshLLMs](https://arxiv.org/abs/2310.03214): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.03214)]: Fresh Prompt, Google search first, then use results in prompt. Our experiments show that FreshPrompt outperforms both competing search engine-augmented prompting methods such as Self-Ask (Press et al., 2022) as well as commercial systems such as Perplexity.AI. [git](https://www.github.com/freshllms/freshqa) \[5 Oct 2023]
    *   [RECOMP: Improving Retrieval-Augmented LMs with Compressors](https://arxiv.org/abs/2310.04408): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.04408)]: 1. We propose RECOMP (Retrieve, Compress, Prepend), an intermediate step which compresses retrieved documents into a textual summary prior to prepending them to improve retrieval-augmented language models (RALMs). 2. We present two compressors – an `extractive compressor` which selects useful sentences from retrieved documents and an `abstractive compressor` which generates summaries by synthesizing information from multiple documents. 3. Both compressors are trained. \[6 Oct 2023]
    *   [Retrieval-Augmentation for Long-form Question Answering](https://arxiv.org/abs/2310.12150): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.12150)]: 1. The order of evidence documents affects the order of generated answers 2. the last sentence of the answer is more likely to be unsupported by evidence. 3. Automatic methods for detecting attribution can achieve reasonable performance, but still lag behind human agreement. `Attribution in the paper assesses how well answers are based on provided evidence and avoid creating non-existent information.` \[18 Oct 2023]
    *   [INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning](https://arxiv.org/abs/2401.06532): INTERS covers 21 search tasks across three categories: query understanding, document understanding, and query-document relationship understanding. The dataset is designed for instruction tuning, a method that fine-tunes LLMs on natural language instructions. [git (⭐194)](https://github.com/DaoD/INTERS) \[12 Jan 2024]
    *   [RAG vs Fine-tuning](https://arxiv.org/abs/2401.08406): Pipelines, Tradeoffs, and a Case Study on Agriculture. \[16 Jan 2024]
    *   [The Power of Noise: Redefining Retrieval for RAG Systems](https://arxiv.org/abs/2401.14887): No more than 2-5 relevant docs + some amount of random noise to the LLM context maximizes the accuracy of the RAG. \[26 Jan 2024]
    *   [Corrective Retrieval Augmented Generation (CRAG)](https://arxiv.org/abs/2401.15884): Retrieval Evaluator assesses the retrieved documents and categorizes them as Correct, Ambiguous, or Incorrect1. For Ambiguous and Incorrect documents, the method uses Web Search to improve the quality of the information. The refined and distilled documents are then used to generate the final output. \[29 Jan 2024] CRAG implementation by LangGraph [git (⭐5.2k)](https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_crag.ipynb)
    *   [RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://arxiv.org/abs/2401.18059): Introduce a novel approach to retrieval-augmented language models by constructing a recursive tree structure from documents. [git (⭐35k)](https://github.com/run-llama/llama_index/blob/main/llama-index-packs/llama-index-packs-raptor/README.md) `pip install llama-index-packs-raptor` / [git (⭐27)](https://github.com/profintegra/raptor-rag) \[31 Jan 2024]
    *   [CRAG: Comprehensive RAG Benchmark](https://arxiv.org/abs/2406.04744): a factual question answering benchmark of 4,409 question-answer pairs and mock APIs to simulate web and Knowledge Graph (KG) search [ref](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024) \[7 Jun 2024]
    *   [PlanRAG](https://arxiv.org/abs/2406.12430): Decision Making. Decision QA benchmark, DQA. Plan -> Retrieve -> Make a decision (PlanRAG) [git (⭐112)](https://github.com/myeon9h/PlanRAG) \[18 Jun 2024]
    *   [Searching for Best Practices in Retrieval-Augmented Generation](https://arxiv.org/abs/2407.01219): `Best Performance Practice`: Query Classification, Hybrid with HyDE (retrieval), monoT5 (reranking), Reverse (repacking), Recomp (summarization). `Balanced Efficiency Practice`: Query Classification, Hybrid (retrieval), TILDEv2 (reranking), Reverse (repacking), Recomp (summarization). \[1 Jul 2024]
    *   [Retrieval Augmented Generation or Long-Context LLMs?](https://arxiv.org/abs/2407.16833): Long-Context consistently outperforms RAG in terms of average performance. However, RAG's significantly lower cost remains a distinct advantage. \[23 Jul 2024]
    *   [Graph Retrieval-Augmented Generation: A Survey](https://arxiv.org/abs/2408.08921) \[15 Aug 2024]

    </details>

### **RAG Pipeline & Advanced RAG**

*   How to optimize RAG pipeline: [Indexing optimization](https://newsletter.theaiedge.io/p/how-to-optimize-your-rag-pipelines) \[24 Oct 2023]

### **Microsoft Azure OpenAI relevant LLM Framework** / **Lucene based search engine with OpenAI Embedding**

*   [JARVIS (⭐23k)](https://github.com/microsoft/JARVIS): an interface for LLMs to connect numerous AI models for solving complicated AI tasks! \[Mar 2023]
*   [Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/): Fabric integrates technologies like Azure Data Factory, Azure Synapse Analytics, and Power BI into a single unified product \[May 2023]

### **Azure Reference Architectures** / **Azure AI Search**

*   A set of capabilities designed to improve relevance in these scenarios. We use a combination of hybrid retrieval (vector search + keyword search) + semantic ranking as the most effective approach for improved relevance out-of–the-box. `TL;DR: Retrieval Performance; Hybrid search + Semantic rank > Hybrid search > Vector only search > Keyword only` [ref](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/azure-cognitive-search-outperforming-vector-search-with-hybrid/ba-p/3929167) \[18 Sep 2023] <br/> <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files\acs-hybrid.png" alt="acs" width="300"/>

### **Semantic Kernel** / **Feature Roadmap**

*   .NET Semantic Kernel SDK: 1. Renamed packages and classes that used the term “Skill” to now use “Plugin”. 2. OpenAI specific in Semantic Kernel core to be AI service agnostic 3. Consolidated our planner implementations into a single package [ref](https://devblogs.microsoft.com/semantic-kernel/introducing-the-v1-0-0-beta1-for-the-net-semantic-kernel-sdk/) \[10 Oct 2023]

### **Semantic Kernel** / **Code Recipes**

*   Chat Copilot Sample Application: A reference application for building a chat experience using Semantic Kernel. Leveraging plugins, planners, and AI memories. [git (⭐2k)](https://github.com/microsoft/chat-copilot) \[Apr 2023]
*   Semantic Kernel Recipes: A collection of C# notebooks [git (⭐165)](https://github.com/johnmaeda/SK-Recipes) \[Mar 2023]
*   Deploy Semantic Kernel with Bot Framework [ref](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/deploy-semantic-kernel-with-bot-framework/ba-p/3928101) [git (⭐51)](https://github.com/Azure/semantic-kernel-bot-in-a-box) \[26 Oct 2023]
*   Semantic Kernel-Powered OpenAI Plugin Development Lifecycle [ref](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/semantic-kernel-powered-openai-plugin-development-lifecycle/ba-p/3967751) \[30 Oct 2023]
*   SemanticKernel Implementation sample to overcome Token limits of Open AI model.
    Semantic Kernel でトークンの限界を超えるような長い文章を分割してスキルに渡して結果を結合したい (zenn.dev)
    [ref](https://zenn.dev/microsoft/articles/semantic-kernel-10) \[06 May 2023]

### **Semantic Kernel** / **Semantic Kernel Planner**

*   Semantic Kernel Planner [ref](https://devblogs.microsoft.com/semantic-kernel/semantic-kernel-planners-actionplanner/) \[24 Jul 2023]

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files\sk-evolution_of_planners.jpg" alt="sk-plan" width="300"/>

### **Semantic Kernel** / **Semantic Function**

*   Prompt Template language Key takeaways

### **LangChain vs Competitors** / **Prompting Frameworks**

*   [Prompting Framework (PF)](https://arxiv.org/abs/2311.12785): Prompting Frameworks for Large Language Models: A Survey [git (⭐72)](https://github.com/lxx0628/Prompting-Framework-Survey)

### **Prompt Guide & Leaked prompts** / **Prompt Template Language**

*   [Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/): Prompt Engineering, also known as In-Context Prompting ... \[Mar 2023]

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   [Fine-tuning a GPT - LoRA](https://dataman-ai.medium.com/fine-tune-a-gpt-lora-e9b72ad4ad3): Comprehensive guide for LoRA [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/Fine-tuning_a_GPT_LoRA.pdf) \[20 Jun 2023]

### **OpenAI's Roadmap and Products** / **OpenAI's plans according to Sam Altman**

*   [Humanloop Interview 2023](https://web.archive.org/web/20230531203946/https://humanloop.com/blog/openai-plans) : [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/openai-plans.pdf) \[29 May 2023]

### **Numbers LLM** / **GPT series release date**

*   [5 Approaches To Solve LLM Token Limits](https://dholmes.co.uk/blog/5-approaches-to-solve-llm-token-limits/) : [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/token-limits-5-approaches.pdf) \[2023]

### **MLLM (multimodal large language model)** / **GPT series release date**

*   Benchmarking Multimodal LLMs.
    *   LLaVA-1.5 achieves SoTA on a broad range of 11 tasks incl. SEED-Bench.
    *   [SEED-Bench](https://arxiv.org/abs/2307.16125): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.16125)]: Benchmarking Multimodal LLMs [git (⭐289)](https://github.com/AILab-CVC/SEED-Bench) \[30 Jul 2023]

        <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/multi-llm.png" width="180" /> -->

### **Learning and Supplementary Materials** / Korean

*   [Large Language Models: Application through Production (⭐727)](https://github.com/databricks-academy/large-language-models): A course on edX & Databricks Academy
*   [Large Language Model Course (⭐36k)](https://github.com/mlabonne/llm-course): Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks. \[Jun 2023]

### **Caching** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   Caching: A technique to store data that has been previously retrieved or computed, so that future requests for the same data can be served faster.
*   To reduce latency, cost, and LLM requests by serving pre-computed or previously served responses.
*   Strategies for caching: Caching can be based on item IDs, pairs of item IDs, constrained input, or pre-computation. Caching can also leverage embedding-based retrieval, approximate nearest neighbor search, and LLM-based evaluation. [ref](https://eugeneyan.com/writing/llm-patterns/#caching-to-reduce-latency-and-cost)

### **Defensive UX** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   Defensive UX: A design strategy that aims to prevent and handle errors in user interactions with machine learning or LLM-based products.
*   Why defensive UX?: Machine learning and LLMs can produce inaccurate or inconsistent output, which can affect user trust and satisfaction. Defensive UX can help by increasing accessibility, trust, and UX quality.
*   [Guidelines for Human-AI Interaction](https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/): Microsoft: Based on a survey of 168 potential guidelines from various sources, they narrowed it down to 18 action rules organized by user interaction stages.
*   [People + AI Guidebook](https://pair.withgoogle.com/guidebook/): Google: Google’s product teams and academic research, they provide 23 patterns grouped by common questions during the product development process3.
*   [Human Interface Guidelines for Machine Learning](https://developer.apple.com/design/human-interface-guidelines/machine-learning): Apple: Based on practitioner knowledge and experience, emphasizing aspects of UI rather than model functionality4.

## [10. Awesome Machine Learning](/content/josephmisiti/awesome-machine-learning/week/README.md)

### C++ / General-Purpose Machine Learning

*   [Truss](https://truss.baseten.co) - An open source framework for packaging and serving ML models.

### Python / Computer Vision

*   [MLX (⭐16k)](https://github.com/ml-explore/mlx)- MLX is an array framework for machine learning on Apple silicon, developed by Apple machine learning research.

### Python / Neural Networks

*   [Kinho (⭐31)](https://github.com/kinhosz/Neural) - Simple API for Neural Network. Better for image processing with CPU/GPU + Transfer Learning.

### Tools / Misc

*   [Infinity (⭐2.2k)](https://github.com/infiniflow/infinity) - The AI-native database built for LLM applications, providing incredibly fast vector and full-text search. Developed using C++20

## [11. Awesome Ipfs](/content/ipfs/awesome-ipfs/week/README.md)

### Pinning services

*   [Gateway3](https://gw3.app/) - A decentralized IPFS pinning service designed for developers. Supports content pinning, IPNS hosting, DAG operations, pinning tweets, and web hosting.

## [12. Free for Dev](/content/ripienaar/free-for-dev/week/README.md)

### Testing

*   [webhookbeam.com](https://webhookbeam.com) - Set up webhooks and monitor them via push notifications and emails.

### Generative AI

*   [Portkey](https://portkey.ai/) - Control panel for Gen AI apps featuring an observability suite & an AI gateway. Send & log up to 10,000 requests for free every month.
*   [OpenPipe](https://openpipe.ai) - Fully managed fine-tuning for developers. Free plan lets you fine-tune one model with upto 2,000 rows per dataset.
*   [Braintrust](https://www.braintrustdata.com/) - Evals, prompt playground, and data management for Gen AI. Free plan gives upto 1,000 private eval rows/week.

### Analytics, Events and Statistics

*   [LogSpot](https://logspot.io) - Full unified web and product analytics platform, including embeddable analytics widgets and automated robots (slack, telegram, and webhooks). Free plan includes 10,000 events per month.

### Privacy Management

*   [Concord](https://www.concord.tech/) - Full data privacy platform, including consent management, privacy request handling (DSARs), and data mapping. Free tier includes core consent management features and they also provide a more advanced plan for free to verified open source projects.

## [13. Free Programming Books (English, By Subjects)](/content/EbookFoundation/free-programming-books/books/free-programming-books-subjects/week/README.md)

### Security & Privacy

*   [The MoonMath Manual to zk-SNARKs](https://leastauthority.com/community-matters/moonmath-manual/) - Least Authority

## [14. Awesome Theoretical Computer Science](/content/mostafatouny/awesome-theoretical-computer-science/week/README.md)

### Lecture Notes / Monograph

*   [Chekuri. Approximation Algorithmis Illinois](https://courses.engr.illinois.edu/cs583/fa2021/) - A broad introduction to results and techniques with an emphasis on fundamental problems and widely applicable tools. Also more advanced and specialized topics.
*   [Dinitz. Approximation Algorithms. Johns Hopkins](https://www.cs.jhu.edu/~mdinitz/classes/ApproxAlgorithms/Spring2021/) - It includes greedy, local search, dynamic programming, randomized rounding, tree embeddings, and semidefinite programming.
*   [Gupta & Ravi. Approximation Algorithms. CMU](http://www.cs.cmu.edu/afs/cs/academic/class/15854-f05/www/) - It includes convex programming-based, randomness, and metric methods.

### Books / Monograph

*   [Williamson & Shmoys. The Design of Approximation Algorithms](https://www.designofapproxalgs.com/) - It includes greedy, local search algorithms, dynamic programming, linear and semidefinite programming, and randomization.
*   [Du & Ko. Design and Analysis of Approximation Algorithms](https://u.pcloud.link/publink/show?code=XZpzNWXZSCkVs6BKd5RzyNhoRzfJCJoaqSok) - A technique-oriented approach provides a unified view. It includes detailed algorithms, proofs, analyses, examples, and applications from research papers.
*   [Vijay Vazirani. Approximation Algorithms](https://u.pcloud.link/publink/show?code=XZgHNWXZkdvT8L18drSSgLP9vqBIDmbPreD7)
*   Fedor Fomin. Parametrized Algorithms - Modern comprehensive explanation of recent tools and techniques with exercises, for graduate students.

## [15. Urban and Regional Planning Resources](/content/APA-Technology-Division/urban-and-regional-planning-resources/week/README.md)

### Public Data Resources / Equity and Environmental Justice

*   [STEAP](https://maps.dot.gov/fhwa/steap/) - The Screening Tool for Equity Analysis of Projects (STEAP) is a census sampling tool that allows rapid screening of potential project locations anywhere in the United States to support Title VI, environmental justice, and other socioeconomic data analyses.

### Vendor Data Resources / Infrastructure

*   [Geomate](https://geomate.ca/en/) - Geomate provides HD vector maps from high-resolution aerial imagery to support autonomous vehicles and urban planning use cases.

## [16. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/week/README.md)

### Software / Communication - Custom Communication Systems

*   [Mattermost](https://mattermost.com/) - Platform for secure collaboration across the entire software development lifecycle, can be integrated with Gitlab (alternative to Slack). ([Source Code (⭐29k)](https://github.com/mattermost/mattermost)) `AGPL-3.0/Apache-2.0` `Go/Docker/K8S`

### Software / Groupware

*   [Tine](https://www.tine-groupware.de/) - Software for digital collaboration in companies and organizations. From powerful groupware functionalities to clever add-ons, tine combines everything to make daily team collaboration easier. ([Source Code (⭐11)](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`

## [17. Awesome Digital History](/content/maehr/awesome-digital-history/week/README.md)

### Archives and primary sources / Africa

*   [West African Arabic Manuscript Database](https://islam.zmo.de/s/westafrica/page/home) - A comprehensive collection of manuscripts that provides insight into the Islamic scholarly tradition in West Africa.

### Learning / Switzerland

*   [Introduction to Python for Humanists](https://python-textbook.pythonhumanities.com/intro.html) - A textbook offering a comprehensive introduction to Python programming, tailored for researchers and students in the humanities.

## [18. Awesome Terraform](/content/shuaibiyy/awesome-terraform/week/README.md)

### Managed Registries / Miscellaneous

*   [cloudsmith](https://help.cloudsmith.io/docs/terraform-modules-repository) - Managed package hoster for internal and external clients. :heavy\_dollar\_sign:

## [19. Awesome Neovim](/content/rockerBOO/awesome-neovim/week/README.md)

### (requires Neovim 0.5)

*   [lopi-py/luau-lsp.nvim (⭐38)](https://github.com/lopi-py/luau-lsp.nvim) - A luau-lsp extension to improve your experience.

### AI / Diagnostics

*   [gsuuon/model.nvim (⭐313)](https://github.com/gsuuon/model.nvim) - Integrate LLMs via a prompt builder interface. Multi-providers including OpenAI (+ compatibles), PaLM, HuggingFace and local engines like llamacpp.

### Marks / Diagnostics

*   [otavioschwanck/arrow.nvim (⭐442)](https://github.com/otavioschwanck/arrow.nvim) - Like harpoon, but with a different UX, single keybinding needed and statusline support.

### Project / Diagnostics

*   [LintaoAmons/cd-project.nvim (⭐95)](https://github.com/LintaoAmons/cd-project.nvim) - All you need is just an easier way to `cd` to another project directory.

## [20. Awesome Developer First](/content/agamm/awesome-developer-first/week/README.md)

### Authentication & Identity

*   [Kinde](https://kinde.com/) - Authentification and user management as a service.

### Backend-as-a-Service

*   [Appwrite](https://appwrite.io/) - End-to-end backend server for frontend and mobile developers. [![Appwrite](https://img.shields.io/github/stars/appwrite/appwrite?style=flat-square\&logo=github\&labelColor=%230D1117\&color=%23161B22)](https://github.com/appwrite/appwrite)

## [21. Awesome Capacitorjs](/content/capawesome-team/awesome-capacitorjs/week/README.md)

### Plugins / Community Plugins

*   [@capawesome-team/capacitor-android-dark-mode-support](https://capawesome.io/plugins/android-dark-mode-support) - Capacitor plugin to support dark mode on Android.
*   [@capawesome-team/capacitor-android-foreground-service](https://capawesome.io/plugins/android-foreground-service) - Capacitor plugin to run a foreground service on Android.
*   [@capawesome-team/capacitor-datetime-picker](https://capawesome.io/plugins/datetime-picker) - Capacitor plugin that let the user easily enter both a date and a time.
*   [@capawesome-team/capacitor-file-compressor](https://capawesome.io/plugins/file-compressor) - Capacitor plugin for compressing files.
*   [@capawesome-team/capacitor-file-opener](https://capawesome.io/plugins/file-opener) - Capacitor plugin to open a file with the default application.
*   [@capawesome-team/capacitor-nfc](https://capawesome.io/plugins/nfc) - Capacitor plugin for reading and writing NFC tags.
*   [@capawesome-team/capacitor-printer](https://capawesome.io/plugins/printer) - Capacitor plugin for printing.

## [22. Awesome Ai4lam](/content/AI4LAM/awesome-ai4lam/week/README.md)

### Learning Resources / Generative AI

*   [What are large language models (LLMs)?](https://www.youtube.com/watch?v=iR2O2GPbB0E) – (YouTube) by Google for Developers
*   [Generative AI for Everyone](https://www.coursera.org/learn/generative-ai-for-everyone?irclickid=S5hzeGTIExyPTTOSNn2PRyfHUkHzH8TNw0Bo1c0\&irgwc=1) – free Coursera course by Andrew Ng
*   [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) – by Stephen Wolfram

### Publications and News Sources / Journals and Magazines

*   [AI & Society](https://link.springer.com/journal/146/articles)
*   [Archival Science](https://link.springer.com/journal/10502)
*   [Big Data & Society](https://journals.sagepub.com/home/bds)
*   [Digital Humanities Quarterly](https://digitalhumanities.org/dhq/)
*   [Digital Scholarship in the Humanities](https://academic.oup.com/dsh)
*   [Journal of Cultural Analytics](https://culturalanalytics.org)
*   [Journal of Documentation](https://www.emerald.com/insight/publication/issn/0022-0418)
*   [Journal of Open Humanities Data](https://openhumanitiesdata.metajnl.com)
*   [Journal of the Association for Information Science and Technology](https://asistdl.onlinelibrary.wiley.com/journal/23301643)
*   [Library Hi Tech](https://www.emerald.com/insight/publication/issn/0737-8831)
*   [Literary and Linguistic Computing](https://dl.acm.org/journal/lilc)
*   [Social Science Computer Review](https://journals.sagepub.com/description/SSC)
*   [World Digital Libraries – An International Journal](https://content.iospress.com/journals/world-digital-libraries-an-international-journal)

## [23. Awesome Django](/content/wsvincent/awesome-django/week/README.md)

### Third-Party Packages / APIs

*   [django-webhook (⭐177)](https://github.com/danihodovic/django-webhook) - A plug-and-play Django app for sending outgoing webhooks on model changes.

### Hosting / PaaS (Platforms-as-a-Service)

*   [Piku (⭐5.7k)](https://github.com/piku/piku)

## [24. Awesome Raspberry Pi](/content/thibmaek/awesome-raspberry-pi/week/README.md)

### Tools

*   [PiKISS (⭐872)](https://github.com/jmcerrejon/PiKISS) - A bunch of scripts with menu to make your life easier.

## [25. Awesome Video](/content/krzemienski/awesome-video/week/README.md)

### Learning / Books

*   [Fundamentals of Multimedia](https://www.amazon.com/Fundamentals-Multimedia-Texts-Computer-Science/dp/303062126X/)  - 2022-02-17 (3rd Edition). Ze-Nian Li (Author), Mark S. Drew (Author), Jiangchuan Liu.

### Encoding / Talks Presentations Podcasts

*   [realeyes-media/demo-encoder (⭐56)](https://github.com/realeyes-media/demo-encoder)  - A nodejs encoding system based on ffmpeg and configured to write HLS streaming files to S3 - realeyes-media/demo-encoder

### Streaming Server and Storage / SRT

*   [prologic/tube (⭐22)](https://github.com/prologic/tube)  - 📺 a Youtube-like (without censorship and features you don't need!) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and R...

### Players / Android

*   [google/ExoPlayer (⭐22k)](https://github.com/google/ExoPlayer)  - ExoPlayer is an application level media player for Android.

### FFMPEG / Web

*   [cuda/ubuntu16.04/ffmpeg-gpu/Dockerfile · master · nvidia / container-images / samples](https://gitlab.com/nvidia/container-images/samples/blob/master/cuda/ubuntu16.04/ffmpeg-gpu/Dockerfile)  - Sample Dockerfiles for Docker Hub images
*   [x264 FFmpeg Options Guide - Linux Encoding](https://sites.google.com/site/linuxencoding/x264-ffmpeg-mapping)  -

## [26. Awesome Generative Deep Art](/content/filipecalegario/awesome-generative-deep-art/week/README.md)

### Generative AI history, timelines, maps, and definitions

*   \[🔥🔥🔥] [Generative AI in a nutshell](https://blog.crisp.se/wp-content/uploads/2024/01/generative-AI-in-a-nutshell.png): a map with the most common Generative AI' concepts by Henrik Kniberg [Youtube Video explaining the map](https://www.youtube.com/watch?v=2IK3DFHRFfw)

### Online Tools and Applications

*   [Recast Studio](https://recast.studio): AI-powered podcast marketing assistant.

### Auxiliary tools and concepts / Deforum

*   [Marblism](https://marblism.com): Generate a SaaS boilerplate from a prompt

## [27. Awesome Fantasy](/content/RichardLitt/awesome-fantasy/week/README.md)

### Epic Fantasy / [The Chronicles of Prydain](https://en.wikipedia.org/wiki/The_Chronicles_of_Prydain) 1964 *by [Lloyd Alexander](https://en.wikipedia.org/wiki/Lloyd_Alexander)* [4.42]

*   [The Book of Three](https://www.goodreads.com/book/show/24780.The_Book_of_Three)
*   [The Black Cauldron](https://www.goodreads.com/book/show/24784.The_Black_Cauldron)
*   [The Castle of Llyr](https://www.goodreads.com/book/show/24779.The_Castle_of_Llyr)
*   [Taran Wanderer](https://www.goodreads.com/book/show/24782.Taran_Wanderer)
*   [The High King](https://www.goodreads.com/book/show/24781.The_High_King)

### Epic Fantasy / [The Daevabad Trilogy](https://www.goodreads.com/series/211584-the-daevabad-trilogy) 2017 *by[S. A. Chakraborty](https://en.wikipedia.org/wiki/S._A._Chakraborty)*[4.3]

*   [The City of Brass](https://www.goodreads.com/book/show/32718027-the-city-of-brass)
*   [The Kingdom of Copper](https://www.goodreads.com/book/show/39988431-the-kingdom-of-copper)
*   [The Empire of Gold](https://www.goodreads.com/book/show/52166786-the-empire-of-gold)

## [28. Awesome Privacy](/content/pluja/awesome-privacy/week/README.md)

### Android Gallery

*   **Google Photos** has privacy issues. They collect a lot of data about you, which you can see in their [privacy policy](https://policies.google.com/privacy?hl=en-US#infocollect). Google can scan your photos and might flag them for different reasons, as shown in this [incident](https://petapixel.com/2022/08/22/google-flags-photos-of-fathers-sick-son-as-child-abuse-informs-police/). They also use your photos to improve their AI technology.
*   **Amazon Photos** also has similar privacy problems. Like Google Photos, it gathers a lot of information from your photo gallery. You can see a bit of what kind of data they collect in their [**examples** list](https://www.amazon.com/gp/help/customer/display.html?nodeId=468496\&ref_=footer_privacy#GUID-8966E75F-9B92-4A2B-BFD5-967D57513A40__SECTION_87C837F9CCD84769B4AE2BEB14AF4F01).
*   **Samsung, Huawei, Xiaomi, etc.** Gallery
*   [Aves (⭐2.4k)](https://github.com/deckerst/aves) - Beautiful gallery and metadata explorer app, built for Android with Flutter.
*   [Fossify Gallery (⭐1.5k)](https://github.com/FossifyOrg/Gallery) - Fork of Simple Gallery. Browse your memories without any interruptions with this photo and video gallery.

## [29. Awesome Embedded Rust](/content/rust-embedded/awesome-embedded-rust/week/README.md)

### Peripheral Access Crates / StarFive

*   [`j71xx-pac`](https://crates.io/crates/jh71xx-pac) - svd2rust generated interface to StarFive [JH71xx](https://www.starfivetech.com/en/site/soc) MCUs - ![crates.io](https://img.shields.io/crates/v/jh71xx-pac.svg)

### HAL implementation crates / StarFive

*   [`j71xx-hal`](https://crates.io/crates/jh71xx-hal) - HAL crate for StarFive [JH71xx](https://www.starfivetech.com/en/site/soc) MCUs - ![crates.io](https://img.shields.io/crates/v/jh71xx-hal.svg)

## [30. Awesome React](/content/enaqx/awesome-react/week/README.md)

### React Frameworks

*   [remix (⭐27k)](https://github.com/remix-run/remix) - Full stack web Framework that lets you focus on the user interface

### React Libraries

*   [react-error-boundary (⭐6.4k)](https://github.com/bvaughn/react-error-boundary) - A React error boundary component that lets you catch errors

## [31. Awesome Vite](/content/vitejs/awesome-vite/week/README.md)

### Templates / React

*   [react-component-library-vite (⭐3)](https://github.com/gsharath/react-component-library-vite) - A library template for with `React`, `Javascript`,`Styled-Components`, `Vitest`, `React Testing Library`, `Storybook`.

## [32. Awesome Agi Cocosci](/content/YuzheSHI/awesome-agi-cocosci/week/README.md)

### Domain Specific Language / Design Theory

*   [Domain-Specific Language](https://en.wikipedia.org/wiki/Domain-specific_language) - ***Wikipedia***. Wikipedia encyclopedia entry on Domain Specific Languages.

## [33. Awesome Cl](/content/CodyReichert/awesome-cl/week/README.md)

### C, C++

*   [stacks-api (⭐1)](https://github.com/kilianmh/stacks-api) - a Stacks API client. [AGPL-3.0](https://directory.fsf.org/wiki/License:Apache2.0)

### Web frameworks / Isomorphic web frameworks

*   [Weblocks (Reblocks) (⭐48)](https://github.com/40ants/reblocks) - A widgets-based framework with a built-in ajax update mechanism that "solves the JavaScript problem". [LLGPL](http://opensource.franz.com/preamble.html).
    *   example code bases: [Ultralisp (⭐228)](https://github.com/ultralisp/ultralisp/), [krasnodar (⭐6)](https://github.com/lct23/krasnodar), a dashboard made for a hackaton (2024) ([demo video](https://diode.zone/videos/watch/9e379a86-c530-4e9d-b8be-7437b1f7200b)).

## [34. Awesome Docker](/content/veggiemonk/awesome-docker/week/README.md)

### IDE integrations

*   [denops-docker.vim (⭐82)](https://github.com/skanehira/denops-docker.vim) - Manage docker containers and images in Vim. By [@skanehira](https://github.com/skanehira)

### Web / Other

*   [Mafl (⭐272)](https://github.com/hywax/mafl) - Minimalistic flexible homepage by [@hywax](https://github.com/hywax/)

---

- Prev: [Jan 29 - Feb 04, 2024](/content/2024/5/README.md)
- Next: [Jan 15 - Jan 21, 2024](/content/2024/3/README.md)