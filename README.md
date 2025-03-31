A Collapse-Resistant Method for Few-shot Learning
Official PyTorch implementation of the paper A Collapse-Resistant Method for Few-shot Learning.

Requirements
Python 3.8, Pytorch 1.7.0, timm 0.3.2

Datasets
Please download mini-imagenet via link and put it in ./datasets/mini/.

Please download tiered-imagenet via link and put it in ./datasets/tiered/.

Please follow download_cifar_fs.sh to obtain the CIFAR-FS dataset and put it in ./datasets/cifarfs/.

Please follow download_fc100.sh to obtain the FC100 dataset and put it in ./datasets/fc100/.

Pretraining
Please follow https://github.com/mrkshllr/FewTURE/tree/main to pretrain the backbone ViT-small and put it in ./initialization/miniimagenet.

Training and inference
Please see ./run.bat.

Quick start :fire:
Please refer to https://github.com/mrkshllr/FewTURE/tree/main to download the checkpoint of the corresponding pretrained ViT-small model.

Put them in the corresponding folders.

Run ./run.bat in bash shell.

Acknowledgement
This repository is built using components of the FewTURE repository for pretraining and the CPEA repository for training and inference.

The metric module used in this repository is built upon DeepBDC

Citing CR-DCov
If you find this repository useful, please consider giving us a star :star: :

If you have any questions regarding our work, please feel free to reach out!
