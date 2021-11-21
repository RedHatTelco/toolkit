# network.toolkit.lldp

To use this multi-platform network automation lldp role:

## Task example:

```
- name: use lldp role
  include_role:
    name: lldp
```

## Full Ansible Playbook example:

```
---
- name: configure lldp on routers
  hosts: routers
  gather_facts: no

  tasks:

    - name: use lldp role
      include_role:
        name: lldp
```
