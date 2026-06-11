# WordPress Deployment Automation using Ansible

## Project Overview

This project automates the deployment of a WordPress website on Amazon Linux 2023 using Ansible.

The deployment includes:

- Nginx Web Server
- PHP 8.x
- MariaDB/MySQL Database
- WordPress CMS
- phpMyAdmin
- SFTP User Configuration
- Let's Encrypt SSL Certificate
- Dynamic DNS using DuckDNS

## Architecture

EC2 Instance

│

├── Nginx

├── PHP-FPM

├── MariaDB

├── WordPress

├── phpMyAdmin

└── SSL (Let's Encrypt)

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

## Features
✔ Automated web stack deployment

✔ Automated database creation

✔ Automated WordPress installation

✔ SFTP access configuration

✔ phpMyAdmin integration

✔ Free SSL certificate configuration

✔ Personal blog deployment


## Repository Structure
.
├── inventory

├── webstack.yml

├── database.yml

├── wordpress.yml

└── nginx/

## Deployment

Run:

```bash
ansible-playbook -i inventory webstack.yml
ansible-playbook -i inventory database.yml
ansible-playbook -i inventory wordpress.yml
