Ansible motd Role
==================

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
     - { role: MichaelRigart.motd, become: true }
```

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>
