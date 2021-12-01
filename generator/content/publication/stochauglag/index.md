---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Training neural networks under physical constraints using a stochastic augmented Lagrangian approach"
authors: [
  "Alp Dener",
  "M. Andres Miller",
  "R. Michael Churchill",
  "Todd S. Munson",
  "Choong-Seock Chang"
]
date: 2020-09-15

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:29:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational Physics (submitted)"
publication_short: "J of Comp Phys"

abstract: "We investigate the physics-constrained training of an encoder-decoder neural network for approximating the Fokker-Planck-Landau collision operator in the 5-dimensional kinetic fusion simulation in XGC. To train this network, we propose a stochastic augmented Lagrangian approach that utilizes pyTorch's native stochastic gradient descent method to solve the inner unconstrained minimization subproblem, paired with a heuristic update for the penalty factor and Lagrange multipliers in the outer augmented Lagrangian loop. Our training results for a single ion species case, with self-collisions and collision against electrons, show that the proposed stochastic augmented Lagrangian approach can achieve higher model prediction accuracy than training with a fixed penalty method for our application problem, with the accuracy high enough for practical applications in kinetic simulations.
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

url_pdf: files/pubs/dener2020auglag.pdf
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
