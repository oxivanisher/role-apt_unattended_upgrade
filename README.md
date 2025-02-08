apt_unattended_upgrade
======================
[![Ansible Lint](https://github.com/oxivanisher/role-apt_unattended_upgrade/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-apt_unattended_upgrade/actions/workflows/ansible-lint.yml)

Enable Debian and Ubuntu desktop systems for unattended security upgrades.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_base.apt_unattended_upgrade
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
