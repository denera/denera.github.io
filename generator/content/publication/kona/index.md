---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Kona: A Parallel Optimization Library for Engineering-Design Problems"
authors: [
  "Alp Dener",
  "Pengfei Meng",
  "Jason E. Hicken",
  "Graeme J. Kennedy",
  "John T. Hwang",
  "Justin S. Gray"
]
date: 2016-01-06
doi: "10.2514/6.2016-1422"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T13:02:45-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "57th AIAA/ASCE/AHS/ASC Structures, Structural Dynamics, and Materials Conference"
publication_short: "AIAA SciTech 2016"

abstract: "Kona is a Python library targeting partial-differential-equation (PDE) governed optimization problems. To address the high computational cost of such problems, Kona permits parallel execution of linear algebra and optimization operations while remaining agnostic to the implementation details of the underlying PDE solver. To accomplish this, Kona adopts a reverse-communication-inspired interface where the optimization algorithm requests the PDE solver to perform a predetermined set of tasks on solver-generated memory. Consequently, the optimization itself is parallelized as long as the user defines parallel data structures within an abstract vector interface and performs the requested tasks in parallel. This abstraction layer also facilitates the rapid development of new optimization algorithms independently from the underlying PDE solvers. In this paper we describe Kona’s software design in detail, and demonstrate its use on test cases, ranging from analytical verification problems to a PDE-constrained engineering system."

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

url_pdf: files/pubs/dener2016kona.pdf
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
