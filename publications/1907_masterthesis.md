---
layout: archive
title: "Tensor Network Kalman Filter for Large-Scale MIMO Systems: With Application to Adaptive Optics"
permalink: /publications/1907_masterthesis/
author_profile: true
---

<p float="center">
  <img src="/images/publications/1907_masterthesis1.png" width="40%" />
  <img src="/images/publications/1907_masterthesis2.png" width="40%" />
</p>

## Abstract

For large-scale system with tens of thousands of states and outputs the computation in the conventional Kalman 
filter becomes time-consuming such that Kalman filtering in large-scale real-time application is practically 
infeasible. A possible mathematical framework to lift the curse of dimensionality is to lift the problem in 
higher dimensions with the use of tensors and then decompose it. The tensor-train decomposition is chosen due 
to its computational advantages for systems with low tensor-train rank. Within this thesis two main limitations 
of the existing tensor Kalman filter are solved. First, a method is developed based on tensor-train rank 
truncation of the covariances to increase the computational speed for more general systems. Second, a MIMO 
tensor Kalman filter is developed for a specific class of systems. The power of the developed methods is 
shown on the example of adaptive optics which fits into the framework. A comparison with state-of-the-art 
large-scale estimation algorithms shows the computational advantage of the tensor Kalman filter at the cost 
of approximation errors.

---
This master thesis contains the publication
[Tensor Network Kalman Filter for LTI Systems](/publications/1909_tensornetworkkf/).

---
**Author:** **Daniel Gedon**\
**Publication:** Master Thesis, TU Delft\
**Links:** 
[Thesis](https://repository.tudelft.nl/islandora/object/uuid:2188c114-05ed-4fe6-9603-85de71e9bffd){: .btn--research}{:target="_blank"}
[Slides](/files/pdf/slides/190705_MasterThesis_DanielGedon_handout.pdf){: .btn--research}\
**BibTeX Citation:**
```
@mastersthesis{gedon2019masterthesis,
    author={Daniel Gedon},
    title={Tensor Network Kalman Filter for Large-Scale MIMO Systems: With Application to Adaptive Optics},
    school={Delft University of Technology},
    address={the Netherlands},
    year={2019},
    }
```

---
Back to page: [Publications](\publications) or [Talks](\talks).