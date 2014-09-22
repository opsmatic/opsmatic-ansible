Opsmatic
========

The Opsmatic role allows the installation of the Opsmatic Agent on hosts you're managing with Ansible

Requirements
------------

This role has no requirements

Role Variables
--------------

The variable `opsmatic_integration_token` must contain your Opsmatic integration token, you can obtain this through the Opsmatic UI.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - opsmatic

License
-------

MIT

Author Information
------------------

Contact us at [https://github.com/opsmatic/opsmatic-ansible](https://github.com/opsmatic/opsmatic-ansible)
