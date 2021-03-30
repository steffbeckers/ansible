# Ansible

## Commands

```
ansible -i ./inventory/hosts ubuntu -m ping --user steff
```

```
ansible-playbook ./playbooks/apt.yml -i ./inventory/hosts --user steff --ask-become-pass
```
