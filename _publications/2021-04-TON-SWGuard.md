---
title: "Control Plane Reflection Attacks and Defenses in Software-Defined Networks"
collection: publications
permalink: /publications/2021-04-TON-SWGuard
excerpt: 'This paper is about novel attacks targeting SDN.'
date: 2021-04-01
venue: 'IEEE/ACM Transactions on Networking (TON)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9288943'

citation: '<i>Menghao Zhang, <b>Guanyu Li</b>, Lei Xu, Jiasong Bai, Mingwei Xu, Guofei Gu, Jianping Wu. &quot;Control Plane Reflection Attacks and Defenses in Software-Defined Networks&quot;. In IEEE/ACM Transactions on Networking (TON), 2021.</i>'

---
**Abstract:**  
Software-Defined Networking (SDN) continues to be deployed spanning from enterprise data centers to cloud computing with the proliferation of various SDN-enabled hardware switches and dynamic control plane applications. However, state-of-the-art SDN-enabled hardware switches have rather limited downlink message processing capability, especially for Flow-Mod and Statistic Query , which may not suffice the huge need of dynamic control plane applications. In this paper, we systematically study the interactions between the control plane applications and the data plane switches, and present two new attacks, namely Control Plane Reflection Attacks, to exploit the limited processing capability of SDN-enabled hardware switches. The reflection attacks adopt direct and indirect data plane events to force the control plane to issue massive expensive downlink messages towards SDN switches. Moreover, we propose a two-phase probing-triggering attack strategy, which makes the reflection attacks much more efficient and powerful. Experiments on a testbed with 3 different physical OpenFlow switches demonstrate that the attacks can lead to catastrophic results such as hurting the establishment of new flows and even disruption of connection between SDN controller and switches. To mitigate such attacks, we present several countermeasures from different perspectives. In particular, we propose a novel, systematical defense framework, SwitchGuard, to detect anomalies of downlink messages and prioritize these messages based on a novel monitoring granularity, i.e., host-application pair (HAP). Implementations and evaluations demonstrate that SwitchGuard can effectively reduce the latency for legitimate hosts and applications under the control plane reflection attacks with only minor overheads.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/abstract/document/9288943){:target="\_blank"}
