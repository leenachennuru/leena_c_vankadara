---
title: Object detection for an Interactive Robotic Memory Aid system.
event:
event_url:


summary: Worked on the design, research and implementation of an interactive Robotic Memory Aid system that assists humans in their search for misplaced belongings within a natural home-like environment.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2015-10-01T13:00:00Z"
date_end: "2016-03-01T15:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'IRMA'
  focal_point: Right

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

 In this project, we worked on the design, research and implementation of an interactive Robotic Memory Aid system that assists humans in their search for misplaced belongings within a natural home-like environment. In addition to collaborating on the design of the system, my contribution to the project was to provide an object detection and classification module which involved literature research on the state of the art and implementing efficient algorithms for segmentation, object localization, feature representation and classification schemes. The end result was a robot that could, during the exploration of its environment, localize and classify objects learned during training in real-time.

Some of the challenges we solved during the process include but don’t limit to the problem of unbalanced classes, the problem of choosing an appropriate metrics for histogram comparisons, choosing an appropriate kernel for Support Vector Machines, reducing false positives, preventing overfitting in a convolutional neural network. A  <a href="https://www2.informatik.uni-hamburg.de/wtm/publications/2016/WTGHAKCREJCWBSHNSTW16/Wieser_KI2016_CR.pdf">paper</a> from this work was published in German Conference on Artificial Intelligence (KI) 2016.
{{< /rawhtml >}}
</div>
