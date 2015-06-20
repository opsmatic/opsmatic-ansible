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

Example /default/main.yml
-------------------------

In the event that you would like to set all of the default variables change the `default/main.yml` file:

```yaml
---                                           
opsmatic_auth_http: "https://api.opsmatic.com"
opsmatic_integration_token: "YOURINTEGRATIONTOKEN"
opsmatic_install_cli: true
opsmatic_host_alias: "myhostalias_name"
opsmatic_groups: ['groupone','grouptwo','groupthree', 'yet-another-group']
opsmatic_file_monitor_list: ['/etc/nginx/nginx.conf','/etc/ssh/sshd_config','/etc/hosts']
```


License
-------

MIT

Author Information
------------------

Contact us at [https://github.com/opsmatic/opsmatic-ansible](https://github.com/opsmatic/opsmatic-ansible)
