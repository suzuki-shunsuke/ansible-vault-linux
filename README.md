vault-linux
============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-vault-linux.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-vault-linux)

Install vault on Linux.

https://galaxy.ansible.com/suzuki-shunsuke/vault-linux/

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
