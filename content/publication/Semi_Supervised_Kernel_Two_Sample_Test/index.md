---
title: "A Semi-Supervised Kernel Two-Sample Test"
authors:
- admin
- Ilmun Kim
- Shubhanshu Shekhar
date: "2025-01-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: >
Recent advancements in statistics and machine learning have spurred the development
of semi-supervised methodologies that effectively integrate both labeled and unlabeled
data. In this context, statistical inference problems have recently gained increasing atten-
tion. Among these, the kernel Maximum Mean Discrepancy (MMD) test is a widely used
method for detecting distributional differences in two-sample testing. However, standard
kernel-MMD tests typically rely on computationally expensive permutation procedures to
establish rejection thresholds. Moreover, incorporating additional covariates introduces
further complications: under the null hypothesis, the distributions of those do not need to
match, violating the exchangeability assumption required by permutation tests. To address
these challenges, we extend kernel-based two-sample testing to a semi-supervised setting
using sample-splitting and studentization. We establish that our test statistic achieves
asymptotic Normality under the null. We further demonstrate that the test statistic,
regardless of the inclusion of unlabeled data, approximates an asymptotic Normal distri-
bution under the alternative, which facilitates accurate power analyses. We demonstrate
that using unlabeled data increases the test’s power while ensuring consistency, despite
the fact that power consistency is maintained without it. We derive an explicit power
expression for bilinear kernels to substantiate these findings and validate the proposed
method’s enhanced performance through numerical simulations.

# Summary. An optional shortened abstract.
summary: We extend the permutation-free kernel two-sample test in the semi-supervised setting.

tags:
- Hypothesis Testing, Semi-Supervise Inference, Kernel Methods, Maximum Mean Discrepancy
featured: false

# links:
# - name: ""
#   url: ""
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
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
