
# Privilege Escalation on Metasploitable

## Project Overview
The **Privilege Escalation on Metasploitable** project focuses on identifying and exploiting vulnerabilities within the Metasploitable 2 virtual machine, a deliberately vulnerable target designed for security professionals and students to practice penetration testing techniques. This project provides practical insights into the security weaknesses commonly found in legacy systems.

## Objectives
- To perform a vulnerability assessment on Metasploitable 2.
- To identify potential privilege escalation vectors.
- To exploit identified vulnerabilities to gain root access.

## Tools Used
- **Metasploit Framework**: A powerful tool for penetration testing that facilitates the discovery and exploitation of vulnerabilities.
- **Nessus**: A vulnerability scanner used to identify weaknesses in the Metasploitable system.
- **Kali Linux**: A Linux distribution specifically designed for penetration testing and security auditing.
- **VirtualBox**: A virtualization platform used to run the Metasploitable and Kali Linux environments.

## Methodology

### 1. Environment Setup
- Configured VirtualBox to run both Metasploitable 2 and Kali Linux in a bridged network mode. This setup allowed both VMs to communicate with each other and the host system, facilitating the penetration testing process.

### 2. Vulnerability Scanning
- Conducted a comprehensive scan of the Metasploitable system using **Nessus**.
- Identified security issues, including:
  - Outdated software versions.
  - Misconfigured services.
  - Exposed sensitive data.

### 3. Exploitation
- Utilized the **Metasploit Framework** to exploit the identified vulnerabilities, focusing on:
  - Local File Inclusion (LFI) vulnerabilities.
  - Misconfigurations that allowed privilege escalation.
- Successfully escalated privileges, gaining root access to the Metasploitable system.

### 4. Post-Exploitation
- Conducted further analysis to assess the extent of the compromise:
  - Extracted sensitive information.
  - Checked for potential backdoors or persistence mechanisms for future access.

## Key Learnings
- **Understanding of Vulnerabilities**: Enhanced understanding of common privilege escalation techniques and the importance of regular security assessments.
- **Hands-On Experience**: Valuable hands-on experience with industry-standard tools like Metasploit and Nessus.
- **Improved Problem-Solving Skills**: Sharpened analytical and problem-solving skills through navigating the complexities of exploiting vulnerabilities.

## Conclusion
The **Privilege Escalation on Metasploitable** project was instrumental in developing practical skills in penetration testing and vulnerability assessment, equipping me with the knowledge and tools necessary to effectively identify and mitigate security risks in real-world environments.

## GitHub Project
- Privilege Escalation on Metasploitable - [GitHub Project](https://github.com/sammyoflightup/Privilege-Escalation-on-Metasploitable)
