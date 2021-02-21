Role Name
=========

![CI](https://github.com/baztian/ansible-asdf/workflows/CI/badge.svg)

Role to download, install and setup [asdf](https://github.com/asdf-vm/asdf).

Set `asdf_root_user_approach` to `no` if you do not want to install plugins
and versions to `/opt/asdf...` but to the user's home folder.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.asdf

License
-------

MIT
