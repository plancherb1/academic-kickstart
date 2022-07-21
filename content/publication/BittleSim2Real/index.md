---
title: "Closing the Sim-to-Real Gap for Ultra-Low-Cost, Resource-Constrained, Quadruped Robot Platforms"
authors:
- JasonJabbour
- SabrinaNeuman
- MarkMazumder
- ColbyBanbury
- ShvetankPrakash
- admin
- VijayJanapaReddi
date: "2022-06-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: In the workshop *[Closing the Reality Gap in Sim2Real Transfer for Robotics](https://sim2real.github.io/)* at *[Robotics Science and Systems (RSS) 2022](https://roboticsconference.org/)*
publication_short: In *Workshop on Closing the Sim2Real Gap at RSS 2022*

abstract: "Automating robust walking gaits for legged robots has been a long-standing challenge. Previous work has achieved robust locomotion gaits on sophisticated quadruped hardware platforms through the use of reinforcement learning and imitation learning. However, these approaches do not consider the strict constraints of ultra-low-cost robot platforms with limited computing resources, few sensors, and restricted actuation. These constrained robot platforms require special attention to successfully transfer skills learned in simulation to reality. As a step toward robust learning pipelines for these constrained robot platforms, we demonstrate how existing state-of-the-art imitation learning pipelines can be modified and augmented to support low-cost, limited hardware. By reducing our model’s observational space, leveraging TinyML to quantize our model, and adjusting the model outputs through post-processing, we are able to learn and deploy successful walking gaits on an 8-DoF, $299 (USD) toy quadruped robot that has reduced actuation and sensor feedback, as well as limited computing resources. A video of our current results can be found at: [https://youtu.be/jloya0TOzWA](https://youtu.be/jloya0TOzWA)."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "As a step toward robust learning pipelines for these constrained robot platforms, we demonstrate how existing state-of-the-art imitation learning pipelines can be modified and augmented to support low-cost, limited hardware. By reducing our model’s observational space, leveraging TinyML to quantize our model, and adjusting the model outputs through post-processing, we are able to learn and deploy successful walking gaits on an 8-DoF, $299 (USD) toy quadruped robot that has reduced actuation and sensor feedback, as well as limited computing resources."

tags:
- Sim-to-Real
- TinyML
- Machine Learning
- Embedded Systems
- Robotics
featured: false

links:
- name: Video
  url: 'https://youtu.be/jloya0TOzWA'
url_pdf: 'https://sim2real.github.io/assets/papers/2022/jabbour.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/Bittle_Sim2Real_RSS22.pdf'
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

