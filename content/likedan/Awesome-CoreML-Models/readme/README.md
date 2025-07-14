# Awesome CoreML Models Overview

Largest list of models for Core ML (for iOS 11+)

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/likedan/Awesome-CoreML-Models/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 likedan/Awesome-CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) · ⭐ 6.7K · 🏷️ Computer Science

[ [Daily](/content/likedan/Awesome-CoreML-Models/README.md) / [Weekly](/content/likedan/Awesome-CoreML-Models/week/README.md) / Overview ]

---

<!--
Title: Awesome Core ML Models
Description: A curated list of machine learning models in Core ML format.
Author: Kedan Li
-->

<p align="center">
<img src="https://github.com/likedan/Awesome-CoreML-Models/raw/master/images/coreml.png" width="329" height="295"/>
</p>

Since iOS 11, Apple released Core ML framework to help developers integrate machine learning models into applications. [The official documentation](https://developer.apple.com/documentation/coreml)

We've put up the largest collection of machine learning models in Core ML format, to help  iOS, macOS, tvOS, and watchOS developers experiment with machine learning techniques.

If you've converted a Core ML model, feel free to submit a [pull request (⭐6.7k)](https://github.com/likedan/Awesome-CoreML-Models/compare).

Recently, we've included visualization tools. And here's one [Netron](https://lutzroeder.github.io/Netron).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# Models

## Image - Metadata/Text

*Models that take image data as input and output useful information about the image.*

*   **TextDetection** - Detecting text using Vision built-in model in real-time. [Download](https://github.com/likedan/Awesome-CoreML-Models/blob/master/README.md/) | [Demo (⭐82)](https://github.com/tucan9389/TextDetection-CoreML) | [Reference](https://developer.apple.com/documentation/vision)
*   **PhotoAssessment** - Photo Assessment using Core ML and Metal. [Download (⭐76)](https://github.com/yulingtianxia/PhotoAssessment/blob/master/PhotoAssessment-Sample/Sources/NIMANasnet.mlmodel) | [Demo (⭐76)](https://github.com/yulingtianxia/PhotoAssessment) | [Reference](https://arxiv.org/abs/1709.05424)
*   **PoseEstimation** - Estimating human pose from a picture for mobile. [Download (⭐1k)](https://github.com/edvardHua/PoseEstimationForMobile/tree/master/release) | [Demo (⭐698)](https://github.com/tucan9389/PoseEstimation-CoreML) | [Reference (⭐1k)](https://github.com/edvardHua/PoseEstimationForMobile)
*   **MobileNet** - Detects the dominant objects present in an image. [Download (⭐711)](https://github.com/hollance/MobileNet-CoreML/raw/master/MobileNet.mlmodel) | [Demo (⭐711)](https://github.com/hollance/MobileNet-CoreML) | [Reference](https://arxiv.org/abs/1704.04861)
*   **Places CNN** - Detects the scene of an image from 205 categories such as bedroom, forest, coast etc. [Download (⭐711)](https://github.com/hollance/MobileNet-CoreML/raw/master/MobileNet.mlmodel) | [Demo (⭐34)](https://github.com/chenyi1989/CoreMLDemo) | [Reference](http://places.csail.mit.edu/index.html)
*   **Inception v3** - Detects the dominant objects present in an image. [Download (⭐219)](https://github.com/yulingtianxia/Core-ML-Sample/blob/master/CoreMLSample/Inceptionv3.mlmodel) | [Demo (⭐219)](https://github.com/yulingtianxia/Core-ML-Sample/) | [Reference](https://arxiv.org/abs/1512.00567)
*   **ResNet50** - Detects the dominant objects present in an image. [Download (⭐44)](https://github.com/ytakzk/CoreML-samples/blob/master/CoreML-samples/Resnet50.mlmodel) | [Demo (⭐44)](https://github.com/ytakzk/CoreML-samples) | [Reference](https://arxiv.org/abs/1512.03385)
*   **VGG16** - Detects the dominant objects present in an image. [Download](https://docs-assets.developer.apple.com/coreml/models/VGG16.mlmodel) | [Demo (⭐37)](https://github.com/alaphao/CoreMLExample) | [Reference](https://arxiv.org/abs/1409.1556)
*   **Car Recognition** - Predict the brand & model of a car. [Download (⭐172)](https://github.com/likedan/Core-ML-Car-Recognition/blob/master/Convert/CarRecognition.mlmodel) | [Demo (⭐44)](https://github.com/ytakzk/CoreML-samples) | [Reference](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html)
*   **YOLO** - Recognize what the objects are inside a given image and where they are in the image. [Download (⭐945)](https://github.com/hollance/YOLO-CoreML-MPSNNGraph/blob/master/TinyYOLO-CoreML/TinyYOLO-CoreML/TinyYOLO.mlmodel) | [Demo (⭐945)](https://github.com/hollance/YOLO-CoreML-MPSNNGraph) | [Reference](http://machinethink.net/blog/object-detection-with-yolo)
*   **AgeNet** - Predict a person's age from one's portrait. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mT1J3T1BEeWx4TWc/view?usp=sharing) | [Demo (⭐321)](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/)
*   **GenderNet** - Predict a person's gender from one's portrait. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mYkNsZHlyc2ZuaFk/view?usp=sharing) | [Demo (⭐321)](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/)
*   **MNIST** - Predict handwritten (drawn) digits from images. [Download (⭐68)](https://github.com/ph1ps/MNIST-CoreML/raw/master/MNISTPrediction/MNIST.mlmodel) | [Demo (⭐68)](https://github.com/ph1ps/MNIST-CoreML) | [Reference](http://yann.lecun.com/exdb/mnist/)
*   **EmotionNet** - Predict a person's emotion from one's portrait. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mTlYtRGdXNFlpWDQ/view?usp=sharing) | [Demo (⭐321)](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_emotions/)
*   **SentimentVision** - Predict positive or negative sentiments from images. [Download](https://drive.google.com/open?id=0B1ghKa_MYL6mZ0dITW5uZlgyNTg) | [Demo (⭐36)](https://github.com/cocoa-ai/SentimentVisionDemo) | [Reference](http://www.sciencedirect.com/science/article/pii/S0262885617300355?via%3Dihub)
*   **Food101** - Predict the type of foods from images. [Download](https://drive.google.com/open?id=0B5TjkH3njRqnVjBPZGRZbkNITjA) | [Demo (⭐149)](https://github.com/ph1ps/Food101-CoreML) | [Reference](http://visiir.lip6.fr/explore)
*   **Oxford102** - Detect the type of flowers from images. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6meDBHT2NaZGxkNzQ/view?usp=sharing) | [Demo (⭐102)](https://github.com/cocoa-ai/FlowersVisionDemo) | [Reference](http://jimgoo.com/flower-power/)
*   **FlickrStyle** - Detect the artistic style of images. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6meDBHT2NaZGxkNzQ/view?usp=sharing) | [Demo (⭐47)](https://github.com/cocoa-ai/StylesVisionDemo) | [Reference](http://sergeykarayev.com/files/1311.3715v3.pdf)
*   **RN1015k500** - Predict the location where a picture was taken. [Download](https://s3.amazonaws.com/aws-bigdata-blog/artifacts/RN1015k500/RN1015k500.mlmodel) | [Demo (⭐57)](https://github.com/awslabs/MXNet2CoreML_iOS_sample_app) | [Reference](https://aws.amazon.com/blogs/ai/estimating-the-location-of-images-using-mxnet-and-multimedia-commons-dataset-on-aws-ec2)
*   **Nudity** - Classifies an image either as NSFW (nude) or SFW (not nude)
    [Download](https://drive.google.com/open?id=0B5TjkH3njRqncDJpdDB1Tkl2S2s) | [Demo (⭐106)](https://github.com/ph1ps/Nudity-CoreML) | [Reference (⭐6k)](https://github.com/yahoo/open_nsfw)
*   **TextRecognition (ML Kit)** - Recognizing text using ML Kit built-in model in real-time. [Download](https://github.com/likedan/Awesome-CoreML-Models/blob/master/README.md/) | [Demo (⭐94)](https://github.com/tucan9389/TextRecognition-MLKit) | [Reference](https://firebase.google.com/docs/ml-kit/ios/recognize-text)
*   **ImageSegmentation** - Segment the pixels of a camera frame or image into a predefined set of classes. [Download](https://developer.apple.com/machine-learning/models/) | [Demo (⭐333)](https://github.com/tucan9389/ImageSegmentation-CoreML) | [Reference (⭐78k)](https://github.com/tensorflow/models/tree/master/research/deeplab)
*   **DepthPrediction** - Predict the depth from a single image. [Download](https://developer.apple.com/machine-learning/models/) | [Demo (⭐138)](https://github.com/tucan9389/DepthPrediction-CoreML) | [Reference (⭐1.1k)](https://github.com/iro-cp/FCRN-DepthPrediction)

## Image - Image

*Models that transform images.*

*   **HED** - Detect nested edges from a color image. [Download (⭐109)](https://github.com/s1ddok/HED-CoreML/blob/master/HED-CoreML/Models/HED_so.mlmodel) | [Demo (⭐109)](https://github.com/s1ddok/HED-CoreML) | [Reference](http://dl.acm.org/citation.cfm?id=2654889)
*   **AnimeScale2x** - Process a bicubic-scaled anime-style artwork [Download (⭐583)](https://github.com/imxieyi/waifu2x-ios/blob/master/waifu2x/models/anime_noise0_model.mlmodel) | [Demo (⭐583)](https://github.com/imxieyi/waifu2x-ios) | [Reference](https://arxiv.org/abs/1501.00092)

## Text - Metadata/Text

*Models that process text data*

*   **Sentiment Polarity** - Predict positive or negative sentiments from sentences. [Download (⭐123)](https://github.com/cocoa-ai/SentimentCoreMLDemo/raw/master/SentimentPolarity/Resources/SentimentPolarity.mlmodel) | [Demo (⭐123)](https://github.com/cocoa-ai/SentimentCoreMLDemo) | [Reference](http://boston.lti.cs.cmu.edu/classes/95-865-K/HW/HW3/)
*   **DocumentClassification** - Classify news articles into 1 of 5 categories. [Download (⭐45)](https://github.com/toddkramer/DocumentClassifier/blob/master/Sources/DocumentClassification.mlmodel) | [Demo (⭐45)](https://github.com/toddkramer/DocumentClassifier) | [Reference (⭐45)](https://github.com/toddkramer/DocumentClassifier/)
*   **iMessage Spam Detection** - Detect whether a message is spam. [Download (⭐37)](https://github.com/gkswamy98/imessage-spam-detection/blob/master/MessageClassifier.mlmodel) | [Demo (⭐37)](https://github.com/gkswamy98/imessage-spam-detection/tree/master) | [Reference](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)
*   **NamesDT** - Gender Classification using DecisionTreeClassifier [Download (⭐36)](https://github.com/cocoa-ai/NamesCoreMLDemo/blob/master/Names/Resources/NamesDT.mlmodel) | [Demo (⭐36)](https://github.com/cocoa-ai/NamesCoreMLDemo) | [Reference](http://nlpforhackers.io/)
*   **Personality Detection** - Predict personality based on user documents (sentences). [Download (⭐19)](https://github.com/novinfard/profiler-sentiment-analysis/tree/master/ios_app/ProfilerSA/ML%20Models) | [Demo (⭐19)](https://github.com/novinfard/profiler-sentiment-analysis/) | [Reference (⭐19)](https://github.com/novinfard/profiler-sentiment-analysis/blob/master/dissertation-v6.pdf)
*   **BERT for Question answering** - Swift Core ML 3 implementation of BERT for Question answering [Download (⭐1.7k)](https://github.com/huggingface/swift-coreml-transformers/blob/master/Resources/BERTSQUADFP16.mlmodel) | [Demo (⭐1.7k)](https://github.com/huggingface/swift-coreml-transformers#-bert) | [Reference (⭐146k)](https://github.com/huggingface/pytorch-transformers#run_squadpy-fine-tuning-on-squad-for-question-answering)
*   **GPT-2** - OpenAI GPT-2 Text generation (Core ML 3) [Download (⭐1.7k)](https://github.com/huggingface/swift-coreml-transformers/blob/master/Resources/gpt2-512.mlmodel) | [Demo (⭐1.7k)](https://github.com/huggingface/swift-coreml-transformers#-gpt-2) | [Reference (⭐146k)](https://github.com/huggingface/pytorch-transformers)

## Miscellaneous

*   **Exermote** - Predicts the exercise, when iPhone is worn on right upper arm. [Download (⭐130)](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Demo (⭐130)](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Reference](http://lausbert.com/2017/08/03/exermote/)
*   **GestureAI** - Recommend an artist based on given location and genre. [Download](https://goo.gl/avdMjD) | [Demo (⭐158)](https://github.com/akimach/GestureAI-CoreML-iOS) | [Reference (⭐158)](https://github.com/akimach/GestureAI-iOS/tree/master/GestureAI)
*   **Artists Recommendation** - Recommend an artist based on given location and genre. [Download (⭐19)](https://github.com/agnosticdev/Blog-Examples/blob/master/UsingCoreMLtoCreateASongRecommendationEngine/Artist.mlmodel) | [Demo](https://github.com/likedan/Awesome-CoreML-Models/blob/master/README.md/) | [Reference](https://www.agnosticdev.com/blog-entry/python/using-scikit-learn-and-coreml-create-music-recommendation-engine)
*   **ChordSuggester** - Predicts the most likely next chord based on the entered Chord Progression. [Download (⭐8)](https://github.com/carlosmbe/Mac-CoreML-Chord-Suggester/blob/main/MLChordSuggester.mlpackage.zip) | [Demo (⭐8)](https://github.com/carlosmbe/Mac-CoreML-Chord-Suggester/tree/main) | [Reference](https://medium.com/@huanlui/chordsuggester-i-3a1261d4ea9e)

## Speech Processing

*   **Streaming ASR** – Real-time streaming speech recognition engine for iOS. Uses Fast Conformer + CTC, runs fully on device.\
    [Download (⭐3)](https://github.com/Otosaku/OtosakuStreamingASR-iOS/releases) | [Demo (⭐3)](https://github.com/Otosaku/OtosakuStreamingASR-iOS) | [Reference (⭐3)](https://github.com/Otosaku/OtosakuStreamingASR-iOS)
*   **Keyword Spotting (KWS)** – On-device keyword spotting engine using lightweight CRNN architecture, optimized for mobile devices.\
    [Download (⭐3)](https://github.com/Otosaku/OtosakuKWS-iOS/releases) | [Demo (⭐3)](https://github.com/Otosaku/OtosakuKWS-iOS) | [Reference (⭐3)](https://github.com/Otosaku/OtosakuKWS-iOS)

# Visualization Tools

*Tools that help visualize CoreML Models*

*   [Netron](https://lutzroeder.github.io/Netron)

# Supported formats

*List of model formats that could be converted to Core ML with examples*

*   [Caffe](https://apple.github.io/coremltools/generated/coremltools.converters.caffe.convert.html)
*   [Keras](https://apple.github.io/coremltools/generated/coremltools.converters.keras.convert.html)
*   [XGBoost](https://apple.github.io/coremltools/generated/coremltools.converters.xgboost.convert.html)
*   [Scikit-learn](https://apple.github.io/coremltools/generated/coremltools.converters.sklearn.convert.html)
*   [MXNet](https://aws.amazon.com/blogs/ai/bring-machine-learning-to-ios-apps-using-apache-mxnet-and-apple-core-ml/)
*   [LibSVM](https://apple.github.io/coremltools/generated/coremltools.converters.libsvm.convert.html)
*   [Torch7 (⭐386)](https://github.com/prisma-ai/torch2coreml)

# The Gold

*Collections of machine learning models that could be converted to Core ML*

*   [Caffe Model Zoo (⭐34k)](https://github.com/BVLC/caffe/wiki/Model-Zoo) - Big list of models in Caffe format.
*   [TensorFlow Models (⭐78k)](https://github.com/tensorflow/models) - Models for TensorFlow.
*   [TensorFlow Slim Models (⭐78k)](https://github.com/tensorflow/models/tree/master/research/slim/README.md) - Another collection of TensorFlow Models.
*   [MXNet Model Zoo](https://mxnet.incubator.apache.org/model_zoo/) - Collection of MXNet models.

*Individual machine learning models that could be converted to Core ML. We'll keep adjusting the list as they become converted.*

*   [LaMem (⭐18)](https://github.com/MiyainNYC/Visual-Memorability-through-Caffe) Score the memorability of pictures.
*   [ILGnet (⭐115)](https://github.com/BestiVictory/ILGnet) The aesthetic evaluation of images.
*   [Colorization (⭐3.4k)](https://github.com/richzhang/colorization) Automatic colorization using deep neural networks.
*   [Illustration2Vec (⭐674)](https://github.com/rezoo/illustration2vec) Estimating a set of tags and extracting semantic feature vectors from given illustrations.
*   [CTPN (⭐1.3k)](https://github.com/tianzhi0549/CTPN) Detecting text in natural image.
*   [Image Analogy (⭐1.4k)](https://github.com/msracver/Deep-Image-Analogy) Find semantically-meaningful dense correspondences between two input images.
*   [iLID (⭐90)](https://github.com/twerkmeister/iLID) Automatic spoken language identification.
*   [Fashion Detection (⭐486)](https://github.com/liuziwei7/fashion-detection) Cloth detection from images.
*   [Saliency (⭐186)](https://github.com/imatge-upc/saliency-2016-cvpr) The prediction of salient areas in images has been traditionally addressed with hand-crafted features.
*   [Face Detection (⭐23)](https://github.com/DolotovEvgeniy/DeepPyramid) Detect face from image.
*   [mtcnn (⭐494)](https://github.com/CongWeilin/mtcnn-caffe) Joint Face Detection and Alignment.
*   [deephorizon (⭐40)](https://github.com/scottworkman/deephorizon) Single image horizon line estimation.

# Contributing and License

*   [See the guide (⭐6.7k)](https://github.com/likedan/Awesome-CoreML-Models/blob/master/.github/CONTRIBUTING.md)
*   Distributed under the MIT license. See LICENSE for more information.

