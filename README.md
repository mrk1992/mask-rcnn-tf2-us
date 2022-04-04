# Mask R-CNN for Object Detection and Segmentation using TensorFlow 2 (2.7.0)

## Introduction
The [mask-rcnn-tf2-us](https://github.com/mrk1992/mask-rcnn-tf2-us) project edits the original [Mask_RCNN](https://github.com/matterport/Mask_RCNN) project, which only supports TensorFlow 1.0, so that it works on TensorFlow 2 (Especially 2.7.0). Based on this new project, the [Mask R-CNN](https://arxiv.org/abs/1703.06870) can be trained and tested (i.e make predictions) in TensorFlow 2. The Mask R-CNN model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

Compared to the [Mask_RCNN](https://github.com/matterport/Mask_RCNN) and [Mask-RCNN-TF2](https://github.com/ahmedfgad/Mask-RCNN-TF2), this project edits the following 2 modules:

1. `model.py`
2. `utils.py`

This project is tested against **tensorflow-gpu 2.7.0**, **keras 2.7.0-tf**, and **python 3.8.12**. Note that the project will not run in TensorFlow 1.0.


## Environment for Linux
~~~
cuda==11.2
cudnn==8.2.0
tensorflow-gpu==2.7.0  
conda==4.12.0
~~~

## Reference
https://github.com/matterport/Mask_RCNN  
https://github.com/ahmedfgad/Mask-RCNN-TF2
