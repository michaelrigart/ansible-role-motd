Ansible motd Role
==================
[![Build Status](https://travis-ci.org/michaelrigart/ansible-role-motd.svg?branch=master)](https://travis-ci.org/michaelrigart/ansible-role-motd)

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