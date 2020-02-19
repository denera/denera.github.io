---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Enabling Modular Aerostructural Optimization: Individual Discipline Feasible without the Jacobians"
authors: [
  "Alp Dener",
  "Jason E. Hicken",
  "Gaetan K. W. Kenway",
  "Joaquim R. R. A. Martins"
]
date: 2018-07-27
doi: "10.2514/6.2018-3570"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:29:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2018 Multidisciplinary Analysis and Optimization Conference, Atlanta, Georgia, USA"
publication_short: "AIAA AVIATION 2018"

abstract: "The individual discipline feasible (IDF) formulation is a modular multidisciplinary design optimization architecture that promotes the use of disparate discipline analysis tools. IDF achieves modularity by introducing coupling variables and coupling constraints into the optimization problem, which enables the state equations for each discipline to be solved independently at each optimization iteration. However, the increased number of optimization variables and nonlinear state-based constraints poses a significant challenge to conventional matrix-explicit optimization algorithms. In this paper, we apply a reduced-space inexact-Newton-Krylov (RSNK) algorithm to a large-scale, high-fidelity aerostructural optimization of a commercial airliner wing. Our findings demonstrate that the RSNK algorithm, paired with a novel matrix-free preconditioner, can solve the IDF problem at least as fast as its multidisciplinary feasible counterpart. In particular, the IDF preconditioner remains highly effective even in the presence of thousands of coupling constraints.
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

url_pdf: files/pubs/dener2018aerostruct.pdf
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
