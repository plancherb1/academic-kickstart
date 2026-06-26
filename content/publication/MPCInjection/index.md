---
title: "MPC-Injection: Biasing Off-Policy Locomotion RL Toward Controller-Induced Behavior Basins"
authors:
- RoyXing
- SeyoungRee
- admin
date: "2026-06-24T00:00:03Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-24T00:00:03Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[Robotics and Automation Letters](https://www.ieee-ras.org/publications/ra-l)* 2025
# publication_short: In *RA-L* 2025

abstract: "Reinforcement learning (RL) for locomotion frequently converges to locally optimal but undeployable behaviors, such as vibrating limbs or scooting on the torso, that maximize return without producing a usable gait. We present MPC-Injection, a low-overhead method that steers RL toward a designer-preferred gait by inserting transitions into the replay buffer from a model predictive controller solving the same Markov decision process. Unlike reward shaping, MPC-Injection does not require redesigning the task reward, and unlike adversarial imitation learning, it adds no discriminator, no kinematic retargeting, and no auxiliary objective. Instead, the controller's preferred behavior is transferred to the policy purely through the replay state distribution. On a 2D walker in simulation and with sim-to-real evaluation on a Go2 quadruped, we show that MPC-Injection drives the policy into the controller's behavior basin using a one to two-term task reward, producing gaits qualitatively comparable to those of reward shaping with twenty-one tuned terms and of adversarial motion priors without their discriminator and retargeting overhead. We further analyze how the injected transitions bias actor-critic updates toward controller-visited states, allowing the policy to learn behaviors that pure RL may fail to reach under simple reward functions."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We present MPC-Injection, a low-overhead method that steers RL toward a designer-preferred gait by inserting transitions into the replay buffer from a model predictive controller solving the same Markov decision process. Unlike reward shaping, MPC-Injection does not require redesigning the task reward, and unlike adversarial imitation learning, it adds no discriminator, no kinematic retargeting, and no auxiliary objective. Instead, the controller's preferred behavior is transferred to the policy purely through the replay state distribution."

tags:
- Model Predictive Control
- Reinforcement Learning
- Replay Buffer
- Trajectory Optimization
featured: false

awards: []

links:
  # - name: "TBD"
  #   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2606.26392'
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
projects: [RobotLearning, GPUOptimization]
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

