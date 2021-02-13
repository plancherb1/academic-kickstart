---
title: "Realtime Model Predictive Control using Parallel DDP on a GPU"
authors:
- admin
- ScottKuindersma
date: "2019-05-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In the workshop *[Toward Online Optimal Control of Dynamic Robots](http://www.rsl.ethz.ch/scientific-events/workshops/ICRA-2019/online-optimal-control.html)* at the *[2019 International Conference on Robotics and Automation (ICRA)](https://www.icra2019.org/)*
publication_short: In *Online Optimal Control Workshop at ICRA 2019*

abstract: ""

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: In this extended abstract we extend our previous work by using our Parallel DDP implementation for MPC on a physical Kuka arm. We demonstrated the feasibility of this approach in the presence of model discrepancies and communication delays between the robot and GPU and found that higher control rates generally lead to better tracking performance across a range of parallelization options.

tags:
- Model Predictive Control
- Differential Dynamic Programming
- Parallel Computing
- GPU
featured: true

links:
- name: Video
  url: 'https://www.youtube.com/watch?v=9FgTHw2vdt8'
url_pdf: 'files/GPU_DDP_ICRA_abstract.pdf'
url_code: 'http://bitly.com/ParallelDDP'
url_dataset: ''
url_poster: 'files/GPU_DDP_ICRA_poster.pdf'
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

