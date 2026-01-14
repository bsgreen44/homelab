## Home Infrastructure Lab
An on premise self-hosted infrastructure environment for accelerated learning in IT, System Administration and DevOps.

## Hardware

#### NAS
- TrueNAS
- Intel N100 4 Core 4 Threads
- 500W PSU
- 128GB NvME SSD
- 32GB DDR5 Laptop RAM
- 2 x 4TB Mirrored HDD Red Iron Wolf 5200RPM 

#### Main Server

**Current**
- GMKtec Mini PC Gaming, M7 AMD Ryzen 7 PRO 6850H
- Proxmox
- 8 Core 16 Thread AMD AM4
- 32GB RAM
- 1TB NvME SSD

**Old**
- Proxmox
- 8 Core 16 Thread AMD AM4
- 32GB RAM
- 500GB NvME SSD, 1TB NvME SSD
- 600W PSU

#### Backup server
- Zimablade
- Proxmox
- Intel E3950 4 Core 4 Threads
- 16GB DDR3L
- 32GB eMMC 5.1, 1TB SSD

#### Network
- Ubiquiti Cloud Gateway Max
- Ubiquiti Lite 8 PoE
- U6+ Access Point
- Brume 2 GL-MT2500 Security Gateway

#### Travel
- Beryl GL-MT3000 Travel Router

#### UPS
- APC 1500VA Backup UPS

## SaaS
**Cloudflare**
**Tailscale**

**Networking (Unifi)**
- Deploy and manage 4 VLAN to ensure secure network segmentation
- Implement firewall, IDS and IPS policies that have successfully notified and blocked inter VLAN traffic, incoming and outgoing traffic
- Manage a local DNS server for over 20 devices that contains local DNS records and filters queries to provide network wide security and privacy
- Deploy a VPN server to provide users secure remote access to services

**Virtualization & Containerization (Proxmox, Docker)**
- Deploy and oversee 30+ containers and VMs on a Type 1 hypervisor
- Manage resource allocation to optimize performance and efficiency of hardware
- Automate weekly backup and update schedules to maximize efficiency

**Storage Solution (TrueNAS)**
- Deploy storage redundancy and disaster recovery policies to ensure data integrity and availability

**Monitoring and Automation**
- Design and deploy frontend applications to monitor and automate backend services
- Utilize tools such as n8n (automation) and Home Assistant (IoT automation and monitoring) to communicate with APIs using TCP/IP, HTTP/HTTPS and SSH protocols
