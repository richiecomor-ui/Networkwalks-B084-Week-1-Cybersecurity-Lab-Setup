<div align="center">

# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>


---

# KALI LINUX VIRTUAL LAB PROJECT REPORT

## Installation, Configuration and Preparation of a Kali Linux Virtual Laboratory for Cybersecurity and Ethical Hacking Practice

**Prepared by:** Richard Comor

**Organization:** Network Walks

**Position:** Cybersecurity Intern
# KALI LINUX VIRTUAL LABORATORY PROJECT REPORT

## Installation, Configuration and Preparation of a Kali Linux Virtual Laboratory for Cybersecurity and Ethical Hacking Practice

**Prepared by:** Richard Comor  
**Organization:** Network Walks  
**Position:** Cybersecurity Intern  
**Project Date:** November 2026  
**Host Operating System:** Microsoft Windows  
**Virtualization Software:** Oracle VM VirtualBox  
**Guest Operating System:** Kali Linux 2026.3

---

# 1. PROJECT INFORMATION

| Project Details | Description |
|---|---|
| Project Title | Installation, Configuration and Preparation of a Kali Linux Virtual Laboratory |
| Author | Richard Comor |
| Organization | Network Walks |
| Position | Cybersecurity Intern |
| Project Category | Cybersecurity |
| Host Operating System | Microsoft Windows |
| Virtualization Platform | Oracle VM VirtualBox |
| Guest Operating System | Kali Linux 2026.3 |
| Project Type | Practical Technical Learning Project |
| Project Period | November 2026 |

# 2. PROJECT OVERVIEW

This project involved the successful installation, configuration, and preparation of a Kali Linux virtual laboratory using Oracle VM VirtualBox on a Windows computer.

The project was undertaken as part of my learning and professional development as a Cybersecurity Intern at Network Walks. The primary objective was to gain practical knowledge of Linux operating systems, virtualization technology, network configuration, and cybersecurity tools.

Kali Linux was selected because it is a specialized Linux distribution widely used in cybersecurity for penetration testing, vulnerability assessment, digital forensics, and security research.

Oracle VM VirtualBox was used to create a virtual environment that allowed Kali Linux to operate independently within the existing Windows operating system.

The project covered the installation of VirtualBox, preparation and registration of the Kali Linux virtual machine, network adapter configuration, IP address assignment, gateway configuration, and network connectivity testing.

The setup was successfully completed, providing a functional virtual laboratory for continued cybersecurity learning and practical exercises.

# 3. PROJECT OBJECTIVES

The main objectives of this project were:

1. To understand the fundamentals of virtualization and its applications in cybersecurity.
2. To install and configure Oracle VM VirtualBox.
3. To successfully install and run Kali Linux 2026.3 as a virtual machine.
4. To understand the relationship between host and guest operating systems.
5. To configure the virtual machine's network adapter.
6. To understand and apply IP addressing, subnet masks, default gateways, and DNS configuration.
7. To establish and test network connectivity within the virtual environment.
8. To develop practical Linux operating system and command-line skills.
9. To become familiar with the Kali Linux environment and its cybersecurity tools.
10. To develop technical troubleshooting and problem-solving skills.
11. To establish a functional laboratory for further cybersecurity training and ethical hacking practice.

# 4. PURPOSE OF THE LAB

The purpose of establishing this virtual laboratory was to create a practical and controlled learning environment for developing cybersecurity knowledge and technical skills.

As a Cybersecurity Intern at Network Walks, I recognized the importance of gaining hands-on experience with the tools, operating systems, and technologies commonly used in the cybersecurity industry.

The Kali Linux virtual laboratory provides an environment for learning Linux administration, understanding network communication, exploring security assessment tools, and developing practical ethical hacking skills.

The laboratory is intended to support learning activities such as:

- Linux command-line operations and system administration.
- Network discovery and analysis.
- IP addressing and network configuration.
- Introduction to vulnerability assessment.
- Penetration testing methodologies.
- Digital forensics fundamentals.
- Understanding cybersecurity threats and defensive techniques.

All security testing and practical exercises will be conducted within authorized environments and on systems for which permission has been granted.

# 5. LAB ARCHITECTURE

The virtual laboratory consists of three primary components:

**1. Windows Host Computer**

The physical computer running Microsoft Windows. It provides the hardware resources required to operate the virtual machine.

**2. Oracle VM VirtualBox**

The virtualization software installed on Windows. It provides the environment for creating, managing, and running the Kali Linux virtual machine.

**3. Kali Linux Virtual Machine**

The guest operating system running within VirtualBox. It provides the environment for cybersecurity learning, Linux administration, and practical security exercises.

**Virtual Network**

The Kali Linux virtual machine communicates through a configured virtual network adapter attached to a NAT Network named `NatNetwork`.

This architecture allows the virtual machine to access network resources through the configured virtual networking environment while remaining separate from the Windows host operating system.

# 6. LAB CONFIGURATION

The following configurations were used to establish the virtual laboratory.

## 6.1 Virtual Machine Configuration

