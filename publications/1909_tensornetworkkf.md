---
layout: archive
title: "Tensor Network Kalman Filter for LTI Systems"
permalink: /publications/1909_tensornetworkkf/
author_profile: true
---

![](/images/publications/1909_tensornetworkkf.png){:width="70%" .align-center}


## Abstract

An extension of the Tensor Network (TN) Kalman filter for large scale LTI systems is presented in this paper. 
The TN Kalman filter can handle exponentially large state vectors without constructing them explicitly. In order to 
have efficient algebraic operations, a low TN rank is required. We exploit the possibility to approximate the 
covariance matrix as a TN with a low TN rank. This reduces the computational complexity for general SISO and MIMO 
LTI systems with TN rank greater than one significantly while obtaining an accurate estimation. Improvements of 
this method in terms of computational complexity compared to the conventional Kalman filter are demonstrated in 
numerical simulations for large scale systems.

---
This publication is contained in the master thesis
[Tensor Network Kalman Filter for Large-Scale MIMO Systems: With Application to Adaptive Optics](/publications/1907_masterthesis/).

---
**Author:** **Daniel Gedon**, Pieter Piscaer, Kim Batselier, Carlas Smith, Michel Verhaegen\
**Publication:** 27th European Signal Processing Conference (EUSIPCO), 2019\
**Links:** 
[doi](https://doi.org/10.23919/EUSIPCO.2019.8902976){: .btn--research}{:target="_blank"}
[IEEE](https://ieeexplore.ieee.org/abstract/document/8902976){: .btn--research}{:target="_blank"}
[Code](https://github.com/dgedon/Tensor-Kalman-Filter){: .btn--research}{:target="_blank"}\
**BibTeX Citation:**
```
@inproceedings{gedon2019tensornetworkkf,
  author={Gedon, Daniel and Piscaer, Pieter and Batselier, Kim and Smith, Carlas and Verhaegen, Michel},
  booktitle={27th European Signal Processing Conference (EUSIPCO)}, 
  title={Tensor Network Kalman Filter for LTI Systems}, 
  year={2019},
  pages={1-5},
  address={A Coruna, Spain},
  }
```

---
Back to page: [Publications](\publications) or [Talks](\talks).