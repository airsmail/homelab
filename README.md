# 🏠 Homelab

My personal homelab environment — a space for continuous learning and hands-on experimentation with infrastructure, virtualization, backup, security, hybrid cloud, and automation.

> ⚠️ All configurations, IP addresses, domain names, and credentials shared in this repo are sanitized/example values. No real environment details are exposed.

---

## 📌 Purpose

This repo documents the technologies I use in enterprise environments, applied and tested in my own homelab — including the tools I've learned, the problems I've run into, and how I solved them.

---

## 🖥️ Infrastructure Overview

| Component | Tool Used | Purpose |
|---|---|---|
| Domain Controller | Windows Server AD DS | Identity & access management |
| Certificate Authority | Windows CA | Certificate management, internal PKI |
| Backup | Veeam Backup & Replication | VM backup, disaster recovery |
| Backup (Proxmox) | Proxmox Backup Server (PBS) | Proxmox-based backup |
| Container Platform | Docker | Service/application isolation |
| Security / Firewall | Sophos (virtual FW) | Network security, traffic filtering |
| Network Segmentation | VLAN | Network segmentation, isolation |

### ☁️ Microsoft 365 / Azure

| Component | Tool Used | Purpose |
|---|---|---|
| Identity Management | Entra ID (Azure AD) | Cloud identity & access management |
| Hybrid Identity | Azure AD Connect | On-prem AD to Entra ID synchronization |
| Device Management | Intune | MDM/MAM, device compliance policies |
| Email | Exchange Online | Cloud email management |
| Virtual Machine | Azure VM | Cloud-hosted virtual servers |
| Access Security | MFA / Conditional Access | Conditional access, multi-factor authentication |
| Backup | Azure Backup | Cloud backup |
| Hybrid Management | Azure Arc | Managing on-prem/multi-cloud resources via Azure |
| Storage | Azure Storage | Cloud storage solutions |
| Compliance & Data Governance | Microsoft Purview (Compliance Manager) | ISO 27001 compliance score, gap/control assessment |

### 🔐 Hybrid Connectivity / VPN

| Connection | Tool | Purpose |
|---|---|---|
| Site-to-Site VPN | Sophos FW ↔ Azure | Secure connectivity between homelab and Azure |
| Point-to-Site / Mesh VPN | Tailscale | Connectivity between Azure VM and the on-prem lab DC |

---

## 🗺️ Architecture

General network/topology diagram (VLAN segmentation, service distribution):

```
[Diagram / visual to be added]
```

---

## 🐳 Docker Services

Services I run via Docker Compose:

```
[docker-compose.yml files / service list to be added]
```

---

## 🔒 Security Notes

- Segmentation logic applied on the Sophos virtual FW
- VLAN-based access control principles
- (General approach shared, not actual rule sets)

---

## 🛠️ Issues Encountered & Solutions

This section documents technical issues I've run into during the homelab journey and how I resolved them.

### [Issue Title]
**Problem:** ...
**Solution:** ...

---

## 📚 Learnings / Notes

- ...
- ...

---

## 🔗 Contact

- [LinkedIn]([#](https://www.linkedin.com/in/ismail-bostan-88a85844/))
- [E-mail](#)
