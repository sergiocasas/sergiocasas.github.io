---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Importance of Prior Knowledge in Precise Multimodal Prediction"
authors: [__Sergio Casas__*, Cole Gulino*, Simon Suo*, Raquel Urtasun]
date: 2020-06-25T16:29:45-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-21T16:29:45-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Roads have well defined geometries, topologies, and traffic rules. While this has been widely exploited in motion planning methods to produce maneuvers that obey the law, little work has been devoted to utilize these priors in perception and motion forecasting methods. In this paper we propose to incorporate these structured priors as a loss function. In contrast to imposing hard constraints, this approach allows the model to handle non-compliant maneuvers when those happen in the real world. Safe motion planning is the end goal, and thus a probabilistic characterization of the possible future developments of the scene is key to choose the plan with the lowest expected cost. Towards this goal, we design a framework that leverages REINFORCE to incorporate non-differentiable priors over sample trajectories from a probabilistic model, thus optimizing the whole distribution. We demonstrate the effectiveness of our approach on real-world self-driving datasets containing complex road topologies and multi-agent interactions. Our motion forecasts not only exhibit better precision and map understanding, but most importantly result in safer motion plans taken by our self-driving vehicle. We emphasize that despite the importance of this evaluation, it has been often overlooked by previous perception and motion forecasting works."

# Summary. An optional shortened abstract.
summary: "_IROS 2020_ <span style='color:red'>__(Oral)__</span> <br>
Incorporate non-differentiable prior knowledge for behavior forecasting"

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

url_pdf: https://arxiv.org/pdf/2006.02636.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/Vtj08GQaB1Q

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
