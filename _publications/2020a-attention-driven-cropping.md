---
title: "Attention-Driven Cropping for Very High Resolution Facial Landmark Detection"
collection: publications
permalink: /publication/2020a-attention-driven-cropping
project_page: https://studios.disneyresearch.com/2020/06/16/attention-driven-cropping-for-very-high-resolution-facial-landmark-detection/
teaser: /images/adc2020.png
excerpt: Facial landmark detection is a fundamental task for many consumer and high-end applications and is almost entirely solved by machine learning methods today.
date: 2020-06-16
venue: 'IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
bibtex: "
@InProceedings{Chandran_2020_CVPR,
author = {Chandran, Prashanth and Bradley, Derek and Gross, Markus and Beeler, Thabo}, 
title = {Attention-Driven Cropping for Very High Resolution Facial Landmark Detection}, 
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}
"
---

**Abstract**
<p>
Facial landmark detection is a fundamental task for many consumer and high-end applications. Today, landmark detection is almost entirely solved by machine learning methods that are trained on a dataset of hand annotated images. Existing datasets are primarily made up of only low resolution images, and current algorithms are limited to inputs of comparable quality and resolution as the training dataset. On the other hand, high resolution imagery is becoming increasingly more common as consumer cameras improve in quality every year. Therefore, there is need for algorithms that can leverage the rich information available in high resolution imagery. Naively attempting to reuse existing network architectures on high resolution imagery is prohibitive due to memory bottlenecks on GPUs. The only current solution is to downsample the images, sacrificing resolution and quality. Building on top of recent progress in attention-based networks, we present a novel, fully convolutional regional architecture that is specially designed for predicting landmarks on very high resolution facial images without downsampling. We demonstrate the flexibility of our architecture by training the proposed model with images of resolutions ranging from 256 x 256 to 4K. In addition to being the first method for facial landmark detection on high resolution images, our approach achieves superior performance over traditional (holistic) state-of-the-art architectures across ALL resolutions, leading to a general-purpose, extremely flexible, high quality landmark detector.
</p>