---
title: "HyP-DESPOT: A hybrid parallel algorithm for online planning under uncertainty"
date: 2018-06-01
publishDate: 2019-11-07T11:46:20.935469Z
authors: ["Panpan Cai", "Yuanfu Luo", "David Hsu", "Wee Sun Lee"]
publication_types: ["1"]
abstract: "Planning under uncertainty is critical for robust
robot performance in uncertain, dynamic environments, but it
incurs high computational cost. State-of-the-art online search
algorithms, such as DESPOT, have vastly improved the computational efficiency of planning under uncertainty and made
it a valuable tool for robotics in practice. This work takes one
step further by leveraging both CPU and GPU parallelization
in order to achieve near real-time online planning performance
for complex tasks with large state, action, and observation
spaces. Specifically, we propose Hybrid Parallel DESPOT (HyPDESPOT), a massively parallel online planning algorithm that
integrates CPU and GPU parallelism in a multi-level scheme.
It performs parallel DESPOT tree search by simultaneously
traversing multiple independent paths using multi-core CPUs and
performs parallel Monte-Carlo simulations at the leaf nodes of
the search tree using GPUs. Experimental results show that HyPDESPOT speeds up online planning by up to several hundred
times, compared with the original DESPOT algorithm, in several
challenging robotic tasks in simulation."
featured: true 
publication: "*Robotics: Science & Systems*"
url_pdf: https://arxiv.org/pdf/1802.06215.pdf
url_code: https://github.com/AdaCompNUS/HyP-DESPOT

image:                                                                           
  caption: ""                                                  
  focal_point: "Center"                                                               
  preview_only: false 
---

