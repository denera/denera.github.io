---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Toward Performance-Portable PETSc for GPU-based Exascale Systems"
authors: [
  "Richard Tran Mills", "Mark F. Adams", "Satish Balay", "Jed Brown", "Alp Dener", "Matthew Knepley", "Scott E. Kruger", "Hannah Morgan", "Todd Munson", "Karl Rupp", "Barry F. Smith", "Stefano Zampini", "Hong Zhang", "Junchao Zhang"
]
date: 2020-11-02

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:29:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint"
publication_short: "arXiv"

abstract: "The Portable Extensible Toolkit for Scientific computation (PETSc) library delivers scalable solvers for nonlinear time-dependent differential and algebraic equations and for numerical optimization.The PETSc design for performance portability addresses fundamental GPU accelerator challenges and stresses flexibility and extensibility by separating the programming model used by the application from that used by the library, and it enables application developers to use their preferred programming model, such as Kokkos, RAJA, SYCL, HIP, CUDA, or OpenCL, on upcoming exascale systems. A blueprint for using GPUs from PETSc-based codes is provided, and case studies emphasize the flexibility and high performance achieved on current GPU-based systems.
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

url_pdf: files/pubs/mills2020petscgpu.pdf
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
