## Semi-supervised Domain Adaptive Medical Image Segmentation through Consistency Regularized Disentangled Contrastive Learning, MICCAI 2023

***Note:*** **Polished code coming soon!**

[Hritam Basak](https://hritam-98.github.io/), [Zhaozheng Yin](https://www3.cs.stonybrook.edu/~zyin/index.htm); [**"Semi-supervised Domain Adaptive Medical Image Segmentation through Consistency Regularized Disentangled Contrastive Learning"**](https://arxiv.org/abs/2307.02798), 26th International Conference on Medical Image Computing and Computer Assisted Intervention **(MICCAI)**, 2023.  

![Overview of Proposed Method](./figures/mainfig.png "Method at a glance")

## Abstract
Although unsupervised domain adaptation (UDA) is a promising direction to alleviate domain shift, they fall short of their supervised counterparts. In this work, we investigate relatively less explored semi-supervised domain adaptation (SSDA) for medical image segmentation, where access to a few labeled target samples can improve the adaptation performance substantially. Specifically, we propose a two-stage training process. First, an encoder is pre-trained in a self-learning paradigm using a novel domain-content disentangled contrastive learning (CL) along with a pixel-level feature consistency constraint. The proposed CL enforces the encoder to learn discriminative content-specific but domain-invariant semantics on a global scale from the source and target images, whereas consistency regularization enforces the mining of local pixel-level information by maintaining spatial sensitivity. This pre-trained encoder, along with a decoder, is further fine-tuned for the downstream task, (i.e. pixel-level segmentation) using a semi-supervised setting. Furthermore, we experimentally validate that our proposed method can easily be extended for UDA settings, adding to the superiority of the proposed strategy. Upon evaluation on two domain adaptive image segmentation tasks, our proposed method outperforms the SoTA methods, both in SSDA and UDA settings.

## Citation
If you find this article useful in your research, consider citing us:
```
@inproceedings{basak2023semisupervised,
    author = {Hritam Basak and Zheozheng Yin},
    title = {Semi-supervised Domain Adaptive Medical Image Segmentation through Consistency Regularized Disentangled Contrastive Learning},
    booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
    year={2023},
    organization={Springer}
}
```
