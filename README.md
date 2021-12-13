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

Deep convolutional neural networks (CNNs) have pushed forward the frontier of super-resolution (SR) research. However, current CNN models exhibit a major flaw: they are biased towards learning low-frequency sig- nals. This bias becomes more problematic for the image SR task which targets reconstructing all fine details and image textures. To tackle this challenge, we propose to improve the learning of high-frequency features both locally and glob- ally and introduce two novel architectural units to existing SR models. Specifically, we propose a dynamic high-pass filtering (HPF) module that locally applies adaptive filter weights for each spatial location and channel group to preserve high-frequency signals. We also propose a matrix multi-spectral channel attention (MMCA) module that predicts the attention map of features decomposed in the frequency domain. This module operates in a global context to adaptively recalibrate feature responses at different frequencies. Extensive qualitative and quantitative results demonstrate that our proposed modules achieve better accuracy and visual improvements against state-of-the-art methods on several benchmark datasets.


### Results

You can find all visual results for each benchmark dataset and scale (x2, x3, x4) at this google drive link.  
https://drive.google.com/file/d/1bT7KRIG_ZQGzDEwDqyx0I3W5sUDR31D7/view?usp=sharing

### Citation
If you find the code helpful in your resarch or work, please cite the following papers:

Our paper:
```
@inproceedings{abdelmagid2021dynamic,
  title={Dynamic High-Pass Filtering and Multi-Spectral Attention for Image Super-Resolution},
  author={Magid, Salma Abdel and Zhang, Yulun and Wei, Donglai and Jang, Won-Dong and Lin, Zudi and Fu, Yun and Pfister, Hanspeter},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={4288--4297},
  year={2021}
}
```

Others used:

```
@InProceedings{Lim_2017_CVPR_Workshops,
  author = {Lim, Bee and Son, Sanghyun and Kim, Heewon and Nah, Seungjun and Lee, Kyoung Mu},
  title = {Enhanced Deep Residual Networks for Single Image Super-Resolution},
  booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  month = {July},
  year = {2017}
}

@inproceedings{zhang2018rcan,
    title={Image Super-Resolution Using Very Deep Residual Channel Attention Networks},
    author={Zhang, Yulun and Li, Kunpeng and Li, Kai and Wang, Lichen and Zhong, Bineng and Fu, Yun},
    booktitle={ECCV},
    year={2018}
}

@article{qin2020fcanet,
  title={Fcanet: Frequency channel attention networks. arXiv},
  author={Qin, Z and Zhang, P and Wu, F and Li, X},
  journal={arXiv preprint arXiv:2012.11879},
  year={2020}
}

@article{zou2020delving,
  title={Delving deeper into anti-aliasing in convnets},
  author={Zou, Xueyan and Xiao, Fanyi and Yu, Zhiding and Lee, Yong Jae},
  journal={arXiv preprint arXiv:2008.09604},
  year={2020}
}

```

### Acknowledgements
This code is built on [EDSR (PyTorch)](https://github.com/thstkdgus35/EDSR-PyTorch). We thank the authors for sharing their codes of EDSR [Torch version](https://github.com/LimBee/NTIRE2017) and [PyTorch version](https://github.com/thstkdgus35/EDSR-PyTorch).
