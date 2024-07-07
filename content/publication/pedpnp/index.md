---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Safety-Oriented Pedestrian Motion and Scene Occupancy Forecasting"
authors: [Katie Luo*, __Sergio Casas__*, Renjie Liao, Xinchen Yan, Yuwen Xiong, Wenyuan Zeng, Raquel Urtasun]
date: 2021-01-21T08:14:09-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-21T18:14:09-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In this paper, we address the important problem in self-driving of forecasting multi-pedestrian motion and their shared scene occupancy map, critical for safe navigation. Our contributions are two-fold. First, we advocate for predicting both the individual motions as well as the scene occupancy map in order to effectively deal with missing detections caused by postprocessing, e.g., confidence thresholding and non-maximum suppression. Second, we propose a Scene-Actor Graph Neural Network (SA-GNN) which preserves the relative spatial information of pedestrians via 2D convolution, and captures the interactions among pedestrians within the same scene, including those that have not been detected, via message passing. On two large-scale real-world datasets, nuScenes and ATG4D, we showcase that our scene-occupancy predictions are more accurate and better calibrated than those from state-of-the-art motion forecasting methods, while also matching their performance in pedestrian motion forecasting metrics."

# Summary. An optional shortened abstract.
summary: "_IROS 2021_ <br>
Hybrid instance-based and instance-free approach to pedestrian behavior prediction"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2101.02385.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/VW1LBoaXIkU

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
