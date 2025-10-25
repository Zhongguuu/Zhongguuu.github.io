---
title:          "THEMIS: Addressing Congestion-Induced Unfairness in Long-Haul RDMA Networks"
date:           2025-09-22 00:00:00 +0800
selected:       false
pub:            "2025 lEEE 33rd International Conference on Network Protocols (ICNP)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  RDMA is promising for enhancing the performance of cross-datacenter (DC) services. However, deploying RDMA over wide-area networks introduces severe congestion control unfairness, primarily due to asymmetric congestion feedback delays between inter-DC flows and intra-DC flows. As a result, intra-DC flows often bear the full burden of congestion response, leading to drastically increased flow completion times (FCT). In this work, we identify two key forms of unfairness — nearsource and near-destination — depending on whether congestion occurs near the sender or receiver of inter-DC flows. Based on this, we propose THEMIS, a fairness maintenance patch for long-haul RDMA networks. To mitigate near-source unfairness, THEMIS devises a Proactive Notification Point to shorten the congestion feedback loop within a single DC. To alleviate neardestination unfairness, THEMIS introduces a Temporary Reaction Point to temporarily slow down the target inter-DC flow until the sender receives the corresponding congestion feedback. We implement an open-source prototype of THEMIS, and evaluate it on both real-world testbed and large-scale simulations. Compared to DCQCN, Annulus and BiCC, THEMIS reduces the intra-DC FCT by up to 79.2%, 63.6% and 55.6%, and decreases overall FCT by up to 61.2%, 31.9% and 59.5% respectively.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Zihan Niu 
  - Menghao Zhang#
  - Jue Zhang
  - Renjie Xie
  - Yuan Yang
  - Xiaohe Hu
links:
  Paper: https://ieeexplore.ieee.org/document/11192376
  Code: https://github.com/luost26/bubble-visual-hash

---
