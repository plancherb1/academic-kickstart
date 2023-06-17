---
title: "RoboShape: Using Topology Patterns to Scalably and Flexibly Deploy Accelerators Across Robots"
authors:
- SabrinaNeuman
- RadhikaGhosal
- ThomasBourgeat
- admin
- VijayJanapaReddi
date: "2023-06-15T00:00:00Z"
doi: "10.1145/3579371.3589104"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2023 International Symposium on Computer Architecture (ISCA)](https://iscaconf.org/isca2023/)*
publication_short: In *ISCA 2023*

abstract: "A key challenge for hardware acceleration of robotics applications is the enormous diversity of possible deployment scenarios. To create efficient accelerators while minimizing non-recurring engineering costs, it is essential to identify high-level computational patterns that are prescribed by the physical characteristics of the deployed robot system and directly embed these domain-specific insights into the accelerator design process. To address this challenge, we present RoboShape, an accelerator framework that leverages two topology-based computational patterns that scale with robot size: (1) topology traversals, and (2) large topology-based matrices. Using these patterns and building on prior work, we expose opportunities to directly use robot topology to inform architectural mechanisms including task scheduling and allocation, data placement, block matrix operations, and sparse I/O data. Designing architectures according to topology-based patterns enables flexible, scalable, optimized accelerator deployment across the nonlinear design space of robot shape and computing resources. With this insight, we establish a systematic framework to generate accelerators, and use it to implement three accelerators for three different robots, achieving speedups over state-of-the-art CPU and GPU solutions. For the topologically-diverse iiwa manipulator, HyQ quadruped, and Baxter torso robots, RoboShape accelerators on an FPGA provide a 4.0x to 4.4x speedup in compute latency over CPU and a 8.0x to 15.1x speedup over GPU for the dynamics gradients, a key bottleneck preventing online execution of nonlinear optimal motion control for legged robots.Taking a broader view, for topology-based applications, RoboShape enables analysis of performance and resource utilization tradeoffs that will be critical to managing resources across accelerators in future full robotics domain-specific SoCs."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We present RoboShape, an accelerator framework that leverages two topology-based computational patterns that scale with robot size: (1) topology traversals, and (2) large topology-based matrices. Using these patterns and building on prior work, we expose opportunities to directly use robot topology to inform architectural mechanisms including task scheduling and allocation, data placement, block matrix operations, and sparse I/O data. For the topologically-diverse iiwa manipulator, HyQ quadruped, and Baxter torso robots, RoboShape accelerators on an FPGA provide a 4.0x to 4.4x speedup in compute latency over CPU and a 8.0x to 15.1x speedup over GPU for the dynamics gradients, a key bottleneck preventing online execution of nonlinear optimal motion control for legged robots. Taking a broader view, for topology-based applications, RoboShape enables analysis of performance and resource utilization tradeoffs that will be critical to managing resources across accelerators in future full robotics domain-specific SoCs."

tags:
- Hardware Acceleration
- Hardware-Software Co-Design
- FPGA
- Robotics
featured: true

links:
# - name: 'TBD'
#   url: ''
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3579371.3589104'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=cy4xcEYcp1o'

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

