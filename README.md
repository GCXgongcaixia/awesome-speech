# awesome-speech
this is a treasure-house of speech

## 目录
* [语音识别（ASR,STT）](#1)
  * [page](#1.1)
  * [open source library/toolbox/code](#1.2)
  * [corpus/dataset](#1.3)
  * [教程（Tutorial）](#1.4)
* [语音合成（Speech Synthesis,TTS）](#2)
  * [page](#2.1)
  * [open source library/toolbox/code](#2.2)
  * [corpus/dataset](#2.3)
  * [教程（Tutorial）](#2.4)
* [声纹识别（Speaker Recognition）](#3)
  * [page](#3.1)
  * [open source library/toolbox/code](#3.2)
  * [corpus/dataset](#3.3)
  * [教程（Tutorial）](#3.4)
* [对话系统（Dialogue Systems）](#4)
  * [page](#4.1)
  * [open source library/toolbox/code](#4.2)
  * [corpus/dataset](#4.3)
  * [教程（Tutorial）](#4.4)
* [前端（front end）](#5)
  * [Speech Processing](#5.1)
  * [Audio I/O](#5.2)
  * [Sound Source Separation](#5.3)
  * [Feature Extraction](#5.4)
  * [VAD](#5.5)
* [resource](#6)
  * [code/tool/data](#6.1)
  * [Tutorial](#6.2)
  * [paper](#6.3)
* [pages](#7)

## <h2 id="1">语音识别</h2>
 ### <h3 id="1.1">page</h3>
 #### Xingyu Na
* http://naxingyu.github.io/
* https://github.com/naxingyu?tab=repositories
 #### Language Processing and Pattern Recognition in University of Aachen
* https://www-i6.informatik.rwth-aachen.de/web/Software/index.html
 #### Fernando de la Calle Silos
* http://www.tsc.uc3m.es/~fsilos/
* https://github.com/fernandodelacalle?tab=repositories

 ### <h3 id="1.2">open source library/toolbox/code</h3>
 #### 1. Espnet
 ##### Espnet官网
* https://github.com/espnet/espnet
* https://espnet.github.io/espnet/
 #### 2. HTK
 ##### HTK官网
* http://htk.eng.cam.ac.uk/download.shtml
 ##### Py2HTK
* https://github.com/g-leech/Py2HTK
 ##### parallel-htk
* https://github.com/jpuigcerver/parallel-htk
 ##### HTK_C_MATLAB_tools
* https://github.com/sinb/HTK_C_MATLAB_tools

 #### 3. Kaldi
 ##### Kaldi官网 
* https://github.com/kaldi-asr/kaldi
 ##### Kaldi官方文档（中文版）
* http://blog.geekidentity.com/asr/kaldi/kaldi_tutorial/
 ##### Kaldi models
* http://kaldi-asr.org/models.html
 ##### Corpus Phonetics Tutorial
* https://www.eleanorchodroff.com/tutorial/kaldi/kaldi-intro.html
 ##### py-kaldi-asr
* https://github.com/pykaldi/pykaldi
* https://github.com/gooofy/py-kaldi-asr
* https://github.com/UFAL-DSG/pykaldi
* https://github.com/janchorowski/kaldi-python
 ##### Dan's DNN implementation:
* http://kaldi-asr.org/doc/dnn2.html
 ##### pytorch-kaldi
* https://github.com/mravanelli/pytorch-kaldi/
 ##### kaldi-lstm
* https://github.com/dophist/kaldi-lstm
 ##### kaldi-ctc
* https://github.com/lingochamp/kaldi-ctc
 ##### keras-kaldi
* https://github.com/dspavankumar/keras-kaldi
 ##### python wrapper for kaldi-online-decoder
* https://github.com/funcwj/pydecoder
 ##### Kaldi+PDNN
* https://github.com/yajiemiao/kaldipdnn
 ##### tfkaldi
* https://github.com/vrenkens/tfkaldi
 ##### Kaldi_CNTK_AMI
* https://github.com/chenguoguo/Kaldi_CNTK_AMI
 ##### kaldi-io-for-python
* https://github.com/vesis84/kaldi-io-for-python
 ##### kaldi-pyio
* https://github.com/funcwj/kaldi-pyio
 ##### kaldi-tree-conv
* https://github.com/dophist/kaldi-tree-conv
 #### kaldi-ivector
* https://github.com/idiap/kaldi-ivector
 ##### kaldi-yesno-tutorial
* https://github.com/keighrim/kaldi-yesno-tutorial
 ##### Kaldi nnet3 教程
* https://gist.github.com/candlewill/f6c789059bf28b99cee8e18b99c20bfd
 ##### Josh Meyer's Website
* http://jrmeyer.github.io/
 ##### Adapting your own Language Model for Kaldi
* https://github.com/srvk/lm_build
 ##### Some Kaldi Notes
* http://jrmeyer.github.io/asr/2016/02/01/Kaldi-notes.html
* http://sentiment-mining.blogspot.com/
* http://pages.jh.edu/~echodro1/tutorial/kaldi/
 ##### kaldi_tutorial
* https://github.com/hyung8758/kaldi_tutorial
 ##### Online decoder for Kaldi NNET2 and GMM speech recognition models with Python bindings
* https://github.com/UFAL-DSG/alex-asr
 ##### ResNet-Kaldi-Tensorflow-ASR
* https://github.com/fernandodelacalle/ResNet-Kaldi-Tensorflow-ASR
 ##### Kaldi ASR: Extending the ASpIRE model
* https://chrisearch.wordpress.com/2017/03/11/speech-recognition-using-kaldi-extending-and-using-the-aspire-model/
 ##### FastCGI support for Kaldi ASR
* https://github.com/dialogflow/asr-server
 ##### alignUsingKaldi
* https://github.com/Sundy1219/alignUsingKaldi
 ##### kaldi-readers-for-tensorflow
* https://github.com/t13m/kaldi-readers-for-tensorflow
 ##### kaldi-iot
* https://github.com/dophist/kaldi-iot
 ##### lattice-info
* https://github.com/jpuigcerver/lattice-info
 ##### lattice-char-to-word
* https://github.com/jpuigcerver/lattice-char-to-word
 ##### lattice-word-length-distribution
* https://github.com/jpuigcerver/lattice-word-length-distribution
 ##### kaldi-lattice-word-index
* https://github.com/jpuigcerver/kaldi-lattice-word-index
 ##### kaldi-decoders
* https://github.com/jpuigcerver/kaldi-decoders
 ##### lattice-remove-ctc-blank
* https://github.com/jpuigcerver/lattice-remove-ctc-blank
 ##### kaldi-lattice-search
* https://github.com/jpuigcerver/kaldi-lattice-search
 ##### htk2kaldi
* https://github.com/jpuigcerver/htk2kaldi
 ##### parallel-kaldi
* https://github.com/jpuigcerver/parallel-kaldi
 ##### kaldi 在线中文识别系统搭建
* https://blog.csdn.net/shichaog/article/details/73655628
 ##### kaldi-docker
* https://github.com/golbin/kaldi-docker

 #### CSLT-Sparse-DNN-Toolkit
* https://github.com/wyq730/CSLT-Sparse-DNN-Toolkit
 #### featxtra
* https://github.com/mvansegbroeck/featxtra
 #### Sphinx
* https://cmusphinx.github.io/
* https://github.com/cmusphinx
* https://github.com/cmusphinx/pocketsphinx
 #### OpenFst
* http://www.openfst.org/twiki/bin/view/FST/WebHome
* https://github.com/UFAL-DSG/openfst
* https://github.com/benob/openfst-utils
* https://github.com/vchahun/pyfst
 #### MIT Spoken Language Systems
* https://groups.csail.mit.edu/sls/downloads/
 #### Julius
* http://julius.osdn.jp/en_index.php
* https://github.com/julius-speech/julius
 #### Bavieca
* http://www.bavieca.org/
 #### Simon 
* https://simon.kde.org/
 #### SIDEKIT
* http://www-lium.univ-lemans.fr/sidekit/
 #### SRILM
* https://www.sri.com/engage/products-solutions/sri-language-modeling-toolkit
* http://www.speech.sri.com/projects/srilm/
* https://github.com/nuance1979/srilm-python
* https://github.com/njsmith/pysrilm
 #### awd-lstm-lm
* https://github.com/salesforce/awd-lstm-lm
 #### ISIP
* https://www.isip.piconepress.com/projects/speech/

 #### MIT Finite-State Transducer (FST) Toolkit
* http://groups.csail.mit.edu/sls/downloads/
 #### MIT Language Modeling (MITLM) Toolkit
* http://groups.csail.mit.edu/sls/downloads/
 #### OpenGrm
* http://www.openfst.org/twiki/bin/view/GRM/WebHome
 #### RNNLM
* http://www.fit.vutbr.cz/~imikolov/rnnlm/
* https://github.com/IntelLabs/rnnlm
* https://github.com/glecorve/rnnlm2wfst
 #### faster-rnnlm
* https://github.com/yandex/faster-rnnlm
 #### CUED-RNNLM Toolkit
* http://mi.eng.cam.ac.uk/projects/cued-rnnlm/
 #### Using RNNLM rescoring a sentence in Chinese ASR system
* https://github.com/Sundy1219/RNNLM
 #### KenLM
* https://github.com/kpu/kenlm
* https://kheafield.com/code/kenlm/
 #### rwthlm
* https://www-i6.informatik.rwth-aachen.de/web/Software/rwthlm.php
 #### word-rnn-tensorflow
* https://github.com/hunkim/word-rnn-tensorflow
 #### tensorlm
* https://github.com/batzner/tensorlm
 #### SpeechRecognition
* https://github.com/Uberi/speech_recognition
 #### SpeechPy
* https://github.com/astorfi/speechpy
 #### Aalto
* https://github.com/aalto-speech/AaltoASR
 #### google-cloud-speech
* https://pypi.org/project/google-cloud-speech/
 #### apiai
https://pypi.org/project/apiai/
 #### wit
* https://github.com/wit-ai/pywit
 #### Nabu
* https://github.com/vrenkens/nabu
 #### asr-study
* https://github.com/igormq/asr-study
 #### dejavu
* https://github.com/worldveil/dejavu
 #### uSpeech
* https://github.com/arjo129/uSpeech
 #### Juicer
* https://github.com/idiap/juicer
 #### PMLS
* http://pmls.readthedocs.io/en/latest/dnn-speech.html
 #### dragonfly
* https://github.com/t4ngo/dragonfly
 #### SPTK
* https://github.com/r9y9/SPTK
* https://github.com/sp-nitech/SPTK
* http://sp-tk.sourceforge.net/
 #### pysptk
* https://github.com/r9y9/pysptk
 #### RWTH ASR
* https://www-i6.informatik.rwth-aachen.de/rwth-asr/
 #### Palaver
* https://github.com/JamezQ/Palaver
 #### Praat
* http://www.fon.hum.uva.nl/praat/
* https://github.com/kylebgorman/textgrid
 #### Speech Recognition Grammar Specification
* https://www.w3.org/TR/speech-grammar/
 #### Automatic_Speech_Recognition
* https://github.com/zzw922cn/Automatic_Speech_Recognition
 #### speech-to-text-wavenet
* https://github.com/buriburisuri/speech-to-text-wavenet
 #### tensorflow-speech-recognition
* https://github.com/pannous/tensorflow-speech-recognition
 #### tensorflow_end2end_speech_recognition
* https://github.com/hirofumi0810/tensorflow_end2end_speech_recognition
 #### tensorflow_speech_recognition_demo
* https://github.com/llSourcell/tensorflow_speech_recognition_demo
 #### AVSR-Deep-Speech
* https://github.com/pandeydivesh15/AVSR-Deep-Speech
 #### TTS and ASR
* https://github.com/roboticslab-uc3m/speech
 #### CTC + Tensorflow Example for ASR
* https://github.com/igormq/ctc_tensorflow_example
 #### tensorflow-ctc-speech-recognition
* https://github.com/philipperemy/tensorflow-ctc-speech-recognition
 #### speechT
* https://github.com/timediv/speechT
 #### end2endASR
* https://github.com/cdyangbo/end2endASR
 #### NADU
* https://github.com/vrenkens/nabu
 #### DTW (Dynamic Time Warping) python module
* https://github.com/pierre-rouanet/dtw
 #### Various scripts and tools for speech recognition model building
* https://github.com/gooofy/speech
 #### 基于深度学习的语音识别系统，使用CNN、LSTM和CTC实现的中文语音识别系统
* https://github.com/nl8590687/ASRT_SpeechRecognition
 #### tacotron_asr
* https://github.com/Kyubyong/tacotron_asr
 #### ASR_Keras
* https://github.com/Chriskamphuis/ASR
 #### Kaggle Tensorflow Speech Recognition Challenge
* https://dinantdatascientist.blogspot.dk/2018/02/kaggle-tensorflow-speech-recognition.html
 #### Speech recognition script for Asterisk that uses google's speech engine
* https://github.com/zaf/asterisk-speech-recog
 #### Libraries and scripts for manipulating and handling ASR output/n-bests/etc
* https://github.com/belambert/asr-tools
 #### Some scripts and commands for working with ASR
* https://github.com/JRMeyer/asr
 #### PySpeechGrammar
* https://github.com/ynop/pyspeechgrammar
 #### Python module for evaluating ASR hypotheses
* https://github.com/belambert/asr-evaluation
 #### edit-distance
* https://github.com/belambert/edit-distance


 ### <h3 id="1.3">dataset</h3>
 #### VoxForge
* http://www.voxforge.org/home
* http://www.voxforge.org/zh
* http://www.repository.voxforge1.org/downloads/SpeechCorpus/Trunk/Audio/Main/16kHz_16bit/
 #### ASR Audio Data Links
* https://github.com/robmsmt/ASR_Audio_Data_Links
 #### The CMU Pronouncing Dictionary
* http://www.speech.cs.cmu.edu/cgi-bin/cmudict
 #### TIMIT
* https://catalog.ldc.upenn.edu/LDC93S1
* https://github.com/syhw/timit_tools
* https://github.com/philipperemy/timit
 #### GlobalPhone Language Models
* http://www.csl.uni-bremen.de/GlobalPhone/
 #### 1 Billion Word Language Model Benchmark
* https://github.com/ciprian-chelba/1-billion-word-language-modeling-benchmark
* http://www.statmt.org/lm-benchmark/
 #### DaCiDian-Develop
* https://github.com/dophist/DaCiDian-Develop
 #### CC-CEDICT
* https://www.mdbg.net/chinese/dictionary?page=cc-cedict
 #### TED-LIUM
* https://lium.univ-lemans.fr/ted-lium3/
 #### open-asr-lexicon
* https://github.com/dophist/open-asr-lexicon

 ### <h3 id="1.4">Tutorial</h3>
 #### University of Edinburgh ASR2017-18
* http://www.inf.ed.ac.uk/teaching/courses/asr/
 #### stanford CS224s
* https://web.stanford.edu/class/cs224s/syllabus.html
 #### NYU asr12
* https://cs.nyu.edu/~mohri/asr12/
 #### Speech Recognition with Neural Networks
* http://andrew.gibiansky.com/blog/machine-learning/speech-recognition-neural-networks/


## <h2 id="2">语音合成</h2>
 ### <h3 id="2.1">page</h3>
 #### CSTR-Edinburgh
* https://github.com/CSTR-Edinburgh

 ### <h3 id="2.2">open source library/toolbox</h3>
 #### WORLD
* https://github.com/mmorise/World
 #### HTS
* http://hts.sp.nitech.ac.jp/
* http://hts-engine.sourceforge.net/
* https://github.com/shamidreza/HTS-demo_CMU-ARCTIC-SLT-Formant
* https://github.com/MattShannon/HTS-demo_CMU-ARCTIC-SLT-STRAIGHT-AR-decision-tree
 #### Tacotron
* https://github.com/Kyubyong/tacotron
* https://github.com/Kyubyong/expressive_tacotron
* https://github.com/keithito/tacotron
* https://github.com/GSByeon/multi-speaker-tacotron-tensorflow
* https://github.com/r9y9/tacotron_pytorch
* https://github.com/soobinseo/Tacotron-pytorch
 #### Tacotron2
* https://github.com/NVIDIA/tacotron2
* https://github.com/riverphoenix/tacotron2
* https://github.com/A-Jacobson/tacotron2
* https://github.com/selap91/Tacotron2
* https://github.com/LGizkde/Tacotron2_Tao_Shujie
* https://github.com/rlawns1016/Tacotron2
* https://github.com/CapstoneInha/Tacotron2-rehearsal
 #### Merlin
* https://github.com/CSTR-Edinburgh/merlin
 #### mozilla TTS
* https://github.com/mozilla/TTS
 #### Flite
* http://www.speech.cs.cmu.edu/flite/
* https://github.com/festvox/flite
 #### Speect
* http://speect.sourceforge.net/
 #### Festival
* https://github.com/festvox/festival
 #### eSpeak
* http://espeak.sourceforge.net/
* https://github.com/gooofy/py-espeak-ng
 #### nnmnkwii
* https://github.com/r9y9/nnmnkwii
 #### Ossian
* https://github.com/CSTR-Edinburgh/Ossian
 #### gTTS
* https://github.com/pndurette/gTTS
 #### gnuspeech
* http://git.savannah.gnu.org/cgit/gnuspeech.git
 #### supercollider
* https://github.com/supercollider/supercollider
 #### sc3-plugins
* https://github.com/supercollider/sc3-plugins
 #### Neural_Network_Voices
* https://github.com/llSourcell/Neural_Network_Voices
 #### pggan-pytorch
* https://github.com/deepsound-project/pggan-pytorch
 #### cainteoir-engine
* https://github.com/rhdunn/cainteoir-engine
 #### loop
* https://github.com/facebookresearch/loop
 #### nnmnkwii
* https://github.com/r9y9/nnmnkwii
 #### TTS and ASR
* https://github.com/roboticslab-uc3m/speech
 #### musa_tts
* https://github.com/santi-pdp/musa_tts
 #### marytts(JAVA)
* https://github.com/marytts/marytts


## <h2 id="3">声纹识别</h2>
 ### <h3 id="3.2">open source library/toolbox</h3>
 #### Alize
* http://mistral.univ-avignon.fr/
 #### speaker-recognition-py3
* https://github.com/crouchred/speaker-recognition-py3
 #### openVP
* https://github.com/dake/openVP
* https://github.com/swshon?tab=repositories
 ### Gender recognition by voice and speech analysis
* http://www.primaryobjects.com/2016/06/22/identifying-the-gender-of-a-voice-using-machine-learning/
* https://github.com/primaryobjects/voice-gender

## <h2 id="4">对话系统</h2>
 ### <h3 id="4.1">pages</h3>
 #### NTU
* http://miulab.tw/
* https://github.com/MiuLab
* https://www.csie.ntu.edu.tw/~yvchen/publication.html
 #### Tsung-Hsien Wen
* https://shawnwun.github.io/
 
 ### <h3 id="4.2">open source library/toolbox</h3>
 #### PyDial
* http://www.camdial.org/pydial/
 #### alex
* https://github.com/UFAL-DSG/alex
 #### ROS 语音交互系统
* https://github.com/hntea/ros-speech
 #### 结合ROS框架的中文语音交互系统 
* https://github.com/hntea/speech-system-zh

## <h2 id="5">前端</h2>
 ### <h3 id="5.1">Speech Processing</h3>
 #### madmom
* https://github.com/CPJKU/madmom
 #### pydub
* https://github.com/jiaaro/pydub
 #### kapre: Keras Audio Preprocessors
* https://github.com/keunwoochoi/kapre
 #### BTK
* http://distantspeechrecognition.sourceforge.net/
 #### EspNet
* https://github.com/espnet/espnet
 #### Signal-Processing
* https://github.com/mathEnthusaistCodes/Signal-Processing
 #### pyroomacoustics
* https://github.com/LCAV/pyroomacoustics
 #### librosa
* https://github.com/librosa/librosa
* https://github.com/librosa/librosa_gallery
 #### REAPER
* https://github.com/google/REAPER
 #### MSD_split_for_tagging
* https://github.com/keunwoochoi/MSD_split_for_tagging
 #### VOICEBOX
* http://www.ee.ic.ac.uk/hp/staff/dmb/voicebox/voicebox.html
 #### liquid-dsp
* https://github.com/jgaeddert/liquid-dsp
 #### ffts
* https://github.com/anthonix/ffts
 #### mir_eval
* https://github.com/craffel/mir_eval
 #### aupyom
* https://github.com/pierre-rouanet/aupyom
 #### Pitch Detection
* http://note.sonots.com/SciSoftware/Pitch.html
 #### TFTB
* http://tftb.nongnu.org/
 #### maracas
* https://github.com/jfsantos/maracas
 #### SRMRpy
* https://github.com/jfsantos/SRMRpy
 #### ssp
* https://github.com/idiap/ssp
* https://github.com/idiap/libssp
 #### iss
* https://github.com/idiap/iss
* https://github.com/idiap/iss-dicts
 #### asr_preprocessing
* https://github.com/hirofumi0810/asr_preprocessing
 #### asrt
* https://github.com/idiap/asrt
 #### Audio super resolution using NN
* https://github.com/kuleshov/audio-super-res
 #### RNN training for noise reduction in robust asr
* https://github.com/amaas/rnn-speech-denoising
 #### RNN for audio noise reduction
* https://github.com/xiph/rnnoise
 #### muda
* https://github.com/bmcfee/muda
 #### Efficient sample rate conversion in python
* https://github.com/bmcfee/resampy
 #### Smarc audio rate converter
* http://audio-smarc.sourceforge.net/
 #### Python scripts to computes f0s of a wave file
* https://github.com/t13m/pyPitchCom

 ### <h3 id="5.2">Audio I/O</h3>
 #### PortAudio
* http://www.portaudio.com/
 #### audiolab
* https://github.com/cournape/audiolab
 #### pytorch audio
* https://github.com/pytorch/audio
 #### Digital Speech Decoder
* https://github.com/szechyjs/dsd
 #### audioread
* https://github.com/beetbox/audioread
 #### audacity.py
* https://github.com/davidavdav/audacity.py

 ### <h3 id="5.3">Sound Source Separation</h3>
 #### HARK
* https://www.hark.jp/wiki.cgi?page=HARK+Installation+Instructions
 #### Deep RNN for Source Separation
* https://github.com/posenhuang/deeplearningsourceseparation
 #### nussl
* https://github.com/interactiveaudiolab/nussl
 #### DNN for Music Source Separation in Tensorflow
* https://andabi.github.io/music-source-separation/
 #### Alexey Ozerov
* http://www.irisa.fr/metiss/ozerov/
 #### University of Surrey CVSSP
* https://github.com/CVSSP
 #### source separation using CNN
* https://github.com/emma-mens/ASR

 ### <h3 id="5.4">Feature Extraction</h3>
 #### openSMILE
* https://audeering.com/technology/opensmile/
* https://github.com/naxingyu/opensmile
 #### veles.sound_feature_extraction
* https://github.com/Samsung/veles.sound_feature_extraction
 #### vamp-plugin-sdk
* https://github.com/c4dm/vamp-plugin-sdk
 #### Yaafe
* http://yaafe.sourceforge.net/
 #### py_bank
* https://github.com/wil-j-wil/py_bank
 #### AuditoryFilterbanks
* https://github.com/jfsantos/AuditoryFilterbanks
 #### python_speech_features
* https://github.com/jameslyons/python_speech_features

 ### <h3 id="5.5">VAD</h3>
* https://github.com/jtkim-kaist/VAD
* https://github.com/jtkim-kaist/VAD_DNN
* https://github.com/marsbroshok/VAD-python
* https://github.com/shiweixingcn/vad
* https://github.com/fedden/RenderMan
 #### rVAD
* http://kom.aau.dk/~zt/online/readme.htm
 #### Aurora 2 VAD
* http://kom.aau.dk/~zt/online/readme.htm
 #### IsraelCohen
* http://webee.technion.ac.il/people/IsraelCohen/Info/Software.html
 #### Python interface to the WebRTC Voice Activity Detector
* https://github.com/wiseman/py-webrtcvad


## <h2 id="6">资源</h2>
 ###<h3 id="6.1">code/tool/data</h3>
 ### cmusphinx
* https://github.com/cmusphinx
 #### julius-speech
* https://github.com/julius-speech
 #### OpenSLR
* http://www.openslr.org/
 #### List of speech recognition software
* https://en.wikipedia.org/wiki/List_of_speech_recognition_software
 #### KTH
* http://www.speech.kth.se/software/
 #### VERBIO
* http://www.verbio.com/webverbiotm/html/productes.php?id=2
 #### timeview
* https://github.com/lxkain/timeview
 #### Speech at CMU Web Page
* http://www.speech.cs.cmu.edu/
 #### CMU Robust Speech Group
* http://www.cs.cmu.edu/~robust/code.html
 #### Speech Software at CMU
* http://www.speech.cs.cmu.edu/hephaestus.html
 #### Aalto Speech Research
* https://github.com/aalto-speech
 #### CMU Festvox Project
* https://github.com/festvox?tab=repositories
* http://www.festvox.org/
 #### CSTR
* http://www.cstr.ed.ac.uk/research/
* http://www.cstr.ed.ac.uk/downloads/
 #### Xiph
* https://github.com/xiph
 #### Brno University of Technology Speech Processing Group
* http://speech.fit.vutbr.cz/software
 #### SoX
* http://sox.sourceforge.net/
 #### STRAIGHT
* https://github.com/shuaijiang/STRAIGHT
* http://www.wakayama-u.ac.jp/~kawahara/STRAIGHTadv/index_e.html
 #### Idiap Research Institute
* https://github.com/idiap
 #### Transcriber
* http://trans.sourceforge.net/en/presentation.php
 #### Amirsina Torfi
* https://github.com/astorfi?tab=repositories
 #### The Speech Recognition Virtual Kitchen
* https://github.com/srvk
* http://www.clsp.jhu.edu/~sriram/software/soft.html
 #### Sparse Representation & Dictionary Learning Algorithms with Applications in Denoising, Separation, Localisation and Tracking
* http://personal.ee.surrey.ac.uk/Personal/W.Wang/codes.html
 #### Audacity
* https://www.audacityteam.org/
 #### beetbox
* https://github.com/beetbox
 #### CAQE
* https://github.com/interactiveaudiolab/CAQE
 #### UCL Speech Filing System
* http://www.phon.ucl.ac.uk/resource/sfs/
 #### Ryuichi Yamamoto
* https://github.com/r9y9?tab=repositories
 #### Kyubyong Park
* https://github.com/Kyubyong?tab=repositories
 #### Hideyuki Tachibana
* https://github.com/tachi-hi?tab=repositories
 #### Colin Raffel
* https://github.com/craffel?tab=repositories
 #### Paul Dixon
* https://github.com/edobashira?tab=repositories
 #### smacpy
* https://github.com/danstowell/smacpy
 #### c4dm
* http://c4dm.eecs.qmul.ac.uk/software_data.html
 #### Matt Shannon
* https://github.com/MattShannon?tab=repositories
 #### Keunwoo Choi
* https://github.com/keunwoochoi?tab=repositories
 #### ADASP
* http://www.tsi.telecom-paristech.fr/aao/en/software-and-database/
 #### uchicago Speech and Language @ TTIC
* http://ttic.uchicago.edu/~klivescu/SLATTIC/resources.htm
 #### justin salamon
* http://www.justinsalamon.com/codedata.html
 #### COLEA
* http://ecs.utdallas.edu/loizou/speech/colea.htm
 #### openAUDIO
* http://www.openaudio.eu/
 #### Praat
* http://www.fon.hum.uva.nl/praat/
* https://github.com/timmahrt/praatIO
 #### librosa
* https://github.com/librosa
 #### Essentia
* https://github.com/MTG/essentia
 #### timmahrt
* https://github.com/timmahrt?tab=repositories
 #### Lefteris Zafiris
* https://github.com/zaf?tab=repositories
 #### audio-to-audio and audio-to-midi alignment
* https://github.com/cataska/scorealign
 #### DNN based hotword and wake word detection toolkit 
* https://github.com/Kitt-AI/snowboy
 #### free-spoken-digit-dataset
* https://github.com/Jakobovski/free-spoken-digit-dataset
 #### 中文语言资源联盟
* http://www.chineseldc.org/resource_list.php?begin=0&count=20
 #### Institute of Formal and Applied Linguistics – Dialogue Systems Group
* https://github.com/UFAL-DSG

* https://github.com/edobashira/speech-language-processing
* https://github.com/andabi?tab=repositories
* https://code.soundsoftware.ac.uk/projects

 ### <h3 id="6.2">tutorial</h3>
 #### DL for Computer Vision, Speech, and Language
* http://llcao.net/cu-deeplearning17/resource.html
 #### 臺大數位語音處理概論
* http://speech.ee.ntu.edu.tw/courses.html
* http://ocw.aca.ntu.edu.tw/ntu-ocw/ocw/cou/104S204
 #### IISc Speech Information Processing
* http://www.ee.iisc.ac.in/new/people/faculty/prasantg/e9261_speech_jan2018.html
* http://www.practicalcryptography.com/miscellaneous/machine-learning/
 
 ### <h3 id="6.3">paper</h3>
* https://arxiv.org/search/?query=speech&searchtype=all&source=header
* https://www.isca-speech.org/iscaweb/index.php/archive/online-archive
* https://www.aclweb.org/anthology/
* https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers
 #### states of the arts and recent results (bibliography) on speech recognition
* https://github.com/syhw/wer_are_we



## <h2 id="7">主页</h2>
 #### Dan Povey
* http://www.danielpovey.com/publications.html
 #### cmusphinx
* https://github.com/cmusphinx
 #### CMU Language Technologies Institute
* https://www.lti.cs.cmu.edu/work
 #### CMU SPEECH@SV
* http://speech.sv.cmu.edu/publications.html
 #### Mitsubishi Electric Research Laboratorie
* http://www.merl.com/publications/
 #### MIT Spoken Language Systems
* https://groups.csail.mit.edu/sls/downloads/
 #### Brno University of Technology Speech Processing Group
* http://speech.fit.vutbr.cz/software
 #### IISc
* https://spire.ee.iisc.ac.in/spire/allPublications.php
 #### uchicago Speech and Language @ TTIC
* http://ttic.uchicago.edu/~klivescu/SLATTIC/resources.htm
 #### RWTH Aachen University
* https://www-i6.informatik.rwth-aachen.de/web/Software/index.html
 #### TOKUDA and NANKAKU LABORATORY
* http://www.sp.nitech.ac.jp/index.php?HOME%2FSOFTWARE
 #### Institute of Formal and Applied Linguistics – Dialogue Systems Group
* https://github.com/UFAL-DSG
 #### Ohio State University speech separation
* http://web.cse.ohio-state.edu/pnl/software.html 
 #### LEAP Laboratory
* http://www.leap.ee.iisc.ac.in/publications/
 #### Hainan Xu
* https://www.cs.jhu.edu/~hxu/
 #### Mark Gales
* http://mi.eng.cam.ac.uk/~mjfg/
 #### Karen Livescu
* http://ttic.uchicago.edu/~klivescu/
 #### Shubham Toshniwal
* https://github.com/shtoshni92?tab=repositories
 #### Adrien Ycart
* http://www.eecs.qmul.ac.uk/~ay304/code.html
 #### Ron Weiss 
* https://ronw.github.io//
 #### Yajie Miao
* https://www.cs.cmu.edu/~ymiao/
 #### Scott T Wisdom
* https://sites.google.com/site/scottwisdomhomepage/publications
 #### Alan W Black
* https://www.cs.cmu.edu/~awb/
 #### Amirsina Torfi
* https://www.amirsinatorfi.com/publications
 #### Liang Lu
* http://ttic.uchicago.edu/~llu/
 #### Zhizheng WU
* http://www.zhizheng.org/
 #### justin salamon
* http://www.justinsalamon.com/codedata.html
 #### Karen Livescu
* http://ttic.uchicago.edu/~klivescu/
 #### Shubham Toshniwal
* http://ttic.uchicago.edu/~shtoshni/#pubs
* https://github.com/shtoshni92?tab=repositories
 #### Keith Vertanen
* http://www.keithv.com/software/
 #### Aviv Gabbay
* http://www.cs.huji.ac.il/~avivga/
 #### Mehryar Mohri
* https://cs.nyu.edu/~mohri/
 #### Jonathan LE ROUX
* http://www.jonathanleroux.org/
 #### Suyoun Kim
* https://synetkim.github.io/
 #### DeepSound
* http://deepsound.io/
 #### Lei Xie
* http://lxie.npu-aslp.org/
