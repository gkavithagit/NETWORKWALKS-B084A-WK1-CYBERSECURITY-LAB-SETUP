🔐 Cybersecurity Lab Environment Setup – Kali Linux & Network Configuration

📌 Internship Details

- Internship: NetworkWalks Cybersecurity Internship
- Week: Week 1
- Project: Cybersecurity Lab Environment Setup
- Operating System: Kali Linux
- Virtualization Platform: Oracle VirtualBox
- Network Type: NAT Network
- Network Subnet: "10.0.0.0/24"
- Project Status: Completed ✅

---

🎯 1. Project Overview

The objective of this project was to build a basic cybersecurity lab environment using Kali Linux and configure its virtual network.

The project involved installing Kali Linux inside Oracle VirtualBox, creating a NAT Network, configuring the network subnet, and setting up the IP configuration inside Kali Linux.

This setup provides a controlled virtual environment for learning Linux, networking, and cybersecurity fundamentals.

---

🛠️ 2. Tools and Technologies Used

Tool| Purpose
Kali Linux| Cybersecurity-focused operating system
Oracle VirtualBox| Virtual machine management
NAT Network| Virtual networking and internet connectivity
IPv4| Network addressing
Linux Terminal| Network configuration and verification

---

⚙️ 3. Implementation Steps

Step 1: Kali Linux Installation

- Downloaded the Kali Linux ISO image.
- Created a virtual machine in Oracle VirtualBox.
- Configured the virtual machine resources.
- Installed Kali Linux successfully.
- Booted into the Kali Linux desktop environment.

Step 2: NAT Network Configuration

Configured a NAT Network in Oracle VirtualBox.

Network Details:

Configuration| Value
Network Type| NAT Network
Network Address| "10.0.0.0/24"
Subnet Mask| "255.255.255.0"
IP Version| IPv4

The NAT Network allows connected virtual machines to communicate through the configured virtual network and access external networks through network address translation.

Step 3: Kali Linux IP Configuration

Configured the IP settings inside the Kali Linux environment according to the assigned network subnet.

The IP configuration was used to connect the Kali Linux virtual machine to the configured NAT Network.

Network Configuration:

Parameter| Configuration
Network Subnet| "10.0.0.0/24"
Subnet Mask| "255.255.255.0"
IP Address| As configured in Kali Linux
Gateway| As configured in the NAT Network
Network Interface| Kali Linux virtual network adapter

Step 4: Network Configuration Verification

Used Linux terminal commands to inspect the network configuration.

Commands explored:

Check IP address:

ip addr

Display network interfaces:

ip link

Display routing information:

ip route

Check network connectivity:

ping -c 4 8.8.8.8

These commands help inspect IP addressing, network interfaces, routing information, and connectivity.

---

📚 4. Key Learnings

Through this project, I gained practical exposure to:

- Installing and configuring Kali Linux.
- Understanding virtualization using Oracle VirtualBox.
- Creating and configuring a NAT Network.
- Understanding IPv4 addressing.
- Configuring a virtual network subnet.
- Understanding subnet masks and network interfaces.
- Configuring and inspecting IP settings in Linux.
- Using Linux networking commands.
- Understanding basic virtual machine network connectivity.

---

🚀 5. Future Learning Goals

The configured cybersecurity lab will be used to explore:

- Advanced Linux commands.
- Networking fundamentals.
- TCP/IP protocols.
- Network scanning in authorized lab environments.
- Cybersecurity tools and techniques.
- Ethical hacking fundamentals.

---

🔗 6. Official Resources

- Kali Linux: https://www.kali.org/
- Oracle VirtualBox: https://www.virtualbox.org/

---

👩‍💻 Author

Kavitha G

BSc Computer Science | Cybersecurity Student

Currently developing practical skills in Python, Linux, Networking, and Cybersecurity.

---

⭐ Week 1 Project – NetworkWalks Cybersecurity Internship

Successfully Completed!
