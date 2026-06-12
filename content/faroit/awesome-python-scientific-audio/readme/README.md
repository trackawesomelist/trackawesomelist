# Awesome Python Scientific Audio Overview

 Curated list of python software and packages related to scientific research in audio

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/faroit/awesome-python-scientific-audio/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 faroit/awesome-python-scientific-audio](https://github.com/faroit/awesome-python-scientific-audio) · ⭐ 1.7K · 🏷️ Programming Languages

[ [Daily](/content/faroit/awesome-python-scientific-audio/README.md) / [Weekly](/content/faroit/awesome-python-scientific-audio/week/README.md) / Overview ]

---

# Python for Scientific Audio

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/faroit/awesome-python-scientific-audio/workflows/CI/badge.svg)](https://github.com/faroit/awesome-python-scientific-audio/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)

The aim of this repository is to create a comprehensive, curated list of python software/tools related and used for scientific research in audio/music applications.

## Contents

*   [Audio Related Packages](#audio-related-packages)
    *   [Read/Write](#read-write)
    *   [Transformations - General DSP](#transformations---general-dsp)
    *   [Feature extraction](#feature-extraction)
    *   [Data augmentation](#data-augmentation)
    *   [Speech Processing](#speech-processing)
    *   [Environmental Sounds](#environmenta)
    *   [Perceptial Models - Auditory Models](#perceptial-models---auditory-models)
    *   [Source Separation](#source-separation)
    *   [Music Information Retrieval](#music-information-retrieval)
    *   [Deep Learning](#deep-learning)
    *   [Symbolic Music - MIDI - Musicology](#symbolic-music---midi---musicology)
    *   [Realtime applications](#realtime-applications)
    *   [Web - Audio](#web-audio)
    *   [Audio related APIs and Datasets](#audio-related-apis-and-datasets)
    *   [Wrappers for Audio Plugins](#wrappers-for-audio-plugins)
*   [Tutorials](#tutorials)
*   [Books](#books)
*   [Scientific Paper](#scientific-papers)
*   [Other Resources](#other-resources)
*   [Related lists](#related-lists)
*   [Contributing](#contributing)
*   [License](#license)

## Audio Related Packages

*   Total number of packages: 67

#### Read-Write

*   [audiolazy (⭐712)](https://github.com/danilobellini/audiolazy) [:octocat: (⭐712)](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) - Expressive Digital Signal Processing (DSP) package for Python.
*   [audioread (⭐536)](https://github.com/beetbox/audioread) [:octocat: (⭐536)](https://github.com/beetbox/audioread) [:package:](https://pypi.python.org/pypi/audioread/) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
*   [mutagen](https://mutagen.readthedocs.io/) [:octocat: (⭐1.9k)](https://github.com/quodlibet/mutagen) [:package:](https://pypi.python.org/pypi/mutagen) - Reads and writes all kind of audio metadata for various formats.
*   [pyAV](http://docs.mikeboers.com/pyav/) [:octocat: (⭐3.2k)](https://github.com/mikeboers/PyAV) - PyAV is a Pythonic binding for FFmpeg or Libav.
*   [pyfar](https://pyfar.readthedocs.io) [:octocat: (⭐129)](https://github.com/pyfar/pyfar) [:package:](https://pypi.org/project/pyfar/) - Read audio files, SOFA files, and COMSOL data with the [pyfar.io](https://pyfar.readthedocs.io/en/stable/modules/pyfar.io.html) module.
*   [(Py)Soundfile](http://pysoundfile.readthedocs.io/) [:octocat: (⭐14)](https://github.com/bastibe/PySoundFile) [:package:](https://pypi.python.org/pypi/SoundFile) - Library based on libsndfile, CFFI, and NumPy.
*   [pySox (⭐538)](https://github.com/rabitt/pysox) [:octocat: (⭐538)](https://github.com/rabitt/pysox) [:package:](https://pypi.python.org/pypi/pysox/) - Wrapper for sox.
*   [stempeg (⭐107)](https://github.com/faroit/stempeg) [:octocat: (⭐107)](https://github.com/faroit/stempeg) [:package:](https://pypi.python.org/pypi/stempeg/) - read/write of STEMS multistream audio.
*   [tinytag (⭐817)](https://github.com/devsnd/tinytag) [:octocat: (⭐817)](https://github.com/devsnd/tinytag) [:package:](https://pypi.python.org/pypi/tinytag/) - reading music meta data of MP3, OGG, FLAC and Wave files.

#### Transformations - General DSP

*   [acoustics](http://python-acoustics.github.io/python-acoustics/) [:octocat: (⭐559)](https://github.com/python-acoustics/python-acoustics/) [:package:](https://pypi.python.org/pypi/acoustics) - useful tools for acousticians.
*   [AudioTK (⭐252)](https://github.com/mbrucher/AudioTK) [:octocat: (⭐252)](https://github.com/mbrucher/AudioTK) - DSP filter toolbox (lots of filters).
*   [AudioTSM](https://audiotsm.readthedocs.io/) [:octocat: (⭐90)](https://github.com/Muges/audiotsm) [:package:](https://pypi.python.org/pypi/audiotsm/) - real-time audio time-scale modification procedures.
*   [Gammatone (⭐229)](https://github.com/detly/gammatone) [:octocat: (⭐229)](https://github.com/detly/gammatone) - Gammatone filterbank implementation.
*   [pyFFTW](http://pyfftw.github.io/pyFFTW/) [:octocat: (⭐420)](https://github.com/pyFFTW/pyFFTW) [:package:](https://pypi.python.org/pypi/pyFFTW/) - Wrapper for FFTW(3).
*   [NSGT](https://grrrr.org/research/software/nsgt/) [:octocat: (⭐106)](https://github.com/grrrr/nsgt) [:package:](https://pypi.python.org/pypi/nsgt) - Non-stationary gabor transform, constant-q.
*   [matchering (⭐2.5k)](https://github.com/sergree/matchering) [:octocat: (⭐2.5k)](https://github.com/sergree/matchering) [:package:](https://pypi.org/project/matchering/) - Automated reference audio mastering.
*   [MDCT (⭐55)](https://github.com/nils-werner/mdct) [:octocat: (⭐55)](https://github.com/nils-werner/mdct) [:package:](https://pypi.python.org/pypi/mdct) - MDCT transform.
*   [pydub](http://pydub.com) [:octocat: (⭐9.8k)](https://github.com/jiaaro/pydub) [:package:](https://pypi.python.org/pypi/mdct) - Manipulate audio with a simple and easy high level interface.
*   [pyfar](https://pyfar.readthedocs.io) [:octocat: (⭐129)](https://github.com/pyfar/pyfar) [:package:](https://pypi.org/project/pyfar/) - Perform general DSP and filtering tailored for acoustic signals with the [pyfar.dsp](https://pyfar.readthedocs.io/en/stable/modules/pyfar.dsp.html) module.
*   [pytftb](http://tftb.nongnu.org) [:octocat: (⭐279)](https://github.com/scikit-signal/pytftb) - Implementation of the MATLAB Time-Frequency Toolbox.
*   [pyroomacoustics (⭐1.9k)](https://github.com/LCAV/pyroomacoustics) [:octocat: (⭐1.9k)](https://github.com/LCAV/pyroomacoustics) [:package:](https://pypi.python.org/pypi/pyroomacoustics) - Room Acoustics Simulation (RIR generator)
*   [PyRubberband (⭐218)](https://github.com/bmcfee/pyrubberband) [:octocat: (⭐218)](https://github.com/bmcfee/pyrubberband) [:package:](https://pypi.python.org/pypi/pyrubberband/) - Wrapper for [rubberband](http://breakfastquay.com/rubberband/) to do pitch-shifting and time-stretching.
*   [PyWavelets](http://pywavelets.readthedocs.io) [:octocat: (⭐2.4k)](https://github.com/PyWavelets/pywt) [:package:](https://pypi.python.org/pypi/PyWavelets) - Discrete Wavelet Transform in Python.
*   [Resampy](http://resampy.readthedocs.io) [:octocat: (⭐283)](https://github.com/bmcfee/resampy) [:package:](https://pypi.python.org/pypi/resampy) - Sample rate conversion.
*   [SFS-Python](http://www.sfstoolbox.org) [:octocat: (⭐72)](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) - Sound Field Synthesis Toolbox.
*   [sound\_field\_analysis](https://appliedacousticschalmers.github.io/sound_field_analysis-py/) [:octocat: (⭐106)](https://github.com/AppliedAcousticsChalmers/sound_field_analysis-py) [:package:](https://pypi.org/project/sound-field-analysis/) - Analyze, visualize and process sound field data recorded by spherical microphone arrays.
*   [STFT](http://stft.readthedocs.io) [:octocat: (⭐48)](https://github.com/nils-werner/stft) [:package:](https://pypi.python.org/pypi/stft) - Standalone package for Short-Time Fourier Transform.

#### Feature extraction

*   [aubio](http://aubio.org/) [:octocat: (⭐3.7k)](https://github.com/aubio/aubio) [:package:](https://pypi.python.org/pypi/aubio) - Feature extractor, written in C, Python interface.
*   [audioFlux (⭐3.3k)](https://github.com/libAudioFlux/audioFlux) [:octocat: (⭐3.3k)](https://github.com/libAudioFlux/audioFlux) [:package:](https://pypi.python.org/pypi/audioflux) - A library for audio and music analysis, feature extraction.
*   [audiolazy (⭐712)](https://github.com/danilobellini/audiolazy) [:octocat: (⭐712)](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) - Realtime Audio Processing lib, general purpose.
*   [essentia](http://essentia.upf.edu) [:octocat: (⭐3.6k)](https://github.com/MTG/essentia) - Music related low level and high level feature extractor, C++ based, includes Python bindings.
*   [python\_speech\_features (⭐2.4k)](https://github.com/jameslyons/python_speech_features) [:octocat: (⭐2.4k)](https://github.com/jameslyons/python_speech_features) [:package:](https://pypi.python.org/pypi/python_speech_features) - Common speech features for ASR.
*   [pyYAAFE (⭐248)](https://github.com/Yaafe/Yaafe) [:octocat: (⭐248)](https://github.com/Yaafe/Yaafe) - Python bindings for YAAFE feature extractor.
*   [speechpy (⭐883)](https://github.com/astorfi/speechpy) [:octocat: (⭐883)](https://github.com/astorfi/speechpy) [:package:](https://pypi.python.org/pypi/speechpy) - Library for Speech Processing and Recognition, mostly feature extraction for now.
*   [spafe (⭐483)](https://github.com/SuperKogito/spafe) [:octocat: (⭐483)](https://github.com/SuperKogito/spafe) [:package:](https://pypi.org/project/spafe/) - Python library for features extraction from audio files.

#### Data augmentation

*   [audiomentations (⭐2.3k)](https://github.com/iver56/audiomentations) [:octocat: (⭐2.3k)](https://github.com/iver56/audiomentations) [:package:](https://pypi.org/project/audiomentations/) -  Audio Data Augmentation.
*   [muda](https://muda.readthedocs.io/en/latest/) [:octocat: (⭐237)](https://github.com/bmcfee/muda) [:package:](https://pypi.python.org/pypi/muda) -  Musical Data Augmentation.
*   [pydiogment (⭐85)](https://github.com/SuperKogito/pydiogment) [:octocat: (⭐85)](https://github.com/SuperKogito/pydiogment) [:package:](https://pypi.org/project/pydiogment/) -  Audio Data Augmentation.

#### Speech Processing

*   [aeneas](https://www.readbeyond.it/aeneas/) [:octocat: (⭐2.8k)](https://github.com/readbeyond/aeneas/) [:package:](https://pypi.python.org/pypi/aeneas/) - Forced aligner, based on MFCC+DTW, 35+ languages.
*   [deepspeech (⭐27k)](https://github.com/mozilla/DeepSpeech) [:octocat: (⭐27k)](https://github.com/mozilla/DeepSpeech) [:package:](https://pypi.org/project/deepspeech/) - Pretrained automatic speech recognition.
*   [gentle (⭐1.7k)](https://github.com/lowerquality/gentle) [:octocat: (⭐1.7k)](https://github.com/lowerquality/gentle) - Forced-aligner built on Kaldi.
*   [Parselmouth (⭐1.3k)](https://github.com/YannickJadoul/Parselmouth) [:octocat: (⭐1.3k)](https://github.com/YannickJadoul/Parselmouth) [:package:](https://pypi.org/project/praat-parselmouth/) - Python interface to the [Praat](http://www.praat.org) phonetics and speech analysis, synthesis, and manipulation software.
*   [persephone](https://persephone.readthedocs.io/en/latest/) [:octocat: (⭐159)](https://github.com/persephone-tools/persephone) [:package:](https://pypi.org/project/persephone/) - Automatic phoneme transcription tool.
*   [pyannote.audio (⭐10k)](https://github.com/pyannote/pyannote-audio) [:octocat: (⭐10k)](https://github.com/pyannote/pyannote-audio) [:package:](https://pypi.org/project/pyannote-audio/) - Neural building blocks for speaker diarization.
*   [pyAudioAnalysis (⭐6.2k)](https://github.com/tyiannak/pyAudioAnalysis)² [:octocat: (⭐6.2k)](https://github.com/tyiannak/pyAudioAnalysis) [:package:](https://pypi.python.org/pypi/pyAudioAnalysis/) - Feature Extraction, Classification, Diarization.
*   [py-webrtcvad (⭐2.5k)](https://github.com/wiseman/py-webrtcvad) [:octocat: (⭐2.5k)](https://github.com/wiseman/py-webrtcvad) [:package:](https://pypi.python.org/pypi/webrtcvad/) -  Interface to the WebRTC Voice Activity Detector.
*   [pypesq (⭐410)](https://github.com/vBaiCai/python-pesq) [:octocat: (⭐410)](https://github.com/vBaiCai/python-pesq) - Wrapper for the PESQ score calculation.
*   [pystoi (⭐360)](https://github.com/mpariente/pystoi) [:octocat: (⭐360)](https://github.com/mpariente/pystoi) [:package:](https://pypi.org/project/pystoi) - Short Term Objective Intelligibility measure (STOI).
*   [visqol-python (⭐2)](https://github.com/talker93/visqol-python) [:octocat: (⭐2)](https://github.com/talker93/visqol-python) [:package:](https://pypi.org/project/visqol-python/) - Port of Google's ViSQOL audio/speech quality metric (MOS-LQO) that installs without Bazel.
*   [PyWorldVocoder (⭐788)](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) [:octocat: (⭐788)](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) - Wrapper for Morise's World Vocoder.
*   [Montreal Forced Aligner](https://montrealcorpustools.github.io/Montreal-Forced-Aligner/) [:octocat: (⭐1.8k)](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) - Forced aligner, based on Kaldi (HMM), English (others can be trained).
*   [SIDEKIT](http://lium.univ-lemans.fr/sidekit/) [:package:](https://pypi.python.org/pypi/SIDEKIT/) - Speaker and Language recognition.
*   [SpeechRecognition (⭐9k)](https://github.com/Uberi/speech_recognition) [:octocat: (⭐9k)](https://github.com/Uberi/speech_recognition) [:package:](https://pypi.python.org/pypi/SpeechRecognition/) -  Wrapper for several ASR engines and APIs, online and offline.

#### Environmental Sounds

*   [sed\_eval](http://tut-arg.github.io/sed_eval) [:octocat: (⭐160)](https://github.com/TUT-ARG/sed_eval) [:package:](https://pypi.org/project/sed_eval/) - Evaluation toolbox for Sound Event Detection

#### Perceptial Models - Auditory Models

*   [cochlea (⭐126)](https://github.com/mrkrd/cochlea) [:octocat: (⭐126)](https://github.com/mrkrd/cochlea) [:package:](https://pypi.python.org/pypi/cochlea/) - Inner ear models.
*   [Brian2](http://briansimulator.org/) [:octocat: (⭐1.2k)](https://github.com/brian-team/brian2) [:package:](https://pypi.python.org/pypi/Brian2) - Spiking neural networks simulator, includes cochlea model.
*   [Loudness (⭐40)](https://github.com/deeuu/loudness) [:octocat: (⭐40)](https://github.com/deeuu/loudness) - Perceived loudness, includes Zwicker, Moore/Glasberg model.
*   [pyloudnorm](https://www.christiansteinmetz.com/projects-blog/pyloudnorm) [:octocat: (⭐771)](https://github.com/csteinmetz1/pyloudnorm) - Audio loudness meter and normalization, implements ITU-R BS.1770-4.
*   [Sound Field Synthesis Toolbox](http://www.sfstoolbox.org) [:octocat: (⭐72)](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) - Sound Field Synthesis Toolbox.

#### Source Separation

*   [commonfate (⭐17)](https://github.com/aliutkus/commonfate) [:octocat: (⭐17)](https://github.com/aliutkus/commonfate) [:package:](https://pypi.python.org/pypi/commonfate) - Common Fate Model and Transform.
*   [NTFLib (⭐49)](https://github.com/stitchfix/NTFLib) [:octocat: (⭐49)](https://github.com/stitchfix/NTFLib) - Sparse Beta-Divergence Tensor Factorization.
*   [NUSSL](https://interactiveaudiolab.github.io/project/nussl.html) [:octocat: (⭐646)](https://github.com/interactiveaudiolab/nussl) [:package:](https://pypi.python.org/pypi/nussl) - Holistic source separation framework including DSP methods and deep learning methods.
*   [NIMFA](http://nimfa.biolab.si) [:octocat: (⭐559)](https://github.com/marinkaz/nimfa) [:package:](https://pypi.python.org/pypi/nimfa) - Several flavors of non-negative-matrix factorization.

#### Music Information Retrieval

*   [Catchy (⭐22)](https://github.com/jvbalen/catchy) [:octocat: (⭐22)](https://github.com/jvbalen/catchy) - Corpus Analysis Tools for Computational Hook Discovery.
*   [chord-detection (⭐145)](https://github.com/sevagh/chord-detection) [:octocat: (⭐145)](https://github.com/sevagh/chord-detection) - Algorithms for chord detection and key estimation.
*   [Madmom](https://madmom.readthedocs.io/en/latest/) [:octocat: (⭐1.6k)](https://github.com/CPJKU/madmom) [:package:](https://pypi.python.org/pypi/madmom) - MIR packages with strong focus on beat detection, onset detection and chord recognition.
*   [mir\_eval](http://craffel.github.io/mir_eval/) [:octocat: (⭐700)](https://github.com/craffel/mir_eval) [:package:](https://pypi.python.org/pypi/mir_eval) - Common scores for various MIR tasks. Also includes bss\_eval implementation.
*   [msaf](http://pythonhosted.org/msaf/) [:octocat: (⭐553)](https://github.com/urinieto/msaf) [:package:](https://pypi.python.org/pypi/msaf) - Music Structure Analysis Framework.
*   [librosa](http://librosa.github.io/librosa/) [:octocat: (⭐8.4k)](https://github.com/librosa/librosa) [:package:](https://pypi.python.org/pypi/librosa) - General audio and music analysis.

#### Deep Learning

*   [Kapre (⭐946)](https://github.com/keunwoochoi/kapre) [:octocat: (⭐946)](https://github.com/keunwoochoi/kapre) [:package:](https://pypi.python.org/pypi/kapre) - Keras Audio Preprocessors
*   [TorchAudio (⭐2.9k)](https://github.com/pytorch/audio) [:octocat: (⭐2.9k)](https://github.com/pytorch/audio) - PyTorch Audio Loaders
*   [nnAudio (⭐1.1k)](https://github.com/KinWaiCheuk/nnAudio) [:octocat: (⭐1.1k)](https://github.com/KinWaiCheuk/nnAudio) [:package:](https://pypi.org/project/nnAudio/) - Accelerated audio processing using 1D convolution networks in PyTorch.

#### Symbolic Music - MIDI - Musicology

*   [Music21](http://web.mit.edu/music21/) [:octocat: (⭐2.5k)](https://github.com/cuthbertLab/music21) [:package:](https://pypi.python.org/pypi/music21) - Toolkit for Computer-Aided Musicology.
*   [Mido](https://mido.readthedocs.io/en/latest/) [:octocat: (⭐1.6k)](https://github.com/olemb/mido) [:package:](https://pypi.python.org/pypi/mido) - Realtime MIDI wrapper.
*   [mingus (⭐925)](https://github.com/bspaans/python-mingus) [:octocat: (⭐925)](https://github.com/bspaans/python-mingus) [:package:](https://pypi.org/project/mingus) - Advanced music theory and notation package with MIDI file and playback support.
*   [Pretty-MIDI](http://craffel.github.io/pretty-midi/) [:octocat: (⭐1k)](https://github.com/craffel/pretty-midi) [:package:](https://pypi.python.org/pypi/pretty-midi) - Utility functions for handling MIDI data in a nice/intuitive way.

#### Realtime applications

*   [Jupylet (⭐251)](https://github.com/nir/jupylet) [:octocat: (⭐251)](https://github.com/nir/jupylet) - Subtractive, additive, FM, and sample-based sound synthesis.
*   [PYO](http://ajaxsoundstudio.com/software/pyo/) [:octocat: (⭐1.4k)](https://github.com/belangeo/pyo) - Realtime audio dsp engine.
*   [python-sounddevice (⭐1.2k)](https://github.com/spatialaudio/python-sounddevice) [:octocat:](http://python-sounddevice.readthedocs.io) [:package:](https://pypi.python.org/pypi/sounddevice) - PortAudio wrapper providing realtime audio I/O with NumPy.
*   [ReTiSAR (⭐80)](https://github.com/AppliedAcousticsChalmers/ReTiSAR) [:octocat: (⭐80)](https://github.com/AppliedAcousticsChalmers/ReTiSAR) - Binaural rendering of streamed or IR-based high-order spherical microphone array signals.

#### Web Audio

*   [TimeSide (Beta) (⭐393)](https://github.com/Parisson/TimeSide/tree/dev) [:octocat: (⭐393)](https://github.com/Parisson/TimeSide/tree/dev) - high level audio analysis, imaging, transcoding, streaming and labelling.

#### Audio Dataset and Dataloaders

*   [beets](http://beets.io/) [:octocat: (⭐15k)](https://github.com/beetbox/beets) [:package:](https://pypi.python.org/pypi/beets) - Music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
*   [musdb](http://dsdtools.readthedocs.io) [:octocat: (⭐201)](https://github.com/sigsep/sigsep-mus-db) [:package:](https://pypi.python.org/pypi/musdb) - Parse and process the MUSDB18 dataset.
*   [medleydb](http://medleydb.readthedocs.io) [:octocat: (⭐212)](https://github.com/marl/medleydb) - Parse [medleydb](http://medleydb.weebly.com/) audio + annotations.
*   [Soundcloud API (⭐112)](https://github.com/soundcloud/soundcloud-python) [:octocat: (⭐112)](https://github.com/soundcloud/soundcloud-python) [:package:](https://pypi.python.org/pypi/soundcloud) - Wrapper for [Soundcloud API](https://developers.soundcloud.com/).
*   [Youtube-Downloader](http://rg3.github.io/youtube-dl/) [:octocat: (⭐140k)](https://github.com/rg3/youtube-dl) [:package:](https://pypi.python.org/pypi/youtube_dl) - Download youtube videos (and the audio).
*   [audiomate (⭐139)](https://github.com/ynop/audiomate) [:octocat: (⭐139)](https://github.com/ynop/audiomate) [:package:](https://pypi.python.org/pypi/audiomate/) - Loading different types of audio datasets.
*   [mirdata](https://mirdata.readthedocs.io/en/latest/) [:octocat: (⭐406)](https://github.com/mir-dataset-loaders/mirdata) [:package:](https://pypi.python.org/pypi/mirdata) - Common loaders for Music Information Retrieval (MIR) datasets.

#### Wrappers for Audio Plugins

*   [VamPy Host](https://code.soundsoftware.ac.uk/projects/vampy-host) [:package:](https://pypi.python.org/pypi/vamp) - Interface compiled vamp plugins.

## Tutorials

*   [Whirlwind Tour Of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) [:octocat: (⭐4k)](https://github.com/jakevdp/WhirlwindTourOfPython) - fast-paced introduction to Python essentials, aimed at researchers and developers.
*   [Introduction to Numpy and Scipy](http://www.scipy-lectures.org/index.html) [:octocat: (⭐3.2k)](https://github.com/scipy-lectures/scipy-lecture-notes) - Highly recommended tutorial, covers large parts of the scientific Python ecosystem.
*   [Numpy for MATLAB® Users](https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html) - Short overview of equivalent python functions for switchers.
*   [MIR Notebooks](http://musicinformationretrieval.com/) [:octocat: (⭐1.3k)](https://github.com/stevetjoa/stanford-mir) - collection of instructional iPython Notebooks for music information retrieval (MIR).
*   [Selected Topics in Audio Signal Processing (⭐69)](https://github.com/spatialaudio/selected-topics-in-audio-signal-processing-exercises) - Exercises as iPython notebooks.
*   [Live-coding a music synthesizer](https://www.youtube.com/watch?v=SSyQ0kRHzis) Live-coding video showing how to use the SoundDevice library to reproduce realistic sounds. [Code (⭐18)](https://github.com/cool-RR/python_synthesizer).
*   [pyfar examples](https://pyfar-gallery.readthedocs.io/en/latest/examples_gallery.html) - Introduction and examples for the python packages for acoustics research (pyfar).

## Books

*   [Python Data Science Handbook (⭐48k)](https://github.com/jakevdp/PythonDataScienceHandbook) - Jake Vanderplas, Excellent Book and accompanying tutorial notebooks.
*   [Fundamentals of Music Processing](https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP) - Meinard Müller, comes with Python exercises.

## Scientific Papers

*   [Python for audio signal processing](http://eprints.maynoothuniversity.ie/4115/1/40.pdf) - John C. Glover, Victor Lazzarini and Joseph Timoney, Linux Audio Conference 2011.
*   [librosa: Audio and Music Signal Analysis in Python](http://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf), [Video](https://www.youtube.com/watch?v=MhOdbtPhbLU) - Brian McFee, Colin Raffel, Dawen Liang, Daniel P.W. Ellis, Matt McVicar, Eric Battenberg, Oriol Nieto, Scipy 2015.
*   [pyannote.audio: neural building blocks for speaker diarization](https://arxiv.org/abs/1911.01255), [Video](https://www.youtube.com/watch?v=37R_R82lfwA) - Hervé Bredin, Ruiqing Yin, Juan Manuel Coria, Gregory Gelly, Pavel Korshunov, Marvin Lavechin, Diego Fustes, Hadrien Titeux, Wassim Bouaziz, Marie-Philippe Gill, ICASSP 2020.

## Other Resources

*   [Coursera Course](https://www.coursera.org/learn/audio-signal-processing) -  Audio Signal Processing, Python based course from UPF of Barcelona and Stanford University.
*   [Digital Signal Processing Course](http://dsp-nbsphinx.readthedocs.io/en/nbsphinx-experiment/index.html) - Masters Course Material (University of Rostock) with many Python examples.
*   [Slack Channel](https://mircommunity.slack.com) - Music Information Retrieval Community.

## Related lists

There is already [PythonInMusic](https://wiki.python.org/moin/PythonInMusic) but it is not up to date and includes too many packages of special interest that are mostly not relevant for scientific applications. [Awesome-Python (⭐302k)](https://github.com/vinta/awesome-python) is large curated list of python packages. However, the audio section is very small.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/faroit/awesome-python-scientific-audio/blob/master/README.md/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could vote for them by adding 👍 to them.

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

