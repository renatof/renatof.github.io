---
title: "On the Design and Implementation of IP-over-P2P Overlay Virtual Private Networks"
collection: publications
permalink: /publication/ieice2020
excerpt: 'This paper describes the evolution of IP-over-P2P VPN overlays'
date: 2020-01-01
venue: 'IEICE Transactions on Communications'
paperurl: 'https://search.ieice.org/bin/pdf_link.php?category=B&lang=E&year=2020&fname=e103-b_1_2&abst='
citation: 'K. Subratie, S. Aditya, V. Daneshmand, K. Ichikawa, and R. Figueiredo, “On the Design and Implementation of IP-over-P2P Overlay Virtual Private Networks”, IEICE Transactions, Vol., No.: Vol.E103-B, No.1, pp.2-10, 2020'
---

The success and scale of the Internet and its protocol IP has spurred emergent distributed technologies such as fog/edge computing and new application models based on distributed containerized microservices. The Internet of Things and Connected Communities are poised to build on these technologies and models and to benefit from the ability to communicate in a peer-to-peer (P2P) fashion. Ubiquitous sensing, actuating and computing implies a scale that breaks the centralized cloud computing model. Challenges stemming from limited IPv4 public addresses, the need for transport layer authentication, confidentiality and integrity become a burden on developing new middleware and applications designed for the network’s edge. One approach - not reliant on the slow adoption of IPv6
- is the use of virtualized overlay networks, which abstract the complexities of the underlying heterogeneous networks that span the components of distributed fog applications and middleware. This paper describes the evolution of the design and implementation of IP-over-P2P (IPOP) - from its purist P2P inception, to a pragmatic hybrid model which is influenced by and incorporates standards. The hybrid client-server/P2P approach allows IPOP to leverage existing robust and mature cloud infrastructure, while still providing the characteristics needed at the edge. IPOP is networking cyberinfrastructure that presents an overlay virtual private network which selforganizes with dynamic membership of peer nodes into a scalable structure. IPOP is resilient to partitioning, supports redundant paths within its fabric, and provides software defined programming of switching rules to utilize these properties of its topology.