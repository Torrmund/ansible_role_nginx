Simple Nginx install for Debian/Ubuntu
======================================

Простая роль для установки NGINX на Debian/Ubuntu из официального репозитория

Requirements
------------

* Ansible >=2.9

Role Variables
--------------

Дополнительные переменные не требуются

Dependencies
------------

None

Example Playbook
----------------

    - hosts: nginx
      roles:
         - rolename

License
-------

MIT
