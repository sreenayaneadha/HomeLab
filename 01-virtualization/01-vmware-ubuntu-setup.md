# VMware & Ubuntu Setup

## Objective

Set up the first virtual machine for the cybersecurity homelab and establish a controlled environment for future security exercises.

## Environment

* Host OS: Windows
* Hypervisor: VMware Workstation Pro
* Guest OS: Ubuntu Linux

## Setup

### 1. Download Ubuntu

Downloaded the Ubuntu Desktop ISO from the official Ubuntu website.

The ISO file is a disk image containing the files required to install Ubuntu. VMware uses this image as the virtual installation media (this is like a virtual CD basically).

### 2. Create the Virtual Machine

Created a new virtual machine in VMware Workstation Pro using the downloaded Ubuntu ISO.

Configured the VM to use Linux/Ubuntu as the guest operating system.

### 3. Allocate Virtual Hardware

Assigned virtual hardware resources to the Ubuntu VM, including:

* CPU cores (2)
* RAM (4 GB)
* Virtual disk storage (40 GB)
* Network adapter (DHCP)

The resources were allocated from the physical Windows host. The VM only receives the resources assigned to it rather than directly controlling the physical hardware.

### 4. Configure Virtual Networking

Configured the VMware virtual network adapter so that the Ubuntu VM could communicate with the host system and access the network.

The virtual network provides a layer between the Ubuntu guest and the physical network interface of the Windows host.

### 5. Install Ubuntu

Started the virtual machine and booted from the Ubuntu ISO.

Completed the Ubuntu installation process, including:

* Selecting the installation language
* Configuring the keyboard
* Creating a user account
* Creating the user password
* Selecting the installation disk
* Completing the installation

The Ubuntu installation was performed on the VM's virtual disk rather than the physical Windows drive.

### 6. Verify the Installation

After installation, booted into Ubuntu and verified that the operating system was functioning correctly.

Basic system and network functionality was tested before beginning cybersecurity exercises.

## Security Relevance

Virtualization provides an isolated environment where security configurations, tools, and experiments can be tested without directly modifying the Windows host.

The Ubuntu VM will serve as the initial system in the cybersecurity laboratory and will later be used for networking, Linux administration, security monitoring, and other cybersecurity exercises.

## Lessons Learned

* A virtual machine allows another operating system to run on the host computer.
* CPU, RAM, storage, and networking can be assigned virtually to the guest using physical resources.
* The VM's virtual disk is separate from the physical operating system's filesystem.
* VMware provides virtualized hardware and networking that allow the guest operating system to function like a separate computer.
