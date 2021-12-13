#  Dynamic High-Pass Filtering and Multi-Spectral Attention for Image Super-Resolution (ICCV 2021).
Project Page

TBD this page is being updated.


You can find all visual results for each benchmark dataset and scale (x2, x3, x4) at this google drive link.  
https://drive.google.com/file/d/1bT7KRIG_ZQGzDEwDqyx0I3W5sUDR31D7/view?usp=sharing

 # Contents
 1. Introduction
 2. Results
 3. Citation
 4. Acknowledgements 


### Introduction

Deep convolutional neural networks (CNNs) have pushed forward the frontier of super-resolution (SR) research. However, current CNN models exhibit a major flaw: they are biased towards learning low-frequency sig- nals. This bias becomes more problematic for the image SR task which targets reconstructing all fine details and image textures. To tackle this challenge, we propose to improve the learning of high-frequency features both locally and glob- ally and introduce two novel architectural units to exist- ing SR models. Specifically, we propose a dynamic high- pass filtering (HPF) module that locally applies adaptive filter weights for each spatial location and channel group to preserve high-frequency signals. We also propose a matrix multi-spectral channel attention (MMCA) module that predicts the attention map of features decomposed in the frequency domain. This module operates in a global con- text to adaptively recalibrate feature responses at differ- ent frequencies. Extensive qualitative and quantitative results demonstrate that our proposed modules achieve better accuracy and visual improvements against state-of-the-art methods on several benchmark datasets.


### Results

You can find all visual results for each benchmark dataset and scale (x2, x3, x4) at this google drive link.  
https://drive.google.com/file/d/1bT7KRIG_ZQGzDEwDqyx0I3W5sUDR31D7/view?usp=sharing

### Citation

@inproceedings{abdelmagid2021dynamic,
  title={Dynamic High-Pass Filtering and Multi-Spectral Attention for Image Super-Resolution},
  author={Magid, Salma Abdel and Zhang, Yulun and Wei, Donglai and Jang, Won-Dong and Lin, Zudi and Fu, Yun and Pfister, Hanspeter},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={4288--4297},
  year={2021}
}

### Acknowledgements 
