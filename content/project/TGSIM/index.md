---
title: Third Generation SIMulation Data (TGSIM)
summary: A Closer Look at the Impacts of Automated Driving Systems on Human Behavior.
tags:
  - Trajecotry Data
  - Traffic Flow Modeling
date: '2023-12-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Real-world trajectory collected from a hovering helicopter on Chicago highway
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

This study collected and processed accurate trajectory datasets capable of characterizing human-automated vehicle interactions under a diverse set of scenarios in diverse highway and city environments. Multiple methods were utilized to collect data: 

* Fixed location aerial videography (a helicopter hovers over a segment of interest); 
* Moving aerial videography (a helicopter follows the automated vehicles as they navigate a longer roadway segment);
* Infrastructure-based videography (multiple overlapping cameras located on overpasses and buildings creating a comprehensive image of the study area). 

Utilizing the fixed location aerial videography approach, trajectories were extracted on I–90/I–94 in Chicago, IL. The moving aerial videography approach was adopted to extract four datasets on I–90/I–94 and I–294 in Chicago, IL. Finally, the infrastructure-based videography approach was utilized to collect data on I–395 in Washington D.C. and on the George Washington University campus (located in the Foggy Bottom Neighborhood). 

Extracting multiple vehicle trajectories from video data raises a set of methodological and practical challenges that vary across the three data measurement approaches. The methodological steps to extract these trajectories are 

* Preprocessing
  * Raw Image Extraction: Every video recording is converted to a sequence of images (i.e., frames) separated at a constant rate over time (e.g., 10 fps). 
  * Reference Image Gereration: This study developed a consistent methodology to convert each image into a fixed coordinate system (i.e., reference image).
* Object Detection : This study used a deep learning-based object detection method, RetinaNet, to identify vehicles in each frame.
* Object Tracking: This study used a centroid tracking algorithm to link the detected vehicles across frames to form vehicle trajectories.
* Image Stabilization
* Trajectory construction

The extracted trajectory datasets are used to develop a comprehensive understanding of the impacts of automated driving systems on human behavior. The datasets can also be used to develop and validate traffic flow models that account for the impacts of automated driving systems on traffic flow. 

This data processing pipline extracted over 11K+
vehicle-kilometers of high-fidelity trajectory data from 14 hours of video. The data will be available for download and use by the research community by June 2024 from USDOT data portal.
