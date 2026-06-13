---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Any House Any Task: Scalable Long-Horizon Planning for Abstract Human Tasks"
authors: ["Zhihong Liu", "Yang Li", "Rengming Huang", "Cewu Lu", "Panpan Cai"]
date: 2026-02-01
publishDate: 2026-02-01T15:00:00+08:00

publication_types: ["3"]

abstract: "Open-world language-conditioned task planning is crucial for robots operating in large-scale household environments. While many recent works attempt to address this problem using Large Language Models (LLMs) via prompting or training, a key challenge remains: scalability. Performance often degrades rapidly with increasing environment size, plan length, instruction ambiguity, and constraint complexity. In this work, we propose Any House Any Task (AHAT), a household task planner optimized for long-horizon planning in large environments given abstract human instructions. At its core, AHAT utilizes an LLM trained to map task instructions and textual scene graphs into grounded subgoals defined in the Planning Domain Definition Language (PDDL). These subgoals are subsequently solved to generate feasible and optimal long-horizon plans through explicit symbolic reasoning. To enhance the model's ability to decompose complex and ambiguous intentions, we introduce TGPO, a novel reinforcement learning algorithm that integrates external correction of intermediate reasoning trace into Group Relative Policy Optimization (GRPO). Experiments demonstrate that AHAT achieves significant performance gains over state-of-the-art prompting, planning, and learning methods, particularly in human-style household tasks characterized by brief instructions but requiring complex execution plans."

publication: "*arXiv preprint*"
featured: false

url_pdf: https://arxiv.org/abs/2602.12244

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
