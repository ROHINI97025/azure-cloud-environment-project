# Azure Cloud Environment Project

## 📌 Project Overview

This project demonstrates hands-on practice with **Microsoft Azure administration and cloud infrastructure**. The project involved deploying and managing a Windows Virtual Machine, configuring basic networking, creating Azure Blob Storage, reviewing Azure Monitor metrics, and troubleshooting common cloud connectivity and storage scenarios.

The project was completed as a practical learning exercise to build foundational skills relevant to **IT Support, Cloud Support, Azure Administration, and Technical Support** roles.



## 🏗️ Architecture

```text
                         Microsoft Azure
                               │
                       Resource Group
                    RG-ITSupport-Practice
                               │
              ┌────────────────┴────────────────┐
              │                                 │
       Virtual Network                    Storage Account
              │                         itsupportpractice2026
            Subnet                              │
              │                           Blob Container
             NIC                           practice-files
              │
       ┌──────┴──────┐
       │             │
  Private IP      Public IP
       │             │
       └──────┬──────┘
              │
             NSG
              │
      Windows Virtual Machine
       VM-ITSupport-Practice
              │
             RDP
              │
       Azure Monitor
```

---

## ☁️ Azure Resources Used

| Resource | Purpose |

| Resource Group | Organize and manage project resources |
| Virtual Network | Provide network connectivity for the VM |
| Subnet | Provide a logical network segment |
| Network Interface (NIC) | Connect the VM to the virtual network |
| Public IP | Enable remote access to the VM |
| Private IP | Provide internal network connectivity |
| Network Security Group (NSG) | Control network traffic |
| Windows Virtual Machine | Provide a Windows cloud computing environment |
| Storage Account | Store cloud data |
| Blob Container | Store files as objects |
| Azure Monitor | Review VM performance and network metrics |



## 🔧 Implementation Steps

### 1. Created the Resource Group

Created the Azure Resource Group:

`RG-ITSupport-Practice`

The resource group was used to organize the Azure resources associated with the project.

### 2. Configured Virtual Networking

Configured the basic networking components required for the virtual machine:

- Virtual Network
- Subnet
- Network Interface
- Private IP address
- Public IP address
- Network Security Group

The network configuration provided connectivity between the VM and Azure network resources.

### 3. Deployed a Windows Virtual Machine

Created the Windows Virtual Machine:

`VM-ITSupport-Practice`

The VM was used to practice basic Azure administration and remote connectivity.

### 4. Connected to the VM Using RDP

Used **Remote Desktop Protocol (RDP)** to connect to the Windows virtual machine and verify remote access.

This provided practical experience with remote administration of a cloud-based Windows system.

### 5. Created Azure Storage

Created the Storage Account:

`itsupportpractice2026`

Created the Blob container:

`practice-files`

The storage environment was used to practice uploading and accessing files using Azure Blob Storage.

### 6. Reviewed Azure Monitor Metrics

Used **Azure Monitor** to review resource and VM-related metrics, including:

- Network In Total
- Network Out Total
- Disk Read Bytes
- Disk Write Bytes

This provided practical exposure to basic cloud monitoring and resource performance observation.



## 🛠️ Troubleshooting Scenarios

### 1. RDP Connection Issue After VM Deallocation

**Problem:**  
After the virtual machine was deallocated and started again, the previous public IP address was no longer valid for the RDP connection.

**Troubleshooting:**  
Checked the VM networking configuration and verified the current public IP address.

**Resolution:**  
Used the updated public IP address to establish the RDP connection successfully.

**Learning:**  
Public IP configuration should be verified when troubleshooting remote connectivity to Azure VMs.



### 2. Network Configuration / Connectivity Issue

**Problem:**  
A network connectivity issue was observed during the project.

**Troubleshooting:**  
Checked the Virtual Network, subnet, Network Interface, IP configuration, and Network Security Group settings.

**Resolution:**  
Verified and corrected the relevant network configuration and retested connectivity.

**Learning:**  
Azure VM connectivity depends on correctly configured network components and security rules.



### 3. Blob Storage Upload / Access Issue

**Problem:**  
An issue occurred while working with file upload/access in the Blob Storage environment.

**Troubleshooting:**  
Checked the Storage Account, Blob container configuration, and access settings.

**Resolution:**  
Corrected the relevant configuration and verified that the blob could be accessed successfully.

**Learning:**  
Storage configuration and access settings should be checked when troubleshooting Azure Blob Storage issues.



## 📊 Monitoring

Azure Monitor was used to review resource activity and performance-related metrics.

The following metrics were reviewed during the project:

- **Network In Total** — observed incoming network traffic
- **Network Out Total** — observed outgoing network traffic
- **Disk Read Bytes** — observed disk read activity
- **Disk Write Bytes** — observed disk write activity

Monitoring these metrics helped provide practical understanding of how cloud resources can be observed after deployment.



## 📸 Project Screenshots

Screenshots and detailed project documentation are available in the project PDF.

### Documentation

📄 **[View Azure Administration Project Documentation](docs/Azure%20Administration.pdf)**

The PDF contains the detailed implementation documentation and screenshots from the project.



## 💰 Cost & Cleanup

This project was created as a learning and practice environment.

To avoid unnecessary Azure usage and potential charges, resources should be stopped or deleted after completing the required practice.

Recommended cleanup:

1. Stop/delete the Virtual Machine
2. Remove unused networking resources
3. Remove unused storage resources
4. Delete the Resource Group when the project is no longer required

Deleting the Resource Group can remove the associated resources together, so it should only be done after confirming that the resources are no longer needed.



## 🎯 Key Learnings

Through this project, I gained practical exposure to:

- Microsoft Azure fundamentals
- Azure Resource Groups
- Windows Virtual Machines
- Virtual Networks and Subnets
- Network Interfaces
- Public and Private IP addresses
- Network Security Groups
- Remote Desktop (RDP)
- Azure Blob Storage
- Azure Monitor
- Basic cloud troubleshooting
- Technical documentation
- Cloud resource management


## 🧰 Technologies & Services

- **Microsoft Azure**
- Azure Virtual Machines
- Azure Virtual Network
- Azure Storage / Blob Storage
- Azure Monitor
- Windows
- RDP
- Basic Networking



## 📄 Project Documentation

Detailed project documentation, including screenshots and implementation details, is available here:

**[Azure Administration Project PDF](docs/Azure%20Administration.pdf)**



## 👩‍💻 Author

**Rohini V**

B.E. Electronics & Communication Engineering | 2026

**Microsoft Azure Fundamentals (AZ-900) Certified**

Interested in entry-level opportunities in:

- IT Support
- Technical Support
- Cloud Support
- Azure Administration
- IT Operations

GitHub: **[ROHINI97025](https://github.com/ROHINI97025)**

**[Azure Administration Project Report](./Azure%20Administration.pdf)**

## Certification

Microsoft Azure Fundamentals – AZ-900
