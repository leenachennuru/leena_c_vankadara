---
title: Neural networks as optimization toolboxes.
summary:
tags:
- kernels
- optimality
date: "2018-12-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: OENN
  focal_point: Smart

links:
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

{{< rawhtml >}}
<div style="text-align: justify">

The idea of using Neural networks for optimisation is not a particularly novel one. Already, in the 80's and 90's, there were a few papers (1, 2) that touched upon this idea. Having said that, this idea has not received the attention that it deserves from the ML community. For instance, many traditional unsupervised learning methods constitute minimising an objective function with or without constraints (for instance, clustering, dimensionality reduction, ordinal embedding, etc). The optimisation problem that arises is typically non-convex and even NP-hard. The traditional approach to solving these problems, often, is to obtain convex relaxations to the original optimisation problem and solve the relaxed problem exactly. The solution to the convex problem is not always guaranteed to be close to the solution of the original problem.

One of the primary causes of the success of deep learning approaches, as widely speculated, theorised and to some extent verified, is that these architectures allow non-convex optimisation to be computationally feasible.  

 The goal of this project is to draw attention to this less explored idea of using Neural networks not just for learning problems but merely for optimisation ones. In a first attempt to address this issue, we use an exceedingly simple neural network architecture to approximately solve the problem of ordinal embedding, which is known to be NP-Hard (3).

</div>
 {{< /rawhtml >}}

### References

1. Haghiri, Siavash, Leena Chennuru Vankadara, and Ulrike von Luxburg. "Large scale representation learning from triplet comparisons." arXiv preprint arXiv:1912.01666 (2019).

2. Anderson, C. Peterson J. "Neural networks and NP-complete optimization problems; a performance study on the graph bisection problem." Complex Systems 2 (1988): 58-59.

3. Tagliarini, Gene A., J. Fury Christ, and Edward W. Page. "Optimization using neural networks." IEEE transactions on computers 12 (1991): 1347-1358.
