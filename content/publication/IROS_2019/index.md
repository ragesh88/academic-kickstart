---
title: "Resilience by Reconfiguration: Exploiting Heterogeneity in Robot Teams"
authors:
- admin
- James A. Preiss
- Gaurav S. Sukhatme
date: "2019-10-01T00:00:00Z"
doi: "10.1109/IROS40897.2019.8968611"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In IEEE/RSJ International Conference on Intelligent Robots and Systems
publication_short: In IROS

abstract: We propose a method to maintain high resource availability in a networked heterogeneous multi-robot system subject to resource failures. In our model, resources such as sensing and computation are available on robots. The robots are engaged in a joint task using these pooled resources. When a resource on a particular robot becomes unavailable (e.g., a sensor ceases to function), the system automatically reconfigures so that the robot continues to have access to this resource by communicating with other robots. Specifically, we consider the problem of selecting edges to be modified in the system’s communication graph after a resource failure has occurred. We define a metric that allows us to characterize the quality of the resource distribution in the network represented by the communication graph. Upon a resource becoming unavailable due to failure, we reconFigure the network so that the resource distribution is brought as close to the maximal resource distribution as possible without a large change in the number of active inter-robot communication links. Our approach uses mixed integer semi-definite programming to achieve this goal. We employ a simulated annealing method to compute a spatial formation that satisfies the inter-robot distances imposed by the topology, along with other constraints. Our method can compute a communication topology, spatial formation, and formation change motion planning in a few seconds. We validate our method in simulation and real-robot experiments with a team of seven quadrotors.

# Summary. An optional shortened abstract.
summary: We propose a method to maintain high resource availability in a networked heterogeneous multi-robot system subject to resource failures.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://ieeexplore.ieee.org/document/8968611
url_pdf: http://robotics.usc.edu/publications/downloads/pub/1044/
url_code: ''
url_dataset: '#'
url_poster: '#'
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
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
