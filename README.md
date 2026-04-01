# Deep-Supervised-Image-Retargeting.

This repository contains a PyTorch implementation of the method from

> Yijing Mei, Xiaojie Guo, Di Sun, Gang Pan, and Jiawan Zhang,  
> **“Deep Supervised Image Retargeting”**, IEEE TCSVT, 2021.  
> [https://ieeexplore.ieee.org/document/9428129](https://ieeexplore.ieee.org/document/9428129)

Please see the notebook (training + evaluation) for the implementation code and details of implementation:

- [`deep_supervised_image_retargeting.ipynb`](./deep_supervised_image_retargeting.ipynb)

We make the code evaluating the pretrained models available here 

- [`mrgan_run_pretrained.py`](./mrgan_run_pretrained.py)

We make the pretrained checkpoints available for download and use here:

-  for the loss_mode="ours": [mrgan_tired_best.pth](mrgan_no_Lm_tv_best3.pth) 
-  for the loss_mode="no_Lm_tv": [mrgan_no_Lm_tv_best3.pth]()

The TIReD dataset was made available by the authors at:  
- [https://github.com/TIReD2020/TIReD](https://github.com/TIReD2020/TIReD)


© 2026 Ali Saraeb. All rights reserved.  

