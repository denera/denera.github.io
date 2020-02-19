---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accelerating Limited-Memory Quasi-Newton Convergence for Large-Scale Optimization"
authors: [
  "Alp Dener",
  "Todd S. Munson"
]
date: 2019-06-08
doi: "10.1007/978-3-030-22744-9_39"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:32:38-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Computational Science 2019, Faro, Portugal"
publication_short: "ICCS 2019"

abstract: "Quasi-Newton methods are popular gradient-based optimization methods that can achieve rapid convergence using only first-order derivatives. However, the choice of the initial Hessian matrix upon which quasi-Newton updates are applied is an important factor that can significantly affect the performance of the method. This fact is especially true for limited-memory variants, which are widely used for large-scale problems where only a small number of updates are applied in order to minimize the memory footprint. In this paper, we introduce both a scalar and a sparse diagonal Hessian initialization framework, and we investigate its effect on the restricted Broyden-class of quasi-Newton methods. Our implementation in PETSc/TAO allows us to switch between different Broyden class methods and Hessian initializations at runtime, enabling us to quickly perform parameter studies and identify the best choices. The results indicate that a sparse Hessian initialization based on the diagonalization of the BFGS formula significantly improves the base BFGS methods and that other parameter combinations in the Broyden class may offer competitive performance."

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

url_pdf: files/pubs/dener2019qn.pdf
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
