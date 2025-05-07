# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**


# Case Study: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

**Name:** SHAIK MAHAMMAD IMRAAN
**Register Number:** 212223100053

---

## Case Overview

ABC Cloud Services operates a private cloud using OpenStack to manage virtual machines (VMs) for internal development, testing, and production purposes. The cloud infrastructure consists of:

* **5 Compute Nodes**, each with:

  * 64 vCPUs
  * 256 GB RAM
  * 2 TB SSD Storage

### OpenStack Services Deployed:

* **Nova**: Compute
* **Neutron**: Networking
* **Cinder**: Block Storage
* **Glance**: Image Management
* **Keystone**: Identity Management
* **Horizon**: Dashboard UI
* **Heat**: Orchestration

The company aims to assess current capacity usage, VM density, and cost-efficiency before planning an expansion. The goal is to align current resource use with business needs and identify optimization opportunities.

---

## Case Study Questions

### 1. Resource Utilization

**Q:** Based on the current infrastructure, what is the total available compute capacity in terms of:

* Total vCPUs
* Total RAM
* Total Storage

**Answer:**

* Total vCPUs = 5 nodes \* 64 vCPUs = **320 vCPUs**
* Total RAM = 5 nodes \* 256 GB = **1280 GB RAM**
* Total Storage = 5 nodes \* 2 TB = **10 TB SSD Storage**

---

### 2. Storage Allocation

**Q:** Given 10 TB of total block storage across the cloud, how many VMs can be supported if:

* a) Each VM is allocated 100 GB block storage
* b) Snapshot storage consumes 20% extra on average

**Answer:**

* Total block storage available = 10 TB = 10,240 GB
* Storage per VM (including snapshots) = 100 GB + 20% of 100 GB = 120 GB
* Maximum number of VMs supported = 10,240 GB / 120 GB = **85 VMs**

---

 Problem 1: Encryption Time Calculation

A company uses AES-256 encryption to secure its data before uploading it to the cloud. It takes 0.05 seconds to encrypt 1 MB of data.

Q: How long will it take to encrypt 2 TB of data before upload?

Problem 2:CPU Utilization Efficiency

A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.

Q: What is the CPU utilization efficiency?

Problem 3: Network Throughput Efficiency

A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only uses 600 Mbps.

Q: What is the network throughput efficiency?

 Problem 4:Energy Efficiency

Two cloud setups process the same workload:

Setup A uses 500W for 2 hours.
Setup B uses 300W for 3.5 hours.
Q: Which setup is more energy-efficient?

Problem 5: 

CPU Utilization Efficiency

A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 75%.

Q: What is the maximum number of VMs that can be efficiently hosted?

Problem 1: Encryption Time Calculation
Given:

Encryption speed = 0.05 seconds per MB

Data size = 2 TB

Solution:

Convert 2 TB to MB:
2
 TB
=
2
×
1024
×
1024
=
2
,
097
,
152
 MB
2 TB=2×1024×1024=2,097,152 MB

Total time = 
2
,
097
,
152
×
0.05
=
104
,
857.6
 seconds
2,097,152×0.05=104,857.6 seconds

Convert to hours:
104
,
857.6
3600
≈
29.13
 hours
3600
104,857.6
​
 ≈29.13 hours

Answer:
≈ 29.13 hours

Problem 2: CPU Utilization Efficiency
Given:

Allocated vCPUs = 8

Used vCPUs = 5.5

Solution:

Efficiency
=
(
Used
Allocated
)
×
100
=
(
5.5
8
)
×
100
=
68.75
%
Efficiency=( 
Allocated
Used
​
 )×100=( 
8
5.5
​
 )×100=68.75%
Answer:
68.75%

Problem 3: Network Throughput Efficiency
Given:

Max bandwidth = 1 Gbps (1000 Mbps)

Used bandwidth = 600 Mbps

Solution:

Efficiency
=
(
Used
Max
)
×
100
=
(
600
1000
)
×
100
=
60
%
Efficiency=( 
Max
Used
​
 )×100=( 
1000
600
​
 )×100=60%
Answer:
60%

Problem 4: Energy Efficiency
Given:

Setup A: 500W for 2 hours → Total energy = 
500
×
2
=
1000
 Wh
500×2=1000 Wh

Setup B: 300W for 3.5 hours → Total energy = 
300
×
3.5
=
1050
 Wh
300×3.5=1050 Wh

Comparison:

Setup A uses 1000 Wh

Setup B uses 1050 Wh

Answer:
Setup A is more energy-efficient (1000 Wh < 1050 Wh).

Problem 5: VM Hosting Efficiency
Given:

Total cores = 16

Cores per VM = 2

Optimal CPU utilization = 75%

Solution:

Total usable cores at 75% efficiency:
16
×
0.75
=
12
 cores
16×0.75=12 cores

Max VMs:
12
2
=
6
 VMs
2
12
​
 =6 VMs

Answer:
6 VMs

This analysis provides a clear view of the current capacity and highlights how many VMs can be efficiently supported with existing block storage, considering snapshot overhead.
