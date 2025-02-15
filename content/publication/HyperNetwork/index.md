---
title: "HyperNetwork Approximating Future Parameters for Time Series Forecasting under Temporal Drifts"
authors:
- Jaehoon Lee
- Chan Kim
- admin
- Haksoo Lim
- Jeongwhan Choi
- Kookjin Lee
- Dongeun Lee
- Sanghyun Hong
- Noseong Park
date: "2023-10-28T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["workshop paper"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2023 Workshop on Distribution Shifts: New Frontiers with Foundation Models"
publication_short: "NeurIPS 2023 Workshop on DistShifts"

abstract: >
  Models for time series forecasting require the ability to extrapolate from previous observations. Yet, extrapolation is challenging, especially when the data spanning several periods is under temporal drifts where each period has a different distribution. To address this problem, we propose HyperGPA, a hypernetwork that generates a target model's parameters that are expected to work well (i.e., be an optimal model) for each period. HyperGPA discovers an underlying hidden dynamics which causes temporal drifts over time, and generates the model parameters for a target period, aided by the structures of computational graphs. In comprehensive evaluations, we show that target models whose parameters are generated by HyperGPA are up to 64.1% more accurate than baselines.

# Summary. An optional shortened abstract.
summary: We address problems caused by temporal drifts with hypernetworks which understand an underlying hidden dynamics and generate the parameters of target time series models.

tags:
- Time series forecasting
- Hypernetwork
- Temporal drifts
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://openreview.net/forum?id=7yVBYSPI8Z
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!--
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

 {{% callout note %}}
 Create your slides in Markdown - click the *Slides* button to check out the example.
 {{% /callout %}}

 Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
