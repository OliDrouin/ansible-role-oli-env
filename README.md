ansible-role-oli-env
=========

Olivier's opensuse dev environment

Requirements
------------

git submodule add git@github.com:OliDrouin/ansible-role-oli-env.git roles/oli_env

Role Variables
--------------
```
vault_ssh_priv_key_ed

vault_ssh_pub_key_ed


vault_ssh_priv_key_rsa

vault_ssh_priv_key_rsa
```
Dependencies
------------


Example Playbook
----------------

---
- hosts: all
  remote_user: auser

  roles:
    - ansible-role-oli-env


License
-------

BSD

Author Information
------------------

Olivier Drouin
