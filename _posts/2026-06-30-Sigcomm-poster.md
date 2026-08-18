---
title:  "AI/ML Workload Monitoring accepted at SIGCOMM 2026 Poster."
search: true
author_profile: true
classes: wide
---

Our Poster titled *" Beyond Probabilistic Data Structures for AI/ML Workload Monitoring "* will be presented at the poster session in SIGCOMM 2026

Congrats to the team, especially Davide Palmiotti.

*Abstract:* The massive scale of Large Language Model (LLM) training requires tracking complex network flows across thousands of GPUs. Modern GPU communication uses aggressive multipath strategies, such as packet spraying, which drastically increases the volume of concurrent flow states. Existing telemetry solutions rely on probabilistic data structures that inherently suffer from hash collisions. To achieve the critical 99-100% accuracy required by AI workloads, these traditional methods must heavily over-provision memory, often demanding 5x to 13x more memory than the theoretical ideal. This severe overhead rapidly exhausts the limited data-plane memory available within modern switch ASICs.  

Because AI/ML training iterations generate highly deterministic and repetitive traffic, the authors propose replacing probabilistic structures with Perfect Hash Functions (PHFs). Prior to the training job, a flow estimator is used to predict the exact set of flows that will traverse a given switch. A custom Perfect Hash Function, denoted as $h(k)$, then maps every flow key to a distinct memory bucket. This architecture eliminates hash collisions entirely, ensuring deterministic 100% measurement accuracy. Furthermore, the memory overhead required to store the PHF within the switch is minimal, needing only about 3 bits per flow