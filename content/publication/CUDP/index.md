---
title: "Constrained Unscented Dynamic Programming"
authors:
- admin
- ZacharyManchester
- ScottKuindersma
date: "2017-09-28T00:00:00Z"
doi: "10.1109/IROS.2017.8206457"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://www.iros2017.org/)*
publication_short: In *IROS 2017*

abstract: Differential Dynamic Programming (DDP) has become a popular approach to performing trajectory optimization for complex, underactuated robots. However, DDP presents two practical challenges. First, the evaluation of dynamics derivatives during optimization creates a computational bottleneck, particularly in implementations that capture second-order dynamic effects. Second, constraints on the states (e.g., boundary conditions, collision constraints, etc.) require additional care since the state trajectory is implicitly defined from the inputs and dynamics. This paper addresses both of these problems by building on recent work on Unscented Dynamic Programming (UDP) - which eliminates dynamics derivative computations in DDP - to support general nonlinear state and input constraints using an augmented Lagrangian. The resulting algorithm has the same computational cost as first-order penalty-based DDP variants, but can achieve constraint satisfaction to high precision without the numerical ill-conditioning associated with penalty methods. We present results demonstrating its favorable performance on several simulated robot systems including a quadrotor and 7-DoF robot arm.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: We build on recent work on Unscented Dynamic Programming (UDP) - which eliminates dynamics derivative computations in DDP - to support general nonlinear state and input constraints using an augmented Lagrangian. The resulting algorithm has the same computational cost as first-order penalty-based DDP variants, but can achieve constraint satisfaction to high precision without the numerical ill-conditioning associated with penalty methods.

tags:
- Differential Dynamic Programming
- Unscented Transform
- Augmented Lagrangian
featured: false

links:
#- name: Publication
#  url: https://ieeexplore.ieee.org/document/8206457
url_pdf: 'files/CUDP_IROS_paper.pdf'
url_code: 'http://bitly.com/ConstrainedUDP'
url_dataset: ''
url_poster: 'files/CUDP_IROS_poster.pdf'
url_project: ''
url_slides: 'files/CUDP_IROS_presentation.pdf'
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
projects: [RobustTrajopt]
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

