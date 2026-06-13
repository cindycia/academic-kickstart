---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Rethinking State Disentanglement in Causal Reinforcement Learning"
authors: ["Haiyao Cao", "Zhen Zhang", "Panpan Cai", "Yuhang Liu", "Jinan Zou", "Ehsan Abbasnejad", "Biwei Huang", "Mingming Gong", "Anton van den Hengel", "Javen Qinfeng Shi"]
date: 2024-08-24
publishDate: 2024-08-24T15:00:00+08:00

publication_types: ["3"]

abstract: "One of the significant challenges in reinforcement learning (RL) when dealing with noise is estimating latent states from observations. Causality provides rigorous theoretical support for ensuring that the underlying states can be uniquely recovered through identifiability. Consequently, some existing work focuses on establishing identifiability from a causal perspective to aid in the design of algorithms. However, these results are often derived from a purely causal viewpoint, which may overlook the specific RL context. We revisit this research line and find that incorporating RL-specific context can reduce unnecessary assumptions in previous identifiability analyses for latent states. More importantly, removing these assumptions allows algorithm design to go beyond the earlier boundaries constrained by them. Leveraging these insights, we propose a novel approach for general partially observable Markov Decision Processes (POMDPs) by replacing the complicated structural constraints in previous methods with two simple constraints for transition and reward preservation. With the two constraints, the proposed algorithm is guaranteed to disentangle state and noise that is faithful to the underlying dynamics. Empirical evidence from extensive benchmark control tasks demonstrates the superiority of our approach over existing counterparts in effectively disentangling state belief from noise."

publication: "*arXiv preprint*"
featured: false

url_pdf: https://arxiv.org/abs/2408.13498
url_code: https://github.com/Haiyao-Nero/causal-rl-rethinking

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
