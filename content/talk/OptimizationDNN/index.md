---
title: Optimizing Neural Networks.
event: A course seminar report.
event_url:


summary:


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2015-04-01T13:00:00Z"
date_end: "2015-07-01T15:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: '[1]'
  focal_point: Right

  links:
  url_pdf: talk/OptimizationDNN/optimizationDNN.pdf

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---
{{< rawhtml >}}
<div style="text-align: justify">

 The analysis presented in the paper is two fold. 1) Recent literature shows that the critical point behaviour of a randomly chosen high-dimensional landscape is riddled with saddle points in contrast to a low dimensional one. Several algorithms that are employed in optimization of loss surfaces arising in training deep neural networks: RMSPROP, ADAGRAD, Momentum based Gradient Descent, Hessain Free optimization, Conjugate gradient descent, Natural gradient descent, Newtons method and Krylov's subspace method were analyzed for their behaviour around saddle points. 2) In the overfitting paradigm, unsupervised pre-training has been studied for its ability to prevent overfitting and its ability to provide the network with a good initialisation.  

{{< /rawhtml >}}
</div>

### References
1. Kuvshinov, V. I., A. V. Kuzmin, and V. A. Piatrou. "Chaotic instantons in periodically perturbed double-well system." arXiv preprint arXiv:0801.1886 (2008).
