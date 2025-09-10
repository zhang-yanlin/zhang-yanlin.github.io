---
title: 'Can the Waymo Open Motion Dataset Support Realistic Behavioral Modeling? A Validation Study with Naturalistic Trajectories'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sungyong Chung
  - Nachuan Li
  - Dana Monzer
  - Hani S. Mahmassani
  - Samer H. Hamdar
  - Alireza Talebpour


# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-08T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2509.03515'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: The Waymo Open Motion Dataset (WOMD) has become a popular resource for data-driven modeling of autonomous vehicles (AVs) behavior. However, its validity for behavioral analysis remains uncertain due to proprietary post-processing, the absence of error quantification, and the segmentation of trajectories into 20-second clips. This study examines whether WOMD accurately captures the dynamics and interactions observed in real-world AV operations. Leveraging an independently collected naturalistic dataset from Level 4 AV operations in Phoenix, Arizona (PHX), we perform comparative analyses across three representative urban driving scenarios discharging at signalized intersections, car-following, and lane-changing behaviors. For the discharging analysis, headways are manually extracted from aerial video to ensure negligible measurement error. For the car-following and lane-changing cases, we apply the Simulation-Extrapolation (SIMEX) method to account for empirically estimated error in the PHX data and use Dynamic Time Warping (DTW) distances to quantify behavioral differences. Results across all scenarios consistently show that behavior in PHX falls outside the behavioral envelope of WOMD. Notably, WOMD underrepresents short headways and abrupt decelerations. These findings suggest that behavioral models calibrated solely on WOMD may systematically underestimate the variability, risk, and complexity of naturalistic driving. Caution is therefore warranted when using WOMD for behavior modeling without proper validation against independently collected data.

# Summary. An optional shortened abstract.
summary: Comprehensive evaluation of the Waymo Open Motion Dataset (WOMD) against naturalistic driving data from Level 4 autonomous vehicle operations in Phoenix, Arizona.
tags: [Behavioral Modeling, Waymo Open Motion Dataset, Naturalistic Driving Data, Autonomous Vehicles, Trajectory Data, Data Validation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'content/publication/TRR25_WODM/2509.03515v1.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
