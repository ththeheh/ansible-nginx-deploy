# Ansible Automation: NGINX Web Server Deployment

This project automates the installation and configuration of the **NGINX web server** on a local Ubuntu system using **Ansible**. It’s designed as a hands-on learning exercise in infrastructure as code (IaC) and system automation.

> Tested on Ubuntu via WSL2
> Built to reinforce Ansible core concepts like playbooks, tasks, and idempotency

---
## What This Project Does

✅ Installs the latest NGINX web server

✅ Creates a custom `index.html`

✅ Starts and enables the NGINX service on boot

✅ Executes the entire setup with a single command

---
## What This Project Does in Simple Terms

This project shows how I automated the setup of a basic website using a tool called Ansible.

Instead of manually installing software like a web server, creating files, and starting services, I wrote a short set of instructions (called a playbook) that tells the computer exactly what to do.

With one command, this playbook:

Installs a web server (NGINX)

Adds a custom web page (Hello from Ansible!)

Starts the server so it's ready to use

It’s a set of instructions that the computer can follow anytime which saves time, avoids human error, and is repeatable on any machine.

---

## Project Structure

ansible-nginx-deploy/

├── hello-nginx.yml # Main Ansible playbook

├── .gitignore # Git exclusions (Python + Ansible)

└── README.md # Project overview and usage

## Requirements

-Ubuntu

-Ansible (https://docs.ansible.com)

-sudo privileges

---

## How to Run It

Run the playbook:

```bash
ansible-playbook hello-nginx.yml

```

Verify it's working:

```bash
curl http://localhost

```

Expected Output:

```html
<h1>Hello from Ansible!</h1>

```

---

## What You will Learn

-Writing your first Ansible playbook in YAML

-Automating package installation and service management

-Using Ansible's apt, copy, and service modules

-Applying DevOps/Infrastructure-as-Code principles in practice

---

## Author

Mary Yunju Kim

Junior Solution Architect | Cloud and Automation Enthusiast

Linkedin: https://www.linkedin.com/in/mary-yunju-kim-610002123/
