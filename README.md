Zabbix SystemD Monitoring Module
=========

Implementation of https://github.com/cavaliercoder/zabbix-module-systemd

_Zabbix module that enables Zabbix to query the systemd D-Bus API for native and granular system state monitoring + relative cgroup (CPU, MEM, IO, ...) metrics._
Requirements
------------

CentOS7
Zabbix Agent - 3.0

Role Variables
--------------

Currently none, however need to modularize versioning 

Dependencies
------------

No external dependencies 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - OULibraries.zabbix-module-systemd

License
-------

BSD

Author Information
------------------

Cody Bennett
