---
title: "Making Multi-String Pattern Matching Scalable and Cost-Efficient with Programmable Switching ASICs"
collection: publications
permalink: /publications/2021-05-INFOCOM-Bolt
excerpt: 'This paper propose a multi-string pattern matching algorithm based on programmable switches'
date: 2021-05-14
venue: 'IEEE International Conference on Computer Communications (INFOCOM)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9488796'

citation: '<i>Shicheng Wang, Menghao Zhang, <b>Guanyu Li</b>, Chang Liu, Ying Liu, Xuya Jia, Mingwei Xu. &quot;Making Multi-String Pattern Matching Scalable and Cost-Efficient with Programmable Switching ASICs&quot;. In The 40th IEEE International Conference on Computer Communications (INFOCOM ''21), May 10-13, 2021, Virtual Event, Canada.</i>'

cnrate: 'INFOCOM：CCF-A/TH-CPL-A，网络领域重要会议'

---
**Abstract:**  
Multi-string pattern matching is a crucial building block for many network security applications, and thus of great importance. Since every byte of a packet has to be inspected by a large set of patterns, it often becomes a bottleneck of these applications and dominates the performance of an entire system. Many existing works have been devoted to alleviate this performance bottleneck either by algorithm optimization or hardware acceleration. However, neither one provides the desired scalability and costs that keep pace with the drastic increase of the network bandwidth and network traffic today. In this paper, we present BOLT, a scalable and cost-efficient multi-string pattern matching system leveraging the capability of emerging programmable switches. BOLT combines the following two techniques, a smart state encoding scheme to fit a large number of strings into the limited memory on the programmable switch, and a variable k-stride transition mechanism to increase the throughput significantly with the same level of memory costs. We implement a prototype of BOLT and make its source code publicly available. Extensive evaluations demonstrate that BOLT could provide orders of magnitude improvement in throughput which is scalable with pattern sets and workloads, and could also significantly decrease the number of entries and memory requirement.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/abstract/document/9488796){:target="\_blank"}
