Role Name
=========

This role preforms a minimal configuration of NRPE on a system. Installing the NRPE agent is out of scope.


Requirements
------------

Dell OpenManage Utilities are requires (dell ansible role) for the customer omreport checks.

Role Variables
--------------

A number of default variables are configured:
- nrpe_cfg: /etc/nagios/nrpe.cfg
- nrpe_cfg_dir: /etc/nrpe.d
- nrpe_plugin_dir: /usr/lib64/nagios/plugins/

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: nrpe }
```
Author Information
------------------

Initial Version: Eoghan Cotter - eoghan.cotter@securelinx.com
