---

title: "Information Correlated Lévy Walk Exploration and Distributed Mapping Using a Swarm of Robots"
authors:
- admin
- Zahi Kakish
- Spring Berman

date: "2020-04-01T00:00:00Z"
doi: "10.1109/TRO.2020.2991612"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Robotics 2020"
publication_short: In TRO 2020

abstract: "In this article, we present a novel distributed method for constructing an occupancy grid map of an unknown environment using a swarm of robots with global localization capabilities and limited inter-robot communication. The robots explore the domain by performing Lévy walks in which their headings are defined by maximizing the mutual information between the robot’s estimate of its environment in the form of an occupancy grid map and the distance measurements that it is likely to obtain when it moves in that direction. Each robot is equipped with laser range sensors, and it builds its occupancy grid map by repeatedly combining its own distance measurements with map information that is broadcast by neighboring robots. Using results on average consensus over time-varying graph topologies, we prove that all robots’ maps will eventually converge to the actual map of the environment. In addition, we demonstrate that a technique based on topological data analysis, developed in our previous work for generating topological maps, can be readily extended for adaptive thresholding of occupancy grid maps. We validate the effectiveness of our distributed exploration and mapping strategy through a series of two-dimensional simulations and multi-robot experiments."

# Summary. An optional shortened abstract.
summary: We present a novel distributed method for constructing an occupancy grid map of an unknown environment using a swarm of robots with global localization capabilities and limited inter-robot communication.

tags:
- multi-robot system mapping

featured: true

links:
- name: IEEE
  url: 'https://ieeexplore.ieee.org/document/9115083'
- name: Arxiv
  url: 'https://arxiv.org/abs/1903.04836'
url_pdf: 'files/papers/TRO_ACS_2020.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=MkLFXSsG_TY&t=1s'

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
- Swarm

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---



---
