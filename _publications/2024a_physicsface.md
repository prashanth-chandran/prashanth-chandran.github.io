---
title: "Learning a Generalized Physical Face Model From Data"
collection: publications
permalink: /publication/2024a_physicsface
project_page: https://studios.disneyresearch.com/2024/07/28/learning-a-generalized-physical-face-model-from-data/
teaser: /images/physface2024.png
excerpt: In this work, we aim to make physics-based facial animation more accessible by proposing a generalized physical face model that we learn from a large 3D face dataset. Once trained, our model can be quickly fit to any unseen identity and produce a ready-to-animate physical face model automatically.
date: 2024-07-28
venue: 'Siggraph'
bibtex: "
@article{Yang2024,
    author = {Yang, Lingchen and Zoss, Gaspard and Chandran, Prashanth and Gross, Markus and Solenthaler, Barbara and Sifakis, Eftychios and Bradley, Derek},
    title = {Learning a Generalized Physical Face Model From Data},
    year = {2024},
    issue_date = {July 2024},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    volume = {43},
    number = {4},
    issn = {0730-0301},
    doi = {10.1145/3658189},
    month = jul,
    articleno = {94},
    numpages = {14},
}
"
---

**Abstract**
<p>
Physically-based simulation is a powerful approach for 3D facial animation as the resulting deformations are governed by physical constraints, allowing to easily resolve self-collisions, respond to external forces and perform realistic anatomy edits. Today’s methods are data-driven, where the actuations for finite elements are inferred from captured skin geometry. Unfortunately, these approaches have not been widely adopted due to the complexity of initializing the material space and learning the deformation model for each character separately, which often requires a skilled artist followed by lengthy network training. In this work, we aim to make physics-based facial animation more accessible by proposing a generalized physical face model that we learn from a large 3D face dataset. Once trained, our model can be quickly fit to any unseen identity and produce a ready-to-animate physical face model automatically. Fitting is as easy as providing a single 3D face scan, or even a single face image. After fitting, we offer intuitive animation controls, as well as the ability to retarget animations across characters. All the while, the resulting animations allow for physical effects like collision avoidance, gravity, paralysis, bone reshaping and more.
</p>