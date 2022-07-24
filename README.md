# Ansible Role: opensc: install_ansible

An ansible role to install ansible.

## Requirements

### Supported platforms

* GNU/Linux
* FreeBSD

## Role Variables

None

## Dependencies

None

## Example Playbook

```
---
- name: setup ansible server
  hosts: ansible
  become: true
  roles:
    - stafwag.install_ansible
```

## License

MIT/BSD

## Author Information

Created by Staf Wagemakers, email: staf@wagemakers.be, website: http://www.wagemakers.be.

