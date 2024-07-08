---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "End-to-end Interpretable Neural Motion Planner"
authors: [Wenyuan Zeng*, Wenjie Luo*, Simon Suo, Abbas Sadat, Bin Yang, __Sergio Casas__, Raquel Urtasun]
date: 2020-06-21T13:55:45-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-21T13:55:45-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "End-to-end Interpretable Neural Motion Planner"
publication_short: "NMP"

abstract: "In this paper, we propose a neural motion planner for learning to drive autonomously in complex urban scenarios that include traffic-light handling, yielding, and interactions with multiple road-users. Towards this goal, we design a holistic model that takes as input raw LIDAR data and a HD map and produces interpretable intermediate representations in the form of 3D detections and their future trajectories, as well as a cost volume defining the goodness of each position that the self-driving car can take within the planning horizon. We then sample a set of diverse physically possible trajectories and choose the one with the minimum learned cost. Importantly, our cost volume is able to naturally capture multi-modality. We demonstrate the effectiveness of our approach in real-world driving data captured in several cities in North America. Our experiments show that the learned cost volume can generate safer planning than all the baselines."

# Summary. An optional shortened abstract.
summary: "_CVPR 2019_ <span style='color:red'>__(Oral)__</span> <br>
Neural motion planner from LiDAR and HD maps
"

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://openaccess.thecvf.com/content_CVPR_2019/papers/Zeng_End-To-End_Interpretable_Neural_Motion_Planner_CVPR_2019_paper.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/CBfTYO3e1b0

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
