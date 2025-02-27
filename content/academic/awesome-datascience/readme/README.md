# Awesome Datascience Overview

:memo: An awesome Data Science repository to learn and apply for real world problems.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/academic/awesome-datascience/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 academic/awesome-datascience](https://github.com/academic/awesome-datascience) · ⭐ 26K · 🏷️ Computer Science

[ [Daily](/content/academic/awesome-datascience/README.md) / [Weekly](/content/academic/awesome-datascience/week/README.md) / Overview ]

---

<div align="center"><img src="https://github.com/academic/awesome-datascience/raw/live/./assets/head.jpg"></div>

# AWESOME DATA SCIENCE

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**An open-source Data Science repository to learn and apply towards solving real world problems.**

This is a shortcut path to start studying **Data Science**. Just follow the steps to answer the questions, "What is Data Science and what should I study to learn Data Science?"

## Sponsors

| Sponsor | Pitch                                         |
| ------- | --------------------------------------------- |
| ---     | Be the first to sponsor! `github@academic.io` |

<br>

## Table of Contents

*   [What is Data Science?](#what-is-data-science)
*   [Where do I Start?](#where-do-i-start)
*   [Training Resources](#training-resources)
    *   [Tutorials](#tutorials)
    *   [Free Courses](#free-courses)
    *   [Massively Open Online Courses](#moocs)
    *   [Intensive Programs](#intensive-programs)
    *   [Colleges](#colleges)
*   [The Data Science Toolbox](#the-data-science-toolbox)
    *   [Algorithms](#algorithms)
        *   [Supervised Learning](#supervised-learning)
        *   [Unsupervised Learning](#unsupervised-learning)
        *   [Semi-Supervised Learning](#semi-supervised-learning)
        *   [Reinforcement Learning](#reinforcement-learning)
        *   [Data  Mining Algorithms](#data-mining-algorithms)
        *   [Deep Learning Architectures](#deep-learning-architectures)
    *   [General Machine Learning Packages](#general-machine-learning-packages)
    *   [Deep Learning Packages](#deep-learning-packages)
        *   [PyTorch Ecosystem](#pytorch-ecosystem)
        *   [TensorFlow Ecosystem](#tensorflow-ecosystem)
        *   [Keras Ecosystem](#keras-ecosystem)
    *   [Visualization Tools](#visualization-tools)
    *   [Miscellaneous Tools](#miscellaneous-tools)
*   [Literature and Media](#literature-and-media)
    *   [Books](#books)
        *   [Book Deals (Affiliated)](#book-deals-affiliated)
    *   [Journals, Publications, and Magazines](#journals-publications-and-magazines)
    *   [Newsletters](#newsletters)
    *   [Bloggers](#bloggers)
    *   [Presentations](#presentations)
    *   [Podcasts](#podcasts)
    *   [YouTube Videos & Channels](#youtube-videos--channels)
*   [Socialize](#socialize)
    *   [Facebook Accounts](#facebook-accounts)
    *   [Twitter Accounts](#twitter-accounts)
    *   [Telegram Channels](#telegram-channels)
    *   [Slack Communities](#slack-communities)
    *   [GitHub Groups](#github-groups)
    *   [Data Science Competitions](#data-science-competitions)
*   [Fun](#fun)
    *   [Infographics](#infographics)
    *   [Datasets](#datasets)
    *   [Comics](#comics)
*   [Other Awesome Lists](#other-awesome-lists)
    *   [Hobby](#hobby)

## What is Data Science?

**[`^        back to top        ^`](#awesome-data-science)**

Data Science is one of the hottest topics on the Computer and Internet farmland nowadays. People have gathered data from applications and systems until today and now is the time to analyze them. The next steps are producing suggestions from the data and creating predictions about the future. [Here](https://www.quora.com/Data-Science/What-is-data-science) you can find the biggest question for **Data Science** and hundreds of answers from experts.

| Link                                                                                                                                   | Preview                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [What is Data Science @ O'reilly](https://www.oreilly.com/ideas/what-is-data-science)                                                  | *Data scientists combine entrepreneurship with patience, the willingness to build data products incrementally, the ability to explore, and the ability to iterate over a solution. They are inherently interdisciplinary. They can tackle all aspects of a problem, from initial data collection and data conditioning to drawing conclusions. They can think outside the box to come up with new ways to view the problem, or to work with very broadly defined problems: “here’s a lot of data, what can you make from it?”*                                                                                       |
| [What is Data Science @ Quora](https://www.quora.com/Data-Science/What-is-data-science)                                                | Data Science is a combination of a number of aspects of Data such as Technology, Algorithm development, and data interference to study the data, analyse it, and find innovative solutions to difficult problems. Basically Data Science is all about Analysing data and driving for business growth by finding creative ways.                                                                                                                                                                                                                                                                                       |
| [The sexiest job of 21st century](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century)                          | *Data scientists today are akin to Wall Street “quants” of the 1980s and 1990s. In those days people with backgrounds in physics and math streamed to investment banks and hedge funds, where they could devise entirely new algorithms and data strategies. Then a variety of universities developed master’s programs in financial engineering, which churned out a second generation of talent that was more accessible to mainstream firms. The pattern was repeated later in the 1990s with search engineers, whose rarefied skills soon came to be taught in computer science programs.*                       |
| [Wikipedia](https://en.wikipedia.org/wiki/Data_science)                                                                                | *Data science is an interdisciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from many structural and unstructured data. Data science is related to data mining, machine learning and big data.*                                                                                                                                                                                                                                                                                                                                                    |
| [How to Become a Data Scientist](https://www.mastersindatascience.org/careers/data-scientist/)                                         | *Data scientists are big data wranglers, gathering and analyzing large sets of structured and unstructured data. A data scientist’s role combines computer science, statistics, and mathematics. They analyze, process, and model data then interpret the results to create actionable plans for companies and other organizations.*                                                                                                                                                                                                                                                                                 |
| [a very short history of #datascience](https://www.forbes.com/sites/gilpress/2013/05/28/a-very-short-history-of-data-science/)         | *The story of how data scientists became sexy is mostly the story of the coupling of the mature discipline of statistics with a very young one--computer science.  The term “Data Science” has emerged only recently to specifically designate a new profession that is expected to make sense of the vast stores of big data. But making sense of data has a long history and has been discussed by scientists, statisticians, librarians, computer scientists and others for years. The following timeline traces the evolution of the term “Data Science” and its use, attempts to define it, and related terms.* |
| [Software Development Resources for Data Scientists](https://www.rstudio.com/blog/software-development-resources-for-data-scientists/) | *Data scientists concentrate on making sense of data through exploratory analysis, statistics, and models. Software developers apply a separate set of knowledge with different tools. Although their focus may seem unrelated, data science teams can benefit from adopting software development best practices. Version control, automated testing, and other dev skills help create reproducible, production-ready code and tools.*                                                                                                                                                                               |
| [Data Scientist Roadmap](https://www.scaler.com/blog/how-to-become-a-data-scientist/)                                                  | *Data science is an excellent career choice in today’s data-driven world where approx 328.77 million terabytes of data are generated daily. And this number is only increasing day by day, which in turn increases the demand for skilled data scientists who can utilize this data to drive business growth.*                                                                                                                                                                                                                                                                                                       |
| [Navigating Your Path to Becoming a Data Scientist](https://www.appliedaicourse.com/blog/how-to-become-a-data-scientist/)              | \_Data science is one of the most in-demand careers today. With businesses increasingly relying on data to make decisions, the need for skilled data scientists has grown rapidly. Whether it’s tech companies, healthcare organizations, or even government institutions, data scientists play a crucial role in turning raw data into valuable insights. But how do you become a data scientist, especially if you’re just starting out? \_                                                                                                                                                                        |

## Where do I Start?

**[`^        back to top        ^`](#awesome-data-science)**

While not strictly necessary, having a programming language is a crucial skill to be effective as a data scientist. Currently, the most popular language is *Python*, closely followed by *R*. Python is a general-purpose scripting language that sees applications in a wide variety of fields. R is a domain-specific language for statistics, which contains a lot of common statistics tools out of the box.

[Python](https://python.org/) is by far the most popular language in science, due in no small part to the ease at which it can be used and the vibrant ecosystem of user-generated packages. To install packages, there are two main methods: Pip (invoked as `pip install`), the package manager that comes bundled with Python, and [Anaconda](https://www.anaconda.com) (invoked as `conda install`), a powerful package manager that can install packages for Python, R, and can download executables like Git.

Unlike R, Python was not built from the ground up with data science in mind, but there are plenty of third party libraries to make up for this. A much more exhaustive list of packages can be found later in this document, but these four packages are a good set of choices to start your data science journey with: [Scikit-Learn](https://scikit-learn.org/stable/index.html) is a general-purpose data science package which implements the most popular algorithms - it also includes rich documentation, tutorials, and examples of the models it implements. Even if you prefer to write your own implementations, Scikit-Learn is a valuable reference to the nuts-and-bolts behind many of the common algorithms you'll find. With [Pandas](https://pandas.pydata.org/), one can collect and analyze their data into a convenient table format. [Numpy](https://numpy.org/) provides very fast tooling for mathematical operations, with a focus on vectors and matrices. [Seaborn](https://seaborn.pydata.org/), itself based on the [Matplotlib](https://matplotlib.org/) package, is a quick way to generate beautiful visualizations of your data, with many good defaults available out of the box, as well as a gallery showing how to produce many common visualizations of your data.

When embarking on your journey to becoming a data scientist, the choice of language isn't particularly important, and both Python and R have their pros and cons. Pick a language you like, and check out one of the [Free courses](#free-courses) we've listed below!

## Real World

**[`^        back to top        ^`](#awesome-data-science)**

Data science is a powerful tool that is utilized in various fields to solve real-world problems by extracting insights and patterns from complex data.

### Disaster

**[`^        back to top        ^`](#awesome-data-science)**

*   [deprem-ml](https://huggingface.co/deprem-ml) [AYA: Açık Yazılım Ağı](https://linktr.ee/acikyazilimagi) (+25k developers) is trying to help disaster response using artificial intelligence. Everything is open-sourced [afet.org](https://afet.org).

## Training Resources

**[`^        back to top        ^`](#awesome-data-science)**

How do you learn data science? By doing data science, of course! Okay, okay - that might not be particularly helpful when you're first starting out. In this section, we've listed some learning resources, in rough order from least to greatest commitment - [Tutorials](#tutorials), [Massively Open Online Courses (MOOCs)](#moocs), [Intensive Programs](#intensive-programs), and [Colleges](#colleges).

### Tutorials

**[`^        back to top        ^`](#awesome-data-science)**

*   [1000 Data Science Projects](https://cloud.blobcity.com/#/ps/explore) you can run on the browser with IPython.
*   [#tidytuesday (⭐7.2k)](https://github.com/rfordatascience/tidytuesday) A weekly data project aimed at the R ecosystem.
*   [Data science your way (⭐601)](https://github.com/jadianes/data-science-your-way)
*   [PySpark Cheatsheet (⭐492)](https://github.com/kevinschaich/pyspark-cheatsheet)
*   [Machine Learning, Data Science and Deep Learning with Python ](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python)
*   [Your Guide to Latent Dirichlet Allocation](https://medium.com/@lettier/how-does-lda-work-ill-explain-using-emoji-108abf40fa7d)
*   [Tutorials of source code from the book Genetic Algorithms with Python by Clinton Sheppard (⭐1.2k)](https://github.com/handcraftsman/GeneticAlgorithmsWithPython)
*   [Tutorials to get started on signal processing for machine learning (⭐66)](https://github.com/jinglescode/python-signal-processing)
*   [Realtime deployment](https://www.microprediction.com/python-1) Tutorial on Python time-series model deployment.
*   [Python for Data Science: A Beginner’s Guide](https://learntocodewith.me/posts/python-for-data-science/)
*   [Minimum Viable Study Plan for Machine Learning Interviews (⭐10k)](https://github.com/khangich/machine-learning-interview)
*   [Understand and Know Machine Learning Engineering by Building Solid Projects](http://mlzoomcamp.com/)
*   [12 free Data Science projects to practice Python and Pandas](https://www.datawars.io/articles/12-free-data-science-projects-to-practice-python-and-pandas)
*   [Best CV/Resume for Data Science Freshers](https://enhancv.com/resume-examples/data-scientist/)
*   [Understand Data Science Course in Java](https://www.alter-solutions.com/articles/java-data-science)
*   [Data Analytics Interview Questions (Beginner to Advanced)](https://www.appliedaicourse.com/blog/data-analytics-interview-questions/)
*   [Top 100+ Data Science Interview Questions and Answers](https://www.appliedaicourse.com/blog/data-science-interview-questions/)

### Free Courses

**[`^        back to top        ^`](#awesome-data-science)**

*   [Data Scientist with R](https://www.datacamp.com/tracks/data-scientist-with-r)

*   [Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python)

*   [Genetic Algorithms OCW Course](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/lecture-videos/lecture-1-introduction-and-scope/)

*   [AI Expert Roadmap (⭐30k)](https://github.com/AMAI-GmbH/AI-Expert-Roadmap) - Roadmap to becoming an Artificial Intelligence Expert

*   [Convex Optimization](https://www.edx.org/course/convex-optimization) - Convex Optimization (basics of convex analysis; least-squares, linear and quadratic programs, semidefinite programming, minimax, extremal volume, and other problems; optimality conditions, duality theory...)

*   [Learning from Data](https://home.work.caltech.edu/telecourse.html) - Introduction to machine learning covering basic theory, algorithms and applications

*   [Kaggle](https://www.kaggle.com/learn) - Learn about Data Science, Machine Learning, Python etc

*   [ML Observability Fundamentals](https://arize.com/ml-observability-fundamentals/) - Learn how to monitor and root-cause production ML issues.

*   [Weights & Biases Effective MLOps: Model Development](https://www.wandb.courses/courses/effective-mlops-model-development) - Free Course and Certification for building an end-to-end machine using W\&B

*   [Python for Data Science by Scaler](https://www.scaler.com/topics/course/python-for-data-science/) - This course is designed to empower beginners with the essential skills to excel in today's data-driven world. The comprehensive curriculum will give you a solid foundation in statistics, programming, data visualization, and machine learning.

*   [MLSys-NYU-2022 (⭐426)](https://github.com/jacopotagliabue/MLSys-NYU-2022/tree/main) - Slides, scripts and materials for the Machine Learning in Finance course at NYU Tandon, 2022.

*   [Hands-on Train and Deploy ML (⭐800)](https://github.com/Paulescu/hands-on-train-and-deploy-ml) - A hands-on course to train and deploy a serverless API that predicts crypto prices.

*   [LLMOps: Building Real-World Applications With Large Language Models](https://www.comet.com/site/llm-course/) - Learn to build modern software with LLMs using the newest tools and techniques in the field.

*   [Prompt Engineering for Vision Models](https://www.deeplearning.ai/short-courses/prompt-engineering-for-vision-models/) - Learn to prompt cutting-edge computer vision models with natural language, coordinate points, bounding boxes, segmentation masks, and even other images in this free course from DeepLearning.AI.

*   [Data Science Course By IBM](https://skillsbuild.org/students/course-catalog/data-science) - Free resources and learn what data science is and how it’s used in different industries.

### MOOC's

**[`^        back to top        ^`](#awesome-data-science)**

*   [Coursera Introduction to Data Science](https://www.coursera.org/specializations/data-science)
*   [Data Science - 9 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/jhu-data-science)
*   [Data Mining - 5 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/data-mining)
*   [Machine Learning – 5 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/machine-learning)
*   [CS 109 Data Science](https://cs109.github.io/2015/)
*   [OpenIntro](https://www.openintro.org/)
*   [CS 171 Visualization](https://www.cs171.org/#!index.md)
*   [Process Mining: Data science in Action](https://www.coursera.org/learn/process-mining)
*   [Oxford Deep Learning](https://www.cs.ox.ac.uk/projects/DeepLearn/)
*   [Oxford Deep Learning - video](https://www.youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)
*   [Oxford Machine Learning](https://www.cs.ox.ac.uk/research/ai_ml/index.html)
*   [UBC Machine Learning - video](https://www.cs.ubc.ca/~nando/540-2013/lectures.html)
*   [Data Science Specialization (⭐4.1k)](https://github.com/DataScienceSpecialization/courses)
*   [Coursera Big Data Specialization](https://www.coursera.org/specializations/big-data)
*   [Statistical Thinking for Data Science and Analytics by Edx](https://www.edx.org/course/statistical-thinking-for-data-science-and-analytic)
*   [Cognitive Class AI by IBM](https://cognitiveclass.ai/)
*   [Udacity - Deep Learning](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187)
*   [Keras in Motion](https://www.manning.com/livevideo/keras-in-motion)
*   [Microsoft Professional Program for Data Science](https://academy.microsoft.com/en-us/professional-program/tracks/data-science/)
*   [COMP3222/COMP6246 - Machine Learning Technologies](https://tdgunes.com/COMP6246-2019Fall/)
*   [CS 231 - Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/)
*   [Coursera Tensorflow in practice](https://www.coursera.org/professional-certificates/tensorflow-in-practice)
*   [Coursera Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)
*   [365 Data Science Course](https://365datascience.com/)
*   [Coursera Natural Language Processing Specialization](https://www.coursera.org/specializations/natural-language-processing)
*   [Coursera GAN Specialization](https://www.coursera.org/specializations/generative-adversarial-networks-gans)
*   [Codecademy's Data Science](https://www.codecademy.com/learn/paths/data-science)
*   [Linear Algebra](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/) - Linear Algebra course by Gilbert Strang
*   [A 2020 Vision of Linear Algebra (G. Strang)](https://ocw.mit.edu/resources/res-18-010-a-2020-vision-of-linear-algebra-spring-2020/)
*   [Python for Data Science Foundation Course](https://intellipaat.com/academy/course/python-for-data-science-free-training/)
*   [Data Science: Statistics & Machine Learning](https://www.coursera.org/specializations/data-science-statistics-machine-learning)
*   [Machine Learning Engineering for Production (MLOps)](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops)
*   [Recommender Systems Specialization from University of Minnesota](https://www.coursera.org/specializations/recommender-systems) is an intermediate/advanced level specialization focused on Recommender System on the Coursera platform.
*   [Stanford Artificial Intelligence Professional Program](https://online.stanford.edu/programs/artificial-intelligence-professional-program)
*   [Data Scientist with Python](https://app.datacamp.com/learn/career-tracks/data-scientist-with-python)
*   [Programming with Julia](https://www.udemy.com/course/programming-with-julia/)
*   [Scaler Data Science & Machine Learning Program](https://www.scaler.com/data-science-course/)
*   [Data Science Skill Tree](https://labex.io/skilltrees/data-science)
*   [Data Science for Beginners - Learn with AI tutor](https://codekidz.ai/lesson-intro/data-science-368dbf)
*   [Machine Learning for Beginners - Learn with AI tutor](https://codekidz.ai/lesson-intro/machine-lear-36abfb)

### Intensive Programs

**[`^        back to top        ^`](#awesome-data-science)**

*   [S2DS](https://www.s2ds.org/)

### Colleges

**[`^        back to top        ^`](#awesome-data-science)**

*   [A list of colleges and universities offering degrees in data science. (⭐153)](https://github.com/ryanswanstrom/awesome-datascience-colleges)
*   [Data Science Degree @ Berkeley](https://ischoolonline.berkeley.edu/data-science/)
*   [Data Science Degree @ UVA](https://datascience.virginia.edu/)
*   [Data Science Degree @ Wisconsin](https://datasciencedegree.wisconsin.edu/)
*   [BS in Data Science & Applications](https://study.iitm.ac.in/ds/)
*   [MS in Computer Information Systems @ Boston University](https://www.bu.edu/online/programs/graduate-programs/computer-information-systems-masters-degree/)
*   [MS in Business Analytics @ ASU Online](https://asuonline.asu.edu/online-degree-programs/graduate/master-science-business-analytics/)
*   [MS in Applied Data Science @ Syracuse](https://ischool.syr.edu/academics/applied-data-science-masters-degree/)
*   [M.S. Management & Data Science @ Leuphana](https://www.leuphana.de/en/graduate-school/masters-programmes/management-data-science.html)
*   [Master of Data Science @ Melbourne University](https://study.unimelb.edu.au/find/courses/graduate/master-of-data-science/#overview)
*   [Msc in Data Science @ The University of Edinburgh](https://www.ed.ac.uk/studying/postgraduate/degrees/index.php?r=site/view\&id=902)
*   [Master of Management Analytics @ Queen's University](https://smith.queensu.ca/grad_studies/mma/index.php)
*   [Master of Data Science @ Illinois Institute of Technology](https://www.iit.edu/academics/programs/data-science-mas)
*   [Master of Applied Data Science @ The University of Michigan](https://www.si.umich.edu/programs/master-applied-data-science)
*   [Master Data Science and Artificial Intelligence @ Eindhoven University of Technology](https://www.tue.nl/en/education/graduate-school/master-data-science-and-artificial-intelligence/)
*   [Master's Degree in Data Science and Computer Engineering @ University of Granada](https://masteres.ugr.es/datcom/)

## The Data Science Toolbox

**[`^        back to top        ^`](#awesome-data-science)**

This section is a collection of packages, tools, algorithms, and other useful items in the data science world.

### Algorithms

**[`^        back to top        ^`](#awesome-data-science)**

These are some Machine Learning and Data Mining algorithms and models help you to understand your data and derive meaning from it.

#### Three kinds of Machine Learning Systems

*   Based on training with human supervision
*   Based on learning incrementally on fly
*   Based on data points comparison and pattern detection

### Comparison

*   [datacompy (⭐526)](https://github.com/capitalone/datacompy) - DataComPy is a package to compare two Pandas DataFrames.

#### Supervised Learning

*   [Regression](https://en.wikipedia.org/wiki/Regression)
*   [Linear Regression](https://en.wikipedia.org/wiki/Linear_regression)
*   [Ordinary Least Squares](https://en.wikipedia.org/wiki/Ordinary_least_squares)
*   [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
*   [Stepwise Regression](https://en.wikipedia.org/wiki/Stepwise_regression)
*   [Multivariate Adaptive Regression Splines](https://en.wikipedia.org/wiki/Multivariate_adaptive_regression_spline)
*   [Softmax Regression](https://d2l.ai/chapter_linear-classification/softmax-regression.html)
*   [Locally Estimated Scatterplot Smoothing](https://en.wikipedia.org/wiki/Local_regression)
*   Classification
    *   [k-nearest neighbor](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
    *   [Support Vector Machines](https://en.wikipedia.org/wiki/Support_vector_machine)
    *   [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree)
    *   [ID3 algorithm](https://en.wikipedia.org/wiki/ID3_algorithm)
    *   [C4.5 algorithm](https://en.wikipedia.org/wiki/C4.5_algorithm)
*   [Ensemble Learning](https://scikit-learn.org/stable/modules/ensemble.html)
    *   [Boosting](https://en.wikipedia.org/wiki/Boosting_\(machine_learning\))
    *   [Stacking](https://machinelearningmastery.com/stacking-ensemble-machine-learning-with-python)
    *   [Bagging](https://en.wikipedia.org/wiki/Bootstrap_aggregating)
    *   [Random Forest](https://en.wikipedia.org/wiki/Random_forest)
    *   [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost)

#### Unsupervised Learning

*   [Clustering](https://scikit-learn.org/stable/modules/clustering.html#clustering)
    *   [Hierchical clustering](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)
    *   [k-means](https://scikit-learn.org/stable/modules/clustering.html#k-means)
    *   [Density-based clustering](https://scikit-learn.org/stable/modules/clustering.html#dbscan)
    *   [Fuzzy clustering](https://en.wikipedia.org/wiki/Fuzzy_clustering)
    *   [Mixture models](https://en.wikipedia.org/wiki/Mixture_model)
*   [Dimension Reduction](https://en.wikipedia.org/wiki/Dimensionality_reduction)
    *   [Principal Component Analysis (PCA)](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)
    *   [t-SNE; t-distributed Stochastic Neighbor Embedding](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)
    *   [Factor Analysis](https://scikit-learn.org/stable/modules/decomposition.html#factor-analysis)
    *   [Latent Dirichlet Allocation (LDA)](https://scikit-learn.org/stable/modules/decomposition.html#latent-dirichlet-allocation-lda)
*   [Neural Networks](https://en.wikipedia.org/wiki/Neural_network)
*   [Self-organizing map](https://en.wikipedia.org/wiki/Self-organizing_map)
*   [Adaptive resonance theory](https://en.wikipedia.org/wiki/Adaptive_resonance_theory)
*   [Hidden Markov Models (HMM)](https://en.wikipedia.org/wiki/Hidden_Markov_model)

#### Semi-Supervised Learning

*   S3VM
*   [Clustering](https://en.wikipedia.org/wiki/Weak_supervision#Cluster_assumption)
*   [Generative models](https://en.wikipedia.org/wiki/Weak_supervision#Generative_models)
*   [Low-density separation](https://en.wikipedia.org/wiki/Weak_supervision#Low-density_separation)
*   [Laplacian regularization](https://en.wikipedia.org/wiki/Weak_supervision#Laplacian_regularization)
*   [Heuristic approaches](https://en.wikipedia.org/wiki/Weak_supervision#Heuristic_approaches)

#### Reinforcement Learning

*   [Q Learning](https://en.wikipedia.org/wiki/Q-learning)
*   [SARSA (State-Action-Reward-State-Action) algorithm](https://en.wikipedia.org/wiki/State%E2%80%93action%E2%80%93reward%E2%80%93state%E2%80%93action)
*   [Temporal difference learning](https://en.wikipedia.org/wiki/Temporal_difference_learning#:~:text=Temporal%20difference%20\(TD\)%20learning%20refers,estimate%20of%20the%20value%20function.)

#### Data Mining Algorithms

*   [C4.5](https://en.wikipedia.org/wiki/C4.5_algorithm)
*   [k-Means](https://en.wikipedia.org/wiki/K-means_clustering)
*   [SVM (Support Vector Machine)](https://en.wikipedia.org/wiki/Support_vector_machine)
*   [Apriori](https://en.wikipedia.org/wiki/Apriori_algorithm)
*   [EM (Expectation-Maximization)](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm)
*   [PageRank](https://en.wikipedia.org/wiki/PageRank)
*   [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost)
*   [KNN (K-Nearest Neighbors)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
*   [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
*   [CART (Classification and Regression Trees)](https://en.wikipedia.org/wiki/Decision_tree_learning)

#### Deep Learning architectures

*   [Multilayer Perceptron](https://en.wikipedia.org/wiki/Multilayer_perceptron)
*   [Convolutional Neural Network (CNN)](https://en.wikipedia.org/wiki/Convolutional_neural_network)
*   [Recurrent Neural Network (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network)
*   [Boltzmann Machines](https://en.wikipedia.org/wiki/Boltzmann_machine)
*   [Autoencoder](https://www.tensorflow.org/tutorials/generative/autoencoder)
*   [Generative Adversarial Network (GAN)](https://developers.google.com/machine-learning/gan/gan_structure)
*   [Self-Organized Maps](https://en.wikipedia.org/wiki/Self-organizing_map)
*   [Transformer](https://www.tensorflow.org/text/tutorials/transformer)
*   [Conditional Random Field (CRF)](https://towardsdatascience.com/conditional-random-fields-explained-e5b8256da776)
*   [ML System Designs)](https://www.evidentlyai.com/ml-system-design)

### General Machine Learning Packages

**[`^        back to top        ^`](#awesome-data-science)**

*   [scikit-learn](https://scikit-learn.org/)
*   [scikit-multilearn (⭐928)](https://github.com/scikit-multilearn/scikit-multilearn)
*   [sklearn-expertsys (⭐487)](https://github.com/tmadl/sklearn-expertsys)
*   [scikit-feature (⭐1.5k)](https://github.com/jundongl/scikit-feature)
*   [scikit-rebate (⭐416)](https://github.com/EpistasisLab/scikit-rebate)
*   [seqlearn (⭐692)](https://github.com/larsmans/seqlearn)
*   [sklearn-bayes (⭐517)](https://github.com/AmazaspShumik/sklearn-bayes)
*   [sklearn-crfsuite (⭐426)](https://github.com/TeamHG-Memex/sklearn-crfsuite)
*   [sklearn-deap (⭐772)](https://github.com/rsteca/sklearn-deap)
*   [sigopt\_sklearn (⭐75)](https://github.com/sigopt/sigopt-sklearn)
*   [sklearn-evaluation (⭐3)](https://github.com/edublancas/sklearn-evaluation)
*   [scikit-image (⭐6.2k)](https://github.com/scikit-image/scikit-image)
*   [scikit-opt (⭐5.4k)](https://github.com/guofei9987/scikit-opt)
*   [scikit-posthocs (⭐359)](https://github.com/maximtrp/scikit-posthocs)
*   [pystruct (⭐665)](https://github.com/pystruct/pystruct)
*   [Shogun](https://www.shogun-toolbox.org/)
*   [xLearn (⭐3.1k)](https://github.com/aksnzhy/xlearn)
*   [cuML (⭐4.4k)](https://github.com/rapidsai/cuml)
*   [causalml (⭐5.2k)](https://github.com/uber/causalml)
*   [mlpack (⭐5.3k)](https://github.com/mlpack/mlpack)
*   [MLxtend (⭐5k)](https://github.com/rasbt/mlxtend)
*   [modAL (⭐2.3k)](https://github.com/modAL-python/modAL)
*   [Sparkit-learn (⭐1.2k)](https://github.com/lensacom/sparkit-learn)
*   [hyperlearn (⭐2k)](https://github.com/danielhanchen/hyperlearn)
*   [dlib (⭐14k)](https://github.com/davisking/dlib)
*   [imodels (⭐1.4k)](https://github.com/csinva/imodels)
*   [RuleFit (⭐414)](https://github.com/christophM/rulefit)
*   [pyGAM (⭐886)](https://github.com/dswah/pyGAM)
*   [Deepchecks (⭐3.7k)](https://github.com/deepchecks/deepchecks)
*   [scikit-survival](https://scikit-survival.readthedocs.io/en/stable)
*   [interpretable](https://pypi.org/project/interpretable)
*   [XGBoost (⭐27k)](https://github.com/dmlc/xgboost)
*   [LightGBM (⭐17k)](https://github.com/microsoft/LightGBM)
*   [CatBoost (⭐8.3k)](https://github.com/catboost/catboost)
*   [JAX (⭐31k)](https://github.com/google/jax)

### Deep Learning Packages

#### PyTorch Ecosystem

*   [PyTorch (⭐87k)](https://github.com/pytorch/pytorch)
*   [torchvision (⭐17k)](https://github.com/pytorch/vision)
*   [torchtext (⭐3.5k)](https://github.com/pytorch/text)
*   [torchaudio (⭐2.6k)](https://github.com/pytorch/audio)
*   [ignite (⭐4.6k)](https://github.com/pytorch/ignite)
*   [PyTorchNet (⭐1.7k)](https://github.com/pytorch/tnt)
*   [PyToune (⭐571)](https://github.com/GRAAL-Research/poutyne)
*   [skorch (⭐6k)](https://github.com/skorch-dev/skorch)
*   [PyVarInf (⭐359)](https://github.com/ctallec/pyvarinf)
*   [pytorch\_geometric (⭐22k)](https://github.com/pyg-team/pytorch_geometric)
*   [GPyTorch (⭐3.7k)](https://github.com/cornellius-gp/gpytorch)
*   [pyro (⭐8.7k)](https://github.com/pyro-ppl/pyro)
*   [Catalyst (⭐3.3k)](https://github.com/catalyst-team/catalyst)
*   [pytorch\_tabular (⭐1.5k)](https://github.com/manujosephv/pytorch_tabular)
*   [Yolov3 (⭐10k)](https://github.com/ultralytics/yolov3)
*   [Yolov5 (⭐53k)](https://github.com/ultralytics/yolov5)
*   [Yolov8 (⭐37k)](https://github.com/ultralytics/ultralytics)

#### TensorFlow Ecosystem

*   [TensorFlow (⭐188k)](https://github.com/tensorflow/tensorflow)
*   [TensorLayer (⭐7.3k)](https://github.com/tensorlayer/TensorLayer)
*   [TFLearn (⭐9.6k)](https://github.com/tflearn/tflearn)
*   [Sonnet (⭐9.8k)](https://github.com/deepmind/sonnet)
*   [tensorpack (⭐6.3k)](https://github.com/tensorpack/tensorpack)
*   [TRFL (⭐3.1k)](https://github.com/deepmind/trfl)
*   [Polyaxon (⭐3.6k)](https://github.com/polyaxon/polyaxon)
*   [NeuPy (⭐738)](https://github.com/itdxer/neupy)
*   [tfdeploy (⭐354)](https://github.com/riga/tfdeploy)
*   [tensorflow-upstream (⭐690)](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream)
*   [TensorFlow Fold (⭐1.8k)](https://github.com/tensorflow/fold)
*   [tensorlm (⭐60)](https://github.com/batzner/tensorlm)
*   [TensorLight (⭐11)](https://github.com/bsautermeister/tensorlight)
*   [Mesh TensorFlow (⭐1.6k)](https://github.com/tensorflow/mesh)
*   [Ludwig (⭐11k)](https://github.com/ludwig-ai/ludwig)
*   [TF-Agents (⭐2.9k)](https://github.com/tensorflow/agents)
*   [TensorForce (⭐3.3k)](https://github.com/tensorforce/tensorforce)

#### Keras Ecosystem

*   [Keras](https://keras.io)
*   [keras-contrib (⭐1.6k)](https://github.com/keras-team/keras-contrib)
*   [Hyperas (⭐2.2k)](https://github.com/maxpumperla/hyperas)
*   [Elephas (⭐1.6k)](https://github.com/maxpumperla/elephas)
*   [Hera (⭐487)](https://github.com/keplr-io/hera)
*   [Spektral (⭐2.4k)](https://github.com/danielegrattarola/spektral)
*   [qkeras (⭐556)](https://github.com/google/qkeras)
*   [keras-rl (⭐5.5k)](https://github.com/keras-rl/keras-rl)
*   [Talos (⭐1.6k)](https://github.com/autonomio/talos)

#### Visualization Tools

**[`^        back to top        ^`](#awesome-data-science)**

*   [altair](https://altair-viz.github.io/)
*   [amcharts](https://www.amcharts.com/)
*   [anychart](https://www.anychart.com/)
*   [bokeh](https://bokeh.org/)
*   [Comet](https://www.comet.com/site/products/ml-experiment-tracking/?utm_source=awesome-datascience)
*   [slemma](https://slemma.com/)
*   [cartodb](https://cartodb.github.io/odyssey.js/)
*   [Cube](https://square.github.io/cube/)
*   [d3plus](https://d3plus.org/)
*   [Data-Driven Documents(D3js)](https://d3js.org/)
*   [dygraphs](https://dygraphs.com/)
*   [exhibit](https://www.simile-widgets.org/exhibit/)
*   [gephi](https://gephi.org/)
*   [ggplot2](https://ggplot2.tidyverse.org/)
*   [Glue](http://docs.glueviz.org/en/latest/index.html)
*   [Google Chart Gallery](https://developers.google.com/chart/interactive/docs/gallery)
*   [highcarts](https://www.highcharts.com/)
*   [import.io](https://www.import.io/)
*   [Matplotlib](https://matplotlib.org/)
*   [nvd3](https://nvd3.org/)
*   [Netron (⭐29k)](https://github.com/lutzroeder/netron)
*   [Openrefine](https://openrefine.org/)
*   [plot.ly](https://plot.ly/)
*   [raw](https://rawgraphs.io)
*   [Resseract Lite (⭐5)](https://github.com/abistarun/resseract-lite)
*   [Seaborn](https://seaborn.pydata.org/)
*   [techanjs](https://techanjs.org/)
*   [Timeline](https://timeline.knightlab.com/)
*   [variancecharts](https://variancecharts.com/index.html)
*   [vida](https://vida.io/)
*   [vizzu (⭐2k)](https://github.com/vizzuhq/vizzu-lib)
*   [Wrangler](http://vis.stanford.edu/wrangler/)
*   [r2d3](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
*   [NetworkX](https://networkx.org/)
*   [Redash](https://redash.io/)
*   [C3](https://c3js.org/)
*   [TensorWatch (⭐3.4k)](https://github.com/microsoft/tensorwatch)
*   [geomap](https://pypi.org/project/geomap/)
*   [Dash](https://plotly.com/dash/)

### Miscellaneous Tools

**[`^        back to top        ^`](#awesome-data-science)**

| Link                                                                                                    | Description                                                                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [The Data Science Lifecycle Process (⭐501)](https://github.com/dslp/dslp)                               | The Data Science Lifecycle Process is a process for taking data science teams from Idea to Value repeatedly and sustainably. The process is documented in this repo                                                                                                                                                           |
| [Data Science Lifecycle Template Repo (⭐185)](https://github.com/dslp/dslp-repo-template)               | Template repository for data science lifecycle project                                                                                                                                                                                                                                                                        |
| [RexMex (⭐281)](https://github.com/AstraZeneca/rexmex)                                                  | A general purpose recommender metrics library for fair evaluation.                                                                                                                                                                                                                                                            |
| [ChemicalX (⭐729)](https://github.com/AstraZeneca/chemicalx)                                            | A PyTorch based deep learning library for drug pair scoring.                                                                                                                                                                                                                                                                  |
| [PyTorch Geometric Temporal (⭐2.7k)](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) | Representation learning on dynamic graphs.                                                                                                                                                                                                                                                                                    |
| [Little Ball of Fur (⭐708)](https://github.com/benedekrozemberczki/littleballoffur)                     | A graph sampling library for NetworkX with a Scikit-Learn like API.                                                                                                                                                                                                                                                           |
| [Karate Club (⭐2.2k)](https://github.com/benedekrozemberczki/karateclub)                                | An unsupervised machine learning extension library for NetworkX with a Scikit-Learn like API.                                                                                                                                                                                                                                 |
| [ML Workspace (⭐3.5k)](https://github.com/ml-tooling/ml-workspace)                                      | All-in-one web-based IDE for machine learning and data science. The workspace is deployed as a Docker container and is preloaded with a variety of popular data science libraries (e.g., Tensorflow, PyTorch) and dev tools (e.g., Jupyter, VS Code)                                                                          |
| [Neptune.ai](https://neptune.ai)                                                                        | Community-friendly platform supporting data scientists in creating and sharing machine learning models. Neptune facilitates teamwork, infrastructure management, models comparison and reproducibility.                                                                                                                       |
| [steppy (⭐134)](https://github.com/minerva-ml/steppy)                                                   | Lightweight, Python library for fast and reproducible machine learning experimentation. Introduces very simple interface that enables clean machine learning pipeline design.                                                                                                                                                 |
| [steppy-toolkit (⭐22)](https://github.com/minerva-ml/steppy-toolkit)                                    | Curated collection of the neural networks, transformers and models that make your machine learning work faster and more effective.                                                                                                                                                                                            |
| [Datalab from Google](https://cloud.google.com/datalab/docs/)                                           | easily explore, visualize, analyze, and transform data using familiar languages, such as Python and SQL, interactively.                                                                                                                                                                                                       |
| [Hortonworks Sandbox](https://www.cloudera.com/downloads/hortonworks-sandbox.html)                      | is a personal, portable Hadoop environment that comes with a dozen interactive Hadoop tutorials.                                                                                                                                                                                                                              |
| [R](https://www.r-project.org/)                                                                         | is a free software environment for statistical computing and graphics.                                                                                                                                                                                                                                                        |
| [Tidyverse](https://www.tidyverse.org/)                                                                 | is an opinionated collection of R packages designed for data science. All packages share an underlying design philosophy, grammar, and data structures.                                                                                                                                                                       |
| [RStudio](https://www.rstudio.com)                                                                      | IDE – powerful user interface for R. It’s free and open source, and works on Windows, Mac, and Linux.                                                                                                                                                                                                                         |
| [Python - Pandas - Anaconda](https://www.anaconda.com)                                                  | Completely free enterprise-ready Python distribution for large-scale data processing, predictive analytics, and scientific computing                                                                                                                                                                                          |
| [Pandas GUI (⭐3.2k)](https://github.com/adrotog/PandasGUI)                                              | Pandas GUI                                                                                                                                                                                                                                                                                                                    |
| [Scikit-Learn](https://scikit-learn.org/stable/)                                                        | Machine Learning in Python                                                                                                                                                                                                                                                                                                    |
| [NumPy](https://numpy.org/)                                                                             | NumPy is fundamental for scientific computing with Python. It supports large, multi-dimensional arrays and matrices and includes an assortment of high-level mathematical functions to operate on these arrays.                                                                                                               |
| [Vaex](https://vaex.io/)                                                                                | Vaex is a Python library that allows you to visualize large datasets and calculate statistics at high speeds.                                                                                                                                                                                                                 |
| [SciPy](https://scipy.org/)                                                                             | SciPy works with NumPy arrays and provides efficient routines for numerical integration and optimization.                                                                                                                                                                                                                     |
| [Data Science Toolbox](https://www.coursera.org/learn/data-scientists-tools)                            | Coursera Course                                                                                                                                                                                                                                                                                                               |
| [Data Science Toolbox](https://datasciencetoolbox.org/)                                                 | Blog                                                                                                                                                                                                                                                                                                                          |
| [Wolfram Data Science Platform](https://www.wolfram.com/data-science-platform/)                         | Take numerical, textual, image, GIS or other data and give it the Wolfram treatment, carrying out a full spectrum of data science analysis and visualization and automatically generate rich interactive reports—all powered by the revolutionary knowledge-based Wolfram Language.                                           |
| [Datadog](https://www.datadoghq.com/)                                                                   | Solutions, code, and devops for high-scale data science.                                                                                                                                                                                                                                                                      |
| [Variance](https://variancecharts.com/)                                                                 | Build powerful data visualizations for the web without writing JavaScript                                                                                                                                                                                                                                                     |
| [Kite Development Kit](http://kitesdk.org/docs/current/index.html)                                      | The Kite Software Development Kit (Apache License, Version 2.0), or Kite for short, is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem.                                                                                                    |
| [Domino Data Labs](https://www.dominodatalab.com)                                                       | Run, scale, share, and deploy your models — without any infrastructure or setup.                                                                                                                                                                                                                                              |
| [Apache Flink](https://flink.apache.org/)                                                               | A platform for efficient, distributed, general-purpose data processing.                                                                                                                                                                                                                                                       |
| [Apache Hama](https://hama.apache.org/)                                                                 | Apache Hama is an Apache Top-Level open source project, allowing you to do advanced analytics beyond MapReduce.                                                                                                                                                                                                               |
| [Weka](https://ml.cms.waikato.ac.nz/weka/index.html)                                                    | Weka is a collection of machine learning algorithms for data mining tasks.                                                                                                                                                                                                                                                    |
| [Octave](https://www.gnu.org/software/octave/)                                                          | GNU Octave is a high-level interpreted language, primarily intended for numerical computations.(Free Matlab)                                                                                                                                                                                                                  |
| [Apache Spark](https://spark.apache.org/)                                                               | Lightning-fast cluster computing                                                                                                                                                                                                                                                                                              |
| [Hydrosphere Mist (⭐325)](https://github.com/Hydrospheredata/mist)                                      | a service for exposing Apache Spark analytics jobs and machine learning models as realtime, batch or reactive web services.                                                                                                                                                                                                   |
| [Data Mechanics](https://www.datamechanics.co)                                                          | A data science and engineering platform making Apache Spark more developer-friendly and cost-effective.                                                                                                                                                                                                                       |
| [Caffe](https://caffe.berkeleyvision.org/)                                                              | Deep Learning Framework                                                                                                                                                                                                                                                                                                       |
| [Torch](http://torch.ch/)                                                                               | A SCIENTIFIC COMPUTING FRAMEWORK FOR LUAJIT                                                                                                                                                                                                                                                                                   |
| [Nervana's python based Deep Learning Framework (⭐3.9k)](https://github.com/NervanaSystems/neon)        | Intel® Nervana™ reference deep learning framework committed to best performance on all hardware.                                                                                                                                                                                                                              |
| [Skale (⭐397)](https://github.com/skale-me/skale)                                                       | High performance distributed data processing in NodeJS                                                                                                                                                                                                                                                                        |
| [Aerosolve](https://airbnb.io/aerosolve/)                                                               | A machine learning package built for humans.                                                                                                                                                                                                                                                                                  |
| [Intel framework (⭐313)](https://github.com/intel/idlf)                                                 | Intel® Deep Learning Framework                                                                                                                                                                                                                                                                                                |
| [Datawrapper](https://www.datawrapper.de/)                                                              | An open source data visualization platform helping everyone to create simple, correct and embeddable charts. Also at [github.com (⭐1.4k)](https://github.com/datawrapper/datawrapper)                                                                                                                                         |
| [Tensor Flow](https://www.tensorflow.org/)                                                              | TensorFlow is an Open Source Software Library for Machine Intelligence                                                                                                                                                                                                                                                        |
| [Natural Language Toolkit](https://www.nltk.org/)                                                       | An introductory yet powerful toolkit for natural language processing and classification                                                                                                                                                                                                                                       |
| [Annotation Lab](https://www.johnsnowlabs.com/annotation-lab/)                                          | Free End-to-End No-Code platform for text annotation and DL model training/tuning. Out-of-the-box support for Named Entity Recognition, Classification, Relation extraction and Assertion Status Spark NLP models. Unlimited support for users, teams, projects, documents.                                                   |
| [nlp-toolkit for node.js](https://www.npmjs.com/package/nlp-toolkit)                                    | This module covers some basic nlp principles and implementations. The main focus is performance. When we deal with sample or training data in nlp, we quickly run out of memory. Therefore every implementation in this module is written as stream to only hold that data in memory that is currently processed at any step. |
| [Julia](https://julialang.org)                                                                          | high-level, high-performance dynamic programming language for technical computing                                                                                                                                                                                                                                             |
| [IJulia (⭐2.8k)](https://github.com/JuliaLang/IJulia.jl)                                                | a Julia-language backend combined with the Jupyter interactive environment                                                                                                                                                                                                                                                    |
| [Apache Zeppelin](https://zeppelin.apache.org/)                                                         | Web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala and more                                                                                                                                                                                                  |
| [Featuretools (⭐7.4k)](https://github.com/alteryx/featuretools)                                         | An open source framework for automated feature engineering written in python                                                                                                                                                                                                                                                  |
| [Optimus (⭐1.5k)](https://github.com/hi-primus/optimus)                                                 | Cleansing, pre-processing, feature engineering, exploratory data analysis and easy ML with PySpark backend.                                                                                                                                                                                                                   |
| [Albumentations (⭐15k)](https://github.com/albumentations-team/albumentations)                          | А fast and framework agnostic image augmentation library that implements a diverse set of augmentation techniques. Supports classification, segmentation, and detection out of the box. Was used to win a number of Deep Learning competitions at Kaggle, Topcoder and those that were a part of the CVPR workshops.          |
| [DVC (⭐14k)](https://github.com/iterative/dvc)                                                          | An open-source data science version control system. It helps track, organize and make data science projects reproducible. In its very basic scenario it helps version control and share large data and model files.                                                                                                           |
| [Lambdo (⭐24)](https://github.com/asavinov/lambdo)                                                      | is a workflow engine that significantly simplifies data analysis by combining in one analysis pipeline (i) feature engineering and machine learning (ii) model training and prediction (iii) table population and column evaluation.                                                                                          |
| [Feast (⭐5.8k)](https://github.com/feast-dev/feast)                                                     | A feature store for the management, discovery, and access of machine learning features. Feast provides a consistent view of feature data for both model training and model serving.                                                                                                                                           |
| [Polyaxon (⭐3.6k)](https://github.com/polyaxon/polyaxon)                                                | A platform for reproducible and scalable machine learning and deep learning.                                                                                                                                                                                                                                                  |
| [UBIAI](https://ubiai.tools)                                                                            | Easy-to-use text annotation tool for teams with most comprehensive auto-annotation features. Supports NER, relations and document classification as well as OCR annotation for invoice labeling                                                                                                                               |
| [Trains (⭐5.8k)](https://github.com/allegroai/clearml)                                                  | Auto-Magical Experiment Manager, Version Control & DevOps for AI                                                                                                                                                                                                                                                              |
| [Hopsworks (⭐1.2k)](https://github.com/logicalclocks/hopsworks)                                         | Open-source data-intensive machine learning platform with a feature store. Ingest and manage features for both online (MySQL Cluster)  and offline (Apache Hive) access, train and serve models at scale.                                                                                                                     |
| [MindsDB (⭐27k)](https://github.com/mindsdb/mindsdb)                                                    | MindsDB is an Explainable AutoML framework for developers. With MindsDB you can build, train and use state of the art ML models in as simple as one line of code.                                                                                                                                                             |
| [Lightwood (⭐461)](https://github.com/mindsdb/lightwood)                                                | A Pytorch based framework that breaks down machine learning problems into smaller blocks that can be glued together seamlessly with an objective to build predictive models with one line of code.                                                                                                                            |
| [AWS Data Wrangler (⭐4k)](https://github.com/awslabs/aws-data-wrangler)                                 | An open-source Python package that extends the power of Pandas library to AWS connecting DataFrames and AWS data related services (Amazon Redshift, AWS Glue, Amazon Athena, Amazon EMR, etc).                                                                                                                                |
| [Amazon Rekognition](https://aws.amazon.com/rekognition/)                                               | AWS Rekognition is a service that lets developers working with Amazon Web Services add image analysis to their applications. Catalog assets, automate workflows, and extract meaning from your media and applications.                                                                                                        |
| [Amazon Textract](https://aws.amazon.com/textract/)                                                     | Automatically extract printed text, handwriting, and data from any document.                                                                                                                                                                                                                                                  |
| [Amazon Lookout for Vision](https://aws.amazon.com/lookout-for-vision/)                                 | Spot product defects using computer vision to automate quality inspection. Identify missing product components, vehicle and structure damage, and irregularities for comprehensive quality control.                                                                                                                           |
| [Amazon CodeGuru](https://aws.amazon.com/codeguru/)                                                     | Automate code reviews and optimize application performance with ML-powered recommendations.                                                                                                                                                                                                                                   |
| [CML (⭐4.1k)](https://github.com/iterative/cml)                                                         | An open source toolkit for using continuous integration in data science projects. Automatically train and test models in production-like environments with GitHub Actions & GitLab CI, and autogenerate visual reports on pull/merge requests.                                                                                |
| [Dask](https://dask.org/)                                                                               | An open source Python library to painlessly transition your analytics code to distributed computing systems (Big Data)                                                                                                                                                                                                        |
| [Statsmodels](https://www.statsmodels.org/stable/index.html)                                            | A Python-based inferential statistics, hypothesis testing and regression framework                                                                                                                                                                                                                                            |
| [Gensim](https://radimrehurek.com/gensim/)                                                              | An open-source library for topic modeling of natural language text                                                                                                                                                                                                                                                            |
| [spaCy](https://spacy.io/)                                                                              | A performant natural language processing toolkit                                                                                                                                                                                                                                                                              |
| [Grid Studio (⭐8.9k)](https://github.com/ricklamers/gridstudio)                                         | Grid studio is a web-based spreadsheet application with full integration of the Python programming language.                                                                                                                                                                                                                  |
| [Python Data Science Handbook (⭐44k)](https://github.com/jakevdp/PythonDataScienceHandbook)             | Python Data Science Handbook: full text in Jupyter Notebooks                                                                                                                                                                                                                                                                  |
| [Shapley (⭐218)](https://github.com/benedekrozemberczki/shapley)                                        | A data-driven framework to quantify the value of classifiers in a machine learning ensemble.                                                                                                                                                                                                                                  |
| [DAGsHub](https://dagshub.com)                                                                          | A platform built on open source tools for data, model and pipeline management.                                                                                                                                                                                                                                                |
| [Deepnote](https://deepnote.com)                                                                        | A new kind of data science notebook. Jupyter-compatible, with real-time collaboration and running in the cloud.                                                                                                                                                                                                               |
| [Valohai](https://valohai.com)                                                                          | An MLOps platform that handles machine orchestration, automatic reproducibility and deployment.                                                                                                                                                                                                                               |
| [PyMC3](https://docs.pymc.io/)                                                                          | A Python Library for Probabalistic Programming (Bayesian Inference and Machine Learning)                                                                                                                                                                                                                                      |
| [PyStan](https://pypi.org/project/pystan/)                                                              | Python interface to Stan (Bayesian inference and modeling)                                                                                                                                                                                                                                                                    |
| [hmmlearn](https://pypi.org/project/hmmlearn/)                                                          | Unsupervised learning and inference of Hidden Markov Models                                                                                                                                                                                                                                                                   |
| [Chaos Genius (⭐749)](https://github.com/chaos-genius/chaos_genius/)                                    | ML powered analytics engine for outlier/anomaly detection and root cause analysis                                                                                                                                                                                                                                             |
| [Nimblebox](https://nimblebox.ai/)                                                                      | A full-stack MLOps platform designed to help data scientists and machine learning practitioners around the world discover, create, and launch multi-cloud apps from their web browser.                                                                                                                                        |
| [Towhee (⭐3.3k)](https://github.com/towhee-io/towhee)                                                   | A Python library that helps you encode your unstructured data into embeddings.                                                                                                                                                                                                                                                |
| [LineaPy (⭐666)](https://github.com/LineaLabs/lineapy)                                                  | Ever been frustrated with cleaning up long, messy Jupyter notebooks? With LineaPy, an open source Python library, it takes as little as two lines of code to transform messy development code into production pipelines.                                                                                                      |
| [envd (⭐2.1k)](https://github.com/tensorchord/envd)                                                     | 🏕️ machine learning development environment for data science and AI/ML engineering teams                                                                                                                                                                                                                                     |
| [Explore Data Science Libraries](https://kandi.openweaver.com/explore/data-science)                     | A search engine 🔎 tool to discover & find a curated list of popular & new libraries, top authors, trending project kits, discussions, tutorials & learning resources                                                                                                                                                         |
| [MLEM (⭐718)](https://github.com/iterative/mlem)                                                        | 🐶 Version and deploy your ML models following GitOps principles                                                                                                                                                                                                                                                              |
| [MLflow](https://mlflow.org/)                                                                           | MLOps framework for managing ML models across their full lifecycle                                                                                                                                                                                                                                                            |
| [cleanlab (⭐10k)](https://github.com/cleanlab/cleanlab)                                                 | Python library for data-centric AI and automatically detecting various issues in ML datasets                                                                                                                                                                                                                                  |
| [AutoGluon (⭐8.5k)](https://github.com/awslabs/autogluon)                                               | AutoML to easily produce accurate predictions for image, text, tabular, time-series, and multi-modal data                                                                                                                                                                                                                     |
| [Arize AI](https://arize.com/)                                                                          | Arize AI community tier observability tool for monitoring machine learning models in production and root-causing issues such as data quality and performance drift.                                                                                                                                                           |
| [Aureo.io](https://aureo.io)                                                                            | Aureo.io is a low-code platform that focuses on building artificial intelligence. It provides users with the capability to create pipelines, automations and integrate them with artificial intelligence models – all with their basic data.                                                                                  |
| [ERD Lab](https://www.erdlab.io/)                                                                       | Free cloud based entity relationship diagram (ERD) tool made for developers.                                                                                                                                                                                                                                                  |
| [Arize-Phoenix](https://docs.arize.com/phoenix)                                                         | MLOps in a notebook - uncover insights, surface problems, monitor, and fine tune your models.                                                                                                                                                                                                                                 |
| [Comet (⭐155)](https://github.com/comet-ml/comet-examples)                                              | An MLOps platform with experiment tracking, model production management, a model registry, and full data lineage to support your ML workflow from training straight through to production.                                                                                                                                    |
| [Opik (⭐5.1k)](https://github.com/comet-ml/opik)                                                        | Evaluate, test, and ship LLM applications across your dev and production lifecycles.                                                                                                                                                                                                                                          |
| [Synthical](https://synthical.com)                                                                      | AI-powered collaborative environment for research. Find relevant papers, create collections to manage bibliography, and summarize content — all in one place                                                                                                                                                                  |
| [teeplot (⭐12)](https://github.com/mmore500/teeplot)                                                    | Workflow tool to automatically organize data visualization output                                                                                                                                                                                                                                                             |
| [Streamlit (⭐38k)](https://github.com/streamlit/streamlit)                                              | App framework for Machine Learning and Data Science projects                                                                                                                                                                                                                                                                  |
| [Gradio (⭐36k)](https://github.com/gradio-app/gradio)                                                   | Create customizable UI components around machine learning models                                                                                                                                                                                                                                                              |
| [Weights & Biases (⭐9.6k)](https://github.com/wandb/wandb)                                              | Experiment tracking, dataset versioning, and model management                                                                                                                                                                                                                                                                 |
| [DVC (⭐14k)](https://github.com/iterative/dvc)                                                          | Open-source version control system for machine learning projects                                                                                                                                                                                                                                                              |
| [Optuna (⭐11k)](https://github.com/optuna/optuna)                                                       | Automatic hyperparameter optimization software framework                                                                                                                                                                                                                                                                      |
| [Ray Tune (⭐36k)](https://github.com/ray-project/ray)                                                   | Scalable hyperparameter tuning library                                                                                                                                                                                                                                                                                        |
| [Apache Airflow (⭐39k)](https://github.com/apache/airflow)                                              | Platform to programmatically author, schedule, and monitor workflows                                                                                                                                                                                                                                                          |
| [Prefect (⭐18k)](https://github.com/PrefectHQ/prefect)                                                  | Workflow management system for modern data stacks                                                                                                                                                                                                                                                                             |
| [Kedro (⭐10k)](https://github.com/kedro-org/kedro)                                                      | Open-source Python framework for creating reproducible, maintainable data science code                                                                                                                                                                                                                                        |
| [Hamilton (⭐2k)](https://github.com/dagworks-inc/hamilton)                                              | Lightweight library to author and manage reliable data transformations                                                                                                                                                                                                                                                        |
| [SHAP (⭐23k)](https://github.com/slundberg/shap)                                                        | Game theoretic approach to explain the output of any machine learning model                                                                                                                                                                                                                                                   |
| [LIME (⭐12k)](https://github.com/marcotcr/lime)                                                         | Explaining the predictions of any machine learning classifier                                                                                                                                                                                                                                                                 |
| [flyte (⭐6k)](https://github.com/flyteorg/flyte)                                                        | Workflow automation platform for machine learning                                                                                                                                                                                                                                                                             |
| [dbt (⭐10k)](https://github.com/dbt-labs/dbt-core)                                                      | Data build tool                                                                                                                                                                                                                                                                                                               |
| [SHAP (⭐23k)](https://github.com/slundberg/shap)                                                        | Game theoretic approach to explain the output of any machine learning model                                                                                                                                                                                                                                                   |
| [LIME (⭐12k)](https://github.com/marcotcr/lime)                                                         | Explaining the predictions of any machine learning classifier                                                                                                                                                                                                                                                                 |
| [zasper (⭐1.9k)](https://github.com/zasper-io/zasper)                                                   | Supercharged IDE for Data Science                                                                                                                                                                                                                                                                                             |

## Literature and Media

**[`^        back to top        ^`](#awesome-data-science)**

This section includes some additional reading material, channels to watch, and talks to listen to.

### Books

**[`^        back to top        ^`](#awesome-data-science)**

*   [Data Science From Scratch: First Principles with Python](https://www.amazon.com/Data-Science-Scratch-Principles-Python-dp-1492041130/dp/1492041130/ref=dp_ob_title_bk)
*   [Artificial Intelligence with Python - Tutorialspoint](https://www.tutorialspoint.com/artificial_intelligence_with_python/artificial_intelligence_with_python_tutorial.pdf)
*   [Machine Learning from Scratch](https://dafriedman97.github.io/mlbook/content/introduction.html)
*   [Probabilistic Machine Learning: An Introduction](https://probml.github.io/pml-book/book1.html)
*   [How to Lead in Data Science](https://www.manning.com/books/how-to-lead-in-data-science) - Early Access
*   [Fighting Churn With Data](https://www.manning.com/books/fighting-churn-with-data)
*   [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-with-python-and-dask)
*   [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
*   [The Data Science Handbook: Advice and Insights from 25 Amazing Data Scientists](https://www.thedatasciencehandbook.com/)
*   [Think Like a Data Scientist](https://www.manning.com/books/think-like-a-data-scientist)
*   [Introducing Data Science](https://www.manning.com/books/introducing-data-science)
*   [Practical Data Science with R](https://www.manning.com/books/practical-data-science-with-r)
*   [Everyday Data Science](https://www.amazon.com/dp/B08TZ1MT3W/ref=cm_sw_r_cp_apa_fabc_a0ceGbWECF9A8) & [(cheaper PDF version)](https://gum.co/everydaydata)
*   [Exploring Data Science](https://www.manning.com/books/exploring-data-science) - free eBook sampler
*   [Exploring the Data Jungle](https://www.manning.com/books/exploring-the-data-jungle) - free eBook sampler
*   [Classic Computer Science Problems in Python](https://www.manning.com/books/classic-computer-science-problems-in-python)
*   [Math for Programmers](https://www.manning.com/books/math-for-programmers) Early access
*   [R in Action, Third Edition](https://www.manning.com/books/r-in-action-third-edition) Early Access
*   [Data Science Bookcamp](https://www.manning.com/books/data-science-bookcamp) Early access
*   [Data Science Thinking: The Next Scientific, Technological and Economic Revolution](https://www.springer.com/gp/book/9783319950914)
*   [Applied Data Science: Lessons Learned for the Data-Driven Business](https://www.springer.com/gp/book/9783030118204)
*   [The Data Science Handbook](https://www.amazon.com/Data-Science-Handbook-Field-Cady/dp/1119092949)
*   [Essential Natural Language Processing](https://www.manning.com/books/getting-started-with-natural-language-processing) - Early access
*   [Mining Massive Datasets](http://www.mmds.org/) - free e-book comprehended by an online course
*   [Pandas in Action](https://www.manning.com/books/pandas-in-action) - Early access
*   [Genetic Algorithms and Genetic Programming](https://www.taylorfrancis.com/books/9780429141973)
*   [Advances in Evolutionary Algorithms](https://www.intechopen.com/books/advances_in_evolutionary_algorithms) - Free Download
*   [Genetic Programming: New Approaches and Successful Applications](https://www.intechopen.com/books/genetic-programming-new-approaches-and-successful-applications) - Free Download
*   [Evolutionary Algorithms](https://www.intechopen.com/books/evolutionary-algorithms) - Free Download
*   [Advances in Genetic Programming, Vol. 3](http://www0.cs.ucl.ac.uk/staff/W.Langdon/aigp3/) - Free Download
*   [Genetic Algorithms and Evolutionary Computation](https://www.talkorigins.org/faqs/genalg/genalg.html) - Free Download
*   [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) - Convex Optimization book by Stephen Boyd - Free Download
*   [Data Analysis with Python and PySpark](https://www.manning.com/books/data-analysis-with-python-and-pyspark) - Early Access
*   [R for Data Science](https://r4ds.had.co.nz/)
*   [Build a Career in Data Science](https://www.manning.com/books/build-a-career-in-data-science)
*   [Machine Learning Bookcamp](https://mlbookcamp.com/) - Early access
*   [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
*   [Effective Data Science Infrastructure](https://www.manning.com/books/effective-data-science-infrastructure)
*   [Practical MLOps: How to Get Ready for Production Models](https://valohai.com/mlops-ebook/)
*   [Data Analysis with Python and PySpark](https://www.manning.com/books/data-analysis-with-python-and-pyspark)
*   [Regression, a Friendly guide](https://www.manning.com/books/regression-a-friendly-guide) - Early Access
*   [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/)
*   [Data Science at the Command Line: Facing the Future with Time-Tested Tools](https://www.oreilly.com/library/view/data-science-at/9781491947845/)
*   [Machine Learning with Python - Tutorialspoint](https://www.tutorialspoint.com/machine_learning_with_python/machine_learning_with_python_tutorial.pdf)
*   [Deep Learning](https://www.deeplearningbook.org/)
*   [Designing Cloud Data Platforms](https://www.manning.com/books/designing-cloud-data-platforms) - Early Access
*   [An Introduction to Statistical Learning with Applications in R](https://www.statlearning.com/)
*   [The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://hastie.su.domains/ElemStatLearn/)
*   [Deep Learning with PyTorch](https://www.simonandschuster.com/books/Deep-Learning-with-PyTorch/Eli-Stevens/9781617295263)
*   [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com)
*   [Deep Learning Cookbook](https://www.oreilly.com/library/view/deep-learning-cookbook/9781491995839/)
*   [Introduction to Machine Learning with Python](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
*   [Artificial Intelligence: Foundations of Computational Agents, 2nd Edition](https://artint.info/index.html) - Free HTML version
*   [The Quest for Artificial Intelligence: A History of Ideas and Achievements](https://ai.stanford.edu/~nilsson/QAI/qai.pdf) - Free Download
*   [Graph Algorithms for Data Science](https://www.manning.com/books/graph-algorithms-for-data-science) - Early Access
*   [Data Mesh in Action](https://www.manning.com/books/data-mesh-in-action) - Early Access
*   [Julia for Data Analysis](https://www.manning.com/books/julia-for-data-analysis) - Early Access
*   [Casual Inference for Data Science](https://www.manning.com/books/julia-for-data-analysis) - Early Access
*   [Regular Expression Puzzles and AI Coding Assistants](https://www.manning.com/books/regular-expression-puzzles-and-ai-coding-assistants) by David Mertz
*   [Dive into Deep Learning](https://d2l.ai/)
*   [Data for All](https://www.manning.com/books/data-for-all)
*   [Interpretable Machine Learning: A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/) - Free GitHub version
*   [Foundations of Data Science](https://www.cs.cornell.edu/jeh/book.pdf) Free Download
*   [Comet for DataScience: Enhance your ability to manage and optimize the life cycle of your data science project](https://www.amazon.com/Comet-Data-Science-Enhance-optimize/dp/1801814430)
*   [Software Engineering for Data Scientists](https://www.manning.com/books/software-engineering-for-data-scientists) - Early Access
*   [Julia for Data Science](https://www.manning.com/books/julia-for-data-science) - Early Access
*   [An Introduction to Statistical Learning](https://www.statlearning.com/) - Download Page
*   [Machine Learning For Absolute Beginners](https://www.amazon.in/Machine-Learning-Absolute-Beginners-Introduction-ebook/dp/B07335JNW1)
*   [Unifying Business, Data, and Code: Designing Data Products with JSON Schema](https://learning.oreilly.com/library/view/unifying-business-data/9781098144999/)

#### Book Deals (Affiliated)

*   [eBook sale - Save up to 45% on eBooks!](https://www.manning.com/?utm_source=mikrobusiness\&utm_medium=affiliate\&utm_campaign=ebook_sale_8_8_22)

*   [Causal Machine Learning](https://www.manning.com/books/causal-machine-learning?utm_source=mikrobusiness\&utm_medium=affiliate\&utm_campaign=book_ness_causal_7_26_22\&a_aid=mikrobusiness\&a_bid=43a2198b)

*   [Managing ML Projects](https://www.manning.com/books/managing-machine-learning-projects?utm_source=mikrobusiness\&utm_medium=affiliate\&utm_campaign=book_thompson_managing_6_14_22)

*   [Causal Inference for Data Science](https://www.manning.com/books/causal-inference-for-data-science?utm_source=mikrobusiness\&utm_medium=affiliate\&utm_campaign=book_ruizdevilla_causal_6_6_22)

*   [Data for All](https://www.manning.com/books/data-for-all?utm_source=mikrobusiness\&utm_medium=affiliate)

### Journals, Publications and Magazines

**[`^        back to top        ^`](#awesome-data-science)**

*   [ICML](https://icml.cc/2015/) - International Conference on Machine Learning
*   [GECCO](https://gecco-2019.sigevo.org/index.html/HomePage) - The Genetic and Evolutionary Computation Conference (GECCO)
*   [epjdatascience](https://epjdatascience.springeropen.com/)
*   [Journal of Data Science](https://jds-online.org/journal/JDS) - an international journal devoted to applications of statistical methods at large
*   [Big Data Research](https://www.journals.elsevier.com/big-data-research)
*   [Journal of Big Data](https://journalofbigdata.springeropen.com/)
*   [Big Data & Society](https://journals.sagepub.com/home/bds)
*   [Data Science Journal](https://www.jstage.jst.go.jp/browse/dsj)
*   [datatau.com/news](https://www.datatau.com/news) - Like Hacker News, but for data
*   [Data Science Trello Board](https://trello.com/b/rbpEfMld/data-science)
*   [Medium Data Science Topic](https://medium.com/tag/data-science) - Data Science related publications on medium
*   [Towards Data Science Genetic Algorithm Topic](https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3#:~:text=A%20genetic%20algorithm%20is%20a,offspring%20of%20the%20next%20generation.) -Genetic Algorithm related Publications towards Data Science

### Newsletters

**[`^        back to top        ^`](#awesome-data-science)**

*   [DataTalks.Club](https://datatalks.club). A weekly newsletter about data-related things. [Archive](https://us19.campaign-archive.com/home/?u=0d7822ab98152f5afc118c176\&id=97178021aa).
*   [The Analytics Engineering Roundup](https://roundup.getdbt.com/about). A newsletter about data science. [Archive](https://roundup.getdbt.com/archive).

### Bloggers

**[`^        back to top        ^`](#awesome-data-science)**

*   [Wes McKinney](https://wesmckinney.com/archives.html) - Wes McKinney Archives.
*   [Matthew Russell](https://miningthesocialweb.com/) - Mining The Social Web.
*   [Greg Reda](http://www.gregreda.com/) - Greg Reda Personal Blog
*   [Kevin Davenport](https://kldavenport.com/) - Kevin Davenport Personal Blog
*   [Julia Evans](https://jvns.ca/) - Recurse Center alumna
*   [Hakan Kardas](https://www.cse.unr.edu/~hkardes/) - Personal Web Page
*   [Sean J. Taylor](https://seanjtaylor.com/) - Personal Web Page
*   [Drew Conway](http://drewconway.com/) - Personal Web Page
*   [Hilary Mason](https://hilarymason.com/) - Personal Web Page
*   [Noah Iliinsky](http://complexdiagrams.com/) - Personal Blog
*   [Matt Harrison](https://hairysun.com/) - Personal Blog
*   [Vamshi Ambati](https://allthingsds.wordpress.com/) - AllThings Data Sciene
*   [Prash Chan](https://www.mdmgeek.com/) - Tech Blog on Master Data Management And Every Buzz Surrounding It
*   [Clare Corthell](http://datasciencemasters.org/) - The Open Source Data Science Masters
*   [Datawrangling](http://www.datawrangling.org) by Peter Skomoroch. MACHINE LEARNING, DATA MINING, AND MORE
*   [Quora Data Science](https://www.quora.com/topic/Data-Science) - Data Science Questions and Answers from experts
*   [Siah](https://openresearch.wordpress.com/) a PhD student at Berkeley
*   [Louis Dorard](https://www.ownml.co/blog/) a technology guy with a penchant for the web and for data, big and small
*   [Machine Learning Mastery](https://machinelearningmastery.com/) about helping professional programmers confidently apply machine learning algorithms to address complex problems.
*   [Daniel Forsyth](https://www.danielforsyth.me/) - Personal Blog
*   [Data Science Weekly](https://www.datascienceweekly.org/) - Weekly News Blog
*   [Revolution Analytics](https://blog.revolutionanalytics.com/) - Data Science Blog
*   [R Bloggers](https://www.r-bloggers.com/) - R Bloggers
*   [The Practical Quant](https://practicalquant.blogspot.com/) Big data
*   [Yet Another Data Blog](https://yet-another-data-blog.blogspot.com/) Yet Another Data Blog
*   [Spenczar](https://spenczar.com/) a data scientist at *Twitch*. I handle the whole data pipeline, from tracking to model-building to reporting.
*   [KD Nuggets](https://www.kdnuggets.com/) Data Mining, Analytics, Big Data, Data, Science not a blog a portal
*   [Meta Brown](https://www.metabrown.com/blog/) - Personal Blog
*   [Data Scientist](https://datascientists.com/) is building the data scientist culture.
*   [WhatSTheBigData](https://whatsthebigdata.com/) is some of, all of, or much more than the above and this blog explores its impact on information technology, the business world, government agencies, and our lives.
*   [Tevfik Kosar](https://magnus-notitia.blogspot.com/) - Magnus Notitia
*   [New Data Scientist](https://newdatascientist.blogspot.com/) How a Social Scientist Jumps into the World of Big Data
*   [Harvard Data Science](https://harvarddatascience.com/) - Thoughts on Statistical Computing and Visualization
*   [Data Science 101](https://ryanswanstrom.com/datascience101/) - Learning To Be A Data Scientist
*   [Kaggle Past Solutions](https://www.chioka.in/kaggle-competition-solutions/)
*   [DataScientistJourney](https://datascientistjourney.wordpress.com/category/data-science/)
*   [NYC Taxi Visualization Blog](https://chriswhong.github.io/nyctaxi/)
*   [Data-Mania](https://www.data-mania.com/)
*   [Data-Magnum](https://data-magnum.com/)
*   [datascopeanalytics](https://datascopeanalytics.com/blog/)
*   [Digital transformation](https://tarrysingh.com/)
*   [datascientistjourney](https://datascientistjourney.wordpress.com/category/data-science/)
*   [Data Mania Blog](https://www.data-mania.com/blog/) - [The File Drawer](https://chris-said.io/) - Chris Said's science blog
*   [Emilio Ferrara's web page](http://www.emilio.ferrara.name/)
*   [DataNews](https://datanews.tumblr.com/)
*   [Reddit TextMining](https://www.reddit.com/r/textdatamining/)
*   [Periscopic](https://periscopic.com/#!/news)
*   [Hilary Parker](https://hilaryparker.com/)
*   [Data Stories](https://datastori.es/)
*   [Data Science Lab](https://datasciencelab.wordpress.com/)
*   [Meaning of](https://www.kennybastani.com/)
*   [Adventures in Data Land](https://blog.smola.org)
*   [Dataclysm](https://theblog.okcupid.com/)
*   [FlowingData](https://flowingdata.com/) - Visualization and Statistics
*   [Calculated Risk](https://www.calculatedriskblog.com/)
*   [O'reilly Learning Blog](https://www.oreilly.com/content/topics/oreilly-learning/)
*   [Dominodatalab](https://blog.dominodatalab.com/)
*   [i am trask](https://iamtrask.github.io/) - A Machine Learning Craftsmanship Blog
*   [Vademecum of Practical Data Science](https://datasciencevademecum.wordpress.com/) - Handbook and recipes for data-driven solutions of real-world problems
*   [Dataconomy](https://dataconomy.com/) - A blog on the newly emerging data economy
*   [Springboard](https://www.springboard.com/blog/) - A blog with resources for data science learners
*   [Analytics Vidhya](https://www.analyticsvidhya.com/) - A full-fledged website about data science and analytics study material.
*   [Occam's Razor](https://www.kaushik.net/avinash/) - Focused on Web Analytics.
*   [Data School](https://www.dataschool.io/) - Data science tutorials for beginners!
*   [Colah's Blog](https://colah.github.io) - Blog for understanding Neural Networks!
*   [Sebastian's Blog](https://ruder.io/#open) - Blog for NLP and transfer learning!
*   [Distill](https://distill.pub) - Dedicated to clear explanations of machine learning!
*   [Chris Albon's Website](https://chrisalbon.com/) - Data Science and AI notes
*   [Andrew Carr](https://andrewnc.github.io/blog/blog.html) - Data Science with Esoteric programming languages
*   [floydhub](https://blog.floydhub.com/introduction-to-genetic-algorithms/) - Blog for Evolutionary Algorithms
*   [Jingles](https://jinglescode.github.io/) - Review and extract key concepts from academic papers
*   [nbshare](https://www.nbshare.io/notebooks/data-science/) - Data Science notebooks
*   [Loic Tetrel](https://ltetrel.github.io/) - Data science blog
*   [Chip Huyen's Blog](https://huyenchip.com/blog/) - ML Engineering, MLOps, and the use of ML in startups
*   [Maria Khalusova](https://www.mariakhalusova.com/) - Data science blog
*   [Aditi Rastogi](https://medium.com/@aditi2507rastogi) - ML,DL,Data Science blog
*   [Santiago Basulto](https://medium.com/@santiagobasulto) - Data Science with Python
*   [Akhil Soni](https://medium.com/@akhil0435) - ML, DL and Data Science
*   [Akhil Soni](https://akhilworld.hashnode.dev/) - ML, DL and Data Science

### Presentations

**[`^        back to top        ^`](#awesome-data-science)**

*   [How to Become a Data Scientist](https://www.slideshare.net/ryanorban/how-to-become-a-data-scientist)
*   [Introduction to Data Science](https://www.slideshare.net/NikoVuokko/introduction-to-data-science-25391618)
*   [Intro to Data Science for Enterprise Big Data](https://www.slideshare.net/pacoid/intro-to-data-science-for-enterprise-big-data)
*   [How to Interview a Data Scientist](https://www.slideshare.net/dtunkelang/how-to-interview-a-data-scientist)
*   [How to Share Data with a Statistician (⭐6.6k)](https://github.com/jtleek/datasharing)
*   [The Science of a Great Career in Data Science](https://www.slideshare.net/katemats/the-science-of-a-great-career-in-data-science)
*   [What Does a Data Scientist Do?](https://www.slideshare.net/datasciencelondon/big-data-sorry-data-science-what-does-a-data-scientist-do)
*   [Building Data Start-Ups: Fast, Big, and Focused](https://www.slideshare.net/medriscoll/driscoll-strata-buildingdatastartups25may2011clean)
*   [How to win data science competitions with Deep Learning](https://www.slideshare.net/0xdata/how-to-win-data-science-competitions-with-deep-learning)
*   [Full-Stack Data Scientist](https://www.slideshare.net/AlexeyGrigorev/fullstack-data-scientist)

### Podcasts

**[`^        back to top        ^`](#awesome-data-science)**

*   [AI at Home](https://podcasts.apple.com/us/podcast/data-science-at-home/id1069871378)
*   [AI Today](https://www.cognilytica.com/aitoday/)
*   [Adversarial Learning](https://adversariallearning.com/)
*   [Chai time Data Science](https://www.youtube.com/playlist?list=PLLvvXm0q8zUbiNdoIazGzlENMXvZ9bd3x)
*   [Data Engineering Podcast](https://www.dataengineeringpodcast.com/)
*   [Data Science at Home](https://datascienceathome.com/)
*   [Data Science Mixer](https://community.alteryx.com/t5/Data-Science-Mixer/bg-p/mixer)
*   [Data Skeptic](https://dataskeptic.com/)
*   [Data Stories](https://datastori.es/)
*   [Datacast](https://jameskle.com/writes/category/Datacast)
*   [DataFramed](https://www.datacamp.com/community/podcast)
*   [DataTalks.Club](https://anchor.fm/datatalksclub)
*   [Gradient Descent](https://wandb.ai/fully-connected/gradient-descent)
*   [Learning Machines 101](https://www.learningmachines101.com/)
*   [Let's Data (Brazil)](https://www.youtube.com/playlist?list=PLn_z5E4dh_Lj5eogejMxfOiNX3nOhmhmM)
*   [Linear Digressions](https://lineardigressions.com/)
*   [Not So Standard Deviations](https://nssdeviations.com/)
*   [O'Reilly Data Show Podcast](https://www.oreilly.com/radar/topics/oreilly-data-show-podcast/)
*   [Partially Derivative](http://partiallyderivative.com/)
*   [Superdatascience](https://www.superdatascience.com/podcast/)
*   [The Data Engineering Show](https://www.dataengineeringshow.com/)
*   [The Radical AI Podcast](https://www.radicalai.org/)
*   [What's The Point](https://fivethirtyeight.com/tag/whats-the-point/)
*   [The Analytics Engineering Podcast](https://roundup.getdbt.com/s/the-analytics-engineering-podcast)

### YouTube Videos & Channels

**[`^        back to top        ^`](#awesome-data-science)**

*   [What is machine learning?](https://www.youtube.com/watch?v=WXHM_i-fgGo)
*   [Andrew Ng: Deep Learning, Self-Taught Learning and Unsupervised Feature Learning](https://www.youtube.com/watch?v=n1ViNeWhC24)
*   [Data36 - Data Science for Beginners by Tomi Mester](https://www.youtube.com/c/TomiMesterData36comDataScienceForBeginners)
*   [Deep Learning: Intelligence from Big Data](https://www.youtube.com/watch?v=czLI3oLDe8M)
*   [Interview with Google's AI and Deep Learning 'Godfather' Geoffrey Hinton](https://www.youtube.com/watch?v=1Wp3IIpssEc)
*   [Introduction to Deep Learning with Python](https://www.youtube.com/watch?v=S75EdAcXHKk)
*   [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk)
*   [Data School](https://www.youtube.com/channel/UCnVzApLJE2ljPZSeQylSEyg) - Data Science Education
*   [Neural Nets for Newbies by Melanie Warrick (May 2015)](https://www.youtube.com/watch?v=Cu6A96TUy_o)
*   [Neural Networks video series by Hugo Larochelle](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
*   [Google DeepMind co-founder Shane Legg - Machine Super Intelligence](https://www.youtube.com/watch?v=evNCyRL3DOU)
*   [Data Science Primer](https://www.youtube.com/watch?v=cHzvYxBN9Ls\&list=PLPqVjP3T4RIRsjaW07zoGzH-Z4dBACpxY)
*   [Data Science with Genetic Algorithms](https://www.youtube.com/watch?v=lpD38NxTOnk)
*   [Data Science for Beginners](https://www.youtube.com/playlist?list=PL2zq7klxX5ATMsmyRazei7ZXkP1GHt-vs)
*   [DataTalks.Club](https://www.youtube.com/channel/UCDvErgK0j5ur3aLgn6U-LqQ)
*   [Mildlyoverfitted - Tutorials on intermediate ML/DL topics](https://www.youtube.com/channel/UCYBSjwkGTK06NnDnFsOcR7g)
*   [mlops.community - Interviews of industry experts about production ML](https://www.youtube.com/channel/UCYBSjwkGTK06NnDnFsOcR7g)
*   [ML Street Talk - Unabashedly technical and non-commercial, so you will hear no annoying pitches.](https://www.youtube.com/c/machinelearningstreettalk)
*   [Neural networks by 3Blue1Brown ](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
*   [Neural networks from scratch by Sentdex](https://www.youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3)
*   [Manning Publications YouTube channel](https://www.youtube.com/c/ManningPublications/featured)
*   [Ask Dr Chong: How to Lead in Data Science - Part 1](https://youtu.be/JYuQZii5o58)
*   [Ask Dr Chong: How to Lead in Data Science - Part 2](https://youtu.be/SzqIXV-O-ko)
*   [Ask Dr Chong: How to Lead in Data Science - Part 3](https://youtu.be/Ogwm7k_smTA)
*   [Ask Dr Chong: How to Lead in Data Science - Part 4](https://youtu.be/a9usjdzTxTU)
*   [Ask Dr Chong: How to Lead in Data Science - Part 5](https://youtu.be/MYdQq-F3Ws0)
*   [Ask Dr Chong: How to Lead in Data Science - Part 6](https://youtu.be/LOOt4OVC3hY)
*   [Regression Models: Applying simple Poisson regression](https://www.youtube.com/watch?v=9Hk8K8jhiOo)
*   [Deep Learning Architectures](https://www.youtube.com/playlist?list=PLv8Cp2NvcY8DpVcsmOT71kymgMmcr59Mf)
*   [Time Series Modelling and Analysis](https://www.youtube.com/playlist?list=PL3N9eeOlCrP5cK0QRQxeJd6GrQvhAtpBK)

## Socialize

**[`^        back to top        ^`](#awesome-data-science)**

Below are some Social Media links. Connect with other data scientists!

*   [Facebook Accounts](#facebook-accounts)
*   [Twitter Accounts](#twitter-accounts)
*   [Telegram Channels](#telegram-channels)
*   [Slack Communities](#slack-communities)
*   [GitHub Groups](#github-groups)
*   [Data Science Competitions](#data-science-competitions)

### Facebook Accounts

**[`^        back to top        ^`](#awesome-data-science)**

*   [Data](https://www.facebook.com/data)
*   [Big Data Scientist](https://www.facebook.com/Bigdatascientist)
*   [Data Science Day](https://www.facebook.com/datascienceday/)
*   [Data Science Academy](https://www.facebook.com/nycdatascience)
*   [Facebook Data Science Page](https://www.facebook.com/pages/Data-science/431299473579193?ref=br_rs)
*   [Data Science London](https://www.facebook.com/pages/Data-Science-London/226174337471513)
*   [Data Science Technology and Corporation](https://www.facebook.com/DataScienceTechnologyCorporation?ref=br_rs)
*   [Data Science - Closed Group](https://www.facebook.com/groups/1394010454157077/?ref=br_rs)
*   [Center for Data Science](https://www.facebook.com/centerdatasciences?ref=br_rs)
*   [Big data hadoop NOSQL Hive Hbase](https://www.facebook.com/groups/bigdatahadoop/)
*   [Analytics, Data Mining, Predictive Modeling, Artificial Intelligence](https://www.facebook.com/groups/data.analytics/)
*   [Big Data Analytics using R](https://www.facebook.com/groups/434352233255448/)
*   [Big Data Analytics with R and Hadoop](https://www.facebook.com/groups/rhadoop/)
*   [Big Data Learnings](https://www.facebook.com/groups/bigdatalearnings/)
*   [Big Data, Data Science, Data Mining & Statistics](https://www.facebook.com/groups/bigdatastatistics/)
*   [BigData/Hadoop Expert](https://www.facebook.com/groups/BigDataExpert/)
*   [Data Mining / Machine Learning / AI](https://www.facebook.com/groups/machinelearningforum/)
*   [Data Mining/Big Data - Social Network Ana](https://www.facebook.com/groups/dataminingsocialnetworks/)
*   [Vademecum of Practical Data Science](https://www.facebook.com/datasciencevademecum)
*   [Veri Bilimi Istanbul](https://www.facebook.com/groups/veribilimiistanbul/)
*   [The Data Science Blog](https://www.facebook.com/theDataScienceBlog/)

### Twitter Accounts

**[`^        back to top        ^`](#awesome-data-science)**

| Twitter                                                     | Description                                                                                                                                                     |
| ----------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Big Data Combine](https://twitter.com/BigDataCombine)      | Rapid-fire, live tryouts for data scientists seeking to monetize their models as trading strategies                                                             |
| Big Data Mania                                              | Data Viz Wiz, Data Journalist, Growth Hacker, Author of Data Science for Dummies (2015)                                                                         |
| [Big Data Science](https://twitter.com/analyticbridge)      | Big Data, Data Science, Predictive Modeling, Business Analytics, Hadoop, Decision and Operations Research.                                                      |
| Charlie Greenbacker                                         | Director of Data Science at @ExploreAltamira                                                                                                                    |
| [Chris Said](https://twitter.com/Chris_Said)                | Data scientist at Twitter                                                                                                                                       |
| [Clare Corthell](https://twitter.com/clarecorthell)         | Dev, Design, Data Science @mattermark #hackerei                                                                                                                 |
| [DADI Charles-Abner](https://twitter.com/DadiCharles)       | #datascientist @Ekimetrics. , #machinelearning #dataviz #DynamicCharts #Hadoop #R #Python #NLP #Bitcoin #dataenthousiast                                        |
| [Data Science Central](https://twitter.com/DataScienceCtrl) | Data Science Central is the industry's single resource for Big Data practitioners.                                                                              |
| [Data Science London](https://twitter.com/ds_ldn)           | Data Science. Big Data. Data Hacks. Data Junkies. Data Startups. Open Data                                                                                      |
| [Data Science Renee](https://twitter.com/BecomingDataSci)   | Documenting my path from SQL Data Analyst pursuing an Engineering Master's Degree to Data Scientist                                                             |
| [Data Science Report](https://twitter.com/TedOBrien93)      | Mission is to help guide & advance careers in Data Science & Analytics                                                                                          |
| [Data Science Tips](https://twitter.com/datasciencetips)    | Tips and Tricks for Data Scientists around the world! #datascience #bigdata                                                                                     |
| [Data Vizzard](https://twitter.com/DataVisualizati)         | DataViz, Security, Military                                                                                                                                     |
| [DataScienceX](https://twitter.com/DataScienceX)            |                                                                                                                                                                 |
| deeplearning4j                                              |                                                                                                                                                                 |
| [DJ Patil](https://twitter.com/dpatil)                      | White House Data Chief, VP @ RelateIQ.                                                                                                                          |
| [Domino Data Lab](https://twitter.com/DominoDataLab)        |                                                                                                                                                                 |
| [Drew Conway](https://twitter.com/drewconway)               | Data nerd, hacker, student of conflict.                                                                                                                         |
| Emilio Ferrara                                              | #Networks, #MachineLearning and #DataScience. I work on #Social Media. Postdoc at @IndianaUniv                                                                  |
| [Erin Bartolo](https://twitter.com/erinbartolo)             | Running with #BigData--enjoying a love/hate relationship with its hype. @iSchoolSU #DataScience Program Mgr.                                                    |
| [Greg Reda](https://twitter.com/gjreda)                     | Working @ *GrubHub* about data and pandas                                                                                                                       |
| [Gregory Piatetsky](https://twitter.com/kdnuggets)          | KDnuggets President, Analytics/Big Data/Data Mining/Data Science expert, KDD & SIGKDD co-founder, was Chief Scientist at 2 startups, part-time philosopher.     |
| [Hadley Wickham](https://twitter.com/hadleywickham)         | Chief Scientist at RStudio, and an Adjunct Professor of Statistics at the University of Auckland, Stanford University, and Rice University.                     |
| [Hakan Kardas](https://twitter.com/hakan_kardes)            | Data Scientist                                                                                                                                                  |
| [Hilary Mason](https://twitter.com/hmason)                  | Data Scientist in Residence at @accel.                                                                                                                          |
| [Jeff Hammerbacher](https://twitter.com/hackingdata)        | ReTweeting about data science                                                                                                                                   |
| [John Myles White](https://twitter.com/johnmyleswhite)      | Scientist at Facebook and Julia developer. Author of Machine Learning for Hackers and Bandit Algorithms for Website Optimization. Tweets reflect my views only. |
| [Juan Miguel Lavista](https://twitter.com/BDataScientist)   | Principal Data Scientist @ Microsoft Data Science Team                                                                                                          |
| [Julia Evans](https://twitter.com/b0rk)                     | Hacker - Pandas - Data Analyze                                                                                                                                  |
| [Kenneth Cukier](https://twitter.com/kncukier)              | The Economist's Data Editor and co-author of Big Data (<http://www.big-data-book.com/>).                                                                        |
| Kevin Davenport                                             | Organizer of <https://www.meetup.com/San-Diego-Data-Science-R-Users-Group/>                                                                                     |
| [Kevin Markham](https://twitter.com/justmarkham)            | Data science instructor, and founder of [Data School](https://www.dataschool.io/)                                                                               |
| [Kim Rees](https://twitter.com/krees)                       | Interactive data visualization and tools. Data flaneur.                                                                                                         |
| [Kirk Borne](https://twitter.com/KirkDBorne)                | DataScientist, PhD Astrophysicist, Top #BigData Influencer.                                                                                                     |
| Linda Regber                                                | Data storyteller, visualizations.                                                                                                                               |
| [Luis Rei](https://twitter.com/lmrei)                       | PhD Student. Programming, Mobile, Web. Artificial Intelligence, Intelligent Robotics Machine Learning, Data Mining, Natural Language Processing, Data Science.  |
| Mark Stevenson                                              | Data Analytics Recruitment Specialist at Salt (@SaltJobs)  Analytics - Insight - Big Data - Data science                                                        |
| [Matt Harrison](https://twitter.com/__mharrison__)          | Opinions of full-stack Python guy, author, instructor, currently playing Data Scientist. Occasional fathering, husbanding, organic gardening.                   |
| [Matthew Russell](https://twitter.com/ptwobrussell)         | Mining the Social Web.                                                                                                                                          |
| [Mert Nuhoğlu](https://twitter.com/mertnuhoglu)             | Data Scientist at BizQualify, Developer                                                                                                                         |
| [Monica Rogati](https://twitter.com/mrogati)                | Data @ Jawbone. Turned data into stories & products at LinkedIn. Text mining, applied machine learning, recommender systems. Ex-gamer, ex-machine coder; namer. |
| [Noah Iliinsky](https://twitter.com/noahi)                  | Visualization & interaction designer. Practical cyclist. Author of vis books: <https://www.oreilly.com/pub/au/4419>                                             |
| [Paul Miller](https://twitter.com/PaulMiller)               | Cloud Computing/ Big Data/ Open Data Analyst & Consultant. Writer, Speaker & Moderator. Gigaom Research Analyst.                                                |
| [Peter Skomoroch](https://twitter.com/peteskomoroch)        | Creating intelligent systems to automate tasks & improve decisions. Entrepreneur, ex-Principal Data Scientist @LinkedIn. Machine Learning, ProductRei, Networks |
| [Prash Chan](https://twitter.com/MDMGeek)                   | Solution Architect @ IBM, Master Data Management, Data Quality & Data Governance Blogger. Data Science, Hadoop, Big Data & Cloud.                               |
| [Quora Data Science](https://twitter.com/q_datascience)     | Quora's data science topic                                                                                                                                      |
| [R-Bloggers](https://twitter.com/Rbloggers)                 | Tweet blog posts from the R blogosphere, data science conferences, and (!) open jobs for data scientists.                                                       |
| [Rand Hindi](https://twitter.com/randhindi)                 |                                                                                                                                                                 |
| [Randy Olson](https://twitter.com/randal_olson)             | Computer scientist researching artificial intelligence. Data tinkerer. Community leader for @DataIsBeautiful. #OpenScience advocate.                            |
| [Recep Erol](https://twitter.com/EROLRecep)                 | Data Science geek @ UALR                                                                                                                                        |
| [Ryan Orban](https://twitter.com/ryanorban)                 | Data scientist, genetic origamist, hardware aficionado                                                                                                          |
| [Sean J. Taylor](https://twitter.com/seanjtaylor)           | Social Scientist. Hacker. Facebook Data Science Team. Keywords: Experiments, Causal Inference, Statistics, Machine Learning, Economics.                         |
| [Silvia K. Spiva](https://twitter.com/silviakspiva)         | #DataScience at Cisco                                                                                                                                           |
| [Harsh B. Gupta](https://twitter.com/harshbg)               | Data Scientist at BBVA Compass                                                                                                                                  |
| [Spencer Nelson](https://twitter.com/spenczar_n)            | Data nerd                                                                                                                                                       |
| [Talha Oz](https://twitter.com/tozCSS)                      | Enjoys ABM, SNA, DM, ML, NLP, HI, Python, Java. Top percentile Kaggler/data scientist                                                                           |
| [Tasos Skarlatidis](https://twitter.com/anskarl)            | Complex Event Processing, Big Data, Artificial Intelligence and Machine Learning. Passionate about programming and open-source.                                 |
| [Terry Timko](https://twitter.com/Terry_Timko)              | InfoGov; Bigdata; Data as a Service; Data Science; Open, Social & Business Data Convergence                                                                     |
| [Tony Baer](https://twitter.com/TonyBaer)                   | IT analyst with Ovum covering Big Data & data management with some systems engineering thrown in.                                                               |
| [Tony Ojeda](https://twitter.com/tonyojeda3)                | Data Scientist , Author , Entrepreneur. Co-founder @DataCommunityDC. Founder @DistrictDataLab. #DataScience #BigData #DataDC                                    |
| [Vamshi Ambati](https://twitter.com/vambati)                | Data Science @ PayPal. #NLP, #machinelearning; PhD, Carnegie Mellon alumni (Blog: <https://allthingsds.wordpress.com> )                                         |
| [Wes McKinney](https://twitter.com/wesmckinn)               | Pandas (Python Data Analysis library).                                                                                                                          |
| [WileyEd](https://twitter.com/WileyEd)                      | Senior Manager - @Seagate Big Data Analytics @McKinsey Alum #BigData + #Analytics Evangelist #Hadoop, #Cloud, #Digital, & #R Enthusiast                         |
| [WNYC Data News Team](https://twitter.com/datanews)         | The data news crew at @WNYC. Practicing data-driven journalism, making it visual, and showing our work.                                                         |
| [Alexey Grigorev](https://twitter.com/Al_Grigor)            | Data science author                                                                                                                                             |
| [İlker Arslan](https://twitter.com/ilkerarslan_35)          | Data science author. Shares mostly about Julia programming                                                                                                      |
| [INEVITABLE](https://twitter.com/WeAreInevitable)           | AI & Data Science Start-up Company based in England, UK                                                                                                         |

### Telegram Channels

**[`^        back to top        ^`](#awesome-data-science)**

*   [Open Data Science](https://t.me/opendatascience) – First Telegram Data Science channel. Covering all technical and popular staff about anything related to Data Science: AI, Big Data, Machine Learning, Statistics, general Math and the applications of former.
*   [Loss function porn](https://t.me/loss_function_porn) — Beautiful posts on DS/ML theme with video or graphic visualization.
*   [Machinelearning](https://t.me/ai_machinelearning_big_data) – Daily ML news.

### Slack Communities

[top](#awesome-data-science)

*   [DataTalks.Club](https://datatalks.club)

### GitHub Groups

*   [Berkeley Institute for Data Science](https://github.com/BIDS)

### Data Science Competitions

Some data mining competition platforms

*   [Kaggle](https://www.kaggle.com/)
*   [DrivenData](https://www.drivendata.org/)
*   [Analytics Vidhya](https://datahack.analyticsvidhya.com/)
*   [InnoCentive](https://www.innocentive.com/)
*   [Microprediction](https://www.microprediction.com/python-1)

## Fun

*   [Infographic](#infographics)
*   [Datasets](#datasets)
*   [Comics](#comics)

### Infographics

**[`^        back to top        ^`](#awesome-data-science)**

| Preview                                                                                                                                                                                                                                     | Description                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [<img src="https://i.imgur.com/0OoLaa5.png" width="150" />](https://i.imgur.com/0OoLaa5.png)                                                                                                                                                | [Key differences of a data scientist vs. data engineer](https://searchbusinessanalytics.techtarget.com/feature/Key-differences-of-a-data-scientist-vs-data-engineer)                                                                                         |
| [<img src="https://cloud.githubusercontent.com/assets/182906/19517857/604f88d8-960c-11e6-97d6-16c9738cb824.png" width="150" />](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/DataScienceEightSteps_Full.png)                    | A visual guide to Becoming a Data Scientist in 8 Steps by [DataCamp](https://www.datacamp.com) [(img)](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/DataScienceEightSteps_Full.png)                                                              |
| [<img src="https://i.imgur.com/W2t2Roz.png" width="150" />](https://i.imgur.com/FxsL3b8.png)                                                                                                                                                | Mindmap on required skills ([img](https://i.imgur.com/FxsL3b8.png))                                                                                                                                                                                          |
| [<img src="https://i.imgur.com/rb9ruaa.png" width="150" />](https://nirvacana.com/thoughts/wp-content/uploads/2013/07/RoadToDataScientist1.png)                                                                                             | Swami Chandrasekaran made a [Curriculum via Metro map](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/).                                                                                                                                 |
| [<img src="https://i.imgur.com/XBgKF2l.png" width="150" />](https://i.imgur.com/4ZBBvb0.png)                                                                                                                                                | by [@kzawadz](https://twitter.com/kzawadz) via [twitter](https://twitter.com/MktngDistillery/status/538671811991715840)                                                                                                                                      |
| [<img src="https://i.imgur.com/l9ZGtal.jpg" width="150" />](https://i.imgur.com/xLY3XZn.jpg)                                                                                                                                                | By [Data Science Central](https://www.datasciencecentral.com/)                                                                                                                                                                                               |
| [<img src="https://i.imgur.com/TWkB4X6.png" width="150" />](https://i.imgur.com/0TydZ4M.png)                                                                                                                                                | Data Science Wars: R vs Python                                                                                                                                                                                                                               |
| [<img src="https://i.imgur.com/gtTlW5I.png" width="150" />](https://i.imgur.com/HnRwlce.png)                                                                                                                                                | How to select statistical or machine learning techniques                                                                                                                                                                                                     |
| [<img src="https://scikit-learn.org/1.5/_downloads/b82bf6cd7438a351f19fac60fbc0d927/ml_map.svg" width="150" />](https://scikit-learn.org/1.5/_downloads/b82bf6cd7438a351f19fac60fbc0d927/ml_map.svg)                                        | [Choosing the Right Estimator](https://scikit-learn.org/1.5/machine_learning_map.html#choosing-the-right-estimator)                                                                                                                                          |
| [<img src="https://i.imgur.com/3JSyUq1.png" width="150" />](https://i.imgur.com/uEqMwZa.png)                                                                                                                                                | The Data Science Industry: Who Does What                                                                                                                                                                                                                     |
| [<img src="https://i.imgur.com/DQqFwwy.png" width="150" />](https://i.imgur.com/RsHqY84.png)                                                                                                                                                | Data Science ~~Venn~~ Euler Diagram                                                                                                                                                                                                                          |
| [<img src="https://www.springboard.com/blog/wp-content/uploads/2016/03/20160324_springboard_vennDiagram.png" width="150" height="150" />](https://www.springboard.com/blog/wp-content/uploads/2016/03/20160324_springboard_vennDiagram.png) | Different Data Science Skills and Roles from [Springboard](https://www.springboard.com)                                                                                                                                                                      |
| [<img src="https://data-literacy.geckoboard.com/assets/img/data-fallacies-to-avoid-preview.jpg" width="150" alt="Data Fallacies To Avoid" />](https://data-literacy.geckoboard.com/poster/)                                                 | A simple and friendly way of teaching your non-data scientist/non-statistician colleagues [how to avoid mistakes with data](https://data-literacy.geckoboard.com/poster/). From Geckoboard's [Data Literacy Lessons](https://data-literacy.geckoboard.com/). |

### Datasets

**[`^        back to top        ^`](#awesome-data-science)**

*   [Academic Torrents](https://academictorrents.com/)
*   [ADS-B Exchange](https://www.adsbexchange.com/data-samples/) - Specific datasets for aircraft and Automatic Dependent Surveillance-Broadcast (ADS-B) sources.
*   [hadoopilluminated.com](https://hadoopilluminated.com/hadoop_illuminated/Public_Bigdata_Sets.html)
*   [data.gov](https://catalog.data.gov/dataset) - The home of the U.S. Government's open data
*   [United States Census Bureau](https://www.census.gov/)
*   [usgovxml.com](https://usgovxml.com/)
*   [enigma.com](https://enigma.com/) - Navigate the world of public data - Quickly search and analyze billions of public records published by governments, companies and organizations.
*   [datahub.io](https://datahub.io/)
*   [aws.amazon.com/datasets](https://aws.amazon.com/datasets/)
*   [datacite.org](https://datacite.org/)
*   [The official portal for European data](https://data.europa.eu/en)
*   [NASDAQ:DATA](https://data.nasdaq.com/) - Nasdaq Data Link A premier source for financial, economic and alternative datasets.
*   [figshare.com](https://figshare.com/)
*   [GeoLite Legacy Downloadable Databases](https://dev.maxmind.com/geoip)
*   [Quora's Big Datasets Answer](https://www.quora.com/Where-can-I-find-large-datasets-open-to-the-public)
*   [Public Big Data Sets](https://hadoopilluminated.com/hadoop_illuminated/Public_Bigdata_Sets.html)
*   [Kaggle Datasets](https://www.kaggle.com/datasets)
*   [A Deep Catalog of Human Genetic Variation](https://www.internationalgenome.org/data)
*   [A community-curated database of well-known people, places, and things](https://developers.google.com/freebase/)
*   [Google Public Data](https://www.google.com/publicdata/directory)
*   [World Bank Data](https://data.worldbank.org/)
*   [NYC Taxi data](https://chriswhong.github.io/nyctaxi/)
*   [Open Data Philly](https://www.opendataphilly.org/) Connecting people with data for Philadelphia
*   [grouplens.org](https://grouplens.org/datasets/) Sample movie (with ratings), book and wiki datasets
*   [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/) - contains data sets good for machine learning
*   [research-quality data sets](https://web.archive.org/web/20150320022752/https://bitly.com/bundles/hmason/1) by [Hilary Mason](https://web.archive.org/web/20150501033715/https://bitly.com/u/hmason/bundles)
*   [National Centers for Environmental Information](https://www.ncei.noaa.gov/)
*   [ClimateData.us](https://www.climatedata.us/) (related: [U.S. Climate Resilience Toolkit](https://toolkit.climate.gov/))
*   [r/datasets](https://www.reddit.com/r/datasets/)
*   [MapLight](https://www.maplight.org/data-series) - provides a variety of data free of charge for uses that are freely available to the general public. Click on a data set below to learn more
*   [GHDx](https://ghdx.healthdata.org/) - Institute for Health Metrics and Evaluation - a catalog of health and demographic datasets from around the world and including IHME results
*   [St. Louis Federal Reserve Economic Data - FRED](https://fred.stlouisfed.org/)
*   [New Zealand Institute of Economic Research – Data1850](https://data1850.nz/)
*   [Open Data Sources (⭐507)](https://github.com/datasciencemasters/data)
*   [UNICEF Data](https://data.unicef.org/)
*   [undata](https://data.un.org/)
*   [NASA SocioEconomic Data and Applications Center - SEDAC](https://earthdata.nasa.gov/centers/sedac-daac)
*   [The GDELT Project](https://www.gdeltproject.org/)
*   [Sweden, Statistics](https://www.scb.se/en/)
*   [StackExchange Data Explorer](https://data.stackexchange.com) - an open source tool for running arbitrary queries against public data from the Stack Exchange network.
*   [San Fransisco Government Open Data](https://datasf.org/opendata/)
*   [IBM Asset Dataset](https://developer.ibm.com/exchanges/data/)
*   [Open data Index](http://index.okfn.org/)
*   [Public Git Archive (⭐328)](https://github.com/src-d/datasets/tree/master/PublicGitArchive)
*   [GHTorrent](https://ghtorrent.org/)
*   [Microsoft Research Open Data](https://msropendata.com/)
*   [Open Government Data Platform India](https://data.gov.in/)
*   [Google Dataset Search (beta)](https://datasetsearch.research.google.com/)
*   [NAYN.CO Turkish News with categories (⭐3)](https://github.com/naynco/nayn.data)
*   [Covid-19 (⭐1.2k)](https://github.com/datasets/covid-19)
*   [Covid-19 Google (⭐118)](https://github.com/google-research/open-covid-19-data)
*   [Enron Email Dataset](https://www.cs.cmu.edu/~./enron/)
*   [5000 Images of Clothes (⭐106)](https://github.com/alexeygrigorev/clothing-dataset)
*   [IBB Open Portal](https://data.ibb.gov.tr/en/)
*   [The Humanitarian Data Exchange](https://data.humdata.org/)
*   [250k+ Job Postings](https://aws.amazon.com/marketplace/pp/prodview-p2554p3tczbes) - An expanding dataset of historical job postings from Luxembourg from 2020 to today. Free with 250k+ job postings hosted on AWS Data Exchange.

### Comics

**[`^        back to top        ^`](#awesome-data-science)**

*   [Comic compilation](https://medium.com/@nikhil_garg/a-compilation-of-comics-explaining-statistics-data-science-and-machine-learning-eeefbae91277)
*   [Cartoons](https://www.kdnuggets.com/websites/cartoons.html)
*   [Data Science Cartoons](https://www.cartoonstock.com/directory/d/data_science.asp)
*   [Data Science: The XKCD Edition](https://davidlindelof.com/data-science-the-xkcd-edition/)

## Other Awesome Lists

*   Other amazingly awesome lists can be found in the [awesome-awesomeness (⭐32k)](https://github.com/bayandin/awesome-awesomeness)
*   [Awesome Machine Learning (⭐67k)](https://github.com/josephmisiti/awesome-machine-learning)
*   [lists (⭐10k)](https://github.com/jnv/lists)
*   [awesome-dataviz (⭐3.9k)](https://github.com/javierluraschi/awesome-dataviz)
*   [awesome-python (⭐234k)](https://github.com/vinta/awesome-python)
*   [Data Science IPython Notebooks. (⭐28k)](https://github.com/donnemartin/data-science-ipython-notebooks)
*   [awesome-r (⭐6.1k)](https://github.com/qinwf/awesome-R)
*   [awesome-datasets (⭐62k)](https://github.com/awesomedata/awesome-public-datasets)
*   [awesome-Machine Learning & Deep Learning Tutorials (⭐16k)](https://github.com/ujjwalkarn/Machine-Learning-Tutorials/blob/master/README.md)
*   [Awesome Data Science Ideas (⭐674)](https://github.com/JosPolfliet/awesome-ai-usecases)
*   [Machine Learning for Software Engineers (⭐28k)](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
*   [Community Curated Data Science Resources](https://hackr.io/tutorials/learn-data-science)
*   [Awesome Machine Learning On Source Code (⭐6.3k)](https://github.com/src-d/awesome-machine-learning-on-source-code)
*   [Awesome Community Detection (⭐2.4k)](https://github.com/benedekrozemberczki/awesome-community-detection)
*   [Awesome Graph Classification (⭐4.8k)](https://github.com/benedekrozemberczki/awesome-graph-classification)
*   [Awesome Decision Tree Papers (⭐2.4k)](https://github.com/benedekrozemberczki/awesome-decision-tree-papers)
*   [Awesome Fraud Detection Papers (⭐1.7k)](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers)
*   [Awesome Gradient Boosting Papers (⭐1k)](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers)
*   [Awesome Computer Vision Models (⭐518)](https://github.com/nerox8664/awesome-computer-vision-models)
*   [Awesome Monte Carlo Tree Search (⭐664)](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers)
*   [Glossary of common statistics and ML terms](https://www.analyticsvidhya.com/glossary-of-common-statistics-and-machine-learning-terms/)
*   [100 NLP Papers (⭐3.8k)](https://github.com/mhagiwara/100-nlp-papers)
*   [Awesome Game Datasets (⭐802)](https://github.com/leomaurodesenv/game-datasets#readme)
*   [Data Science Interviews Questions (⭐9.2k)](https://github.com/alexeygrigorev/data-science-interviews)
*   [Awesome Explainable Graph Reasoning (⭐2k)](https://github.com/AstraZeneca/awesome-explainable-graph-reasoning)
*   [Top Data Science Interview Questions](https://www.interviewbit.com/data-science-interview-questions/)
*   [Awesome Drug Synergy, Interaction and Polypharmacy Prediction (⭐90)](https://github.com/AstraZeneca/awesome-drug-pair-scoring)
*   [Deep Learning Interview Questions](https://www.adaface.com/blog/deep-learning-interview-questions/)
*   [Top Future Trends in Data Science in 2023](https://medium.com/the-modern-scientist/top-future-trends-in-data-science-in-2023-3e616c8998b8)
*   [How Generative AI Is Changing Creative Work](https://hbr.org/2022/11/how-generative-ai-is-changing-creative-work)
*   [What is generative AI?](https://www.techtarget.com/searchenterpriseai/definition/generative-AI)
*   [Top 100+ Machine Learning Interview Questions (Beginner to Advanced)](https://www.appliedaicourse.com/blog/machine-learning-interview-questions/)
*   [Data Science Projects (⭐1.9k)](https://github.com/veb-101/Data-Science-Projects)
*   [Is Data Science a Good Career?](https://www.scaler.com/blog/is-data-science-a-good-career/)
*   [The Future of Data Science: Predictions and Trends](https://www.appliedaicourse.com/blog/future-of-data-science/)
*   [Data Science and Machine Learning: What’s The Difference?](https://www.appliedaicourse.com/blog/data-science-and-machine-learning-whats-the-difference/)
*   [AI in Data Science: Uses, Roles, and Tools](https://www.scaler.com/blog/ai-in-data-science/)
*   [Top 13 Data Science Programming Languages](https://www.appliedaicourse.com/blog/data-science-programming-languages/)

### Hobby

*   [Awesome Music Production (⭐1.1k)](https://github.com/ad-si/awesome-music-production)

<!-- Global site tag (gtag.js) - Google Analytics -->

<script async src="https://www.googletagmanager.com/gtag/js?id=G-YL0RV0E5XZ"></script>

<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-YL0RV0E5XZ');
</script>

