---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mimic Intent, Not Just Trajectories"
authors: ["Renming Huang", "Chendong Zeng", "Wenjing Tang", "Jintian Cai", "Cewu Lu", "Panpan Cai"]
date: 2026-02-01
publishDate: 2026-02-01T15:00:00+08:00

publication_types: ["1"]

abstract: "While imitation learning (IL) has achieved impressive success in dexterous manipulation through generative modeling and pretraining, state-of-the-art approaches like Vision-Language-Action (VLA) models still struggle with adaptation to environmental changes and skill transfer. We argue this stems from mimicking raw trajectories without understanding the underlying intent. To address this, we propose explicitly disentangling behavior intent from execution details in end-2-end IL: \"Mimic Intent, Not just Trajectories\" (MINT). We achieve this via multi-scale frequency-space tokenization, which enforces a spectral decomposition of action chunk representation. We learn action tokens with a multi-scale coarse-to-fine structure, and force the coarsest token to capture low-frequency global structure and finer tokens to encode high-frequency details. This yields an abstract Intent token that facilitates planning and transfer, and multi-scale Execution tokens that enable precise adaptation to environmental dynamics. Building on this hierarchy, our policy generates trajectories through next-scale autoregression, performing progressive intent-to-execution reasoning, thus boosting learning efficiency and generalization. Crucially, this disentanglement enables one-shot transfer of skills, by simply injecting the Intent token from a demonstration into the autoregressive generation process. Experiments on several manipulation benchmarks and on a real robot demonstrate state-of-the-art success rates, superior inference efficiency, robust generalization against disturbances, and effective one-shot transfer."

publication: "*Robotics: Science and Systems (RSS)*"
featured: true

url_pdf: https://arxiv.org/abs/2602.08602
url_project: https://renming-huang.github.io/MINT

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
