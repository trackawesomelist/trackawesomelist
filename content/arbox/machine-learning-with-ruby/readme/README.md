# Machine Learning with Ruby Overview

Curated list: Resources for machine learning in Ruby

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/arbox/machine-learning-with-ruby/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 arbox/machine-learning-with-ruby](https://github.com/arbox/machine-learning-with-ruby) · ⭐ 2K · 🏷️ Computer Science

[ [Daily](/content/arbox/machine-learning-with-ruby/README.md) / [Weekly](/content/arbox/machine-learning-with-ruby/week/README.md) / Overview ]

---

<img title="Awesome Machine Learning with Ruby" alt="Awesome Machine Learning with Ruby" src="https://github.com/arbox/machine-learning-with-ruby/raw/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

\[[RubyNLP (⭐1k)](https://github.com/arbox/nlp-with-ruby) |
[RubyDataScience (⭐681)](https://github.com/arbox/data-science-with-ruby) |
[RubyInterop (⭐37)](https://github.com/arbox/ruby-interoperability)]

# Awesome Machine Learning with Ruby [<img src="https://github.com/arbox/machine-learning-with-ruby/raw/master/ruby.jpg" align="left" width="30px" height="30px" />][ruby]

> Curated List of Ruby Machine Learning Links and Resources

[Machine Learning][ml] is a field of [Computational Science][cs] -
often nested under [AI][ai] research - with many practical
applications due to the ability of resulting algorithms to
systematically implement a specific solution without explicit
programmer's instructions. Obviously many algorithms need a definition
of [features][fe] to look at or a biggish [training set][ts] of data to derive the
solution from.

This curated list comprises [*awesome*][awesome] libraries,
data sources, tutorials and presentations about [Machine Learning][ml]
utilizing the [Ruby][ruby] programming language.

A lot of useful resources on this list come from the development by
[The Ruby Science Foundation][sciruby], our [contributors][contributors] and
our own day to day work on various ML applications.

:sparkles: Every [contribution](https://github.com/arbox/machine-learning-with-ruby/blob/master/readme.md/contributing.md) is welcome! Add links through pull
requests or create an issue to start a discussion.

Follow us on [Twitter](https://twitter.com/NonWebRuby) and please spread
the word using the `#RubyML` hash tag!

<!-- nodoc -->

## Contents

<!-- toc -->

*   [:sparkles: Tutorials](#sparkles-tutorials)
*   [Machine Learning Libraries](#machine-learning-libraries)
    *   [Frameworks](#frameworks)
    *   [Neural networks](#neural-networks)
    *   [Deep Learning](#deep-learning)
    *   [Kernel methods](#kernel-methods)
    *   [Evolutionary algorithms](#evolutionary-algorithms)
    *   [Bayesian methods](#bayesian-methods)
    *   [Decision trees](#decision-trees)
    *   [Clustering](#clustering)
    *   [Linear classifiers](#linear-classifiers)
    *   [Statistical models](#statistical-models)
    *   [Gradient boosting](#gradient-boosting)
    *   [Vector search](#vector-search)
*   [Applications of machine learning](#applications-of-machine-learning)
*   [Data structures](#data-structures)
*   [Data visualization](#data-visualization)
*   [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
*   [Projects and Code Examples](#projects-and-code-examples)
*   [Heroku buildpacks](#heroku-buildpacks)
*   [Books, Blogs, Channels](#books-blogs-channels)
*   [Community](#community)
*   [Related Resources](#related-resources)
*   [License](#license)

<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

Please help us to fill out this section! :smiley:

*   [Ruby neural networks](https://www.honeybadger.io/blog/ruby-neural-networks/)
*   [How to implement linear regression in Ruby](https://www.practicalai.io/implementing-linear-regression-using-ruby/) <sup>\[[code (⭐5)](https://github.com/daugaard/example-linear-regression)]</sup>
*   [How to implement classification using logistic regression in Ruby](https://www.practicalai.io/implementing-classification-using-logistic-regression-in-ruby/)
*   [How to implement simple binary classification using a Neural Network in Ruby](https://www.practicalai.io/implementing-simple-classification-using-neural-network-in-ruby/) <sup>\[[code (⭐10)](https://github.com/daugaard/example-neural-network)]</sup>
*   [How to implement classification using a SVM in Ruby](https://www.practicalai.io/implementing-classification-using-a-svm-in-ruby/) <sup>\[[code (⭐5)](https://github.com/daugaard/example-svm)]</sup>
*   [Unsupervised learning using k-means clustering in Ruby](https://www.practicalai.io/unsupervised-learning-using-k-means-clustering-in-ruby/) <sup>\[[code (⭐0)](https://github.com/daugaard/example-kmeans-clustering)]</sup>
*   [Teaching an AI to play a simple game using Q-Learning in Ruby](https://www.practicalai.io/teaching-ai-play-simple-game-using-q-learning/) <sup>\[[code (⭐37)](https://github.com/daugaard/q-learning-simple-game)]</sup>
*   [Teaching a Neural Network to play a game using Q-Learning in Ruby](https://www.practicalai.io/teaching-a-neural-network-to-play-a-game-with-q-learning/) <sup>\[[code (⭐37)](https://github.com/daugaard/q-learning-simple-game/tree/neuralnetwork)]</sup>
*   [Using the Python scikit-learn machine learning library in Ruby using PyCall](https://www.practicalai.io/using-scikit-learn-machine-learning-library-in-ruby-using-pycall/) <sup>\[[code (⭐3)](https://github.com/daugaard/scikit-learn-from-ruby)]</sup>
*   [How to *evolve* neural networks in Ruby using the Machine Learning Workbench (⭐19)](https://github.com/giuse/machine_learning_workbench/blob/master/examples/neuroevolution.rb)

## Machine Learning Libraries

[Machine Learning][ml] algorithms in pure Ruby or written in other
programming languages with appropriate bindings for Ruby.

### Frameworks

*   [LangChain.rb (⭐714)](https://github.com/andreibondarev/langchainrb) -
    Build ML/AI-supercharged applications with Ruby's LangChain.
*   [weka (⭐64)](https://github.com/paulgoetze/weka-jruby) -
    JRuby bindings for Weka, different ML algorithms implemented through Weka.
*   [ai4r (⭐711)](https://github.com/SergioFierens/ai4r) -
    Artificial Intelligence for Ruby.
*   [classifier-reborn (⭐541)](https://github.com/jekyll/classifier-reborn) -
    General classifier module to allow Bayesian and other types of classifications. <sup>\[[dep: GLS](#gls)]</sup>
*   [scoruby (⭐68)](https://github.com/asafschers/scoruby) -
    Ruby scoring API for [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) (Predictive Model Markup Language).
*   [rblearn (⭐1)](https://github.com/himkt/rblearn) - Feature Extraction and Crossvalidation library.
*   [data\_modeler (⭐1)](https://github.com/giuse/data_modeler) -
    Model your data with machine learning. Ample test coverage, examples to start fast, complete documentation. Production ready since 1.0.0.
*   [shogun (⭐3k)](https://github.com/shogun-toolbox/shogun) - Polyfunctional and mature
    machine learning toolbox with [Ruby bindings (⭐3k)](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby).
*   [aws-sdk-machinelearning (⭐3.5k)](https://github.com/aws/aws-sdk-ruby) -
    Machine Learning API of the Amazon Web Services.
*   [azure\_mgmt\_machine\_learning (⭐274)](https://github.com/Azure/azure-sdk-for-ruby) -
    Machine Learning API of the Microsoft Azure.
*   [machine\_learning\_workbench (⭐19)](https://github.com/giuse/machine_learning_workbench) -
    Growing machine learning framework written in pure Ruby, high performance computing using
    [Numo](https://github.com/ruby-numo/), CUDA bindings through [Cumo (⭐91)](https://github.com/sonots/cumo).
    Currently implementating neural networks, evolutionary strategies, vector quantization, and plenty of
    examples and utilities.
*   [Deep NeuroEvolution (⭐124)](https://github.com/giuse/DNE) -
    Experimental setup based on the [machine\_learning\_workbench (⭐19)](https://github.com/giuse/machine_learning_workbench)
    towards searching for deep neural networks (rather than training) using evolutionary algorithms. Applications to the
    [OpenAI Gym (⭐33k)](https://github.com/openai/gym) using [PyCall (⭐1k)](https://github.com/mrkn/pycall.rb).
*   [rumale (⭐714)](https://github.com/yoshoku/rumale) -
    Machine Learninig toolkit in Ruby with wide range of implemented algorithms
    (SVM, Logistic Regression, Linear Regression, Random Forest etc.) and
    interfaces similar to [Scikit-Learn][scikit] in Python.
*   [eps (⭐631)](https://github.com/ankane/eps) - Bayesian Classification and Linear Regression with exports
    using [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend using [GSL][gsl].
*   [ruby-openai (⭐2k)](https://github.com/alexrudall/ruby-openai) - OpenAI API wrapper

### Neural networks

*   [neural-net-ruby (⭐127)](https://github.com/gbuesing/neural-net-ruby) -
    Neural network written in Ruby.
*   [ruby-fann (⭐465)](https://github.com/tangledpath/ruby-fann) -
    Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
*   [cerebrum (⭐35)](https://github.com/irfansharif/cerebrum) -
    Experimental implementation for Artificial Neural Networks in Ruby.
*   [tlearn-rb (⭐96)](https://github.com/josephwilk/tlearn-rb) -
    Recurrent Neural Network library for Ruby.
*   [brains (⭐60)](https://github.com/jedld/brains-jruby) -
    Feed-forward neural networks for JRuby based on
    [brains (⭐0)](https://github.com/jedld/brains).
*   [machine\_learning\_workbench (⭐19)](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) -
    Framework including pure-Ruby implementation of both feed-forward and recurrent neural networks
    (fully connected). Training available using neuroevolution (Natural Evolution Strategies algorithms).
*   [rann (⭐3)](https://github.com/mikecmpbll/rann) -
    Flexible Ruby ANN implementation with backprop (through-time, for recurrent
    nets), gradient checking, adagrad, and parallel batch execution.

### Deep learning

*   [tensor\_stream (⭐509)](https://github.com/jedld/tensor_stream) -
    Ground-up and standalone reimplementation of TensorFlow for Ruby.
*   [red-chainer (⭐101)](https://github.com/red-data-tools/red-chainer) - Deep learning framework for Ruby.
*   [tensorflow (⭐823)](https://github.com/somaticio/tensorflow.rb) - Ruby bindings for [TensorFlow](https://www.tensorflow.org/).
*   [ruby-dnn (⭐43)](https://github.com/unagiootoro/ruby-dnn) - Simple deep learning for Ruby.
*   [torch-rb (⭐595)](https://github.com/ankane/torch-rb) - Ruby bindings for [LibTorch (⭐73k)](https://github.com/pytorch/pytorch)
    using [rice (⭐355)](https://github.com/jasonroelofs/rice).
*   [mxnet (⭐48)](https://github.com/mrkn/mxnet.rb) - Ruby bindings for [mxnet](https://mxnet.apache.org/).

### Kernel methods

*   [rb-libsvm (⭐279)](https://github.com/febeling/rb-libsvm) -
    Support Vector Machines with Ruby and the [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) library. <sup>\[[dep: bundled](#bundled)]</sup>

### Evolutionary algorithms

*   [machine\_learning\_workbench (⭐19)](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) -
    Framework including pure-Ruby implementations of Natural Evolution Strategy algorithms
    (black-box optimization), specifically Exponential NES (XNES),
    Separable NES (sNES), Block-Diagonal NES (BDNES) and more.
    Applications include neural network search/training (neuroevolution).
*   [simple\_ga (⭐9)](https://github.com/giuse/simple_ga) -
    Simplest Genetic Algorithms implementation in Ruby.

### Bayesian methods

*   [linnaeus (⭐37)](https://github.com/djcp/linnaeus) -
    Redis-backed Bayesian classifier.
*   [naive\_bayes (⭐47)](https://github.com/reddavis/Naive-Bayes) -
    Simple Naive Bayes classifier.
*   [nbayes (⭐152)](https://github.com/oasic/nbayes) -
    Full-featured, Ruby implementation of Naive Bayes.

### Decision trees

*   [decisiontree (⭐1.4k)](https://github.com/igrigorik/decisiontree) -
    Decision Tree ID3 Algorithm in pure Ruby. <sup>\[[dep: GraphViz](#graphviz) |
    [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.

### Clustering

*   [kmeans-clusterer (⭐93)](https://github.com/gbuesing/kmeans-clusterer) -
    k-means clustering in Ruby.
*   [k\_means (⭐115)](https://github.com/reddavis/K-Means) -
    Attempting to build a fast, memory efficient K-Means program.
*   [knn (⭐37)](https://github.com/reddavis/knn) -
    Simple K Nearest Neighbour Algorithm.

### Linear classifiers

*   [liblinear-ruby-swig (⭐82)](https://github.com/tomz/liblinear-ruby-swig) -
    Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
*   [liblinear-ruby (⭐83)](https://github.com/kei500/liblinear-ruby) -
    Ruby interface to LIBLINEAR using SWIG.

### Statistical models

*   [rtimbl (⭐5)](https://github.com/maspwr/rtimbl) -
    Memory based learners from the Timbl framework.
*   [lda-ruby (⭐133)](https://github.com/ealdent/lda-ruby) -
    Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
    (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering.
*   [maxent\_string\_classifier (⭐9)](https://github.com/mccraigmccraig/maxent_string_classifier) -
    JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
*   [omnicat (⭐11)](https://github.com/mustafaturan/omnicat) -
    Generalized rack framework for text classifications.
*   [omnicat-bayes (⭐32)](https://github.com/mustafaturan/omnicat-bayes) -
    Naive Bayes text classification implementation as an OmniCat classifier strategy. <sup>\[[dep: bundled](#bundled)]</sup>

### Gradient boosting

*   [xgboost (⭐18)](https://github.com/PairOnAir/xgboost-ruby) —
    Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)]</sup>
*   [xgb (⭐92)](https://github.com/ankane/xgb) —
    Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)]</sup>
*   [lightgbm (⭐65)](https://github.com/ankane/lightgbm) —
    Ruby bindings for LightGBM. <sup>\[[dep: LightGBM](#lightgbm)]</sup>

### Vector search

*   [flann (⭐2.1k)](https://github.com/mariusmuja/flann) -
    Ruby bindings for the [FLANN (⭐2.1k)](https://github.com/flann-lib/flann) (Fast Library for Approximate Nearest Neighbors). <sup>\[[flann](#flann)]</sup>
*   [annoy-rb (⭐28)](https://github.com/yoshoku/annoy.rb) -
    Ruby bindings for the [Annoy (⭐12k)](https://github.com/spotify/annoy) (Approximate Nearest Neighbors Oh Yeah).
*   [hnswlib.rb (⭐12)](https://github.com/yoshoku/hnswlib.rb) -
    Ruby bindings for the [Hnswlib (⭐3.7k)](https://github.com/nmslib/hnswlib) that implements approximate nearest neighbor search with Hierarchical Navigable Small World graphs.
*   [ngt-ruby (⭐44)](https://github.com/ankane/ngt-ruby) -
    Ruby bindings for the [NGT (⭐1.1k)](https://github.com/yahoojapan/NGT) (Neighborhood Graph and Tree for Indexing High-dimensional data).
*   [milvus (⭐14)](https://github.com/andreibondarev/milvus) —
    Ruby client for Milvus Vector DB.
*   [pinecone (⭐50)](https://github.com/ScotterC/pinecone) —
    Ruby client for Pinecone Vector DB.
*   [qdrant-ruby (⭐26)](https://github.com/andreibondarev/qdrant-ruby) —
    Ruby wrapper for the Qdrant vector search database API.
*   [weaviate-ruby (⭐36)](https://github.com/andreibondarev/weaviate-ruby) —
    Ruby wrapper for the Weaviate vector search database API.

## Applications of machine learning

*   [phashion (⭐695)](https://github.com/westonplatter/phashion) -
    Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files. <sup>\[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)]</sup>

## Data structures

If you're going to implement your own ML algorithms you're probably interested
in storing your feature sets efficiently. Look for appropriate
[data structures (⭐681)](https://github.com/arbox/data-science-with-ruby#data-structures)
in our [Data Science with Ruby][ds-with-ruby] list.

## Data visualization

Please refer to the [Data Visualization (⭐681)](https://github.com/arbox/data-science-with-ruby#visualization)
section on the [Data Science with Ruby][ds-with-ruby] list.

## Articles, Posts, Talks, and Presentations

*   2022
    *   *Discover Machine Learning in Ruby* by [Justin Bowen](https://twitter.com/TonsOfFun111) <sup>\[[video](https://www.youtube.com/watch?v=HPbizNgcyFk)]</sup>

*   2019
    *   *TensorStream: Bringing Machine Learning to Ruby* by [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/) <sup>\[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)]</sup>
    *   *Easy machine learning with Ruby using SVMKit* by [@kojix](https://twitter.com/kojix2dayo) <sup>\[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)]</sup>

*   2018
    *   *Deep Learning Programming on Ruby* by [Kenta Murata](https://twitter.com/mrkn)
        & [Yusaku Hatanaka ](https://twitter.com/hatappi) <sup>\[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) |
        [page](https://rubykaigi.org/2018/presentations/mrkn.html)]</sup>
    *   *How to use trained Keras and TensorFlow machine learning models within Ruby on Rails* by [Denis Sellu](https://twitter.com/denis_sellu) <sup>\[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)]</sup>

*   2017
    *   *Scientific Computing on JRuby* by [Prasun Anand](https://twitter.com/prasun_anand) <sup>\[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
        [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
        [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
        [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
    *   *Is it Food? An Introduction to Machine Learning* by [Matthew Mongeau](https://twitter.com/halogenandtoast) <sup>\[[video](https://www.youtube.com/watch?v=8G709hKkthY) |
        [slides](https://www.slideshare.net/halogenandtoast/is-it-food)]</sup>
    *   *Bayes is BAE* by [Richard Schneeman](https://twitter.com/schneems) <sup>\[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) |
        [slides](https://speakerdeck.com/schneems/bayes-is-bae)]</sup>
    *   *Ruby Roundtable: Machine Learning in Ruby* by [RubyThursday](https://rubythursday.com/) <sup>\[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)]</sup>

*   2016
    *   *Practical Machine Learning with Ruby* by [Jordan Hudgens](https://twitter.com/jordanhudgens) <sup>\[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
    *   *Deep Learning: An Introduction for Ruby Developers* by [Geoffrey Litt](https://twitter.com/geoffreylitt) <sup>\[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
    *   *How I made a pure-Ruby word2vec program more than 3x faster* by [Kei Sawada](https://twitter.com/remore) <sup>\[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
    *   *Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby* by [Eric Weinstein](https://twitter.com/ericqweinstein) <sup>\[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) |
        [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
    *   *Building a Recommendation Engine with Machine Learning Techniques* by [Brian Sam-Bodden](https://twitter.com/bsbodden) <sup>\[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)]</sup>
    *   :sparkles: *SciRuby Machine Learning: Current Status and Future* by [Kenta Murata](https://twitter.com/mrkn) <sup>\[[slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) |
        [video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)]</sup>
    *   *Ruby Roundtable: Intro to Tensorflow* by [RubyThursday](https://rubythursday.com/) <sup>\[[video](https://www.youtube.com/watch?v=pYC5mXHUWkc)]</sup>

*   2015
    *   *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://twitter.com/rugginoso) <sup>\[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)]</sup>
    *   *Using Ruby Machine Learning to Find Paris Hilton Quotes* by [Rick Carlino](https://github.com/RickCarlino) <sup>\[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>

*   2014
    *   *Test Driven Neural Networks* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU\&t=36s)]</sup>
    *   *Five machine learning techniques that you can use in your Ruby apps today* by [Benjamin Curtis](https://twitter.com/stympy) <sup>\[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
        [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
    *   *Machine Learning for Fun and Profit* by [John Paul Ashenfelter](https://twitter.com/johnashenfelter) <sup>\[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)]</sup>

*   2013
    *   *Sentiment Analysis using Support Vector Machines in Ruby* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=iSug6CgxWxc) |
        [code (⭐12)](https://github.com/hexgnu/sentiment_analyzer)]</sup>
    *   *Recommender Systems with Ruby* by [Marcel Caraciolo](https://twitter.com/marcelcaraciolo) <sup>\[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)]</sup>
    *   *Detecting Faces with Ruby: FFI in a Nutshell* by [Marc Berszick](https://github.com/arbox/machine-learning-with-ruby/blob/master/readme.md/) <sup>\[[post](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/)]</sup>

*   2012
    *   *Machine Learning with Ruby, Part One* by [Vasily Vasinov](https://twitter.com/vasinov) <sup>\[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
    *   *Recurrent Neural Networks in Ruby* by [Joseph Wilk](https://twitter.com/josephwilk) <sup>\[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
    *   *Recommendation Engines using Machine Learning, and JRuby* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
    *   *Practical Machine Learning and Rails* by [Andrew Cantino](https://twitter.com/tectonic)
        and [Ryan Stout](https://twitter.com/ryanstout) <sup>\[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)]</sup>

*   2011
    *   *Clustering in Ruby* by [Colin Drake](https://twitter.com/colinfdrake) <sup>\[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)]</sup>
    *   *Text Classification using Support Vector Machines in Ruby* by [Rimas Silkaitis](https://twitter.com/neovintage) <sup>\[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)]</sup>

*   2010
    *   *bayes\_motel – Bayesian classification for Ruby* by [Mike Perham](https://twitter.com/mperham) <sup>\[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
    *   *Intelligent Ruby: Getting Started with Machine Learning* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[video](https://vimeo.com/22513786)]</sup>

*   2009

*   2008
    *   *Support Vector Machines (SVM) in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>

*   2007
    *   *Decision Tree Learning in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>

## Projects and Code Examples

*   [Wine Clustering (⭐0)](https://github.com/hexgnu/wine_clustering) -
    Wine quality estimations clustered with different algorithms.
*   [simple\_ga (⭐9)](https://github.com/giuse/simple_ga) -
    Basic (working) demo of Genetic Algorithms in Ruby.
*   [Handwritten Digits Recognition (⭐5)](https://github.com/jdrzj/handwritten-digits-recognition) -
    Handwritten digits recognition using Neural Networks and Ruby.

## Heroku buildpacks

*   [GSL and Ruby buildpack (⭐3)](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby)
*   [OpenCV and Ruby buildpack (⭐3)](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv)
*   [ImageMagick buildpack (⭐46)](https://github.com/mcollina/heroku-buildpack-imagemagick)

## Books, Blogs, Channels

*   [Kirk, Matthew](https://twitter.com/mjkirk).
    *Thoughtful Machine Learning: A Test-Driven Approach*. O'Reilly, 2014. <sup>\[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
    [code (⭐127)](https://github.com/thoughtfulml/examples)]</sup>
*   [Practical Artificial Intelligence](https://www.practicalai.io/) -
    Blog about Artificial Intelligence and Machine Learning with tutorials and code samples in Ruby.

## Community

*   [SciRuby Mailing List](https://groups.google.com/forum/#!forum/sciruby-dev)
*   [SciRuby Slack](https://sciruby.slack.com/)
*   [Red Data Gitter](https://gitter.im/red-data-tools/)
*   [Reddit](https://www.reddit.com/r/MachineLearning/search?q=Ruby\&restrict_sr=on)
*   [Stack Overflow](https://stackoverflow.com/search?q=machine+learning+ruby)
*   [Twitter](https://twitter.com/search?q=Machine%20Learning%20Ruby\&src=typd)
*   [NonWebRuby](https://twitter.com/NonWebRuby)
*   [Ruby AI Builders Discord](https://discord.gg/zDyFJFBTGB)
*   [X Ruby AI group](https://twitter.com/i/communities/1709211359039078677)
*   [Mastodon Ruby AI and Data group](https://ruby.social/@Ruby_AI_and_Data@chirp.social)

## Related Resources

*   <a name="lightgbm"></a>
    [LightGBM (⭐16k)](https://github.com/microsoft/LightGBM)
*   <a name="xgboost"></a>
    [XGBoost (⭐25k)](https://github.com/dmlc/xgboost)
*   <a name="gls"></a>
    \[GSL (GNU Scientific Library)]\[gls]
*   <a name="opencv"></a>
    [OpenCV](https://opencv.org/)
*   <a name="empty-lines-around-access-modifier"></a>
    [Graphviz](http://www.graphviz.org/)
*   <a name="gnuplot"></a>
    [Gnuplot](http://www.gnuplot.info/)
*   <a name="xquartz"></a>
    [X11/XQuartz](https://www.xquartz.org/)
*   <a name="imagemagic"></a>
    [ImageMagick](https://www.imagemagick.org/script/index.php)
*   <a name="r"></a>
    [R](http://www.r-project.org/)
*   <a name="octave"></a>
    [Octave](https://www.gnu.org/software/octave/)
*   [scikit-learn algorithm cheatsheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/)
*   [Awesome Ruby (⭐13k)](https://github.com/markets/awesome-ruby#natural-language-processing) -
    Among other awesome items a short list of NLP related projects.
*   [Ruby NLP (⭐1.3k)](https://github.com/diasks2/ruby-nlp) -
    State-of-Art collection of Ruby libraries for NLP.
*   [Speech and Natural Language Processing (⭐2.2k)](https://github.com/edobashira/speech-language-processing) -
    General List of NLP related resources (mostly not for Ruby programmers).
*   [Scientific Ruby](http://sciruby.com/) -
    Linear Algebra, Visualization and Scientific Computing for Ruby.
*   [iRuby (⭐801)](https://github.com/SciRuby/iruby) - IRuby kernel for Jupyter (formerly IPython).
*   [Kiba (⭐1.7k)](https://github.com/thbar/kiba) -
    Lightweight [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) (Extract, Transform, Load) pipeline.
*   [Awesome OCR (⭐2.5k)](https://github.com/kba/awesome-ocr) -
    Multitude of OCR (Optical Character Recognition) resources.
*   [Awesome TensorFlow (⭐17k)](https://github.com/jtoy/awesome-tensorflow) -
    Machine Learning with TensorFlow libraries.
*   [rb-gsl (⭐96)](https://github.com/SciRuby/rb-gsl) -
    Ruby interface to the [GNU Scientific Library](https://www.gnu.org/software/gsl/).
*   [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
    Modern Reference and Tutorial on Embedding and Extending Ruby using C programming language.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
`Awesome ML with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors][contributors].

To the extent possible under law, the person who associated CC0 with
`Awesome ML with Ruby` has waived all copyright and related or neighboring rights
to `Awesome ML with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->

[ruby]: https://www.ruby-lang.org/en/

[awesome]: https://github.com/sindresorhus/awesome/blob/master/awesome.md

[change-pr]: https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md

[ml]: https://en.wikipedia.org/wiki/Machine_learning

[ds-with-ruby]: https://github.com/arbox/data-science-with-ruby

[contributors]: https://github.com/arbox/machine-learning-with-ruby/graphs/contributors

[sciruby]: https://github.com/sciruby

[ai]: https://en.wikipedia.org/wiki/Artificial_intelligence

[cs]: https://en.wikipedia.org/wiki/Computational_science

[fe]: https://en.wikipedia.org/wiki/Feature_engineering

[ts]: https://en.wikipedia.org/wiki/Test_set

[gsl]: https://www.gnu.org/software/gsl/

[scikit]: https://scikit-learn.org/stable/index.html

