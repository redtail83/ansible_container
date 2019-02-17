Ansible Role: Ansible Container
=========

Install Ansible Container for CentOS.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

This role depends on:

* redtail83.docker
* redtail83.ansible
* redtail83.python36

Example Playbook
----------------

CentOS 7:

    - hosts: servers
      roles:
         - { role: redtail83.ansible_container }

License
-------

MIT
