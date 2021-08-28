---
title: "Parallel and Constrained Differential Dynamic Programming for Model Predictive Control"
authors:
- admin
date: "2018-05-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Harvard University Masters of Engineering Thesis

abstract: Differential Dynamic Programming (DDP) has become a popular approach to performing trajectory optimization for complex, underactuated robots. However, using DDP in dynamic environments presents three practical challenges. First, the evaluation of dynamics derivatives during optimization creates a computational bottleneck, particularly in implementations that capture second-order dynamic effects. Second, constraints on the states (e.g., boundary conditions, collision constraints) require additional care since the state trajectory is implicitly defined from the inputs and dynamics. Third, computing solutions fast enough for online robotic motion planning can be challenging. This thesis addresses these problems by first building on recent work on Unscented Dynamic Programming (UDP)—which eliminates dynamics derivative computations in DDP—to support general nonlinear state and input constraints to high precision using an augmented Lagrangian. We then leverage parallel computations for increased throughput and systematically analyze the insights, challenges, tradeoffs, and benefits of implementing a parallelized variant of DDP on both a multi-core CPU and a graphics processing unit (GPU). Finally, we present results demonstrating the performance of our constrained UDP (CUDP) and parallel DDP algorithms on several simulated robot systems including a quadrotor and a 7-DoF robotic arm.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: This thesis builds on recent work on Unscented Dynamic Programming (UDP)—which eliminates dynamics derivative computations in DDP—to support general nonlinear state and input constraints to high precision using an augmented Lagrangian. It then leverages parallel computations for increased throughput and systematically analyzes the insights, challenges, tradeoffs, and benefits of implementing a parallelized variant of DDP on both a multi-core CPU and a graphics processing unit (GPU).

tags:
- Model Predictive Control
- Differential Dynamic Programming
- Unscented Transform
- Augmented Lagrangian
- Parallel Computing
- GPU

featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'files/Masters_Thesis.pdf'
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
projects: [RobustTrajopt, AcceleratingRobotics]
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

