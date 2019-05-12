# GitLab Ansible Playbook

This playbook is used to spin up an example GitLab server. 

## Local Development with Vagrant and Ansible
If you want to do local development work then you must first adjust the gitlab.yml hosts. You must change 
`- hosts: gitlab` to `- hosts: all`. This will allow Vagrant to generate an inventory for you. 