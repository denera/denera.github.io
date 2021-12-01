---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Comparison of inexact- and Quasi-Newton Algorithms for Aerodynamic Shape Optimization"
authors: [
  "Alp Dener",
  "Gaetan K. W. Kenway",
  "Zhoujie Lyu",
  "Jason E. Hicken",
  "Joaquim R. R. A. Martins"
]
date: 2015-01-09
doi: "10.2514/6.2015-1945"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T12:54:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "53rd AIAA Aerospace Sciences Meeting, Kissimmee, Florida, USA"
publication_short: "AIAA SciTech 2015"

abstract: "Large-scale aerodynamic and multidisciplinary design problems challenge conventional optimization algorithms, because these problems typically involve thousands of design variables and constraints. Alternative algorithms must be developed that produce solutions to large-scale design problems in a reasonable time. To this end, we investigate a scalable reduced-space Newton–Krylov optimization algorithm. This inexact-Newton algorithm uses a novel matrix-free Krylov solver that requires only KKT-matrix-vector products; these products are formed by solving two linear PDEs. We present preliminary results that benchmark the inexact-Newton algorithm against a conventional quasi-Newton algorithm on the Euler-based drag minimization of the Common-Research-Model wing benchmark. For this problem, the preliminary results indicate that the inexact-Newton algorithm scales well and outperforms the conventional algorithm for problems with more than 500 design variables."

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

url_pdf: files/pubs/dener2015aso.pdf
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
