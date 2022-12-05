# Computer Vision

In this repository some projects in the context of Computer Vision are presented. These projects include contents of the graduate level courses of the Technical University of Munich. 

## Foreground Background Detection
:key: Keywords: Gaussian Mixture Model, Unsupervised foreground segmentation

:wrench: Matlab

#### Segmentation
Implementation of a Gaussian Mixture Model based forground segmenation model from the papers "Efficient adaptive density estimation per image pixel for the task of background subtraction" [[1]](#1), "Improved Adaptive Gaussian Mixture Model for Background Subtraction"[[2]](#2) and Adaptive background mixture models for real-time tracking [[3]](#3). The model was developed in Matlab and evaluated on the ChokePoint Dataset [[4]](#4).

<p align="center">
<img src="etc/GaussianMixtureModel.gif" alt="animated" width="400"/>
</p>

:link: https://arma.sourceforge.net/chokepoint/

Observations: Objects that move once the background model has been created tend to create a "ghost". This phenomenon can best be observed if the start of the frames is chosen in such a way that a person is already in the image at this point. The "ghost" remains in the image as foreground for the following frames. 

#### :bookmark_tabs: Sources

<a id="1">[1]</a> Efficient adaptive density estimation per image pixel for the task of background subtraction [Zivkov Z. et al., 2004](https://www.sciencedirect.com/science/article/pii/S0167865505003521)

<a id="2">[2]</a> Improved Adaptive Gaussian Mixture Model for Background Subtraction [Zivkov Z., 2006](https://ieeexplore.ieee.org/document/1333992)

<a id="3">[3]</a> Adaptive background mixture models for real-time tracking [Stauffer C., W.E.L Grimson 1999](http://www.ai.mit.edu/projects/vsam/Publications/stauffer_cvpr98_track.pdf)

<a id="4">[4]</a> Patch-based Probabilistic Image Quality Assessment for
Face Selection and Improved Video-based Face Recognition [Wong et al., 2014](https://arxiv.org/abs/1304.0869)


## Learning with limited (labeled) Data
:key: Keywords: Active Learning, Self-supervised Learning, Contrastive Learning

:wrench: Tools: TensorFlow, MLFlow, Docker, Kubernetes 