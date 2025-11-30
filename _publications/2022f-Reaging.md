---
title: "Production-Ready Face Re-Aging for Visual Effects"
collection: publications
permalink: /publication/2022f-Reaging
project_page: https://studios.disneyresearch.com/2022/11/30/production-ready-face-re-aging-for-visual-effects/
teaser: /images/fran2022.png
excerpt: We demonstrate how the simple U-Net, surprisingly, allows us to advance the state of the art for re-aging real faces on video, with unprecedented temporal stability and preservation of facial identity across variable expressions, viewpoints, and lighting conditions.
date: 2022-11-30
venue: 'Siggraph Asia'
bibtex: "
@article{Zoss_2022, 
author = {Zoss, Gaspard and Chandran, Prashanth and Sifakis, Eftychios  and Gross, Markus and Gotardo, Paulo and Bradley, Derek}, 
title = {Production-Ready Face Re-Aging for Visual Effects}, 
year = {2022}, 
issue_date = {December 2022}, 
publisher = {Association for Computing Machinery}, 
address = {New York, NY, USA}, 
volume = {41}, 
number = {6}, 
issn = {0730-0301}, 
doi = {10.1145/3550454.3555520}, 
journal = {ACM Trans. Graph.}, 
month = {nov}, 
articleno = {237}, 
numpages = {12}, 
keywords = {facial re-aging, image and video editing} 
}
"
---

**Abstract**
<p>
Photorealistic digital re-aging of faces in video is becoming increasingly common in entertainment and advertising. But the predominant 2D painting workflow often requires frame-by-frame manual work that can take days to accomplish, even by skilled artists. Although research on facial image re-aging has attempted to automate and solve this problem, current techniques are of little practical use as they typically suffer from facial identity loss, poor resolution, and unstable results across subsequent video frames. In this paper, we present the first practical, fully-automatic and production-ready method for re-aging faces in video images. Our first key insight is in addressing the problem of collecting longitudinal training data for learning to re-age faces over extended periods of time, a task that is nearly impossible to accomplish for a large number of real people. We show how such a longitudinal dataset can be constructed by leveraging the current state-of-the-art in facial re-aging that, although failing on real images, does provide photoreal re-aging results on synthetic faces. Our second key insight is then to leverage such synthetic data and formulate facial re-aging as a practical image-to-image translation task that can be performed by training a well-understood U-Net architecture, without the need for more complex network designs. We demonstrate how the simple U-Net, surprisingly, allows us to advance the state of the art for re-aging real faces on video, with unprecedented temporal stability and preservation of facial identity across variable expressions, viewpoints, and lighting conditions. Finally, our new face re-aging network (FRAN) incorporates simple and intuitive mechanisms that provides artists with localized control and creative freedom to direct and fine-tune the re-aging effect, a feature that is largely important in real production pipelines and often overlooked in related research work.
</p>