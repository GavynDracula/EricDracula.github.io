---
title: "Bolt: Scalable and Cost-Efficient Multistring Pattern Matching With Programmable Switches"
collection: publications
permalink: /publications/2022-09-TON-Bolt
excerpt: 'This paper designs high-performance multi-string pattern matching system with programmable switches'
date: 2022-09-04
venue: 'IEEE Transactions on Dependable and Secure Computing (TDSC)'
paperurl: 'https://ieeexplore.ieee.org/document/9875219'

citation: '<i>Shicheng Wang, Menghao Zhang, <b>Guanyu Li</b>, Chang Liu, Zhiliang Wang, Ying Liu, Mingwei Xu. &quot;Bolt: Scalable and Cost-Efficient Multistring Pattern Matching With Programmable Switches&quot;. In IEEE/ACM Transactions on Networking (TON), 2022.</i>'

cnrate: 'TON：CCF-A/TH-CPL-A，网络领域顶级期刊'

---
**Abstract:**  
Multi-string pattern matching is a crucial building block for many network security applications and thus of great importance. Since every byte of a packet has to be inspected by a large set of patterns, it often becomes a bottleneck of these applications and dominates the performance of an entire system. Many existing studies have been devoted to alleviating this performance bottleneck either by algorithm optimization or hardware acceleration. However, neither one provides the desired scalability and costs that keep pace with the drastic increase in network bandwidth and traffic today. To address these issues, in this paper, we present, a scalable and cost-efficient multi-string pattern matching system leveraging the capability of emerging programmable switches. combines the following techniques: (1) an efficient state encoding scheme to fit a large number of strings into the limited memory on a programmable switch; (2) a variable k-stride transition mechanism to increase the throughput significantly with the same level of memory cost; and (3) a compact pattern2rule mapping method to accommodate multiple co-existing strings in one rule. We implement a prototype of and make its source code publicly available. Extensive evaluations demonstrate that can provide multi-hundred Gbps throughput and scales well with various pattern sets and workloads.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/document/9875219){:target="\_blank"}
