---
title: "RAYA: Learning Where and When to Intervene for Robot Recovery"
authors:
- IshaanMahajan
- CharlesChen
- FrederikeDuembgen
- admin
date: "2026-09-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "In *[Frontiers of Optimization for Robotics](https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home)* a Workshop at [2026 International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)"
# publication_short: In *Frontiers of Optimization* at *ICRA 2026*

abstract: "A robot can predict failure and still be unable to prevent it. By the time a safety mechanism reacts, the nominal plan may already have spent the control authority that recovery requires, and fixed task priorities may block whatever response remains. Our key insight is that both aspects are decided inside the controller. Recoverability must inform actions while they are chosen rather than veto them afterward, and task objectives must be adapted as recoverability shrinks. Building on this, we present RAYA, a hybrid learned-analytic framework that places a learned finite-horizon recoverability margin inside an optimal controller with hard constraints and pairs it with a bounded learned scheduler that shifts task weights to facilitate recovery. Across 7,200 simulation episodes per controller spanning quadrotor and autonomous-vehicle benchmarks, RAYA not only improves survival rates, but also transfers the learned components zero-shot to unseen trajectories, disturbances, plant shifts, and friction layouts. We developed an embedded realization of RAYA and deployed it on-board a 35g Crazyflie quadrotor. Across 40 combined hardware flights under wind with either aerodynamic mismatch or an unmodeled 40% motor-command loss, each of three baselines fails in all trials, while RAYA completes 10/10 six-cycle missions. Project Website: https://raya-control.github.io/."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We present RAYA, a hybrid learned-analytic framework that places a learned finite-horizon recoverability margin inside an optimal controller with hard constraints and pairs it with a bounded learned scheduler that shifts task weights to facilitate recovery. Across 7,200 simulation episodes per controller spanning quadrotor and autonomous-vehicle benchmarks, RAYA not only improves survival rates, but also transfers the learned components zero-shot to unseen trajectories, disturbances, plant shifts, and friction layouts. We developed an embedded realization of RAYA and deployed it on-board a 35g Crazyflie quadrotor. Across 40 combined hardware flights under wind with either aerodynamic mismatch or an unmodeled 40% motor-command loss, each of three baselines fails in all trials, while RAYA completes 10/10 six-cycle missions."

tags:
- Safety
- Recoverability
- MCU
- MPC
featured: false

awards: []

links:
  - name: "Website"
    url: "https://raya-control.github.io/"
url_pdf: 'https://arxiv.org/abs/2609.21690'
url_code: 'https://github.com/RAYA-CONTROL/RAYA'
url_dataset: ''
url_poster: ''
url_project: 'https://raya-control.github.io/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=Zy9LKJpOZww'

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