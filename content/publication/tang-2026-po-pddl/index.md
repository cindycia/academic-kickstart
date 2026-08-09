---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PO-PDDL: Learning Symbolic POMDPs from Visual Demonstrations for Robot Planning Under Uncertainty"
authors: ["Wenjing Tang", "Xuanjin Jin", "Yuan Liu", "Renming Huang", "Cewu Lu", "Panpan Cai"]
date: 2026-06-14
publishDate: 2026-06-14T15:00:00+08:00

publication_types: ["3"]

abstract: "Real-world robot task planning must operate under both stochastic action execution and partial observability, yet constructing Partially Observable Markov Decision Process (POMDP) models for real robotics domains remains difficult and labor-intensive. We introduce PO-PDDL, a symbolic formulation of POMDPs that preserves the relational structure and LLM-friendly syntax of the Planning Domain Definition Language (PDDL), while explicitly modeling partial observability, stochasticity, and beliefs. Building on this formulation, we propose a demonstration-driven pipeline for learning PO-PDDL models. The proposed method reconstructs latent symbolic state trajectories from real-robot execution videos, identifies partial observability via inconsistencies between inferred states and visual observations, and learns stochastic transition and observation models accordingly. The resulting PO-PDDL domains are reusable across tasks and enable online belief-space planning under both perception and execution uncertainty. Experiments on real-world long-horizon manipulation tasks show that our method consistently outperforms existing PDDL and POMDP model-learning approaches, achieving robust task planning under uncertainty with significantly lower planning cost."

publication: "*arXiv preprint*"
featured: true

url_pdf: https://arxiv.org/abs/2606.15654
url_project: https://po-pddl.github.io/

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
