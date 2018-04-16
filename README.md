# Intel® Rack Scale Design Reference Software

Intel® Rack Scale Design (Intel® RSD) reference software is a logical architecture that disaggregates compute, storage, and network resources, and introduces the ability to more efficiently pool and utilize these resources. Intel® Rack Scale Design software APIs simplify resource management and provide the ability to dynamically compose resources based on workload-specific demands.

Learn more at the [official Intel® RSD site](http://intel.com/intelRSD).

## Getting Started

This repository is a good starting point for developers who are ready to start working with Intel® RSD software. For more details on Intel® RSD, please visit  the [official Intel® RSD site](http://intel.com/intelRSD). It is recommended that you read this entire documentation before starting work with your own Rack Scale Design solution. **Keep in mind this code is reference software only.** It is expected that developers will take this reference software and make it their own. 

## Documents

All documents referred to in this ReadMe document can be also found at the [official Intel® Rack Scale Design Site](http://intel.com/intelRSD).

## Questions and issues
For questions, concerns, or defects found in the in the current Intel® RSD reference software, please create a new issue in this repository. If your questions are about a previous release, include the Intel® RSD version in your topic.

**Note**: When creating a new issue, including additional information such as log files, REST API dumps or other operating system information can expedite response time.

## News

### New version of Rack Scale Solution Reference Software (2.3) has been released!
The new version of Rack Scale Solution Reference Software (v2.3) has been released! Here is the list of the most important changes:

1.	NVMe over Fabrics (NVMe-oF) – Enables composition of nodes connected to NVM Express (NVMe)\* drives via RDMA over Converged Ethernet protocol through the Leaf Switches (TORs).

2.	 Quality of Service (QoS) – Supports setting some QoS parameters to configure for the Leaf Switches. It is required to allocate the capability of a network for selected network traffic over Ethernet. NVMe-oF is one of the traffic types that requires an appropriate level of network resources to be allocated.

3.	Standards-Based Storage Management – The Storage Services REST API is aligned to the Storage Networking Industry Association (SNIA) Swordfish\* specification.



## _Disclaimer_

This code is **reference software only and is not feature complete**. 
Intel makes no claims for the quality or completeness of this code.
*Other names and brands may be claimed as the property of others.
