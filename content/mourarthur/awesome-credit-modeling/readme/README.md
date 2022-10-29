# Awesome Credit Modeling Overview

A collection of awesome papers, articles and various resources on credit and credit risk modeling

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mourarthur/awesome-credit-modeling/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 mourarthur/awesome-credit-modeling](https://github.com/mourarthur/awesome-credit-modeling) · ⭐ 65 · 🏷️ Miscellaneous

[ [Daily](/content/mourarthur/awesome-credit-modeling/README.md) / [Weekly](/content/mourarthur/awesome-credit-modeling/week/README.md) / Overview ]

---

# Awesome Credit Modeling [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> A growing collection of awesome papers, articles and various resources on credit scoring and credit risk modeling.

Credit scoring is the term used to describe formal statistical methods used for classifying applicants for credit into risk classes. Lenders use such classifications to assess an applicant's creditworthiness and probability of default.

## Contents

*   [Introduction](#introduction)
*   [Credit Scoring](#credit-scoring)
*   [Institutional Credit Risk](#institutional-credit-risk)
*   [Peer-to-Peer Lending](#peer-to-peer-lending)
*   [Sample Selection](#sample-selection)
*   [Feature Selection](#feature-selection)
*   [Model Explainability](#model-explainability)

## Introduction

*   [Statistical Classification Methods in Consumer Credit Scoring: A Review](https://www.jstor.org/stable/2983268) - Classic introduction and review of the subject of credit scoring.

*   [Consumer Finance: Challenges for Operational Research](https://www.jstor.org/stable/40540227) - Reviews the development of credit scoring (the way of assessing risk in consumer finance) and what is meant by a credit score. Outlines 10 challenges for Operational Research to support modelling in consumer finance.

*   [Machine Learning in Credit Risk Modeling](https://www.slideshare.net/YvanDeMunck/machine-learning-in-credit-risk-modeling-a-james-white-paper) - James (formerly CrowdProcess) is a now-defunct online credit risk management startup that provided risk management tools to financial institutions. This whitepaper offers an overview of machine learning applications in the field of credit risk modeling.

*   ['Lending by numbers': credit scoring and the constitution of risk within American consumer credit](https://www.tandfonline.com/doi/abs/10.1080/03085140601089846) - Examines how statistical credit-scoring technologies became applied by lenders to the problem of controlling levels of default within American consumer credit. Explores their perceived methodological, procedural and temporal risks.

*   [Machine Learning in Financial Crisis Prediction: A Survey](https://ieeexplore.ieee.org/document/6069610) - Reviews 130 journal papers from the period between 1995 and 2010, focusing on the development of state-of-the-art machine-learning techniques for bankruptcy prediction and credit score modeling. Also presents their current achievements and limitations.

*   [Fintech and big tech credit: a new database](https://www.bis.org/publ/work887.pdf) - This Working Paper by the Bank of International Settlements, while not as focused on credit risk, maps the conditions for and niches occupied by alternative credit, be it provided by fintechs or big tech companies.

## Credit Scoring

*   [Benchmarking state-of-the-art classification algorithms for credit scoring: An update of research](https://www.sciencedirect.com/science/article/abs/pii/S0377221715004208) - There have been several advancements in scorecard development, including novel learning methods, performance measures and techniques to reliably compare different classifiers, which the credit scoring literature does not reflect. This paper compares several novel classification algorithms to the state-of-the-art in credit scoring. In addition, the extent to which the assessment of alternative scorecards differs across established and novel indicators of predictive accuracy is examined.

*   [Classification methods applied to credit scoring: Systematic review and overall comparison](https://www.sciencedirect.com/science/article/abs/pii/S1876735416300101) - The need for controlling and effectively managing credit risk has led financial institutions to excel in improving techniques designed for this purpose, resulting in the development of various quantitative models by financial institutions and consulting companies. Hence, the growing number of academic studies about credit scoring shows a variety of classification methods applied to discriminate good and bad borrowers. This paper aims to present a systematic literature review relating theory and application of binary classification techniques for credit scoring financial analysis. The general results show the use and importance of the main techniques for credit rating, as well as some of the scientific paradigm changes throughout the years.

*   [Classifier Technology and the Illusion of Progress](https://projecteuclid.org/euclid.ss/1149600839) - A great many tools have been developed for supervised classification, ranging from early methods such as linear discriminant analysis through to modern developments such as neural networks and support vector machines. A large number of comparative studies have been conducted in attempts to establish the relative superiority of these methods. This paper argues that these comparisons often fail to take into account important aspects of real problems, so that the apparent superiority of more sophisticated methods may be something of an illusion. In particular, simple methods typically yield performance almost as good as more sophisticated methods, to the extent that the difference in performance may be swamped by other sources of uncertainty that generally are not considered in the classical supervised classification paradigm.

*   [Financial credit risk assessment: a recent review](https://dl.acm.org/doi/10.1007/s10462-015-9434-x) - Summarizes the traditional statistical models and state-of-the-art intelligent methods for financial distress forecasting, with emphasis on the most recent achievements.

*   [Good practice in retail credit scorecard assessment](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2601932) - In retail banking, predictive statistical models called ‘scorecards’ are used to assign customers to classes, and hence to appropriate actions or interventions. Such assignments are made on the basis of whether a customer's predicted score is above or below a given threshold. The predictive power of such scorecards gradually deteriorates over time, so that performance needs to be monitored. Common performance measures used in the retail banking sector include the Gini coefficient, the Kolmogorov–Smirnov statistic, the mean difference, and the information value. However, all of these measures use irrelevant information about the magnitude of scores, and fail to use crucial information relating to numbers misclassified. The result is that such measures can sometimes be seriously misleading, resulting in poor quality decisions being made, and mistaken actions being taken.

*   [A literature review on the application of evolutionary computing to credit scoring](https://link.springer.com/article/10.1057/jors.2012.145) - The aim of this paper is to summarize the most recent developments in the application of evolutionary algorithms to credit scoring by means of a thorough review of scientific articles published during the period 2000–2012.

*   [Machine learning predictivity applied to consumer creditworthiness](https://fbj.springeropen.com/articles/10.1186/s43093-020-00041-w) - Analyzes the adequacy of borrower’s classification models using a Brazilian bank’s loan database, exploring machine learning techniques, and comparing their predictive accuracy with a benchmark based on a Logistic Regression model. Comparisons are based on usual classification performance metrics.

*   [Consumer credit-risk models via machine-learning algorithms](https://alo.mit.edu/wp-content/uploads/2015/06/Household-behaviorConsumer-credit-riskCredit-card-borrowingMachine-learningNonparametric-estimation.pdf) - The authors apply machine-learning techniques to construct nonlinear nonparametric forecasting models of consumer credit risk. They are able to construct out-of-sample forecasts that signiﬁcantly improve the classiﬁcation rates of credit-card-holder delinquencies and defaults.

*   [Example-Dependent Cost-Sensitive Logistic Regression for Credit Scoring](https://ieeexplore.ieee.org/document/7033125) - Several real-world classification problems are example-dependent cost-sensitive in nature, where the costs due to misclassification vary between examples. Credit scoring is a typical example of cost-sensitive classification. However, it is usually treated using methods that do not take into account the real financial costs associated with the lending business.

*   [Credit scoring using the clustered support vector machine](https://www.sciencedirect.com/science/article/abs/pii/S0957417414005119) - Introduces the use of the clustered support vector machine (CSVM) for credit scorecard development. This recently designed algorithm addresses some of the limitations associated with traditional nonlinear support vector machine (SVM) based methods for classification. Specifically, it is well known that as historical credit scoring datasets get large, these nonlinear approaches, while highly accurate, become computationally expensive. The CSVM can achieve comparable levels of classification performance while remaining relatively cheap computationally.

*   [A comparative study on base classifiers in ensemble methods for credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417416306947) - In the last years, the application of artificial intelligence methods on credit risk assessment has meant an improvement over classic methods. Recent works show that ensembles of classifiers achieve the better results for this kind of tasks.

*   [Multiple classifier application to credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0957417409008847) - ([Corrigendum](https://www.sciencedirect.com/science/article/pii/S0957417410012364)) - This paper explores the predicted behaviour of five classifiers for different types of noise in terms of credit risk prediction accuracy, and how such accuracy could be improved by using classifier ensembles.

*   [Recent developments in consumer credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011866) - The riskiness of lending to a credit applicant is usually estimated using a logistic regression model though researchers have considered many other types of classifier, but data quality issues may prevent these laboratory based results from being achieved in practice. The training of a classifier on a sample of accepted applicants rather than on a sample representative of the applicant population seems not to result in bias though it does result in difficulties in setting the cut off.

*   [A survey of credit and behavioural scoring: forecasting financial risk of lending to consumers](https://www.sciencedirect.com/science/article/abs/pii/S0169207000000340) - Surveys the techniques used — both statistical and operational research based — to help organisations decide whether or not to grant credit to consumers. It also discusses the need to incorporate economic conditions into the scoring systems and the way the systems could change from estimating the probability of a consumer defaulting to estimating the profit a consumer will bring to the lending organisation.

*   [The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients](https://www.sciencedirect.com/science/article/abs/pii/S0957417407006719) - This research compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification.

*   [Super-App Behavioral Patterns in Credit Risk Models: Financial, Statistical and Regulatory Implications](https://arxiv.org/abs/2005.14658) - Presents the impact of alternative data that originates from an app-based marketplace, in contrast to traditional bureau data, upon credit scoring models. These alternative data sources have shown themselves to be immensely powerful in predicting borrower behavior in segments traditionally underserved by banks and financial institutions. At the same time alternative data must be carefully validated to overcome regulatory hurdles across diverse jurisdictions.

## Institutional Credit Risk

*   [Availability of Credit to Small Businesses](https://www.federalreserve.gov/publications/2017-september-availability-of-credit-to-small-businesses.htm) - Section 2227 of the Economic Growth and Regulatory Paperwork Reduction Act of 1996 requires that, every five years, the Board of Governors of the Federal Reserve System submit a report to the Congress detailing the extent of small business lending by all creditors. The most recent one is dated September, 2017.

*   [Credit Scoring and the Availability, Price, and Risk of Small Business Credit](https://muse.jhu.edu/article/181124) - Finds that small business credit scoring is associated with expanded quantities, higher averages prices, and greater average risk levels for small business credits under $100,000, after controlling for bank size and other differences across banks.

*   [Credit Risk Assessment Using Statistical and Machine Learning: Basic Methodology and Risk Modeling Applications](https://link.springer.com/article/10.1023/A:1008699112516) - An important ingredient to accomplish the goal of a more efficient use of resources through risk modeling is to find accurate predictors of individual risk in the credit portfolios of institutions. In this context the authors make a comparative analysis of different statistical and machine learning modeling methods of classification on a mortgage loan dataset with the motivation to understand their limitations and potential.

*   [Random Survival Forests Models for SME Credit Risk Measurement](https://link.springer.com/article/10.1007/s11009-008-9078-2) - Extends the existing literature on empirical research in the field of credit risk default for Small Medium Enterprizes (SMEs), proposing a non-parametric approach based on Random Survival Forests (RSF) and comparing its performance with a standard logit model.

*   [Modeling Institutional Credit Risk with Financial News](https://arxiv.org/abs/2004.08204) - Current work in downgrade risk modeling depends on multiple variations of quantitative measures provided by third-party rating agencies and risk management consultancy companies. There has been a wide push into using alternative sources of data, such as financial news, earnings call transcripts, or social media content, to possibly gain a competitive edge in the industry. This paper proposes a predictive downgrade model using solely news data represented by neural network embeddings.

*   [Bankruptcy prediction for credit risk using neural networks: A survey and new results](https://ieeexplore.ieee.org/document/935101) - The prediction of corporate bankruptcies is an important and widely studied topic since it can have significant impact on bank lending decisions and profitability. This work reviews the topic of bankruptcy prediction, with emphasis on neural-network (NN) models and develops an NN bankruptcy prediction model, proposing novel indicators for the NN system.

## Peer-to-Peer Lending

*   [Network based credit risk models](https://www.tandfonline.com/doi/abs/10.1080/08982112.2019.1655159) - Peer-to-Peer lending platforms may lead to cost reduction, and to an improved user experience. These improvements may come at the price of inaccurate credit risk measurements. The authors propose to augment traditional credit scoring methods with “alternative data” that consist of centrality measures derived from similarity networks among borrowers, deduced from their financial ratios.

## Sample Selection

*   [Reject inference in application scorecards: evidence from France](https://econpapers.repec.org/paper/drmwpaper/2016-10.htm) - Good introduction and discussion on the topic.

*   [Reject inference, augmentation, and sample selection](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011969) - In-depth discussion.

*   [Instance sampling in credit scoring: An empirical study of sample size and balancing](http://www.research.lancs.ac.uk/portal/en/publications/instance-sampling-in-credit-scoring-an-empirical-study-of-sample-size-and-balancing\(89b83914-c7f2-499a-8fa1-844d6cb6004d\).html) - Discusses the traditional sampling conventions in credit modeling and argues that using larger samples provides a significant increase in accuracy across algorithms.

## Feature Selection

*   [A multi-objective approach for profit-driven feature selection in credit scoring](https://www.sciencedirect.com/science/article/pii/S0167923619300570) - In credit scoring, feature selection aims at removing irrelevant data to improve the performance and interpretability of the scorecard. Standard techniques treat feature selection as a single-objective task and rely on statistical criteria such as correlation. Recent studies suggest that using profit-based indicators may improve the quality of scoring models for businesses.

*   [Data mining feature selection for credit scoring models](https://link.springer.com/article/10.1057/palgrave.jors.2601976) - The features used may have an important effect on the performance of credit scoring models. The process of choosing the best set of features for credit scoring models is usually unsystematic and dominated by somewhat arbitrary trial. This paper presents an empirical study of four machine learning feature selection methods.

*   [Combination of feature selection approaches with SVM in credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417409010719) - An effective classificatory model in credit scoring will objectively help managers who rely on intuitive experience. This study proposes four approaches using the SVM (support vector machine) classifier for feature selection that retain sufficient information for classification purposes.

## Model Explainability

*   [Explainable Machine learning in Credit Risk Management](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3506274) - Proposes an explainable AI model that can be used in credit risk management and, in particular, in measuring the risks that arise when credit is borrowed employing credit scoring platforms.

*   [Machine learning explainability in finance: an application to default risk analysis](https://www.bankofengland.co.uk/working-paper/2019/machine-learning-explainability-in-finance-an-application-to-default-risk-analysis) - This Staff Working Paper from the Bank of England proposes a framework for addressing the ‘black box’ problem present in some Machine Learning (ML) applications.

*   [Regulatory learning: How to supervise machine learning models? An application to credit scoring](https://www.sciencedirect.com/science/article/pii/S2405918817300648) - The arrival of Big Data strategies is threatening the latest trends in financial regulation related to the simplification of models and the enhancement of the comparability of approaches chosen by financial institutions. Indeed, the intrinsic dynamic philosophy of Big Data strategies is almost incompatible with the current legal and regulatory framework as illustrated in this paper. Besides, the model selection may also evolve dynamically forcing both practitioners and regulators to develop libraries of models, strategies allowing to switch from one to the other as well as supervising approaches allowing financial institutions to innovate in a risk mitigated environment.

