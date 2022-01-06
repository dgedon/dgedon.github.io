---
layout: archive
title: "First Steps Towards Self-Supervised Pretraining of the 12-Lead ECG"
permalink: /publications/2109_ecgssl/
author_profile: true
---

![](/images/publications/2109_ecgssl.png){:width="60%" .align-center}

## Abstract

Self-supervised learning is a paradigm that extracts general features which describe the input space by artificially 
generating labels from the input without the need for explicit annotations. The learned features can then be used 
by transfer learning to boost the performance on a downstream task. Such methods have recently produced state of 
the art results in natural language processing and computer 
vision. Here, we propose a self-supervised learning method 
for 12-lead electrocardiograms (ECGs). For pretraining 
the model we design a task to mask out subsegements of all 
channels of the input signals and try to predict the actual 
values. As the model architecture, we use a U-ResNet containing an encoder-decoder structure. We test our method 
by self-supervised pretraining on the CODE dataset and 
then transfer the learnt features by finetuning on the PTBXL and CPSC benchmarks to evaluate the effect of our 
method in the classification of 12-leads ECGs. The method 
does provide modest improvements in performance when 
compared to not using pretraining. In future work we will 
make use of these ideas in smaller dataset, where we believe 
it can lead to larger performance gains.

---
**Authors:** *Daniel Gedon*, Antônio H. Ribeiro, Niklas Wahlström, Thomas B. Schön\
**Publication:** Computing in Cardiology (CinC), 2021 (Online)\
**Links:**
[Paper](https://www.cinc.org/2021/Program/accepted/162_Preprint.pdf){: .btn--research}{:target="_blank"}{:target="_blank"}
[Slides](/files/pdf/slides/210915_ssl_ecg_handout.pdf){: .btn--research}
[Video (10 min)](https://www.dropbox.com/s/bvpi2h7qzkg5kod/21_cinc_ssl_ecg.mp4?dl=0){: .btn--research}\
**BibTeX Citation:**
```
@inproceedings{ribeiro2020ecgensemble,
  author={Gedon, Daniel and Ribeiro, Antônio H. and Wahlstr{\"o}m, Niklas and Sch{\"o}n, Thomas B},
  booktitle={Computing in Cardiology},
  title={First Steps Towards Self-Supervised Pretraining of the 12-Lead ECG},
  year={2021},
  pages={1-4},
  note={online},
  }
```

---
Back to page: [Publications](\publications) or [Talks](\talks).