---
title: "pytest-gpu-proof: Enabling Cloud-CPU Continuous Integration for GPU Code with Local GPU Attestation"
authors:
- admin
date: "2026-09-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: "In the *[Workshop on Open Robotics Software](https://sites.google.com/rice.edu/iros26-robotics-software/)* at the *[2026 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://2026.ieee-iros.org/)*"
publication_short: In *Open Robotics Software* at *IROS 2026*

abstract: "GPU acceleration is now routine across robotics, but cloud-hosted GPU continuous integration (CI) runners are expensive, resulting in severe under-testing of GPU-accelerated code. We present pytest-gpu-proof, an open-source pytest plugin offering a practical middle ground. Tests can be run on a local machine, signed with a receipt of exactly what ran and what it produced, and integrated into standard CPU CI workflows (e.g., GitHub Actions). The tool is open source and on PyPI, and we are actively integrating it across our lab's software stack."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "GPU acceleration is now routine across robotics, but cloud-hosted GPU continuous integration (CI) runners are expensive, resulting in severe under-testing of GPU-accelerated code. We present pytest-gpu-proof, an open-source pytest plugin offering a practical middle ground. Tests can be run on a local machine, signed with a receipt of exactly what ran and what it produced, and integrated into standard CPU CI workflows (e.g., GitHub Actions). The tool is open source and on PyPI, and we are actively integrating it across our lab's software stack."

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- Continuous Integration
- Software Testing
featured: false

awards: []

links:
  - name: "Website"
    url: "https://a2r-lab.org/pytest-gpu-proof/"
url_pdf: 'https://arxiv.org/abs/2609.28862'
url_code: 'https://github.com/A2R-Lab/pytest-gpu-proof'
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
projects: [Accelerators]
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