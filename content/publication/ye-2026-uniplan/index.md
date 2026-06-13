---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "UniPlan: Vision-Language Task Planning for Mobile Manipulation with Unified PDDL Formulation"
authors: ["Haoming Ye", "Yunxiao Xiao", "Cewu Lu", "Panpan Cai"]
date: 2026-02-01
publishDate: 2026-02-01T15:00:00+08:00

publication_types: ["3"]

abstract: "Integration of VLM reasoning with symbolic planning has proven to be a promising approach to real-world robot task planning. Existing work like UniDomain effectively learns symbolic manipulation domains from real-world demonstrations, described in Planning Domain Definition Language (PDDL), and has successfully applied them to real-world tasks. These domains, however, are restricted to tabletop manipulation. We propose UniPlan, a vision-language task planning system for long-horizon mobile-manipulation in large-scale indoor environments, that unifies scene topology, visuals, and robot capabilities into a holistic PDDL representation. UniPlan programmatically extends learned tabletop domains from UniDomain to support navigation, door traversal, and bimanual coordination. It operates on a visual-topological map, comprising navigation landmarks anchored with scene images. Given a language instruction, UniPlan retrieves task-relevant nodes from the map and uses a VLM to ground the anchored image into task-relevant objects and their PDDL states; next, it reconnects these nodes to a compressed, densely-connected topological map, also represented in PDDL, with connectivity and costs derived from the original map; Finally, a mobile-manipulation plan is generated using off-the-shelf PDDL solvers. Evaluated on human-raised tasks in a large-scale map with real-world imagery, UniPlan significantly outperforms VLM and LLM+PDDL planning in success rate, plan quality, and computational efficiency."

publication: "*arXiv preprint*"
featured: false

url_pdf: https://arxiv.org/abs/2602.08537

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
