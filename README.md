# WordPress Deployment on AWS using Ansible

## Overview

This project demonstrates automated deployment of a WordPress website on AWS EC2 using Ansible.

Features:
- Amazon Linux 2023
- Nginx
- PHP 8+
- MariaDB/MySQL
- WordPress
- phpMyAdmin
- SFTP User Access
- DuckDNS Domain
- Let's Encrypt SSL Certificate
- Ansible Automation

## Architecture

EC2 Instance
    |
Nginx
    |
PHP-FPM
    |
WordPress
    |
MariaDB

## Technologies Used

- AWS EC2
- Amazon Linux 2023
- Ansible
- Nginx
- PHP 8
- MariaDB
- WordPress
- phpMyAdmin
- Certbot
- DuckDNS

## Deployment

Run:

```bash
ansible-playbook -i inventory webstack.yml
ansible-playbook -i inventory database.yml
ansible-playbook -i inventory wordpress.yml
