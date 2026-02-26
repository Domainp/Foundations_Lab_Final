Network Security
Network security consists of the policies, processes, and practices adopted to prevent, detect, and monitor unauthorized access, misuse, modification, or denial of a computer network and network-accessible resources.

Key Goal: To protect the integrity and usability of your data while it is in transit.

Lab Connection: Demonstrated this by setting up communication between your Linux Mint, Kali, and Ubuntu virtual machines and verifying the link in Cisco Packet Tracer.


GRC (Governance, Risk, and Compliance)
GRC is a structured approach to aligning IT with business goals while managing risks and meeting all industry and government regulations.

Governance: The set of rules and policies that dictate how an organization operates.

Risk: Identifying and mitigating technical or physical threats that could harm the organization.

Compliance: Ensuring the organization follows laws (like HIPAA or GDPR) and internal security standards.

Lab Connection: By organizing screenshots into a clean folder hierarchy and keeping repository Private, you are practicing GRC standards.


Cloud Security
Cloud security is a collection of security measures designed to protect cloud-based infrastructure, applications, and data. These measures ensure user and device authentication, data privacy, and resource access control.

Shared Responsibility: In the cloud, the provider (like AWS or Azure) secures the hardware, while the user (you) is responsible for securing the data and access permissions.

Lab Connection: The use of a GitHub repository to store and version-control  lab deliverables is a practical example of using cloud-based tools for security documentation.

Category,                               Competency Demonstrated
Linux Administration,                   Provisioned an Ubuntu 24.04 LTS (AMD64) Server environment and managed system permissions using chmod.
Automation & Scripting,                 Authored and executed a Bash audit script to automate system health logs and file I/O operations.
Network Engineering,                    "Engineered a Star Topology using Cisco hardware, implementing static IPv4 addressing and verifying Layer 3 connectivity via ICMP."
Infrastructure-as-Code,                 Managed the technical supply chain by synchronizing local infrastructure artifacts to a remote GitHub repository using Git CLI.
Technical Troubleshooting,              Resolved ICMP timeouts (logical layer) and Git pathspec errors (directory context) through systematic debugging.


Linux Systems Administration: Provisioned an Ubuntu 24.04 LTS environment and automated system audits using Bash scripting.

Network Engineering: Designed a functional Star Topology and configured static IPv4 addressing within a Cisco environment.

Version Control & CI/CD: Managed the deployment pipeline by synchronizing local artifacts to a remote repository via Git CLI.


Security Philosophy
Confidentiality: The lab environment utilizes virtualization (such as VirtualBox or UTM) or cloud-based containers (Google Cloud Shell) to abstract your physical hardware. This isolation protects confidentiality by completely separating your experimental lab workspace from your host operating system, ensuring that security tools or scripts run in the lab cannot accidentally access or expose the private data stored on your personal laptop.

Integrity: The overarching objective of the deployment is to stop troubleshooting various physical laptops and instead build "one standardized environment". This strict standardization ensures system integrity by providing a controlled, clean state for your operations. Because the Linux virtual machine operates independently, running system audit scripts like lab_verify.sh will not modify, corrupt, or compromise the integrity of your host machine's critical system files.

Availability: The deployment is designed with three distinct hardware paths (Standard Build, Apple Silicon Build, and Cloud Build) to accommodate any device constraints. By abstracting the hardware, the lab guarantees the availability of a stable Ubuntu or Debian Linux terminal for 100% of the class. This ensures that your workspace and necessary tools (like Git and Python3) remain consistently accessible and ready for use regardless of the physical device you are using.

Nieles, M., Dempsey, K., & Pillitteri, V. Y. (2017). An introduction to information security (NIST Special Publication 800-12 Rev. 1). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-12r1

