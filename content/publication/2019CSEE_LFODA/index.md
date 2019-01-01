+++
title = "A Real-time Robust Low-Frequency Oscillation Detection and Analysis (LFODA) System with Innovative Ensemble Filtering"
date = 2018-12-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Desong Bian", "Zhe Yu", "Di Shi", "Ruisheng Diao", "Zhiwei Wang"]

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
publication = "In IEEE  *CSEE Journal of Power and Energy Systems*, IEEE."
publication_short = "In *CSEE*"

# Abstract and optional shortened version.
abstract = "Low-frequency oscillations are hazardous to power system operation, which can lead to cascading failures if not detected and mitigated in a timely manner. This paper presents a robust and automated real-time monitoring system for detecting grid oscillations and analyzing their mode shapes using PMU measurements. A novel Extended Kalman Filtering (EKF) based approach is introduced to detect and analyze oscillations. To further improve the accuracy and efficiency of the presented software system, it takes advantages of three effective signal processing methods (including Prony's Method, Hankel Total Least Square (HTLS) Method, EKF) and adopts a novel voting schema to significantly reduce the computation cost. Results from these methods are processed through a time-series filter to ensure the consistency of detected oscillations and reduce the number of false alarms. The Density-Based Spatial Clustering of Applications with Noise (DBSCAN) method is used to accurately classify oscillation modes and the PMU measurement channels. The LFODA system has been functioning well in the State Grid Jiangsu Electric Power Company with 176 PMUs and 1000+ channels since Feb. 2018, demonstrating outstanding performance in reducing false alarms with much less computational cost."
abstract_short = "A robust and automated real-time monitoring system for detecting grid oscillations and analyzing their mode shares using PMU measurements are introducted."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["WAMS","oscillation"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["PMU","WAMS"]

# Links (optional).
#url_pdf = ""
url_preprint = "https://arxiv.org/ftp/arxiv/papers/1812/1812.11266.pdf"
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
#doi = ""

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
