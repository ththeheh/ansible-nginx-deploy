# ⚙️nsible Automation: NGINX Web Server Deployment

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
