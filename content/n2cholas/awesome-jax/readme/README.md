# Awesome Jax Overview

JAX - A curated list of resources https://github.com/google/jax

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/n2cholas/awesome-jax/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 n2cholas/awesome-jax](https://github.com/n2cholas/awesome-jax) · ⭐ 757 · 🏷️ Computer Science

[ [Daily](/content/n2cholas/awesome-jax/README.md) / [Weekly](/content/n2cholas/awesome-jax/week/README.md) / Overview ]

---

<!--lint ignore double-link-->

# Awesome JAX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[<img src="https://raw.githubusercontent.com/google/jax/master/images/jax_logo_250px.png" alt="JAX Logo" align="right" height="100">](https://github.com/google/jax)

<!--lint ignore double-link-->

[JAX](https://github.com/google/jax) brings automatic differentiation and the [XLA compiler](https://www.tensorflow.org/xla) together through a [NumPy](https://numpy.org/)-like API for high performance machine learning research on accelerators like GPUs and TPUs.

<!--lint enable double-link-->

This is a curated list of awesome JAX libraries, projects, and other resources. Contributions are welcome!

## Contents

*   [Libraries](#libraries)
*   [Models and Projects](#models-and-projects)
*   [Videos](#videos)
*   [Papers](#papers)
*   [Tutorials and Blog Posts](#tutorials-and-blog-posts)
*   [Books](#books)
*   [Community](#community)

<a name="libraries" />

## Libraries

*   Neural Network Libraries
    *   [Flax](https://github.com/google/flax) - Centered on flexibility and clarity. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
    *   [Haiku](https://github.com/deepmind/dm-haiku) - Focused on simplicity, created by the authors of Sonnet at DeepMind. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
    *   [Objax](https://github.com/google/objax) - Has an object oriented design similar to PyTorch. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
    *   [Elegy](https://poets-ai.github.io/elegy/) - A High Level API for Deep Learning in JAX. Supports Flax, Haiku, and Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">
    *   [Trax](https://github.com/google/trax) - "Batteries included" deep learning library focused on providing solutions for common workloads. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
    *   [Jraph](https://github.com/deepmind/jraph) - Lightweight graph neural network library. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
    *   [Neural Tangents](https://github.com/google/neural-tangents) - High-level API for specifying neural networks of both finite and *infinite* width. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
    *   [HuggingFace](https://github.com/huggingface/transformers) - Ecosystem of pretrained Transformers for a wide range of natural language tasks (Flax). <img src="https://img.shields.io/github/stars/huggingface/transformers?style=social" align="center">
    *   [Equinox](https://github.com/patrick-kidger/equinox) - Callable PyTrees and filtered JIT/grad transformations => neural networks in JAX. <img src="https://img.shields.io/github/stars/patrick-kidger/equinox?style=social" align="center">
*   [NumPyro](https://github.com/pyro-ppl/numpyro) - Probabilistic programming based on the Pyro library. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
*   [Chex](https://github.com/deepmind/chex) - Utilities to write and test reliable JAX code. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
*   [Optax](https://github.com/deepmind/optax) - Gradient processing and optimization library. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
*   [RLax](https://github.com/deepmind/rlax) - Library for implementing reinforcement learning agents. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
*   [JAX, M.D.](https://github.com/google/jax-md) - Accelerated, differential molecular dynamics. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
*   [Coax](https://github.com/coax-dev/coax) - Turn RL papers into code, the easy way. <img src="https://img.shields.io/github/stars/coax-dev/coax?style=social" align="center">
*   [Distrax](https://github.com/deepmind/distrax) - Reimplementation of TensorFlow Probability, containing probability distributions and bijectors. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
*   [cvxpylayers](https://github.com/cvxgrp/cvxpylayers) - Construct differentiable convex optimization layers. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
*   [TensorLy](https://github.com/tensorly/tensorly) - Tensor learning made simple. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">
*   [NetKet](https://github.com/netket/netket) - Machine Learning toolbox for Quantum Physics. <img src="https://img.shields.io/github/stars/netket/netket?style=social" align="center">

<a name="new-libraries" />

### New Libraries

This section contains libraries that are well-made and useful, but have not necessarily been battle-tested by a large userbase yet.

*   Neural Network Libraries
    *   [FedJAX](https://github.com/google/fedjax) - Federated learning in JAX, built on Optax and Haiku. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
    *   [Equivariant MLP](https://github.com/mfinzi/equivariant-MLP) - Construct equivariant neural network layers. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
    *   [jax-resnet](https://github.com/n2cholas/jax-resnet/) - Implementations and checkpoints for ResNet variants in Flax. <img src="https://img.shields.io/github/stars/n2cholas/jax-resnet?style=social" align="center">
    *   [Parallax](https://github.com/srush/parallax) - Immutable Torch Modules for JAX. <img src="https://img.shields.io/github/stars/srush/parallax?style=social" align="center">
*   [jax-unirep](https://github.com/ElArkk/jax-unirep) - Library implementing the [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) for protein machine learning applications. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
*   [jax-flows](https://github.com/ChrisWaites/jax-flows) - Normalizing flows in JAX. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
*   [sklearn-jax-kernels](https://github.com/ExpectationMax/sklearn-jax-kernels) - `scikit-learn` kernel matrices using JAX. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
*   [jax-cosmo](https://github.com/DifferentiableUniverseInitiative/jax_cosmo) - Differentiable cosmology library. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
*   [efax](https://github.com/NeilGirdhar/efax) - Exponential Families in JAX. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
*   [mpi4jax](https://github.com/PhilipVinc/mpi4jax) - Combine MPI operations with your Jax code on CPUs and GPUs. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
*   [imax](https://github.com/4rtemi5/imax) - Image augmentations and transformations. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
*   [FlaxVision](https://github.com/rolandgvc/flaxvision) - Flax version of TorchVision. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
*   [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) - Probabilistic programming language based on program transformations.
*   [Optimal Transport Tools](https://github.com/google-research/ott) - Toolbox that bundles utilities to solve optimal transport problems.
*   [delta PV](https://github.com/romanodev/deltapv) - A photovoltaic simulator with automatic differentation. <img src="https://img.shields.io/github/stars/romanodev/deltapv?style=social" align="center">
*   [jaxlie](https://github.com/brentyi/jaxlie) - Lie theory library for rigid body transformations and optimization. <img src="https://img.shields.io/github/stars/brentyi/jaxlie?style=social" align="center">
*   [BRAX](https://github.com/google/brax) - Differentiable physics engine to simulate environments along with learning algorithms to train agents for these environments. <img src="https://img.shields.io/github/stars/google/brax?style=social" align="center">
*   [flaxmodels](https://github.com/matthias-wright/flaxmodels) - Pretrained models for Jax/Flax. <img src="https://img.shields.io/github/stars/matthias-wright/flaxmodels?style=social" align="center">
*   [CR.Sparse](https://github.com/carnotresearch/cr-sparse) - XLA accelerated algorithms for sparse representations and compressive sensing. <img src="https://img.shields.io/github/stars/carnotresearch/cr-sparse?style=social" align="center">
*   [exojax](https://github.com/HajimeKawahara/exojax) - Automatic differentiable spectrum modeling of exoplanets/brown dwarfs compatible to JAX. <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">
*   [JAXopt](https://github.com/google/jaxopt) - Hardware accelerated (GPU/TPU), batchable and differentiable optimizers in JAX. <img src="https://img.shields.io/github/stars/google/jaxopt?style=social" align="center">
*   [PIX](https://github.com/deepmind/dm_pix) - PIX is an image processing library in JAX, for JAX. <img src="https://img.shields.io/github/stars/deepmind/dm_pix?style=social" align="center">
*   [bayex](https://github.com/alonfnt/bayex) - Bayesian Optimization powered by JAX. <img src="https://img.shields.io/github/stars/alonfnt/bayex?style=social" align="center">
*   [JaxDF](https://github.com/ucl-bug/jaxdf) - Framework for differentiable simulators with arbitrary discretizations. <img src="https://img.shields.io/github/stars/ucl-bug/jaxdf?style=social" align="center">
*   [tree-math](https://github.com/google/tree-math) - Convert functions that operate on arrays into functions that operate on PyTrees. <img src="https://img.shields.io/github/stars/google/tree-math?style=social" align="center">
*   [jax-models](https://github.com/DarshanDeshpande/jax-models) - Implementations of research papers originally without code or code written with frameworks other than JAX. <img src="https://img.shields.io/github/stars/DarshanDeshpande/jax-modelsa?style=social" align="center">
*   [PGMax](https://github.com/vicariousinc/PGMax) - A framework for building discrete Probabilistic Graphical Models (PGM's) and running inference inference on them via JAX. <img src="https://img.shields.io/github/stars/vicariousinc/pgmax?style=social" align="center">
*   [EvoJAX](https://github.com/google/evojax) - Hardware-Accelerated Neuroevolution <img src="https://img.shields.io/github/stars/google/evojax?style=social" align="center">
*   [evosax](https://github.com/RobertTLange/evosax) - JAX-Based Evolution Strategies <img src="https://img.shields.io/github/stars/RobertTLange/evosax?style=social" align="center">
*   [SymJAX](https://github.com/SymJAX/SymJAX) - Symbolic CPU/GPU/TPU programming. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
*   [mcx](https://github.com/rlouf/mcx) - Express & compile probabilistic programs for performant inference. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
*   [Einshape](https://github.com/deepmind/einshape) - DSL-based reshaping library for JAX and other frameworks. <img src="https://img.shields.io/github/stars/deepmind/einshape?style=social" align="center">
*   [ALX](https://github.com/google-research/google-research/tree/master/alx) - Open-source library for distributed matrix factorization using Alternating Least Squares, more info in [*ALX: Large Scale Matrix Factorization on TPUs*](https://arxiv.org/abs/2112.02194).
*   [Diffrax](https://github.com/patrick-kidger/diffrax) - Numerical differential equation solvers in JAX. <img src="https://img.shields.io/github/stars/patrick-kidger/diffrax?style=social" align="center">
*   [tinygp](https://github.com/dfm/tinygp) - The *tiniest* of Gaussian process libraries in JAX. <img src="https://img.shields.io/github/stars/dfm/tinygp?style=social" align="center">
*   [gymnax](https://github.com/RobertTLange/gymnax) - Reinforcement Learning Environments with the well-known gym API. <img src="https://img.shields.io/github/stars/RobertTLange/gymnax?style=social" align="center">
*   [Mctx](https://github.com/deepmind/mctx) - Monte Carlo tree search algorithms in native JAX. <img src="https://img.shields.io/github/stars/deepmind/mctx?style=social" align="center">
*   [KFAC-JAX](https://github.com/deepmind/kfac-jax) - Second Order Optimization with Approximate Curvature for NNs. <img src="https://img.shields.io/github/stars/deepmind/kfac-jax?style=social" align="center">
*   [TF2JAX](https://github.com/deepmind/tf2jax) - Convert functions/graphs to JAX functions. <img src="https://img.shields.io/github/stars/deepmind/tf2jax?style=social" align="center">
*   [jwave](https://github.com/ucl-bug/jwave) - A library for differentiable acoustic simulations <img src="https://img.shields.io/github/stars/ucl-bug/jwave?style=social" align="center">
*   [GPJax](https://github.com/thomaspinder/GPJax) - Gaussian processes in JAX.
*   [Jumanji](https://github.com/instadeepai/jumanji) - A Suite of Industry-Driven Hardware-Accelerated RL Environments written in JAX. <img src="https://img.shields.io/github/stars/instadeepai/jumanji?style=social" align="center">
*   [Eqxvision](https://github.com/paganpasta/eqxvision) - Equinox version of Torchvision. <img src="https://img.shields.io/github/stars/paganpasta/eqxvision?style=social" align="center">
*   [JAXFit](https://github.com/dipolar-quantum-gases/jaxfit) - Accelerated curve fitting library for nonlinear least-squares problems (see [arXiv paper](https://arxiv.org/abs/2208.12187)). <img src="https://img.shields.io/github/stars/dipolar-quantum-gases/jaxfit?style=social" align="center">

<a name="models-and-projects" />

## Models and Projects

### JAX

*   [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) - Official implementation of [*Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains*](https://people.eecs.berkeley.edu/\~bmild/fourfeat).
*   [kalman-jax](https://github.com/AaltoML/kalman-jax) - Approximate inference for Markov (i.e., temporal) Gaussian processes using iterated Kalman filtering and smoothing.
*   [jaxns](https://github.com/Joshuaalbert/jaxns) - Nested sampling in JAX.
*   [Amortized Bayesian Optimization](https://github.com/google-research/google-research/tree/master/amortized_bo) - Code related to [*Amortized Bayesian Optimization over Discrete Spaces*](http://www.auai.org/uai2020/proceedings/329_main_paper.pdf).
*   [Accurate Quantized Training](https://github.com/google-research/google-research/tree/master/aqt) - Tools and libraries for running and analyzing neural network quantization experiments in JAX and Flax.
*   [BNN-HMC](https://github.com/google-research/google-research/tree/master/bnn_hmc) - Implementation for the paper [*What Are Bayesian Neural Network Posteriors Really Like?*](https://arxiv.org/abs/2104.14421).
*   [JAX-DFT](https://github.com/google-research/google-research/tree/master/jax_dft) - One-dimensional density functional theory (DFT) in JAX, with implementation of [*Kohn-Sham equations as regularizer: building prior knowledge into machine-learned physics*](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.036401).
*   [Robust Loss](https://github.com/google-research/google-research/tree/master/robust_loss_jax) - Reference code for the paper [*A General and Adaptive Robust Loss Function*](https://arxiv.org/abs/1701.03077).
*   [Symbolic Functionals](https://github.com/google-research/google-research/tree/master/symbolic_functionals) - Demonstration from [*Evolving symbolic density functionals*](https://arxiv.org/abs/2203.02540).
*   [TriMap](https://github.com/google-research/google-research/tree/master/trimap) - Official JAX implementation of [*TriMap: Large-scale Dimensionality Reduction Using Triplets*](https://arxiv.org/abs/1910.00204).

### Flax

*   [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) - Flax implementation of the Performer (linear transformer via FAVOR+) architecture.
*   [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) - Implementation of [*NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis*](http://www.matthewtancik.com/nerf) with multi-device GPU/TPU support.
*   [mip-NeRF](https://github.com/google/mipnerf) - Official implementation of [*Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields*](https://jonbarron.info/mipnerf).
*   [RegNeRF](https://github.com/google-research/google-research/tree/master/regnerf) - Official implementation of [*RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs*](https://m-niemeyer.github.io/regnerf/).
*   [Big Transfer (BiT)](https://github.com/google-research/big_transfer) - Implementation of [*Big Transfer (BiT): General Visual Representation Learning*](https://arxiv.org/abs/1912.11370).
*   [JAX RL](https://github.com/ikostrikov/jax-rl) - Implementations of reinforcement learning algorithms.
*   [gMLP](https://github.com/SauravMaheshkar/gMLP) - Implementation of [*Pay Attention to MLPs*](https://arxiv.org/abs/2105.08050).
*   [MLP Mixer](https://github.com/SauravMaheshkar/MLP-Mixer) - Minimal implementation of [*MLP-Mixer: An all-MLP Architecture for Vision*](https://arxiv.org/abs/2105.01601).
*   [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) - Implementation of [*Second Order Optimization Made Practical*](https://arxiv.org/abs/2002.09018).
*   [NesT](https://github.com/google-research/nested-transformer) - Official implementation of [*Aggregating Nested Transformers*](https://arxiv.org/abs/2105.12723).
*   [XMC-GAN](https://github.com/google-research/xmcgan_image_generation) - Official implementation of [*Cross-Modal Contrastive Learning for Text-to-Image Generation*](https://arxiv.org/abs/2101.04702).
*   [FNet](https://github.com/google-research/google-research/tree/master/f_net) - Official implementation of [*FNet: Mixing Tokens with Fourier Transforms*](https://arxiv.org/abs/2105.03824).
*   [GFSA](https://github.com/google-research/google-research/tree/master/gfsa) - Official implementation of [*Learning Graph Structure With A Finite-State Automaton Layer*](https://arxiv.org/abs/2007.04929).
*   [IPA-GNN](https://github.com/google-research/google-research/tree/master/ipagnn) - Official implementation of [*Learning to Execute Programs with Instruction Pointer Attention Graph Neural Networks*](https://arxiv.org/abs/2010.12621).
*   [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) - Collection of models and methods implemented in Flax.
*   [Protein LM](https://github.com/google-research/google-research/tree/master/protein_lm) - Implements BERT and autoregressive models for proteins, as described in [*Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences*](https://www.biorxiv.org/content/10.1101/622803v1.full) and [*ProGen: Language Modeling for Protein Generation*](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2).
*   [Slot Attention](https://github.com/google-research/google-research/tree/master/ptopk_patch_selection) - Reference implementation for [*Differentiable Patch Selection for Image Recognition*](https://arxiv.org/abs/2104.03059).
*   [Vision Transformer](https://github.com/google-research/vision_transformer) - Official implementation of [*An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale*](https://arxiv.org/abs/2010.11929).
*   [FID computation](https://github.com/matthias-wright/jax-fid) - Port of [mseitzer/pytorch-fid](https://github.com/mseitzer/pytorch-fid) to Flax.
*   [ARDM](https://github.com/google-research/google-research/tree/master/autoregressive_diffusion) - Official implementation of [*Autoregressive Diffusion Models*](https://arxiv.org/abs/2110.02037).
*   [D3PM](https://github.com/google-research/google-research/tree/master/d3pm) - Official implementation of [*Structured Denoising Diffusion Models in Discrete State-Spaces*](https://arxiv.org/abs/2107.03006).
*   [Gumbel-max Causal Mechanisms](https://github.com/google-research/google-research/tree/master/gumbel_max_causal_gadgets) - Code for [*Learning Generalized Gumbel-max Causal Mechanisms*](https://arxiv.org/abs/2111.06888), with extra code in [GuyLor/gumbel\_max\_causal\_gadgets\_part2](https://github.com/GuyLor/gumbel_max_causal_gadgets_part2).
*   [Latent Programmer](https://github.com/google-research/google-research/tree/master/latent_programmer) - Code for the ICML 2021 paper [*Latent Programmer: Discrete Latent Codes for Program Synthesis*](https://arxiv.org/abs/2012.00377).
*   [SNeRG](https://github.com/google-research/google-research/tree/master/snerg) - Official implementation of [*Baking Neural Radiance Fields for Real-Time View Synthesis*](https://phog.github.io/snerg).
*   [Spin-weighted Spherical CNNs](https://github.com/google-research/google-research/tree/master/spin_spherical_cnns) - Adaptation of [*Spin-Weighted Spherical CNNs*](https://arxiv.org/abs/2006.10731).
*   [VDVAE](https://github.com/google-research/google-research/tree/master/vdvae_flax) - Adaptation of [*Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images*](https://arxiv.org/abs/2011.10650), original code at [openai/vdvae](https://github.com/openai/vdvae).
*   [MUSIQ](https://github.com/google-research/google-research/tree/master/musiq) - Checkpoints and model inference code for the ICCV 2021 paper [*MUSIQ: Multi-scale Image Quality Transformer*](https://arxiv.org/abs/2108.05997)
*   [AQuaDem](https://github.com/google-research/google-research/tree/master/aquadem) - Official implementation of [*Continuous Control with Action Quantization from Demonstrations*](https://arxiv.org/abs/2110.10149).
*   [Combiner](https://github.com/google-research/google-research/tree/master/combiner) - Official implementation of [*Combiner: Full Attention Transformer with Sparse Computation Cost*](https://arxiv.org/abs/2107.05768).
*   [Dreamfields](https://github.com/google-research/google-research/tree/master/dreamfields) - Official implementation of the ICLR 2022 paper [*Progressive Distillation for Fast Sampling of Diffusion Models*](https://ajayj.com/dreamfields).
*   [GIFT](https://github.com/google-research/google-research/tree/master/gift) - Official implementation of [*Gradual Domain Adaptation in the Wild:When Intermediate Distributions are Absent*](https://arxiv.org/abs/2106.06080).
*   [Light Field Neural Rendering](https://github.com/google-research/google-research/tree/master/light_field_neural_rendering) - Official implementation of [*Light Field Neural Rendering*](https://arxiv.org/abs/2112.09687).
*   [Sharpened Cosine Similarity in JAX by Raphael Pisoni](https://colab.research.google.com/drive/1KUKFEMneQMS3OzPYnWZGkEnry3PdzCfn?usp=sharing) -  A JAX/Flax implementation of the Sharpened Cosine Similarity layer.

### Haiku

*   [AlphaFold](https://github.com/deepmind/alphafold) - Implementation of the inference pipeline of AlphaFold v2.0, presented in [*Highly accurate protein structure prediction with AlphaFold*](https://www.nature.com/articles/s41586-021-03819-2).
*   [Adversarial Robustness](https://github.com/deepmind/deepmind-research/tree/master/adversarial_robustness) - Reference code for [*Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples*](https://arxiv.org/abs/2010.03593) and [*Fixing Data Augmentation to Improve Adversarial Robustness*](https://arxiv.org/abs/2103.01946).
*   [Bootstrap Your Own Latent](https://github.com/deepmind/deepmind-research/tree/master/byol) - Implementation for the paper [*Bootstrap your own latent: A new approach to self-supervised Learning*](https://arxiv.org/abs/2006.07733).
*   [Gated Linear Networks](https://github.com/deepmind/deepmind-research/tree/master/gated_linear_networks) - GLNs are a family of backpropagation-free neural networks.
*   [Glassy Dynamics](https://github.com/deepmind/deepmind-research/tree/master/glassy_dynamics) - Open source implementation of the paper [*Unveiling the predictive power of static structure in glassy systems*](https://www.nature.com/articles/s41567-020-0842-8).
*   [MMV](https://github.com/deepmind/deepmind-research/tree/master/mmv) - Code for the models in [*Self-Supervised MultiModal Versatile Networks*](https://arxiv.org/abs/2006.16228).
*   [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) - Official Haiku implementation of [*NFNets*](https://arxiv.org/abs/2102.06171).
*   [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) - Normalizing flows with JAX.
*   [OGB-LSC](https://github.com/deepmind/deepmind-research/tree/master/ogb_lsc) - This repository contains DeepMind's entry to the [PCQM4M-LSC](https://ogb.stanford.edu/kddcup2021/pcqm4m/) (quantum chemistry) and [MAG240M-LSC](https://ogb.stanford.edu/kddcup2021/mag240m/) (academic graph)
    tracks of the [OGB Large-Scale Challenge](https://ogb.stanford.edu/kddcup2021/) (OGB-LSC).
*   [Persistent Evolution Strategies](https://github.com/google-research/google-research/tree/master/persistent_es) - Code used for the paper [*Unbiased Gradient Estimation in Unrolled Computation Graphs with Persistent Evolution Strategies*](http://proceedings.mlr.press/v139/vicol21a.html).
*   [Two Player Auction Learning](https://github.com/degregat/two-player-auctions) - JAX implementation of the paper [*Auction learning as a two-player game*](https://arxiv.org/abs/2006.05684).
*   [WikiGraphs](https://github.com/deepmind/deepmind-research/tree/master/wikigraphs) - Baseline code to reproduce results in [*WikiGraphs: A Wikipedia Text - Knowledge Graph Paired Datase*](https://aclanthology.org/2021.textgraphs-1.7).

### Trax

*   [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) - Implementation of the Reformer (efficient transformer) architecture.

### NumPyro

*   [lqg](https://github.com/RothkopfLab/lqg) - Official implementation of Bayesian inverse optimal control for linear-quadratic Gaussian problems from the paper [*Putting perception into action with inverse optimal control for continuous psychophysics*](https://elifesciences.org/articles/76635)

<a name="videos" />

## Videos

*   [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - JAX, its use at DeepMind, and discussion between engineers, scientists, and JAX core team.
*   [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) - Simple neural network from scratch in JAX.
*   [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) - JAX's core design, how it's powering new research, and how you can start using it.
*   [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) - Introduction to Bayesian modelling using NumPyro.
*   [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) - JAX intro presentation in [*Program Transformations for Machine Learning*](https://program-transformations.github.io) workshop.
*   [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) - Presentation of TPU host access with demo.
*   [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) - Tutorial created by Zico Kolter, David Duvenaud, and Matt Johnson with Colab notebooks avaliable in [*Deep Implicit Layers*](http://implicit-layers-tutorial.org).
*   [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) - A four part YouTube tutorial series with Colab notebooks that starts with Jax fundamentals and moves up to training with a data parallel approach on a v3-32 TPU Pod slice.
*   [JAX, Flax & Transformers 🤗](https://github.com/huggingface/transformers/blob/9160d81c98854df44b1d543ce5d65a6aa28444a2/examples/research_projects/jax-projects/README.md#talks) - 3 days of talks around JAX / Flax, Transformers, large-scale language modeling and other great topics.

<a name="papers" />

## Papers

This section contains papers focused on JAX (e.g. JAX-based library whitepapers, research on JAX, etc). Papers implemented in JAX are listed in the [Models/Projects](#projects) section.

<!--lint ignore awesome-list-item-->

*   [**Compiling machine learning programs via high-level tracing**. Roy Frostig, Matthew James Johnson, Chris Leary. *MLSys 2018*.](https://mlsys.org/Conferences/doc/2018/146.pdf) - White paper describing an early version of JAX, detailing how computation is traced and compiled.
*   [**JAX, M.D.: A Framework for Differentiable Physics**. Samuel S. Schoenholz, Ekin D. Cubuk. *NeurIPS 2020*.](https://arxiv.org/abs/1912.04232) - Introduces JAX, M.D., a differentiable physics library which includes simulation environments, interaction potentials, neural networks, and more.
*   [**Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization**. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. *arXiv 2020*.](https://arxiv.org/abs/2010.09063) - Uses JAX's JIT and VMAP to achieve faster differentially private than existing libraries.

<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

*   [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) - Describes the state of JAX and the JAX ecosystem at DeepMind.
*   [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - Neural network building blocks from scratch with the basic JAX operators.
*   [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) - Learn how to create a simple convolutional network with the Linen API by Flax and train it to recognize handwritten digits.
*   [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) - Compares Flax, Haiku, and Objax on the Kaggle flower classification challenge.
*   [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) - Introduction to both JAX and Meta-Learning.
*   [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) - Concise implementation of [RealNVP](https://arxiv.org/abs/1605.08803).
*   [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) - Tutorial on implementing path tracing.
*   [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) - Ensemble nets are a method of representing an ensemble of models as one single logical model.
*   [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) - Implements different methods for OOD detection.
*   [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) - Understand how autodiff works using JAX.
*   [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) - Showcases how to go from a PyTorch-like style of coding to a more Functional-style of coding.
*   [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) - Tutorial demonstrating the infrastructure required to provide custom ops in JAX.
*   [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) - Explores how JAX can power the next generation of scalable neuroevolution algorithms.
*   [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) - Demonstrates how to use JAX to perform inner-loss optimization with SGD and Momentum, outer-loss optimization with gradients, and outer-loss optimization using evolutionary strategies.
*   [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) - Walk through of implementing automatic differentiation variational inference (ADVI) easily and cleanly with JAX.
*   [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) - Trains a classification model robust to different combinations of input channels at different resolutions, then uses a genetic algorithm to decide the best combination for a particular loss.
*   [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/probml-notebooks/blob/main/notebooks/jax_intro.ipynb) - Colab that introduces various aspects of the language and applies them to simple ML problems.
*   [Writing an MCMC sampler in JAX by Jeremie Coullon](https://www.jeremiecoullon.com/2020/11/10/mcmcjax3ways/) - Tutorial on the different ways to write an MCMC sampler in JAX along with speed benchmarks.
*   [How to add a progress bar to JAX scans and loops by Jeremie Coullon](https://www.jeremiecoullon.com/2021/01/29/jax_progress_bar/) - Tutorial on how to add a progress bar to compiled loops in JAX using the `host_callback` module.
*   [Get started with JAX by Aleksa Gordić](https://github.com/gordicaleksa/get-started-with-JAX) - A series of notebooks and videos going from zero JAX knowledge to building neural networks in Haiku.
*   [Writing a Training Loop in JAX + FLAX by Saurav Maheshkar and Soumik Rakshit](https://wandb.ai/jax-series/simple-training-loop/reports/Writing-a-Training-Loop-in-JAX-FLAX--VmlldzoyMzA4ODEy) - A tutorial on writing a simple end-to-end training and evaluation pipeline in JAX, Flax and Optax.
*   [Implementing NeRF in JAX by Soumik Rakshit and Saurav Maheshkar](https://wandb.ai/wandb/nerf-jax/reports/Implementing-NeRF-in-JAX--VmlldzoxODA2NDk2?galleryTag=jax) - A tutorial on 3D volumetric rendering of scenes represented by Neural Radiance Fields in JAX.
*   [Deep Learning tutorials with JAX+Flax by Phillip Lippe](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/JAX/tutorial2/Introduction_to_JAX.html) - A series of notebooks explaining various deep learning concepts, from basics (e.g. intro to JAX/Flax, activiation functions) to recent advances (e.g., Vision Transformers, SimCLR), with translations to PyTorch.

<a name="books" />

## Books

*   [Jax in Action](https://www.manning.com/books/jax-in-action) - A hands-on guide to using JAX for deep learning and other mathematically-intensive applications.

<a name="community" />

## Community

*   [JAX GitHub Discussions](https://github.com/google/jax/discussions)
*   [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/n2cholas/awesome-jax/blob/main/readme.md/contributing.md) first.
