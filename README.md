# ansible-dns-config"

# Ansible Role: DNS Configuration

## 📘 Overview

This Ansible role configures DNS settings on Linux servers. It ensures that all managed nodes use a specified DNS server, configures resolv.conf, and optionally enforces hostname resolution rules for a consistent environment.

## 📁 Role Path

.
├── inventory.ini
├── README.md
├── roles
│   └── dns
│       ├── client.dns.yml
│       ├── handlers
│       │   └── main.yaml
│       ├── tasks
│       │   └── main.yaml
│       ├── templates
│       │   ├── db.forward.j2
│       │   ├── db.reverse.j2
│       │   └── named.conf.j2
│       └── vars
│           └── main.yaml
└── site.yaml






🔐 Permissions
Make sure the ansible user has:

Passwordless SSH access

Passwordless sudo privileges

📦 Requirements
Ansible 2.9+ (or higher)

Supported OS: CentOS, RHEL, Ubuntu

📄 License
MIT License
