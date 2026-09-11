# NETWORKWALKS – Week 1 Cybersecurity Lab Setup

## 📌 Project Overview

This repository contains my Week 1 work completed as part of the Networkwalks Cybersecurity Program.

The objective was to build a basic cybersecurity virtual lab using VirtualBox and Kali Linux, configure the virtual network, and verify the lab environment.

---

## 🖥️ Lab Environment

### Host Machine

| Specification    | Details                                 |
| ---------------- | --------------------------------------- |
| Operating System | Windows 11                              |
| Processor        | Intel(R) Core(TM) i7-14700HX @ 2.10 GHz |
| RAM              | 16 GB                                   |

### Virtual Machine

| Specification           | Details                 |
| ----------------------- | ----------------------- |
| Virtualization Platform | Oracle VirtualBox 7.2.6 |
| Operating System        | Kali Linux 2026.2       |
| VM Memory               | 2048 MB (2 GB)          |
| Network Mode            | NAT Network             |
| NAT Network Name        | `NatNetwork`            |
| Network Range           | `10.0.0.0/24`           |
| Snapshot                | Created                 |

---

## ⚙️ Lab Setup

### 1. VirtualBox Setup

Oracle VirtualBox was used to create and manage the Kali Linux virtual machine for the cybersecurity lab.

![VirtualBox Setup](screenshots/Screenshot-1-Virtualbox.png)

---

### 2. Virtual Network Configuration

A NAT Network named `NatNetwork` was configured in VirtualBox using the required network range.

![Network Settings](screenshots/Screenshot-2-network-settings.png)

---

### 3. Kali Linux Virtual Machine

Kali Linux 2026.2 was configured as the virtual machine for the cybersecurity lab. The VM was allocated 2048 MB of memory.

![Kali Linux](screenshots/Screenshot-3-kali-linux.png)

---

### 4. Kali Linux Network Configuration

The Kali Linux VM was connected to the configured NAT Network and the network settings were configured accordingly.

![Kali Linux Network Settings](screenshots/Screenshot-4-kali-network-settings.png)

---

## 🛠️ Troubleshooting

### Problem Faced

During the initial setup, I took some time to understand how to configure the NAT Network in VirtualBox and connect the Kali Linux VM to the correct network.

### How I Solved It

I checked the VirtualBox network configuration and then reviewed the network settings inside Kali Linux. After connecting the VM to the correct NAT Network, I verified the configuration and continued with the lab setup.

This helped me understand how the VirtualBox virtual network and the Kali Linux network configuration work together.

---

## 📚 What I Learned

Through this week's practical work, I learned:

* How to set up a virtual cybersecurity lab using VirtualBox.
* How to configure a Kali Linux virtual machine.
* How to create and configure a NAT Network.
* How to connect a virtual machine to a specific VirtualBox network.
* How to configure network settings inside Kali Linux.
* How to troubleshoot basic virtual networking problems.
* The importance of creating a VM snapshot before continuing with future practical labs.

---

## 🔐 Disclaimer

This project was completed for educational and cybersecurity learning purposes.

All practical work was performed within my own virtual lab environment. Security tools and techniques should only be used on systems that you own or have explicit authorization to test.

Unauthorized access to systems or networks is illegal.

---

## 👤 Author

**Kishore B**

B.E. Computer Science and Engineering – Cyber Security
Jerusalem College of Engineering
