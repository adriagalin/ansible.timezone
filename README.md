adriagalin.timezone
===================

[![Build Status](https://travis-ci.org/adriagalin/ansible.timezone.svg?branch=master)](https://travis-ci.org/adriagalin/ansible.timezone) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-timezone-blue.svg)](https://galaxy.ansible.com/adriagalin/timezone)

An ansible role for set up timezone and localtime.

Requirements
------------

Tested on:

-	Ubuntu 16.04 LTS
-	Ubuntu 18.04 LTS
-	Ubuntu 20.04 LTS

Should work with:

-	All Ubuntu
-	All Debian

Role Variables
--------------

```yaml
ag_timezone: A timezone (e.g Etc/UTC)
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: adriagalin.timezone }
```

License
-------

GPLv3 License.

Author Information
------------------

[Adrià Galín](http://www.adriagalin.com)

Inspiration
-----------

During development, some roles in Ansible Galaxy/Github also inspired me:

-	[knopki](https://github.com/knopki/ansible-timezone)
-	and many others.

thank you.
