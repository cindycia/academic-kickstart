---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Vec-QMDP: Vectorized POMDP Planning on CPUs for Real-Time Autonomous Driving"
authors: ["Xuanjin Jin", "Yanxin Dong", "Bin Sun", "Huan Xu", "Zhihui Hao", "XianPeng Lang", "Panpan Cai"]
date: 2026-02-01
publishDate: 2026-02-01T15:00:00+08:00

publication_types: ["1"]

abstract: "Planning under uncertainty for real-world robotics tasks, such as autonomous driving, requires reasoning in enormous high-dimensional belief spaces, rendering the problem computationally intensive. While parallelization offers scalability, existing hybrid CPU-GPU solvers face critical bottlenecks due to host-device synchronization latency and branch divergence on SIMT architectures, limiting their utility for real-time planning and hindering real-robot deployment. We present Vec-QMDP, a CPU-native parallel planner that aligns POMDP search with modern CPUs' SIMD architecture, achieving 227x-1073x speedup over state-of-the-art serial planners. Vec-QMDP adopts a Data-Oriented Design (DOD), refactoring scattered, pointer-based data structures into contiguous, cache-efficient memory layouts. We further introduce a hierarchical parallelism scheme: distributing sub-trees across independent CPU cores and SIMD lanes, enabling fully vectorized tree expansion and collision checking. Efficiency is maximized with the help of UCB load balancing across trees and a vectorized STR-tree for coarse-level collision checking. Evaluated on large-scale autonomous driving benchmarks, Vec-QMDP achieves state-of-the-art planning performance with millisecond-level latency, establishing CPUs as a high-performance computing platform for large-scale planning under uncertainty."

publication: "*Robotics: Science and Systems (RSS)*"
featured: true

url_pdf: https://arxiv.org/abs/2602.08334

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
