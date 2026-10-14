# BoardNet: Board Examination Communication Network

**BoardNet** is a Cisco Packet Tracer networking project designed to simulate a centralized communication infrastructure for six Higher Secondary Certificate (HSC) education boards in Bangladesh: Dhaka, Chattogram, Rajshahi, Barishal, Sylhet, and Khulna.

The project implements an interconnected network that supports administrative communication and examination-related services through appropriate IP addressing, routing, and server configurations.

## Key Features

- **Network Topology Design:** Six board networks interconnected according to the specified topology requirements.
- **VLSM Subnetting:** Efficient IP address allocation based on the estimated host requirements of each board.
- **Dynamic Routing:** RIP configuration among the Dhaka, Sylhet, and Rajshahi routers.
- **Static Routing and Redundancy:** Static routes for Khulna and Barishal, with backup paths to maintain connectivity during primary link failures.
- **DHCP Configuration:** Centralized DHCP through the Dhaka router for Dhaka, Chattogram, Sylhet, and Rajshahi, with dedicated DHCP servers for Khulna and Barishal.
- **DNS Configuration:** Centralized DNS service hosted by the Dhaka board for network-wide domain name resolution.
- **Web Hosting:** Web servers for `www.dhk.edu.bd` and `www.ctg.edu.bd`, accessible across all board networks.
- **Email Services:** Dedicated email servers for all six boards to support official communication.
- **Network Testing:** Verification of connectivity, dynamic IP assignment, DNS resolution, website accessibility, email configuration, and redundant routing.

## Tools and Technologies

- Cisco Packet Tracer
- IPv4 Addressing and VLSM
- RIP Routing Protocol
- Static Routing and Default Routing
- DHCP, DNS, HTTP, and Email Services

## Project Objectives

- Design a scalable network addressing the communication needs of six HSC education boards.
- Configure routing and server services according to the project requirements.
- Establish end-to-end connectivity between the board networks.
- Demonstrate fault tolerance through alternative routing paths.

## Project Deliverables

- Cisco Packet Tracer simulation file (`.pkt` or `.pka`)
- Network topology diagram
- VLSM subnetting tree and IP addressing table
- Router configuration commands
- DHCP, DNS, web server, and email server configuration details

**Project Type:** Computer Networking / Network Simulation  
**Platform:** Cisco Packet Tracer
