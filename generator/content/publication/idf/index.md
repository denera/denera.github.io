---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Revisiting Individual Discipline Feasible using matrix-free Inexact-Newton-Krylov"
authors: [
  "Alp Dener",
  "Jason E. Hicken"
]
date: 2014-01-16
doi: "10.2514/6.2014-011"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-19T12:42:15-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "10th AIAA Multidisciplinary Design Optimization Conference, National Harbor, Maryland, USA"
publication_short: "AIAA SciTech 2014"

abstract: "The individual-discipline-feasible (IDF) formulation was proposed to simplify the implementation of MDO problems. The IDF formulation introduces coupling variables into the optimization problem that eliminate the need for a full multidisciplinary analysis at each optimization iteration; this simplifies the solution of MDO problems by maintaining modularity of the discipline software. Historically, the MDO community has used conventional optimization algorithms to solve IDF-formulated problems. Conventional optimizers are not well suited to IDF, because they use limited-memory quasi-Newton methods (linear convergence) and require the constraint Jacobian explicitly. The cost of computing the coupling-variable constraint Jacobian is prohibitively expensive for high-fidelity IDF problems. Matrix-free Reduced-Space inexact-Newton-Krylov (RSNK) algorithms overcome these issues, because they scale superlinearly and do not require the constraint Jacobian explicitly. Therefore, this class of algorithm has great potential to solve IDF-formulated MDO problems in a scalable and efficient manner. In this paper, we describe the application of RSNK to the IDF formulation and compare its performance to the multidisciplinary feasible architecture."

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

url_pdf: files/pubs/dener2014idf.pdf
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
