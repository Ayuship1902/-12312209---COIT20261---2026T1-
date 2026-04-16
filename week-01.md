
# COIT20261 – Week 01 Portfolio
 Name: Ayushiben Patel
 
 Student ID: 12312209

 Unit Name: Network Services and Automation
 
 Unit code: COIT20261 

## Section A – Setup and Preparation
### 1. Understanding the Unit
Section A – Setup and Preparation
Understanding the Unit

This unit focuses on the foundational concepts of networking and cybersecurity. 
It introduces practical skills such as configuring network devices, using virtual environments, simulating networks with GNS3, and documenting technical work professionally using GitHub and Markdown.  

### Key learnings from the Unit Profile:
  • Understand network design, simulation, and troubleshooting using GNS3.  
  • Gain hands-on skills in Linux network configuration.  
  • Build a professional portfolio to showcase practical tasks and teamwork.  
  • Develop version-control and documentation practices through GitHub.

### 2. Software Setup
 - I installed Vertualbox and GNS3.
 - Create private GitHub Repository.
 - svreenshot
    
## Section B – GNS3 Hands‑On Task
**Objective**  
Create a simple GNS3 project with one Linux host and configure a static IP.
| Item | Details |
|------|----------|
| Project Name | GNS3‑Intro‑12312209 |
| Node | Linux Host |
| IP Address | 10.10.1.101 |
| Netmask | 255.255.255.0 |

**Network Configuration – /etc/network/interfaces**

    auto eth0   
    iface eth0 inet static
        address 10.10.1.1
        netmask 255.255.255.0
       up sysctl net.ipv4.ipforward=0

## To show IP address details
 ip address show    
