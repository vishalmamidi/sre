# SRE

| Aspect | DevOps                                                | SRE                                                                                                      |
| ------ | ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Focus  | works with dev & ops for software delivery lifecycyle | ensures reliabliity, scalability & performance                                                           |
| Goals  | Faster delivery, increased deployment frequency,      | system reliability, availability, and performance through scalable and sustainable operations |

#### DHCP - **Dynamic Host Configuration Protocol**
It is a protocol that allows networks to dynamically allocate IP addresses to hosts on the network

#### DNS - **Domain Name System**
maps hostname to one or more IP addresses. also known as DNS resolvers

#### APR - Accelerated Problem Resolution
1. Monitoring and Alerting
2. Rapid Diagnosis
3. Issue Resolution and Mitigation
4. Post-mortem Analysis and Documentation
5. Continuous Improvement

#### Hardlink and Softlink/Symbolic links

Underneath the file system, files are represented by inodes

A file in the file system is basically a link to an inode

**hard link** creates another file with a link to the same underlying inode
**symbolic link** is a link to another name in the file system. same as shortcut in windows

When you delete a file, it removes one link to the underlying inode. The inode is only deleted when all links to the inode have been deleted.

in hard link Any changes to the data on the inode is reflected in all files
file copy is different when compare to hard link

#### Multithreading
executing multiple threads simultaneously. A thread is a lightweight sub-process, the smallest unit of processing

#### LILO (Linux Loader) 
bootloader for Linux that is used to load Linux into memory


#### Linux Shell
command-line interpreter from which we can run linux/unix commands
examples: KSH,SH,BASH,ZSH

#### CDN (Content Delivery Network) 
network of servers that stores and distributes content to clients.
CDNs are most commonly used to store static content, such as images and videos
example: Cloudflare CDN 

#### Service Level Objective (SLO)
Service Level Objective is a performance target set by a service provider to ensure the quality of their service.

often expressed as a percentage of uptime or response time

#### SLA - Service level agreement
commitment between service provider and customer, Like 99% SLA 
how reliable/available the system is to its end users expressed in percentage

example
SLA for Accessibility 
SLA for Response Time 
SLA for Error Rate
