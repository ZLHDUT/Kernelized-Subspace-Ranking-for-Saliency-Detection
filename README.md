# Kernelized Subspace Ranking for Saliency Detection
This package has the source code for the paper "Kernelized Subspace Ranking for Saliency Detection" (ECCV16).

## Citing this work
If you find this work useful in your research, please consider citing:

     @inproceedings{wangeccv16,
        Author={Tiantian Wang and Lihe Zhang and Huchuan Lu and Chong Sun and Jinqing Qi},
        Title={Kernelized Subspace Ranking for Saliency Detection},
        Booktitle={European Conference on Computer Vision (ECCV)},
        Year={2016}
     }

## Installation
1. Install prerequsites for `Caffe` (see: [Caffe installation instructions](http://caffe.berkeleyvision.org/installation.html))
2. Compile the `./sds_eccv2014-master/extern/caffe`submodule.
3. Compile the `./gop_1.3` submodule.

## Prerequisites
Download pretrained SDS model from [1](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/shape/sds/). Then put it into the `./sds_eccv2014-master` folder.

## Train & Test
1. Run `demo.m` in `./code_superpixels` folder to generate superpixels in a Windows environment.
2. Train: run `train.m` to generate trained model in the `./trained_model` folder.
3. Test: run `test.m` to generate saliency maps in the `./saliency_map` folder. 

## Our Trained Model
Download our trained models from BaiDuYun Drive(https://pan.baidu.com/s/1jHXguHK). Then put it into the `./trained_model` folder.


## Saliency Map
The saliency maps on the SED1, SED2, SOD, PASCAL, MSRA, HKU-IS, THUR15K, ECSSD and DUT-OMRON datasets can be found in this repository.

## Contact
tiantianwang.ice@gmail.com

[1] Hariharan B, Arbelaez P, Girshick R, et al. Simultaneous detection and segmentation, ECCV2014


