# Welcome to Our UniSA Cyber

Welcome to the home of UniSA Cyber, where you will find public repositories for cybersecurity research projects that have been undertaken at the University of South Australia (UniSA). These repositories contain code, documentation, and other resources that may be useful for others working on similar problems or looking to learn more about cybersecurity.

## Projects
Here are some of the selected project reporitories:

### [S3FS - SDN-based Space Systems Framework for Simulations]
**Description:** This project developed a simulation framework for SDN-based space systems for the Earth Observation use case. The framework implements dynamic Inter-Satellite Links (ISL) and a dynamic topology based on the orbital dynamics of the Walker Constellation. The framework is designed to simulate a constellation of satellites in low Earth orbit (LEO) that communicate with ground stations via satellite terminals connected through an SDN network. The framework allows for experimentation with different routing protocols through the POX controller.

**Technology Stack:** Mininet, Python, Open vSwitch (OVS), Pox, etc
**GitHub Repository:** [Link to the GitHub repository](https://github.com/UniSACyber/S3FS)
**Reference Paper** Uhongora, U., Thinyane, M., & Law, YW. (2024) "Development of an SDN-based Space Systems Simulation Framework for Intrusion Detection." IEEE International Conference on Cyber Security and Resilience (IEEE CSR), forthcoming.

### [S3ID - SDN-based Space Systems Intrusion Detection]
**Description:** This project developed an intrusion detection dataset for SDN-based space systems, based on the S3FS framework. The dataset includes four classes of labelled data for normal traffic, two types of SYN flood attacks, and port scanning attacks. The dataset is designed to help researchers in developing intrusion detection systems (IDS) that can detect anomalies in SDN-based space systems.

**Technology Stack:** Same as the 33FS framework including TCPDump and CICFlowMeter.
**GitHub Repository:** [Link to the other GitHub repository](https://github.com/UniSACyber/S3ID)
**Reference Paper** Uhongora, U., Thinyane, M., & Law, YW. (2024) "Development of an SDN-based Space Systems Simulation Framework for Intrusion Detection." IEEE International Conference on Cyber Security and Resilience (IEEE CSR), forthcoming.

## How to Use These Repositories
Each repository contains its own README file with more detailed information about the project, licensing, how to install and run it, and any prerequisites you need to know about. Please refer to each repository's README for specific instructions on using the code or documentation provided. 

## Licensing
Unless otherwise noted, all content is licensed under a [GNU General Public License v3.0](https://www.tldrlegal.com/license/gnu-general-public-license-v3-gpl-3). This means you are free to use the code for any purpose, including commercial purposes, as long as you provide proper attribution and distribute your changes under the same license. Attribution requirements for each repository, including the academic publications to be cited, will be specified in their respective READMEs.
