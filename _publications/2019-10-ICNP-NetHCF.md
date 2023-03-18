---
title: "NetHCF: Enabling Line-rate and Adaptive Spoofed IP Traffic Filtering"
collection: publications
permalink: /publications/2019-10-ICNP-NetHCF
excerpt: 'This paper is about utilizing programmable data planes to filter spoofed IP traffic.'
date: 2019-10-10
venue: 'IEEE International Conference on Network Protocols (ICNP)'
paperurl: 'https://ieeexplore.ieee.org/document/8888057'

citation: '<i><b>Guanyu Li</b>, Menghao Zhang, Chang Liu, Xiao Kong, Ang Chen, Guofei Gu, Haixin Duan. &quot;NetHCF: Enabling Line-rate and Adaptive Spoofed IP Traffic Filtering&quot;. In The 27th IEEE International Conference on Network Protocols (ICNP ''19), Chicago, IL, USA, October 7-10, 2019.</i>'

cnrate: 'ICNP：CCF-B/TH-CPL-A，网络领域重要会议'

---
**Abstract:**  
In this paper, we design NETHCF, a line-rate in-network system for filtering spoofed traffic. NETHCF leverages the opportunity provided by programmable switches to design a novel defense against spoofed IP traffic, and it is highly efficient and adaptive. One key challenge stems from the restrictions of the computational model and memory resources of programmable switches. We address this by decomposing the HCF system into two complementary components—one component for the data plane and another for the control plane. We also aggregate the IP-to-Hop-Count (IP2HC) mapping table for efficient memory usage, and design adaptive mechanisms to handle end-to-end routing changes, IP popularity changes, and network activity dynamics. We have built a prototype on a hardware Tofino switch, and our evaluation demonstrates that NETHCF can achieve line-rate and adaptive traffic filtering with low overheads.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/document/8888057){:target="\_blank"}
