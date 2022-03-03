---
title: "Tripod: Towards a Scalable, Efficient and Resilient Cloud Gateway"
collection: publications
permalink: /publications/2019-03-JSAC-Tripod
excerpt: 'This paper is about implementing a scalable, efficient and resilient cloud gateway.'
date: 2019-03-01
venue: 'IEEE Journal on Selected Areas in Communications (JSAC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8635514'

citation: '<i>Menghao Zhang, Jun Bi, Kai Gao, Yi Qiao, <b>Guanyu Li</b>, Xiao Kong, Zhaogeng Li, Hongxin Hu. &quot;Tripod: Towards a Scalable, Efficient and Resilient Cloud Gateway&quot;. In IEEE Journal on Selected Areas in Communications (JSAC), 2019.</i>'

---
**Abstract:**  
Cloud gateways are fundamental components of a cloud platform, where various network functions (e.g., L4/L7 load balancing, network address translation, stateful firewall, and SYN proxy) are deployed to process millions of connections and billions of packets. Providing high-performance and failure-resilient packet processing with a scalable traffic management mechanism is crucial to ensuring the quality of service of a cloud provider, and hence is of great importance. Many network functions nowadays are implemented in software with commodity servers for low cost and high flexibility. However, existing software-based network function frameworks oftentimes provide part of these features, while cannot satisfy all three requirements above simultaneously. To address these issues, in this paper, we introduce TRIPOD, a novel network function framework specialized for cloud gateways. Having identified the fundamental limitations of loosely coupling traffic, processing logic and state, TRIPOD jointly manages these three elements with the unique characteristics of cloud gateways, which is enabled by a simple, efficient traffic processing mechanism, and a high performance state management service. Adopting several effective techniques and optimizations, TRIPOD is able to achieve scalable traffic management (&lt;100 flow rules for even Tbps traffic), high performance (reducing 40% of latency compared with state of the art) and failure resilience (similar packet/connection loss rate compared to state of the art), with reasonable overheads (less than 10% of the workload traffic) even under an extremely heavy traffic, making it a good fit for cloud gateways.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/abstract/document/8635514){:target="\_blank"}
