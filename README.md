Ansible Role | Template
=========
[![Build Status](https://travis-ci.org/arnobirchler/ansible-role-portainer.svg?branch=master)](https://travis-ci.org/arnobirchler/ansible-role-portainer)

Role that install portainer with travis-ci configuration

Requirements
------------

Docker

Role Variables
--------------

No variables needed.

Dependencies
------------

Ansible : No dependencies

Travis : 2 Depedencies
  - [Github gist](https://gist.github.com/arnobirchler/627e4655465b696a0b521a560bc2206f)
  - [Docker images](https://hub.docker.com/r/arnobirchler/docker-os-ansible/)

Example Playbook
----------------
```
- name: "FILE | create a file"
  file:
    path: "./test.txt"
    state: touch
```

License
-------

MIT

Author Information
------------------

Arno Birchler
