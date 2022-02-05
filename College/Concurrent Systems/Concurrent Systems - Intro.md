# Concurrent Systems and Operating Systems

## Overview

 **Concurrency** 
- What / Why / How, 
- Grappling with Concurrency Issues. 


**Operating Systems **
-  Operating system architectures, 
-  Memory Management (OS perspective), 
-  Processes and Thread Management, 
-  File Storage (disk I/O and file systems).

## Assessment

20% Assignments
- Tool Usage 2%
- Thread Programming 6%
- Concurrency Modeling 6%
- OS Coding 6%

80% Examination
- 2hr Exam

## What is Concurrency?
![[Pasted image 20220125171839.png]]
- Concurrent Programs: Many streams that interfere with each other.

## Concurrency vs. Parallelism
![[Pasted image 20220125172042.png]]
- Main difference is that concurrency deals with how programs are constructed, where as parallelism uses more hardware to speed up computation.

## Types of Concurrency
![[Pasted image 20220125172308.png]]

## Types of Parallelism
![[Pasted image 20220125172839.png]]

## POSIX
![[Pasted image 20220125173338.png]]
![[Pasted image 20220125173717.png]]
![[Pasted image 20220125173954.png]]
![[Pasted image 20220125174216.png]]
## Creating a pthread
![[Pasted image 20220125174602.png]]
![[Pasted image 20220127150258.png]]
![[Pasted image 20220127150412.png]]
## Thread Code
![[Pasted image 20220127150752.png]]
![[Pasted image 20220127152533.png]]
![[Pasted image 20220127152618.png]]
**After execution the threads finish in a different order than they were created in the loop**
![[Pasted image 20220127152808.png]]
## Another Example
![[Pasted image 20220127152947.png]]
![[Pasted image 20220127153404.png]]