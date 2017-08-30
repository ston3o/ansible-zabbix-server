Ansible-zabbix-server [![Ansible Galaxy](https://img.shields.io/badge/galaxy-zabbix-660198.svg)][1]
===

> Install zabbix-server on debian stretch.

Requirements
---

- Ansible >= 2.2.1

Example Playbook
---

```
- hosts: localhost
  vars:
    - zabbix_version: 3.4
    - zabbix_url: zabbix.example.com
    - server_dbname: zabbix
    - server_dbuser: zabbix
    - server_dbpassword: zabbix

  roles:
    - role: zabbix-server
```

License
---

GNU GPL v3.0

**Free Software, Hell Yeah!**

[1]: https://galaxy.ansible.com/ston3o/zabbix-server/
