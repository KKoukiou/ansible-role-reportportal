# ReportPortal

This deploy is meant to deploy [reportportal](http://reportportal.io/)
using `docker-compose` on Centos target basic on the [documentation](http://reportportal.io/docs).

Requirements
------------

None.

Role Variables
--------------

None

Dependencies
------------

- shomatan.docker
- shomatan.docker-compose

Example Playbook
----------------

    - hosts: reportportal
      roles:
         - { role: kkoukiou.reportportal }

License
-------

MIT

Author Information
------------------

Katerina Koukiou
