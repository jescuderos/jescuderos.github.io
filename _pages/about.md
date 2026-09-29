---
layout: about
title: About
permalink: /
subtitle: Full Professor of Computer Architecture · University of Castilla-La Mancha
selected_papers: false
social: true
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<style>
  .about-intro {
    display: flex;
    flex-direction: column;
    gap: 1.25rem;
    margin-bottom: 1rem;
  }

  .about-intro__photo {
    order: 1;
  }

  .about-intro__text {
    order: 2;
  }

  .about-intro__photo img {
    display: block;
    height: auto;
    width: 100%;
  }

  @media (min-width: 768px) {
    .about-intro {
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(220px, 30%);
      align-items: start;
      gap: 1.5rem;
    }

    .about-intro__text {
      grid-column: 1;
      grid-row: 1;
    }

    .about-intro__photo {
      grid-column: 2;
      grid-row: 1;
    }
  }
</style>

<div class="about-intro">
  <div class="about-intro__photo">
    <img src="{{ '/assets/img/jesus-escudero-sahuquillo.jpeg' | relative_url }}" alt="Jesús Escudero Sahuquillo" class="img-fluid z-depth-1 rounded">
  </div>
  <div class="about-intro__text" markdown="1">

I am a **Full Professor of Computer Architecture at the University of Castilla-La Mancha (UCLM)** and Deputy Director of the UCLM International Doctoral School. My research focuses on **high-performance interconnection networks for supercomputers and data centers**, with particular emphasis on network topologies, routing algorithms, congestion management, and energy efficiency.

Throughout my career, I have combined academic research with international and industrial experience, including positions at **Oracle Corporation** in Norway and the **Universitat Politècnica de València**, as well as research stays at **Simula Research Laboratory** and **Heidelberg University**. <u>I have participated in more than 20 R&D projects and several industry collaborations</u>, <u>published over 60 peer-reviewed papers, co-supervised four PhD theses, and co-invented several patents</u>. A central goal of my work is to bridge **academic research and technology transfer**, collaborating with universities, research institutions, and companies on next-generation high-performance computing and networking technologies.

  </div>
</div>

## Research Interests

High-Performance Interconnection Networks · HPC & Data Centers · Network Topologies · Routing · Congestion Management · Energy Efficiency · Computer Architecture

## Selected Publications

Recent journal and conference publications (2022–2026). Each DOI links to the publication record.

