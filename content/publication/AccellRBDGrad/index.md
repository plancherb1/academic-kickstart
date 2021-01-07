---
title: "Accelerating Robot Dynamics Gradients on a CPU, GPU, and FPGA"
authors:
- admin
- Sabrina Neuman
- Thomas Bourgeat
- Scott Kuindersma
- Srini Devadas
- Vijay Janapa Reddi
date: "2021-12-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *[Robotics and Automation Letters](https://www.ieee-ras.org/publications/ra-l)* 2021
publication_short: In *RAL* 2021

abstract: Computing the gradient of rigid body dynamics is a central operation in many state-of-the-art planning and control algorithms in robotics. Parallel computing platforms such as GPUs and FPGAs can offer significant performance gains for algorithms with hardware-compatible computational structures. However, the process of refactoring the underlying algorithm to reveal these structures, and implementing performance-critical kernels that exploit them, can be challenging. In this paper, we detail our designs of faster than state-of-the-art implementations of the gradient of rigid body dynamics on a CPU, GPU, and FPGA. We find that our optimized FPGA and GPU implementations provide as much as a 3.0x end-to-end speedup over an optimized CPU implementation and that the relative performance across hardware platforms depends on the number of gradient evaluations required.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: In this paper, we detail our designs of faster than state-of-the-art implementations of the gradient of rigid body dynamics on a CPU, GPU, and FPGA. We find that our optimized FPGA and GPU implementations provide as much as a 3.0x end-to-end speedup over an optimized CPU implementation and that the relative performance across hardware platforms depends on the number of gradient evaluations required.

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- FPGA
- Model Predictive Control

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
url_code: 'https://bitly.com/fast-rbd-grad'
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

