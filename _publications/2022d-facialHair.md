---
title: "Facial Hair Tracking for High Fidelity Performance Capture"
collection: publications
permalink: /publication/2022d-facialHair
teaser: /images/hair2022.png
excerpt: We demonstrate the proposed capture pipeline on a variety of different facial hair styles and lengths, ranging from sparse and short to dense full-beards. [[Project Page]](https://studios.disneyresearch.com/2022/07/24/facial-hair-tracking-for-high-fidelity-performance-capture/)<br><br><br>
date: 2022-07-24
venue: 'Siggraph'
bibtex: "
@article{10.1145/3528223.3530116,<br>
author = {Winberg, Sebastian and Zoss, Gaspard and Chandran, Prashanth and Gotardo, Paulo and Bradley, Derek},<br>
title = {Facial Hair Tracking for High Fidelity Performance Capture},<br>
year = {2022},<br>
issue_date = {July 2022},<br>
publisher = {Association for Computing Machinery},<br>
address = {New York, NY, USA},<br>
volume = {41},<br>
number = {4},<br>
issn = {0730-0301},<br>
url = {https://doi.org/10.1145/3528223.3530116},<br>
doi = {10.1145/3528223.3530116},<br>
journal = {ACM Trans. Graph.},<br>
month = {jul},<br>
articleno = {165},<br>
numpages = {12},<br>
keywords = {hair tracking, facial hair capture, performance capture}<br>
}
"
---

**Abstract**
<p>
Facial hair is a largely overlooked topic in facial performance capture. Most production pipelines in the entertainment industry do not have a way to automatically capture facial hair or track the skin underneath it. Thus, actors are asked to shave clean before face capture, which is very often undesirable. Capturing the geometry of individual facial hairs is very challenging, and their presence makes it harder to capture the deforming shape of the underlying skin surface. Some attempts have already been made at automating this task, but only for static faces with relatively sparse 3D hair reconstructions. In particular, current methods lack the temporal correspondence needed when capturing a sequence of video frames depicting facial performance. The problem of robustly tracking the skin underneath also remains unaddressed. In this paper, we propose the first multiview reconstruction pipeline that tracks both the dense 3D facial hair, as well as the underlying 3D skin for entire performances. Our method operates with standard setups for face photogrammetry, without requiring dense camera arrays. For a given capture subject, our algorithm first reconstructs a dense, high-quality neutral 3D facial hairstyle by registering sparser hair reconstructions over multiple frames that depict a neutral face under quasi-rigid motion. This custom-built, reference facial hairstyle is then tracked throughout a variety of changing facial expressions in a captured performance, and the result is used to constrain the tracking of the 3D skin surface underneath. We demonstrate the proposed capture pipeline on a variety of different facial hairstyles and lengths, ranging from sparse and short to dense full-beards.
</p>

[Project Page](https://studios.disneyresearch.com/2022/07/24/facial-hair-tracking-for-high-fidelity-performance-capture/)

**Bibtex:** 
<pre>
@article{10.1145/3528223.3530116,
author = {Winberg, Sebastian and Zoss, Gaspard and Chandran, Prashanth and Gotardo, Paulo and Bradley, Derek},
title = {Facial Hair Tracking for High Fidelity Performance Capture},
year = {2022},
issue_date = {July 2022},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {41},
number = {4},
issn = {0730-0301},
url = {https://doi.org/10.1145/3528223.3530116},
doi = {10.1145/3528223.3530116},
journal = {ACM Trans. Graph.},
month = {jul},
articleno = {165},
numpages = {12},
keywords = {hair tracking, facial hair capture, performance capture}
}
</pre>
{: .notice}