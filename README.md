# Azure Cloud Environment – VM, Storage, Monitoring & Troubleshooting

A practical Azure administration project focused on basic cloud infrastructure, Windows VM management, networking, storage, monitoring, remote access, and troubleshooting.

## Project Objective

The objective of this project was to build and troubleshoot a basic cloud environment using Microsoft Azure and gain practical exposure to common Azure administration and IT support tasks.

## Azure Resources

- Resource Group: `RG-ITSupport-Practice`
- Virtual Machine: `VM-ITSupport-Practice`
- Storage Account: `itsupportpractice2026`
- Blob Container: `practice-files`

## Azure Services & Concepts

- Azure Virtual Machines
- Azure Resource Groups
- Azure Virtual Network (VNet)
- Subnet
- Network Interface (NIC)
- Public and Private IP addresses
- Network Security Group (NSG)
- Azure Storage Account
- Azure Blob Storage
- Azure Monitor
- Remote Desktop Protocol (RDP)

## Practical Work

### 1. Virtual Machine

- Deployed a Windows-based Azure Virtual Machine.
- Reviewed the VM overview and configuration.
- Practiced starting and stopping the VM.
- Reviewed the VM's associated networking resources.

### 2. Networking

Reviewed the VM's:

- Virtual Network (VNet)
- Subnet
- Network Interface (NIC)
- Private IP address
- Public IP address
- Network Security Group (NSG)

The networking configuration was also reviewed during connectivity troubleshooting.

### 3. Remote Access

Used Windows Remote Desktop Protocol (RDP) to access the Azure VM.

The VM's public IP address and RDP connection information were used to establish remote access.

### 4. Azure Storage

- Created an Azure Storage Account.
- Created a private Blob Storage container named `practice-files`.
- Uploaded a sample document.
- Verified the uploaded file in the container.

### 5. Monitoring

Reviewed Azure Monitor metrics associated with the VM, including:

- Network In Total
- Network Out Total
- Disk Read Bytes
- Disk Write Bytes

These metrics were examined to understand basic resource activity and their usefulness during troubleshooting.

## Troubleshooting Scenarios

### RDP Connection Failure

**Problem:**  
Unable to connect using a previously downloaded RDP file.

**Investigation:**  
Compared the public IP address stored in the RDP file with the current public IP address shown in Azure.

**Root Cause:**  
The RDP file contained an outdated public IP address.

**Resolution:**  
Verified the current public IP address and downloaded updated RDP connection information.

**Verification:**  
Used the updated configuration to establish the remote connection.

### VM Network Connectivity

**Problem:**  
The Azure VM may be running but remote access or network connectivity may not work as expected.

**Investigation:**  
Reviewed the VNet, subnet, NIC, IP configuration and NSG settings.

**Possible Cause:**  
Incorrect network configuration or an NSG rule restricting required traffic.

**Resolution:**  
Reviewed the relevant network configuration and access rules.

### Blob Storage Upload or Access

**Problem:**  
Unable to upload or access a file in Blob Storage.

**Investigation:**  
Checked the Storage Account, Blob container and access configuration.

**Resolution:**  
Verified the correct container and storage configuration and uploaded the sample file successfully.

## Skills Demonstrated

- Microsoft Azure Fundamentals
- Azure VM Administration
- Basic Cloud Infrastructure
- Azure Networking
- Network Troubleshooting
- Azure Blob Storage
- Azure Monitor
- RDP Troubleshooting
- Technical Documentation

## Project Documentation

The detailed project report with screenshots and practical observations is available here:

**[Azure Administration Project Report](./Azure%20Administration.pdf)**

## Certification

Microsoft Azure Fundamentals – AZ-900
