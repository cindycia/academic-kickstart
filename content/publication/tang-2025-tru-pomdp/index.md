---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tru-POMDP: Task Planning Under Uncertainty via Tree of Hypotheses and Open-Ended POMDPs"
authors: ["Wenjing Tang", "Xinyu He", "Yongxi Huang", "Yunxiao Xiao", "Cewu Lu", "Panpan Cai"]
date: 2025-12-01
publishDate: 2025-09-26T15:00:00+08:00

publication_types: ["1"]

abstract: "Task planning under uncertainty is essential for home-service robots operating in the real world. Tasks involve ambiguous human instructions, hidden or unknown object locations, and open-vocabulary object types, leading to significant open-ended uncertainty and a boundlessly large planning space. To address these challenges, we propose Tru-POMDP, a planner that combines structured belief generation using Large Language Models (LLMs) with principled POMDP planning. Tru-POMDP introduces a hierarchical Tree of Hypotheses (TOH), which systematically queries an LLM to construct high-quality particle beliefs over possible world states and human goals. We further formulate an open-ended POMDP model that enables rigorous Bayesian belief tracking and efficient belief-space planning over these LLM-generated hypotheses. Experiments on complex object rearrangement tasks across diverse kitchen environments show that Tru-POMDP significantly outperforms state-of-the-art LLM-based and LLM-tree-search hybrid planners, achieving higher success rates with significantly better plans, stronger robustness to ambiguity and occlusion, and greater planning efficiency."

publication: "*Advances in Neural Information Processing Systems (NeurIPS)*"
featured: true

url_pdf: https://arxiv.org/abs/2506.02860
url_project: https://tru-pomdp.github.io

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
