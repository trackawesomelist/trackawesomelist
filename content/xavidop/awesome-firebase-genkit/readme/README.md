# Awesome Firebase Genkit Overview

🔥 List of Firebase Genkit talks, plugins, tools, examples & articles! Contributions welcome!

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/xavidop/awesome-firebase-genkit/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 xavidop/awesome-firebase-genkit](https://github.com/xavidop/awesome-firebase-genkit) · ⭐ 4 · 🏷️ LLM

[ [Daily](/content/xavidop/awesome-firebase-genkit/README.md) / [Weekly](/content/xavidop/awesome-firebase-genkit/week/README.md) / Overview ]

---

<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Firebase Genkit <!-- omit from toc -->

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/xavidop/awesome-firebase-genkit/actions/workflows/lint.yaml/badge.svg)](https://github.com/xavidop/awesome-firebase-genkit/actions/workflows/lint.yaml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/xavidop/awesome-firebase-genkit/) <a href="https://app.commanddash.io/agent/github_firebase_genkit"><img src="https://img.shields.io/badge/AI-Genkit%20Assist-EB9FDA"></a>

<!-- [![lint](https://github.com/xavidop/awesome-firebase-genkit/actions/workflows/lint.yaml/badge.svg)](https://github.com/xavidop/awesome-firebase-genkit/actions/workflows/lint.yaml) -->

<!-- subtitle -->

A collection of awesome things regarding the Firebase Genkit ecosystem.

<p align="center">
  <a href="CODE_OF_CONDUCT.md">Code Of Conduct</a>
  <a href="CONTRIBUTING.md">Contribution guide</a>
  <a href="https://github.com/xavidop/awesome-firebase-genkit/graphs/contributors">Contributors</a>
</p>

<!-- image -->

<picture>
  <source media="(prefers-color-scheme: light)" srcset="/assets/Product_Lockup_Genkit_Horizontal_Full_Color.png">
  <source media="(prefers-color-scheme: dark)" srcset="/assets/Product_Lockup_Genkit_Horizontal_Monochrome.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://github.com/xavidop/awesome-firebase-genkit/raw/main/assets/Product_Lockup_Genkit_Horizontal_Full_Color.png">
</picture>

<!-- description -->

Genkit is a framework designed to help you build AI-powered applications and features. It provides open source libraries for Node.js and Go, plus developer tools for testing and debugging.

</div>

<!-- TOC -->

## Contents <!-- omit from toc -->

*   [Plugins](#plugins)
    *   [JavaScript - Official](#javascript---official)
    *   [JavaScript - Community](#javascript---community)
    *   [Golang - Official](#golang---official)
    *   [Golang - Community](#golang---community)
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
    *   [`@genkit-ai/google-cloud`](https://www.npmjs.com/package/@genkit-ai/google-cloud) - The Google Cloud plugin exports Firebase Genkit's telemetry and logging data to Google Cloud's operation suite.
4.  Other Plugins
    *   [`@genkit-ai/firebase`](https://firebase.google.com/docs/genkit/plugins/firebase) - Firebase plugin provides several integrations with Firebase services: Indexers and retrievers using Cloud Firestore vector store, Trace storage using Cloud Firestore, Flow deployment using Cloud Functions, Authorization policies for Firebase Authentication users.
    *   [`genkitx-langchain`](https://firebase.google.com/docs/genkit/plugins/langchain) - Genkit plugin to work with LangChain.

### JavaScript - Community

1.  Model / Embedding Plugins
    *   [`genkitx-github`](https://github.com/xavidop/genkitx-github) - Plugin for GitHub Models APIs.
    *   [`genkitx-anthropic`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/anthropic) - Plugin for Anthropic AI APIs.
    *   [`genkitx-cohere`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/cohere) - Plugin for Cohere APIs.
    *   [`genkitx-groq`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/groq) - Plugin for Groq APIs.
    *   [`genkitx-mistral`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/mistral) - Plugin for Mistral AI APIs.
    *   [`genkitx-openai`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/openai) - Plugin for OpenAI APIs.
    *   [`genkitx-azure-openai`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/azure-openai) - Plugin for Azure OpenAI APIs.
2.  Vector Store Plugins
    *   [`genkitx-convex`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/convex) - Plugin for Convex Vector Stores.
    *   [`genkitx-hnsw`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/hnsw) - Plugin for HNSW Vector Stores.
    *   [`genkitx-qdrant`](https://github.com/qdrant/qdrant-genkit) - Plugin for Qdrant Vector Stores.
    *   [`genkitx-astra-db`](https://www.npmjs.com/package/genkitx-astra-db) - Plugin for AstraDB Vector Stores.
    *   [`genkitx-pgvector`](https://www.npmjs.com/package/genkitx-pgvector) - Plugin for PostgeSQL (PGVector) Vector Stores.
    *   [`genkitx-tidb`](https://github.com/BelfoSamad/genkitx-tidb) - Plugin for TiDB Vector Stores.
    *   [`genkitx-redis`](https://github.com/retzd-tech/genkitx-redis) - Plugin for Redis Vector Stores.
3.  Other Plugins
    *   [`genkitx-graph`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/graph) - Plugin for building Graph workflows.
    *   [`@invertase/genkit-plugin-redis`](https://github.com/invertase/genkit-plugin-redis) - A Redis Plugin for GenKit that adds Redis for efficient state storage, trace storage, caching, and rate limiting.
    *   [`genkitx-rxjs`](https://github.com/pavelgj/genkitx-rxjs) - A simple RxJS helper/adapter for Firebase Genkit.
    *   [`@agentic/genkit`](https://agentic.so/sdks/genkit) - Agentic Tools adapter for the Firebase Genkit SDK.

### Golang - Official

1.  Model / Embedding Plugins
    *   [`vertexai`](https://firebase.google.com/docs/genkit-go/plugins/vertex-ai) - The Vertex AI plugin provides interfaces to several AI services: Google generative AI models and Vector Search.
    *   [`googleai`](https://firebase.google.com/docs/genkit-go/plugins/google-genai) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API.
    *   [`ollama`](https://firebase.google.com/docs/genkit-go/plugins/ollama) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
2.  Vector Store Plugins
    *   [`pinecone`](https://firebase.google.com/docs/genkit-go/plugins/pinecone) - Plugin for Pinecone Vector Stores.
    *   [`localvec`](https://firebase.google.com/docs/genkit-go/rag) - Plugin for Local Vector Store for development purposes.
3.  Monitoring Plugins
    *   [`googlecloud`](https://firebase.google.com/docs/genkit-go/plugins/google-cloud) - The Google Cloud plugin exports Firebase Genkit's telemetry and logging data to Google Cloud's operation suite.

### Golang - Community

1.  Model / Embedding Plugins
    *   [`openai`](https://pkg.go.dev/github.com/yukinagae/genkit-go-plugins/plugins/openai) - Plugin for OpenAI APIs.

## Talks

*   [Supercharge your app with Firebase Genkit](https://www.youtube.com/watch?v=eVud8llb_W0) - A talk on how to supercharge your app with Firebase Genkit.

## Videos

*   [Getting started with Genkit](https://www.youtube.com/watch?v=M8rfDySBBvM) - A video tutorial on how to get started with Genkit.
*   [What are Genkit flows? - YouTube](https://youtu.be/ONR38NZK5FE) - Flows are a key concept in Genkit. Learn what makes them special, and how to use them.
*   [Build an Angular app with Genkit and deploy to Firebase](https://youtu.be/TGHua_RtUjs) - Join Pavel as he builds an Angular app and deploys it to Firebase.
*   [DeepDive #1 - Genkit's reflection API and how it powers Genkit's developer UI](https://youtu.be/CGVBR8quZac) - Learn how the Genkit developer UI communicates with Genkit through the reflection API.
*   [Retrieval Augmented Generation (RAG) with Genkit](https://youtu.be/p8ZlYAmbWHE) - Learn how to efficiently parse PDFs, convert their content into searchable vectors using Genkit's local vector store, and implement a re-ranker to pinpoint the most relevant documents for your queries.
*   [Firebase After Hours #3 - Genkit: More than Meets the AI!](https://youtu.be/VFPsp7aURWA?t=152s) - Hang out with Nohe and Peter to learn more about Firebase Genkit, Google's open source AI integration framework. With special guest Pavel Jbanov, lead engineer on the Genkit team.
*   [Firebase After Hours #4 - Genkit: Tooltime](https://youtu.be/01XOIhh2ibA) - Learn how to give LLMs superpowers by conneting the to the real world using tool calling.

## Articles

*   [Build Firebase Genkit Node.js apps with Dash Agents](https://medium.com/firebase-developers/build-firebase-genkit-nodejs-apps-with-dash-agents-skip-the-docs-258e067b3fdc) - A step-by-step guide to building Genkit Node.js apps by leveraging Dash Agents.
*   [Firebase GenKit with Gemma using Ollama](https://xavidop.me/gcp/2024-05-24-firebase-genkit-ollama/) - Firebase project that uses the Gen AI Kit with Gemma using Ollama.
*   [Master Gemma2 and Genkit](https://medium.com/firebase-developers/how-to-develop-using-the-gemma2-model-in-genkit-085f22ce68f3) - Learng how to integrate Gemma2 with Genkit.
*   [Unleash the Power of Function Calling with Genkit](https://medium.com/firebase-developers/implementing-function-calling-using-genkit-0c03f6cb9179) - Learn how to implement function calling using Genkit.

## Tutorials

*   [Slack Bot App](https://medium.com/firebase-developers/build-a-slack-bot-app-with-firebase-genkit-in-just-100-lines-71d4e49c9e08) - A tutorial on how to build a Slack Bot App with Firebase Genkit.

<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

*   [Firebase](https://x.com/firebase) - Official Twitter account for Firebase.
*   [Genkit Discord server](https://discord.gg/qXt5zzQKpc) - Official Discord server for Genkit.
*   [Genkit GitHub (⭐611)](https://github.com/firebase/genkit) - Official GitHub repository for Genkit.
*   [The Fire Company](https://github.com/TheFireCo) - The Fire Company GitHub organization.

## Contributors

[Thanks goes to these contributors (⭐5)](https://github.com/xavidop/awesome-firebase-genkit/graphs/contributors)!

