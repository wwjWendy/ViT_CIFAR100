# ViT_CIFAR100

### Requirements
torch
torchvision
torchsummary
pytorch-lightning==1.2.1
comet-ml==3.3.5
matplotlib
numpy
pandas
scipy


### Train ViT on CIFAR-100
main.py --dataset c100 --label-smoothing --autoaugment

### Ref.

* ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale", Dosovitskiy, A., et. al, (ICLR'21) ](https://openreview.net/forum?id=YicbFdNTTy)
  * Vision Transformer paper.

* ["TransGAN: Two Transformers Can Make One Strong GAN", Jiang, Y., et. al, (2021)](https://arxiv.org/abs/2102.07074)
  * This repo is inspired by the discriminator of TransGAN.

* ["Training data-efficient image transformers & distillation through attention", Touvron, H., et. al, (2021)](https://arxiv.org/abs/2012.12877)
  * Some tricks comes from this paper.
