Role Name
=========

Ansible role for deploying and configuring Hashicorp Vault on a RH based distro

Requirements
------------

N/A

Role Variables
--------------

VAULT_CONFIG - Vault configuration file; only the minimum config, requires TLS certificates and Consul already installed to serve as a storage backend

VAULT_SERVICE - Vault systemd service file

Dependencies
------------

j0rdan0.consul

Example Playbook
----------------

    - hosts: servers
      roles:
         - j0rdan0.consul
         - j0rdan0.vault

License
-------

BSD

Author Information
------------------

https://github.com/j0rdan0

https://acidburn.me

@j0rdan0 (Twitter)
