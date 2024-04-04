# Road Map for Cybersecurity (Based on My Experience)
## Introduction
Road Map for Cybersecurity based on my experience.

# Prerequisites for Learning Hacking (don't worry even if you don't have any software prerequisites).
## Hardware
1. **Personal Computer:**
   - A reliable computer with decent processing power and memory (prefered 8gb ram with 512 ssd and atleast 8 cores)

2. **Network Interface Card (NIC):**
   - Essential for network communication and packet analysis.

3. **External Storage:**
   - Additional storage space for tools, scripts, and captured data.

## Software
1. **Operating System:**
   - Linux distributions like Kali Linux or Parrot OS are commonly used for hacking due to their built-in security tools.

2. **Virtualization Software:**
   - Tools like VirtualBox or VMware for creating virtual environments to practice without affecting your main system.

3. **Networking Tools:**
   - Wireshark for packet analysis, Nmap for network scanning, and Netcat for network communication.

4. **Programming Languages:**
   - Learn at least one scripting language such as Python for writing custom scripts and automation.

5. **Security Tools:**
   - Metasploit Framework, Burp Suite, and John the Ripper for penetration testing and ethical hacking.

6. **Encryption Tools:**
   - GPG (GNU Privacy Guard) for secure communication and file encryption.

7. **Web Development Basics:**
   - Understand web technologies, HTML, CSS, and JavaScript for web application security testing.

8. **Databases:**
   - Basic knowledge of databases and SQL for exploiting database vulnerabilities.

## Skills and Knowledge
1. **Networking Basics:**
   - Understand TCP/IP, subnetting, and network protocols.

2. **Cybersecurity Fundamentals:**
   - Familiarity with basic cybersecurity concepts and practices.

3. **Ethical Hacking Ethics:**
   - Develop a strong understanding of ethical hacking principles and legal considerations.


# Starting Point 
- **Basic Operating of Windows:** Downloads and Installations, copy paste and some other shortcuts.
- **Base Terminalogy:** Base terminology if you just learned using of computers.

# Lets Start with Learning Types of OS can be used for hacking:

## Kali Linux
- **Description:** A Debian-based Linux distribution designed for digital forensics, penetration testing, and security auditing.
- **Features:**
  - Pre-installed tools for various hacking and penetration testing tasks.
  - Regularly updated with the latest security tools.

## Parrot Security OS
- **Description:** A Debian-based security-oriented operating system designed for penetration testing, ethical hacking, and forensic analysis.
- **Features:**
  - Lightweight and designed for performance.
  - Includes a wide range of penetration testing tools.

## BackBox Linux
- **Description:** An Ubuntu-based Linux distribution focused on penetration testing and security assessment.
- **Features:**
  - User-friendly interface.
  - Pre-installed tools for penetration testing and ethical hacking.

## BlackArch Linux
- **Description:** An Arch Linux-based distribution for penetration testers and security researchers.
- **Features:**
  - Large repository of tools for various security testing tasks.
  - Rolling release model for up-to-date tools.

## Windows Subsystem for Linux (WSL)
- **Description:** A compatibility layer for running Linux binary executables natively on Windows 10.
- **Features:**
  - Allows the use of Linux tools on a Windows system.
  - Useful for those who prefer a Windows environment.

## Samurai Web Testing Framework
- **Description:** A virtual machine (VM) based on Ubuntu focused on web application penetration testing.
- **Features:**
  - Includes a set of tools for web application security testing.
  - Specifically tailored for web application assessments.

## Live Hacking OS
- **Description:** A Linux distribution designed for ethical hacking, penetration testing, and forensic analysis.
- **Features:**
  - Customized for ease of use in ethical hacking scenarios.
  - Includes various security tools.

## Security Onion
- **Description:** A Linux distribution for intrusion detection, network security monitoring, and log management.
- **Features:**
  - Integrates several open-source security tools for network analysis.
  - Designed for monitoring and defending networks.

## Conclusion
These operating systems are commonly used in ethical hacking environments to provide a dedicated platform with pre-installed tools for various security testing tasks.Throughout our hacking journey, we predominantly rely on Kali Linux as our primary operating system if you had experience in any other operating system feel free to use it.

