---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 1
description: Research on scalable, efficient interconnection networks for supercomputers and data centers.
---

My research focuses on the communication infrastructure that connects processors, accelerators, memory and storage in **supercomputers and data centers**. The central goal is to make these networks faster, more predictable and more energy-efficient as systems grow in scale and traffic becomes increasingly demanding.

I conduct this work within the **High-Performance Networks and Architectures (RAAP)** group at the University of Castilla-La Mancha, combining network architecture, routing and congestion-control research with implementation, simulation and technology transfer.

[Research themes](#research-themes) · [Projects](#projects)

## Research themes

[Congestion management](#congestion-management) · [Routing and topologies](#adaptive-routing-and-network-topologies) · [Energy efficiency](#energy-efficient-interconnection-networks) · [Network architecture](#hpc-and-data-center-network-architecture)

### Congestion management

Congestion can allow a small number of traffic flows to degrade the performance of an entire system. My work develops mechanisms to **detect congestion, identify the traffic responsible for it and isolate or regulate that traffic**. This includes queueing schemes, injection throttling, adaptive notifications, flow control and quality-of-service techniques for both lossless and lossy networks.

Current directions include fine-grain network monitoring, incast management and dynamic congestion isolation in HPC and data-center fabrics.

**Representative work**

- [ECP: Improving the Accuracy of Congesting-Packets Identification in High-Performance Interconnection Networks](https://doi.org/10.1109/MM.2025.3527722), _IEEE Micro_, 2025.
- [A smart and novel approach for managing incast and in-network congestion through adaptive routing](https://doi.org/10.1016/j.future.2024.04.041), _Future Generation Computer Systems_, 2024.
- [Congestion management in high-performance interconnection networks using adaptive routing notifications](https://doi.org/10.1007/s11227-022-04926-1), _The Journal of Supercomputing_, 2023.

### Adaptive routing and network topologies

I investigate how routing algorithms and network topology interact to determine performance, scalability and implementation cost. The work spans **Fat-Tree, Dragonfly, Slim Fly and KNS networks**, with particular attention to adaptive and non-minimal routing, deadlock freedom, head-of-line blocking and the practical constraints of commercial InfiniBand hardware.

The objective is to translate algorithmic advances into routing mechanisms that can be deployed on real systems.

**Representative work**

- [Adaptive Routing in InfiniBand Hardware](https://doi.org/10.1109/CCGRID54584.2022.00056), _IEEE/ACM CCGrid_, 2022.
- [Head-of-line blocking avoidance in Slim Fly networks using deadlock-free non-minimal and adaptive routing](https://doi.org/10.1002/cpe.4441), _Concurrency and Computation: Practice and Experience_, 2019.
- [Improving Non-minimal and Adaptive Routing Algorithms in Slim Fly Networks](https://doi.org/10.1109/HOTI.2017.11), _IEEE Hot Interconnects_, 2017 — **Best Student Paper Award**.

### Energy-efficient interconnection networks

Network power management cannot be considered independently from routing and congestion: saving energy may reduce available capacity precisely when traffic pressure increases. I study **power-aware network operation** and the interaction between energy-saving policies, congestion control and application communication patterns.

This research aims to reduce energy use while preserving throughput, latency and service quality in Ethernet-based and HPC interconnects.

**Representative work**

- [On the power saving in high-speed Ethernet-based networks for supercomputers and data centers](https://doi.org/10.1016/j.sysarc.2026.103786), _Journal of Systems Architecture_, 2026.
- [Combined power management and congestion control in High-Speed Ethernet-based Networks for Supercomputers and Data Centers](https://arxiv.org/abs/2511.10159), arXiv preprint, 2025.
- [Effects of Congestion Management on Energy Saving Techniques in Interconnection Networks](https://doi.org/10.1109/HiPINEB.2019.00009), _HiPINEB_, 2019.

### HPC and data-center network architecture

My broader systems research covers the design, modelling and evaluation of interconnection architectures for emerging HPC and AI workloads. It includes **real communication-pattern characterization, intra-node and inter-node communication, workload reproduction, simulation tools and new European interconnect technologies**.

This line connects architecture research with projects such as RED-SEA, TETRA-2 and the ATLAS data-acquisition network at CERN.

**Representative work**

- [On the impact of intra- and inter-node communication in the performance of interconnection networks in HPC and AI systems](https://doi.org/10.1007/s11227-026-08483-9), _The Journal of Supercomputing_, 2026.
- [Distributed fast and accurate simulation platform for advanced ARM- and RISC-V-based HPC systems](https://doi.org/10.1007/s11227-025-07972-7), _The Journal of Supercomputing_, 2025.
- [RED-SEA Project: Towards a new-generation European interconnect](https://doi.org/10.1016/j.micpro.2024.105102), _Microprocessors and Microsystems_, 2024.

## From research to systems

My experience at **Oracle in Oslo** included the development of InfiniBand EDR technology. Further collaborations have connected academic research with Huawei, Bull/Atos, NVIDIA and the ATLAS experiment at CERN. Within the **DMA2 Chair**, I work with Cojali and Grupo OESÍA on microelectronic systems based on open architectures.

## Projects

My project portfolio connects fundamental research on interconnection networks with the design and evaluation of systems for **high-performance computing, data centers and scientific infrastructures**. This section highlights selected projects in which I have held a leading role or made a substantial contribution; the [CV page]({{ '/cv/' | relative_url }}) provides a broader overview.

| Category                  | Project or collaboration                                             | Period and funding                                                             | Role and scope                                                                                                                                                         |
| ------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Competitive project**   | **TETRA-2 · Efficient Techniques for Advanced Network Technologies** | 2022–2025 · Government of Castilla-La Mancha and ERDF · SBPLY/21/180501/000248 | co-PI with Pedro Javier García · Routing, congestion management, quality of service and energy efficiency · 19-member UCLM team                                        |
| **Competitive project**   | **Congestion control for next-generation data centers**              | 2020–2023 · Spanish Ministry of Science and Innovation · PID2019-109001RA-I00  | PI · Congestion detection, traffic identification and control in data-center interconnects                                                                             |
| **Competitive project**   | **Interconnection network design for ATLAS at CERN**                 | 2021–2022 · BBVA Foundation Leonardo Grant                                     | PI · Modelling and optimization of the ATLAS data-acquisition network · One of five ICT awards in the 2020 call                                                        |
| **European project**      | **RED-SEA · Network Solution for Exascale Architectures**            | 2021–2024 · Horizon 2020 / EuroHPC · Grant 955776                              | co-PI at UCLM · 11-partner consortium developing European exascale interconnect technologies · [Selected journal output](https://doi.org/10.1016/j.micpro.2024.105102) |
| **European networks**     | **HiPEAC Networks of Excellence**                                    | HiPEAC-2 to HiPEAC-6                                                           | Long-term European collaboration in high-performance and embedded computer architecture                                                                                |
| **Technical association** | **ATLAS experiment at CERN**                                         | 2019–2025 · CERN ATLAS and UCLM RAAP                                           | co-PI with Pedro Javier García · Technical cooperation and research visits on data-acquisition interconnects                                                           |
| **Research chair**        | **DMA2 · Open microelectronic architectures**                        | 2024–2026 · Spanish Government PERTE Chip · TSI-069100-2023-0014               | Research and postgraduate education with Cojali and Tecnobit (Grupo OESÍA) · Co-director of the associated Master's programme                                          |
| **Technology transfer**   | **Industry and research collaborations**                             | Various periods                                                                | Bull/Atos BXI topology evaluation; Intel Omni-Path and Huawei routing and congestion control; Simula network simulation; Oracle InfiniBand EDR development             |

[Back to Research themes](#research-themes) · [Browse Publications]({{ '/publications/' | relative_url }}) · [View CV]({{ '/cv/' | relative_url }})
