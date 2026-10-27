# Kali Linux Lab Setup — Week 1

## Project Overview

This is my first lab project for the Networkwalks cybersecurity program. The goal was to set up VirtualBox and Kali Linux and configure the network.

## Tools Used

- Oracle VirtualBox
- Kali Linux
- 7-Zip

## Lab Configuration

- **Virtual Machine:** Kali Linux
- **Network Type:** NAT Network
- **Network Address:** `10.0.0.0/24`
- **Kali IP Address:** `10.0.0.2/24`
- **Shared Folder:** Downloads

## Steps I Followed

1. Installed VirtualBox and prepared Kali Linux.
2. Created a NAT Network in VirtualBox.
3. Configured the network settings for Kali Linux.
4. Set up a shared folder to access Downloads.
5. Checked the network configuration.
6. Worked on clipboard and drag-and-drop settings.
7. Prepared a snapshot of the virtual machine.

## Problems and Solutions

I had difficulty accessing the shared Downloads folder at first. I checked the folder path and learned that Linux paths are case-sensitive. I was then able to access the folder using `/media/sf_Downloads`.

## What I Learned

- How to use VirtualBox and Kali Linux.
- Basic virtual network configuration.
- How to set up and access shared folders.
- How to troubleshoot simple setup issues.

## Screenshots

Screenshots of my lab setup and configuration are included in this repository.

## Author

Malak Meaity

Networkwalks Cybersecurity Program — Week 1
