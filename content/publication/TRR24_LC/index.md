---
title: 'An Investigation of Discretionary Lane-changing Decisions: Insights From the Third Generation SIMulation (TGSIM) Dataset'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alireza Talebpour
  - Hani S. Mahmassani
  - Samer H. Hamdar

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: The data-driven characterization of discretionary lane-changing behaviors has traditionally been hindered by the scarcity of high-resolution data that can precisely record lateral movements. In this study, we conducted an exploratory investigation leveraging the Third Generation SIMulation (TGSIM) dataset to advance our understanding of discretionary lane-changing behaviors. In this paper, we developed a discretionary lane-changing extraction pipeline and scrutinized crucial factors such as gaps and relative speeds in leading and following directions. A Dynamic Time Warping (DTW) analysis was performed to quantify the difference between any pair of lane-changing behaviors, and an Affinity Propagation (AP) clustering, evaluated on normalized dynamic time warping distance, was conducted. Our results yielded five clusters based on lead and lag gaps, enabling us to categorize lane-changing behaviors into aggressive, neutral, and cautious for both leading and following directions. Clustering based on relative speeds revealed two distinct groups of lane-changing behaviors, one representing overtaking and the other indicative of transitioning into a lane with stable and homogenous speed. The proposed DTW analysis, in conjunction with AP clustering, demonstrated promising potential in categorizing and characterizing lane-changing behaviors. Additionally, this approach can be readily adapted to analyze any driving behavior.

# Summary. An optional shortened abstract.
summary: Lane-changing behaviors can be categorized from a dynamic time warping perspective.
tags: [traffic flow modeling]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  - TGSIM

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
