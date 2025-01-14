# Masked Image Residual Learning for Scaling Deeper Vision Transformers
Official implementation of the paper [Masked Image Residual Learning for Scaling Deeper Vision Transformers](https://arxiv.org/abs/2309.14136)
> Abstract: Deeper Vision Transformers (ViTs) are more challenging to train. We expose a
degradation problem in deeper layers of ViT when using masked image modeling
(MIM) for pre-training. To ease the training of deeper ViTs, we introduce a self-supervised learning framework called Masked Image Residual Learning (MIRL),
which significantly alleviates the degradation problem, making scaling ViT along
depth a promising direction for performance upgrade. We reformulate the pretraining objective for deeper layers of ViT as learning to recover the residual of the
masked image. We provide extensive empirical evidence showing that deeper ViTs
can be effectively optimized using MIRL and easily gain accuracy from increased
depth. With the same level of computational complexity as ViT-Base and ViT-Large,
we instantiate 4.5× and 2× deeper ViTs, dubbed ViT-S-54 and ViT-B-48. The
deeper ViT-S-54, costing 3× less than ViT-Large, achieves performance on par with
ViT-Large. ViT-B-48 achieves 86.2% top-1 accuracy on ImageNet. On one hand,
deeper ViTs pre-trained with MIRL exhibit excellent generalization capabilities
on downstream tasks, such as object detection and semantic segmentation. On the
other hand, MIRL demonstrates high pre-training efficiency. With less pre-training
time, MIRL yields competitive performance compared to other approaches.

<div align='center'>
<img src="mirl_arch.png" alt="Architecture" width="880" style="display: block;"/>
</div>




Code and pretrained models will be uploaded soon


## Updates

***07/Oct/2023***

The preprint version is public at [arxiv](https://arxiv.org/abs/2309.14136).
