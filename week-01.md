
# COIT20261 – Week 01 Portfolio
 Name: Ayushiben Patel
 
 Student ID: 12312209

 Unit Name: Network Services and Automation
 
 Unit code: COIT20261 

## Section A – Setup and Preparation
### 1. Understanding the Unit
   I reviewed the unit profile to understand the course structure and assessment requirements.I learned that I need to make a GitHub portfolio and add my tutorial work to it each week, like screenshots, tests, and reflections. This portfolio counts for 20% of my final grade.

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

         auto eth0   
         iface eth0 inet static
             address 10.10.1.101
             netmask 255.255.255.
             up sysctl net.ipv4.ipforward=0 

6. Started the node  

7. Opened web console  

8. Verified IP using command:
ip addr show

## 5. Screenshots

### Network Topology   
![](images/GNS3-Intro-12312209-network.png)

### IP Address
![](images/GNS3-Intro-12312209-ipaddress.png)

##  6. Testing Results
- The node ran properly with no errors.
- The IP address 10.10.1.1 showed up correctly.
- Everything worked the way it was supposed to.

##  7. Key Learnings
- i Learned how to create a project in GNS3  
- I also learned how to set a static IP in Linux.
- I useed the  ip address show command  
- I understood how to turn off IP forwarding.

##  8. Reflection
This week helped me get used to the basic tools for the networking labs. At first, editing the /etc/network/interfaces file was confusing, but after practising, I understood how static IP setup works.

I also learned how to use GitHub to keep a portfolio, which will help me track my work during the term.

##  Conclusion
Week 1 gave me a good start with the networking tools and basic setup. I now feel more confident using GNS3 and Linux commands for the next labs.


