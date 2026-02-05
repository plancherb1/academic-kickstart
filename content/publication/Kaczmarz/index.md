---
title: "TAG-K: Tail-Averaged Greedy Kaczmarz for Computationally Efficient and Performant Online Inertial Parameter Estimation"
authors:
- ShuoSha
- AnupamBhakta
- JustinJiang
- KevinQiu
- IshaanMahajan
- GabrielBravo
- admin
date: "2026-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2026 IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)*
publication_short: In *ICRA 2026*

abstract: "Accurate online inertial parameter estimation is essential for adaptive robotic control, enabling real-time adjustment to payload changes, environmental interactions, and system wear. Traditional methods such as Recursive Least Squares (RLS) and the Kalman Filter (KF) often struggle to track abrupt parameter shifts or incur high computational costs, limiting their effectiveness in dynamic environments and for computationally constrained robotic systems. As such, we introduce TAG-K, a lightweight extension of the Kaczmarz method that combines greedy randomized row selection for rapid convergence with tail averaging for robustness under noise and inconsistency. This design enables fast, stable parameter adaptation while retaining the low per-iteration complexity inherent to the Kaczmarz framework. We evaluate TAG-K in synthetic benchmarks and quadrotor tracking tasks against RLS, KF, and other Kaczmarz variants. TAG-K achieves 1.5x-1.9x faster solve times on laptop-class CPUs and 4.8x-20.7x faster solve times on embedded microcontrollers. More importantly, these speedups are paired with improved resilience to measurement noise and a 25% reduction in estimation error, leading to nearly 2x better end-to-end tracking performance."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce TAG-K, a lightweight extension of the Kaczmarz method that combines greedy randomized row selection for rapid convergence with tail averaging for robustness under noise and inconsistency. This design enables fast, stable parameter adaptation while retaining the low per-iteration complexity inherent to the Kaczmarz framework. We evaluate TAG-K in synthetic benchmarks and quadrotor tracking tasks against RLS, KF, and other Kaczmarz variants. TAG-K achieves 1.5x-1.9x faster solve times on laptop-class CPUs and 4.8x-20.7x faster solve times on embedded microcontrollers. More importantly, these speedups are paired with improved resilience to measurement noise and a 25% reduction in estimation error, leading to nearly 2x better end-to-end tracking performance."

tags:
- Parameter Estimation
- Embedded Systems
- Edge Computing

featured: false

awards: []

links:
#   - name: "Website"
#     url: "https://tinympc.org/"
url_pdf: 'https://arxiv.org/abs/2510.04839'
url_code: 'https://github.com/a2r-lab/TAG-K'
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
projects: [TinyRobots]
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

