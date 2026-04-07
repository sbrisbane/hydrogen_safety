Role Name
=========

This role installs and configures DSU and the OpenManage Utilities.
Source of packages is out of scope but expected to come from Dell repositories.

https://linux.dell.com/repo/hardware/dsu/os_dependent/RHEL7_64/
https://linux.dell.com/repo/hardware/dsu/os_independent/

Requirements
------------

Package management is expected to be handled by an external application, such as Red Hat Satellite. Registering to package management service is outside the scope of this role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
    - hosts: servers
      roles:
         - { role: dell }
```

Author Information
------------------

Initial Version: Eoghan Cotter - eoghan.cotter@securelinx.com
