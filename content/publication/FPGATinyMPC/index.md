---
title: "MPC Solver Hardware Generation Framework with Model-Specific Operation Fusion and Pruning"
authors:
- ZhenyuWu
- admin
- IanMcInerney
- HaydenKwokHaySo
- MaolinWang
- KwangTingCheng
date: "2025-12-01T00:00:00Z"
doi: "10.1109/ICFPT67023.2025.00047"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2025 International Conference on Field Programmable Technology](https://www.icfpt.org/)*
publication_short: In *ICFPT* 2025

abstract: "Model Predictive Control (MPC) is a state-of-the- art and robust control framework. However, its stringent per-formance requirements for computational infrastructure, and its need for real-time computation at the edge, hinder its widespread adoption in various application scenarios. This is particularly challenging for the MCUs commonly found on tiny robots. To address this computational challenge, we developed a flexible MPC solver hardware generation framework which includes a parameterized and programmable vector architecture template that accommodates instruction-level and data-level parallelism in vector and matrix functional units, and a model-specific fused architecture. Implementation of the proposed processor on the Ultra96 platform achieves up to a 9.73x speedup compared to existing generic solutions on MCUs. Moreover, end-to-end performance tests reveal that this speedup reduces the overall control error by 25.96%. Overall, the enhanced flexibility and performance of our proposed processor design open up the potential for MPC to be utilized in a broader range of applications."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We developed a flexible MPC solver hardware generation framework which includes a parameterized and programmable vector architecture template that accommodates instruction-level and data-level parallelism in vector and matrix functional units, and a model-specific fused architecture. Implementation of the proposed processor on the Ultra96 platform achieves up to a 9.73x speedup compared to existing generic solutions on MCUs. Moreover, end-to-end performance tests reveal that this speedup reduces the overall control error by 25.96%."

tags:
- Hardware Acceleration
- Model Predictive Control
- FPGA

featured: false

links:
#- name: TBD
#  url: TBD
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

