---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GAMMA: A General Agent Motion Model for Autonomous Driving"
authors: ["Yuanfu Luo*", "Panpan Cai* (co-first and corresponding author)", "Yiyuan Lee", "David Hsu"]
# date: 2022-02-25T15:46:42+08:00
doi: ""
date: 2022-02-01

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-25T15:46:42+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.

abstract: "This paper presents GAMMA, a general motion prediction model that enables large-scale real-time simulation and planning for autonomous driving. GAMMA models heterogeneous, interactive traffic agents that operate under diverse road conditions, with various geometric and kinematic constraints. GAMMA treats the prediction task as constrained optimization in traffic agents’ velocity space. The objective is to optimize an agent’s driving performance, while obeying all the constraints
resulting from the agent’s kinematics, collision avoidance with other agents, and the environmental context. Further, GAMMA explicitly conditions the prediction on human behavioral states as parameters of the optimization model, in order to account for versatile human behaviors. We evaluated GAMMA on a set of real-world benchmark datasets. The results show that GAMMA achieves high prediction accuracy on both homogeneous and heterogeneous traffic datasets, with sub-millisecond execution time. Further, the computational efficiency and the flexibility of GAMMA enable (i) simulation of mixed urban traffic at many locations worldwide and (ii) planning for autonomous driving in dense traffic with uncertain driver behaviors, both in real-time. The open-source code of GAMMA is available online."

publication: "*Robotics and Automation Letter*"
featured: true

url_pdf: https://arxiv.org/pdf/1906.01566.pdf
url_code: https://github.com/AdaCompNUS/gamma
url_dataset: https://github.com/AdaCompNUS/gamma/tree/master/dataset

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "" # "Smart"
  preview_only: false

---
