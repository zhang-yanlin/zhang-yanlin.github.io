---
title: The Third Generation SIMulation Data (TGSIM)
summary:  A unique dataset providing accurate L0 to L3 trajectory data, enabling an in-depth exploration of the effects of automated driving systems on human behavior.
tags:
  - Trajecotry Data
  - Traffic Flow Modeling
date: '2023-12-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Data collection from a moving helicopter on Chicago highway
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
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

The Third Generation SIMulation Data (TGSIM) project is a three-year research effort funded by the U.S. Department of Transportation (USDOT) to develop a comprehensive understanding of the impacts of automated driving systems on human behavior. The project is a led by [Dr. Alireza Talebpour (UIUC)](https://cee.illinois.edu/directory/profile/ataleb), [Dr. Hani Mahmassani (Northwestern)](https://transportation.northwestern.edu/people/director/mahmassani-hani/) and [Dr. Samer Hamdar (GWU)](https://engineering.gwu.edu/samer-hamdar).

The project aims to collect and process accurate trajectory datasets capable of characterizing human-automated vehicle interactions under a diverse set of scenarios in diverse highway and city environments. The datasets will be used to develop and validate traffic flow models that account for the impacts of automated driving systems on traffic flow. At the forefront of this project, I served as the **leading graduate research assistant**, playing a crucial role in developing a comprehensive data extraction pipeline that stands as a testament to our innovative approach to understanding the future of mobility. 

## Data Collecting Methodologies

Multiple methods were utilized to ensure comprehensive coverage of our study areas:

* **Fixed location aerial videography:** a helicopter hovers over a segment of interest.
* **Moving aerial videography:** a helicopter tracks the automated vehicles as they navigate a longer roadway segment.
* **Infrastructure-based videography:** multiple overlapping cameras located on overpasses and buildings creating a comprehensive image of the study area. 

## Data Processing Pipeline
<figure>
  <img src="trajectory.png" width="80%" alt="Trajectory Illustration"/>
  <figcaption>A sample of the extracted trajectories.</figcaption>
</figure>
Extracting multiple vehicle trajectories from video data raises a set of methodological and practical challenges that vary across the three data collection approaches. The pipeline developed for this project includes the following steps: 

* **Preprocessing:**
  * **Raw Image Extraction:** Converting the vedio into a sequence of frames separated at 30 fps over time.
  * **Reference Image Gereration:** Developing a consistent methodology to convert each image into a fixed coordinate system (i.e., reference image).
* **Object Detection:** Leveraging RetinaNet and YOLOv5 for precise vehicle identification within each frame.
* **Object Tracking:** Performing a centroid tracking algorithm to trace vehicle trajectories through consecutive frames.
* **Image Stabilization**
* **Trajectory construction**

## Impact and Contribution
This data collection and processing approach enabled us to extract more than 11,000 vehicle-kilometers of high-fidelity trajectory data from 14 hours of video footage. My contributions not only facilitated the development of a data processing pipeline that is of precision but also paved the way for a deeper understanding of automated driving systems' impact on traffic flow and human behaviors. 

The datasets, poised to be released to the research community by June 2024 through the USDOT data portal.