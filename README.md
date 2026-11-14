# Venus-Technologies-Network-Configuration-and-Development-CMN-CaseStudy-
Designed a 6-site WAN in Cisco Packet Tracer (7 routers, 4 switches) with VLSM subnetting, OSPF, VLANs, and SSH

## Enterprise WAN Design: Venus Technologies (CMN620S)

**Module:** CMN620S Communications Networks, NUST | **Type:** Group case study | **Tool:** Cisco Packet Tracer

### Scenario
Venus Technologies is a company with its headquarters in Windhoek and five branch offices (Oshakati, Grootfontein, Mariental, Lüderitz and Opuwo). It has 505 employees across 6 sites, projected to grow to 2,020 by 2030. The task was to design a scalable, secure network for the whole company.

### What was designed
- **Topology:** 7 routers (a Windhoek hub, five branch routers and an ISP router) and 4 branch switches, connected by point-to-point serial links.
- **Addressing:** VLSM subnetting of `172.27.0.0/19`, with `/30` subnets for the WAN links.
- **Routing:** OSPF between the hub and branches.
- **Segmentation:** VLANs on the branch switches (10, 20, 30 and 99).
- **Security:** SSH-based remote management and device access controls.
- **Documentation:** Packet Tracer topology and a written design report, including an STP discussion.

### Skills demonstrated
Subnetting and VLSM, WAN design, OSPF routing, VLANs, secure remote management, network documentation.
Case study Documentation with Screenshots: 

Documentation: [CMN case study.pdf](https://github.com/user-attachments/files/34862017/CMN.case.study.pdf)
