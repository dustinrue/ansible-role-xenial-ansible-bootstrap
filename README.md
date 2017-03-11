Ansible bootstrap for Ubuntu 16.04 (Xenial)

To use against Xenial, playbook should contain the following at the top

---
- hosts: all
  gather_facts: false

  roles:
    - xenial-ansible-bootstrap
