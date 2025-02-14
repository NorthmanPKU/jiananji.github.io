---
title: "Chainedfilter: Combining membership filters by chain rule"
collection: publications
category: conferences
header:
    teaser: "JJN.png"
permalink: /publication/chainedfilter
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-12-12
venue: 'SIGMOD'
paperurl: 'https://yangtonghome.github.io/uploads/DaVinci_icde_final.pdf'
citation: 'Haoyu Li, Liuhui Wang, Qizhi Chen, Jianan Ji, Yuhan Wu, Yikai Zhao, Tong Yang, Aditya Akella'

---
Membership (membership query/membership testing) is a fundamental problem across databases, networks and security. However, previous research has primarily focused on either approximate solutions, such as Bloom Filters, or exact methods, like perfect hashing and dictionaries, without attempting to develop an integral theory. In this paper, we propose a unified and complete theory, namely chain rule, for general membership problems, which encompasses both approximate and exact membership as extreme cases. Building upon the chain rule, we introduce a straightforward yet versatile algorithm framework, namely ChainedFilter, to combine different elementary filters without losing information. Our evaluation results demonstrate that ChainedFilter improves performance of many applications including static dictionary, lossless data compression, Cuckoo Hashing, LSM-Tree and Learned Filters.