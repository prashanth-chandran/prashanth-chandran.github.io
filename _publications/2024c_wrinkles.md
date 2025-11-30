---
title: "Stylize My Wrinkles: Bridging the Gap from Simulation to Reality"
collection: publications
permalink: /publication/2024c_wrinkles
teaser: /images/style2024.png
excerpt: In this work we aim to overcome the gap between synthetic simulation and real skin scanning, by proposing a method that can be applied to large skin regions (e.g. an entire face) with the controllability of simulation and the organic look of real micro details. [[Project Page]](https://studios.disneyresearch.com/2024/06/07/stylize-my-wrinkles-bridging-the-gap-from-simulation-to-reality/)<br><br>
date: 2024-04-20
venue: 'Eurographics'
bibtex: "
@article{Weiss2024B,
    author = {Weiss, S. and Stanhope, J. and Chandran, P. and Zoss, G. and Bradley, D.},
    title = {Stylize My Wrinkles: Bridging the Gap from Simulation to Reality},
    journal = {Computer Graphics Forum},
    volume = {43},
    number = {2},
    pages = {e15048},
    doi = {https://doi.org/10.1111/cgf.15048},
    year = {2024}
}
"
---

**Abstract**
<p>
Modeling realistic human skin with pores and wrinkles down to the milli- and micrometer resolution is a challenging task. Prior work showed that such micro geometry can be efficiently generated through simulation methods, or in specialized cases via 3D scanning of real skin. Simulation methods allow to highly customize the wrinkles on the face, but can lead to a synthetic look. Scanning methods can lead to a more organic look for the micro details, however these methods are only applicable to small skin patches due to the required image resolution. In this work we aim to overcome the gap between synthetic simulation and real skin scanning, by proposing a method that can be applied to large skin regions (e.g. an entire face) with the controllability of simulation and the organic look of real micro details. Our method is based on style transfer at its core, where we use scanned displacement maps of real skin patches as style images and displacement maps from an artist-friendly simulation method as content images. We build a library of displacement maps as style images by employing a simplified scanning setup that can capture high-resolution patches of real skin. To create the content component for the style transfer and to facilitate parameter-tuning for the simulation, we design a library of preset parameter values depicting different skin types, and present a new method to fit the simulation parameters to scanned skin patches. This allows fully-automatic parameter generation, interpolation and stylization across entire faces. We evaluate our method by generating realistic skin micro details for various subjects of different ages and genders, and demonstrate that our approach achieves a more organic and natural look than simulation alone.
</p>

[Project Page](https://studios.disneyresearch.com/2024/06/07/stylize-my-wrinkles-bridging-the-gap-from-simulation-to-reality/)
