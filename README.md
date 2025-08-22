# 🖥️ Personal Infrastructure

This repository contains the configuration, services, and automation I use to manage my personal infrastructure.  
Everything is primarily managed through **Dockploy** with Docker/Docker Compose as the foundation.  

The goal is to keep all sysadmin-related work **versioned, documented, and reproducible** — so I can rebuild or expand my environment quickly.

---

## 📦 Service Stack

### Productivity & Media
- **📚 Calibre** → Web-based book management
- **🎲 FoundryVTT** → Virtual tabletop for D&D campaigns

### Monitoring & Infra
- **🖥️ Beszel** → Hardware/infrastructure monitoring
- **📡 Uptime Kuma** → Uptime and status monitoring

### Projects & Experiments
- **🐦 UmberWood** → Discord bot + databases
- **🏦 OwlBank** → Mock banking service for the *Go Skate* game

---

## 📂 Repository Structure
```
├─ services/ # Service definitions (Dockerfiles, configs, templates)
├─ deployments/ # Dockploy YAMLs for live environments
├─ scripts/ # Backup, restore, and utility scripts
├─ traefik/ # Reverse proxy configs
├─ docs/ # Documentation and runbooks
└─ README.md # You're here
```

---

## 🚀 Usage

### Clone Repo
```bash
git clone https://github.com/Zephira58/sysadmin.git
cd sysadmin
```

