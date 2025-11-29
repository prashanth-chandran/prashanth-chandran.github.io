---
title: "ScaffoldAvatar: High-Fidelity Gaussian Avatars with Patch Expressions"
collection: publications
permalink: /publication/scaffold_2025
teaser: /images/scaffold_25.png
excerpt: In this work, we propose to couple locally-defined facial expressions with 3D Gaussian splatting to enable creating ultra-high fidelity, expressive and photorealistic head avatars. [[Project Page]](https://studios.disneyresearch.com/2025/07/09/scaffoldavatar-high-fidelity-gaussian-avatars-with-patch-expressions/)<br><br><br>
date: 2025-07-10
venue: 'SIGGRAPH'
bibtex: "
@inproceedings{Shivangi2025Scaffold,<br>
author = {Aneja, Shivangi and Weiss, Sebastian and Baeza, Irene and Chandran, Prashanth and Zoss, Gaspard and Niessner, Matthias and Bradley, Derek},<br>
title = {ScaffoldAvatar: High-Fidelity Gaussian Avatars with Patch Expressions},<br>
year = {2025},<br>
isbn = {9798400715402},<br>
publisher = {Association for Computing Machinery},<br>
address = {New York, NY, USA},<br>
url = {https://doi.org/10.1145/3721238.3730729},<br>
doi = {10.1145/3721238.3730729},<br>
booktitle = {Proceedings of the Special Interest Group on Computer Graphics and Interactive Techniques Conference Conference Papers},<br>
articleno = {90},<br>
numpages = {11},<br>
keywords = {Photorealistic 3D avatars, 3D Gaussian Splatting, 3D Face Modelling},<br>
series = {SIGGRAPH Conference Papers '25}<br>
}<br>
"
---

**Abstract**
<p>
Generating high-fidelity real-time animated sequences of photorealistic 3D head avatars is important for many graphics applications, including immersive telepresence and movies. This is a challenging problem particularly when rendering digital avatar close-ups for showing character’s facial microfeatures and expressions. To capture the expressive, detailed nature of human heads, including skin furrowing and finer-scale facial movements, we propose to couple locally-defined facial expressions with 3D Gaussian splatting to enable creating ultra-high fidelity, expressive and photorealistic head avatars. In contrast to previous works that operate on a global expression space, we condition our avatar’s dynamics on patch-based local expression features and synthesize 3D Gaussians at a patch level. In particular, we leverage a patch-based geometric 3D face model to extract patch expressions and learn how to translate these into local dynamic skin appearance and motion by coupling the patches with anchor points of Scaffold-GS, a recent hierarchical scene representation. These anchors are then used to synthesize 3D Gaussians on-the-fly, conditioned by patch-expressions and viewing direction. We employ color-based densification and progressive training to obtain high-quality results and faster convergence for high resolution 3K training images. By leveraging patch-level expressions, ScaffoldAvatar consistently achieves state-of-the-art performance with visually natural motion, while encompassing diverse facial expressions and styles in real time.
</p>

[Project Page](https://studios.disneyresearch.com/2025/07/09/scaffoldavatar-high-fidelity-gaussian-avatars-with-patch-expressions/)

**Bibtex:** 
<pre>
@inproceedings{Shivangi2025Scaffold,
author = {Aneja, Shivangi and Weiss, Sebastian and Baeza, Irene and Chandran, Prashanth and Zoss, Gaspard and Niessner, Matthias and Bradley, Derek},
title = {ScaffoldAvatar: High-Fidelity Gaussian Avatars with Patch Expressions},
year = {2025},
isbn = {9798400715402},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3721238.3730729},
doi = {10.1145/3721238.3730729},
booktitle = {Proceedings of the Special Interest Group on Computer Graphics and Interactive Techniques Conference Conference Papers},
articleno = {90},
numpages = {11},
keywords = {Photorealistic 3D avatars, 3D Gaussian Splatting, 3D Face Modelling},
series = {SIGGRAPH Conference Papers '25}
}
</pre>
{: .notice}