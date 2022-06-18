# Moodle-Specification
<On-Prem> - 1500 - 2000 CCUs
Application server
5 VM dengan spesifikasi berikut:
CPU 4 cores
RAM 16 GB
Storage 100 GB (SSD preferred)
OS Ubuntu 20.04 LTS 64-bit or latest

 
Database server
1 VM dengan spesifikasi berikut:
CPU 16 cores
RAM 128 GB
Storage 300 GB (SSD preferred)
OS Ubuntu 20.04 LTS 64-bit or latest

 
File server
1 VM dengan spesifikasi berikut:
CPU 4 cores
RAM 16 GB
Storage 1 TB/2 TB (SSD preferred) -  depends on Data Size
OS Ubuntu 20.04 LTS 64-bit or latest


Redis server
1 VM dengan spesifikasi berikut:
CPU 8 cores
RAM 64 GB
Storage 100 GB (SSD preferred)
OS Ubuntu 20.04 LTS 64-bit or latest

 
Load Balancer
2 VM dengan spesifikasi berikut
CPU 4 Cores
RAM 16 GB
Storage 500 GB (SSD Preferred)
OS Ubuntu 20.04 LTS 64-bit or latest


<Azure Cloud>
Application server
1 Virtual Machine Scale Set + Load balancer
Minimal 2 instance for HA
D4s_v3
OSDisk Premium SSD 32GB
OS Ubuntu 20.04 LTS 64-bit or latest

 
Database server
1 VM F8s_v2
OSDisk Premium SSD 32GB
Storage 256 GB Standard SSD
OS Ubuntu 20.04 LTS 64-bit or latest


File server
1  VM DS1_v2
OSDisk Premium SSD 32GB
Storage 2 TB Standard SSD
OS Ubuntu 20.04 LTS 64-bit or latest


Redis server
1 VM D4s_v3
OSDisk Premium SSD 32GB
OS Ubuntu 20.04 LTS 64-bit or latest
