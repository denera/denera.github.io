---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Error-tolerant Multisecant Method for Nonlinearly Constrained Optimization"
authors: [
  "Jason E. Hicken",
  "Pengfei Meng",
  "Alp Dener"
]
date: 2020-02-14

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:29:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Optimization and Engineering (submitted)"
publication_short: "Opt and Eng"

abstract: "We present a derivative-based algorithm for nonlinearly constrained optimization problems that is tolerant of inaccuracies in the data. The algorithm solves a semi-smooth set of nonlinear equations that are equivalent to the first-order optimality conditions, and it is matrix-free in the sense that it does not require the explicit Lagrangian Hessian or Jacobian of the constraints. The solution method is quasi-Newton, but rather than approximating only the Hessian or constraint Jacobian, the Jacobian of the entire nonlinear set of equations is approximated using a multisecant method. We show how preconditioning can be incorporated into the multisecant update in order to improve the performance of the method. For nonconvex problems, we propose a simple modification of the secant conditions to regularize the Hessian. Numerical experiments suggest that the algorithm is a promising alternative to conventional gradient-based algorithms, particularly when errors are present in the data.
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

url_pdf: files/pubs/hicken2020multisecant.pdf
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
