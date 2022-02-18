---
title: "Interpolation and Regularization for Causal Learning"
authors:
- admin
- Luca Rendsburg
- Ulrike von Luxburg
- Debarghya Ghoshdastidar
date: "2022-02-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: We study the problem of learning causal models from observational data through the lens of interpolation and its counterpart---regularization. A large volume of recent theoretical, as well as empirical work, suggests that, in highly complex model classes, interpolating estimators can have good statistical generalization properties and can even be optimal for statistical learning. Motivated by an analogy between statistical and causal learning recently highlighted by Janzing (2019), we investigate whether interpolating stimators can also learn good causal models. To this end, we consider a simple linearly confounded model and derive precise asymptotics for the *causal risk* of the min-norm interpolator and ridge-regularized regressors in the high-dimensional regime. Under the principle of independent causal mechanisms, a standard assumption in causal learning, we find that interpolators cannot be optimal and causal learning requires stronger regularization than statistical learning. This resolves a recent conjecture in Janzing (2019). Beyond this assumption, we find a larger range of behavior that can be precisely characterized with a new measure of *confounding strength*. If the confounding strength is negative, causal learning requires weaker regularization than statistical learning, interpolators can be optimal, and the optimal regularization can even be negative. If the confounding strength is large, the optimal regularization is infinite, and learning from observational data is actively harmful.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Causality
- Interpolation
- Benign Overfitting
- Double Descent
- Learning Theory
- High-dimensional Statistics
featured: false

links:
url_pdf:
#url_project: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Causal double descent'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
