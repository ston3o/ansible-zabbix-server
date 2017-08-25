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
    - zabbix_url: zabbix.example.com
    - server_dbpassword: zabbix-server

  roles:
    - role: zabbix-server
```

License
---

GNU GPL v3.0

**Free Software, Hell Yeah!**

[1]: https://www.zabbix.com/