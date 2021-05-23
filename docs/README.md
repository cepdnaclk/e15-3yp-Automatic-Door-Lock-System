---
layout: home
permalink: index.html
repository-name: e15-3yp-Automatic-Door-Lock-System
title: Automatic Door Lock System
---
# Automatic Door Lock System

---
## Team
-  E/15/119, D.L. D. Hasanika, [e15119@eng.pdn.ac.lk](mailto:e15119@eng.pdn.ac.lk)
-  E/15/202, D.P. Liyanage, [e15202@eng.pdn.ac.lk](mailto:e15202@eng.pdn.ac.lk)
-  E/15/208, G.G.R. D. Madhushani, [e15208@eng.pdn.ac.lk](mailto:e15208@eng.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Hardware & Software Designs](#hardware-and-software-designs)
4. [Testing](#testing)
5. [Detailed budget](#detailed-budget)
6. [Conclusion](#conclusion)
7. [Links](#links)

---

## Introduction


Today, security has become the most important thing to be considered. People need a security system to prohibit unauthorized access to their property. Our target is to implement an automatic door lock system which allows the access only for authorized people. It helps to safeguard property from unauthorized people. 


## Solution Architecture

### Data Flow and Infrastructure
#### RFID Door Lock System
![image](https://user-images.githubusercontent.com/73756777/119256010-2e5d5580-bbdc-11eb-8da4-2ede3789e3fc.png)
#### Mechanism of RFID Reader
![image](https://user-images.githubusercontent.com/73756777/119256021-3ae1ae00-bbdc-11eb-925a-750572ff2004.png)
#### Fingerprint Sensor
![image](https://user-images.githubusercontent.com/73756777/119256034-47660680-bbdc-11eb-8f4d-addde3c1924d.png)
#### Face Recognition
![image](https://user-images.githubusercontent.com/73756777/119256051-58167c80-bbdc-11eb-9e65-60ac5fcb0d0c.png)


## Hardware and Software Designs
### Node 1 : RFID Door Lock System PCB design
![image](https://user-images.githubusercontent.com/73756777/119256070-6ebcd380-bbdc-11eb-9322-41392a330225.png)
![image](https://user-images.githubusercontent.com/73756777/119256124-b80d2300-bbdc-11eb-8716-11f337f32c19.png)
![image](https://user-images.githubusercontent.com/73756777/119256129-bba0aa00-bbdc-11eb-8a2f-eb9f793d6977.png)
![image](https://user-images.githubusercontent.com/73756777/119256132-be9b9a80-bbdc-11eb-9da1-6b475a0922ce.png)
### Node 2 : Completed PCB Design
![image](https://user-images.githubusercontent.com/73756777/119256150-decb5980-bbdc-11eb-80b8-e4a0b7664243.png)
![image](https://user-images.githubusercontent.com/73756777/119256146-db37d280-bbdc-11eb-9fc9-162bf7f601d2.png)
![image](https://user-images.githubusercontent.com/73756777/119256158-e7239480-bbdc-11eb-8aa0-7522cde0f313.png)




## Testing

[PDF document Group_4_Automatic_Door_Lock_System_test_plan.pdf](Group_4_Automatic_Door_Lock_System_test_plan.pdf)


## Conclusion

Special Note: 

We decided to use IR sensors instead of PIR sensors. Because PIR sensors detect all the motions in a wide range. So it was difficult to use in this project.

We removed the face recognition part from our node 2. Because for the high security, recognizing only the fingerprint is sufficient. 

## Links  
- <a href = "https://github.com/cepdnaclk/e15-3yp-Automatic-Door-Lock-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e15-3yp-Automatic-Door-Lock-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
