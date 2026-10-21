# Linux Server Administration and Hardening

## **Overview**
This project documents the setup of a small **Linux server** from installation to handover. It covers users and **sudo**, **SSH** key-only login, a **firewall**, a service managed with **systemd**, logs, **backups** with a tested restore, and a runbook.

## **Server Setup**
- **Server:** Ubuntu Server or Debian VM
- **Client:** workstation used for SSH
- **Hypervisor:** VirtualBox, VMware or Hyper-V
- **Service:** one service such as nginx, Samba or a DNS server

## **Project Objectives**
- Create admin and standard users with **sudo**
- Configure **SSH** key-only login and disable root login
- Configure a default-deny **firewall**
- Install and manage a service with **systemd**
- Read logs and check disk, memory and listening ports
- Automate **backups** and test a restore
- Write a handover runbook

---

## **1. Installation and Users**
1. **Install the operating system**
2. **Create an admin user with sudo**
3. **Create a standard user**
4. **Set up the network and hostname**

## Installation and Users - Visual Guide

<!-- screenshots -->


## **2. SSH Hardening**
1. **Generate an SSH key pair**
2. **Copy the public key to the server**
3. **Disable password login**
4. **Disable root login**

## SSH Hardening - Visual Guide

<!-- screenshots -->


## **3. Firewall**
1. **Set the default policy to deny**
2. **Allow SSH and the service ports**
3. **Check the rules**

## Firewall - Visual Guide

<!-- screenshots -->


## **4. Services with systemd**
1. **Install the service**
2. **Enable and start it with systemctl**
3. **Check its status and logs**

## Services with systemd - Visual Guide

<!-- screenshots -->


## **5. Logs and Monitoring**
1. **Read the logs with journalctl**
2. **Set up log rotation**
3. **Check disk, memory and listening ports with df, free and ss**

## Logs and Monitoring - Visual Guide

<!-- screenshots -->


## **6. Backups and Restore**
1. **Write the backup script**
2. **Schedule it with cron or a systemd timer**
3. **Restore from a backup and confirm the data**

## Backups and Restore - Visual Guide

<!-- screenshots -->


## **7. Handover Runbook**
1. **Document the accounts, services and ports**
2. **Document the backup and restore steps**
3. **List the common problems and fixes**

## Handover Runbook - Visual Guide

<!-- screenshots -->


## **Project Outcomes & Key Results**
- **Secure Access** – Key-only SSH with root login disabled
- **Default-Deny Firewall** – Only the required ports open
- **Tested Backups** – A backup restored successfully
- **Handover Runbook** – A page anyone could use to look after the server

## **Potential Next Steps**
- **Add automatic security updates**
- **Add monitoring with SNMP or an agent**
- **Build the same server with Ansible**

---

This project is part of my **Networking and Infrastructure portfolio**. For any inquiries, reach out via **[LinkedIn](https://www.linkedin.com/in/kimutai-fredrick/)**.

**_Built and documented by Fredrick Kimutai._**
