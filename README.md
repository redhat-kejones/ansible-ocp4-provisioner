ocp4-provisioner
=========

This Ansible role will configure a linux system to be ready to provision
OpenShift 4.

Requirements
------------

- Expects a base RHEL variant installation
- Reachable on at least 1 IP
- SSH enabled

Role Variables
--------------

- tbd

Dependencies
------------

- none

Example Playbook
----------------

```yaml
- hosts: ocp4-provisioner
  tasks:
  - name: Deploy ocp4-provisioner
    roles:
      - ocp4-provisioner
```

License
-------

GPLv3

Author Information
------------------

[Red Hat North American Public Sector Solution Architects](https://redhatgov.io)
