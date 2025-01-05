---
title: "Time Series Forecasting with Hypernetworks Generating Parameters in Advance"
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
date: "2022-11-22T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2211.12034"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint"
# publication_short: ""

abstract: >
  Forecasting future outcomes from recent time series data is not easy, especially when the future data are different from the past (i.e. time series are under temporal drifts). Existing approaches show limited performances under data drifts, and we identify the main reason: It takes time for a model to collect sufficient training data and adjust its parameters for complicated temporal patterns whenever the underlying dynamics change. To address this issue, we study a new approach; instead of adjusting model parameters (by continuously re-training a model on new data), we build a hypernetwork that generates other target models' parameters expected to perform well on the future data. Therefore, we can adjust the model parameters beforehand (if the hypernetwork is correct). We conduct extensive experiments with 6 target models, 6 baselines, and 4 datasets, and show that our HyperGPA outperforms other baselines.

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
url_pdf: https://arxiv.org/abs/2211.12034
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).


