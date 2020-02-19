---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Preconditioning Nonlinear Conjugate Gradient with Diagonalized Quasi-Newton"
authors: [
  "Alp Dener",
  "Adam Denchfield",
  "Todd S. Munson"
]
date: 2019-06-12
doi: "10.1145/3324989.3325712"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:36:14-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the Platform for Advanced Scientific Computing Conference"
publication_short: "PASC 2019"

abstract: "Nonlinear conjugate gradient (NCG) methods can generate search directions using only first-order information and a few dot products, making them attractive algorithms for solving large-scale optimization problems. However, even the most modern NCG methods can require large numbers of iterations and, therefore, many function evaluations to converge to a solution. This poses a challenge for simulation-constrained problems where the function evaluation entails expensive partial or ordinary differential equation solutions. Preconditioning can accelerate convergence and help compute a solution in fewer function evaluations. However, general-purpose preconditioners for nonlinear problems are challenging to construct. In this paper, we review a selection of classical and modern NCG methods, introduce their preconditioned variants, and propose a preconditioner based on the diagonalization of the BFGS formula. As with the NCG methods, this preconditioner utilizes only first-order information and requires only a small number of dot products. Our numerical experiments using CUTEst problems indicate that the proposed preconditioner successfully reduces the number of function evaluations at negligible additional cost for its update and application."

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

url_pdf: files/pubs/dener2019cg.pdf
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
