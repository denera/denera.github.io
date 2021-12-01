---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Modular Matrix-Free Approach to Multidisciplinary Design Optimization"
authors: [
  "Alp Dener"
]
date: 2017-11-19
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:10:41-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "The individual discipline feasible (IDF) formulation is a multidisciplinary design optimization (MDO) architecture that provides modularity for the underlying discipline solvers. Similar to reduced-space methods, the IDF formulation does not require the optimization algorithm to converge the state variables for each disci- pline in addition to the optimization variables; the state equations are still solved fully at each optimization iteration. However, IDF decouples the discipline equations from each other through the introduction of coupling variables and constraints to the optimization problem. Consequently, the discipline solutions at each optimization iteration can be performed independently and in parallel. This promotes the use of existing discipline-specific PDE solvers, and lowers the software development challenge of creating efficient coupled discipline analyses.

Despite its advantages in modularity, the IDF architecture has remained largely unused by researchers and practitioners alike since its introduction in the early 1990s. The addition of large numbers of variables and constraints into the optimization problem proved to be challenging for conventional gradient-based optimization approaches. In particular, the explicit constraint Jacobian required by these algorithms is prohibitively expensive to compute for IDF problems.

In this thesis, we propose a reduced-space inexact-Newton-Krylov (RSNK) algorithm that can address the challenges posed by the IDF formulation. RSNK achieves this with three key components: a matrix-free formulation that avoids explicit Jacobians and Hessians, a new Krylov solver tailored for nonconvex saddle-point problems, and a novel matrix-free preconditioner for the IDF architecture. We implement RSNK in a parallel-agnostic optimization library, and verify its efficacy on a range of low- and high-fidelity test problems drawn from aerospace applications. Our findings demonstrate that RSNK scales favorably with the size of the design space, exhibits superlinear asymptotic convergence, and can efficiently solve large-scale PDE-governed MDO problems."

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

url_pdf: files/pubs/dener2017thesis.pdf
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
