# Awesome List Updates on Dec 31, 2018

6 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Deep Learning Resources](/content/guillaume-chevalier/Awesome-Deep-Learning-Resources/README.md)

### Posts and Articles

*   [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) - Good for understanding the "Attention Is All You Need" (AIAYN) paper.
*   [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) - Also good for understanding the "Attention Is All You Need" (AIAYN) paper.
*   [Improving Language Understanding with Unsupervised Learning](https://blog.openai.com/language-unsupervised/) - SOTA across many NLP tasks from unsupervised pretraining on huge corpus.
*   [NLP's ImageNet moment has arrived](https://thegradient.pub/nlp-imagenet/) - All hail NLP's ImageNet moment.
*   [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](https://jalammar.github.io/illustrated-bert/) - Understand the different approaches used for NLP's ImageNet moment.

### Practical Resources / Librairies and Implementations

*   [Self Governing Neural Networks (SGNN): the Projection Layer (⭐22)](https://github.com/guillaume-chevalier/SGNN-Self-Governing-Neural-Networks-Projection-Layer) - With this, you can use words in your deep learning models without training nor loading embeddings.

### Practical Resources / Some Datasets

*   [SentEval: An Evaluation Toolkit for Universal Sentence Representations](https://arxiv.org/abs/1803.05449) - A Python framework to benchmark your sentence representations on many datasets (NLP tasks).
*   [ParlAI: A Dialog Research Software Platform](https://arxiv.org/abs/1705.06476) - Another Python framework to benchmark your sentence representations on many datasets (NLP tasks).

### Papers / Attention Mechanisms

*   [Attention Is All You Need](https://arxiv.org/abs/1706.03762) (AIAYN) - Introducing multi-head self-attention neural networks with positional encoding to do sentence-level NLP without any RNN nor CNN - this paper is a must-read (also see [this explanation](http://nlp.seas.harvard.edu/2018/04/03/attention.html) and [this visualization](http://jalammar.github.io/illustrated-transformer/) of the paper).

### Papers / Other

*   [ProjectionNet: Learning Efficient On-Device Deep Networks Using Neural Projections](https://arxiv.org/abs/1708.00630) - Replace word embeddings by word projections in your deep neural networks, which doesn't require a pre-extracted dictionnary nor storing embedding matrices.
*   [Self-Governing Neural Networks for On-Device Short Text Classification](http://aclweb.org/anthology/D18-1105) - This paper is the sequel to the ProjectionNet just above. The SGNN is elaborated on the ProjectionNet, and the optimizations are detailed more in-depth (also see my [attempt to reproduce the paper in code (⭐22)](https://github.com/guillaume-chevalier/SGNN-Self-Governing-Neural-Networks-Projection-Layer) and watch [the talks' recording](https://vimeo.com/305197775)).
*   [Matching Networks for One Shot Learning](https://arxiv.org/abs/1606.04080) - Classify a new example from a list of other examples (without definitive categories) and with low-data per classification task, but lots of data for lots of similar classification tasks - it seems better than siamese networks. To sum up: with Matching Networks, you can optimize directly for a cosine similarity between examples (like a self-attention product would match) which is passed to the softmax directly. I guess that Matching Networks could probably be used as with negative-sampling softmax training in word2vec's CBOW or Skip-gram without having to do any context embedding lookups.

## [2. Awesome Dotnet Core](/content/thangchung/awesome-dotnet-core/README.md)

### Frameworks, Libraries and Tools / Application Frameworks

*   [Prism (⭐5.8k)](https://github.com/PrismLibrary/Prism) - Prism is a framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms.

### Articles / Workflow

*   [InfoQ .NET articles](https://www.infoq.com/dotnet) -  Collection of best .NET articles on InfoQ site

## [3. Awesome Web Security](/content/qazbnm456/awesome-web-security/README.md)

### Offensive / Cross Site Request Forgery

*   [XSRFProbe (⭐790)](https://github.com/0xInfection/XSRFProbe) - The Prime CSRF Audit & Exploitation Toolkit by [@0xInfection](https://github.com/0xinfection).

## [4. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Scripting

*   [AngelScript](https://www.angelcode.com/angelscript/) - AngelScript is a game-oriented interpreted/compiled scripting language. \[zlib]

## [5. Awesome CoreML Models](/content/likedan/Awesome-CoreML-Models/README.md)

### Image - Metadata/Text

*   **PhotoAssessment** - Photo Assessment using Core ML and Metal. [Download (⭐60)](https://github.com/yulingtianxia/PhotoAssessment/blob/master/PhotoAssessment-Sample/Sources/NIMANasnet.mlmodel) | [Demo (⭐60)](https://github.com/yulingtianxia/PhotoAssessment) | [Reference](https://arxiv.org/abs/1709.05424)
*   **PoseEstimation** - Estimating human pose from a picture for mobile. [Download (⭐969)](https://github.com/edvardHua/PoseEstimationForMobile/tree/master/release) | [Demo (⭐649)](https://github.com/tucan9389/PoseEstimation-CoreML) | [Reference (⭐969)](https://github.com/edvardHua/PoseEstimationForMobile)
*   **RN1015k500** - Predict the location where a picture was taken. [Download](https://s3.amazonaws.com/aws-bigdata-blog/artifacts/RN1015k500/RN1015k500.mlmodel) | [Demo (⭐54)](https://github.com/awslabs/MXNet2CoreML_iOS_sample_app) | [Reference](https://aws.amazon.com/blogs/ai/estimating-the-location-of-images-using-mxnet-and-multimedia-commons-dataset-on-aws-ec2)
*   **Nudity** - Classifies an image either as NSFW (nude) or SFW (not nude)
    [Download](https://drive.google.com/open?id=0B5TjkH3njRqncDJpdDB1Tkl2S2s) | [Demo (⭐103)](https://github.com/ph1ps/Nudity-CoreML) | [Reference (⭐5.7k)](https://github.com/yahoo/open_nsfw)

### Image - Image

*   **HED** - Detect nested edges from a color image. [Download (⭐103)](https://github.com/s1ddok/HED-CoreML/blob/master/HED-CoreML/Models/HED_so.mlmodel) | [Demo (⭐103)](https://github.com/s1ddok/HED-CoreML) | [Reference](http://dl.acm.org/citation.cfm?id=2654889)
*   **AnimeScale2x** - Process a bicubic-scaled anime-style artwork [Download (⭐510)](https://github.com/imxieyi/waifu2x-ios/blob/master/waifu2x/models/anime_noise0_model.mlmodel) | [Demo (⭐510)](https://github.com/imxieyi/waifu2x-ios) | [Reference](https://arxiv.org/abs/1501.00092)

### Text - Metadata/Text

*   **DocumentClassification** - Classify news articles into 1 of 5 categories. [Download (⭐43)](https://github.com/toddkramer/DocumentClassifier/blob/master/Sources/DocumentClassification.mlmodel) | [Demo (⭐43)](https://github.com/toddkramer/DocumentClassifier) | [Reference (⭐43)](https://github.com/toddkramer/DocumentClassifier/)
*   **NamesDT** - Gender Classification using DecisionTreeClassifier [Download (⭐34)](https://github.com/cocoa-ai/NamesCoreMLDemo/blob/master/Names/Resources/NamesDT.mlmodel) | [Demo (⭐34)](https://github.com/cocoa-ai/NamesCoreMLDemo) | [Reference](http://nlpforhackers.io/)

### Miscellaneous

*   **Exermote** - Predicts the exercise, when iPhone is worn on right upper arm. [Download (⭐123)](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Demo (⭐123)](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Reference](http://lausbert.com/2017/08/03/exermote/)
*   [Netron](https://lutzroeder.github.io/Netron)
*   [Caffe](https://apple.github.io/coremltools/generated/coremltools.converters.caffe.convert.html)
*   [Keras](https://apple.github.io/coremltools/generated/coremltools.converters.keras.convert.html)
*   [XGBoost](https://apple.github.io/coremltools/generated/coremltools.converters.xgboost.convert.html)
*   [Scikit-learn](https://apple.github.io/coremltools/generated/coremltools.converters.sklearn.convert.html)
*   [MXNet](https://aws.amazon.com/blogs/ai/bring-machine-learning-to-ios-apps-using-apache-mxnet-and-apple-core-ml/)
*   [LibSVM](https://apple.github.io/coremltools/generated/coremltools.converters.libsvm.convert.html)
*   [Torch7 (⭐380)](https://github.com/prisma-ai/torch2coreml)
*   [TensorFlow Slim Models (⭐76k)](https://github.com/tensorflow/models/tree/master/research/slim/README.md) - Another collection of TensorFlow Models.
*   [MXNet Model Zoo](https://mxnet.incubator.apache.org/model_zoo/) - Collection of MXNet models.
*   [LaMem (⭐17)](https://github.com/MiyainNYC/Visual-Memorability-through-Caffe) Score the memorability of pictures.
*   [ILGnet (⭐106)](https://github.com/BestiVictory/ILGnet) The aesthetic evaluation of images.
*   [Colorization (⭐3.2k)](https://github.com/richzhang/colorization) Automatic colorization using deep neural networks.
*   [Illustration2Vec (⭐667)](https://github.com/rezoo/illustration2vec) Estimating a set of tags and extracting semantic feature vectors from given illustrations.
*   [CTPN (⭐1.3k)](https://github.com/tianzhi0549/CTPN) Detecting text in natural image.
*   [Image Analogy (⭐1.4k)](https://github.com/msracver/Deep-Image-Analogy) Find semantically-meaningful dense correspondences between two input images.
*   [iLID (⭐86)](https://github.com/twerkmeister/iLID) Automatic spoken language identification.
*   [Fashion Detection (⭐462)](https://github.com/liuziwei7/fashion-detection) Cloth detection from images.
*   [Saliency (⭐183)](https://github.com/imatge-upc/saliency-2016-cvpr) The prediction of salient areas in images has been traditionally addressed with hand-crafted features.
*   [Face Detection (⭐23)](https://github.com/DolotovEvgeniy/DeepPyramid) Detect face from image.
*   [mtcnn (⭐498)](https://github.com/CongWeilin/mtcnn-caffe) Joint Face Detection and Alignment.
*   [deephorizon (⭐35)](https://github.com/scottworkman/deephorizon) Single image horizon line estimation.

## [6. Awesome Interview Questions](/content/DopplerHQ/awesome-interview-questions/README.md)

### Programming Languages/Frameworks/Platforms / Objective-C

*   [iOS Interview Questions For Beginners](http://ichuiphonedev.blogspot.com/2014/05/iphone-latest-interview-questions-and.html)

### OS / Linux

*   [10 Job Interview Questions for Linux System Administrators from Linux.com](https://www.linuxfoundation.org/blog/2015/07/10-job-interview-questions-for-linux-system-administrators/)

### Blockchain / Windows

*   [Top 55 Blockchain Interview Questions You Must Prepare In 2018](https://www.edureka.co/blog/interview-questions/blockchain-interview-questions/)
*   [Blockchain Interview Questions](https://mindmajix.com/blockchain-interview-questions)
*   [Top Blockchain Interview Questions](https://intellipaat.com/interview-question/blockchain-interview-questions/)
*   [Blockchain Developer Interview Questions and Answers](https://applicature.com/blog/blockchain-interview-questions)
*   [10 Essential Blockchain Interview Questions ](https://www.toptal.com/blockchain/interview-questions)
*   [Top 30 Blockchain Interview Questions – For Freshers to Experienced](https://data-flair.training/blogs/blockchain-interview-questions/)
*   [Most Frequently Asked Blockchain Interview Questions](https://www.digitalvidya.com/blog/blockchain-interview-questions/)

---

- Prev: [Jan 01, 2019](/content/2019/01/01/README.md)
- Next: [Dec 30, 2018](/content/2018/12/30/README.md)