Ansible Midnight Commander role.
=========
[![Build Status](https://travis-ci.org/spitfast/ansible-mc-role.svg?branch=master)](https://travis-ci.org/spitfast/ansible-mc-role)

Install Midnight Commander and set mcedit as default editor.

Requirements
------------
Ansible version **2.0.1** or higher.

Role Variables
--------------
```yml
---
mc_set_as_default_editor: true
```

Dependencies
------------
None.

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------
MIT

Author Information
------------------

[Gordon Shumway](https://github.com/spitfast/)
