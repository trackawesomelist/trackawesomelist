# Awesome List Updates on Oct 18, 2023

14 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Gatling](/content/aliesbelik/awesome-gatling/README.md)

### Related / Awesome Lists

*   [Awesome Software Quality (⭐2.2k)](https://github.com/ligurio/sqa-wiki) - A list of free software testing and verification resources.

## [2. Awesome Embedded Rust](/content/rust-embedded/awesome-embedded-rust/README.md)

### Firmware projects / WIP

*   [rmk (⭐275)](https://github.com/HaoboGu/rmk): Mechanical keyboard firmware for stm32/rp2040, supports vial/dynamic keymap/eeprom, written in Rust

## [3. Awesome Nextjs](/content/unicodeveloper/awesome-nextjs/README.md)

### Apps

*   [StorageBox (⭐19)](https://github.com/AlandSleman/StorageBox) - A Simple File Storage Service Built with Go and Next.js.

## [4. Awesome Vite](/content/vitejs/awesome-vite/README.md)

### Templates / React

*   [vite-react-dapp-template (⭐6)](https://github.com/huseyindeniz/vite-react-dapp-template) - Starter template for decentralized app frontend development with preconfigured Wallet Authentication, i18n and UI features.

## [5. Awesome Ios Books](/content/bystritskiy/awesome-ios-books/README.md)

### Swift

*   [*Swift Apprentice: Beyond the Basics* by Eli Ganim, Ehab Amer, Matt Galloway](https://www.kodeco.com/books/swift-apprentice-beyond-the-basics)

## [6. Awesome Opentofu](/content/virtualroot/awesome-opentofu/README.md)

### Tools / Environment managers

*   [asdf-opentofu (⭐20)](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.

## [7. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **RLHF (Reinforcement Learning from Human Feedback) & SFT (Supervised Fine-Tuning)** / **Llama 2 Finetuning**

*   Machine learning technique that trains a "reward model" directly from human feedback and uses the model as a reward function to optimize an agent's policy using reinforcement learning.

### **Build an LLMs from scratch: picoGPT and lit-gpt** / **GPT series release date**

*   `youtube`: [Andrej Karpathy](https://www.youtube.com/watch?v=l8pRSuU81PU): Reproduce the GPT-2 (124M) from scratch. \[June 2024] / [SebastianRaschka](https://www.youtube.com/watch?v=kPGTx4wcm_w): Developing an LLM: Building, Training, Finetuning  \[June 2024]

    <details>

    <summary>Expand</summary>

    *   Beam Search \[1977] in Transformers is an inference algorithm that maintains the `beam_size` most probable sequences until the end token appears or maximum sequence length is reached. If `beam_size` (k) is 1, it's a `Greedy Search`. If k equals the total vocabularies, it's an `Exhaustive Search`. [ref](https://huggingface.co/blog/constrained-beam-search) \[Mar 2022]

    #### Classification of Attention

    *   [ref](https://arize.com/blog-course/attention-mechanisms-in-machine-learning/): Must-Read Starter Guide to Mastering Attention Mechanisms in Machine Learning \[12 Jun 2023]

    1.  Encoder-Decoder Attention:

        1.  Soft Attention: assigns continuous weights to input elements, allowing the model to attend to multiple elements simultaneously. Used in neural machine translation.
        2.  Hard Attention: selects a subset of input elements to focus on while ignoring the rest. Used in image captioning.
        3.  Global Attention: focuses on all elements of the input sequence when computing attention weights. Captures long-range dependencies and global context.
        4.  Local Attention: focuses on a smaller, localized region of the input sequence when computing attention weights. Reduces computational complexity. Used in time series analysis.

    2.  Extended Forms of Attention: Only one Decoder component (only Input Sequence, no Target Sequence)

        1.  Self Attention: attends to different parts of the input sequence itself, rather than another sequence or modality. Captures long-range dependencies and contextual information. Used in transformer models.
        2.  Multi-head Self-Attention: performs self-attention multiple times in parallel, allowing the model to jointly attend to information from different representation subspaces.

        <!-- 1. Hierarchical Attention: attends to different levels of granularity in the input sequence, allowing the model to capture both local and global context. -->

    3.  Other Types of Attention:

        1.  Sparse Attention: reduces computation by focusing on a limited selection of similarity scores in a sequence, resulting in a sparse matrix. It includes implementations of “strided” and “fixed” attention. [ref](https://blog.research.google/2020/10/rethinking-attention-with-performers.html) \[23 Oct 2020]

        <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/rethinking-attention-with-performers.gif"/> -->

        1.  Cross-Attention: mixes two different embedding sequences, allowing the model to attend to information from both sequences. In a Transformer, when the information is passed from encoder to decoder that part is known as Cross Attention. [ref](https://vaclavkosar.com/ml/cross-attention-in-transformer-architecture) / [ref](https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html) \[9 Feb 2023]

        2.  Sliding Window Attention (SWA): A technique used Longformer. It uses a fixed-size window of attention around each token, which allows the model to scale efficiently to long inputs. Each token attends to half the window size tokens on each side. [ref (⭐9.1k)](https://github.com/mistralai/mistral-src#sliding-window-to-speed-up-inference-and-reduce-memory-pressure)

    </details>

## [8. Awesome Langchain](/content/kyrolabs/awesome-langchain/README.md)

### Tools / Agents

*   [GPT Researcher (⭐13k)](https://github.com/assafelovic/gpt-researcher): GPT Researcher is an autonomous agent designed for comprehensive online research on a variety of tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)

### Tools / Platforms

*   [Openllmetry (⭐1.5k)](https://github.com/traceloop/openllmetry): Open-source observability for your LLM application, based on OpenTelemetry ![GitHub Repo stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social)

### Open Source Projects / Other / Chatbots

*   [PersonalityChatbot (⭐43)](https://github.com/btrcm00/chatbot-with-langchain): Langchain chatbot for chat with personality using Langchain🦜 | LangSmith | MongoDB. ![GitHub Repo stars](https://img.shields.io/github/stars/btrcm00/chatbot-with-langchain?style=social)

### Other LLM Frameworks / Videos Playlists

*   [MemGPT (⭐11k)](https://github.com/cpacker/MemGPT): Teaching LLMs memory management for unbounded context ![GitHub Repo stars](https://img.shields.io/github/stars/cpacker/MemGPT?style=social)

## [9. Awesome Board Games](/content/edm00se/awesome-board-games/README.md)

### Strategy

### [Lotería](https://boardgamegeek.com/boardgame/5878/loteria)

> Lotería (Spanish word meaning "lottery") is a traditional game of chance, similar to bingo, but using images on a deck of cards instead of numbered ping pong balls. Every image has a name and an assigned number, but the number is usually ignored. Each player has at least one tabla, a board with a randomly created 4 x 4 grid of pictures with their corresponding name and number. Players choose a tabla (Spanish word for "board") to play with, from a variety of previously created tablas, each with a different selection of images.

![Lotería image](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Loteria_boards.jpg/330px-Loteria_boards.jpg)

| Players | Min. Age | Time |
| ------: | -------: | ---: |
|       2 |        8 |  20m |

### Party

### [Outfoxed](https://boardgamegeek.com/boardgame/172931/outfoxed)

> This game is like Clue but for younger kids – and yet still fun for adults too. A fox stole a pot pie, and you have to figure out which fox it was before they escape into the foxhole. My kids regularly play this cooperative whodunnit game independently, and I love watching them work together as a team to solve the mystery. This is a fun little game to build your child’s logic and deductive reasoning skills!

![Outfoxed](https://cf.geekdo-images.com/v0FCI-wY8YlPn39XKd3F8w__itemrep/img/KGnNOM0FA8nwFXtKFsamxkx5v2E=/fit-in/246x300/filters:strip_icc\(\)/pic2401324.jpg)

| Players | Min. Age | Time |
| ------: | -------: | ---: |
|   2 - 4 |        5 |  20m |

## [10. Free for Dev](/content/ripienaar/free-for-dev/README.md)

### Security and PKI

*   [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - Search across 20 million exposed secrets in public GitHub repositories, gists, issues,and comments for Free

## [11. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Tree-sitter Supported Colorscheme / Diagnostics

*   [text-to-colorscheme (⭐281)](https://github.com/svermeulen/text-to-colorscheme) - Dynamically generated colorschemes generated on the fly with a text prompt using ChatGPT.

### Neovim Lua Development / Diagnostics

*   [nvim-lusc (⭐13)](https://github.com/svermeulen/nvim-lusc) - Adds support for Structured Async/Concurrency in Lua.

### Motion / Diagnostics

*   [gsuuon/tshjkl.nvim (⭐99)](https://github.com/gsuuon/tshjkl.nvim) - Toggle to navigate and select tree-sitter nodes with hjkl.

## [12. Awesome Bash](/content/awesome-lists/awesome-bash/README.md)

### Books and Resources

*   [explainshell](https://explainshell.com) - A website that breaks down and explains shell (Bash) commands (including their flags and options).

## [13. Static Analysis](/content/analysis-tools-dev/static-analysis/README.md)

### Multiple languages / [Other](#other-1)

*   [BugProve](https://www.bugprove.com) :copyright: — BugProve is a firmware analysis platform featuring both static and dynamic analysis techniques to discover memory corruptions, command injections and other classes or common weaknesses in binary code. It also detects vulnerable dependencies, weak cryptographic parameters, misconfigurations, and more.
*   [OpenRewrite](https://docs.openrewrite.org/) — OpenRewrite [fixes common static analysis issues](https://docs.openrewrite.org/running-recipes/popular-recipe-guides/common-static-analysis-issue-remediation)  reported through Sonar and other tools using a Maven and Gradle plugin or the Moderne CLI.

## [14. Free Programming Books (English, By Programming Language)](/content/EbookFoundation/free-programming-books/README.md)

### Go / Phoenix

*   [An Introduction to Programming in Go](https://www.golang-book.com/books/intro) - Caleb Doxsey

### SQL (implementation agnostic) / Play Scala

*   [Learning SQL](https://riptutorial.com/Download/sql.pdf) - Compiled from StackOverflow Documentation (PDF)

### SQL Server / Play Scala

*   [Learning Microsoft SQL Server](https://riptutorial.com/Download/microsoft-sql-server.pdf) - Compiled from StackOverflow Documentation (PDF)

---

- Prev: [Oct 19, 2023](/content/2023/10/19/README.md)
- Next: [Oct 17, 2023](/content/2023/10/17/README.md)