# Basic system configuration

This role does basic system configuration like /etc/motd

## Example playbook

```
---
- hosts: example-host
  become: true
  roles:
    - nbuchwitz.basic
```
