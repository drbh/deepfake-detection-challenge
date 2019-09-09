## Welcome 👋 to the unoffical deepfake-detection-challenge repo

This repopository is to help share resources and research with anyone interested in detecting deepfake videos and a starting place for those entering Facebook's $10 Million; Deepfake Detection Challenge. 

Please feel free to contribute **research papers, github repos, research summaries, anything else!**.  Just make a PR with your update and I'll merge it asap ✅


## Facebook Offical Challenge Page

https://ai.facebook.com/blog/deepfake-detection-challenge/


[![Deepfake Detection Challenge](https://img.youtube.com/vi/wxsijKZRSCQ/0.jpg)](https://www.youtube.com/watch?v=wxsijKZRSCQ "Deepfake Detection Challenge")

## Challenge Explained

“Deepfake” techniques, which present realistic AI-generated videos of real people doing and saying fictional things, have significant implications for determining the legitimacy of information presented online. Yet the industry doesn't have a great data set or benchmark for detecting them. We want to catalyze more research and development in this area and ensure that there are better open source tools to detect deepfakes. That’s why Facebook, the Partnership on AI, Microsoft, and academics from Cornell Tech, MIT, University of Oxford, UC Berkeley, University of Maryland, College Park, and University at Albany-SUNY are coming together to build the Deepfake Detection Challenge (DFDC).

The goal of the challenge is to produce technology that everyone can use to better detect when AI has been used to alter a video in order to mislead the viewer. The Deepfake Detection Challenge will include a data set and leaderboard, as well as grants and awards, to spur the industry to create new ways of detecting and preventing media manipulated via AI from being used to mislead others. The governance of the challenge will be facilitated and overseen by the Partnership on AI’s new Steering Committee on AI and Media Integrity, which is made up of a broad cross-sector coalition of organizations including Facebook, WITNESS, Microsoft, and others in civil society and the technology, media, and academic communities.

Written by Mike Schroepfer

## Grading 

Q: How will the challenge be judged a winner selected?  

A: We are going to be providing a test mechanism that enables teams to score the effectiveness of their models, against one or more black box test sets from our founding partners.


## Current Research

| Year | Title | Summary | Author | Link |
| ---- | ----- | ------- | ------ | ---- |
| 26 Aug 2019 | FaceForensics++: Learning to Detect Manipulated Facial Images | "FaceForensics++ is a dataset of facial forgeries that enables researchers to train deep-learning-based approaches in a supervised fashion. The dataset contains manipulations created with four state-of-the-art methods, namely, Face2Face, FaceSwap, DeepFakes, and NeuralTextures." | Andreas Rossler, Davide Cozzolino, Luisa Verdoliva, Christian Riess, Justus Thies, Matthias Nießner | [pdf](https://arxiv.org/pdf/1901.08971.pdf) [benchmarks](http://kaldir.vc.in.tum.de/faceforensics_benchmark/)
| 9 Aug 2019 | FakeCatcher: Detection of Synthetic Portrait Videos using Biological Signals | "w. We extract biological signals from facial regions on authentic and fake portrait video pairs. We apply transformations to compute the spatial coherence and temporal consistency, capture the signal characteristics in feature sets and PPG maps, and train a probabilistic SVM and a CNN. Then, we aggregate authenticity probabilities to decide whether the video is fake or authentic." | Umur Aybars Ciftci, Ilke Demir, Lijun Yin (Binghampton) | [pdf](https://arxiv.org/pdf/1901.02212.pdf)
| 2019 | Exposing DeepFake Videos By Detecting Face Warping Artifacts | "DeepFake algorithm can only generate images of limited resolutions, which need to be further warped to match the original faces in the source video. Such transforms leave distinctive artifacts in the resulting DeepFake videos, and we show that they can be effectively captured by convolutional neural networks (CNNs)." | Yuezun Li, Siwei Lyu (University at Albany) | [pdf](https://arxiv.org/pdf/1811.00656.pdf)
| 13 Nov 2018 | EXPOSING DEEP FAKES USING INCONSISTENT HEAD POSES | "Our method is based on the observations that Deep Fakes are created by splicing synthesized face region into the original image, and in doing so, introducing errors that can be revealed when 3D head poses are estimated from the face images. We perform experiments to demonstrate this phenomenon and further develop a classification method based on this cue. Using features based on this cue, an SVM classifier is evaluated using a set of real face images and Deep Fakes." | Xin Yang, Yuezun Li and Siwei Lyu (NYU) | [pdf](https://arxiv.org/pdf/1811.00661) | 
| 26 Oct 2018 | CAPSULE-FORENSICS: USING CAPSULE NETWORKS TO DETECT FORGED IMAGES AND VIDEOS | "The method introduced in this paper uses a capsule network to detect various kinds of spoofs, from replay attacks using printed images or recorded videos to computergenerated videos using deep convolutional neural networks." | Huy H. Nguyen , Junichi Yamagishi, and Isao Echizen (National Institute of Informatics, Tokyo, Japan and The University of Edinburgh, Edinburgh, UK ) | [pdf](https://arxiv.org/pdf/1810.11215.pdf)
| Oct 2018 | Forensics Face Detection From GANs Using Convolutional Neural Network | "We use GANs to create fake faces with multiple resolutions and sizes to help data augments. Moreover, we apply a deep face recognition system to transfer weight to our system for robust face feature extraction" | Tai Do Nhu, In Seop Na, S.H. Kim |[pdf](https://www.researchgate.net/profile/Tai_Do_Nhu/publication/327905310_Forensics_Face_Detection_From_GANs_Using_Convolutional_Neural_Network/links/5bac84e7a6fdccd3cb768b1c/Forensics-Face-Detection-From-GANs-Using-Convolutional-Neural-Network.pdf)
| Aug 2018 | Detection of Deepfake Video Manipulation | "photo response non uniformity (PRNU) analysis is tested for its effectiveness at detecting Deepfake video manipulation. The PRNU analysis shows a significant difference in mean normalised cross correlation scores between authentic videos and Deepfakes." | Marissa Koopman, Andrea Macarulla Rodriguez, Zeno Geradts (University of Amsterdam & Netherlands Forensic Institute) | [pdf](https://www.researchgate.net/profile/Zeno_Geradts/publication/329814168_Detection_of_Deepfake_Video_Manipulation/links/5c1bdf7da6fdccfc705da03e/Detection-of-Deepfake-Video-Manipulation.pdf)
| 2018 | Deepfake Video Detection Using Recurrent Neural Networks | "This paper proposes a temporal-aware pipeline to automatically detect deepfake videos. Our system uses a convolutional neural network (CNN) to extract frame-level features. These features are then used to train a recurrent neural network (RNN) that learns to classify if a video has been subject to manipulation or not." | D Güera, EJ Delp (Purdue) | [pdf](https://engineering.purdue.edu/~dgueraco/content/deepfake.pdf) |


## Resouces

https://github.com/aerophile/awesome-deepfakes