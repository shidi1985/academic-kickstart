+++
title = "Estimate the Lost Phasor Measurement Unit Data Using Alternating Direction Multipliers Method"
date = 2018-03-17T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mang Liao","Di Shi", "Zhe Yu", "Wendong Zhu","Zhiwei Wang","Yingmeng Xiang"]

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
abstract = "This paper presents a novel algorithm for recovering missing data of phasor measurement units (PMUs). Due to the low-rank property of PMU data, missing measurement estimation can be formulated as a low-rank matrix-completion problem. Based on maximum-margin matrix factorization, we propose an efficient algorithm based on alternating direction method of multipliers (ADMM) for solving the matrix completion problem. Comparing to existing approaches, the proposed ADMM based algorithm does not need to estimate the rank of the target data matrix and provides better performance in computation complexity. In addition, we consider the case of measurements missing from all PMU channels and provide a strategy of reshaping the matrix which contains the received PMU data for estimation. Numerical results using PMU measurements from IEEE 68-bus power system model illustrate the effectiveness and efficiency of the proposed approaches."
abstract_short = "The problem of recovering the lost PMU data using ADMM algorithm is considered."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["WAMS"]

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
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8440469"
url_preprint = "https://arxiv.org/pdf/1708.07733.pdf"
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
doi = "10.1109/TDC.2018.8440469"

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
