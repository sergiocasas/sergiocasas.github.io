---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Just Label What You Need: Fine-Grained Active Selection for Perception and Prediction through Partially Labeled Scenes"
authors: [Sean Segal, Nishanth Kumar, __Sergio Casas__, Wenyuan Zeng, Mengye Ren, Jingkang Wang, Raquel Urtasun]
date: 2021-01-21T14:02:04-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-21T16:02:04-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Self-driving vehicles must perceive and predict the future positions of nearby actors in order to avoid collisions and drive safely. A learned deep learning module is often responsible for this task, requiring large-scale, high-quality training datasets. As data collection is often significantly cheaper than labeling in this domain, the decision of which subset of examples to label can have a profound impact on model performance. Active learning techniques, which leverage the state of the current model to iteratively select examples for labeling, offer a promising solution to this problem. However, despite the appeal of this approach, there has been little scientific analysis of active learning approaches for the perception and prediction (P&P) problem. In this work, we study active learning techniques for P&P and find that the traditional active learning formulation is ill-suited for the P&P setting. We thus introduce generalizations that ensure that our approach is both cost-aware and allows for fine-grained selection of examples through partially labeled scenes. Our experiments on a real-world, large-scale self-driving dataset suggest that fine-grained selection can improve the performance across perception, prediction, and downstream planning tasks."

# Summary. An optional shortened abstract.
summary: "_arXiv preprint 2021_ <br>
Cost-aware active learning allows for fine-grained selection of examples through partially labeled scenes"

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

url_pdf: https://arxiv.org/pdf/2104.03956.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
