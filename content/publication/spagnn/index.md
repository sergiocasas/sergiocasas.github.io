---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data"
authors: [__Sergio Casas__, Cole Gulino, Renjie Liao, Raquel Urtasun]
date: 2020-06-22T23:16:19-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-14T22:16:19-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In this paper, we tackle the problem of relational behavior forecasting from sensor data. Towards this goal, we propose a novel spatially-aware graph neural network (SpAGNN) that models the interactions between agents in the scene. Specifically, we exploit a convolutional neural network to detect the actors and compute their initial states. A graph neural network then iteratively updates the actor states via a message passing process. Inspired by Gaussian belief propagation, we design the messages to be spatially-transformed parameters of the output distributions from neighboring agents. Our model is fully differentiable, thus enabling end-to-end training. Importantly, our probabilistic predictions can model uncertainty at the trajectory level. We demonstrate the effectiveness of our approach by achieving significant improvements over the state-of-the-art on two real-world self-driving datasets: ATG4D and nuScenes."

# Summary. An optional shortened abstract.
summary: "_ICRA 2020_ <br>
Relational reasoning for multi-agent behavior prediction from sensors"

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

url_pdf: https://arxiv.org/pdf/1910.08233.pdf
# url_arxiv: https://arxiv.org/abs/1910.08233
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/zdk66stOeSk

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
