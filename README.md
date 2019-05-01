Zabbix SystemD Monitoring Module
=========

Returns state of all enabled SystemD services

Services can be narrowed down using the {#SERVICE.NAME} filter in Zabbix 
>> See Filters in https://www.zabbix.com/documentation/3.0/manual/discovery/low_level_discovery#discovery_of_file_systems

Implementation of https://github.com/cavaliercoder/zabbix-module-systemd

_Zabbix module that enables Zabbix to query the systemd D-Bus API for native and granular system state monitoring + relative cgroup (CPU, MEM, IO, ...) metrics._

Requirements
------------

> * CentOS 7
> * Zabbix Agent - 3.0

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
