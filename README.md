[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-NFS-blue.svg)](https://galaxy.ansible.com/wluisaraujo/nfs) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-nfs.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-nfs)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [NFS](https://)
------------

Description
------------

 * Ansible role for NFS
 
Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.nfs
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - nfs
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
