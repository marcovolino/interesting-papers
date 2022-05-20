---
layout: paper
title: 'HVH: Learning a Hybrid Neural Volumetric Representation for Dynamic Hair Performance Capture'
authors: 'Ziyan Wang, Giljoo Nam, Tuur Stuyck, Stephen Lombardi, Michael Zollhoefer, Jessica Hodgins, Christoph Lassner'
venue: 'CVPR'
year: 2022
paper-url: 'https://arxiv.org/abs/2112.06904'
project-url: 'https://ziyanw1.github.io/hvh/'
topic: 'Hair'

---

## Abstract
Capturing and rendering life-like hair is particularly challenging due to its fine geometric structure, the complex physical interaction and its non-trivial visual appearance.Yet, hair is a critical component for believable avatars. In this paper, we address the aforementioned problems: 1) we use a novel, volumetric hair representation that is com-posed of thousands of primitives. Each primitive can be rendered efficiently, yet realistically, by building on the latest advances in neural rendering. 2) To have a reliable control signal, we present a novel way of tracking hair on the strand level. To keep the computational effort manageable, we use guide hairs and classic techniques to expand those into a dense hood of hair. 3) To better enforce temporal consistency and generalization ability of our model, we further optimize the 3D scene flow of our representation with multi-view optical flow, using volumetric ray marching. Our method can not only create realistic renders of recorded multi-view sequences, but also create renderings for new hair configurations by providing new control signals. We compare our method with existing work on viewpoint synthesis and drivable animation and achieve state-of-the-art results. Please check out our project website at this https URL.

