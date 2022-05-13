---
title: Amina Amara PhD thesis defense
date: 2022-05-13T07:00:52.658Z
summary: " **Title:** A deep learning-based approach for anchor user modeling across online social networks under a big data environment. 


**Supervisors:** Mohamed BEN AOUICHA & Mohamed Ali HADJ TAEIB


**Defense Date:** 26 may 2022 "
draft: false
featured: false
authors:
  - admin
  - medali
tags:
  - Cross-social networks analytics
  - anchor user modeling
  - network representation learning
  - convolutional graph neural networks
  - big data
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
**Title:** A deep learning-based approach for anchor user modeling across online social networks under a big data environment. 

**Supervisors:** Mohamed BEN AOUICHA & Mohamed Ali HADJ TAEIB "

**Defense Date:** 26 may 2022

An accurate and comprehensive user modeling has been proven
  fundamental for many personalized social media-based services including link
  prediction and recommendation systems. A major challenge lies in that data
  available in a single online social network are usually very limited and
  sparse. Depending on the purpose for which an online social platform is
  designed, each platform offers only a partial view of a user from a particular
  perspective. Therefore, users are usually involved in several online social
  networks simultaneously to enjoy specific services provided by different
  networks, thus bringing about the interconnection of online social networks
  via bridge users called anchor users. Accordingly, a comprehensive anchor user
  modeling requires taking into account the user’s social data scattered through
  several social networking platforms. However, online social networks are
  completely isolated. In this respect, the present research work aims to build
  a holistic and comprehensive anchor user model from his data distributed over
  multiple social information sources and thus serve for enhancing the quality
  of personalized social media-based services. For this reason, we first study
  different aspects related to the target social networking platforms selected
  in this dissertation including covered functionalities, data heterogeneity,
  and data accessibility. The study reveals also that the major challenge
  towards anchor user modeling is linking user’s identities across online social
  networks. Moreover, recent trend to solve the user modeling problem is to
  leverage network embedding techniques and build embedding vectors
  corresponding to user nodes in the social network. Thereby, this thesis
  firstly presents a detailed survey of more recent network embedding based
  approaches. Then, the problem of anchor user identification across social
  platforms is addressed by providing a feature-based approach exploiting
  various similarity measures. Indeed, the proposed algorithm leverages the
  profile information (i.e. the user’s name) with the network properties (i.e.
  friendship network) to compute the matching degree between the two user’s
  identities pertaining to two different social networks and then the obtained
  result is compared to a predefined threshold value to decide whether the two
  profiles pertain to the same real person or not. Several similarity measures
  are tested including Jaccard Index, Hub Promoted Index, Hub Depressed Index,
  and Sørenson Index. Experimental results conducted on two real-world datasets,
  collected from Facebook and Twitter social networks, showed that the Jaccard
  Index outperforms all other measures with a threshold value δ = 0.03. In
  addition, as social networks stand as typical sources of big data, a BIGUI
  (BIG User Identification) architecture for anchor users storing and processing
  is designed. The provided architecture is built on the basis of a set of
  adequate technologies in conformity with the social big graph data pipeline to
  cope with online social network-associated big data challenges. Thereafter,
  the next step consists on building an anchor user model encoding diverse
  network structures of the given user, i.e. intra-network and cross-network
  features. In this regard, the OVRAU model (Overall low-dimensional Vector
  Representation for Anchor Users) is implemented to learn an overall
  low-dimensional representation for modeling anchor users, from a multiplex
  heterogeneous social network, by investigating the intra-network as well as
  cross-network structural information. Unlike existing works, the proposed
  model considers the multi-network scenarios to capture diverse network
  structures of anchor users. For this reason, OVRAU model includes two types of
  embeddings for each anchor user: one high-dimensional base embedding and a
  low-dimensional social edge embedding for each social network. In particular,
  the model learns a function that generates social edge embeddings by sampling
  and aggregating structural features from an anchor user's neighborhood inside
  different social networks, through one of three candidate functions of
  aggregation, namely mean aggregator, max-pooling aggregator, and LSTM
  aggregator, with self-attention mechanism. Link prediction is used as a
  downstream task to evaluate the effectiveness of the learned embeddings.
  Experiments have been conducted on real-world social networks dataset and the
  experimental results demonstrate that the proposed model with all three
  variants can significantly outperform the existing approaches of network
  representation learning when it is applied on link prediction task and also
  achieves better performance over all compared baselines. 