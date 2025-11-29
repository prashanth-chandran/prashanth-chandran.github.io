---
title: "Fast Dynamic Facial Wrinkles"
collection: publications
permalink: /publication/2024f_fastwrinkles
teaser: /images/fwrinkles2024.png
excerpt: We present a new method to animate the dynamic motion of skin micro wrinkles under facial expression deformation. [[Project Page]](https://studios.disneyresearch.com/2024/04/26/fast-dynamic-facial-wrinkles/)<br><br><br>
date: 2024-04-20
venue: 'Eurographics'
bibtex: "
@inproceedings{Weiss2024B,<br>
    booktitle = {Eurographics 2024 - Short Papers},<br>
    editor = {Hu, Ruizhen and Charalambous, Panayiotis},<br>
    title = {Fast Dynamic Facial Wrinkles},<br>
    author = {Weiss, Sebastian and Chandran, Prashanth and Zoss, Gaspard and Bradley, Derek},<br>
    year = {2024},<br>
    publisher = {The Eurographics Association},<br>
    ISSN = {1017-4656},<br>
    ISBN = {978-3-03868-237-0},<br>
    DOI = {10.2312/egs.20241016}<br>
}<br>
"
---

**Abstract**
<p>
We present a new method to animate the dynamic motion of skin micro wrinkles under facial expression deformation. Since wrinkles are formed as a reservoir of skin for stretching, our model only deforms wrinkles that are perpendicular to the stress axis. Specifically, those wrinkles become wider and shallower when stretched, and deeper and narrower when compressed. In contrast to previous methods that attempted to modify the neutral wrinkle displacement map, our approach is to modify the way wrinkles are constructed in the displacement map. To this end, we build upon a previous synthetic wrinkle generator that allows us to control the width and depth of individual wrinkles when generated on a per-frame basis. Furthermore, since constructing a displacement map per frame of animation is costly, we present a fast approximation approach using pre-computed displacement maps of wrinkles binned by stretch direction, which can be blended interactively in a shader. We compare both our high-quality and fast methods with previous techniques for wrinkle animation and demonstrate that our work retains more realistic details.
</p>

[Project Page](https://studios.disneyresearch.com/2024/04/26/fast-dynamic-facial-wrinkles/)

**Bibtex:** 
<pre>
@inproceedings{Weiss2024B,
    booktitle = {Eurographics 2024 - Short Papers},
    editor = {Hu, Ruizhen and Charalambous, Panayiotis},
    title = {{Fast Dynamic Facial Wrinkles}},
    author = {Weiss, Sebastian and Chandran, Prashanth and Zoss, Gaspard and Bradley, Derek},
    year = {2024},
    publisher = {The Eurographics Association},
    ISSN = {1017-4656},
    ISBN = {978-3-03868-237-0},
    DOI = {10.2312/egs.20241016}
}
</pre>
{: .notice}