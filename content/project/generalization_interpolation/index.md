---
title: Revisiting "No free lunch".
summary:
tags:
- generalization
- supervised Learning
- interpolation
- inductive bias
date: "2018-12-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

{{< rawhtml >}}
<div style="text-align: justify">

Classical learning theory suggests that choosing a hypothesis class that is neither too complex nor too simple would lead to optimal expected (generalization) risk. This is typically demonstrated by a U-shaped curve between the expected risk of the estimator and the complexity of the function class (Figure a). Recent work has demonstrated that under certain additional assumptions (such as a minimum norm condition), extending the curve beyond the interpolating regime could lead to learning estimators with lower expected risk. This phenomenon is illustrated in Figure b. Current tools of learning theory do not sufficiently explain this phenomenon. Several questions arise from this discovery: How do we understand generalization properties of interpolating estimators? What kind of explicit biases can give rise to (near) interpolating estimators with desirable generalization properties? Overparameterized neural networks have been known to (empirically) achieve estimators with good generalization properties. A natural question that follows is "what kind of biases underlie such existing models that demonstrate the double descent phenomenon"?

This project is aimed at addressing such questions.

<!-- <figure>
<img src="double_descent.jpg" alt="Double descent">
<figcaption>[1] Different curves demonstrating the relationship between complexity of the hypothesis class and expected risk.</figcaption>
</figure> -->

{{< /rawhtml >}}
</div>
