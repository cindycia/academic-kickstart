---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "LEADER: Learning Attention over Driving Behaviors for Planning under Uncertainty"
authors: ["Mohamad H. Danesh*", "Panpan Cai* (corresponding author)", "David Hsu"]
# date: 2022-02-25T15:46:42+08:00
doi: ""
date: 2022-12-14

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-09T15:46:42+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.

abstract: "Uncertainty on human behaviors poses a significant challenge to autonomous driving in crowded urban environments. The partially observable Markov decision processes (POMDPs) offer a principled framework for planning under uncertainty, often leveraging Monte Carlo sampling to achieve online performance for complex tasks. However, sampling also raises safety concerns by potentially missing critical events. To address this, we propose a new algorithm, LEarning Attention over Driving bEhavioRs (LEADER), that learns to attend to critical human behaviors during planning. LEADER learns a neural network generator to provide attention over human behaviors in real-time situations. It integrates the attention into a belief-space planner, using importance sampling to bias reasoning towards critical events. To train the algorithm, we let the attention generator and the planner form a min-max game. By solving the min-max game, LEADER learns to perform risk-aware planning without human labeling."

publication: "*Conference on Robot Learning (CORL) (Best paper finalist)*"
featured: true

url_pdf: https://arxiv.org/abs/2209.11422

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "TopLeft" # "Smart"
  preview_only: false

---
