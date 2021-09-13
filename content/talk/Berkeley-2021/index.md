---
title: Abductive Learning of Phonotactic Constraints
authors:
- admin
event: Invited talk, UC Berkeley Phorum
event_url: ""

location: Invited talk, UC Berkeley Phorum
address:
  street: ""
  city: ""
  region: ""
  postcode: ''
  country: ''

summary: I describe general properties of phonotactic learning via a series of non-statistical abductive inference algorithms   
abstract: Inductive learning of phonotactic knowledge from data often relies on statistical heuristics to select plausible phonotactic constraints, such as in the popular Maximum Entropy learners (Hayes & Wilson 2008). Wilson & Gallagher (2018) claim that such statistical heuristics are necessary, given that feature-based constraints allow for exponentially large hypothesis spaces. I show that such statistical heuristics are unnecessary, by providing a series of non-statistical algorithms which use abduction to select the most general feature-based constraint grammars for both local and long-distance phonotactics. I compare these algorithms to MaxEnt grammars to showcase their similar behavior on synthetic and natural phonotactic data. Like any algorithms, these help us clarify general properties of phonotactic learning. 1) the space of possible constraints possesses significant structure (a partial order) that learners can easily exploit, 2) even given this structure, there are multiple pairwise incomparable grammars which are surface-true, and 3) particular constraint selection is due to the particular abductive (not inductive) principles learners possess which guide the search, regardless of whether such principles are statistically formulated or not.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-09-17T12:00:00Z"
#date_end: "2020-06-01T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-06-03T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
# name: Poster
#  url: "ampposter.pdf"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
# internal-project

# Enable math on this page?
math: true
---