# How to Install Kali Linux in VirtualBox

Follow these steps to install Kali Linux in VirtualBox:

## Step 1: Download Kali Linux ISO
1. Go to the [official Kali Linux download page](https://www.kali.org/downloads/).
2. Choose the appropriate ISO file for your system (e.g., 64-bit or 32-bit).
3. Download the ISO file to your computer.

## Step 2: Install VirtualBox
1. Download and install [Oracle VM VirtualBox](https://www.virtualbox.org/) on your host machine.
2. Follow the installation instructions provided by VirtualBox.

## Step 3: Create a New Virtual Machine
1. Open VirtualBox and click on the "New" button.
2. Enter a name for your virtual machine (e.g., "Kali Linux").
3. Select "Linux" as the type and "Debian" as the version.
4. Click "Next" to proceed.

## Step 4: Assign Memory (RAM)
1. Choose the amount of RAM to allocate to the virtual machine. It's recommended to allocate at least 2 GB for a smooth experience.
2. Click "Next" to proceed.

## Step 5: Create a Virtual Hard Disk
1. Select "Create a virtual hard disk now" and click "Create."
2. Choose the hard disk file type (typically VDI) and click "Next."
3. Select the storage on the physical hard disk (usually "Dynamically allocated") and click "Next."
4. Choose the size of the virtual hard disk and click "Create."

## Step 6: Configure Virtual Machine Settings
1. Select your newly created virtual machine from the VirtualBox manager.
2. Click on "Settings" and navigate to the "Storage" tab.
3. Click on the empty disk icon under "Controller: IDE" and select "Choose a disk file."
4. Navigate to the location where you downloaded the Kali Linux ISO file and select it.
5. Click "OK" to save the settings.

## Step 7: Install Kali Linux
1. Start the virtual machine by clicking the "Start" button in VirtualBox.
2. Follow the on-screen instructions to install Kali Linux on the virtual machine.
3. Choose your language, location, keyboard layout, and other preferences during the installation process.
4. When prompted, select the option to "Graphical Install" for an easier installation process.
5. Complete the installation by following the prompts to set up user accounts, passwords, and disk partitions.

## Step 8: Post-Installation Setup
1. After the installation is complete, restart the virtual machine.
2. Log in to Kali Linux using the credentials you created during the installation process.
3. Update the system and install any additional packages or tools as needed.

You have now successfully installed Kali Linux in VirtualBox. 

## Alternative Method
Skip installation and download already installed Virtual Machine (VM) You can watch this video for that: ``` https://youtu.be/9GL-hDqMXwY ``` (video language Telugu)

# Familiarizing with Kali Linux

## Interface Overview

### Desktop Environment
Kali Linux typically uses the Xfce desktop environment. Navigate through the menu and explore the various tools available.

### Terminal
The terminal is your command-line interface. Open it by right-clicking on the desktop and selecting "Open Terminal."

## File System

### Root Directory
- `/`: The root directory is the top-level directory in the Linux file system hierarchy.

### Home Directory
- `/home/username`: This is the home directory for the user account you are logged in with.

### Key Directories
- `/etc`: Configuration files.
- `/usr`: User binaries and program files.
- `/var`: Variable data, such as logs and temporary files.

## Basic Commands

### File and Directory Commands
1. `ls`: List files and directories.
2. `cd`: Change directory.
3. `pwd`: Print working directory.
4. `mkdir`: Create a directory.
5. `touch`: Create an empty file.

### System Information
1. `uname -a`: Display system information.
2. `cat /etc/os-release`: Show information about the operating system.

### Package Management
1. `apt update`: Update package lists.
2. `apt upgrade`: Upgrade installed packages.
3. `apt install package_name`: Install a new package.

### User Management
1. `whoami`: Display the current username.
2. `sudo`: Execute a command with superuser privileges.
3. `useradd`: Add a new user.
4. `passwd`: Change user password.

### Network Commands
1. `ifconfig`: Show network interfaces.
2. `ping`: Test network connectivity.
3. `netstat`: Display network statistics.

### Full Command List
```
https://github.com/pranay-root/CEH_Practical_Cmds
```

## Conclusion
This brief guide provides a starting point for familiarizing yourself with Kali Linux. Explore the tools, directories, and commands to become more comfortable with this powerful operating system designed for penetration testing and ethical hacking.

# Networking Basics Understanding IP Addresses

## What is an IP Address?

### Definition
- **IP Address:** A unique numerical label assigned to each device connected to a computer network. It will enable us to communicate with other devices

### Types of IP Addresses
1. **IPv4 Address:**
   - Consists of four sets of numbers separated by dots (e.g., 192.168.0.1).
   - Limited address space.

2. **IPv6 Address:**
   - Longer address format with hexadecimal characters (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
   - Introduced to address the limitations of IPv4.

## Finding Your IP Address in Kali Linux

### Using the Command Line
1. Open the terminal in Kali Linux.
2. Use the following command to display your IP address:
   ```bash
   ifconfig
   ```

## Finding Your IP Address in Windows

### Using the Command Line
1. Open the command Prompt in windows using search bar.
2. Use the following command to display your IP address:
   ```bash
   ipconfig
   ```
   # Understanding IPv4 Addresses 

## IPv4 Address Structure

### Format
- An IPv4 address consists of four sets of numbers separated by dots, for example, `192.168.0.1`.

### Network Portion and Host Portion
- **Network Portion:** The leftmost sets of numbers in the address. eg:``` In ip address 192.168.0.29 Network Portion is "192.168" ```
- **Host Portion:** The rightmost set of numbers in the address. eg:``` In ip address 192.168.0.29 Host Portion is "0.29" ```

### Subnet Mask
- A subnet mask is used to determine the network and host portions of an IP address.
- It consists of a series of binary '1's followed by '0's (e.g., `255.255.255.0`).

## Identifying Network and Host

### Example1 
- If your IP address is `192.168.0.1` with a subnet mask of `255.255.255.0`:
  - **Network Portion:** `192.168.0`
  - **Host Portion:** `1`
  - 
### Example 2
- If your IP address is `172.16.2.5` with a subnet mask of `255.255.0.0`:
  - **Network Portion:** `172.16`
  - **Host Portion:** `2.5

### Determining Subnet Size
- The number of '0's in the subnet mask determines the size of the subnet.

## Dynamic Host Configuration Protocol (DHCP)

### Dynamic IP Address Assignment
- When connected to the internet, your ISP (Internet Service Provider) assigns your device a dynamic IP address.
- The IP address is leased for a specific duration and may change over time.

### DHCP in Kali Linux
- Kali Linux, like many operating systems, can use DHCP to obtain an IP address automatically.
- To configure DHCP in Kali Linux, ensure your network interface is set to obtain an IP address automatically.

## Static IP Address

### Fixed IP Address Assignment
- A static IP address is manually configured and does not change.
- Useful for devices that require a consistent IP address.

### Configuring Static IP in Kali Linux
- Edit the network configuration file:
  ```bash
  nano /etc/network/interfaces
  ```
# Important Networking Protocols

## 1. TCP/IP (Transmission Control Protocol/Internet Protocol)
- **Description:** The fundamental suite of protocols for communication on the Internet.
- **Protocols Included:**
  - TCP (Transmission Control Protocol): Ensures reliable, connection-oriented communication.
  - IP (Internet Protocol): Manages addressing and routing.

## 2. HTTP/HTTPS (Hypertext Transfer Protocol/Secure)
- **Description:** Used for transferring web content between clients and servers.
- **Port:** 80 (HTTP), 443 (HTTPS)

## 3. FTP (File Transfer Protocol)
- **Description:** Facilitates the transfer of files between a client and server.
- **Port:** 21

## 4. SMTP (Simple Mail Transfer Protocol)
- **Description:** Sends emails between servers.
- **Port:** 25

## 5. POP3 (Post Office Protocol version 3)
- **Description:** Retrieves emails from a server.
- **Port:** 110

## 6. IMAP (Internet Message Access Protocol)
- **Description:** Retrieves and manages emails with advanced features.
- **Port:** 143

## 7. DNS (Domain Name System)
- **Description:** Resolves domain names to IP addresses.
- **Port:** 53

## 8. DHCP (Dynamic Host Configuration Protocol)
- **Description:** Assigns IP addresses dynamically to devices on a network.
- **Port:** 67/68

## 9. SNMP (Simple Network Management Protocol)
- **Description:** Manages and monitors network devices.
- **Port:** 161/162

## 10. ICMP (Internet Control Message Protocol)
- **Description:** Used for error reporting and network diagnostics (e.g., ping).
- **Does not have a specific port.**

## 11. ARP (Address Resolution Protocol)
- **Description:** Maps IP addresses to MAC addresses in a local network.
- **Does not have a specific port.**

## 12. HTTPS (Hypertext Transfer Protocol Secure)
- **Description:** A secure version of HTTP, encrypted with SSL/TLS.
- **Port:** 443

## 13. SSH (Secure Shell)
- **Description:** Provides secure remote access and command execution.
- **Port:** 22

## 14. VPN (Virtual Private Network)
- **Description:** Secures communication over a public network by creating a private network.
- **Uses various protocols like IPsec, OpenVPN, and others.**

## Conclusion
These protocols form the backbone of modern networking, enabling seamless communication and data exchange between devices. Understanding these protocols is essential for network administrators and security professionals.

# Understanding Ports and Their Services

## What is a Port?

- A port is a virtual endpoint for communication in a network.
- It allows multiple services to run on a single device by using different port numbers.

## Types of Ports

### Well-Known Ports (0-1023)
- Reserved for common services and protocols.
- Examples:
  - Port 80: HTTP (Hypertext Transfer Protocol)
  - Port 443: HTTPS (HTTP Secure)
  - Port 21: FTP (File Transfer Protocol)
  - Port 22: SSH (Secure Shell)

### Registered Ports (1024-49151)
- Assigned by IANA (Internet Assigned Numbers Authority) for specific services.
- Examples:
  - Port 8080: Alternative HTTP port
  - Port 3306: MySQL database
  - Port 3389: Remote Desktop Protocol (RDP)

### Dynamic or Private Ports (49152-65535)
- Used for dynamic, private, or temporary purposes.
- Typically chosen by client applications for temporary use.

## Commonly Associated Services

### HTTP (Hypertext Transfer Protocol)
- **Port:** 80
- **Description:** Used for unencrypted web traffic.

### HTTPS (HTTP Secure)
- **Port:** 443
- **Description:** Used for secure, encrypted web traffic.

### FTP (File Transfer Protocol)
- **Port:** 21
- **Description:** Used for file transfers between a client and a server.

### SSH (Secure Shell)
- **Port:** 22
- **Description:** Used for secure remote access and command execution.

### DNS (Domain Name System)
- **Port:** 53
- **Description:** Resolves domain names to IP addresses.

### SMTP (Simple Mail Transfer Protocol)
- **Port:** 25
- **Description:** Used for sending email.

### POP3 (Post Office Protocol version 3)
- **Port:** 110
- **Description:** Retrieves emails from a server.

### IMAP (Internet Message Access Protocol)
- **Port:** 143
- **Description:** Retrieves emails with more features than POP3.

### SNMP (Simple Network Management Protocol)
- **Port:** 161/162
- **Description:** Manages and monitors network devices.

## Conclusion
Ports are essential for enabling communication between devices on a network. Understanding the types of ports and their associated services is crucial for network administration and security.

# Types of Hackers

## 1. **Black Hat Hackers**
- **Description:** Malicious hackers who exploit systems for personal gain, often engaging in illegal activities.
- **Motivation:** Financial gain, data theft, sabotage, or causing harm.

## 2. **White Hat Hackers (Ethical Hackers)**
- **Description:** Security professionals who use their skills to identify and fix vulnerabilities, typically employed by organizations to enhance security.
- **Motivation:** Protecting systems, networks, and data from unauthorized access.

## 3. **Grey Hat Hackers**
- **Description:** Hackers who fall between black hat and white hat categories, sometimes exploiting systems without permission but with the intent to notify the owner and help fix the vulnerabilities.
- **Motivation:** Mixed, ranging from curiosity to a desire for recognition.

## 4. **Hacktivists**
- **Description:** Activists who use hacking techniques to advance their social, political, or environmental causes.
- **Motivation:** Promoting a specific agenda, exposing perceived injustices, or raising awareness.

## 5. **Script Kiddies (Skiddies)**
- **Description:** Individuals who use pre-written scripts or tools without fully understanding the underlying hacking techniques.
- **Motivation:** Often seeking to gain notoriety without deep technical knowledge.

## 6. **Nation-State or State-Sponsored Hackers**
- **Description:** Hackers employed or supported by governments for cyber espionage, intelligence gathering, or strategic disruption.
- **Motivation:** National security, political influence, economic advantage.

## 7. **Cyber Criminals**
- **Description:** Individuals or groups engaged in cybercrime activities for financial gain, including identity theft, credit card fraud, and ransomware attacks.
- **Motivation:** Monetary profit.

## 8. **Crackers**
- **Description:** Individuals who specialize in circumventing software protections (e.g., breaking software licenses or copy protection mechanisms).
- **Motivation:** Bypassing security measures for unauthorized access.

## 9. **Social Engineers**
- **Description:** Hackers who manipulate human psychology to trick individuals into revealing sensitive information.
- **Motivation:** Gathering information, bypassing security measures through human interaction.

## 10. **Bug Bounty Hunters**
- **Description:** Ethical hackers who search for and report security vulnerabilities in software or systems, often participating in bug bounty programs.
- **Motivation:** Earning rewards or recognition for responsible disclosure.

## Conclusion
The diverse motivations and activities of hackers highlight the complexity of the cybersecurity landscape. Understanding these categories helps organizations and individuals develop more targeted and effective cybersecurity strategies.

# Common Types of Cyber Attacks

## 1. **Phishing Attacks**
- **Description:** Deceptive attempts to trick individuals into revealing sensitive information, such as passwords or financial details.
- **Example:** Email phishing, where attackers send fraudulent emails posing as legitimate entities.

## 2. **Malware**
- **Description:** Malicious software designed to harm or exploit systems or users.
- **Types:**
  - **Viruses:** Self-replicating programs that attach to other files.
  - **Worms:** Independent programs that can spread across networks.
  - **Trojans:** Disguised as legitimate software, but performs malicious actions.
  - **Ransomware:** Encrypts files and demands a ransom for decryption keys.

## 3. **Man-in-the-Middle (MitM) Attacks**
- **Description:** Attackers intercept and potentially alter communication between two parties without their knowledge.
- **Example:** Eavesdropping on unsecured Wi-Fi networks.

## 4. **Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) Attacks**
- **Description:** Overloading a system, network, or service to disrupt its availability.
- **DoS Example:** Flooding a website with traffic to make it unavailable.
- **DDoS Example:** Coordinating multiple systems to overwhelm a target with traffic.

## 5. **SQL Injection**
- **Description:** Exploiting vulnerabilities in database systems by injecting malicious SQL code.
- **Example:** Entering manipulated data into a web form to access or manipulate a database.

## 6. **Cross-Site Scripting (XSS)**
- **Description:** Injecting malicious scripts into web pages viewed by other users.
- **Example:** Attacker injects scripts into a forum post that, when viewed, steal user data.

## 7. **Social Engineering Attacks**
- **Description:** Manipulating individuals to divulge confidential information through psychological manipulation.
- **Example:** Pretending to be a trustworthy entity to trick employees into revealing sensitive information.

## 8. **Zero-Day Exploits**
- **Description:** Attacks that exploit vulnerabilities unknown to the software vendor.
- **Example:** Exploiting a recently discovered software vulnerability before a patch is released.

## 9. **Drive-By Downloads**
- **Description:** Malicious software is downloaded and installed on a user's device without their knowledge.
- **Example:** Exploiting vulnerabilities in a web browser to download malware when a user visits a compromised website.

## 10. **IoT (Internet of Things) Exploitation**
- **Description:** Targeting vulnerabilities in connected devices to gain unauthorized access or disrupt functionality.
- **Example:** Exploiting security flaws in smart home devices.

## Conclusion
Being aware of these common types of cyber attacks is essential for individuals and organizations to implement effective cybersecurity measures and protect against potential threats. Regular security awareness training and staying updated on emerging threats are key elements of a robust cybersecurity strategy.









