# Awesome List Updates on Mar 08, 2024

10 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Distraction Blocker](/content/stan8086/awesome-distraction-blocker/README.md)

### Apps and Tools / Windows

*   [FocusWriter](https://gottcode.org/focuswriter/) - A distraction-free writing environment.
*   [Cold Turkey](https://getcoldturkey.com/) - [Review](https://productivity.directory/cold-turkey) - Block distracting websites and applications.

### Apps and Tools / MacOS

*   [SelfControl](https://selfcontrolapp.com/) - [Review](https://productivity.directory/selfcontrol) - A free and open-source application for Mac OS X that lets you block your own access to distracting websites.
*   [HeyFocus](https://heyfocus.com/) - [Review](https://productivity.directory/heyfocus) - Block websites and applications to improve productivity.

### Apps and Tools / Linux

*   [LeechBlock NG (⭐547)](https://github.com/proginosko/LeechBlockNG) - A simple productivity tool designed to block distracting websites.

### Apps and Tools / Browser Extensions

*   [StayFocusd](https://chrome.google.com/webstore/detail/stayfocusd/laankejkbhbdhmipfmgcngdelahlfoji) - [Review](https://productivity.directory/stayfocusd) - Increase your productivity by limiting the amount of time spent on time-wasting websites.
*   [Freedom](https://freedom.to/) - [Review](https://productivity.directory/freedom) - Block distractions on all of your devices.

### Apps and Tools / Mobile Apps

*   [Forest](https://www.forestapp.cc/) - [Review](https://productivity.directory/forest) - Stay focused, be present, and turn your focused moments into a lovely forest.
*   [Offtime](http://offtime.co/) - Disconnect from smartphone overuse.

### Research Papers / Mobile Apps

*   [Understanding and Developing Tools for Attention Management in Technology-Intensive Workplaces](https://example.com)

### Communities / Mobile Apps

*   [Productivity Directory](https://productivity.directory/) - A directory for productivity tools and apps
*   [Productivity Blog](https://blog.productivity.directory/) - Top blog on Productivity
*   [r/productivity](https://www.reddit.com/r/productivity/) - The subreddit dedicated to productivity hacks and tips.
*   [Focusmate Community](https://www.focusmate.com/community) - A virtual co-working community to increase accountability and focus.

### Contribution Guidelines / Mobile Apps

*   Search previous suggestions before making a new one, as yours may be a duplicate.
*   Suggested resources should be of high quality and well-documented.
*   Comments on why the resource is worthwhile are encouraged.
*   Make an individual pull request for each suggestion.

## [2. Awesome Polars](/content/ddotta/awesome-polars/README.md)

### Resources / Blog posts

*   [Revisiting a Classic Cheminformatics Paper with Polars: The Wiener Index](https://bertiewooster.github.io/2023/03/10/Revisiting-a-Classic-Cheminformatics-Paper-The-Wiener-Index.html) - A science blog post that uses Polars to track the information for the molecules in DataFrames by [@bertiewooster](https://github.com/bertiewooster).

## [3. Awesome Langchain](/content/kyrolabs/awesome-langchain/README.md)

### Tools / Services

*   [MindSQL (⭐168)](https://github.com/Mindinventory/MindSQL) - A python package for Txt-to-SQL with self hosting functionalities and RESTful APIs compatible with proprietary as well as open source LLM.![GitHub Repo stars](https://img.shields.io/github/stars/mindinventory/mindsql?style=social)

## [4. Awesome Svelte](/content/TheComputerM/awesome-svelte/README.md)

### Tutorials

*   [Setup Authentication with AuthJS and Sveltekit 2.0](https://www.youtube.com/watch?v=ridRgYSJ0ds) - @bradcypert (YouTube)

### State Libraries

*   [exome (⭐222)](https://github.com/Marcisbee/exome) - Simple proxy based state manager for deeply nested states.

### UI Libraries

*   [Skeleton](https://www.skeleton.dev/docs/get-started) - Skeleton uses Tailwind utility classes and design system to easily create theme-able user interfaces.
*   [M3 Svelte (⭐156)](https://github.com/KTibow/m3-svelte) - Robust component library implementing Material Design 3

## [5. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2106.09685)]: LoRA is one of PEFT technique. To represent the weight updates with two smaller matrices (called update matrices) through low-rank decomposition. [git (⭐10k)](https://github.com/microsoft/LoRA) \[17 Jun 2021]

     <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/LoRA.png" alt="LoRA" width="390"/>

    <details open>

    <summary>Expand: LoRA Family</summary>

    1.  [LoRA+](https://arxiv.org/abs/2402.12354): Improves LoRA’s performance and fine-tuning speed by setting different learning rates for the LoRA adapter matrices. \[19 Feb 2024]
    2.  [LoTR](https://arxiv.org/abs/2402.01376): Tensor decomposition for gradient update. \[2 Feb 2024]
    3.  [The Expressive Power of Low-Rank Adaptation](https://arxiv.org/abs/2310.17513): Theoretically analyzes the expressive power of LoRA. \[26 Oct 2023]
    4.  [DoRA](https://arxiv.org/abs/2402.09353): Weight-Decomposed Low-Rank Adaptation. Decomposes pre-trained weight into two components, magnitude and direction, for fine-tuning. \[14 Feb 2024]
    5.  LoRA Family [ref](https://towardsdatascience.com/an-overview-of-the-lora-family-515d81134725) \[11 Mar 2024]
        *   `LoRA` introduces low-rank matrices A and B that are trained, while the pre-trained weight matrix W is frozen.
        *   `LoRA+` suggests having a much higher learning rate for B than for A.
        *   `VeRA` does not train A and B, but initializes them randomly and trains new vectors d and b on top.
        *   `LoRA-FA` only trains matrix B.
        *   `LoRA-drop` uses the output of B\*A to determine, which layers are worth to be trained at all.
        *   `AdaLoRA` adapts the ranks of A and B in different layers dynamically, allowing for a higher rank in these layers, where more contribution to the model’s performance is expected.
        *   `DoRA` splits the LoRA adapter into two components of magnitude and direction and allows to train them more independently.
        *   `Delta-LoRA` changes the weights of W by the gradient of A\*B.
    6.  5 Techniques of LoRA [ref](https://blog.dailydoseofds.com/p/5-llm-fine-tuning-techniques-explained): LoRA, LoRA-FA, VeRA, Delta-LoRA, LoRA+ \[May 2024]

    </details>

### **Quantization Techniques** / **Llama Finetuning**

*   [The Era of 1-bit LLMs](https://arxiv.org/abs/2402.17764): All Large Language Models are in 1.58 Bits. BitNet b1.58, in which every single parameter (or weight) of the LLM is ternary {-1, 0, 1}. \[27 Feb 2024]

### **MLLM (multimodal large language model)** / **GPT series release date**

*   Anthrophic
    1.  [Claude 3 Opus](https://www.anthropic.com/news/claude-3-family), the largest version of the new LLM, outperforms rivals GPT-4 and Google’s Gemini 1.0 Ultra. Three variants: Opus, Sonnet, and Haiku. \[Mar 2024]

### **Build an LLMs from scratch: picoGPT and lit-gpt** / **GPT series release date**

*   [Spreadsheets-are-all-you-need (⭐1.1k)](https://github.com/ianand/spreadsheets-are-all-you-need): Spreadsheets-are-all-you-need implements the forward pass of GPT2 entirely in Excel using standard spreadsheet functions. \[Sep 2023]

### **Evaluating Large Language Models** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   [LLMPerf Leaderboard (⭐414)](https://github.com/ray-project/llmperf-leaderboard): Evaulation the performance of LLM APIs. \[Dec 2023]

## [6. Awesome Agi Cocosci](/content/YuzheSHI/awesome-agi-cocosci/README.md)

### Abduction / Applications in AI

*   [Human Comprehensible Active Learning of Genome-Scale Metabolic Networks](https://arxiv.org/abs/2308.12740) - ***AAAI Spring Symposium Series 2023 on Computational Scientific Discovery***, 2023. \[[All Versions](https://scholar.google.com/scholar?cluster=10875437066608527790)]. \[[Extended Abstract](http://cogsys.org/symposium/discovery-2023/abstracts/Abstract_3169.pdf)]. \[[Slides](http://cogsys.org/symposium/discovery-2023/talks/Ai.pdf)]. This work introduces a novel machine learning framework ILP-iML1515 based on Inductive Logic Programming (ILP) that performs abductive logical reasoning and actively learns from training examples. The ILP-iML1515 framework 1) allows high-throughput simulations and 2) actively selects experiments that reduce the experimental cost of learning gene functions in comparison to randomly selected experiments.

### Domain Specific Language / Design Practises

*   [How Domain Experts Use an Embedded DSL](https://dl.acm.org/doi/abs/10.1145/3622851) - ***OOPSLA'23***, 2023. This work conducts a thematic analysis identified five key themes, including: the interaction between the eDSL and the host language has significant and sometimes unexpected impacts on eDSL user experience, and users preferentially engage with domain-specific communities and code templates rather than host language resources.

## [7. Awesome Django](/content/wsvincent/awesome-django/README.md)

### Third-Party Packages / Commands

*   [django-typer (⭐66)](https://github.com/bckohan/django-typer) - Write Django management commands using the [Typer CLI library](https://typer.tiangolo.com).

## [8. Awesome Stacks](/content/stackshareio/awesome-stacks/README.md)

### Graphweaver - GraphQL API Over Multiple Datasources [↗](https://awesomestacks.dev/graphweaver-graphql-api-over-multiple-datasources) / Resources

*   [Graphweaver](https://graphweaver.com/) - [🛠️](https://stackshare.io/graphweaver) - [🐙 (⭐428)](https://github.com/exogee-technology/graphweaver) - Data Everywhere - Instant GraphQL.
*   [AWS Cognito](https://aws.amazon.com/cognito) - Pre-built integration with AWS Cognito.
*   [Connect to a datasource](https://graphweaver.com/docs/connect-to-a-data-source)

## [9. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### (requires Neovim 0.5)

*   [LukasPietzschmann/boo.nvim (⭐32)](https://github.com/LukasPietzschmann/boo.nvim) - Quickly pop-up some LSP-powered information of the thing your cursor is on.

## [10. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [ai-commands (⭐18)](https://github.com/muePatrick/zsh-ai-commands) - Asks GPT (gpt-4-turbo-preview) for CLI commands that achieve the described target action.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [acenoster (⭐13)](https://github.com/himdek/Acenoster-ZSH-Theme) - A multi-purpose theme with very detailed `git` and `mercurial` support. Also includes decorators for AWS profile name, virtual environment name if any, number of background tasks, current directory and previous command's exit code if non-zero.

---

- Prev: [Mar 09, 2024](/content/2024/03/09/README.md)
- Next: [Mar 07, 2024](/content/2024/03/07/README.md)