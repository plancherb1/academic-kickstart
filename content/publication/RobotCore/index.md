---
title: "RobotCore: An Open Architecture for Hardware Acceleration in ROS 2"
authors:
- VictorMayoralVilches
- SabrinaNeuman
- admin
- VijayJanapaReddi
date: "2022-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://iros2022.org/)*
publication_short: In *IROS 2022*

abstract: "Hardware acceleration can revolutionize robotics, enabling new applications by speeding up robot response times while remaining power-efficient. However, the diversity of acceleration options makes it difficult for roboticists to easily deploy accelerated systems without expertise in each specific hardware platform. In this work, we address this challenge with RobotCore, an architecture to integrate hardware acceleration in the widely-used ROS 2 robotics software framework. This architecture is target-agnostic (supports edge, workstation, data center, or cloud targets) and accelerator-agnostic (supports both FPGAs and GPUs). It builds on top of the common ROS 2 build system and tools and is easily portable across different research and commercial solutions through a new firmware layer. We also leverage the Linux Tracing Toolkit next generation (LTTng) for low-overhead real-time tracing and benchmarking. To demonstrate the acceleration enabled by this architecture, we use it to deploy a ROS 2 perception computational graph on a CPU and FPGA. We employ our integrated tracing and benchmarking to analyze bottlenecks, uncovering insights that guide us to improve FPGA communication efficiency. In particular, we design an intra-FPGA ROS 2 node communication queue to enable faster data flows, and use it in conjunction with FPGA-accelerated nodes to achieve a 24.42% speedup over a CPU."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce RobotCore, an architecture to integrate hardware acceleration in the widely-used ROS 2 robotics software framework. This architecture is target-agnostic (supports edge, workstation, data center, or cloud targets) and accelerator-agnostic (supports both FPGAs and GPUs). It builds on top of the common ROS 2 build system and tools and is easily portable across different research and commercial solutions through a new firmware layer. We also leverage the Linux Tracing Toolkit next generation (LTTng) for low-overhead real-time tracing and benchmarking. To demonstrate the acceleration enabled by this architecture, we design an intra-FPGA ROS 2 node communication queue to enable faster data flows, and use it in conjunction with FPGA-accelerated nodes to achieve a 24.42% speedup over a CPU."

tags:
- Hardware Acceleration
- Hardware-Software Co-Design
- FPGA
- Robotics
- ROS2
featured: false

awards: []

links:
  - name: "Website"
    url: "https://accelerationrobotics.com/robotcore.php"
url_pdf: 'https://arxiv.org/abs/2205.03929'
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

