Ansible motd Role
==================
[![Build Status](https://semaphoreci.com/api/v1/projects/a1942bbc-a453-4574-b692-d028f246b819/459471/badge.svg)](https://semaphoreci.com/michaelrigart/ansible-role-motd)

An ansible role for configuring motd.

Role Variables
--------------

```yaml
motd_additional_files: holds a list of additional motd files that need to be transferred to the remote host
motd_remove_files: holds a list of motd files that need to be removed from the remote host
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: MichaelRigart.motd, sudo: Yes }
```

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>
