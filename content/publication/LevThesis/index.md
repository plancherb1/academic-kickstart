---
title: "Reinforcement Learning to Enable Robust Robotic Model Predictive Control"
authors:
- LevGrossman
advisedByMe: true
date: "2020-05-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Harvard University Bachelors of Arts Thesis

abstract: Traditional methods of robotic planning and trajectory optimization often break down when environmental conditions change, real-world noise is introduced, or when rewards become sparse. Consequently, much of the work involved in calculating trajectories is done not by algorithms, but by hand - tuning cost functions and engineering rewards. This thesis seeks to minimize this human effort by building on prior work combining both model-based and modelfree methods within an actor-critic framework. This specific synergy allows for the automatic learning of cost functions expressive enough to enable robust robotic planning. This thesis proposes a novel algorithm, “Reference-Guided, Value-Based MPC,” which combines model predictive control (MPC) and reinforcement learning (RL) to compute feasible trajectories for a robotic arm. The algorithm does this while 1) achieving an almost 50% higher planning success rate than standard MPC, 2) solving in sparse environments considered unsolvable by current state of the art algorithms, and 3) generalizing its solutions to different environment initializations.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: This thesis proposes a novel algorithm, “Reference-Guided, Value-Based MPC,” which combines model predictive control (MPC) and reinforcement learning (RL) to compute feasible trajectories for a robotic arm. The algorithm does this while 1) achieving an almost 50% higher planning success rate than standard MPC, 2) solving in sparse environments considered unsolvable by current state of the art algorithms, and 3) generalizing its solutions to different environment initializations.

tags:
- Reinforcement Learning
- Model Predictive Control

featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://dash.harvard.edu/bitstream/handle/1/37364714/GROSSMAN-SENIORTHESIS-2020.pdf?sequence=1&isAllowed=y'
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
projects: [RobustTrajopt]
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

