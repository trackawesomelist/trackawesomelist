# Awesome Firebase Genkit Overview

🔥 List of Genkit talks, plugins, tools, examples & articles! Contributions welcome!

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/xavidop/awesome-firebase-genkit/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 xavidop/awesome-firebase-genkit](https://github.com/xavidop/awesome-genkit) · ⭐ 52 · 🏷️ LLM

[ [Daily](/content/xavidop/awesome-firebase-genkit/README.md) / [Weekly](/content/xavidop/awesome-firebase-genkit/week/README.md) / Overview ]

---

<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Genkit <!-- omit from toc -->

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/xavidop/awesome-genkit/actions/workflows/lint.yaml/badge.svg)](https://github.com/xavidop/awesome-genkit/actions/workflows/lint.yaml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/xavidop/awesome-genkit/)

<!-- subtitle -->

A collection of awesome things regarding the Genkit ecosystem.

<p align="center">
  <a href="CODE_OF_CONDUCT.md">Code Of Conduct</a>
  <a href="CONTRIBUTING.md">Contribution guide</a>
  <a href="https://github.com/xavidop/awesome-genkit/graphs/contributors">Contributors</a>
</p>

<!-- image -->

<picture>
  <source media="(prefers-color-scheme: light)" srcset="/assets/genkit-logo.png">
  <source media="(prefers-color-scheme: dark)" srcset="/assets/genkit-logo-dark.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://github.com/xavidop/awesome-genkit/raw/main/assets/genkit-logo.png">
</picture>

<!-- description -->

Genkit is a framework designed to help you build AI-powered applications and features. It provides open source libraries for Node.js and Go, plus developer tools for testing and debugging.

</div>

<!-- TOC -->

## Contents <!-- omit from toc -->

*   [Plugins](#plugins)
    *   [JavaScript - Official](#javascript---official)
    *   [JavaScript - Community](#javascript---community)
    *   [Python - Official](#python---official)
    *   [Golang - Official](#golang---official)
    *   [Golang - Community](#golang---community)
*   [API References](#api-references)
*   [Solutions](#solutions)
*   [Talks](#talks)
*   [Videos](#videos)
*   [Articles](#articles)
*   [Tutorials](#tutorials)
*   [Follow](#follow)
*   [Contributors](#contributors)

<!-- CONTENT -->

## Plugins

### JavaScript - Official

1.  Model / Embedding Plugins
    *   [`@genkit-ai/vertexai`](https://firebase.google.com/docs/genkit/plugins/vertex-ai) - The Vertex AI plugin provides interfaces to several AI services: Google generative AI models, A subset of evaluation metrics through the Vertex AI Rapid Evaluation API, Vector Search.
    *   [`@genkit-ai/googleai`](https://firebase.google.com/docs/genkit/plugins/google-genai) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API.
    *   [`genkitx-ollama`](https://firebase.google.com/docs/genkit/plugins/ollama) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
2.  Vector Store Plugins
    *   [`genkitx-pinecone`](https://firebase.google.com/docs/genkit/plugins/pinecone) - Plugin for Pinecone Vector Stores.
    *   [`genkitx-chromadb`](https://firebase.google.com/docs/genkit/plugins/chroma) - Plugin for Chroma Vector Stores.
    *   [`@genkit-ai/dev-local-vectorstore`](https://firebase.google.com/docs/genkit/rag) - Plugin for Local Vector Store for development purposes.
3.  Monitoring Plugins
    *   [`@genkit-ai/google-cloud`](https://www.npmjs.com/package/@genkit-ai/google-cloud) - The Google Cloud plugin exports Genkit's telemetry and logging data to Google Cloud's operation suite.
4.  Other Plugins
    *   [`@genkit-ai/firebase`](https://firebase.google.com/docs/genkit/plugins/firebase) - Firebase plugin provides several integrations with Firebase services: Indexers and retrievers using Cloud Firestore vector store, Trace storage using Cloud Firestore, Flow deployment using Cloud Functions, Authorization policies for Firebase Authentication users.
    *   [`@genkit-ai/express`](https://www.npmjs.com/package/@genkit-ai/express) - Express plugin provides an Express middleware for Genkit.

### JavaScript - Community

1.  Model / Embedding Plugins
    *   [`genkitx-github`](https://github.com/xavidop/genkitx-github) - Plugin for GitHub Models APIs.
    *   [`genkitx-anthropic`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/anthropic) - Plugin for Anthropic AI APIs.
    *   [`genkitx-cohere`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/cohere) - Plugin for Cohere APIs.
    *   [`genkitx-groq`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/groq) - Plugin for Groq APIs.
    *   [`genkitx-mistral`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/mistral) - Plugin for Mistral AI APIs.
    *   [`genkitx-openai`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/openai) - Plugin for OpenAI APIs.
    *   [`genkitx-azure-openai`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/azure-openai) - Plugin for Azure OpenAI APIs.
    *   [`genkitx-aws-bedrock`](https://github.com/xavidop/genkitx-aws-bedrock) - Plugin for AWS Bedrock APIs.
    *   [`genkitx-deepseek`](https://github.com/oddbit/genkitx-deepseek) - Plugin for Deepseek Cloud APIs.
    *   [`genkitx-huggingface`](https://github.com/xavidop/genkitx-huggingface) - Plugin for Hugging Face Inference APIs.
2.  Vector Store Plugins
    *   [`genkitx-convex`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/convex) - Plugin for Convex Vector Stores.
    *   [`genkitx-hnsw`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/hnsw) - Plugin for HNSW Vector Stores.
    *   [`genkitx-qdrant`](https://github.com/qdrant/qdrant-genkit) - Plugin for Qdrant Vector Stores.
    *   [`genkitx-astra-db`](https://www.npmjs.com/package/genkitx-astra-db) - Plugin for AstraDB Vector Stores.
    *   [`genkitx-pgvector`](https://www.npmjs.com/package/genkitx-pgvector) - Plugin for PostgeSQL (PGVector) Vector Stores.
    *   [`genkitx-tidb`](https://github.com/BelfoSamad/genkitx-tidb) - Plugin for TiDB Vector Stores.
    *   [`genkitx-redis`](https://github.com/retzd-tech/genkitx-redis) - Plugin for Redis Vector Stores.
    *   [`genkitx-voiceflow`](https://github.com/xavidop/genkitx-voiceflow) - Plugin for Voiceflow KB.
3.  Evaluator Plugins
    *   [`genkitx-promptfoo`](https://github.com/yukinagae/genkitx-promptfoo) - Plugin for Promptfoo Evaluations.
4.  Other Plugins
    *   [`genkitx-graph`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/graph) - Plugin for building Graph workflows.
    *   [`@invertase/genkit-plugin-redis`](https://github.com/invertase/genkit-plugin-redis) - A Redis Plugin for Genkit that adds Redis for efficient state storage, trace storage, caching, and rate limiting.
    *   [`genkitx-rxjs`](https://github.com/pavelgj/genkitx-rxjs) - A simple RxJS helper/adapter for Genkit.
    *   [`@agentic/genkit`](https://agentic.so/sdks/genkit) - Agentic Tools adapter for the Genkit SDK.

### Python - Official

1.  Model / Embedding Plugins
    *   [`google-genai`](https://python.api.genkit.dev/reference/plugins/google-genai/) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API & Vertex AI models.
    *   [`ollama`](https://python.api.genkit.dev/reference/plugins/ollama/) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
2.  Vector Store Plugins
    *   [`firestore`](https://python.api.genkit.dev/reference/plugins/firestore/) - The Firestore plugin provides interfaces to the Firestore vector store.
    *   [`dev_local_vectorstore`](https://python.api.genkit.dev/reference/plugins/dev-local-vectorstore/) - Plugin for Local Vector Store for development purposes.
3.  Other Plugins:
    *   [`flask`](https://python.api.genkit.dev/flask/) - Flask plugin for building web applications with Genkit.

### Golang - Official

1.  Model / Embedding Plugins
    *   [`googlegenai`](https://firebase.google.com/docs/genkit-go/plugins/google-genai) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API & Vertex AI Models.
    *   [`ollama`](https://firebase.google.com/docs/genkit-go/plugins/ollama) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
2.  Vector Store Plugins
    *   [`pinecone`](https://firebase.google.com/docs/genkit-go/plugins/pinecone) - Plugin for Pinecone Vector Stores.
    *   [`localvec`](https://firebase.google.com/docs/genkit-go/rag) - Plugin for Local Vector Store for development purposes.
    *   [`pgvector`](https://firebase.google.com/docs/genkit-go/pgvector) - Plugin for PostgreSQL (PGVector) Vector Stores.
3.  Monitoring Plugins
    *   [`googlecloud`](https://firebase.google.com/docs/genkit-go/plugins/google-cloud) - The Google Cloud plugin exports Genkit's telemetry and logging data to Google Cloud's operation suite.

### Golang - Community

1.  Model / Embedding Plugins
    *   [`openai`](https://pkg.go.dev/github.com/yukinagae/genkit-go-plugins/plugins/openai) - Plugin for OpenAI APIs.

## API References

1.  [JavaScript](https://js.api.genkit.dev/) - Specs for the JavaScript API.
2.  [Python](https://python.api.genkit.dev/) - Specs for the Python API.
3.  [Golang](https://pkg.go.dev/github.com/firebase/genkit/go) - Specs for the Golang API.

## Solutions

*   [`internal AI`](https://github.com/tanabee/internal-ai) - An open-source Genkit-based internal AI chat application.

## Talks

*   [Supercharge your app with Genkit](https://www.youtube.com/watch?v=eVud8llb_W0) - A talk on how to supercharge your app with Genkit.
*   [Accelerating Generative AI App Development with Flutter & Genkit](https://speakerdeck.com/coborinai/accelerating-generative-ai-app-development-with-flutter-and-firebase-genkit) - Slides from a presentation at FlutterGakkai, a Flutter conference in Japan, showcasing how to integrate Genkit with Flutter for rapid generative AI app development.

## Videos

*   [Getting started with Genkit/JS 1.0](https://www.youtube.com/watch?v=3p1P5grjXIQ) - Learn how to get started with Genkit/JS 1.0.
*   [Getting started with Genkit (outdated)](https://www.youtube.com/watch?v=M8rfDySBBvM) - A video tutorial on how to get started with Genkit.
*   [What are Genkit flows? (outdated)](https://youtu.be/ONR38NZK5FE) - Flows are a key concept in Genkit. Learn what makes them special, and how to use them.
*   [Build an Angular app with Genkit and deploy to Firebase (outdated)](https://youtu.be/TGHua_RtUjs) - Join Pavel as he builds an Angular app and deploys it to Firebase.
*   [DeepDive #1 - Genkit's reflection API and how it powers Genkit's developer UI (outdated)](https://youtu.be/CGVBR8quZac) - Learn how the Genkit developer UI communicates with Genkit through the reflection API.
*   [Retrieval Augmented Generation (RAG) with Genkit (outdated)](https://youtu.be/p8ZlYAmbWHE) - Learn how to efficiently parse PDFs, convert their content into searchable vectors using Genkit's local vector store, and implement a re-ranker to pinpoint the most relevant documents for your queries.
*   [Firebase After Hours #3 - Genkit: More than Meets the AI! (outdated)](https://youtu.be/VFPsp7aURWA?t=152s) - Hang out with Nohe and Peter to learn more about Genkit, Google's open source AI integration framework. With special guest Pavel Jbanov, lead engineer on the Genkit team.
*   [Firebase After Hours #4 - Genkit: Tooltime (outdated)](https://youtu.be/01XOIhh2ibA) - Learn how to give LLMs superpowers by conneting the to the real world using tool calling.

## Articles

*   [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://firebase.blog/posts/2025/02/gemini-genkit-pdf-structured-data) - Learn how to extract structured data from PDFs using Gemini 2.0 and Genkit 1.0.
*   [Genkit in Node, Building a Weather Service with AI Integration](https://xavidop.me/firebase/gcp/2025-02-28-firebase-genkit-node-tool/) - Explore how to build a weather service using Genkit in Node.js using Express, GitHub Models and Tools.
*   [Build Genkit Node.js apps with Dash Agents](https://medium.com/firebase-developers/build-firebase-genkit-nodejs-apps-with-dash-agents-skip-the-docs-258e067b3fdc) - A step-by-step guide to building Genkit Node.js apps by leveraging Dash Agents.
*   [Genkit with Gemma using Ollama](https://xavidop.me/firebase/gcp/2024-05-24-firebase-genkit-ollama/) - Firebase project that uses the Gen AI Kit with Gemma using Ollama.
*   [Master Gemma2 and Genkit](https://medium.com/firebase-developers/how-to-develop-using-the-gemma2-model-in-genkit-085f22ce68f3) - Learn how to integrate Gemma2 with Genkit.
*   [Unleash the Power of Function Calling with Genkit](https://medium.com/firebase-developers/implementing-function-calling-using-genkit-0c03f6cb9179) - Learn how to implement function calling using Genkit.
*   [Unlocking the power of code execution in Genkit](https://medium.com/firebase-developers/getting-started-with-code-execution-in-genkit-c5391b45b321) - Learn how to integrate Python code within Genkit.
*   [Understanding Genkit flows with Czech language tricks](https://dev.to/denisvalasek/understanding-genkit-flows-with-czech-language-tricks-26i3) - Learn how to work with Genkit flows and use the features of Genkit UI.
*   [Orchestrating Firebase and AI: 8 Genkit Architecture Patterns](https://medium.com/@nozomi-koborinai/orchestrating-firebase-and-ai-8-genkit-architecture-patterns-12e44db40345) - A guide to 8 architecture patterns for integrating Firebase and AI using Genkit.
*   [High-Precision Responses with Genkits Google Search Integration](https://medium.com/firebase-developers/high-precision-responses-with-genkits-google-search-integration-7f142f5c9693) - Learn how to integrate Google Search with Genkit.
*   [How to Develop Firebase functions with Genkit](https://medium.com/@nozomi-koborinai/how-to-develop-firebase-genkit-functions-2677b386a227) - A practical guide to efficient local testing of Firebase Functions with Genkit Firebase product integrations.
*   [Genkit for Go Developers: A Guide to Building LLM Applications](https://medium.com/@yukinagae/firebase-genkit-for-go-developers-a-guide-to-building-llm-applications-f96c51c34b10) - A getting started guide for Go developers using Genkit.
*   [Orchestrating Firebase and AI: Genkit architecture example](https://docs.google.com/presentation/d/10F2hjzJhdInSuhDQ8G_B2raGz79mzTRIcWU_59Zh5Y8/edit?usp=sharing) - Presented in a lightning talk at GDG DevFest Tokyo 2024.
*   [Getting Started with AI Image Generation Apps on Flutter, Genkit, and Imagen 3](https://medium.com/@nozomi-koborinai/getting-started-with-ai-image-generation-apps-on-flutter-genkit-and-imagen-3-9a83c63cbdf3) - A guide to building an AI image generation app using Flutter, Genkit, and Google's Imagen 3.
*   [Extending Your AI Application with Genkit MCP](https://medium.com/@nozomi-koborinai/extending-your-ai-application-with-genkit-mcp-475d7533ca9e) - Learn how to integrate Google Maps using Genkit MCP client to query MCP servers for enhanced location-based AI features.
*   [Genkit vs Agent Development Kit (ADK): Choosing the Right Google‑Backed AI Framework](https://medium.com/@nozomi-koborinai/genkit-vs-agent-development-kit-adk-choosing-the-right-google-backed-ai-framework-1744b73234ac) - A comparison of two Google-backed AI frameworks, helping developers choose the right tool for their needs.

## Tutorials

*   [Slack Bot App](https://medium.com/firebase-developers/build-a-slack-bot-app-with-firebase-genkit-in-just-100-lines-71d4e49c9e08) - A tutorial on how to build a Slack Bot App with Genkit.

<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

*   [Firebase](https://x.com/firebase) - Official Twitter account for Firebase.
*   [Genkit Discord server](https://discord.gg/qXt5zzQKpc) - Official Discord server for Genkit.
*   [Genkit GitHub (⭐1.4k)](https://github.com/firebase/genkit) - Official GitHub repository for Genkit.
*   [The Fire Company](https://github.com/TheFireCo) - The Fire Company GitHub organization.

## Contributors

[Thanks goes to these contributors (⭐52)](https://github.com/xavidop/awesome-genkit/graphs/contributors)!

