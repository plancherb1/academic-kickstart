---
title: "pRRTC: GPU-Parallel RRT-Connect for Fast, Consistent, and Low-Cost Motion Planning"
authors:
- ChihHuang
- PranavJadhav
- admin
- ZacharyKingston
date: "2025-03-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: #In *[2025 International Conference on Intelligent Robots and Systems](http://www.iros25.org/)*
publication_short: #In *IROS 2025*

abstract: Sampling-based motion planning algorithms, like the Rapidly-Exploring Random Tree (RRT) and its widely used variant, RRT-Connect, provide efficient solutions for high-dimensional planning problems faced by real-world robots. However, these methods remain computationally intensive, particularly in complex environments that require many collision checks. As such, to improve performance, recent efforts have explored parallelizing specific components of RRT, such as collision checking or running multiple planners independently, but no prior work has integrated parallelism at multiple levels of the algorithm for robotic manipulation. In this work, we present pRRTC, a GPU-accelerated implementation of RRT-Connect that achieves parallelism across the entire algorithm through multithreaded expansion and connection, SIMT-optimized collision checking, and hierarchical parallelism optimization, improving efficiency, consistency, and initial solution cost. We evaluate the effectiveness of pRRTC on the MotionBenchMaker dataset using robots with 7, 8, and 14 degrees-of-freedom, demonstrating up to 6x average speedup on constrained reaching tasks at high collision checking resolution compared to state-of-the-art. pRRTC also demonstrates a 5x reduction in solution time variance and 1.5x improvement in initial path costs compared to state-of-the-art motion planners in complex environments across all robots.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: In this work, we present pRRTC, a GPU-accelerated implementation of RRT-Connect that achieves parallelism across the entire algorithm through multithreaded expansion and connection, SIMT-optimized collision checking, and hierarchical parallelism optimization, improving efficiency, consistency, and initial solution cost. We evaluate the effectiveness of pRRTC on the MotionBenchMaker dataset using robots with 7, 8, and 14 degrees-of-freedom, demonstrating up to 6x average speedup on constrained reaching tasks at high collision checking resolution compared to state-of-the-art. pRRTC also demonstrates a 5x reduction in solution time variance and 1.5x improvement in initial path costs compared to state-of-the-art motion planners in complex environments across all robots.

tags:
- Motion Planning
- Parallel Computing
- GPU
featured: false

links:
# - name: PDF
#   url: "https://arxiv.org/abs/2503.06757"
url_pdf: 'https://arxiv.org/abs/2503.06757'
url_code: 'https://github.com/CoMMALab/pRRTC'
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

