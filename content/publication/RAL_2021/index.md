---
title: "Adaptive and Risk-Aware Target Tracking with Heterogeneous Robot Teams"
authors:
- Siddharth Mayya
- admin
- Lifeng Zhou
- Vinay Senthil
- Dinesh Thakur
- Gaurav Sukhatme
- Vijay Kumar
date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Accepted to IEEE Robotics and Automation Letters 2022
publication_short: Accepted to IEEE RA-L 2022

abstract: We consider a scenario where a team of robots with heterogeneous sensors must track a set of hostile targets which induce sensory failures on the robots. In particular, the likelihood of failures depends on the proximity between the targets and the robots. We propose a control framework that implicitly addresses the competing objectives of performance maximization and sensor preservation (which impacts the future performance of the team).  Our framework consists of a predictive component---which accounts for the risk of being detected by the target, and a reactive component---which maximizes the performance of the team regardless of the failures that have already occurred. Based on a measure of the abundance of sensors in the team, our framework can generate aggressive and risk-averse robot configurations to track the targets. Crucially, the heterogeneous sensing capabilities of the robots are explicitly considered in each step, allowing for a more expressive risk-performance trade-off. Simulated experiments with induced sensor failures demonstrate the efficacy of the proposed approach.

# Summary. An optional shortened abstract.
summary: We consider a scenario where a team of robots with heterogeneous sensors must track a set of hostile targets which induce sensory failures on the robots.

tags:
- Resilient multi-robot system
featured: true

links:
url_pdf: ''
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Resilience

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
