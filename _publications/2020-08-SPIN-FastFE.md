---
title: "FastFE: Accelerating ML-based Traffic Analysis with Programmable Switches"
collection: publications
permalink: /publications/2020-08-SPIN-FastFE
excerpt: 'This paper propose a feature extracting system accelerated with programmable switches'
date: 2020-08-10
venue: 'ACM SIGCOMM Workshop on Secure Programmable Network Infrastructure (SPIN)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3405669.3405818'

citation: '<i>Jiasong Bai, Menghao Zhang, <b>Guanyu Li</b>, Chang Liu, Mingwei Xu, Hongxin Hu. &quot;FastFE: Accelerating ML-based Traffic Analysis with Programmable Switches&quot;. In The 1st ACM SIGCOMM Workshop on Secure Programmable Network Infrastructure (SPIN ''20), August 14, 2020, Virtual Event, NY, USA.</i>'

---
**Abstract:**  
Modern traffic analysis applications are usually designed to identify malicious behaviors by inferring sensitive information with machine learning (ML) techniques from network traffic, and they are of great importance to security with the growing use of encryption and other evasion techniques that make classic content-based analysis infeasible. However, with the soaring throughput of networks reaching hundreds of Gbps, it becomes more and more challenging for traffic analysis applications to keep up with today's high-speed large-volume network traffic. In particular, existing feature extractor components in traffic analysis are suffering from undesirable communications, storage, and computation bottleneck. To this end, this paper presents FastFE, a high-speed feature extractor that leverages the capability of new-generation programmable switches to generate desired traffic features flexibly and efficiently. We provide a set of general, easy-to-use, and expressive interfaces for operators to express which traic features they desire, and a policy enforcement engine that can effectively translate these policies into underlying primitives in programmable switches and commodity servers. Our case study on a state-of-the-art ML-based traffic analysis application, Kitsune, demonstrates the significant advancement of FastFE and its low overheads. As an ongoing work, we are working on a full prototype design and implementation, and hope FastFE can serve as a crucial build block for future ML-based traffic analysis applications.

**Paper URL:**  
[Read or download the complete paper here](https://dl.acm.org/doi/abs/10.1145/3405669.3405818){:target="\_blank"}
