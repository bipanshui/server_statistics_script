# 📊 Server Stats Script (`server-stats.sh`)

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/server-stats)
![GitHub stars](https://img.shields.io/github/stars/your-username/server-stats?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/server-stats?style=social)
![License](https://img.shields.io/badge/license-MIT-green)
![Bash](https://img.shields.io/badge/made%20with-bash-1f425f.svg)
![Platform](https://img.shields.io/badge/platform-linux-blue)
![CI](https://github.com/your-username/server-stats/actions/workflows/main.yml/badge.svg)

---

## 🚀 Overview

A lightweight **Bash script** to analyze basic server performance metrics on any Linux system.

Perfect for:
- 🧑‍💻 DevOps Engineers  
- 🖥️ System Administrators  
- 📚 Students learning Linux  

Get a quick snapshot of your system health directly from the terminal ⚡

---

## ✨ Features

- 🖥️ **CPU Usage**
  - Total CPU usage percentage

- 🧠 **Memory Usage**
  - Total, Used, Free memory
  - Usage percentage

- 💾 **Disk Usage**
  - Total, Used, Free space
  - Usage percentage

- 🔥 **Top Processes**
  - Top 5 by CPU usage
  - Top 5 by Memory usage

---

## 🌟 Extended Features (Optional)

- 🏷️ OS version  
- ⏱️ System uptime  
- 📈 Load average  
- 👥 Logged-in users  
- 🔐 Failed login attempts  

---

## 📦 Requirements

- Linux OS (Ubuntu, Fedora, RHEL, etc.)
- Bash

### Required Commands:
- `top`
- `ps`
- `free`
- `df`
- `uptime`
- `who`

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/server-stats.git
cd server-stats
chmod +x server-stats.sh
