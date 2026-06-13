---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "World Modeling Makes a Better Planner: Dual Preference Optimization for Embodied Task Planning"
authors: ["Siyin Wang", "Zhaoye Fei", "Qinyuan Cheng", "Shiduo Zhang", "Panpan Cai", "Jinlan Fu", "Xipeng Qiu"]
date: 2025-07-01
publishDate: 2025-07-01T15:00:00+08:00

publication_types: ["1"]

abstract: "Recent advances in large vision-language models (LVLMs) have shown promise for embodied task planning, yet they struggle with fundamental challenges like dependency constraints and efficiency. Existing approaches either solely optimize action selection or leverage world models during inference, overlooking the benefits of learning to model the world as a way to enhance planning capabilities. We propose Dual Preference Optimization (D²PO), a new learning framework that jointly optimizes state prediction and action selection through preference learning, enabling LVLMs to understand environment dynamics for better planning. To automatically collect trajectories and stepwise preference data without human annotation, we introduce a tree search mechanism for extensive exploration via trial-and-error. Extensive experiments on VoTa-Bench demonstrate that our D²PO-based method significantly outperforms existing methods and GPT-4o when applied to Qwen2-VL (7B), LLaVA-1.6 (7B), and LLaMA-3.2 (11B), achieving superior task success rates with more efficient execution paths."

publication: "*Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL)*"
featured: false

url_pdf: https://arxiv.org/abs/2503.10480

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
