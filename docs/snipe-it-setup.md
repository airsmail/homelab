# **Snipe-IT Enterprise Docker Installation Guide**

This document contains tested steps for deploying a secure and isolated Snipe-IT infrastructure in enterprise environments (on a Proxmox virtual machine).

## **1. Server Preparation (Ubuntu / Debian)**
* Create a virtual machine (VM) with 2 vCPU, 4GB RAM, and 30-40GB of Disk space.
* Complete the installation of OpenSSH and QEMU Guest Agent (for Proxmox).

## **2. Docker and Docker Compose Installation**
```bash
sudo apt update
sudo apt install docker.io docker-compose-v2 -y
sudo systemctl enable --now docker
