<center><img src = 'https://github.com/avs-abhishek123/Detectron2/blob/c0b9dd859690f630610a8b4fa83aaaae03b4cc08/detectron2_cover.png' width = 920 height = 500 "></center>

<h1 align ="left" style="color: purple; font-size: 80px;"><b><u>Detectron2 Object Detection & Manipulating Images using Cartoonization</u></b></h1>


## Abstract
<p> <a href = 'https://www.ijert.org/research/detectron2-object-detection-manipulating-images-using-cartoonization-IJERTV10IS080122.pdf'> [ Paper Link ] </a> </p>
<p>
In today's world, there is a rapid increase in the autonomous vehicle. There are various levels of autonomous vehicles depending upon the degree of autonomy-for the lower degree of autonomy driver has more power and functionality for managing, on coming to the fully automated vehicle like Tesla are expected to have full control
over the functions. These advances cooperate to plan the vehicle's position and its nearness to everything around it. Because of this, there is popularity for these vehicles, since they give a great deal of advantages to individuals utilizing them. We use the Facebook AI Research software system that implements object detection algorithms, Caffe2 deep learning framework for advanced object detection by offering speedy training. We have also manipulated images to derive insights addressing the issues companies face when making the step from research to production. We have implemented detectron2 object detection for faster detection of objects. There is labeling of the object & we used manipulation of images using cartoonization.
</p>

<br>
<div align="center">
  <img src="https://github.com/avs-abhishek123/Detectron2/blob/236e72cd3edb57a6a0e41e5ec74f1fdae1730d67/detectron2_segmented_image.png"/>
</div>
<br>

---

## Introduction & Features

Detectron is Facebook AI Research's software system that implements state-of-the-art object detection algorithms, including [Mask R-CNN](https://arxiv.org/abs/1703.06870). It is written in Python and powered by the [Caffe2](https://github.com/caffe2/caffe2) deep learning framework.

At FAIR, Detectron has enabled numerous research projects, including: [Feature Pyramid Networks for Object Detection](https://arxiv.org/abs/1612.03144), [Mask R-CNN](https://arxiv.org/abs/1703.06870), [Detecting and Recognizing Human-Object Interactions](https://arxiv.org/abs/1704.07333), [Focal Loss for Dense Object Detection](https://arxiv.org/abs/1708.02002), [Non-local Neural Networks](https://arxiv.org/abs/1711.07971), [Learning to Segment Every Thing](https://arxiv.org/abs/1711.10370), [Data Distillation: Towards Omni-Supervised Learning](https://arxiv.org/abs/1712.04440), [DensePose: Dense Human Pose Estimation In The Wild](https://arxiv.org/abs/1802.00434), and [Group Normalization](https://arxiv.org/abs/1803.08494).


The goal of Detectron is to provide a high-quality, high-performance codebase for object detection *research*. It is designed to be flexible in order to support rapid implementation and evaluation of novel research. Detectron includes implementations of the following object detection algorithms:

- [Mask R-CNN](https://arxiv.org/abs/1703.06870) -- *Marr Prize at ICCV 2017*
- [RetinaNet](https://arxiv.org/abs/1708.02002) -- *Best Student Paper Award at ICCV 2017*
- [Faster R-CNN](https://arxiv.org/abs/1506.01497)
- [RPN](https://arxiv.org/abs/1506.01497)
- [Fast R-CNN](https://arxiv.org/abs/1504.08083)
- [R-FCN](https://arxiv.org/abs/1605.06409)

using the following backbone network architectures:

- [ResNeXt{50,101,152}](https://arxiv.org/abs/1611.05431)
- [ResNet{50,101,152}](https://arxiv.org/abs/1512.03385)
- [Feature Pyramid Networks](https://arxiv.org/abs/1612.03144) (with ResNet/ResNeXt)
- [VGG16](https://arxiv.org/abs/1409.1556)

Additional backbone architectures may be easily implemented. For more details about these models, please see [References](#references) below.

---

## Installation, Quick Start: Using Detectron, Model Zoo and Baselines & Update

Please find installation instructions for Caffe2 and Detectron in [`INSTALL.md`](INSTALL.md).
After installation, please see [`GETTING_STARTED.md`](GETTING_STARTED.md) for brief tutorials covering inference and training with Detectron.
Model Zoo and Baselines - We provide a large set of baseline results and trained models available for download in the [Detectron Model Zoo](MODEL_ZOO.md).
- 4/2018: Support Group Normalization - see [`GN/README.md`](./projects/GN/README.md)
**Detectron is deprecated. Please see [detectron2](https://github.com/facebookresearch/detectron2), a ground-up rewrite of Detectron in PyTorch.**

---

## License
![](https://github.com/avs-abhishek123/Detectron2/blob/236e72cd3edb57a6a0e41e5ec74f1fdae1730d67/detectron2_logo.png)

Detectron is released under the [Apache 2.0 license](https://github.com/facebookresearch/detectron/blob/master/LICENSE). 

## Reference for Detectron

If you use Detectron in your research or wish to refer to the baseline results published in the [Model Zoo](MODEL_ZOO.md), please use the following Detectron2 original  BibTeX entry.


```BibTeX
@misc{wu2019detectron2,
  author =       {Yuxin Wu and Alexander Kirillov and Francisco Massa and
                  Wan-Yen Lo and Ross Girshick},
  title =        {Detectron2},
  howpublished = {\url{https://github.com/facebookresearch/detectron2}},
  year =         {2019}
}
```

---

## To cite my paper: 
|Citing Text|
|---|
| Allena Venkata Sai Abhishek , Sonali Kotni, 2021, Detectron2 Object Detection & Manipulating Images using Cartoonization, INTERNATIONAL JOURNAL OF ENGINEERING RESEARCH & TECHNOLOGY (IJERT) Volume 10, Issue 08 (August 2021), |
