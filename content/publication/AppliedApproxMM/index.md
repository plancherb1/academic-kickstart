---
title: "Application of Approximate Matrix Multiplication to Neural Networks and Distributed SLAM"
authors:
- admin
- CameliaBrumar 
- IulianBrumar
- LilliamPentecost
- SakethRama
- DavidBrooks
date: "2019-09-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2019 IEEE High Performance Extreme Computing Conference (HPEC)](http://www.ieee-hpec.org/)*
publication_short: In *HPEC 2019*

abstract: "Computational efficiency is a critical constraint for a variety of cutting-edge real-time applications. In this work, we identify an opportunity to speed up the end-to-end runtime of two such compute bound applications by incorporating approximate linear algebra techniques. Particularly, we apply approximate matrix multiplication to artificial Neural Networks (NNs) for image classification and to the robotics problem of Distributed Simultaneous Localization and Mapping (DSLAM). Expanding upon recent sampling-based Monte Carlo approximation strategies for matrix multiplication, we develop updated theoretical bounds, and an adaptive error prediction strategy. We then apply these techniques in the context of NNs and DSLAM increasing the speed of both applications by 15-20% while maintaining a 97% classification accuracy for NNs running on the MNIST dataset and keeping the average robot position error under 1 meter (vs 0.32 meters for the exact solution). However, both applications experience variance in their results. This suggests that Monte Carlo matrix multiplication may be an effective technique to reduce the memory and computational burden of certain algorithms when used carefully, but more research is needed before these techniques can be widely used in practice."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We apply approximate matrix multiplication to artificial Neural Networks for image classification and to the robotics problem of Distributed Simultaneous Localization and Mapping increasing the speed of both applications by 15-20% while maintaining a 97% classification accuracy for NNs running on the MNIST dataset and keeping the average robot position error under 1
meter (vs 0.32 meters for the exact solution). However, both applications experience variance in their results."

tags:
- Approximation
- Neural Networks
- SLAM
featured: false

links:
url_pdf: 'files/Applied_Approx_MM.pdf'
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
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