| Configuration | Details |
|---|---|
| Host Operating System | Microsoft Windows |
| Virtualization Software | Oracle VM VirtualBox |
| Guest Operating System | Kali Linux 2026.3 |
| Network Adapter | Adapter 1 |
| Adapter Status | Enabled |
| Network Attachment | NAT Network |
| Network Name | NatNetwork |
| Adapter Type | Intel PRO/1000 MT Desktop (82540EM) |
| Promiscuous Mode | Allow All |
| Virtual Cable | Connected |

## 6.2 Network Configuration

The following IP addressing scheme was used for the laboratory:

| Network Parameter | Configuration |
|---|---|
| Network Address | 10.0.0.0 |
| IP Address | 10.0.0.2 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 10.0.0.1 |
| Network Type | NAT Network |

The network configuration was completed to enable communication between the Kali Linux virtual machine and the configured virtual network.

The network adapter was enabled, connected to the designated NAT Network, and configured to support the required network communication.

The IP address, subnet mask, and default gateway were configured according to the laboratory requirements. Network connectivity was subsequently tested.

# 7. LAB SETUP PROCEDURE

The following steps describe the process followed to successfully establish the Kali Linux virtual laboratory.

## Step 1: Preparing the Host Computer

The first step involved preparing a Windows computer to serve as the host operating system.

The computer provided the processing power, memory, and storage required to run the virtual machine.

## Step 2: Installing Oracle VM VirtualBox

Oracle VM VirtualBox was downloaded and installed on the Windows computer.

The software was selected because it supports virtualization and allows multiple operating systems to run on a single physical computer.

## Step 3: Downloading Kali Linux

The Kali Linux 2026.3 virtual machine package was downloaded using the Google Chrome browser.

The downloaded package contained the necessary virtual machine files required to run Kali Linux through VirtualBox.

## Step 4: Extracting the Installation Files

The downloaded Kali Linux archive was extracted into a designated folder on the computer.

The extracted files included the virtual machine configuration file and virtual hard disk file.

The `.vbox` file contained the virtual machine configuration, while the `.vdi` file contained the virtual hard disk.

## Step 5: Registering the Virtual Machine

The extracted Kali Linux virtual machine was registered in Oracle VM VirtualBox.

The existing virtual machine configuration file was located and added through VirtualBox Manager.

This allowed VirtualBox to recognize and manage the Kali Linux virtual machine.

## Step 6: Starting Kali Linux

After successful registration, the Kali Linux virtual machine was started.

The operating system booted successfully, providing access to the Kali Linux desktop environment.

## Step 7: Configuring the Network Adapter

The network configuration settings were accessed through:

VirtualBox Manager → Kali Linux → Settings → Network → Adapter 1.

The network adapter was enabled and configured as follows:

- Attached to: NAT Network.
- Network Name: NatNetwork.
- Adapter Type: Intel PRO/1000 MT Desktop (82540EM).
- Promiscuous Mode: Allow All.
- Cable Connected: Enabled.

The configuration was saved and the virtual network adapter was connected.

## Step 8: Configuring the IP Address

The network settings within Kali Linux were configured using the IP addressing information provided for the laboratory.

The following parameters were applied:

- IP Address: 10.0.0.2
- Subnet Mask: 255.255.255.0
- Default Gateway: 10.0.0.1

The configuration established the required network addressing information for the virtual machine.

## Step 9: Configuring and Testing Network Connectivity

After configuring the network adapter and IP addressing information, network connectivity was tested.

The purpose of this stage was to confirm that Kali Linux could communicate through the configured virtual network.

The network configuration and connectivity checks formed part of the final verification process.

## Step 10: Finalizing the Virtual Laboratory

After completing the installation, registration, operating system configuration, and network setup, the virtual laboratory was successfully established.

Kali Linux was running within Oracle VM VirtualBox and was ready to serve as the foundation for further cybersecurity learning and practical exercises.

# 8. PROBLEMS ENCOUNTERED AND SOLUTIONS

During the setup process, several technical challenges were encountered. These challenges provided opportunities to develop troubleshooting and problem-solving skills.

| Problems Encountered | Solutions Implemented |
|---|---|
| VirtualBox initially could not locate the Kali Linux virtual machine. | Located the extracted virtual machine configuration file and registered the existing machine through VirtualBox Manager. |
| VirtualBox displayed difficulties opening the virtual machine. | Investigated the virtual machine registration and file-location settings and corrected the configuration. |
| Difficulties locating and managing extracted installation files. | Organized the extracted virtual machine files in the appropriate storage location. |
| Kali Linux initially displayed a disconnected network status. | Examined the virtual network adapter settings, enabled the adapter, selected the correct NAT Network, and reconnected the virtual cable. |
| Network connectivity was not immediately established. | Reviewed the network configuration, IP addressing, and gateway settings, then performed network connectivity checks. |

## 8.1 Lessons from Troubleshooting

The troubleshooting process demonstrated that successful virtualization requires more than simply installing an operating system.

Correct file management, virtual machine registration, network adapter configuration, and proper IP addressing are all essential components.

I also learned the importance of identifying the source of technical problems and applying appropriate solutions rather than immediately reinstalling software or making unnecessary changes.

