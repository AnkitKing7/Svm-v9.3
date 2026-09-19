# ███████╗██╗   ██╗

# ██╔════╝██║   ██║

# ███████╗██║   ██║

# ╚════██║██║   ██║

# ███████║╚██████╔╝

# ╚══════╝ ╚═════╝

#

# SVM v9.3 — Virtual Machine Management System

[![Version](https://img.shields.io/badge/version-v9.3-blue.svg)](https://github.com/AnkitKing7/Svm-v9.3)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node.js-21.x-green.svg)](https://nodejs.org/)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows-blue.svg)](https://github.com/AnkitKing7/Svm-v9.3)

**SVM v9.3** is a powerful web-based Virtual Machine Management System built with Node.js, Express, and QEMU/KVM.

It provides an intuitive web panel for creating, managing, monitoring, and controlling QEMU/KVM virtual machines with cloud-init support.

---

## 🖥️ SVM v9.3

![SVM Panel](https://i.imgur.com/0DmkSi4.png)

### SV Logo

```text
███████╗██╗   ██╗
██╔════╝██║   ██║
███████╗██║   ██║
╚════██║██║   ██║
███████║╚██████╔╝
╚══════╝ ╚═════╝

        SVM v9.3
```

---

## ✨ Features

### 🖥️ Complete VM Management

* Create virtual machines
* Start, stop, restart, and delete VMs
* Reinstall VMs with different OS templates
* Attach and detach ISO files
* Resize virtual disks
* Manage VM resources

### ☁️ Cloud-Init Support

* Ubuntu
* Debian
* Fedora
* CentOS
* AlmaLinux
* Automatic network configuration
* User creation
* Password management
* Automated VM initialization

### 🌐 Network Configuration

* Static IPv4 addressing
* Bridge networking
* Custom MAC address generation
* VLAN support
* VM network management

### 🖥️ Web Console & SSH

* Web-based VM console
* VNC/console access
* WebSocket SSH terminal
* Real-time log streaming
* VM status monitoring

### 👤 User Management

* Admin and User roles
* User authentication
* User profiles
* Password management
* Discord OAuth2 integration

### 🛠️ Admin Dashboard

* System overview
* VM statistics
* Manage all virtual machines
* User management
* Role assignment
* System configuration

### 🔐 License System

* License key activation
* Machine-based licensing
* Online validation
* Offline validation
* Secure license management

---

## 🚀 Quick Start

### Requirements

Make sure your system has:

* Linux server
* Node.js 21.x
* QEMU/KVM
* `sudo` access
* `unzip`
* Git
* Internet connection

### Installation

Clone the repository:

```bash
git clone https://github.com/AnkitKing7/Svm-v9.3.git
cd Svm-v9.3
```

Install dependencies:

```bash
npm install
```

Start the panel:

```bash
npm start
```

---

## 📦 Automatic Installation

You can also use the included installation script:

```bash
chmod +x install.sh
bash install.sh
```

The installer can configure the required packages and prepare the SVM v9.3 environment.

---

## ⚙️ Configuration

Before starting the panel, configure the required environment variables.

Example:

```env
PORT=3000
NODE_ENV=production
```

Add any additional configuration required by your deployment.

---

## 🔑 License

SVM v9.3 uses a license system for authorized installations.

A valid license may be required depending on your deployment and configuration.

---

## 🛡️ Security

For production deployments:

* Use HTTPS
* Use a strong administrator password
* Keep Node.js and system packages updated
* Restrict unnecessary ports
* Configure firewall rules
* Do not expose QEMU management interfaces publicly
* Keep license keys and secrets private

---

## 📸 Panel

SVM v9.3 provides a centralized web interface for managing your virtual machines.

![SVM v9.3 Panel](https://i.imgur.com/0DmkSi4.png)

---

## 🔗 Repository

**GitHub:**
https://github.com/AnkitKing7/Svm-v9.3

---

## 👨‍💻 Developer

**AnkitKing7**

SVM v9.3 — Virtual Machine Management System

---

## 📄 License

This project is proprietary software.

See the [LICENSE](LICENSE) file for the applicable license terms.

---

# SV • SVM v9.3

**Virtual Machine Management Made Simple.**
