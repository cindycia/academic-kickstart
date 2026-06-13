---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ForceVLA: Enhancing VLA Models with a Force-aware MoE for Contact-rich Manipulation"
authors: ["Jiawen Yu*", "Hairuo Liu*", "Qiaojun Yu*", "Jieji Ren", "Ce Hao", "Haitong Ding", "Guangyu Huang", "Guofan Huang", "Yan Song", "Panpan Cai", "Wenqiang Zhang", "Cewu Lu"]
date: 2025-12-01
publishDate: 2025-05-28T15:00:00+08:00

publication_types: ["1"]

abstract: "Vision-Language-Action (VLA) models have advanced general-purpose robotic manipulation by leveraging pretrained visual and linguistic representations. However, they struggle with contact-rich tasks that require fine-grained control involving force, especially under visual occlusion or dynamic uncertainty. To address these limitations, we propose ForceVLA, a novel end-to-end manipulation framework that treats external force sensing as a first-class modality within VLA systems. ForceVLA introduces FVLMoE, a force-aware Mixture-of-Experts fusion module that dynamically integrates pretrained visual-language embeddings with real-time 6-axis force feedback during action decoding. This enables context-aware routing across modality-specific experts, enhancing the robot's ability to adapt to subtle contact dynamics. We also introduce ForceVLA-Data, a new dataset comprising synchronized vision, proprioception, and force-torque signals across five contact-rich manipulation tasks. ForceVLA improves average task success by 23.2% over strong π0-based baselines, achieving up to 80% success in tasks such as plug insertion. Our approach highlights the importance of multimodal integration for dexterous manipulation and sets a new benchmark for physically intelligent robotic control."

publication: "*Advances in Neural Information Processing Systems (NeurIPS)*"
featured: false

url_pdf: https://arxiv.org/abs/2505.22159
url_project: https://sites.google.com/view/forcevla2025

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
