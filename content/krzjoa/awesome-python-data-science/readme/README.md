# Awesome Python Data Science Overview

Probably the best curated list of data science software in Python.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/krzjoa/awesome-python-data-science/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 krzjoa/awesome-python-data-science](https://github.com/krzjoa/awesome-python-data-science) · ⭐ 3.4K · 🏷️ Programming Languages

[ [Daily](/content/krzjoa/awesome-python-data-science/README.md) / [Weekly](/content/krzjoa/awesome-python-data-science/week/README.md) / Overview ]

---

<div align="center">
    <a href="https://krzjoa.github.io/awesome-python-data-science/"><img width="250" height="250" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/py-datascience.png" alt="pyds"></a>
    <br>
    <br>
    <br>
</div>

<h1 align="center">
    Awesome Python Data Science
</h1>
<div align="center"><a href="https://github.com/sindresorhus/awesome">
<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" border="0">
</a>
</div>
</br>

> Probably the best curated list of data science software in Python

## Contents

*   [Contents](#contents)

*   [Machine Learning](#machine-learning)
    *   [General Purpose Machine Learning](#general-purpose-machine-learning)
    *   [Gradient Boosting](#gradient-boosting)
    *   [Ensemble Methods](#ensemble-methods)
    *   [Imbalanced Datasets](#imbalanced-datasets)
    *   [Kernel Methods](#kernel-methods)

*   [Deep Learning](#deep-learning)
    *   [PyTorch](#pytorch)
    *   [TensorFlow](#tensorflow)
    *   [Keras](#keras)
    *   [JAX](#jax)
    *   [Others](#others)

*   [Automated Machine Learning](#automated-machine-learning)

*   [Natural Language Processing](#natural-language-processing)

*   [Computer Audition](#computer-audition)

*   [Computer Vision](#computer-vision)

*   [Time Series](#time-series)

*   [Reinforcement Learning](#reinforcement-learning)

*   [Graph Machine Learning](#graph-machine-learning)

*   [Graph Manipulation](#graph-manipulation)

*   [Learning-to-Rank & Recommender Systems](#learning-to-rank-&-recommender-systems)

*   [Probabilistic Graphical Models](#probabilistic-graphical-models)

*   [Probabilistic Methods](#probabilistic-methods)

*   [Model Explanation](#model-explanation)

*   [Optimization](#optimization)

*   [Genetic Programming](#genetic-programming)

*   [Feature Engineering](#feature-engineering)
    *   [General](#general)
    *   [Feature Selection](#feature-selection)

*   [Visualization](#visualization)
    *   [General Purposes](#general-purposes)
    *   [Interactive plots](#interactive-plots)
    *   [Map](#map)
    *   [Automatic Plotting](#automatic-plotting)
    *   [NLP](#nlp)

*   [Data Manipulation](#data-manipulation)
    *   [Data Frames](#data-frames)
    *   [Pipelines](#pipelines)
    *   [Data-centric AI](#data-centric-ai)
    *   [Synthetic Data](#synthetic-data)

*   [TabGAN (⭐565)](https://github.com/Diyago/Tabular-data-generation) - Synthetic tabular data generation using GANs, Diffusion Models, and LLMs. <img height="16" width="16" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

*   [Deployment](#deployment)

*   [Statistics](#statistics)

*   [Distributed Computing](#distributed-computing)

*   [Experimentation](#experimentation)

*   [Data Validation](#data-validation)

*   [Evaluation](#evaluation)

*   [Computations](#computations)

*   [Web Scraping](#web-scraping)

*   [Spatial Analysis](#spatial-analysis)

*   [Quantum Computing](#quantum-computing)

*   [Conversion](#conversion)

*   [Contributing](#contributing)

*   [License](#license)

## Machine Learning

### General Purpose Machine Learning

*   [SciPy](https://scipy.org/) - Fundamental algorithms for scientific computing in Python
*   [scikit-learn](https://scikit-learn.org/stable/) - Machine learning in Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [PyCaret (⭐9.7k)](https://github.com/pycaret/pycaret) - An open-source, low-code machine learning library in Python.  <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/R_big.png" alt="R inspired lib">
*   [Shogun (⭐3.1k)](https://github.com/shogun-toolbox/shogun) - Machine learning toolbox.
*   [xLearn (⭐3.1k)](https://github.com/aksnzhy/xlearn) - High Performance, Easy-to-use, and Scalable Machine Learning Package.
*   [cuML (⭐5.2k)](https://github.com/rapidsai/cuml) - RAPIDS Machine Learning Library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [modAL (⭐2.3k)](https://github.com/cosmic-cortex/modAL) - Modular active learning framework for Python3. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Sparkit-learn (⭐1.1k)](https://github.com/lensacom/sparkit-learn) - PySpark + scikit-learn = Sparkit-learn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/spark_big.png" alt="Apache Spark based">
*   [mlpack (⭐5.6k)](https://github.com/mlpack/mlpack) - A scalable C++ machine learning library (Python bindings).
*   [dlib (⭐14k)](https://github.com/davisking/dlib) - Toolkit for making real-world machine learning and data analysis applications in C++ (Python bindings).
*   [MLxtend (⭐5.1k)](https://github.com/rasbt/mlxtend) - Extension and helper modules for Python's data analysis and machine learning libraries. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [hyperlearn (⭐2.4k)](https://github.com/danielhanchen/hyperlearn) - 50%+ Faster, 50%+ less RAM usage, GPU support re-written Sklearn, Statsmodels. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Reproducible Experiment Platform (REP) (⭐700)](https://github.com/yandex/rep) - Machine Learning toolbox for Humans. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [scikit-multilearn (⭐956)](https://github.com/scikit-multilearn/scikit-multilearn) - Multi-label classification for python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [seqlearn (⭐705)](https://github.com/larsmans/seqlearn) - Sequence classification toolkit for Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [pystruct (⭐670)](https://github.com/pystruct/pystruct) - Simple structured learning framework for Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [sklearn-expertsys (⭐489)](https://github.com/tmadl/sklearn-expertsys) - Highly interpretable classifiers for scikit learn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [RuleFit (⭐443)](https://github.com/christophM/rulefit) - Implementation of the rulefit. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [metric-learn (⭐1.4k)](https://github.com/all-umass/metric-learn) - Metric learning algorithms in Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [pyGAM (⭐991)](https://github.com/dswah/pyGAM) - Generalized Additive Models in Python.
*   [causalml (⭐5.8k)](https://github.com/uber/causalml) - Uplift modeling and causal inference with machine learning algorithms. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

### Gradient Boosting

*   [XGBoost (⭐28k)](https://github.com/dmlc/xgboost) - Scalable, Portable, and Distributed Gradient Boosting. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [LightGBM (⭐18k)](https://github.com/Microsoft/LightGBM) - A fast, distributed, high-performance gradient boosting. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [CatBoost (⭐8.9k)](https://github.com/catboost/catboost) - An open-source gradient boosting on decision trees library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [ThunderGBM (⭐712)](https://github.com/Xtra-Computing/thundergbm) - Fast GBDTs and Random Forests on GPUs. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [NGBoost (⭐1.9k)](https://github.com/stanfordmlgroup/ngboost) - Natural Gradient Boosting for Probabilistic Prediction.
*   [TensorFlow Decision Forests (⭐695)](https://github.com/tensorflow/decision-forests) - A collection of state-of-the-art algorithms for the training, serving and interpretation of Decision Forest models in Keras. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="keras"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">

### Ensemble Methods

*   [ML-Ensemble](http://ml-ensemble.com/) - High performance ensemble learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Stacking (⭐230)](https://github.com/ikki407/stacking) - Simple and useful stacking library written in Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [stacked\_generalization (⭐119)](https://github.com/fukatani/stacked_generalization) - Library for machine learning stacking generalization. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [vecstack (⭐700)](https://github.com/vecxoz/vecstack) - Python package for stacking (machine learning technique). <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

### Imbalanced Datasets

*   [imbalanced-learn (⭐7.1k)](https://github.com/scikit-learn-contrib/imbalanced-learn) - Module to perform under-sampling and over-sampling with various techniques. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [imbalanced-algorithms (⭐241)](https://github.com/dialnd/imbalanced-algorithms) - Python-based implementations of algorithms for learning on imbalanced data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">

### Kernel Methods

*   [pyFM (⭐926)](https://github.com/coreylynch/pyFM) - Factorization machines in python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [fastFM (⭐1.1k)](https://github.com/ibayer/fastFM) - A library for Factorization Machines. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [tffm (⭐779)](https://github.com/geffy/tffm) - TensorFlow implementation of an arbitrary order Factorization Machine. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [liquidSVM (⭐71)](https://github.com/liquidSVM/liquidSVM) - An implementation of SVMs.
*   [scikit-rvm (⭐236)](https://github.com/JamesRitchie/scikit-rvm) - Relevance Vector Machine implementation using the scikit-learn API. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [ThunderSVM (⭐1.6k)](https://github.com/Xtra-Computing/thundersvm) - A fast SVM Library on GPUs and CPUs. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">

## Deep Learning

### PyTorch

*   [PyTorch (⭐99k)](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [pytorch-lightning (⭐31k)](https://github.com/Lightning-AI/lightning) - PyTorch Lightning is just organized PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [ignite (⭐4.8k)](https://github.com/pytorch/ignite) - High-level library to help with training neural networks in PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [skorch (⭐6.2k)](https://github.com/dnouri/skorch) - A scikit-learn compatible neural network library that wraps PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Catalyst (⭐3.4k)](https://github.com/catalyst-team/catalyst) - High-level utils for PyTorch DL & RL research. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [ChemicalX (⭐773)](https://github.com/AstraZeneca/chemicalx) - A PyTorch-based deep learning library for drug pair scoring. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">

### TensorFlow

*   [TensorFlow (⭐195k)](https://github.com/tensorflow/tensorflow) - Computation using data flow graphs for scalable machine learning by Google. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [TensorLayer (⭐7.4k)](https://github.com/zsdonghao/tensorlayer) - Deep Learning and Reinforcement Learning Library for Researcher and Engineer. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [TFLearn (⭐9.6k)](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API for TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [Sonnet (⭐9.9k)](https://github.com/deepmind/sonnet) - TensorFlow-based neural network library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [tensorpack (⭐6.3k)](https://github.com/ppwwyyxx/tensorpack) - A Neural Net Training Interface on TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [tfdeploy (⭐355)](https://github.com/riga/tfdeploy) - Deploy TensorFlow graphs for fast evaluation and export to TensorFlow-less environments running numpy. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [tensorflow-upstream (⭐700)](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) - TensorFlow ROCm port. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/amd_big.png" alt="Possible to run on AMD GPU">
*   [TensorFlow Fold (⭐1.8k)](https://github.com/tensorflow/fold) - Deep learning with dynamic computation graphs in TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [TensorLight (⭐11)](https://github.com/bsautermeister/tensorlight) - A high-level framework for TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [Mesh TensorFlow (⭐1.6k)](https://github.com/tensorflow/mesh) - Model Parallelism Made Easier. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [Ludwig (⭐12k)](https://github.com/uber/ludwig) - A toolbox that allows one to train and test deep learning models without the need to write code. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">

### JAX

*   [JAX (⭐35k)](https://github.com/google/jax) - Composable transformations of Python+NumPy programs: differentiate, vectorize, JIT to GPU/TPU, and more.
*   [FLAX (⭐7.1k)](https://github.com/google/flax) - A neural network library for JAX that is designed for flexibility.
*   [Optax (⭐2.2k)](https://github.com/google-deepmind/optax) - A gradient processing and optimization library for JAX.

### Keras

*   [Keras](https://keras.io) - A high-level neural networks API running on top of TensorFlow.  <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [keras-contrib (⭐1.6k)](https://github.com/keras-team/keras-contrib) - Keras community contributions. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [Hyperas (⭐2.2k)](https://github.com/maxpumperla/hyperas) - Keras + Hyperopt: A straightforward wrapper for a convenient hyperparameter. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [Elephas (⭐1.6k)](https://github.com/maxpumperla/elephas) - Distributed Deep learning with Keras & Spark. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [qkeras (⭐577)](https://github.com/google/qkeras) - A quantization deep learning library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">

### Others

*   [transformers (⭐159k)](https://github.com/huggingface/transformers) - State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [Tangent (⭐2.3k)](https://github.com/google/tangent) - Source-to-Source Debuggable Derivatives in Pure Python.
*   [autograd (⭐7.5k)](https://github.com/HIPS/autograd) - Efficiently computes derivatives of numpy code.
*   [Caffe (⭐35k)](https://github.com/BVLC/caffe) - A fast open framework for deep learning.
*   [nnabla (⭐2.8k)](https://github.com/sony/nnabla) - Neural Network Libraries by Sony.

## Automated Machine Learning

*   [auto-sklearn (⭐8.1k)](https://github.com/automl/auto-sklearn) - An AutoML toolkit and a drop-in replacement for a scikit-learn estimator. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Auto-PyTorch (⭐2.5k)](https://github.com/automl/Auto-PyTorch) - Automatic architecture search and hyperparameter optimization for PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [AutoKeras (⭐9.3k)](https://github.com/keras-team/autokeras) - AutoML library for deep learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [AutoGluon (⭐10k)](https://github.com/awslabs/autogluon) - AutoML for Image, Text, Tabular, Time-Series, and MultiModal Data.
*   [TPOT (⭐10k)](https://github.com/rhiever/tpot) - AutoML tool that optimizes machine learning pipelines using genetic programming. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [MLBox (⭐1.5k)](https://github.com/AxeldeRomblay/MLBox) - A powerful Automated Machine Learning python library.

## Natural Language Processing

*   [torchtext (⭐3.6k)](https://github.com/pytorch/text) - Data loaders and abstractions for text and NLP. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [KerasNLP (⭐972)](https://github.com/keras-team/keras-nlp) - Modular Natural Language Processing workflows with Keras. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras based/compatible">
*   [spaCy](https://spacy.io/) - Industrial-Strength Natural Language Processing.
*   [NLTK (⭐15k)](https://github.com/nltk/nltk) -  Modules, data sets, and tutorials supporting research and development in Natural Language Processing.
*   [CLTK (⭐903)](https://github.com/cltk/cltk) - The Classical Language Toolkik.
*   [gensim](https://radimrehurek.com/gensim/) - Topic Modelling for Humans.
*   [pyMorfologik (⭐18)](https://github.com/dmirecki/pyMorfologik) - Python binding for <a href="https://github.com/morfologik/morfologik-stemming">Morfologik</a>.
*   [skift (⭐233)](https://github.com/shaypal5/skift) - Scikit-learn wrappers for Python fastText. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Phonemizer (⭐1.5k)](https://github.com/bootphon/phonemizer) - Simple text-to-phonemes converter for multiple languages.
*   [flair (⭐14k)](https://github.com/zalandoresearch/flair) - Very simple framework for state-of-the-art NLP.

## Computer Audition

*   [torchaudio (⭐2.9k)](https://github.com/pytorch/audio) - An audio library for PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [librosa (⭐8.3k)](https://github.com/librosa/librosa) - Python library for audio and music analysis.
*   [Yaafe (⭐248)](https://github.com/Yaafe/Yaafe) - Audio features extraction.
*   [aubio (⭐3.7k)](https://github.com/aubio/aubio) - A library for audio and music analysis.
*   [Essentia (⭐3.5k)](https://github.com/MTG/essentia) - Library for audio and music analysis, description, and synthesis.
*   [LibXtract (⭐231)](https://github.com/jamiebullock/LibXtract) - A simple, portable, lightweight library of audio feature extraction functions.
*   [Marsyas (⭐424)](https://github.com/marsyas/marsyas) - Music Analysis, Retrieval, and Synthesis for Audio Signals.
*   [muda (⭐237)](https://github.com/bmcfee/muda) - A library for augmenting annotated audio data.
*   [madmom (⭐1.6k)](https://github.com/CPJKU/madmom) - Python audio and music signal processing library.

## Computer Vision

*   [torchvision (⭐18k)](https://github.com/pytorch/vision) - Datasets, Transforms, and Models specific to Computer Vision. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [PyTorch3D (⭐9.8k)](https://github.com/facebookresearch/pytorch3d) - PyTorch3D is FAIR's library of reusable components for deep learning with 3D data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [KerasCV (⭐1.1k)](https://github.com/keras-team/keras-cv) - Industry-strength Computer Vision workflows with Keras. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="MXNet based">
*   [OpenCV (⭐87k)](https://github.com/opencv/opencv) - Open Source Computer Vision Library.
*   [Decord (⭐2.5k)](https://github.com/dmlc/decord) - An efficient video loader for deep learning with smart shuffling that's super easy to digest.
*   [MMEngine (⭐1.5k)](https://github.com/open-mmlab/mmengine) - OpenMMLab Foundational Library for Training Deep Learning Models. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [scikit-image (⭐6.5k)](https://github.com/scikit-image/scikit-image) - Image Processing SciKit (Toolbox for SciPy).
*   [imgaug (⭐15k)](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments.
*   [imgaug\_extension](https://github.com/cadenai/imgaug_extension) - Additional augmentations for imgaug.
*   [Augmentor (⭐5.1k)](https://github.com/mdbloice/Augmentor) - Image augmentation library in Python for machine learning.
*   [albumentations (⭐15k)](https://github.com/albu/albumentations) - Fast image augmentation library and easy-to-use wrapper around other libraries.
*   [LAVIS (⭐11k)](https://github.com/salesforce/LAVIS) - A One-stop Library for Language-Vision Intelligence.

## Time Series

*   [sktime (⭐9.7k)](https://github.com/alan-turing-institute/sktime) - A unified framework for machine learning with time series. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [skforecast (⭐1.5k)](https://github.com/JoaquinAmatRodrigo/skforecast) - Time series forecasting with machine learning models
*   [darts (⭐9.3k)](https://github.com/unit8co/darts) - A python library for easy manipulation and forecasting of time series.
*   [statsforecast (⭐4.7k)](https://github.com/Nixtla/statsforecast) - Lightning fast forecasting with statistical and econometric models.
*   [mlforecast (⭐1.2k)](https://github.com/Nixtla/mlforecast) - Scalable machine learning-based time series forecasting.
*   [neuralforecast (⭐4k)](https://github.com/Nixtla/neuralforecast) - Scalable machine learning-based time series forecasting.
*   [tslearn (⭐3.1k)](https://github.com/rtavenar/tslearn) - Machine learning toolkit dedicated to time-series data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [tick (⭐541)](https://github.com/X-DataInitiative/tick) - Module for statistical learning, with a particular emphasis on time-dependent modeling.  <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [greykite (⭐1.9k)](https://github.com/linkedin/greykite) - A flexible, intuitive, and fast forecasting library next.
*   [Prophet (⭐20k)](https://github.com/facebook/prophet) - Automatic Forecasting Procedure.
*   [PyFlux (⭐2.1k)](https://github.com/RJT1990/pyflux) - Open source time series library for Python.
*   [bayesloop (⭐169)](https://github.com/christophmark/bayesloop) - Probabilistic programming framework that facilitates objective model selection for time-varying parameter models.
*   [luminol (⭐1.2k)](https://github.com/linkedin/luminol) - Anomaly Detection and Correlation library.
*   [dateutil](https://dateutil.readthedocs.io/en/stable/) - Powerful extensions to the standard datetime module
*   [maya (⭐3.4k)](https://github.com/timofurrer/maya) - makes it very easy to parse a string and for changing timezones
*   [Chaos Genius (⭐775)](https://github.com/chaos-genius/chaos_genius) - ML powered analytics engine for outlier/anomaly detection and root cause analysis

## Reinforcement Learning

*   [Gymnasium (⭐12k)](https://github.com/Farama-Foundation/Gymnasium) - An API standard for single-agent reinforcement learning environments, with popular reference environments and related utilities (formerly [Gym (⭐37k)](https://github.com/openai/gym)).
*   [PettingZoo (⭐3.4k)](https://github.com/Farama-Foundation/PettingZoo) - An API standard for multi-agent reinforcement learning environments, with popular reference environments and related utilities.
*   [MAgent2 (⭐326)](https://github.com/Farama-Foundation/MAgent2) - An engine for high performance multi-agent environments with very large numbers of agents, along with a set of reference environments.
*   [Stable Baselines3 (⭐13k)](https://github.com/DLR-RM/stable-baselines3) - A set of improved implementations of reinforcement learning algorithms based on OpenAI Baselines.
*   [Shimmy (⭐205)](https://github.com/Farama-Foundation/Shimmy) - An API conversion tool for popular external reinforcement learning environments.
*   [EnvPool (⭐1.3k)](https://github.com/sail-sg/envpool) - C++-based high-performance parallel environment execution engine (vectorized env) for general RL environments.
*   [RLlib](https://ray.readthedocs.io/en/latest/rllib.html) - Scalable Reinforcement Learning.
*   [Tianshou (⭐10k)](https://github.com/thu-ml/tianshou/#comprehensive-functionality) - An elegant PyTorch deep reinforcement learning library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Acme (⭐4k)](https://github.com/google-deepmind/acme) - A library of reinforcement learning components and agents.
*   [Catalyst-RL (⭐48)](https://github.com/catalyst-team/catalyst-rl) - PyTorch framework for RL research. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [d3rlpy (⭐1.7k)](https://github.com/takuseno/d3rlpy) - An offline deep reinforcement learning library.
*   [DI-engine (⭐3.6k)](https://github.com/opendilab/DI-engine) - OpenDILab Decision AI Engine. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [TF-Agents (⭐3k)](https://github.com/tensorflow/agents) - A library for Reinforcement Learning in TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">
*   [TensorForce (⭐3.3k)](https://github.com/reinforceio/tensorforce) - A TensorFlow library for applied reinforcement learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">
*   [TRFL (⭐3.1k)](https://github.com/deepmind/trfl) - TensorFlow Reinforcement Learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [Dopamine (⭐11k)](https://github.com/google/dopamine) - A research framework for fast prototyping of reinforcement learning algorithms.
*   [keras-rl (⭐5.6k)](https://github.com/keras-rl/keras-rl) - Deep Reinforcement Learning for Keras. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [garage (⭐2.1k)](https://github.com/rlworkgroup/garage) - A toolkit for reproducible reinforcement learning research.
*   [Horizon (⭐3.7k)](https://github.com/facebookresearch/Horizon) - A platform for Applied Reinforcement Learning.
*   [rlpyt (⭐2.3k)](https://github.com/astooke/rlpyt) - Reinforcement Learning in PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [cleanrl (⭐9.5k)](https://github.com/vwxyzjn/cleanrl) - High-quality single file implementation of Deep Reinforcement Learning algorithms with research-friendly features (PPO, DQN, C51, DDPG, TD3, SAC, PPG).
*   [Machin (⭐418)](https://github.com/iffiX/machin) -  A reinforcement library designed for pytorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [SKRL (⭐1k)](https://github.com/Toni-SM/skrl) - Modular reinforcement learning library (on PyTorch and JAX) with support for NVIDIA Isaac Gym, Isaac Orbit and Omniverse Isaac Gym. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Imitation (⭐1.7k)](https://github.com/HumanCompatibleAI/imitation) - Clean PyTorch implementations of imitation and reward learning algorithms. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">

## Graph Machine Learning

*   [pytorch\_geometric (⭐24k)](https://github.com/rusty1s/pytorch_geometric) - Geometric Deep Learning Extension Library for PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [pytorch\_geometric\_temporal (⭐3k)](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) - Temporal Extension Library for PyTorch Geometric. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [PyTorch Geometric Signed Directed (⭐147)](https://github.com/SherylHYX/pytorch_geometric_signed_directed) -  A signed/directed graph neural network extension library for PyTorch Geometric. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [dgl (⭐14k)](https://github.com/dmlc/dgl) - Python package built to ease deep learning on graph, on top of existing DL frameworks. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/mxnet_big.png" alt="MXNet based">
*   [GRAPE (⭐626)](https://github.com/AnacletoLAB/grape/tree/main) - GRAPE is a Rust/Python Graph Representation Learning library for Predictions and Evaluations
*   [Spektral (⭐2.4k)](https://github.com/danielegrattarola/spektral) - Deep learning on graphs. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [StellarGraph (⭐3k)](https://github.com/stellargraph/stellargraph) - Machine Learning on Graphs. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">  <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [Graph Nets (⭐5.4k)](https://github.com/google-deepmind/graph_nets) - Build Graph Nets in Tensorflow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">
*   [TensorFlow GNN (⭐1.5k)](https://github.com/tensorflow/gnn) - A library to build Graph Neural Networks on the TensorFlow platform. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">
*   [Auto Graph Learning (⭐1.1k)](https://github.com/THUMNLab/AutoGL) -An autoML framework & toolkit for machine learning on graphs.
*   [PyTorch-BigGraph (⭐3.5k)](https://github.com/facebookresearch/PyTorch-BigGraph) - Generate embeddings from large-scale graph-structured data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Auto Graph Learning (⭐1.1k)](https://github.com/THUMNLab/AutoGL) - An autoML framework & toolkit for machine learning on graphs.
*   [Karate Club (⭐2.3k)](https://github.com/benedekrozemberczki/karateclub) - An unsupervised machine learning library for graph-structured data.
*   [Little Ball of Fur (⭐713)](https://github.com/benedekrozemberczki/littleballoffur) - A library for sampling graph structured data.
*   [GreatX (⭐89)](https://github.com/EdisonLeeeee/GreatX) - A graph reliability toolbox based on PyTorch and PyTorch Geometric (PyG). <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [Jraph (⭐1.5k)](https://github.com/google-deepmind/jraph) - A Graph Neural Network Library in Jax.
*   [TRL (⭐18k)](https://github.com/huggingface/trl) - Train transformer language models with reinforcement learning.
*   [Cleora (⭐529)](https://github.com/BaseModelAI/cleora) - The Graph Embedding Engine.

## Graph Manipulation

*   [Networkx (⭐17k)](https://github.com/networkx/networkx) - Network Analysis in Python.
*   [Rustworkx (⭐1.6k)](https://github.com/Qiskit/rustworkx) - A high performance Python graph library implemented in Rust.
*   [graph-tool](https://graph-tool.skewed.de/) - an efficient Python module for manipulation and statistical analysis of graphs (a.k.a. networks).
*   [igraph (⭐1.4k)](https://github.com/igraph/python-igraph) - Python interface for igraph.

## Learning-to-Rank & Recommender Systems

*   [LightFM (⭐5.1k)](https://github.com/lyst/lightfm) - A Python implementation of LightFM, a hybrid recommendation algorithm.
*   [Spotlight](https://maciejkula.github.io/spotlight/) - Deep recommender models using PyTorch.
*   [Surprise (⭐6.8k)](https://github.com/NicolasHug/Surprise) - A Python scikit for building and analyzing recommender systems.
*   [RecBole (⭐4.4k)](https://github.com/RUCAIBox/RecBole) - A unified, comprehensive and efficient recommendation library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [allRank (⭐997)](https://github.com/allegro/allRank) - allRank is a framework for training learning-to-rank neural models based on PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [TensorFlow Recommenders (⭐2k)](https://github.com/tensorflow/recommenders) - A library for building recommender system models using TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="Keras compatible">
*   [TensorFlow Ranking (⭐2.8k)](https://github.com/tensorflow/ranking) - Learning to Rank in TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="TensorFlow">

## Probabilistic Graphical Models

*   [pomegranate (⭐3.5k)](https://github.com/jmschrei/pomegranate) - Probabilistic and graphical models for Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [pgmpy (⭐3.2k)](https://github.com/pgmpy/pgmpy) - A python library for working with Probabilistic Graphical Models.
*   [pyAgrum](https://agrum.gitlab.io/) - A GRaphical Universal Modeler.

## Probabilistic Methods

*   [pyro (⭐9k)](https://github.com/uber/pyro) - A flexible, scalable deep probabilistic programming library built on PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [PyMC (⭐9.6k)](https://github.com/pymc-devs/pymc) - Bayesian Stochastic Modelling in Python.
*   [ZhuSuan](https://zhusuan.readthedocs.io/en/latest/) - Bayesian Deep Learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [GPflow](https://gpflow.readthedocs.io/en/latest/?badge=latest) - Gaussian processes in TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [InferPy (⭐148)](https://github.com/PGM-Lab/InferPy) - Deep Probabilistic Modelling Made Easy.  <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [PyStan (⭐364)](https://github.com/stan-dev/pystan) - Bayesian inference using the No-U-Turn sampler (Python interface).
*   [sklearn-bayes (⭐523)](https://github.com/AmazaspShumik/sklearn-bayes) - Python package for Bayesian Machine Learning with scikit-learn API. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [skpro (⭐320)](https://github.com/alan-turing-institute/skpro) - Supervised domain-agnostic prediction framework for probabilistic modelling by [The Alan Turing Institute](https://www.turing.ac.uk/). <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [PyVarInf (⭐362)](https://github.com/ctallec/pyvarinf) - Bayesian Deep Learning methods with Variational Inference for PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [emcee (⭐1.6k)](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC.
*   [hsmmlearn (⭐87)](https://github.com/jvkersch/hsmmlearn) - A library for hidden semi-Markov models with explicit durations.
*   [pyhsmm (⭐575)](https://github.com/mattjj/pyhsmm) - Bayesian inference in HSMMs and HMMs.
*   [GPyTorch (⭐3.9k)](https://github.com/cornellius-gp/gpytorch) - A highly efficient and modular implementation of Gaussian Processes in PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [sklearn-crfsuite (⭐435)](https://github.com/TeamHG-Memex/sklearn-crfsuite) - A scikit-learn-inspired API for CRFsuite. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

## Model Explanation

*   [dalex (⭐1.5k)](https://github.com/ModelOriented/DALEX) - moDel Agnostic Language for Exploration and explanation. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"><img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/R_big.png" alt="R inspired/ported lib">
*   [Shapley (⭐224)](https://github.com/benedekrozemberczki/shapley) - A data-driven framework to quantify the value of classifiers in a machine learning ensemble.
*   [Alibi (⭐2.6k)](https://github.com/SeldonIO/alibi) - Algorithms for monitoring and explaining machine learning models.
*   [anchor (⭐813)](https://github.com/marcotcr/anchor) - Code for "High-Precision Model-Agnostic Explanations" paper.
*   [aequitas (⭐757)](https://github.com/dssg/aequitas) - Bias and Fairness Audit Toolkit.
*   [Contrastive Explanation (⭐45)](https://github.com/MarcelRobeer/ContrastiveExplanation) - Contrastive Explanation (Foil Trees). <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [yellowbrick (⭐4.4k)](https://github.com/DistrictDataLabs/yellowbrick) - Visual analysis and diagnostic tools to facilitate machine learning model selection. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [scikit-plot (⭐2.4k)](https://github.com/reiinakano/scikit-plot) - An intuitive library to add plotting functionality to scikit-learn objects. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [shap (⭐25k)](https://github.com/slundberg/shap) - A unified approach to explain the output of any machine learning model. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [InterpretML (⭐6.8k)](https://github.com/interpretml/interpret) - InterpretML implements the Explainable Boosting Machine (EBM), a modern, fully interpretable machine learning model based on Generalized Additive Models (GAMs). This open-source package also provides visualization tools for EBMs, other glass-box models, and black-box explanations. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [ELI5 (⭐2.8k)](https://github.com/TeamHG-Memex/eli5) - A library for debugging/inspecting machine learning classifiers and explaining their predictions.
*   [Lime (⭐12k)](https://github.com/marcotcr/lime) - Explaining the predictions of any machine learning classifier. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [FairML (⭐365)](https://github.com/adebayoj/fairml) - FairML is a python toolbox auditing the machine learning models for bias. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [L2X (⭐124)](https://github.com/Jianbo-Lab/L2X) - Code for replicating the experiments in the paper *Learning to Explain: An Information-Theoretic Perspective on Model Interpretation*.
*   [PDPbox (⭐861)](https://github.com/SauceCat/PDPbox) - Partial dependence plot toolbox.
*   [PyCEbox (⭐163)](https://github.com/AustinRochford/PyCEbox) - Python Individual Conditional Expectation Plot Toolbox.
*   [Skater](https://github.com/datascienceinc/Skater) - Python Library for Model Interpretation.
*   [model-analysis (⭐1.3k)](https://github.com/tensorflow/model-analysis) - Model analysis tools for TensorFlow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [themis-ml (⭐126)](https://github.com/cosmicBboy/themis-ml) - A library that implements fairness-aware machine learning algorithms. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [treeinterpreter (⭐761)](https://github.com/andosa/treeinterpreter) - Interpreting scikit-learn's decision tree and random forest predictions. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [AI Explainability 360 (⭐1.8k)](https://github.com/IBM/AIX360) - Interpretability and explainability of data and machine learning models.
*   [Auralisation (⭐42)](https://github.com/keunwoochoi/Auralisation) - Auralisation of learned features in CNN (for audio).
*   [CapsNet-Visualization (⭐396)](https://github.com/bourdakos1/CapsNet-Visualization) - A visualization of the CapsNet layers to better understand how it works.
*   [lucid (⭐4.7k)](https://github.com/tensorflow/lucid) - A collection of infrastructure and tools for research in neural network interpretability.
*   [Netron (⭐33k)](https://github.com/lutzroeder/Netron) - Visualizer for deep learning and machine learning models (no Python code, but visualizes models from most Python Deep Learning frameworks).
*   [FlashLight](https://github.com/dlguys/flashlight) - Visualization Tool for your NeuralNetwork.
*   [tensorboard-pytorch (⭐8k)](https://github.com/lanpa/tensorboard-pytorch) - Tensorboard for PyTorch (and chainer, mxnet, numpy, ...).

## Genetic Programming

*   [gplearn (⭐1.8k)](https://github.com/trevorstephens/gplearn) - Genetic Programming in Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [PyGAD (⭐2.2k)](https://github.com/ahmedfgad/GeneticAlgorithmPython) - Genetic Algorithm in Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/keras_big.png" alt="keras">
*   [DEAP (⭐6.4k)](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python.
*   [karoo\_gp (⭐164)](https://github.com/kstaats/karoo_gp) - A Genetic Programming platform for Python with GPU support. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [monkeys (⭐125)](https://github.com/hchasestevens/monkeys) - A strongly-typed genetic programming framework for Python.
*   [sklearn-genetic (⭐325)](https://github.com/manuel-calzolari/sklearn-genetic) - Genetic feature selection module for scikit-learn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

<a name="opt"></a>

## Optimization

*   [Optuna (⭐14k)](https://github.com/optuna/optuna) - A hyperparameter optimization framework.
*   [pymoo (⭐2.8k)](https://github.com/anyoptimization/pymoo) - Multi-objective Optimization in Python.
*   [pycma (⭐1.3k)](https://github.com/CMA-ES/pycma?tab=readme-ov-file) - Python implementation of CMA-ES.
*   [Spearmint (⭐1.6k)](https://github.com/HIPS/Spearmint) - Bayesian optimization.
*   [BoTorch (⭐3.5k)](https://github.com/pytorch/botorch) - Bayesian optimization in PyTorch. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pytorch_big2.png" alt="PyTorch based/compatible">
*   [scikit-opt (⭐6.4k)](https://github.com/guofei9987/scikit-opt) - Heuristic Algorithms for optimization.
*   [sklearn-genetic-opt (⭐357)](https://github.com/rodrigo-arenas/Sklearn-genetic-opt) - Hyperparameters tuning and feature selection using evolutionary algorithms. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [SMAC3 (⭐1.2k)](https://github.com/automl/SMAC3) - Sequential Model-based Algorithm Configuration.
*   [Optunity (⭐425)](https://github.com/claesenm/optunity) - Is a library containing various optimizers for hyperparameter tuning.
*   [hyperopt (⭐7.6k)](https://github.com/hyperopt/hyperopt) - Distributed Asynchronous Hyperparameter Optimization in Python.
*   [hyperopt-sklearn (⭐1.6k)](https://github.com/hyperopt/hyperopt-sklearn) - Hyper-parameter optimization for sklearn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [sklearn-deap (⭐772)](https://github.com/rsteca/sklearn-deap) - Use evolutionary algorithms instead of gridsearch in scikit-learn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [sigopt\_sklearn (⭐75)](https://github.com/sigopt/sigopt_sklearn) - SigOpt wrappers for scikit-learn methods. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Bayesian Optimization (⭐8.6k)](https://github.com/fmfn/BayesianOptimization) - A Python implementation of global optimization with gaussian processes.
*   [SafeOpt (⭐150)](https://github.com/befelix/SafeOpt) - Safe Bayesian Optimization.
*   [scikit-optimize (⭐2.8k)](https://github.com/scikit-optimize/scikit-optimize) - Sequential model-based optimization with a `scipy.optimize` interface.
*   [Solid (⭐584)](https://github.com/100/Solid) - A comprehensive gradient-free optimization framework written in Python.
*   [PySwarms (⭐1.4k)](https://github.com/ljvmiranda921/pyswarms) - A research toolkit for particle swarm optimization in Python.
*   [Platypus (⭐647)](https://github.com/Project-Platypus/Platypus) - A Free and Open Source Python Library for Multiobjective Optimization.
*   [GPflowOpt (⭐274)](https://github.com/GPflow/GPflowOpt) - Bayesian Optimization using GPflow. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [POT (⭐2.8k)](https://github.com/rflamary/POT) - Python Optimal Transport library.
*   [Talos (⭐1.6k)](https://github.com/autonomio/talos) - Hyperparameter Optimization for Keras Models.
*   [nlopt (⭐2.2k)](https://github.com/stevengj/nlopt) - Library for nonlinear optimization (global and local, constrained or unconstrained).
*   [OR-Tools](https://developers.google.com/optimization) - An open-source software suite for optimization by Google; provides a unified programming interface to a half dozen solvers: SCIP, GLPK, GLOP, CP-SAT, CPLEX, and Gurobi.

## Feature Engineering

### General

*   [Featuretools (⭐7.6k)](https://github.com/Featuretools/featuretools) - Automated feature engineering.
*   [Feature Engine (⭐2.2k)](https://github.com/feature-engine/feature_engine) - Feature engineering package with sklearn-like functionality. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [OpenFE (⭐872)](https://github.com/IIIS-Li-Group/OpenFE) - Automated feature generation with expert-level performance.
*   [skl-groups (⭐41)](https://github.com/dougalsutherland/skl-groups) - A scikit-learn addon to operate on set/"group"-based features. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Feature Forge (⭐385)](https://github.com/machinalis/featureforge) - A set of tools for creating and testing machine learning features. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [few (⭐52)](https://github.com/lacava/few) - A feature engineering wrapper for sklearn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [scikit-mdr (⭐126)](https://github.com/EpistasisLab/scikit-mdr) - A sklearn-compatible Python implementation of Multifactor Dimensionality Reduction (MDR) for feature construction. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [tsfresh (⭐9.2k)](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [dirty\_cat (⭐20)](https://github.com/dirty-cat/dirty_cat) - Machine learning on dirty tabular data (especially: string-based variables for classifcation and regression). <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [NitroFE (⭐108)](https://github.com/NITRO-AI/NitroFE) - Moving window features. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [sk-transformer (⭐11)](https://github.com/chrislemke/sk-transformers) - A collection of various pandas & scikit-learn compatible transformers for all kinds of preprocessing and feature engineering steps <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [tubular (⭐100)](https://github.com/azukds/tubular) - Collection of scikit-learn compatible transformers written in [narwhals (⭐1.6k)](https://github.com/narwhals-dev/narwhals), which can accept either polars/pandas inputs and utilise the chosen library under the hood. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"><img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">

### Feature Selection

*   [scikit-feature (⭐1.6k)](https://github.com/jundongl/scikit-feature) - Feature selection repository in Python.
*   [boruta\_py (⭐1.6k)](https://github.com/scikit-learn-contrib/boruta_py) - Implementations of the Boruta all-relevant feature selection method. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [BoostARoota (⭐234)](https://github.com/chasedehan/BoostARoota) - A fast xgboost feature selection algorithm. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [scikit-rebate (⭐422)](https://github.com/EpistasisLab/scikit-rebate) - A scikit-learn-compatible Python implementation of ReBATE, a suite of Relief-based feature selection algorithms for Machine Learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [zoofs (⭐253)](https://github.com/jaswinder9051998/zoofs) - A feature selection library based on evolutionary algorithms.

## Visualization

### General Purposes

*   [Matplotlib (⭐23k)](https://github.com/matplotlib/matplotlib) - Plotting with Python.
*   [seaborn (⭐14k)](https://github.com/mwaskom/seaborn) - Statistical data visualization using matplotlib.
*   [prettyplotlib (⭐1.7k)](https://github.com/olgabot/prettyplotlib) - Painlessly create beautiful matplotlib plots.
*   [python-ternary (⭐780)](https://github.com/marcharper/python-ternary) - Ternary plotting library for Python with matplotlib.
*   [missingno (⭐4.2k)](https://github.com/ResidentMario/missingno) - Missing data visualization module for Python.
*   [chartify (⭐3.6k)](https://github.com/spotify/chartify/) - Python library that makes it easy for data scientists to create charts.
*   [physt (⭐137)](https://github.com/janpipek/physt) - Improved histograms.

### Interactive plots

*   [animatplot (⭐417)](https://github.com/t-makaro/animatplot) - A python package for animating plots built on matplotlib.
*   [plotly](https://plot.ly/python/) - A Python library that makes interactive and publication-quality graphs.
*   [Bokeh (⭐20k)](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
*   [Altair](https://altair-viz.github.io/) - Declarative statistical visualization library for Python. Can easily do many data transformation within the code to create graph
*   [bqplot (⭐3.7k)](https://github.com/bqplot/bqplot) - Plotting library for IPython/Jupyter notebooks
*   [pyecharts (⭐16k)](https://github.com/pyecharts/pyecharts) - Migrated from [Echarts (⭐66k)](https://github.com/apache/echarts), a charting and visualization library, to Python's interactive visual drawing library.<img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pyecharts.png" alt="pyecharts"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/echarts.png" alt="echarts">

### Map

*   [folium](https://python-visualization.github.io/folium/quickstart.html#Getting-Started) - Makes it easy to visualize data on an interactive open street map
*   [geemap (⭐3.9k)](https://github.com/giswqs/geemap) - Python package for interactive mapping with Google Earth Engine (GEE)

### Automatic Plotting

*   [HoloViews (⭐2.9k)](https://github.com/ioam/holoviews) - Stop plotting your data - annotate your data and let it visualize itself.
*   [AutoViz (⭐1.9k)](https://github.com/AutoViML/AutoViz): Visualize data automatically with 1 line of code (ideal for machine learning)
*   [SweetViz (⭐3.1k)](https://github.com/fbdesignpro/sweetviz): Visualize and compare datasets, target values and associations, with one line of code.

### NLP

*   [pyLDAvis (⭐1.8k)](https://github.com/bmabey/pyLDAvis): Visualize interactive topic model

## Deployment

*   [fastapi](https://fastapi.tiangolo.com/) - Modern, fast (high-performance), a web framework for building APIs with Python
*   [streamlit](https://www.streamlit.io/) - Make it easy to deploy the machine learning model
*   [streamsync (⭐1.4k)](https://github.com/streamsync-cloud/streamsync) - No-code in the front, Python in the back. An open-source framework for creating data apps.
*   [gradio (⭐42k)](https://github.com/gradio-app/gradio) - Create UIs for your machine learning model in Python in 3 minutes.
*   [Vizro (⭐3.7k)](https://github.com/mckinsey/vizro) - A toolkit for creating modular data visualization applications.
*   [datapane](https://datapane.com/) - A collection of APIs to turn scripts and notebooks into interactive reports.
*   [binder](https://mybinder.org/) - Enable sharing and execute Jupyter Notebooks
*   [Deepnote (⭐2.8k)](https://github.com/deepnote/deepnote) - Deepnote is a drop-in replacement for Jupyter with an AI-first design, sleek UI, new blocks, and native data integrations. Use Python, R, and SQL locally in your favorite IDE, then scale to Deepnote cloud for real-time collaboration, Deepnote agent, and deployable data apps.

## Statistics

*   [pandas\_summary (⭐531)](https://github.com/mouradmourafiq/pandas-summary) - Extension to pandas dataframes describe function. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [Pandas Profiling (⭐13k)](https://github.com/pandas-profiling/pandas-profiling) - Create HTML profiling reports from pandas DataFrame objects. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [statsmodels (⭐11k)](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
*   [stockstats (⭐1.5k)](https://github.com/jealous/stockstats) - Supply a wrapper `StockDataFrame` based on the `pandas.DataFrame` with inline stock statistics/indicators support.
*   [weightedcalcs (⭐113)](https://github.com/jsvine/weightedcalcs) - A pandas-based utility to calculate weighted means, medians, distributions, standard deviations, and more.
*   [scikit-posthocs (⭐382)](https://github.com/maximtrp/scikit-posthocs) - Pairwise Multiple Comparisons Post-hoc Tests.
*   [Alphalens (⭐4.2k)](https://github.com/quantopian/alphalens) - Performance analysis of predictive (alpha) stock factors.

## Data Manipulation

### Data Frames

*   [pandas](https://pandas.pydata.org/pandas-docs/stable/) - Powerful Python data analysis toolkit.
*   [polars (⭐38k)](https://github.com/pola-rs/polars) - A fast multi-threaded, hybrid-out-of-core DataFrame library.
*   [Arctic (⭐3.1k)](https://github.com/manahl/arctic) - High-performance datastore for time series and tick data.
*   [datatable (⭐1.9k)](https://github.com/h2oai/datatable) - Data.table for Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/R_big.png" alt="R inspired/ported lib">
*   [pandas\_profiling (⭐13k)](https://github.com/pandas-profiling/pandas-profiling) - Create HTML profiling reports from pandas DataFrame objects
*   [cuDF (⭐9.6k)](https://github.com/rapidsai/cudf) - GPU DataFrame Library. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/gpu_big.png" alt="GPU accelerated">
*   [blaze (⭐3.2k)](https://github.com/blaze/blaze) - NumPy and pandas interface to Big Data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [pandasql (⭐1.3k)](https://github.com/yhat/pandasql) -  Allows you to query pandas DataFrames using SQL syntax. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [pandas-gbq (⭐490)](https://github.com/pydata/pandas-gbq) - pandas Google Big Query. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [xpandas (⭐26)](https://github.com/alan-turing-institute/xpandas) - Universal 1d/2d data containers with Transformers .functionality for data analysis by [The Alan Turing Institute](https://www.turing.ac.uk/).
*   [pysparkling (⭐271)](https://github.com/svenkreiss/pysparkling) - A pure Python implementation of Apache Spark's RDD and DStream interfaces. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/spark_big.png" alt="Apache Spark based">
*   [modin (⭐10k)](https://github.com/modin-project/modin) - Speed up your pandas workflows by changing a single line of code. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [swifter (⭐2.6k)](https://github.com/jmcarpenter2/swifter) - A package that efficiently applies any function to a pandas dataframe or series in the fastest available manner.
*   [pandas-log (⭐218)](https://github.com/eyaltrabelsi/pandas-log) - A package that allows providing feedback about basic pandas operations and finds both business logic and performance issues.
*   [vaex (⭐8.5k)](https://github.com/vaexio/vaex) - Out-of-Core DataFrames for Python, ML, visualize and explore big tabular data at a billion rows per second.
*   [xarray (⭐4.1k)](https://github.com/pydata/xarray) - Xarray combines the best features of NumPy and pandas for multidimensional data selection by supplementing numerical axis labels with named dimensions for more intuitive, concise, and less error-prone indexing routines.

### Pipelines

*   [pdpipe (⭐725)](https://github.com/shaypal5/pdpipe) - Sasy pipelines for pandas DataFrames.
*   [SSPipe](https://sspipe.github.io/) - Python pipe (|) operator with support for DataFrames and Numpy, and Pytorch.
*   [pandas-ply (⭐197)](https://github.com/coursera/pandas-ply) - Functional data manipulation for pandas. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [Dplython (⭐760)](https://github.com/dodger487/dplython) - Dplyr for Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/R_big.png" alt="R inspired/ported lib">
*   [sklearn-pandas (⭐2.9k)](https://github.com/scikit-learn-contrib/sklearn-pandas) - pandas integration with sklearn. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn"> <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [Dataset (⭐205)](https://github.com/analysiscenter/dataset) - Helps you conveniently work with random or sequential batches of your data and define data processing.
*   [pyjanitor (⭐1.5k)](https://github.com/ericmjl/pyjanitor) - Clean APIs for data cleaning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [meza (⭐421)](https://github.com/reubano/meza) - A Python toolkit for processing tabular data.
*   [Prodmodel (⭐58)](https://github.com/prodmodel/prodmodel) - Build system for data science pipelines.
*   [dopanda (⭐480)](https://github.com/dovpanda-dev/dovpanda) -  Hints and tips for using pandas in an analysis environment. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [Hamilton (⭐2.4k)](https://github.com/DAGWorks-Inc/hamilton) - A microframework for dataframe generation that applies Directed Acyclic Graphs specified by a flow of lazily evaluated Python functions.

### Data-centric AI

*   [cleanlab (⭐11k)](https://github.com/cleanlab/cleanlab) - The standard data-centric AI package for data quality and machine learning with messy, real-world data and labels.
*   [snorkel (⭐5.9k)](https://github.com/snorkel-team/snorkel) - A system for quickly generating training data with weak supervision.
*   [dataprep (⭐2.2k)](https://github.com/sfu-db/dataprep) - Collect, clean, and visualize your data in Python with a few lines of code.

### Synthetic Data

*   [ydata-synthetic (⭐1.6k)](https://github.com/ydataai/ydata-synthetic) - A package to generate synthetic tabular and time-series data leveraging the state-of-the-art generative models. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">

## Distributed Computing

*   [Horovod (⭐15k)](https://github.com/uber/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/tf_big2.png" alt="sklearn">
*   [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html) - Exposes the Spark programming model to Python. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/spark_big.png" alt="Apache Spark based">
*   [Veles (⭐916)](https://github.com/Samsung/veles) - Distributed machine learning platform.
*   [Jubatus (⭐709)](https://github.com/jubatus/jubatus) - Framework and Library for Distributed Online Machine Learning.
*   [DMTK (⭐2.7k)](https://github.com/Microsoft/DMTK) - Microsoft Distributed Machine Learning Toolkit.
*   [PaddlePaddle (⭐24k)](https://github.com/PaddlePaddle/Paddle) - PArallel Distributed Deep LEarning.
*   [dask-ml (⭐944)](https://github.com/dask/dask-ml) - Distributed and parallel machine learning. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [Distributed (⭐1.7k)](https://github.com/dask/distributed) - Distributed computation in Python.

## Experimentation

*   [mlflow (⭐25k)](https://github.com/mlflow/mlflow) - Open source platform for the machine learning lifecycle.
*   [Neptune](https://neptune.ai) - A lightweight ML experiment tracking, results visualization, and management tool.
*   [dvc (⭐15k)](https://github.com/iterative/dvc) - Data Version Control | Git for Data & Models | ML Experiments Management.
*   [envd (⭐2.2k)](https://github.com/tensorchord/envd) - 🏕️ machine learning development environment for data science and AI/ML engineering teams.
*   [Sacred (⭐4.4k)](https://github.com/IDSIA/sacred) - A tool to help you configure, organize, log, and reproduce experiments.
*   [Ax (⭐2.7k)](https://github.com/facebook/Ax) - Adaptive Experimentation Platform. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">

## Data Validation

*   [great\_expectations (⭐11k)](https://github.com/great-expectations/great_expectations) - Always know what to expect from your data.
*   [pandera (⭐4.3k)](https://github.com/unionai-oss/pandera) - A lightweight, flexible, and expressive statistical data testing library.
*   [deepchecks (⭐4k)](https://github.com/deepchecks/deepchecks) - Validation & testing of ML models and data during model development, deployment, and production. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [evidently (⭐7.4k)](https://github.com/evidentlyai/evidently) - Evaluate and monitor ML models from validation to production.
*   [TensorFlow Data Validation (⭐780)](https://github.com/tensorflow/data-validation) - Library for exploring and validating machine learning data.
*   [DataComPy (⭐638)](https://github.com/capitalone/datacompy)- A library to compare Pandas, Polars, and Spark data frames. It provides stats and lets users adjust for match accuracy.

## Evaluation

*   [recmetrics (⭐582)](https://github.com/statisticianinstilettos/recmetrics) - Library of useful metrics and plots for evaluating recommender systems.
*   [Metrics (⭐1.7k)](https://github.com/benhamner/Metrics) - Machine learning evaluation metric.
*   [sklearn-evaluation (⭐3)](https://github.com/edublancas/sklearn-evaluation) - Model evaluation made easy: plots, tables, and markdown reports. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/sklearn_big.png" alt="sklearn">
*   [AI Fairness 360 (⭐2.8k)](https://github.com/IBM/AIF360) - Fairness metrics for datasets and ML models, explanations, and algorithms to mitigate bias in datasets and models.
*   [alibi-detect (⭐2.5k)](https://github.com/SeldonIO/alibi-detect) - Algorithms for outlier, adversarial and drift detection.<img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/alibi-detect.png" alt="sklearn">

## Computations

*   [NumPy](https://numpy.org/) - The fundamental package for scientific computing with Python
*   [Dask (⭐14k)](https://github.com/dask/dask) - Parallel computing with task scheduling. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [bottleneck (⭐1.2k)](https://github.com/kwgoodman/bottleneck) - Fast NumPy array functions written in C.
*   [CuPy (⭐11k)](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA.
*   [scikit-tensor (⭐405)](https://github.com/mnick/scikit-tensor) - Python library for multilinear algebra and tensor factorizations.
*   [numdifftools (⭐280)](https://github.com/pbrod/numdifftools) - Solve automatic numerical differentiation problems in one or more variables.
*   [quaternion (⭐656)](https://github.com/moble/quaternion) - Add built-in support for quaternions to numpy.
*   [adaptive (⭐1.2k)](https://github.com/python-adaptive/adaptive) - Tools for adaptive and parallel samping of mathematical functions.
*   [NumExpr (⭐2.4k)](https://github.com/pydata/numexpr) - A fast numerical expression evaluator for NumPy that comes with an integrated computing virtual machine to speed calculations up by avoiding memory allocation for intermediate results.

## Web Scraping

*   [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): The easiest library to scrape static websites for beginners
*   [Scrapy](https://scrapy.org/): Fast and extensible scraping library. Can write rules and create customized scraper without touching the core
*   [Selenium](https://selenium-python.readthedocs.io/installation.html#introduction): Use Selenium Python API to access all functionalities of Selenium WebDriver in an intuitive way like a real user.
*   [Pattern (⭐8.9k)](https://github.com/clips/pattern): High level scraping for well-establish websites such as Google, Twitter, and Wikipedia. Also has NLP, machine learning algorithms, and visualization
*   [twitterscraper (⭐2.5k)](https://github.com/taspinar/twitterscraper): Efficient library to scrape Twitter

## Spatial Analysis

*   [GeoPandas (⭐5.1k)](https://github.com/geopandas/geopandas) - Python tools for geographic data. <img height="20" src="https://github.com/krzjoa/awesome-python-data-science/raw/master/img/pandas_big.png" alt="pandas compatible">
*   [PySal (⭐1.5k)](https://github.com/pysal/pysal) - Python Spatial Analysis Library.

## Quantum Computing

*   [qiskit (⭐7.2k)](https://github.com/Qiskit/qiskit) - Qiskit is an open-source SDK for working with quantum computers at the level of circuits, algorithms, and application modules.
*   [cirq (⭐4.9k)](https://github.com/quantumlib/Cirq) - A python framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
*   [PennyLane (⭐3.1k)](https://github.com/XanaduAI/pennylane) - Quantum machine learning, automatic differentiation, and optimization of hybrid quantum-classical computations.
*   [QML (⭐208)](https://github.com/qmlcode/qml) - A Python Toolkit for Quantum Machine Learning.

## Conversion

*   [sklearn-porter (⭐1.3k)](https://github.com/nok/sklearn-porter) - Transpile trained scikit-learn estimators to C, Java, JavaScript, and others.
*   [ONNX (⭐21k)](https://github.com/onnx/onnx) - Open Neural Network Exchange.
*   [MMdnn (⭐5.8k)](https://github.com/Microsoft/MMdnn) -  A set of tools to help users inter-operate among different deep learning frameworks.
*   [treelite (⭐814)](https://github.com/dmlc/treelite) - Universal model exchange and serialization format for decision tree forests.

## Contributing

Contributions are welcome! :sunglasses: </br>
Read the \<a href=[https://github.com/krzjoa/awesome-python-datascience/blob/master/CONTRIBUTING.md>contribution (⭐3.4k)](https://github.com/krzjoa/awesome-python-datascience/blob/master/CONTRIBUTING.md>contribution) guideline</a>.

## License

This work is licensed under the Creative Commons Attribution 4.0 International License - [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

