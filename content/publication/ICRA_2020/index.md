---
title: "Resilience in multi-robot target tracking through reconfiguration"
authors:
- admin
- Nicole Fronda
- Gaurav Sukhatme
date: "2019-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the proceedings of International Conference on Robotics and Automation 2020
publication_short: In ICRA 2020

abstract: "We address the problem of maintaining resource availability in a networked multi-robot system performing distributed target tracking. In our model, robots are equipped with sensing and computational resources enabling them to track a target’s position using a Distributed Kalman Filter (DKF). We use the trace of each robot’s sensor measurement noise covariance matrix as a measure of sensing quality. When a robot’s sensing quality deteriorates, the systems communication graph is modified by adding edges such that the robot with deteriorating sensor quality may share information with other robots to improve the team’s target tracking ability. This computation is performed centrally and is designed to work without a large change in the number of active communication links. We propose two mixed integer semi-definite programming formulations (an ‘agent-centric’ strategy and a ‘team-centric’ strategy) to achieve this goal. We implement both formulations and a greedy strategy in simulation and show that the team centric strategy outperforms the agent-centric and greedy strategies."

# Summary. An optional shortened abstract.
summary: "We address the problem of maintaining resource availability in a networked multi-robot system performing distributed target tracking"

tags:
- Resilient multi-robot system
featured: true

links:
- name: Arxiv
  url: https://arxiv.org/abs/1910.01300
- name: IEEE
  url: 'https://ieeexplore.ieee.org/document/9196961'
url_pdf: 'files/papers/ICRA2020.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/Nhu9-ABUNAw'

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
