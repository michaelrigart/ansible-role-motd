Ansible motd Role
==================

An ansible role for configuring motd.

Role Variables
--------------

motd_additional_files: holds a list of additional motd files that need to be transferred to the remote host
motd_remove_files: holds a list of motd files that need to be removed from the remote host


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: MichaelRigart.motd }

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>