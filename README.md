# data_ansible

This is my ansibl repo to process DB setup and Script execute.

Server where ansible will be connect I copy premade ssh key

$ ssh-copy-id -i ~/.ssh/ansible.pub XX.XX.XX.XX

To check ansible host server connect:

ansible all --key-file ~/.ssh/ansible -i inventory -m ping

Add local ansible.cfg file can use

ansible all -m ping
