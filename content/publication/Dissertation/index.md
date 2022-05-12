---
title: "GPU Acceleration for Real-time, Whole-body, Nonlinear Model Predictive Control"
authors:
- admin
date: "2022-04-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Harvard University PhD Dissertation

abstract: "Whole-body, nonlinear model predictive control (MPC) refers to the control strategy where a robot’s state and input trajectories are continually optimized over a finite time horizon while taking into account the robot’s full nonlinear dynamics. This has been referred to as the “Holy Grail” of robot motion planning and control, as it can enable robots to dynamically compute optimal trajectories and adapt to changes in their environment. Unfortunately, the underlying trajectory optimization algorithms traditionally used to solve these problems are computationally expensive and often too slow to run in real-time. Compounding this issue, the impending end of Moore’s Law and the end of Dennard Scaling have led to a utilization wall that limits the performance a single CPU chip can deliver, requiring computer scientists to look beyond the CPU to exploit large-scale parallelism available on alternative computing platforms such as GPUs. This dissertation address these challenges by exposing, analyzing, and leveraging the structured sparsity and parallelism patterns found in the numerical optimization and rigid body dynamics algorithms commonly used for whole-body, nonlinear MPC. Through careful algorithmic refactoring and re-design, this work exploits these patterns to enable real-time MPC performance through GPU-acceleration. It also validates the feasibility of this approach in the presence of model discrepancies and communication delays between the robot and GPU by deploying the resulting implementations onto a physical manipulator arm. Overall, this dissertation finds that GPU acceleration can provide nearly order-of-magnitude speedups, and open-sources its implementations to aid the wider robotics community in accelerating both robotics computations and application development timelines."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: This dissertation address the computational challenges of whole-body, nonlinear model predictive control (MPC) by exposing, analyzing, and leveraging the structured sparsity and parallelism patterns found in the underlying numerical optimization and rigid body dynamics algorithms. Through careful algorithmic refactoring and re-design, this work exploits these patterns to enable real-time MPC performance through GPU-acceleration. It also validates the feasibility of this approach in the presence of model discrepancies and communication delays between the robot and GPU by deploying the resulting implementations onto a physical manipulator arm. Overall, this dissertation finds that GPU acceleration can provide nearly order-of-magnitude speedups, and open-sources its implementations to aid the wider robotics community in accelerating both robotics computations and application development timelines.

tags:
- Model Predictive Control
- GPU
- Parallel Computing
- Differential Dynamic Programming
- Rigid Body Dynamics
- Trajectory Optimization

featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'files/Dissertation.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/tTy2Vhg2G-I'

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

