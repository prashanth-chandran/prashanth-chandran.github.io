---
title: "Learning Dynamic 3D Geometry and Texture for Video Face Swapping"
collection: publications
permalink: /publication/2022h-swap3D
project_page: https://studios.disneyresearch.com/2022/10/05/learning-dynamic-3d-geometry-and-texture-for-video-face-swapping/
teaser: /images/swap2022.png
excerpt: We approach the problem of face swapping from the perspective of learning simultaneous convolutional facial autoencoders for the source and target identities, using a shared encoder network with identity-specific decoders.
date: 2022-10-05
venue: 'Pacific Graphics'
bibtex: "
@article {Ott22a, 
journal = {Computer Graphics Forum}, 
title = {Learning Dynamic 3D Geometry and Texture for Video Face Swapping}, 
author = {Otto, Christopher and Naruniec, Jacek and Helminger, 
Leonhard and Etterlin, Thomas and Mignone, Graziana and 
 Chandran, Prashanth and Zoss, Gaspard and Schroers, Christopher 
 and Gross, Markus and Gotardo, Paulo and Bradley, Derek and Weber, Romann},
year = {2022},
pages={611-622},
month={Oct},
number={7},
volume={41},
publisher = {The Eurographics Association and John Wiley & Sons Ltd.},
ISSN = {1467-8659},
DOI = {10.1111/cgf.14705}
}
"
---

**Abstract**
<p>
Face swapping is the process of applying a source actor’s appearance to a target actor’s performance in a video. This is a challenging visual effect that has seen increasing demand in film and television production. Recent work has shown that data-driven methods based on deep learning can produce compelling effects at production quality in a fraction of the time required for a traditional 3D pipeline. However, the dominant approach operates only on 2D imagery without reference to the underlying facial geometry or texture, resulting in poor generalization under novel viewpoints and little artistic control. Methods that do incorporate geometry rely on pre-learned facial priors that do not adapt well to particular geometric features of the source and target faces. We approach the problem of face swapping from the perspective of learning simultaneous convolutional facial autoencoders for the source and target identities, using a shared encoder network with identity-specific decoders. The key novelty in our approach is that each decoder first lifts the latent code into a 3D representation, comprising a dynamic face texture and a deformable 3D face shape, before projecting this 3D face back onto the input image using a differentiable renderer. The coupled autoencoders are trained only on videos of the source and target identities, without requiring 3D supervision. By leveraging the learned 3D geometry and texture, our method achieves face swapping with higher quality than when using off-the-shelf monocular 3D face reconstruction, and overall lower FID score than state-of-the-art 2D methods. Furthermore, our 3D representation allows for efficient artistic control over the result, which can be hard to achieve with existing 2D approaches.
</p>