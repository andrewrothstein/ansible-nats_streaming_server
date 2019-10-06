andrewrothstein.nats_streaming_server
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nats_streaming_server.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nats_streaming_server)

Installs [nats-streamin-server](https://github.com/nats-io/nats-streaming-server)

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
    - andrewrothstein.nats_streaming_server
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
