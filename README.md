# Selective Hearing

This page provides the list of references described in the following paper:


```
Selective Hearing: A Machine Listening Perspective

@inproceedings{CanoLukashevich_MMSP19,
address = {Kuala Lumpur, Malaysia},
author = {Cano, Estefan\'{i} and Lukashevich, Hanna},
booktitle = {Proceedings of the IEEE 21st International Worshop on Multimedia Signal Processing (MMSP)},
title = {{Selective Hearing: A Machine Listening Perspective}},
year = {2019}
}
```

You can download a .bib file with all the references in the paper [here](./MMSP19_SelectiveHearing.bib). 

Below you can find more detailed information about the references and resources.


# 1. Sound Source Detection and Classification

## Sound Events [[18]](https://trepo.tuni.fi//handle/10024/116599)
* [[18]](https://trepo.tuni.fi//handle/10024/116599) Detection and Classification of Acoustic Scenes and Events (DCASE) 
[[website]](http://dcase.community/)
* [[19]](http://dcase.community/documents/workshop2018/proceedings/DCASE2018Workshop_Serizel_22.pdf) Large-scale weakly labeled semi-supervised sound event detection in domestic environments 
[[website]](http://dcase.community/challenge2018/task-large-scale-weakly-labeled-semi-supervised-sound-event-detection)
* [[20]](http://dcase.community/documents/challenge2018/technical_reports/DCASE2018_Lu_19.pdf)  Mean Teacher Convolution System for DCASE 2018 Task 4 
* [[21]](https://ieeexplore.ieee.org/abstract/document/7472917) Recurrent neural networks for polyphonic sound event detection in real life recordings
[[preprint]](http://www.cs.tut.fi/sgn/arg/music/tuomasv/parascandolo-icassp2016.pdf)
* [[22]](https://arxiv.org/abs/1805.03647) End-to-End Polyphonic Sound Event Detection Using Convolutional Recurrent Neural Networks with Learned Time-Frequency Representation Input


![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Noisy Labels`
* [[23]](https://ieeexplore.ieee.org/document/8461975) Large-Scale Weakly Supervised Audio Classification Using Gated Convolutional Neural Network 
[[preprint]](http://personal.ee.surrey.ac.uk/Personal/W.Wang/papers/XuKWP_ICASSP_2018.pdf)
* [[24]](https://ieeexplore.ieee.org/abstract/document/6685834) Classification in the Presence of Label Noise: A Survey
* [[25]](https://ieeexplore.ieee.org/document/8683158) Learning Sound Event Classifiers from Web Audio with Noisy Labels [[preprint]](https://arxiv.org/abs/1901.01189)[[code]](https://github.com/edufonseca/icassp19)
* [[26]](http://dcase.community/documents/challenge2018/technical_reports/DCASE2018_Dorfer_999.pdf) Training General-Purpose Audio Tagging Networks with Noisy Labels and Iterative Self-Verification [[code]](https://github.com/CPJKU/dcase_task2)

![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Joint optimization`
* [[27]](https://ieeexplore.ieee.org/abstract/document/8567942) Sound Event Localization and Detection of Overlapping Sources Using Convolutional Recurrent Neural Networks [[preprint]](https://arxiv.org/abs/1807.00129)

## Speech
![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `Voice Activity Detection`
* [[28]](https://www.isca-speech.org/archive/Interspeech_2018/pdfs/1151.pdf) Joint Learning Using Denoising Variational Autoencoders for Voice Activity Detection
* [[29]](https://ieeexplore.ieee.org/document/6637694) Real-life voice activity detection with LSTM Recurrent Neural Networks and an application to Hollywood movies [[preprint]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.364.4084&rep=rep1&type=pdf)
* [[30]](https://pdfs.semanticscholar.org/31c7/4962122ba5fe1c469101b5bc2ae6d88c9c18.pdf) Feature Learning with Raw-Waveform CLDNNs for Voice Activity Detection

![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Speaker Recognition`
* [[31]](https://ieeexplore.ieee.org/abstract/document/7178885) Advances in deep neural network approaches to speaker recognition

![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Robustness`
* [[32]](https://ieeexplore.ieee.org/document/8461375) X-Vectors: Robust DNN Embeddings for Speaker Recognition [[preprint]](https://www.danielpovey.com/files/2018_icassp_xvectors.pdf) [[code]](https://github.com/kaldi-asr/kaldi/tree/master/egs/sre16/v2) [[models]](http://kaldi-asr.org/models/m3)
* [[33]](https://pdfs.semanticscholar.org/dae7/c5e90bbe1538192d85282757068fef79fafa.pdf?_ga=2.97114969.795981087.1569225783-1727351385.1568271670) How to train your speaker embeddings extractor
* [[34]](https://arxiv.org/pdf/1605.01635.pdf) The IBM Speaker Recognition System: Recent Advances and Error Analysis

## Music 
![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Instrument Classification`
* [[35]](https://ieeexplore.ieee.org/document/7755799) Deep Convolutional Neural Networks for Predominant Instrument Recognition in Polyphonic Music [[preprint]](https://arxiv.org/pdf/1605.09507.pdf)
* [[36]](https://arxiv.org/abs/1605.06644) Deep convolutional networks on the pitch spiral for musical instrument recognition [[code]](https://github.com/lostanlen/ismir2016)

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `Activity Detection`
* [[37]](http://ismir2018.ircam.fr/doc/pdfs/275_Paper.pdf) Instrument Activity Detection in Polyphonic Music using Deep Neural Networks
* [[38]](http://www.ofai.at/~jan.schlueter/pubs/2018_ismir.pdf) Zero Mean Convolutions for Level-Invariant Singing Voice Detection [[code]](https://github.com/f0k/ismir2018)

# 2. Sound Source Localization [[3]](https://hal.archives-ouvertes.fr/hal-01058575/document)
* [[39]](https://ieeexplore.ieee.org/document/7952211) DOA estimation with histogram analysis of spatially constrained active intensity vectors [[preprint]](https://pdfs.semanticscholar.org/db39/56916d941cdad01ac4c59cb6749e1e34e010.pdf)
* [[40]](https://ieeexplore.ieee.org/abstract/document/8651493) Multi-Speaker DOA Estimation Using Deep Convolutional Networks Trained With Noise Signals [[preprint]](https://arxiv.org/abs/1807.11722)
* [[41]](https://ieeexplore.ieee.org/document/8010441) Multiple-Speaker Localization Based on Direct-Path Features and Likelihood Maximization With Spatial Sparsity Regularization [[preprint]](https://arxiv.org/abs/1611.01172)

![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Improving Computational Efficiency`
* [[42]](https://www.sciencedirect.com/science/article/abs/pii/S0921889017309399?via%3Dihub) Lightweight and optimized sound source localization and tracking methods for open and closed microphone array configurations [[preprint]](https://arxiv.org/abs/1812.00115)
* [[43]](https://ieeexplore.ieee.org/document/7039285) Fast Sound Source Localization Using Two-Level Search Space Clustering [[code]](https://github.com/LeeTaewoo/fast_sound_source_localization_using_TLSSC)
* [[44]](https://ieeexplore.ieee.org/document/6557035) Real-Time Multiple Sound Source Localization and Counting Using a Circular Microphone Array [[preprint]](https://hal.archives-ouvertes.fr/hal-01367320/document)
* [[45]](https://ieeexplore.ieee.org/document/8683732) End-to-end Binaural Sound Localisation from the Raw Waveform [[preprint]](https://arxiv.org/abs/1904.01916)

# 3. Sound Source Separation [[9]](https://www.wiley.com/en-sg/Audio+Source+Separation+and+Speech+Enhancement-p-9781119279891)
## Speech
* [[46]](https://ieeexplore.ieee.org/abstract/document/8264702) Speaker-Independent Speech Separation With Deep Attractor Network [[preprint]](https://arxiv.org/abs/1707.03634)
* [[47]](https://ieeexplore.ieee.org/document/8461639) Multi-Channel Deep Clustering: Discriminative Spectral and Spatial Embeddings for Speaker-Independent Speech Separation [[preprint]](https://www.merl.com/publications/docs/TR2018-007.pdf) [[demo]](http://www.merl.com/demos/deep-clustering)

![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Improving Computational Efficiency`
* [[48]](https://ieeexplore.ieee.org/document/8169997) Low latency sound source separation using convolutional recurrent neural networks [[preprint]](http://www.cs.tut.fi/~tuomasv/papers/PID4978439.pdf)
* [[49]](https://ieeexplore.ieee.org/document/7952149) Low-latency real-time blind source separation for hearing aids based on time-domain implementation of online independent vector analysis with truncation of non-causal components [[preprint]](http://spandh.dcs.shef.ac.uk/chat2017/papers/CHAT_2017_sunohara.pdf)
* [[50]](https://ieeexplore.ieee.org/abstract/document/8462116) TaSNet: Time-Domain Audio Separation Network for Real-Time, Single-Channel Speech Separation [[preprint]](https://arxiv.org/abs/1711.00541)
* [[51]](https://ieeexplore.ieee.org/document/7602895) Convolutive blind source separation with low latency [[preprint]]

## Music [[5]](https://ieeexplore.ieee.org/document/8588410)

* [[52]](https://ieeexplore.ieee.org/abstract/document/8336997) An Overview of Lead and Accompaniment Separation in Music [[preprint]](https://arxiv.org/abs/1804.08300)
* [[53]](https://link.springer.com/chapter/10.1007/978-3-319-93764-9_28) The 2018 Signal Separation Evaluation Campaign [[website]](https://sisec18.unmix.app/#/) [[preprint]](https://arxiv.org/abs/1804.06267)
* [[54]](https://ieeexplore.ieee.org/document/5784290) A Musically Motivated Mid-Level Representation for Pitch Estimation and Musical Audio Source Separation [[preprint]](https://www.researchgate.net/publication/220373063_A_Musically_Motivated_Mid-Level_Representation_for_Pitch_Estimation_and_Musical_Audio_Source_Separation)
* [[55]](https://ieeexplore.ieee.org/document/7952158) Improving music source separation based on deep neural networks through data augmentation and network blending [[preprint]](https://pdfs.semanticscholar.org/76e4/fb97d6fa7c870f5f8ec6d78242d43650b282.pdf)

![#f03c15](https://placehold.it/15/f03c15/000000?text=+)  `Spatial Separation`
* [[4]](https://ieeexplore.ieee.org/document/7473924) Projection-Based Demixing of Spatial Audio [[preprint]](https://hal.inria.fr/hal-01260588/document)

# 4. Active Noise Control (ANC) [[11]](https://ieeexplore.ieee.org/abstract/document/763310)

* [[56]](https://ieeexplore.ieee.org/document/7736174) Recent Advances in Active Noise Control Inside Automobile Cabins: Toward quieter cars
* [[57]](https://www.sciencedirect.com/science/article/abs/pii/S0003682X17303079) Hybrid approach to noise control of industrial exhaust systems 
* [[58]](https://ieeexplore.ieee.org/abstract/document/8264817) Active Noise Control Over Space: A Wave Domain Approach [[preprint]](http://users.cecs.anu.edu.au/~thush/publications/2018/ANC_Aimee.pdf)
* [[14]](https://ieeexplore.ieee.org/document/8577985) Signal Processing Challenges for Active Noise Cancellation Headphones [[preprint]](http://ikspub.iks.rwth-aachen.de/pdfs/liebich18c.pdf)

# 5. Sound Source Enhancement
## Speech [[9]](https://www.wiley.com/en-sg/Audio+Source+Separation+and+Speech+Enhancement-p-9781119279891)
* [[8]](https://ieeexplore.ieee.org/document/7038277) Phase Processing for Single-Channel Speech Enhancement: History and recent advances [[preprint]](http://www.jonathanleroux.org/pdf/Gerkmann2015SPM03.pdf)
* [[59]](https://www.isca-speech.org/archive/archive_papers/interspeech_2013/i13_0436.pdf) Speech enhancement based on deep denoising autoencoder
* [[60]](https://ieeexplore.ieee.org/document/6932438) A Regression Approach to Speech Enhancement Based on Deep Neural Networks 
* [[61]](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1428.PDF) SEGAN: Speech Enhancement Generative Adversarial Network [[preprint]](https://arxiv.org/abs/1703.09452) [[code]](https://arxiv.org/abs/1703.09452) [[demo]](http://veu.talp.cat/segan/)
* [[6]](https://ieeexplore.ieee.org/document/7805139) A Consolidated Perspective on Multimicrophone Speech Enhancement and Source Separation

## Music
* [[10]](https://archives.ismir.net/ismir2015/paper/000190.pdf) New Sonorities for Early Jazz Recordings Using Sound Source Separation and Automatic Mixing Tools
* [[63]](http://www.aes.org/e-lib/browse.cfm?elib=19277) Remixing music using source separation algorithms to improve the musical experience of cochlear implant usersPerceptual Evaluation of Source Separation for Remixing Music [[preprint]](https://pdfs.semanticscholar.org/1afc/2d6d7ef1c07e63e773cf0d0fbeb1f61db83c.pdf)
* [[64]](https://asa.scitation.org/doi/10.1121/1.4971424) Remixing music using source separation algorithms to improve the musical experience of cochlear implant users



