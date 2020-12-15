---
title: "Exploration, Mapping and Scalar Field Estimation using a Swarm of Resource-Constrained Robots"
authors:
- admin
date: "2018-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Ph.D. Thesis, Arizona State University
publication_short:  Ph.D. Thesis, Arizona State University

abstract: Robotic swarms can potentially perform complicated tasks such as exploration and mapping at large space and time scales in a parallel and robust fashion. This thesis presents strategies for mapping environmental features of interest – specifically obstacles, collision-free paths, generating a metric map and estimating scalar density fields in an unknown domain using data obtained by a swarm of resource constrained robots. First, an approach was developed for mapping a single obstacle using a swarm of point-mass robots with both directed and random motion. The swarm population dynamics are modeled by a set of advection-diffusion-reaction partial differential equations (PDEs) in which a spatially-dependent indicator function marks the presence or absence of the obstacle in the domain. The indicator function is estimated by solving an optimization problem with PDEs as constraints. Second, a methodology for constructing a topological map of an unknown environment was proposed, which indicates collision-free paths for navigation, from data collected by a swarm of finite-sized robots. As an initial step, the number of topological features in the domain was quantified by applying tools from algebraic topology, to a probability function over the explored region that indicates the presence of obstacles. A topological map of the domain is then generated using a graph-based wave propagation algorithm. This approach is further extended, enabling the technique to construct a metric map of an unknown domain with obstacles using uncertain position data collected by a swarm of resource constrained robots, filtered using intensity measurements of an external signal. Next, a distributed method was developed to construct the occupancy grid map of an unknown environment using a swarm of inexpensive robots or mobile sensors with limited communication. In addition to this, an exploration strategy which combines information theoretic ideas with Levy walks was also proposed. Finally, the problem of reconstructing a two-dimensional scalar field using observations from a subset of a sensor network in which each node communicates its local measurements to its neighboring nodes was addressed. This problem reduces to estimating the initial condition of a large interconnected system with first-order linear dynamics, which can be solved as an optimization problem.

# Summary. An optional shortened abstract.
summary:

tags:
- Swarm mapping
featured: false

links:
- name: ASU
  url: 'https://repository.asu.edu/items/51727'
url_pdf: 'https://repository.asu.edu/attachments/211424/content/Ramachandran_asu_0010E_18506.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://ragesh88.github.io/Thesis_presentation/'
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
