---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "UniDomain: Pretraining a Unified PDDL Domain from Real-World Demonstrations for Generalizable Robot Task Planning"
authors: ["Haoming Ye", "Yunxiao Xiao", "Cewu Lu", "Panpan Cai"]
date: 2025-12-01
publishDate: 2025-07-29T15:00:00+08:00

publication_types: ["1"]

abstract: "Robotic task planning in real-world environments requires reasoning over implicit constraints from language and vision. While LLMs and VLMs offer strong priors, they struggle with long-horizon structure and symbolic grounding. Existing methods that combine LLMs with symbolic planning often rely on handcrafted or narrow domains, limiting generalization. We propose UniDomain, a framework that pre-trains a PDDL domain from robot manipulation demonstrations and applies it to online robotic task planning. It extracts atomic domains from 12,393 manipulation videos to form a unified domain with 3,137 operators, 2,875 predicates, and 16,481 causal edges. Given a target class of tasks, it retrieves relevant atomics from the unified domain and systematically fuses them into high-quality meta-domains to support compositional generalization in planning. Experiments on diverse real-world tasks show that UniDomain solves complex, unseen tasks in a zero-shot manner, achieving up to 58% higher task success and 160% improvement in plan optimality over state-of-the-art LLM and LLM-PDDL baselines."

publication: "*Advances in Neural Information Processing Systems (NeurIPS)*"
featured: true

url_pdf: https://arxiv.org/abs/2507.21545
url_project: https://roboticsjtu.github.io/UniDomain/

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
