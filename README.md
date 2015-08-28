Ansible Role: Pa11y
=========

Installs pa11y ( http://pa11y.org).

Requirements
------------

Requires nodejs and npm be previously installed.
Suggest geerlingguy.nodejs ( https://galaxy.ansible.com/list#/roles/465)

Role Variables
--------------

none yet

Dependencies
------------

geerlingguy.nodejs (Installs Node).

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: joestewart/pa11y }

License
-------

BSD

Author Information
------------------

This role was created in 2015 by Joe Stewart
