# Awesome Azure Openai Llm Overview

A curated collection of resources for 🌌 Azure OpenAI, 🦙 LLMs (+RAG, Agents). Monthly Updates.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/kimtth/awesome-azure-openai-llm/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 kimtth/awesome-azure-openai-llm](https://github.com/kimtth/awesome-azure-openai-llm) · ⭐ 402 · 🏷️ LLM

[ [Daily](/content/kimtth/awesome-azure-openai-llm/README.md) / [Weekly](/content/kimtth/awesome-azure-openai-llm/week/README.md) / Overview ]

---

# Awesome Azure OpenAI + LLM

![GitHub last commit](https://img.shields.io/github/last-commit/kimtth/awesome-azure-openai-llm?label=commit\&color=hotpink\&style=flat-square)
![Azure OpenAI](https://img.shields.io/badge/llm-azure_openai-blue?style=flat-square)
![GitHub Created At](https://img.shields.io/github/created-at/kimtth/awesome-azure-openai-llm?style=flat-square)

A comprehensive, curated collection of resources for Azure OpenAI, Large Language Models (LLMs), and their applications.

🔹Concise Summaries: Each resource is briefly described for quick understanding\
🔹Chronological Organization: Resources appended with date (first commit, publication, or paper release)\
🔹Monthly Updates: The list is updated monthly; candidate entries before the update are tracked in the issue.

<!-- > [!TIP]
> A refined list focusing on Azure and Microsoft products.  
> Check [**_Awesome Azure OpenAI & Copilot_**](https://github.com/kimtth/awesome-azure-openai-copilot).   --> 

## 🧭 Quick Navigation (Propedia-style)

| Layer / Era                 | What it controls                                                                                                                                                                                 | Jump to sections                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Weights** <br/> 2022-2023 | Parametric knowledge baked into the model. <br/> `Themes: Pretraining, Scaling Laws, Fine-tuning, RLHF, Alignment, Instruction-following, Few-shot`                                              | Foundations: [Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-landscape), [Comparison](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-comparison), [Evolutionary Tree](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#evolutionary-tree-of-large-language-models), [LLM Collection](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-collection) <br/> Training: [Finetuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#finetuning), [Other Techniques and LLM Patterns](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#other-techniques-and-llm-patterns), [Training & Fine-tuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#training--fine-tuning) <br/> Behavior and safety: [Trustworthy, Safe and Secure LLM](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#trustworthy-safe-and-secure-llm), [Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-is-abilities), [Reasoning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#reasoning), [Orchestration Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#orchestration-frameworks)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Context** <br/> 2023-2024 | What the model sees at inference time. <br/> `Themes: Prompting, Chain-of-Thought, RAG, Memory, Long Context, Knowledge Injection, Context Engineering`                                          | Prompting: [Prompt Engineering and Visual Prompts](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#prompt-engineering-and-visual-prompts), [Prompt Engineering & Tooling](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#prompt-engineering--tooling) <br/> Retrieval: [RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#rag-retrieval-augmented-generation), [Advanced RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#advanced-rag), [GraphRAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#graphrag), [RAG Application](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#rag-application), [Vector Database & Embedding](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#vector-database--embedding), [Azure AI Search](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#azure-ai-search) <br/> Memory and context windows: [Memory](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#memory), [Context Constraints](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#context-constraints), [Caching](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#caching), [RAG Solution Design](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#rag-solution-design), [RAG Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#rag-research)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Harness** <br/> 2025-2026 | How the agent acts in the real world. <br/> `Themes: Function Calling, Tool Ecosystems, MCP, Skills, Workflow Graphs, Multi-agent, A2A protocols, Orchestration, Agent Infrastructure, Security` | Agent runtime: [Top Agent Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#top-agent-frameworks), [Orchestration Framework](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#orchestration-framework), [Frameworks / SDKs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#frameworks--sdks), [Agent Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#agent-frameworks), [Agent Development](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#agent-development) <br/> Protocols and tools: [Model Context Protocol (MCP)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#model-context-protocol-mcp), [A2A](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#a2a), [Computer use](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#computer-use), [Skill](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#skill), [Harness](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#harness), [Dev Tools, MCP & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#dev-tools-mcp--extensions), [Coding](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#coding) <br/> Ops and governance: [Apps / Ready-to-use Agents](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#apps--ready-to-use-agents), [General AI Tools and Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#general-ai-tools-and-extensions), [Evaluating Large Language Models](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models), [LLM Evalution Benchmarks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#llm-evalution-benchmarks), [LLMOps](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#llmops-large-language-model-operations), [Agent Design Patterns](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#agent-design-patterns), [Agent Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#agent-research), [Reflection, Tool Use, Planning and Multi-agent collaboration](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#reflection-tool-use-planning-and-multi-agent-collaboration), [Proposals & Glossary](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#proposals--glossary) |

Refereces: [DailyDoseOfDS - *Evolution of the Agent Landscape*](https://blog.dailydoseofds.com/p/evolution-of-agent-landscape-from)

## 1. App & Agent

🚀 RAG Systems, LLM Applications, Agents, Frameworks & Orchestration

*   **RAG**
    *   [RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#rag-retrieval-augmented-generation)
    *   [Advanced RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#advanced-rag)
    *   [GraphRAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#graphrag)
    *   [RAG Application](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#rag-application)
    *   [Vector Database & Embedding](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#vector-database--embedding)
*   **Application**
    *   [Top Agent Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#top-agent-frameworks)
    *   [Orchestration Framework](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#orchestration-framework)
    *   [Frameworks / SDKs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#frameworks--sdks)
    *   [Apps / Ready-to-use Agents](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#apps--ready-to-use-agents)
    *   [**Popular LLM Applications** (Ranked by GitHub star count ≥1000)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#popular-llm-applications-ranked-by-github-star-count-1000)
    *   [No Code & User Interface](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#no-code--user-interface)
    *   [Personal AI assistant & desktop](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#personal-ai-assistant--desktop)
    *   [Caching](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#caching)
    *   [Data Processing](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#data-processing)
    *   [Gateway](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#gateway)
    *   [Memory](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#memory)
*   **Agent Protocols**
    *   [MCP](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#model-context-protocol-mcp)
    *   [A2A](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#a2a)
    *   [Computer use](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#computer-use)
*   **Coding & Research**
    *   [Coding](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#coding)
    *   [Skill](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#skill) / [Harness](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#harness)
    *   [Domain-Specific Agents](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#domain-specific-agents)
    *   [Deep Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/applications.md#deep-research)

**[⬆ back to top](#azure-openai--llm)**

## 2. Azure OpenAI & Copilot

🌌 Microsoft's Cloud-Based AI Platform and Services

*   **Overview**
    *   [Azure OpenAI & Foundry Overview](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#azure-openai--foundry-overview)
*   **Frameworks**
    *   [Orchestration Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#orchestration-frameworks)
    *   [Agent Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#agent-frameworks)
*   **Tooling**
    *   [Prompt Engineering & Tooling](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#prompt-engineering--tooling)
    *   [Dev Tools, MCP & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#dev-tools-mcp--extensions)
*   **Products**
    *   [Copilot Product Catalog](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#copilot-product-catalog)
    *   [Agent Development](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#agent-development)
    *   [Microsoft 365 Agent Development](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#microsoft-365-agent-development)
*   **Services**
    *   [Azure AI Search](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#azure-ai-search)
    *   [Microsoft Foundry & AI Services](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#microsoft-foundry--ai-services)
*   **Research**
    *   [Microsoft Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#microsoft-research)
*   **Applications**
    *   [Sample Applications](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#sample-applications)
    *   [Solution Accelerators](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#solution-accelerators)
    *   [Architecture Patterns & Use Cases](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/azure.md#architecture-patterns--use-cases)

**[⬆ back to top](#azure-openai--llm)**

## 3. Research & Survey

🧠 LLM Landscape, Prompt Engineering, Finetuning, Challenges & Surveys

*   **Landscape**
    *   [Large Language Model: Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-landscape)
    *   [Comparison](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-comparison)
    *   [Evolutionary Tree](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#evolutionary-tree-of-large-language-models)
    *   [LLM Collection](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-collection)
*   **Prompting**
    *   [Prompt Engineering and Visual Prompts](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#prompt-engineering-and-visual-prompts)
*   **Finetuning**
    *   [Pre-training and Post-training](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#finetuning)
    *   [Other Techniques and LLM Patterns](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#other-techniques-and-llm-patterns)
*   **Challenges**
    *   [Context Constraints](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#context-constraints)
    *   [Trustworthy, Safe and Secure LLM](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#trustworthy-safe-and-secure-llm)
    *   [Large Language Model's Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#large-language-model-is-abilities)
    *   [Reasoning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#reasoning)
*   **Products & Impact**
    *   [OpenAI Roadmap](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#openai-roadmap)
    *   [OpenAI Models](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#openai-models)
    *   [OpenAI Products](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#openai-products)
    *   [Anthropic Products](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#anthropic-ai-products)
    *   [Google AI Products](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#google-ai-products)
    *   [AGI Discussion and Social Impact](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#agi-discussion-and-social-impact)
*   **Survey & Build**
    *   [Survey on Large Language Models](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#survey-on-large-language-models)
    *   [Additional Topics: A Survey of LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#additional-topics-a-survey-of-llms)
    *   [**LLM Research** (Ranked by cite count ≥150)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#llm-research-ranked-by-cite-count-150)
    *   [Build an LLMs from Scratch](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#build-an-llms-from-scratch-picogpt-and-lit-gpt)
    *   [Business Use Cases](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/models_research.md#business-use-cases)

**[⬆ back to top](#azure-openai--llm)**

## 4. Tools, Datasets, and Evaluation

🛠️ AI Tools, Training Data, Datasets & Evaluation Methods

*   **Tools**
    *   [General AI Tools and Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#general-ai-tools-and-extensions)
    *   [LLM for Robotics](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#llm-for-robotics)
    *   [Awesome Demo](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#awesome-demo)
*   **Data**
    *   [Datasets for LLM Training](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#datasets-for-llm-training)
*   **Evaluation**
    *   [Evaluating Large Language Models](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models)
    *   [LLM Evalution Benchmarks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#llm-evalution-benchmarks)
    *   [LLMOps: Large Language Model Operations](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/tools_extra.md#llmops-large-language-model-operations)

**[⬆ back to top](#azure-openai--llm)**

## 5. Best Practices

📋 Curated Blogs, Patterns, and Implementation Guidelines

*   **RAG**
    *   [The Problem with RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#the-problem-with-rag)
    *   [RAG Solution Design](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#rag-solution-design)
    *   [RAG Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#rag-research)
    *   [**RAG Research** (Ranked by cite count >=100)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#rag-research-ranked-by-cite-count-100)
*   **Agent**
    *   [Agent Design Patterns](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#agent-design-patterns)
    *   [Agent Research](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#agent-research)
    *   [**Agent Research** (Ranked by cite count >=100)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#agent-research-ranked-by-cite-count-100)
    *   [Reflection, Tool Use, Planning and Multi-agent collaboration](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#reflection-tool-use-planning-and-multi-agent-collaboration)
    *   [Tool Use: LLM to Master APIs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#tool-use)
*   **Reference**
    *   [Proposals & Glossary](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/best_practices.md#proposals--glossary)

**[⬆ back to top](#azure-openai--llm)**

## 📖 Legend & Notation

| Symbol | Meaning                   | Symbol                                                                                                                                  | Meaning           |
| ------ | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| ✍️     | Blog post / Documentation | ![github](https://img.shields.io/github/stars/kimtth/awesome-azure-openai-llm?style=flat\&label=%20\&color=f0f1f2\&cacheSeconds=360000) | GitHub repository |
| 🗄️    | Archived files            | 💡🏆                                                                                                                                    | Recommend         |
| 🗣️    | Source citation           | 📺                                                                                                                                      | Video content     |
| 📑     | Academic paper            | 🤗                                                                                                                                      | Huggingface       |

<!-- 
All rights reserved © `kimtth` 
-->

<!-- 
https://shields.io/badges/git-hub-created-at
-->

**[`^        back to top        ^`](#azure-openai--llm)**

