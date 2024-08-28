# Awesome List Updates on Nov 27, 2023

6 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Free for Dev](/content/ripienaar/free-for-dev/README.md)

### CDN and Protection

*   [CacheFly](https://portal.cachefly.com/signup/free2023) - Up to 5 TB per month of Free CDN traffic, 19 Core PoPs , 1 Domain and Universal SSL.

## [2. Awesome Db Tools](/content/mgramin/awesome-db-tools/README.md)

### Schema / Diagrams

*   [QuickDBD](https://www.quickdatabasediagrams.com/) - Simple online tool to quickly draw database diagrams.

### Data / Compare

*   [KS DB Merge Tools](https://ksdbmerge.tools) - GUI to compare and sync DB schema and data. For Oracle Database, MySQL, MariaDB, SQL Server, PostgreSQL, SQLite, MS Access and Cross-DBMS.

## [3. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **RAG Pipeline & Advanced RAG**

*   [cite](https://twitter.com/yi_ding/status/1721728060876300461) \[7 Nov 2023] `OpenAI has put together a pretty good roadmap for building a production RAG system.` Naive RAG -> Tune Chunks -> Rerank & Classify -> Prompt Engineering. In `llama_index`... [Youtube](https://www.youtube.com/watch?v=ahnGLM-RC1Y)  <br/> <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/oai-rag-success-story.jpg" width="500">

### **Azure Enterprise Services** / **Azure AI Search**

*   Copilot (FKA. Bing Chat Enterprise) \[18 Jul 2023] [Privacy and Protection](https://learn.microsoft.com/en-us/bing-chat-enterprise/privacy-and-protections#protected-by-default)
    1.  Doesn't have plugin support
    2.  Only content provided in the chat by users is accessible to Bing Chat Enterprise.

### **Prompt Engineering** / **Prompt Template Language**

*   Adversarial Prompting
    *   Prompt Injection: `Ignore the above directions and ...`
    *   Prompt Leaking: `Ignore the above instructions ... followed by a copy of the full prompt with exemplars:`
    *   Jailbreaking: Bypassing a safety policy, instruct Unethical instructions if the request is contextualized in a clever way. [ref](https://www.promptingguide.ai/risks/adversarial)

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   [Practical Tips for Finetuning LLMs Using LoRA (Low-Rank Adaptation)](https://magazine.sebastianraschka.com/p/practical-tips-for-finetuning-llms) \[19 Nov 2023]: Best practical guide of LoRA.
    1.  QLoRA saves 33% memory but increases runtime by 39%, useful if GPU memory is a constraint.
    2.  Optimizer choice for LLM finetuning isn’t crucial. Adam optimizer’s memory-intensity doesn’t significantly impact LLM’s peak memory.
    3.  Apply LoRA across all layers for maximum performance.
    4.  Adjusting the LoRA rank is essential.
    5.  Multi-epoch training on static datasets may lead to overfitting and deteriorate results.

## [4. Awesome Ai4lam](/content/AI4LAM/awesome-ai4lam/README.md)

### Conferences and Workshops / Upcoming Conferences and Workshops

*   [IIPC General Assembly & Web Archiving Conference](https://netpreserve.org/ga2024/) – Apr. 24–26 at the Bibliothèque nationale de France, Paris, France.
*   [Fantastic Futures 2024](https://www.nfsa.gov.au/fantastic-futures-canberra-2024-artificial-intelligence-libraries-archives-and-museums) – Oct. 16–18 at the National Film and Sound Archive of Australia (NFSA), Canberra, Australia.

### Conferences and Workshops / Past Conferences and Workshops

*   [ai4Libraries Conference](https://www.ai4libraries.org) – Oct. 19 virtual event hosted by Georgia Tech Library, Atlanta, Georgia, USA.
*   [Fantastic Futures 2018](https://www.nb.no/hva-skjer/ai-conference/) – Dec. 5 at the National Library of Norway, Oslo, Norway.
*   [Fantastic Futures 2019](https://wayback.stanford.edu/was/20230508165810/http://library.stanford.edu/projects/fantastic-futures) – Dec. 4–6 at Stanford University, Stanford, California, USA.
*   [Fantastic Futures 2021](https://www.bnf.fr/fr/captations-et-supports-de-la-conference-2021) – Dec. 8–10 at the Bibliothèque nationale de France, Paris, France.
*   [Fantastic Futures 2022](https://sites.google.com/view/ai4lam/ai4lam-2022-virtual-event) – Nov. 30–Dec. 2 virtual event hosted by the British Library, London, England.
*   [Fantastic Futures 2023](https://ff2023.archive.org) – Nov. 15–17 at Internet Archive Canada Headquarters, Vancouver, British Columbia, Canada.

## [5. Awesome Kotlin](/content/KotlinBy/awesome-kotlin/README.md)

### Libraries/Frameworks / Misc

*   [jillesvangurp/querylight (⭐5)](https://github.com/jillesvangurp/querylight) - In memory search engine for simple in app search. Implements tf/idf and a some basic queries, tokenizers and analyzers.
*   [jillesvangurp/geogeometry (⭐125)](https://github.com/jillesvangurp/geogeometry) - GeoGeometry is a set of algorithms and functions for manipulating geo hashes and geometric shapes with geo coordinates

### Libraries/Frameworks / API Clients

*   [jillesvangurp/kt-search (⭐105)](https://github.com/jillesvangurp/kt-search) - Kotlin multiplatform library for Elasticsearch and Opensearch
*   [formation-res/overpass-kotlin-client (⭐1)](https://github.com/formation-res/overpass-kotlin-client) - A simple client for overpass that uses ktor-client and kotlinx.serialization for parsing JSON responses.

### Libraries/Frameworks / Internationalisation and Localization

*   [formation-res/fluent-kotlin (⭐10)](https://github.com/formation-res/fluent-kotlin) - Kotlin multi platdform localization for js and jvm based on project fluent.

### Projects / Web

*   [jillesvangurp/rankquest-studio (⭐7)](https://github.com/jillesvangurp/rankquest-studio) - Rankquest Studio is a web based tool that you can use to benchmark search query metrics for your search APIs. Written in Kotlin & Fritz2

### Projects / Examples

*   [formation-res/kt-fullstack-demo (⭐3)](https://github.com/formation-res/kt-fullstack-demo) - This demo kotlin-js project implements a UI and server for a little recipe search engine to demonstrate fritz2, kotlin-js, localization with mozilla fluent, use of koin in a webapp.

## [6. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/README.md)

### Software / Communication - Email - Mail Delivery Agents

*   [Piler](https://www.mailpiler.org/) - Feature-rich email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`

### Software / File Transfer - Web-based File Managers

*   [mikochi (⭐198)](https://github.com/zer0tonin/Mikochi) - Browse remote folders, upload files, delete, rename, download and stream files to VLC/mpv. `MIT` `Go/Docker/K8S`

### Software / Knowledge Management Tools

*   [Digimindmap](https://ladigitale.dev/digimindmap/#/) - Create simple mindmaps (documentation in French). ([Demo](https://ladigitale.dev/digimindmap/#/), [Source Code](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`

---

- Prev: [Nov 28, 2023](/content/2023/11/28/README.md)
- Next: [Nov 26, 2023](/content/2023/11/26/README.md)