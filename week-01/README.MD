
# COIT20261 – Week 01 Portfolio
 Name: Ayushiben Patel
 
 Student ID: 12312209

 Unit Name: Network Services and Automation
 
 Unit code: COIT20261 

## Section A – Setup and Preparation
### 1. Understanding the Unit
   I reviewed the unit profile to understand the course structure and assessment requirements.I learned that I need to make a GitHub portfolio and add my tutorial work to it each week, like screenshots, tests, and reflections. This portfolio counts for 20% of my final grade.

### Key learnings from the Unit Profile:
  • Understand network design, simulation, and troubleshooting using GNS3.  
  • Gain hands-on skills in Linux network configuration.  
  • Build a professional portfolio to showcase practical tasks and teamwork.  
  • Develop version-control and documentation practices through GitHub.

### 2. Software Setup
   I installed the software I needed for the unit.
VirtualBox is for running virtual machines, and GNS3 is for simulating networks.
Both programs are needed for the networking labs.


### 3. GitHub Repository
## Section B – GNS3 Hands‑On Task
  I created a private GitHub repository and give me name like : 12312209---COIT20261---2026T1-

I also shared the repository with my tutor.


## 4. Task 1 – GNS3 Basics

###  Aim
To learn basic GNS3 operations such as creating a project, adding a node, configuring an IP address, and running Linux commands.

###  Steps Performed
1. Created a new project named:  
   `GNS3-Intro-<studentID>`

2. Added one **Linux Host node**

3. Added text in the workspace including:
   - Name  
   - Student ID  
   - Date  
   - Project title  

4. Selected IP address:  
   10.10.1.101

5. Configured static IP in  /etc/network/interfaces :

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
![](images/GNS3-Intro-12312209-ipaddress.png)

Network Topology
![](images/GNS3-Intro-12312209-network.png)

