Ansible Midnight Commander role.
=========
[![Build Status](https://travis-ci.org/spitfast/ansible-mc-role.svg?branch=master)](https://travis-ci.org/spitfast/ansible-mc-role)

Install Midnight Commander and set mcedit as default editor for specified users.

Requirements
------------
Ansible version **2.0.1** or higher.

Role Variables
--------------
```yml
---
mc_set_as_default_editor: true
mc_users_home_path:
  - "/root"
```

Dependencies
------------
None.

Example Playbook
----------------
```yaml
---
- hosts: localhost
  roles:
   - spitfast.mc
```

License
-------
MIT

Author Information
------------------

[Gordon Shumway](https://github.com/spitfast/)