| Year | Publication and venue                                                                                                                                           | DOI                                                                              |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| 2026 | **On the impact of intra- and inter-node communication in the performance of interconnection networks in HPC and AI systems.** _The Journal of Supercomputing_. | [10.1007/s11227-026-08483-9](https://doi.org/10.1007/s11227-026-08483-9)         |
| 2026 | **On the power saving in high-speed Ethernet-based networks for supercomputers and data centers.** _Journal of Systems Architecture_.                           | [10.1016/j.sysarc.2026.103786](https://doi.org/10.1016/j.sysarc.2026.103786)     |
| 2025 | **ECP: Improving the Accuracy of Congesting-Packets Identification in High-Performance Interconnection Networks.** _IEEE Micro_.                                | [10.1109/MM.2025.3527722](https://doi.org/10.1109/MM.2025.3527722)               |
| 2025 | **Quality-of-service provision for BXIv3-based interconnection networks.** _The Journal of Supercomputing_.                                                     | [10.1007/s11227-025-07069-1](https://doi.org/10.1007/s11227-025-07069-1)         |
| 2025 | **Distributed fast and accurate simulation platform for advanced ARM- and RISC-V-based HPC systems.** _The Journal of Supercomputing_.                          | [10.1007/s11227-025-07972-7](https://doi.org/10.1007/s11227-025-07972-7)         |
| 2024 | **Hybrid Congestion Control for BXI-Based Interconnection Networks.** _Euro-Par 2024_.                                                                          | [10.1007/978-3-031-69766-1_17](https://doi.org/10.1007/978-3-031-69766-1_17)     |
| 2024 | **Quality-of-Service Provision for BXI3-Based Interconnection Networks.** _IEEE Hot Interconnects_.                                                             | [10.1109/HOTI63208.2024.00015](https://doi.org/10.1109/HOTI63208.2024.00015)     |
| 2024 | **A New Mechanism to Identify Congesting Packets in High-Performance Interconnection Networks.** _IEEE Hot Interconnects_.                                      | [10.1109/HOTI63208.2024.00016](https://doi.org/10.1109/HOTI63208.2024.00016)     |
| 2024 | **A Hybrid Solution to Provide End-to-End Flow Control and Congestion Management in High-Performance Interconnection Networks.** _IEEE CCGrid_.                 | [10.1109/CCGrid59990.2024.00011](https://doi.org/10.1109/CCGrid59990.2024.00011) |
| 2024 | **A smart and novel approach for managing incast and in-network congestion through adaptive routing.** _Future Generation Computer Systems_.                    | [10.1016/j.future.2024.04.041](https://doi.org/10.1016/j.future.2024.04.041)     |
| 2024 | **RED-SEA Project: Towards a new-generation European interconnect.** _Microprocessors and Microsystems_.                                                        | [10.1016/j.micpro.2024.105102](https://doi.org/10.1016/j.micpro.2024.105102)     |
| 2024 | **Implementation and testing of a KNS topology in an InfiniBand cluster.** _The Journal of Supercomputing_.                                                     | [10.1007/s11227-024-06214-6](https://doi.org/10.1007/s11227-024-06214-6)         |
| 2023 | **Monitoring InfiniBand Networks to React Efficiently to Congestion.** _IEEE Micro_.                                                                            | [10.1109/MM.2023.3241840](https://doi.org/10.1109/MM.2023.3241840)               |
| 2023 | **Extending the VEF traces framework to model data center network workloads.** _The Journal of Supercomputing_.                                                 | [10.1007/s11227-022-04692-0](https://doi.org/10.1007/s11227-022-04692-0)         |
| 2023 | **Congestion management in high-performance interconnection networks using adaptive routing notifications.** _The Journal of Supercomputing_.                   | [10.1007/s11227-022-04926-1](https://doi.org/10.1007/s11227-022-04926-1)         |
| 2022 | **RED-SEA: Network Solution for Exascale Architectures.** _Euromicro DSD_.                                                                                      | [10.1109/DSD57027.2022.00100](https://doi.org/10.1109/DSD57027.2022.00100)       |
| 2022 | **Improving Congestion Control through Fine-Grain Monitoring of InfiniBand Networks.** _IEEE Hot Interconnects_.                                                | [10.1109/HOTI55740.2022.00020](https://doi.org/10.1109/HOTI55740.2022.00020)     |
| 2022 | **Adaptive Routing in InfiniBand Hardware.** _IEEE CCGrid_.                                                                                                     | [10.1109/CCGRID54584.2022.00056](https://doi.org/10.1109/CCGRID54584.2022.00056) |
| 2022 | **Reducing the Impact of Interjob Interference in Dragonfly Networks Using Virtual Partitions.** _IEEE Micro_.                                                  | [10.1109/MM.2022.3151258](https://doi.org/10.1109/MM.2022.3151258)               |

[Explore my research]({{ '/research/' | relative_url }}) · [Publications]({{ '/publications/' | relative_url }}) · [CV]({{ '/cv/' | relative_url }})

## About me

<details markdown="1">
<summary>Read the full biography</summary>

I am a **Full Professor at the University of Castilla-La Mancha (UCLM)**, where I teach at the School of Computer Science and Engineering (ESII) in Albacete. In 2006, I joined UCLM's **High-Performance Networks and Architectures (RAAP) research group** as a predoctoral researcher. I completed my PhD in 2011 under the supervision of Professors Francisco J. Quiles and Pedro J. García, and continued working with the RAAP group until 2013. During this period, I carried out several predoctoral and postdoctoral research stays at **Simula Research Laboratory** in Oslo, Norway, and at **ZITI, Heidelberg University**, Germany.

In 2014, I worked as an engineer/researcher at **Oracle Corporation** in Oslo, contributing to the development of **InfiniBand EDR networking technology**. In 2015, I joined the **Universitat Politècnica de València (UPV)** to work with Professor José Duato under a competitive postdoctoral fellowship funded through the call that replaced the Juan de la Cierva programme. I ranked 6th among the 8 fellowships awarded in the ICT area from 105 applications (7.5% acceptance rate). In December 2015, I returned to the RAAP group under a competitive **Access to the Spanish Science, Technology and Innovation System (SECTI)** postdoctoral fellowship funded by UCLM, ranking 2nd among 20 fellowships awarded from 89 applications across all research areas (22% acceptance rate).

In 2019, I was awarded the **I3 research certificate** by the Spanish State Research Agency (AEI), and I obtained **ANECA accreditation as Associate Professor and Full Professor** in 2020 and 2024, respectively. Since 2023, I have served as **Deputy Director of the UCLM International Doctoral School**.

My research focuses on improving the performance of **high-performance interconnection networks for supercomputers and data centers**. In particular, my work addresses the design of novel network topologies and routing algorithms, as well as congestion-management and energy-saving techniques. A key goal of my research is to promote **technology transfer** and ensure that research outcomes generate tangible benefits for society.

I have delivered invited talks at international conferences and companies and participated in **IEEE and IETF standardization activities**, including the IEEE 802.1Q and NENDICA groups. I maintain active collaborations with industrial partners such as **Huawei, Bull, and NVIDIA**, as well as with researchers from universities and research institutions including the University of Valladolid (Prof. F. J. Andújar), the Royal Academy of Sciences and Openchip (Prof. J. Duato), UPV (Profs. E. Quintana, J. Sahuquillo, and M. E. Gómez), UC3M (Prof. J. Carretero), Simula Research Laboratory (Prof. T. Skeie), NTNU (Prof. E. G. Gran), ETH Zürich (Prof. T. Hoefler), the **ATLAS experiment at CERN** (W. Vandelli), NVIDIA (E. Zahavi), and Huawei.

I have participated in **more than 20 regional, national, and European R&D projects**, as well as several industry-funded R&D contracts, coordinating a number of them. I have been **Principal Investigator (PI) of two national projects**, funded by the Spanish Ministry of Science through the RETOS programme and by the BBVA Foundation through a Leonardo Grant. I have also served as **co-PI at UCLM of the European RED-SEA project**, funded by Horizon 2020, and of the regional **TETRA-2 project**, funded by the Government of Castilla-La Mancha.

I have published **more than 60 peer-reviewed papers** in international journals and conferences. I have co-supervised **four PhD theses** and currently co-supervise three additional PhD candidates. I am also co-inventor of **three Spanish patents**, one of them granted following substantive examination, and **two international patents**. I have served as an editor and reviewer for several JCR-indexed journals and international conferences.

Since 2023, I have been involved in the **Chair in Microelectronic Systems Design Based on Open Architectures (DMA2)**, funded by the Spanish Government's **PERTE Chip** programme. I co-direct its postgraduate Master's programme and conduct research within the Chair in collaboration with two companies based in Castilla-La Mancha: **Cojali and Grupo OESÍA**.

</details>
