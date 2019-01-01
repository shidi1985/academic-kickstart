+++
title = "An Alternating Direction Method of Multipliers Based Approach for PMU Data Recovery"
date = 2018-08-07T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mang Liao", "Di Shi", "Zhe Yu", "Zhehan Yi", "Zhiwei Wang", "Yingmeng Xiang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *IEEE Transactions on Smart Grid*, IEEE."
publication_short = "In *IEEETSG*"

# Abstract and optional shortened version.
abstract = "This paper presents a novel algorithm for recovering missing phasor measurement unit (PMU) data. Due to the low-rank property of PMU data, missing measurement recovery can be formulated as a low-rank matrix-completion problem. Based on maximum-margin matrix factorization, we propose an efficient algorithm, alternating direction method of multipliers (ADMM), for solving the matrix completion problem. Compared to existing approaches, the proposed ADMM based algorithm does not need to estimate the rank of the target data matrix and provides better performance in computation complexity. Since PMU data are transferred through insecure and delayed communications, we consider the case of measurements missing from all PMU channels in several sampling instants and provide the strategies of reshaping the matrix composed by the received PMU data for the recovery. Numerical results using real PMU measurements from State Grid Jiangsu Electric Power Company illustrate the effectiveness and efficiency of the proposed approaches."
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

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["WAMS","PMU"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8428530"
#url_preprint = "https://arxiv.org/ftp/arxiv/papers/1706/1706.05419.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1109/TSG.2018.2864176"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
