---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "LookOut: Diverse Multi-Future Prediction and Planning for Self-Driving"
authors: [Alexander Cui*, Abbas Sadat*, __Sergio Casas__*, Renjie Liao, Raquel Urtasun]
date: 2021-01-21T15:02:57-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-21T16:02:57-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Self-driving vehicles need to anticipate a diverse set of future traffic scenarios in order to safely share the road with other traffic participants that may exhibit rare but dangerous driving. In this paper, we present LookOut, an approach to jointly perceive the environment and predict a diverse set of futures from sensor data, estimate their probability, and optimize a contingency plan over these diverse future realizations. In particular, we learn a diverse joint distribution over multi-agent future trajectories in a traffic scene that allows us to cover a wide range of future modes with high sample efficiency while leveraging the expressive power of generative models. Unlike previous work in diverse motion forecasting, our diversity objective explicitly rewards sampling future scenarios that require distinct reactions from the self-driving vehicle for improved safety. Our contingency planner then finds comfortable trajectories that ensure safe reactions to a wide range of future scenarios. Through extensive evaluations, we show that our model demonstrates significantly more diverse and sample-efficient motion forecasting in a large-scale self-driving dataset as well as safer and more comfortable motion plans in long-term closed-loop simulations than current state-of-the-art models.
"

# Summary. An optional shortened abstract.
summary: "_ICCV 2021_ <br>
Contingency planning from diverse joint trajectory samples for all actors in the scene"

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

url_pdf: https://arxiv.org/pdf/2101.06547.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/xtM3Sn_Ibjg

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
