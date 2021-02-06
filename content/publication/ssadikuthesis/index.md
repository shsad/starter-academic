---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Locally Accelerated Conditional Gradients - AISTATS 2020"
authors: [Jelena Diakonikolas, Alejandro Carderera, Sebastian Pokutta]
date: 2019-06-19T13:46:30-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-04T13:46:30-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AISTATS 2020"
publication_short: "AISTATS 2020"

abstract: "Conditional gradients constitute a class of projection-free first-order algorithms for smooth convex optimization. As such, they are frequently used in solving smooth convex optimization problems over polytopes, for which the computational cost of orthogonal projections would be prohibitive. However, they do not enjoy the optimal convergence rates achieved by projection-based accelerated methods; moreover, achieving such globally-accelerated rates is information-theoretically impossible for these methods. To address this issue, we present Locally Accelerated Conditional Gradients -- an algorithmic framework that couples accelerated steps with conditional gradient steps to achieve local acceleration on smooth strongly convex problems. Our approach does not require projections onto the feasible set, but only on (typically low-dimensional) simplices, thus keeping the computational cost of projections at bay. Further, it achieves the optimal accelerated local convergence. Our theoretical results are supported by numerical experiments, which demonstrate significant speedups of our framework over state of the art methods in both per-iteration progress and wall-clock time."

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

links:
  - icon_pack: fas
    icon: video
    name: Video
    url: 'https://slideslive.com/38930107/locally-accelerated-conditional-gradients?ref=account-folder-52123-folders'
  - icon_pack: ai
    icon: arxiv
    name: PDF
    url: 'https://arxiv.org/pdf/1906.07867.pdf'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/pokutta/lacg'
  - icon_pack: fas
    icon: chalkboard-teacher
    name: Blog Post
    url: 'http://www.pokutta.com/blog/research/2019/07/04/LaCG-abstract.html'
  - icon_pack: fas
    icon: file
    name: Slides
    url: 'AISTATSPresentation.pdf'

url_pdf: 
url_code: 
url_slides:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Primal gap convergence comparison: Minimization of quadratic over Birkhoff polytope. See paper for details."
  focal_point: "Center"
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
