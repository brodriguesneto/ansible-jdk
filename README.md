jdk
===
[![Build Status](https://travis-ci.org/everproven/ansible-jdk.svg?branch=master)](https://travis-ci.org/everproven/ansible-jdk)

An Ansible role that installs [Oracle JDK] 1.8.

Platforms
---------

Role tested on Linux operating systems:

* Ubuntu Server 18.04 LTS
* Ubuntu Server 16.04 LTS

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```YAML
---
- hosts: all
  become: True
  roles:
    - role: everproven.jdk
```

License
-------

[Apache License 2.0]

Author Information
------------------

[Ever Proven]

[Oracle JDK]: https://en.wikipedia.org/wiki/Java_Development_Kit
[Apache License 2.0]: https://github.com/everproven/ansible-jdk/blob/master/LICENSE
[Ever Proven]: https://github.com/everproven
