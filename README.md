Role Name
=========

Make the user sudoer without password.

Requirements
------------

None

Role Variables
--------------

user: - username to make sudoer

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      become: yes
      vars:
        user: slava
      roles:
         - vyacheslavisaev

License
-------

BSD

Author Information
------------------

Viacheslav Isaev.
