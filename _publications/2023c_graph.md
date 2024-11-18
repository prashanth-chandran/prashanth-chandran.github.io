---
title: Graph-Based Synthesis for Skin Micro Wrinkles
collection: publications
permalink: /publication/2023c_graph
teaser: /images/graph2023.png
excerpt: We present a novel graph-based simulation approach for generating micro wrinkle geometry on human skin, which can easily scale up to the micro-meter range and millions of wrinkles. [[Project Page]](https://studios.disneyresearch.com/2023/07/03/graph-based-synthesis-for-skin-micro-wrinkles/)<br><br>
date: 2023-07-03
venue: 'Eurographics Symposium on Geometry Processing'
bibtex: "
@article{Weiss2023,<br>
author = {Weiss, Sebastian and Moulin, Jonathan and Chandran, Prashanth and Zoss, Gaspard and Gotardo, Paulo and Bradley, Derek},<br>
title = {Graph-Based Synthesis for Skin Micro Wrinkles},<br>
journal={Computer Graphics Forum (Symposium on Geometry Processing)},<br>
year = {2023},<br>
month = {6},<br>
}<br>
"
---

**Abstract**
<p>
We present a novel graph-based simulation approach for generating micro wrinkle geometry on human skin, which can easily scale up to the micro-meter range and millions of wrinkles. The simulation first samples pores on the skin and treats them as nodes in a graph. These nodes are then connected and the resulting edges become candidate wrinkles. An iterative optimization inspired by pedestrian trail formation is then used to assign weights to those edges, i.e., to carve out the wrinkles. Finally, we convert the graph to a detailed skin displacement map using novel shape functions implemented in graphics shaders. Our simulation and displacement map creation steps expose fine controls over the appearance at real-time framerates suitable for interactive exploration and design. We demonstrate the effectiveness of the generated wrinkles by enhancing state-of-art 3D reconstructions of real human subjects with simulated micro wrinkles, and furthermore propose an artist-driven design flow for adding micro wrinkles to fictional characters.
</p>

[Project Page](https://studios.disneyresearch.com/2023/07/03/graph-based-synthesis-for-skin-micro-wrinkles/)

**Bibtex:** 
<pre>
@article{Weiss2023,
author = {Weiss, Sebastian and Moulin, Jonathan and Chandran, Prashanth and Zoss, Gaspard and Gotardo, Paulo and Bradley, Derek},
title = {Graph-Based Synthesis for Skin Micro Wrinkles},
journal={Computer Graphics Forum (Symposium on Geometry Processing)},
year = {2023},
month = {6},
}
</pre>
{: .notice}