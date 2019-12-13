Ansible Role:  
=========

Ansible role to install Node LTS Version & Yarn on RHEL/CentOS

Requirements
------------

The following variables can be optionally set with values in a .yml file in either host_vats or group_vars

```
node_module_dirs
node_version
```
Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cyberitas.nodelts }

License
-------

MIT

Author Information
------------------

Created in 2019 by James Dugger for Cyberitas Technologies, LLC
