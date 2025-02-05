# Playbook
[servers]
ubu2 ansible_host=192.168.240.13
ubu3 ansible_host=192.168.240.14

[servers2]
ubu2 ansible_host=192.168.240.13

[servers3]
ubu3 ansible_host=192.168.240.14

[all:vars]
ansible_python_interpreter=/usr/bin/python
