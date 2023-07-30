
# Network Design

This repository contains the materials related to the Network Design Assignment carried out as a fulfillment for the module EN2150: Communication Network Engineering, which was carried out in two phases. The assignment involved designing the Local Area Network (LAN) for the ENTC Department and designing the Backbone Network for University of Moratuwa (UOM) and simulating the network using Cisco Packet Tracer.

## Phase 1: Backbone Network Design & LAN Design 

In this phase, the backbone network for the University of Moratuwa and the internal network of one building (ENTC) were designed. The following tasks were accomplished:

1. **Backbone Network Design for UOM:** Multiple buildings housing academic faculties/departments, administrative offices, library, and     the data center building (CITeS) were interconnected. The design was     intended for long-term use (20-25 years) and took into consideration     the total cost for cabling, incorporating both active and passive       systems.
  
  2.  **Study of ENTC LAN:** The local area network of the ENTC building was analyzed to serve as a reference design for the LAN.
  
  3.  **Cisco Packet Tracer Simulation:** The ENTC network was simulated using Cisco Packet Tracer Software to validate the design      before implementing it for the backbone network.

    

### Files for Phase 1

1.  [Concise Report](https://github.com/randika-perera/Network-Design/blob/main/Phase%201/Report.pdf): This report includes the approach to the backbone design with justification, network diagrams, IP addressing scheme, and justification for the selection of active and passive components. It also provides features/specifications of routers/switches and the Bill of Quantities (BOQ) for passive and active components.
    
2.  [Packet Tracer Simulation Files](https://github.com/randika-perera/Network-Design/tree/main/Phase%201/Packet%20Tracer%20Files): This directory contains the Packet Tracer simulation files.
    

## Phase 2: Routing Configuration and Simulation

In this phase, the previously designed network topology was utilized for further configuration and simulations. The routing configuration for the backbone network was implemented using OSPF to ensure redundancy and availability of key resources.

### Tasks Completed in Phase 2:

 1. **Routing Configuration for Backbone Network:** OSPF was configured to enable the backbone nodes to advertise the IP blocks of connected departments/divisions. Redundancy was implemented to ensure uninterrupted access to crucial resources.
    
2. **Simulation Scenarios:** After configuring OSPF, we conducted simulations to demonstrate various routing scenarios:
      
- **Routing Path for ENTC Student Accessing LMS Servers:** We simulated the routing path taken by a network session of an ENTC student accessing the LMS (Learning Management System) servers located in the university data center.
      
-   **Broken Link between ENTC and Data Center:** In this scenario, we assumed that the link connecting the backbone network nodes    between ENTC and the data center was broken. We then showed the    routing path taken by the network session referred to in the previous scenario.
      
- **Collaborative Research Project Accessing Mechanical Department Server:** We demonstrated the routing path taken for a network session in which an ENTC student needed to access a server maintained    at the Mechanical Department as part of a collaborative research project.
      
- **Broken Backbone Link for Collaborative Research Project:** For this simulation, we disconnected any one of the backbone links used by the routing path established in the previous scenario. This allowed us to observe the new routing path taken by the network session after the link failure.

### Files for Phase 2

1.  [Concise Report](https://github.com/randika-perera/Network-Design/blob/main/Phase%202/Report.pdf): Includes the basis of our routing design and detailed simulation results.
    
2.  [Packet Tracer Simulation Files](https://github.com/randika-perera/Network-Design/tree/main/Phase%202/Packet%20Tracer%20Files): This directory contains the Packet Tracer simulation files.
    
