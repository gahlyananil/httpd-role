cat /etc/ansible/apache.yml
---
- hosts: all
  become: true
  roles:
    - apache


================================================

# ansible-playbook /etc/ansible/apache.yml


