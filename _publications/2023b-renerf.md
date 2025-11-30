---
title: "ReNeRF: Relightable Neural Radiance Fields with Nearfield Lighting"
collection: publications
permalink: /publication/2023b-renerf
project_page: https://studios.disneyresearch.com/2023/10/02/renerf-relightable-neural-radiance-fields-with-nearfield-lighting/
teaser: /images/renerf2023.png
excerpt: In this paper, we target the application scenario of capturing high-fidelity assets for neural relighting in controlled studio conditions, but without requiring a dense light stage. Instead, we leverage a small number of area lights commonly used in photogrammetry.
date: 2023-10-02
venue: 'International Conference on Computer Vision (ICCV)'
bibtex: "
@InProceedings{Xu_2023_ICCV,
    author    = {Xu, Yingyan and Zoss, Gaspard and Chandran, Prashanth and Gross, Markus and Bradley, Derek and Gotardo, Paulo},
    title     = {ReNeRF: Relightable Neural Radiance Fields with Nearfield Lighting},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023},
    pages     = {22581-22591}
}
"
---

**Abstract**
<p>
Recent work on radiance fields and volumetric inverse rendering (e.g., NeRFs) has provided excellent results in building data-driven models of real scenes for novel view synthesis with high photorealism. While full control over viewpoint is achieved, scene lighting is typically "baked" into the model and cannot be changed; other methods only capture limited variation in lighting or make restrictive assumptions about the captured scene. These limitations prevent the application on arbitrary materials and novel 3D environments with complex, distinct lighting. In this paper, we target the application scenario of capturing high-fidelity assets for neural relighting in controlled studio conditions, but without requiring a dense light stage. Instead, we leverage a small number of area lights commonly used in photogrammetry. We propose ReNeRF, a relightable radiance field model based on the intuitive and powerful approach of image-based relighting, which implicitly captures global light transport (for arbitrary objects) without complex, error-prone simulations. Thus, our new method is simple and provides full control over viewpoint and lighting, without simplistic assumptions about how light interacts with the scene. In addition, ReNeRF does not rely on the usual assumption of distant lighting - during training, we explicitly account for the distance between 3D points in the volume and point samples on the light sources. Thus, at test time, we achieve better generalization to novel, continuous lighting directions, including nearfield lighting effects.
</p>