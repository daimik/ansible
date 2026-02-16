# 🏠 Home Lab Ansible Playbooks

Welcome! 👋 This repo is the central hub for all the Ansible automation that keeps my home lab infrastructure healthy, updated, and running smoothly.

## 🤔 What is this?

A collection of Ansible playbooks designed to automate the boring (but important!) stuff — system updates, maintenance tasks, health checks, and more across my entire home lab environment.

## 🖥️ Infrastructure

This repo manages a mix of:

- 🟢 **Proxmox VE** hypervisor nodes
- 📦 **LXC containers**
- 💻 **Virtual machines**
- 🐧 All running **Debian** or **Ubuntu**

## ⚙️ How it works

All playbooks are executed automatically via **Semaphore UI** on a schedule — no manual intervention needed. Just set it and forget it! 🚀

The playbooks are smart enough to detect what type of system they're running on and adjust their behavior accordingly. For example, Proxmox hosts get extra health checks that regular Debian/Ubuntu machines don't need.

## 📂 Repo structure

```
📁 playbooks/          → All Ansible playbooks live here
📄 README.md           → You are here! 👀
```

## 🎯 Goals

- 🔄 Keep everything up to date automatically
- 🛡️ Maintain system health and stability
- 🧹 Clean up unused packages and clutter
- 🔁 Handle reboots gracefully when needed
- 📊 Verify services are running after updates

## 🚧 Work in progress

This repo is always evolving as new services and automation ideas come up. More playbooks coming soon! ✨

---

*Built with ❤️ and way too many hours tinkering in the home lab*
