---
title: "Shape Transformers: Topology-Independent 3D Shape Models Using Transformers"
collection: publications
permalink: /publication/2022a-shapetransformers
teaser: /images/st2022.png
excerpt: We present a new nonlinear parametric 3D shape model based on transformer architectures.  [[Project Page]](https://studios.disneyresearch.com/2022/04/25/shape-transformers-topology-independent-3d-shape-models-using-transformers/)<br><br>
date: 2022-04-05
venue: 'Eurographics'
bibtex: "
@article{https://doi.org/10.1111/cgf.14468, <br>
author = {Chandran, Prashanth and Zoss, Gaspard and Gross, Markus and Gotardo, Paulo and Bradley, Derek},<br>
title = {Shape Transformers: Topology-Independent 3D Shape Models Using Transformers},
journal = {Computer Graphics Forum},<br>
volume = {41},<br>
number = {2},<br>
pages = {195-207},<br>
doi = {https://doi.org/10.1111/cgf.14468},<br>
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14468},<br>
year = {2022}<br>
}
"
---

**Abstract**
<p>
Parametric 3D shape models (e.g., for faces) are heavily utilized in computer graphics and vision applications to provide priors on the observed variability of an object’s geometry. Original models were linear and operated on the entire shape at once. They were later enhanced to provide localized control on different shape parts separately. In deep shape models, nonlinearity was introduced via a sequence of fully-connected layers and activation functions, and locality was introduced in recent models that use mesh convolution networks. As common limitations, these models often dictate, in one way or another, the allowed extent of spatial correlations and also require that a fixed mesh topology be specified ahead of time. To overcome these limitations, we present a new nonlinear parametric 3D shape model based on transformer architectures. A key benefit of this new model comes from using the transformer’s “self-attention” mechanism to automatically learn nonlinear spatial correlations for a class of 3D shapes. This is in contrast to global models that correlate everything and local models that dictate the correlation extent. Our transformer 3D shape autoencoder is a better alternative to mesh convolution models, which require specially- crafted convolution, and down/up-sampling operators that can be difficult to design. Additionally, our model is topologically independent: it can be trained once and then evaluated on any mesh topology, unlike previous methods. We demonstrate the application of our model to different datasets, including 3D faces, 3D hand shapes and full human bodies. Our experiments demonstrate the strong potential of our transformer-based 3D shape model in several applications in computer graphics and vision.
</p>

[Project Page](https://studios.disneyresearch.com/2022/04/25/shape-transformers-topology-independent-3d-shape-models-using-transformers/)

**Bibtex:** 
<pre>
@article{https://doi.org/10.1111/cgf.14468,
author = {Chandran, Prashanth and Zoss, Gaspard and Gross, Markus and Gotardo, Paulo and Bradley, Derek},
title = {Shape Transformers: Topology-Independent 3D Shape Models Using Transformers},
journal = {Computer Graphics Forum},
volume = {41},
number = {2},
pages = {195-207},
doi = {https://doi.org/10.1111/cgf.14468},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14468},
year = {2022}
}
</pre>
{: .notice}