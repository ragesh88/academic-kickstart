---

title: "A Probabilistic Approach to Automated Construction of Topological Maps using a Stochastic Robotic Swarm"
authors:
- admin
- Sean Wilson
- Spring Berman

date: "2017-04-01T00:00:00Z"
doi: "10.1109/LRA.2016.2647641"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters 2017"
publication_short: In RAL 2017

abstract: In this paper, we present a novel procedure for constructing a topological map of an unknown environment from data collected by a swarm of robots with limited sensing capabilities and no communication or global localization. Topological maps are sparse roadmap representations of environments that can be used to identify collision-free trajectories for robots to navigate through a domain. Our method uses uncertain position data obtained by robots during the course of random exploration to construct a probability function over the explored region that indicates the presence of obstacles. Techniques from topological data analysis, in particular the concept of persistent homology, are applied to the probability map to segment the obstacle regions. Finally, a graph-based wave propagation algorithm is applied to the obstacle-free region to construct the topological map of the domain in the form of an approximate generalized Voronoi diagram. We demonstrate the effectiveness of our approach in a variety of simulated domains and in multirobot experiments on a domain with two obstacles.

# Summary. An optional shortened abstract.
summary: We present a novel procedure for constructing a topological map of an unknown environment from data collected by a swarm of robots with limited sensing capabilities and no communication or global localization.

tags:
- multi-robot system mapping

featured: false

links:
- name: IEEE
  url: 'https://ieeexplore.ieee.org/document/7805135'
url_pdf: 'files/papers/RAL2016.pdf'
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
- Swarm

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---



---
