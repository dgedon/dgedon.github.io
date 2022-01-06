---
layout: archive
title: "ResNet-based ECG Diagnosis of Myocardial Infarction in the Emergency Department"
permalink: /publications/2112_nstemiworkshop/
author_profile: true
---


## Abstract

Myocardial infarctions (MIs) are often missed
in the emergency department. In managed settings deep learning models have shown promise 
in electrocardiogram (ECG) classification. However, in a real-world scenario there is a lack 
of high performing models for classification of 
MIs. We developed a ResNet-based deep neural network to classify the ECG between non-ST-elevation MI (NSTEMI), ST-elevation MI 
(STEMI), and control status in the more challenging real-world setting. In a test set, our 
model discriminates STEMIs/NSTEMIs with 
an AUROC of 0.85/0.76 and a Brier score of 
0.10/0.18. The model also generalizes well and 
obtains a similar performance on an additional 
test set collected in the months following the initial collection and that does not overlap temporally with the set used for developing the model. 
Our results are on par with human-level performance reported in previous studies for STEMIs 
and above human-level for NSTEMIs.

---
This is the workshop paper for the working manuscript 
[Artificial Intelligence-Based ECG Diagnosis of Myocardial Infarction in High-Risk Emergency Department Patients](/publications/2202_nstemi/).
In this workshop paper we concentrate on high risk patients which were admitted to the coronary care unit. 
In the full paper, we extend this to all patients at the emergency department which increases the control pool massively.

This paper was admitted as spotlight talk to the NeurIPS workshop.

---
**Authors:** **Daniel Gedon**$^\ast$, Stefan Gustafsson$^\ast$, Erik Lampa, Antônio H. Ribeiro, Martin J. Holzmann, Thomas B. Schön, Johan Sundström\
**Publication:** Machine learning from ground truth: New medical imaging datasets for unsolved medical problems Workshop at NeurIPS, 2021 (Online), Spotlight talk\
**Links:**
[Paper](/files/pdf/publications/21_NSTEMI_AI_Health_workshop.pdf){: .btn--research}
[Slides](/files/pdf/slides/211214_neurips_gedon_handout.pdf){: .btn--research}\
**BibTeX Citation:**
```
@inproceedings{gedon2021,
  author={Gedon, Daniel and Gustafsson, Stefan and Lampa, Erik and Ribeiro, Antônio H. and Holzmann, Martin J. and Sch{\"o}n, Thomas B and Sundstr{\"o}m, Johan},
  booktitle = {Advances in Neural Information Processing Systems 34/Machine learning from ground truth: New medical imaging datasets for unsolved medical problems Workshop},
  title={ResNet-based ECG Diagnosis of Myocardial Infarction in the Emergency Department},
  year={2021},
  note={online},
  }
```

---
Back to page: [Publications](\publications) or [Talks](\talks).