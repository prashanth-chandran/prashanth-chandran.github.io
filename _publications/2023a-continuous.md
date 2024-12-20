---
title: "Continuous Landmark Detection With 3D Queries"
collection: publications
permalink: /publication/2023a-continuous
teaser: /images/cont2023.png
excerpt: We propose the first facial landmark detection network that can predict continuous, unlimited landmarks, allowing to specify the number and location of the desired landmarks at inference time. [[Project Page]](https://studios.disneyresearch.com/2023/06/04/continuous-landmark-detection-with-3d-queries/)<br><br>
date: 2023-06-04
venue: 'IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
bibtex: "
@InProceedings{Chandran_2023_CVPR,<br>
    author    = {Chandran, Prashanth and Zoss, Gaspard and Gotardo, Paulo and Bradley, Derek},<br>
    title     = {Continuous Landmark Detection With 3D Queries},<br>
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},<br>
    month     = {June},<br>
    year      = {2023},<br>
    pages     = {16858-16867}<br>
}
"
---

**Abstract**
<p>
Neural networks for facial landmark detection are notoriously limited to a fixed set of landmarks in a dedicated layout, which must be specified at training time. Dedicated datasets must also be hand-annotated with the corresponding landmark configuration for training. We propose the first facial landmark detection network that can predict continuous, unlimited landmarks, allowing to specify the number and location of the desired landmarks at inference time. Our method combines a simple image feature extractor with a queried landmark predictor, and the user can specify any continuous query points relative to a 3D template face mesh as input. As it is not tied to a fixed set of landmarks, our method is able to leverage all pre-existing 2D landmark datasets for training, even if they have inconsistent landmark configurations. As a result, we present a very powerful facial landmark detector that can be trained once, and can be used readily for numerous applications like 3D face reconstruction, arbitrary face segmentation, and is even compatible with helmeted mounted cameras, and therefore could vastly simplify face tracking workflows for media and entertainment applications.
</p>

[Project Page](https://studios.disneyresearch.com/2023/06/04/continuous-landmark-detection-with-3d-queries/)

**Bibtex:** 
<pre>
@InProceedings{Chandran_2023_CVPR,
    author    = {Chandran, Prashanth and Zoss, Gaspard and Gotardo, Paulo and Bradley, Derek},
    title     = {Continuous Landmark Detection With 3D Queries},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {16858-16867}
}
</pre>
{: .notice}