Deploy and Configure Apache Web Server (Ansible)

Overview

This Ansible playbook automates the installation and configuration of the Apache web server on Linux systems.
It installs Apache, deploys a custom configuration template, and ensures the service is enabled and started

Supported Platforms
  
   🟢 CentOS / RHEL (uses httpd)
   
  How It Works
   
Installs Apache using the yum module.
  
Deploys a Jinja2 template to /etc/httpd/conf.d/default.conf.

Restarts Apache automatically when configuration changes.

Ensures Apache is enabled and started at boot.
