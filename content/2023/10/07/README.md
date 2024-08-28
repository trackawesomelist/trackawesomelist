# Awesome List Updates on Oct 07, 2023

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/README.md)

### **Finetuning** / PEFT: Parameter-Efficient Fine-Tuning ([Youtube](https://youtu.be/Us5ZFp16PaU)) [24 Apr 2023]

*   [Efficient Streaming Language Models with Attention Sinks](http://arxiv.org/abs/2309.17453): \[[cnt](https://scholar.google.com/scholar?hl=en\&as_sdt=0%2C5\&q=arxiv%3A+2309.17453)] 1. StreamingLLM, an efficient framework that enables LLMs trained with a finite length attention window to generalize to infinite sequence length without any fine-tuning. 2. We neither expand the LLMs' context window nor enhance their long-term memory. [git (⭐6.4k)](https://github.com/mit-han-lab/streaming-llm) \[29 Sep 2023]

    <details>

    <summary>Expand: StreamingLLM</summary>

    <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/streaming-llm.png" alt="streaming-attn"/>

    *   Key-Value (KV) cache is an important component in the StreamingLLM framework.

    1.  Window Attention: Only the most recent Key and Value states (KVs) are cached. This approach fails when the text length surpasses the cache size.
    2.  Sliding Attention /w Re-computation: Rebuilds the Key-Value (KV) states from the recent tokens for each new token. Evicts the oldest part of the cache.
    3.  StreamingLLM: One of the techniques used is to add a placeholder token (yellow-colored) as a dedicated attention sink during pre-training. This attention sink attracts the model’s attention and helps it generalize to longer sequences. Outperforms the sliding window with re-computation baseline by up to a remarkable 22.2× speedup.

    </details>

## [2. Awesome Qubes OS](/content/xn0px90/Awesome-Qubes-OS/README.md)

### Optics and Extra Info / Unikernel-like

*   [Qubes OS Summit 2023](https://www.youtube.com/watch?v=_UxndcxIngw) - Day 1

## [3. Awesome List](/content/sindresorhus/awesome/README.md)

### Decentralized Systems

*   [Mastodon (⭐24)](https://github.com/hyperupcall/awesome-mastodon#readme) - Open source decentralized microblogging network.

## [4. Web Development Resources](/content/markodenic/web-development-resources/README.md)

### Coding Challenge Platforms:

- Website: <https://divize.io/challenges>



### Animation Libraries:

- Website: [Motion One](https://motion.dev)



## [5. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Colleges

*   [BS in Data Science & Applications](https://study.iitm.ac.in/ds/)

### Comparison / Unsupervised Learning

*   [Neural Networks](https://en.wikipedia.org/wiki/Neural_network)

### Comparison / Deep Learning architectures

*   [Multilayer Perceptron](https://en.wikipedia.org/wiki/Multilayer_perceptron)
*   [Convolutional Neural Network (CNN)](https://en.wikipedia.org/wiki/Convolutional_neural_network)
*   [Recurrent Neural Network (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network)
*   [Boltzmann Machines](https://en.wikipedia.org/wiki/Boltzmann_machine)
*   [Autoencoder](https://www.tensorflow.org/tutorials/generative/autoencoder)
*   [Generative Adversarial Network (GAN)](https://developers.google.com/machine-learning/gan/gan_structure)
*   [Self-Organized Maps](https://en.wikipedia.org/wiki/Self-organizing_map)
*   [Transformer](https://www.tensorflow.org/text/tutorials/transformer)
*   [Conditional Random Field (CRF)](https://towardsdatascience.com/conditional-random-fields-explained-e5b8256da776)

## [6. Awesome Pinned Gists](/content/matchai/awesome-pinned-gists/README.md)

### External Services

*   [osu-box (⭐7)](https://github.com/AiverAiva/osu-box) - Update a pinned gist to display your osu! stats.

## [7. Free Programming Books (English, By Subjects)](/content/EbookFoundation/free-programming-books/books/free-programming-books-subjects/README.md)

### Algorithms & Data Structures

*   [Algorithmic Thinking](https://labuladong.gitbook.io/algo-en) - Donglai Fu

### Open Source Ecosystem

*   [500 lines or less (⭐29k)](https://github.com/aosabook/500lines) - Build from Source Code

### Quantum Computing

*   [Introduction to Quantum Information](https://www.gla.ac.uk/media/Media_344957_smxx.pdf) - Stephen M. Barnett (PDF)

---

- Prev: [Oct 08, 2023](/content/2023/10/08/README.md)
- Next: [Oct 06, 2023](/content/2023/10/06/README.md)