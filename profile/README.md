# Welcome to UniSA Cyber

Welcome to the home of UniSA Cyber, where you will find public repositories for cybersecurity research projects that have been undertaken at the University of South Australia (UniSA). These repositories contain code, documentation, and other resources that may be useful for others working on similar problems or looking to learn more about cybersecurity.

## Projects
Here are some of the selected project reporitories:

### S3FS - SDN-based Space Systems Framework for Simulations
This project developed a simulation framework for SDN-based space systems for the Earth Observation use case. The framework implements dynamic Inter-Satellite Links (ISL) and a dynamic topology based on the orbital dynamics of the Walker Constellation. The framework is designed to simulate a constellation of satellites in low Earth orbit (LEO) that communicate with ground stations via satellite terminals connected through an SDN network. The framework allows for experimentation with different routing protocols through the POX controller.

- **Technologies Used:** Mininet, Python, Open vSwitch (OVS), Pox, OpenFlow
- **GitHub Repository:** [Link to the GitHub repository](https://github.com/UniSACyber/S3FS)
- **Reference Paper:** U. Uhongora, M. Thinyane and Y. W. Law, __"Development of an SDN-based Space System Simulation Framework for Intrusion Detection,"__ 2025 IEEE International Conference on Cyber Security and Resilience (CSR), Chania, Crete, Greece, 2025, pp. 524-529, [doi: 10.1109/CSR64739.2025.11130072](https://doi.org/10.1109/CSR64739.2025.11130072).

### S3ID - SDN-based Space Systems Intrusion Detection
This project developed an intrusion detection dataset for SDN-based space systems, based on the S3FS framework. The dataset includes four classes of labelled data for normal traffic, two types of SYN flood attacks, and port scanning attacks. The dataset is designed to help researchers in developing intrusion detection systems (IDS) that can detect anomalies in SDN-based space systems.

- **Technologies Used:** Same as the S3FS framework including TCPDump and CICFlowMeter.
- **GitHub Repository:** [Link to the GitHub repository](https://github.com/UniSACyber/S3ID)
- **Reference Paper:** U. Uhongora, M. Thinyane and Y. W. Law, __"Development of an SDN-based Space System Simulation Framework for Intrusion Detection,"__ 2025 IEEE International Conference on Cyber Security and Resilience (CSR), Chania, Crete, Greece, 2025, pp. 524-529, [doi: 10.1109/CSR64739.2025.11130072](https://doi.org/10.1109/CSR64739.2025.11130072).

### PSDSN - Programmable (data plane) Software Defined Satellite Networking
This project aims to extend S3FS by incorporating (P4-enabled) data plane programmability within the simulation framework and investigating security use-cases and solutions enabled by the SD-Fabric within S3FS and for SDSNs. 

- **Technologies Used:** S3FS, ONOS (micro-ONOS), Stratum BMv2, P4, OpenFlow, Docker, K8S
- **GitHub Repository:** [Link to GitHub repository](https://github.com/UniSACyber/PSDSN) (*currently private*)
  
## How to Use These Repositories
Each repository contains its own README file with more detailed information about the project, licensing, how to install and run it, and any prerequisites you need to know about. Please refer to each repository's README for specific instructions on using the code or documentation provided. 

## Licensing
Unless otherwise noted, all content is licensed under a [GNU General Public License v3.0](https://www.tldrlegal.com/license/gnu-general-public-license-v3-gpl-3). This means you are free to use the code for any purpose, including commercial purposes, as long as you provide proper attribution and distribute your changes under the same license. Attribution requirements for each repository, including the academic publications to be cited, will be specified in their respective READMEs.
