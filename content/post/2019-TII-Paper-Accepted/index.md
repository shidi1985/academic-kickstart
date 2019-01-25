+++
title = "Paper on Reinforcement-Learning-Based Optimal Control for Hybrid Energy Storage System is accepted by IEEE TII."
date = 2019-01-24T00:00:00

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = Stream
list_format = 1

# Optional featured image (relative to `static/img/` folder).
#[header]

#image = ""
#caption = ""

[image]
  # Caption (optional)
  caption = "Grid Eye Platform-Home Page"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"

+++

In this paper, a reinforcement-learning-based online optimal (RL-OPT) control method is proposed for hybrid energy storage system (HESS) in AC/DC microgrids involving photovoltaic (PV) system and diesel generators (DG). Due to the low system inertia, conventional unregulated charging and discharging (C&D) of energy storages in microgrids may introduce disturbances that degrade power quality and system performance, especially in fast C&D situations. Secondary and tertiary control levels can optimize the state of charge (SOC) reference of HESS periodically; however, they are lacking the direct controllability of regulating the transient performance. Additionally, the unknown and time-varying system parameters greatly limit the performance of conventional model-based controllers. In this study, the optimal control theory is used to optimize the C&D profile and to suppress the disturbances caused by integrating HESS. Neural networks (NN) are devised to train the nonlinear dynamics of HESS based on the input/output measurement, and to learn the optimal control input for bidirectional converter interfaced HESS using the estimated system dynamics. Because the proposed RL-OPT method is fully decentralized, which only requires the local measurements, the plug & play capability of HESS can be easily realized. Both islanded and grid-tied modes are considered. Extensive simulations and experiments are conducted to evaluate the effectiveness of proposed method.

Check here for detail: https://www.geirina.net/assets/paper/Journal_r1_preprint.pdf
