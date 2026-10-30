# Cybersecurity Lab Setup using VirtualBox and Kali Linux

## Week 1 – Project Module 1 | Networkwalks Cybersecurity Internship

### Project Overview
This project focuses on setting up a cybersecurity testing lab using Oracle VirtualBox and Kali Linux. The lab provides an isolated environment for learning and practicing basic cybersecurity and networking concepts.

### Objectives
- Set up a Kali Linux virtual machine.
- Configure a NAT Network in VirtualBox.
- Assign a static IP address to Kali Linux.
- Verify network and internet connectivity.
- Configure clipboard and file-sharing features.
- Create a virtual machine snapshot.

### Lab Configuration

| Component | Configuration |
|---|---|
| Virtualization Tool | Oracle VirtualBox |
| Operating System | Kali Linux |
| Network Mode | NAT Network |
| Network Name | CyberLab |
| Network Subnet | 10.0.0.0/24 |
| Kali Linux IP | 10.0.0.2/24 |
| Gateway | 10.0.0.1 |
| Shared Folder | /downloads |

### Implementation and Testing

**1. Virtual Machine Setup**

Created a separate Kali Linux virtual machine in Oracle VirtualBox for cybersecurity lab activities.

**2. Network Configuration**

Created a NAT Network named CyberLab and configured the Kali Linux network interface with a static IP address.

**3. Connectivity Verification**

Used terminal commands to verify:
- Network interface configuration
- Default gateway connectivity
- Internet connectivity
- DNS resolution

**4. Shared Folder and Clipboard**

Configured the VirtualBox shared folder, bidirectional clipboard and drag-and-drop settings to support file exchange between the host and virtual machine.

**5. Snapshot**

Created a snapshot named `Networkwalks-Kali-WK1-Setup` to preserve the completed lab configuration.

### Screenshots

#### 1. Kali Linux Virtual Machine
![Virtual Machine](screenshots/01-virtualbox-vm.png)

#### 2. Network Configuration
![Network Setup](screenshots/02-network-setup.png)

#### 3. Terminal Commands and Connectivity Tests
![Terminal Commands](screenshots/03-terminal-commands.png)

#### 4. Virtual Machine Snapshot
![VM Snapshot](screenshots/04-vm-snapshot.png)

### Learning Outcomes
- Learned basic VirtualBox configuration.
- Understood NAT Network setup and static IP configuration.
- Practiced network and internet connectivity testing.
- Learned how to configure shared folders and clipboard integration.
- Understood the importance of virtual machine snapshots.

### Conclusion
Successfully completed the Week 1 Project Module 1 lab setup. This practical exercise provided hands-on experience with virtualization, basic networking and Kali Linux.

### Internship
**Organization:** Networkwalks  
**Program:** Cybersecurity Internship  
**Module:** Week 1 – Project Module 1

<img width="1920" height="1080" alt="Virtual machine with Kali" src="https://github.com/user-attachments/assets/7e455193-bb18-4a21-92df-be4201372e18" />
<img width="977" height="652" alt="Network setup" src="https://github.com/user-attachments/assets/3bf345b9-7fe4-4c71-99e3-6eb4448fb6ab" />
<img width="1920" height="983" alt="Terminal commands" src="https://github.com/user-attachments/assets/03c6832f-2e8a-4f80-9da2-5efa95479f77" />
<img width="1920" height="1080" alt="VM snapshot" src="https://github.com/user-attachments/assets/28071f2e-6c90-46db-add3-9df7d363847e" />



