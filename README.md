Ansible role zabbixagent
=========

Simple role for zabbix agent

Requirements
------------

- Centos
- Ubuntu

Role Variables
--------------

```yaml
zabbixagent_version: 7.0
zabbixagent_server:
zabbixagent_serveractive:
zabbixagent_listenip: "{{ ansible_default_ipv4.address }}"
zabbixagent_sourceip: "{{ ansible_default_ipv4.address }}"
zabbixagent_hostname:  "{{ inventory_hostname }}"
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
