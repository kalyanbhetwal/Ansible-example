# Ansible-example

examples:
1. ansible -i ./inventory/hosts ubuntu -m ping --user root --ask-pass
2. ansible ansible-playbook ./playbooks/apt.yml --user root --ask-pass --ask-become-pass -i ./inventory/hosts