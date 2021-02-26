---
title: "Resilience in multi-robot multi-target tracking with unknown number of targets through reconfiguration"
authors:
- admin
- Nicole Fronda
- Gaurav Sukhatme
date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Control of Network Systems 2020
publication_short: TCNS 2020

abstract: "We address the problem of maintaining resource availability in a networked multi-robot team performing distributed tracking of unknown number of targets in an environment of interest. Based on our model, robots are equipped with sensing and computational resources enabling them to cooperatively track a set of targets in an environment using a distributed Probability Hypothesis Density (PHD) filter. We use the trace of a robot's sensor measurement noise covariance matrix to quantify its sensing quality. While executing the tracking task, if a robot experiences sensor quality degradation, then robot team's communication network is reconfigured such that the robot with the faulty sensor may share information with other robots to improve the team's target tracking ability without enforcing a large change in the number of active communication links. A central system which monitors the team executes all the network reconfiguration computations. We consider two different PHD fusion methods in this paper and propose four different Mixed Integer Semi-Definite Programming (MISDP) formulations (two formulations for each PHD fusion method) to accomplish our objective. All four MISDP formulations are validated in simulation."

# Summary. An optional shortened abstract.
summary: "We address the problem of maintaining resource availability in a networked multi-robot team performing distributed tracking of unknown number of targets in an environment of interest."

tags:
- Resilient multi-robot system
featured: true

links:
- name: Arxiv
  url: 'https://arxiv.org/abs/2004.07197'
url_pdf: 'files/papers/TCNS_2020.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
