# Awesome List Updates on Dec 11, 2023

2 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **What is the RAG (Retrieval-Augmented Generation)?**

*   In a 2020 paper, Meta (Facebook) came up with a framework called retrieval-augmented generation to give LLMs access to information beyond their training data. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2005.11401)] \[22 May 2020]

    1.  RAG-sequence — We retrieve k documents, and use them to generate all the output tokens that answer a user query.
    2.  RAG-token— We retrieve k documents, use them to generate the next token, then retrieve k more documents, use them to generate the next token, and so on. This means that we could end up retrieving several different sets of documents in the generation of a single answer to a user’s query.
    3.  Of the two approaches proposed in the paper, the RAG-sequence implementation is pretty much always used in the industry. It’s cheaper and simpler to run than the alternative, and it produces great results. [cite](https://towardsdatascience.com/add-your-own-data-to-an-llm-using-retrieval-augmented-generation-rag-b1958bf56a5a) \[30 Sep 2023]

### **LlamaIndex**

*   [LlamaIndex Overview (Japanese)](https://dev.classmethod.jp/articles/llamaindex-tutorial-001-overview-v0-7-9/) \[17 Jul 2023]
*   [LlamaIndex Tutorial](https://nanonets.com/blog/llamaindex/): A Complete LlamaIndex Guide \[18 Oct 2023]
*   [CallbackManager (Japanese)](https://dev.classmethod.jp/articles/llamaindex-tutorial-003-callback-manager/) \[27 May 2023] / [Customize TokenTextSplitter (Japanese)](https://dev.classmethod.jp/articles/llamaindex-tutorial-002-text-splitter/) \[27 May 2023] / [Chat engine ReAct mode](https://gpt-index.readthedocs.io/en/stable/examples/chat_engine/chat_engine_react.html), [FLARE Query engine](https://docs.llamaindex.ai/en/stable/examples/query_engine/flare_query_engine.html)
*   Multimodal RAG Pipeline [ref](https://blog.llamaindex.ai/multi-modal-rag-621de7525fea) \[Nov 2023]

### **Vector Database Comparison**

*   [Not All Vector Databases Are Made Equal](https://towardsdatascience.com/milvus-pinecone-vespa-weaviate-vald-gsi-what-unites-these-buzz-words-and-what-makes-each-9c65a3bd0696): Printed version for "Medium" limits. [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/vector-dbs.pdf) \[2 Oct 2021]

### **Vector Database Comparison** / **Vector Database Options for Azure**

*   [Pgvector extension on Azure Cosmos DB for PostgreSQL](https://azure.microsoft.com/en-us/updates/generally-available-pgvector-extension-on-azure-cosmos-db-for-postgresql/): [ref](https://python.langchain.com/docs/modules/data_connection/vectorstores/integrations/pgvector) \[13 Jun 2023]
*   [Vector Search in Azure Cosmos DB for MongoDB vCore](https://devblogs.microsoft.com/cosmosdb/introducing-vector-search-in-azure-cosmos-db-for-mongodb-vcore/) \[23 May 2023]
*   [Azure Cache for Redis Enterprise](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/introducing-vector-search-similarity-capabilities-in-azure-cache/ba-p/3827512): Enterprise [Redis Vector Search Demo](https://ecommerce.redisventures.com/) \[22 May 2023 ]

### **Vector Database Comparison** / **Lucene based search engine with OpenAI Embedding**

*   [Vector Search with OpenAI Embeddings: Lucene Is All You Need](https://arxiv.org/abs/2308.14963): Our experiments were based on Lucene 9.5.0, but indexing was a bit tricky
    because the HNSW implementation in Lucene restricts vectors to 1024 dimensions, which was not sufficient for OpenAI’s 1536-dimensional embeddings. Although the resolution of this issue, which is to make vector dimensions configurable on a per codec basis, has been merged to the Lucene source trunk [git (⭐2.5k)](https://github.com/apache/lucene/pull/12436), this feature has not been folded into a Lucene release (yet) as of early August 2023. \[29 Aug 2023]

### **Microsoft Azure OpenAI relevant LLM Framework** / **Lucene based search engine with OpenAI Embedding**

*   [Kernel Memory (⭐1.3k)](https://github.com/microsoft/kernel-memory): Kernel Memory (FKA. Semantic Memory (SM)) is an open-source service and plugin specialized in the efficient indexing of datasets through custom continuous data hybrid pipelines. \[Jul 2023]
*   [FLAML (⭐3.8k)](https://github.com/microsoft/FLAML): A lightweight Python library for efficient automation of machine learning and AI operations. FLAML provides an seamless interface for AutoGen, AutoML, and generic hyperparameter tuning. \[Dec 2020]
*   A Memory in Semantic Kernel vs Kernel Memory (FKA. Semantic Memory (SM)): Kernel Memory is designed to efficiently handle large datasets and extended conversations. Deploying the memory pipeline as a separate service can be beneficial when dealing with large documents or long bot conversations. [ref (⭐1.9k)](https://github.com/microsoft/chat-copilot/tree/main/memorypipeline)

### **Azure Reference Architectures** / **Azure AI Search**

*   Azure Cognitive Search rebranding Azure AI Search, it supports Vector search and semantic ranker. \[16 Nov 2023]

### **Azure Enterprise Services** / **Azure AI Search**

*   Azure OpenAI Service On Your Data in Public Preview [ref](https://techcommunity.microsoft.com/t5/ai-cognitive-services-blog/introducing-azure-openai-service-on-your-data-in-public-preview/ba-p/3847000) \[19 Jun 2023]
*   Azure OpenAI Finetuning: Babbage-002 is $34/hour, Davinci-002 is $68/hour, and Turbo is $102/hour. [ref](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/fine-tuning-now-available-with-azure-openai-service/ba-p/3954693) \[16 Oct 2023]
*   Customer Copyright Commitment: protects customers from certain IP claims related to AI-generated content. [ref](https://learn.microsoft.com/en-us/legal/cognitive-services/openai/customer-copyright-commitment) \[16 Nov 2023]

### **Semantic Kernel** / **Semantic Kernel Planner**

*   Stepwise Planner released. The Stepwise Planner features the "CreateScratchPad" function, acting as a 'Scratch Pad' to aggregate goal-oriented steps. \[16 Aug 2023]

### **Prompt Engineering** / **Prompt Template Language**

*   [ReAct](https://arxiv.org/abs/2210.03629): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2210.03629)]: Grounding with external sources. (Reasoning and Act): Combines reasoning and acting [ref](https://react-lm.github.io/) \[6 Oct 2022]
*   Zero-shot
    *   [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2205.11916)]: Let’s think step by step. \[24 May 2022]
*   Few-shot Learning
    *   [Open AI: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2005.14165)] \[28 May 2020]
*   [Retrieval Augmented Generation (RAG)](https://arxiv.org/abs/2005.11401): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2005.11401)]: To address such knowledge-intensive tasks. RAG combines an information retrieval component with a text generator model. \[22 May 2020]
*   [Chain-of-Verification reduces Hallucination in LLMs](https://arxiv.org/abs/2309.11495): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.11495)]: A four-step process that consists of generating a baseline response, planning verification questions, executing verification questions, and generating a final verified response based on the verification results. \[20 Sep 2023]
*   [Reflexion](https://arxiv.org/abs/2303.11366): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2303.11366)]: Language Agents with Verbal Reinforcement Learning. 1. Reflexion that uses `verbal reinforcement`
    to help agents learn from prior failings. 2. Reflexion converts binary or scalar feedback from the environment into verbal feedback in the form of a textual summary, which is then added as additional context for the LLM agent in the next episode. 3. It is lightweight and doesn’t require finetuning the LLM. \[20 Mar 2023] / [git (⭐2.1k)](https://github.com/noahshinn024/reflexion)

### **Langchain Agent & Memory** / **Criticism to Langchain**

*   The Problem With LangChain: [ref](https://minimaxir.com/2023/07/langchain-problem/) / [git (⭐29)](https://github.com/minimaxir/langchain-problems) \[14 Jul 2023]
*   What’s your biggest complaint about langchain?: [ref](https://www.reddit.com/r/LangChain/comments/139bu99/whats_your_biggest_complaint_about_langchain/) \[May 2023]

### **Langchain vs Competitors** / **Langchain vs LlamaIndex**

*   Basically LlamaIndex is a smart storage mechanism, while Langchain is a tool to bring multiple tools together. [cite](https://community.openai.com/t/llamaindex-vs-langchain-which-one-should-be-used/163139) \[14 Apr 2023]

### **Langchain vs Competitors** / **Langchain vs Semantic Kernel vs Azure Machine Learning Prompt flow**

*   What's the difference between LangChain and Semantic Kernel?

    LangChain has many agents, tools, plugins etc. out of the box. More over, LangChain has 10x more popularity, so has about 10x more developer activity to improve it. On other hand, **Semantic Kernel architecture and quality is better**, that's quite promising for Semantic Kernel. [ref (⭐20k)](https://github.com/microsoft/semantic-kernel/discussions/1326) \[11 May 2023]
*   Using Prompt flow with Semantic Kernel: [ref](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/planners/evaluate-and-deploy-planners/) \[07 Sep 2023]

### **Finetuning** / **Prompt Template Language**

*   [PEFT](https://huggingface.co/blog/peft): Parameter-Efficient Fine-Tuning. PEFT is an approach to fine tuning only a few parameters. \[10 Feb 2023]
*   [Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2303.15647): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2303.15647)] \[28 Mar 2023]
*   [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.14314)]: 4-bit quantized pre-trained language model into Low Rank Adapters (LoRA). [git (⭐9.7k)](https://github.com/artidoro/qlora) \[23 May 2023]
*   [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2203.02155)] \[4 Mar 2022]
*   [LIMA: Less Is More for Alignment](https://arxiv.org/abs/2305.11206): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.11206)]: fine-tuned with the standard supervised loss on <b>only 1,000 carefully curated prompts and responses, without any reinforcement learning or human preference modeling.</b> LIMA demonstrates remarkably strong performance, either equivalent or strictly preferred to GPT-4 in 43% of cases. \[18 May 2023]
*   <details>

    <summary>Expand</summary>

    1.  [LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models](https://arxiv.org/abs/2309.12307): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.12307)]: A combination of sparse local attention and LoRA [git (⭐2.5k)](https://github.com/dvlab-research/LongLoRA) \[21 Sep 2023]

    *   Key Takeaways from LongLora

        <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/longlora.png" alt="long-lora"/>

        1.  The document states that LoRA alone is not sufficient for long context extension.

        2.  Although dense global attention is needed during inference, fine-tuning the model can be done by sparse local attention, shift short attention (S2-Attn).

        3.  S2-Attn can be implemented with only two lines of code in training.

    2.  [QA-LoRA](https://arxiv.org/abs/2309.14717): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.14717)]: Quantization-Aware Low-Rank Adaptation of Large Language Models. A method that integrates quantization and low-rank adaptation for large language models. [git (⭐100)](https://github.com/yuhuixu1993/qa-lora) \[26 Sep 2023]

### **Finetuning** / **Llama 2 Finetuning**

*   [Multi-query attention (MQA)](https://arxiv.org/abs/2305.13245): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.13245)] \[22 May 2023]
*   [Comprehensive Guide for LLaMA with RLHF](https://huggingface.co/blog/stackllama): StackLLaMA: A hands-on guide to train LLaMA with RLHF \[5 Apr 2023]

### **RLHF (Reinforcement Learning from Human Feedback) & SFT (Supervised Fine-Tuning)** / **Llama 2 Finetuning**

*   Libraries: [TRL](https://huggingface.co/docs/trl/index), [trlX (⭐4.4k)](https://github.com/CarperAI/trlx), [Argilla](https://docs.argilla.io/en/latest/tutorials/libraries/colab.html)

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/TRL-readme.png" width="500" />

    <!-- [SFTTrainer](https://huggingface.co/docs/trl/main/en/trainer#trl.SFTTrainer) from TRL -->

    TRL: from the Supervised Fine-tuning step (SFT), Reward Modeling step (RM) to the Proximal Policy Optimization (PPO) step

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/chip.jpg" width="400" />

    The three steps in the process: 1. pre-training on large web-scale data, 2. supervised fine-tuning on instruction data (instruction tuning), and 3. RLHF. [ref](https://aman.ai/primers/ai/RLHF/) \[ⓒ 2023]
*   `Supervised Fine-Tuning (SFT)` fine-tuning a pre-trained model on a specific task or domain using labeled data. This can cause more significant shifts in the model’s behavior compared to RLHF.

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/rlhf-dpo.png" width="400" />
*   [Reinforcement Learning from AI Feedback (RLAF)](https://arxiv.org/abs/2309.00267): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.00267)]: Uses AI feedback to generate instructions for the model. TLDR: CoT (Chain-of-Thought, Improved), Few-shot (Not improved). Only explores the task of summarization. After training on a few thousand examples, performance is close to training on the full dataset. RLAIF vs RLHF: In many cases, the two policies produced similar summaries. \[1 Sep 2023]

### **Model Compression for Large Language Models** / **Llama 2 Finetuning**

*   A Survey on Model Compression for Large Language Models [ref](https://arxiv.org/abs/2308.07633) \[15 Aug 2023]

### **Pruning and Sparsification** / **Llama 2 Finetuning**

*   [Wanda Pruning](https://arxiv.org/abs/2306.11695): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2306.11695)]: A Simple and Effective Pruning Approach for Large Language Models \[20 Jun 2023] [ref](https://www.linkedin.com/pulse/efficient-model-pruning-large-language-models-wandas-ayoub-kirouane)

### **Knowledge Distillation: Reducing Model Size with Textbooks** / **Llama 2 Finetuning**

*   [Orca 2](https://arxiv.org/abs/2311.11045): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2311.11045)]: Orca learns from rich signals from GPT 4 including explanation traces; step-by-step thought processes; and other complex instructions, guided by teacher assistance from ChatGPT. [ref](https://www.microsoft.com/en-us/research/blog/orca-2-teaching-small-language-models-how-to-reason/) \[18 Nov 2023]
*   Distilled Supervised Fine-Tuning (dSFT)
    1.  [Zephyr 7B](https://arxiv.org/abs/2310.16944): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.16944)] Zephyr-7B-β is the second model in the series, and is a fine-tuned version of mistralai/Mistral-7B-v0.1 that was trained on on a mix of publicly available, synthetic datasets using Direct Preference Optimization (DPO). [ref](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta) \[25 Oct 2023]
    2.  [Mistral 7B](https://arxiv.org/abs/2310.06825): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.06825)]: Outperforms Llama 2 13B on all benchmarks. Uses Grouped-query attention (GQA) for faster inference. Uses Sliding Window Attention (SWA) to handle longer sequences at smaller cost. [ref](https://mistral.ai/news/announcing-mistral-7b/) \[10 Oct 2023]

### **Other techniques and LLM patterns** / **Llama 2 Finetuning**

*   [Large Transformer Model Inference Optimization](https://lilianweng.github.io/posts/2023-01-10-inference-optimization/): Besides the increasing size of SoTA models, there are two main factors contributing to the inference challenge ... \[10 Jan 2023]

### **3. Visual Prompting & Visual Grounding** / **Llama 2 Finetuning**

*   [Visual Prompting](https://arxiv.org/abs/2211.11635) \[21 Nov 2022]
*   [Andrew Ng’s Visual Prompting Livestream](https://www.youtube.com/watch?v=FE88OOUBonQ) \[24 Apr 2023]

### **OpenAI's Roadmap and Products** / **OpenAI's plans according to Sam Altman**

*   OpenAI’s CEO Says the Age of Giant AI Models Is Already Over [ref](https://www.wired.com/story/openai-ceo-sam-altman-the-age-of-giant-ai-models-is-already-over/) \[17 Apr 2023]
*   Q\* (pronounced as Q-Star): The model, called Q\* was able to solve basic maths problems it had not seen before, according to the tech news site the Information. [ref](https://www.theguardian.com/business/2023/nov/23/openai-was-working-on-advanced-model-so-powerful-it-alarmed-staff) \[23 Nov 2023]

### **OpenAI's Roadmap and Products** / **GPT-4 details leaked** `unverified`

*   GPT-4V(ision) system card: [ref](https://openai.com/research/gpt-4v-system-card) \[25 Sep 2023] / [ref](https://cdn.openai.com/papers/GPTV_System_Card.pdf)
*   [The Dawn of LMMs](https://arxiv.org/abs/2309.17421): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.17421)]: Preliminary Explorations with GPT-4V(ision) \[29 Sep 2023]
*   GPT-4 details leaked
    *   GPT-4 is a language model with approximately 1.8 trillion parameters across 120 layers, 10x larger than GPT-3. It uses a Mixture of Experts (MoE) model with 16 experts, each having about 111 billion parameters. Utilizing MoE allows for more efficient use of resources during inference, needing only about 280 billion parameters and 560 TFLOPs, compared to the 1.8 trillion parameters and 3,700 TFLOPs required for a purely dense model.
    *   The model is trained on approximately 13 trillion tokens from various sources, including internet data, books, and research papers. To reduce training costs, OpenAI employs tensor and pipeline parallelism, and a large batch size of 60 million. The estimated training cost for GPT-4 is around $63 million. [ref](https://www.reddit.com/r/LocalLLaMA/comments/14wbmio/gpt4_details_leaked) \[Jul 2023]

### **OpenAI's Roadmap and Products** / **OpenAI Products**

*   [OpenAI DevDay 2023](https://openai.com/blog/new-models-and-developer-products-announced-at-devday): GPT-4 Turbo with 128K context, Assistants API (Code interpreter, Retrieval, and function calling), GPTs (Custom versions of ChatGPT: [ref](https://openai.com/blog/introducing-gpts)), Copyright Shield, Parallel Function Calling, JSON Mode, Reproducible outputs \[6 Nov 2023]
*   [ChatGPT can now see, hear, and speak](https://openai.com/blog/chatgpt-can-now-see-hear-and-speak): It has recently been updated to support multimodal capabilities, including voice and image. \[25 Sep 2023] [Whisper (⭐64k)](https://github.com/openai/whisper) / [CLIP (⭐23k)](https://github.com/openai/Clip)
*   [GPT-3.5 Turbo Fine-tuning](https://openai.com/blog/gpt-3-5-turbo-fine-tuning-and-api-updates) Fine-tuning for GPT-3.5 Turbo is now available, with fine-tuning for GPT-4 coming this fall. \[22 Aug 2023]
*   [DALL·E 3](https://openai.com/dall-e-3) : In September 2023, OpenAI announced their latest image model, DALL-E 3 [git (⭐11k)](https://github.com/openai/dall-e) \[Sep 2023]
*   Open AI Enterprise: Removes GPT-4 usage caps, and performs up to two times faster [ref](https://openai.com/blog/introducing-chatgpt-enterprise) \[28 Aug 2023]
*   [Custom instructions](https://openai.com/blog/custom-instructions-for-chatgpt): In a nutshell, the Custom Instructions feature is a cross-session memory that allows ChatGPT to retain key instructions across chat sessions. \[20 Jul 2023]

### **Trustworthy, Safe and Secure LLM** / **GPT series release date**

*   [The Foundation Model Transparency Index](https://arxiv.org/abs/2310.12941): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.12941)]: A comprehensive assessment of the transparency of foundation model developers [ref](https://crfm.stanford.edu/fmti/) \[19 Oct 2023]
*   [Hallucinations](https://arxiv.org/abs/2311.05232): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2311.05232)]: A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions \[9 Nov 2023]

### **Large Language Model Is: Abilities** / **GPT series release date**

*   [Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2206.07682)]: Large language models can develop emergent abilities, which are not explicitly trained but appear at scale and are not present in smaller models. . These abilities can be enhanced using few-shot and augmented prompting techniques. [ref](https://www.jasonwei.net/blog/emergence) \[15 Jun 2022]
*   [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2110.08207)]: A language model trained on various tasks using prompts can learn and generalize to new tasks in a zero-shot manner. \[15 Oct 2021]
*   [Language Modeling Is Compression](https://arxiv.org/abs/2309.10668): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.10668)]: Lossless data compression, while trained primarily on text, compresses ImageNet patches to 43.4% and LibriSpeech samples to 16.4% of their raw size, beating domain-specific compressors like PNG (58.5%) or FLAC (30.3%). \[19 Sep 2023]
*   [LLMs Represent Space and Time](https://arxiv.org/abs/2310.02207): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.02207)]: Large language models learn world models of space and time from text-only training. \[3 Oct 2023]
*   [Improving mathematical reasoning with process supervision](https://openai.com/research/improving-mathematical-reasoning-with-process-supervision) \[31 May 2023]
*   [Large Language Models for Software Engineering](https://arxiv.org/abs/2310.03533): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2310.03533)]: Survey and Open Problems, Large Language Models (LLMs) for Software Engineering (SE) applications, such as code generation, testing, repair, and documentation. \[5 Oct 2023]
*   [LLMs for Chip Design](https://arxiv.org/abs/2311.00176): Domain-Adapted LLMs for Chip Design \[31 Oct 2023]

### **Large Language Models (in 2023)** / **GPT series release date**

*   [Twitter](https://twitter.com/hwchung27/status/1710003293223821658) / [Video](https://t.co/vumzAtUvBl) / [Slides](https://t.co/IidLe4JfrC) \[6 Oct 2023]

### **Evolutionary Tree of Large Language Models** / **GPT series release date**

*   [A Survey of Large Language Models](https://arxiv.org/abs/2303.18223): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2303.18223)] /[git (⭐9.5k)](https://github.com/RUCAIBox/LLMSurvey) \[31 Mar 2023] contd.
*   [LLM evolutionary tree](https://arxiv.org/abs/2304.13712): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2304.13712)]: A curated list of practical guide resources of LLMs (LLMs Tree, Examples, Papers) [git (⭐9k)](https://github.com/Mooler0410/LLMsPracticalGuide) \[26 Apr 2023]

### **LLM Materials for East Asian Languages** / Japanese

*   [LLM 研究プロジェクト](https://blog.brainpad.co.jp/entry/2023/07/27/153006): ブログ記事一覧 \[27 Jul 2023]
*   [rinna](https://huggingface.co/rinna): rinna の 36 億パラメータの日本語 GPT 言語モデル: 3.6 billion parameter Japanese GPT language model \[17 May 2023]
*   [rinna: bilingual-gpt-neox-4b](https://huggingface.co/rinna/bilingual-gpt-neox-4b): 日英バイリンガル大規模言語モデル \[17 May 2023]

### **Learning and Supplementary Materials** / Korean

*   [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+1706.03762)]: 🏆 The Transformer,
    based solely on attention mechanisms, dispensing with recurrence and convolutions
    entirely. \[12 Jun 2017] [Illustrated transformer](http://jalammar.github.io/illustrated-transformer/)
*   [Must read: the 100 most cited AI papers in 2022](https://www.zeta-alpha.com/post/must-read-the-100-most-cited-ai-papers-in-2022) : [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/top-cited-2020-2021-2022-papers.pdf) \[8 Mar 2023]
*   [The Best Machine Learning Resources](https://medium.com/machine-learning-for-humans/how-to-learn-machine-learning-24d53bb64aa1) : [doc](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/files/ml_rsc.pdf) \[20 Aug 2017]
*   [What are the most influential current AI Papers?](https://arxiv.org/abs/2308.04889): NLLG Quarterly arXiv Report 06/23 [git (⭐8)](https://github.com/NL2G/Quaterly-Arxiv) \[31 Jul 2023]
*   [Comparing Adobe Firefly, Dalle-2, OpenJourney, Stable Diffusion, and Midjourney](https://blog.usmanity.com/comparing-adobe-firefly-dalle-2-and-openjourney/): Generative AI for images \[20 Jun 2023]
*   [Open Problem and Limitation of RLHF](https://arxiv.org/abs/2307.15217): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2307.15217)]: Provides an overview of open problems and the limitations of RLHF \[27 Jul 2023]

### **Section 11: Datasets for LLM Training** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   LLM-generated datasets:
    1.  [Self-Instruct](https://arxiv.org/abs/2212.10560): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2212.10560)]: Seed task pool with a set of human-written instructions. \[20 Dec 2022]
    2.  [Self-Alignment with Instruction Backtranslation](https://arxiv.org/abs/2308.06259): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2308.06259)]: Without human seeding, use LLM to produce instruction-response pairs. The process involves two steps: self-augmentation and self-curation. \[11 Aug 2023]
*   [RedPajama](https://together.ai/blog/redpajama): LLaMA training dataset of over 1.2 trillion tokens [git (⭐4.4k)](https://github.com/togethercomputer/RedPajama-Data) \[17 Apr 2023]

### **Challenges in evaluating AI systems** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   [Pretraining on the Test Set Is All You Need](https://arxiv.org/abs/2309.08632): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.08632)]
    *   On that note, in the satirical Pretraining on the Test Set Is All You Need paper, the author trains a small 1M parameter LLM that outperforms all other models, including the 1.3B phi-1.5 model. This is achieved by training the model on all downstream academic benchmarks. It appears to be a subtle criticism underlining how easily benchmarks can be "cheated" intentionally or unintentionally (due to data contamination). [cite](https://twitter.com/rasbt) \[13 Sep 2023]

## [2. Awesome Cakephp](/content/FriendsOfCake/awesome-cakephp/README.md)

### Templating

*   🍰 [Templating (⭐1)](https://github.com/dereuromark/cakephp-templating) - HTML snippets as value objects, (Font) icons, and templating topics.

---

- Prev: [Dec 12, 2023](/content/2023/12/12/README.md)
- Next: [Dec 10, 2023](/content/2023/12/10/README.md)