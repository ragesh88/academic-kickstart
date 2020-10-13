---
title: "An Optimal Control Approach to Mapping GPS-Denied Environments using a Stochastic Robotic Swarm"
authors:
- admin
- Karthik Elamvazhuthi
- Spring Berman

date: "2018-01-01T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-319-51532-8_29"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "In the proceedings of International Symposium on Robotics Research"
publication_short: In ISRR 2015

abstract: This paper presents an approach to mapping a region of interest using observations from a robotic swarm without localization. The robots have local sensing capabilities and no communication, and they exhibit stochasticity in their motion.We model the swarm population dynamics with a set of advection-diffusion-reaction partial differential equations (PDEs). The map of the environment is incorporated into this model using a spatially-dependent indicator function that marks the presence or absence of the region of interest throughout the domain. To estimate this indicator function, we define it as the solution of an optimization problem in which we minimize an objective functional that is based on temporal robot data. The optimization is performed numerically offline using a standard gradient descent algorithm.Simulations show that our approach can produce fairly accurate estimates of the positions and geometries of different types of regions in an unknown environment.

# Summary. An optional shortened abstract.
summary: We present an approach to mapping a region of interest using observations from a robotic swarm without localization. The robots have local sensing capabilities and no communication, and they exhibit stochasticity in their motion.

tags:
- Swarm mapping

featured: true

links:
- name: Springer
  url: https://link.springer.com/chapter/10.1007/978-3-319-51532-8_29
url_pdf: 'files/papers/ISRR2018.pdf'
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
