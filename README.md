andrewrothstein.node-config
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-node-config.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-node-config)

Sets some node configurations and installs npm.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.node-config
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
