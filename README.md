# time_synchronization
ansible role for chrony deployment

## requirements

## variables

## dependencies

## examples
```
---

- name: deploy chrony
  ansible.builtin.include_role:
    name: time_synchronization
    tasks_from: chrony_deploy.yml

...
```
