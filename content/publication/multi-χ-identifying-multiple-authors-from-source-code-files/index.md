---
title: "Multi-χ: Identifying Multiple Authors from Source Code Files"
publication_types:
  - "2"
authors:
  - Mohammed Abuhamad
  - Tamer Abuhmed
  - DaeHun Nyang
  - David Mohaisen
date: "2020-07-01T00:00:00Z"
doi: 10.2478/popets-2020-0044
publication: "Proceedings on Privacy Enhancing Technologies 2020 (3), 25-41"
abstract: Most authorship identification schemes assume that code samples are written by a single author. However, real software projects are typically the result of a team effort, making it essential to consider a finegrained multi-author identification in a single code sample, which we address with Multi-χ. Multi-χ leverages a deep learning-based approach for multi-author identification in source code, is lightweight, uses a compact representation for efficiency, and does not require any code parsing, syntax tree extraction, nor feature selection. In Multi-χ, code samples are divided into small segments, which are then represented as a sequence of n-dimensional term representations. The sequence is fed into an RNN-based verification model to assist a segment integration process which integrates positively verified segments, ie, integrates segments that have a high probability of being written by one author. Finally, the resulting segments from the integration process are represented using word2vec or TF-IDF and fed into the identification model. We evaluate Multi-χ with several Github projects (Caffe, Facebook’s Folly, Tensor-Flow, etc.) and show remarkable accuracy. For example, Multi-χ achieves an authorship example-based accuracy (A-EBA) of 86.41% and per-segment authorship identification of 93.18% for identifying 562 programmers. We examine the performance against multiple dimensions and design choices, and demonstrate its effectiveness.
draft: false
featured: false
url_pdf: https://infolab.skku.edu/publication/popets-2020-0044.pdf
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-04-29T04:29:41.350Z
---
