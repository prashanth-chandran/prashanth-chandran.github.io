---
title: "Topologically Consistent Multi-view 3D Head Reconstruction via Coarse-Guided Layered Surface Sampling"
collection: publications
permalink: /publication/shells_2026
project_page: https://syntec-research.github.io/SHELLS/
paperurl: https://syntec-research.github.io/SHELLS/files/paper.pdf
teaser: /images/shells2026.jpg
excerpt: From calibrated multi-view images, SHELLS reconstructs 18k-vertex 3D heads in 0.08 seconds. It aggregates DinoV2 features via projective surface-aware feature sampling, allowing a transformer to predict dense semantic meshes 3.5x faster with 88% less GPU memory than state-of-the-art methods.
date: 2026-07-26
venue: 'SIGGRAPH'
bibtex: "
@inproceedings{Bolkart2026SHELLS,
  author    = {Bolkart, Timo and Wang, Daoye and Chandran, Prashanth},
  title     = {Topologically Consistent Multi-view 3D Head Reconstruction via Coarse-Guided Layered Surface Sampling},
  year      = {2026},
  publisher = {Association for Computing Machinery},
  keywords  = {Registration, 3D Head Reconstruction},
  series    = {SIGGRAPH Conference Papers '26}
}
"
---

**Abstract**
<p>
We present SHELLS (Semantic Head Estimation via Layered Local Sampling), an efficient feed-forward framework for 3D head reconstruction in dense semantic correspondence from multi-view images. State-of-the-art methods typically refine vertices independently using localized feature volumes. This couples memory-intensive feature sampling to the output mesh resolution, limiting scalability for dense topologies (&ge; 10k vertices) and producing noisy surfaces due to a lack of global context. In contrast, SHELLS decouples feature extraction from mesh resolution via a hierarchical sampling strategy. We extract multi-view features using a DinoV2 backbone with LoRA adaptation, projectively sample a sparse global feature cloud, and predict an intermediate coarse mesh. This coarse prior guides the construction of layered, surface-aware sampling shells that serve as a discrete search space for the final reconstruction. By utilizing a shared transformer architecture, SHELLS maintains global surface consistency while requiring only 12% of the GPU memory of volume-based approaches. Experimental results show that SHELLS reduces median registration error by 21% &ndash; 29% and achieves a 3.5&times; speedup, predicting 18k-vertex meshes in 0.08 seconds. Notably, our model is trained exclusively on synthetic data yet generalizes effectively to real-world captures, eliminating the need for the costly, pre-registered multi-view datasets common in prior work.
</p>
