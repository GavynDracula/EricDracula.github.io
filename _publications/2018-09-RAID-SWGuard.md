---
title: "Control Plane Reflection Attacks in SDNs: New Attacks and Countermeasures"
collection: publications
permalink: /publication/2018-09-RAID-SWGuard
excerpt: 'This paper is about novel attacks targeting SDN.'
date: 2018-09-12
venue: 'International Symposium on Research in Attacks, Intrusions and Defenses (RAID)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-00470-5_8'

citation: '<i>Menghao Zhang, <b>Guanyu Li</b>, Lei Xu, Jun Bi, Guofei Gu, and Jiasong Bai. &quot;Control Plane Reflection Attacks in SDNs: New Attacks and Countermeasures&quot;. In the 21st International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2018), Heraklion, Crete, Greece, September 10-12, 2018.</i>'

---
***Abstract***
Software-Defined Networking (SDN) continues to be deployed spanning from enterprise data centers to cloud computing with emerging of various SDN-enabled hardware switches. In this paper, we present Control Plane Reflection Attacks to exploit the limited processing capability of SDN-enabled hardware switches. The reflection attacks adopt direct and indirect data plane events to force the control plane to issue massive expensive control messages towards SDN switches. Moreover, we propose a two-phase probing-triggering attack strategy to make the reflection attacks much more efficient, stealthy and powerful. Experiments on a testbed with physical OpenFlow switches demonstrate that the attacks can lead to catastrophic results such as hurting establishment of new flows and even disruption of connections between SDN controller and switches. To mitigate such attacks, we propose a novel defense framework called SWGuard. In particular, SWGuard detects anomalies of downlink messages and prioritizes these messages based on a novel monitoring granularity, i.e., host-application pair (HAP). Implementations and evaluations demonstrate that SWGuard can effectively reduce the latency for legitimate hosts and applications under Control Plane Reflection Attacks with only minor overheads.

[Read or download the complete paper here](https://link.springer.com/chapter/10.1007/978-3-030-00470-5_8){:target="\_blank"}
