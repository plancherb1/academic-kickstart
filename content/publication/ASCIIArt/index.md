---
title: "ASCII Art Turns LLMs into VLA Controllers"
authors:
- YitaoJiang
- RoyXing
- LuyangZhao
- admin
- MuhaoChen
- DevinBalkcom
date: "2026-06-19T00:00:03Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-19T00:00:03Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[Robotics and Automation Letters](https://www.ieee-ras.org/publications/ra-l)* 2025
# publication_short: In *RA-L* 2025

abstract: "Vision–Language–Action (VLA) controllers are often built by extending vision–language models (VLMs) with action supervision, relying on multimodal backbones with large data and compute requirements. We demonstrate that a text-only large language model (LLM) can be adapted into a VLA-style controller when visual observations are rendered into a text input using an ASCII representation. This ASCII-as-vision interface enables existing training and deployment stacks for LLMs to efficiently condition on visual state, follow natural-language instructions, and produce constrained, executable actions. We fine-tune and compare multiple LLMs and VLMs across model families and scales, using both expert demonstrations from a planning-based teacher, as well as DAgger for iterative improvement. In a 2D manipulation benchmark, in both simulation and on a physical manipulator, the resulting controllers can identify task-relevant entities and plan feasible action sequences. Our results suggest that ASCII rendering can serve as a lightweight, interpretable modality bridge from images to text, complementing conventional VLA pipelines, and opening directions for VLA research with text-only backbones."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We demonstrate that a text-only large language model (LLM) can be adapted into a VLA-style controller when visual observations are rendered into a text input using an ASCII representation. This ASCII-as-vision interface enables existing training and deployment stacks for LLMs to efficiently condition on visual state, follow natural-language instructions, and produce constrained, executable actions."

tags:
- Vision–Language–Action Models
- Large Language Models
- VLAs
- LLMs
featured: false

awards: []

links:
  # - name: "TBD"
  #   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2606.21470'
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
projects: [RobotLearning]
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

