---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Neural Randomized Planning for Whole Body Robot Motion"
authors: ["Yunfan Lu", "Yuchen Ma", "David Hsu", "Panpan Cai"]
date: 2024-05-18
publishDate: 2024-05-18T15:00:00+08:00

publication_types: ["3"]

abstract: "Robot motion planning has made vast advances over the past decades, but the challenge remains: robot mobile manipulators struggle to plan long-range whole-body motion in common household environments in real time, because of high-dimensional robot configuration space and complex environment geometry. To tackle the challenge, this paper proposes Neural Randomized Planner (NRP), which combines a global sampling-based motion planning (SBMP) algorithm and a local neural sampler. Intuitively, NRP uses the search structure inside the global planner to stitch together learned local sampling distributions to form a global sampling distribution adaptively. It benefits from both learning and planning. Locally, it tackles high dimensionality by learning to sample in promising regions from data, with a rich neural network representation. Globally, it composes the local sampling distributions through planning and exploits local geometric similarity to scale up to complex environments. Experiments both in simulation and on a real robot show NRP yields superior performance compared to some of the best classical and learning-enhanced SBMP algorithms. Further, despite being trained in simulation, NRP demonstrates zero-shot transfer to a real robot operating in novel household environments, without any fine-tuning or manual adaptation."

publication: "*arXiv preprint*"
featured: false

url_pdf: https://arxiv.org/abs/2405.11317

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
