---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "What Truly Matters in Trajectory Prediction for Autonomous Driving?"
authors: ["Phong Tran*", "Haoran Wu*", "Cunjun Yu*", "Panpan Cai", "Sifa Zheng", "David Hsu"]
date: 2023-12-01
publishDate: 2023-09-21T15:00:00+08:00

publication_types: ["1"]

abstract: "Trajectory prediction plays a vital role in the performance of autonomous driving systems, and prediction accuracy, such as average displacement error (ADE) or final displacement error (FDE), is widely used as a performance metric. However, a significant disparity exists between the accuracy of predictors on fixed datasets and driving performance when the predictors are used downstream for vehicle control, because of a dynamics gap. In the real world, the prediction algorithm influences the behavior of the ego vehicle, which, in turn, influences the behaviors of other vehicles nearby. This interaction results in predictor-specific dynamics that directly impacts prediction results. In fixed datasets, since other vehicles' responses are predetermined, this interaction effect is lost, leading to a significant dynamics gap. This paper studies the overlooked significance of this dynamics gap. We also examine several other factors contributing to the disparity between prediction performance and driving performance. The findings highlight the trade-off between the predictor's computational efficiency and prediction accuracy in determining real-world driving performance. In summary, an interactive, task-driven evaluation protocol for trajectory prediction is crucial to capture its effectiveness for autonomous driving."

publication: "*Advances in Neural Information Processing Systems (NeurIPS)*"
featured: true

url_pdf: https://arxiv.org/abs/2306.15136
url_project: https://whatmatters23.github.io/

image:
  caption: ""
  focal_point: ""
  preview_only: false

---
