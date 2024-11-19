# Awesome Azure Openai Llm Overview

a curated list of 🔎Azure OpenAI, 🦙Large Language Models, and 🌌 references with 🎋notes.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/kimtth/awesome-azure-openai-llm/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 kimtth/awesome-azure-openai-llm](https://github.com/kimtth/awesome-azure-openai-llm) · ⭐ 326 · 🏷️ LLM

[ [Daily](/content/kimtth/awesome-azure-openai-llm/README.md) / [Weekly](/content/kimtth/awesome-azure-openai-llm/week/README.md) / Overview ]

---

# Azure OpenAI + LLMs (Large Language Models)

![Static Badge](https://img.shields.io/badge/llm-azure_openai-blue?style=flat-square) <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a> ![GitHub Created At](https://img.shields.io/github/created-at/kimtth/awesome-azure-openai-llm?style=flat-square)

This repository contains references to Azure OpenAI, Large Language Models (LLM), and related services and libraries. It follows a similar approach to the ‘Awesome-list’.

🔹Brief each item on a few lines as possible. <br/>
🔹The dates are determined by the date of the commit history, the Article published date, or the Paper issued date (v1). <br/>
🔹Capturing a chronicle and key terms of that rapidly advancing field. <br/>
🔹Disclaimer: Please be aware that some content may be outdated.

## What's the difference between Azure OpenAI and OpenAI?

1.  OpenAI offers the latest features and models, while Azure OpenAI provides a reliable, secure, and compliant environment with seamless integration into other Azure services.
2.  Azure OpenAI supports `private networking`, `role-based authentication`, and `responsible AI content filtering`.
3.  Azure OpenAI does not use user input as training data for other customers. [Data, privacy, and security for Azure OpenAI](https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy). Azure OpenAI does not share user data, including prompts and responses, with OpenAI.

*   [What is Azure OpenAI Service?](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview)
*   [Open AI Models](https://platform.openai.com/docs/models)
*   [Abuse Monitoring](https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy): To detect and mitigate abuse, Azure OpenAI stores all prompts and generated content securely for up to thirty (30) days. (No prompts or completions are stored if the customer chooses to turn off abuse monitoring.)

## Table of contents

*   **Section 1** : [RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#section-1-rag-llamaindex-and-vector-storage)
    *   [RAG (Retrieval-Augmented Generation)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#what-is-the-rag-retrieval-augmented-generation)
    *   [Vector DB](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#vector-database-comparison)
    *   [RAG Design & Application](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#rag-solution-design--application)
    *   [LlamaIndex](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#llamaindex)
*   **Section 2** : [Azure OpenAI](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#section-2--azure-openai-and-reference-architecture)
    *   [Microsoft LLM & Copilot](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#microsoft-azure-openai-relevant-llm-framework)
    *   [Azure Architectures & AI Search](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#azure-reference-architectures)
    *   [Azure Services](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#azure-enterprise-services)
*   **Section 3** : [Semantic Kernel & DSPy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#section-3--microsoft-semantic-kernel-and-stanford-nlp-dspy)
    *   [Semantic Kernel](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#semantic-kernel): Micro-orchestration
    *   [DSPy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#dspy): Optimizer frameworks
*   **Section 4** : [LangChain](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#section-4--langchain-features-usage-and-comparisons)
    *   [LangChain Features](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-feature-matrix--cheetsheet): Macro & Micro-orchestration
    *   [LangChain Agent & Criticism](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-chain-type-chains--summarizer)
    *   [LangChain vs Competitors](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-vs-competitors)
*   **Section 5** : [Prompting & Finetuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#section-5-prompt-engineering-finetuning-and-visual-prompts)
    *   [Prompt Engineering](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#prompt-engineering)
    *   [Finetuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#finetuning): PEFT (e.g., LoRA), RLHF, SFT
    *   [Quantization & Optimization](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#quantization-techniques)
    *   [Other Techniques](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#other-techniques-and-llm-patterns): e.g., MoE
    *   [Visual Prompting](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#visual-prompting--visual-grounding)
*   **Section 6** : [Challenges & Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#section-6--large-language-model-challenges-and-solutions)
    *   [AGI Discussion](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#agi-discussion)
    *   [OpenAI Products & Roadmap](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#openais-roadmap-and-products)
    *   [LLM Constraints](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#context-constraints): e.g., RoPE
    *   [Trust & Safety](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#trustworthy-safe-and-secure-llm)
    *   [LLM Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#large-language-model-is-abilities)
*   **Section 7** : [LLM Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#section-7--large-language-model-landscape)
    *   [LLM Taxonomy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#large-language-models-in-2023)
    *   [Open-Source LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#open-source-large-language-models)
    *   [Domain-Specific LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#llm-for-domain-specific): e.g., Software development
    *   [Multimodal LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#mllm-multimodal-large-language-model)
    *   [Generative AI Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#generative-ai-landscape)
*   **Section 8** : [Surveys & References](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#section-8-survey-and-reference)
    *   [LLM Surveys](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#survey-on-large-language-models)
    *   [Building LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#build-an-llms-from-scratch-picogpt-and-lit-gpt)
    *   [LLMs for Korean & Japanese](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#llm-materials-for-east-asian-languages)
*   **Section 9** : [Agents & Applications](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#section-9-applications-and-frameworks)
    *   [Applications & Frameworks](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#applications-frameworks-and-user-interface-uiux)
    *   [AutoGPT & Agents](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#agents-autogpt-and-communicative-agents): Frameworks & Agent Design Patterns
    *   [Caching & UX](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#caching)
    *   [LLMs for Robotics](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#llm-for-robotics-bridging-ai-and-robotics) / [Awesome demo](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent_app.md/#awesome-demo)
*   **Section 10** : [AI Tools & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/ai_tool.md/#section-10-general-ai-tools-and-extensions)
    *   [AI Tools & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/ai_tool.md/#section-10-general-ai-tools-and-extensions)
*   **Section 11** : [Datasets](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/dataset.md/#section-11-datasets-for-llm-training)
    *   [LLM Training Datasets](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/dataset.md/#section-11-datasets-for-llm-training)
*   **Section 12** : [Evaluations](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/eval.md/#section-12-evaluating-large-language-models--llmops)
    *   [LLM Evaluation & LLMOps](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/eval.md/#section-12-evaluating-large-language-models--llmops)
*   **Contributors** :
    *   [Contributors](#contributors): 👀
*   **Symbols**
    *   `ref`: external URL
    *   `doc`: archived doc
    *   `cite`: the source of comments
    *   `cnt`: number of citations
    *   `git`: GitHub link
    *   `x-ref`: Cross reference
    *   📺: youtube or video

## **Contributors**

<a href="https://github.com/kimtth/awesome-azure-openai-llm/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kimtth/awesome-azure-openai-llm" />
</a>

ⓒ `https://github.com/kimtth` all rights reserved.

