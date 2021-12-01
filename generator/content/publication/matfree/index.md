---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Matrix-free algorithm for the optimization of multidisciplinary systems"
authors: [
  "Alp Dener",
  "Jason E. Hicken"
]
date: 2017-06-23
doi: "10.1007/s00158-017-1734-0"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:06:59-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Structural and Multidisciplinary Optimization"
publication_short: "Struct Multidisc Optim"

abstract: "Multidisciplinary engineering systems are usually modeled by coupling software components that were developed for each discipline independently. The use of disparate solvers complicates the optimization of multidisciplinary systems and has been a long-standing motivation for optimization architectures that support modularity. The individual discipline feasible (IDF) formulation is particularly attractive in this respect. IDF achieves modularity by introducing optimization variables and constraints that effectively decouple the disciplinary solvers during each optimization iteration. Unfortunately, the number of variables and constraints can be significant, and the IDF constraint Jacobian required by most conventional optimization algorithms is prohibitively expensive to compute. Furthermore, limited-memory quasi-Newton approximations, commonly used for large-scale problems, exhibit linear convergence rates that can struggle with the large number of design variables introduced by the IDF formulation. In this work, we show that these challenges can be overcome using a reduced-space inexact-Newton-Krylov algorithm. The proposed algorithm avoids the need for the explicit constraint Jacobian and Hessian by using a Krylov iterative method to solve the Newton steps. The Krylov method requires matrix-vector products, which can be evaluated in a matrix-free manner using second-order adjoints. The Krylov method also needs to be preconditioned, and a key contribution of this work is a novel and effective preconditioner that is based on approximating a monolithic solution of the (linearized) multidisciplinary system. We demonstrate the efficacy of the algorithm by comparing it with the popular multidisciplinary feasible formulation on two test problems."

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

url_pdf: files/pubs/dener2017matfree.pdf
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
