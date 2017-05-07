[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-node-config.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-node-config)
andrewrothstein.node-config
=========

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
