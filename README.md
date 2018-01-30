# image-tester-ansible
Ansible script to test Images in Openstack

Environment: Openstack
Requirements: 
Ansible 2.3.1.0
Python version = 2.7.13 
Openstack CLI tool

1. Source your Openstack credentials
2. Enter your keyname in "key_name:" (line 15, main.yml)
3. Enter your SSH Security group Name "security_groups:" (line 13, main.yml)



Folder Structure:
Playbooks = contains create_and_test folder.
create_and_test = contains main.yml and servers.yml
to change OS to be tested or flavors edit servers.yml

Testing: Run ansible-playbook main.yml
