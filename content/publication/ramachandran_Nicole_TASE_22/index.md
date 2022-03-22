---

title: "Resilient Multi-Robot Multi-Target Tracking"
authors:
- admin
- Nicole Fronda
- James Priess
- Zhenghao Dai
- Gaurav Sukhatme

date: "2022-03-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Accepted to IEEE Transactions on Automation Science and Engineering (T-ASE)"
publication_short: Accepted to T-ASE 2022

abstract: "We address the problem of ensuring resource availability in a networked multi-robot system performing distributed target tracking. Specifically, we consider a multi-target tracking scenario where the targets are driven by exogenous inputs that are unknown to the robots performing the tracking task. Robots track the positions of targets using a form of the Distributed Kalman Filter (DKF). We use the trace of each robot’s sensor measurement noise covariance matrix as a measure of its sensing quality. When a robot’s sensing quality deteriorates, the team’scommunication graph is modified by adding edges such that the robot with deteriorating sensor quality may share information with other robots to improve the team’s target tracking ability. This computation is performed centrally and is designed to work without a large change in the number of active inter-robot communication links. Our method generates coordinates for the robots such the new communication graph can be realized in 3D. To achieve this, we propose two mixed integer semi-definite programming formulations, namely an ‘agent-centric’ strategy and a ‘team-centric’ strategy. We implement both formulations and a greedy, baseline strategy in simulation. Our simulation results show that the team-centric approach outperforms both agent-centric and greedy methods. Additionally, we show the effectiveness of our method in real-world settings through a multirobot experiment performed in real-time. "

# Summary. An optional shortened abstract.
summary: We address the problem of ensuring resource availability in a networked multi-robot system performing distributed target tracking.

tags:
- Resilient multi-robot system

featured: True

links:
url_pdf: 'files/papers/TASE_2022.pdf'
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



---
