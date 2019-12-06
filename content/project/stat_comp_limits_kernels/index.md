---
title: Statistical vs computational limits of kernels.
summary:
tags:
- kernels
- optimality
date: "2019-11-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Surprisingly (or rather unsurprisingly), studying the interplay between statistical and computational properties of algorithms is not a common place in Machine learning although it is glaringly obvious that

1) without computational constraints, exhaustive search or Maximum likelihood based approaches can always find the right solution, if it exists - (statistical optimality).

2) Without statistical guarantees, computationally efficient algorithms are mere heuristics and cannot be deployed in any high-stake real-world applications.  

This focus of this project is to contribute to bridging this gap.

#### Statistical-computational tradeoffs of kernel methods for unsupervised learning:

One of the components of this project is to study the statistical optimality of kernel based algorithms for unsupervised leaning in an information-theoretic sense under different computational constraints. For instance, if we allow the computational complexity of the class of admissible algorithms to be exponential, then an algorithm is typically said to be optimal if it reaches the information-theoretic limit ($ \rho_{NP}^{lower} $ in the figure).  Similarly, one could ask, how does the information theoretic limit change when restricted to the class of poly-time algorithms and do the corresponding poly-time kernel methods achieve this limit?   

In particular, we study this problem in the framework of clustering under both parametric and non-parametric distributional assumptions.

P.S: To our surprise, in this framework even statistical properties of kernel methods have not been well understood due to several technical challenges that arise in analysing kernel algorithms.  

#### Statistical vs computational limits of kernel methods for supervised learning:
Unlike in the case of unsupervised learning, kernel methods have been extensively studied in supervised learning. However, an stimulating idea (uncovered in of the recent works by Mikhail Belkin) I have come across lately is that the Laplacian kernel ($e^{\vert \vert x - y \vert \vert}$) has much more desirable optimisation properties than the Gaussian kernel ($e^{{\vert \vert x - y \vert \vert}^2}$). Considering that one of the primary setbacks of using kernel methods is that they often tend to underperform on a large scale, it would be quite intriguing to understand if these limitations are fundamentally computational or statistical.

#### Publications:

XXX GIVE REFERENCE TO THE AISTATS REVIEW HERE XXX

#### Other References:
 XXX GIVE REFERENCE TO BELKIN'S PAPER HERE XXX

If you find yourselves peaked by this project, then don't hesitate to contact me for a chat.
