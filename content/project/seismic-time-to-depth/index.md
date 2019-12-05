---
title: Time to depth conversion and seismic interval velocity estimation 
summary: Research project developed with Ecopetrol S.A., which includes the development of optimization algorithms for time to depth conversion, and development of modules for DesicionSpace Geoscience Software.
tags:
- Seismic
- Time-to-depth conversion
- DecisionSpace Geoscience
- Software
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.

image:
  placement: 1
  caption: Interactive Picking Plugin for DecisionSpace Geoscience
  focal_point: "Center"
---
Time-domain seismic imaging, also known as time migration, is a fast and robust process for areas with mild lateral velocity variation. Even so, structural problems by mild lateral velocity variation can appear under this approach. An alternative known as depth migration manages to mitigate this problem in areas with lateral velocity variation. Therefore, time-to-depth conversion techniques have been employed to obtain seismic interval velocity. In detail, these techniques consist of solving a system of partial differential equations ill-posed with missing boundary conditions, which could lead to stability issues. Thus, an alternative two-step approach, solution of a system of partial differential equations, and interval velocity estimation from an optimization problem were proposed to take into account lateral velocity variations for the 2D case. However, the formulation of an optimization problem for the 3D case is not direct, and it is crucial for the seismic analysis in the interior of the earth. 

In this project, we develop optimization problems to estimate the seismic interval velocity from Dix velocity on 2D and 3D data using image ray theory. Furthermore, we develop different modules for the DecisionSpace Geoscience software to implement the designed algorithms.