# image-tester-ansible
Ansible script to test Images in Openstack

Environment: Openstack
Requirements: 
Ansible 2.3.1.0
Python version = 2.7.13 
Openstack CLI tool

1. Source your Openstack credentials

Folder Structure:

Playbooks = contains create_and_test folder.
create_and_test = contains main.yml and servers.yml

Servers created
servers tested

to change OS to be tested or flavors edit servers.yml

to run Testing, run: ansible-playbook main.yml
