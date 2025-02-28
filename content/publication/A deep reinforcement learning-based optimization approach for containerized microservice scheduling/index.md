---
title: 'A deep reinforcement learning-based optimization approach for containerized microservice scheduling in Hybrid Fog/Cloud environments'
authors:
  - ameni-kallel-chaari
  - rekik
  - mahdi-khemakhem
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2025-02-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.engappai.2024.109745'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: 
  - article-journal

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: The deployment of microservices in Hybrid Fog/Cloud (HFC) environments for Internet of Things (IoT) applications presents a significant challenge in efficiently scheduling containerized services across distributed resources. While existing studies have explored microservice scheduling, a comprehensive approach that considers resource constraints, workflow dependencies, and dynamic hybrid environments remains elusive. This paper introduces a novel Deep Reinforcement Learning-based Algorithm (DRLA) for containerized microservice scheduling in HFC environments. DRLA utilizes a multi-constrained Binary Quadratic Program (BQP) model to optimize execution time, resource consumption, and occupancy rates while considering microservice dependencies and resource capabilities. The algorithm leverages two Deep Reinforcement Learning (DRL) agents, DQN and REINFORCE, to learn and adapt to the dynamic nature of the HFC federation. Experimental evaluations using five real-world Business Process (BP) use cases demonstrate that DRLA outperforms existing scheduling approaches such as default Kubernetes, Reward Sharing Deep Q-Learning (RSDQL), and Deep Reinforcement Learning (DRL) schedulers. Compared to existing schedulers, ours delivers optimal or near-optimal solutions, demonstrating significant improvements in key performance values. Indeed, DRLA achieves average optimality gaps of just 0.16% and 0.21%, significantly outperforming the Kubernetes scheduler, which exhibits a gap of 2.88%. It is worth noting that other similar algorithms see a far higher increase in optimality gaps. This highlights DRLA’s excellent performance and ability to schedule containerized microservices in hybrid fog/cloud environments, resulting in near-optimal solutions for a variety of use cases.

# Summary. An optional shortened abstract.
# summary: 

tags:
  - Hybrid Fog/Cloud environment
  - Containerized microservices problem
  - Scheduling model
  - Multi-objective optimization
  - Deep reinforce learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:
---

<!-- # {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
