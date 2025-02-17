# Playbook
---
- name: Basic System Setup
  hosts: web
  become: true
  remote_user: cours
  tasks:
    - name: install apache2
      apt:
        name: apache2
        state: present

=====



