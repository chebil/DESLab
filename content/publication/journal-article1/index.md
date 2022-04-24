---
title: 'Cross-network representation learning for anchor users on multiplex heterogeneous social network'
authors:
  - admin
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2022-01-25T00:00:00Z'
doi: 'https://doi.org/10.1016/j.asoc.2022.108461'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-25T00:00:00ZZ'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: Online users are typically involved in multiple online social networks simultaneously to enjoy a variety of social network services, thus bringing about the interconnection of online social networks via bridge users called anchor users. Anchor users can be beneficial to a wide range of social network analysis applications such as cross-domain system recommendation, cross-network information diffusion, and link prediction, taking anchor user’s intra-network structural information along with its cross-network structural properties into consideration. Several studies have so far tried to learn low-dimensional representations of social users by capturing their network structures inside one social network but they have not fully leveraged their intra-network structures with their cross-network structures to boost the performance of the aforementioned analysis tasks. In this paper, we present a novel deep learning model to learn Overall low-dimensional Vector Representations for Anchor Users (OVRAU), from a multiplex heterogeneous social network by investigating the intra-network as well as the cross-network structural information. Unlike previous works, our proposed model considers the multi-network scenario to encode diverse network structures of anchor users. We propose two types of embeddings to capture the different structural information of an anchor user from multiple social networks a high-dimensional base embedding and a low-dimensional social edge embedding for each social network. In particular, we learn a function that generates social edge embeddings by sampling and aggregating structural features from an anchor user’s neighborhood inside different social networks through one of three candidate aggregator functions namely mean, max-pooling and LSTM, with a self-attention mechanism. Link prediction is used as a downstream task to evaluate the effectiveness of the learned embeddings. Experiments were conducted on real-world social networks dataset, and the results demonstrate that our proposed model involving all the three variants can significantly outperform the existing network representation learning approaches when applied on the link prediction task and also achieve better performance over all compared baselines.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Cross-social networks analysis
  - Anchor users
  - Network representation learning
  - Graph neural networks
  - Link prediction
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
