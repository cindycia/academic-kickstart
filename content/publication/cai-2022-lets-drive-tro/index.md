---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Closing the Planning-Learning Loop with Application to Autonomous Driving"
authors: ["Panpan Cai", "David Hsu"]
# date: 2023-02-25T15:46:42+08:00
doi: ""
date: 2023-08-09

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-09T15:46:42+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.

abstract: "Real-time planning under uncertainty is critical for robots operating in complex dynamic environments. Consider, for example, an autonomous robot vehicle driving in dense, unregulated urban traffic of cars, motorcycles, buses, etc.. The robot vehicle has to plan in both short and long terms, in order to interact with many traffic participants of uncertain intentions and drive effectively. Planning explicitly over a long time horizon, however, incurs prohibitive computational cost and is impractical under real-time constraints. To achieve real-time performance for large-scale planning, this work introduces a new algorithm Learning from Tree Search for Driving (LeTS-Drive), which integrates planning and learning in a closed loop, and applies it to autonomous driving in crowded urban traffic in simulation. Specifically, LeTS-Drive learns a policy and its value function from data provided by an online planner, which searches a sparsely-sampled belief tree; the online planner in turn uses the learned policy and value functions as heuristics to scale up its run-time performance for real-time robot control. These two steps are repeated to form a closed loop so that the planner and the learner inform each other and improve in synchrony. The algorithm learns on its own in a self-supervised manner, without human effort on explicit data labeling. Experimental results demonstrate that LeTS-Drive outperforms either planning or learning alone, as well as open-loop integration of planning and learning."

publication: "*IEEE Transactions on Robotics (T-RO)*"
featured: true

url_pdf: https://arxiv.org/abs/2101.03834
url_code: https://github.com/cindycia/lets-drive

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "" # "Smart"
  preview_only: false

---
