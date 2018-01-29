# image-tester-ansible
Ansible script to test Images in Openstack

Environment: Openstack
Requirements: 
Ansible 2.3.1.0
Python version = 2.7.13 
Openstack CLI tool

1. Source your Openstack credentials

Folder Structure:

Playbooks = Contains all Playbooks
    Create_VMs = Contains main.yml and host file, to edit the diffrent OS you want to test, you can also specify the Flavour and name. Run ansible-playbook main.yml to create the VMs.
    Install2IP = Contains Install2IP.yml and host file, 
