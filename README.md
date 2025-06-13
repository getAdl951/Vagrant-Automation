# 🖥️ Automated Website Deployment using Vagrant, CentOS, and Apache

This project demonstrates how to automate the provisioning of a virtual machine and the deployment of a static website using **Vagrant**, **CentOS Stream 9**, and **Apache HTTP Server**.

---

## 📌 Project Overview

Using Vagrant, this setup provisions a CentOS Stream 9 virtual machine on VirtualBox, installs Apache, downloads a pre-designed website template from [Tooplate](https://www.tooplate.com/), and serves it on an HTTP server — all done automatically through shell provisioning.

---

## ⚙️ Features

- ✅ **CentOS Stream 9** base box via Eurolinux
- ✅ **VirtualBox provider** with 1024MB RAM
- ✅ **Apache Web Server (httpd)** installation & setup
- ✅ **Private** and **Public** networking enabled
- ✅ **Shell script provisioning** for full automation
- ✅ Downloads and deploys a modern HTML template automatically

---

## 🛠️ Tech Stack

- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)
- [CentOS Stream 9](https://www.centos.org/centos-stream/)
- [Apache HTTP Server](https://httpd.apache.org/)
- [Tooplate Template](https://www.tooplate.com/view/2135-mini-finance)
- Bash / Shell scripting

---

## 🚀 How It Works

1. Vagrant sets up a CentOS virtual machine.
2. A shell script installs Apache and required tools.
3. It then downloads the website ZIP file and unpacks it.
4. Files are moved to `/var/www/html/` to make the site live.
5. The website is accessible via the VM's IP address.

---

## 🧑‍💻 Usage

### ✅ Prerequisites

- [VirtualBox](https://www.virtualbox.org/) installed
- [Vagrant](https://www.vagrantup.com/) installed

### 📦 Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