# 9. WHAT I LEARNED

The project provided valuable practical knowledge and experience in several areas of information technology and cybersecurity.

**1. Understanding Virtualization**

I learned how virtualization allows multiple operating systems to run on a single physical computer using software such as Oracle VM VirtualBox.

**2. Understanding Host and Guest Operating Systems**

I gained practical knowledge of how a host operating system supports and manages a guest operating system within a virtual environment.

**3. Introduction to Kali Linux**

I became familiar with Kali Linux and its importance as a specialized operating system for cybersecurity professionals.

**4. Virtual Machine Management**

I learned how to download, extract, register, start, and manage virtual machine files.

**5. Network Configuration**

I gained practical exposure to virtual network adapters, NAT Network configuration, IP addresses, subnet masks, and default gateways.

**6. Network Troubleshooting**

I developed a better understanding of how network connectivity problems can be investigated and resolved through configuration checks and Linux diagnostic commands.

**7. Linux Operating System Skills**

The project introduced me to the Kali Linux desktop environment and provided a foundation for learning Linux commands and system administration.

**8. Technical Problem-Solving**

Working through the installation and configuration challenges improved my ability to investigate technical issues systematically.

**9. Ethical Cybersecurity Practices**

I developed a better appreciation of the importance of authorization, responsible security testing, and the use of controlled laboratory environments.

# 10. TOOLS AND RESOURCES

The following tools and resources were used during the project:

| Tool or Resource | Purpose |
|---|---|
| Microsoft Windows | Host operating system |
| Oracle VM VirtualBox | Virtualization platform |
| Kali Linux 2026.3 | Cybersecurity learning environment |
| Google Chrome | Downloading installation files |
| VirtualBox Manager | Managing and configuring the virtual machine |
| Windows File Explorer | Managing virtual machine files |
| Linux Network Manager | Managing network connections |
| `nmcli` | Examining network device and connection status |
| NAT Network | Providing virtual network connectivity |

## Reference Materials

- Official Kali Linux Documentation: https://www.kali.org/docs/
- Kali Linux Downloads: https://www.kali.org/get-kali/
- Oracle VM VirtualBox User Manual: https://www.virtualbox.org/manual/

# 11. AUTHOR

**Name:** Richard Comor

**Organization:** Network Walks

**Position:** Cybersecurity Intern

## Author's Statement

I undertook this project as part of my learning and professional development during my cybersecurity internship at Network Walks.

The project provided an opportunity to gain practical exposure to Linux operating systems, virtualization technology, network configuration, and the foundational tools used in cybersecurity.

My objective was to establish a functional virtual laboratory that would support continuous learning, practical experimentation, and the development of technical skills required in the cybersecurity industry.

The experience strengthened my understanding of the importance of hands-on learning, technical troubleshooting, and continuous professional development.

# 12. CONCLUSION

The Kali Linux Virtual Laboratory project was successfully completed, providing a practical introduction to virtualization and cybersecurity laboratory preparation.

Through the installation and configuration of Oracle VM VirtualBox, preparation of Kali Linux, registration of the virtual machine, and network configuration, I gained valuable practical knowledge of how virtual environments are established and managed.

The successful completion of the laboratory setup represents an important step in my development as a Cybersecurity Intern at Network Walks.

The virtual environment will serve as a foundation for further learning in Linux administration, network security, vulnerability assessment, penetration testing, and ethical hacking.

The project also reinforced the importance of patience, problem-solving, documentation, and continuous learning in the cybersecurity profession.

# 13. PROJECT COMPLETION STATUS

The following table summarizes the activities undertaken and their completion status.

| Project Activity | Status |
|---|---|
| Oracle VirtualBox installation | Completed |
| Kali Linux 2026.3 preparation | Completed |
| Virtual machine registration | Completed |
| Kali Linux booting | Completed |
| Virtual network adapter configuration | Completed |
| Network connection troubleshooting | Completed |
| IP address and gateway configuration | Completed |
| Internet connectivity testing | Completed |
| Separate virtual machine clone | Not Completed |
| Further cybersecurity practical exercises | Planned |

# 14. PROJECT EVIDENCE AND SCREENSHOTS

Screenshots should be included in this section to provide visual evidence of the completed laboratory setup.

Recommended screenshots include:

1. Oracle VirtualBox Manager showing the registered Kali Linux virtual machine.
2. Kali Linux desktop showing the operating system running successfully.
3. VirtualBox network adapter settings showing the configured NAT Network.
4. Kali Linux network configuration showing the assigned IP address and gateway.
5. Terminal output showing successful network connectivity testing.

Each screenshot should have a figure number and a short description.

**Figure 1:** Oracle VirtualBox Manager displaying the Kali Linux virtual machine.

**Figure 2:** Kali Linux 2026.3 successfully running within VirtualBox.

**Figure 3:** Virtual network adapter configuration.

**Figure 4:** Kali Linux IP address and gateway configuration.

**Figure 5:** Network connectivity verification.

---

**END OF PROJECT REPORT**

**Prepared by: Richard Comor**  
**Cybersecurity Intern, Network Walks**
**Project Date:** November 2026

---
