# Awesome List Updates on Nov 01, 2023

16 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Capacitorjs](/content/capawesome-team/awesome-capacitorjs/README.md)

### Plugins / Community Plugins

*   [capacitor-plugin-safe-area (⭐55)](https://github.com/AlwaysLoveme/capacitor-plugin-safe-area) - Get SafeArea info on Android and IOS.

## [2. Awesome Ai Tools](/content/mahseema/awesome-ai-tools/README.md)

### Video / Stable Diffusion resources

*   [ShortVideoGen](https://shortgen.video/) - Create short videos with audio using text prompts.

## [3. Awesome Embedded Rust](/content/rust-embedded/awesome-embedded-rust/README.md)

### Books, blogs, and training materials / Free and public materials

*   [Tweede golf's workshop](https://workshop.tweede.golf) - A full workshop about Rust and embedded Rust. The embedded parts use the nRF52840-DK and a LIS3DH breakout board. ([github source (⭐11)](https://github.com/tweedegolf/rust-workshop))

## [4. Awesome Swift](/content/matteocrippa/awesome-swift/README.md)

### Chat

*   [ExyteChat (⭐746)](https://github.com/exyte/chat) - SwiftUI Chat UI framework with fully customizable message cells, input view, and a built-in media picker

## [5. Urban and Regional Planning Resources](/content/APA-Technology-Division/urban-and-regional-planning-resources/README.md)

### Public Data Resources / Housing

*   [National Housing Preservation Database](https://preservationdatabase.org/) - The National Housing Preservation Database contains property and subsidy-level data pulled from nine different HUD and USDA data sources.  The database contains information on over 70,000 properties nationwide.

## [6. Awesome Graphql](/content/chentsulin/awesome-graphql/README.md)

### JavaScript Examples / React

*   [Apollo Client documentation](https://www.apollographql.com/docs/react) - Documentation and example for building GraphQL apps using apollo client.

### Tools - Security / React

*   [GraphQLer (⭐71)](https://github.com/omar2535/GraphQLer) - Dependency-aware dynamic GraphQL testing tool

## [7. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Semantic Kernel** / **Semantic Kernel Planner**

*   Is Semantic Kernel Planner the same as LangChain agents?

    > Planner in SK is not the same as Agents in LangChain. [cite (⭐21k)](https://github.com/microsoft/semantic-kernel/discussions/1326) \[11 May 2023]

    > Agents in LangChain use recursive calls to the LLM to decide the next step to take based on the current state.
    > The two planner implementations in SK are not self-correcting.
    > Sequential planner tries to produce all the steps at the very beginning, so it is unable to handle unexpected errors.
    > Action planner only chooses one tool to satisfy the goal

### **LangChain Agent & Memory** / LangChain Agent

*   If you're using a text LLM, first try `zero-shot-react-description`.
*   If you're using a Chat Model, try `chat-zero-shot-react-description`.
*   If you're using a Chat Model and want to use memory, try `conversational-react-description`.

### **Prompt Engineering** / **Prompt Template Language**

*   [Recursively Criticizes and Improves (RCI)](https://arxiv.org/abs/2303.17491): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2303.17491)] \[30 Mar 2023]
    *   Critique: Review your previous answer and find problems with your answer.
    *   Improve: Based on the problems you found, improve your answer.
*   [Tree of Thought](https://arxiv.org/abs/2305.10601): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2305.10601)]: Self-evaluate the progress intermediate thoughts make towards solving a problem \[17 May 2023] [git (⭐4.5k)](https://github.com/ysymyth/tree-of-thought-llm) / Agora: Tree of Thoughts (ToT) [git (⭐4.2k)](https://github.com/kyegomez/tree-of-thoughts)

    *   `tree-of-thought\forest_of_thought.py`: Forest of thought Decorator sample
    *   `tree-of-thought\tree_of_thought.py`: Tree of thought Decorator sample
    *   `tree-of-thought\react-prompt.py`: ReAct sample without LangChain
*   Zero-shot, one-shot and few-shot [cite](https://arxiv.org/abs/2005.14165) \[28 May 2020]

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/zero-one-few-shot.png" width="200">
*   Promptist

    *   [Promptist](https://arxiv.org/abs/2212.09611): Microsoft's researchers trained an additional language model (LM) that optimizes text prompts for text-to-image generation.
        *   For example, instead of simply passing "Cats dancing in a space club" as a prompt, an engineered prompt might be "Cats dancing in a space club, digital painting, artstation, concept art, soft light, hdri, smooth, sharp focus, illustration, fantasy."

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   Category: Represent approach - Description - Pseudo Code [ref](https://speakerdeck.com/schulta) \[22 Sep 2023]

    1.  Adapters: Adapters - Additional Layers. Inference can be slower.

        ```python
        def transformer_with_adapter(x):
          residual = x
          x = SelfAttention(x)
          x = FFN(x) # adapter
          x = LN(x + residual)
          residual = x
          x = FFN(x) # transformer FFN
          x = FFN(x) # adapter
          x = LN(x + residual)
          return x
        ```

    2.  Soft Prompts: Prompt-Tuning - Learnable text prompts. Not always desired results.

        ```python
        def soft_prompted_model(input_ids):
          x = Embed(input_ids)
          soft_prompt_embedding = SoftPromptEmbed(task_based_soft_prompt)
          x = concat([soft_prompt_embedding, x], dim=seq)
          return model(x)
        ```

    3.  Selective: BitFit - Update only the bias parameters. fast but limited.

        ```python
        params = (p for n,p in model.named_parameters() if "bias" in n)
        optimizer = Optimizer(params)
        ```

    4.  Reparametrization: LoRa - Low-rank decomposition. Efficient, Complex to implement.

        ```python
        def lora_linear(x):
          h = x @ W # regular linear
          h += x @ W_A @ W_B # low_rank update
          return scale * h
        ```

### **Quantization Techniques** / **Llama Finetuning**

*   Post-training quantization (PTQ): The model is quantized after it has been trained without further optimization during the quantization process.

    | Method                      | Pros                                                        | Cons                                                            |
    | --------------------------- | ----------------------------------------------------------- | --------------------------------------------------------------- |
    | Post-training quantization  | Easy to use, no need to retrain the model                   | May result in accuracy loss                                     |
    | Quantization-aware training | Can achieve higher accuracy than post-training quantization | Requires retraining the model, can be more complex to implement |

### **Numbers LLM** / **GPT series release date**

*   [Numbers every LLM Developer should know (⭐4k)](https://github.com/ray-project/llm-numbers) \[18 May 2023] <br/> <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/llm-numbers.png" height="360">

### **Large Language Models (in 2023)** / **GPT series release date**

*   Change in perspective is necessary because some abilities only emerge at a certain scale. Some conclusions from the past are invalidated and we need to constantly unlearn intuitions built on top of such ideas.
*   From first-principles, scaling up the Transformer amounts to efficiently doing matrix multiplications with many, many machines.
*   Further scaling (think 10000x GPT-4 scale). It entails finding the inductive bias that is the bottleneck in further scaling.

### **LLM Materials for East Asian Languages** / Japanese

*   [法律:生成 AI の利用ガイドライン](https://storialaw.jp/blog/9414): Legal: Guidelines for the Use of Generative AI

## [8. Awesome Talks](/content/JanVanRyswyck/awesome-talks/README.md)

### Databases

*   [Things Every Developer Absolutely, Positively Needs To Know About Database Indexing](https://www.youtube.com/watch?v=HubezKbFL7E) by **Kai Sassnowski** \[41:49]

## [9. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Compression

*   [minizip-ng (⭐1.2k)](https://github.com/zlib-ng/minizip-ng) - Fork of the popular zip manipulation library found in the zlib distribution. \[zlib]

## [10. Awesome Parasite](/content/ecohealthalliance/awesome-parasite/README.md)

### Databases

*   [Human Virus Database (HVD)](http://computationalbiology.cn/humanVirusBase/#/) - A database of human viruses, including information on infected tissues. See description and use in a predictive model in [Ye et al. 2022](https://academic.oup.com/bioinformatics/article-abstract/38/11/3087/6569817?redirectedFrom=fulltext)

## [11. Awesome Board Games](/content/edm00se/awesome-board-games/README.md)

### Family

### [Stationfall](https://boardgamegeek.com/boardgame/316624/stationfall)

> A game of blackmail and betrayal, murder and mayhem, danger and destruction.
> What is Stationfall? Well, imagine a dozen or so random humans, robots, and none-of-the-aboves, each with their own abilities, goals, and secret relationships, have been turned loose on a space station that is going to be incinerated upon its inevitable reentry into Earth's atmosphere. You are one of these characters, and the others are collaborators you have on hand ready to assist you in achieving your goals. But choose them wisely, as any one of them could secretly be another player waiting to betray you!
>
> *   Stationfall is a box full of creative solutions, but that box is going to morph, twist, and grow teeth over the course of play. Your best turns will exploit the unique tactical freedom of being a secret conspiracy, as well as deductions about your opponents’ identities and motives. Stationfall is messy, intricate, and full of dangerous variables.

![Stationfall game image](https://cf.geekdo-images.com/eUiju5SqZbkNt8gnEofrTw__itemrep/img/lpTPPEk14XV1RzIhRYVIWNHD0I4=/fit-in/246x300/filters:strip_icc\(\)/pic6035127.png)

| Players | Min. Age |    Time |
| ------: | -------: | ------: |
|   1 - 9 |       12 | 90-120m |

### Party

### [The Last Bottle of Rum](https://boardgamegeek.com/boardgame/275557/last-bottle-rum)

> A pirate board game for 2 to 5 players, where you play as a pirate looking to trade its treasures for the very last bottle of rum of the archipelago... Prepare to explore uncharted waters, plunder your enemies and avoid the Kraken! To win the game, a player will have to score the most victory points by digging up hidden treasures.

> On each turn, choose two cards from your hand. The cards you play determines the actions you may take. Cleverly combo actions and effects to overcome obstacles and keep pace with rival captains. Fire your cannons on your opponents to slow down their treasure-hunting. Push your luck at the risk of being cursed and chased by the deadly Kraken! Play one of the unique characters and use your game-changing abilities when it’s least expected!

> The first Captain to collect 10 booty points gets the last bottle of the archipelago and wins the game.

![The Last Bottle of Rum](https://cf.geekdo-images.com/W-28SI7dtFwOM6KYD9egrQ__itemrep/img/UIIbwvNMAHbyDJriFpltV-7nHd4=/fit-in/246x300/filters:strip_icc\(\)/pic5715210.jpg)

| Players | Min. Age |   Time |
| ------: | -------: | -----: |
|   2 - 5 |      10+ | 45-60m |
### [Zoo Vadis](https://boardgamegeek.com/boardgame/368061/zoo-vadis)

> What if the animals were the ones who ran the zoo? Presumably, this wild government would be built upon the support of fellow creatures and fueled by the fame, attention, and prestige of wide-eyed visitors. Naturally, the most aspirational beasts would lobby for a position in the star exhibit, and the lead star would be elected Zoo Mascot.In order to join the star exhibit, each species must campaign its way up the hierarchy of enclosures with the majority support of animal voters. And the lead star will be the species that has earned the most laurels from both raving fans and jealous rivals along the way. How does one gain support and earn laurels? Through crafty politicking, clever negotiations, and ruthless schemes. There can only be one Zoo Mascot, after all. Where are you going? That is the ultimate question of Zoo Vadis.
>
> Zoo Vadis is an evolution of Reiner Knizia’s classic negotiation game, Quo Vadis? It retains the elegant, political gameplay that fans have come to love while introducing many innovations and improvements by: a) Enhancing the 3-player game and tailoring the board to all player counts through neutral, bribable figures—roaming peacocks, b) Widening the player count with a second game board for 6-7 players, c) Expanding the possibilities for strategic negotiation with asymmetric animal abilities, d) Increasing tactical opportunities with new special laurel tokens, e) Broadening the appeal of the theme and presentation with vibrant zoo art by Kwanchai Moriya and Brigette Indelicato, f) Enlivening the production with chunky animal figures and functional player screens.
>
> Like the original design, the game ends immediately when the Star Exhibit is full. Only the animals who have reached the Star Exhibit qualify for victory, and the winner is the player with the most laurels.

![Zoo Vadis](https://cf.geekdo-images.com/Kl3NjtNKpuJNPjdBQtdsow__itemrep/img/mmVsnLtn3T4zkeNbjWpfrWZKS5c=/fit-in/246x300/filters:strip_icc\(\)/pic6988937.jpg)

| Players | Min. Age |   Time |
| ------: | -------: | -----: |
|   3 - 7 |      10+ | 20-40m |
### [Twilight Inscription](https://boardgamegeek.com/boardgame/361545/twilight-inscription)

> Roll your way through the Twilight Imperium universe.
> The Lazax Empire has burned to ash, rejected by its subjects. The aftermath was tragedy and petty conflict in equal measure, a time of loss and exhaustion. In the ensuing Dark Years, the factions of the galaxy retreated and recovered their strength. Now, they look upon the stars and see an opportunity—a chance to reclaim what was lost. A chance to redefine galactic civilization. A chance to leave their mark upon the stars.
> Twilight Inscription, an epic roll-and-write game for one to eight players, offers an experience unlike anything Fantasy Flight Games has done before. With a limited pool of resources at your disposal, you’ll need to carefully manage Navigation, Expansion, Industry, and Warfare as you amass victory points and earn your right to the throne on Mecatol Rex. Will your faction become the new rulers of the galaxy? Or will your fledgling empire fade into obscurity? Anything can happen in this strategic, infinitely-replayable game!

![Twilight Inscription](https://cf.geekdo-images.com/g36va6ofPCzNZXF-9GEpCg__itemrep/img/V3Cny2dR0eXaJjFkqkOCOoKP9Tg=/fit-in/246x300/filters:strip_icc\(\)/pic7132023.png)

| Players | Min. Age |    Time |
| ------: | -------: | ------: |
|   1 - 8 |      14+ | 90-120m |

### Contribute

### [Hadrian's Wall](https://boardgamegeek.com/boardgame/304783/hadrians-wall)

> When visiting the North of Britannia in 122 AD, the Roman Emperor Hadrian Augustus witnessed the aftermath of war between his armies and the savage Picts. In a show of Roman might, he ordered a wall to be built that would separate the Pict tribes from the rest of England. Grand in its design, the wall stretched 80 Roman miles, from coast to coast. Hadrian's Wall stood in service to the Roman Empire for nearly 300 years before its eventual decline. Today, Hadrian's Wall is a UNESCO World Heritage Site and the remains of the forts, towers, and turrets can still be explored.
>
> In Hadrian's Wall, players take on the role of a Roman General placed in charge of the construction of a milecastle and bordering wall. Over six years (rounds), players will construct their fort and wall, man the defenses, and attract civilians by building services and providing entertainment — all while defending the honor of the Roman Empire from the warring Picts. The player who can accumulate the most renown, piety, valor and discipline, whilst avoiding disdain, will prove to the Emperor they are the model Roman citizen and be crowned Legatus Legionis!

![Hadrian's Wall](https://cf.geekdo-images.com/4XzRDw3VrgNpNfZlzZl66w__itemrep/img/V1Db0T3MlAicjsL1C_PrOLfm_xY=/fit-in/246x300/filters:strip_icc\(\)/pic5608818.png)

| Players | Min. Age |   Time |
| ------: | -------: | -----: |
|   1 - 6 |      12+ | 30-60m |

Contributions are welcome and encouraged! Read the [contribution guidelines](https://github.com/edm00se/awesome-board-games/blob/main/readme.md/contributing.md) first.

## [12. Awesome Generative Deep Art](/content/filipecalegario/awesome-generative-deep-art/README.md)

### Human-AI Interaction

*   \[🔥🔥🔥] [\[2310.07127\] An HCI-Centric Survey and Taxonomy of Human-Generative-AI Interactions](https://arxiv.org/abs/2310.07127): "a survey of 154 papers, providing a novel taxonomy and analysis of Human-GenAI Interactions from both human and Gen-AI perspectives".

### Critical Views about Generative AI

*   [Responsible enterprise decisions with knowledge-enriched generative AI | Deloitte Netherlands](https://www2.deloitte.com/nl/nl/pages/risk/articles/responsible-enterprise-decisions-with-knowledge-enriched-generative-AI.html)
*   [\[2310.13149\] Understanding Generative AI in Art: An Interview Study with Artists on G-AI from an HCI Perspective](https://arxiv.org/abs/2310.13149)
*   [\[2309.12338\] Artificial Intelligence and Aesthetic Judgment](https://arxiv.org/abs/2309.12338): "as generative AI influences contemporary aesthetic judgment we outline some of the pitfalls and traps in attempting to scrutinize what AI generated media means"

### Related Awesome Lists / Deforum

*   [Hannibal046/Awesome-LLM: Awesome-LLM (⭐17k)](https://github.com/Hannibal046/Awesome-LLM): a curated list of Large Language Model
*   [AlexChalakov/awesome-generative-ai-companies (⭐95)](https://github.com/AlexChalakov/awesome-generative-ai-companies): a curated list of Gеnerative AI companies, sorted by focus area and total fundraised amount

### Retrieval-Augmented Generation (RAG) / Prompt Engineering for Text-to-image

*   [dssjon/biblos: biblos.app (⭐191)](https://github.com/dssjon/biblos): example of RAG architecture using semantic search and summarization for retrieving Bible passages

### Autonomous LLM Agents / Prompt Engineering for Text-to-image

*   [\[2309.02427\] Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427): "we draw on the rich history of cognitive science and symbolic artificial intelligence to propose Cognitive Architectures for Language Agents (CoALA)"

### AI Tools for Research / Multi-agents

*   [\[2310.17143\] Supercharging academic writing with generative AI: framework, techniques, and caveats](https://arxiv.org/abs/2310.17143)

## [13. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### State Management / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [exome (⭐228)](https://github.com/Marcisbee/exome) - Simple proxy based state manager for deeply nested states, works with Angular Signals and RxJS.

## [14. Static Analysis](/content/analysis-tools-dev/static-analysis/README.md)

### Programming Languages / [Other](#other-1)

*   [Dataflow Framework (⭐1k)](https://github.com/typetools/checker-framework) — An industrial-strength dataflow framework for Java. The Dataflow Framework is used in the Checker Framework, Google’s Error Prone, Uber’s NullAway, Meta’s Nullsafe, and in other contexts. It is distributed with the Checker Framework.

### Other / [Other](#other-1)

*   [kani (⭐2.1k)](https://github.com/model-checking/kani) — The Kani Rust Verifier is a bit-precise model checker for Rust.
    Kani is particularly useful for verifying unsafe code blocks in Rust,
    where the "unsafe superpowers" are unchecked by the compiler.
    Kani verifies:
*   [vale](https://vale.sh) — A syntax-aware linter for prose built with speed and extensibility in mind.

## [15. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Deep Learning Packages / PyTorch Ecosystem

*   [Yolov3 (⭐10k)](https://github.com/ultralytics/yolov3)
*   [Yolov5 (⭐49k)](https://github.com/ultralytics/yolov5)
*   [Yolov8 (⭐27k)](https://github.com/ultralytics/ultralytics)

## [16. Free Programming Books (English, By Subjects)](/content/EbookFoundation/free-programming-books/books/free-programming-books-subjects/README.md)

### Data Science

*   [Feature Engineering and Selection: A Practical Approach for Predictive Models](https://bookdown.org/max/FES/) - Max Kuhn, Kjell Johnson

---

- Prev: [Nov 02, 2023](/content/2023/11/02/README.md)
- Next: [Oct 31, 2023](/content/2023/10/31/README.md)