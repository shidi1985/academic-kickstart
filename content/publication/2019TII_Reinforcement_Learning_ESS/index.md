+++
title = "Reinforcement-Learning-Based Optimal Control for Hybrid Energy Storage Systems in Hybrid AC/DC Microgrids"
date = 2019-01-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jiajun Duan", "Zhehan Yi", "Di Shi", "Chang Lin", "Xiaohu Zhang", "Zhiwei Wang"]

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
publication = "In *IEEE Transactions on Industrial Informatics*."
publication_short = "In *IEEE TII*"

# Abstract and optional shortened version.
abstract = "In this paper, a reinforcement-learning-based online optimal (RL-OPT) control method is proposed for hybrid energy storage system (HESS) in AC/DC microgrids involving photovoltaic (PV) system and diesel generators (DG). Due to the low system inertia, conventional unregulated charging and discharging (C&D) of energy storages in microgrids may introduce disturbances that degrade power quality and system performance, especially in fast C&D situations. Secondary and tertiary control levels can optimize the state of charge (SOC) reference of HESS periodically; however, they are lacking the direct controllability of regulating the transient performance. Additionally, the unknown and time-varying system parameters greatly limit the performance of conventional model-based controllers. In this study, the optimal control theory is used to optimize the C&D profile and to suppress the disturbances caused by integrating HESS. Neural networks (NN) are devised to train the nonlinear dynamics of HESS based on the input/output measurement, and to learn the optimal control input for bidirectional converter interfaced HESS using the estimated system dynamics. Because the proposed RL-OPT method is fully decentralized, which only requires the local measurements, the plug & play capability of HESS can be easily realized. Both islanded and grid-tied modes are considered. Extensive simulations and experiments are conducted to evaluate the effectiveness of proposed method."
abstract_short = "A data-driven reinforcement learning based control algorithm is proposed for hybrid energy storage system and validated using experiments."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["ESS"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ESS"]

# Links (optional).
#url_pdf = ""
url_preprint = "https://www.geirina.net/assets/paper/Journal_r1_preprint.pdf"
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
