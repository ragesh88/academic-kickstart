---
title: "Resilient Coverage: Exploring the Local-to-Global Trade-off"
authors:
- admin
- Lifeng Zhou
- James A. Preiss
- Gaurav S. Sukhatme
date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In IEEE/RSJ International Conference on Intelligent Robots and Systems
publication_short: In IROS

abstract: We propose a centralized control framework to select suitable robots from a heterogeneous pool and place them at appropriate locations to monitor a region for events of interest. In the event of a robot failure, the framework repositions robots in a user-defined local neighborhood of the failed robot to compensate for the coverage loss. The central controller augments the team with additional robots from the robot pool when simply repositioning robots fails to attain a user-specified level of desired coverage. The size of the local neighborhood around the failed robot and the desired coverage over the region are two objectives that can be manipulated to achieve a user-specified balance. We investigate the trade-off between the coverage compensation achieved through local repositioning and the computation required to plan the new robot locations. We also study the relationship between the size of the local neighborhood and the number of additional robots added to the team for a given user-specified level of desired coverage. We use extensive simulations and an experiment with a team of seven quadrotors to verify the effectiveness of our framework. Additionally, we show that to reach a high level of coverage in a neighborhood with a large robot population, it is more efficient to enlarge the neighborhood size, instead of adding additional robots and repositioning them.

# Summary. An optional shortened abstract.
summary: We propose a centralized control framework to select suitable robots from a heterogeneous pool and place them at appropriate locations to monitor a region for events of interest

tags:
- Resilient multi-robot system
featured: true

links:
- name: ArXiv
  url: https://arxiv.org/pdf/1910.01917
url_pdf:
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
