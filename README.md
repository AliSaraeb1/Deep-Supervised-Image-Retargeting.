# Deep-Supervised-Image-Retargeting.

This repository contains a PyTorch implementation of the method from

> Yijing Mei, Xiaojie Guo, Di Sun, Gang Pan, and Jiawan Zhang,  
> **“Deep Supervised Image Retargeting”**, IEEE TCSVT, 2021.  
> [https://ieeexplore.ieee.org/document/9428129](https://ieeexplore.ieee.org/document/9428129)

Please see the following notebook (training) for the implementation code, details of implementation, and other explanations (please note that this took 30 hours on a supercomputer to finish, and there is no need to run it again). I make it available here, though:

- [deep_supervised_image_retargeting.ipynb](./deep_supervised_image_retargeting.ipynb)

We make the code for evaluating the best checkpoints of pretrained models available here (this takes roughly 10 minutes on Google Colab GPU):

- [mrgan_run_pretrained.ipynb](mrgan_run_pretrained.ipynb)

We make the pretrained checkpoints available for download and use here:

-  for the loss_mode="ours": [mrgan_tired_best.pth](mrgan_tired_best.pth) 
-  for the loss_mode="no_Lm_tv": [mrgan_no_Lm_tv_best3.pth](mrgan_no_Lm_tv_best3.pth)

To see the triplet image outputs, see 

-  [mrgan_outputs](mrgan_outputs)

To see the reported metrics, look at

-  for the loss_mode="ours": [run.log](mrgan_outputs/tired_best/run.log)
-  for the loss_mode="no_Lm_tv": [run.log](mrgan_outputs/no_Lm_tv_best3/run.log)

The TIReD dataset was made available by the authors at:  
- [https://github.com/TIReD2020/TIReD](https://github.com/TIReD2020/TIReD)


© 2026 Ali Saraeb. All rights reserved.  

