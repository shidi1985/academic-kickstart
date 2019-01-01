+++
title = "Forced Oscillation Source Location via Multivariate Time Series Classification"
date = 2018-03-17T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yao Meng", "Zhe Yu", "Di Shi","Desong Bian","Zhiwei Wang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Proceediongs of 2018 IEEE/PES *Transmission and Distribution Conference and Exposition*, IEEE."
publication_short = "In *T&D*"

# Abstract and optional shortened version.
abstract = "Precisely locating low-frequency oscillation sources is the prerequisite of suppressing sustained oscillation, which is an essential guarantee for the secure and stable operation of power grids. Using synchrophasor measurements, a machine learning method is proposed to locate the source of forced oscillation in power systems. Rotor angle and active power of each power plant are utilized to construct multivariate time series (MTS). Applying Mahalanobis distance metric and dynamic time warping, the distance between MTS with different phases or lengths can be appropriately measured. The obtained distance metric, representing characteristics during the transient phase of forced oscillation under different disturbance sources, is used for offline classifier training and online matching to locate the disturbance source. Simulation results using the four-machine two-area system and IEEE 39-bus system indicate that the proposed location method can identify the power system forced oscillation source online with high accuracy."
abstract_short = "The problem of using metric learning in forced oscillation source locating is considered."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["WAMS","oscillation"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["WAMS","PMU"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8440420"
url_preprint = "https://arxiv.org/ftp/arxiv/papers/1711/1711.03601.pdf"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1109/TDC.2018.8440420"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
