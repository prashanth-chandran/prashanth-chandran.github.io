---
title: A Perceptual Shape Loss for Monocular 3D Face Reconstruction
collection: publications
permalink: /publication/2023d_percep
teaser: /images/percep2023.png
excerpt: In this work, we propose a new loss function for monocular face capture, inspired by how humans would perceive the quality of a 3D face reconstruction given a particular image. It is widely known that shading provides a strong indicator for 3D shape in the human visual system. [[Project Page]](https://studios.disneyresearch.com/2023/10/09/a-perceptual-shape-loss-for-monocular-3d-face-reconstruction/)
date: 2023-10-09
venue: 'Pacific Graphics'
bibtex: "
@article{Otto2023,<br>
    journal = {Computer Graphics Forum},<br>
    title = {A Perceptual Shape Loss for Monocular 3D Face Reconstruction},<br>
    author = {Otto, Christopher and Chandran, Prashanth and Zoss, Gaspard and Gross, Markus and Gotardo, Paulo and Bradley, Derek},<br>
    year = {2023},<br>
    publisher = {The Eurographics Association and John Wiley & Sons Ltd.},<br>
    ISSN = {1467-8659},<br>
    DOI = {10.1111/cgf.14945}<br>
}<br>
"
---

**Abstract**
<p>
Monocular 3D face reconstruction is a wide-spread topic, and existing approaches tackle the problem either through fast neural network inference or offline iterative reconstruction of face geometry. In either case carefully-designed energy functions are minimized, commonly including loss terms like a photometric loss, a landmark reprojection loss, and others. In this work we propose a new loss function for monocular face capture, inspired by how humans would perceive the quality of a 3D face reconstruction given a particular image. It is widely known that shading provides a strong indicator for 3D shape in the human visual system. As such, our new ‘perceptual’ shape loss aims to judge the quality of a 3D face estimate using only shading cues. Our loss is implemented as a discriminator-style neural network that takes an input face image and a shaded render of the geometry estimate, and then predicts a score that perceptually evaluates how well the shaded render matches the given image. This ‘critic’ network operates on the RGB image and geometry render alone, without requiring an estimate of the albedo or illumination in the scene. Furthermore, our loss operates entirely in image space and is thus agnostic to mesh topology. We show how our new perceptual shape loss can be combined with traditional energy terms for monocular 3D face optimization and deep neural network regression, improving upon current state-of-the-art results.
</p>

[Project Page](https://studios.disneyresearch.com/2023/10/09/a-perceptual-shape-loss-for-monocular-3d-face-reconstruction/)

**Bibtex:** 
<pre>
@article{Otto2023,
    journal = {Computer Graphics Forum},
    title = {A Perceptual Shape Loss for Monocular 3D Face Reconstruction},
    author = {Otto, Christopher and Chandran, Prashanth and Zoss, Gaspard and Gross, Markus and Gotardo, Paulo and Bradley, Derek},
    year = {2023},
    publisher = {The Eurographics Association and John Wiley & Sons Ltd.},
    ISSN = {1467-8659},
    DOI = {10.1111/cgf.14945}
}
</pre>
{: .notice}