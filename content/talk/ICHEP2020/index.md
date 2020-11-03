---
title: Automated selection of particle-jet features for data analysis inHigh Energy Physics experiments
event: 40th International Conference on High Energy Physics
event_url: https://indico.cern.ch/event/868940/overview

location: Source Themes HQ
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: ICHEP 2020
abstract: "In high-energy physics experiments, the sensitivity of selection-based analyses critically depends on which observable quantities are taken into consideration and which ones are discarded as considered least important. In this process, scientists are usually guided by their cultural background and by literature.
Yet simple and powerful, this approach may be sub-optimal when machine learning strategies are envisaged and potentially all features are usable. On the other hand, training multivariate algorithms with all available features is often impossible, due to lack of calibration or computing power limitations. How to robustly choose the set of observables to use in a modern high-energy physics analysis?
We show here that it is possible to rank the relative importance of all available features in an automated fashion by engineering a fast and powerful classification model.
Features are sorted with the Random Forest algorithm, then selected as input quantities for a Deep Learning Neural Network. We make it explicit the relation between Random Forest importance ranking and signal-to-background ratio increase, varying the number of features to feed the Neural Network with. We benchmark our procedure with the case of highly boosted di-jet resonances decaying to two $b$ quarks, to be selected against an overwhelming QCD background. Promising results from Monte Carlo simulation with HEP pseudo-detectors are shown."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2030-06-01T13:00:00Z"
date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: file-pdf
  icon_pack: fa
  name: PDF
  url: ichep2020_diluca.pdf
- icon: youtube
  icon_pack: fab
  name: Youtube
  url: ichep2020_diluca.pdf
- icon: file-pdf
  icon_pack: fa
  name: Event
  url: https://indico.cern.ch/event/868940/contributions/3814682/


# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

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

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
