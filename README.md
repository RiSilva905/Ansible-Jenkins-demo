# Ansible-Jenkins-demo
A short demo of Ansible configuring an EC2 instance with Jenkins, installing the neccessary software for it to work and configuring it as a service.

The Key.pem should be inside the directory that will be running as for the command to use it will be:
ansible-playbook -i hosts main.yml --private-key key.pem