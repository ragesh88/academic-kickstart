---

title: "Resilient Monitoring in Heterogeneous Multi-robot System through Network Reconfiguration"
authors:
- admin
- Pietro Pierpaoli
- Magnus Egerstedt
- Gaurav Sukhatme

date: "2020-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to IEEE Transactions on Robotics"
publication_short: Submitted to TRO

abstract: "We propose a framework for resilience in a networked heterogeneous multi-robot team subject to resource failures. Each robot in the team is equipped with resources that it shares with its neighbors. Additionally, each robot in the team executes a task, whose performance depends on the resources to which it has access. When a resource on a particular robot becomes unavailable (eg. a camera ceases to function), the team optimally reconfigures its communication network so that the robots affected by the failure can continue their tasks. We focus on a monitoring task, where robots individually estimate the state of an exogenous process. We encode the end-to-end effect of a robot's resource loss on the monitoring performance of the team by defining a new stronger notion of observability -- one-hop observability. By abstracting the impact that low-level individual resources have on the task performance through the notion of one-hop observability, our framework leads to the principled reconfiguration of information flow in the team to effectively replace the lost resource on one robot with information from another, as long as certain conditions are met. Network reconfiguration is converted to the problem of selecting edges to be modified in the system's communication graph after a resource failure has occurred. A controller based on finite-time convergence control barrier functions drives each robot to a spatial location that enables the communication links of the modified graph. We validate the effectiveness of our framework by deploying it on a team of differential-drive robots estimating the position of a group of quadrotors. "

# Summary. An optional shortened abstract.
summary: We propose a framework for resilience in a networked heterogeneous multi-robot team subject to resource failures. Each robot in the team is equipped with resources that it shares with its neighbors.

tags:
- Resilient multi-robot system

featured: False

links:
- name: Arxiv
  url: 'https://arxiv.org/abs/2008.01321'
url_pdf: 'files/papers/TRO_special_2020.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/aGsVBOeSg4E'

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
