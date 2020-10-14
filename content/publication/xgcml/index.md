---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Encoder-decoder neural network for solving the nonlinear Fokker-Planck-Landau collision operator in XGC"
authors: [
  "M. Andres Miller",
  "R. Michael Churchill",
  "Alp Dener",
  "Choong-Seock Chang",
  "Todd S. Munson",
  "Robert Hager"
]
date: 2020-09-14

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:29:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Plasma Physics (submitted)"
publication_short: "J of Plasma Phys"

abstract: "An encoder-decoder neural network has been used to examine the possibility for acceleration of a partial integro-differential equation, the Fokker-Planck-Landau collision operator. This is part of the governing equation in the massively parallel particle-in-cell code, XGC, which is used to study turbulence in fusion energy devices. The neural network emphasizes physics-inspired learning, where it is taught to respect physical conservation constraints of the collision operator by including them in the training loss, along with the L2 loss. In particular, network architectures used for the computer vision task of semantic segmentation have been used for training. A penalization method is used to enforce the 'soft' constraints of the system and integrate error in the conservation properties into the loss function. During training, quantities representing the density, momentum, and energy for all species of the system is calculated at each configuration vertex, mirroring the procedure in XGC. This simple training has produced a median relative loss, across configuration space, on the order of 10E-04, which is low enough if the error is of random nature, but not if it is of drift nature in timesteps. The run time for the Picard iterative solver of the operator scales as order n squared, where n is the number of plasma species. As the XGC1 code begins to attack problems including a larger number of species, the collision operator will become expensive computationally, making the neural network solver even more important, since the training only scales as n. A wide enough range of collisionality is considered in the training data to ensure the full domain of collision physics is captured. An advanced technique to decrease the losses further will be discussed, which will be subject of a subsequent report. Eventual work will include expansion of the network to include multiple plasma species.
"

# Summary. An optional shortened abstract.
summary: ""

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

url_pdf: files/pubs/miller2020xgc.pdf
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
