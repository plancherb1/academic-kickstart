---
title: "Solving Quadratic Programs with Slack Variables via ADMM without Increasing the Problem Size"
authors:
- ThomasLew
- MarcusGreiff
- JohnSubosits
- admin
date: "2025-11-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: #In *[2026 European Control Conference (ECC)](https://ecc26.euca-ecc.org/)*
publication_short: #In *ECC 2026*

abstract: "Proximal methods such as the Alternating Direction Method of Multipliers (ADMM) are effective at solving constrained quadratic programs (QPs). To tackle infeasible QPs, slack variables are often introduced to ensure feasibility, which changes the structure of the problem, increases its size, and slows down numerical resolution. In this letter, we propose a simple ADMM scheme to tackle QPs with slack variables without increasing the size of the original problem. The only modification is a slightly different projection in the z-update, while the rest of the algorithm remains standard. We prove that the method is equivalent to applying ADMM to the QP with additional slack variables, even though slack variables are not added. Numerical experiments show speedups of the approach."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We propose a simple ADMM scheme to tackle QPs with slack variables without increasing the size of the original problem. The only modification is a slightly different projection in the z-update, while the rest of the algorithm remains standard. We prove that the method is equivalent to applying ADMM to the QP with additional slack variables, even though slack variables are not added. Numerical experiments show speedups of the approach."

tags:
- Optimal Control
- ADMM
featured: false

links:
# - name: TBD
#   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2511.08451'
url_code: 'https://github.com/A2R-Lab/ADMMSlack'
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
projects: [GPUOptimization]
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

