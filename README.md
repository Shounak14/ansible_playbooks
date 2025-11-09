# Ansible Playbooks

This repo contains all the Ansible playbooks I made while learning Linux and Ansible basics.  
Each playbook covers a small use case to understand how automation works using Ansible.



# Playbooks

1. first_playbook.yml
- My first playbook.
- A simple introductory playbook that pings all nodes, creates a directory, and writes a message file on each managed server.



2. task1_files.yml
- Demonstrates file management tasks such as creating directories, copying files, viewing output, and deleting resources.
- Helps understand how Ansible handles file operations on remote managed nodes.



3. task2_packages.yml
- Used to manage software packages using apt.
- Installs the tree package, verifies it, and then removes it to demonstrate package lifecycle management in Ansible.



4. task3_users.yml
- Used to create and manage user accounts and groups on target servers.
- Ensures the user’s home directory is properly created and assigned correct permissions.



5. task3_level2.yml
- Used to manage users, groups, and sudo privileges in a structured way.
- Demonstrates creating users, assigning groups, setting passwords, and configuring sudo access using loops and variables.



6. task_level3.yml
-Installs and manages the Apache web server, ensuring the service is running.
-Demonstrates deploying a custom web page and using handlers to restart services when changes occur.



# How to Run

To run any playbook:
ansible-playbook -i /etc/ansible/hosts <playbook_name>.yml
