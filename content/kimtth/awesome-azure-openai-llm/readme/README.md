# Awesome Azure Openai Llm Overview

A curated collection of resources for 🌌 Azure OpenAI, 🦙 LLMs (+RAG, Agents). Monthly Updates.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/kimtth/awesome-azure-openai-llm/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 kimtth/awesome-azure-openai-llm](https://github.com/kimtth/azure-openai-llm-notes) · ⭐ 422 · 🏷️ LLM

[ [Daily](/content/kimtth/awesome-azure-openai-llm/README.md) / [Weekly](/content/kimtth/awesome-azure-openai-llm/week/README.md) / Overview ]

---

# Azure OpenAI + LLM

![GitHub last commit](https://img.shields.io/github/last-commit/kimtth/awesome-azure-openai-llm?label=commit\&color=hotpink\&style=flat-square)
![Azure OpenAI](https://img.shields.io/badge/llm-azure_openai-blue?style=flat-square)
![GitHub Created At](https://img.shields.io/github/created-at/kimtth/awesome-azure-openai-llm?style=flat-square)

A comprehensive, curated collection of resources for Azure OpenAI, Large Language Models (LLMs), and their applications.

🔹Concise Summaries: Each resource is briefly described for quick understanding\
🔹Chronological Organization: Resources appended with date (first commit, publication, or paper release)\
🔹Monthly Updates: The list is updated monthly; candidate entries before the update are tracked in the issue.\
🔹A list for Azure and Microsoft products only, linted by the official Awesome rules: [Azure OpenAI & Copilot (⭐10)](https://github.com/kimtth/awesome-azure-openai-copilot).\
🔹Applications archived or inactive for over 12 months are listed in [`applications.old.md`](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/./section/applications.old.md). Archived Azure repositories are listed in [`azure.old.md`](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/./section/azure.old.md).

## 🧭 Quick Navigation (Propedia-style)

| Layer / Era                             | What it controls                                                                                             | Jump to sections                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Weights** <br/> 2022-2023             | Capabilities encoded in model parameters. <br/> `Themes: Pretraining, scaling, fine-tuning, alignment`       | [Model landscape](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-landscape) · [Model collection](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-collection) · [Training & optimization](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-training-and-optimization) · [Model training](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#models-training--inference)                                                                                    |
| **Context** <br/> 2023-2024             | Instructions and knowledge supplied at inference. <br/> `Themes: Prompting, RAG, memory, long context`       | [Prompting](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#prompt-engineering-and-visual-prompts) · [RAG](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#rag-retrieval-augmented-generation) · [IQ, Data & Memory (Azure)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#iq-data--memory) · [Memory](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#memory) · [Long-context limits](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#context-and-long-context-limits)   |
| **Agentic Engineering** <br/> 2025-2026 | How applications use models and tools to act. <br/> `Themes: Agents, MCP, skills, orchestration, evaluation` | [Agent frameworks](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#agents--context-engineering) · [Agent protocols](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#agent-protocol) · [Agentic engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#agentic-engineering) · [Agent best practices](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#agent-best-practices) · [Evaluation](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models) |

Refereces: [DailyDoseOfDS - *Evolution of the Agent Landscape*](https://blog.dailydoseofds.com/p/evolution-of-agent-landscape-from)

## 1. App & Agent

🚀 [RAG Systems, LLM Applications, Agents, Frameworks & Orchestration](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md)

*   **RAG**
    *   [RAG](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#rag-retrieval-augmented-generation)
    *   [GraphRAG](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#graphrag)
    *   [RAG Application](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#rag-application)
    *   [Vector Database & Embedding](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#vector-database--embedding)
*   **Application**
    *   [Top Agent Frameworks](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#top-agent-frameworks)
    *   [Additional Agent Framework](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#additional-agent-framework)
    *   [Cache](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#cache)
    *   [Data & Analytics Agents](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#data--analytics-agents)
    *   [Data Processing & OCR](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#data-processing--ocr)
    *   [Desktop AI Assistant](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#desktop-ai-assistant)
    *   [Memory](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#memory)
    *   [Model Gateway](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-gateway)
    *   [Model Serving & Local Runtimes](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-serving--local-runtimes)
    *   [Observability & LLMOps](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#observability--llmops)
    *   [**Popular LLM Applications** (GitHub Stars >= 1000)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/x_llm_apps.md)
    *   [SDKs, Integration & ML Libraries](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#sdks-integration--ml-libraries)
    *   [Training & Fine-tuning](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#training--fine-tuning)
    *   [UI & No-Code Tool](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#ui--no-code-tool)
*   **Agent Protocols**
    *   [A2A](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#a2a)
    *   [Computer & Browser use](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#computer--browser-use)
    *   [Model Context Protocol (MCP)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-context-protocol-mcp)
*   **Coding & Research**
    *   [Coding](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#coding)
    *   [Deep Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#deep-research)
    *   [Domain-Specific Agents](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#domain-specific-agents)
    *   [Skills](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#skills)
    *   [Agentic Engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#agentic-engineering): Harness Engineering → Loop Engineering → Graph Engineering

**[⬆ back to top](#azure-openai--llm-wiki)**

## 2. Azure OpenAI & Copilot

🌌 [Microsoft's Cloud-Based AI Platform and Services](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md)

*   **Microsoft Ecosystem**
    *   [Microsoft 365 Copilot](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#microsoft-365-copilot)
    *   [Power Platform & Copilot Studio](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#power-platform--copilot-studio)
    *   [Copilot Products](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#copilot-products)
*   **Platform**
    *   [AI Platform & Services](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#ai-platform--services)
    *   [Models, Training & Inference](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#models-training--inference)
    *   [IQ, Data & Memory](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#iq-data--memory)
    *   [Agents & Context Engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#agents--context-engineering)
*   **Operations & Design**
    *   [Developer Tools, MCP & .NET](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#developer-tools-mcp--net)
    *   [Safety, Security & LLMOps](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#safety-security--llmops)
    *   [Architecture & Reference Designs](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#architecture--reference-designs)
    *   [Solution Accelerators & Samples](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#solution-accelerators--samples)
    *   [Use Cases & Customer Stories](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#use-cases--customer-stories)
*   **Learning & Research**
    *   [Learning Resources & Workshops](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#learning-resources--workshops)
    *   [Microsoft Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#microsoft-research)

**[⬆ back to top](#azure-openai--llm-wiki)**

## 3. Research & Survey

🧠 [LLM Landscape, Prompt Engineering, Finetuning, Challenges & Surveys](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md)

*   **Landscape**
    *   [Large Language Model Landscape](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-landscape)
    *   [Large Language Model Collection](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-collection)
    *   [Foundation Model Providers](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#foundation-model-providers)
    *   [Domain-Specific and Specialized LLMs](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#domain-specific-and-specialized-llms)
*   **Prompting**
    *   [Prompt Engineering and Visual Prompts](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#prompt-engineering-and-visual-prompts)
*   **Training & Optimization**
    *   [Large Language Model Training and Optimization](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-training-and-optimization)
    *   [Pre-training and Data Preparation](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#pre-training-and-data-preparation)
    *   [Architecture and Inference Patterns](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#architecture-and-inference-patterns)
    *   [Post-training and Fine-Tuning](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#post-training-and-fine-tuning)
*   **Impact & Products**
    *   [AI Adoption, Impact, and Society](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#ai-adoption-impact-and-society)
    *   [OpenAI Products](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#openai-products)
    *   [Anthropic AI Products](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#anthropic-ai-products)
    *   [Google AI Products](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#google-ai-products)
*   **Survey & Reference**
    *   [Survey and Reference](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#survey-and-reference)
    *   [Additional Topics: A Survey of LLMs](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#additional-topics-a-survey-of-llms)
    *   [**LLM Research** (Ranked by cite count ≥150)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/x_llm_papers.md)
    *   [Learning Resources, Implementations, and Regional Materials](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#learning-resources-implementations-and-regional-materials)

**[⬆ back to top](#azure-openai--llm-wiki)**

## 4. Datasets, Evaluation, and Extras

🛠️ [Training Data, Datasets & Evaluation Methods](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md)

*   **Data**
    *   [Datasets for LLM Training](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#datasets-for-llm-training)
*   **Evaluation**
    *   [Evaluating Large Language Models](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models)
    *   [LLM Evaluation Benchmarks](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#llm-evaluation-benchmarks)
    *   [LLMOps: Large Language Model Operations](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#llmops-large-language-model-operations)
*   **Extras**
    *   [LLM for Robotics](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#llm-for-robotics)
    *   [Awesome Demo](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#awesome-demo)

**[⬆ back to top](#azure-openai--llm-wiki)**

## 5. Best Practices

📋 [Curated Blogs, Patterns, and Implementation Guidelines](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md)

*   **RAG**
    *   [The Problem with RAG](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#the-problem-with-rag)
    *   [RAG Solution Design](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#rag-solution-design)
    *   [RAG Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#rag-research)
    *   [**RAG Research** (Ranked by cite count >=100)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#rag-research-ranked-by-cite-count-100)
*   **Agent**
    *   [Agent Design Patterns](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#agent-design-patterns)
    *   [Agent Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#agent-research)
    *   [**Agent Research** (Ranked by cite count >=100)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#agent-research-ranked-by-cite-count-100)
    *   [Tool Use: LLM to Master APIs](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#tool-use)
*   **Security**
    *   [Security and Governance](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#security-and-governance)
*   **Reference**
    *   [Proposals & Glossary](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#proposals--glossary)

**[⬆ back to top](#azure-openai--llm-wiki)**

## 🧭 Start Here: Choose a Goal

Pick the outcome closest to your task and follow the links in order. Each path is a short starting point, not a required sequence.

| Goal                                     | Suggested path                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Build a RAG application**              | [RAG](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#rag-retrieval-augmented-generation) → [Azure IQ, Data & Memory (AI Search)](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#iq-data--memory) → [RAG Solution Design](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#rag-solution-design) → [RAG Application](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#rag-application)                                         |
| **Design an AI agent**                   | [Top Agent Frameworks](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#top-agent-frameworks) → [Agent Design Patterns](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#agent-design-patterns) → [Agents & Context Engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#agents--context-engineering) → [Memory](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#memory)                                               |
| **Connect tools with MCP**               | [Model Context Protocol](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-context-protocol-mcp) → [Developer Tools, MCP & .NET](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#developer-tools-mcp--net) → [Tool Use](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/best_practices.md#tool-use)                                                                                                                                                                                     |
| **Build a Microsoft 365 agent**          | [Microsoft 365 Copilot](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#microsoft-365-copilot) → [Agents & Context Engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#agents--context-engineering)                                                                                                                                                                                                                                                                                                                    |
| **Build a coding or research agent**     | [Coding](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#coding) → [Skills](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#skills) → [Agentic Engineering](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#agentic-engineering) → [Deep Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#deep-research)                                                                                                       |
| **Run a local model application**        | [Model Collection](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-collection) → [Model Serving & Local Runtimes](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-serving--local-runtimes) → [Model Gateway](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#model-gateway) → [Observability & LLMOps](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#observability--llmops)             |
| **Train or evaluate a model**            | [Datasets for LLM Training](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#datasets-for-llm-training) → [Training & Fine-tuning](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/applications.md#training--fine-tuning) → [Evaluating Large Language Models](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models) → [Evaluation Metrics](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#evaluation-metrics) |
| **Operate an application in production** | [Architecture & Reference Designs](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#architecture--reference-designs) → [Safety, Security & LLMOps](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/azure.md#safety-security--llmops) → [LLMOps](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#llmops-large-language-model-operations) → [Evaluation](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/tools_extra.md#evaluating-large-language-models)          |
| **Explore LLM research**                 | [Model Landscape](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#large-language-model-landscape) → [Survey and Reference](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#survey-and-reference) → [LLM Research](https://github.com/kimtth/azure-openai-llm-notes/blob/main/README.md/section/models_research.md#llm-research-ranked-by-cite-count-150)                                                                                                                                                    |

## 📖 Legend & Notation

| Symbol                                                                                                                                  | Meaning           | Symbol | Meaning        |
| --------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------ | -------------- |
| ![github](https://img.shields.io/github/stars/kimtth/awesome-azure-openai-llm?style=flat\&label=%20\&color=f0f1f2\&cacheSeconds=360000) | GitHub repository | 🗄️    | Archived files |
| 💡🏆                                                                                                                                    | Recommend         | 📺     | Video content  |
| 📑                                                                                                                                      | Academic paper    | 🤗     | Huggingface    |

<!-- 
All rights reserved © `kimtth` 
-->

<!-- 
https://shields.io/badges/git-hub-created-at
-->

**[`^        back to top        ^`](#azure-openai--llm-wiki)**

