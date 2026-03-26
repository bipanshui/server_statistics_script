# 📊 Server Stats Script (`server-stats.sh`)

A lightweight Bash script to analyze basic server performance metrics on any Linux system.

This script is useful for **system administrators, DevOps engineers, and learners** who want a quick overview of system health directly from the terminal.

---

## 🚀 Features

### 🖥️ CPU Usage
- Displays total CPU usage percentage

### 🧠 Memory Usage
- Shows:
  - Total memory
  - Used memory
  - Free memory
  - Usage percentage

### 💾 Disk Usage
- Displays:
  - Total disk space
  - Used space
  - Free space
  - Usage percentage

### 🔥 Top Processes
- Top 5 processes by **CPU usage**
- Top 5 processes by **Memory usage**

---

## 🌟 Stretch Features (Optional)

- OS version
- System uptime
- Load average
- Logged-in users
- Failed login attempts

---

## 📦 Requirements

- Linux OS (Ubuntu, Fedora, RHEL, etc.)
- Bash
- Commands:
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
