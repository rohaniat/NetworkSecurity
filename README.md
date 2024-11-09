# Medical Clinic Network Security Assessment

This repository contains the files for the network security assessment of a medical clinic. The objective was to analyze the current network setup, assess its vulnerabilities, and provide a plan for a more secure future-state architecture.

## Files in this Repository

- **NetworkSecurityReport.pdf**: This document provides a comprehensive assessment of the medical clinic's network security, detailing various aspects like device inventory, patch management, exposed services, user authentication, and cloud service use. It also includes specific recommendations for improving security.
- **NetworkSecurityDiagram.pdf**: A diagram of the network architecture, illustrating the current flat network design and a proposed future-state segmented architecture with VLANs, enhanced firewall placement, and access controls.

## Project Overview

### 1. Attack Surface Analysis
The report details a thorough analysis of the clinic's attack surface:
- **Endpoints and Devices**: Includes patient health record servers, workstations, imaging devices, POS terminals, and access points.
- **Network Layer**: IP ranges, open ports, and firewall configurations.
- **User Accounts**: Password security and account management recommendations.
- **Data Handling**: Encryption at rest and in transit for patient data.
- **Cloud Services**: AWS usage for backups and data storage.
- **Patch Management**: Manual patching and vulnerability scans.

### 2. Network Architecture
The provided diagram compares the **Current Network Architecture** and the **Proposed Future-State Architecture**:
- **Current Architecture**: A flat network without segmentation, lacking traffic control and isolation.
- **Proposed Architecture**: Segmented into VLANs with dedicated firewall rules for each section, limiting attack vectors and enhancing data protection.

### How to Use This Repository
1. Review the `NetworkSecurityReport.pdf` to understand the full context of the network security assessment.
2. Refer to `NetworkSecurityDiagram.pdf` to visualize the current network layout and proposed improvements.

### Future Recommendations
- Implement VLAN segmentation as outlined.
- Introduce centralized patch management.
- Apply multi-factor authentication (MFA) for critical systems.
- Regularly audit and update firewall rules to maintain security.

---

This repository is designed to support network security best practices and provide a foundational guide for improving network security within healthcare environments.
