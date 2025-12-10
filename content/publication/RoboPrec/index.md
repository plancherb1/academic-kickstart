---
title: "RoboPrec: Enabling Reliable Embedded Computing for Robotics by Providing Accuracy Guarantees Across Mixed-Precision Datatypes"
authors:
- AlpYilmaz
- ThomasBourgeat
- LillianPentecost
- admin
- SabrinaNeuman
date: "2025-12-09T00:00:00Z"
doi: "10.1109/LRA.2025.3641090"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *[Robotics and Automation Letters](https://www.ieee-ras.org/publications/ra-l)* 2025
publication_short: In *RA-L* 2025

abstract: "Mobile robots demand power efficiency as well as accuracy and high performance in their computations. Embedded microcontrollers and FPGAs can consume as much as 1000x less power than large CPUs and GPUs, however, these power-efficient platforms often lack full floating-point support and rely on fixed-point computations to deliver performance. This is a challenge as most robotics software uses floating-point datatypes (double, float) to conservatively ensure accuracy, and prior works that use fixed-point types employ unreliable ad hoc approaches to select the datatype precision (i.e., quantity and allocation of bits). We address this challenge with the RoboPrec framework, where we: (i) develop a transpiler that integrates code transformations and robot-specific code generation with traditional numerical stability analysis methods (which calculate error bounds), and adapts them to be practical for robotics software; and then leverage this to (ii) generate guaranteed-accuracy fixed-point code that is deployable to embedded computing platforms. We use rigid body dynamics, a fundamental robotics workload, as a motivating case study. We find that RoboPrec-generated 32-bit fixed-point code can be up to 8x faster than float and 122x faster than double on embedded processors while, critically, also providing guaranteed accuracy bounds with lower worst-case error than float."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce the RoboPrec framework, where we: (i) develop a transpiler that integrates code transformations and robot-specific code generation with traditional numerical stability analysis methods (which calculate error bounds), and adapts them to be practical for robotics software; and then leverage this to (ii) generate guaranteed-accuracy fixed-point code that is deployable to embedded computing platforms. We use rigid body dynamics, a fundamental robotics workload, as a motivating case study. We find that RoboPrec-generated 32-bit fixed-point code can be up to 8x faster than float and 122x faster than double on embedded processors while, critically, also providing guaranteed accuracy bounds with lower worst-case error than float."

tags:
- Numerical Stability
- Mixed Precision
- Transpiler

featured: false

links:
#- name: TBD
#  url: TBD
url_pdf: ''
url_code: 'https://github.com/robomorphic/roboprec'
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

