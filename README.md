Role Name
=========

A role to install and configure backupninja

Requirements
------------

None, configuration is present to backup MySQL and MongoDB databases, with easy ways to add to these.

Role Variables
--------------

This role is very configurable, please feel free to overrule any of the defaults in your own variables.

At the very least, the following variables need to be replaced or checked:
  - backupninja_encryption_password
  - backupninja_reportemail
  - backupninja_reportdir
  - backupninja_default_jobs


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sigio.backupninja }

License
-------

MIT

Author Information
------------------

Mark Janssen -- Sig-I/O Automatisering
https://sig-io.nl
