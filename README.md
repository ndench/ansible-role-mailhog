Mailhog
=========

[![Build Status](https://travis-ci.org/ndench/ansible-role-mailhog.svg?branch=master)](https://travis-ci.org/ndench/ansible-role-mailhog)

Ansible role to install [Mailhog](https://github.com/mailhog/MailHog) as a Systemd service.

Requirements
------------

* Systemd

Role Variables
--------------

All variables are listed below, along with their default values in [defaults/main.yml](defaults/main.yml):

```yaml
ndench_mailhog:
    version: 1.0.0 # The version of mailhog to install
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: dev
      roles:
         - { role: ndench.mailhog }

License
-------

MIT

Author Information
------------------

This role was created in 2017 by [Nathan Dench](https://www.linkedin.com/in/nathandench/).
