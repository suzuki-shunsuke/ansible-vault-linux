vault-linux
============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-vault-linux.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-vault-linux)

Install vault on Linux.

https://galaxy.ansible.com/suzuki-shunsuke/vault-linux/

This role is deprecated
------------------------

Please use [suzuki-shunsuke.hashicorp-binary](https://galaxy.ansible.com/suzuki-shunsuke/hashicorp-binary/).

Requirements
------------

* unzip

Role Variables
--------------

* vault_version: The Vault version. The default value is 0.6.2.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.vault-linux
```

License
-------

MIT
