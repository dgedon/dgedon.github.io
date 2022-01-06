---
layout: archive
title: "Automatic 12-lead ECG classiﬁcation using a convolutional network ensemble"
permalink: /publications/2009_ecgensemble/
author_profile: true
---

<p float="center">
  <img src="/images/publications/2009_ecgensemble1.png" width="40%" />
  <img src="/images/publications/2009_ecgensemble2.png" width="40%" />
</p>

## Abstract

The 12-lead electrocardiogram (ECG) is a major diagnostic test for cardiovascular diseases and enhanced automated analysis tools might lead to more reliable diagnosis and improved clinical practice. Deep neural networks
are models composed of stacked transformations that learn
tasks by examples. Inspired by the success of these models
in computer vision, we propose an end-to-end approach for
the task at hand. We trained deep convolutional neural network models in the heterogeneous dataset provided in the
Physionet 2020 Challenge and used an ensemble of seven
of these convolutional models for the classification of abnormalities present in the ECG records. Ensembles use the
output of multiple models to generate a combined prediction and are known to improve performance and generalization when compared to the individual models. In our
submission, we use an ensemble of neural networks with
the architecture similar to the one described in Nat Commun 11, 1760 (2020) for 12-lead ECGs classification. Our
approach achieved a challenge validation score of 0.657,
and full test score of 0.132, placing us, the “Code Team”,
in 28 out of 41 in the official ranking.

---
**Authors:** Antônio H. Ribeiro, **Daniel Gedon**, Daniel Martins Teixeira, Manoel H. Ribeiro, Antonio L. Pinho Ribeiro, Thomas B. Schön, Wagner Meira Jr.\
**Publication:** Computing in Cardiology (CinC), 2020 (Online)\
**Links:**
[doi](https://www.doi.org/10.22489/CinC.2020.130){: .btn--research}{:target="_blank"}
[IEEE](https://ieeexplore.ieee.org/document/9344356){: .btn--research}{:target="_blank"}
[Code](https://github.com/antonior92/physionet-12ecg-classification){: .btn--research}{:target="_blank"}
[Slides](/files/pdf/slides/200915_CinC.pdf)[Slides](/files/pdf/slides/200915_CinC.pdf){: .btn--research}\
**BibTeX Citation:**
```
@inproceedings{ribeiro2020ecgensemble,
  author={Ribeiro, Antônio H and Gedon, Daniel and Teixeira, Daniel Martins and Ribeiro, Manoel Horta and Ribeiro, Antonio L Pinho and Sch{\"o}n, Thomas B and Meira, Wagner},
  booktitle={Computing in Cardiology},
  title={Automatic 12-lead ECG Classification Using a Convolutional Network Ensemble},
  year={2020},
  pages={1-4},
  note={online},
  }
```

---
Back to page: [Publications](\publications).