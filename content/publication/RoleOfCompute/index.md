---
title: "The Role of Compute in Autonomous Aerial Vehicles"
authors:
- Behzad Boroujerdian
- Hasan Genc
- Srivatsan Krishnan
- Pieter Bardienus
- Bardienus Duisterhof
- admin
- Kayvan Mansoorshahi
- Marcelino Almeida
- Aleksandra Faust
- Vijay Janapa Reddi
date: "2019-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *[arXiv](https://arxiv.org/abs/1906.10513)*
publication_short: In *arXiv*

abstract: "Autonomous and mobile cyber-physical machines are becoming an inevitable part of our future. In particular, unmanned aerial vehicles have seen a resurgence in activity. With multiple use cases, such as surveillance, search and rescue, package delivery, and more, these unmanned aerial systems are on the cusp of demonstrating their full potential. Despite such promises, these systems face many challenges, one of the most prominent of which is their low endurance caused by their limited onboard energy. Since the success of a mission depends on whether the drone can finish it within such duration and before it runs out of battery, improving both the time and energy associated with the mission are of high importance. Such improvements have traditionally arrived at through the use of better algorithms. But our premise is that more powerful and efficient onboard compute can also address the problem. In this paper, we investigate how the compute subsystem, in a cyber-physical mobile machine, such as a Micro Aerial Vehicle (MAV), can impact mission time and energy. Specifically, we pose the question as 'what is the role of computing for cyber-physical mobile robots?' We show that compute and motion are tightly intertwined, and as such a close examination of cyber and physical processes and their impact on one another is necessary. We show different 'impact paths' through which compute impacts mission metrics and examine them using a combination of analytical models, simulation, micro and end-to-end benchmarking. To enable similar studies, we open sourced MAVBench, our tool-set, which consists of (1) a closed-loop real-time feedback simulator and (2) an end-to-end benchmark suite comprised of state-of-the-art kernels. By combining MAVBench, analytical modeling, and an understanding of various compute impacts, we show up to 2X and 1.8X improvements for mission time and mission energy for two optimization case studies. Our investigations, as well as our optimizations, show that cyber-physical co-design, a methodology with which both the cyber and physical processes/quantities of the robot are developed with consideration of one another, similar to hardware-software co-design, is necessary for arriving at the design of the optimal robot."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "By combining MAVBench (our tool-set, which consists of (1) a closed-loop real-time feedback simulator and (2) an end-to-end benchmark suite comprised of state-of-the-art kernels), analytical modeling, and an understanding of various compute impacts, we show up to 2X and 1.8X improvements for mission time and mission energy for two optimization case studies. Our investigations, as well as our optimizations, show that cyber-physical co-design, a methodology with which both the cyber and physical processes/quantities of the robot are developed with consideration of one another, similar to hardware-software co-design, is necessary for arriving at the design of the optimal robot."

tags:
- Cyber-Physical Systems
- Motion Planning
- MAV
- Compute
featured: false

links:
url_pdf: 'files/Role_Of_Compute.pdf'
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
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
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

