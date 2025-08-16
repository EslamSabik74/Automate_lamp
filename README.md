# Automate LAMP with Ansible

This project automates the installation and configuration of a **LAMP stack** (Linux, Apache, MySQL/MariaDB, PHP) using **Ansible**.  
The goal is to make server setup faster, consistent, and reusable.

---

## Features
- Installs and configures **Apache** web server.
- Installs and secures **MySQL** database.
- Installs **PHP** and required extensions.
- Uses **roles**, **inventories**, and **group_vars** for flexible configuration.
- Easily extendable for future technologies (e.g., PHP 8+, Docker, Kubernetes).

---
## Project Structure
Automate_lamp/
│── ansible.cfg
│── inventory/ # Inventory file with dev/prod environments
│── group_vars/ # Variables for groups
│── playbook.yml # Main playbook to run
│── roles/
│ ├── apache/
│ ├── mysql/
│ ├── php/

