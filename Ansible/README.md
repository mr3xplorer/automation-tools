# Ansible
Ansible to automate the configuration of a basic Linux server on AWS.

# Basic Ansible Server Configuration

## Overview

This project walks through using Ansible to automate the configuration of a basic Linux server on AWS. create Ansible playbooks to install packages, configure users, and set up a simple web server. This hands-on project provides experience with configuration management using Ansible.

## Project Structure

- **`ansible_playbooks/`:** Directory containing Ansible playbooks.
  - **`install_packages.yml`:** Ansible playbook to install necessary packages.
  - **`configure_users.yml`:** Ansible playbook to configure users.
  - **`setup_web_server.yml`:** Ansible playbook to set up a simple web server.
- **`README.md`:** Project documentation providing instructions and information.

## Prerequisites

1. **Ansible Installation:** Ensure Ansible is installed on your local machine. You can install it using package managers like `apt`, `yum`, or with Python's `pip`.

2. **AWS Account:** Set up an AWS account if you don't have one. Obtain your AWS access and secret keys.

3. **EC2 Instance:** Launch a basic Linux EC2 instance on AWS that you want to configure using Ansible.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/basic-ansible-server-configuration.git
   cd basic-ansible-server-configuration
   ```

2. **Configure Ansible:**
   - Update the Ansible inventory file (`ansible.cfg` or `/etc/ansible/hosts`) with the IP address or hostname of your target EC2 instance.

3. **Review Playbooks:**
   - Open the playbooks in the `ansible_playbooks/` directory and review the tasks. Adjust configurations as needed.

4. **Run Ansible Playbooks:**
   - Execute Ansible playbooks to configure the server.
     ```bash
     ansible-playbook ansible_playbooks/install_packages.yml
     ansible-playbook ansible_playbooks/configure_users.yml
     ansible-playbook ansible_playbooks/setup_web_server.yml
     ```

## Customization

Feel free to customize the playbooks in the `ansible_playbooks/` directory to suit your specific server configuration requirements. You can add or modify tasks based on your needs.

## Learnings

- Automating server configuration using Ansible.
- Writing Ansible playbooks for package installation, user configuration, and web server setup.
- Understanding basic configuration management concepts.
