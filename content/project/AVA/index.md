---
title: Automated Vehicles for All (AVA) 
summary: A systematic and scalable approach to the safe integration of cooperative automated vehicles (CAVs) into the nation’s transportation system. 
tags:
  - Automated Driving Systems
  - Safety Testing
date: '2023-11-16T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: real-time road segmentation using LiDAR data
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/ava-share'
url_pdf: ''
url_slides: ''
url_video: ''

# # Slides (optional).
# #   Associate this project with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example
---

## Project Overview

The Automated Vehicles for All (AVA) project is a four-year research effort funded by the U.S. Department of Transportation (USDOT). This project is dedicated to forging a systematic approach to achieve a safe integration of automated driving systems into the existing transportation infrastructure, especially on rural roads and multimodal driving enviorments. The project is a led by [Dr. Reza Langari (TAMU)](https://engineering.tamu.edu/mechanical/profiles/langari-reza.html), [Dr. Alireza Talebpour (UIUC)](https://cee.illinois.edu/directory/profile/ataleb), [Dr.Francis Assadian (UC Davis)](https://faculty.engineering.ucdavis.edu/assadian/) and [Dr. Samer Hamdar (GWU)](https://engineering.gwu.edu/samer-hamdar).

Aiming to enhance the safety and efficiency of automated driving systems in rural and multimodal driving environments, this project endeavors to not only evaluate these systems, but also generate a comprehensive dataset for automated vehicle safety analysis and rulemaking. Within this project, I served as a **graduate research assistant**, contributing across multiple teams including **perception**, **data analysis**, and **safety testing**. 

## My contribution
<figure>
  <img src="AVA-data-analysis.gif" width="100%" alt="Trajectory Illustration"/>
  <figcaption>An example of road testing.</figcaption>
</figure>

1. **[Real-time road segmentation using LiDAR data](https://github.com/ava-share/sphereformer-ros):** I undertook the evaluation of various deep learning models, ultimately integrating the [SphereFormer](https://github.com/dvlab-research/SphereFormer) model with ROS to facilitate real-time road segmentation utilizing LiDAR data. This application was rigorously tested in a live environment with an automated vehicle, showcasing the potential for enhanced navigational safety.

2. **[Comprehensive Data Extraction Pipeline](https://github.com/ava-share/Data_extraction):** I designed and implemented a comprehensive data extraction pipeline that invinvorporates camera-based detection, 2D-to-3D data fusion, and object tracking to generate a detailed dataset for the analysis of automated vehicle safety and the formulation of regulatory standards.


3. **Implementation of control algorithm and Satety Testing:** I conducted safety testing on the control and acturation systems of automated vehicles for rural environments in Rantoul, IL.

Through these contributions, I aimed to push the boundaries of what's possible with automated driving technologies, ensuring they can be safely and effectively integrated into our transportation systems, particularly in environments that present unique challenges with less infrustructure supports.

