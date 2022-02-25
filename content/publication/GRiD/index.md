---
title: "GRiD: GPU-Accelerated Rigid Body Dynamics with Analytical Gradients"
authors:
- admin
- SabrinaNeuman
- RadhikaGhosal
- ScottKuindersma
- VijayJanapaReddi
date: "2022-02-24T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]
underReviewFlag: False

# Publication name and optional abbreviated publication name.
publication: In the 2022 *[IEEE International Conference on Robotics and Automation](http://www.icra2022.org/)*
publication_short: In *ICRA* 2022

abstract: We introduce GRiD, a GPU-accelerated library for computing rigid body dynamics with analytical gradients. GRiD was designed to accelerate the nonlinear trajectory optimization subproblem used in state-of-the-art robotic planning, control, and machine learning, which requires tens to hundreds of naturally parallel computations of rigid body dynamics and their gradients at each iteration. GRiD leverages URDF parsing and code generation to deliver optimized dynamics kernels that not only expose GPU-friendly computational patterns, but also take advantage of both fine-grained parallelism within each computation and coarse-grained parallelism between computations. Through this approach, when performing multiple computations of rigid body dynamics algorithms, GRiD provides as much as a 7.2x speedup over a state-of-the-art, multi-threaded CPU implementation, and maintains as much as a 2.5x speedup when accounting for I/O overhead. We release GRiD as an open-source library for use by the wider robotics community.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary:  We introduce and release GRiD, an open-source, GPU-accelerated library for computing rigid body dynamics with analytical gradients. GRiD was designed to accelerate nonlinear trajectory optimization through optimized code generation, GRiD provides as much as a 7.2x speedup over a state-of-the-art, multi-threaded CPU implementation and maintains as much as a 2.5x speedup when accounting for I/O overhead.

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- Rigid Body Dynamics

featured: true

links:
  - name: Benchmark Experiments
    url: 'https://github.com/robot-acceleration/GRiDBenchmarks'
url_pdf: 'https://arxiv.org/pdf/2109.06976.pdf'
url_code: 'https://github.com/robot-acceleration/GRiD'
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
projects: [AcceleratingRobotics]
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

